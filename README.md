# Local AI Agent

    This project is a local AI-powered question-answering application designed to provide expert answers about a pizza restaurant based on relevant reviews.

    ## Features

    - Uses the `OllamaLLM` model for generating responses.
    - Retrieves relevant reviews using a vector-based retriever.
    - Allows users to ask questions interactively in a terminal-based interface.

    ## Requirements

    - Python 3.8 or higher
    - Required Python packages:
        - `langchain_ollama`
        - `langchain_core`
        - `vector`
        - `pandas`

    ## Installation

    1. Clone this repository or download the code.
    2. Install the required Python packages:
         ```bash
         pip install langchain_ollama langchain_core vector pandas
         ```

    ## Usage

    1. Run the script:
         ```bash
         python /C:/Users/mateo/Desktop/Local AI Agent/main.py
         ```
    2. Enter your question about the pizza restaurant when prompted.
    3. Type `q` to quit the application.

    ## File Structure

    - `main.py`: The main script that runs the application.
    - `vector.py`: Contains the `retriever` logic for fetching relevant reviews.

    ## Customization

    - Modify the `template` variable in `main.py` to change the prompt used for generating responses.
    - Replace the `model` parameter in `OllamaLLM` with a different model if needed.

    ## License

    This project is licensed under the MIT License. See the LICENSE file for details.