# LMS-Testing-Project-

UI Functional Test Cases Documentation

Project: Freelance Learn Automation Web App

App URL: https://freelance-learn-automation.vercel.app/login

Objective

The primary objective of this test suite is to validate the UI/UX, functionality, form validation, and screen navigation of the Freelance Learn Automation platform. The test cases focus on Sign In, Sign Up, Home Screen interactions, and Practical Exercises.

Modules Covered

Sign In Screen

Sign Up Flow

Home Screen Course Display

Enroll Process

Practice Screen Functional Tests

Sign Out Flow

Screenshots

1. Sign In Screen

![Screenshot 2025-06-09 135336](https://github.com/user-attachments/assets/58e3acb2-82e0-499d-9fee-7a8844ea6edc)


2. Home Screen

![Screenshot 2025-06-09 135405](https://github.com/user-attachments/assets/d9fbb658-16f9-4566-809e-59febe8a0afc)


3. Practice Screen

![Screenshot 2025-06-09 135621](https://github.com/user-attachments/assets/98990b7e-4ba8-463f-bcce-c3845fde5767)


4. Cart Screen
   
![Screenshot 2025-06-09 135500](https://github.com/user-attachments/assets/ebcd645e-80cd-458a-92e2-ed44c7c23234)


5. Sign Out Screen

![Screenshot 2025-06-09 135744](https://github.com/user-attachments/assets/a5bfae82-92fd-4c82-838a-d075f415b5ec)


Key Test Areas

Sign In Validation

Test combinations of valid, invalid, blank, special characters, numbers, and alphanumeric usernames and passwords.

Test long strings (>30 characters).

Test with international characters (accents, umlauts).

Social media icons are displayed and redirect correctly.

Error messages are shown properly.

Sign Up Validation

Validate all required fields: Name, Email, Password, Interests, Gender, Hobbies.

Handle errors for duplicate email or missing required data.

Post successful sign up, redirect to Sign In screen.

Home Screen

Verify the display of 3 core courses: Java Freshers, Selenium, Playwright.

Validate add to cart and enroll button workflows.

Enroll Now Popup

Handle empty Address/Phone No warnings.

Ensure order ID is generated post successful enroll.

Practice Section

Enable Text Field after 5 sec and validate input.

Show/Hide functionality for entered text.

Alert popup on double click.

Drag and drop action validation.

Sign Out

Verify sign out button redirects user to login screen.

Types of Testing Performed

Functional Testing – Ensured every feature behaves as expected based on requirements.

Exploratory Testing – Tested the app without predefined test cases to discover unexpected bugs.

Ad-hoc Testing – Performed random testing scenarios to catch edge-case issues.

Compatibility Testing – Verified website works correctly across multiple browsers (Chrome, Firefox, Edge) and screen sizes.

Integration Testing – Ensured modules such as sign in → enroll → practice flow work seamlessly.

System Testing – Validated the entire LMS portal from end-to-end.

Sanity Testing – Checked basic functionalities work post-build deployment.

Performance Testing – Observed loading time, responsiveness of pages, and lag under simulated loads.

Tools Used

Manual Testing

Web UI Inspection

Bug Tracking via JIRA 

Automation-ready structure (for Selenium)

Author: Murali Krishna

Role: QA Engineer (Manual + Automation)

GitHub: https://github.com/muralikrishnabigala

LinkedIn : https://www.linkedin.com/in/b-muralikrishna-715730228/

Document Link : https://docs.google.com/document/d/114hT0j0UqtC5LYqfEBTawB4F7sMJoI9FzmhdTBoE6qg/edit?usp=sharing


