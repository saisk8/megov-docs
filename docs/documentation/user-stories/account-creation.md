# Login Stories

### **User Story 1: Account Creation via Email**

**As a** prospective student,  
**I want** to create an account using my email address,  
**So that** I can begin the enrollment process without needing to remember a password.

**Acceptance Criteria:**

- The system should provide an option to create an account using an email address.
- The user should enter their email address and submit the form.
- The system should send a One-Time Password (OTP) to the provided email address.
- The user should be prompted to enter the OTP received via email.
- The OTP should be valid for a configurable time (e.g., 10 minutes).
- If the OTP is correct, the account should be created, and the user should be logged in automatically.
- If the OTP is incorrect or expires, the user should be notified with the option to resend the OTP.

### **User Story 2: Account Creation via Mobile Number**

**As a** prospective student,  
**I want** to create an account using my mobile number,  
**So that** I can begin the enrollment process without needing to remember a password.

**Acceptance Criteria:**

- The system should provide an option to create an account using a mobile number.
- The user should enter their mobile number and submit the form.
- The system should send an OTP to the provided mobile number via SMS.
- The user should be prompted to enter the OTP received via SMS.
- The OTP should be valid for a configurable time (e.g., 10 minutes).
- If the OTP is correct, the account should be created, and the user should be logged in automatically.
- If the OTP is incorrect or expires, the user should be notified with the option to resend the OTP.

### **User Story 3: Resend OTP**

**As a** prospective student,  
**I want** to have the option to resend the OTP,  
**So that** I can still complete the account creation if I did not receive the OTP or it expired.

**Acceptance Criteria:**

- The user should have the option to request a new OTP if the original OTP was not received or has expired.
- The system should allow resending the OTP after a short waiting period (e.g., 30 seconds).
- The user should be notified that a new OTP has been sent to their email or mobile number.

### **User Story 4: OTP Rate Limiting**

**As a** system administrator,  
**I want** to implement rate limiting on OTP requests,  
**So that** the system is protected against abuse or malicious attempts to request multiple OTPs.

**Acceptance Criteria:**

- The system should limit the number of OTP requests to a configurable number (e.g., 5 requests per hour).
- If the rate limit is exceeded, the user should be temporarily blocked from requesting more OTPs and notified of the time when they can try again.
- The system should log any attempts that exceed the rate limit for security monitoring.

### **User Story 5: Account Creation Completion**

**As a** prospective student,  
**I want** to be guided to complete my profile after account creation,  
**So that** I can proceed with the enrollment process.

**Acceptance Criteria:**

- After successful OTP verification, the user should be redirected to a profile completion page.
- The profile completion page should prompt the user to fill in mandatory details like full name, date of birth, and address.
- The user should be able to skip optional details or save and continue later.
- The system should notify the user if mandatory fields are missing before allowing them to proceed.

### **User Story 6: OTP Expiration Notification**

**As a** prospective student,  
**I want** to be notified if my OTP has expired,  
**So that** I understand why my OTP did not work and can request a new one.

**Acceptance Criteria:**

- If the OTP has expired, the system should inform the user immediately upon submission.
- The system should provide an option to request a new OTP directly from the expiration notification.
- The user should not be allowed to use an expired OTP.

### **User Story 7: Multiple Attempts Handling**

**As a** prospective student,  
**I want** to be able to re-enter my email or mobile number if I realize I made a mistake,  
**So that** I can still create my account with the correct information.

**Acceptance Criteria:**

- The user should be able to navigate back to the email or mobile number entry screen if they need to correct their information.
- If the user enters a new email or mobile number, a new OTP should be sent to the updated information.
- The system should invalidate any previously sent OTPs associated with the old email or mobile number.

### **User Story 8: Account Duplication Prevention**

**As a** system,  
**I want** to prevent the creation of duplicate accounts with the same email or mobile number,  
**So that** the enrollment process is secure and avoids confusion.

**Acceptance Criteria:**

- The system should check if an account with the entered email or mobile number already exists.
- If an account exists, the user should be notified and provided with options to either log in or recover their account.
- The system should not allow creating multiple accounts with the same email or mobile number.

### **User Story 9: Email/Mobile Verification Status**

**As a** prospective student,  
**I want** to be able to verify my email or mobile number if it hasn’t been verified during account creation,  
**So that** I can continue with the enrollment process.

**Acceptance Criteria:**

- If the user’s email or mobile number was not verified during account creation, the system should prompt for verification upon the next login attempt.
- The user should receive an OTP to their unverified email or mobile number.
- Upon entering the correct OTP, the system should mark the email or mobile number as verified and allow the user to continue.

### **User Story 10: Forgotten OTP Handling**

**As a** prospective student,  
**I want** an option to regenerate an OTP if I have forgotten it or closed the verification window,  
**So that** I can still complete the account creation process.

**Acceptance Criteria:**

- The system should provide an option to regenerate the OTP if the user has forgotten or lost access to the original OTP.
- The user should be notified that the previous OTP has been invalidated and a new one has been sent.
- The process should follow the same flow as the initial OTP verification.
  #docs/egov
