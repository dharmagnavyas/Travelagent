# Customer Support Bot Tutorial

This project creates a customer support bot for Swiss Airlines using the LangChain library, SQLite database, and OpenAI's GPT-4 model. The bot can handle various tasks such as fetching user flight information, searching for flights, updating tickets, canceling tickets, and providing recommendations for hotels, car rentals, and excursions.

## Prerequisites

- Python
- OpenAI API Key
- Tavily API Key
- LangChain API Key

## Installation

1. **Create a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add your API keys:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   TAVILY_API_KEY=your_tavily_api_key
   LANGCHAIN_API_KEY=your_langchain_api_key
   ```

## Usage

1. **Run the script:**

   ```bash
   python main.py
   ```

2. **Interact with the bot:**

   The bot will prompt you to enter questions. Below are some example questions you can ask:

### Example Questions

1. **What are my flight timings?**

2. **What are the available options to update my flight for the same departure and arrival?**

3. **Is there any availability next week?**

4. **Can you tell me available options for my week-long stay for any dates?**

5. **OK, could you place a reservation for any recommended hotel on any date in BSL? It sounds nice.**

6. **Yes, go ahead and book anything that's moderately expensive and has availability.**

7. **Now for a car, what are my options?**

8. **Awesome, let's just get the cheapest option. Go ahead and book for 7 days.**

9. **Cool, so now what recommendations do you have on excursions?**

10. **Are they available while I'm there?**

11. **Interesting, I like the mountains, what options are there?**


## Notes

- Ensure your environment variables are correctly set up before running the script.
- Make sure to add .env file having api keys for langchain, openai and travly.
- You might need to adjust the example dates and locations to match the data available in your SQLite database.
