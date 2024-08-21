# cube-voyager-lang

This extension aims to provide language support for Cube Voyager script files in VSCODE.

## Developing

- Currently rough completed the keyword support, and continue to complete the remaining keywords based on the document chapters

## Convert Yaml to Json

Use the following statement to convert yaml to json:

```shell
npx js-yaml syntaxes/cvoyager.tmLanguage.yaml > syntaxes/cvoyager.tmLanguage.json
```

## Keyword description

### General syntax

statements:

- `%...%`/`@...@`
- `;`
- `/*...*/`

## Release notes

### 0.0.1

- A language support file was written based on the keywords and syntax in the documentation
- Written in yaml
