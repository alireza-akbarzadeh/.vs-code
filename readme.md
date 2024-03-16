# VS Code Configuration Repository

## Overview

This repository contains my VS Code configuration settings and keybindings.

## Settings

Check out the setting JSON file I provided for you attached to this repository


### Extensions

Here are the extensions I use:

- **Code Spell Checker**: Helps check spelling errors in code.
- **Cody AI**: (Provide a brief description of what this extension does.)
- **Error Lens**: (Explain what Error Lens does.)
- **React, React-Native, and Redux in JS/TS with ES7**: (Brief description of this extension's functionality.)
- **ESLint**: Linting utility for JavaScript and TypeScript.
- **Git Blame**: Provides Git blame information in the editor.
- **Git Graph**: Visualize Git repository history.
- **Git History**: View and search Git history.
- **Git Ignore**: Support for .gitignore files.
- **GitLens**: Supercharges the Git capabilities built into Visual Studio Code.
- **JavaScript and TypeScript Nightly**: (Brief description of this extension.)
- **Material Icon Theme**: Provides Material Design icons for Visual Studio Code.
- **Monokai Pro**: A color theme for Visual Studio Code.
- **Prettier Code Formatter**: Formats code using Prettier.
- **Prettier ESLint**: Integrates Prettier with ESLint.
- **Pretty TypeScript Errors**: Improves the display of TypeScript errors.
- **Project Manager**: Easily switch between projects in Visual Studio Code.
- **Tailwind CSS IntelliSense**: IntelliSense for Tailwind CSS.
- **Todo Highlight**: Highlight TODO, FIXME, etc. comments within your code.
- **Turbo Console Log**: Quickly add console.log statements with keyboard shortcuts.


## Keybindings

### Keybindings

- **Shift + Tab**: Outdent selected text.
  - Command: `outdent`
  - When: `editorTextFocus && !editorTabMovesFocus`

- **Ctrl + Space**: Trigger suggestion for completion.
  - Command: `editor.action.triggerSuggest`
  - When: `editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible`

- **Shift + Cmd + G**: Open Source Control Management (SCM) view.
  - Command: `workbench.view.scm`
  - When: `workbench.scm.active`

- **Ctrl + Shift + G**: Close Source Control Management (SCM) view.
  - Command: `-workbench.view.scm`
  - When: `workbench.scm.active`

## Additional Information

For more detailed information about the configuration of my terminal, check out [this repository](https://github.com/alireza-akbarzadeh/dotfiles).


![image](https://github.com/alireza-akbarzadeh/.vs-code/assets/82927248/58044f31-58ab-478d-9c4c-7b2a57cc153d)



