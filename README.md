# 🎉 Event Management System  

A simple **event management web application** built with **HTML, TailwindCSS, and vanilla JavaScript**.  
This project includes two user roles — **Admin** and **Attendee** — each with their own dashboard, features, and navigation flow.  

---

## 🚀 Features  

### 🔑 Authentication  
- Login page with option to choose **Attendee** or **Admin** role.  
- New student registration page.  

### 👨‍💻 Admin Side  
- **Dashboard** with upcoming events and stats overview.  
- **Create Events** page to add new events.  
- **QR Code Scan** page for attendee check-in.  
- **Analytics & Feedback** pages for event insights.  
- **Settings** for managing account and preferences.  

### 👩‍🎓 Attendee Side  
- **Dashboard** with upcoming events.  
- **Explore Events** page to discover new events.  
- **Feedback Form** to share event reviews.  
- **Profile / Settings** page for managing account.  

---

## 📂 Project Structure  

```

event-management/
│── index.html              # Login Page
│── register.html           # Register Page
│── admin-dashboard.html    # Admin Dashboard
│── admin-create-event.html # Admin Create Event
│── admin-feedback.html     # Admin Feedback
│── admin-analytics.html    # Admin Analytics
│── admin-settings.html     # Admin Settings
│── attendee-dashboard.html # Attendee Dashboard
│── upcoming-events.html    # Attendee Upcoming Events
│── explore.html            # Explore Events (Attendee)
│── settings.html           # Attendee Settings/Profile
│── feedback.html           # Feedback Form
│── profile.html            # Attendee Profile
│── scan-qr.html            # QR Code Scan (Admin)
│
├── assets/
│   ├── style.css           # Custom Styles
│   └── script.js           # JS for navigation & form handling

````

---

## ⚡️ Tech Stack  

- **Frontend**: HTML, TailwindCSS  
- **Scripting**: JavaScript (Vanilla)  
- **Styling**: Custom CSS + Tailwind classes  
- **Icons**: Google Material Symbols  

---

## 🔄 Flow  

### Admin  
1. Login → Admin Dashboard  
2. Create events, view attendees, scan QR, check analytics & feedback.  

### Attendee  
1. Login → Attendee Dashboard  
2. Browse upcoming events, explore events, give feedback, manage profile.  

---

````

2. Navigate into the folder:

   ```bash
   cd event-management
   ```
3. Open `index.html` in your browser to start.

---

## 📌 Notes

* No backend/database is included — this is a **frontend prototype**.
* Navigation between pages is handled by **JavaScript redirection**.
* You can extend it by adding:

  * Authentication with Firebase/Auth0.
  * Database (MySQL, MongoDB, PostgreSQL).
  * API for event creation and attendee management.

---



Built with ❤️ by Tripathi

