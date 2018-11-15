<!-- default file list -->
*Files to look at*:

* **[MainPage.xaml](./CS/LoadShapefile/MainPage.xaml) (VB: [MainPage.xaml](./VB/LoadShapefile/MainPage.xaml))**
<!-- default file list end -->
# How to: Load vector data from Shapefile


This example demonstrates how to load vector data from Shapefile.


<h3>Description</h3>

To load vector data from Shapefile, do the following.<br />1. Create a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapVectorFileLayertopic">VectorFileLayer</a> object and add it&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapControl_Layerstopic">MapControl.Layers</a> collection.<br />2. Create an instance of the&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapShapefileReadertopic">ShapefileReader</a> class and assign&nbsp;the instance&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapVectorFileLayer_FileReadertopic">VectorFileLayer.FileReader</a> property.<br />3. Create&nbsp;a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapMapFileSourceBasetopic">MapFileSourceBase</a> class descendant object, configure it&nbsp;and assign to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapFileReaderBase_FileSourcetopic">FileSource</a> property of the instance.

<br/>


