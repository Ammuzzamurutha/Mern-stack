CSS Flexbox (Flexible Box Layout) is a 1D layout model designed for arranging items in rows or columns, allowing them to dynamically fill space, shrink, or grow to fit screen sizes
display: flex is a CSS property that activates the Flexbox (Flexible Box) layout model for an element. It is a one-dimensional layout system designed to arrange items in either a row or a column.
The flex-direction CSS property determines the direction in which flex items are laid out within a flex container. 
row (default): Items are placed horizontally from left to right (in left-to-right languages like English).
row-reverse: Items are placed horizontally but in reverse order, starting from the right side.
column: Items are stacked vertically from top to bottom.
column-reverse: Items are stacked vertically but in reverse order, starting from the bottom. 
The CSS justify-content property defines how the browser distributes space between and around content items along the main axis of a Flexbox container or the inline axis of a Grid container.
flex-start (Default): Items are packed toward the start of the container.
flex-end: Items are packed toward the end of the container.
center: Items are centered along the main axis.
space-between: Items are evenly distributed; the first item is at the start edge and the last item is at the end edge.
space-around: Items are distributed with equal space around them. Visually, the gaps between items are double the size of the gaps at the edges.
space-evenly: Items are distributed so that the spacing between any two items and the spacing to the edges is exactly the same. 
The align-items CSS property controls how items are positioned along a container's cross axis
stretch (default): Items stretch to fill the container's height (or width in column layouts).
center: Items are centered along the cross axis.
flex-start / start: Items align to the beginning of the container (e.g., the top in a row layout).
flex-end / end: Items align to the end of the container (e.g., the bottom in a row layout).
baseline: Items align based on the baseline of their text content
content alignment typically involves two axes: the main axis (usually horizontal) and the cross axis (usually vertical)
The CSS align-self property allows you to align an individual flex or grid item along the cross axis, overriding the default alignment set by its parent's align-items property.
Flex sizing refers to how elements (flex items) within a flex container expand, shrink, and occupy space along the main axis. This behavior is primarily controlled by three CSS properties: flex-grow, flex-shrink, and flex-basis
General Syntax: flex: <flex-grow> <flex-shrink> <flex-basis>;
----------------------------------------------------------------------------------------------------------
Keypad activity 
involves div and child divs grouped by classes 
grouped 3 divs with single name 
and then added styling 
----------------------------------------------------------------------------------------------------------

