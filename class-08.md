## Learn CSS Layout
In the early days of the web, designs more complex than a simple document were laid out with <table> elements. CSS was widely adopted by browsers in the late 90's. CSS allowed web developers to use it to create things on a page without having to use HTML. Modern CSS has some powerful tools for layouts.
There are two main layout mechanisms that create layout rules for multiple elements, flexbox and grid.
Flexbox is a layout mechanism for one-dimensional layouts. Layout across a single axis, either horizontally or vertically
Grid is similar in a lot of ways to flexbox, but it is designed to control multi-axis layouts instead of single-axis layouts (vertical or horizontal space)

If not using grid or flexbox, your elements display in normal flow. There are a number of layout methods that you can use to adjust the behavior and position of items when in normal flow. You can also wrap text around an image using Floats.
-img {
	float: left;
	margin-right: 1em;
}

## Multicolumn layout 
If you have a long list of elements like countries of the worlds you can use split the countries into multiple columns to avoid crowding and white space.This automatically splits that long list into two columns and adds a gap between the two columns

## Positioning
The position property changes how an element behaves in the normal flow of the document and how it relates to other elements.

## Layouts ( from duckett book)
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box. Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. 

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element

CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning

_
- Normal Flow
every block-level appears in a new line  causing each item to appear lower down than the previous one.

- Relative Positiong
This moves an element from the position it would be in normal flow

- Absolute Positioning
This Positions the element in relation to its containg element.