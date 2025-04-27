# DGCA CPL Exam Prep Suite - Data Repository

**âš ï¸ IMPORTANT: This repository MUST be kept PRIVATE. âš ï¸**

This repository serves as the central data store for the DGCA CPL Exam Prep Suite desktop application. It contains:

*   User authentication data (uth/)
*   Question banks (questions/)
*   Test definitions (	ests/)
*   Student results (esults/)
*   Flagged questions (lags/)
*   Media assets for questions (media/)
*   Announcements (nnouncements.md)
*   Optional: Glossary, Moderator Logs, User Notes, Reference Assets

## Structure

*   **uth/**: Contains credentials.json with user details (hashed passwords).
*   **questions/**: Holds subject-specific question banks in JSON format (e.g., ir_regulations.json).
*   **	ests/**: Contains JSON definitions for specific tests created by moderators.
*   **esults/**: Stores individual student test attempt results, organized by username.
*   **lags/**: Stores lists of question IDs flagged by users during tests.
*   **media/**: Contains image and diagram files referenced in questions.
*   **logs/**: (Optional) Contains audit logs, like moderator actions.
*   **
otes/**: (Optional) Stores user-specific notes.
*   **ssets/references/**: (Optional) Stores reference PDFs/documents uploaded by moderators.
*   **nnouncements.md**: A simple file for general announcements.
*   **glossary.json**: (Optional) Definitions for terms and acronyms.

## Application Configuration

The desktop application needs to be configured with the URL of this repository and a GitHub Personal Access Token (PAT) with appropriate read/write permissions to interact with this data. Ensure the PAT is handled securely by the application.
