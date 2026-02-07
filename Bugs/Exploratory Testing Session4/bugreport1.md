# GraphicsGale - Bug Report №1

## Title
- The bottom layer shifts to the right in the "Layer" interface when using "Combine Visible" or "Combine Down" with empty checkboxes

## Description:
- The bug was found during the fourth exploratory testing session. The file "exploratory_testing_gif1.gal" was used. The file is located in the "Media/Source" directory.

## Environment:
- OS: Windows 11;
- Version: 2.10.01.

## Steps:
1. Open the application and create a new canvas;
2. Click on the "Add" tool in the layers section and create two layers;
3. Move the bottom scrollbar of the "Layer" interface fully to the right;
4. Click on the "Combine Down" or "Combine Visible" tool with both checkboxes unchecked.

## Expected Result:
- A fourth layer named "Combined" appears in the "Layer" interface. All layers remain aligned without any shifting in the list.

## Actual Result:
- A fourth layer named "Combined" appears in the "Layer" interface. The bottom layer shifts to the right.

## Evidence:
- Located in the "Bugs/Exploratory Testing Session4" directory;
- File names:
- exploratory_testing_session4_bug1.png;
- exploratory_testing_session4_bug2.png;
- exploratory_testing_session4_bug3.png;
- exploratory_testing_session4_bug4.png;
- exploratory_testing_session4_bug5.png.
