# Instructions

1. Install extensions
1. Copy/merge **settings.json**
1. Adjust path for `vscode_custom_css.imports`
1. Let VSCode modify itself

    ```sh
    sudo chown -R $(whoami) "$(which code)"
    sudo chown -R $(whoami) /usr/share/code
    ```

1. Run **Reload Custom CSS and JS**
1. Repeat `4.` and `5.` after VSCode updates
