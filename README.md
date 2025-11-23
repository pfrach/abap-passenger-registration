[README.txt](https://github.com/user-attachments/files/23698025/README.txt)
# Passenger Registration System (ABAP)

A SAP ABAP program for registering passengers, validating input data, and saving records into custom tables. This project demonstrates object-oriented ABAP, selection screens, data validation, and user interaction via popup messages.

---

## Features

- **Passenger Registration**  
  Allows users to enter personal information including first name, last name, document type and number, phone number, email, and password.  

- **Data Validation**  
  - Validates email format  
  - Validates document number format  
  - Handles errors gracefully via popup messages  

- **Database Integration**  
  Inserts validated passenger data into a custom table for further processing in SAP environments.  

- **User Feedback**  
  Uses SAP standard popup functions (`POPUP_TO_INFORM`) to provide immediate feedback to the user.  

---

## Technologies & SAP Components

- **ABAP Reports** – classical report program structure  
- **ABAP Objects** – object-oriented approach for passenger creation and validation (`ZCL_PASSENGER`)  
- **Selection Screens** – interactive user input  
- **Custom DDIC Tables** – `ZZZ_PASS_TAB` for storing passenger data  
- **SAP Standard Functions** – popup messages for notifications  

---

## How It Works

1. The user enters personal data on the selection screen.  
2. The program validates email and document number.  
3. If valid, a new passenger record is created in the custom table.  
4. A confirmation popup displays the passenger number.  

---

## Use Cases

- Demonstrates basic SAP ABAP object-oriented programming  
- Example of input validation and error handling in ABAP  
- Can be extended for airline booking systems or CRM integrations  

---

## Future Improvements

- Add password encryption and security enhancements  
- Integrate with SAP workflow for automated approvals  
- Extend to full passenger management system with flight reservations  
