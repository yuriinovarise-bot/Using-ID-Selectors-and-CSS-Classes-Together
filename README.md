Using ID Selectors and CSS Classes Together
Description

In CSS, an element can have both an ID and one or more classes. This allows you to assign some styles via the ID and other styles via class selectors.

Example

HTML:

<div id="block" class="large">
	<p>text</p>
	<p>text</p>
</div>


CSS:

#block {
	color: red;
	font-family: Arial;
}

.large {
	font-size: 30px;
}


The #block selector styles only the element with the unique ID block.

The .large class selector can be applied to multiple elements, giving them a consistent font size.

Combining ID and class selectors gives flexibility in styling unique elements while keeping reusable styles.

Tasks

Style a block using both its ID and class attributes.

Apply a different style to another block using only a class.

Understand the difference between ID selectors and class selectors, and how they can work together.
