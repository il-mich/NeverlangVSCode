```
 _   _                     _                    __      _______    _____          _      
| \ | |                   | |                   \ \    / / ____|  / ____|        | |     
|  \| | _____   _____ _ __| | __ _ _ __   __ _   \ \  / / (___   | |     ___   __| | ___ 
| . ` |/ _ \ \ / / _ \ '__| |/ _` | '_ \ / _` |   \ \/ / \___ \  | |    / _ \ / _  |/ _ \
| |\  |  __/\ V /  __/ |  | | (_| | | | | (_| |    \  /  ____) | | |___| (_) | (_| |  __/
|_| \_|\___| \_/ \___|_|  |_|\__,_|_| |_|\__, |     \/  |_____/   \_____\___/ \____|\___|
                                          __/ |                                          
                                         |___/                                           
```

## Neverlang VS Code README

Welcome to the Neverlang VS Code extension!

### What is provided

This extension gives some basic syntax highlighting, which as of today does not
include embedded syntaxes for the languages used in the implementation of the slices.
The package includes some useful snippets.

### "Installation"

Clone this repo in your `~/.vscode/extensions` folder and restart VS Code.

### Suggestions

It is recommended to add `"editor.snippetSuggestions": "top"` to your global or
local VS Code config in order to get snippet matches before completion suggestions.

The "Non terminals" rule unfortunately has to be triggered manually:
write the prefix symbol `<--` or a subset of it and (on Linux) press
`ctrl + Space` to open the IntelliSense menu.

### Contributions

By following the TextMate XML syntax it is possible to refine and expand the
syntax highlighting provided in `./syntaxes/Neverlang.tmLanguage`.

And using the [VSCode documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
one can add snippets to the `./snippets/Neverlang.json` file.

Feel free to add to this package and possibly create pull requests.