<small> [Vote Tally Automation](/docs/vote-tally-automation) > <u>[vote-tally-automation.md](/docs/vote-tally-automation/vote-tally-automation.md/)</u></small>

# Vote Tally Automation

The **Vote Tally Automation** module is the core engine of the project that handles all the counting. Instead of people counting paper ballots by hand, the system automatically records every vote the moment a student submits it. This ensures that the results are 100% accurate and available instantly. By removing human error, this module makes the election process faster, more reliable, and completely transparent for the organization.



# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Automated Vote Counting for the project |
| **Actor** | System Backend (Automated) |
| **Pre-conditions** | 1. An election session is "Ongoing."<br>2. A voter has successfully submitted a secure ballot. |
| **Trigger** | A voter clicks the "Yes, Submit Vote" button. |
| **Main Success Scenario** | 1. System receives the encrypted ballot data.<br>2. System identifies the selected candidates for each position.<br>3. System increments the **Vote Count** for each selected candidate in the database automatically.<br>4. System updates the **Total Votes Cast** and **Turnout Percentage** for the session.<br>5. System pushes the new totals to the **Live Results** dashboard immediately. |
| **Alternative Flow (Audit)** | 1. System keeps a secure, background log of every transaction.<br>2. Admin can verify that the total tally matches the number of used one-time codes. |
| **Exception Flow** | 1. Two votes arrive at the exact same millisecond.<br>2. System uses database "locking" to ensure both votes are counted correctly without any data loss. |
| **Post-conditions** | The election standings are updated in real-time, and the data is ready for the automatic report generation once the election closes. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>