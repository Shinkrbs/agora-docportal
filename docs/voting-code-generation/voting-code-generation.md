<small> [Voting Code Generation](/docs/voting-code-generation) > <u>[voting-code-generation.md](/docs/voting-code-generation/voting-code-generation.md/)</u></small>

# Voting Code Generation

The **Voting Code Generation** module is responsible for creating the secure access keys for the project. To ensure the election is fair and private, the system automatically creates a unique, one-time voting code for every student on the eligible voter list. These codes are generated using a random process so they cannot be guessed, and each code can only be used to submit a single ballot.

# Use Case Scenario

| Field | Description |
| :--- | :--- |
| **Use Case Name** | Generate Unique Voting Codes |
| **Actor** | System Backend (Automated) |
| **Pre-conditions** | 1. The list of eligible voters has been successfully imported.<br>2. The admin has initiated the code generation process. |
| **Trigger** | Admin clicks the **"Generate Codes"** button in the Voter Management section. |
| **Main Success Scenario** | 1. System scans the list of all registered voters for the specific election session.<br>2. System uses a secure random generator to create a **Unique One-Time Code** for each student.<br>3. System checks each new code against existing ones to ensure there are no duplicates.<br>4. System stores the generated code in the database and links it to the specific voter record.<br>5. System marks the voter status as "Code Generated." |
| **Alternative Flow (Incremental)** | 1. Admin adds a few more voters to an existing list manually.<br>2. System identifies the new voters and generates codes only for those specific individuals. |
| **Exception Flow** | 1. System encounters a database error while saving codes.<br>2. System stops the process and alerts the admin that the generation failed, ensuring no partial or corrupted lists are created. |
| **Post-conditions** | Every eligible voter now has a private, unique code assigned to them, which is ready to be sent out via the **Voting Code Distribution** module. |
----------------------------------------------------------
<p align="center">© 2026 Vastra</p>