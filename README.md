# 🏨 Hatfield Hotel Database Project

## 📘 Overview

This project models a booking and room management system for the **Hatfield Hotel**, a multi-room hotel that handles guest bookings, room types, seasonal pricing, and additional services through a structured relational database.

---

## 🧩 System Features

### 🛏️ Room Types
Each room is assigned a type, which determines its bed arrangement and sleeping capacity:

- **Single**: 1 single bed (sleeps 1)
- **Double**: 1 double bed (sleeps 2)
- **Twin**: 2 single beds (sleeps 2)
- **Family**: 1 double + 2 single beds (sleeps 4)

### 🚪 Room Extras
Rooms may include:
- **Fixed extras**: Built-in amenities like en-suite baths or showers, included in the room price.
- **Additional extras**: Optional, guest-requested items (e.g., cots, irons), charged per night used.

### 👤 Guest Bookings
- A **booking** is made by a single guest, even for group reservations.
- Bookings support **multi-room**, **multi-day**, and **variable start dates** per room.
- Guests specify the **reason** for their stay: `Business` or `Leisure`.

### 📅 Seasons and Pricing
Room prices depend on:
1. **Room type**
2. **Season**
3. **Day of the week**

#### Seasons:
- **Low**: December 1st – March 31st
- **Mid**: April 1st – May 31st & October 1st – November 30th
- **High**: June 1st – September 30th

The total booking cost includes room rates per night, adjusted for season and day, plus any additional extras


#### SQL Skills Acquired

PL/SQL: Writing and executing stored procedures, functions, and packages.

Triggers: Creating and managing triggers to automatically respond to database events.

Advanced Queries: Constructing complex queries for data manipulation, aggregation, and filtering.

Transaction Management: Understanding and implementing transactions to ensure consistency and isolation in database operations.

Query Optimisation: Analysing and optimising SQL queries to improve performance and efficiency.

Working with Big Data: Designing and executing SQL queries that scale for large datasets.
