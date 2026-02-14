# GraphicsGale - Bug Report №3

## Title:
- The numbers "00" are not displayed in the frame name when selecting the tag "%frameindex_zero%".

## Description:
- The bug was found during the third documentation testing session.

## Environment:
- OS: Windows 11;
- Version: 2.10.01.

## Steps:
1. Open the application and create a new canvas;
2. Open the "Properties" modal window by clicking on "..." in the frames section;
3. In the "Name" parameter, select the value "%frameindex_zero%";
4. Click the "OK" button.

## Expected result:
- The frame name changes from "1" to "00".

## Actual result:
- The frame name changed from "1" to "0". Another digit "0" was not added to the name.

## Severity:
- Low.

## Priority:
- Minor.

## Evidence:

### Screenshot 1:
![Bug Screenshot 1](../Bugs/Documentation%20Testing%20Session3/documentation_testing_session3_bug5.png)

### Screenshot 2:
![Bug Screenshot 2](../Bugs/Documentation%20Testing%20Session3/documentation_testing_session3_bug12.png)

### Screenshot 3:
![Bug Screenshot 3](../Bugs/Documentation%20Testing%20Session3/documentation_testing_session3_bug13.png)

- Screenshots are located in the directory "Bugs/Documentation Testing Session3";
- File names:
- "documentation_testing_session3_bug5.png";
- "documentation_testing_session3_bug12.png";
- "documentation_testing_session3_bug13.png".
