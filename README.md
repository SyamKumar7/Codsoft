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
    print("I'm not sure I understand. Could you try rephrasing?")```




# Tic-Tac-Toe AI

This project implements an AI agent that plays the classic game of Tic-Tac-Toe against a human player. The AI is designed to be unbeatable by leveraging algorithms like Minimax, with or without Alpha-Beta Pruning. This project is a great way to explore concepts in game theory, decision-making, and basic search algorithms.

---

## Features

- **Unbeatable AI**: The AI uses the Minimax algorithm to evaluate all possible moves and choose the optimal one.
- **Alpha-Beta Pruning**: Reduces the search space for faster decision-making (optional).
- **Human vs AI**: Play against the AI in an interactive console-based game.
- **Dynamic Board**: The game updates and displays the Tic-Tac-Toe board after every move.

---

## How It Works

1. **Minimax Algorithm**: 
   - Explores all possible moves for the AI and the human player.
   - Calculates the score for each move to determine the optimal play.
2. **Alpha-Beta Pruning** (Optional):
   - Optimizes Minimax by eliminating branches that don’t affect the final decision.
3. **Win, Lose, or Draw**:
   - The AI ensures it never loses by always selecting the best possible move.
4. **User Interaction**:
   - The human player chooses their moves by entering the row and column numbers.

---

## Prerequisites

- Python 3.6 or higher installed on your system.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-ai.git
   cd tic-tac-toe-ai

