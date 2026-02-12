# Documentation Testing - Session 6

## Goal:
- Verification of chapters "7. Save Options", "8. Preferences", and "9. Toolbar" against the actual application.

## Notes and observations:

### 1. Chapter "7. Save Options":

### 1-1. GIF. Option "Comment". Documentation gap:
- In chapter "7. Save Options" the following information is provided regarding the "Comment" option of the GIF format: "Attaches a comment to a file. It has no effect on an image";
- The documentation does not clarify that in order to view the written comment, the GIF file must be opened in special tools that read GIF metadata.

Impact:
- Risk of misunderstanding, as the user does not receive clarification on where exactly the comment can be viewed.

Evidence:
- Screenshot is located in directory "Bugs/Documentation Testing Session6";
- Screenshot name: "documentation_testing_session6_bug1.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification that the comment is stored in GIF metadata and is not displayed when viewing the image, and that a special tool is required to view the comment.



### 1-2. File format "AVI". Documentation gap:
- The application includes the "AVI" format for saving;
- In chapter "7. Save Options" this format is not mentioned, although other formats are listed (BMP, DIB, ICO, CUR, ANI, JPG, GIF, PNG, TGA, TIF).

Impact:
- Reduces documentation completeness;
- User does not receive information about AVI saving options.

Evidence:
- Screenshots are located in directory "Bugs/Documentation Testing Session6";
- Screenshot names: "documentation_testing_session6_bug2.png", "documentation_testing_session6_bug3.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add description of AVI format and its options to chapter 7.

---

### 2. Chapter "8. Preferences":

### 2-1. Spelling error:
- In chapter "8. Preferences" the following sentence appears: "Doesn't show the dialog box in adding a frmae or duplicating a frame";
- The word "frame" is misspelled as "frmae".

Impact:
- Reduces documentation quality;
- Affects professional appearance.

Evidence:
- Screenshot is located in directory "Bugs/Documentation Testing Session6";
- Screenshot name: "documentation_testing_session6_bug4.png".

Severity: trivial.
Priority: trivial.

Improvement suggestion:
- Correct the spelling error.



### 2-2. "ColorPalette". Formatting/style error:
- In chapter "8. Preferences" there is a section titled "ColorPalette";
- The title lacks a space between two words;
- It should be "Color Palette".

Impact:
- Reduces documentation quality;
- Affects professional appearance.

Evidence:
- Screenshot is located in directory "Bugs/Documentation Testing Session6";
- Screenshot name: "documentation_testing_session6_bug5.png".

Severity: trivial.
Priority: trivial.

Improvement suggestion:
- Correct the formatting.



### 2-3. Style inconsistency between documentation and application:
- In chapter "8. Preferences" all functions are written in one style, while in the application they are written in another;
- Documentation: "Fit window when magnifying";
- Application: "Fit Window When Magnifying".

Impact:
- Creates stylistic inconsistency in function names;
- May confuse users, though does not affect functionality.

Evidence:
- Screenshots are located in directory "Bugs/Documentation Testing Session6";
- Screenshot names: "documentation_testing_session6_bug6.png", "documentation_testing_session6_bug7.png".

Severity: trivial.
Priority: trivial.

Improvement suggestion:
- Establish a unified formatting style for both documentation and application.



### 2-4. Function name mismatch between documentation and application:
- In chapter "8. Preferences", section "View", the documentation describes a function named "Auto zoom on opening";
- In the application, the function is named "Auto Zoom in Opening File".

Impact:
- Creates inconsistency between names of the same function;
- Reduces clarity and consistency of terminology;
- May confuse users.

Evidence:
- Screenshots are located in directory "Bugs/Documentation Testing Session6";
- Screenshot names: "documentation_testing_session6_bug8.png", "documentation_testing_session6_bug9.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Rename the function in documentation from "Auto zoom on opening" to "Auto Zoom in Opening File".



### 2-5. Documentation gap:
- In the "Preferences" modal window, under the "View" tab, there is a function "Loop the first and the last";
- In documentation, this function is not mentioned.

Impact:
- Reduces documentation completeness.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add information about the "Loop the first and the last" function in the "View" section.



### 2-6. Function name mismatch between documentation and application:
- In chapter "8. Preferences", section "Color Palette", documentation describes a function named "Show Color Data";
- In the application, the function is named "Show Balloon Tip with Color Value".

Impact:
- Creates inconsistency between names of the same function;
- Reduces clarity and consistency of terminology;
- May confuse users.

Evidence:
- Screenshots are located in directory "Bugs/Documentation Testing Session6";
- Screenshot names: "documentation_testing_session6_bug10.png", "documentation_testing_session6_bug11.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Rename the function in documentation from "Show Color Data" to "Show Balloon Tip with Color Value".



### 2-7. Tab name mismatch between documentation and application:
- In chapter "8. Preferences" there are sections titled "Loading" and "Saving";
- In the application, the corresponding tabs in the "Preferences" modal window are named "Load" and "Save".

Impact:
- Reduces consistency of terminology.

Evidence:
- Screenshots are located in directory "Bugs/Documentation Testing Session6";
- Screenshot names: "documentation_testing_session6_bug12.png", "documentation_testing_session6_bug13.png".

Severity: trivial.
Priority: trivial.

Improvement suggestion:
- Align tab names between documentation and application (either update documentation to match the application, or vice versa).
