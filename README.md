# VILT-Mastery-Build-Advanced-SPAs-with-Vue

Suggested VSCode Extensions:
Auto Close Tag

Beautify Blade

ESLint

Laravel Extra Intellisense

PHP Intelephense

PHP Namespace Resolver

Tailwind CSS IntelliSense

Vue Language Features (Volar)

Custom Workspace Settings
You can configure VSCode PER PROJECT.

Inside the project create the .vscode folder. Inside the folder, create the settings.json file and paste the following:

{
  "eslint.validate": [
    "javascript",
    "javascriptvue",
    "vue"
  ],
  "eslint.format.enable": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "workbench.colorTheme": "Default Dark+",
  "editor.fontFamily": "Cascadia Code",
  "editor.fontWeight": "400",
}