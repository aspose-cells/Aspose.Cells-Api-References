---
title: PlotArea
second_title: Aspose.Cells for Java API Reference
description: Encapsulates the object that represents the plot area in a chart.
type: docs
weight: 418
url: /java/com.aspose.cells/plotarea/
---

**Inheritance:**
java.lang.Object, [com.aspose.cells.ChartFrame](../../com.aspose.cells/chartframe)
```
public class PlotArea extends ChartFrame
```

Encapsulates the object that represents the plot area in a chart.
## Constructors

| Constructor | Description |
| --- | --- |
| [PlotArea()](#PlotArea--) |  |
## Methods

| Method | Description |
| --- | --- |
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
| [getFont()](#getFont--) | Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object. |
| [getHeight()](#getHeight--) | Gets or sets the height of plot-area bounding box in units of 1/4000 of the chart area. |
| [getInnerHeight()](#getInnerHeight--) | Gets or sets the height of plot area in units of 1/4000 of the chart area. |
| [getInnerWidth()](#getInnerWidth--) | Gets or sets the width of plot area in units of 1/4000 of the chart area. |
| [getInnerX()](#getInnerX--) | Gets or gets the x coordinate of the upper top corner of plot area in units of 1/4000 of the chart area. |
| [getInnerY()](#getInnerY--) | Gets or gets the x coordinate of the upper top corner of plot area in units of 1/4000 of the chart area. |
| [getShadow()](#getShadow--) | True if the frame has a shadow. |
| [getShapeProperties()](#getShapeProperties--) | Gets the [getShapeProperties()](../../com.aspose.cells/chartframe\#getShapeProperties--) object. |
| [getTextFont()](#getTextFont--) | Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object. |
| [getTextOptions()](#getTextOptions--) | Gets and sets the options of the text. |
| [getWidth()](#getWidth--) | Gets or sets the width of plot-area bounding box in units of 1/4000 of the chart area. |
| [getX()](#getX--) | Gets or gets the x coordinate of the upper left corner of plot-area bounding box in units of 1/4000 of the chart area. |
| [getY()](#getY--) | Gets or gets the y coordinate of the upper top corner of plot-area bounding box in units of 1/4000 of the chart area. |
| [hashCode()](#hashCode--) |  |
| [isAutomaticSize()](#isAutomaticSize--) | Indicates whether the plot area is automatic sized. |
| [isDefaultPosBeSet()](#isDefaultPosBeSet--) | Indicates whether default position(DefaultX, DefaultY, DefaultWidth and DefaultHeight) are set. |
| [isInnerMode()](#isInnerMode--) | Indicates whether the size of the plot area size includes the tick marks, and the axis labels. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoScaleFont(boolean value)](#setAutoScaleFont-boolean-) | Please see the getter of this property: [getAutoScaleFont()](../../com.aspose.cells/chartframe\#getAutoScaleFont--) |
| [setAutomaticSize(boolean value)](#setAutomaticSize-boolean-) | Please see the getter of this property: @CREF1333\_ |
| [setBackground(int value)](#setBackground-int-) | Please see the getter of this property: [getBackground()](../../com.aspose.cells/chartframe\#getBackground--) |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Please see the getter of this property: [getBackgroundMode()](../../com.aspose.cells/chartframe\#getBackgroundMode--) |
| [setHeight(int value)](#setHeight-int-) | Please see the getter of this property: @CREF1327\_ |
| [setInnerHeight(int value)](#setInnerHeight-int-) | Please see the getter of this property: @CREF1331\_ |
| [setInnerMode(boolean value)](#setInnerMode-boolean-) | Please see the getter of this property: [isInnerMode()](../../com.aspose.cells/chartframe\#isInnerMode--) |
| [setInnerWidth(int value)](#setInnerWidth-int-) | Please see the getter of this property: @CREF1332\_ |
| [setInnerX(int value)](#setInnerX-int-) | Please see the getter of this property: @CREF1329\_ |
| [setInnerY(int value)](#setInnerY-int-) | Please see the getter of this property: @CREF1330\_ |
| [setPositionAuto()](#setPositionAuto--) | Set position of the plot area to automatic |
| [setShadow(boolean value)](#setShadow-boolean-) | Please see the getter of this property: [getShadow()](../../com.aspose.cells/chartframe\#getShadow--) |
| [setWidth(int value)](#setWidth-int-) | Please see the getter of this property: @CREF1328\_ |
| [setX(int value)](#setX-int-) | Please see the getter of this property: @CREF1325\_ |
| [setY(int value)](#setY-int-) | Please see the getter of this property: @CREF1326\_ |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlotArea() {#PlotArea--}
```
public PlotArea()
```


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
### getFont() {#getFont--}
```
public Font getFont()
```


Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object.

**Returns:**
[Font](../../com.aspose.cells/font)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the height of plot-area bounding box in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getInnerHeight() {#getInnerHeight--}
```
public int getInnerHeight()
```


Gets or sets the height of plot area in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getInnerWidth() {#getInnerWidth--}
```
public int getInnerWidth()
```


Gets or sets the width of plot area in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getInnerX() {#getInnerX--}
```
public int getInnerX()
```


Gets or gets the x coordinate of the upper top corner of plot area in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getInnerY() {#getInnerY--}
```
public int getInnerY()
```


Gets or gets the x coordinate of the upper top corner of plot area in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
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
### getTextFont() {#getTextFont--}
```
public Font getTextFont()
```


Gets a [ChartArea.getFont()](../../com.aspose.cells/chartarea\#getFont--) object of the specified ChartFrame object. NOTE: This member is now obsolete. Instead, please use ChartFrame.Font property. This property will be removed 12 months later since JANUARY 2012. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
[Font](../../com.aspose.cells/font)
### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Gets and sets the options of the text.

**Returns:**
[TextOptions](../../com.aspose.cells/textoptions)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets the width of plot-area bounding box in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getX() {#getX--}
```
public int getX()
```


Gets or gets the x coordinate of the upper left corner of plot-area bounding box in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Gets or gets the y coordinate of the upper top corner of plot-area bounding box in units of 1/4000 of the chart area.

The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks. If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method.

The **X**, **Y**, **Width** and **Height** of **PlotArea** represents the plot-area bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. If you want to get actual size of plot area, you should call **InnerX**, **InnerY**, **InnerWidth** and **InnerHeight** properties.

For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutomaticSize() {#isAutomaticSize--}
```
public boolean isAutomaticSize()
```


Indicates whether the plot area is automatic sized.

**Returns:**
boolean
### isDefaultPosBeSet() {#isDefaultPosBeSet--}
```
public boolean isDefaultPosBeSet()
```


Indicates whether default position(DefaultX, DefaultY, DefaultWidth and DefaultHeight) are set.

**Returns:**
boolean
### isInnerMode() {#isInnerMode--}
```
public boolean isInnerMode()
```


Indicates whether the size of the plot area size includes the tick marks, and the axis labels. False specifies that the size shall determine the size of the plot area, the tick marks, and the axis labels. Only for Xlsx file.

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

### setAutomaticSize(boolean value) {#setAutomaticSize-boolean-}
```
public void setAutomaticSize(boolean value)
```


Please see the getter of this property: @CREF1333\_

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


Please see the getter of this property: [getBackgroundMode()](../../com.aspose.cells/chartframe\#getBackgroundMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Please see the getter of this property: @CREF1327\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInnerHeight(int value) {#setInnerHeight-int-}
```
public void setInnerHeight(int value)
```


Please see the getter of this property: @CREF1331\_

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

### setInnerWidth(int value) {#setInnerWidth-int-}
```
public void setInnerWidth(int value)
```


Please see the getter of this property: @CREF1332\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInnerX(int value) {#setInnerX-int-}
```
public void setInnerX(int value)
```


Please see the getter of this property: @CREF1329\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInnerY(int value) {#setInnerY-int-}
```
public void setInnerY(int value)
```


Please see the getter of this property: @CREF1330\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPositionAuto() {#setPositionAuto--}
```
public void setPositionAuto()
```


Set position of the plot area to automatic

### setShadow(boolean value) {#setShadow-boolean-}
```
public void setShadow(boolean value)
```


Please see the getter of this property: [getShadow()](../../com.aspose.cells/chartframe\#getShadow--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Please see the getter of this property: @CREF1328\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Please see the getter of this property: @CREF1325\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Please see the getter of this property: @CREF1326\_

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
