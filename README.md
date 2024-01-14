# Table Tracker - Serverless Data Processing

## Introduction

Welcome to the Table Tracker App 🚀, a serverless solution designed to streamline restaurant reservations in Halifax, Nova Scotia. This technical proposal provides an in-depth overview of the architecture, components, and modules incorporated into the project.

## Project Overview

The Table Tracker App aims to deliver an efficient and user-friendly reservation platform for restaurant guests in Halifax. Leveraging the power of Google Cloud Platform (GCP) and Amazon Web Services (AWS) serverless architecture ensures scalability, security, and cost-effectiveness.

## App Components

1. **Customer App:** Enables customers to make reservations.
2. **Partner App:** Empowers restaurants to manage bookings and menus.
3. **Admin App:** Provides administrators with insightful visualizations.

## Key Layers

1. **Frontend:** React.js.
2. **Backend Services:** Serverless functions for reservations, notifications, and analytics in Google Cloud Platform (GCP) and Amazon Web Services (AWS).
3. **Database:**
    - Firestore for dynamic content.
    - AWS DynamoDB for static content.
    - Amazon S3 for storing restaurant and menu images.
4. **Authentication:** Firebase Authentication.
5. **APIs:** Amazon API Gateway or Google API Gateway for RESTful APIs.

## Modules

### Customer App

#### 1. Sign Up & Login Module
- Email and password login.
- Google Single Sign-On.

#### 2. List Restaurants
- View available restaurants, opening hours, and menus.

#### 3. Reservation Management
- Book, edit, delete, view reservations.
- Book, edit, delete, view menu for a reservation.

#### 4. Chatbot
- Interact with a chatbot for restaurant information, menu details, and reservations.

#### 5. Notifications
- Receive notifications about offers and reservation updates.

### Partner App

#### 1. Sign Up & Login Module
- Email and password login.
- Google Single Sign-On.

#### 2. Restaurant Details
- Add availability, opening and closing hours, and menus.
- Manage tables and reservations.

#### 3. Reservation Management
- View, edit, delete reservations.

#### 4. Menu Management
- Edit, delete, and view menus.
- Add prices and offers.

#### 5. Holistic View
- Visualize daily, weekly, and monthly reservations.

#### 6. Chatbot
- Interact with a chatbot for booking information and menu details.

#### 7. Notifications
- Receive notifications about new reservations and updates.

### Admin App

#### 1. Visualizations
- Top 10 restaurants and food items.
- Peak order periods.
- Top 10 customers.
- Filtered reviews.

## Data Storage and Security

- Reservation data stored securely in Firestore.
- Role-based access control for data privacy.
- Encryption for Personally Identifiable Information (PII).
- Firebase Authentication for secure user access.

## Development Environment

- Git for collaborative development.
- CI/CD pipelines.
- Regular logging and weekly commits to ensure project progress and quality.
