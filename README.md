# Bob 🍍🍕 expert

This is a demo with Ollama and LangChainJS

```bash
curl http://ollama-service:11434/api/generate -d '{
  "model": "qwen2.5:3b",
  "prompt": "Why is the sky blue?"
}'
```

```bash
curl http://ollama-service:11434/api/generate -d '{
  "model": "qwen2.5:3b",
  "prompt": "Why is the sky blue?",
  "stream": false
}'
```
