## Summary (Summarize the bug encountered concisely)

The "Save" button is not functioning properly on the project creation page.

## Steps to reproduce     

1. Navigate to the project creation page.
2. Fill in the required project details.
3. Click on the "Save" button.

## What is the current bug behavior?

After clicking the "Save" button, nothing happens. The project is not created, and there is no indication of any action being taken.

## What is the expected correct behavior?

After clicking the "Save" button, the project creation process should begin, and the user should be redirected to the project's dashboard with a success message confirming the creation of the project.

     
## Relevant logs and/or screenshots
No errors in console and the page just wouldn't load

## Possible fixes

1. Check browser is working.
2. Check the JavaScript console for any errors related to the button functionality.
3. Ensure that the button's onclick event is properly bound to the function responsible for project creation.
4. Verify the backend logic to ensure that project creation requests are being processed correctly.

## Whom do you report/ Assign To/ Tags

Reported by: Matti Simpson
Assigned to: Matti Simpson
Tags: ProjectCreation, ButtonFunctionality, Bug


## Priority

HIGH
