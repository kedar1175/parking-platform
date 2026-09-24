# 🚗 Parking Platform

A web-based parking marketplace that connects drivers looking for parking spaces with parking-space owners who want to rent out their unused parking spaces.

## 📌 Problem Statement

Finding parking in busy areas can be difficult and time-consuming.

At the same time, many private parking spaces remain unused for several hours during the day.

This project aims to connect these two sides through a single platform.

## 💡 Proposed Solution

The platform allows parking-space owners to list their available parking spaces.

Drivers can:

- Search for available parking spaces
- Select date and time
- Check parking availability
- Book a parking space
- Make a payment
- View booking history

Parking owners can:

- Register their parking space
- Set availability
- Set parking prices
- Manage bookings
- View their parking information

## 👥 User Roles

| Role | Main Responsibilities |
|------|-----------------------|
| Customer | Search and book parking |
| Parking Owner | List and manage parking spaces |
| Admin | Manage users, listings and bookings |

## 🛠️ Technology Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Spring Security

### Frontend
- HTML
- CSS
- JavaScript

### Database
- MySQL

### Tools
- Git
- GitHub
- VS Code / IntelliJ IDEA
- Maven

## 🏗️ System Architecture

```text
User
  ↓
Frontend
HTML / CSS / JavaScript
  ↓
REST API
  ↓
Spring Boot Backend
  ↓
MySQL Database