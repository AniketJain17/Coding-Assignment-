# Sociomania Dashboard

## Introduction

Welcome to the Social Media Dashboard project! This web application is a mini social media dashboard developed as part of the coding assignment for the Full-Stack Engineer Intern position for Winter 2024.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Assumptions](#assumptions)
- [Challenges](#challenges)
- [Contributing](#contributing)
- [License](#license)

## Features

- Interacts with a mock API to display analytics of social media posts of like.
- User authentication for secure access.
- Allows users to draft and schedule social media posts, including support for titles and descriptions. 

## Setup

To set up the Social Media Dashboard locally, follow these instructions:

### Prerequisites

- [Python](https://www.python.org/downloads/) installed
- [Node.js](https://nodejs.org/) installed (for frontend development)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/social-media-dashboard.git
    cd social-media-dashboard
    ```

2. Set up the backend:

    ```bash
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py makemigrations
    python manage.py runserver
    ```

4. Access the dashboard at [http://127.0.0.1:8000/](http://127.0.0.1:8000/) (or the appropriate URL based on your setup).

## Sample User Accounts

Use the following sample accounts to explore the features of the Social Media Dashboard:

| Username   | Password      |
|------------|---------------|
| shyam      | shyam         |
| khusu      | khusu         |
| yasss      | yasss         |
| aniket     | AniketAdmin   |
| admin1122  | admin         |

Note: These are sample accounts provided for testing purposes. Please do not use real or sensitive credentials.


## Usage

1. Register or log in using your credentials.
2. Explore the analytics dashboard to view post statistics.
3. Use the drafting and scheduling features to create social media posts.

## Assumptions
- While registering you need to click save button twice for registartion, one for saving image and second for profile save. 
- You need to click in Home after clicking save while registering.
- Users are required to have at least a pic and description for social media posts.

## Challenges
During the development of this project, I encountered some challenges, particularly as I am relatively new to Django and backend development. The learning curve in understanding Django's architecture, ORM, and routing took some time.
To overcome these challenges, I extensively referred to the official Django documentation (https://docs.djangoproject.com/) and watched tutorials on YouTube. These resources played a crucial role in enhancing my understanding and proficiency in Django development.
While this added some time to the development process, it was a valuable learning experience, and I am now more confident in my ability to work with Django for future projects.
