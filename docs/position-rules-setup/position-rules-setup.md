<small> [Position Rules Setup](/docs/position-rules-setup) > <u>[position-rules-setup.md](/docs/position-rules-setup/position-rules-setup.md/)</u></small>

# Position Rules Setup

The **Position Rules Setup** module allows admins to set specific requirements for every position in the election. After an admin chooses a position, they can add rules to make sure only qualified students can run. For example, an admin can set a rule so that a specific position is "for 3rd year students only" or "limited to Computer Science students." This module ensures that the election follows the official organization's rules and keeps the process fair.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Set Position Eligibility Rules |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. Admin is currently in the process of adding a new position. |
| **Trigger** | Admin begins the "Create Position" workflow. |
| **Main Success Scenario** | 1. Admin enters the **Position Name** (e.g., "3rd Year Representative").<br>2. While defining the position, the admin selects the **Add Rule** option.<br>3. Admin chooses a requirement category like **"Year Level"**.<br>4. Admin sets the specific rule (e.g., "Year Level = 3rd Year").<br>5. Admin saves the position.<br>6. System saves both the position and its rules at the same time. |
| **Alternative Flow (Course Rule)** | 1. Admin adds a rule based on the student's department.<br>2. Admin sets the rule to "Computer Science only". |
| **Exception Flow** | 1. Admin tries to save a rule with an empty requirement field.<br>2. System highlights the empty field and asks the admin to finish the rule before saving. |
| **Post-conditions** | The new position is created with strict eligibility rules already attached, so the system can automatically check candidates as they sign up. |

----------------------------------------------------------
<p align="center">© 2026 Vastra</p>