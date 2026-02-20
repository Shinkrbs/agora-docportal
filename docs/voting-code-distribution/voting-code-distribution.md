<small> [Voting Code Distribution](/docs/voting-code-distribution) > <u>[voting-code-distribution.md](/docs/voting-code-distribution/voting-code-distribution.md/)</u></small>

# Voting Code Distribution

The **Voting Code Distribution** module handles the delivery of secure credentials to all eligible voters in the project. Once the voter list is finalized, the system automatically sends an email to each student's official registered university address. This email contains their unique, one-time voting code, the direct link to the voting portal, and the link to the live results. By automating this step, the project ensures that every voter receives their access key privately and securely without any manual work from the admins.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Automated Distribution of Voting Codes |
| **Actor** | System Backend (Automated) |
| **Pre-conditions** | 1. The voter list for the election session has been imported.<br>2. The election session is ready to begin. |
| **Trigger** | Admin clicks the "Send Codes" button or the scheduled start time is reached. |
| **Main Success Scenario** | 1. System generates a unique, random one-time code for every student on the voter list.<br>2. System creates a personalized email for each voter.<br>3. System sends the email containing the **One-time Code**, **Voting Link**, and the **Live Results Link** to the student's registered email.<br>4. System updates the status of each voter to "Code Sent." |
| **Alternative Flow (Resend)** | 1. A student reports they did not receive their email.<br>2. Admin finds the student in the voter list and clicks **"Resend Code."**<br>3. System sends the email again to that specific student. |
| **Exception Flow** | 1. System fails to send an email due to an invalid address.<br>2. System flags the specific voter with a "Delivery Failed" status so the admin can fix the email address. |
| **Post-conditions** | All eligible voters have their secure access codes, allowing them to proceed to the secure ballot module to cast their vote. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>