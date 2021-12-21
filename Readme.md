# Tips

### settings.json

The [settings.json](settings.json) file is automatically taken by Visual Studio Code when opening root folder as project.

It creates a new compilation recipe so the makeindex package can work.

Due to how the compilation recipe works, compiling the secondary .tex files by their own does not work in Visual Studio Code.

To understand why this is necessary refer to:
[How to modify makeindex script in vs code for latex](https://stackoverflow.com/questions/58895384/how-to-modify-makeindex-script-in-vs-code-for-latex/70084011#70084011)


# To Do

### Images in between references

* Tried using notes field to \includegraphics, does not work
* Tried using []  for image position with custom scales for size, does not work
* Tried using [hbpt] for image position with custom scales for size, does not work





