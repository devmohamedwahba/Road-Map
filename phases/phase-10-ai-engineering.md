# 📌 Phase 10 — AI Engineering (2–3 Months) ⭐⭐⭐⭐⭐

## 🤖 LLM Fundamentals

### Core Concepts
- [ ] What are LLMs (transformer architecture overview)
- [ ] Tokens and tokenization
- [ ] Context window (input limits)
- [ ] Temperature (creativity vs determinism)
- [ ] Top-p (nucleus sampling)
- [ ] Max tokens (output length)
- [ ] Stop sequences
- [ ] System prompts vs user prompts
- [ ] Chat vs completion models

### Prompt Engineering
- [ ] Zero-shot prompting
- [ ] Few-shot prompting (examples in prompt)
- [ ] Chain-of-thought (CoT) reasoning
- [ ] Role prompting
- [ ] Output format specification (JSON mode)
- [ ] Prompt templates
- [ ] Prompt injection awareness and defense
- [ ] Prompt versioning and testing

### Model Selection
- [ ] OpenAI models (GPT-4o, GPT-4-turbo, o1)
- [ ] Anthropic models (Claude 3.5 Sonnet, Claude 4)
- [ ] Google Gemini (Pro, Ultra)
- [ ] Open-source models (Llama, Mistral, Qwen)
- [ ] Cost vs quality vs speed tradeoffs
- [ ] When to use which model

---

## 🔌 LLM APIs & Integration

### OpenAI API
- [ ] Chat completions
- [ ] Function calling / tool use
- [ ] Structured outputs (JSON schema)
- [ ] Streaming responses
- [ ] Embeddings API
- [ ] Moderation API
- [ ] Vision (image inputs)
- [ ] Batch API
- [ ] Error handling and retries

### Anthropic API
- [ ] Messages API
- [ ] Tool use
- [ ] Streaming
- [ ] System prompts
- [ ] Extended thinking

### Common Patterns
- [ ] API key management
- [ ] Rate limiting and backoff
- [ ] Token counting and cost tracking
- [ ] Caching LLM responses
- [ ] Fallback between providers
- [ ] Async API calls

---

## 📚 RAG (Retrieval-Augmented Generation)

### Embeddings
- [ ] What are embeddings (vector representations)
- [ ] Embedding models (OpenAI ada-002, Cohere, open-source)
- [ ] Dimensionality and similarity (cosine, dot product, Euclidean)
- [ ] Sentence embeddings vs word embeddings

### Document Processing
- [ ] Document loaders (PDF, DOCX, HTML, Markdown)
- [ ] Text splitting / chunking strategies
- [ ] Chunk size vs overlap tradeoffs
- [ ] Semantic chunking
- [ ] Metadata extraction and enrichment
- [ ] Document hierarchy preservation

### Retrieval
- [ ] Semantic search (vector similarity)
- [ ] Keyword search (BM25)
- [ ] Hybrid search (combine vector + keyword)
- [ ] Re-ranking (cross-encoders, Cohere Rerank)
- [ ] Filtering by metadata
- [ ] Maximum Marginal Relevance (MMR)
- [ ] Multi-query retrieval
- [ ] Parent document retriever

### RAG Pipeline
- [ ] Ingestion pipeline (load → chunk → embed → store)
- [ ] Query pipeline (embed query → retrieve → rerank → generate)
- [ ] Context window management
- [ ] Source attribution and citations
- [ ] Hallucination detection
- [ ] Evaluation metrics (faithfulness, relevance, recall)

### Advanced RAG
- [ ] Multi-modal RAG (images, tables)
- [ ] Graph RAG (knowledge graphs)
- [ ] Agentic RAG (agent decides what to retrieve)
- [ ] Self-RAG (self-reflection)
- [ ] Corrective RAG
- [ ] Adaptive retrieval

---

## 🗄️ Vector Databases

### pgvector (PostgreSQL extension)
- [ ] Installation and setup
- [ ] Vector columns and indexing (IVFFlat, HNSW)
- [ ] Similarity search queries
- [ ] Combining with relational queries
- [ ] Performance tuning

### Qdrant
- [ ] Collections and points
- [ ] Payload filtering
- [ ] Search with filters
- [ ] Batch operations
- [ ] Snapshots and backups

### Pinecone
- [ ] Indexes and namespaces
- [ ] Upsert and query
- [ ] Metadata filtering
- [ ] Serverless vs pod-based

### Comparison
- [ ] When to use pgvector (existing Postgres, simple use case)
- [ ] When to use dedicated vector DB (scale, advanced features)
- [ ] Indexing algorithms (HNSW, IVF, PQ)

---

## 🧠 AI Frameworks

### LangChain / LangGraph
- [ ] Chains (sequential, parallel)
- [ ] Agents (ReAct, tool-calling)
- [ ] LangGraph state machines
- [ ] Nodes and edges
- [ ] Conditional routing
- [ ] Persistence and checkpointing
- [ ] Human-in-the-loop
- [ ] Streaming

### LlamaIndex
- [ ] Document ingestion
- [ ] Index types (vector, keyword, tree, knowledge graph)
- [ ] Query engines
- [ ] Response synthesis
- [ ] Sub-question query engine
- [ ] Agents in LlamaIndex

### PydanticAI
- [ ] Agent definition
- [ ] Tool registration
- [ ] Structured outputs
- [ ] Dependency injection
- [ ] Multi-model support
- [ ] Testing agents

---

## 🔧 MCP (Model Context Protocol)

### Concepts
- [ ] What is MCP and why it exists
- [ ] MCP architecture (host, client, server)
- [ ] Transport layer (stdio, HTTP/SSE)
- [ ] Protocol messages (request, response, notification)

### MCP Server Development
- [ ] Building an MCP server (Python SDK)
- [ ] Defining tools (name, description, input schema)
- [ ] Implementing resources
- [ ] Implementing prompts
- [ ] Error handling
- [ ] Server configuration and deployment

### MCP Client
- [ ] Client implementation
- [ ] Server discovery
- [ ] Tool calling flow
- [ ] Context management

### Tool Calling
- [ ] Function/tool definition patterns
- [ ] Schema design for tools
- [ ] Error handling in tools
- [ ] Composing multiple tools
- [ ] Tool approval flows

---

## 🤖 AI Agents

### Agent Architecture
- [ ] Perception → Planning → Action loop
- [ ] ReAct pattern (Reasoning + Acting)
- [ ] Tool selection and execution
- [ ] Output parsing

### Memory
- [ ] Short-term memory (conversation buffer)
- [ ] Long-term memory (vector store)
- [ ] Episodic memory
- [ ] Working memory
- [ ] Memory summarization
- [ ] Memory retrieval strategies

### Planning
- [ ] Task decomposition
- [ ] Plan-and-execute pattern
- [ ] Tree of thought
- [ ] Reflection and self-correction
- [ ] Re-planning on failure

### Multi-Agent Systems
- [ ] Agent communication protocols
- [ ] Supervisor pattern
- [ ] Hierarchical agents
- [ ] Collaborative agents
- [ ] Debate/adversarial agents
- [ ] Agent handoffs

### Evaluation & Safety
- [ ] Agent evaluation frameworks
- [ ] Guardrails and safety layers
- [ ] Output validation
- [ ] Cost control
- [ ] Latency optimization
- [ ] Observability (LangSmith, Phoenix)

---

## 🚀 Phase 10 Projects

- [ ] **AI Customer Support Bot** — RAG, conversation memory, tool use, escalation
- [ ] **AI Travel Planner** — multi-agent, API integrations, user preferences
- [ ] **AI Coding Assistant** — MCP server, code analysis tools, context management
