# settings.json
```json
{
    "xmake.debugConfigType": "codelldb",
    "C_Cpp.intelliSenseEngine": "disabled",
    "git.path": "C:\\Program Files\\Git\\cmd",
    "editor.fontLigatures": false,
    "vim.useCtrlKeys": true,
    "vim.handleKeys": {
        "<C-w>": false,
        "<C-c>": false,
        "<C-v>": false,
        "<C-b>": false,
        "<C-j>": false,
    },
    "vim.useSystemClipboard": true,
    "vim.insertModeKeyBindings": [
        {
        "before": ["j", "k"],
        "after": ["<Esc>"]
        }
    ],
    "vim.visualModeKeyBindings": [
        {
        "before": ["j", "k"],
        "after": ["<Esc>"]
        }
    ],
    "vim.normalModeKeyBindings": [
        {
        "before": ["<leader>", "t", "n"],
        "commands": [":tabnext"]
        },
        {
        "before": ["<leader>", "t", "p"],
        "commands": [":tabprev"]
        },
        {
        "before": ["<leader>", "t", "f"],
        "commands": [":tabfirst"]
        },
        {
        "before": ["<leader>", "t", "l"],
        "commands": [":tablast"]
        }
    ],
    "vim.ignorecase": false,
    "vim.leader": " ",
    "vim.easymotion": true,
    "vim.sneak": true,
    "vim.surround": true,
    "vim.statusBarColorControl": true,
    "vim.statusBarColors": {
        "normal": "#005f5f",
        "insert": "#5f0000",
        "visual": "#5f00af",
        "visualline": "#005f87",
        "visualblock": "#86592d",
        "replace": "#000000"
    },
    "workbench.colorCustomizations": {
        "statusBar.background": "#005f5f",
        "statusBar.noFolderBackground": "#005f5f",
        "statusBar.debuggingBackground": "#005f5f",
        "statusBar.foreground": "#ffffff",
        "statusBar.debuggingForeground": "#ffffff"
    }
}


```