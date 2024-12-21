# LangChain Notebooks

This repository contains Jupyter notebooks demonstrating various features of LangChain, including models, prompts, output parsers, memory, chains, and Q&A over documents.

## Repository Structure

### Notebooks

1. **L1-Model_prompt_parser.ipynb**: Demonstrates how to use LangChain for making API calls to OpenAI, creating prompts, models, and output parsers.
2. **L2-Memory.ipynb**: Explores different types of memory in LangChain, including ConversationBufferMemory, ConversationBufferWindowMemory, ConversationTokenBufferMemory, and ConversationSummaryMemory.
3. **L3-Chains.ipynb**: Shows how to create and use different types of chains in LangChain, such as LLMChain, SimpleSequentialChain, SequentialChain, and Router Chain.
4. **L4-QnA.ipynb**: Provides an example of how to perform Q&A over documents using LangChain.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment:
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up your OpenAI API key:
    - Copy [.envexample](http://_vscodecontentref_/5) to [.env](http://_vscodecontentref_/6):
        ```sh
        cp .envexample .env
        ```
    - Replace `sk-xxxxxx-xxxxxx-xxxxxx-xxxxxx` in [.env](http://_vscodecontentref_/7) with your actual OpenAI API key.

## Usage

Open the Jupyter notebooks using Jupyter Lab or Jupyter Notebook:
```sh
jupyter lab
# or
jupyter notebook