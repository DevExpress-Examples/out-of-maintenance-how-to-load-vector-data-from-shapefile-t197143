<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128572287/14.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T197143)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainPage.xaml](./CS/LoadShapefile/MainPage.xaml) (VB: [MainPage.xaml](./VB/LoadShapefile/MainPage.xaml))**
<!-- default file list end -->
# How to: Load vector data from Shapefile


This example demonstrates how to load vector data from Shapefile.


<h3>Description</h3>

To load vector data from Shapefile, do the following.<br />1. Create a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapVectorFileLayertopic">VectorFileLayer</a> object and add it&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapControl_Layerstopic">MapControl.Layers</a> collection.<br />2. Create an instance of the&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapShapefileReadertopic">ShapefileReader</a> class and assign&nbsp;the instance&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapVectorFileLayer_FileReadertopic">VectorFileLayer.FileReader</a> property.<br />3. Create&nbsp;a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapMapFileSourceBasetopic">MapFileSourceBase</a> class descendant object, configure it&nbsp;and assign to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapFileReaderBase_FileSourcetopic">FileSource</a> property of the instance.

<br/>


