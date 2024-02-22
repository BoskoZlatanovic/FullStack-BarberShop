Student Project in 3rd year. <br> 
Subject - Script Languages. <br> 
Backend - Node.js. <br> 
FrontEnd in Vue. <br>

Node.js and Vue.js Full-Stack Application
Overview

This full-stack application is designed to manage and schedule personal training sessions, developed using Node.js with Express for the backend and Vue.js for the frontend. It consists of three backend services (User Service, Training Scheduling Service, and Notification Service) and a user-friendly client application.
Backend Services
1. REST Service

    Exposes data in the database.
    Provides CRUD operations for all entities.
    Implements user input validation (using Joi or similar libraries).
    Handles user authorization (authenticated users only).

2. Authentication Service

    Manages user registration (API only, no GUI).
    Implements login functionality using JWT.

3. Application Service

    Serves HTML and resources for the GUI.
    Performs CRUD operations on the database via GUI.
    All routes are prefixed with /admin and organized in separate modules.

Frontend Application

    Developed with Vue.js.
    Supports two additional user types: Guest (read-only access) and Registered User (can create and modify their content).
    Utilizes the backend REST service for data access.
    Delivered from the root (/) route of the Application Service.
    Incorporates Vue Router and Vuex store.
    Uses Bootstrap Vue or a similar library for UI components.
    Implements validation for all user inputs.
    Optional real-time web feature using WebSockets.
