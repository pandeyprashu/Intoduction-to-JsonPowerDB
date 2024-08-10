# Intoduction-to-JsonPowerDB

# Student Enrollment Form

This repository contains a simple HTML form for student enrollment, designed to interact with a backend database via REST API. The form allows users to enter student details, check if the student already exists in the database, and either save or update the student's information accordingly.


![Screenshot (95)](https://github.com/user-attachments/assets/d5cfa133-3a64-43b2-8c0d-1451e4e51473)

## Features

- **Student Enrollment Form**: Captures details such as Roll No, Full Name, Class, Birth Date, Address, and Enrollment Date.
- **Buttons**: 
  - **Save**: Saves new student records to the database.
  - **Update**: Updates existing student records in the database.
  - **Reset**: Resets the form fields.
- **Form Behavior**:
  - On page load or button click, the form displays in an empty state with only the Roll No field enabled.
  - If the Roll No exists in the database, the form fields are populated, and the Update and Reset buttons are enabled.
  - If the Roll No does not exist, the Save and Reset buttons are enabled.
- **Validation**: Ensures that all fields are filled before submitting.

## Setup

To use this form, ensure you have the following:

1. **API Endpoint**: Update the API endpoint URLs and connection tokens in the script section of `index.html` to match your backend configuration.
2. **Database**: Ensure that the backend API is properly configured to interact with the `SCHOOL-DB` and `STUDENT-TABLE` as specified in the script.

## Files

- `index.html`: The main HTML file containing the form and JavaScript logic.
- **Libraries Used**:
  - Bootstrap: For styling and responsive design.
  - jQuery: For handling AJAX requests and form manipulations.

## Usage

1. **Load the Form**: Open `index.html` in a web browser.
2. **Enter Roll No**: Enter a Roll No to check if the student exists.
   - If the student exists, the form fields will be populated, and the Update button will be enabled.
   - If the student does not exist, the form fields will be enabled, and the Save button will be available.
3. **Save/Update**: Click Save to store new records or Update to modify existing records.
4. **Reset**: Click Reset to clear the form and start over.


