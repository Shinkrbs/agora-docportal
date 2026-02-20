<small> [Project Homepage](/docs/project-homepage) > [Authentication](/docs/project-homepage/authentication/) > <u>[sign-up.md](/docs/project-homepage/authentication/sign-up.md)</u></small>

![SignupScreen](/assets/project-homepage/authentication/SignupScreen.png)
![SignuptwoScreen](/assets/project-homepage/authentication/SignuptwoScreen.png)

# Sign Up

The **Sign Up** module provides a structured, two-step onboarding process for new administrators to register and configure their organization within the system. The first step focuses on personal account creation, requiring the user's full name, university email, and a secure password. The second step, Organization Setup, allows the administrator to either join an existing organization using a co-admin code or create an entirely new organization profile. This multi-stage flow ensures that every admin account is correctly linked to a specific student body before they gain access to the management tools.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Admin Registration and Organization Setup |
| **Actor** | New System Administrator / Organization Officer |
| **Pre-conditions** | 1. User does not yet have an admin account.<br>2. User must have a valid university email address. |
| **Trigger** | User clicks the "Sign up" link from the Login page. |
| **Main Success Scenario** | 1. User enters their **Full Name**, **Email**, and **Password** in the first step.<br>2. User clicks **"Continue"** to proceed to organization setup.<br>3. User selects **"Create a New Organization"** or **"Join an Existing Organization"**.<br>4. User clicks **"Complete Setup"**.<br>5. System creates the account, links it to the organization, and redirects to the dashboard. |
| **Alternative Flow (Existing Org)** | 1. User selects **"Join an Existing Organization"**.<br>2. User enters a valid organization code provided by a primary admin.<br>3. System verifies the code and adds the user as a co-admin. |
| **Exception Flow (Validation)** | 1. User enters an invalid email format or passwords do not match.<br>2. System displays a validation error message next to the specific field.<br>3. User corrects the information to proceed. |


----------------------------------------------------------
<p align="center">© 2026 Vastra</p>