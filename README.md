# McNeel Templates

Templates for creating plugins for Rhino and Grasshopper. Since McNeel only publishes templates for Visual Studio then
this repo is for those who uses a different IDE that doesn't support `.vsix` files.

## Plugin Documentation

* [Grasshopper](https://developer.rhino3d.com/guides/grasshopper/)
* [Rhino](https://developer.rhino3d.com/guides/rhinocommon/)

## Getting started with the templates

### Rider

[Source](https://www.jetbrains.com/help/rider/Creating_and_Opening_Projects_and_Solutions.html#managing-project-templates)

* Clone this repo
* In the New Project/New Solution dialog, click More Templates on the left, then click Install Template, and then choose a
the path to where you cloned this repo.
* When the path to the template appears in the list, click Reload.
* As soon as the template is installed, you can find it in the list on the left and use it to create new projects.


### dotnet CLI

```powershell
dotnet new --install $TEMPLATE_PATH
```