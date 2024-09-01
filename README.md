# Ethical AI Interaction Monitor

This project is a prototype for an Ethical AI Interaction Monitor designed to ensure that AI systems, particularly in sensitive fields like finance, law, and medicine, adhere to ethical guidelines during interactions with users.

## Project Structure

- **model.py**: Contains the core functions to load rules, generate AI responses, check for compliance with rules, and add new rules.
- **app.py**: The Streamlit app that provides a user interface for interacting with the AI and a trainer interface for adding new rules.
- **rules.json**: Contains the initial ethical rules for the AI to follow.
- **requirements.txt**: Lists all the dependencies needed to run the project.
- **README.md**: This documentation file.

## How to Run the Project

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/EthicalAIInteractionMonitor.git
    cd EthicalAIInteractionMonitor
    ```

2. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:
    ```sh
    streamlit run app.py
    ```

4. **Open your browser** and go to `http://localhost:8501` to interact with the app.

## Features

- **User Interface**: Ask any question, and the AI will respond while ensuring compliance with ethical guidelines.
- **Trainer Interface**: Add new rules to the system, specifying the category, keywords, and rules to be enforced.

## Deployment

This project can be deployed on any platform that supports Streamlit. For deploying on Streamlit Cloud, simply push the repository to GitHub and connect it to Streamlit Cloud.

## License

This project is licensed under the MIT License.
