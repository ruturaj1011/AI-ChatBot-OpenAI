# AI Chatbot

## Introduction
This project is a software development chatbot designed to assist developers with coding tasks, provide programming advice, and answer technical questions. The chatbot is powered by OpenAI's API.

## Installation
To install and set up the project, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/software-dev-chatbot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd software-dev-chatbot
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```

## Setup OpenAI API Key
To use the OpenAI API, you need to set up your API key:
1. Obtain your OpenAI API key from [OpenAI](https://beta.openai.com/signup/).
2. Create a file named config.js in the root directory of the project and add your OpenAI API key:
``` // config.js
        module.exports = {
            OpenAIAPIKey: 'your-openai-api-key-here'
        };

## Usage
To start the chatbot, run the following command:
```bash
npm start
```
Once the chatbot is running, you can interact with it through the command line or integrate it with your preferred messaging platform.

