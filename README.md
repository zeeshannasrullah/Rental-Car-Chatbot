# Rental-Car-Chatbot

The main purpose of the chatbot is to assist users by answering questions related to vehicle availability, rental prices, and booking information in a simple and interactive way.

The chatbot uses semantic similarity with transformer-based embeddings to understand user queries and provide accurate responses from a predefined dataset. If a suitable answer is not found, it falls back to a basic conversational model to continue the interaction smoothly. A Gradio-based web interface is used to make the chatbot easy to use for beginners and non-technical users.
The chatbot answers user queries related to car availability, pricing, and rentals by combining semantic similarity (MiniLM embeddings) with a rule-based conversational fallback (ChatterBot) and provides an interactive Gradio web interface.

## Technologies Used

Python

Sentence Transformers (all-MiniLM-L6-v2)

ChatterBot & ChatterBot Corpus

spaCy (en_core_web_sm)

Gradio
