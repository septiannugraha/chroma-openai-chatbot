# Chatbot with Memory using ChromaDB and OpenAI's GPT-3.5 Model

This is a Python project demonstrating how to create a chatbot with a memory-like feature using ChromaDB and OpenAI's GPT-3.5 model. This chatbot is capable of referring to past interactions when generating responses, overcoming the limitations of context window size in certain OpenAI models.

## Features

- User interface for interacting with the chatbot
- Chat history storage using ChromaDB
- Use of embeddings for querying past interactions
- Memory-like feature allowing the bot to refer to past interactions

## Prerequisites

- Python 3.7+
- An OpenAI API key
- ChromaDB

## Setup and Installation

1. Clone this repository

    ```bash
    git clone https://github.com/septiannugraha/chroma-openai-chatbot.git
    ```

2. Change into the directory

    ```bash
    cd chroma-openai-chatbot
    ```

3. Install the required Python packages

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables

    Create a .env file in the root directory and set the following environment variables:

    ```env
    OPENAI_KEY=your_openai_key
    MODEL_NAME=model_name
    EMBEDDING_MODEL=embedding_model_name
    ```

## Usage

Run the Python script `main.py`:

```bash
python main.py
```

## Contributing

Please feel free to contribute to this project. Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.