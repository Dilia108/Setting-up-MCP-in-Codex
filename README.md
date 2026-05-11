# Setting Up MCP in Codex

This notebook shows how to connect Codex to the LangChain documentation MCP server and query it with a LangChain agent.

## What it does

- Loads environment variables from `.env`
- Connects to the LangChain docs MCP server
- Loads MCP tools into LangChain
- Builds an agent and queries it with a sample question

## Setup

1. Create a `.env` file with your `OPENAI_API_KEY`.
2. Install the notebook dependencies from the first cell.
3. Run the notebook cells from top to bottom.

## Notes

- Keep `.env` out of git and never print its contents in the notebook.
- If the query hangs, check network access to OpenAI and to `https://docs.langchain.com/mcp`.
- A fresh kernel restart can help if cells were run out of order.

