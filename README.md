This project was developed by [IVNA FEITOSA](https://github.com/IvnaFeitosa), [FRANCIO CHAVIER](https://github.com/FrancioXavier), [FELIPE FERRAZ](https://github.com/FelipeFerraz4), and [JOHN KAUÃ](https://github.com/JohnKaua).
# Front-end Pharmacy Project

Repository tools and usability documentation.

## Installation
After cloning the repository, install dependencies and run the project:
```bash
npm install
npm start
```
Code formatters such as Prettier and ESLint are used to improve code quality. It is recommended to add these configurations to your VScode `settings.json` so that the code is automatically formatted among other development advantages and to properly follow the project standard.

Follow the settings below:
```json
"javascript.preferences.quoteStyle": "single",
"typescript.preferences.quoteStyle": "single",
"javascript.validate.enable": false,
"javascript.updateImportsOnFileMove.enabled": "always",
"typescript.updateImportsOnFileMove.enabled": "always",
"javascript.suggest.autoImports": true,
"typescript.suggest.autoImports": true,
"[javascript]": {
  "editor.suggestSelection": "recentlyUsed",
  "editor.suggest.showKeywords": false,
  "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
},
"emmet.syntaxProfiles": {
  "javascript": "jsx"
},
"emmet.includeLanguages": {
  "django-html": "html",
  "javascript": "javascriptreact",
  "typescript": "typescriptreact"
},
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": "explicit",
  "source.fixAll": "explicit"
},
"git.enableSmartCommit": true,
"eslint.validate": [
  {
    "language": "javascript",
    "autoFix": true
  },
  {
    "language": "javascriptreact",
    "autoFix": true
  }
],
```

## Extensions and Other Dependencies
To utilize the configurations already made in the previous section, it will be necessary to install these extensions to your VS Code:

* ESLint
* editorconfig for VS Code
* Prettier - Code formatter