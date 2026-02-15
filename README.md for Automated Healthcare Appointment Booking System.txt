
## 🏥 Automated Healthcare Appointment Booking System (n8n)

### Overview

This workflow automates the end-to-end process of booking healthcare appointments using Google Forms, Google Sheets, Google Calendar, and Gmail.
It validates appointment availability, schedules confirmed bookings, sends automated emails, and logs all appointments—completely hands-free.

---

### 🔁 Workflow Flow

1. **Google Form Submission**

   * Patient submits appointment details via Google Form.
2. **Google Sheets Trigger**

   * Triggers workflow when a new response is added.
3. **Date & Time Normalization**

   * Combines preferred date and time into a single datetime value.
4. **Appointment Duration Logic**

   * Automatically sets a 30-minute appointment window.
5. **Google Calendar Availability Check**

   * Verifies if the selected time slot is available.
6. **Conditional Logic**

   * If unavailable → send rejection email
   * If available → create calendar event
7. **Confirmation Email**

   * Sends booking confirmation to the patient.
8. **Booking Log**

   * Appends confirmed appointments to a tracking Google Sheet.

---

### 🛠️ Tools & Integrations

* n8n
* Google Forms
* Google Sheets
* Google Calendar
* Gmail
* JavaScript (Code Node)

---

### ✅ Key Features

* Automatic availability validation
* Zero double-booking
* Real-time email notifications
* Centralized appointment tracking
* Fully no-code/low-code automation

---

### 👨‍💻 My Role

* Workflow architecture & logic
* API & Google integrations
* Error handling & validation
* End-to-end automation design

---

### 🚀 Use Cases

* Clinics & hospitals
* Private practitioners
* Telemedicine platforms
* Appointment-based services

---


