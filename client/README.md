# QuickEMS — Frontend

QuickEMS is a web-based Employee Management System that simplifies employee administration, attendance tracking, leave management, and payslip access through role-based dashboards.

## Tech Stack

- **React.js + Vite** — Frontend development
- **Tailwind CSS** — Styling
- **React Router** — Navigation
- **Axios** — REST API communication
- **Context API** — Authentication state management

## Features

- Admin and employee login
- Role-based dashboards
- Employee management
- Attendance tracking
- Leave applications and approvals
- Payslip viewing and printing
- Profile management

## Getting Started

```bash
cd client
npm install
```

Create a `.env` file in the `client` directory:

```env
VITE_BASE_URL=http://localhost:4000
```

For production, replace the value with your deployed backend URL.

Start the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

## Deployment

The frontend is deployed on Vercel.

- **Root Directory:** `client`
- **Build Command:** `npm run build`
- **Output Directory:** `dist`
- Configure `VITE_BASE_URL` in Vercel Environment Variables.

## API Integration

Axios communicates with the backend REST APIs and attaches the JWT token to authenticated requests.

---

**QuickEMS — Simplifying Employee and HR Management.**
