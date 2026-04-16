# Mess Portal 🍽️
**A D3 Fest Hackathon Submission**

Develop a comprehensive solution for mess management to remove the hassle of buying paper coupons and provide a centralized platform for both students and administrators. 

### 🧱 Problem Statement (D3H05)
The solution provides necessary facilities to the mess admin and the students. For mess admins, they can manage coupons, menu details, and pricing via a dedicated dashboard. Students can buy coupons from their dashboard, deciding their desired meals for the week. 

**Core Objectives:**
* **Task 1:** Implement QR codes for each meal a day in place of paper coupons.
* **Task 2:** Integrate Razorpay for seamless online payments.

---

## ✨ Salient Features

### For Students
* **Weekly Overview:** View the weekly menu, timings, and costs in one place.
* **Online Purchasing:** Decide and purchase desired meals online seamlessly.
* **Purchase History:** Review the meals purchased for both the present and upcoming week.
* **Digital Identity:** Use a single, unique QR code instead of paper coupons to claim meals.

### For Mess Owners (Admins)
* **Menu Management:** Manage the menu items, edit timings, and regulate prices.
* **Forecasting:** Track the total meals to be cooked based on purchased coupons.
* **QR Verification:** Scan and verify student QR codes to provide meals efficiently.
* **Payment Gateway:** Accept online payments securely via Razorpay integration.

---

## 🎯 Detailed Description & Walkthrough

### Student Services

**Home Page & Menu**
View the mess timings and the daily menu right from the home page.
![](/assets/time_menu.jpg)

**Google Authentication**
Students sign in securely using their respective Google accounts. Access can be restricted to specific institutional domains (e.g., `iiit-bh.ac.in`).
![](/assets/google_signin.jpg)

**Buying Coupons**
Students select their desired meals for the upcoming week using a checkbox system. The total amount is calculated and displayed at the bottom before checkout.
![](/assets/purchase_page.jpg)

**Payment Integration**
Clicking "Continue with Payment" directs the student to the Razorpay gateway to securely complete their transaction.
![](/assets/payment.jpg)

**Purchase History**
A dedicated dashboard to check which meal and day coupons are active for the current and upcoming weeks.
![](/assets/purchase_history.jpg)

**QR Code Generation**
Students receive a unique, static QR code. This acts as a digital ID and can be scanned directly from a smartphone or printed. If compromised, a new QR code can be generated instantly.
![](/assets/qr_code.jpg)

### Administrator Services

**Admin Panel**
An intuitive interface to edit the cost, timings, and items on the weekly menu.
![](/assets/admin_panel.jpg)

**Total Meals Tracker**
Displays the exact count of meals to be cooked for the present and upcoming weeks based on the real-time purchasing data.
![](/assets/total_meals.jpg)

**Scan & Verify QR**
Admins select the current meal type and scan student QR codes. 
* **Green Tick:** The student has purchased the coupon for that specific meal/day.
* **Red Cross:** The student has not purchased the meal or has already claimed it.
Admins can simply press "Scan New" for the next student in line.
![](/assets/scan_qr.jpg)

---

## 👥 Team Members
* **Uday Deshpande**
* **Atharva Bakre**
