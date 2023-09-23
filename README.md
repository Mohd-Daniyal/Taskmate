 # TaskMate - A Django Task Management Application

<!-- Optional: Include a logo or screenshot of your app -->
![1](https://github.com/Mohd-Daniyal/Taskmate/assets/96229438/ba877ac0-1ff5-4200-832e-451a304fa4a1)


TaskMate is a web-based task management application built using Django, HTML, and CSS. It allows users to manage tasks, create, read, update, and delete tasks, and provides user authentication and login features.

![2](https://github.com/Mohd-Daniyal/Taskmate/assets/96229438/97953ecc-325a-4772-85d7-7b7e47832263)


## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Application](#running-the-application)
  - [User Authentication](#user-authentication)
  - [CRUD Operations](#crud-operations)
- [Contributing](#contributing)


## Getting Started

### Prerequisites

Before you can run TaskMate, you'll need the following installed on your system:

- Python 3.10
- Django

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Mohd-Daniyal/Taskmate.git
   ```

2. Navigate to the project directory:

   ```bash
   cd taskmate
   ```

3. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

## Usage

### Running the Application

To run the TaskMate application, use the following command:

```bash
python manage.py runserver
```

The application will be accessible at `http://localhost:8000` by default.

### User Authentication

TaskMate provides user authentication features. Users can:

- Register for a new account
- Log in with their credentials
- Log out

### CRUD Operations

TaskMate allows users to manage tasks with the following CRUD operations:

- Create a new task
- Read (View) tasks
- Update task details
- Delete tasks
  
![3](https://github.com/Mohd-Daniyal/Taskmate/assets/96229438/2438087a-83d0-4b73-a432-6d35aa267350)


## Contributing

We welcome contributions from the community. If you'd like to contribute to TaskMate, please follow these steps:

1. Fork the project on GitHub.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request on GitHub.
