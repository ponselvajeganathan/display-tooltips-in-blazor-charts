# Show Informative Tooltips in Blazor Charts

## Overview

This sample demonstrates how to display and customize tooltips in the Syncfusion Blazor Chart component. The application shows how tooltip information can be presented when users interact with chart data points and illustrates multiple customization approaches for improving the tooltip experience.

The sample demonstrates tooltip content formatting using HTML, custom tooltip templates, and visual styling options. It serves as a practical reference for developers who want to provide richer contextual information within Syncfusion Blazor Charts.

## Key Features

- Demonstrates tooltip support in Syncfusion Blazor Charts.
- Shows how tooltip information is displayed when interacting with chart data points.
- Demonstrates formatting tooltip content using HTML-based content.
- Demonstrates custom tooltip template rendering.
- Shows how tooltip appearance can be customized beyond the default presentation.
- Demonstrates tooltip border customization for improved visual styling.
- Uses Syncfusion Chart tooltip functionality to provide contextual information about chart data.
- Implements tooltip examples inside a hosted Blazor application with Client, Server, and Shared projects.
- Supports chart interaction scenarios where users need detailed information without permanently displaying data labels.

## Prerequisites

- Visual Studio 2022
- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `DisplayTooltip.sln`.
3. Restore all NuGet packages.
4. Set the hosted startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root containing the solution.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed after the application starts.

## Project Structure

- `Client/Pages/` — contains the Razor page implementing tooltip rendering, tooltip templates, and chart interaction scenarios.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see https://help.syncfusion.com/chart-sdk/blazor/charts/tool-tip

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.