# Hospital-C-Project

A simple Hospital Management system using C language.

## Table of Contents

-   [Description](#description)
-   [Features](#features)
-   [Getting Started](#getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
-   [Usage](#usage)
-   [Project Structure](#project-structure)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)

## Description

This project is a basic Hospital Management system implemented in the C programming language. It provides a command-line interface for managing essential hospital operations.  The system allows users to add, list, search, edit, and delete patient records.  It's designed as a simple data management application using file storage.

## Features

* **Patient Management:**
    * Add new patient records, including:
        * First Name
        * Last Name
        * Gender
        * Age
        * Address
        * Contact Number
        * Email
        * Problem/Diagnosis
        * Prescribed Doctor
    * View all patient records.
    * Search for a patient record by first name.
    * Edit existing patient records.
    * Delete patient records.
* **Login:** A simple login system protects access to the main menu.

## Getting Started

This section will guide you on how to set up and run the Hospital-C-Project on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:

* **C Compiler:** You will need a C compiler such as GCC (GNU Compiler Collection) installed on your system.
    * For Linux (Debian/Ubuntu):
        ```bash
        sudo apt-get update
        sudo apt-get install gcc
        ```
    * For macOS: If you have Xcode or Command Line Tools installed, GCC is usually included. You can check by running `gcc --version` in your terminal. If not, you can install it from the App Store or via Homebrew (`brew install gcc`).
    * For Windows: You can install MinGW (Minimalist GNU for Windows) or WSL (Windows Subsystem for Linux) and then install GCC within the Linux environment.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Mirzaa-dev/Hospital-C-Project.git](https://github.com/Mirzaa-dev/Hospital-C-Project.git)
    ```
    *(Replace the URL if your repository is different)*
2.  **Navigate to the project directory:**
    ```bash
    cd Hospital-C-Project
    ```
3.  **Compilation:** Compile the C source code using GCC.  Ensure that all the `.c` files are compiled together.
    ```bash
    gcc main.c -o hospital
    ```
    *If you have multiple .c files, compile them all at once.  For example, if you had patient.c, and doctor.c, the command would be:*
    ```bash
     gcc main.c patient.c doctor.c -o hospital
    ```

## Usage

1.  **Run the executable:** After successful compilation, you can run the program using the following command in your terminal:
    ```bash
    ./hospital
    ```
    *(On Windows, you might need to run `hospital.exe`)*
2.  **Login:** The program will prompt you for a username and password. The credentials are:
    * Username:  `RHM`
    * Password:  `22918`
3.  **Main Menu:** After successful login, you will be presented with the main menu:
    * `1. Add Patient Record`:  Add a new patient to the system.
    * `2. List Patient Records`:  View all patients in the system.
    * `3. Search Patient Record`: Search for a patient by their first name.
    * `4. Edit Patient Record`:  Edit an existing patient's information.
    * `5. Delete Patient Record`:  Delete a patient from the system.
    * `6. Exit`:  Close the application.
4.  **Follow the on-screen prompts:** The program will guide you through each operation.

## Project Structure

Hospital-C-Project/├── main.c        # Main program entry point.  Contains the login, main menu, and calls functions from other parts of the program.├── Record2.dat   # File used to store patient records.├── README.md     # Project documentation.
## Contributing

Contributions to this project are welcome. If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix (`git checkout -b feature/your-feature-name`).
3.  Make your changes and commit them (`git commit -am 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Create a new Pull Request.

## License

*(Optional:  You can add a license here, such as the MIT License.  This specifies how others can use your code.)*

## Contact

Mirzaa-dev
