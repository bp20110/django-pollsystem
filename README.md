# django-pollsystem

## Setup
This project utilizes `asdf` to manage Python and `poetry` for dependencies. Follow the steps below to set up your development environment.

### Prerequisites Installation
- **Installing asdf**:
  If `asdf` is not yet installed on your system, please follow the instructions in the [asdf official documentation](https://asdf-vm.com/).

### Environment Setup
- **Installing Python**:
  Use `asdf` to install the Python version specified in the `.tool-versions` file.
  ```bash
  asdf plugin-add python
  asdf install

- **Installing Poetry**:
  Next, use asdf to install poetry, which simplifies dependency management.
  ```bash
  asdf plugin-add poetry
  asdf install

### Installing Dependencies
  - **Use poetry to install the project dependencies.**
    ```bash
    poetry install

### Running the Project
  - **To run the project locally, use the following command**
    ```bash
    poetry run python manage.py runserver
  - **After starting the server, open http://127.0.0.1:8000 in your browser to check if the application is functioning correctly.**
