# Projeto Integrado 4 - EP1: Integração Contínua com GitHub Actions

## ✅ Objetivo do EP1

O objetivo deste Entregável Parcial é configurar um processo de **integração contínua** usando o **GitHub Actions**, para automatizar a verificação do código desenvolvido. Com isso, conseguimos manter o projeto mais confiável, organizado e com menos erros.

---

## ⚙️ O que foi configurado

- Um arquivo `.yml` foi criado no caminho `.github/workflows/ci.yml`.
- Esse arquivo contém um **workflow de verificação automática** utilizando a ferramenta **HTMLHint**.
- Toda vez que o código é enviado (push ou pull request) para a branch `main`, o GitHub Actions roda automaticamente.
- A ferramenta verifica os arquivos `.html` para encontrar erros, avisos e más práticas.

---

## 📁 Estrutura do Projeto

```bash
Projeto-integrado-4/
├── .github/
│   └── workflows/
│       └── ci.yml
├── index.html
├── README.md
└── ...
```

---

## 📚 Componente Extensionista – O que é Integração Contínua?

**Integração Contínua (CI)** é uma prática de desenvolvimento onde o código é automaticamente verificado a cada nova alteração enviada ao repositório. Isso ajuda a manter a qualidade do projeto, identificar erros rapidamente e evitar acúmulo de problemas no código.

Para quem está aprendendo a programar, como nós, essa prática é muito importante porque:

- Ensina disciplina e organização no desenvolvimento de software;
- Permite detectar erros imediatamente, facilitando a correção;
- Dá uma noção real de como funciona um ambiente de trabalho profissional;
- Prepara estudantes para o uso de ferramentas modernas do mercado.

Ao aplicar CI com GitHub Actions, mesmo projetos simples se beneficiam com automação e controle de qualidade desde o início. Isso torna o aprendizado mais prático e alinhado com as exigências do mundo real da tecnologia.

---

## 💻 Como usar localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/ErickLima7/Projeto-integrado-4.git
cd Projeto-integrado-4
```

### 2. Rodar o HTMLHint localmente

Se você tiver o Node.js instalado, execute:

```bash
npm install -g htmlhint
htmlhint index.html
```

Isso irá verificar o código HTML e mostrar erros, se existirem.

---

## 🔄 Verificação automática no GitHub

Sempre que você fizer um push ou pull request para a branch `main`, o GitHub Actions irá:

- Baixar o código do repositório (`checkout`);
- Rodar a ferramenta `htmlhint` para verificar os arquivos HTML;
- Exibir o resultado na aba [Actions](https://github.com/ErickLima7/Projeto-integrado-4/actions) do GitHub.

Se houver erros, eles serão listados lá para que a equipe possa corrigir rapidamente.

---

## 🔗 Links úteis

- 🔗 [Repositório no GitHub](https://github.com/ErickLima7/Projeto-integrado-4)
- 🧪 [Aba de Actions (CI rodando)](https://github.com/ErickLima7/Projeto-integrado-4/actions)
- 📝 [Relatório do grupo (Google Drive)](COLE_AQUI_O_LINK_DO_RELATORIO)

---

## 👥 Equipe

- Erick Vinicius de Oliveira Lima  
- Larissa Barbosa da Silva
