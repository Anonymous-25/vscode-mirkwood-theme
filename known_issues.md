# Known Issues

Mirkwood primarily controls the visual appearance of Visual Studio Code through its color and theme definitions. Syntax highlighting itself is provided by Visual Studio Code's language grammars and extensions.

Some syntax highlighting differences or unexpected colors may therefore be caused by the language grammar rather than Mirkwood.

## Syntax Highlighting

Mirkwood uses TextMate scopes and semantic highlighting provided by Visual Studio Code. Because different languages use different grammars, some tokens may not always receive the expected color.

If you notice incorrect or missing syntax highlighting:

1. Check whether the issue occurs only in a specific programming language.
2. Check whether the issue is also present when using another VS Code theme.
3. Make sure the relevant language extension is installed and up to date.
4. If the problem occurs only with Mirkwood, please open an issue in this project with a minimal code example and a screenshot if possible.

## Known Theme Issues

There are currently no known critical issues with the Mirkwood theme.

Minor differences may occur between languages because of differences in their TextMate grammars and semantic-token implementations.

## Reporting an Issue

If you find a problem that appears to be caused by Mirkwood, please report it through the project's issue tracker.

When reporting an issue, please include:

* VS Code version
* Mirkwood version
* Operating system
* Programming language
* Relevant language extension
* A small code example showing the problem
* Screenshot of the unexpected highlighting, if possible
* Whether semantic highlighting is enabled

This information helps determine whether the issue comes from the Mirkwood theme, a language grammar, a language extension, or Visual Studio Code itself.
