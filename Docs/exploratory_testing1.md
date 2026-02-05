# GraphicsGale - Exploratory Testing (Session 1)

## Goal:
- Explore basic drawing and selection tools to understand application behavior and usability.

## Environment:
- OS: Windows 11;
- Application: GraphicsGale;
- Version: 2.10.01.

## Initial setup:
- Canvas size: 256x256;
- Color mode: 32bit (Full color + Alpha Channel).

## Notes / Observations:
1. Opened the application and created a new canvas with the parameters described above;
2. Started drawing combinations and palletes of different colours;
3. Decided to add text "Combination of colours 1" using the "Draw Text" tool;
4. Wanted to edit the text, but the "Draw Text" tool created a second identical text instead of allowing me to modify the first one;
5. Could not figure out how to edit existing text. Tried to use an "Eraser" tool to clear the canvas from text, but such a tool does not exist in the application;
6. Found the "Paint Mode" tool, which has three modes: "Normal", "Clear", "Opacity";
7. Switched from "Normal" mode to "Clear" mode;
8. Using the "Pen" tool in "Clear" mode, I was able to remove the digit "1" from the text;
9. Wanted to use the "Eyedropper" tool, but it does not exist in the interface. By clicking around, I discovered that right-click (RMB) allows switching to the selected colour;
10. Enlarged colour combinations using the "Rectangular Selection" tool;
11. Tried to enlarge other colour combinations using the "Oval Selection" tool after switching from "Rectangular Selection", but the tool did not respond;
12. Switched to the "Pen" tool, then to "Oval Selection", and after these transitions the "Oval Selection" tool started working;
13. Tried to switch back from "Oval Selection" to "Rectangular Selection", but the interface did not respond. After right-clicking on the canvas, the oval selection disappeared, and only then the "Rectangular Selection" tool worked;
14. Tested the "Lasso" tool by selecting objects, moving them, and modifying them in various ways;
15. Tested the "Mover" tool:
- When the canvas window has a scroll bar, "Mover" works and moves the window in the desired direction;
- When the scroll bar is absent, the tool does not work.
16. When switching to the "Mover" tool, left-click (LMB) allows moving the canvas window, but pressing and holding RMB switches from "Mover" to "Rectangular Selection" and starts selecting an area of the canvas/image;
17. Tested the "Zoom" tool:
- LMB zooms in;
- RMB zooms out.
18. Tested the "MagicWand" tool:
- LMB on colours or areas filled with one colour selects those areas precisely, allowing further manipulations (resize, expand, shrink, transform);
- RMB does nothing.
19. When clicking on a brown-coloured area, "MagicWand" selects both brown and adjacent olive colour, failing to distinguish between two different colours;
20. Tested the "Color Selection" tool:
- Precisely selects areas with different colours;
- Recognizes differences between two similar colours with different saturation or shade levels.
21. "Pen" tool:
- LMB press and hold draws as expected;
- RMB press and hold starts area selection and switches to "Rectangular Selection";
- Simple RMB click acts as the "Eyedropper" tool.
22. Tested the "Connect Line" tool:
- LMB press and hold creates a line in the desired direction;
- LMB click extends the line following the cursor, automatically continuing until RMB is pressed to stop;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
23. Tested the "Spline Curve" tool:
- Both LMB press and hold or simple click extend the curve following the cursor, continuing until RMB is pressed to stop;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
24. Tested the "Rectangle" tool:
- LMB click does nothing;
- RMB click does nothing except acting as "Eyedropper";
- LMB press and hold draws a rectangle shape;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
25. Tested the "Filled Rectangle" tool:
- LMB click does nothing;
- RMB click does nothing except acting as "Eyedropper";
- LMB press and hold draws a filled rectangle with the chosen colour;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
26. Tested the "Oval" tool:
- LMB click does nothing;
- RMB click does nothing except acting as "Eyedropper";
- LMB press and hold draws oval or circle shapes;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
27. Tested the "Filled Oval" tool:
- LMB click does nothing;
- RMB click does nothing except acting as "Eyedropper";
- LMB press and hold draws filled oval or circle shapes with the chosen colour;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
28. Tested the "Flood Fill" tool:
- LMB click fills the area with the chosen colour;
- RMB click acts as "Eyedropper";
- LMB press and hold does nothing;
- RMB press and hold starts area selection and switches to "Rectangular Selection".
29. Tested the "Color Replacer" tool:
- Attempting to draw over already colored areas does nothing;
- Drawing is possible on untouched areas;
- RMB click acts as "Eyedropper";
- RMB press and hold starts area selection and switches to "Rectangular Selection".
30. Tried interacting with the "Antialias" and "Transparent" tools, but observed no effects or changes;
31. Saved the file as "exploratory_testing_image" in PNG format and separately in .gal format.
