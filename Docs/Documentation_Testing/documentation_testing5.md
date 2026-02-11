# Documentation Testing - Session 5

## Goal:
- Verification of chapter "6. Main Menu" and its items for consistency with actual application behavior.

## Notes and observations:

### 1. Section "6-1. File":

### 1-1. Grammar mistake:
- In section "6-1. File" there is the following sentence: "Only current frame is saved when a image is saved as a file format except GAL, GIF, ANI, and AVI";
- It should be: "Only current frame is saved when an image is saved as a file format except GAL, GIF, ANI, and AVI".

Impact:
- Reduces documentation quality;
- Affects professional look.

Evidence:
- Screenshot is located in directory "Bugs/Documentation Testing Session5";
- Screenshot name: "documentation_testing_session5_bug1.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Fix grammar mistake.

---

### 2. Section "6-3. View":

### 2-1. Gap in documentation:
- In section "6-3. View" functions of the "View" menu are described, but some functions that exist in the actual application ("Selected Line", "Frame", "Layer", "Toolbar" and others) are not described in section "6-3. View".

Impact:
- Creates inconsistency between documentation and application;
- Reduces documentation completeness.

Evidence:
- Screenshots are located in directory "Bug/Documentation Testing Session5";
- Screenshot names: "documentation_testing_session5_bug2.png", "documentation_testing_session5_bug3.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add information about mentioned functions.

---

### 3. Section "6-4. Image":

### 3-1. Missing details in documentation:
- In section "6-4. Image" functions of the "Image" menu are described, but functions are described briefly, while the following functions have modal windows that are not mentioned in documentation;
- Functions with modal windows: "Rotate...", "Scroll...", "Slope...", "Adjust Color...", "Effect...";
- Same situation exists in section "6-5. All Frames".

Impact:
- Reduces documentation completeness;
- Risk of errors during usage.

Evidence:
- Screenshot is located in directory "Bugs/Documentation Testing Session5";
- Screenshot name: "documentation_testing_session5_bug4.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add more detailed information about mentioned functions and their modal windows with parameters.



### 3-2. Function "Rotate by 90 Degrees". Gap in documentation:
- In the application in the "Image" menu there is a function "Rotate by 90 Degrees";
- In documentation there is no information about this function.

Impact:
- Reduces documentation completeness.

Evidence:
- Screenshots are located in directory "Bug/Documentation Testing Session5";
- Screenshot names: "documentation_testing_session5_bug5.png", "documentation_testing_session5_bug6.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add information about "Rotate by 90 Degrees" function in documentation.



### 3-3. Grammar mistakes:
- In section "6-4. Image" there are sentences with small grammar mistakes.

Fragments of sentences with grammar mistakes:
- "Sets a opaque";
- "Select a image";
- "Inverts a alpha blend value";
- "Deletes a alpha";
- "Inverts a alpha channel of current layer";
- "Duplicates a alpha channel".

Impact:
- Reduces documentation quality;
- Affects professional look.

Evidence:
- Screenshot is located in directory "Bug/Documentation Testing Session5";
- Screenshot name: "documentation_testing_session5_bug7.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Fix grammar mistakes.

---

### 4. Section "6-5. All Frames":

### 4-1. Function "Remove Border...". Gap in documentation:
- In the application in the "All Frames" menu there is a function "Remove Border...";
- In documentation there is no information about this function.

Impact:
- Reduces documentation completeness.

Evidence:
- Screenshots are located in directory "Bug/Documentation Testing Session5";
- Screenshot names: "documentation_testing_session5_bug8.png", "documentation_testing_session5_bug9.png", "documentation_testing_session5_bug10.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add information about "Remove Border..." function in documentation.



### 4-2. Function "Fit to Image". Name inconsistency in documentation:
- In documentation in section "6-5. All Frames" there is description of function "Fit";
- In the application this function is called "Fit to Image".

Impact:
- Creates inconsistency in function name.

Evidence:
- Screenshots are located in directory "Bug/Documentation Testing Session5";
- Screenshot names: "documentation_testing_session5_bug11.png", "documentation_testing_session5_bug12.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Option 1: Rename function in application from "Fit to Image" to "Fit";
- Option 2: Rename function in documentation from "Fit" to "Fit to Image".



### 4-3. Functions "Enlarge Canvas..." and "Resample...". Missing details in documentation:
- In section "6-5. All Frames" there is short description of functions "Enlarge Canvas..." and "Resample...", but there is no information about their modal windows.

Impact:
- Reduces documentation completeness;
- Risk of errors during usage.

Evidence:
- Screenshots are located in directory "Bug/Documentation Testing Session5";
- Screenshot names: "documentation_testing_session5_bug13.png", "documentation_testing_session5_bug14.png", "documentation_testing_session5_bug15.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add more detailed information about mentioned functions and their modal windows with parameters.

---

### 5. Section "6-6. Capture":

### 5-1. Gap in documentation:
- In section "6-6. Capture" functions of the "Capture" menu are described: "Full Screen", "Window", "HotKey Setup...";
- But documentation does not mention that when using "Full Screen" and "Window" the application minimizes, and then a new canvas with captured image is created;
- This behavior can be perceived by user as unexpected or wrong, because documentation describes only final result ("Copies an image") but not intermediate action.

Impact:
- Creates inconsistency between documentation and actual application behavior;
- User may think program "crashed" or "disappeared" when it minimizes;
- Reduces documentation value as reference material, because it does not reflect real UX.

Evidence:
- Screenshot and video are located in directory "Bug/Documentation Testing Session5";
- File names: "documentation_testing_session5_bug16.png", "documentation_testing_session5_bug17.mp4".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification in documentation that when using "Full Screen" and "Window" the application minimizes to perform capture, after which a new canvas with image is created.

---

### 6. Section "6-7. Window":

### 6-1. Functions "Tile Horizontal" and "Tile Vertical". Lack of detailed information:
- In section "6-7. Window" functions "Tile Horizontal" and "Tile Vertical" are described briefly, but there is no clarification that they work only when more than one window is open. This creates lack of clarity and may lead user to think functions do not work when only one canvas is open.

Impact:
- Risk of misunderstanding. User with only one canvas may think functions do not work, because there is no visual effect;
- Reduces documentation clarity. The phrase "Tiles windows horizontal/vertical" is formally correct, but too short and does not explain condition (multiple windows).

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification that functions work only when more than one window (canvas) is open;
- Add note: "If only one canvas is open, there will be no visual effect".



### 6-2. Function "Arrange Icons". Lack of detailed information:
- In section "6-7. Window" function "Arrange Icons" is described very briefly ("Arranges icons"), without explanation that it refers to arranging minimized windows (icons) inside MDI interface (Multiple Document Interface). This reduces clarity and may confuse user.

Impact:
- Risk of misunderstanding;
- Reduces documentation value as reference material.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification in documentation that function arranges minimized windows (icons) inside application workspace.

---

### 7. Menu "Help". Gap in documentation:
- In the application there is a menu called "Help";
- In documentation there is no information about this menu.

Impact:
- Reduces documentation completeness;
- User does not get information about update function, help contents, and program details.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add in documentation section "6-8. Help" with information about functions of this menu.
