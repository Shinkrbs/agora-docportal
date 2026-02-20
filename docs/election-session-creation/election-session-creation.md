<small> [Election Session Creation](/docs/election-session-creation) > <u>[election-session-creation.md](/docs/election-session-creation/election-session-creation.md/)</u></small>

![Election Session Creation](/assets/election-session-creation/CreateElectionSession.png)

# Election Session Creation

The **Election Session Creation** module is where admins set up a new voting event for the project. To start, an admin gives the election a clear title and sets the specific start and end dates for when students can vote. The admin also selects a pre-made position template to decide which offices (like President or Secretary) are being contested. This module makes it easy to launch multiple different elections for various student groups quickly and accurately.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Create New Election Session |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. Position templates have already been created in the system. |
| **Trigger** | Admin clicks the **"Create New Election"** button in the Elections Management section. |
| **Main Success Scenario** | 1. Admin enters the **Election Title** (e.g., "Student Government Elections 2024").<br>2. Admin selects the **Start Date** and **End Date** for the voting period.<br>3. Admin chooses a **Position Template** from the dropdown menu.<br>4. Admin clicks **"Create Election"**.<br>5. System saves the new session and adds it to the active elections list. |
| **Alternative Flow (Cancel)** | 1. Admin clicks the **"Cancel"** button.<br>2. System closes the window without saving any changes. |
| **Exception Flow (Empty Fields)** | 1. Admin tries to create the election while leaving a field blank.<br>2. System shows an alert asking the user to fill in all required information before proceeding. |
| **Post-conditions** | The election session is now scheduled and ready for candidates to be added and for voters to participate once the start date arrives. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>