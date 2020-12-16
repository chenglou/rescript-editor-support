## master
- Fix issue where type variables are printed with global renaming when hovering or autocompleting a module (see https://github.com/rescript-lang/rescript-editor-support/issues/38).
- Fix issue where a log file was always created (see https://github.com/rescript-lang/rescript-vscode/issues/47).

## Release 1.0.1 of rescript-vscode 
This [commit](https://github.com/rescript-lang/rescript-editor-support/commit/232ad609766c415048750c5cc828973a9995f382) is vendored in [rescript-vscode 1.0.1](https://github.com/rescript-lang/rescript-vscode/releases/tag/1.0.1).

- Support printing inline records.
- Add typedef hover support.
- Always output valid json, even in case of internal error.
- Remove semicolon in module top level preview.
- Support syntax highlight in hover fenced blocks.
- Fix printing of variant arguments.
- Use outcome printer from the syntax to print type declarations.
- Fix issue in command-line parsing on Windows with paths of the form `c:/...:line:column`.

## Release 1.0.0 of rescript-vscode 
This [commit](https://github.com/rescript-lang/rescript-editor-support/commit/d45f45793a307a3bb87dcac0542fd412669f1b6e) is vendored in [rescript-vscode 1.0.0](https://github.com/rescript-lang/rescript-vscode/releases/tag/1.0.0).