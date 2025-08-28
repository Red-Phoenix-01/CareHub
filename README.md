# 🩺 CareHub – Doctor Appointment & Video Consultation Platform

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://care-hub-seven.vercel.app/)  
[![License](https://img.shields.io/badge/License-MIT-green)]()  

CareHub is a **full-stack doctor consultation platform** built with **React 19**, **Next.js 15**, **Tailwind CSS**, **NeonDB**, **Prisma**, **Clerk Authentication**, **Vonage Video API**, and **Shadcn UI**. It allows users to **book appointments, consult via video call, and manage their medical journey securely**.  

---

## 🚀 Live Demo

👉 [CareHub Live](https://care-hub-seven.vercel.app/)

---

## 📸 Screenshots

**Homepage:**  
![Homepage](https://github.com/amitkumardemo/CareHub/blob/master/Screenshot%202025-06-10%20131341.png)

**Video Consultation Screen (optional example):**  
*(Add screenshot if available)*

---

## ✨ Features

- 🧑‍⚕️ Browse and consult **verified doctors**
- 📅 Book appointments with **real-time availability**
- 📹 Secure **high-quality video consultations** (Vonage)
- 💳 Credit-based subscription system (**2 credits = 1 consult**)
- 🔐 Secure **login/register** using Clerk Authentication
- 📄 Manage **past consultations** and **doctor notes**
- 📱 Fully **responsive** and **mobile-friendly UI**
- 💡 Built with **modern components** using Shadcn UI

---

## 🛠 Tech Stack

| Category            | Technology                      |
|---------------------|---------------------------------|
| Frontend            | React 19, Next.js 15, Tailwind CSS |
| UI Components       | Shadcn UI                        |
| Backend             | Next.js App Router, Prisma ORM   |
| Database            | NeonDB (PostgreSQL)             |
| Authentication      | Clerk Authentication            |
| Video Calls         | Vonage Video API                |
| Styling             | Tailwind CSS                    |
| Deployment          | Vercel (recommended)            |

---

## ⚙️ Getting Started

Follow these steps to **run CareHub locally**:

### 1. Clone the Repository
```bash
git clone https://github.com/amitkumardemo/CareHub.git
cd CareHub

2. Install Dependencies
npm install

3. Configure Environment Variables

Create a .env file in the root directory and add the following keys (replace the placeholders with your actual credentials):

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
VONAGE_API_KEY=your_vonage_api_key
VONAGE_API_SECRET=your_vonage_api_secret
DATABASE_URL=your_neondb_connection_string


Explanation:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY and CLERK_SECRET_KEY: Required for Clerk authentication.

VONAGE_API_KEY and VONAGE_API_SECRET: Used for video call functionality.

DATABASE_URL: NeonDB connection string for storing app data.

4. Run the Development Server
npm run dev


Open http://localhost:3000
 in your browser to view the app.

