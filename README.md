# 🌊 Observatório Oceanográfico da UFF — Site Oficial

Este repositório abriga o **site institucional do Observatório Oceanográfico da Universidade Federal Fluminense (UFF)**, desenvolvido com [Jekyll](https://jekyllrb.com/), [GitHub Pages](https://pages.github.com/) e o tema [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), com elementos inspirados no [Academic Pages](https://github.com/academicpages/academicpages).

---

## 📌 Objetivos

- Divulgar as **atividades científicas, acadêmicas e extensionistas** do Observatório.
- Organizar e apresentar de forma modular o acervo de:
  - Projetos de pesquisa, extensão e ensino.
  - Disciplinas e conteúdos educacionais.
  - Publicações científicas e produtos gerados pelo laboratório.
- Consolidar os **perfis da equipe**, com destaque para formação, interesses e produções.
- Implementar um portal bilíngue leve e responsivo.

---

## 📁 Estrutura do Projeto

A estrutura base segue a lógica do Jekyll, com uso intensivo de coleções customizadas e páginas modulares:

```
.
├── _data/                    # Dados de navegação e configuração
├── _pages/                  # Páginas principais do site (sobre, equipe, etc.)
│   └── equipe/              # Perfis individuais da equipe
├── _projects/               # Projetos de pesquisa, ensino e extensão
├── _publications/          # Publicações científicas e produtos
├── _teaching/              # Disciplinas e conteúdos educacionais
├── assets/img/             # Logos, banners e imagens
├── _config.yml             # Arquivo de configuração principal
├── Gemfile                 # Dependências Ruby/Jekyll
├── index.md                # Página inicial (com banner e logo)
└── README.md               # Este arquivo
```

---

## 💡 Funcionalidades Implementadas

- ✅ Tema **Minimal Mistakes** ativo via `remote_theme`
- ✅ Estrutura modular com **coleções Jekyll** personalizadas
- ✅ Layout para perfis individuais da equipe (com `author_profile: true`)
- ✅ Navegação lateral personalizada (`sidebar.nav`)
- ✅ Suporte bilíngue planejado (`/` para PT, `/en/` para EN)
- ✅ Pronto para integração com domínio institucional (ex.: `observatorio.oceanografico.uff.br`)

---

## 🧩 Exemplos e Modelos

Exemplos disponíveis no repositório:

- 🧑‍🔬 Perfil individual da equipe (`_pages/equipe/andre-belem.md`)
- 📚 Publicação científica (`_publications/`)
- 📘 Disciplina de ensino (`_teaching/`)
- 🧪 Projeto de pesquisa/extensão (`_projects/`)

---

## 🚀 Como Rodar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/observatorio-oceanografico/observatorio-oceanografico.github.io.git
cd observatorio-oceanografico.github.io
```

2. Instale as dependências (com Ruby já instalado):

```bash
bundle install
```

3. Execute o servidor local:

```bash
bundle exec jekyll serve
```

4. Acesse no navegador: [http://localhost:4000](http://localhost:4000)

---

## 🌐 Versão Online

A versão mais recente estará sempre disponível em:  
👉 **[observatorio-oceanografico.github.io](https://observatorio-oceanografico.github.io)**

---

## ✍️ Créditos

Desenvolvido por **Prof. André L. Belem** e equipe do Observatório Oceanográfico (UFF).  
Inspirado em [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) e [Academic Pages](https://github.com/academicpages/academicpages).

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---
