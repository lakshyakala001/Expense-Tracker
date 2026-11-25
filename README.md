# ExpenseFlow
A minimal expense-tracking web app demo built with HTML, CSS and vanilla JavaScript.

## Run
Open `index.html` in a modern browser. The app uses browser localStorage for demo persistence.

## Admin demo credentials
- Username: `admin`
- Password: `admin123`

Admin credentials are not displayed in the login UI.

## User workflow
1. Create a user account from Sign up.
2. Admin signs in and approves or rejects the registration.
3. Approved user signs in and adds, edits, deletes, filters and sorts expense entries.
4. User dashboard and analytics display category totals.
5. Admin may suspend or reinstate approved accounts and view activity log.

## Important limitations
This is a front-end demonstration, not a production-secure financial service. Authentication and data are stored locally in browser storage; passwords are not hashed, there is no server/database, and the admin account is seeded client-side. Users sharing the same browser profile can potentially inspect or modify local data. For production, use a backend (e.g. Node/Express), database, hashed passwords, server-side authorization, secure session handling, validation, and audit logging.
