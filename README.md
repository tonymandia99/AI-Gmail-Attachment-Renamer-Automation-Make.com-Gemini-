# AI-Gmail-Attachment-Renamer-Automation-Make.com-Gemini-

🔹 Goal

To automatically process incoming Gmail attachments by using AI (Gemini) to generate descriptive filenames, upload files into Google Drive, and log results into Google Sheets — removing manual steps and ensuring audit-ready file management.
🔗 Workflow Demo (Make.com): 

🔗 Google Sheets Log (Sample)

🔹 Problem It Solves

Manual effort: No more downloading, renaming, and re-uploading attachments.

Inconsistent filenames: AI ensures meaningful, standardized file naming.

Lost files: Files are auto-organized into the correct Google Drive folder.

Poor tracking: Google Sheets log provides full traceability (timestamp, old/new filename, type, link).

Workflow inefficiency: The automation replaces repetitive admin tasks with a clean, end-to-end process.

🔹 Project Goal

Build a Make.com workflow that:

Detects incoming Gmail attachments

Uses Gemini AI to analyze content (PDF, XLSX, CSV — excluding Google Docs due to API limits)

Generates a descriptive filename automatically

Renames and uploads the file to a specified Google Drive folder

Logs details (timestamp, original filename, new filename, type, link) in Google Sheets

Optionally sends a summary email after processing

🔹 Features

✅ Gmail monitoring for attachments
✅ AI-powered file renaming with Gemini
✅ Google Drive structured storage
✅ Google Sheets logging for auditability
✅ Optional summary email notifications
✅ Modular, clean Make.com scenario design

🔹 Tech Stack

Make.com (Integromat) – workflow automation

Gmail API – fetch incoming attachments

Gemini API – AI content understanding & renaming

Google Drive API – file storage & management

Google Sheets API – structured logging

🔹 Deliverables

Fully functional Make.com scenario file (workflow.make.json)

PNG screenshots of Gmail trigger and Google Sheets log

Documentation (README.md) with setup & customization guide
