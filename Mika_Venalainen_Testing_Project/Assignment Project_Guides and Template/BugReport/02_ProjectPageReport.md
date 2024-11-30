# Bug Report: Typo in Project Creation Button

## Summary
The "Create blank project" button in the project creation page contains a typo: it displays "Create black project" instead of "Create blank project." This typo may confuse users and impact the user experience.

## Steps to reproduce
1. Navigate to the project creation page: [https://gitlab.com/projects/new#blank_project](https://gitlab.com/projects/new#blank_project).
2. Observe the button text for creating a new blank project.

## What is the current bug behavior?
The button displays the text "Create black project" instead of "Create blank project."

## What is the expected correct behavior?
The button should display "Create blank project" as intended.

## Relevant logs and/or screenshots
### Screenshot:
![Typo Screenshot](../Image/Bug_Project_create_blank.png)

## Possible fixes
The typo can be fixed by updating the button label text in the source code from "Create black project" to "Create blank project." The relevant file might be in the frontend repository, specifically in the localization or button component configuration.

## Whom do you report/Assign To/Tags
/label ~bug ~reproduced ~needs-investigation  
/cc @project-manager  
/assign @qa-tester  

## Priority
Minor
