Make an application for dynamically previewing the design of a paper plate.
This will be used to help communicate with customers.

### Plate Drawing Preview

There is a live preview on the left showing a CAD drawing of a paper plate.

This drawing must look identical to the attached image of a real drawing.
Below are details to understand the attached image:

- The drawing has fixed dimensions matching a piece of paper (8.5" x 11").
- There are 2 views: Top View and Front Section View. The top view is always directly over the front section view. The top view has a line (A) indicating the path of the section view (Section A-A).
- The title block is in the bottom right. It includes information about the company, plate design, designer, and date.
- Below the drawings is a disclaimer. This text must be exactly the same.
- The front section views (Section A-A) show the dimensions.
- In the attached example image, the plate geometry is in red and the dimensions are in black.
- The placement of the dimensions is somewhat flexible. Just make sure they don't overlap and all clearly have leader lines pointing to the correct location.

### Plate Configuration Panel

There is a configuration panel on the right that provides all configuration options for the design of the plate in the drawing.

- It is always visible.
- The plate design is dynamically generated from the values in the configuration panel. This is very very important.

The parameters are the following:

- THICK - The thickness of the paper. Default to 0.018 inches.
- PLATE DEPTH - The distance from the top to the bottom of the plate.
- TOP OUT DIAMETER - The maximum diameter from measuring the outside of the plate.
- TOP IN DIAMETER - Intersection of the theoretical side wall and the top of the plate.
- BOTTOM OUT DIAMETER - Intersection of the side wall and the bottom of the plate.
- SIDE WALL - The angle between the plate bottom and the plate side.
- TOP RADIUS - The transition radius between the plate top and the plate side.
- BOTTOM RADIUS - The transition radius between the plate bottom and the plate side.
- FLANGE DEPTH - The distance from the top of the plate to the bottom of the the flange.
- TURN DOWN - The angle of the flange relative to the plate top.
- TURN DOWN RADIUS - The transition radius between the plate top and the flange.

### Enhancements

The following features are independent of the design but must be included.

1. Saved Designs - Add a "designs" tab in the configuration panel for storing the current and past designs. This will allow the user to quickly switch between designs. Add 3 example plates so the history already has samples to test with.

1. Export to PDF - A button below the drawing preview. This will open a new page formatted for printing and trigger the print dialog.

1. Quick Add - Add a text box below the configuration options with the title "Quick Add". This will be used for copying an email into it that has all the configuration values somewhere. Use AI to scan the email text and automatically fill in the configuration values.

### Other considerations

- All dimensions are in inches by default. Add a toggle for metric (millimeters).
- The interface needs to be beautiful. This tool will be used by sales and marketing teams.
- Make it work best for desktop. Phone does not matter.
- Multiple users will be using this simultaneously. Make sure they can't see each others designs.

### Context

- Plates are made out of paper board, not paper (like for writing).
- You are an expert paper plate designer.
- You are an expert computer aided drafter.

# Future Ideas

The following are features we want to add in the future. Don't do them now, but make sure things are safe for adding them later.

- Blank size calculation - Determine the size of paper required for the press to form the plate shape described in this drawing.
- Volume calculation - The amount of water the plate would hold if filled to the very top.
- Polygon Shape support - Expand support for triangle, square, pentagon, hexagon, and octagon shapes.
- Oval Shape support - Expand support for oval and egg shapes.
- Email Button - Opens the users email client and inserts all the required dimensions as a list.

## Additional prompts

### More plate types

```md
Add support for different shaped plates.
Add a configuration option in the side panel to pick shape: Round, Triangle, Square, Pentagon, Hexagon, Octagon.
For all options except round, add a configuration option in the side panel to set "Corner Radius". default: 0.5 inches
```

### Show in 3D

```md
1. Add a 3D viewer that renders the plate in a semi-realistic way.

   - It should support all plate shapes.
   - It should be a solid model, not wireframe.
   - The plate should be floating in space so it can be easily rotated and viewed from different angles.

2. Add mouse controls to pan, zoom, and rotate.

   - Rotate is controlled by clicking and dragging. Add a toggle to invert rotation.
   - Pan is controlled by holding ctrl (windows) / cmd (mac) then clicking and dragging.
   - Zoom is controlled by holding shift then clicking and dragging.
   - Add a toggle to invert

3. Add a toggle to show a cross section view.
```

```md
Change the 3D viewer to show the plate on a wood table. Make the background look like dining room of a person's home.
```
