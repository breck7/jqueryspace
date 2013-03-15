space
=====

space is an experimental jQuery plugin that brings responsiveness to absolutely positioned websites. It works by creating negative space elements that bind two sibling blocks to each other.

How it works:

1. Create an absolutely positioned div that you want to be responsive based on its content.
2. Create a second div.
3. Create a div with type="space". Set the origin to your first div and the end to your second div. Set a width or height.
4. Include the space 

Two possible approaches:
- 1, just look at the changes between min-height and height.
- 2, get the size of the negative space + bottom of the parent div


Render the vertical tree first.

Then render the horizontal tree.

Todo: use CSS transform for faster performance?




