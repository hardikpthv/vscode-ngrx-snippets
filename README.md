# NgRx (Version 9) Snippets for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/hardikpthv.NgRxSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.NgRxSnippets)
[![Install](https://vsmarketplacebadge.apphb.com/installs-short/hardikpthv.NgRxSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.NgRxSnippets)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/hardikpthv.NgRxSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.NgRxSnippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/hardikpthv.NgRxSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.NgRxSnippets)
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

| Snippet                        | Purpose                                                            |
| ------------------------------ | ------------------------------------------------------------------ |
| ngrx-actions-setup             | Fully configured Action constants, creators with success and fail. |
| ngrx-create-action-setup       | `createAction` setup                                               |
| ngrx-create-action             | `createAction`                                                     |
| ngrx-create-action-props       | `createAction` with `props`                                        |
| ngrx-actions-setup-crud        | Fully configured Actions for CRUD operations.                      |
| ngrx-action                    | Action                                                             |
| ngrx-action-success            | Success Action                                                     |
| ngrx-action-fail               | Fail Action                                                        |
| ngrx-effect-setup              | Fully configured Effect                                            |
| ngrx-effect                    | Effect                                                             |
| ngrx-create-effect-setup       | Fully configured Effect using `createEffect`                       |
| ngrx-create-effect             | `createEffect` function                                            |
| ngrx-root-effect-registration  | Effect Registration for root module                                |
| ngrx-feat-effect-registration  | Effect Registration for feature module                             |
| ngrx-reducer                   | Reducer                                                            |
| ngrx-reducer-setup             | Reducer with state definition                                      |
| ngrx-on                        | `on`                                                               |
| ngrx-selector                  | `createSelector()`                                                 |
| ngrx-feat-selector             | `createFeatureSelector()`                                          |
| ngrx-store-select              | `store.select()`                                                   |
| ngrx-dispatch-action           | `store.dispatch()`                                                 |
| ngrx-devtool-instrument        | Store devtool instrument specification                             |
| ngrx-entities-setup            | Data entities setup                                                |
| ngrx-entity-adapter-setup      | Entity adapter                                                     |
| ngrx-entity-store-registration | Entity store registration                                          |
| ngrx-entity-data-service       | Entity service data service                                        |

### Using Angular Material or Webcomponents 🤔

- Check out:
  - [Angular Material Snippets](https://bit.ly/ng-material-vscode)
  - [Webcomponents and Lit Snippets](https://bit.ly/lit-vscode)
