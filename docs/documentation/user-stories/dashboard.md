# Dashboard Page User Stories

### **User Story 1: Comprehensive Application Status Tracking**

**As a** student,  
**I want** to have a comprehensive view of my application status on the dashboard,  
**So that** I can easily track my progress and understand what actions are needed to complete my application.

**Acceptance Criteria:**

- **Status Overview:**
  - The dashboard should display a visual progress bar indicating the completion percentage of the application process.
  - The progress bar should be segmented into distinct phases (e.g., Account Creation, Enrollment, Registration, Review).
  - Each phase should indicate whether it is **Not Started**, **In Progress**, **Completed**, or **Pending Review**.
- **Detailed Status Breakdown:**
  - Clicking on each phase should expand to show detailed tasks required within that phase.
  - Completed tasks should be marked with a checkmark, while pending tasks should be clearly indicated.
  - For pending tasks, provide direct links or buttons to proceed with completing them.
- **Real-Time Updates:**
  - The status should update in real-time as the student completes various parts of the application.
  - Notifications should appear for any changes in status, including approvals, rejections, or requests for additional information.
- **Error Notifications:**
  - If there are errors or missing information in any part of the application, the dashboard should highlight these with clear messages and guidance on how to resolve them.

### **User Story 2: Personalized Notifications and Reminders**

**As a** student,  
**I want** to receive personalized notifications and reminders on my dashboard,  
**So that** I stay informed about important updates and deadlines related to my application.

**Acceptance Criteria:**

- **Notification Center:**
  - The dashboard should include a notification center displaying all recent and unread notifications.
  - Notifications should cover:
    - Upcoming deadlines.
    - Submission confirmations.
    - Requests for additional information or documents.
    - Application status changes (e.g., "Your enrollment has been approved. Proceed to registration.").
- **Timely Reminders:**
  - Automated reminders should be sent ahead of important deadlines (e.g., 7 days before, 1 day before).
  - Reminders should include clear instructions on what actions are required.
- **Multi-Channel Notifications:**
  - Notifications should be sent via multiple channels as per user preference: dashboard alerts, email, and SMS.
  - Preferences for notification channels should be configurable within the user profile settings.
- **Read and Unread Status:**
  - Users should be able to mark notifications as read or unread.
  - Option to archive or delete old notifications for better organization.

### **User Story 3: Easy Access to Support and Assistance**

**As a** student,  
**I want** quick access to support and assistance options from the dashboard,  
**So that** I can get help promptly if I encounter any issues during the application process.

**Acceptance Criteria:**

- **Support Links:**
  - The dashboard should prominently display links to various support options, including:
    - **FAQ Section:** Common questions and answers about the application process.
    - **Live Chat:** Real-time chat support with admissions staff.
    - **Email Support:** Form to send detailed inquiries via email.
    - **Phone Support:** Contact numbers for immediate assistance.
- **Live Chat Integration:**
  - Live chat should be accessible directly from the dashboard, with minimal clicks.
  - Chat should support automated responses for common queries and escalate to human agents as needed.
  - Chat history should be saved and accessible for future reference.
- **Help Articles and Tutorials:**
  - Provide access to step-by-step guides, video tutorials, and other resources to assist with different parts of the application.
  - Resources should be searchable and categorized for easy navigation.

### **User Story 4: Profile Management and Editing**

**As a** student,  
**I want** to view and edit my personal profile information from the dashboard,  
**So that** I can keep my details up-to-date and accurate throughout the application process.

**Acceptance Criteria:**

- **Profile Overview:**
  - The dashboard should display key profile information such as name, contact details, and account settings.
- **Edit Functionality:**
  - Users should be able to edit their personal information directly from the dashboard.
  - Changes should be validated in real-time to ensure data accuracy (e.g., proper email format, valid phone numbers).
  - After editing, users should receive confirmation that their profile has been successfully updated.
- **Security Measures:**
  - Sensitive changes (e.g., email or phone number updates) should require verification through OTP sent to the new contact information.
  - Provide options to update password and security settings, even if the primary login is passwordless, for added security layers.
- **Multi-Language Support:**
  - Profile and dashboard should support multiple languages (e.g., English and Spanish) with easy toggling between languages.

### **User Story 5: Document Management and Tracking**

**As a** student,  
**I want** to manage and track all my uploaded documents from the dashboard,  
**So that** I can ensure all necessary documents are submitted and address any issues promptly.

**Acceptance Criteria:**

- **Document Summary:**
  - The dashboard should display a list of all required documents along with their submission status (e.g., Uploaded, Pending, Rejected).
- **Upload and Re-upload Capability:**
  - Users should be able to upload missing documents directly from the dashboard.
  - If a document is rejected (e.g., due to poor quality or incorrect format), users should receive a notification with reasons and an option to re-upload.
- **Document Preview:**
  - Provide the ability to preview uploaded documents within the dashboard for verification purposes.
- **Supported Formats and Guidelines:**
  - Clearly specify supported file formats and size limits for each document type.
  - Provide guidelines and examples for acceptable documents to assist users in proper submission.
- **Security and Privacy:**
  - Ensure all uploaded documents are stored securely with appropriate encryption.
  - Display privacy notices informing users how their documents will be used and protected.

### **User Story 6: Application History and Activity Log**

**As a** student,  
**I want** to view the history and activity log of my application process,  
**So that** I can keep track of all actions taken and have a record for future reference.

**Acceptance Criteria:**

- **Activity Log Access:**
  - The dashboard should include an activity log detailing all actions taken during the application process, including dates and times.
- **Logged Activities:**
  - Activities should include account creation, form submissions, document uploads, status changes, and communications with support.
- **Filter and Search:**
  - Users should be able to filter activities by date range and activity type.
  - A search function should be available to find specific entries quickly.
- **Export Capability:**
  - Provide an option to export the activity log as a PDF or CSV file for personal records.
- **Data Integrity:**
  - Ensure all activity data is accurate and tamper-proof to maintain trust and transparency.

---

## **Application Form-Filling Flow User Stories**

### **Enrollment Phase**

#### **User Story 7: Multiple Enrollment Methods**

**As a** student,  
**I want** to have various methods available for completing my enrollment,  
**So that** I can choose the most convenient option based on my circumstances.

**Acceptance Criteria:**

- **Available Methods:**
  - The system should support multiple enrollment methods, including:
    - **Online Independent Enrollment**
    - **Kiosk Submission at School**
    - **Physical Enrollment at School**
    - **Website Inquiry Form**
    - **Website Chat with Staff**
    - **Website Email with Staff**
- **Method Selection:**
  - Upon starting the enrollment process, users should be presented with all available methods and brief descriptions.
  - Users should be able to select their preferred method and proceed accordingly.
- **Seamless Transition:**
  - For methods requiring staff assistance, the system should facilitate scheduling and initiating contact seamlessly.
  - All methods should ultimately result in the required data being captured and stored uniformly within the system.

#### **User Story 8: Online Independent Enrollment Process**

**As a** student,  
**I want** to complete my enrollment independently through an online portal,  
**So that** I can enroll at my own pace and convenience without needing in-person assistance.

**Acceptance Criteria:**

- **Secure Access:**
  - Enrollment portal should be accessible after secure login through the student's account.
- **Form Structure:**
  - The enrollment form should be organized into logical sections (e.g., Personal Information, Academic History, Contact Details).
  - Each section should include clear instructions and mandatory field indicators.
- **Data Validation:**
  - Real-time validation should be implemented to catch errors and incomplete fields before submission.
  - Helpful error messages should guide users to correct input mistakes.
- **Save and Resume:**
  - Users should be able to save their progress at any point and resume later from where they left off.
  - Auto-save functionality should be implemented to prevent data loss.
- **Document Uploads:**
  - Users should be prompted to upload required documents (Proof of Identity, Proof of Residence) within the form flow.
  - Upload interface should support drag-and-drop and provide immediate feedback on successful uploads.
- **Digital Signature Integration:**
  - At the end of the form, users should be prompted to digitally sign using an integrated and legally compliant e-signature solution.
  - Signature process should be straightforward, with options to draw, type, or upload a signature as appropriate.
- **Confirmation and Receipt:**
  - Upon successful submission, users should receive an on-screen confirmation and a receipt via email/SMS detailing the submission and next steps.

#### **User Story 9: Kiosk Submission at School**

**As a** student,  
**I want** to complete my enrollment using a kiosk at the school,  
**So that** I can receive assistance and use available resources if needed.

**Acceptance Criteria:**

- **User-Friendly Interface:**
  - The kiosk should have a touch-friendly, intuitive interface guiding users through each step of the enrollment form.
- **Accessibility Features:**
  - Kiosk interface should support accessibility features such as adjustable text size, screen reader support, and language options (e.g., English and Spanish).
- **Document Scanning:**
  - The kiosk should be equipped with scanning capabilities to allow users to digitize and upload required documents on-site.
  - Scanned documents should be previewed for clarity before submission.
- **Assistance Availability:**
  - Staff assistance should be readily available to help users navigate the kiosk process if needed.
- **Digital Signature Capture:**
  - Kiosk should include a digital signature pad or touch-screen functionality to capture the user's signature securely.
- **Secure Data Handling:**
  - All data entered and documents uploaded through the kiosk should be transmitted securely and not stored locally to ensure privacy.
- **Immediate Confirmation:**
  - Upon completion, the kiosk should print a confirmation receipt and/or send a digital confirmation via email/SMS.

#### **User Story 10: Assisted Enrollment via Website Chat**

**As a** student,  
**I want** to complete my enrollment with assistance through a website chat,  
**So that** I can get real-time support and clarification during the process.

**Acceptance Criteria:**

- **Initiating Chat:**
  - Users should be able to initiate a chat session directly from the website or dashboard.
  - Chat interface should be responsive and support both desktop and mobile devices.
- **Assistance Process:**
  - A live agent should guide the user through filling out the enrollment form, either by providing instructions or inputting information on the user's behalf.
  - The chat should support file sharing to allow users to send required documents directly through the chat interface.
- **Secure Information Exchange:**
  - All data and documents shared during the chat should be transmitted securely and handled in compliance with privacy regulations.
- **Digital Signature Coordination:**
  - After completing the form, the agent should prompt the user to digitally sign via a secure link or embedded signature process.
- **Confirmation and Follow-up:**
  - Upon completion, the user should receive confirmation of submission and information on the next steps.
  - The chat transcript should be available for the user to review or download for their records.

#### **User Story 11: Handling Incomplete or Missing Information**

**As a** student,  
**I want** the system to notify me of any incomplete or missing information during enrollment,  
**So that** I can provide all necessary details and avoid delays in my application processing.

**Acceptance Criteria:**

- **Real-Time Validation:**
  - The system should check for required fields and document uploads in real-time as the user progresses through the form.
- **Error Messages:**
  - Clear and specific error messages should be displayed next to any incomplete or incorrectly filled fields.
- **Summary of Missing Items:**
  - Before final submission, the system should present a summary listing any missing information or documents.
- **Guidance for Completion:**
  - Provide helpful tips or links to resources explaining how to obtain and upload required documents.
- **Flexibility:**
  - Allow users to save and exit even if the form is incomplete, with pending items clearly marked for future completion.
- **Notifications:**
  - Send automated reminders via email/SMS prompting users to complete pending items, including deadlines if applicable.

#### **User Story 12: Multi-Language Support Throughout Enrollment**

**As a** non-English speaking student,  
**I want** the enrollment process to be available in my preferred language,  
**So that** I can understand and complete the application accurately.

**Acceptance Criteria:**

- **Language Selection:**
  - Users should be able to select their preferred language at the start of the enrollment process and change it at any point.
- **Supported Languages:**
  - The system should support at least English and Spanish, with potential for additional languages based on user demographics.
- **Consistent Translation:**
  - All text, instructions, error messages, and notifications should be accurately translated and culturally appropriate.
- **Document Translation Assistance:**
  - Provide guidance or resources for translating necessary documents if required.
- **Support in Preferred Language:**
  - Live support (chat, email, phone) should be available in the selected language where possible.

### **Registration Phase**

#### **User Story 13: Seamless Transition from Enrollment to Registration**

**As a** student,  
**I want** to seamlessly proceed from enrollment to registration without unnecessary delays,  
**So that** I can complete my application efficiently in one session if desired.

**Acceptance Criteria:**

- **Immediate Prompt:**
  - Upon successful completion of enrollment, the system should immediately prompt the user to proceed to the registration phase.
- **Information Carry-Over:**
  - Relevant information collected during enrollment should be pre-populated in the registration forms where applicable to avoid redundant data entry.
- **Option to Pause:**
  - Users should have the option to pause and return to registration at a later time if needed, with progress saved accordingly.
- **Clear Instructions:**
  - Provide clear explanations of what additional information and documents are required in the registration phase.
- **Progress Tracking:**
  - Maintain progress indicators showing the user's advancement through the entire application process, including both enrollment and registration phases.

#### **User Story 14: Comprehensive Registration Form Completion**

**As a** student,  
**I want** to provide all necessary additional information during registration,  
**So that** my application is complete and ready for evaluation.

**Acceptance Criteria:**

- **Form Sections:**
  - The registration form should include detailed sections such as:
    - **Academic Background**
    - **Previous Education Records**
    - **Emergency Contact Information**
    - **Medical Information (if applicable)**
    - **Additional Program-Specific Details**
- **Field Guidance:**
  - Each field should include contextual help or tooltips explaining what information is required and acceptable formats.
- **Conditional Fields:**
  - Implement dynamic fields that appear based on previous answers to collect relevant information efficiently.
- **Document Uploads:**
  - Prompt for additional documents as required (e.g., transcripts, immunization records), with clear instructions and supported formats.
- **Data Verification:**
  - Include validation checks to ensure data consistency and completeness before allowing submission.
- **Review and Edit:**
  - Provide a comprehensive review page summarizing all entered information before final submission, with options to edit any section as needed.

#### **User Story 15: Digital Signature and Legal Compliance in Registration**

**As a** student,  
**I want** to securely digitally sign my registration forms,  
**So that** I can fulfill legal requirements and officially submit my application.

**Acceptance Criteria:**

- **Signature Prompt:**
  - After completing all registration fields, the system should prompt for a digital signature.
- **E-Signature Integration:**
  - Utilize a compliant digital signature solution (e.g., DocuSign, Adobe Sign) that meets all legal and regulatory standards.
- **Signature Methods:**
  - Allow users to sign by:
    - **Drawing** their signature using a mouse or touch screen.
    - **Typing** their name with appropriate font styles.
    - **Uploading** an image of their handwritten signature.
- **Consent and Acknowledgement:**
  - Include a consent checkbox confirming that the user has read and agrees to all terms and conditions, with links to relevant policies.
- **Signature Verification:**
  - Implement mechanisms to verify the authenticity of the signature, such as email/SMS confirmation codes if required.
- **Audit Trail:**
  - Maintain a secure audit trail recording the date, time, and IP address associated with the signature for legal purposes.
- **Confirmation Receipt:**
  - Provide a signed copy of the registration form to the user via email/SMS for their records.

#### **User Story 16: Application Review and Approval Process**

**As a** admissions officer,  
**I want** to review and approve student applications efficiently,  
**So that** we can process enrollments in a timely and organized manner.

**Acceptance Criteria:**

- **Administrative Dashboard:**
  - Provide a dedicated dashboard for admissions officers to view, filter, and manage incoming applications.
- **Application Overview:**
  - Each application should display key information at a glance, including applicant details, completion status, and submission timestamps.
- **Detailed Review:**
  - Officers should be able to access full application details, including all entered information and uploaded documents.
- **Commenting and Feedback:**
  - Include functionality for officers to add internal comments and notes on applications.
  - Provide the ability to request additional information or corrections from applicants through the system, triggering notifications on the student's dashboard.
- **Approval Workflow:**
  - Implement a clear workflow for approving, rejecting, or placing applications on hold, with appropriate status updates communicated to the applicant.
- **Automated Notifications:**
  - Upon decision, automated notifications should be sent to applicants informing them of the outcome and next steps.
- **Reporting and Analytics:**
  - Provide reporting tools to track application volumes, processing times, and other key metrics for operational insights.

#### **User Story 17: Handling Rejected or Incomplete Applications**

**As a** student,  
**I want** to understand why my application was rejected or marked incomplete,  
**So that** I can take appropriate actions to address issues and reapply if possible.

**Acceptance Criteria:**

- **Clear Communication:**
  - If an application is rejected or marked incomplete, the system should notify the student with clear reasons and detailed feedback.
- **Resolution Guidance:**
  - Provide specific instructions on how to address the issues, including links to relevant forms or support resources.
- **Opportunity to Reapply:**
  - Allow students to update and resubmit their applications after addressing the cited issues.
- **Support Access:**
  - Offer direct access to support channels (chat, email, phone) for students to seek further clarification or assistance.
- **Status Tracking:**
  - Update the application status accordingly upon resubmission, with real-time tracking available on the dashboard.
