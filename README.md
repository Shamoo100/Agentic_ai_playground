# AI Research Assistant

An intelligent research assistant powered by LangChain that combines multiple AI capabilities to provide comprehensive research and information gathering.

## Features

- **Web Search Integration**: Uses DuckDuckGo for real-time internet searches
- **Wikipedia Integration**: Direct access to Wikipedia's knowledge base
- **Interactive Interface**: Simple command-line interface for research queries
- **Error Handling**: Robust error handling for reliable operation

## Technical Stack

- **LangChain Framework**: For agent orchestration and tool integration
- **OpenAI GPT-3.5**: Powers the core language understanding and response generation
- **DuckDuckGo Search**: For real-time web searches
- **Wikipedia API**: For accessing Wikipedia content
- **Python**: Core implementation language

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Shamoo100/Agentic_ai_playground.git
cd Agentic_ai_playground
```

2. Create and activate virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a .env file with your API keys:
```
OPENAI_API_KEY=your_openai_api_key
```

## Usage

Run the assistant:
```bash
python main.py
```

Type your research query when prompted. The assistant will:
- Search the internet using DuckDuckGo
- Query Wikipedia when relevant
- Provide a comprehensive response

Enter 'quit' to exit the program.

## Example Queries

- "What are the latest developments in quantum computing?"
- "Explain the impact of artificial intelligence on healthcare"
- "What are the main causes of climate change?"

## Contributing

Feel free to open issues or submit pull requests to improve the project.

## License

MIT License