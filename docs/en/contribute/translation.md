# Translation contribution guide

## Add a new language

In the `mkdocs.yml` file, look for `i18n` in the plugins section. Then, add the language you want to translate in the format below:

```yaml
- locale: pt # language code, must be the same as the folder
name: Portuguese # name of the language that will be displayed in the translation bar
build: true # enable translation, must be `true`
nav: # translate the navigation bar
- xx: xx.md # translate the navigation bar item
# add other navigation bar items
```

In the `docs` folder, create a folder for the new language with the code that is in `mkdocs.yml`.

!!! tip "Tip"
    To ensure that all files will be translated, copy the original language folder and rename it to the new language.
    **Example**: `docs/pt` to `docs/es`.

!!! danger "Important"
    Do not change the filenames.

Run `mkdocs serve` to run the project locally and check if the language was translated correctly.

If everything is correct, create a new Pull Request as per the [contributing guide](docs.md/#pull-request) for the new translation.
