
# AuthDash - Personal Expense Tracker

This project is a React-based single-page application (SPA) created for a Software Configuration Management (SCM) mini project.

## Features
- **Mock Authentication**: Login validation against a local data source.
- **Persistent Data**: Uses browser `localStorage` to save and retrieve expenses.
- **Responsive UI**: Built with Tailwind CSS for a mobile-first, clean experience.
- **Route Protection**: Ensures only authenticated users can access the dashboard.

## SCM Notes
- **Version Control**: Follow standard Git flow (feature branches, pull requests).
- **Environment**: No backend required. Runs locally via development server.
- **Deployment**: Can be hosted as a static site using GitHub Pages or similar.

## Data Schema
- **User**: `{ username, role, password }`
- **Expense**: `{ id, amount, category, description, date }`
