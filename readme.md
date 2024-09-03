# Knoledge Graph RAG with LLaMa 3.1, LangChain, Ollama & Neo4j

## Overview
This project utilizes various libraries and services such as Neo4j for database management and OpenAI for AI functionalities. The project is configured to run in a Python environment.

## Setup

### Prerequisites
- Python 3.9
- pip (Python package installer)

### Installation

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create a virtual environment:**
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Configure environment variables:**
    - Copy the [`.env.example`] file to [`.env`]:
        ```sh
        cp .env.example .env
        ```
    - Fill in the required values in the [`.env`] file:
        ```env
        NEO4J_URI = <your-neo4j-uri>
        NEO4J_USERNAME = <your-neo4j-username>
        NEO4J_PASSWORD = <your-neo4j-password>
        OPENAI_API_KEY = <your-openai-api-key>
        ```

## Usage

### Running the Jupyter Notebook
1. **Start Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```
2. **Open and run the [`notebook.ipynb`].**

## Dependencies
The project relies on the following Python packages:
- [`langchain`]
- [`langchain-community`]
- [`langchain-openai`]
- [`langchain-ollama`]
- [`langchain-experimental`]
- [`neo4j`]
- [`tiktoken`]
- [`yfiles_jupyter_graphs`]
- [`python-dotenv`]

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Please feel free to contribute by making a pull request.

## Acknowledgments
- [Neo4j](https://neo4j.com/)
- [OpenAI](https://openai.com/)