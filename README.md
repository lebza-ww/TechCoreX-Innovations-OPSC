# TechCoreX-Innovations-OPSC
# 💰 MaliBudget – Personal Finance Manager

> **Track. Save. Achieve.**  
> A mobile budgeting app built to help South Africans manage their finances with ease.

---

##  Repository

[![GitHub](https://img.shields.io/badge/GitHub-TechCoreX--Innovations--OPSC-181717?logo=github)](https://github.com/lebza-ww/TechCoreX-Innovations-OPSC.git)

🔗 [https://github.com/lebza-ww/TechCoreX-Innovations-OPSC.git](https://github.com/lebza-ww/TechCoreX-Innovations-OPSC.git)

---

##  Demo Video

[![MaliBudget Demo](https://img.shields.io/badge/YouTube-Watch%20Demo-red?logo=youtube)](https://youtu.be/wQIomhGl7eA)

🔗 [https://youtu.be/wQIomhGl7eA](https://youtu.be/wQIomhGl7eA)

---

##  About the App

**MaliBudget** is a personal finance management mobile application designed to help users track income and expenses, set savings goals, manage budgets by category, and gain insights through analytics — all in one place.

The app is built with the South African market in mind, supporting ZAR (South African Rand) as the default currency and using a +27 phone number format during registration.

---

##  Features

- **User Authentication** - Secure login and account creation with password strength validation
- **Dashboard / Home Screen** - Overview of total balance, income, and expenses at a glance
- **Add Expense** - Log expenses by amount, category, date, time, and optional description with receipt photo upload
- **Budget Tracking** - Set and monitor spending budgets per category (e.g., Groceries, Entertainment)
- **Savings Goals** - Create and track personal savings targets
- **Analytics** - Visualise spending trends over monthly, 3-month, and 6-month periods
- **Profile & Settings** - Manage currency, categories, dark mode, notifications, and security settings

---

##  App Layout Description of Screenshots

| Login | Register | Home |
|-------|----------|------|
| Welcome screen with email/password login | Create account with name, email, phone & password | Balance overview with budgets & recent transactions |

| Add Expense | Goals | Analytics | Profile |
|-------------|-------|-----------|---------|
| Log a new expense with category & receipt | Track savings goals progress | Spending breakdown & trend charts | Manage settings & preferences |

---

##  Tech Stack

- **IDE:** Android Studio
- **Language:** Kotlin
- **Platform:** Android (Native)
- **Backend & Database:** Firebase (Firestore / Realtime Database)
- **Authentication:** Firebase Authentication
- **UI:** XML Layouts (Material Design)
- **Build System:** Gradle (Kotlin DSL)
- **Currency:** ZAR (South African Rand / R)

---

##  Getting Started

### Prerequisites

- Android Studio (latest stable version)
- Android SDK (API Level 21+)
- Java Development Kit (JDK 11 or higher)
- A Firebase project with Firestore & Authentication enabled
- An Android device or emulator (Android 5.0 Lollipop or higher)

### Installation

```bash
# Clone the repository
git clone https://github.com/lebza-ww/TechCoreX-Innovations-OPSC.git

# Open the project in Android Studio
# File > Open > Select the cloned folder

# Sync Gradle dependencies
# Click "Sync Now" when prompted in Android Studio

# Connect your Firebase project
# Add your google-services.json to the /app directory

# Run the app
# Click the Run button or use Shift + F10
```

### Running on Android Device / Emulator

1. Connect your Android device via USB or start an emulator in Android Studio
2. Select your target device from the device dropdown
3. Click **Run ▶** or press `Shift + F10`

---

##  Group Members

| Name | Student Number |
|------|---------------|
| Munei Nevhutanda | ST10333563 |
| Lebogang Ntlatleng | ST10456295 |
| Portia Mashaba | ST10357369 |
| Mpho Nethomboni | ST10448422 |
| Mulamuleli Given Mutshotsho | ST10311127|

> _Student numbers to be filled in._

---

##  Project Structure

```
TechCoreX-Innovations-OPSC/
├── MaliBudget/
│   ├── app/
│   │   ├── src/
│   │   │   ├── main/
│   │   │   │   ├── java/
│   │   │   │   │   └── com/malibudget/
│   │   │   │   │       ├── activities/
│   │   │   │   │       ├── fragments/
│   │   │   │   │       ├── adapters/
│   │   │   │   │       └── models/
│   │   │   │   ├── res/
│   │   │   │   │   ├── layout/
│   │   │   │   │   ├── drawable/
│   │   │   │   │   └── values/
│   │   │   │   └── AndroidManifest.xml
│   │   │   └── google-services.json
│   │   └── build.gradle.kts
│   └── build/
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

---

##  License

This project is licensed under the Apache 2.0 License. It was developed as part of an academic assignment. All rights reserved by the group members listed above.

---

*MaliBudget — Manage your finances with ease.* 🇿🇦

