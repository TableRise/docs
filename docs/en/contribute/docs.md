# Documentation contribution guide

Documentation is an essential part of any project, as it is through it that users and developers can understand how the project works, how to use it, and how to contribute to it. Therefore, it is important that the documentation is clear, objective, and complete.

## Tools

To write the project documentation, we use Markdown, a simple and easy-to-learn markup language. With Markdown, it is possible to create documents with basic formatting, such as titles, lists, links, images, among others. To render the documentation website, we use [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

To view the documentation in real time, we recommend using [VS Code](https://code.visualstudio.com/), a free and open source code editor that has native support for Markdown.

!!! tip "Tip"
    To install VS Code, go to the [official website](https://code.visualstudio.com/) and download the version compatible with your operating system.

### Recommended extensions

- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) to check Markdown formatting.
- [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) to view documentation in real time.
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) to highlight Markdown formatting errors.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) and [Brazilian Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian) to check the spelling of the text. This same creator has other extensions for other languages.

## Writing standards

To maintain consistency and quality of the documentation, it is important to follow some writing standards. Below, we list some guidelines that should be followed when contributing to the project's documentation:

1. **Clarity**: The documentation must be clear and objective, avoiding unnecessary technical terms and jargon. Try to explain the concepts in a simple and direct way, so that anyone can understand.
2. **Organization**: The documentation must be organized into sections and subsections, to facilitate reading and navigation. Use headings and subheadings to divide content into smaller, more digestible chunks.
3. **Consistency**: Maintain consistency in text formatting, using the same structure and style throughout the documentation. This includes the use of headings, lists, links, images, and other elements.
4. **Proofreading**: Check the text for spelling and grammar before submitting your contribution. Typos and grammar errors can make the documentation difficult to understand.
5. **Updating**: Keep the documentation up to date, reflecting the latest changes and developments in the project. If any information is out of date, correct it or add a note informing the change.
6. **Accessibility**: Make sure the documentation is accessible to all users, including those with visual or hearing impairments. Use alternative text descriptions for images and videos, and provide transcripts for audio content. 7. **References**: Whenever possible, include references and links to other sources of information, such as tutorials, guides, and official documentation. This helps users delve deeper into the subject and find more resources on the topic.

## Basic Markdown syntax

Below, we list some basic Markdown formatting elements to help you write documentation:

| Element | Syntax |
| --- | --- |
| Title | `#` to create titles and subtitles. The more `#`, the smaller the title. |
| Bold | `**text**` to make the text bold. |
| Italic | `*text*` to make the text italic. |
| List | `- item` to create an unordered list. |
| Link | `[text](url)` to create a link. |
| Image | `![alt](url)` to insert an image. |
| Image with link | `[![alt](url)](url)` to insert a linked image. |
| Code | `` `code` `` to highlight code snippets. |
| Code block | `` ```code``` `` to create a code block. |
| Quote | `> text` to create a quote. |

For more information on Markdown formatting, see the [official documentation](https://www.markdownguide.org/basic-syntax/). Also see the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/reference/) references.

## Submit your contribution

!!! warning "Important"
    Before submitting your contribution, check if there is already an [issue](https://github.com/TableRise/docs/issues) open for the problem or suggestion you want to address. Otherwise, create a new issue describing what you intend to do.

### Pull Request

1. Fork the desired repository. For example, [this repository](https://github.com/TableRise/docs).
2. Clone the repository to your local machine: `git clone https://github.com/<USER>/<REPOSITORY>.git`.
3. Create a branch for your contribution: `git checkout -b feat/<ISSUE_ID>/your-contribution-name`.
4. Make any necessary changes to the documentation.
5. Check that the documentation is formatted correctly.
6. Add and commit the changes: `git add . && git commit -m "Add your-contribution-name"`.
7. Push to your branch: `git push origin feat/<ISSUE_ID>your-contribution-name`.
8. Create a Pull Request to the `main` branch of the original repository.
9. Wait for your contribution to be reviewed and approved.

After following these steps, your contribution will be evaluated by the responsible team and, if approved, will be incorporated into the project documentation.

!!! success "Congratulations"
    Thank you for contributing! 🚀
