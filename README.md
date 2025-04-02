# Langchain Langgraph Langsmith Intro Arithmetic Agent

A TypeScript-based arithmetic agent using LangChain.js and LangGraph for performing sequential arithmetic operations with OpenAI function calling.

## Features

- Performs arithmetic operations using natural language input
- Supports addition, multiplication, and division
- Uses OpenAI's GPT-4 model for natural language understanding
- Built with LangChain.js and LangGraph for workflow management

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/langchain-arithmetic-agent.git
   cd langchain-arithmetic-agent
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Then edit `.env` and add your OpenAI API key.

## Usage

Run the agent:
```bash
npm start
```

The agent will process the arithmetic expression "Add 3 and 4 then multiply that by 10 and divide it by 2" and show the step-by-step calculation.

## Development

Build the project:
```bash
npm run build
```

## License

MIT 