# FastAPI Authentication Boilerplate

![FastAPI Logo](https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png)

[![Build Status](https://img.shields.io/travis/yourusername/yourreponame.svg)](https://travis-ci.org/yourusername/yourreponame)
[![Coverage Status](https://img.shields.io/coveralls/yourusername/yourreponame.svg)](https://coveralls.io/r/yourusername/yourreponame)

This repository contains boilerplate code for setting up user authentication in a [FastAPI](https://fastapi.tiangolo.com/) web application. It aims to provide a solid starting point for FastAPI projects requiring user authentication.

## Features

- [ ] User registration and login
- [ ] Token-based authentication (JWT)
- [ ] Secure password hashing
- [ ] Email confirmation flow
- [ ] Password reset functionality
- [ ] Role-based access control

## Getting Started

### Prerequisites

- Python 3.10 or higher
- Pip

### Installation

1. Clone this repository:

    ```sh
    git clone https://github.com/mmathew23/fastapi_auth.git
    cd fastapi_auth
    ```

2. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

3. Set environment variables:

    ```sh
    export SECRET_KEY=your-secret-key
    export DATABASE_URL=your-database-url
    export SMTP_HOST=your-smtp-host
    export SMTP_PORT=your-smtp-port
    export EMAIL_USERNAME=your-email
    export EMAIL_PASSWORD=your-email-password
    ```

4. Run the application:

    ```sh
    uvicorn app.main:app --reload
    ```

5. Visit `http://127.0.0.1:8000` in your browser to view the application.

## Usage

For a complete guide on how to use this boilerplate code, including customizing it for your own needs, see the [documentation](https://github.com/mmathew23/fastapi_auth/wiki).

## Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) for more information on how to get involved.

## License

This project is licensed under the terms of the MIT license. See [LICENSE](LICENSE) for additional details.

## Acknowledgments

- [FastAPI](https://fastapi.tiangolo.com/) - For the awesome web framework!

