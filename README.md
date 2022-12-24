## *** this is a work-in-progress ***

# SpreadsheetGear code samples for Visual Studio Code

This repository contains [SpreadsheetGear](https://www.spreadsheetgear.com/) code samples for .NET6 WPF, .NET6 Windows Forms, ASP.NET Core, Python 3 and Jupyter Notebook applications. 

[Visual Studio Code (VSCode)](https://code.visualstudio.com/) is a source code editor for Windows, Linux and MacOS. This repository is based on a fork of [SpreadsheetGear/SpreadsheetGearExplorerSamples](https://github.com/SpreadsheetGear/SpreadsheetGearExplorerSamples) which was developed using Visual Studio 2022 on Windows. Changes for the folder-centric VSCode include workspace files (.code-workspace) for all code samples, and new Jupyter Notebook and Python code samples.

**These SpreadsheetGear code samples will run in Visual Studio Code on Windows, MacOS and Linux unless *"Windows only"* is indicated.**

* [Samples_WebCSharp](docs/Samples_WebCSharp.md) - Contains C# sample code in a ASP.NET Core web app
* Samples_WebPython - Contains Python 3 sample code in a Python and Flask web app
* Samples_JupyterCSharp - Contains .NET 6.0 C# sample code in Jupyter notebooks
* Samples_JupyterPython - Contains Python 3 sample code in Jupyter notebooks
* [Samples_WindowsForms](docs/Samples_WindowsForms.md) - Contains .NET 6.0 C# sample code for Windows Forms ***(Windows only)***
* [Samples_WindowsWPF](docs/Samples_WindowsWPF.md) - Contains .NET 6.0 C# sample code for WPF ***(Windows only)***

# Get Started #
  1. [SpreadsheetGear Nuget packages used in these demos](#spreadsheetgear-nuget-packages-used-in-these-demos)
  2. [Install Visual Studio Code and Python on Windows, Linux or MacOS](#visual-studio-code-installation)
  3. [Open and run SpreadsheetGear code samples in Visual Studio Code](#open-and-run-spreadsheetgear-code-samples-in-visual-studio-code)

# SpreadsheetGear Nuget packages used in these demos
The code samples in this repository demonstrates a wide variety of APIs and features from these SpreadsheetGear Nuget packages:
*   **[SpreadsheetGear Engine for .NET](https://www.nuget.org/packages/SpreadsheetGear/9.1.19-beta)** - the primary SpreadsheetGear library that provides a core set of APIs to read, write, manipulate and calculate workbooks, build charts, format worksheets and cells, and more.
*   **[SpreadsheetGear for Windows](https://www.nuget.org/packages/SpreadsheetGear.Windows/9.1.19-beta)** - builds on SpreadsheetGear Engine for .NET to add powerful Excel-compatible image rendering, viewing, editing, formatting, calculating, filtering, sorting, charting, printing and more to your Windows Forms and WPF applications with the easy-to-use WorkbookView and FormulaBar controls.

Learn more about these products on our [Features Page](https://www.spreadsheetgear.com/Products/Features) and more details on their diffences on our [Comparison Page](https://www.spreadsheetgear.com/Products/Compare).

# Visual Studio Code and Python installation

*These instructions should work for Windows, MacOS and Linux*

1. From [Download .NET](https://dotnet.microsoft.com/en-us/download)
    - Install the .NET 6.0 SDK - *required for SpreadsheetGear code samples*
    - Install the .NET 7.0 SDK - *required for .NET Extension Pack for Visual Studio Code*
2. Install [Visual Studio Code](https://code.visualstudio.com/)
3. Install [.NET Extension Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)
    - Ignore the "Getting Started with .NET" prompt to "Install .NET SDK". You already installed it in step 1.
4. Install [Git version control](https://git-scm.com/download)
5. For Python code samples 
    - Install [Python](https://www.python.org/) or a "conda" installer like [Anaconda](https://www.anaconda.com/products/distribution) or [MiniConda](https://docs.conda.io/en/latest/miniconda.html) which include Python
    - Install [Python Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    - *Optional -* [Create a Python Virtual Environment](https://code.visualstudio.com/docs/python/environments) for running SpreadsheetGear Python code samples in VSCode.
    

# Open and run SpreadsheetGear code samples in Visual Studio Code
1. Clone this repo into your target folder.

```
Windows command line example:
C:\temp>git clone https://github.com/tracktownsoftware/SpreadsheetGearCodeSamples_VSCode.git
```
2. Run Visual Studio Code and select "File | Open workspace from File..." to open a code workspace file (.code-workspace) from your local SpreadsheetGearCodeSamples_VSCode folder:
    - **[Samples_WebCSharp.code-workspace](docs/Samples_WebCSharp.md)**
    - Samples_WebPython.code-workspace
    - Samples_JupyterCSharp.code-workspace
    - Samples_JupyterPython.code-workspace
    - **[Samples_WindowsForms.code-workspace](docs/Samples_WindowsForms.md)**
    - **[Samples_WindowsWPF.code-workspace](docs/Samples_WindowsWPF.md)**

3. **For additional instructions specific to a code workspace, click on its link in Step 2 above.**

