# UE4_Custom-UMG-Layout
Unreal Engine 4 Widget that can be placed within other widgets to provide customizable layout during runtime

## Features
- Changing widget position during runtime.
- Save current widget position automatically and load it when running the game again.
- Lock widget position, prevent accidentally moving.
- Snapping widget to widget and/or widget to vertical and horizontal middle of screen.
- Widgets cannot leave viewport.
- Customizable, all features can be enabled and disabled as required.

## Setting up the widget
Setting up the widget doesn't require any additional work in blueprints, just add the widget to any existing User Widget or
create a new one and just add it.

For creating a new widget:  
1. Add a new User Widget to your project.
2. To the Canvas Panel add a new Overlay widget
3. The the new Overlay widget the CUL_Frame widget as first child.
4. Set the CUL_Frame to span the Overlay vertically and horizontally
5. Continue adding elements to the Overlay as required
6. Run the project

A small tutorial on how to set up the widget can be found here: https://youtu.be/MvB0rJP8Jnc
