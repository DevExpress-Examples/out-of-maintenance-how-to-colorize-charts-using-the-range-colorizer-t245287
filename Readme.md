<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568865/15.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T245287)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/RangeColorizerExample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/RangeColorizerExample/MainWindow.xaml))**
<!-- default file list end -->
# How to colorize charts using the Range Colorizer


This example demonstrates how to colorize the GDP bar chart by <a href="http://www.happyplanetindex.org/about/">HPI</a> using Range Colorizer.


<h3>Description</h3>

To use the Range Colorizer, perform the following steps.<br />-&nbsp;Create a <strong>RangeColorizer</strong> object and assign it to the <strong>Series.Colorizer</strong> property.<br />- Populate the <strong>RangeColorizer.RangeStops</strong> collection.<br />- Specify the <strong>ChartPaletteColorizerBase.Palette</strong> property if you want to use a non-default palette to colorize chart.<br />- In addition it is possible to specify the <strong>RangeColorizer.ValueProvider</strong> property to customize the way using to provide floating point number values based on color data member values.

<br/>


