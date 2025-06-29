# 🤖 HRGPT – AI-Powered HR Assistant

HRGPT is a smart backend system that uses Google’s Gemini LLM to convert natural language HR queries into secure SQL `SELECT` statements. It allows employees to ask questions like _"How many leaves do I have left?"_ or _"Show my last month’s attendance"_ and retrieves accurate data from a PostgreSQL database.

---

## 🚀 Features

- 🧠 **AI-driven Natural Language to SQL**  
  Converts employee HR questions into SQL using the Gemini 1.5 Flash API.

- 🔐 **Safe Querying**  
  Automatically filters and allows only `SELECT` queries for data protection.

- ⚙️ **Modular Prompt System**  
  Uses dynamic prompt templates to guide Gemini's SQL generation accurately.

- 🗄️ **PostgreSQL Integration**  
  Executes LLM-generated SQL directly on a connected HR database.

- 🛡️ **Error Handling**  
  Includes robust error catching, logging, and SQL validation.

---

## 🧱 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **AI**: Google Gemini API (v1.5 Flash)
- **Other**: Axios, dotenv

---


