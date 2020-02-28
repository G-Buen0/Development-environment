# Dev Environment
The goal of this repositorie is save the installations process of my development environment in MacOs after VS Code installation.

# 1- Homebrew install
[Homebrew](https://brew.sh/) is a package manager for MacOs.

Install:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
# 2- Node.js install
Install [Node](https://nodejs.org/en/) via Homebrew:
```
brew install node
```
# 3- Yarn install
[Yarn](https://yarnpkg.com/) is a Node package manager.

Install via Homebrew using --ignore-dependencies tag for install yarn without Node:
```
brew install yarn --ignore-dependencies 
```
# 4- VS Code extensions

- Dracula Official:  `A dark theme for Visual Studio Code.`

- GitLens: `Supercharge the Git capabilities built into Visual Studio Code.`

- HTML CSS Support: `CSS support for HTML documents.`

- HTML Snippets: ` Full HTML tags including HTML5 Snippets.`

- IntelliSense for CSS class names in HTML: `CSS class name completion for the HTML class attribute based on the definitions found in your workspace.`

- Material Icon Theme: `Material Design Icons for Visual Studio Code.`

# VS Code settings.json
Some settings:
```
{
    "terminal.integrated.shell.osx": "/bin/zsh",
    "emmet.syntaxProfiles": {
        "javascript": "jsx",
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
    }
}
```
# ZSH Terminal