# AdvogaFácil - Automação Jurídica (Pará)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

O **AdvogaFácil** é uma plataforma de alto desempenho projetada para centralizar o fluxo de trabalho jurídico. O foco principal é a integração inteligente com os sistemas PJe e Projudi dos tribunais do Pará, eliminando a fragmentação de dados e a perda de prazos.

---

## Escopo do Projeto
O sistema atua como um hub central para:
* **TJPA** (Tribunal de Justiça do Pará - Projudi)
* **TRT8** (Tribunal Regional do Trabalho da 8ª Região)
* **JFPA** (Justiça Federal - Seção Judiciária do Pará)
* **TRE-PA** (Tribunal Regional Eleitoral do Pará)

---

## Estrutura do Repositório

```text
AdvogaFacil/
├── .env                  # Variáveis de ambiente e credenciais (local apenas)
├── .gitignore            # Configuração de exclusão do Git (venv, .env, pycache)
├── README.md             # Visão geral e guia rápido do projeto
├── CHANGELOG.md          # Registro histórico de alterações e versões
├── CONTRIBUTING.md       # Diretrizes para novos colaboradores
├── LICENSE.md            # Termos de uso e licença (MIT)
├── requirements.txt      # Dependências do Python (FastAPI, Playwright, etc.)
│
├── docs/                 # Documentação técnica detalhada
│   ├── REQUISITOS.md     # Levantamento de RF e RNF
│   ├── INSTALL.md        # Guia de instalação passo a passo
│   ├── DIAGRAMAS.md      # Visão geral das modelagens
│   ├── ARQUITETURA.md    # Estrutura sistêmica e componentes
│   ├── DIAGRAMA_CLASSES.md # Modelagem de objetos e herança
│   ├── DIAGRAMA_SEQUENCIA.md # Fluxo de sincronização com tribunais
│   ├── DIAGRAMA_ESTADOS.md # Ciclo de vida das petições
│   ├── DIAGRAMA_COMPONENTES.md # Organização dos módulos internos
│   └── DB_SCHEMA.md      # Modelagem Entidade-Relacionamento (PostgreSQL)
│
└── src/                  # Código-fonte da aplicação
    ├── main.py           # Ponto de entrada da API FastAPI
    ├── scrapers/         # Motores de busca (TJPA, TRT8, etc.)
    └── database/         # Configurações de modelos e migrações

    ---

## Funcionalidades Principais
- [x] **Dashboard Unificado:** Visualize todos os processos em uma única tela.
- [x] **Sincronização Automática:** Robôs de alta performance que monitoram movimentações 24/7.
- [x] **Gestão de Prazos:** Cálculo automatizado com base no calendário judiciário paraense.
- [x] **Peticionamento em Lote:** Envio de documentos via integração com assinadores (PJeOffice/Shodo).

---

## Stack Tecnológica
* **Linguagem:** Python 3.10+
* **Framework Web:** FastAPI
* **Automação:** Playwright (Engines de Scraping)
* **Banco de Dados:** PostgreSQL com suporte a JSONB
* **Tarefas Assíncronas:** Celery + Redis

---

## Desenvolvedor

**Márcio Rodrigues de Oliveira** cda.marcio@gmail.com

---

## Licença MIT

Copyright (c) 2026 Márcio Rodrigues de Oliveira

A permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados, para lidar no Software sem restrições, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO.

