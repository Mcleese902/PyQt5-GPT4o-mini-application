ChatGPT-4o Mini Assistant
ChatGPT-4o Mini Assistant is a simple PyQt5 application designed to interact with OpenAI's GPT models. It provides a user-friendly interface for managing personas, customizing prompts, and chatting with an AI assistant. The application is designed for those who want more control over the AI model's behavior and responses.

Features
Persona Management: Create, edit, and delete personas. Each persona can have a unique prompt, tone, and associated documents that the AI references.
Customizable Prompts: Set specific prompts for the AI based on the selected persona to tailor the assistant's responses.
Document Management: Upload documents to further train or inform the AI persona on specific subject matter.
Response Tone: Choose the tone of the AI's responses (e.g., Formal, Informal, Friendly, Professional).
Light/Dark Mode: Toggle between light and dark mode for a comfortable user experience.
Session Management: Manage chat sessions with the ability to save, load, and clear conversations.
Installation
To install and run the ChatGPT-4o Mini Assistant, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/chatgpt4o-mini-assistant.git
cd chatgpt4o-mini-assistant
Set up a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set your OpenAI API key:

Open the main.py file.
Replace 'your-openai-api-key' with your actual OpenAI API key.
Run the application:

bash
Copy code
python main.py
Usage
Login/Registration:

Upon starting the application, you'll be prompted to log in or register. Registration currently does not require email verification to streamline the testing and development process.
Persona Management:

Use the "Manage Personas" option under the Settings menu to create, edit, or delete personas. Each persona can have a unique prompt and documents that guide the AI's responses.
Chat:

Select a persona, set a custom prompt if needed, and start chatting with the AI. The chat history is displayed in the main window, and you can export or import conversations as needed.
Toggle Light/Dark Mode:

Switch between light and dark themes using the "Toggle Dark Mode" option in the Settings menu.
Set Persona Tone:

Adjust the tone of the AI's responses by selecting the "Set Persona Tone" option in the Settings menu.
File Structure
main.py: The main application file containing the UI logic and interaction with the OpenAI API.
persona_manager.py: Handles persona creation, editing, deletion, and document management.
session_memory.py: Manages chat session memory.
requirements.txt: Lists the dependencies required to run the application.
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
OpenAI for the GPT models that power this application.
PyQt5 for the user interface framework.
Python for providing the programming language used to develop this project.
