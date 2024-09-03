# Contacts Manager
Simple app for managing contacts

# Tech

### API

C# 12, ASP.NET 8, EF Core 8, PostgreSQL 16, Docker

### Frontend

Next.js :)

# Core Features

### Contact Management
  - View Contacts List
  - View Contact Details
  - Add Contact
  - Edit Contact
  - Delete Contact

# Essential Non-Functional Requirements

### Authenticity and Authorization

- Only authenticated user can see own contacts details and edit, add or delete it.
- However, it is possible for non-authenticated user (guest) to see everyone else contact list with limited details.

### Security

- Since the application requires authentication, it is mandatory to store users password in a secure place.

-- *Out of Scope* -- 

### Maintainability

- Code documentation

### Appearance

It is not required that app fullfills specific design or appearance requirements.
