# ASSIGNMENT

# 🧠 Multi-Agent Pipeline - Assignment 4

This project demonstrates a modular multi-agent system built as part of Assignment 4.

## 🔧 Components

- **Supervisor Node**: Central control unit to decide next steps.
- **Router Function**: Directs the flow to appropriate functional nodes.
- **LLM Node**: Calls a large language model for answers.
- **RAG Node**: Implements Retrieval-Augmented Generation.
- **Web Crawler Node**: Fetches real-time info from the internet.
- **Validation Node**: Validates the generated output.
  - If failed → back to Supervisor for re-routing.
  - If passed → final output is generated.

## 🔁 Flow

1. User Query → Supervisor Node  
2. Supervisor → Router  
3. Router → Functional Node (LLM / RAG / WebCrawler)  
4. → Validation Node  
5. If valid → ✅ Output  
6. Else → 🔁 back to Supervisor

## 🧪 Tech Stack

- Python
- LangChain / Custom Node Design
- Optional: OpenAI/Groq for LLM calls
- BeautifulSoup/Selenium for Web Crawling

## 📂 Submission Info

- Submitted on: **[Date]**
- Deadline: 9 PM Friday

