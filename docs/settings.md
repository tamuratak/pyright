# Pyright Settings

The Pyright VS Code extension honors the following settings.

**pyright.disableLanguageServices** [boolean]: Disables all language services except for “hover”. This includes type completion, signature completion, find definition, find references, and find symbols in file. This option is useful if you want to use pyright only as a type checker but want to run another Python language server for langue service features.

**pyright.disableOrganizeImports** [boolean]: Disables the “Organize Imports” command. This is useful if you are using another extension that provides similar functionality and you don’t want the two extensions to fight each other.

**pyright.openFilesOnly** [boolean]: Determines whether pyright analyzes (and reports errors for) all files in the workspace, as indicated by the config file. If this option is set to true, pyright analyzes only open files.

**pyright.typeCheckingMode** ["off", "basic", "strict"]: Determines the default type-checking level used by pyright. This can be overridden in the configuration file.

**pyright.useLibraryCodeForTypes** [boolean]: Determines whether pyright reads, parses and analyzes library code to extract type information in the absence of type stub files. This can add significant overhead and may result in poor-quality type information. The default value for this option is false.

**python.analysis.typeshedPaths** [array of paths]: Paths to look for typeshed modules. Pyright currently honors only the first path in the array.

**python.analysis.autoSearchPaths** [boolean]: Determines whether pyright automatically adds common search paths like "src" if there are no execution environments defined in the config file.

**python.pythonPath** [path]: Path to Python interpreter.

**python.venvPath** [path]: Path to folder with subdirectories that contain virtual environments.


