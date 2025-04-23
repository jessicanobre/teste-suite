Test Report 2 – Invalid Login Attempt
Title: Invalid Login with Incorrect Credentials
Description: This test checks the system’s behavior when invalid login credentials are provided.
Objective: To ensure the system rejects incorrect credentials and displays the proper error message.
What is being tested: Login error handling and feedback to the user.
Prerequisites:

Access to the SuiteCRM instance.

Supported browser.

Test Procedure:

Navigate to crm.alunostds.dev.br.

Enter wronguser as the username.

Enter wrongpass as the password.

Click the “Login” button.

Expected Result:
The system should display an error message indicating login failure.

Actual Result:
An error message appears: "Invalid username or password."

Result Analysis:
Test passed. The system correctly rejected the invalid credentials.

Error Description:
N/A

Evidence:
![Captura de tela 2025-04-23 191155](https://github.com/user-attachments/assets/9bf74c5c-ed59-4ce4-b6e7-efdba2222ba2)

Screenshot: [Insert login failure screenshot]

Browser: Firefox

OS: Windows 11

