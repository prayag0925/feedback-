💼 Customer Feedback & Issue Reporting System

A Complete Real-World React Project for Professional Form Handling

The Customer Feedback & Issue Reporting System is a fully interactive, React-based application designed to collect structured user feedback and issue reports. Built with industry standards in mind, this project simulates real-world support platforms such as JIRA, Zendesk, Freshdesk, and GitHub Issues.

The application features a professionally validated feedback form, dynamic field management, controlled + uncontrolled components, and a live-updating feedback dashboard. This project is perfect for students, developers, and learners who want to master advanced React form concepts in a practical environment.

📝 Project Description

This system enables users to submit complaints, bug reports, suggestions, and improvement ideas using a well-structured form. It covers all major real-world form concepts, including:

✔ Controlled & Uncontrolled Components

✔ Form Validation (real-time + onBlur)

✔ Event Handling

✔ Dynamic Form Rows (add/remove)

✔ Refs Usage

✔ State Management

✔ Conditional Rendering

✔ Modern UI/UX Form Styling

Submitted feedback instantly appears in a polished dashboard where entries are displayed as styled cards with category/priority badges, descriptions, steps to reproduce, and more.

🧩 Key Features
🔹 1. Complete Feedback Submission Form

Collects detailed user information:

Full Name

Email

Issue Category (Bug, Suggestion, Complaint, Other)

Priority Level (Low, Medium, High)

Detailed Description (validated)

Screenshot URL (uncontrolled input)

Additional Notes (uncontrolled textarea)

Dynamic Form Rows allow adding/removing:

Steps to Reproduce

Suggested Improvements

This mirrors real ticket systems used in SaaS and CRM platforms.

🔹 2. Controlled & Uncontrolled Components

Both approaches are used strategically:

✔ Controlled Components

Full Name

Email

Category

Priority

Description

Steps List

Suggested Improvements

✔ Uncontrolled Components (via Refs)

Screenshot URL

Additional Notes

This setup reflects real-world use cases where critical fields require validation, while optional fields use refs for simplicity and performance.

🔹 3. Event Handling & State Management

Demonstrates professional handling of React events:

onChange → field updates

onSubmit → final submission

onClick → add/remove rows

onBlur → validation checks

onFocus → styling effects

The UI updates instantly using React state.

🔹 4. Form Validation

Features enterprise-level validation:

Required fields

Email format checking

Minimum text length validation

Category & priority enforcement

Real-time inline error messages

Red error borders

Submit button disabled until valid

🔹 5. Modern Form Styling

Clean and responsive UI includes:

Card-based layout

Highlighted input focus states

Red error text + border styles

Hover & active button effects

Professional spacing, padding, and typography

Fully responsive for mobile screens

🔹 6. Feedback Dashboard

Shows all submitted feedback as elegant cards containing:

User info

Category & priority badges

Description

Screenshot thumbnail

Steps to reproduce

Suggested improvements

Timestamp

Conditional rendering for optional fields

This resembles real support ticket dashboards used in SaaS tools.

🧱 Project Modules
FeedbackForm.jsx     → Main form logic + validation  
DynamicList.jsx      → Reusable dynamic (add/remove) list component  
FeedbackList.jsx     → Displays submitted feedback  
FeedbackCard.jsx     → Single feedback card component  
App.jsx              → State management + data flow  


<img width="1920" height="1080" alt="Screenshot 2025-12-04 114753" src="https://github.com/user-attachments/assets/17a2447a-7c7c-489a-9e89-3d30a2782877" />
<img width="1920" height="1080" alt="Screenshot 2025-12-04 114813" src="https://github.com/user-attachments/assets/436cb10c-55ce-48a0-a09d-8070e21b9087" />
<img width="1920" height="1080" alt="Screenshot 2025-12-04 114822" src="https://github.com/user-attachments/assets/d7a1fb2a-a513-42ae-9f90-b2fbfb1a14fd" />

