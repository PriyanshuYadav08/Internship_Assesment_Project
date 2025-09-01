# Wedding Planner App

A mini **Wedding Planning App** built in **Kotlin (Native Android)** as part of an internship assignment.  
The app helps users manage their wedding tasks, venues, budget, and guest list in a clean and wedding-themed interface.  

---

## 📌 Features

### 🔐 Authentication
- User **Signup/Login** with email or mobile number.  
- Data stored locally (SQLite/SharedPreferences).  

### ✅ Wedding Checklist
- Preloaded checklist (e.g., Venue Booking, Catering, Photography, Mehendi, Sangeet, Honeymoon).  
- Add, edit, and mark tasks as completed.  
- Progress bar showing overall completion.  

### 🏨 Venue Listing
- Browse **5–10 wedding venues** with:
  - Name  
  - Location  
  - Price Range  
  - Capacity  
- Filter venues by **budget** and **capacity**.  
- Static dummy data (no backend).  

### 💰 Budget Calculator (Bonus)
- Enter total wedding budget.  
- Auto-calculate simple breakdown:
  - Venue (40%)  
  - Catering (30%)  
  - Décor (20%)  
  - Misc (10%)  
- Visualized using a **Pie Chart** (MPAndroidChart).  

### 👥 Guest List Management (Bonus)
- Add guest name + phone number.  
- Track RSVP status (Yes / No / Maybe).  
- Edit or delete guests.  
- Stored locally in SQLite.  

### 🎨 UI & Creativity
- Wedding-themed colours (pastel pink, gold, maroon).  
- Clean, modern design.  
- Smooth transitions and animations.  

---

## 🏗️ Tech Stack

- **Language:** Kotlin  
- **Architecture:** MVVM  
- **Database:** Room (SQLite) + SharedPreferences  
- **UI:** XML Layouts, RecyclerView, BottomNavigationView  
- **Libraries:**
  - [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) → Budget Pie Chart  
  - [Lottie](https://airbnb.io/lottie/#/) → Animations 

---

## 🚀 App Flow

1. **Splash Screen** → App logo + animation.  
2. **Login/Signup** → User authentication (local storage).  
3. **Dashboard (BottomNavigation):**  
   - **Checklist Tab** → Manage wedding tasks.  
   - **Venues Tab** → Browse venues + filter.  
   - **Budget Tab (Bonus)** → Budget calculator + chart.  
   - **Guests Tab (Bonus)** → Guest list + RSVP.  
4. Data persists across app launches.  

---

## ⚡ How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/PriyanshuYadav08/Internship_Assesment_Project.git
