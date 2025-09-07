# AI Gateway Stack (working repo)
- Este repositório centraliza configs do stack (Ollama, LiteLLM Proxy, Qdrant, Open-WebUI).
- `configs/snapshots/` guarda TARs de configurações encontradas no host (sem volumes).
- `docs` e `report` são links simbólicos para pastas já existentes em /data/stack/.
Fluxo: snapshot inicial -> padronização de compose/configs -> commit -> fallback seguro.
