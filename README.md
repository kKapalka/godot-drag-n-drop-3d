# godot-drag-n-drop-3d
Godot Plugin for a 3D Drag &amp; Drop. Developed for version 4.2.2


Projected list of features:

- GridMap for painting the draggable area & area permitted for object placement
- Pick up & Place (click, movement, click) and Drag & Drop (mouse down, movement, mouse up)
- Shaders for informing the player whether the area permits object placement
- Free Movement & Snap To Grid
- Definable object pick-up rotation and inertia (object rotating upon pick-up, object lagging behind and rotating while being dragged around)
- Object returning to its original location upon 'ui_cancel' event
- Event listeners for 'on_picked_up', 'on_drag_started', 'on_dragging', 'on_drag_ended', 'on_drag_canceled', 'on_drag_permitted_area_entered' / 'exited', 'on_drag_forbidden_area_entered' / 'exited', 'on_drop_successful', 'on_drop_failed'
- Mapping of 2D UI elements to 3D objects to be placed