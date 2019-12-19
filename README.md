Visual Studio Workspaces for Alfred
============

A simple but useful Alfred workflow with VS Code Workspaces support.

![Visual Studio Workspaces for Alfred](https://repository-images.githubusercontent.com/115214026/adbf5a80-226d-11ea-9535-6b87689cf996)


Requirements
----------------
You have to install the `code` command line tool from VS Code.


Installation
----------------

- Download "VS Code Workspaces.alfredworkflow" extension by clicking the "raw" link.
- Double click the *.alfredextension file to install.


Instructions
----------------

code `<Project name>`


Credits
----------------

Thanks to [bigluck/alfred2-sublimeprojects](https://github.com/bigluck/alfred2-sublimeprojects) for most of the code and copy!


Fuzzy-ish type maching
----------------

Thanks to [natecavanaugh](https://github.com/natecavanaugh) contribute now are allowed a fuzzy-ish type matching of the names of projects; for instance, if you have 3 projects such as:

- dotfiles
- Liferay Dev
- Liferay Plugins

Typing `de` will give you `dotfiles` and `Liferay Dev`.
Typing `lfr` will give you both `Liferay Dev` and `Liferay Plugins`.
Typing `ldev` will give you just `Liferay Dev`.

This fits more with how fuzzy matching is done in Sublime and makes it really easy to select projects.
