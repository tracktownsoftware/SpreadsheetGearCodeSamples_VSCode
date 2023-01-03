# Get Started #
  1. [SpreadsheetGear Nuget packages used in these demos](../README.md#get-started)
  2. [Install Visual Studio Code on Windows, Linux or MacOS](../README.md#visual-studio-code-installation)
  3. Use Git to clone this repository

# C# Jupyter Notebooks in Samples_JupyterCSharp #
- [JupyterCSharp_HelloWorld.ipynb](../Samples_JupyterCSharp/JupyterCSharp_HelloWorld.ipynb)
- [CSharpExcelToolsComparison.ipynb](../Samples_JupyterCSharp/CSharpExcelToolsComparison.ipynb)
- [JupyterCSharp_Part1_Workbook.ipynb](../Samples_JupyterCSharp/JupyterCSharp_Part1_Workbook.ipynb)

*Note: Viewing the above Jupyter notebooks on GitHub will present a static HTML view. To use them interactively you need to open them in a Jupyter notebook editor like Visual Studio Code.*

# Open Samples_JupyterCSharp notebooks interactively in VSCode #
1. Run Visual Studio Code and select "File | Open workspace from File...".
2. Navigate to your local **SpreadsheetGearCodeSamples_VSCode folder** and open **Samples_JupyterCSharp.code-workspace**
3. You should see Samples_JupyterCSharp.code-workspace open in Visual Studio Code (VS Code).
4. Show the VSCode Explorer by clicking its icon in the upper left.
5. Use VSCode explorer to double-click and open the Jupyter notebook you want to see.

# What are Jupyter Notebooks? #

A Jupyter Notebook is a document for creating and sharing live code, equations, visualizations, and text.

The history of Jupyter Notebooks in Visual Studio Code:
- Visual Studio Code has long supported Python Jupyter Notebooks and Python code
- In 2019 an additional .NET based Jupyter kernel was introduced and supported C#, F#, and Powershell
- Today the current .NET Interactive kernel supports C#, F#, Powershell, Javascript, SQL, KQL, HTML and Mermaid.
- You can mix language cells in the same .NET Interactive kernel notebook. Variable sharing is supported across code for C#, F#, Powershell, Javascript, SQL and KQL.

Jupyter notebooks with C# code are known by different names

- In this repo I use the term "C# Jupyter notebooks" for notebooks that contain C# code. 
- Another term is ".NET Interactive" notebook because notebooks with C# use the ".NET Interactive" Jupyter kernel.
- The latest term is "Polygot" notebook. Microsoft renamed the Visual Studio Code extension to [Polygot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) from the former ".NET Interactive Notebooks" extension.

# Make your Jupyter notebook Python or .NET Interactive (C#) #
1. In VSCode add a new file with the ".ipynb" extension 
2. Open the notebook in VSCode
3. The active Jupyter notebook kernel will show in the upper right (A in the image below). Click on it if you want to change the kernel.
4. After clicking the active kernel you should see other kernel options (B in the image below). If you want a C# Jupyter notebook then select .Net Interactive as the kernel.

![Image](images/ChangeNotebookKernel.jpg)

# Useful links #
- [Polygot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)
- [.NET Interactive Notesbooks is now Polygot Notebooks](https://devblogs.microsoft.com/dotnet/dotnet-interactive-notebooks-is-now-polyglot-notebooks/)
- [.NET Interactive Notebooks for C#](https://github.com/dotnet/csharp-notebooks)



