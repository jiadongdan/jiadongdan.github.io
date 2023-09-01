---
title: "Matplotlib Arrows Guid"

tags: [ "matplotlib", "arrows", "plot"]


date: 2022-01-11T16:12:29-07:00
draft: false
---

Arrows are often used to annotate plots. This tutorial shows different ways to add arrow patches to plots: (1) using `plt.arrow()` or `ax.arrow()`; (2) using `FancyArrow`; (3) using `plt.annotate()` or `ax.annotate()`; (4) using `FancyArrawPatch`. Methods (3) and (4) are useful if you are annotating a plot, and don't want the arrow to change shape or position if you **pan** or **scale** the plot. In practice, methods (1) and (2) are not recommended since the produced arrows can be distorted the aspect ratio of the plot changes.



{{< table_of_contents >}}

# Using `plt.arrow()` or `ax.arrow()`

```python
import matplotlib.pyplot as plt

# create fig and ax
fig, ax = plt.subplots(1, 1, figsize=(7.2, 3.6))
# plot arrows
ax.arrow(x=0, y=0, dx=0.5, dy=0.5, width=0.01)
# ax.arrow() returns a FancyArrow object.
```

The resulting arrow is affected by the Axes aspect ratio and data limits. This may produce an arrow whose head is not square with its stem. To create an arrow whose head is square with its stem, use `annotate()`.

# Using `FancyArraw`

According to [Matplotlib's Arrow Guid](https://matplotlib.org/stable/gallery/shapes_and_collections/arrow_guide.html), `FancyArrow`'s API is relatively awkward, and requires in particular passing `length_includes_head=True` so that the arrow tip is `(dx, dy)` away from the arrow start. `FancyArrow` is only included here because it is the arrow class returned by `Axes.arrow`. **Using `FancyArrow` is equivalent to directly calling ax.arrow() or plt.arrow()**, so here no demo code is displayed.

# Using `plt.annotate()` or `ax.annotate()`

```python
import matplotlib.pyplot as plt

# create fig and ax
fig, ax = plt.subplots(1, 1, figsize=(7.2, 3.6))
ax.set_xlim(0, 1)
ax.set_ylim(0, 1)
ax.annotate(text='', xy=(0, 0), xytext=(0.5, 0.5), xycoords='data', arrowprops=dict(facecolor='black', shrink=0.05))
```

When using `annotate()` to draw arrows only, **we need to set `text` to empty string, and `arrowprops` must be specified**. Inside the function call of `annotate()`, an arrow is created by `FancyArrowPatch`. A `FancyArrowPatch` arrow won't change shape or position if you pan or scale the plot, which is the key difference from `FancyArrow`.

Annotations can do more than just drawing arrows. Annotations are graphical elements, often pieces of text, that explain, add context to, or otherwise highlight some portion of the visualized data. For details, see [Matplotlib Annotation Guide](https://matplotlib.org/stable/tutorials/text/annotations.html).

Both `plt.annotate()` and `ax.annotate()` return a `Text` object. It is hard to update the arrow position afterwards.


# Using `FancyArrawPatch` (recommended)

```python
from matplotlib.patches import FancyArrowPatch

fig, ax = plt.subplots(1, 1, figsize=(7.2, 3.6))
arrow = FancyArrowPatch(posA=(0.2,0.2), posB=(0.5, 0.5), mutation_scale=100)
ax.add_patch(arrow)
```

# More tips about `FancyArrowPatch`

* set `ec='none'`, otherwise the edge of the arrow will be smoothed and blurred when arrow is very small.
* set `'transform=ax.transAxes'`, the arrow will use `Axes`'s fractional coordinates.
* `mutation_scale` controls the size of the arrow.


# Summary


# Related links

* [Arrow Guid](https://matplotlib.org/stable/gallery/shapes_and_collections/arrow_guide.html)