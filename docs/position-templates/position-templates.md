<small> [Position Templates](/docs/position-templates) > <u>[position-templates.md](/docs/position-templates/position-templates.md/)</u></small>

![Position Template](/assets/position-templates/PositionTemplate.png)

# Position Templates

The **Position Templates** module allows admins to create and reuse sets of positions for different elections in the project. Instead of adding every position (like President, Vice President, etc.) manually for every new election, an admin can save them as a template. This makes setting up a new election much faster and ensures that all organizational setups remain consistent across different voting sessions.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Create and Reuse Position Template for the project |
| **Actor** | System Admin / Election Officer |
| **Pre-conditions** | 1. Admin is logged in.<br>2. Admin is on the "Position Templates" management page. |
| **Trigger** | Admin clicks the **"Create Template"** button to start a new configuration. |
| **Main Success Scenario** | 1. Admin enters a **Template Name** (e.g., "Student Government Executive").<br>2. Admin adds the required positions to the list.<br>3. Admin clicks **"Create Template"** to save the set.<br>4. System stores the template.|
| **Alternative Flow (Reusing)** | 1. Admin creates a new election session.<br>2. Admin selects a saved template from the dropdown menu.<br>3. System automatically fills in all the positions and rules from that template. |
| **Exception Flow** | 1. Admin tries to save a template name that is already being used.<br>2. System shows an error message and asks the admin to choose a unique name. |
| **Post-conditions** | The template is available for any future election, allowing for quick setup and standardized ballots. |


----------------------------------------------------------
<p align="center">© 2026 Vastra</p>