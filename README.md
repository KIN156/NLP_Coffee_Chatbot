# NLP_Coffee_Chatbot

This repository contains the code and resources for a Coffee Ordering Chatbot. The chatbot is designed to take coffee orders from users and provide responses based on user input.

## Files Included

### `preprocessing.py`

This Python script is responsible for preprocessing the data and training the machine learning model used by the chatbot. Here are the key steps and components:

- Load data from the `kinjalkumari_intents.json` file.
- Extract patterns, responses, and intents from the data.
- Encode the list of intents.
- Tokenize the patterns using the Keras tokenizer.
- Define the model architecture.
- Compile and fit the data to the model for training.
- Save the trained tokenizer, encoder, and model to the hard disk.

### `chatbotv2.py`

This Python script implements the Coffee Ordering Chatbot. Here are the main functionalities:

- Load the intents JSON file and saved tokenizer, encoder, and model.
- Define functions to predict user intents and provide responses.
- Start a chat with the user, accepting input and providing chatbot responses.
- The chatbot can be exited by typing 'exit'.

## How to Use

1. Clone or download this repository to your local machine.
2. Ensure you have Python and the required libraries installed (TensorFlow, numpy, etc.).
3. Run the `preprocessing.py` script to preprocess data and train the model.
4. Run the `chatbotv2.py` script to start the Coffee Ordering Chatbot.


## Output

Type 'exit' to quit the chatbot
You: Can I order a coffee?
1/1 [========-==-=-================] - 0s 184ms/step
Bot: Of course! What's your order?
You: What kinds of coffee do you have?
1/1 [==============================] - Os 28ms/step
Bot: If you're looking for something bold, I recommend trying our dark roast. If you want something lighter, our blonde r
You: How much does a coffee cost?
1/1 [==============================1 - 0s 26ms/ster
Bot: Our prices vary depending on the size and type of drink. A small coffee starts at $2.50.
You: Can I get a latte please?
1/1 [==============================1 - 0s 26Ms/step
Bot: Sure thing, a latte it is!
You: What's the price of a latte?
1/1 [==============================1 - 0s 26ms/ step
Bot: A cappuccino is $3.50 for a small
You: Can I pay with a credit card?
1/1 [ess=========================== l
- Os 28ms/step
Bot: We accept all major credit cards, as well as cash.
You: Where's my order?
1/1 [==============================] - 0s 25ms/step
Bot: I'm sorry for the delay. Let me check on the status of your order.
You: Do you have cream for coffee?
171 [==
==
- Os 30ms/step
Bot: Absolutely! I'11 make sure to add that to your coffee.
You: See you later
1/1 [==============================1 - 0s 26ms/step
Bot: Take care! Come back soon!
You: exit

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or additional features, please fork the repository, make your changes, and submit a pull request.

## License

This project is available under the [MIT License](LICENSE.md). You are free to use, modify, and distribute the code for both educational and commercial purposes.

---

**Author:** Kinjalkumari Dhimmar
**Contact:** kinjalkumaridhimmar@gmail.com
**LinkedIn:** https://www.linkedin.com/in/dhimmar-kinjal/
