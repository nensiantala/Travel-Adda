# 🌍 Travel Adda - Online Travel Booking Platform

**Travel Adda** is a fully functional PHP-based travel booking website that allows customers to explore travel packages, book trips, share feedback, and track their bookings. It also includes admin and agent dashboards for managing packages, bookings, feedback, and analytics with real-time charts.

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, Bootstrap 5, JavaScript (AJAX)
- **Backend**: PHP (Core PHP)
- **Database**: MySQL
- **Libraries**: Chart.js, PHPMailer
- **Tools**: VS Code, XAMPP/LAMP, Git

---

## 📁 Project Structure
<img width="264" height="595" alt="image" src="https://github.com/user-attachments/assets/a0360f74-7e57-4650-9d3d-303abc475d83" />
<img width="269" height="568" alt="image" src="https://github.com/user-attachments/assets/5a245d5e-65c2-401e-8006-05a100dc066f" />



---

## ✨ Features

### 👤 Customer Panel
- Registration/Login
- Browse packages with images, ratings, trip duration, and date range
- View detailed itinerary (Day-wise activities)
- Book packages
- Rate and give feedback
- View My Bookings

### 🔐 Admin Panel
- Admin login
- Dashboard overview
- Manage Packages (Add/Edit/Delete)
- Approve/Reject Bookings (with PHPMailer email alerts)
- View Feedback
- Manage Users

### 🧑‍💼 Agent Panel
- Agent Registration (with company details)
- Agent Login
- Dashboard showing:
  - Pending/Accepted/Rejected Bookings
  - Revenue Tracking
  - Real-Time Charts:
    - Monthly Bookings
    - Revenue Trend
    - Package Popularity
- Charts powered by AJAX + Chart.js

### 📊 Analytics
- Real-time chart updates using AJAX
- Separate PHP APIs for agent-specific data
- Combined chart backend for cleaner frontend code

### 📩 Email Integration
- Confirmation emails using **PHPMailer**
- Email on:
  - Booking success
  - Booking approval
  - Booking rejection

---

## 💾 Database Tables

- `customers` - Customer details
- `agents` - Agent profile and login info
- `admins` - Admin credentials
- `packages` - Travel package details (images, date, price, itinerary)
- `bookings` - Booking records with status
- `feedback` - 5-star rating + comment system
- `payments` *(optional)* - Extendable for online payments
- `itinerary` - Stored in a structured format: `Day|Title|Duration`

---

## 💡 Special Functionalities

- ⭐ **Feedback system**: Dynamic 5-star feedback with average ratings
- 📅 **Date management**: Packages include `start_date`, `end_date`, `duration`
- 🧭 **Show More / Show Less**: For package description and feedback
- 🖼 **Image upload**: Admin adds images to packages
- 📈 **Charts**: 4 agent charts (bookings, revenue, status, popularity)
- 🧩 **Modular structure**: `header.php`, `footer.php`, and unified CSS

---

## 🔧 Setup Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/nensiantala/Travel-Adda.git
Import the SQL file into your MySQL database.

Configure db_connect.php with your DB credentials.

Start your local server (XAMPP/WAMP/LAMP).

Open http://localhost/travel-adda/index.php

## Screenshots:

   <img width="1292" height="2374" alt="image" src="https://github.com/user-attachments/assets/6124dd10-1910-41f9-b6ad-17ec13450454" />
   <img width="1292" height="2923" alt="image" src="https://github.com/user-attachments/assets/c4391417-e61a-4614-8cdc-733191ae9628" />
   <img width="1292" height="1660" alt="image" src="https://github.com/user-attachments/assets/049572f7-dd4a-4624-a667-9ad7235d1e2f" />
   <img width="1292" height="983" alt="image" src="https://github.com/user-attachments/assets/85972144-8581-414d-94bf-3b3cb84254cd" />
   <img width="1292" height="2611" alt="image" src="https://github.com/user-attachments/assets/5cfbf24e-5f0e-41af-855b-5aef42b84cd9" />
   <img width="1292" height="1273" alt="image" src="https://github.com/user-attachments/assets/82b280ca-e6aa-4dbb-a6d8-89d71ae88877" />


   




