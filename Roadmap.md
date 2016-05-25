# Roadmap

With the "1.0" release behind us, now is a good time to look towards the future. We typically look out 6 to 12 months, establish a set of themes we want to work towards, and then schedule work each milestone supporting those themes. VS Code will continue to ship monthly and we'll make progress against each of the following themes during each iteration.

## Improve Getting Started

It should be quick and natural to customize the tool to the way you work. You should be able to quickly get started with your code.   

* Configure key bindings, themes, common settings on first run of VS Code
* Ability to create new and populated Workspaces from within VS Code
* "Open in VS Code" from a git repository
* Installation improvements such as auto move to Applications on OSX, Linux auto-update, and in product release notes

## Eliminate Adoption Blockers

VS Code is a young product and there still missing features and experiences that you are asking for and that we want to deliver. 

* [Tabs](https://github.com/Microsoft/vscode/issues/224) and window management (e.g. horizontal split)
* [VIM style key binding support](https://github.com/Microsoft/vscode/issues/3600)
* [Indent guides](https://github.com/Microsoft/vscode/issues/2192)
* Fast Search and Global Replace
* List of errors in a panel
* Multiple workspaces with fast switching
* [Integrated Terminal](https://github.com/Microsoft/vscode/issues/143)

## Improved Extension discovery and management 

We  want to make it easy for developers to discover extensions. Once you discovered we want to make it easy to manage them.

* New in product extension management experience
* Improved recommendation experience
* Support for "extension packs”, collections of extensions and settings
* Support to install an extension for `trial`, remind user whether they want to keep it. 
* Switching between "extension packs"
* Improved documentation to feature extensions and extension packs appropriately
* SDK: Improve extension README authoring and quality  
* Continue to improve the [Marketplace](https://marketplace.visualstudio.com/vscode) experience for discovering and installing extensions

## TypeScript, JavaScript, and Node development

We will continue to improve our code editing, navigation, and understanding experiences by partnering with the TypeScript team on the Salsa language service. 

* Work with the TypeScript team on the JavaScript language service which powers our JavaScript and TypeScript editing experiences to:
    * Automatic acquisition of .d.ts files to enable IntelliSense "out of the box"
    * Angular IntelliSense
    * Diagnostics on project configuration files (`jsconfig.json`, `tsconfig.json`)
* Node Debugger: Step over uninteresting (generated) code
* Improved npm support and help to keep the `package.json` consistent with the installed node modules

## Summary

These are examples of just some of the work we will be focusing on in the next 6 to 12 months. We will provide much more detail in each of our [monthly iteration plans](https://github.com/Microsoft/vscode/wiki/Iteration-Plans) so follow along and let us know what you think! 
