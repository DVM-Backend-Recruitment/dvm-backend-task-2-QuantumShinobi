# CinemaCloud

A full-featured movie ticket booking system built with Django, featuring user and theatre administration capabilities. The application uses PostgreSQL for data storage and is containerized using Docker for easy deployment.

## Setup and Demo

> [!NOTE]  
> You have to login their BITS email address to access the videos.

- [Setup Guide](https://drive.google.com/file/d/1wVDZFIc3ZvyRHToMURR9SIVv61-zuBhW/view?usp=sharing)
- [Demo Video](https://drive.google.com/file/d/1gPo92R-yt1GS051Hx9h4LJCsvKKZInwB/view?usp=sharing)

### User Features

- **Authentication**

  - Email & Password login
  - Google OAuth integration
  - Email verification
  - Secure password reset

- **Booking Management**

  - Movie ticket booking with seat selection
  - Food & beverage ordering
  - Digital wallet transactions
  - Ticket cancellation system
  - Email confirmations for bookings
  - Transaction history

- **User Experience**
  - Movie search functionality
  - Location-based theatre filtering
  - Profile management
  - Booking history

### Theatre Administration

- **Theatre Management**
  - Screen configuration
  - Show scheduling
  - Food item inventory
  - Revenue tracking
  - Transaction monitoring
  - Wallet management

## Tech Stack

- **Backend**: Django
- **Database**: PostgreSQL
- **Web Server**: Nginx
- **WSGI Server**: Gunicorn
- **Authentication**: Django AllAuth
- **Containerization**: Docker

## Setup Instructions

### Development Environment

1. Clone the repository

```sh
git clone <repository-url>
cd cinemacloud
```
