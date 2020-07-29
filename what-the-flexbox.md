# What the flexbox WesBos course Notes

* 100vh is new way to write 100% height
* flex direction.  justify-content and align items don't necessarily mean left to right or top to bottom
* flex direction row is default
* flex-direction: column;  is another option
* main access and cross access
* flex-wrap: nowrap; is the default.  if your flex items width is bigger, it doesn't matter, it will try to fit it in one block. 
* flex-wrap: wrap respects the stated width of each flex item.
* by default flex items will stretch across the entire container size.  That's why you can set height: 100vh or min-height: 100vh
* flex-wrap: wrap-reverse; will go reverse on the cross axis.
* min-height will make teh window height expand (scroll) as needed
* marign is not part of the box model... padding and border are part of the box model.
* You can use calc if you want to include margin and remove it from the 33.333333% box width.  otherwise use padding and border.

## flexbox ordering
* flex: 1 on your flex items will give each of them the same width and fill up the space horizontally.
* order property. no units, just relative.  Easy way to move around items especially like responsive design desktop vs. mobile site...by default all flex items have an order of 1.

## Alignment

* for justify-content to work when your main axis is column, you need a fixed height so you can put something like min-height: 100vh.

## Align items

* by default align-items is set to stretch
* align items baseline will match the bottom of the content or if it's horizontal axis is main, then the beginning of the axis.

## Flex property
* flex-grow, flex-shrink, and flex-basis are all encompassed into flex.
* flex is shorthand for both flex-shrink and flex-grow.
* flex-basis is the normal width including padding of the element.
* default flex-grow is 0. if you put flex-grow: 1 it will take up all the remaining white space.
* flex grow, shrink and then basis.  example: flex: 10 5 400px;

## navbar challenge
* for something to wrap, it needs to have a width (aka basis).

## mobile reorder challenge
* order of elements is by default 0. // you need to make them all high so then when you reorder, you can use 1-...
