# Deep Code Indexer

A high-performance MCP server that provides AI agents with deep semantic understanding of codebases. It combines traditional static analysis with modern embeddings to enable precise, context-aware code navigation and reasoning across multiple repositories.

## Key Features
- Hybrid search using FTS5 for text and embeddings for semantic similarity
- Call graph generation, git blame analysis, and build system integration
- Multi-repo workspace support with GPU-accelerated semantic search
- 25+ tools for comprehensive code intelligence and hotspot identification

## Tech Stack
- Python, SQLite/FTS5, Sentence Transformers
- Tree-sitter, LibCST, NetworkX
- FastMCP, PyTorch, CUDA (optional)

## Getting Started
```bash
git clone https://github.com/zoreanuj/deep-code-indexer.git
cd deep-code-indexer
pip install -r requirements.txt
python server.py
```