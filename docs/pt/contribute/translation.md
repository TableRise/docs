# Guia de contribuição para tradução

## Adicionar novo idioma

No arquivo `mkdocs.yml`, procure por `i18n` na seção de plugins. Em seguida, adicione o idioma que deseja traduzir no formato abaixo:

```yaml
- locale: pt # código do idioma, deve ser o mesmo da pasta
  name: Português # nome do idioma que será exibido na barra de tradução
  build: true # habilitar tradução, deve estar como `true`
  nav: # traduzir a barra de navegação
    - xx: xx.md # traduzir o item da barra de navegação
    # adicione outros itens da barra de navegação
```

Na pasta `docs`, crie uma pasta para o novo idioma com o código que está no `mkdocs.yml`.

!!! tip "Dica"
    Para garantir que todos os arquivos serão traduzidos, copie a pasta do idioma original e renomeie-a para o novo idioma.
    **Exemplo**: `docs/pt` para `docs/es`.

!!! danger "Importante"
    Não altere o nome dos arquivos.

Execute `mkdocs serve` para executar o projeto localmente e verificar se o idioma foi traduzido corretamente.

Se tudo estiver correto, crie um novo Pull Request conforme o [guia de contribuição](docs.md/#pull-request) para a nova tradução.
