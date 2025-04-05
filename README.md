<div align="center">
  <br />
  <img src="https://github.com/adrianhajdin/healthcare/assets/151519281/a7dd73b6-93de-484d-84e0-e7f4e299167b" alt="Project Banner" />
  <br />
  <br />

  <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
  <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />

  <h3 align="center">Healthcare Management System</h3>
</div>

---

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Getting Started](#getting-started)

---

## 🤖 Introduction

A healthcare management system for patients and administrators. Patients can register, manage their medical information, and book appointments. Admins can view, schedule, and cancel appointments. The app supports secure document uploads, SMS notifications, and is fully responsive.

---

## ⚙️ Tech Stack

- **Next.js 14**
- **TypeScript**
- **Tailwind CSS**
- **ShadCN UI**
- **Appwrite (Database, Auth, Storage)**
- **Twilio (SMS)**

---

## 🔋 Features

- Patient registration with medical and personal data
- File upload using Appwrite Storage
- Doctor selection and appointment booking
- Admin panel to manage appointments (schedule, cancel)
- SMS notifications on appointment status
- Responsive design
- Form validation with Zod
- Clean and modular codebase

---

## 🤸 Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

```bash
git clone https://github.com/MRafay620/healthcare.git
cd healthcare
npm install
```

### Environment Setup

Create a `.env.local` file in the root:

```env
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=your_project_id
API_KEY=your_secret_key
DATABASE_ID=your_db_id
PATIENT_COLLECTION_ID=your_patient_collection
APPOINTMENT_COLLECTION_ID=your_appointment_collection
NEXT_PUBLIC_BUCKET_ID=your_bucket_id
NEXT_PUBLIC_ADMIN_PASSKEY=your_admin_passkey
```

> Replace placeholders with your actual Appwrite credentials.

### Run the Project

```bash
npm run dev
```

Visit `http://localhost:3000` to view the app.

## 🧩 License

This project is licensed under the [MIT License](LICENSE).
Let me know if you'd like to include additional sections like deployment steps or contributor guidelines!

## Screenshots

<img width="939" alt="Image" src="https://github.com/user-attachments/assets/7aa53227-f694-42da-9e28-a0a574304913" />
<img width="933" alt="Image" src="https://github.com/user-attachments/assets/0d0a35c2-0802-4f3d-bbcb-62eb10977b6c" />
<img width="949" alt="Image" src="https://github.com/user-attachments/assets/c335996e-57d0-4ea5-8c7f-b68935a5d0a4" />
<img width="943" alt="Image" src="https://github.com/user-attachments/assets/55ebd12d-c463-401f-88a0-addbf3433c74" />
<img width="918" alt="Image" src="https://github.com/user-attachments/assets/edd9d936-dfe7-4ada-82e2-deea4987bef6" />
<img width="950" alt="Image" src="https://github.com/user-attachments/assets/185f454e-10e4-4f66-8111-549a87e5b7e9" />
