### Job Completion Certificate Digitization System

This app presents the design and implementation of a digital solution developed to automate the preparation of Job Completion Certificates. The system replaces a previously manual, paper-based process with a streamlined digital workflow, improving efficiency, accuracy, and document management.

## Technologies Used

- Power Apps – User interface for data entry
- SharePoint – Backend data storage
- Power Automate – Workflow automation and document generation

## Key Features

- End-to-end automation of certificate generation
- Digital approval and signing process
- Dynamic document generation using templates
- Automatic PDF conversion
- Email notifications to stakeholders
- Centralized and secure data storage

## How the System Works

 **A Power Apps form provides a user-friendly interface for:**

- Inputting project and vendor details
- Uploading or capturing signatures
- Submitting requests for processing

**Power Automate orchestrates the entire process:**

**Step 1: Trigger**
- The workflow is triggered when a form is submitted from Power Apps.

**Step 2: Data Retrieval**
- The system retrieves submitted data from the SharePoint list.

**Step 3: Approval Process**
- An approval email is sent to the designated approver.
- The approver reviews the request via a link provided in the email.
- The approver signs/approves the request digitally.

**Step 4: Document Generation**
- A predefined Microsoft Word template is populated dynamically with:
- Project details
- Vendor information
- Financial data
- Signature images

**Step 5: PDF Conversion**
- The populated Word document is automatically converted into a PDF file.

**Step 6: Notification**
- The final PDF certificate is sent via email to the requester.


## Benefits of the Application

- **Efficiency:** Reduces processing time significantly
- **Accuracy:** Minimizes human errors in documentation
- **Traceability:** Maintains audit trail of approvals and submissions
- **Accessibility:** Enables remote approval and document access
- **Scalability:** Can be extended to other documentation workflows

## Screenshots
- Contains images of the app interface