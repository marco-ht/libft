# Libft

This repository contains my implementation of the **libft** project, developed as part of the 42 School curriculum. The purpose of this project is to showcase my skills in C programming, algorithms, and creating custom library functions that are robust, efficient, and adhere to the high standards of coding required by 42.

---

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Testing](#testing)
- [Acknowledgments](#acknowledgments)
- [Disclaimer](#disclaimer)
- [License](#license)

---

## Overview

The **libft** project is a self-made library of frequently used functions in C that are essential for everyday programming tasks, such as string manipulation, memory management, and more. This project was undertaken to both learn and demonstrate my understanding of core C programming concepts and to provide a solid foundation for future projects.

---

## Project Structure

The repository is organized as follows:

libft/ ├── includes/ # Header files for the library functions ├── srcs/ # Source code files for library implementations ├── tests/ # Unit tests to validate the library functions ├── Makefile # Makefile for compiling the project └── README.md # This file

- **includes/**: Contains all the necessary header files.
- **srcs/**: Contains the implementation of each function.
- **tests/**: Contains test cases for verifying the correctness of each function.
- **Makefile**: Automates the compilation process.

---

## Installation

To build the libft library, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/libft.git
   cd libft
Compile the project:

Run the following command in your terminal:

make
This command will compile the library and create an archive file (usually libft.a) in the project directory.

Usage
After compiling, you can link the libft.a archive to your C projects. For example:

#include "libft.h"

int main(void) {
    // Example usage of ft_strlen
    char *example = "Hello, world!";
    size_t length = ft_strlen(example);
    // ...
    return 0;
}
Compile your program by linking the libft archive:

gcc -Wall -Wextra -Werror your_program.c libft.a -o your_program
Features
Memory Functions: Custom implementations for memory management.

String Functions: Implementations for string manipulation, searching, and modification.

Character Checks: Functions to validate and transform individual characters.

Linked Lists: Basic operations for creating and managing linked lists.

Additional Utilities: Other utility functions to enhance your C programming experience.

Testing
Unit tests are provided in the tests/ directory. To run the tests:

Navigate to the tests directory:

cd tests
Compile and run the test suite:

make test
This will run a series of predefined tests to ensure that all functions behave as expected.

Acknowledgments
My thanks to the 42 community and mentors for their invaluable guidance.

Special thanks to those who have shared their insights and contributions in various open source projects, helping me to understand and implement this library.

Disclaimer
IMPORTANT:
This project was developed solely as part of the educational curriculum at 42 School. The code within this repository is published only for demonstration purposes to showcase my programming capabilities.

Academic Integrity Notice:
It is strictly prohibited to copy or present this code as your own work in any academic projects at 42. The use of this code in academic exercises by anyone other than the original author is a breach of 42 School's regulations. Any misuse of this project will be considered a violation of the ethical standards set forth by 42.

License
This repository is licensed under the Creative Commons - NonCommercial-NoDerivatives (CC BY-NC-ND 4.0) license. This means you are free to share the repository as long as you:

Provide appropriate credit.

Do not use it for commercial purposes.

Do not modify, transform, or build upon the material.

For more information, please refer to the CC BY-NC-ND 4.0 license details.

Developed with passion and adherence to the high standards of 42 School.
