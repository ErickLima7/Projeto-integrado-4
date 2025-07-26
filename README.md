\# Projeto Integrado 4 - EP1: Integração Contínua com GitHub Actions



\## ✅ Objetivo do EP1



O objetivo deste Entregável Parcial é configurar um processo de \*\*integração contínua\*\* usando o \*\*GitHub Actions\*\*, para automatizar a verificação do código desenvolvido. Com isso, conseguimos manter o projeto mais confiável, organizado e com menos erros.



---



\## ⚙️ O que foi configurado



\- Um arquivo `.yml` foi criado no caminho `.github/workflows/ci.yml`.

\- Esse arquivo contém um \*\*workflow de verificação automática\*\* (usando HTMLHint).

\- Toda vez que o código é enviado para o repositório, ele roda automaticamente.

\- A ferramenta usada verifica os arquivos `.html` para encontrar erros ou avisos.



---



\## 📁 Estrutura do projeto



```bash

Projeto-integrado-4/

├── .github/

│   └── workflows/

│       └── ci.yml

├── index.html

├── README.md

└── ...



