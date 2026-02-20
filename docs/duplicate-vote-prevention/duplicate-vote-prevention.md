<small> [Duplicate Vote Prevention](/docs/duplicate-vote-prevention) > <u>[duplicate-vote-prevention.md](/docs/duplicate-vote-prevention/duplicate-vote-prevention.md/)</u></small>

![Duplicate Vote Prevention](/assets/duplicate-vote-prevention/DuplicateVotePrevention.png)

# Duplicate Vote Prevention

The **Duplicate Vote Prevention** module is a key security feature of the project. It ensures that every student can only vote one time. This works by giving each voter a **One-time Voting Code** using the email they provided. When a student is ready to vote, they must enter this unique code into the voting interface. Once a code is used to submit a ballot, the system marks it as "used," and it cannot be used again. This simple method keeps the election fair and prevents anyone from voting twice.

# Use Case

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Unique Code Verification |
| **Actor** | Student (Voter) |
| **Pre-conditions** | 1. The voter has received their unique one-time code via email.<br>2. An election session is currently active. |
| **Trigger** | The voter opens the voting link and reaches the security screen. |
| **Main Success Scenario** | 1. Voter enters their **One-time Voting Code** into the input field.<br>2. Voter clicks the **"Proceed to Vote"** button.<br>3. System checks if the code is valid and has not been used yet.<br>4. System grants access to the digital ballot.<br>5. After the vote is cast, the system expires the code immediately. |
| **Alternative Flow (Invalid Code)** | 1. Voter enters a code that does not exist or has a typo.<br>2. System shows an error message saying the code is invalid. |
| **Exception Flow (Used Code)** | 1. Voter tries to use a code that has already been used to cast a vote.<br>2. System blocks access and informs the user that a vote has already been recorded for this code. |
| **Post-conditions** | The voter's identity remains anonymous, but the system successfully records that one unique vote has been cast, preventing any duplicates. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>