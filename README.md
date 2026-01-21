# LLM_Comparsion_Models
LLM Comparison Model that evaluates and compares responses from Gemini, OpenAI, and Hugging Face models using the same prompts to analyze accuracy, reasoning quality, and performance, helping users understand strengths and limitations of each LLM.

🚀 LLM Nexus – Enterprise LLM Comparison Platform

LLM Nexus is a Streamlit-based web application that enables side-by-side comparison of multiple Large Language Models (LLMs) such as OpenAI (ChatGPT), Google Gemini, and Meta LLaMA.
The platform supports parallel execution, fallback handling, authentication, and report generation, making it suitable for academic, research, and enterprise evaluation.

📌 Project Objective

The main goal of this project is to:

Analyze and compare responses from different LLMs

Understand performance, accuracy, and reliability of LLMs

Provide a unified interface to evaluate multiple AI models

Handle API failures using fallback mechanisms


🧱 Project Structure
LLM_Model_Project/
│
├── app.py # Main Streamlit application
├── auth.py # Authentication & access control
├── config.py # Application configuration
│
├── models/ # LLM integrations
│ ├── chatgpt_model.py # OpenAI ChatGPT integration
│ ├── gemini_model.py # Google Gemini integration
│ └── llama_model.py # Meta LLaMA integration
│
├── utils/ # Utility modules
│ ├── router.py # Model routing & fallback logic
│ ├── parallel.py # Parallel execution handler
│ ├── rate_limiter.py # API rate limiting
│ └── report.py # Response comparison & reports
│
├── data/ # Input / output storage
├── .env # API keys (ignored in GitHub)
├── .venv/ # Virtual environment (ignored)
└── pycache/ # Cache files


🛠️ Technologies Used

Python 3.10

Streamlit – Web UI

Pandas – Data processing

dotenv – Environment variable management

Parallel Processing

REST APIs – OpenAI, Gemini, LLaMA

🤖 Supported LLMs
Model	Provider
ChatGPT	OpenAI
Gemini	Google
LLaMA	Meta


⚙️ Key Features

🔐 User authentication

⚡ Parallel execution of LLMs

🔁 Fallback handling

⏳ API rate limiting

📊 Response comparison reports

🌐 Interactive Streamlit dashboard


▶️ How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/your-username/LLM_Model_Project.git
cd LLM_Model_Project
2️⃣ Create Virtual Environment
python -m venv .venv
.venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Configure API Keys

Create a .env file:

OPENAI_API_KEY=your_api_key
GEMINI_API_KEY=your_api_key
HUGGINGFACE_API_KEY=your_api_key

5️⃣ Run Application
streamlit run app.py

📈 Applications / Use Cases

LLM benchmarking

AI model selection

Research & academic projects

Enterprise AI evaluation

NLP performance comparison
