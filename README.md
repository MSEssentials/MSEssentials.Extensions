<p align="center"><img src=".gitea/readme/icon.png"/></p>

<h1 align="center">SimpleToolkit.Extensions</h1>

<h3 align="center"><b>Set of helpers, class extensions, UI controls used in my other C# projects</b></h3>

<p align="center">SimpleToolkit is package of useful classes, helpers, extensions and UI controls, I use in my C# projects. Extensions subpackage contains classes extensions.</p>

---

## Informations

> [!Important]
> **For Github users:**
>
> This is only mirror repository. All changes are first uploaded to the repository <a href="https://repos.mateuszskoczek.com/SimpleToolkit/SimpleToolkit.Extensions">here</a>. Releases are also published on original repository. However, Github repository handles issues and pull requests for better accessibility.

## NuGet registry status

<table>
    <tr>
        <th>
            Subpackage
        </th>
        <th>
            Status
        </th>
    </tr>
    <tr>
        <td>
            <b>SimpleToolkit.Extensions</b>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.Extensions/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.Extensions.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th colspan=2>
            Other subpackages
        </th>
    </tr>
    <tr>
        <td>
            SimpleToolkit.Attributes
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.Attributes/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.Attributes.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.MVVM
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.MVVM/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.MVVM.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.UI.Models
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.UI.Models/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.UI.Models.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.UI.WinUI.Behaviors
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.UI.WinUI.Behaviors/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.UI.WinUI.Behaviors.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.UI.WinUI.Converters
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.UI.WinUI.Converters/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.UI.WinUI.Converters.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.UI.WinUI.Controls
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.UI.WinUI.Controls/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.UI.WinUI.Controls.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <td>
            SimpleToolkit.UI.WinUI.Helpers
        </td>
        <td>
            <a href="https://www.nuget.org/packages/SimpleToolkit.UI.WinUI.Helpers/"><img src="https://img.shields.io/nuget/v/SimpleToolkit.UI.WinUI.Helpers.svg?style=flat-square"></a>
        </td>
    </tr>
</table>

## Features

- **StringExtensions**
    - *(static)* **CreateRandom** - returns random string
    - **Shuffle** - returns shuffled string
- **HttpClientExtensions**
    - **DownloadAsync** - allows to track progress of downloading data
- **StreamExtensions**
    - **CopyToAsync** - allows to track progress of copying data
- **IEnumerableExtensions**
    - **Random** - returns random item from IEnumerable

## Installation and usage

You can download package from official NuGet registry or .nupkg file itself from Releases tab.

**CLI:**

```
dotnet add package SimpleToolkit.Extensions
```

**Package reference in .csproj file:**

```
<PackageReference Include="SimpleToolkit.Extensions" Version="<version>" />
```

## Attribution and contribution

This project is open source on MIT License, so you can just copy and upload again to your repository. But according to the license, you must include information about the original author. You can find license <a href="https://repos.mateuszskoczek.com/SimpleToolkit/SimpleToolkit.Extensions/src/branch/main/LICENSE">here</a>.

However, the preferred way to contribute would be to propose improvements in a pull request, through issues, or through other means of communication.

**Other sources:**

- Icon by <a href="icons8.com">Icons8</a>