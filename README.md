# Streamlit Interview Chatbot 🤖

This project is an interactive interview chatbot built with [Streamlit](https://streamlit.io/) and [OpenAI GPT](https://platform.openai.com/). It simulates an HR interview experience, collects user information, conducts a mock interview, and provides AI-generated feedback.

## Features

- Collects personal and professional information from the user
- Simulates an interview for various tech positions and companies
- Uses OpenAI's GPT model for dynamic interview questions and responses
- Provides a feedback score and summary at the end of the interview

## Setup

1. **Clone the repository**

    ```bash
        git clone <your-repo-url>
        cd Prototype
    ```

2. **Install dependencies**

    ```bash
        pip install -r requirements.txt
    ```

3. **Configure OpenAI API Key**

- Create a file at `.streamlit/secrets.toml`

4. **Run the app**

    ```bash
        streamlit run [app.py](http://_vscodecontentref_/0)
    ```

## Usage

- Fill in your personal information and select the desired position and company.
- Start the interview and answer the chatbot's questions.
- After 5 responses, click "Get Feedback" to receive your interview score and feedback.
- Optionally, restart the interview for more practice.

## Requirements

- Python 3.7+
- See `requirements.txt` for Python dependencies.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

