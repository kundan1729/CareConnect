

```markdown
# 🏥 Hospital Management System

This is a **Hospital Management System** built using **Laravel + Jetstream**, enhanced with the **Corona Admin Dashboard** for a modern, responsive UI experience. It streamlines core hospital operations such as appointment booking, attendance tracking, and user management.

---

## ✨ Features

- 🔐 **Jetstream Authentication**
  - Login, Registration, Email Verification
  - Profile Management
  - Two-Factor Authentication (2FA)
  - Session Management
- 👨‍⚕️ Doctor & Staff Dashboard
- 📅 Patient Appointment Booking
- 📊 Admin Panel with Corona Dashboard UI
- 🧾 Payment System (Coming Soon)
- 🌐 Fully Responsive UI (Tailwind + Corona Template)

---

## 🎨 Admin Dashboard UI

This project integrates the **[Corona Admin Dashboard](https://www.bootstrapdash.com/product/corona-admin-template/)** for an elegant and intuitive user interface. It includes:

- Sidebar navigation
- Interactive charts
- Cards and widgets for key metrics
- Light/Dark Mode ready

---

## 🚀 Deployed Link

[![Coming Soon](https://img.shields.io/badge/Deployed-Link--Coming%20Soon-orange?style=for-the-badge&logo=laravel)](#)

> 🌐 **Live demo is coming soon! Stay tuned for updates.**

---

## 🛠️ Tech Stack

- **Backend**: Laravel 10 + Jetstream
- **Frontend**: Blade, Tailwind CSS, Corona Admin Template
- **Authentication**: Laravel Jetstream (Livewire or Inertia.js)
- **Database**: MySQL
- **Other Tools**: Laravel Sanctum, Composer, NPM

---

## ⚙️ Installation

```bash
git clone https://github.com/kundan1729/hospital-management.git
cd hospital-management
composer install
npm install && npm run build
cp .env.example .env
php artisan key:generate
```

### 🛢️ Configure your `.env` file

Update the following lines in `.env` with your DB credentials:

```env
DB_DATABASE=hospital
DB_USERNAME=root
DB_PASSWORD=your_password
```

### 🗄️ Run migrations

```bash
php artisan migrate
```

### 🚀 Serve the application

```bash
php artisan serve
```

Visit `http://localhost:8000` to view the app.

---

## 👨‍⚕️ User Roles

- **Admin**: Manage doctors, staff, appointments, and system settings.
- **Doctor**: View appointments, manage patient records, mark attendance.
- **Staff**: Assist with hospital operations and attendance.
- **Patient**: Register, login, and book appointments.

---

## 📸 Screenshots
![Uploading image.png…]()

![image](https://github.com/user-attachments/assets/62ec708d-0528-4fa6-8c4d-ebdf7a248fd3)

![Screenshot 2025-04-25 221824](https://github.com/user-attachments/assets/c143e982-ef8c-42c8-b95f-932d4678b052)
![Screenshot 2025-04-25 222143](https://github.com/user-attachments/assets/4d942c05-b15e-45de-a749-5e8c11f464bd)

![Screenshot 2025-04-25 222244](https://github.com/user-attachments/assets/35115d1e-e7dc-4810-8e9e-dc68cf061bbf)
![Screenshot 2025-04-25 222256](https://github.com/user-attachments/assets/436e2df5-22e9-4dba-aa0d-95747e940b97)




_ currntly working on admin dasboard  UI ,screen Coming soon…_

---

## 👨‍💻 Author

**Kundan Kumar**  
GitHub: [@kundan1729](https://github.com/kundan1729)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
```

---

Let me know if:
- You want to add dashboard screenshots with the Corona template in action
- You’d like a markdown badge for Corona Admin
- You're ready to replace the "Coming Soon" with your deployed URL

Great work combining Jetstream and Corona — that's a power move! 🔥
