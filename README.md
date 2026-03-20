# Simple Chatbot 🤖

## Overview

This Python program implements a basic rule-based chatbot that interacts with users through text input. It responds to specific keywords using predefined replies and provides random fallback responses when it doesn't understand the input.

## Features

* Interactive command-line chatbot
* Recognizes simple keywords (e.g., "hello", "how are you", "bye", "name")
* Provides multiple responses for variety using random selection
* Handles unknown inputs with default replies
* Exit option to end the conversation

## Requirements

* Python 3.x

## How It Works

* The chatbot uses a dictionary of predefined responses mapped to keywords.
* When a user enters a message:

  * The input is converted to lowercase.
  * The program checks if any keyword exists in the input.
  * If a match is found, a random response is selected and displayed.
  * If no match is found, a default response is shown.
* The chat continues in a loop until the user types `"exit"`.

## Usage

1. Run the script:

   ```bash
   python chatbot.py
   ```
2. Start chatting with the bot.
3. Type `exit` to end the conversation.

## Example

```
🤖 Chatbot: Hello! Type 'exit' to quit.

You: hello
🤖 Chatbot: Hi there!

You: how are you
🤖 Chatbot: Doing great!

You: what is AI?
🤖 Chatbot: I don't understand that.

You: exit
🤖 Chatbot: Goodbye!
```

## Customization

You can easily expand the chatbot by editing the `responses` dictionary:

```python
responses = {
    "your_keyword": ["Response 1", "Response 2"]
}
```

## File Structure

```
chatbot.py
README.md
```

## Limitations

* Does not understand complex sentences
* No natural language processing (NLP)
* Works only with keyword matching

## Future Improvements

* Add NLP using libraries like NLTK or spaCy
* Integrate machine learning for smarter responses
* Build a graphical user interface (GUI)
* Add voice input/output

## License

This project is open-source and free to use.

