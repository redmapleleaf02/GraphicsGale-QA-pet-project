# Documentation Testing - Session 3

## Goal:
- Verification of chapter "4. Exposition of Screen" and its sections against the actual behavior of the application.

## Notes and observations:

### 1. Section "4-1. Color Palette":

### 1-1. "Chooses Color":
- In section "4-1. Color Palette" there is a hyperlink inside an image that leads to information about colors;
- In the first part of this hyperlink there is a heading "Chooses Color", which contains the following information: "Drag&Drop with holding the Shift-key down Exchanges the order of colors. Colors of the image are not affected";
- Several attempts were made to change the order of colors while holding the "Shift" key, but nothing changed;
- More detailed information with step-by-step actions is missing.

Impact:
- The stated information does not correspond to reality.

Evidence:
- Screenshot with the stated information is located in the directory "Bugs/Documentation Testing Session3";
- Screenshot name: "documentation_testing_session3_bug1.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add more details and step-by-step actions for clearer and more understandable instructions.



### 1-2. "Chooses Color":
- The heading "Chooses Color" contains the following information: "Drag&Drop with holding the Control-key down. Copies the color. Colors of the image are affected when the image's format is 256 or less colors";
- Several attempts were made to copy a color while holding the "Ctrl" key, but nothing happened;
- More detailed information with step-by-step actions is missing.

Impact:
- The stated information does not correspond to reality.

Evidence:
- Screenshot with the stated information is located in the directory "Bugs/Documentation Testing Session3";
- Screenshot name: "documentation_testing_session3_bug2.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add more details and step-by-step actions for clearer and more understandable instructions.



### 1-3. Function "Uniform Color":
- This function has a description in the documentation, but step-by-step actions are missing for a complete picture and understanding of how the function works;
- Several attempts were made to use the "Uniform Color" function, but it was not possible to achieve the expected result;
- More detailed information with step-by-step actions is missing.

Impact:
- Difficulties arise in mastering this function.

Evidence:
- Screenshot with the stated information is located in the directory "Bugs/Documentation Testing Session3";
- Screenshot name: "documentation_testing_session3_bug3.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add more details and step-by-step actions for clearer and more understandable instructions.

---

### 2. Section "4-2. Frame":

### 2-1. Grammatical error:
- In section "4-2. Frame" there is the following sentence: "Plays a animation preview";
- It should be "Plays an animation preview".

Impact:
- Reduces the quality of the documentation;
- Affects professional appearance.

Evidence:
- Screenshot with the stated information is located in the directory "Bugs/Documentation Testing Session3";
- Screenshot name: "documentation_testing_session3_bug4.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Correct the grammatical error.



### 2-2. Frame's Properties. Tags "%framenumber_zero%" and "%frameindex_zero%":
- In section "4-2. Frame" there is a hyperlink leading to a page titled "Frame's Properties";
- On this page there is the following information: "Tag: %framenumber_zero%. Description: The zero-padded frame number beginning with 1. Example: Walk_01, Walk_02";
- Separately, there is the following information: "Tag: %frameindex_zero%. Description: The zero-padded frame number beginning with 0. Example: Walk_00, Walk_01";
- When using the above tags in the application, the actual result does not match the examples given in the documentation.

Impact:
- The stated information does not correspond to reality.

Evidence:
- Screenshots with the stated information are located in the directory "Bugs/Documentation Testing Session3";
- Screenshot names: "documentation_testing_session3_bug5.png", "documentation_testing_session3_bug6.png", "documentation_testing_session3_bug7.png", "documentation_testing_session3_bug8.png", "documentation_testing_session3_bug9.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Fix the inconsistency.



### 2-3. Frame's Properties. Parameter "Delay" values:
- On the page "Frame's Properties" there is the following information: "Delay: The duration of showing a image. The measure is 1/100sec., 1/100sec., or 1/1000sec";
- In the application, the parameter "Delay" has the following values: "1/60 sec. (for Video-Game)", "1/100 sec. (for GIF)", "1/1000 sec.".

Impact:
- The stated information does not correspond to reality.

Evidence:
- Screenshots with the stated information are located in the directory "Bugs/Documentation Testing Session3";
- Screenshot names: "documentation_testing_session3_bug10.png", "documentation_testing_session3_bug11.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Correct the inconsistency by rewriting the text in the documentation.



### 2-4. Grammatical error:
- On the page "Frame's Properties" there is the following sentence: "The duration of showing a image";
- It should be "The duration of showing an image".

Impact:
- Reduces the quality of the documentation;
- Affects professional appearance.

Evidence:
- Screenshot with the stated information is located in the directory "Bugs/Documentation Testing Session3";
- Screenshot name: "documentation_testing_session3_bug10.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Correct the grammatical error.
