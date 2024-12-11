# Financial Assistant Chatbot

A simple financial assistant chatbot built with Python and Streamlit. This chatbot is designed to help users with personal finance topics like budgeting, investing, savings, loans, and more.

---

## Features

- **Intent Recognition**: The chatbot identifies user queries based on predefined patterns and intents.
- **Dynamic Responses**: Provides helpful financial advice and explanations for common questions.
- **Streamlit Interface**: A user-friendly web app for seamless interactions.
- **Machine Learning**: Uses TF-IDF vectorization and logistic regression to predict user intents.

---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/AbhishekP2003/financial-assistant-chatbot.git
2. Navigate to the project directory:
   ```bash
   cd healthcare-chatbot
   
3. Create a Virtual Environment (Optional but Recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt

5. Run the application:
   ```
   streamlit run financial_asst_chatbot.py
   ```
   
   Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response

---

## Images
- Greetings!
  ![Greetings](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/eda836790da4ccc9c69476a61b384ae9286e0f50/Greetings.png)

- Budgeting
  ![Budgeting](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/4daefce61242db80758aee0a6fe4c8b36513a57c/Budgeting.png)

- Investing
  ![Investing](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/79893903dde35f8ee184029fe263eee123cbd224/Investing.png)

- Savings
  ![savings](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/adf44f7da857d193b5c91a94041558051d64e883/Savings.png)

- Loans
  ![loans](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/2789c2fae5e92d84880dce8e5d0b507f4b3ba263/Loans.png)

- Stockmarket
  ![stockmarket](https://github.com/AbhishekP2003/Financial-assistant-chatbot/blob/1088a11bfb62ae31c952556ca05db7681e8a56a8/Stockmarket.png)

- Good Bye
  ![Good Bye]

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---

Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.

---

