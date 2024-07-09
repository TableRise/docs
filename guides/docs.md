# Guia de contribuição para documentações

## Sumário

1. [Introdução](#introdução)
2. [Ferramentas](#ferramentas)
3. [Padrões de escrita](#padrões-de-escrita)
4. [Sintaxes básicas do Markdown](#sintaxes-básicas-do-markdown)
5. [Envie sua contribuição](#envie-sua-contribuição)

## Introdução

A documentação é uma parte essencial de qualquer projeto, pois é através dela que os usuários e desenvolvedores conseguem entender como o projeto funciona, como utilizá-lo e como contribuir com ele. Por isso, é importante que a documentação seja clara, objetiva e completa.

## Ferramentas

Para escrever a documentação do projeto, utilizamos o Markdown, uma linguagem de marcação simples e fácil de aprender. Com o Markdown, é possível criar documentos com formatação básica, como títulos, listas, links, imagens, entre outros.

Para visualizar a documentação em tempo real, recomendamos o uso do [VS Code](https://code.visualstudio.com/), um editor de código gratuito e open source, que possui suporte nativo para Markdown.

### Instalação

Para instalar o VS Code, acesse o [site oficial](https://code.visualstudio.com/) e faça o download da versão compatível com o seu sistema operacional.

### Extensões recomendadas

- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) para verificar a formatação do Markdown.
- [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) para visualizar a documentação em tempo real.
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) para realçar os erros de formatação do Markdown.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) e [Brazilian Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian) para verificar a ortografia do texto. Esse mesmo criador possui outras extensões para outros idiomas.

## Padrões de escrita

Para manter a consistência e a qualidade da documentação, é importante seguir alguns padrões de escrita. Abaixo, listamos algumas diretrizes que devem ser seguidas ao contribuir com a documentação do projeto:

1. **Clareza**: A documentação deve ser clara e objetiva, evitando termos técnicos e jargões desnecessários. Procure explicar os conceitos de forma simples e direta, para que qualquer pessoa possa entender.
2. **Organização**: A documentação deve ser organizada em seções e subseções, para facilitar a leitura e a navegação. Utilize títulos e subtítulos para dividir o conteúdo em partes menores e mais fáceis de serem absorvidas.
3. **Coerência**: Mantenha a coerência na formatação do texto, utilizando a mesma estrutura e estilo ao longo de toda a documentação. Isso inclui o uso de títulos, listas, links, imagens, entre outros elementos.
4. **Correção**: Verifique a ortografia e a gramática do texto antes de enviar sua contribuição. Erros de digitação e concordância podem prejudicar a compreensão da documentação.
5. **Atualização**: Mantenha a documentação sempre atualizada, refletindo as últimas mudanças e novidades do projeto. Se alguma informação estiver desatualizada, corrija-a ou adicione uma nota informando a mudança.
6. **Acessibilidade**: Certifique-se de que a documentação seja acessível a todos os usuários, incluindo pessoas com deficiência visual ou auditiva. Utilize descrições em texto alternativo para imagens e vídeos, e forneça transcrições para conteúdos em áudio.
7. **Referências**: Sempre que possível, inclua referências e links para outras fontes de informação, como tutoriais, guias e documentações oficiais. Isso ajuda os usuários a se aprofundarem no assunto e a encontrar mais recursos sobre o tema.

## Sintaxes básicas do Markdown

Abaixo, listamos alguns elementos básicos de formatação do Markdown, para ajudar na escrita da documentação:

| Elemento | Sintaxe |
| --- | --- |
| Título | `#` para criar títulos e subtítulos. Quanto mais `#`, menor o título. |
| Negrito | `**texto**` para deixar o texto em negrito. |
| Itálico | `*texto*` para deixar o texto em itálico. |
| Lista | `- item` para criar uma lista não ordenada. |
| Link | `[texto](url)` para criar um link. |
| Imagem | `![alt](url)` para inserir uma imagem. |
| Imagem com link | `[![alt](url)](url)` para inserir uma imagem com link. |
| Código | `` `código` `` para destacar trechos de código. |
| Bloco de código | `` ```código``` `` para criar um bloco de código. |
| Citação | `> texto` para criar uma citação. |

Para mais informações sobre a formatação do Markdown, consulte a [documentação oficial](https://www.markdownguide.org/basic-syntax/).

## Envie sua contribuição

> [!IMPORTANT]
>
> Antes de enviar sua contribuição, verifique se já existe uma [issue](https://github.com/TableRise/docs/issues) aberta para o problema ou a sugestão que você deseja abordar. Caso contrário, crie uma nova issue descrevendo o que você pretende fazer.

### Fork e Pull Request

1. Faça um fork do repositório desejado. Por exemplo, [este repositório](https://github.com/TableRise/docs).
2. Clone o repositório para a sua máquina local: `git clone https://github.com/<USUÁRIO>/<REPOSITÓRIO>.git`.
3. Crie uma branch para a sua contribuição: `git checkout -b feat/<ISSUE_ID>/nome-da-sua-contribuição`.
4. Faça as alterações necessárias na documentação.
5. Verifique se a documentação está formatada corretamente.
6. Adicione e comite as alterações: `git add . && git commit -m "Adiciona nome-da-sua-contribuição"`.
7. Faça o push para a sua branch: `git push origin feat/<ISSUE_ID>/nome-da-sua-contribuição`.
8. Crie um Pull Request para a branch `main` do repositório original.
9. Aguarde a revisão e a aprovação da sua contribuição.

Após seguir esses passos, sua contribuição será avaliada pela equipe responsável e, se aprovada, será incorporada à documentação do projeto.

## Obrigado por contribuir! 🚀
