# CSS-Flex-Container
# Parent Element (container)
Like we specified in th previous chapter, this is a flex container (the blue area)
with three flex items:

The flex container becomes flexible by setting the display property to flex.

# The flex-direction Property
The flex-direction property defines in which direction the container wants to stck the flex items.

Example

The column value stacks the flex items vertically (from top to bottom):

The column-reverse value stacks the flex items vertically (but from bottom to top)

Example

The row value stacks the flex items horizontally (from left to right):

Example

The row-reverse value stacks the flex items horizontally (but from right to left):

# The flex-wrap Property
The flex-wrap property specifies whether the flex items should wrap or not. 

The examples below have 12 flex items, to better demonstrate the flex-wrap property.

Example

The wrap value specifies that the flex items will wrap if necessara:

Example

The rowrap value specifies that the flex items will not wrap (this is default):

Example

The wrap-reverse value specifies that the flexible items will wrap if necessaray, in reverse order:

# The flex-flow Property
The flex-flow property is a shorthand property for setting for setting both the flex-directio and flex-wrap properties.

# The justify-content Property
The justify-content property is used to align the flex items:

Example

The center value aligns the flex items at the center of the container:

Example

The flex-start value aligns the flex items at the beginning of the container (this is default):

Example

The flex-end value align the flex items at the end of the container:

Example

The space-around value displays the flex items with space before, between, and after lines:

Example

The space-between value displays the flex items with space between the lines:

# The align-items Property
The align-items property is used to align the flex items.

In these examples we a 200 pixels highg container, to better demonstrrate the align-items property.

Example

The center value align the lfex items int he middle of the container:

Example

The flex-start value aligns the flex items at the top of the container:

Example

The flex-end value aligns the flex items at thte bottom of the container:

Example

The stretch value streches the flex items to fill the container (this is deafult):

Example 

The baseline value align the flex items such as their bselines aligns:

Note: the example uses different font-size demonstrate that the items gets aligned by  the text baseline:

# The align-content Property
The align-content property is used to align the flex lines.

In these examples we use 600pixesl high container, with the flex-wrap property set to wrap, to better demonstrate the align-content property.

Example

The space-between value displays the flex lines with equal space betweent them:

Example

The space-around value displays the flex lines with space before , between, and after them:

Example

The stretch value stretches the flex lines to take up the remaining space (this is default):

Example 

The center value displays display the flex lines in the middle of the container:

Example

The flex-start value display the flex lines at the start of the container:

Example

The flex-end value displays the flex lines at the end of the container:

# Perfect Centering
In the following example we will solve a very common style problem: perfect centering.

SOLUTION: Set both the justify-content and align-items properties to center, and the flex item will be perfectly centered:

# The CSS Flexbox Container Properties
The following talbe llists all the CSS Flexbox Container properties:

Note: I just added screen shot in the top.