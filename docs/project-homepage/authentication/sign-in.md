<small> [Project Homepage](/docs/project-homepage) > [Authentication](/docs/project-homepage/authentication/) > <u>[sign-in.md](/docs/project-homepage/authentication/sign-in.md)</u></small>

![login-page](/assets/project-homepage/authentication/LoginScreen.png)

# Sign In

The **Sign In** module acts as the secure gateway for administrators to access their dashboards. It features a dual-authentication approach using Google OAuth integration or using the traditional email and password fields. Additionally, the module also includes important account management features such as "Forgot Password?" link for account recovery and "Sign up" link for new administrators.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Admin Login for Student Organization Election System (SOES) |
| **Actor** | System Administrator / Organization Officer |
| **Pre-conditions** | 1. User must have an active admin account.<br>2. User must have a stable internet connection. |
| **Trigger** | User navigates to the SOES login URL. |
| **Main Success Scenario** | 1. User enters registered **Email** and **Password**.<br>2. User clicks the **"Sign in"** button.<br>3. System validates credentials against the database.<br>4. System grants access and redirects the user to the **Admin Dashboard**. |
| **Alternative Flow (OAuth)** | 1. User clicks the **"Login with Google"** button.<br>2. User selects their authenticated university Google account.<br>3. System verifies OAuth token and redirects to the dashboard. |
| **Exception Flow (Invalid)** | 1. User enters incorrect credentials.<br>2. System displays an error message: "Invalid email or password."<br>3. User remains on the login page to try again. |
| **Exception Flow (Recovery)**| 1. User clicks **"Forgot password?"**.<br>2. System redirects to the password reset request page. |
| **Post-conditions** | The user is authenticated and authorized to manage elections, candidates, and voter data. |


----------------------------------------------------------
<p align="center">© 2026 Vastra</p>