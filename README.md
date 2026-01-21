# Task Manager Web Application

This project is a web-based Task Manager application developed as a university final project.

## Project Description
The application allows users to register, log in, and manage their personal tasks.
Each user can create, edit, update, and delete tasks.
All tasks are securely stored in a database and are visible only to their owner.

## Main Features
- User registration and authentication
- Secure password hashing
- Create, edit, delete tasks
- Task statuses: TODO, IN_PROGRESS, DONE
- Task deadlines
- User-based data isolation (users can see only their own tasks)

## Technologies Used
- Next.js (React)
- PostgreSQL
- REST API
- JWT-based authentication
- SQL database schema

## Database Structure
The database contains two main tables:
- users – stores user credentials
- tasks – stores tasks linked to users via user_id

Each task belongs to exactly one user.

## Security
- Passwords are stored in hashed form
- Authorization checks are applied on every request
- Users cannot access other users’ data

## Project Structure
The full source code is provided in the archive:
anything_fixed.zip

## How to Run
1. Extract the archive
2. Configure environment variables
3. Run database SQL schema
4. Start the development server

## Author
Nurislam
