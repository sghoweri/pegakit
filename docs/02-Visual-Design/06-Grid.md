# Grid

Our grid system is based off of Harry Robert's framework-less [CSS grid system.](undefined) The grid separates the layout from content and is baked into the components. All Pega sites use a responsive, Sass-based grid inspired by [CSS Wizardry Grid](https://github.com/csswizardry/csswizardry-grids).The grid is flexible enough to create a variety of layouts, from a single-column layout to complex layouts created by breaking the page into up to six columns, and combining columns from there.

Unlike Bootstrap, this grid is built as you go. There are no pre-defined columns or rows. To start, in a .twig file use the code below to define the grid:

```
{% grid %}
 {% cell %}

 {% endcell %}
{% endgrid %}
```

Rows and columns can now be thought of as cells which are defined by fractions For example, to create a two column layout add:

```
{% grid %}

  {% cell "u-1/2" %}
  {% endcell %}

  {% cell "u-1/2" %}
  {% endcell %}

{% endgrid %}
```

This creates two equal columns:

A traditional two-column layout with a left sidebar and wide content area can be created by breaking the layout into 5 columns, and creating one cell of 2/5 and another of 3/5:

```
{% grid %}
   {% cell "u-2/5" %}
   {% endcell %}

   {% cell "u-3/5" %}
   {% endcell %}
 {% endgrid %}
```

Our grid system employs a mobile first approach. Thus, breakpoints start at small screens and expand to larger screen widths. This means that a single-column grid will remain single-column whether it’s on a user’s mobile device or on their laptop. To display cells at full width only at the small breakpoint (typical for responsive sites), you can use @[breakpoint] to customize the grid:

```
{% grid %}

  {% cell "u-1/1 u-1/2@small" %}
  {% endcell %}

  {% cell "u-1/1 u-1/2@small" %}
  {% endcell %}

{% endgrid %}
```

This creates a two-column grid that collapses to a single stacked column on smaller breakpoints.