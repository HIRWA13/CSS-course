# CSS Grid

## intro:

Grid in CSS is a powerful tool that helps us to align layouts in a two dimensional alignment unlike flexbox that aligns elements in one dimension.

## Grid Teminologies:

Before practicing grid one should know the following terms:

[Grid Container]() : this is the element tha contains items that the grid property will have effect on.
it is the parent of the grid items.

[Grid Items](): these are items(elements) present in a grid container
i.e they are the children of the Grid Container.

[Grid Cell](): This is the intersection of a row and a column in the grid. each cell can contain one or more grid items.
Grid cells are created by defining the number of columns and rows in the grid.

[Grid Track](): a grid track is defined as a single row or a column of the grid. Grid tracks can be sized explicitly by using a length or a percentage value or they can be sized utomatically using the "[auto]" value.
Grid tracks are created by defining grid lines

[Grid Area](): a grid area is a rectangular area of the grid that contains one or more grid cells. a grid area is defined by giving a name to a group of cells. Grid areas can span multiple rows and columns.

### The difference between a [grid area]() and a [grid track]():

-> a grid track spans the whole column or row but a grid area spans due to the number of grid cells that makes it up.

[Grid Lines](): grid lines are the lines that defines the boundary of a grid track or grid area.Grid lines can be either Vertical or Horizontal and are numbered from '1 to n' where n is the number of columns or rows.

In Summary:
a grid track is a single column or row of the grid, a grid cell is the intersection of a column and a row of the grid, a grid area is an area combining one or more grid cells and grid lines are the lines that defines the boundaries of grid tracks and grid areas.

## Grid Properties:

These are properties that makes it possible to design layouts using grid.
we have properties on both parent grid(grid_containner) and child grid(grid_item).

### Grid Container properties:

**|1.grid-template-columns|**: this helps u to specify how many columns the grid should have and the sizes of each.

**|2.grid-template-rows|**: this allows us to specify the number of rows our grid should have and the size of each row.

**|3.grid-gap|**: this helps us to provide a space between columns and rows

**|4.grid-auto-rows|**: this property helps us to define the length of a row in the grid.

**|5.grid-auto-columns|**: this property helps us to define the length of a column in our grid.

**|6.grid-template-areas|**: this property allows us to create grid areas in the grid.

**|7.justify-content|**: this propert deals with positioning of the grid on the X-axis(its responsibility is to position the grid container on various positions[center, start, end, etc]())
**|8.align-items|**: this property allows us to specify where to position our grid on the Y-axis.(it works the same way as the justify-content property but it takes effect on the Y-axis).

### Grid items property:

these are the properties that works on individual grid items.

**|1.grid-column|**: this property allows us to define the column starting position and ending position of the grid item.
**|2.grid-row|**: this works the same way as the [grid-colummn] but it takes effect on rows.
**|3.align-self|**: with this, we align a grid-item on Y-axis([center-start-end-etc])
**|4.justify-self|**: with this, we align a grid-item on X-axis([center-start-end-etc])
**|5.order|**: this property helps us to change the HTML stacking order of our grid item.

## The Difference Between Grid and FlexBox:

-> in CSS, FlexBox helps us to to create one dimensional layouts with a row or a column by using the "[flex-direction]" property where you set it to either row or column [But] with CSS Grid, we have the ability to create two dimensional layouts and we are also able to span multiple rows or columns without changing their original Heights or widths.

_|This directory contains demomonstrations of the CSS Grid, Remember to check it out.|_

## Author:

[HIRWA](www.github.com/HIRWA13)
