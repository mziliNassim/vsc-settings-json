```json
{
  // open json editor for settings
  "workbench.settings.editor": "json",

  // Font size
  "editor.fontSize": 17,
  "terminal.integrated.fontSize": 13,

  "editor.wordWrap": "off",

  // Change font
  "editor.fontFamily": "Cascadia Code",
  "editor.codeLensFontFamily": "Cascadia Code",
  "editor.inlayHints.fontFamily": "Cascadia Code",
  "scm.inputFontFamily": "Cascadia Code",
  "terminal.integrated.fontFamily": "Hack Nerd Font",
  "chat.editor.fontFamily": "Cascadia Code",
  "debug.console.fontFamily": "HCascadia Code",
  "notebook.output.fontFamily": "Cascadia Code",
  "markdown.preview.fontFamily": "Cascadia Code",

  // font style " => != === <!-- --> "
  "editor.fontLigatures": true,

  // ui -- Misc
  /* window */
  "window.commandCenter": false,
  "window.titleBarStyle": "custom",
  "window.zoomLevel": 0.65,
  "window.menuBarVisibility": "classic",

  /* editor */
  "editor.guides.indentation": false,
  "editor.renderWhitespace": "selection",
  "editor.renderLineHighlight": "all",
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.overviewRulerBorder": false,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.tabSize": 1,
  "editor.detectIndentation": true,
  "editor.lineHeight": 1.6,
  "editor.codeActionsOnSave": {},
  "editor.linkedEditing": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "editor.fontWeight": "normal",
  "editor.autoClosingBrackets": "always",
  "editor.minimap.size": "fit",
  "editor.minimap.side": "right",
  "editor.minimap.autohide": true,
  "editor.minimap.scale": 1,
  "editor.minimap.showSlider": "always",
  "editor.minimap.renderCharacters": true,
  "editor.mouseWheelZoom": false,

  /* workbench */
  "workbench.layoutControl.enabled": false,
  "workbench.startupEditor": "none",
  "breadcrumbs.filePath": "off",
  /* explorer */
  "explorer.compactFolders": false,
  /* git */
  "git.decorations.enabled": false,
  /* scm */
  "scm.diffDecorations": "none",
  /* files */
  "files.insertFinalNewline": false,
  "files.trimTrailingWhitespace": true,
  "[markdown]": {
    "files.trimTrailingWhitespace": false
  },
  /* extensions */
  "extensions.ignoreRecommendations": true,

  // Toggle excluded files
  "files.exclude": {
    "**/.git": false,
    "**/.svn": false,
    "**/.hg": false,
    "**/CVS": false,
    "**/.DS_Store": false,
    "**/Thumbs.db": false,
    "**/node_modules": false,
    "**/.next": false,
    "**/.husky": false,
    "**/drizzle": false,
    "**/dist": false,
    "**/.todo.md": false,
    "**/.vscode": false,
    "**/.eslintrc.cjs": false,
    "**/.editorconfig": false,
    "**/.gitignore": false,
    "**/.lintstagedrc.mjs": false,
    "**/.markdownlint.json": false,
    "**/.markdownlintignore": false,
    "**/.prettierignore": false,
    "**/bun.lockb": false,
    "**/cspell.json": false,
    "**/package-lock.json": false,
    "**/pnpm-lock.yaml": false,
    "**/next-env.d.ts": false,
    "**/postcss.config.cjs": false,
    "**/prettier.config.js": false,
    "**/README.md": false,
    "**/next.config.js": false,
    "**/tailwind.config.ts": false,
    "**/drizzle.config.ts": false,
    "**/migrate.ts": false,
    "**/.env.example": false
  },

  // Termenall
  "code-runner.runInTerminal": true,
  "terminal.integrated.defaultProfile.windows": "PowerShell",

  // icons
  "workbench.iconTheme": "sweet-vscode-icons",

  // settings Sync
  "settingsSync.ignoredExtensions": [],

  // formatting code
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Auto close tag
  "auto-close-tag.activationOnLanguage": [
    "xml",
    "php",
    "blade",
    "ejs",
    "jinja",
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "plaintext",
    "markdown",
    "vue",
    "liquid",
    "erb",
    "lang-cfml",
    "cfml",
    "HTML (EEx)",
    "HTML (Eex)",
    "plist"
  ],

  // Tabnine
  "tabnine.experimentalAutoImports": true,

  // Apc
  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": false,
    "size": 30
  },
  "apc.electron": {
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 12,
      "y": 10
    }
  },
  "apc.font.family": "Cascadia Code",
  "apc.monospace.font.family": "Hack Nerd Font",
  "apc.statusBar": {
    "position": "editor-bottom",
    "height": 25,
    "fontSize": 10
  },
  "apc.stylesheet": {
    ".sidebar > .composite": "height: 1px !important",
    ".pane-header": "background-color: transparent !important",
    ".title-label": "display: none !important",
    ".title-actions": "display: none !important",
    ".titlebar-center": "display: none !important",
    ".inline-tabs-placeholder": "display: none !important",
    ".file-icons-enabled > .quick-input-widget.show-file-icons": "position: fixed !important; top: 50% !important; transform: translateY(-50%) !important; z-index: 9999 !important; box-shadow: 10px 10px 10px #0002;",
    ".quick-input-widget.show-file-icons .quick-input-title": "display: none !important",
    ".split-view-view.visible": "background-color: #161925 !important; box-shadow: 10px 10px 10px #0002 !important"
  },
  "animations.Install-Method": "Apc Customize UI++",
  "apc.imports": [
    "file:///c:/Users/NASSIM/.vscode/extensions/brandonkirbyson.vscode-animations-2.0.1/dist/updateHandler.js"
  ],
  // =============== end APC ===============

  "turboConsoleLog.addSemicolonInTheEnd": true,
  "turboConsoleLog.logMessagePrefix": "",
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDragAndDrop": false,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.autoSave": "afterDelay",
  "explorer.confirmDelete": false,
  "errorLens.enabledDiagnosticLevels": ["error"],
  "tabnine.codeLensEnabled": false,

  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "TODO:",
      "color": "#FF8C00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],
  "glassit.alpha": 255,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorTheme": "Sweet Dracula",
  "workbench.productIconTheme": "fluent-icons",
  "background.backgroundBlur": ["1", "0", "0", "0"],
  "background.backgroundOpacity": [0.9, 0.9, 0.9, 0.9],
  "editor.fontVariations": false,
  "vscode_vibrancy.theme": "Default Dark",
  "editor.accessibilitySupport": "off",
  "workbench.colorCustomizations": {
    "terminal.background": "#00000000"
  },
  "workbench.settings.applyToAllProfiles": ["workbench.colorCustomizations"],
  "bracket-pair-colorizer-2.depreciation-notice": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.editor.editorActionsLocation": "titleBar",
  "window.customTitleBarVisibility": "windowed",
  "terminal.integrated.env.windows": {},
  "editor.cursorBlinking": "expand",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "terminal.integrated.enableMultiLinePasteWarning": "auto",
  "tailwindCSS.files.exclude": ["**/node_modules/**", "**/.hg/**", "**/.svn/**"]

  // ========== End Settings ==========
}
```
