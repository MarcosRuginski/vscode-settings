```
{ 
    // Define o tema do VSCode 
    "workbench.colorTheme": "GitHub Dark Default",

    // Aumenta a fonte do terminal
    "terminal.integrated.fontSize": 14,
    
    // Define o tema dos icones na sidebar
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    
    // Associação do nome do arquivo com o ícone
    "material-icon-theme.folders.associations": {
        "infra": "app",
        "entities": "class",
        "domain": "class",
        "schemas": "class",
        "typeorm": "database",
        "repositories": "mappings",
        "http": "container",
        "migrations": "tools",
        "modules": "components",
        "implementations": "core",
        "dtos": "typescript",
        "fakes": "mock",
        "websockets": "pipe",
        "protos": "pipe",
        "grpc": "pipe",
        "providers": "include",
        "subscribers": "messages",
        "useCases": "controller",
        "kafta": "scripts",
        "wappers": "meta",
        "_shared": "shared",
        "eslint-config": "tools"
    },
    
    // Configura tamanho e familia da fonte
    "editor.tabSize": 2,
    "editor.fontSize": 14,
    "editor.lineHeight": 21,
    "editor.fontWeight": "500",
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true, // Mostra simbolo <= >=
    
    "explorer.compactFolders": false,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations":true,
    
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",
    
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": true,
    "explorer.confirmDragAndDrop": true,
    "explorer.confirmDelete": false,
    
    // Coloca as linhas brancas
    "editor.rulers": [80, 120], 
    
    // Quando salva, automaticamente corrige os erros
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit"
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit"
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit"
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": "explicit"
        }
    },

    // Quando salva, automaticamente corrige formtação
    "[php]": {
        "editor.formatOnSave": true,
        "editor.formatOnPaste": true,
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    
    "emmet.syntaxProfiles": { "javascript": "jsx" }, // Auto complete do HTML para js
    "emmet.includeLanguages": { "javascript": "javascriptreact" },  // Auto complete do HTML para js
    
    "editor.minimap.enabled": false,
    "window.zoomLevel": 0,
    
    // Oculta menu superior, pressionar ALT para exibir novamente
    "window.menuBarVisibility": "toggle",
    
    // Busca automaticamente novos commits
    "git.autofetch": true,

    // Faz o stash automaticamente na hora de puxar os commits
    "git.autoStash": true,
}
```
