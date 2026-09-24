# How to Set Opacity in a Syncfusion Blazor Chart

## Overview

This sample demonstrates how to customize the transparency of a chart series in Syncfusion [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts). The implementation renders a `SplineArea` series using the `SfChart` component and applies transparency through the `ChartSeries.Opacity` property.

The sample binds a strongly typed collection of country-based data to the chart and displays the series using a semi-transparent green fill. Adjusting series opacity is useful when visualizing overlapping chart elements, improving readability, and highlighting important data without completely obscuring underlying chart content.

## Key Features

- Uses the `SfChart` component to render chart data.
- Configures a category-based X-axis using `ChartPrimaryXAxis`.
- Binds chart data through the `ChartSeries.DataSource` property.
- Maps category and value fields using `XName="X"` and `YName="Y"`.
- Demonstrates transparency customization using `ChartSeries.Opacity="0.5"`.
- Applies a custom series fill color using `Fill="Green"`.
- Renders the data as a `ChartSeriesType.SplineArea` series.
- Configures a visible series outline using `ChartSeriesBorder`.
- Sets the series border width using `Width="2"`.
- Sets the series border color using `Color="black"`.
- Uses a strongly typed `ChartData` model containing `X` and `Y` properties.
- Demonstrates how opacity values between `0` and `1` affect chart series appearance.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the following project file:

   `ChartOpacity/ChartOpacity.csproj`

3. Restore NuGet packages.
4. Build the project.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory:

```bash
cd ChartOpacity
```

5. Restore NuGet packages:

```bash
dotnet restore
```

6. Run the application:

```bash
dotnet run
```

7. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

`ChartOpacity/Pages/Index.razor` — Hosts the Blazor Chart sample, defines the `ChartData` model, initializes the chart data source, and demonstrates opacity customization through the `ChartSeries.Opacity` property.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for the `Opacity` property in Blazor Charts: https://help.syncfusion.com/chart-sdk/blazor/charts/chart-types/spline-area#series-customization

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.