<small> [Election Session Status](/docs/election-session-status) > <u>[election-session-status.md](/docs/election-session-status/election-session-status.md/)</u></small>

# Election Sessin Status

The **Election Session Status** module lets admins see the current state of any voting event in the project. It uses simple labels to show what stage the election is in. For example, a "Pending" status means the election hasn't started yet, while "Ongoing" means students are currently voting, or "Paused" means the election is stopped for the mean time. Once the time is up, it changes to "Closed," and finally "Results Posted" when the admin shares the winners. This helps everyone stay organized and informed.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Track Election Progress |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. At least one election session has been created. |
| **Trigger** | Admin opens the "Elections" management page. |
| **Main Success Scenario** | 1. Admin views the list of all created elections.<br>2. Admin checks the **Status Label** next to each election title.<br>3. System automatically updates the status from **"Pending"** to **"Ongoing"** based on the start date.<br>4. System automatically changes the status to **"Closed"** once the end date passes. |
| **Alternative Flow (Manual Update)** | 1. Admin reviews the results of a "Closed" election.<br>2. Admin clicks the **"Post Results"** button.<br>3. System updates the status to **"Results Posted"** for public viewing. |
| **Exception Flow** | 1. System detects a date conflict or error in the schedule.<br>2. System displays a warning icon next to the status to alert the admin. |
| **Post-conditions** | The admin knows exactly which elections are active and which ones need further action like posting results. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>