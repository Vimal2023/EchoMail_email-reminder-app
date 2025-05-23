# EchoMail - Email Reminder App

EchoMail is a full-stack web application built with Node.js, Express, MongoDB, Nodemailer, Node-Cron, Bootstrap, and EJS. It allows users to schedule email reminders for tasks and communications, ensuring timely follow-ups and deadline management. The app features a simple interface for scheduling, viewing, and managing reminders, with automated email delivery at specified times.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)


# LIVE ::
https://echomail-vimal.onrender.com

## Features
- **Schedule Email Reminders**: Set reminders with email, message, date, and time.
- **View All Reminders**: Display all scheduled reminders with status (pending/sent).
- **Automatic Email Delivery**: Sends emails at the specified time using Nodemailer and Node-Cron.
- **Simple Interface**: User-friendly UI built with Bootstrap 5 and EJS templates.
- **Responsive Design**: Includes favicon and Apple touch icon for enhanced browser/mobile compatibility.

## Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (MongoDB Atlas)
- **Email Service**: Nodemailer (using Gmail SMTP)
- **Scheduling**: Node-Cron for automated task scheduling
- **Frontend**: EJS, Bootstrap 5
- **Environment Variables**: Managed with `dotenv`
- **Static Assets**: Served via Express (e.g., favicon.ico, apple-touch-icon.png)

## Prerequisites
- **Node.js**: Version 14 or higher
- **MongoDB Atlas Account**: Free tier for database storage
- **Gmail Account**: With app password for Nodemailer
- **Git**: For cloning the repository
- **GitHub Account**: For deployment (optional)

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/echomail.git
   cd echomail
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the project root.
   - Add the following variables:
     ```env
     MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.emngez1.mongodb.net/email-reminder
     EMAIL_USER=<your-gmail-address>
     EMAIL_PASSWORD=<your-gmail-app-password>
     PORT=5000
     ```
   - **MongoDB URI**: Get from MongoDB Atlas (create a free cluster, enable `0.0.0.0/0` in Network Access).
   - **Gmail App Password**: Enable 2FA in your Google Account, then generate an app password via [Google Account Security](https://myaccount.google.com/security).





