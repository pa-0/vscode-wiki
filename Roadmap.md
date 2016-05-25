# Roadmap

VS Code is off to a great start, thanks to you. As of May 2016 we've had over 2.3MM downloads and now more than 650K users in the last month. We're just getting started though, we want VS Code to be the editor of choice for any language and any platform.

With the "1.0" release behind us, now is a good time to look towards the future. We typically look out 6 to 12 months, establish a set of themes we want to work towards, and then schedule work each milestone supporting those themes. VS Code will continue to ship monthly and we'll make progress against each of the following themes during each iteration.

## Getting to “WOW!"

When you try VS Code for the first time, we want you to have a "WOW!" experience within minutes.

It should be quick and natural to customize the tool to the way you work. You should be able to quickly get started with your code, whether it is on your local drive or on GitHub. You should be able to get great [IntelliSense](https://en.wikipedia.org/wiki/Intelligent_code_completion), and you should be able to navigate and reason about your entire codebase without having to configure the tool. You should be able to press F5 and debug your application, again without lengthy configuration.  

Give us 5 minutes and we'll give you a new favorite development tool.

### WOW! Examples

* Configure key bindings, themes, common settings on first run of VS Code
* Ability to create new Workspaces from within VS Code
* "Open in VS Code" from a git repository
* Setting "Packs" for common settings (key bindings, extensions, etc.)
* Installation improvements such as auto move to Applications on OSX, Linux auto-update, and in product release notes

## Eliminate Adoption Blockers

Often we hear "If Code just had [blank], it would be my primary development tool!".

VS Code is a young product and there still are a few, yet critical, missing features and experiences that we want to deliver. If you want tabs, you should be able to have tabs. If you want to see four files horizontally or vertically, you should be able to that as well.

We want to make sure there aren't any gaps preventing VS Code from becoming your favorite editor.

### Adoption Blocker Examples

* [Tabs](https://github.com/Microsoft/vscode/issues/224) and window management (e.g. horizontal split)
* [VIM style key binding](https://github.com/Microsoft/vscode/issues/3600)
* [Indent guides](https://github.com/Microsoft/vscode/issues/2192)
* Fast Search and Global Replace
* Error List
* Multiple workspaces with fast switching
* [Integrated Terminal](https://github.com/Microsoft/vscode/issues/143)


## Accelerate the Ecosystem 

If VS Code is easy to configure and has all the features you expect, it still is not very useful unless it supports the language or framework **you** are developing for.

It isn't possible for the VS Code team to build every language experience. Our job is to provide the platform on which the ecosystem can build those experiences. We want to enable the domain experts for Swift, Ruby, or one of the many popular languages today to be able to build the best end-to-end experiences in VS Code.

We also want to make it easy for developers to discover all of the great extensions in the ecosystem. When you start VS Code and open your Go sources, you should be guided to install the right extensions and quickly get to "WOW!".

### Ecosystem Examples

* In product extension management and recommendation experiences
* Support for "extension packs”, collections of extensions and settings 
* Fast switching between "extension packs"
* Improved documentation to feature extensions and extension packs appropriately
* SDK: Improve extension README authoring and quality  
* Expand the core VS Code extensibility APIs, for example source code control 
* Continue to improve the [Marketplace](https://marketplace.visualstudio.com/vscode) experience for discovering and installing extensions
* For partners we will make it easy to consume and ship the stand-alone "Monaco" editor

## Full Stack Web + Node Development Experiences

VS Code's "native" language and platform experiences are targeted at building full stack web and node applications using JavaScript and TypeScript. Much of this is a result of the fact that we use VS Code to build VS Code, and VS Code itself is a modern web and Node based application hosted inside the cross platform Electron shell.

We want VS Code to be the best tool for doing Web and Node development. We will continue to improve our code editing, navigation, and understanding experiences by partnering with the TypeScript team on the Salsa language service. We will continue to expand our diagnostics capabilities and partner with the Visual Studio diagnostics team on bringing additional capabilities to not only Node debugging, but for all languages that plug into Code.

### Full Stack + Node Examples

* Work with the TypeScript team on the Salsa language service which powers our JavaScript and TypeScript editing experiences to:
    * Automatic detection of .d.ts files to enable IntelliSense "out of the box"
    * Angular IntelliSense
    * Diagnostics on project configuration files (`jsconfig.json`, `tsconfig.json`)
* Node Debugger: Step over uninteresting (generated) code
* Improved npm support and help to keep the `package.json` consistent with the installed node modules

## Summary

These are examples of just some of the work we will be focusing on in the next 6 to 12 months. We will provide much more detail in each of our [monthly iteration plans](https://github.com/Microsoft/vscode/wiki/Iteration-Plans) so follow along and let us know what you think! 
