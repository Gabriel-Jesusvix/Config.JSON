{
    // Workbench
    "workbench.iconTheme": "symbols",
    "workbench.editor.labelFormat": "short",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.activityBar.location": "hidden",
    "workbench.sideBar.location": "right",
    // Editor settings
    "editor.wordWrap": "on",
    "editor.fontSize": 14,
    "editor.lineHeight": 1.8,
    "terminal.integrated.fontSize": 14,
    "editor.tabSize": 2,
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontLigatures": true,
    "editor.renderLineHighlight": "gutter",
    "editor.rulers": [80, 120],
    "editor.parameterHints.enabled": false,
    "editor.semanticHighlighting.enabled": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.codeActionsOnSave": {
      "source.fixAll": "always",
      "source.fixAll.eslint": "always",
      "source.addMissingImports": "always",
      "source.sortMembers": "always",
      "source.organizeImports": "always",
      
    },
    "[prisma]": {
      "editor.formatOnSave": true,
    },
      
    // VSCode stuff
    "breadcrumbs.enabled": true,
    "explorer.compactFolders": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",
    
    // Emmet
    "emmet.syntaxProfiles": { "javascript": "jsx" },
    "emmet.includeLanguages": { "javascript": "javascriptreact" },
    
    // Extensions
    "extensions.ignoreRecommendations": true,
    "material-icon-theme.folders.associations": {
      "domain": "core",
      "infra": "app",
      "main": "public",
      "presentation": "connection",
      "cryptography": "secure",
      "entities": "class",
      "repositories": "mappings",
      "protocols": "resource",
      "useCases": "components",
      "subcomponents": "components",
      "adapters": "connection",
      "factories": "container",
      "globals": "global",
      "ui": "views"
    },
    "material-icon-theme.files.associations": {
      "ormconfig.json": "database",
      "tsconfig.json": "tune",
      ".lintstagedrc.json": "tune"
    },
    "polacode.transparentBackground": true,
    "polacode.shadow": "none",
    "github.copilot.enable": {
      "*": true,
      "yaml": false,
      "plaintext": true,
      "markdown": false
    },
    "gitlens.defaultDateFormat": null,
    "gitlens.hovers.currentLine.over": "line",
    "liveServer.settings.donotShowInfoMsg": true,
    "git.confirmSync": false,
    "editor.inlineSuggest.enabled": true,
    "symbols.hidesExplorerArrows": false,
    "tabnine.experimentalAutoImports": true,
    "editor.occurrencesHighlight": "off",
    "editor.selectionHighlight": false,
    "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
    "terminal.integrated.env.osx": {
      "FIG_NEW_SESSION": "1"
    },
    "editor.accessibilitySupport": "off",
    "totalTypeScript.hiddenTips": [
      "ts-object-type",
      "optional-object-property",
      "type-alias-declaration",
      "basic-types",
      "union-type",
      "literal-type"
    ],
    "workbench.editor.empty.hint": "hidden",
    "git.suggestSmartCommit": false,
    "window.commandCenter": false,
    "workbench.layoutControl.enabled": false,
    "explorer.fileNesting.enabled": true,
    "explorer.fileNesting.patterns": {
      "package.json": ".eslint*, package-lock*,.prettierignore,.prettierrc* ,prettier*, tsconfig*, vite*, pnpm-lock*, bun.lockb, nest* ,.gitignore, .editorconfig, .env*, .env.example*, babel*",
      "Gemfile": "Gemfile.lock",
      "tailwind.config.js": "tailwind.config*, postcss.config*",
      ".env.local": ".env*",
      ".env": ".env*"
    },
    "editor.minimap.enabled": false,
    "workbench.colorTheme": "Material Theme Ocean",
  }
