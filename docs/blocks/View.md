---
title: View
description: Documentation for built-in View blocks in Sketchware Pro.
sidebar_position: 7
slug: view
tags:
 - Blocks
 - Built-in 
 - View
---

In Sketchware Pro, View blocks let you control and style every UI element on your app's screen (such as Buttons, TextViews, Layouts, and ImageViews). You can use them to hide/show views, rotate them, animate positions, change colors and borders, add or remove views dynamically, and listen for click or touch events.

# Built-in View Blocks

### View: [view] setVisible visible: [visible]
![set visible](assets/view/set-visible.png)

Changes whether a view is visible on screen. You can set it to:
- `VISIBLE`: The view is shown normally.
- `INVISIBLE`: The view becomes hidden/invisible, but still reserves its space on screen.
- `GONE`: The view is completely hidden and its space is collapsed as if it doesn't exist.

### visibility of View: [view] equals visible: [visible]
![visibility of equals](assets/view/visibility-of-equals.png)

Checks if a view's current visibility state matches `VISIBLE`, `INVISIBLE`, or `GONE`. Returns `true` if it matches, otherwise `false`.

### View: [view] setElevation ()
![set elevation](assets/view/set-elevation.png)

Sets the elevation (shadow depth) of a view in density pixels (dp). A higher number gives the view a deeper drop shadow, making it look raised off the screen.

### View: [view] setRotation ()
![set rotation](assets/view/set-rotation.png)

Rotates a view clockwise by a chosen angle in degrees (e.g., `45`, `90`, `180`).

### View: [view] getRotation
![get rotation](assets/view/get-rotation.png)

Returns the current rotation angle of the view in degrees.

### View: [view] setAlpha ()
![set alpha](assets/view/set-alpha.png)

Sets how transparent or opaque a view is. Accepts values from `0.0` (completely invisible / transparent) to `1.0` (fully visible / solid).

### View: [view] getAlpha
![get alpha](assets/view/get-alpha.png)

Returns the current opacity (alpha) of the view between `0.0` and `1.0`.

### View: [view] setTranslationX ()
![set translation x](assets/view/set-translation-x.png)

Shifts the view horizontally to the left or right from its original spot without changing the layout. Positive numbers move it right; negative numbers move it left.

### View: [view] getTranslationX
![get translation x](assets/view/get-translation-x.png)

Returns the current horizontal shift distance (translation X) of the view in pixels.

### View: [view] setTranslationY ()
![set translation y](assets/view/set-translation-y.png)

Shifts the view vertically up or down from its original spot. Positive numbers move it down; negative numbers move it up.

### View: [view] getTranslationY
![get translation y](assets/view/get-translation-y.png)

Returns the current vertical shift distance (translation Y) of the view in pixels.

### View: [view] setScaleX ()
![set scale x](assets/view/set-scale-x.png)

Stretches or shrinks the width of the view. `1.0` is normal size, `2.0` is double width, and `0.5` is half width.

### View: [view] getScaleX
![get scale x](assets/view/get-scale-x.png)

Returns the current horizontal scale multiplier of the view.

### View: [view] setScaleY ()
![set scale y](assets/view/set-scale-y.png)

Stretches or shrinks the height of the view. `1.0` is normal size, `2.0` is double height, and `0.5` is half height.

### View: [view] getScaleY
![get scale y](assets/view/get-scale-y.png)

Returns the current vertical scale multiplier of the view.

### View: [view] getLocationX
![get location x](assets/view/get-location-x.png)

Returns the horizontal X coordinate of the view's top-left corner on the screen in pixels.

### View: [view] getLocationY
![get location y](assets/view/get-location-y.png)

Returns the vertical Y coordinate of the view's top-left corner on the screen in pixels.

### View: [view] getHeight
![get height](assets/view/get-height.png)

Returns the actual height of the view on screen in pixels.

### View: [view] getWidth
![get width](assets/view/get-width.png)

Returns the actual width of the view on screen in pixels.

### View: [view] requestFocus
![request focus](assets/view/request-focus.png)

Gives keyboard focus to a view, such as bringing the cursor into an EditText input box so the user can start typing.

### View: [view] removeView View: [child]
![remove view](assets/view/remove-view.jpg)

Removes a specific child view from inside a parent layout (e.g. removing a button from a LinearLayout).

### View: [view] removeAllViews
![remove all views](assets/view/remove-all-views.png)

Clears out and removes all child views inside a parent layout in one go.

### View: [view] addView View: [child]
![add view](assets/view/add-view.png)

Adds a new child view to the end of a parent layout.

### View: [view] getChildAt ()
![get child at](assets/view/get-child-at.png)

Retrieves the child view at a specific index inside a parent container. Indexing starts at `0` for the first child.

### View: [view] addView View: [child] index ()
![add view at index](assets/view/add-view-at-index.png)

Inserts a child view into a specific position/index inside a parent layout.

### View: [view] setGravity Gravity Vertical: [v] Gravity Horizontal: [h]
![set gravity](assets/view/set-gravity.png)

Controls how content inside the view is aligned (e.g., Center, Left, Right, Top, Bottom).

### View: [view] setColorFilter Color: [c] with PorterDuff [mode]
![set color filter](assets/view/set-color-filter.png)

Tints or paints over an image view with a chosen color using a blending mode (like `SRC_IN` or `MULTIPLY`).

### View: [view] setBackgroundColor Color: [c]
![set background color](assets/view/set-background-color.png)

Sets the solid background color of any view.

### View: [view] setBackgroundResource BackgroundImage: [img]
![set background resource](assets/view/set-background-resource.png)

Sets an imported image from your project's Image Manager as the view's background.

### View: [view] setBackgroundDrawable drawable: [d]
![set background drawable](assets/view/set-background-drawable.png)

Sets a custom drawable graphic as the background of a view.

### View: [view] setStroke () strokeColor Color: [c]
![set stroke](assets/view/set-stroke.png)

Adds a colored outline border around a view with the chosen line thickness.

### View: [view] setCornerRadius () color Color: [c]
![set corner radius](assets/view/set-corner-radius.png)

Gives the view rounded corners with a chosen radius and fills it with a background color.

### View: [view] setGradientBackground Color: [c1] and Color: [c2]
![set gradient background](assets/view/set-gradient-background.png)

Applies a smooth color gradient background that blends from the first color into the second color.

### View: [view] performClick
![perform click](assets/view/perform-click.png)

Simulates a finger tap on a view through code, triggering its `onClick` event just as if the user clicked it physically.

### When View: [view] clicked
![when clicked](assets/view/when-clicked.png)

Container event block. Any blocks placed inside will run whenever the specified view is clicked.

### When View: [view] long clicked
![when long clicked](assets/view/when-long-clicked.png)

Container event block. Any blocks placed inside will run when the user presses and holds down on the view.

### When View: [view] touched
![when touched](assets/view/when-touched.png)

Container event block. Runs whenever a finger touches, moves across, or releases from the view.

### View: [view] showSnackbar text [] actionText []
![show snackbar](assets/view/show-snackbar.png)

Pops up a quick temporary notification bar (Snackbar) at the bottom of the screen with a message and an optional clickable action button.

## Bottom line
That was the explanation for every built-in View block in Sketchware Pro. If you think some info is wrong or doesn't exist, please let us know in our discord server or simply open a Pull Request in our website's GitHub repository.
