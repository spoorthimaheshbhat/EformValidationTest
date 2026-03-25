# User Stories – Test-A-Form e-Form System

---

## Epic: User Data Collection via E-Form

The system enables users to input and submit structured data through a multi-step form with validation and confirmation.

---

## User Story 1: Access the Form

**As a user**,
I want to access the form via a public URL,
So that I can provide my response without authentication barriers.

### Acceptance Criteria:

* Given the user has a valid URL
* When the user opens the link
* Then the form should load successfully
* And all UI elements should be visible

---

## User Story 2: View Form Elements

**As a user**,
I want to clearly view all form fields and instructions,
So that I can understand what data is required.

### Acceptance Criteria:

* Given the form is loaded
* When the user views the page
* Then all fields (text, dropdown, checkbox, etc.) should be visible
* And labels/instructions should be readable

---

## User Story 3: Enter Valid Data

**As a user**,
I want to enter valid information into each field,
So that my form submission is accepted.

### Acceptance Criteria:

* Given the user is filling the form
* When valid inputs are entered
* Then the system should accept the data without errors

---

## User Story 4: Mandatory Field Validation

**As a user**,
I want to be notified when required fields are empty,
So that I can complete the form correctly.

### Acceptance Criteria:

* Given mandatory fields are empty
* When the user attempts to submit
* Then error messages should be displayed
* And submission should be blocked

---

## User Story 5: Email Format Validation

**As a user**,
I want the system to validate my email format,
So that incorrect emails are not submitted.

### Acceptance Criteria:

* Given the user enters an invalid email
* When the input loses focus or form is submitted
* Then an error message should be displayed
* And submission should be prevented

---

## User Story 6: Numeric Range Validation

**As a user**,
I want numeric inputs to be validated within a defined range,
So that I don’t enter invalid values.

### Acceptance Criteria:

* Given a numeric field with range (1–10)
* When user enters a value outside the range
* Then an error message should be shown
* And submission should be blocked

---

## User Story 7: Multi-Section Navigation

**As a user**,
I want to navigate between sections of the form,
So that I can complete it step-by-step.

### Acceptance Criteria:

* Given the user is in Section 1
* When the user clicks “Next”
* Then the system should navigate to Section 2
* And previously entered data should be retained

---

## User Story 8: Optional Fields Handling

**As a user**,
I want to skip optional fields if I choose,
So that I can submit the form faster.

### Acceptance Criteria:

* Given optional fields are left empty
* When the user submits the form
* Then submission should still be successful

---

## User Story 9: Checkbox Selection

**As a user**,
I want to select multiple options using checkboxes,
So that I can provide multiple responses.

### Acceptance Criteria:

* Given checkbox options are available
* When the user selects one or more options
* Then selections should be recorded correctly

---

## User Story 10: Dropdown Selection

**As a user**,
I want to select an option from a dropdown list,
So that I can provide predefined input.

### Acceptance Criteria:

* Given dropdown options are available
* When the user selects one option
* Then the selected value should be stored

---

## User Story 11: Date Input Validation

**As a user**,
I want to enter a valid date,
So that the system captures accurate temporal data.

### Acceptance Criteria:

* Given a date field is present
* When the user enters/selects a date
* Then it should follow valid date format
* And invalid formats should be rejected

---

## User Story 12: Time Input Validation

**As a user**,
I want to enter a valid time,
So that time-based data is captured correctly.

### Acceptance Criteria:

* Given a time field is present
* When the user enters time
* Then it should follow valid format (HH:MM)

---

## User Story 13: Submit the Form

**As a user**,
I want to submit the form after completing required fields,
So that my response is recorded.

### Acceptance Criteria:

* Given all required fields are valid
* When the user clicks “Submit”
* Then the form should be successfully submitted

---

## 📌 User Story 14: Confirmation Message

**As a user**,
I want to see a confirmation message after submission,
So that I know my response was recorded.

### Acceptance Criteria:

* Given the form is successfully submitted
* When submission completes
* Then a confirmation message should be displayed
* And it should indicate success

---

## User Story 15: Backend Data Storage

**As a system**,
I want to store submitted responses in Google Sheets,
So that data can be reviewed and analyzed.

### Acceptance Criteria:

* Given a form submission is successful
* When data is processed
* Then a new row should be added in Google Sheets
* And all field values should match input data

---

## User Story 16: Invalid Submission Handling

**As a system**,
I want to prevent invalid form submissions,
So that data integrity is maintained.

### Acceptance Criteria:

* Given invalid or incomplete input
* When the user attempts submission
* Then submission should be blocked
* And appropriate error messages should be displayed

---

## User Story 17: Sign-In Redirection (Optional)

**As a user**,
I want to be redirected when clicking “Sign in to Google”,
So that I can authenticate if needed.

### Acceptance Criteria:

* Given a sign-in option is present
* When the user clicks the link
* Then the system should redirect to Google Sign-In page

---

## User Story 18: System Reliability

**As a user**,
I want the form to function consistently,
So that I can complete submission without errors.

### Acceptance Criteria:

* Given stable internet connection
* When user interacts with the form
* Then all actions should perform without crashes or delays

---
