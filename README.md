# Calestra Academy (Temporary README.md will be updated soon)

![Calestra Academy Logo](/src/assets/calestra.jpg)

Calestra Academy is a fictional school website project made for learning and practicing web development.

The project is planned to have a public website, student portal, and admin dashboard.

## Flowchart

![Calestra Academy Flowchart](/src/assets/temporary-flowchart.png)

## Project Structure

This is the **temporary project structure**. It may change as development continues.

```text
calestra-academy/
├── src/
│   ├── components/
│   │   ├── common/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── Button.jsx
│   │   │   └── Card.jsx
│   │   ├── student/
│   │   │   └── StudentSidebar.jsx
│   │   └── admin/
│   │       └── AdminSidebar.jsx
│   │
│   ├── layouts/
│   │   ├── PublicLayout.jsx
│   │   ├── StudentLayout.jsx
│   │   └── AdminLayout.jsx
│   │
│   ├── pages/
│   │   ├── public/
│   │   │   ├── Beranda.jsx
│   │   │   ├── Login.jsx
│   │   │   └── PPDB.jsx
│   │   ├── student/
│   │   │   ├── Dashboard.jsx
│   │   │   └── ProfilSiswa.jsx
│   │   └── admin/
│   │       ├── Dashboard.jsx
│   │       ├── ManajemenSiswa.jsx
│   │       └── InputNilai.jsx
│   │
│   ├── guards/
│   │   ├── ProtectedRoute.jsx
│   │   └── AdminRoute.jsx
│   │
│   ├── context/
│   │   └── AuthContext.jsx
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── index.html
├── package.json
└── vite.config.js
```

### Structure

* `components/` → Reusable components.
* `layouts/` → Page layouts for public, student, and admin sections.
* `pages/` → Pages based on their respective sections.
* `guards/` → Handles protected routes and admin access.
* `context/` → Global authentication state.
* `App.jsx` → Application routing.
* `main.jsx` → Application entry point.

## Status

**In Development 🚧**

The project is still under development. The structure, features, and implementation may change during development.

## Purpose

This project is made for learning purposes and is not affiliated with any real school or institution.