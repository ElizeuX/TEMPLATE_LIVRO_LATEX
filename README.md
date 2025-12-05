 ![ALPHA ok](https://img.shields.io/badge/Alpha-ok-FF1493?logo=checkmarx) ![BETA Pending](https://img.shields.io/badge/Beta-Pending-999999?logo=checkmarx&logoColor=white) ![Version final](https://img.shields.io/badge/Versão-final-999999?logo=rocket&logoColor=white)

# 📚 Template de Livro em LaTeX

Este repositório contém um **template completo de livro em LaTeX**, pensado para autores que querem organizar o manuscrito de forma profissional, com foco em:

- Livros de ficção ou não ficção
- Versões para impressão, PDF digital e DOCX
- Textos em português (Brasil)

> Use este template como base para seus projetos de livro, ajustando apenas o conteúdo e alguns detalhes de configuração.

---

## ✨ Recursos do template

- Estrutura organizada em capítulos
- Metadados do livro configuráveis (`autor`, `título`, `editora`, `ano`, `ISBN`)
- Sumário gerado automaticamente
- Numeração de páginas no estilo livro
- Suporte a imagens (`graphicx`)
- Arquivos de configuração separados (preambulo/opções)
- Estilo consistente para:
  - Títulos de capítulos e seções
  - Cabeçalhos e rodapés (via `fancyhdr`, se habilitado)
  - Quebra de páginas em modo livro (`book` class)
- Pronto para ser integrado com pipelines de CI (por exemplo, GitHub Actions) para gerar PDF automaticamente a cada commit

---

## 📁 Estrutura do projeto

Um exemplo de estrutura (ajuste de acordo com seu repositório):

```text
.
├── main.tex               # Arquivo principal do livro
├── misc/
│   ├── preamble.sty       # Preambulo: pacotes e configurações globais
│   ├── options.sty        # Opções específicas do livro (margens, fonte etc.)
│   └── ...
├── chapters/
│   ├── cap01.tex          # Capítulo 1
│   ├── cap02.tex          # Capítulo 2
│   └── ...
├── assets/
│   └── img/               # Imagens usadas no livro
└── README.md
