#  Model Context Protocol (MCP) Tutorial Project

This project demonstrates how to use the **Model Context Protocol (MCP)** to structure prompts for Large Language Models (LLMs) using **LangChain**, **FAISS**, and a mock LLM. It walks through how MCP improves prompt quality and includes a visualization of prompt structure.

---

## What is MCP?

**Model Context Protocol** is a systematic approach for crafting LLM prompts. It segments input into:
- ✅ **Task Description**
- ✅ **Constraints**
- ✅ **Tools**
- ✅ **Examples**

This helps LLMs interpret user intent more reliably and produce higher quality output.

---

## Technologies Used

- [LangChain](https://github.com/langchain-ai/langchain)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Transformers](https://huggingface.co/docs/transformers)
- [Matplotlib + Seaborn](https://seaborn.pydata.org/)
- Python 3.11+

---

## Project Structure

- **Context Setup**: Define MCP content in memory
- **Vector Store**: Embed content using HuggingFace MiniLM and store in FAISS
- **Fake LLM**: Use LangChain's mock LLM for quick testing
- **RetrievalQA**: Ask questions using context-aware retrieval
- **Visualization**: Bar chart showing simulated MCP prompt structure

---

## How to Run

1. Clone the repo or copy the notebook to Colab
2. Install dependencies:

   ```bash
   pip install -q langchain langchain-community faiss-cpu matplotlib seaborn


Sample Output
Response: MCP structures prompts with task, constraints, tools, and examples.

Notes
This uses a FakeListLLM for simplicity. Replace with OpenAI, HuggingFaceHub, or any production-grade LLM for real use.

FAISS is used here for local, fast retrieval. You can swap with Chroma or a cloud vector DB.
License
MIT © 2025 

## How to Run
