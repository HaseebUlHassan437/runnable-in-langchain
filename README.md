# Runnable in LangChain

This repository explores different types of **Runnables** in LangChain, a framework for building AI applications. It demonstrates how to structure chains using `RunnableSequence`, `RunnableParallel`, `RunnableBranch`, `RunnableLambda`, and `RunnablePassthrough` to create dynamic workflows with LLMs.

---

## 📁 Repository Structure

| File | Description |
|-------|-------------|
| **runnable_branch.py** | Demonstrates conditional execution using `RunnableBranch`, generating a report and summarizing it based on length. |
| **runnable_lambda.py** | Implements `RunnableLambda` to compute word count in parallel with joke generation. |
| **runnable_sequence.py** | Chains multiple steps sequentially using `RunnableSequence` to generate and explain jokes. |
| **runnable_parallel.py** | Uses `RunnableParallel` to create separate social media posts (Tweet & LinkedIn) concurrently. |
| **runnable_passthrough.py** | Showcases `RunnablePassthrough`, ensuring some inputs remain unchanged while processing others. |

---

## 🚀 Quick Start

1. Clone this repo  
   ```bash
   git clone https://github.com/HaseebUlHassan437/runnable-in-langchain.git
   cd runnable-in-langchain
   ```

2. Create & activate a virtual environment  
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Add your API key to a `.env` file  
   ```
   GOOGLE_API_KEY=your_gemini_api_key_here
   ```

5. Run any example script  
   ```bash
   python runnable_branch.py
   python runnable_lambda.py
   python runnable_sequence.py
   ```

---

## 🔧 Tech Stack

- **LangChain** — AI workflow orchestration  
- **Google Gemini (PaLM)** via `langchain-google-genai`  
- **Python dotenv** — Environment management  
- **Pydantic** — Data validation (if needed)  

---

## 📄 License

MIT © 2025

## 📫 Contact

Questions or feedback? Email **haseebulhassan1172003@gmail.com**.

