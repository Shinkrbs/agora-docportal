<small> [Partylists Management](/docs/partylists-management) > <u>[partylists-management.md](/docs/partylists-management/partylists-management.md/)</u></small>

# Partylist Management

The **Partylist Management** module allows admins to organize candidates into official groups or "partylists". This module makes it easy to manage team-based campaigns by letting admins create a partylist identity and then assign specific verified candidates to it. This ensures that the digital ballot correctly groups candidates who are running together, helping voters identify their preferred political groups. To save time, admins can add candidates one by one or use the batch import feature to upload a large list of partylists and their members at once using a CSV file.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Create and Manage Partylists |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. Candidates must be already registered in the system. |
| **Trigger** | Admin clicks on "Candidates & Party Lists" and selects the "Partylist" tab. |
| **Main Success Scenario** | 1. Admin clicks **"Add Partylist"** and enters the **Partylist Name**.<br>2. Admin uploads the **Partylist Logo**.<br>3. Admin selects a candidate from the registered list.<br>4. Admin assigns the candidate to the specific **Partylist**.<br>5. System saves the link and updates the candidate's profile to show their new affiliation. |
| **Alternative Flow (Batch Import)** | 1. Admin selects the **"Import CSV"** option.<br>2. Admin uploads a CSV file containing multiple partylist names and assigned candidates.<br>3. System parses the file and creates all partylists and links candidates automatically. |
| **Alternative Flow (Remove)** | 1. Admin selects an existing Partylist.<br>2. Admin chooses to remove a candidate from that list.<br>3. System updates the candidate to "Independent" status. |
| **Exception Flow** | 1. Admin tries to create a Partylist with a name that already exists.<br>2. System shows an error message saying the name is taken. |
| **Post-conditions** | Candidates are now grouped by their partylists and will appear this way on the election ballot and results page. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>