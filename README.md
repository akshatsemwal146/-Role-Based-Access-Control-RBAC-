# RBAC-VRV-Security
 Role-Based Access Control (RBAC)
# User Management System (RBAC-VRV-Security)

A **User Management System** built with **React-JS** for managing users and roles in a dynamic table format. This app allows you to add, edit, and delete users and roles, with persistent data stored using `localStorage`.

## Features

### User Management
- **Add Users**: Easily add new users by filling out a form with details like name, email, and role. The email input is validated for correct format.
- **Edit Users**: Modify existing user details by clicking the "Edit" button in the table. The form is pre-filled with the user's current details.
- **Delete Users**: Permanently remove users from the system by clicking the "Delete" button.

### Role Management
- **Create and Assign Roles**: Define roles that can be assigned to users during addition or editing. Roles help in managing user permissions effectively.

### Responsiveness
- Designed to work seamlessly on both desktop and mobile devices. Tables and forms adjust gracefully to different screen sizes.

### Data Persistence
- **localStorage** is used to ensure data remains available even after a page refresh.

---

## Technologies Used
- **React**: For building a dynamic and responsive user interface.
- **Tailwind CSS**: For sleek styling and responsiveness.
- **localStorage**: For persisting user and role data.

---

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Node.js** (LTS version recommended)
- **npm** (comes with Node.js)

### Clone the Repository
```bash
git clone https://github.com/akshatsemwal146/RBAC-VRV-Security
cd RBAC-VRV-Security
Install Dependencies
Run the following command to install all required dependencies:

bash
Copy code
npm install
Start the Application
Launch the app locally with:

bash
Copy code
npm start
The application will be accessible at http://localhost:3000 in your web browser.

How to Use
Create Roles:

Start by creating roles to assign to users.
Add Users:

Click the "Add User" button to fill out a form with details like name, email, role, and status.
Edit Users:

Click the "Edit" button next to a user's record in the table to modify their details.
Delete Users:

Click the "Delete" button to permanently remove a user.
Project Workflow
User Actions
All user actions (add, edit, delete) update localStorage for data persistence.
Data is loaded from localStorage whenever the page is refreshed.
Role Management
Roles can be assigned to users, helping to control their access and permissions.
Folder Structure
The project has the following structure:

bash
Copy code
src/
├── components/      # React components for User and Role Management
├── styles/          # Tailwind CSS configurations
├── utils/           # Utility functions for localStorage handling
├── App.js           # Main application file
├── index.js         # Entry point
Contribution Guidelines
Contributions are welcome! If you have ideas for new features or improvements:

Fork this repository.
Create a new branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add feature-name'.
Push to the branch: git push origin feature-name.
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
React Documentation: For clear and concise guidance on building React apps.
Tailwind CSS: For an efficient styling workflow.
Community contributions and feedback.
