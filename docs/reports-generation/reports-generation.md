<small> [Reports Generation](/docs/reports-generation) > <u>[reports-generation.md](/docs/reports-generation/reports-generation.md/)</u></small>

![Reports Generation](/assets/reports-generation/ReportsGeneration.png)

# Reports Generation

The **Reports Generation** module handles the final documentation for the project. To ensure accuracy and security, the system automatically creates an official report as soon as an election session ends. Admins do not need to compile data manually; they can simply go to this module to download the finished report for record-keeping and official audits.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Download Automatically Generated Reports |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. An election session has officially ended. |
| **Trigger** | The system finishes the final tally and moves the session to "Closed" status. |
| **Main Success Scenario** | 1. System automatically gathers all vote data, turnout stats, and winner details once the election ends.<br>2. System generates a formatted, downloadable report (like a PDF).<br>3. Admin navigates to the **"Reports & Results"** section.<br>4. Admin finds the completed election in the list.<br>5. Admin clicks the **"Download Report"** button to save the official document. |
| **Alternative Flow (View Only)** | 1. Admin chooses to view the report data on the screen instead of downloading it.<br>2. System displays the same official figures in the dashboard view. |
| **Exception Flow** | 1. Admin checks for a report while the election is still "Ongoing."<br>2. System shows a "Report Pending" status and informs the admin it will be ready once the election closes. |
| **Post-conditions** | The admin has an official, system-generated document ready for university filing or auditing. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>