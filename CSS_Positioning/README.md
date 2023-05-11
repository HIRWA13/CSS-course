# CSS Positioning

In CSS, positioning means the placement and layout of elements on a webpage.

CSS provides several properties that allows us to position elements precisely and control their
appearence on the page.

Those propersties are:

[Position Static]()
[Position Relative]()
[Position Absolute]()
[Position Fixed]()
[Position Sticky]()

## Position Static:

This is the default position property of all HTML elements in the normal flow.
-> when you add property "position: static" to an element nothing changes unless it had other position
property that you want to transition from.

## Position Relative:

Adding position relative to an element, first of all the element becomes the ancestral position of its child elements and second we unlock the coordinate properties ("Top, Bottom, Left, Right") that allows
us to move the element wherever we want based on its original position.

eg: element{
position: relative;
top: 10px;
right: 20px;
---------------
with the above code, the element is set to move 10px away from the top
and 20px away from the right relative to its current position
}

## Position Absolute:

When we set "position absolute" to an element, the same thing happen as on the "position relative"
but the element moves relative to its ancestral positioned element(the parent) and with it also we
will have the ability to use the ("Top, Bottom, Left, Right") position property coordinates.

when setting position absolute to an element, remember to set its parent to be positioned absolute so
that the element will positioned relatively to the parent otherwise it will get positioned relative
to the viewport.

eg:
parent {
position: relative;
}
child {
position: absolute;
right: 10px;
bottom: 10px;
}
with the above code, the child element is positioned relative to its parent element and is supposed
to move 10px right away and 20px bottom away.

## Position Fixed:

When we add position fixed to an element, we give it the ability to get stuck on the screen based on the
posititional coordinates ("Top, Bottom, Left, Right") and additionaly the element which is set to position fixed moves relative to the screen(viewport) it does not care about its parent container at all.

eg:
element {
position: fixed;
top: 10px;
left: 20px;
}
----------------
with the above code, the element is set to be fixed on the the screen at 10px away from the top and 20px away from the left.

## Position Sticky:

when we set position sticky to an element, we give it the ability to switch from "position static" to "position fixed" based on the coordinate properties that we specified.

this property is commonly used on the famous navigation bars that are stuck on the top of of the viewport.

eg:
navigation{
position: sticky;
top: 0
}
------------------
with above code, when we scroll and the navigation reaches at the top: 0, it will be stuck there and other elements will move bellow under it.

### Author

[HIRWA](www.github.com/HIRWA13)
