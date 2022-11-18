---
title: ErrorBar
second_title: Aspose.Cells for Java API Reference
description: Represents error bar of data series.
type: docs
weight: 191
url: /java/com.aspose.cells/errorbar/
---

**Inheritance:**
java.lang.Object, [com.aspose.cells.Line](../../com.aspose.cells/line)
```
public class ErrorBar extends Line
```

Represents error bar of data series.

```
Workbook workbook = new Workbook();
         Cells cells = workbook.getWorksheets().get(0).getCells();
         cells.get("a1").putValue(2);
         cells.get("a2").putValue(5);
         cells.get("a3").putValue(3);
         cells.get("a4").putValue(6);
         cells.get("b1").putValue(4);
         cells.get("b2").putValue(3);
         cells.get("b3").putValue(6);
         cells.get("b4").putValue(7);
 
         cells.get("C1").putValue("Q1");
         cells.get("C2").putValue("Q2");
         cells.get("C3").putValue("Y1");
         cells.get("C4").putValue("Y2");
 
         int chartIndex = workbook.getWorksheets().get(0).getCharts().add(ChartType.COLUMN, 11, 0, 27, 10);
 
         Chart chart = workbook.getWorksheets().get(0).getCharts().get(chartIndex);
         chart.getNSeries().add("A1:B4", true);
 
         chart.getNSeries().setCategoryData("C1:C4");
 
         for(int i = 0; i <chart.getNSeries().getCount(); i ++)
         {
         		Series aseries = chart.getNSeries().get(i);
         		aseries.getYErrorBar().setDisplayType(ErrorBarDisplayType.MINUS);
         		aseries.getYErrorBar().setType(ErrorBarType.FIXED_VALUE);
         		aseries.getYErrorBar().setAmount(5);
         }
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ErrorBar()](#ErrorBar--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmount()](#getAmount--) | Represents amount of error bar. |
| [getBeginArrowLength()](#getBeginArrowLength--) | Specifies the length of the arrowhead for the begin of a line. |
| [getBeginArrowWidth()](#getBeginArrowWidth--) | Specifies the width of the arrowhead for the begin of a line. |
| [getBeginType()](#getBeginType--) | Specifies an arrowhead for the begin of a line. |
| [getCapType()](#getCapType--) | Specifies the ending caps. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Represents the [Color](../../com.aspose.cells/color) of the line. |
| [getCompoundType()](#getCompoundType--) | Specifies the compound line type |
| [getDashType()](#getDashType--) | Specifies the dash line type |
| [getDisplayType()](#getDisplayType--) | Represents error bar display type. |
| [getEndArrowLength()](#getEndArrowLength--) | Specifies the length of the arrowhead for the end of a line. |
| [getEndArrowWidth()](#getEndArrowWidth--) | Specifies the width of the arrowhead for the end of a line. |
| [getEndType()](#getEndType--) | Specifies an arrowhead for the end of a line. |
| [getFormattingType()](#getFormattingType--) | Gets or sets format type. |
| [getGradientFill()](#getGradientFill--) | Represents gradient fill. |
| [getJoinType()](#getJoinType--) | Specifies the joining caps. |
| [getMinusValue()](#getMinusValue--) | Represents negative error amount when error bar type is Custom. |
| [getPlusValue()](#getPlusValue--) | Represents positive error amount when error bar type is Custom. |
| [getShowMarkerTTop()](#getShowMarkerTTop--) | Indicates if formatting error bars with a T-top. |
| [getStyle()](#getStyle--) | Represents the style of the line. |
| [getThemeColor()](#getThemeColor--) | Gets and sets the theme color. |
| [getTransparency()](#getTransparency--) | Returns or sets the degree of transparency of the line as a value from 0.0 (opaque) through 1.0 (clear). |
| [getType()](#getType--) | Represents error bar amount type. |
| [getWeight()](#getWeight--) | Gets or sets the [WeightType](../../com.aspose.cells/weighttype) of the line. |
| [getWeightPt()](#getWeightPt--) | Gets or sets the weight of the line in unit of points. |
| [getWeightPx()](#getWeightPx--) | Gets or sets the weight of the line in unit of pixels. |
| [hashCode()](#hashCode--) |  |
| [isAuto()](#isAuto--) | Indicates whether this line style is auto assigned. |
| [isAutomaticColor()](#isAutomaticColor--) | Indicates whether the color of line is automatic assigned. |
| [isVisible()](#isVisible--) | Represents whether the line is visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmount(double value)](#setAmount-double-) | Please see the getter of this property: [getAmount()](../../com.aspose.cells/errorbar\#getAmount--) |
| [setAuto(boolean value)](#setAuto-boolean-) | Please see the getter of this property: [isAuto()](../../com.aspose.cells/line\#isAuto--) |
| [setBeginArrowLength(int value)](#setBeginArrowLength-int-) | Please see the getter of this property: [getBeginArrowLength()](../../com.aspose.cells/line\#getBeginArrowLength--) |
| [setBeginArrowWidth(int value)](#setBeginArrowWidth-int-) | Please see the getter of this property: [getBeginArrowWidth()](../../com.aspose.cells/line\#getBeginArrowWidth--) |
| [setBeginType(int value)](#setBeginType-int-) | Please see the getter of this property: [getBeginType()](../../com.aspose.cells/line\#getBeginType--) |
| [setCapType(int value)](#setCapType-int-) | Please see the getter of this property: [getCapType()](../../com.aspose.cells/line\#getCapType--) |
| [setColor(Color value)](#setColor-com.aspose.cells.Color-) | Please see the getter of this property: [getColor()](../../com.aspose.cells/line\#getColor--) |
| [setCompoundType(int value)](#setCompoundType-int-) | Please see the getter of this property: [getCompoundType()](../../com.aspose.cells/line\#getCompoundType--) |
| [setDashType(int value)](#setDashType-int-) | Please see the getter of this property: [getDashType()](../../com.aspose.cells/line\#getDashType--) |
| [setDisplayType(int value)](#setDisplayType-int-) | Please see the getter of this property: [getDisplayType()](../../com.aspose.cells/errorbar\#getDisplayType--) |
| [setEndArrowLength(int value)](#setEndArrowLength-int-) | Please see the getter of this property: [getEndArrowLength()](../../com.aspose.cells/line\#getEndArrowLength--) |
| [setEndArrowWidth(int value)](#setEndArrowWidth-int-) | Please see the getter of this property: [getEndArrowWidth()](../../com.aspose.cells/line\#getEndArrowWidth--) |
| [setEndType(int value)](#setEndType-int-) | Please see the getter of this property: [getEndType()](../../com.aspose.cells/line\#getEndType--) |
| [setFormattingType(int value)](#setFormattingType-int-) | Please see the getter of this property: [getFormattingType()](../../com.aspose.cells/line\#getFormattingType--) |
| [setJoinType(int value)](#setJoinType-int-) | Please see the getter of this property: [getJoinType()](../../com.aspose.cells/line\#getJoinType--) |
| [setMinusValue(String value)](#setMinusValue-java.lang.String-) | Please see the getter of this property: [getMinusValue()](../../com.aspose.cells/errorbar\#getMinusValue--) |
| [setPlusValue(String value)](#setPlusValue-java.lang.String-) | Please see the getter of this property: [getPlusValue()](../../com.aspose.cells/errorbar\#getPlusValue--) |
| [setShowMarkerTTop(boolean value)](#setShowMarkerTTop-boolean-) | Please see the getter of this property: [getShowMarkerTTop()](../../com.aspose.cells/errorbar\#getShowMarkerTTop--) |
| [setStyle(int value)](#setStyle-int-) | Please see the getter of this property: [getStyle()](../../com.aspose.cells/line\#getStyle--) |
| [setThemeColor(ThemeColor value)](#setThemeColor-com.aspose.cells.ThemeColor-) | Please see the getter of this property: [getThemeColor()](../../com.aspose.cells/line\#getThemeColor--) |
| [setTransparency(double value)](#setTransparency-double-) | Please see the getter of this property: [getTransparency()](../../com.aspose.cells/line\#getTransparency--) |
| [setType(int value)](#setType-int-) | Please see the getter of this property: [getType()](../../com.aspose.cells/errorbar\#getType--) |
| [setVisible(boolean value)](#setVisible-boolean-) | Please see the getter of this property: [isVisible()](../../com.aspose.cells/line\#isVisible--) |
| [setWeight(int value)](#setWeight-int-) | Please see the getter of this property: [getWeight()](../../com.aspose.cells/line\#getWeight--) |
| [setWeightPt(double value)](#setWeightPt-double-) | Please see the getter of this property: [getWeightPt()](../../com.aspose.cells/line\#getWeightPt--) |
| [setWeightPx(double value)](#setWeightPx-double-) | Please see the getter of this property: [getWeightPx()](../../com.aspose.cells/line\#getWeightPx--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ErrorBar() {#ErrorBar--}
```
public ErrorBar()
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
### getAmount() {#getAmount--}
```
public double getAmount()
```


Represents amount of error bar.  The amount must be greater than or equal to zero.

**Returns:**
double
### getBeginArrowLength() {#getBeginArrowLength--}
```
public int getBeginArrowLength()
```


Specifies the length of the arrowhead for the begin of a line.

**Returns:**
int
### getBeginArrowWidth() {#getBeginArrowWidth--}
```
public int getBeginArrowWidth()
```


Specifies the width of the arrowhead for the begin of a line.

**Returns:**
int
### getBeginType() {#getBeginType--}
```
public int getBeginType()
```


Specifies an arrowhead for the begin of a line.

**Returns:**
int
### getCapType() {#getCapType--}
```
public int getCapType()
```


Specifies the ending caps.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Represents the [Color](../../com.aspose.cells/color) of the line.

**Returns:**
[Color](../../com.aspose.cells/color)
### getCompoundType() {#getCompoundType--}
```
public int getCompoundType()
```


Specifies the compound line type

**Returns:**
int
### getDashType() {#getDashType--}
```
public int getDashType()
```


Specifies the dash line type

**Returns:**
int
### getDisplayType() {#getDisplayType--}
```
public int getDisplayType()
```


Represents error bar display type.

**Returns:**
int
### getEndArrowLength() {#getEndArrowLength--}
```
public int getEndArrowLength()
```


Specifies the length of the arrowhead for the end of a line.

**Returns:**
int
### getEndArrowWidth() {#getEndArrowWidth--}
```
public int getEndArrowWidth()
```


Specifies the width of the arrowhead for the end of a line.

**Returns:**
int
### getEndType() {#getEndType--}
```
public int getEndType()
```


Specifies an arrowhead for the end of a line.

**Returns:**
int
### getFormattingType() {#getFormattingType--}
```
public int getFormattingType()
```


Gets or sets format type.

**Returns:**
int
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Represents gradient fill.

**Returns:**
[GradientFill](../../com.aspose.cells/gradientfill)
### getJoinType() {#getJoinType--}
```
public int getJoinType()
```


Specifies the joining caps.

**Returns:**
int
### getMinusValue() {#getMinusValue--}
```
public String getMinusValue()
```


Represents negative error amount when error bar type is Custom.

**Returns:**
java.lang.String
### getPlusValue() {#getPlusValue--}
```
public String getPlusValue()
```


Represents positive error amount when error bar type is Custom.

**Returns:**
java.lang.String
### getShowMarkerTTop() {#getShowMarkerTTop--}
```
public boolean getShowMarkerTTop()
```


Indicates if formatting error bars with a T-top.

**Returns:**
boolean
### getStyle() {#getStyle--}
```
public int getStyle()
```


Represents the style of the line.

**Returns:**
int
### getThemeColor() {#getThemeColor--}
```
public ThemeColor getThemeColor()
```


Gets and sets the theme color. If the foreground color is not a theme color, NULL will be returned.

**Returns:**
[ThemeColor](../../com.aspose.cells/themecolor)
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Returns or sets the degree of transparency of the line as a value from 0.0 (opaque) through 1.0 (clear).

**Returns:**
double
### getType() {#getType--}
```
public int getType()
```


Represents error bar amount type.

```
Workbook wb = new Workbook("chart.xlsx");
         Chart chart = wb.getWorksheets().get(0).getCharts().get(0);
         Series aseries = chart.getNSeries().get(0);
         //Sets custom error bar type
         aseries.getYErrorBar().setType(ErrorBarType.CUSTOM);
         aseries.getYErrorBar().setPlusValue("=Sheet1!A1");
         aseries.getYErrorBar().setMinusValue("=Sheet1!A2");
```

**Returns:**
int
### getWeight() {#getWeight--}
```
public int getWeight()
```


Gets or sets the [WeightType](../../com.aspose.cells/weighttype) of the line.

**Returns:**
int
### getWeightPt() {#getWeightPt--}
```
public double getWeightPt()
```


Gets or sets the weight of the line in unit of points.

**Returns:**
double
### getWeightPx() {#getWeightPx--}
```
public double getWeightPx()
```


Gets or sets the weight of the line in unit of pixels.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAuto() {#isAuto--}
```
public boolean isAuto()
```


Indicates whether this line style is auto assigned.

**Returns:**
boolean
### isAutomaticColor() {#isAutomaticColor--}
```
public boolean isAutomaticColor()
```


Indicates whether the color of line is automatic assigned.

**Returns:**
boolean
### isVisible() {#isVisible--}
```
public boolean isVisible()
```


Represents whether the line is visible.

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




### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Please see the getter of this property: [getAmount()](../../com.aspose.cells/errorbar\#getAmount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setAuto(boolean value) {#setAuto-boolean-}
```
public void setAuto(boolean value)
```


Please see the getter of this property: [isAuto()](../../com.aspose.cells/line\#isAuto--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBeginArrowLength(int value) {#setBeginArrowLength-int-}
```
public void setBeginArrowLength(int value)
```


Please see the getter of this property: [getBeginArrowLength()](../../com.aspose.cells/line\#getBeginArrowLength--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBeginArrowWidth(int value) {#setBeginArrowWidth-int-}
```
public void setBeginArrowWidth(int value)
```


Please see the getter of this property: [getBeginArrowWidth()](../../com.aspose.cells/line\#getBeginArrowWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBeginType(int value) {#setBeginType-int-}
```
public void setBeginType(int value)
```


Please see the getter of this property: [getBeginType()](../../com.aspose.cells/line\#getBeginType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCapType(int value) {#setCapType-int-}
```
public void setCapType(int value)
```


Please see the getter of this property: [getCapType()](../../com.aspose.cells/line\#getCapType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColor(Color value) {#setColor-com.aspose.cells.Color-}
```
public void setColor(Color value)
```


Please see the getter of this property: [getColor()](../../com.aspose.cells/line\#getColor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.cells/color) |  |

### setCompoundType(int value) {#setCompoundType-int-}
```
public void setCompoundType(int value)
```


Please see the getter of this property: [getCompoundType()](../../com.aspose.cells/line\#getCompoundType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDashType(int value) {#setDashType-int-}
```
public void setDashType(int value)
```


Please see the getter of this property: [getDashType()](../../com.aspose.cells/line\#getDashType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDisplayType(int value) {#setDisplayType-int-}
```
public void setDisplayType(int value)
```


Please see the getter of this property: [getDisplayType()](../../com.aspose.cells/errorbar\#getDisplayType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndArrowLength(int value) {#setEndArrowLength-int-}
```
public void setEndArrowLength(int value)
```


Please see the getter of this property: [getEndArrowLength()](../../com.aspose.cells/line\#getEndArrowLength--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndArrowWidth(int value) {#setEndArrowWidth-int-}
```
public void setEndArrowWidth(int value)
```


Please see the getter of this property: [getEndArrowWidth()](../../com.aspose.cells/line\#getEndArrowWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndType(int value) {#setEndType-int-}
```
public void setEndType(int value)
```


Please see the getter of this property: [getEndType()](../../com.aspose.cells/line\#getEndType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFormattingType(int value) {#setFormattingType-int-}
```
public void setFormattingType(int value)
```


Please see the getter of this property: [getFormattingType()](../../com.aspose.cells/line\#getFormattingType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJoinType(int value) {#setJoinType-int-}
```
public void setJoinType(int value)
```


Please see the getter of this property: [getJoinType()](../../com.aspose.cells/line\#getJoinType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMinusValue(String value) {#setMinusValue-java.lang.String-}
```
public void setMinusValue(String value)
```


Please see the getter of this property: [getMinusValue()](../../com.aspose.cells/errorbar\#getMinusValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlusValue(String value) {#setPlusValue-java.lang.String-}
```
public void setPlusValue(String value)
```


Please see the getter of this property: [getPlusValue()](../../com.aspose.cells/errorbar\#getPlusValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setShowMarkerTTop(boolean value) {#setShowMarkerTTop-boolean-}
```
public void setShowMarkerTTop(boolean value)
```


Please see the getter of this property: [getShowMarkerTTop()](../../com.aspose.cells/errorbar\#getShowMarkerTTop--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Please see the getter of this property: [getStyle()](../../com.aspose.cells/line\#getStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setThemeColor(ThemeColor value) {#setThemeColor-com.aspose.cells.ThemeColor-}
```
public void setThemeColor(ThemeColor value)
```


Please see the getter of this property: [getThemeColor()](../../com.aspose.cells/line\#getThemeColor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ThemeColor](../../com.aspose.cells/themecolor) |  |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Please see the getter of this property: [getTransparency()](../../com.aspose.cells/line\#getTransparency--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Please see the getter of this property: [getType()](../../com.aspose.cells/errorbar\#getType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Please see the getter of this property: [isVisible()](../../com.aspose.cells/line\#isVisible--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Please see the getter of this property: [getWeight()](../../com.aspose.cells/line\#getWeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWeightPt(double value) {#setWeightPt-double-}
```
public void setWeightPt(double value)
```


Please see the getter of this property: [getWeightPt()](../../com.aspose.cells/line\#getWeightPt--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setWeightPx(double value) {#setWeightPx-double-}
```
public void setWeightPx(double value)
```


Please see the getter of this property: [getWeightPx()](../../com.aspose.cells/line\#getWeightPx--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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
