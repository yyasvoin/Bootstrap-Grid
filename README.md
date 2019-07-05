# Bootstrap Grid

In class exercise to get familiar with Bootstrap's responsive grid. Use the [official Bootstrap documentation](https://getbootstrap.com/docs/4.2/layout/grid/) as a reference while working through this lab. Take some time now to read through its introduction and _How it works_ section.

Learning how to use Bootstrap's responsive grid will greatly ease the development of responsive layouts, allowing you to develop UIs that look great on devices ranging from mobile phones to desktop computers.


***
- [Instructions](#instructions)
	- [Equal-width Columns](#equal-width-columns)
	- [Set Columns Width](#set-columns-width)
	- [Breakpoint Specific](#breakpoint-specific)
	- [Alignment](#alignment)
	- [Nesting](#nesting)
- [Resources](#resources)
***




## Instructions

No CSS or custom styles even through HTML's `style` attribute are to be written to finish this exercise.

### Equal-width Columns

All three elements should have equal widths and appear on the same line regardless of viewport width.


### Set Columns Width

- The _first_ and _last_ elements should be variable width like the last row.
- The _second_ element should have a grid column width of **3**.
- The _third_ element should have a grid column width of **7**.


### Breakpoint Specific

_All_ columns should span:

- **12** grid columns for the ***xs*** breakpoint.
- **6** grid columns for the ***sm*** breakpoint.
- **4** grid columns for the ***md*** breakpoint.
- **3** grid columns for the ***lg*** and ***xl*** breakpoints.


### Alignment

#### Row #1
- _All_ columns should be:
	- Of equal width
	- Vertically centered

#### Row #2
- _All_ columns should be of equal width.
- The _first_ column should be vertically aligned to the bottom.
- The _last_ column should be vertically centered.

### Row #3
- _All_ columns should have equal spacing between themselves but span from both ends of the container.
- All columns should have the ***xs*** breakpoint sized to be **3** grid columns.

### Row #4
- _All_ columns should have equal spacing between themselves and have equal spacing ***around*** each element, not ***between*** each element.
- The _first_ and _last_ column should have **4** grid columns in width for the ***md*** breakpoint (same as row #4).

_If you're suck refer to [this](https://getbootstrap.com/docs/4.2/layout/grid/#alignment) section of the documentation._


### Nesting

Create these elements in the order they're listed.

1. Create a `<h1>` element:
	1. Must always span full width of row
1. Create **two** `<div>`:
	1. Both must span full width of row for the ***xs*** breakpoint
	1. Both must span half the width of the row for all other breakpoints
	1. First `<div>`:
		1. Has the HTML class `fun-facts`
		1. Contains four equal sized columns that are vertically aligned
		1. In each column add a `<p>` element with a fun fact about yourself.
	1. Second `<div>`:
		1. Has the HTML class `fun-fibs`
		1. Contains four **unequal** sized columns that do not span the whole width of the row
			1. Vertically align each one differently
		1. Have equal spacing ***around*** them horizontally. The columns can be any width, but no two can be the same
		1. In each column add a `<p>` element with lies about yourself.
