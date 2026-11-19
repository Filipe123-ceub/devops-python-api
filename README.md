# DevOps Python API — Pipeline CI/CD com GitHub Actions, Docker, Amazon ECR e EC2

API REST desenvolvida em Python com **FastAPI** para gerenciamento de tarefas (`/tasks`) e monitoramento de saúde (`/health`), estruturada para demonstrar uma esteira completa de Integração Contínua (CI) e Entrega Contínua (CD) na AWS.

## Tecnologias Utilizadas

* **Linguagem e Framework:** Python 3.13, FastAPI, Uvicorn, Pydantic
* **Qualidade e Testes:** Pytest, Pytest-Cov, HTTPX, Ruff
* **Containerização:** Docker
* **CI/CD:** GitHub Actions
* **Nuvem (AWS):** Amazon Elastic Container Registry (ECR), Amazon EC2 (Ubuntu Linux) e AWS IAM

---

## Execução Local

1. Clone o repositório e aceda à pasta do projeto:
   ```bash
   git clone [https://github.com/Filipe123-ceub/devops-python-api.git](https://github.com/Filipe123-ceub/devops-python-api.git)
   cd devops-python-api