# College Chatbot

A Flask-based chatbot application designed to provide information about colleges. The bot utilizes the dataset of colleges and responds to user queries about various aspects like hostel availability and fees, as well as other general queries. The chatbot can respond based on a dataset provided and general knowledge.

## Features

- **Flask Web Framework**: For building the web app and handling routes.
- **Dataset Integration**: The chatbot uses a CSV file (`collegedataset.csv`) containing college details like names, hostel availability, and hostel fees etc.
- **Generative AI**: Utilizes Google’s Generative AI model to generate responses based on user queries.
- **Session Management**: Stores user history and context, including the detected college name for personalized responses.

## Requirements

- Python 3.x
- Flask
- Pandas
- langchain_google_genai
