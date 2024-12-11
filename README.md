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

- Symptoms
  ![symptoms](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/57a10b7d45c4d0badc2861b74a43da7aaf5f03d9/symptoms.png)

- Treatment
  ![treatment](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/e7abd4e2e6f68611101495c4e075f06d78785a43/treatment.png)

- Appointment
  ![appointment](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/e7abd4e2e6f68611101495c4e075f06d78785a43/appointment.png)

- Nutrition
  ![nutrition](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/e7abd4e2e6f68611101495c4e075f06d78785a43/nutrition.png)

- Mental Health
  ![Mental Health](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/e7abd4e2e6f68611101495c4e075f06d78785a43/Mental_health.png)

- Good Bye
  ![Good Bye](https://github.com/diwakarnagaraju/Healthcare-chatbot/blob/e7abd4e2e6f68611101495c4e075f06d78785a43/Goodbye.png)

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

