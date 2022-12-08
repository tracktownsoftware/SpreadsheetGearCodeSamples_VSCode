## *** this is a work-in-progress ***

# SpreadsheetGear sample code for Visual Studio Code

This repository contains SpreadsheetGear sample code for .NET6 WPF, .NET6 Windows Forms, ASP.NET Core, and Jupyter Notebook applications. 

Visual Studio Code (VSCode) is a source code editor for Windows, Linux and MacOS. This repository is based on a fork of [SpreadsheetGear/SpreadsheetGearExplorerSamples](https://github.com/SpreadsheetGear/SpreadsheetGearExplorerSamples) which was developed using Visual Studio 2022 on Windows. Sample code has been simplified for VSCode with one solution file (.sln) per folder and only one possible startup project (.csproj) per solution.

* **Sample code for SpreadsheetGear in Visual Studio Code on Windows:**
  *   [SpreadsheetGearExplorerSamples_WPF](/SpreadsheetGearExplorerSamples_WPF) - Contains C# sample code for WPF.
  *   [SpreadsheetGearExplorerSamples_WindowsForms](/SpreadsheetGearExplorerSamples_WindowsForms) - Contains C# sample code for Windows Forms.
* **Sample code for SpreadsheetGear in Visual Studio Code on Windows, Linux and MacOS:**
  *   [SpreadsheetGearExplorerSamples_Web](/SpreadsheetGearExplorerSamples_Web) - Contains sample code for ASP.NET Core Razor Pages.
  *   SpreadsheetGearSampleCode_JupyterCSharp - Contains Jupyter notebook C# sample code
  *   SpreadsheetGearSampleCode_JupyterPython - Contains Jupyter notebook Python sample code

## Get Started ##
* [SpreadsheetGear Nuget packages used in these demos](#spreadsheetgear-nuget-packages-used-in-these-demos)
* [Install Visual Studio Code on Windows, Linux or MacOS](#visual-studio-code-installation)
* [Open and run SpreadsheetGear sample code in Visual Studio Code](#open-and-run-spreadsheetgear-sample-code-in-visual-studio-code)

## SpreadsheetGear Nuget packages used in these demos
The sample code in this repository demonstrates a wide variety of APIs and features from these SpreadsheetGear Nuget packages:
*   **[SpreadsheetGear Engine for .NET](https://www.nuget.org/packages/SpreadsheetGear/9.1.19-beta)** - the primary SpreadsheetGear library that provides a core set of APIs to read, write, manipulate and calculate workbooks, build charts, format worksheets and cells, and more.
*   **[SpreadsheetGear for Windows](https://www.nuget.org/packages/SpreadsheetGear.Windows/9.1.19-beta)** - builds on SpreadsheetGear Engine for .NET to add powerful Excel-compatible image rendering, viewing, editing, formatting, calculating, filtering, sorting, charting, printing and more to your Windows Forms and WPF applications with the easy-to-use WorkbookView and FormulaBar controls.

Learn more about these products on our [Features Page](https://www.spreadsheetgear.com/Products/Features) and more details on their diffences on our [Comparison Page](https://www.spreadsheetgear.com/Products/Compare).

## Visual Studio Code installation
**For Windows:**
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [.NET Extension Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)
  * The .NET Extension pack includes:
    * [C# for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
    * Jupyter Notebooks
* Install the [.NET SDK](https://dotnet.microsoft.com/en-us/download) (SpreadsheetGear requires .NET 6.0 or greater)
* Install [Git for Windows](https://git-scm.com/download/win)
* *Optional* - Install [GitLens to "Supercharge Git within VS Code"](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

**For MacOS:**
* work-in-progress

**For Linux:**
* work-in-progress

## Open and run SpreadsheetGear sample code in Visual Studio Code
**1. Clone this repo into your target folder (I'll use "temp")**

```
Windows command line example:
C:\temp>git clone https://github.com/tracktownsoftware/SpreadsheetGearExplorerSamples_VSCode.git
```
    
**2. In Visual Studio Code open and run the sample code folder you are interested in:**

- **Sample code for Windows only**
  - Open and run SpreadsheetGearExplorerSamples_WPF
  - Open and run SpreadsheetGearExplorerSamples_WindowsForms

- **Sample code for Windows, Linux and MacOS**
  - Open and run SpreadsheetGearExplorerSamples_Web
  - Open and run SpreadsheetGearSampleCode_JupyterCSharp
  - Open and run SpreadsheetGearSampleCode_JupyterPython
