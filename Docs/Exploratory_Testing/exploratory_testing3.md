# GraphicsGale - Exploratory Testing (Session 3)

## Goal:
- Test the remaining tools related to creating image animations and create a small GIF animation.

## Environment:
- OS: Windows 11;
- Application: GraphicsGale;
- Version: 2.10.01.

## Initial setup:
- Canvas size: 200x200;
- Color mode: 32bit (Full color + Alpha channel).

## Notes and observations:
1. Opened the application and created a new canvas with the parameters described above;
2. Drew a small house;
3. While drawing, noticed that basic tools lack hotkeys for quick keyboard interaction;
4. Clicked on the tool with a film icon named "Add":
- A modal window titled "Properties" opened with a single tab named "Current frame";
- The "Current frame" tab contains parameters: "Name", "Transparency", "Delay", "Disposal", and buttons "Apply", "OK", "Cancel";
- Next to "Name" there is a selector with values "%framenumber%", "%framenumber_zero%", "%frameindex%", "%frameindex_zero%". Selected "%framenumber%";
- Next to "Transparency" there is a single checkbox named "Transparent Color". Clicking it displays a rectangle with a specific color, and clicking that rectangle opens another modal window titled "Color" where other colors can be selected. Since I was unsure what this parameter does, I left the checkbox unchecked;
- Next to "Delay" there is a selector with values "1/60 sec. (for Video Game)", "1/100 sec. (for GIF)", "1/1000 sec.". Since the goal of this exploratory testing is not only to check tools but also to create a GIF animation, I selected "1/100 sec. (for GIF)";
- Below the "Delay" selector there is a field to enter numeric values. I assume this field sets animation delay in milliseconds (ms). The initial value is "100". Left it unchanged to later check GIF playback speed;
- Next to "Disposal" there is a selector with values "Not Specify", "Not Dispose", "Fill with Background Color" and "Restore to Previous". Did not fully understand this parameter, but selected "Fill with Background Color";
- Clicked "OK" and a new white canvas was created.
5. Using "Add", "Copy (Ctrl+C)" and "Paste (Ctrl+V)" created 8 frames;
6. Clicked on the "Duplicate" tool:
- The same modal window as with "Add" opened;
- Unlike "Add", instead of a white canvas it creates a duplicate of the image.
7. Tool "Delete":
- Clicking the tool opens a modal window with the message "Selected frame(s) will be deleted" and buttons "OK" and "Cancel";
- "Cancel" aborts the delete command;
- "OK" deletes the selected frame.
8. Tool "Back Frame":
- Allows moving back to previous frames.
9. Tool "Forward Frame":
- Allows moving forward to next frames.
10. Saved current work in ".gal" format with name "exploratory_testing_gif1";
11. Attempted to save the file in ".gif" format:
- A modal window appeared with the message "GIF format does not support high-color and full-color. Should the image be changed to 8bpp (256colors) format?" and buttons "Yes" and "No";
- "No" closes the modal window and the file is not saved as ".gif";
- "Yes" closes the modal window and the file is saved as ".gif".

Observation after selecting "Yes":
- About 80% of colors in the "Palette" interface turned black;
- GIF playback was quite slow.


12. Selected all 9 frames using Shift and changed the "Delay" parameter from "100" to "10";
13. Saved the file in ".gif" format with name "exploratory_testing_gif2".

Observations:
- Animation speed became faster;
- On the next save in ".gif" format, the modal window with the message "GIF format does not support high-color and full-color. Should the image be changed to 8bpp (256colors) format?" did not appear.

14. Tool "Properties":
- Opens a modal window with tabs "Current frame" and "All Frames" with the same parameters and buttons as the "Add" tool (point 4).
15. Tool "Cut":
- Performs the same function as "Delete" (point 7).
16. Tool "Copy":
- Copies the selected frame.
17. Tool "Paste Frames":
- Clicking the tool opens a selector with three values: "Paste to Left", "Paste to Right", "Merge";
- "Paste to Left" inserts a frame to the left of the selected frame;
- "Paste to Right" inserts a frame to the right of the selected frame;
- "Merge" combines selected frames.

Observations:
- Merging two similar frames with slight differences caused differing objects (in my case, white ovals) to merge and turn into white squares.

18. Tool "Play From First Frame":
- Clicking the tool makes the "Preview" window start playback from the first frame.

Observations:
- During this process, the "Play" tool remains inactive.

19. Tool "Pause":
- Clicking the tool makes the "Preview" window pause playback.

Observations:
- "Pause" automatically deactivates after being clicked;
- "Play From First Frame" deactivates after "Pause";
- "Play" activates after "Pause".

20. Tool "Play":
- Clicking the tool makes the "Preview" window resume playback.

Observations:
- "Play" automatically deactivates after being clicked;
- "Play From First Frame" activates after "Play";
- "Pause" activates after "Play".
