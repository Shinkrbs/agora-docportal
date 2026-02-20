<small> [Live Results](/docs/live-results) > <u>[live-results.md](/docs/live-results/live-results.md/)</u></small>

![Live Resuls](/assets/live-results/LiveResults.png)

# Live Results

The **Live Results** module provides a real-time and transparent view of how the voting is going. The system automatically counts every vote as it is cast, so there is no need for manual counting. The link to view these live results is sent directly to each voter's email along with their unique one-time voting code.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | View Real-time Election Tally |
| **Actor** | Student (Voter) / Admin |
| **Pre-conditions** | 1. An election session is "Ongoing" or "Results Posted."<br>2. The user has received the results link via their school email. |
| **Trigger** | User clicks the live results link sent to their email. |
| **Main Success Scenario** | 1. User opens the **Live Results** page from their email link.<br>2. User sees the **Live Tally** status and the last time it was updated.<br>3. User reviews the **Voter Turnout** and **Total Votes Cast**.<br>4. User sees the automatic tally for each position (President, VP, etc.).<br>5. System displays a **"Leading"** badge next to the candidate with the most votes.<br>6. System updates the numbers automatically as more students vote. |
| **Alternative Flow (Results Posted)** | 1. The election ends and the admin posts the final results.<br>2. User clicks the same link to see the official final winners. |
| **Exception Flow** | 1. The user tries to open the link before the election starts.<br>2. System shows a message saying the results are not yet available. |
| **Post-conditions** | The user is fully informed about the election standings through an official and automated count. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>