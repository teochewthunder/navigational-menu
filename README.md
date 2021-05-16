# Navigational Menu 

## The `nav` tag
The placeholder for the navigational menu is the `nav` tag, which has been placed at the top of the screen using the `position`, `top` and `left` properties.

## The first level
The entire navigational menu is represented by a single `ul` tag. The first level menu items are the `li` tags within the first `ul` tag. 
- It is important to set the `display` property to `inline-block` in order to set `float` and `width` properties.
- `a` tags are also styled to remove underlines, as well as the `hover` pseudoselector, though these are merely ornamental.

## The second level
These are nested `ul` and `li` tags. They are again styled setting the `display` property to `inline-block`, as well as `padding` for adjustment.
- `a` tags inherit styles from the parent.
- in addition, background color changes on `hover`.

## The third level
As with the second level, `ul` and `li` tags are nested within the required second level menu items.
- `padding` and `margin` properties are used to adjust alignment.
- `a` tags inherit styles from the parent.
