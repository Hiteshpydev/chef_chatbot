# Chef Auguste Chatbot 🧑‍🍳

## Project Overview

This is an AI-powered chatbot designed to act as "Chef Auguste," a professional, world-renowned chef. It aims to provide culinary guidance, share recipes, explain cooking techniques, and offer ingredient expertise in a confident, encouraging, and sophisticated tone. The bot is built using the Google Gemini API.

## Features ✨

* **Professional Chef Persona:** Responds as a knowledgeable and experienced culinary expert.
* **Recipe Guidance:** Provides clear and detailed recipes.
* **Technique Explanation:** Breaks down complex cooking methods.
* **Ingredient Insights:** Offers advice on selection, seasonality, and pairings.
* **Problem Solving:** Helps troubleshoot common kitchen issues.
* **Interactive Chat:** Maintains context through chat history for engaging conversations.

## Technologies Used 🛠️

* **Python:** The core programming language.
* **Google Gemini API:** Powers the AI's natural language understanding and generation.
* **`google-generativeai` library:** Python client library for interacting with the Gemini API.
* **`python-dotenv`:** Used for securely loading API keys from a `.env` file.

## Setup and Installation 🚀

To run this chatbot locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/chef-chatbot-auguste.git](https://github.com/YOUR_GITHUB_USERNAME/chef-chatbot-auguste.git)
    cd chef-chatbot-auguste
    ```
    (Replace `YOUR_GITHUB_USERNAME` and `chef-chatbot-auguste` with your actual GitHub username and repository name.)

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install google-generativeai python-dotenv
    ```

4.  **Set up your Gemini API Key:**
    * Obtain a Google Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    * Create a file named `.env` in the root directory of your project (the same directory as `main.py` or your primary script).
    * Add your API key to the `.env` file in the following format:
        ```
        KEY=YOUR_GEMINI_API_KEY_HERE
        ```
        (Replace `YOUR_GEMINI_API_KEY_HERE` with your actual API key.)

5.  **Run the chatbot:**
    ```bash
    python your_main_script_name.py
    ```
    (Replace `your_main_script_name.py` with the actual name of your Python file, e.g., `app.py` or `main.py`).


