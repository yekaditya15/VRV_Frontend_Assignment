

# User and Role Management Dashboard

A modern web application built using React, Ant Design, and React Router for managing user roles and users. This application features a responsive layout, role-based access control, and user management functionalities. It is designed to be an easy-to-use interface for managing users and their respective roles within an organization.

### Live Demo: [View the live application](https://vrv-frontend-assignment.vercel.app/)

## Features

- **Role Management**:
  - Create, update, and delete roles.
  - Assign specific permissions (Read, Write, Delete) to each role.

- **User Management**:
  - View and manage users.
  - Assign roles to users.
  - Update user status (active/inactive).

- **Search Functionality**:
  - Search users and roles by name or keyword.
  - Easily filter through users or roles with an intuitive search bar in the UI.

- **Responsive UI**:
  - Built with Ant Design components for a modern and clean UI.
  - Mobile-friendly layout.

- **Routing and Navigation**:
  - Utilize React Router for seamless navigation between different sections (Home, User Management, Role Management).


## Tech Stack

- **Frontend**:
  - React
  - React Router
  - Ant Design
  - JavaScript (ES6+)
  
- **Development Tools**:
  - Node.js
  - npm (or yarn)

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** (v6 or higher) or **yarn**

## Getting Started

Follow these steps to get your project up and running:

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### 2. Install Dependencies

Run the following command to install the necessary dependencies:

```bash
npm install
```

or if you are using yarn:

```bash
yarn install
```

### 3. Run the Application

After the dependencies are installed, run the application with the following command:

```bash
npm start
```

or with yarn:

```bash
yarn start
```

The application will start on [http://localhost:3000](http://localhost:3000).

### 4. Folder Structure

Here’s a breakdown of the folder structure:

```
/src
  /components        # Reusable components (e.g., User Management, Role Management)
  /services          # API functions to manage data
  App.js            # Main app file where routing and layout are defined
  index.js          # Entry point of the React application

```

### 5. Modify Data (Optional)

The data (users, roles, permissions) is stored in a mock array inside the `services` folder. If you wish to modify the data, you can change the contents of `rolesData` and `usersData` in `services` to add or remove roles and users.

```js
let rolesData = [
  { id: 1, roleName: "Admin", permissions: ["Read", "Write", "Delete"] },
  { id: 2, roleName: "User", permissions: ["Read"] },
];

let usersData = [
  { id: 1, username: "johnDoe1", email: "john@example.com", role: "Admin", status: "active" },
  { id: 2, username: "janeSmith3", email: "jane@example.com", role: "User", status: "active" },
];
```

### 6. Test the Application

Once the app is running locally, you can test the following features:

- **Home Page**: The landing page of the application.
- **User Management**: View users, add new users, edit existing users, or delete users.
- **Role Management**: Create, update, and delete roles and assign permissions to roles.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.





