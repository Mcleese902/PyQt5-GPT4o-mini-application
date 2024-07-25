# GPT-4 Mini Chat UI

A Python/PyQt5-based mini chat application using GPT-4 for conversational AI. This application provides a simple and interactive user interface for chatting with a GPT-4 model.

## Features

- Simple and intuitive user interface built with PyQt5
- Seamless integration with GPT-4 for natural language conversations
- Secure authentication (not included in the public repo for privacy reasons)
- Easy setup and configuration

## Requirements

- Python 3.7+
- PyQt5
- OpenAI GPT-4 API key
- SQLite

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Mcleese902/gpt4-mini-chat-ui.git
    cd gpt4-mini-chat-ui
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Initialize the database:**

    ```bash
    python init_db.py
    ```

5. **Run the application:**

    ```bash
    python main.py
    ```

## Files

- `gpt4o-mini_chat.py`: Core application file for the GPT-4 chat interface.
- `gpt4o-mini_chat.spec`: Spec file for PyInstaller to create an executable.
- `init_db.py`: Script to initialize the SQLite database.
- `main.py`: Main entry point for the application.
-
## Usage

Once the application is running, you'll see a graphical user interface where you can start chatting with the GPT-4 model. Enter your text in the input field and press Enter to send your message. The GPT-4 model will respond accordingly.

## Authentication

The authentication system is designed to be secure and private. It is not included in the public repository to protect personal login information. Ensure that you set up your own authentication mechanism if you fork or modify this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- PyQt5 for the user interface framework
- OpenAI for the API

##  Contact

For any questions or suggestions, please contact support@blackdiamondtech.ca .
