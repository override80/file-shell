# File Shell – File Manager / Editor for Home Assistant

A powerful file and code editor for Home Assistant.

---

## Features

- **File management** – browse, create, delete, rename, move, copy files and folders
- **Code editor** – powered by [CodeMirror 6](https://codemirror.net/) with syntax highlighting for:
  - YAML, Python, JavaScript, JSON, PHP, HTML, CSS, Shell, Jinja and more
- **Multi‑tab editing** – open multiple files simultaneously; each tab preserves undo history, scroll position, cursor, and language mode
- **Auto‑save drafts** – unsaved changes are saved locally and can be restored on reopen
- **Terminal** – interactive shell
- **Favorites** – quickly access your most‑used files and folders
- **Archive support** – create and extract `.zip`, `.tar`, `.gz`, `.tgz` archives
- **Drag‑and‑drop upload** – upload single files or entire folder trees with progress indicators
- **Permissions management** – view and change file mode
- **Validation** – syntax checking for YAML, Python, JSON, and JavaScript
- **Admin‑only** – the panel and all API endpoints are restricted to Home Assistant admin users

---

## Screenshots

![](/screenshot-1.png?raw=true)

![](/screenshot-2.png?raw=true)

![](/screenshot-3.png?raw=true)

![](/screenshot-4.png?raw=true)

![](/screenshot-5.png?raw=true)

---

## Installation

### HACS (recommended)

1. Add this repository to HACS as a custom repository:
   - **Repository URL**: `https://github.com/junkfix/file-shell`
   - **Category**: Integration
2. Install the integration via HACS.
3. Restart Home Assistant.
4. Go to Settings → Devices & Services → Add Integration → File Shell

### Manual

1. Copy the `file_shell` folder to your `custom_components/` directory.
2. Restart Home Assistant.
4. Go to Settings → Devices & Services → Add Integration → File Shell
   
    or 
    Add the following to your `configuration.yaml`
    ```yaml
    file_shell:
    ```


