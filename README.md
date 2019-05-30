# NgRx Snippets for VS Code

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)

This extension for Visual Studio Code adds snippets of Typescript for NgRx.

Have a look at [CHANGELOG](CHANGELOG.md) for the latest changes

## Installation

1.  Install Visual Studio Code 1.10.0 or higher
1.  Launch VS Code
1.  Hit `Cmd`-`Shift`-`P` (macOS) or `Ctrl`-`Shift`-`P` (Windows, Linux)
1.  Select `Install Extension`
1.  Choose the extension `NgRx snippets`
1.  Reload Visual Studio Code

## Usage

Start typing `ngrx-*` and hit `enter`, the snippet spreads out.

![Use Extension](images/usage.gif)

### TypeScript Snippets

| Snippet                 | Purpose                                                            |
| ----------------------- | ------------------------------------------------------------------ |
| ngrx-actions-setup      | Fully configured Action constants, creators with success and fail. |
| ngrx-actions-setup-crud | Fully configured Actions for CRUD operations.                      |
| ngrx-action             | Action                                                             |
| ngrx-action-success     | Success Action                                                     |
| ngrx-action-fail        | Fail Action                                                        |
| ngrx-effect-setup       | Fully configured Effect                                            |
| ngrx-effect             | Effect                                                             |
| ngrx-reducer            | Reducer                                                            |
| ngrx-case               | `case:` for reducer's `switch`                                     |
| ngrx-selector           | `createSelector()`                                                 |
| ngrx-feat-selector      | `createFeatureSelector()`                                          |
| ngrx-store-select       | `store.select()`                                                   |
| ngrx-dispatch-action    | `store.dispatch()`                                                 |

### Using Angular Material
 - Check out [Angular Material Snippets](https://bit.ly/ng-material-vscode)
