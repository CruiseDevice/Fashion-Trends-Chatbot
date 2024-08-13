# Fashion Trends Chatbor

## Overview

This project involves the creation of a custom chatbot designed to provide users with insights into the latest fashion trends for 2023. The chatbot utilizes a dataset containing detailed descriptions of various fashion trends, sourced from reputable fashion publications. By leveraging natural language processing and machine learning, the chatbot offers users tailored responses based on specific queries.

## Dataset

The dataset used in this project is `2023_fashion_trends.csv`, which contains 94 rows of data. Each row includes:
- **URL**: The web address where the fashion trend is discussed.
- **Trends**: A description of the fashion trend, including styles, colors, and influences.
- **Source**: The title of the article or publication where the trend is featured.

## Use Case

The primary goal of this chatbot is to assist fashion enthusiasts, shoppers, and industry professionals in staying updated with current fashion trends. It provides detailed insights and recommendations, helping users make informed fashion choices.

## Features

- **Interactive Q&A**: Users can ask questions about 2023 fashion trends and receive detailed responses.
- **Custom Prompts**: The chatbot uses custom prompts with context from the dataset to generate precise answers.
- **Continuous Interaction**: Users can interact with the chatbot in a loop, asking multiple questions in a single session.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/CruiseDevice/Fashion-Trends-Chatbot.git
    cd fashion-trends-chatbot

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt

3. Set Up OpenAI API Key:
    - Create a `.env` file in the project root directory
    - Add your OpenAI API key to the `.env` file:
    ```bash
    OPENAI_API_KEY=your_openai_api_key_here

4. Run the Chatbot
    - Run the notebook in `vscode` or `jupyter notebook`

## Usage

- The chatbot will prompt you to enter questions about fashion trends
- Type your question and press Enter to receive a response
- Type 'exit' to end the session.

## Example Question

- "What are the key fashion trends for 2023?"
- "How can I incorporate cobalt blue into my wardrobe?"
