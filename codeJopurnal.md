==========================
===> CSS code journal <===

## Flexbox.
* To use the flexbox layout, assign the  property display with a value of flex to your container.

* you can control the direction of flow with the ```flex-direction``` property, which can be assigned to flex containers.

* you can use ```row-reverse``` and ```column-reverse``` to change the order fo HTML elements displayed

* you can also change the order of individual flex items with the property ```order``` howevery be careful when doing this as changing the order can cause problems for users navigating your site with their keyboards or a screen reader instead of a mouse or touch screen

## Flex Properties.
* they are properties available for flex items. (the child items of the flex container). With these three properties
    * ```flex-grow```
    * ```flex-shrink```
    * ```flex-basis```
* You can control the ratios of the items with the flex container. you can either set each property on its own or use the shorthand form where you combine all three in the property ```flex```. The calues are passed on in this order:
    * ```flex-grow, flex-shrink, flex-basis```
    * example code
    * ```.profile-text {flex: 1 1 100px;}```
    * The flex-basis value assigns teh base size to each element.in this case its 100px. This means that before any specific layout behavior is added to the flex items, they'll already have a width of 100px.
    * ```flex-grow``` and ```flex-shrink``` tell the flex-items whether they're allowed to grow or shrink within the flex container.

    * You can use the shorthand form where you combine all three in the property ```flex```
        * The values are passed on in this order:
            ```flex-grow, flex-shrink, flex-basis```

            ```.profile-text {flex: 1 1 100px }```
        * The ```flex-basis``` value assigns the base size to each element. in this case, this is 100px this means that before any specific layout behavior is addes to the flex items, they'll already have a width of 100px. ```flex-grow``` and ```flex-shrink``` tell the ```flex-items``` whether they're allowed to grow or shrink within the flex container.