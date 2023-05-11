# CSS FlexBox

## intro:

**|FlexBox|** is a powerfull tool that allows us to easily arrange and align items in a container. it works by defining a flexible containerthat contains one or more flex items which can be flexed and re-ordered according to the needs of the layout.

to use flexbox, we first need to define a container and set its "[display]" property to "[flex]" and this will turn the container into a flex container and allows us to use all the [flex-properties].

eg:
**|.container|**{
display: flex;
}
once we have a flex container, we can control the layout of its children using various properties that flexbox provides.

#### Bellow are properties that we can use on either [flex-container] or a [flex-item].

**|flex-direction|**: this property determine the direction of the main axis of the flex container, which is the axis along which the flex items are laid out.

the default value of this property is [row] which means that items are laid horizontally. other values include [column] for vertical layouts, [row-reverse] for reversed-horizonal layouts, [column-revers] for vertical layouts in a reversed order.

**|justify-content|**: this property controls the alignment of items along the main-axis of the flex-container. the default value is the [flex-start] which aligns items at the start of the container, [center] which centers items in the container, [flex-end] which aligns items at the end of the container, [space-between] which distributes items evenly with space between them, [space-arround] which distrributes items evenly with space arround them and [space-evenly] that distributes items evenly with equal space arround the flex items.
**|align-items|**: this property controls the the alignment of items along the cross items along the cros axis of the flex-container which is the axis perpendicular to the main axis. the default value is [strecth] which stretches the item to fill the container. other values include [flex-start] aligns items at the start of the cross axis, [flex-end] that aligns items at the end of the cross axis, [center] which centers items on the cross axis and [baseline] that aligns items along with their baselines.
**|flex-wrap|**: this property controls wether items are allowed to wrap onto multiple lines if there isn't enough space remaining in the container. the default value is "[nowrap]" which means that items should not wrap. other values include [wrap] that means iems will wrip onto multiple lines as necessary and [wrap-reverse] that means items will wrap onto multiple lines in a reverse order.
**|flex-grow|**: this property controls how much a flex item should grow to fill any remaining space in the container. the default value is [0] which means that the item will not grow. by setting this property to a positive value means that the item will have to grow proportionally to other items in the container.
**|flex-shrink|**: this property controls how much a flex item should shrink if there isn't enough space remaining in the container. the default value is [1] which means the item will shrink proportionally to other items in the container and by setting this property to [0], the item will not shrink at all.

_|Those are just some of the most used properties available in flexbox, but the gives us a good starting for understanding how to use this layout.|_

_|This directory involves the files that demontrates how to work with flexbox on a beginner level, Remember to check them out.|_
