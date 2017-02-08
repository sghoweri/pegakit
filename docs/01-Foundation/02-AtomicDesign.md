# Atomic Design

The web moves fast. Where once we could get away with designing pages as discrete objects, modern web design requires a design system that builds from the ground up, allowing us to iterate quickly while maintaining a consistent look and feel across properties. By creating a rich, versatile library of reusable components, we can add new layouts quickly, without building up new [technical or design debt](http://en.wikipedia.org/wiki/Technical_debt). While a new campaign or feature might require the creation of a new component,  new patterns come at a high cost—they require new design elements, additional code, maintenance, and they increase the [cognitive load](http://en.wikipedia.org/wiki/Cognitive_load) on users.

The public part of this guide focuses on the atoms - the basic building blocks of our digital presence. For an ongoing reference to the rest of our design patterns, visit our [full pattern library](https://patterns.pega.com).

## Atomic what, now?

Atomic design flips the traditional model of web layout on its head. Rather than designing discrete *page templates* and breaking them down into CSS components, atomic design starts from the base-level components and works up to finished designs:

### Atoms

The most basic elements of a web system - colors, fonts, grid, etc. These atoms form the basis of this guide.

```
{{ color swatch: Pega Blue }} {{ color swatch: Pega Dark Gray }}
```

```
{{ icon: search block }} {{ icon: case study }}
```

### Molecules

Combinations of two or more atoms that always appear together, e.g. a "share" element or a search box.

```
{{ Share element }}
```

```
{{ Search form }}
```

### Organisms

Combinations of molecules that make up a discrete section of a page, e.g. global navigation, or a hero banner.

```
{{ hero banner }}
```

### Templates

Multiple atoms, molecules and organisms that work together to form a discrete page template, e.g. an article or set of search results.

### Pages

The application of real-world content into templates.