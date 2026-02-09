# Documentation Testing - Session 1

## Goal:
- Check the documentation for structure and navigation.

## Notes and observations:

### 1. Content issue in documentation:
- Chapter "3. Tutorial" has sections "3-1. Prepare Canvas", "3-2. Paint", "3-3. Frame", and so on;
- Clicking on chapter "3. Tutorial" displays the same information as section "3-1. Prepare Canvas";
- However, chapter "4. Exposition of Screen", which has sections "4-1. Color Palette", "4-2. Frame", and so on, contains separate, unique content that does not duplicate information from other sections.

Impact:
- Logical navigation is disrupted;
- User loses overview of the chapter;
- Information is duplicated.

Severity: low.
Priority: minor.

Improvement suggestion:
- Change the content of chapter "3. Tutorial", for example, by adding hyperlinks to the subsections of chapter 3 instead of duplicating the information.

---

### 2. Missing/hidden section:
- Chapter "4. Exposition of Screen" contains an image with embedded navigation leading to 7 separate sections;
- In the left part of the documentation, the contents of chapter 4 consist of five sections: "4-1. Color Palette", "4-2. Frame", "4-3. Layer", "4-4. Preview", and "4-5. History";
- The sixth section in the image with embedded navigation leads to chapter "5. Paint Tools";
- The seventh section in the image with embedded navigation leads to section "4-5. Loupe", which is not displayed in the left documentation contents.

Evidences:
- Screenshots are located in the "Bugs/Documentation Testing Session1" directory;
- Screenshot names: "documentation_testing_session1_bug1.png", "documentation_testing_session1_bug2.png".

Impact:
- Logical navigation is disrupted;
- Documentation structure is disrupted;
- User loses sight of the hidden section;
- Numbering of the hidden section "4-5. Loupe" duplicates the numbering of section "4-5. History".

Severity: low.
Priority: medium.

Improvement suggestion:
- Add chapter "5. Paint Tools" as a subsection of chapter "4. Exposition of Screen".

---

### 3. Content issue in documentation:
- Chapter "6. Main Menu" has sections "6-1. File", "6-2. Edit", "6-3. View", and so on;
- Clicking on chapter "6. Main Menu" displays the same information as section "6-1. File".

Impact:
- Logical navigation is disrupted;
- User loses overview of the chapter;
- Information is duplicated.

Severity: low.
Priority: minor.

Improvement suggestion:
- Change the content of chapter "6. Main Menu", for example, by adding hyperlinks to the subsections of chapter 6 instead of duplicating the information.

---

### 4. Content issue in documentation:
- Chapter "9. Toolbar" has sections "9-1. Docking" and "9-2. Auto Hide";
- Clicking on chapter "9. Toolbar" displays the same information as section "9-1. Docking".

Impact:
- Logical navigation is disrupted;
- User loses overview of the chapter;
- Information is duplicated.

Severity: low.
Priority: minor.

Improvement suggestion:
- Change the content of chapter "9. Toolbar", for example, by adding hyperlinks to the subsections of chapter 9 instead of duplicating the information.

---

### Conclusion:
- No critical errors found;
- Several minor defects identified;
- Overall, the documentation is usable, but it can be improved for greater clarity.


---


## Additional notes (09.02.2026):

### 5. Missing/hidden section:
- Section "4-1. Color Palette" contains an image with embedded navigation leading to a separate page, which is not displayed in the left documentation contents.

Evidences:
- Screenshots are located in the directory "Bugs/Documentation Testing Session 1";
- Screenshot names: "documentation_testing_session1_bug3.png", "documentation_testing_session1_bug4.png".

Impact:
- Logical navigation is disrupted;
- Documentation structure is disrupted;
- User loses sight of the hidden section.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add the hidden page as a subsection of "4-1. Color Palette" so that the page with separate information is not lost to the user and is displayed in the left documentation contents.

---

### 6. Missing/hidden section:
- Section "4-2. Frame" contains an embedded hyperlink in the contents leading to a separate page titled "Frame's Properties", which is not displayed in the left documentation contents.

Evidences:
- Screenshots are located in the directory "Bugs/Documentation Testing Session 1";
- Screenshot names: "documentation_testing_session1_bug5.png", "documentation_testing_session1_bug6.png".

Impact:
- Logical navigation is disrupted;
- Documentation structure is disrupted;
- User loses sight of the hidden section.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add the hidden page as a subsection of "4-2. Frame" so that the page with separate information is not lost to the user and is displayed in the left documentation contents.

---

### 7. Missing/hidden section:
- Section "4-3. Layer" contains an embedded hyperlink in the contents leading to a separate page titled "Layer's Properties", which is not displayed in the left documentation contents.

Evidences:
- Screenshots are located in the directory "Bugs/Documentation Testing Session 1";
- Screenshot names: "documentation_testing_session1_bug7.png", "documentation_testing_session1_bug8.png".

Impact:
- Logical navigation is disrupted;
- Documentation structure is disrupted;
- User loses sight of the hidden section.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add the hidden page as a subsection of "4-3. Layer" so that the page with separate information is not lost to the user and is displayed in the left documentation contents.

---

### 8. Missing/hidden section:
- Chapter "8. Preferences" contains an embedded hyperlink in the contents leading to a separate page titled "Menus", which is not displayed in the left documentation contents.

Evidences:
- Screenshots are located in the directory "Bugs/Documentation Testing Session 1";
- Screenshot names: "documentation_testing_session1_bug9.png", "documentation_testing_session1_bug10.png".

Impact:
- Logical navigation is disrupted;
- Documentation structure is disrupted;
- User loses sight of the hidden section.

Severity: low.
Priority: minor.

Improvement suggestion:
- Move the contents of the hidden page into chapter "6. Main Menu", since the information in chapter "6. Main Menu" duplicates the information of section "6-1. File".
