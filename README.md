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

<img width="1440" alt="NLP_coffee_chatbot_ss" src="https://github.com/KIN156/NLP_Coffee_Chatbot/assets/67004684/b8800ee1-05ba-4ea7-bc90-29f393c36f0c">


## Contributing

Contributions to this project are welcome. If you have ideas for improvements or additional features, please fork the repository, make your changes, and submit a pull request.

## License

This project is available under the [MIT License](LICENSE.md). You are free to use, modify, and distribute the code for both educational and commercial purposes.

---

**Author:** Kinjalkumari Dhimmar
**Contact:** kinjalkumaridhimmar@gmail.com
**LinkedIn:** https://www.linkedin.com/in/dhimmar-kinjal/
