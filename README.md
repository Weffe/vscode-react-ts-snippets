# React + Typescript Code Snippets

> Forked from https://github.com/infeng/vscode-react-typescript

-------------------

![version badge](https://img.shields.io/badge/version-1.1.0-blue.svg?logo=visual-studio-code&style=for-the-badge)

This extension contains opinionated code snippets for React with Typescript.

VS Marketplace link: https://marketplace.visualstudio.com/items?itemName=weffe.vscode-react-ts-snippets

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

Launch VS Code Quick Open (Ctrl + P or Cmd + P), paste the following command, and press enter.

`ext install weffe.vscode-react-ts-snippets`

Alternatively you can open the extensions panel and search for 'React + Typescript Code Snippets'.

## Alternative Installation

If you want to manually install the snippets then simply copy the `snippets.json` content from here: https://raw.githubusercontent.com/Weffe/vscode-react-ts-snippets/master/snippets/snippets.json

Next, in VS Code go to File -> Preferences -> User Snippets

In the popup window, search for `typescriptreact` and click on the option.

Finally, this will take you to a new window where you can paste in the copied snippets and then save!

Now, you will have access to the snippets across VS Code.

## Supported languages (file extensions)

* TypeScript (.ts)
* TypeScript React (.tsx)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

| Trigger  | Content |
| -------: | ------- |
| `tsrcc →`    | `class component skeleton` |
| `tsrcfull →` | `class component skeleton with Props, State, and constructor` |
| `tsrcjc →`   | `class component skeleton without import and default export lines` |
| `tsrpcc →`   | `class purecomponent skeleton` |
| `tsrpcjc →`  | `class purecomponent without import and default export lines` |
| `tsrpfc →`    | `pure function component skeleton` |
| `tsrsfc →`    | `stateless functional component` |
| `conc →`     | `class default constructor with props and context` |
| `cwm →`      | `componentWillMount method` |
| `ren →`      | `render method` |
| `cdm →`      | `componentDidMount method` |
| `cwrp →`     | `componentWillReceiveProps method` |
| `scu →`      | `shouldComponentUpdate method` |
| `cwu →`      | `componentWillUpdate method` |
| `cdu →`      | `componentDidUpdate method` |
| `cwum →`     | `componentWillUnmount method` |
| `gdsfp →`    | `getDerivedStateFromProps method` |
| `gsbu →`      | `getSnapshotBeforeUpdate method` |
| `sst →`      | `this.setState with object as parameter` |
| `bnd →`      | `binds the this of method inside the constructor` |
| `met →`      | `simple method` |
| `imt →`      | `import a dependency` |
| `imta →`     | `import everything from a dependency` |
| `imtd →`     | `import default object from a dependency` |
| `tsrcm →`    | `Create a React + MobX Component` |
| `tsrcmfull →`    | `Create a stateful React + MobX Component` |
| `tsrcmrr →`    | `Create a React + MobX + React-Router Component` |
| `tsrcmrrfull →`    | `Create a stateful React + MobX + React-Router Component` |

## License

MIT
