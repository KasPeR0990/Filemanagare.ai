# Project overview
We are building a file-structurer web app using AI that can access the files/folders you give it permission to. It's a chat space where you prompt what the AI should do. Features include structuring files, maps, or specific storage spaces. Example features are sorting, renaming, creating, and deleting different types of files and folders.

The Front-end will be developed using Next.js 14, ShadCN, TailwindCSS, Lucide icons.  
The Back-end will be developed using Python, OpenAI API key, FastAPI, Firebase.

# Core functionalities

1. **Chat Space**
   - a. Create an interactive chat interface for the frontend.
   - b. Use AI to process natural language input, enabling users to describe their desired actions intuitively.
   - c. Include a clear and structured chat history, showing both user prompts and AI responses.

2. **Sorting**
   - a. By name, type, date created, or size.
   - b. Incorporate AI-driven tagging and grouping based on file content.
   - c. Allow users to toggle between manual sorting options and AI-generated groupings.

3. **Renaming**
   - a. Provide options for batch renaming using consistent naming schemes (e.g., "File_001," "Project2024_Report").
   - b. Include an AI-powered suggestion tool that proposes names tailored to file content.
   - c. Implement a preview function for users to confirm the renaming pattern before applying changes.

4. **Creating & Deleting**
   - a. Controlled operations with clear prompts like "Create a folder named 'Reports'."
   - b. Confirm deletions to prevent accidental data loss.

5. **File Previews**
   - a. Generate image previews using thumbnail creation tools.
   - b. Extract document content for PDFs and text files to create short, informative snippets.
   - c. Optimize the loading of previews for large files or datasets to ensure smooth performance.

6. **Access Control**
   - a. Implement a role-based access system that enables granular permission settings for files and folders.
   - b. Integrate third-party cloud services using APIs (e.g., Google Drive API, Dropbox API).
   - c. Provide an intuitive interface for managing permissions and linking cloud accounts.

7. **User Account**
   - a. Use a secure authentication system like Firebase Authentication or OAuth for login and account management.
   - b. Offer account recovery options, such as password resets via email.
   - c. Allow users to view and manage their account details, including activity history and linked services.

8. **Data Backup**
   - a. Implement a data backup system to periodically save user-selected files and folders.
   - b. Store backups securely in cloud storage services.
   - c. Allow users to restore files from backups if needed.

9. **Building Tools**
   - a. **Front-end**
     - Built with Next.js 14, ShadCN, and TailwindCSS.
     - Lucide icons used for clear navigation.
   - b. **Back-end**
     - Built with Python.
     - Packages used in `packagesinstalled.txt`

# Documentation

Below are code examples demonstrating how to integrate the packages from` to implement the core functionalities of the project.

---

## Packages to Integrate

- 