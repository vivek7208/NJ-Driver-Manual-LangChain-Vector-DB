# 🚗 New Jersey Driver Manual Query System 📚

This project is a Streamlit application 💻 that allows users to query information from the New Jersey Driver Manual. The application uses the OpenAI API 🧠 and the LangChain library 📖 to process and retrieve relevant information from the loaded documents.

The project highlights how to leverage a ChromaDB vectorstore in a Langchain pipeline to create a GPT Knowledge Test NJ 🗺️. You can load in a pdf-based document 📄 and use it alongside an LLM (Language Model) without the need for fine-tuning 🎛️.

## What is ChromaDB Vectorstore? 🤔

ChromaDB is a part of the LangChain library and it's used for storing vectors. A vectorstore like ChromaDB is essentially a database designed for efficient storage and retrieval of high-dimensional vectors. In the context of this project, we use it to store the document data in a format that's easy for the language model to process and retrieve.

## What is LangChain? 📖

LangChain is a Python library designed to facilitate the use of Language Models in various tasks. It provides a set of tools and abstractions to make it easier to load documents, process text, and interact with language models. In this project, we're using LangChain to load the New Jersey Driver Manual, process it into a format the language model can understand, and handle the user's queries.

## 📝 Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## ⚙️ Installation

1. Clone the repository 📂
2. Install the necessary libraries and dependencies 🧩
3. Set your OpenAI API key in the environment variables 🗝️

```bash
git clone https://github.com/username/repository.git
cd repository
pip install -r requirements.txt
export OPENAI_API_KEY="your_api_key_here"
```

## 🖥️ Usage

Once you have the project set up, you can run the Streamlit application using the command:

```bash
streamlit run app.py
```

This will start a local server and the application will be accessible via a web browser 🌐. The user can then input a query into the text box, and the application will retrieve relevant information from the New Jersey Driver Manual using OpenAI's language model.

## 👥 Contributing

Contributions are always welcome!

## ⚖️ License

This project is licensed under the terms of the MIT license. See [LICENSE](./LICENSE) for more details.
