# Lest Language VSCode Extension

VSCode extension providing syntax highlighting for the Lest programming language.

## Features

- Syntax highlighting
- Embedded code syntax highlighting (when available for language)
  - Code between 
    ```hs
    -- @embed "file-name" "language-name"
    ```
    and
    ```hs
    -- @end embed "file-name"
    ```
  - Example:
    ```hs
    -- @embed "main.hs" "c"
    module Main where
      main :: IO ()
      main = do putStrLn "Hello, world!"
    -- @end embed "main.hs"
    ```
<!-- 
Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow. 
-->

## Requirements

- No requirements.

## Extension Settings

- No settings yet.
<!-- 
Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something.
-->

## Known Issues

- No known issues.
<!-- 
Calling out known issues can help limit users opening duplicate issues against your extension. 
-->

## Release Notes

### 0.0.1

- most tokens are accounted for
- no larger sections of code have been added yet, e.g., functions, function bodies, spec definitions

## Planned

### 0.0.2

- add function definition and type declaration support

### 0.0.3

- add spec definition support

<!-- 
### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

--- 
-->
