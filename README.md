# Create a Line Chart showing U.S. Egg Prices more than Twice in 2022

The national average price for a dozen large Grade A eggs has more than doubled from $1.93 in January to $4.25 in December 2022. This sample demonstrates how to create a line chart in .NET MAUI (SfCartesianChart) showing U.S. egg prices more than twice in 2022.

## Line chart customization

The [StrokeDashArray](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.Charts.LineSeries.html#Syncfusion_Maui_Charts_LineSeries_StrokeDashArray) property of LineSeries is used to render the line series with dashes. Odd value is considered as rendering size and even value is considered as gap.

## Line data marker customization

We can customize the series markers appearance by creating an instance of the [MarkerSettings](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.Charts.LineSeries.html#Syncfusion_Maui_Charts_LineSeries_MarkerSettings) property.

## Plot area customization for line chart 

SfCartesianChart allows you to add any view to the chart plot area using [PlotAreaBackgroundView](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.Charts.ChartBase.html#Syncfusion_Maui_Charts_ChartBase_PlotAreaBackgroundView) property, which is useful for adding any relevant data, a watermark, or a color gradient to the background of the chart

![line-chart](https://github.com/syncfusion-content/winui-docs/assets/105482474/d8d86ebe-6528-482a-b598-e2ad1f58019b)

For a step by step procedure, refer to the [U.S Egg Prices Chart](https://www.syncfusion.com/blogs/post/dotnet-maui-line-chart-visualize-egg-price.aspx).
