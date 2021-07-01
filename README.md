# R Extension for Visual Studio Code

[![Badge](https://aka.ms/vsls-badge)](https://aka.ms/vsls)

This [VS Code](https://code.visualstudio.com/) extension provides support for the [R programming language](https://www.r-project.org), including features such as
extended syntax highlighting, interacting with R terminals, viewing data, plots, workspace variables, help pages, managing packages, and working with [R Markdown](https://rmarkdown.rstudio.com/) documents.

Go to the [wiki](https://github.com/REditorSupport/vscode-R/wiki) to view the documentation of the extension.

## Getting started

1. [Install R](https://cloud.r-project.org/) (>= 3.4.0) on your system. For Windows users, Writing R Path to the registry is recommended in the installation.

2. Install [`jsonlite`](https://github.com/jeroen/jsonlite) and [`rlang`](https://github.com/r-lib/rlang) packages in R.

    ```r
    install.packages(c("jsonlite", "rlang"))
    ```

3. Install the [R extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=REditorSupport.r).

4. Create an R file and start coding.

Note that the above steps only provide basic code editing functionalities and features of interacting with R sessions. To get full R development experience such as code completion, linting, formatting, debugging, etc., go to the installation wiki pages ([Windows](https://github.com/REditorSupport/vscode-R/wiki/Installation:-Windows) | [macOS](https://github.com/REditorSupport/vscode-R/wiki/Installation:-macOS) | [Linux](https://github.com/REditorSupport/vscode-R/wiki/Installation:-Linux)) for detailed instructions of installing the following recommended software and extensions:

* [radian](https://github.com/randy3k/radian): A modern R console that corrects many limitations of the official R terminal and supports many features such as syntax highlighting and auto-completion.

* [languageserver](https://github.com/REditorSupport/languageserver): An R package that implements the Language Server Protocol for R to provide a wide range of language analysis features such as auto-completion, function signature, documentation, symbol highlight, document outline, code formatting, symbol hover, diagnostics, go to definition, find references, etc.

* [vscode-r-lsp](https://marketplace.visualstudio.com/items?itemName=REditorSupport.r-lsp): A VS Code extension of R LSP Client to communicate between VS Code and R Language Server.

* [VSCode-R-Debugger](https://github.com/ManuelHentschel/VSCode-R-Debugger): A VS Code extension to support R debugging capabilities.

* [httpgd](https://github.com/nx10/httpgd): An R package to provide a graphics device that asynchronously serves SVG graphics via HTTP and WebSockets.

## Features

* Extended syntax highlighting for R, R Markdown, and R Documentation.

* Snippets for R and R Markdown.

* [Interacting with R terminals](https://github.com/REditorSupport/vscode-R/wiki/Interacting-with-R-terminals): Sending code to terminals, running multiple terminals, working with remote servers.

* [Package development](https://github.com/REditorSupport/vscode-R/wiki/Package-development): Build, test, install, load all and other commands from devtools.

* [Keyboard shortcuts](https://github.com/REditorSupport/vscode-R/wiki/Keyboard-shortcuts): Built-in and customizable keyboard shortcuts.

* [Workspace viewer](https://github.com/REditorSupport/vscode-R/wiki/Sidebar-user-interface#workspace-viewer): Environment pane to show global variables in the attached R session.

* [Help pages viewer](https://github.com/REditorSupport/vscode-R/wiki/Sidebar-user-interface#help-pages-viewer): Viewing R help pages and searching help topics.

* [Package management](https://github.com/REditorSupport/vscode-R/wiki/Sidebar-user-interface#package-management): Installing and removing R packages.

* Session symbol hover and completion.

* [Data viewer](https://github.com/REditorSupport/vscode-R/wiki/Interactive-viewers#data-viewer): Viewing `data.frame` or `matrix` in a grid or a list structure in a treeview.

* [Plot viewer](https://github.com/REditorSupport/vscode-R/wiki/Plot-viewer): PNG file viewer and SVG plot viewer based on [httpgd](https://github.com/nx10/httpgd).

* [Webpage viewer](https://github.com/REditorSupport/vscode-R/wiki/Interactive-viewers#webpage-viewer): Viewing [htmlwidgets](https://www.htmlwidgets.org) such as interactive graphics and [visual profiling results](https://rstudio.github.io/profvis/).

* [Browser viewer](https://github.com/REditorSupport/vscode-R/wiki/Interactive-viewers#browser-viewer): Viewing interactive [shiny](https://shiny.rstudio.com) apps.

* [R Markdown support](https://github.com/REditorSupport/vscode-R/wiki/R-Markdown): R Markdown chunk highlighting, chunk navigation, and execute commands.

* [RStudio add-in support](https://github.com/REditorSupport/vscode-R/wiki/RStudio-addin-support): Run supported RStudio add-ins in VS Code with a live R session.

* Full support of [Remote Development](https://code.visualstudio.com/docs/remote/remote-overview) via [SSH](https://code.visualstudio.com/docs/remote/ssh), [Containers](https://code.visualstudio.com/docs/remote/containers) and [WSL](https://code.visualstudio.com/docs/remote/wsl).

* [Live share collaboration](https://github.com/REditorSupport/vscode-R/wiki/Live-share-collaboration): Shared workspace, terminal, and viewer in R pair programming.

## Questions, issues, feature requests, and contributions

* If you have a question about accomplishing something in general with the extension, please [ask on Stack Overflow](https://stackoverflow.com/questions/tagged/visual-studio-code+r).

* If you find a problem or have a feature request with the extension, please [find out](https://github.com/REditorSupport/vscode-R/issues) if there is a current issue you may upvote or otherwise [file an issue](https://github.com/REditorSupport/vscode-R/issues/new/choose).

* Contributions are always welcome! Please see the [contributing guide](https://github.com/REditorSupport/vscode-R/wiki/Contributing) for more details.
