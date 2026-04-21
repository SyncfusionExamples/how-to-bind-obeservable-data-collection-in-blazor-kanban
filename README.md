# How to Bind Observable Data Collection in Blazor Kanban

A concise Blazor sample demonstrating how to bind an observable data collection to the Syncfusion Blazor Kanban component. The sample shows how the Kanban board automatically reflects additions, deletions, and updates when using an observable collection as the data source.

## Overview

Use this project to learn how to integrate `ObservableCollection<T>` (or similar observable patterns) with the Syncfusion Kanban component so UI updates occur automatically when the collection changes. This is useful for real-time updates or local in-memory editing scenarios.

Documentation: https://blazor.syncfusion.com/documentation/kanban/data-binding#observable-collection

Online examples: https://blazor.syncfusion.com/documentation/common/data-binding/data-updates#observable-collection

## Features

- Automatic UI updates when the data collection changes
- Examples for add, update, and delete operations bound to the Kanban board
- Pattern for integrating observable collections with Blazor and Syncfusion components

## Prerequisites

- Visual Studio 2022 (or later)
- The .NET SDK required by the solution

## Run the project

1. Clone the repository to a local folder.
2. Open the solution in Visual Studio 2022.
3. Restore NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Build and run the project from Visual Studio.

Optional CLI commands:

```powershell
dotnet restore
dotnet build
```

## Troubleshooting & support

If you encounter issues, confirm that packages are restored, the project builds, and the license key is registered correctly. For more details about Syncfusion components consult the Syncfusion Blazor documentation.
