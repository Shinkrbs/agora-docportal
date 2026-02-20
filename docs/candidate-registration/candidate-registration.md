<small> [Candidate Registration](/docs/candidate-registration) > <u>[candidate-registration.md](/docs/candidate-registration.md/)</u></small>

![Candidate Registration](/assets/candidate-registration/CandidateRegistration.png)

# Candidate Registration

The **Candidate Registration** module is where admins add people running for office to the system. After a rigorous manual analysis and verification of the candidate's eligibility and requirements, they can be officially added to the system. This module ensures that only qualified individuals appear on the ballot. Admins can add candidates one by one or save time by using the batch import feature to upload a large list of candidates at once using a CSV file.

# Use Case

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Register New Candidate |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. The candidate has passed a manual verification check. |
| **Trigger** | Admin clicks on "Candidates & Party Lists" and selects "Add Candidate." |
| **Main Success Scenario** | 1. Admin enters the candidate's **Full Name**, **Year Level**, and **Course**.<br>2. Admin uploads the **Candidate Photo**.<br>3. Admin selects the **Position** and **Affiliation** (Independent or Partylist).<br>4. Admin clicks **"Add Candidate"**.<br>5. System saves the profile and displays it in the registered candidates list. |
| **Alternative Flow (Batch Import)** | 1. Admin selects the **"Import CSV"** option.<br>2. Admin uploads a CSV file containing multiple candidate records.<br>3. System parses the file and adds all valid candidates to the system at once. |
| **Exception Flow** | 1. Admin misses a required field.<br>2. System highlights the empty field and prevents saving until it is fixed. |
| **Post-conditions** | The candidate is now officially part of the election and will appear on the digital ballot for voters. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>