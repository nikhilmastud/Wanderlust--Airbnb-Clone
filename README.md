# Wanderlust – Airbnb-Style Property Rental Web App

Wanderlust is a web application project inspired by property-rental platforms. It is built with JavaScript, Node.js, Express.js, MongoDB, EJS, and Bootstrap.

> **Project status:** In progress. The repository documentation should reflect only the features implemented in the current codebase.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Templating:** EJS
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Version control:** Git and GitHub

## Project Goals

- Build a web application for browsing property listings.
- Render dynamic pages with EJS templates.
- Use Express.js to handle application routes.
- Store application data in MongoDB.
- Provide a responsive interface using Bootstrap.

## Features

Confirm each feature against the current code before describing it as complete:

- [ ] View all property listings
- [ ] View an individual property's details
- [ ] Create, edit, and delete listings (CRUD)
- [ ] User registration and login
- [ ] User authorization and ownership checks
- [ ] Reviews and ratings
- [ ] Form validation and user-friendly error handling
- [ ] Responsive layouts for mobile and desktop

## Getting Started

### Prerequisites

Install the following before running the project:

- Node.js and npm
- MongoDB local instance or a MongoDB Atlas cluster
- Git

### 1. Clone the repository

```bash
git clone https://github.com/nikhilmastud/Wanderlust.git
cd Wanderlust
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root. Add the environment variables expected by the application, for example:

```env
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=replace_with_a_long_random_secret
```

Use the exact variable names required by the code in this repository. Never commit `.env` or real passwords, tokens, or database credentials to GitHub.

### 4. Start the application

Check `package.json` for the available scripts. If the project defines a `start` script, run:

```bash
npm start
```

If it defines a development script instead, use the corresponding command listed in `package.json`.

Then open the local URL printed by the application in your browser.

## Project Structure

The exact structure depends on the current implementation. A typical Express + EJS application may look like this:

```text
Wanderlust/
├── models/        # Database models
├── routes/        # Express route handlers
├── views/         # EJS templates
├── public/        # CSS, JavaScript, and static assets
├── app.js         # Application entry point (if used by this project)
├── package.json
├── .env           # Local secrets; do not commit
├── .gitignore
└── README.md
```

Only folders and files that actually exist in the project should be listed as part of its final structure.

## Security Notes

- Keep `.env` out of version control.
- Do not publish MongoDB passwords, session secrets, API keys, or personal credentials.
- Use a restricted database user and configure MongoDB Atlas network access appropriately.
- Validate user input on the server side.

## Future Improvements

Potential next steps, depending on the current implementation:

- Improve validation and error pages.
- Add search, filtering, and sorting for listings.
- Improve accessibility and mobile responsiveness.
- Add automated tests.
- Deploy the application and document the live URL.

## Author

**Nikhil Mastud**

GitHub: [nikhilmastud](https://github.com/nikhilmastud)

---

This README is a starting point. Update the feature checklist, project structure, commands, and screenshots after verifying them against the actual source code.
