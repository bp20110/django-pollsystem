# django-pollsystem

## Overview
This project is intended to review Django through the official Django tutorial. We will develop a simple polling system.

## Technology Stack
- **Programming Language:** Python 3.11.4
- **Framework:** Django 5.0.4

## Setup
This project utilizes `asdf` to manage the versions of Python and Poetry, and `Poetry` to manage dependencies. Follow the steps below to set up your development environment.

### Prerequisites Installation
- **Installing asdf**:
  If `asdf` is not yet installed on your system, please follow the instructions in the [asdf official documentation](https://asdf-vm.com/).

### Clone the repository
```bash
  git clone https://github.com/bp20110/django-pollsystem.git
```

### Environment Setup

- **Installing Python**:
  Use `asdf` to install the Python, which simplifies dependency management.
  ```bash
  asdf plugin-add python

- **Installing Poetry**:
  Next, use asdf to install poetry.
  ```bash
  asdf plugin-add poetry

- **Installing the Versions**:
  Install the versions of the tools specified in the .toolversions file.
  ```bash
  asdf install

### Installing Dependencies
  - **Use poetry to install the project dependencies.**
    ```bash
      poetry install

## Running the Project
  - **To run the project locally, use the following command**
    ```bash
    poetry run python manage.py runserver
  - **After starting the server, open http://127.0.0.1:8000 in your browser to check if the application is functioning correctly.**
