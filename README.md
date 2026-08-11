# ☕ LangChain Quick Recap

A quick-reference LangChain repository - perfect for a coffee break review! This project covers essential LangChain patterns and techniques through hands-on Jupyter notebooks.

## 📚 Topics Covered

### 1. Basic Agent Architecture
**Notebook:** `1_basicAgentArcht.ipynb`
- Setting up basic LangChain agents
- Integrating with OpenAI models
- Google search integration using SerpAPI
- Agent workflow fundamentals

### 2. Streaming & Batch Processing
**Notebook:** `2_streamingBatchProcessing.ipynb`
- Stream processing patterns
- Batch operation handling
- Efficient data flow management

### 3. Tool Calling
**Notebook:** `3_toolCalling.ipynb`
- Implementing tool-calling patterns
- Returning control to LLM after tool execution
- Building interactive agent workflows

### 4. Structured Output
**Notebook:** `4_structureOutput.ipynb`
- Pydantic schema integration
- Optional fields and constraints
- Field/model validators
- Strict parsing and error handling

### 5. Middleware
**Notebook:** `5_middleware.ipynb`
- Middleware patterns in LangChain
- Message summarization
- State management with checkpointers

### 6. Moderation Approach
**Notebook:** `6_moderationApproch.ipynb`
- OpenAI Moderation API integration
- Content safety checks
- Category breakdown and filtering

### 7. Human in Loop
**Notebook:** `7_humanInLoop.ipynb`
- Interactive agent patterns
- User confirmation workflows
- Human oversight integration

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- OpenAI API key
- SerpAPI key (for search functionality)

### Installation

```bash
# Clone the repository
cd Lang-Chain

# Install dependencies using uv
uv sync

# Or using pip
pip install -r requirements.txt
```

### Configuration

Create a `.env` file with your API keys:

```env
OPENAI_API_KEY=your_openai_api_key
SERPAPI_API_KEY=your_serpapi_key
CHAT_MODEL=gpt-4
MODERATION_MODEL=omni-moderation-latest
```

## 📖 Usage

Open any notebook in Jupyter or VS Code and run the cells sequentially. Each notebook is self-contained and focuses on a specific LangChain concept.

## 🎯 Purpose

This repository serves as a quick reference guide for LangChain patterns and best practices. Perfect for:
- Quick concept reviews
- Learning LangChain fundamentals
- Building production-ready agent systems
- Understanding middleware and tool integration

---

*Happy learning! ☕*
