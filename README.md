Manual Test Cases and Bug Reporting Guide for DemoQA Website

Welcome to the Manual Test Cases and Bug Reporting Guide for the DemoQA website. 
This guide provides instructions on writing effective manual test cases and reporting bugs for the DemoQA website. 
Following these guidelines will help ensure the quality and reliability of the website.

Manual Test Cases
Writing Test Cases

When writing manual test cases, follow these best practices:

Title and Description: Provide a clear and concise title for the test case. Include a brief description of the functionality being tested.

Preconditions: Specify any necessary preconditions, such as logged-in user, specific data, or system configurations.

Test Steps: Outline the steps to be performed in a sequential manner. Be specific and include all necessary details.

Expected Results: Clearly define the expected outcome or result of each step. This should include what you expect to see on the screen or any specific messages.

Test Data: If the test case requires specific test data, mention it clearly.

Cleanup Steps: Provide steps to return the system to a stable state after the test, especially if the test involves creating, updating, or deleting data.

Example Test Case:
Title: Verify User Registration Functionality

Description: This test case verifies the registration functionality of the DemoQA website.

Preconditions:

Access to the DemoQA registration page.
Test Steps:

Navigate to the registration page.
Enter valid user details (username, email, password).
Click on the registration button.
Verify the user is redirected to the login page.

Expected Results:
User should be registered successfully and redirected to the login page.

Bug Reporting
Writing Bug Reports

When reporting bugs, provide detailed information to help developers understand and fix the issue:

Title: Provide a descriptive and concise title summarizing the issue.

Description: Include a detailed description of the problem encountered. Mention the steps to reproduce the issue, including any specific input, data, or configurations used.

Expected results: Describe what you expected to happen when performing the steps.

Actual results: Explain what actually happened, including any error messages, unexpected outcomes, or issues observed.

Screenshots/Attachments: If applicable, attach screenshots or videos that illustrate the problem.

Environment: Provide information about the browser, operating system, and any other relevant details.

Example Bug Report:
Title: Error When Submitting Contact Form

Description: When attempting to submit the contact form on the DemoQA website, an error message is displayed, and the form submission fails.

Steps to Reproduce:

Navigate to the "Contact Us" page.
Fill in the required fields: Name, Email, Message.
Click on the "Submit" button.
Expected results:
The form should be submitted successfully, and a confirmation message should be displayed.

Actual results:
An error message stating "Internal Server Error" is displayed, and the form submission fails.

Screenshots: Attached screenshot showing the error message.

Environment:

Browser: Chrome version 92.0.4515.159
Operating System: Windows 10

Conclusion
Following these guidelines for writing manual test cases and bug reports will contribute to the overall quality of the DemoQA website. 
Clear and detailed documentation is essential for effective communication between testers, developers, and stakeholders, ensuring that issues are identified and resolved efficiently.

Happy testing and bug hunting! If you have any questions or need assistance, please don't hesitate to reach out.
