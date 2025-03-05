[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-orange.svg)](https://sonarcloud.io/summary/new_code?id=nagyzekkyandras_vscode-terminal)

[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=nagyzekkyandras_vscode-terminal&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=nagyzekkyandras_vscode-terminal)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=nagyzekkyandras_vscode-terminal&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=nagyzekkyandras_vscode-terminal)

![Build Status](https://github.com/nagyzekkyandras/vscode-terminal/actions/workflows/build.yml/badge.svg)

# Terminal

Run terminal command directly in Text Editor

## Notice
Forked from [formulahendry/vscode-terminal](https://github.com/formulahendry/vscode-terminal).


Marketplace: https://marketplace.visualstudio.com/items?itemName=nagyzekkyandras.basic-terminal

## Features

* Run all the commands in Text Editor
* Run the selected commands in Text Editor
* Stop the running commands
* View output in Output Window
* Open Integrated Terminal at current file's directory
* Quick way to toggle Integrated Terminal

## Usages

* Write or select a set of commands in Text Editor, then use shortcut `Ctrl+Alt+R`, or press `F1` and then select/type `Run Terminal Command`, the commands will run and the output will be shown in the Output Window.
* To stop the running commands, use shortcut `Ctrl+Alt+C`, or press `F1` and then select/type `Stop Terminal Command`

![Usage](images/usage.gif)

* To open Integrated Terminal at current file's directory, use shortcut `Ctrl+Alt+O`, or press `F1` and then select/type `Open in Integrated Terminal`, or right click in Text Editor/Explorer and then click `Open in Integrated Terminal` in context menu

![Open](images/open.gif)

* To toggle Integrated Terminal, use shortcut `Ctrl+Alt+T`, or click the `Terminal` icon in the Status Bar at the bottom

![Toggle](images/toggle.png)

## Change Log
### 0.1.1 (2024-06-17)
* Bump @types/node from 20.14.1 to 20.14.2
* Bump @types/vscode from 1.89.0 to 1.90.0

### 0.1.0 (2024-06-04)
* Dependency updates
* Removed application-insights

### 0.0.10 (2017-07-22)
* [#10](https://github.com/formulahendry/vscode-terminal/issues/10): Handle case-insensitive bash path

### 0.0.9 (2017-07-20)
* [#9](https://github.com/formulahendry/vscode-terminal/issues/9): Open terminal for Bash on Windows

### 0.0.8 (2017-05-15)
* Quick way to toggle Integrated Terminal in the Status Bar

### 0.0.7
* Add 'Open in Integrated Terminal' context menu

### 0.0.6
* Upgrade applicationinsights npm since [telemetry data requires HTTPS](https://azure.microsoft.com/en-us/updates/application-insights-telemetry-data-now-requires-https-with-shutdown-of-http-data-collectors/)

### 0.0.5
* Add Application Insights to track telemetry data

### 0.0.4
* Update the future of this extension

### 0.0.3
* Add support to stop running commands

### 0.0.2
* Update README.md and add GitHub info

### 0.0.1
* Initial Release
