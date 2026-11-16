 # CREATE AN  ACCOUNT IN AWS SET UP A ROOT USER AND AN IAM USER 

### NAME: HARI PRIYA S
### REG NUMBER: 212223220029
 
  ## AIM
  To Create an Account in AWS Set up a Root user and an IAM user.

## ALGORITHM
 ### Steps 1:Sign Up for an AWS Account (Root User Creation)
 
Go to the AWS Management Console homepage and click Create an AWS Account.

Enter your Root user email address and choose an AWS account name.

Click Verify email address, check your inbox for the verification code, and enter it to proceed.

Create and confirm a strong password for your root user.

 ### Steps 2:Provide Contact and Billing Information
 
Select your account type (Personal or Professional) and fill in your contact details (name, phone number, address, country).

Read and accept the AWS Customer Agreement, then click Continue.

Enter your valid credit or debit card details for identity verification and billing. (AWS has a Free Tier, but a small temporary authorization charge may apply to verify the card).

Complete the phone verification step (SMS or voice call) to confirm your identity and activate your account. Choose the Basic Support (Free) plan when prompted.

 ### Steps 3:Secure Your Root User with MFA
Log in to the AWS Management Console as the Root user.

Click on your account name in the top-right corner and select Security credentials.

Scroll down to the Multi-factor authentication (MFA) section and click Assign MFA device.

Choose an authenticator app (such as Google Authenticator, Authy, or a hardware token), scan the QR code, and enter two consecutive sequential MFA codes to complete activation. Note: Never use the root user for daily operational tasks; use it only for initial setup and billing.

 ### Steps 4:Navigate to the IAM Dashboard
In the top search bar of the AWS Console, type IAM and select IAM (Identity and Access Management) from the services list.

Look at the left-hand navigation pane to manage access, users, and security tools.

 ### Steps 5:Create an IAM User for Daily Use
In the IAM dashboard, click on Users in the left menu, then click Create user.

Enter a User name (e.g., admin-user or your name) and check the box for Provide user access to the AWS Management Console if you need console access.

Select I want to create an IAM user, choose a custom password, and uncheck the password reset requirement if preferred. Click Next.

Set permissions by choosing Attach policies directly, search for and select AdministratorAccess (or another specific policy depending on your needs), and click Next.

Review your settings and click Create user. Save the console sign-in URL and credentials securely.

## OUTPUT
<img width="1917" height="1135" alt="image" src="https://github.com/user-attachments/assets/7e51d19b-2dda-4fa5-8d75-5a1a2d4d2d5f" />
<img width="1902" height="1103" alt="image" src="https://github.com/user-attachments/assets/d5907f1f-c575-4faf-8154-7503656bb58d" />
<img width="1912" height="1052" alt="image" src="https://github.com/user-attachments/assets/0f4cc63b-fdfc-48c2-8441-97b66c6626dd" />
<img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/37279800-dd10-43d9-ab9e-898273f8a932" />
<img width="1912" height="1053" alt="image" src="https://github.com/user-attachments/assets/6b7556ac-bbc2-4e15-acbb-4e3d0cc17ae2" />
<img width="1917" height="1140" alt="image" src="https://github.com/user-attachments/assets/97311705-1e15-43ec-a9a9-f06eb42f0694" />


<img width="1917" height="1196" alt="image" src="https://github.com/user-attachments/assets/09ab53ae-e5fa-459d-9073-ce0aaf7b54fc" />
<img width="1917" height="1156" alt="image" src="https://github.com/user-attachments/assets/960da680-5e51-43d3-b902-17ce8e2d3402" />


## RESULT:-
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
