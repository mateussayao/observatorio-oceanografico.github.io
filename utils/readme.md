# Scripts auxiliares — Observatório Oceanográfico

Esta pasta contém scripts utilitários para gerar conteúdos do site do Observatório Oceanográfico.

## Script: `gerar_alumni.py`

Este script:

1. Baixa automaticamente a planilha de ex-integrantes (alumni) do Google Drive.
2. Gera um arquivo `alumni-o2.html` com a lista formatada em HTML.
3. Move o arquivo gerado para a pasta `_includes/`, onde pode ser incluído no site Jekyll.

### Como executar

Requisitos:
- Python 3
- Bibliotecas: `pandas`, `gdown`

Instale as dependências (se necessário):

```bash
pip install pandas gdown
