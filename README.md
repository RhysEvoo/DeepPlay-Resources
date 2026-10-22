# DeepPlay Plugins

The plugins DeepPlay's Store offers, for DeepPlay on the PS3. DeepPlay reads `catalog.json` and downloads a plugin's
files from `<id>/`, checking each against the size and SHA-256 the catalogue lists.

| File | What it is |
| --- | --- |
| `catalog.json` | Every plugin's entry |
| `<id>/plugin.json` | One plugin's entry: its words, colours, version and files |
| `<id>/module.sprx` | The plugin, compiled and signed |
| `<id>/icon.png` | Its 256x256 icon |
| `<id>/background.jpg` | Its 1280x720 page background |
| `<id>/README.md` | What it is |

These files are made by `publish-plugin.ps1` in the DeepPlay source; don't edit them here.