# AI Life Admin — Systematic Frontend V4

## What changed

This is a clean, user-driven frontend prototype.

### 1. Login / Signup first
- Login page is shown before the dashboard.
- Create account stores a prototype profile in browser localStorage.
- Each email gets a separate empty workspace.
- Logout is available in the sidebar.
- **This is frontend-only authentication for the prototype.** Real secure authentication will be implemented with the Node/Express + MongoDB backend.

### 2. No pre-filled personal data
After signup, the workspace starts empty. The user/client must add their own:
- Tasks
- Client tasks
- Calendar events
- Notes
- Goals
- Habits
- Health logs
- Income
- Expenses
- Bills
- Document metadata

### 3. Menubar includes all major modules
- Dashboard
- AI Assistant
- Tasks & Client Work
- Calendar
- Notes
- Goals
- Routine & Habits
- Health
- Finance & Expenses
- Bills & Payments
- Documents
- Analytics
- Settings

### 4. Client task management
The Add Task modal supports:
- Myself or Client
- Client/user name
- Priority
- Due date
- Category
- Pending/completed status

### 5. Themes
- Light Mode
- Dark Mode
- Glass Executive / Glassmorphic

Theme preference is saved in localStorage.

## Run

1. Extract the ZIP.
2. Open the extracted folder in VS Code.
3. Open `index.html`.
4. Right click → **Open with Live Server**.
5. Create an account.
6. Add your own tasks/data.

## Next backend phase

Replace prototype localStorage authentication/data with:
- Node.js + Express
- MongoDB
- bcrypt password hashing
- JWT authentication
- User-specific records
- Client/user relationships
- Real CRUD APIs
- Secure server-side AI integration
- File storage
- Notifications/reminders
