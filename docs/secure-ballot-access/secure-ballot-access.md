<small> [Secure Ballot Access](/docs/secure-ballot-access) > <u>[secure-ballot-access.md](/docs/secure-ballot-access/secure-ballot-access.md/)</u></small>

![VotingPage](/assets/secure-ballot-access/VotingPage.png)
![SubmitVote](/assets/secure-ballot-access/SubmitVote.png)

# Secure Ballot Access

The **Secure Ballot Access** module provides a simple and secure way for students to cast their votes. This interface appears immediately after a voter enters their unique, one-time code. It is designed to look like a straightforward survey, where voters can easily select their chosen candidates for each position. The system ensures that the voting process is intuitive and that every selection is clearly marked before the final submission.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Cast Vote via Secure Interface |
| **Actor** | Student (Voter) |
| **Pre-conditions** | 1. Voter has entered a valid, unused one-time code.<br>2. The system has verified the code and granted access. |
| **Trigger** | The voter is redirected to the voting page after successful code verification. |
| **Main Success Scenario** | 1. Voter reviews the list of positions (e.g., President, Vice President) and candidates.<br>2. Voter selects one candidate for each position by clicking on their profile.<br>3. System highlights the selected candidate and marks them as **"Selected"**.<br>4. Voter clicks the **"Submit My Vote"** button at the bottom of the page.<br>5. A confirmation window appears showing all choices.<br>6. Voter clicks **"Yes, Submit Vote"** to finalize the ballot.<br>7. System records the vote anonymously and marks the one-time code as used. |
| **Alternative Flow (Review)** | 1. Voter clicks **"Review My Choices"** on the confirmation window.<br>2. System closes the window and lets the voter change their selections before submitting. |
| **Exception Flow** | 1. Voter tries to submit without selecting a candidate for a required position.<br>2. System shows a reminder to make a selection before the final submission. |
| **Post-conditions** | The vote is securely stored in the project database, and the voter can no longer access the ballot using the same code. |


----------------------------------------------------------
<p align="center">© 2026 Vastra</p>