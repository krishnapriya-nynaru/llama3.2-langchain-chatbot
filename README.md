# llama3.2-langchain-chatbot
## 🤖 Llama3.2 Chatbot with LangChain and Streamlit
Welcome to Llama3.2 Chatbot, a powerful conversational AI built using Ollama Llama 3.2, LangChain, and Streamlit. This chatbot is designed to deliver interactive, human-like conversations, providing smart and efficient natural language understanding.

Whether you're building an assistant, answering FAQs, or just exploring the potential of conversational AI, this project offers a modular and user-friendly foundation to get started.

## Key Features
**Llama 3.2 Integration:** Leverages the advanced capabilities of Ollama Llama 3.2 for accurate and context-aware responses.
**LangChain Framework:** Easily manage prompts, memory, and workflows with the power of LangChain.
**Streamlit UI:** A simple and sleek web interface for seamless interaction.
**Extensible Design:** Easily customizable to fit a variety of use cases.

Get started today and create your personalized conversational AI! 🌟

 ## Setup
 - [**Download**](https://ollama.com/) and install Ollama onto the available supported platforms (including Windows Subsystem for Linux)
 - Once Ollama is installed, download the Llama 3.2 model:
 ```bash
 ollama pull llama3.2:1b
 ```
 This command fetches the Llama 3.2 model and prepares it for local use.
 - Before integrating the model into the chatbot, you can test it directly using the following command:
 ```bash
 ollama run llama3.2:1b
 ```
- Clone this GitHub repository to your local machine:
```bash
git clone https://github.com/krishnapriya-nynaru/llama3.2-langchain-chatbot
```
 ## Install Dependencies
 1. pip install langchain
 2. pip install -U langchain-ollama
 3. pip install streamlit

## Run the chatbot
Launch the chatbot interface using Streamlit:
```bash
streamlit run app.py
```
Open your browser and navigate to: http://localhost:8501

Start interacting with your chatbot! 🎉

## Contributing
Contributions are welcome! To contribute to this project:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and ensure the code passes all tests.
4. Submit a pull request with a detailed description of your changes.

If you have any suggestions for improvements or features, feel free to open an issue!

## Acknowledgments
- [**llama3.2**](https://www.llama.com/)
- [**Ollama**](https://ollama.com/)
- [**Langchain**](https://python.langchain.com/docs/introduction/)
- [**ollama LLM**](https://python.langchain.com/docs/integrations/llms/ollama/)
