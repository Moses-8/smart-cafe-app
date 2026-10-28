# Smart Café PRD v1

## Problem

Customers currently queue to place orders in the café.

The Smart Café app allows customers to browse products,
place orders and track order progress directly from a mobile app.

## Target Users

### Customers

Customers can:

- Register
- Login
- Browse menu
- Add items to cart
- Place orders
- Track orders

## Goals

Create a simple and secure mobile ordering experience.

## MVP Features

- Registration
- Login
- Menu browsing
- Shopping cart
- Place order
- Track order status

## Future Features

- Notifications
- Loyalty rewards
- Recommendations

## Data Requirements

### User

- User ID
- Email
- Password

### Menu Item

- Item ID
- Name
- Price

### Order

- Order ID
- Customer ID
- Total Price
- Status

## Technologies

- Kotlin
- Android Studio
- Firebase Authentication
- Room Database
- Jetpack Compose

## Acceptance Criteria

### Registration

Given a new user

When registration details are valid

Then an account should be created.

### Login

Given a registered user

When correct credentials are entered

Then the dashboard should open.
