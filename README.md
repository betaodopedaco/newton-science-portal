# Newton Science: API e Portal de Física

Um portal educativo e API minimalista dedicada à ciência e às descobertas de Isaac Newton. Desenvolvido com **Node.js** (sem dependências externas para o core), o projeto oferece factos históricos aleatórios e uma calculadora de força gravitacional baseada na Lei da Gravitação Universal.

---

## 🚀 Funcionalidades

- **API de Factos Históricos**: Endpoint `GET /api/facts` que retorna curiosidades sobre a vida e obra de Newton.
- **Calculadora Gravitacional**: Endpoint `POST /api/gravity` para cálculo da força de atração entre dois corpos.
- **Servidor de Arquivos Estáticos**: Implementação nativa de um servidor web para servir HTML, CSS e JS.
- **Segurança Básica**: Proteção contra ataques de *path traversal* no servidor de ficheiros.
- **Interface Educativa**: Frontend simples para interagir com as funcionalidades da API.

## 🛠️ Tecnologias Utilizadas

- **Backend**: Node.js (Módulos nativos: `http`, `fs`, `path`)
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Lógica Científica**: Implementação da Constante Gravitacional Universal ($G = 6.67430 \times 10^{-11}$).

## Status
![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

Projeto focado em demonstrar o poder dos módulos nativos do Node.js para criar servidores web e APIs funcionais sem dependências pesadas.

## 📦 Como Executar

### Pré-requisitos
- Node.js instalado (v12+)

### Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/betaodopedaco/newton-science-portal.git
   cd newton-science-portal
   ```

2. Inicie o servidor:
   ```bash
   node server.js
   ```
   O portal estará disponível em `http://localhost:8080`.

## 📂 Estrutura do Projeto

```text
carlosportifolio/
├── server.js       # Servidor HTTP e lógica da API (Node.js nativo)
├── public/         # Ficheiros do frontend
│   ├── index.html  # Interface principal
│   ├── script.js   # Lógica de interação com a API
│   └── style.css   # Estilização
└── package.json    # Metadados do projeto
```

---
Desenvolvido por [Carlos Henrique](https://github.com/betaodopedaco)
