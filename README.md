# Django Tweet Management App

A simple Django-based web application for managing tweets with user authentication.

## 📌 Features

- **User Registration & Login**: Secure user authentication system using Django’s built-in auth.
- **Tweet Creation**: Logged-in users can add tweets.
- **Tweet Editing & Deletion**: Only the user who created a tweet can edit or delete it.
- **Public Feed**: All users can view tweets from all other users.
- **Clean UI**: Minimalist interface for smooth user experience.

## 🔒 Access Control

- Users must log in to create, edit, or delete tweets.
- Edit/Delete permissions are restricted to the original author only.
- Viewing tweets is open to all authenticated users.

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite (default, can be replaced with PostgreSQL/MySQL)
- **Frontend**: HTML, CSS, Bootstrap 
- **Auth**: Django’s built-in user authentication


