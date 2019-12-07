# presentation

### Slide 1

CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system.

### Slide 2

The grid properties are supported in all modern browsers, but grid properties are not supported in Opera mini and partial supported in IE’/;

### Slide 3

A grid layout consists of a parent element, with one or more child elements.

An HTML element becomes a grid container by setting the display property to grid or inline-grid.

All direct children of the grid container become grid items.

In my example, a div with class grid-container is grid container and all child elements with class grid-item is grid items.

### Slide 4

The vertical line of grid items are called columns and The horizontal line of grid items are called rows.

### Slide 5

The space between each column/row are called gaps. You can adjust the gap size by using one of the properties:

grid-column-gap

grid-row-gap

grid-gap

The grid-column-gap property sets the gap between the columns.

The grid-row-gap property sets the gap between the rows.

The grid-gap property is a shorthand property for the grid-column-gap and the grid-row-gap properties. In my last example, 50px is grid-column-gap and 20 is grid-row-gap.

### Slide 6

The grid-template-columns property defines the number of columns in your grid layout, and it can define the width of each column. If you want your grid layout to contain 4 columns, specify the width of the 4 columns, or "auto" if all columns should have the same width.

in my second example, the first, second, and last columns have a fixed width. The third column occupies the rest of the space

### Slide 7

The grid-template-rows property defines the height of each row. The value is a space-separated-list, where each value defines the height of the respective row

### Slide 8

justify-items is used to justify the grid items along the row axis. The possible values are start, end, center and stretch. Here are examples with center and end

### Slide 9

Similar to justify-items, but aligns the grid items along the column axis. Here are examples with center and end

### Slide 10

The justify-content property is used to align the whole grid inside the container. You can use the following values: start, end, center, stretch, space-around, space-between or space evenly. On this slide, you can see four examples.

### Slide 11-12

The align-content property is used to vertically align the whole grid inside the container.

### Slide 13

Both justify-self and align-self are analogous to the equivalent properties available on the container (justify-items and align-items), but they apply on specific items that should be positioned differently than the rest of the grid items. Here are examples with justify-self: end and align-self:start;

### Slide 14

The line between columns are called column lines.

The line between rows are called row lines.

In the picture you can see the numbers of these lines

### Slide 15

You can place items onto the grid by line number. In the following example the item1 is positioned from column line 1 to column line 3, and other example the item1 is positioned from row line 1 to row line 3.

### Slide 16

The grid-column property defines on which column(s) to place an item.

You define where the item will start, and where the item will end.

The grid-column property is a shorthand property for the grid-column-start and the grid-column-end properties.

To place an item, you can refer to line numbers, or use the keyword "span" to define how many columns the item will span.

### Slide 17

The grid-row property is similar to The grid-column property.

The grid-row property defines on which rows to place an item.

The grid-row property is a shorthand property for the grid-row-start and the grid-row-end properties.

### Slide 18

The grid-area property can be used as a shorthand property for the grid-row-start, grid-column-start, grid-row-end and the grid-column-end properties.

### Slide 19

The grid-area property can also be used to assign names to grid items.

Item1 gets the name "item1" and spans all five columns using the grid-template-areas property.

Each row in the grid-template-areas property is defined by apostrophes (' ')

The columns in each row is defined inside the apostrophes, separated by a space. Period signs represent items with no name

### Slide 20

The Grid Layout allows us to position the items anywhere we like.

You can re-arrange the order for certain screen sizes

### Slide 21

The minmax() function makes to define the size of a grid track as a minimum to maximum range.

The syntax of the minmax() function is simple, it takes two arguments: a minimum and a maximum value.

In my example, the first column ranges between 200px and 500px and the remaining space is evenly shared between the other two.

### Slide 22

With CSS Grid Layout, we get a new flexible unit: the Fr unit. Fr is a fractional unit and 1fr is for 1 part of the available space. Here are a few examples of the fr unit at work.

### Slide 23

You can also use the fr unit together with the repeat() function for a simpler syntax. The result of this syntax is similar to The results of this syntax You can use repeat() more than once. You can also combine repeat() with other CSS units

### Slide 24

With so much scope to build efficient layouts using just CSS, there is no doubt that Grid will has a huge part to play in the future of front end development.
