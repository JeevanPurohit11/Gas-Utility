# Gas Utility Service Application

## Overview

A surge in customer service requests is overwhelming a gas utility company. The current system's capacity is insufficient, resulting in prolonged wait times and subpar service for customers.

This Django application is designed to facilitate consumer services for gas utilities. It enables customers to submit service requests online, monitor the progress of their requests, and access their account details. Additionally, the application provides customer support representatives with a dedicated tool for request management and customer assistance.

---

## Features

### Customer Features

- **Service Requests**
  - Customers can create service requests online.
  - The form includes options for selecting the service type, providing detailed descriptions, and attaching files.

- **Request Tracking**
  - Customers can track the status of their service requests.
  - Information displayed includes submission date, resolution date, and current status.

- **Account Information**
  - Customers can view their account details, including billing information and service history.

### Admin/Customer Support Features

- **Request Management**
  - Admins can manage customer service requests.
  - Features include assigning tasks to support staff and updating request statuses.

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/JeevanPurohit11/Gas-Utility-Task.git
cd Gas-Utility-Task
```
Step 2: Set Up a Virtual Environment
For Linux/macOS:
```bash
python3 -m venv venv
source venv/bin/activate
```
For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```
Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```
Step 4: Apply Migrations
```bash
python3 manage.py makemigrations
python3 manage.py migrate
```
Step 5: Run the Development Server
```bash
python3 manage.py runserver
```
