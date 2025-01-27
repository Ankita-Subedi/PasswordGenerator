# Password Generator Application

## Overview
This project is a simple password generator application built with React. It allows users to generate random passwords based on customizable criteria, including length and character types.

## Features
- **Password Length**: Set the desired length of the password (6 to 100 characters).
- **Character Options**: Include numbers and special characters in the generated password.
- **Copy to Clipboard**: Easily copy the generated password to the clipboard.

## Components
### PswChanger
The PswChanger component is responsible for generating passwords. It includes:
- A range input to select the password length.
- Checkboxes to include numbers and special characters.
- A read-only input field displaying the generated password.
- A button to copy the password to the clipboard.

## Usage
1. Adjust the password length using the slider.
2. Check the boxes to include numbers and/or special characters.
3. Click the "Copy" button to copy the generated password.

## Installation
To run this project locally, clone the repository and install the dependencies:
bash
git clone <repository-url>
cd <project-directory>
npm install


## Running the Application
To start the application, run:
bash
npm run dev

[Click here to view live](https://password-generator-mu-wine-75.vercel.app/)