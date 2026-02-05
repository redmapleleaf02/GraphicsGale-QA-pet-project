# GraphicsGale - Exploratory Testing (Session 4)

## Goal:
- Try out and test tools related to layers.

## Environment:
- OS: Windows 11;
- Application: GraphicsGale;
- Version: 2.10.01.

## Initial setup:
- File: exploratory_testing_gif1.gal.

## Notes and observations:
1. Opened the application and opened the file named "exploratory_testing_gif1.gal";
2. Clicked on the tool with an icon of two sheets of paper and a plus sign in the corner, named "Add":
- A modal window titled "Properties" opened with parameters "Name", "Transparency", "Opacity" and buttons "OK" and "Cancel";
- In the "Name" parameter, the name of the next layer is automatically entered. In this case, the "Name" parameter contained the value "Layer2";
- In the "Transparency" parameter there is a single checkbox named "Transparent Color" and a rectangle with a specific color below the checkbox. Checked the box and selected white color;
- In the "Opacity" parameter there is a scale, and below the scale there is a numeric field with a percentage indicator next to it. I do not fully understand what this parameter does, but for experiment set the value to 179 (the percentage indicator changed to 70.2%);
- The "Cancel" button closes the modal window without any changes in the application;
- The "OK" button creates a new layer named "Layer2" in the "Layer" interface;
- Drew a sun object in "Layer2".

Observations:
- In the "Layer" interface, "Layer2" appeared above "Layer1";
- Before interacting with the "Add" tool, the tools "Delete", "Combine Down", "Combine Visible", "Previous Layer" and "Next Layer" were unavailable;
- After interacting with the "Add" tool, the tools "Delete", "Combine Down", "Combine Visible", "Previous Layer" and "Next Layer" became available;
- After interacting with the "Add" tool, I began to experience difficulty understanding the functionality of this tool;
- Noticed that the tool name duplicates the tool name from the animation and frames section (point 4 of "exploratory_testing3.md").

Improvement suggestions:
- Rename the tool (from the layers section) "Add" to "Add Layer";
- Rename the tool (from the frames section) "Add" to "Add Frame".

3. Tool "Duplicate":
- Opens the same modal window as the "Add" tool, with the same parameters and buttons;
- Only the "Name" parameter changes (the current layer name gets the prefix "Copy_");
- The "Cancel" button closes the modal window without any changes in the application;
- The "OK" button creates a new layer named "Copy_Layer2" in the "Layer" interface.

Observations:
- The tool name duplicates the tool name from the animation and frames section (point 6 of "exploratory_testing3.md");
- When creating layers with long names, the mini‑previews of the layers shift sideways in the small "Layer" interface;
- The "Layer" interface cannot be expanded or resized. Mini‑previews can only be viewed using the bottom and right scrollbars.

Improvement suggestions:
- Rename the tool (from the layers section) "Duplicate" to "Duplicate Layer";
- Rename the tool (from the frames section) "Duplicate" to "Duplicate Frame";
- Add the ability to expand the "Layer" interface window.

4. Tool "Delete":
- Opens a modal window with the message "Current Layer will be deleted" and buttons "OK" and "Cancel";
- The "Cancel" button closes the modal window without any changes in the application;
- The "OK" button deletes the selected layer.

Observation:
- The tool name duplicates the tool name from the animation and frames section (point 7 of "exploratory_testing3.md").

Improvement suggestions:
- Rename the tool (from the layers section) "Delete" to "Delete Layer";
- Rename the tool (from the frames section) "Delete" to "Delete Frame".

5. Tool "Combine Down":
- Opens a modal window titled "Combine Down" with two checkboxes ("Delete Original Layers" and "Make Alpha Channel") and two buttons ("OK" and "Cancel");
- The "Cancel" button closes the modal window without any changes in the application;
- If both checkboxes are left unchecked and "OK" is clicked, a new layer named "Combined" appears, merging objects from previous layers;
- Repeating the previous step creates identical layers without changes in names or content;
- If only "Delete Original Layers" is checked, the layer below the current one is deleted;
- If only "Make Alpha Channel" is checked, a new layer named "Combined" appears;
- If both checkboxes are checked, the layer below the current one is deleted.

Observation:
- The effects and results of the "Make Alpha Channel" checkbox are unclear.

6. Tool "Combine Visible":
- Opens a modal window titled "Combine Visible" with identical checkboxes and buttons as "Combine Down";
- If both checkboxes are left unchecked and "OK" is clicked, a new layer named "Combined" appears, merging objects from previous layers;
- Repeating the previous step creates identical layers without changes in names or content;
- If only "Delete Original Layers" is checked, all layers are deleted;
- If only "Make Alpha Channel" is checked, a new layer named "Combined" appears;
- If both checkboxes are checked, all layers are deleted.

Observations:
- The effects and results of the "Make Alpha Channel" checkbox are unclear;
- Creating multiple layers with the same name "Combined" makes it difficult to navigate the "Layer" interface;
- Using "Combine Visible" with empty checkboxes causes the first bottom layer to shift to the right if the bottom scrollbar is moved fully to the right;
- Repeating the action causes the bottom layer to shift further right each time (this behavior was captured in screenshots and saved in the repository under names "exploratory_testing_session4_bug1", "exploratory_testing_session4_bug2", "exploratory_testing_session4_bug3", "exploratory_testing_session4_bug4" and "exploratory_testing_session4_bug5");
- This behavior also repeats when using "Combine Down";
- The bottom layer returns to its original position if the bottom scrollbar is moved fully left and then "Combine Visible" or "Combine Down" is used with "OK" clicked in the modal window.

Additional observation:
- This behavior of the bottom layer also occurs when clicking the "Move Up" and "Move Down" buttons inside the "Layer" interface.

7. Tool "Previous Layer":
- Moves down one layer;
- Selects the layer below the current one;
- Allows navigation through the list of layers in the "Layer" interface.
8. Tool "Next Layer":
- Moves up one layer;
- Selects the layer above the current one;
- Allows navigation through the list of layers in the "Layer" interface.
9. Tool "Properties":
- Opens the same modal window with the same parameters and buttons as the "Add" tool (point 2);
- Allows editing parameters of the selected layer;
- The "Cancel" button closes the modal window without any changes in the application or layers;
- The "OK" button applies the changed parameter values to the selected layer.

Observation:
- The tool name duplicates the tool name from the animation and frames section (point 14 of "exploratory_testing3.md").

Improvement suggestions:
- Rename the tool (from the layers section) "Properties" to "Layer Properties";
- Rename the tool (from the frames section) "Properties" to "Frame Properties".

10. Saved the current image named "exploratory_testing_image_session4" in gal and png formats.
