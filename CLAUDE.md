# Ollama

`docker-compose.yml` wrapper around the official `ollama/ollama` image, GPU-passthrough enabled
(NVIDIA), serving the Ollama API on port 11434.

`./data` (bind-mounted to `/root/.ollama`, holds downloaded model weights) is gitignored — can be
tens of GB and is regenerable by re-pulling models.

Run it: `docker compose up -d` from this directory.
