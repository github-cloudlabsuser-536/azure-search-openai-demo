# Backend

This folder contains the main server-side code for the application.

## Files

1. **app.py**: This is the main application file. It contains the main server routes and handlers. The `upload` function handles file uploads from users, and the `config` function returns the current application configuration.

2. **approaches/chatreadretrieveread.py**: This file contains the implementation of the chat approach. It uses the OpenAI ChatCompletion API and Azure AI Search to generate responses to user queries.

## Setup

To set up the backend, follow these steps:

1. Install the required dependencies with `pip install -r requirements.txt`.
2. Run the server with `python app.py`.

## Usage

Once the server is running, you can interact with it through the following endpoints:

- `POST /upload`: Upload a file to the server.
- `GET /config`: Get the current server configuration.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](../CONTRIBUTING.md) before getting started.