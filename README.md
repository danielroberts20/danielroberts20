### Hi there 👋

CS graduate from the University of Southampton (First Class). My dissertation applied the AutoPlait algorithm to time series segmentation for human activity recognition — also a First.

I'm currently building two interconnected AI/ML projects during a multi-year trip across ~9 countries:

**[TravelNet](https://travelnet.dev)** — A personal telemetry platform collecting live GPS, health, and financial data via Raspberry Pi. Includes an ML pipeline: DBSCAN location clustering, Hidden Markov Model trip segmentation, anomaly detection, and time series forecasting. Full stack: Python, FastAPI, SQLite, Docker — deployed on the Pi itself with an nginx reverse proxy.

**Trevor** — A RAG-based conversational AI interface over TravelNet's data and 3 years of personal journal entries. LLM provider abstraction (OpenAI / Anthropic / local Ollama on GPU), tool-calling loop for hybrid SQL + semantic retrieval, Chroma vector store, and a citation pipeline. The stack runs across a Raspberry Pi and a remote GPU node over Tailscale.

The full arc: collect real data → analyse it with ML → make it queryable with LLMs → ship it.
