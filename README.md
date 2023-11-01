# SWE642

This project is an extension of a previous assignment, aimed at enhancing a web page using various web technologies, including JavaScript, Bootstrap, cookies, and Ajax implementation. Below are the specific details and instructions for the assignment.

## Assignment Overview
The objective of this assignment is to improve a web page and provide an enriched user experience by implementing the following features and functionalities:

### Navigation Bar Enhancement:
- Redesigned the webpage to incorporate a Bootstrap navigation bar with a medium to dark background.
- Implement tab functionality, allowing users to easily switch between different sections of the page.

### Cookie and Greetings Implementation:
- On the Student Survey Form Page, used cookies to store a user's information, including their name.
- Displaying a personalized greeting message based on the time of day (e.g., "Good Morning," "Good Afternoon," or "Good Evening").
- If the stored name in the cookie differs from the user's input, provided a hyperlink to allow the user to update their name, and reset the cookie.

### Survey Form Extension and Data Computation:
- Added an additional text box labeled "Data" and two output fields labeled "Average" and "Maximum" on the Student Survey Form.
- Require the user to input ten comma-separated numbers ranging from 1 through 100 in the "Data" field.
- Developed JavaScript functions to calculate the average and maximum of the numbers entered in the "Data" field.
- Automatically computes and populates the Average and Maximum output fields when the user finishes entering the ten numbers.
- Displays an error message if the "Data" field does not contain at least ten valid comma-separated values between 1 and 100.

### Form Validation Event Handling:
- Create an event handler to validate form inputs when the user clicks the submit button on the Survey Form.
- Validate the following criteria:
  - Name: Should contain only alphabetic characters.
  - Address: Should contain appropriate numeric, alphabetic, or alphanumeric characters.
  - Ensure at least two checkboxes are checked.
  - Verify that a radio button option is selected.
  - Validate the email address format.
- If any form field does not meet the validation criteria, display a consolidated error message using a window dialog box.
- Clear only the fields with errors on alert, not all fields.
- Include a Reset button to clear all form contents.

### Ajax and JSON Integration:
- Implement Ajax functionality to automatically populate the "City" and "State" fields based on the entered ZIP code.
- Retrieve a JSON file containing valid ZIP codes, city, and state information from the server using an Ajax call.
- Compare the entered ZIP code against the data in the JSON file and populate the "City" and "State" fields if a match is found.
- Display an "invalid ZIP" message if the entered ZIP code is not found in the JSON data.
- Register an event handler for the "onblur" event associated with the ZIP code input field.

## Deployment
To view the CS Department Information Page and Survey Form, follow the link below:
- Home Page: [Home Page](https://dummysai.s3.amazonaws.com/myblog_akula.html)
- Survey Form: [Survey Form](https://dummysai.s3.amazonaws.com/survey_akula.html)
