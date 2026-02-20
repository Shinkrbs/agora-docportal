<small> [Voter Import](/docs/voter-import) > <u>[voter-import.md](/docs/voter-import/voter-import.md/)</u></small>

# Voter Import

The **Voter Import** module allows admins to add a list of eligible students who are allowed to vote in the project. Admins can enter student details manually or save time by uploading a large list of voters all at once using a **CSV** or **Excel** file. This module is important because it defines exactly who will receive a unique code to participate in a specific election session.



# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Add Eligible Voters to the project |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. An election session has been created. |
| **Trigger** | Admin opens the "Voter Management" section and selects "Import Voters". |
| **Main Success Scenario** | 1. Admin selects the **Batch Import** option.<br>2. Admin uploads a **CSV** or **Excel** file with student names and emails.<br>3. System checks the file for any errors or empty fields.<br>4. Admin clicks **"Confirm Import"**.<br>5. System adds all students to the voter list for that specific election. |
| **Alternative Flow (Manual)** | 1. Admin chooses to add a voter manually.<br>2. Admin types in the student's **Full Name**, **University Email**, and **Student ID**.<br>3. Admin clicks **"Save Voter"** to add them to the list. |
| **Exception Flow** | 1. Admin uploads a file with the wrong format.<br>2. System shows an error message and asks the admin to use the correct template. |
| **Post-conditions** | The list of eligible voters is ready, and the system can now generate and send unique codes to everyone on the list. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>