# GenAI Medical Chatbot

## Overview
GenAI Medical Chatbot is an AI-powered conversational assistant designed to provide reliable medical information using the **LLaMA** model and **Pinecone Vector Database**. The chatbot utilizes a **Medical Encyclopedia** as a knowledge base to deliver precise and context-aware responses.

## Features
- **Conversational AI**: Leverages the LLaMA model for natural language understanding and generation.
- **Vector Search with Pinecone**: Efficient retrieval of medical information from an indexed Medical Encyclopedia.
- **Python Environment**: Built with Python and supporting libraries for seamless AI integration.
- **Context-Aware Responses**: Provides detailed, well-referenced medical insights.

## Tech Stack
- **LLama Model** – For generative AI responses.
- **Pinecone** – Vector database for efficient similarity search.
- **Medical Encyclopedia** – Used as a knowledge source.
- **Python** – Core programming language.
- **Streamlit** – For UI development.

## Installation
### Prerequisites
Ensure you have Python (>=3.8) installed.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/genai-medical-chatbot.git
   cd genai-medical-chatbot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up **Pinecone API**:
   - Create an account on [Pinecone](https://www.pinecone.io/).
   - Get your API key and configure it in the environment variables.
   ```bash
   export PINECONE_API_KEY="your_api_key"
   ```
4. Load and index the medical encyclopedia:
   ```python
   python index_medical_data.py
   ```
5. Run the chatbot:
   ```python
   python chatbot.py
   ```

## Usage
- Ask medical-related questions in natural language.
- The chatbot retrieves relevant context from the Medical Encyclopedia.
- Generates AI-powered responses based on the **LLaMA model**.

## API Integration
If using **FastAPI**, run:
```bash
uvicorn app:app --host 0.0.0.0 --port 8000
```
Then, access the chatbot API at `http://localhost:8000/docs`

## Contribution
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit changes and push to your fork.
4. Submit a Pull Request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Meta AI** for the LLaMA model.
- **Pinecone** for providing an efficient vector search database.
- **Medical Encyclopedia** sources for reliable information.

---
Feel free to customize this README with specific details about your implementation!


