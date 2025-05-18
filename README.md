# Autogen Chat Agent Setup

## Project Overview
The Autogen Chat Agent is a versatile and autonomous agent designed to execute tasks based on a given prompt without user intervention. It leverages the power of OpenAI's GPT models to efficiently complete tasks, offering reliable and self-driven execution.

## Prerequisites
Make sure you have Python installed on your system. The recommended version is Python 3.8 or higher.

## Installation

1. Install the required packages using pip:
```
pip install autogen httpx
```


## Setting Up the LLM Configuration

In your Python script, set up the LLM configuration as follows:

```python
config_list = [
    {
        "model": "gpt-4o",
        "api_key": "",  # Add your API key here
        "api_type": "azure",
        "base_url": "",  # Add the base URL here
        "api_version": "",  # Specify the API version here
    }
]
```

Replace the placeholders in the configuration with your actual values:

- **api_key**: Your Azure OpenAI API key.
- **base_url**: The base URL for your Azure OpenAI instance.
- **api_version**: The version of the API you are using.

## Running the Agent
After setting up the configuration, run your Python script (**autogen_chat.py**) to initialize the Autogen Agent:

```
python autogen_chat.py
```
## Troubleshooting
- Make sure the **API key** and **URL** are correctly configured.
- Ensure that all required packages are installed.

For any issues, please refer to the official **Autogen** and **HTTPX** documentation.
