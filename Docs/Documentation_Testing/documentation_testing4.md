# Documentation Testing - Session 4

## Goal:
- Verification of chapter "5. Paint Tools" against the actual behavior of the application.

## Notes and observations:

### 1. Tool "Lasso". Lack of clarification in documentation:
- Documentation states: "To select area by polygon, click at the point in polygon and right-click at the last point. Press ESC key to cancel the last point";
- Documentation does not clarify that ESC works only during polygon construction, before finishing with right-click.

Impact:
- Causes user misunderstanding;
- Creates false expectations.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification: "ESC cancels the last point before finishing the polygon with right-click".

---

### 2. Tool "Connect Line". Lack of clarification in documentation:
- Documentation states: "To draw connected lines, keep on clicking and right-click at the last point. Press ESC key to cancel the last point";
- Documentation does not clarify that ESC works only during line construction, before finishing with right-click.

Impact:
- Causes user misunderstanding;
- Creates false expectations.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification: "ESC cancels the last point before finishing connected lines with right-click".

---

### 3. Tool "Spline Curve". Lack of clarification in documentation:
- Documentation states: "Keep on clicking and right-click at the last point. Press ESC key to cancel the last point";
- Documentation does not clarify that ESC works only during curve construction, before finishing with right-click.

Impact:
- Causes user misunderstanding;
- Creates false expectations.

Severity: low.
Priority: minor.

Improvement suggestion:
- Add clarification: "ESC cancels the last point before finishing curved lines with right-click".

---

### 4. Tool "Draw Text". Lack of detailed information:
- Documentation states: "Draw Text: Click to draw text. Click and drag the text to move it";
- When using the tool, a "Draw Text" window appears with following parameters: "Text", "History", "Preset", "Font", "Size", "Styles", "Border", "Pitch", "Line Space(J)", "Alignment", "Option" — none of which are explained anywhere in the documentation.

Impact:
- Documentation is incomplete;
- User is forced to explore parameters and details independently.

Evidence:
- Screenshots are located in the directory "Bugs/Documentation Testing Session4";
- Screenshot names: "documentation_testing_session4_bug1.png", "documentation_testing_session3_bug2.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Add detailed information about the tool and the parameter window.

---

### 5. Tool "AntiAlias". Grammatical error:
- In chapter "5. Paint Tools" there is the following sentence: "A image will be built using neutral colors when the AntiAlias is ON";
- Correct form: "An image will be built using neutral colors when the AntiAlias is ON".

Impact:
- Reduces the quality of the documentation;
- Affects professional appearance.

Evidence:
- Screenshot is located in the directory "Bugs/Documentation Testing Session4";
- Screenshot name: "documentation_testing_session4_bug3.png".

Severity: low.
Priority: minor.

Improvement suggestion:
- Correct the grammatical error.
