# infra-signet-docker

Ambiente Docker para rodar um **nó Bitcoin na rede Signet** (e opcionalmente um miner) de forma simples, usando Docker e Docker Compose.  
O repositório contém `Dockerfile`, `Dockerfile.miner`, `docker-compose.yml`, `bitcoin.conf`, `entrypoint.sh` e arquivos Nix (`flake.nix`, `flake.lock`) para reprodutibilidade. :contentReference[oaicite:0]{index=0}

---

## ✅ Pré-requisitos

- **Docker** e **Docker Compose v2** instalados.
- WSl Linux
- (Opcional) **Nix** caso queira usar os *flakes* (`flake.nix` está na raiz). :contentReference[oaicite:1]{index=1}

---

## 🚀 Como começar

### 1) Clonar o repositório
```bash
git clone https://github.com/vinteum-bdl/infra-signet-docker.git
cd infra-signet-docker
