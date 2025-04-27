# HP User RPL Language Support

This Visual Studio Code extension adds language support for [HP User RPL](https://en.wikipedia.org/wiki/RPL_(programming_language)), the programming language used in HP graphing calculators such as the HP 50g, HP 49G, and other similar models. It provides syntax highlighting and helps streamline development directly within VSCode.

RPL source files from these calculators use the **RPL character set**, which is a superset of ISO 8859-1.
For more information, see: <https://en.wikipedia.org/wiki/RPL_character_set>

For best viewing and editing of RPL source code, open files using the **"ISO 8859-15"** encoding.

### Recommended VS Code Settings

To ensure proper handling of encoding and formatting for files, add the following to your `settings.json` in VS Code:

```json
"[userrpl]": {
  "files.encoding": "iso885915",
  "files.autoGuessEncoding": false,
  "editor.tabSize": 2,
  "editor.wordWrap": "off"
}
```

These settings help preserve the correct character encoding and maintain a consistent editing experience tailored to RPL code.
