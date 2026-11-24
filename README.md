---


## Taskvise

A full-stack manpower management system built with **React, TypeScript, TailwindCSS, Node.js, and Firebase**.  
This application provides role-based dashboards for **Admin, Manager, and Employee**, helping organizations streamline employee, project, and task management.



## Features

- **Authentication & Authorization**
  - Login, Signup, and Role-based access (Admin, Manager, Employee)
  - Protected routes with JWT/Firebase

- **Dashboards**
  - **Admin Dashboard**: Manage employees, projects, and overall reports
  - **Manager Dashboard**: Track team progress, assign tasks, and view reports
  - **Employee Dashboard**: Manage profile, view tasks, submit leaves, and time tracking

- **Employee Management**
  - Add, edit, and manage employee records
  - Role-based permissions

- **Project & Task Management**
  - Assign projects to teams
  - Track tasks and deadlines
  - Gantt charts for project progress

- **Notifications**
  - In-app notification panel
  - Alerts for tasks, deadlines, and updates

- **Time Tracking**
  - Employee attendance and work hours monitoring

---

## Screenshots

### Authentication
![Login Page](<img width="1917" height="867" alt="image" src="https://github.com/user-attachments/assets/75be8cf5-1e47-4df0-a82d-2c1f4703768d" />)

### Admin Dashboard
![Admin Dashboard](<img width="1919" height="871" alt="image" src="https://github.com/user-attachments/assets/3a89af66-3a01-4034-85a7-670ec551b551" />)

### Manager Dashboard
![Manager Dashboard](<img width="1918" height="869" alt="image" src="https://github.com/user-attachments/assets/87e803e2-9bfb-476c-aac7-72956635beae" />)

### Employee Dashboard
![Employee Dashboard](<img width="1913" height="873" alt="image" src="https://github.com/user-attachments/assets/4b094c2b-05f4-4fba-8d3c-7bf133d09abc" />)

### Project Tracking (Gantt Chart)
![Gantt Chart](./screenshots/gantt.png)


---

## Tech Stack

**Frontend:**
- React + TypeScript
- TailwindCSS
- Vite

**Backend & APIs:**
- Node.js / Express
- Firebase (Auth, Firestore, Notifications)

**Other Tools:**
- PostCSS
- shadcn/ui (prebuilt components)
- Chart libraries for dashboards

---

## Project Structure

```

manpower/
├── public/                # Static assets
├── src/
│   ├── components/
│   │   ├── admin/         # Admin dashboard components
│   │   ├── employee/      # Employee views
│   │   ├── dashboard/     # Shared dashboard components
│   │   ├── auth/          # Login, Signup, Auth provider
│   │   ├── charts/        # Gantt charts and stats
│   │   ├── layout/        # Layouts and Protected Routes
│   │   ├── ui/            # Reusable UI components (shadcn/ui)
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── ...
├── server.js              # Backend server
├── package.json
├── tailwind.config.ts
├── tsconfig.json
├── vite.config.ts
└── .env                   # Environment variables

````

---

## Installation & Setup

### 1Clone the repository
```bash
git clone https://github.com/your-username/manpower.git
cd manpower
````

### 2Install dependencies

```bash
npm install
```

### 3Set up environment variables

Create a `.env` file in the root directory:

```env
PORT=5000
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
```

### 4Run the development server

```bash
npm run dev
```

### 5Build for production

```bash
npm run build
```

---

## Usage

* **Admin**: Manage employees, assign projects, and generate reports
* **Manager**: Assign tasks, track project timelines, and monitor team performance
* **Employee**: View tasks, track time, apply for leaves, and manage profile

---

## Contributing

1. Fork the repo
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

---

## License

This project is licensed under the **MIT License**.
Feel free to use and modify as per your needs.

```

---

Would you like me to also **add example screenshots (placeholders)** inside the README (like `![Dashboard Screenshot](./screenshots/dashboard.png)`), so your GitHub page looks more attractive?
```
