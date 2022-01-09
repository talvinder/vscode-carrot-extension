# Carrot (Gherkin extension) Syntax and Snippets

[![Build Status](https://travis-ci.org/euclidity/vscode-cucumber.svg?branch=master)](https://travis-ci.org/euclidity/vscode-cucumber)

A [Visual Studio Code](https://code.visualstudio.com/) [extension](https://marketplace.visualstudio.com/items?itemName=stevejpurves.cucumber) for [Cucumber](https://cucumber.io/) projects that:

- enables syntax highlight for `.feature` files;
- offers code snippets or templates to write `Carrot` scenarios faster.

## How to use

The syntax highlight is applied automatically to `.feature` files. If that doesn't happen, you can open the **Command Pallete**, type **Change Language Mode** and select the `Gherkin`. `Carrot` is an extension of `Gherkin` and hence uses the same `.feature` file extension.

To use snippets you just need to type the prefix and press `Tab`. These are the snippets we provide:

- `fea` - Feature
- `sc` - Scenario heading
- `sce` - Scenario
- `sco` - Scenario Outline
- `steps`- Multiline steps
- `giv` - Given step
- `whe` - When step
- `the` - Then step
- `des` - Design link
- `suc` - Success criteria
- `kpi` - KPI to track
- `imp` - Impact expected

Feature snippet contains the keywords, `user story`, `okr`, `epic` and `sprint`. Hence, they are not provided separately.

## Install

Given you have [Visual Studio Code](https://code.visualstudio.com/) installed:

1. Open the command palette `Ctrl-Shift-P` (Windows, Linux) or `Cmd-Shift-P` (macOS).
2. Select **Install Extension**, search for **Carrot (Gherkin extension) Syntax and Snippets**, install it.
3. Finally, reload Visual Studio Code.

## Contribute

Feature requests or issue reports should be done [here](https://github.com/talvinder/vscode-carrot/issues).

Feel free to help us improve this extension with pull requests at our [official repository](https://github.com/talvinder/vscode-carrot).

## Acknowledgements

👏 Our big thanks to our contributors and to other libraries and resources we used to develop this extension 👏

### Team behind carrot
- Author: [Talvinder Singh](mailto:talvinder27@gmail.com)

### Team behind vscode-cucumber

- Author: [Steve Purves](mailto:stevejpurves@gmail.com)
- Maintainer: [Diogo Nunes](https://github.com/dialex)
- Contributors: [(these amazing people)](https://github.com/stevejpurves/vscode-cucumber/graphs/contributors)

### Dependencies

- [TextMate Syntax and Snippet definitions for Cucumber](https://github.com/cucumber/cucumber-tmbundle)
