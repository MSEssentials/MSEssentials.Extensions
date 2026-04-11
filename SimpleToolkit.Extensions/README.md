# SimpleToolkit.Extensions

### Set of helpers, class extensions, UI controls used in my other C# projects

SimpleToolkit is package of useful classes, helpers, extensions and UI controls, I use in my C# projects. Extensions subpackage contains classes extensions.

---

## NuGet registry status

| Subpackage                        | Status                                                                                                                                                                                                            |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **SimpleToolkit.Extensions**      | [![NuGet version (SimpleToolkit.Extensions)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.Extensions?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.extensions/)                            |
| SimpleToolkit.Attributes          | [![NuGet version (SimpleToolkit.Attributes)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.Attributes?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.attributes/)                            |
| SimpleToolkit.MVVM                | [![NuGet version (SimpleToolkit.MVVM)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.MVVM?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.mvvm/)                                              |
| SimpleToolkit.UI.Models           | [![NuGet version (SimpleToolkit.UI.Models)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.UI.Models?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.ui.models/)                               |
| SimpleToolkit.UI.WinUI.Behaviors  | [![NuGet version (SimpleToolkit.UI.WinUI.Behaviors)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.UI.WinUI.Behaviors?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.ui.winui.behaviors/)    |
| SimpleToolkit.UI.WinUI.Converters | [![NuGet version (SimpleToolkit.UI.WinUI.Converters)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.UI.WinUI.Converters?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.ui.winui.converters/) |
| SimpleToolkit.UI.WinUI.Controls   | [![NuGet version (SimpleToolkit.UI.WinUI.Controls)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.UI.WinUI.Controls?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.ui.winui.controls/)       |
| SimpleToolkit.UI.WinUI.Helpers    | [![NuGet version (SimpleToolkit.UI.WinUI.Helpers)](https://img.shields.io/gitea/v/release/SimpleToolkit/SimpleToolkit.UI.WinUI.Helpers?gitea_url=https%3A%2F%2Frepos.mateuszskoczek.com%2F&display_name=release&label=nuget)](https://repos.mateuszskoczek.com/SimpleToolkit/-/packages/nuget/simpletoolkit.ui.winui.helpers/)          |

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

To download package from organization package registry, you have to add new NuGet package source. You will need access details, which you can obtain by contacting the repository owner. You can also download .nupkg file from repository Releases page.

**CLI:**

```
dotnet nuget add source --name SimpleToolkit --username <username> --password <password> https://repos.mateuszskoczek.com/api/packages/SimpleToolkit/nuget/index.json
dotnet add package --source SimpleToolikt SimpleToolkit.Extensions
```

**Package reference in .csproj file:**

```
<PackageReference Include="SimpleToolkit.Extensions" Version="<version>" />
```

## Attribution and contribution

This project is open source on MIT License, so you can just copy and upload again to your repository. But according to the license, you must include information about the original author. You can find license [here](https://repos.mateuszskoczek.com/SimpleToolkit/SimpleToolkit.Extensions/src/branch/main/LICENSE).

However, the preferred way to contribute would be to propose improvements in a pull request, through issues, or through other means of communication.

**Other sources:**

- Icon by [Icons8](icons8.com)