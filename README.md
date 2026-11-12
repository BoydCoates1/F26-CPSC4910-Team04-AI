TruckerReward AI

AI-powered customer support assistant for the TruckerReward platform.

Architecture

TruckerReward AI uses Dify for conversational AI and knowledge retrieval, with Ollama providing local language model inference during development.

Components
Dify: AI application orchestration and knowledge management.
Ollama: Local AI model hosting.
TruckerReward Backend: Secure API integration with Dify.
Knowledge Base: Product documentation, customer support resources, and platform policies.
Repository Structure
deployment/ - Docker and AWS deployment configuration.
configuration/ - Model and prompt configuration.
knowledge-base/ - Source documentation for the AI knowledge base.
documentation/ - Architecture and setup documentation.
Development

Development is performed locally using Docker Compose and Ollama.

Security

Never commit API keys, passwords, credentials, private customer information, or environment files containing secrets.
