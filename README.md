# Password Reset Form

This repository contains a simple yet effective HTML form for resetting passwords. It's designed to be integrated with backend systems for secure operations.

## Features

- **Secure Handling**: Ensures that sensitive data like `SecretKey` and `TitleID` are not exposed in the client-side code.
- **Token Retrieval**: Utilizes `URLSearchParams` to extract tokens from the URL.
- **Backend Integration**: Prepared for backend server integration to handle authentication and sensitive data storage.

## Prerequisites

Before you begin, ensure you have the following:
- Access to the game management portal to retrieve your `SecretKey`.
- Your application's `TitleID`.
- A backend server to securely store sensitive information and handle requests.

## Setup

1. Clone the repository to your local machine.
2. Replace placeholder values with your actual `SecretKey` and `TitleID` in the server-side code (not included in this repository).
3. Configure your backend server to handle POST requests from the form.

## Usage

To use this form:
1. Host the HTML file on your server.
2. Direct users to the form page.
3. Upon form submission, the backend server will process the request.

## Security

**Important**: Never store sensitive information like `SecretKey` and `TitleID` on the client side. Always use server-side or environment variables to handle such data securely.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

## Acknowledgments

- This form is designed for educational purposes.
- Thanks to all contributors who have helped to improve this project.

