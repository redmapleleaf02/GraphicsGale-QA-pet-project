# GraphicsGale - Exploratory Testing (Session 2)

## Goal:
Explore basic tools and commands to understand application behaviour and usability.

## Environment:
- OS: Windows 11;
- Application: GraphicsGale;
- Version: 2.10.01.

## Initial setup:
- Canvas size: 256x256;
- Color mode: 32bit (Full color + Alpha channel).

## Notes and observations:
1. Opened the application and created a new canvas 256x256 with parameter "32bit (Full color + Alpha channel)";
2. Tried the "Onion Skin" tool and did not fully understand what it does or how it works. Without prior training, the tool is not intuitive;
3. Tried the "Snap" tool and also did not understand its function or behaviour. It is likely explained in the documentation, but at the moment the application is being tested using the black-box method;
4. Grid:
- Clicking the tool displays the canvas with a grid;
- Clicking the tool again removes the grid and restores the canvas to its normal view.
5. Custom-Grid:
- Clicking the tool opens a selector (dropdown list) with the following options: "None", "8x8", "16x16", "32x32", "64x64", "Input...", "Setup..." and "Show Custom-Grid";
- Selecting options from "8x8" to "64x64" displays the canvas with blue grid cells of the specified size;
- In combination with the "Snap" and "Pen" tools, it is possible to draw straight lines within the grid cells or diagonally;
- Selecting "Input..." opens a modal window with tabs "Grid Size" and "Divided Number", where grid parameters can be customized;
- Selecting "Setup..." opens a modal window with standard grid sizes ("8x8", "16x16", "32x32", "64x64") and buttons "Add", "Edit", "Delete", "OK";
- Clicking "Add" allows adding custom grid sizes, which then appear in the "Custom-Grid" selector after confirmation with "OK".
6. Magnification:
- Clicking the tool opens a selector with values "10%", "20%", "30%", "40%", "50%", "60%", "70%", "80%", "90%", "100%", "200%", "300%", "400%", "500%", "600%", "700%", "800%", "900%", "1000%", "1500%", "2000%", "2500%", "3000%", "3500%", "4000%" and "Setup...";
- Selecting "Setup..." opens a modal window with the listed percentages and buttons "Add", "Edit", "Delete", "Default", "Clear", "OK";
- Clicking "Add" opens a modal window with parameter "Magnification(%)" and buttons "OK" and "Cancel", allowing custom zoom values;
- Attempting to enter "10000" or "100000" results in "8000%" (values above 8000% are not allowed);
- Attempting values below "10%" (9% to 0%) disables the "OK" button;
- Attempting negative values (e.g., "-500%") results in a duplicate "10%" entry (values below 10% are not allowed);
- Deleting a value prompts a confirmation dialog: "Would you like to delete selected item?" with "OK" and "Cancel";
- Added and deleted values are reflected in the selector.
7. Copy (Ctrl+C):
- Copies the current canvas image, which can be pasted into messages (e.g., WhatsApp) or other editors (e.g., Paint);
- Enables interaction with tools previously unavailable: "Paste (Ctrl+V)" and "Paste New Image";
- After a few minutes, "Paste (Ctrl+V)" and "Paste New Image" become deactivated.
8. Paste (Ctrl+V):
- Inserts the copied image onto the current canvas;
- Unlike MS Paint, where pasted content fully covers the underlying image, in GraphicsGale the pasted image blends as a layer.
9. Paste New Image:
- Creates a new window and canvas with the copied image.
10. Undo (Ctrl+Z):
- Cancels the last performed action;
- Returns to the previous state;
- Not available if no prior actions were performed.
11. Redo (Ctrl+Y):
- Repeats an action previously undone with Undo;
- Restores steps that were cancelled earlier;
- Not available if there are no undone actions to restore.
12. Save (Ctrl+S):
- On first use with a new canvas, the tool opens a "Save" modal window to choose location, filename and file type;
- Supports multiple formats: "Gale (.gal)", "Bitmap (.bmp)", "Device Independent Bitmap (.dib)", "ICON (.ico)", "Cursor (.cur)", "Animated Cursor (.ani)", "JPEG (.jpg; .jpeg)", "GIF (.gif)", "PNG (.png)", "TGA (.tga)", "TIFF (.tif; .tiff)", "AVI (.avi)";
- On subsequent use, saves automatically without showing the modal window.
13. Browse:
- Opens a separate desktop application "GaleBrowser ver.2.09.00";
- Allows browsing user directories, subdirectories and their files with the formats listed in point 12.
14. Open (Ctrl+O):
- Opens a modal window with directories, subdirectories and files;
- Allows opening files with the formats listed in point 12.
15. New (Ctrl+N):
- Opens a "New" dialog to set canvas size (height and width) and choose colour mode: "1bit(2colors)", "4bit(16colors)", "8bit(256colors)", "15bit(32000colors)", "16bit(64000colors)", "24bit(Full color)" and "32bit(Full color + Alpha channel);
- The maximum canvas size: "9999x9999x24". The application does not allow larger values, even if user enters "100000" for each parameter;
- The minimum canvas size: "1x1x24". The application does not allow smaller values, even with negative input.
