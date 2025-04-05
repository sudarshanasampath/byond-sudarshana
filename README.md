# Simple Task Tracker 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Architecture & Design Principles](#architecture--design-principles)
- [Diagrammatic Representation](#diagrammatic-representation)
- [User Roles and Stories](#user-roles-and-stories)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Security Measures](#security-measures)

## Introduction
This system manages tasks.
The Simple Task Tracker system enables users to easily search, filter, and manage yasks.

## Features

- **User Authentication**: Secure login and registration for users with role-based access control.
- **Tasl Management**: Add, update, and manage tasks.

## Architecture & Design Principles

- **Client-Server Architecture**: Utilizes a client-server model with a Vue.js front end and a Laravel back end.
- **User Authentication**: Secure login and registration for users with role-based access control.
- **Task Management**: Add, update, and manage tasks details.
- **Security**: Implements secure authentication mechanisms using Laravel Sanctum.

## Diagrammatic Representation
### ER DIAGRAM 


### USER FLOW CHART 


## User Roles and Stories

### User
- **Create Task**: Create a task.
- **View Task**: See task details.
- **Update Task**: Update a task.
- **Delete Task**: Delete a Task

### Administrator (MA)
- **Manage users**: Add and update users and managers.
- **View and manage all tasks**: Manage tasks.

### manager
- **Manage Tasks**: Manage all tasks.

## System Requirements

- **Frontend**: Vue.js
- **Backend**: Laravel
- **Database**: MySQL
- **Tools**: VS Code, MySQL Workbench, Postman, Swagger UI

## Installation

### Prerequisites

- Node.js (>= 14.x)
- PHP (>= 11)
- MySQL (>= 8.x)
- Docker (optional, for containerization)

### Steps

1. **Clone the repository**:

2. **Backend Setup**:

3. **Frontend Setup**:

4. **Database Setup**:
    - Set up the MySQL database through Laravel migration process

## Usage

1. **Register** as a user.
2. **Login** to the system.
3. **Navigate** to the tasks list.
4. **Create** or **Update** a task.
5. **View** and **Delete** Tasks.

## API Documentation


## Security Measures

- **Data Protection**: All sensitive data, such as passwords, are encrypted using SHA-256.
- **Access Control**: Implemented using Laravel Sanctum with role-based access control (RBAC).
- **Audit Logging**: All user activities are logged with timestamps.

## Wiki

