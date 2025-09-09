<div align="center">
  <br />
    <a href="https://your-vercel-link.vercel.app" target="_blank">
      <img src="https://github.com/sanemi07/yoom/assets/your-banner-image" alt="Yoom Project Banner" width="600">
    </a>
  
  <br />

  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Vercel-black?style=for-the-badge&logoColor=white&logo=vercel&color=000000" alt="vercel" />
  </div>

  <h2 align="center">Yoom – A Zoom Clone</h2>

  <div align="center">
    Build a modern, real-time video conferencing app with authentication, scheduling, recordings, and more.
  </div>
</div>

---

## 📋 Table of Contents

1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Features](#features)  
4. [Quick Start](#quick-start)  
5. [Assets & Code](#assets-code)  
6. [Live Demo](#live-demo)  
7. [More](#more)

---

## 🤖 Introduction

**Yoom** is a modern video conferencing platform built with **Next.js**, **TypeScript**, and **Tailwind CSS**. Users can:

- Securely log in using email/password or social login  
- Create instant or scheduled meetings  
- Manage participants (mute, pin, remove)  
- Share screens, react with emojis, and record meetings  
- Access past meetings and recordings  

All interactions are **real-time, secure, and responsive** across devices.

---

## ⚙️ Tech Stack

- **Next.js** – Frontend framework  
- **TypeScript** – Type safety  
- **Tailwind CSS** – Styling  
- **Clerk** – Authentication & authorization  
- **getstream** – Video & real-time communication  
- **shadcn/ui** – UI components  

---

## 🔋 Features

- **Authentication**: Email/password & social login with Clerk  
- **New Meeting**: Instantly start meetings with camera/mic setup  
- **Meeting Controls**: Mute/unmute, screen share, pin participants, record, grid view  
- **Exit Meeting**: Leave or end meetings  
- **Schedule Meetings**: Set future meetings with date/time  
- **Past Meetings**: View history & recordings  
- **Personal Room**: Unique instant meeting link  
- **Join via Link**: Easily join meetings shared by others  
- **Responsive Design**: Works on mobile, tablet, desktop  
- **Secure Real-time Functionality**: All actions are private and encrypted  

---

## 🤸 Quick Start

**Prerequisites**

- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/en/)  
- [npm](https://www.npmjs.com/)  

**Clone Repository**

```bash
git clone https://github.com/YOUR_USERNAME/yoom.git
cd yoom
Install Dependencies

npm install


Set Up Environment Variables

Create a .env file in the root:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=


Replace with your Clerk and getstream credentials.

Run the App

npm run dev


Open http://localhost:3000
 to view locally.

🕸️ Assets & Code

Global CSS: app/globals.css includes Tailwind directives and custom overrides for Stream and Clerk.

Components: Reusable React components under components/

Meeting Card Example:

<MeetingCard
  title="Team Sync"
  date="Sep 12, 2025"
  icon="/icons/meeting.svg"
  buttonText="Join"
  handleClick={() => console.log('Joining')}
  link="https://yoom-link"
/>


Icons & Images: Stored in /public folder.

🔗 Live Demo

Check out the app live on Vercel:
https://your-vercel-link.vercel.app
