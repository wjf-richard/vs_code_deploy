1、 vscode 配置

```
  {
  "window.zoomLevel": 1,
  "editor.quickSuggestions": {
      "strings": true
  },
  "element-helper.version": "2.3",
  "editor.tabSize": 2,
  // Use 'prettier-eslint' instead of 'prettier'. Other settings will only be fallbacks in case they could not be inferred from eslint rules.
  "prettier.eslintIntegration": true,
  // If true, will use single instead of double quotes
  "prettier.singleQuote": true,
  // Whether to add a semicolon at the end of every line
  "prettier.semi": false,
  // 在函数参数括号前定义空格处理。需要 TypeScript >= 2.1.5。
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  // Default formatter for <template> region
  "vetur.format.defaultFormatter.html": "prettier",
  // Turns auto fix on save on or off.
  "eslint.autoFixOnSave": false,
  // 控制编辑器在空白字符上显示特殊符号的方式。
  "editor.renderWhitespace": "all",
  "git.autofetch": true,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  //  Validate vue-html in <template> using eslint-plugin-vue
  "vetur.validation.template": false,
}
```
