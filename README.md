# 🌊 Observatório Oceanográfico da UFF — Site Oficial

Este repositório abriga o **site institucional do Observatório Oceanográfico da Universidade Federal Fluminense (UFF)**, desenvolvido com [Jekyll](https://jekyllrb.com/), [GitHub Pages](https://pages.github.com/) e o tema [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), com elementos inspirados no [Academic Pages](https://github.com/academicpages/academicpages).

## Objetivos deste repositório

- Facilitar a modificação e inclusão de dados pelos alunos sem necessidade de conhecimento profundo em web design
- Divulgar as **atividades científicas, acadêmicas e extensionistas** do Observatório.
- Organizar e apresentar de forma modular o acervo de:
  - Projetos de pesquisa, extensão e ensino.
  - Disciplinas e conteúdos educacionais.
  - Publicações científicas e produtos gerados pelo laboratório.
- Consolidar os **perfis da equipe**, com destaque para formação, interesses e produções.
- Implementar um portal bilíngue leve e responsivo.

## Estrutura do Projeto

A estrutura base segue a lógica do Jekyll, com uso intensivo de coleções customizadas e páginas modulares:

```
.
├── _data/                    # Dados de navegação, equipe e menus
├── _includes/                # Blocos HTML reutilizáveis (header, footer, etc.)
├── _layouts/                 # Layouts base usados pelas páginas e posts
├── _pages/                  # Páginas principais do site
│   ├── equipe.md            # Página geral da equipe
│   ├── ensino.md            # Página geral de ensino
│   ├── extensao.md          # Página geral de extensão
│   ├── projetos.md          # Página geral de projetos
│   ├── sobre.md             # Página institucional
│   └── noticias.md          # Página agregadora de notícias
├── _posts/                  # Arquivos de notícias (seguem padrão de blog Jekyll)
├── _projects/               # Projetos de pesquisa, ensino e extensão
├── _publications/           # Publicações científicas e produtos
├── _teaching/               # Disciplinas e conteúdos educacionais
├── assets/
│   ├── css/                 # Estilos customizados
│   ├── img/                 # Logos, banners e imagens
│   └── js/                  # Scripts JS customizados
├── _config.yml              # Configuração principal do Jekyll
├── Gemfile                  # Dependências Ruby (Jekyll, plugins, etc.)
├── README.md                # Descrição do projeto
└── index.md                 # Página inicial do site
```

## Funcionalidades Implementadas

- ✅ Tema **Minimal Mistakes** ativo via `remote_theme`
- ✅ Estrutura modular com **coleções Jekyll** personalizadas
- ✅ Layout para perfis individuais da equipe (com `author_profile: true`)
- ✅ Navegação lateral personalizada (`sidebar.nav`)
- ✅ Suporte bilíngue planejado (`/` para PT, `/en/` para EN)
- ✅ Pronto para integração com domínio institucional (ex.: `observatorio.oceanografico.uff.br`)


## Exemplos e Modelos

Exemplos disponíveis no repositório:

- 🧑‍🔬 Perfil individual da equipe (`_pages/equipe/andre-belem.md`)
- 📚 Publicação científica (`_publications/`)
- 📘 Disciplina de ensino (`_teaching/`)
- 🧪 Projeto de pesquisa/extensão (`_projects/`)


## Como Rodar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/observatorio-oceanografico/observatorio-oceanografico.github.io.git
cd observatorio-oceanografico.github.io
```

2. Execução com Docker: **Construa a imagem Docker:**

```bash
./build.sh
```

> Esse script compila o site Jekyll em ambiente isolado e gera uma imagem leve com NGINX.

**O servidor será iniciado automaticamente.**  
   Você poderá acessar o site em:

```bash
http://localhost:8080
```

## Versão Online

A versão mais recente estará sempre disponível em:  
👉 **[observatorio-oceanografico.github.io](https://observatorio-oceanografico.github.io)**


## Créditos

Desenvolvido por **Prof. André L. Belem** e equipe do Observatório Oceanográfico (UFF).  
Inspirado em [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) e [Academic Pages](https://github.com/academicpages/academicpages) e com a ajuda de [**F.R.I.D.A.Y**](https://observatoriooceanografico.org/equipe/friday-bot/).


##  Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---
