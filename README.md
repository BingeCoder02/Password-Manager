# Password-Manager

Password Manager is a straightforward, client-side web application built using HTML, CSS, and JavaScript. It empowers users to securely store, view, copy, and delete their passwords directly within their browser, with all data securely stored locally via localStorage.

## Features

- Comprehensive Password Management: Easily add, view, and delete passwords for your favorite websites.
- Secure Password Display: Passwords are masked (****) by default, ensuring your sensitive data stays protected.
- Effortless Copying: Instantly copy website names, usernames, or passwords to your clipboard with a single click.
- Local Data Storage: All password data is stored locally in your browser using localStorage, meaning no data is transmitted to any server, safeguarding your privacy.

## Usage
### Adding a Password

- Enter the website, username, and password details into the respective fields.
- Click the "Submit" button to save the password locally.
- Your saved passwords will be displayed in the table for easy access.

### Copying Data

- Click the copy icon next to any website, username, or password to copy the data to your clipboard.
- A "Copied!" message will appear briefly to confirm the action.

### Deleting a Password

- Click the "Delete" button next to any password entry to remove it from the list.
- The entry will be permanently deleted from local storage.

## Project Structure

- index.html: The main HTML file that provides the structure for the page.
- style.css: The CSS file responsible for the visual styling of the application.
- script.js: The JavaScript file that contains all the logic for managing passwords, including saving, deleting, and copying functionalities.
