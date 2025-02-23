# Kiosk-Based User Management System

## Description

This web application is designed for use in a **KIOSK** equipped with a **QR scanner**. The system identifies users by scanning their QR codes and displays relevant information about them. Additionally, it prints different types of tickets based on the user's role. The system also features a **ticket purchasing section**, which integrates with **WooCommerce and FooEvents** via a custom API to enable ticket sales and check-ins directly from the KIOSK.

## Features

### 1. QR Code Scanning & User Identification
- Users scan their **QR codes** at the KIOSK.
- The system retrieves and displays their **profile information**.
- A **ticket is printed** based on the user type.

### 2. User Roles & Ticket Printing
Each user type gets a distinct ticket when scanned:
- **Model**
- **Designer**
- **Photographer**
- **Videographer**
- **Volunteer**

### 3. Ticket Purchasing & Check-In
- The main **ticket sales** platform operates on **WooCommerce & FooEvents**.
- A **custom API** connects the KIOSK to FooEvents.
- Users can **purchase tickets** directly from the KIOSK.
- Purchased tickets are **linked back** to FooEvents for centralized tracking.

## Technologies Used

- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Real-time Communication:** Socket.io
- **E-commerce Integration:** WooCommerce, FooEvents API

## Key Functionalities

- QR code scanning and user identification.
- Display of user information upon scanning.
- Automatic ticket printing based on user type.
- Ticket purchase and check-in via a custom API.
- Seamless integration with FooEvents and WooCommerce for ticket management.

## Video Demonstrations

### User QR Scanning & Ticket Printing
[[CLICK HERE]](https://www.youtube.com/shorts/rswR4AL3Yjk)


