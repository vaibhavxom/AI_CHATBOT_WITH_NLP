# AI CHATBOT WITH NLP


## Overview

This project implements a simple AI chatbot using Natural Language Processing (NLP) techniques with the help of the NLTK library. The chatbot is designed to understand basic user inputs and respond appropriately based on predefined patterns and responses. It can handle greetings, farewells, expressions of gratitude, and inquiries about its identity.

## Features

- **Greeting Recognition**: The chatbot can recognize various greetings and respond accordingly.
- **Goodbye Handling**: It can acknowledge when the user wants to end the conversation.
- **Thank You Responses**: The chatbot can respond to expressions of gratitude.
- **Identity Inquiry**: It can provide information about itself when asked for its name.
- **Default Response**: If the input does not match any predefined patterns, the chatbot will respond with a default message.

## Requirements

- Python 3.x
- NLTK library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vaibhavxom/AI_CHATBOT_WITH_NLP.git
    cd AI_CHATBOT_WITH_NLP
    ```
#
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```
#
3. Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
#
4. Install dependencies:
    ```bash
   pip install nltk
    ```
    
Run the application:
```bash
python chatbot.py
```
## Code Explanation
**Imports**: The script imports necessary libraries such as nltk, random, string, and re.  
**Patterns and Responses**: Predefined patterns and corresponding responses are stored in dictionaries for easy access.  
**Input Preprocessing**: The preprocess_input function converts user input to lowercase and removes punctuation for better matching.  
**Response Generation**: The get_response function checks the user input against predefined patterns and returns a random response from the corresponding category.  
**Chatbot Loop**: The chatbot function runs an infinite loop, allowing the user to interact with the chatbot until they choose to exit.

## Example Interaction  

![image](https://github.com/user-attachments/assets/fb23eb9e-9540-4f16-84a0-a1241e41558b)


