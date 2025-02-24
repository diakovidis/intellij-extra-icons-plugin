<h1 align="center">
    Extra Icons
</h1>

<p align="center">
    <a href="https://travis-ci.org/jonathanlermitage/intellij-extra-icons-plugin"><img src="https://travis-ci.org/jonathanlermitage/intellij-extra-icons-plugin.svg?branch=master"/></a>
    <a href="https://plugins.jetbrains.com/plugin/11058-extra-icons"><img src="https://img.shields.io/jetbrains/plugin/v/11058-extra-icons.svg"/></a>
    <a href="https://plugins.jetbrains.com/plugin/11058-extra-icons"><img src="https://img.shields.io/jetbrains/plugin/d/11058-extra-icons.svg"/></a>
    <a href="https://github.com/jonathanlermitage/intellij-extra-icons-plugin/blob/master/LICENSE.txt"><img src="https://img.shields.io/github/license/jonathanlermitage/intellij-extra-icons-plugin.svg"/></a>
</p>

Intellij IDEA (Community and Ultimate) plugin that adds icons for files like Travis YML, Appveyor YML, etc.  
Starting from version 0.4, it works with all JetBrains products like WebStorm, DataGrip, etc.

Download plugin on [GitHub](https://github.com/jonathanlermitage/intellij-extra-icons-plugin/releases), [JetBrains Plugins Repository](https://plugins.jetbrains.com/plugin/11058-extra-icons) or via IntelliJ IDEA (<kbd>File</kbd>, <kbd>Settings</kbd>, <kbd>Plugins</kbd>, <kbd>Browse repositories...</kbd>).

## Author

Jonathan Lermitage (<jonathan.lermitage@gmail.com>)  
Linkedin profile: [jonathan-lermitage-092711142](https://www.linkedin.com/in/jonathan-lermitage-092711142/)

## Contributors

* Edoardo Luppi (<lp.edoardo@gmail.com>)
* Matthias Kunnen ([github.com/MatthiasKunnen](https://github.com/MatthiasKunnen))

## Build

### Gradle commands

* build plugin: `./gradlew buildPlugin`. See generated jar: `build/libs/ij-extra-icons-x.y.z.183.jar`.
* run IDE with plugin: `./gradlew runIde`.
* check for dependencies updates: `./gradlew dependencyUpdates -Drevision=release -DoutputFormatter=plain -DoutputDir=./build/`.

### Branches

* [master](https://github.com/jonathanlermitage/intellij-extra-icons-plugin): plugin is compatible with 183.0+ IDE builds (2018.3 and newer).
* [ide173](https://github.com/jonathanlermitage/intellij-extra-icons-plugin/tree/ide173): plugin is compatible with 173.0+ IDE builds (2017.3 and newer), but doesn't support AngularJS icons.

## Contribution

Open an issue or a pull-request. Contributions should be tested on both [master](https://github.com/jonathanlermitage/intellij-extra-icons-plugin) and [ide173](https://github.com/jonathanlermitage/intellij-extra-icons-plugin/tree/ide173) branches, unless your code targets 183.0+ IDE builds.    
Please reformat new and modified code only: do not reformat the whole project or entire existing file (in other words, try do limit the amount of changes in order to speed up code review).

## License

MIT License. In other words, you can do what you want: this project is entirely OpenSource, Free and Gratis.

## Screenshot

![Dark Screenshot](misc/screenshots/intellijidea-ce_dark.png)

![Screenshot](misc/screenshots/intellijidea-ce.png)

![Config Panel Screenshot](misc/screenshots/config-panel.png)
