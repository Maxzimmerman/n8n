# In the n8n folder
docker compose up -d

# Pull mistral into the ollama container (good balance of speed vs quality)
# This downloads ~4GB, only needed once — stored in ./ollama-data
docker compose exec ollama ollama pull mistral