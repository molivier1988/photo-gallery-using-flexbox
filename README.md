# Photo Gallery using Flexbox

## Purpose

Build a responsive photo gallery using Flexbox

## What I learnt

Flexbox is used to place elements in one-dimension either horizontal or vertical.

To make an element a flexbox ```display: flex```

Flexbox has a main-axis and a cross-axis which can be swapped using ```flex-direction```.
There are 2 options ***row*** (default) | ***column***.

Possible values for ```flex-direction```

```row```   => Default
```row-reverse```
```column```
```column-reverse```

## Flex Wrap

Defines how flex items behave when the container is too small to contain them.
There are 2 options ```nowrap``` (default) | ```warp```

## Justify Content

Determines how flex items are positioned along the main axis. ```justify-content```

## Align Items

Positions flex items along the cross-axis. ```align-items```

## Adding Space between flex items.

Space flex items using ```row-gap``` | ```column-gap``` | ```gap``` (to set both row and column together)

## Parent vs. Child

## Other observations

Often when setting a fixed width and hight on images they can get a little
distorted. Use the ```object-fit: cover``` property to resolve this.

```::after``` is used to create an element that is the last child of the selected element.

For our image gallery if you give this pseudo-element the same width as the other
images it will push our last actual image left. 

***See code block starting at line 40 in the css file***

***NOTE*** ```::after``` must contain the ```content: ""``` property to ensure
this element has no content.