# 📚 Book Recommendation Chatbot

This project is a **Book Recommendation Chatbot** built using **IBM Watson Assistant**. It interacts with users and recommends books based on genres, user mood, and feedback. The chatbot is designed to simulate human-like conversation while offering personalized book suggestions.

## 🔧 Features

- User-friendly chatbot interface
- Book recommendations based on genre or user interest
- Handles feedback (positive/negative)
- Randomized response generation for better user experience
- Built using IBM Watson Assistant and JSON configuration

## 💻 Technologies Used

- IBM Watson Assistant
- JSON for dialog flow
- Intents, Entities, and Dialog Nodes
- Git for version control

## 📁 Project Structure

Book-Recommendation-Chatbot/
│
├── ChatBot/
│   ├── intents.json       # User intents like 'recommend\_book', 'feedback'
│   ├── entities.json      # Entities such as book genres (e.g., fiction, thriller)
│   ├── dialog\_nodes.json  # Dialog flow configuration
│   └── workspace.json     # Complete workspace export (Watson Assistant)
│
└── README.md              # Project documentation


## 🚀 Getting Started

1. Clone this repository:
  
   git clone https://github.com/shreyakesharwani-7/Book-Recommendation-Chatbot.git


2. Navigate to the ChatBot directory:

   cd Book-Recommendation-Chatbot/ChatBot

3. Train the assistant using provided intents, entities, and dialog nodes.

## 🧠 Sample Intents

* `#recommend_book` – Suggest books to user
* `#feedback` – Accept and analyze user feedback
* `#greet`, `#goodbye` – Basic conversational intents

## 🧩 Sample Entities

* `@genre` – Fiction, Thriller, Romance, Sci-fi, Mystery, etc.
* `@feedback` – Positive, Negative, Neutral

## 🤖 Example Conversations

**User:** Can you suggest a good thriller?
**Bot:** Sure! You might enjoy *The Girl with the Dragon Tattoo* by Stieg Larsson.

**User:** I loved the last book you suggested!
**Bot:** I'm glad you enjoyed it! Would you like another recommendation?

## 🙋‍♀️ Author

**Shreya Kesharwani**
📧 [shreyakesharwani5524@gmail.com](mailto:shreyakesharwani5524@gmail.com)
🔗 [GitHub](https://github.com/shreyakesharwani-7) | [LinkedIn](https://www.linkedin.com/in/shreyakesharwani70/) | [GFG](https://www.geeksforgeeks.org/user/shreyakesharwani/)


- Additional intents/entities setup guide
