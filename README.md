# task management application by Richard Adamu 

## Description
please follow this step to get the project up and running 

## Features
- User authentication
- Task creation and management
- Responsive design

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
   - [Cloning the Repository](#cloning-the-repository)
   - [Setting Up a Virtual Environment](#setting-up-a-virtual-environment)
   - [Installing Dependencies](#installing-dependencies)
3. [Running Migrations](#running-migrations)
4. [Running the Development Server](#running-the-development-server)
5. [License]()

## Prerequisites
Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Python](https://www.python.org/downloads/)
- You have installed [Git](https://git-scm.com/)
- You have a evns running 

## Installation

### Cloning the Repository
To clone the repository, run the following command:

```bash
-git clone https://github.com/your-username/your-repository-name.git
-cd your-repository-name
-once everything is cloned to your desired directory, unzip the benmore file first.
-move the 'lib' zip file into the benmore directory benfore unzipping it.

#setting-up-a-virtual-environment
-activate your evns workspace and install django framework
-check and verify your file, you should have (lib,scripts,tasky,pyvenv.cfg)

### Installing Dependencies
-on your terminal navigate to the project file and run this command (pip install djangorestframework)

# running-migrations
- just in case, run the (python manage.py migrate)
-create a superuser for the admin (python manage.py createsuperuser)

# running-the-development-server
- if all requirements are setup correctly run the server by using the command (python manage.py runserver)
-copy and paste the server address
- use the server link on your terminalto visit the admin dashboard and create a user account http://0.0.0.1:0000/admin
-use the server link http://0.0.0.1:0000/tasks/dashboard  and you will be redirected to a login page
- debug is set to true. you can turn it off as you please

#license
- By following these steps and understanding clearly the documentation, I assure that anyone can easily clone and run my Django and TailwindCSS project from GitHub.
