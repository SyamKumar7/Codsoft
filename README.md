# Codsoft
# Chatbot with Rule-Based Responses

This project is a simple chatbot that responds to user inputs using predefined rules. It is built using basic programming constructs like `if-else` statements or pattern matching to identify user queries and provide appropriate responses. This project serves as an excellent starting point to understand natural language processing (NLP) concepts and conversation flow.

---

## Features

- **Rule-Based Responses**: Handles user inputs with predefined rules and provides relevant responses.
- **Customizable Rules**: Easily extend the chatbot by adding new rules.
- **Lightweight Design**: Built using only core Python, with no additional dependencies.
- **Fallback Handling**: Responds gracefully when inputs do not match any predefined rules.

---

## How It Works

1. **Rule Matching**: User inputs are matched against predefined patterns or keywords.
2. **Predefined Responses**: Based on the matched input, the chatbot selects a relevant response.
3. **Fallback Response**: When no match is found, the chatbot provides a generic response like “I don’t understand that.”

### Example Rule
```python
if "hello" in user_input.lower():
    print("Hello! How can I assist you?")
elif "bye" in user_input.lower():
    print("Goodbye! Have a great day!")
else:
    print("I'm not sure I understand. Could you try rephrasing?")
