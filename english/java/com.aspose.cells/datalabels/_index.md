---
title: DataLabels
second_title: Aspose.Cells for Java API Reference
description: Encapsulates a collection of all the DataLabel objects for the specified Series.
type: docs
weight: 155
url: /java/com.aspose.cells/datalabels/
---

**Inheritance:**
java.lang.Object, [com.aspose.cells.ChartFrame](../../com.aspose.cells/chartframe), [com.aspose.cells.ChartTextFrame](../../com.aspose.cells/charttextframe)
```
public class DataLabels extends ChartTextFrame
```

Encapsulates a collection of all the DataLabel objects for the specified Series.

```
//Set the DataLabels in the chart
         Workbook wb = new Workbook("chart.xlsx");
         Chart chart = wb.getWorksheets().get(0).getCharts().get(0);
         DataLabels datalabels;
         for (int i = 0; i  <chart.getNSeries().getCount(); i++)
         {
             datalabels = chart.getNSeries().get(i).getDataLabels();
             //Set the position of DataLabels
             datalabels.setPosition(LabelPositionType.INSIDE_BASE);
             //Show the category name in the DataLabels
             datalabels.setShowCategoryName(true);
             //Show the value in the DataLabels
             datalabels.setShowValue(true);
             //Not show the percentage in the DataLabels
             datalabels.setShowPercentage(false);
             //Not show the legend key.
             datalabels.setShowLegendKey(false);
         }
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabels()](#DataLabels--) |  |
## Methods

| Method | Description |
| --- | --- |
| [characters(int startIndex, int length)](#characters-int-int-) | Returns a Characters object that represents a range of characters within the text. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Gets the [Area](../../com.aspose.cells/area). |
| [getAutoScaleFont()](#getAutoScaleFont--) | True if the text in the object changes font size when the object size changes. |
| [getBackground()](#getBackground--) | Gets and sets the display mode of the background NOTE: This member is now obsolete. |
| [getBackgroundMode()](#getBackgroundMode--) | Gets and sets the display mode of the background |
| [getBorder()](#getBorder--) | Gets the [Line](../../com.aspose.cells/line). |
| [getChart()](#getChart--) | Gets the chart to which this object belongs. |
| [getClass()](#getClass--) |  |
| [getDefaultHeight()](#getDefaultHeight--) | Represents height of default position |
| [getDefaultWidth()](#getDefaultWidth--) | Represents width of default position |
| [getDefaultX()](#getDefaultX--) | Represents x of default position |
| [getDefaultY()](#getDefaultY--) | Represents y of default position |
| [getDirectionType()](#getDirectionType--) | Gets and sets the direction of text. |
| [getFont()](#getFont--) | Gets the font of the DataLabels; |
| [getHeight()](#getHeight--) | Gets or sets the height of frame in units of 1/4000 of the chart area. |
| [getLinkedSource()](#getLinkedSource--) | Gets and sets a reference to the worksheet. |
| [getNumber()](#getNumber--) | Gets and sets the built-in number format. |
| [getNumberFormat()](#getNumberFormat--) | Represents the format string for the DataLabels object. |
| [getNumberFormatLinked()](#getNumberFormatLinked--) | True if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells). |
| [getPosition()](#getPosition--) | Represents the position of the data label. |
| [getReadingOrder()](#getReadingOrder--) | Represents text reading order. |
| [getRotationAngle()](#getRotationAngle--) | Represents text rotation angle. |
| [getSeparator()](#getSeparator--) | Gets or sets the separator type used for the data labels on a chart. |
| [getSeparatorType()](#getSeparatorType--) | Gets or sets the separator type used for the data labels on a chart. |
| [getSeparatorValue()](#getSeparatorValue--) | Gets or sets the separator value used for the data labels on a chart. |
| [getShadow()](#getShadow--) | True if the frame has a shadow. |
| [getShapeProperties()](#getShapeProperties--) | Gets the [getShapeProperties()](../../com.aspose.cells/chartframe\#getShapeProperties--) object. |
| [getShapeType()](#getShapeType--) | Gets or sets shape type of data label. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Represents a specified chart's data label percentage value display behavior. |
| [getShowCategoryName()](#getShowCategoryName--) | Represents a specified chart's data label category name display behavior.True to display the category name for the data labels on a chart. |
| [getShowCellRange()](#getShowCellRange--) | Indicates whether showing cell range as the data labels. |
| [getShowLegendKey()](#getShowLegendKey--) | Represents a specified chart's data label legend key display behavior. |
| [getShowPercentage()](#getShowPercentage--) | Represents a specified chart's data label percentage value display behavior. |
| [getShowSeriesName()](#getShowSeriesName--) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. |
| [getShowValue()](#getShowValue--) | Represents a specified chart's data label values display behavior. |
| [getText()](#getText--) | Gets or sets the text of data label. |
| [getTextDirection()](#getTextDirection--) | Represents text reading order. |
| [getTextFont()](#getTextFont--) | Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Gets and sets the text horizontal alignment. |
| [getTextOptions()](#getTextOptions--) | Gets and sets the options of the text. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Gets or sets the text vertical alignment of text. |
| [getWidth()](#getWidth--) | Gets or sets the width of frame in units of 1/4000 of the chart area. |
| [getX()](#getX--) | Gets or sets the x coordinate of the upper left corner in units of 1/4000 of the chart area. |
| [getY()](#getY--) | Gets or sets the y coordinate of the upper left corner in units of 1/4000 of the chart area. |
| [hashCode()](#hashCode--) |  |
| [isAutoText()](#isAutoText--) | Indicates the text is auto generated. |
| [isAutomaticSize()](#isAutomaticSize--) | Indicates whether the chart frame is automatic sized. |
| [isDefaultPosBeSet()](#isDefaultPosBeSet--) | Indicates whether default position(DefaultX, DefaultY, DefaultWidth and DefaultHeight) are set. |
| [isDeleted()](#isDeleted--) | Indicates whether this data labels is deleted. |
| [isInnerMode()](#isInnerMode--) | Indicates whether the size of the plot area size includes the tick marks, and the axis labels. |
| [isNeverOverlap()](#isNeverOverlap--) | Indicates whether the datalabels display never overlap. |
| [isResizeShapeToFitText()](#isResizeShapeToFitText--) | Gets or sets whether a shape should be auto-fit to fully contain the text described within it. |
| [isTextWrapped()](#isTextWrapped--) | Gets or sets a value indicating whether the text is wrapped. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoScaleFont(boolean value)](#setAutoScaleFont-boolean-) | Please see the getter of this property: [getAutoScaleFont()](../../com.aspose.cells/chartframe\#getAutoScaleFont--) |
| [setAutoText(boolean value)](#setAutoText-boolean-) | Please see the getter of this property: [isAutoText()](../../com.aspose.cells/datalabels\#isAutoText--) |
| [setAutomaticSize(boolean value)](#setAutomaticSize-boolean-) | Please see the getter of this property: [isAutomaticSize()](../../com.aspose.cells/chartframe\#isAutomaticSize--) |
| [setBackground(int value)](#setBackground-int-) | Please see the getter of this property: [getBackground()](../../com.aspose.cells/chartframe\#getBackground--) |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Please see the getter of this property: [getBackgroundMode()](../../com.aspose.cells/datalabels\#getBackgroundMode--) |
| [setDeleted(boolean value)](#setDeleted-boolean-) | Please see the getter of this property: @CREF79\_ |
| [setDirectionType(int value)](#setDirectionType-int-) | Please see the getter of this property: [getDirectionType()](../../com.aspose.cells/datalabels\#getDirectionType--) |
| [setHeight(int value)](#setHeight-int-) | Please see the getter of this property: [getHeight()](../../com.aspose.cells/chartframe\#getHeight--) |
| [setInnerMode(boolean value)](#setInnerMode-boolean-) | Please see the getter of this property: [isInnerMode()](../../com.aspose.cells/chartframe\#isInnerMode--) |
| [setLinkedSource(String value)](#setLinkedSource-java.lang.String-) | Please see the getter of this property: @CREF84\_ |
| [setNeverOverlap(boolean value)](#setNeverOverlap-boolean-) | Please see the getter of this property: [isNeverOverlap()](../../com.aspose.cells/datalabels\#isNeverOverlap--) |
| [setNumber(int value)](#setNumber-int-) | Please see the getter of this property: [getNumber()](../../com.aspose.cells/datalabels\#getNumber--) |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Please see the getter of this property: [getNumberFormat()](../../com.aspose.cells/datalabels\#getNumberFormat--) |
| [setNumberFormatLinked(boolean value)](#setNumberFormatLinked-boolean-) | Please see the getter of this property: [getNumberFormatLinked()](../../com.aspose.cells/datalabels\#getNumberFormatLinked--) |
| [setPosition(int value)](#setPosition-int-) | Please see the getter of this property: [getPosition()](../../com.aspose.cells/datalabels\#getPosition--) |
| [setPositionAuto()](#setPositionAuto--) | Set position of the frame to automatic |
| [setReadingOrder(int value)](#setReadingOrder-int-) | Please see the getter of this property: @CREF86\_ |
| [setResizeShapeToFitText(boolean value)](#setResizeShapeToFitText-boolean-) | Please see the getter of this property: @CREF89\_ |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Please see the getter of this property: @CREF82\_ |
| [setSeparator(int value)](#setSeparator-int-) | Please see the getter of this property: [getSeparator()](../../com.aspose.cells/datalabels\#getSeparator--) |
| [setSeparatorType(int value)](#setSeparatorType-int-) | Please see the getter of this property: [getSeparatorType()](../../com.aspose.cells/datalabels\#getSeparatorType--) |
| [setSeparatorValue(String value)](#setSeparatorValue-java.lang.String-) | Please see the getter of this property: [getSeparatorValue()](../../com.aspose.cells/datalabels\#getSeparatorValue--) |
| [setShadow(boolean value)](#setShadow-boolean-) | Please see the getter of this property: [getShadow()](../../com.aspose.cells/chartframe\#getShadow--) |
| [setShapeType(int value)](#setShapeType-int-) | Please see the getter of this property: [getShapeType()](../../com.aspose.cells/datalabels\#getShapeType--) |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Please see the getter of this property: [getShowBubbleSize()](../../com.aspose.cells/datalabels\#getShowBubbleSize--) |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Please see the getter of this property: [getShowCategoryName()](../../com.aspose.cells/datalabels\#getShowCategoryName--) |
| [setShowCellRange(boolean value)](#setShowCellRange-boolean-) | Please see the getter of this property: [getShowCellRange()](../../com.aspose.cells/datalabels\#getShowCellRange--) |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Please see the getter of this property: [getShowLegendKey()](../../com.aspose.cells/datalabels\#getShowLegendKey--) |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Please see the getter of this property: [getShowPercentage()](../../com.aspose.cells/datalabels\#getShowPercentage--) |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Please see the getter of this property: [getShowSeriesName()](../../com.aspose.cells/datalabels\#getShowSeriesName--) |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Please see the getter of this property: [getShowValue()](../../com.aspose.cells/datalabels\#getShowValue--) |
| [setText(String value)](#setText-java.lang.String-) | Please see the getter of this property: [getText()](../../com.aspose.cells/datalabels\#getText--) |
| [setTextDirection(int value)](#setTextDirection-int-) | Please see the getter of this property: @CREF85\_ |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Please see the getter of this property: @CREF80\_ |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Please see the getter of this property: @CREF81\_ |
| [setTextWrapped(boolean value)](#setTextWrapped-boolean-) | Please see the getter of this property: [isTextWrapped()](../../com.aspose.cells/datalabels\#isTextWrapped--) |
| [setWidth(int value)](#setWidth-int-) | Please see the getter of this property: [getWidth()](../../com.aspose.cells/chartframe\#getWidth--) |
| [setX(int value)](#setX-int-) | Please see the getter of this property: [getX()](../../com.aspose.cells/chartframe\#getX--) |
| [setY(int value)](#setY-int-) | Please see the getter of this property: [getY()](../../com.aspose.cells/chartframe\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataLabels() {#DataLabels--}
```
public DataLabels()
```


### characters(int startIndex, int length) {#characters-int-int-}
```
public FontSetting characters(int startIndex, int length)
```


Returns a Characters object that represents a range of characters within the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The index of the start of the character. |
| length | int | The number of characters. |

**Returns:**
[FontSetting](../../com.aspose.cells/fontsetting) - Characters object.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public Area getArea()
```


Gets the [Area](../../com.aspose.cells/area).

**Returns:**
[Area](../../com.aspose.cells/area)
### getAutoScaleFont() {#getAutoScaleFont--}
```
public boolean getAutoScaleFont()
```


True if the text in the object changes font size when the object size changes. The default value is True.

**Returns:**
boolean
### getBackground() {#getBackground--}
```
public int getBackground()
```


Gets and sets the display mode of the background NOTE: This member is now obsolete. Instead, please use ChartFrame.BackgroundMode property. This property will be removed 12 months later since JANUARY 2012. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
int
### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Gets and sets the display mode of the background

**Returns:**
int
### getBorder() {#getBorder--}
```
public Line getBorder()
```


Gets the [Line](../../com.aspose.cells/line).

**Returns:**
[Line](../../com.aspose.cells/line)
### getChart() {#getChart--}
```
public Chart getChart()
```


Gets the chart to which this object belongs.

**Returns:**
[Chart](../../com.aspose.cells/chart)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultHeight() {#getDefaultHeight--}
```
public int getDefaultHeight()
```


Represents height of default position

**Returns:**
int
### getDefaultWidth() {#getDefaultWidth--}
```
public int getDefaultWidth()
```


Represents width of default position

**Returns:**
int
### getDefaultX() {#getDefaultX--}
```
public int getDefaultX()
```


Represents x of default position

**Returns:**
int
### getDefaultY() {#getDefaultY--}
```
public int getDefaultY()
```


Represents y of default position

**Returns:**
int
### getDirectionType() {#getDirectionType--}
```
public int getDirectionType()
```


Gets and sets the direction of text.

**Returns:**
int
### getFont() {#getFont--}
```
public Font getFont()
```


Gets the font of the DataLabels;

**Returns:**
[Font](../../com.aspose.cells/font)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the height of frame in units of 1/4000 of the chart area. How to convert units of 1/4000 to pixels? Height In Pixels = Y \* Chart.ChartObject.Height / 4000;

**Returns:**
int
### getLinkedSource() {#getLinkedSource--}
```
public String getLinkedSource()
```


Gets and sets a reference to the worksheet.

**Returns:**
java.lang.String
### getNumber() {#getNumber--}
```
public int getNumber()
```


Gets and sets the built-in number format.

**Returns:**
int
### getNumberFormat() {#getNumberFormat--}
```
public String getNumberFormat()
```


Represents the format string for the DataLabels object.

**Returns:**
java.lang.String
### getNumberFormatLinked() {#getNumberFormatLinked--}
```
public boolean getNumberFormatLinked()
```


True if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public int getPosition()
```


Represents the position of the data label.

**Returns:**
int
### getReadingOrder() {#getReadingOrder--}
```
public int getReadingOrder()
```


Represents text reading order.

**Returns:**
int
### getRotationAngle() {#getRotationAngle--}
```
public int getRotationAngle()
```


Represents text rotation angle.
0: Not rotated.

255: Top to Bottom.

\-90: Downward.

90: Upward.


**Returns:**
int
### getSeparator() {#getSeparator--}
```
public int getSeparator()
```


Gets or sets the separator type used for the data labels on a chart. NOTE: This member is now obsolete. Instead, please use DataLabels.SeparatorType property. This property will be removed 12 months later since September 2020. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
int
### getSeparatorType() {#getSeparatorType--}
```
public int getSeparatorType()
```


Gets or sets the separator type used for the data labels on a chart. To set custom separator, please set the property [getSeparatorType()](../../com.aspose.cells/datalabels\#getSeparatorType--) as DataLabelsSeparatorType.CUSTOM and then specify the expected value for [getSeparatorValue()](../../com.aspose.cells/datalabels\#getSeparatorValue--).

**Returns:**
int
### getSeparatorValue() {#getSeparatorValue--}
```
public String getSeparatorValue()
```


Gets or sets the separator value used for the data labels on a chart.

**Returns:**
java.lang.String
### getShadow() {#getShadow--}
```
public boolean getShadow()
```


True if the frame has a shadow.

**Returns:**
boolean
### getShapeProperties() {#getShapeProperties--}
```
public ShapePropertyCollection getShapeProperties()
```


Gets the [getShapeProperties()](../../com.aspose.cells/chartframe\#getShapeProperties--) object.

**Returns:**
[ShapePropertyCollection](../../com.aspose.cells/shapepropertycollection)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Gets or sets shape type of data label.

**Returns:**
int
### getShowBubbleSize() {#getShowBubbleSize--}
```
public boolean getShowBubbleSize()
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide.

**Returns:**
boolean
### getShowCategoryName() {#getShowCategoryName--}
```
public boolean getShowCategoryName()
```


Represents a specified chart's data label category name display behavior.True to display the category name for the data labels on a chart. False to hide.

**Returns:**
boolean
### getShowCellRange() {#getShowCellRange--}
```
public boolean getShowCellRange()
```


Indicates whether showing cell range as the data labels.

**Returns:**
boolean
### getShowLegendKey() {#getShowLegendKey--}
```
public boolean getShowLegendKey()
```


Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible.

**Returns:**
boolean
### getShowPercentage() {#getShowPercentage--}
```
public boolean getShowPercentage()
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide.

**Returns:**
boolean
### getShowSeriesName() {#getShowSeriesName--}
```
public boolean getShowSeriesName()
```


Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide.

**Returns:**
boolean
### getShowValue() {#getShowValue--}
```
public boolean getShowValue()
```


Represents a specified chart's data label values display behavior. True displays the values. False to hide.

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


Gets or sets the text of data label.

**Returns:**
java.lang.String
### getTextDirection() {#getTextDirection--}
```
public int getTextDirection()
```


Represents text reading order. NOTE: This member is now obsolete. Instead, please use ChartTextFrame.ReadingOrder property. This property will be removed 12 months later since March 2020. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
int
### getTextFont() {#getTextFont--}
```
public Font getTextFont()
```


Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object. NOTE: This member is now obsolete. Instead, please use ChartFrame.Font property. This property will be removed 12 months later since JANUARY 2012. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
[Font](../../com.aspose.cells/font)
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Gets and sets the text horizontal alignment.

**Returns:**
int
### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Gets and sets the options of the text.

**Returns:**
[TextOptions](../../com.aspose.cells/textoptions)
### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public int getTextVerticalAlignment()
```


Gets or sets the text vertical alignment of text.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets the width of frame in units of 1/4000 of the chart area. How to convert units of 1/4000 to pixels? Width In Pixels = Width \* Chart.ChartObject.Height / 4000;

**Returns:**
int
### getX() {#getX--}
```
public int getX()
```


Gets or sets the x coordinate of the upper left corner in units of 1/4000 of the chart area. How to convert units of 1/4000 to pixels? X In Pixels = X \* Chart.ChartObject.Width / 4000;

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Gets or sets the y coordinate of the upper left corner in units of 1/4000 of the chart area. How to convert units of 1/4000 to pixels? Y In Pixels = Y \* Chart.ChartObject.Height / 4000;

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoText() {#isAutoText--}
```
public boolean isAutoText()
```


Indicates the text is auto generated.

**Returns:**
boolean
### isAutomaticSize() {#isAutomaticSize--}
```
public boolean isAutomaticSize()
```


Indicates whether the chart frame is automatic sized.

**Returns:**
boolean
### isDefaultPosBeSet() {#isDefaultPosBeSet--}
```
public boolean isDefaultPosBeSet()
```


Indicates whether default position(DefaultX, DefaultY, DefaultWidth and DefaultHeight) are set.

**Returns:**
boolean
### isDeleted() {#isDeleted--}
```
public boolean isDeleted()
```


Indicates whether this data labels is deleted.

**Returns:**
boolean
### isInnerMode() {#isInnerMode--}
```
public boolean isInnerMode()
```


Indicates whether the size of the plot area size includes the tick marks, and the axis labels. False specifies that the size shall determine the size of the plot area, the tick marks, and the axis labels. Only for Xlsx file.

**Returns:**
boolean
### isNeverOverlap() {#isNeverOverlap--}
```
public boolean isNeverOverlap()
```


Indicates whether the datalabels display never overlap. (For Pie chart)

**Returns:**
boolean
### isResizeShapeToFitText() {#isResizeShapeToFitText--}
```
public boolean isResizeShapeToFitText()
```


Gets or sets whether a shape should be auto-fit to fully contain the text described within it. Auto-fitting is when text within a shape is scaled in order to contain all the text inside.

**Returns:**
boolean
### isTextWrapped() {#isTextWrapped--}
```
public boolean isTextWrapped()
```


Gets or sets a value indicating whether the text is wrapped.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoScaleFont(boolean value) {#setAutoScaleFont-boolean-}
```
public void setAutoScaleFont(boolean value)
```


Please see the getter of this property: [getAutoScaleFont()](../../com.aspose.cells/chartframe\#getAutoScaleFont--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAutoText(boolean value) {#setAutoText-boolean-}
```
public void setAutoText(boolean value)
```


Please see the getter of this property: [isAutoText()](../../com.aspose.cells/datalabels\#isAutoText--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAutomaticSize(boolean value) {#setAutomaticSize-boolean-}
```
public void setAutomaticSize(boolean value)
```


Please see the getter of this property: [isAutomaticSize()](../../com.aspose.cells/chartframe\#isAutomaticSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Please see the getter of this property: [getBackground()](../../com.aspose.cells/chartframe\#getBackground--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Please see the getter of this property: [getBackgroundMode()](../../com.aspose.cells/datalabels\#getBackgroundMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDeleted(boolean value) {#setDeleted-boolean-}
```
public void setDeleted(boolean value)
```


Please see the getter of this property: @CREF79\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDirectionType(int value) {#setDirectionType-int-}
```
public void setDirectionType(int value)
```


Please see the getter of this property: [getDirectionType()](../../com.aspose.cells/datalabels\#getDirectionType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Please see the getter of this property: [getHeight()](../../com.aspose.cells/chartframe\#getHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInnerMode(boolean value) {#setInnerMode-boolean-}
```
public void setInnerMode(boolean value)
```


Please see the getter of this property: [isInnerMode()](../../com.aspose.cells/chartframe\#isInnerMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLinkedSource(String value) {#setLinkedSource-java.lang.String-}
```
public void setLinkedSource(String value)
```


Please see the getter of this property: @CREF84\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNeverOverlap(boolean value) {#setNeverOverlap-boolean-}
```
public void setNeverOverlap(boolean value)
```


Please see the getter of this property: [isNeverOverlap()](../../com.aspose.cells/datalabels\#isNeverOverlap--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setNumber(int value) {#setNumber-int-}
```
public void setNumber(int value)
```


Please see the getter of this property: [getNumber()](../../com.aspose.cells/datalabels\#getNumber--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public void setNumberFormat(String value)
```


Please see the getter of this property: [getNumberFormat()](../../com.aspose.cells/datalabels\#getNumberFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNumberFormatLinked(boolean value) {#setNumberFormatLinked-boolean-}
```
public void setNumberFormatLinked(boolean value)
```


Please see the getter of this property: [getNumberFormatLinked()](../../com.aspose.cells/datalabels\#getNumberFormatLinked--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPosition(int value) {#setPosition-int-}
```
public void setPosition(int value)
```


Please see the getter of this property: [getPosition()](../../com.aspose.cells/datalabels\#getPosition--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPositionAuto() {#setPositionAuto--}
```
public void setPositionAuto()
```


Set position of the frame to automatic

### setReadingOrder(int value) {#setReadingOrder-int-}
```
public void setReadingOrder(int value)
```


Please see the getter of this property: @CREF86\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setResizeShapeToFitText(boolean value) {#setResizeShapeToFitText-boolean-}
```
public void setResizeShapeToFitText(boolean value)
```


Please see the getter of this property: @CREF89\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRotationAngle(int value) {#setRotationAngle-int-}
```
public void setRotationAngle(int value)
```


Please see the getter of this property: @CREF82\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSeparator(int value) {#setSeparator-int-}
```
public void setSeparator(int value)
```


Please see the getter of this property: [getSeparator()](../../com.aspose.cells/datalabels\#getSeparator--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSeparatorType(int value) {#setSeparatorType-int-}
```
public void setSeparatorType(int value)
```


Please see the getter of this property: [getSeparatorType()](../../com.aspose.cells/datalabels\#getSeparatorType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSeparatorValue(String value) {#setSeparatorValue-java.lang.String-}
```
public void setSeparatorValue(String value)
```


Please see the getter of this property: [getSeparatorValue()](../../com.aspose.cells/datalabels\#getSeparatorValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setShadow(boolean value) {#setShadow-boolean-}
```
public void setShadow(boolean value)
```


Please see the getter of this property: [getShadow()](../../com.aspose.cells/chartframe\#getShadow--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Please see the getter of this property: [getShapeType()](../../com.aspose.cells/datalabels\#getShapeType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public void setShowBubbleSize(boolean value)
```


Please see the getter of this property: [getShowBubbleSize()](../../com.aspose.cells/datalabels\#getShowBubbleSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public void setShowCategoryName(boolean value)
```


Please see the getter of this property: [getShowCategoryName()](../../com.aspose.cells/datalabels\#getShowCategoryName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowCellRange(boolean value) {#setShowCellRange-boolean-}
```
public void setShowCellRange(boolean value)
```


Please see the getter of this property: [getShowCellRange()](../../com.aspose.cells/datalabels\#getShowCellRange--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public void setShowLegendKey(boolean value)
```


Please see the getter of this property: [getShowLegendKey()](../../com.aspose.cells/datalabels\#getShowLegendKey--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public void setShowPercentage(boolean value)
```


Please see the getter of this property: [getShowPercentage()](../../com.aspose.cells/datalabels\#getShowPercentage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public void setShowSeriesName(boolean value)
```


Please see the getter of this property: [getShowSeriesName()](../../com.aspose.cells/datalabels\#getShowSeriesName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public void setShowValue(boolean value)
```


Please see the getter of this property: [getShowValue()](../../com.aspose.cells/datalabels\#getShowValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Please see the getter of this property: [getText()](../../com.aspose.cells/datalabels\#getText--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTextDirection(int value) {#setTextDirection-int-}
```
public void setTextDirection(int value)
```


Please see the getter of this property: @CREF85\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Please see the getter of this property: @CREF80\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public void setTextVerticalAlignment(int value)
```


Please see the getter of this property: @CREF81\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTextWrapped(boolean value) {#setTextWrapped-boolean-}
```
public void setTextWrapped(boolean value)
```


Please see the getter of this property: [isTextWrapped()](../../com.aspose.cells/datalabels\#isTextWrapped--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Please see the getter of this property: [getWidth()](../../com.aspose.cells/chartframe\#getWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Please see the getter of this property: [getX()](../../com.aspose.cells/chartframe\#getX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Please see the getter of this property: [getY()](../../com.aspose.cells/chartframe\#getY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
