---
title: FormBuildGridControl class
description: This topic describes the FormBuildGridControl class.
author: robinarh
manager: tonyafehr
ms.date: 06/25/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

audience: Developer
ms.reviewer: rhaertle
ms.search.scope: Operations
ms.search.region: Global
ms.author: rhaertle
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0
---

# Class FormBuildGridControl

[!include [banner](../../includes/banner.md)]

```xpp
class FormBuildGridControl extends FormBuildControl
```

The FormBuildGridControl class lets you create, read, update, and delete X++ code and metadata.

## Remarks

Make sure that the user has access to the development security key (SysDevelopment) before this API is called.

## Examples

## Methods

| Method                                                                                                      | Description                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| public int activeBackColor(\[int value\])                                                                   |                                                                                                                                         |
| public int activeForeColor(\[int value\])                                                                   |                                                                                                                                         |
| public boolean alignControl(\[boolean value\])                                                              | Determines whether to align the control.                                                                                                |
| public boolean allowEdit(\[boolean value\])                                                                 | Determines whether the user can change the contents of the control.                                                                     |
| public int alternateRowShading(\[int value\])                                                               |                                                                                                                                         |
| public boolean autoDataGroup(\[boolean value\])                                                             |                                                                                                                                         |
| public boolean autoDeclaration(\[boolean value\])                                                           | Determines whether the system can declare a member variable that has the same name as the control.                                      |
| public int backgroundColor(\[int value\])                                                                   | Gets or sets the background color of the control.                                                                                       |
| public int backStyle(\[int value\])                                                                         | Determines whether the control background can be transparent.                                                                          |
| public int border(\[int value\])                                                                            | Gets or sets the style of the borderline of the control.                                                                                |
| public int bottomMargin(\[int value\])                                                                      |                                                                                                                                         |
| public int colorScheme(\[int value\])                                                                       | Gets or sets the color scheme of the control.                                                                                           |
| public ConfigurationKeyId configurationKey(\[ConfigurationKeyId value\])                                    | Gets or sets the configuration key that is assigned to the control.                                                                     |
| public int containerId()                                                                                    | Retrieves the ID of the parent container for the control.                                                                               |
| public str countryRegionCodes(\[str value\])                                                                |                                                                                                                                         |
| public FieldId countryRegionContextField(\[FieldId value\])                                                 |                                                                                                                                         |
| public str dataGroup(\[str value\])                                                                         |                                                                                                                                         |
| public str dataRelationPath(\[str value\])                                                                  |                                                                                                                                         |
| public int dataSource(\[AnyType value\])                                                                    | Gets or sets a data source that is used by the control or the form.                                                                     |
| public str defaultAction(\[str value\])                                                                     |                                                                                                                                         |
| public str defaultActionLabel(\[str value\])                                                                |                                                                                                                                         |
| public int displayTarget(\[int value\])                                                                     |                                                                                                                                         |
| public int dragDrop(\[int value\])                                                                          | Determines whether to enable or disable drag-and-drop operations for the control.                                                       |
| public boolean enabled(\[boolean value\])                                                                   | Determines whether to enable or disable the object.                                                                                     |
| public boolean exportAllowed(\[boolean value\])                                                             |                                                                                                                                         |
| public str exportLabel(\[str value\])                                                                       |                                                                                                                                         |
| public boolean gridLines(\[boolean value\])                                                                 |                                                                                                                                         |
| public int gridLinesStyle(\[int value\])                                                                    |                                                                                                                                         |
| public str groupBy(\[str value\])                                                                           |                                                                                                                                         |
| public int height(int value, \[int mode\])                                                                  | Gets or sets the height of the control.                                                                                                 |
| public int heightMode(\[int value\])                                                                        | Gets or sets a calculation mode for the height of the control.                                                                          |
| public int heightValue(\[int value\])                                                                       | Gets or sets the height of the control.                                                                                                 |
| public str helpText(\[str value\])                                                                          | Gets or sets the help text to display at the bottom of the screen when a field or control is pointed to.                                |
| public str hierarchyParent(\[str value\])                                                                   |                                                                                                                                         |
| public boolean highlightActive(\[boolean value\])                                                           |                                                                                                                                         |
| public int id()                                                                                             | Retrieves the ID of the control.                                                                                                        |
| public boolean isContainer()                                                                                | Retrieves a value that indicates whether the control is a container control.                                                            |
| public int left(int value, \[int mode\])                                                                    |                                                                                                                                         |
| public int leftMargin(\[int value\])                                                                        |                                                                                                                                         |
| public int leftMode(\[int value\])                                                                          |                                                                                                                                         |
| public int leftValue(\[int value\])                                                                         |                                                                                                                                         |
| public int moreRowsIndicator(\[int value\])                                                                 |                                                                                                                                         |
| public int moveControl(int controlId, \[int insertAfterControlId\])                                         | Moves a specified control to the control.                                                                                               |
| public boolean multiSelect(\[boolean value\])                                                               |                                                                                                                                         |
| public str name(\[str value\])                                                                              | Gets or sets the name that is used in code to identify a form, report, table, query, or other application object. |
| public int neededPermission(\[int value\])                                                                  |                                                                                                                                         |
| public int rightMargin(\[int value\])                                                                       |                                                                                                                                         |
| public int scrollbars(\[int value\])                                                                        |                                                                                                                                         |
| public SecurityKeyId securityKey(\[SecurityKeyId value\])                                                   |                                                                                                                                         |
| public boolean showColLabels(\[boolean value\])                                                             |                                                                                                                                         |
| public boolean showRowLabels(\[boolean value\])                                                             |                                                                                                                                         |
| public boolean skip(\[boolean value\])                                                                      | Sets or returns a value that indicates whether the control is skipped when the user presses the TAB key to move to the control.         |
| public int style(\[int value\])                                                                             |                                                                                                                                         |
| public int top(int value, \[int mode\])                                                                     |                                                                                                                                         |
| public int topMargin(\[int value\])                                                                         |                                                                                                                                         |
| public int topMode(\[int value\])                                                                           |                                                                                                                                         |
| public int topValue(\[int value\])                                                                          |                                                                                                                                         |
| public int type(\[int value\])                                                                              |                                                                                                                                         |
| public int userData(\[int value\])                                                                          |                                                                                                                                         |
| public int userDataItem(\[int value\])                                                                      |                                                                                                                                         |
| public int userDataItems(\[int value\])                                                                     |                                                                                                                                         |
| public boolean useUserLayout(\[boolean value\])                                                             |                                                                                                                                         |
| public int verticalSpacing(\[int value\], \[AutoMode mode\])                                                |                                                                                                                                         |
| public AutoMode verticalSpacingMode(\[AutoMode mode\])                                                      |                                                                                                                                         |
| public int verticalSpacingValue(\[int value\])                                                              |                                                                                                                                         |
| public boolean visible(\[boolean value\])                                                                   |                                                                                                                                         |
| public int visibleCols(\[int value\], \[AutoMode mode\])                                                    |                                                                                                                                         |
| public AutoMode visibleColsMode(\[AutoMode mode\])                                                          |                                                                                                                                         |
| public int visibleColsValue(\[int value\])                                                                  |                                                                                                                                         |
| public int visibleRows(\[int value\], \[AutoMode mode\])                                                    |                                                                                                                                         |
| public AutoMode visibleRowsMode(\[AutoMode mode\])                                                          |                                                                                                                                         |
| public int visibleRowsValue(\[int value\])                                                                  |                                                                                                                                         |
| public int width(int value, \[int mode\])                                                                   | Gets or sets the width of the control.                                                                                                  |
| public int widthMode(\[int value\])                                                                         | Gets or sets the calculation mode of the width of the control.                                                                          |
| public int widthValue(\[int value\])                                                                        | Gets or sets the width of the control.                                                                                                  |
| public void registerOverrideMethod(str methodToOverride, str objectMethodToCall, \[Object overrideObject\]) |                                                                                                                                         |

## Method activeBackColor

```xpp
public int activeBackColor([int value])
```

### Parameters - activeBackColor

value  

### Return Value - activeBackColor

## Method activeForeColor

```xpp
public int activeForeColor([int value])
```

### Parameters - activeForeColor

value  

### Return Value - activeForeColor

## Method alignControl

Determines whether to align the control.

```xpp
public boolean alignControl([boolean value])
```

### Parameters - alignControl

value  

### Return Value - alignControl

true if the control should be aligned; otherwise, false.

### Remarks - alignControl

The upper-left corner of the control is aligned according to the longest label.

## Method allowEdit

Determines whether the user can change the contents of the control.

```xpp
public boolean allowEdit([boolean value])
```

### Parameters - allowEdit

value  

### Return Value - allowEdit

true if the control can be edited; otherwise, false.

### Remarks - allowEdit

When this property is set on a container control, modifications are disabled or enabled for all controls in the container.

## Method alternateRowShading

```xpp
public int alternateRowShading([int value])
```

### Parameters - alternateRowShading

value  

### Return Value - alternateRowShading

## Method autoDataGroup

```xpp
public boolean autoDataGroup([boolean value])
```

### Parameters - autoDataGroup

value  

### Return Value - autoDataGroup

## Method autoDeclaration

Determines whether the system can declare a member variable that has the same name as the control.

```xpp
public boolean autoDeclaration([boolean value])
```

### Parameters - autoDeclaration

value  

### Return Value - autoDeclaration

true if the member variable can be declared for this control; otherwise, false.

### Remarks - autoDeclaration

Controls cannot have identical names.

## Method backgroundColor

Gets or sets the background color of the control.

```xpp
public int backgroundColor([int value])
```

### Parameters - backgroundColor

value  

### Return Value - backgroundColor

An integer that contains a packed RGB color.

### Remarks - backgroundColor

The integer that is returned contains a packed RGB color as follows:

-   The low-order byte contains a value for the relative intensity of red.
-   The second byte contains a value for green.
-   The third byte contains a value for blue.
-   The high-order byte must be zero.
-   The maximum value for a single byte is 255.

## Method backStyle

Determines whether the control background can be transparent.

```xpp
public int backStyle([int value])
```

### Parameters - backStyle

value  

### Return Value - backStyle

1 if the control background can be transparent; otherwise, 0.

## Method border

Gets or sets the style of the borderline of the control.

```xpp
public int border([int value])
```

### Parameters - border

value  

### Return Value - border

An integer between zero and four, inclusive.

### Remarks - border

The integer that is returned contains the style of the borderline of the control as follows:

| Value. | Description. |
|--------|--------------|
| 0      | Auto.        |
| 1      | 3D.          |
| 2      | Single line. |
| 3      | Flat.        |
| 4      | None.        |

## Method bottomMargin

```xpp
public int bottomMargin([int value])
```

### Parameters - bottomMargin

value  

### Return Value - bottomMargin

## Method colorScheme

Gets or sets the color scheme of the control.

```xpp
public int colorScheme([int value])
```

### Parameters - colorScheme

value  

### Return Value - colorScheme

An integer between zero and two, inclusive.

### Remarks - colorScheme

The color scheme is defined according to the following table:

| Value. | Style.                        |
|--------|-------------------------------|
| 0      | Default.                      |
| 1      | The Microsoft Windows palette. |
| 2      | The true-color scheme.        |

## Method configurationKey

Gets or sets the configuration key that is assigned to the control.

```xpp
public ConfigurationKeyId configurationKey([ConfigurationKeyId value])
```

### Parameters - configurationKey

value  

### Return Value - configurationKey

The identifier of the configuration key that is assigned to the control.

### Remarks - configurationKey

The configuration key is used to determine whether this control can be displayed. If the configuration key is disabled in the system, the control is not displayed in the form.

## Method containerId

Retrieves the ID of the parent container for the control.

```xpp
public int containerId()
```

### Return Value - containerId

The ID of the parent container.

## Method countryRegionCodes

```xpp
public str countryRegionCodes([str value])
```

### Parameters - countryRegionCodes

value  

### Return Value - countryRegionCodes

## Method countryRegionContextField

```xpp
public FieldId countryRegionContextField([FieldId value])
```

### Parameters - countryRegionContextField

value  

### Return Value - countryRegionContextField

## Method dataGroup

```xpp
public str dataGroup([str value])
```

### Parameters - dataGroup

value  

### Return Value - dataGroup

## Method dataRelationPath

```xpp
public str dataRelationPath([str value])
```

### Parameters - dataRelationPath

value  

### Return Value - dataRelationPath

## Method dataSource

Gets or sets a data source that is used by the control or the form.

```xpp
public int dataSource([AnyType value])
```

### Parameters - dataSource

value  

### Return Value - dataSource

The identifier of the data source to use.

## Method defaultAction

```xpp
public str defaultAction([str value])
```

### Parameters - defaultAction

value  

### Return Value - defaultAction

## Method defaultActionLabel

```xpp
public str defaultActionLabel([str value])
```

### Parameters - defaultActionLabel

value  

### Return Value - defaultActionLabel

## Method displayTarget

```xpp
public int displayTarget([int value])
```

### Parameters - displayTarget

value  

### Return Value - displayTarget

## Method dragDrop

Determines whether to enable or disable drag-and-drop operations for the control.

```xpp
public int dragDrop([int value])
```

### Parameters - dragDrop

value  

### Return Value - dragDrop

1 if drag-and-drop operations are enabled; otherwise, false.

## Method enabled

Determines whether to enable or disable the object.

```xpp
public boolean enabled([boolean value])
```

### Parameters - enabled

value  

### Return Value - enabled

true if the object is enabled; otherwise, false.

### Remarks - enabled

The enabled property allows for controls to be enabled or disabled at run time. For example, you can disable objects that do not apply to the current state of the application. You can also disable a control that is used only for display purposes, such as an error message, which provides read-only information.

## Method exportAllowed

```xpp
public boolean exportAllowed([boolean value])
```

### Parameters - exportAllowed

value  

### Return Value - exportAllowed

## Method exportLabel

```xpp
public str exportLabel([str value])
```

### Parameters - exportLabel

value  

### Return Value - exportLabel

## Method gridLines

```xpp
public boolean gridLines([boolean value])
```

### Parameters - gridLines

value  

### Return Value - gridLines

## Method gridLinesStyle

```xpp
public int gridLinesStyle([int value])
```

### Parameters - gridLinesStyle

value  

### Return Value - gridLinesStyle

## Method groupBy

```xpp
public str groupBy([str value])
```

### Parameters - groupBy

value  

### Return Value - groupBy

## Method height

Gets or sets the height of the control.

```xpp
public int height(int value, [int mode])
```

### Parameters - height

value  

<!-- -->

mode  

### Return Value - height

The height of the control in pixels.

### Remarks - height

Exact mode is used if the value parameter is omitted. Calculate the height according to the following table:

| Mode.            | Height calculation.                                                                       |
|------------------|-------------------------------------------------------------------------------------------|
| -1 Exact.        | The exact height in pixels of the controls is used.                                       |
| 0 Auto.          | The height of the control is calculated automatically and the value parameter is ignored. |
| 1 Column height. | The layout of the form determines the height of the control.                              |

The height and height calculation mode can be set separately.

## Method heightMode

Gets or sets a calculation mode for the height of the control.

```xpp
public int heightMode([int value])
```

### Parameters - heightMode

value  

### Return Value - heightMode

The calculation mode.

### Remarks - heightMode

Calculate the height according to the following table:

| Mode.          | Height Calculation.                                                                       |
|----------------|-------------------------------------------------------------------------------------------|
| Exact.         | The exact height in pixels of the controls is used.                                       |
| Auto.          | The height of the control is calculated automatically and the value parameter is ignored. |
| Column height. | The layout of the form determines the height of the control.                              |

The height of the control might change when the mode is set to auto or column height.

## Method heightValue

Gets or sets the height of the control.

```xpp
public int heightValue([int value])
```

### Parameters - heightValue

value  

### Return Value - heightValue

The height in pixels.

### Remarks - heightValue

The height of the control is not changed unless the exact height calculation mode is used.

## Method helpText

Gets or sets the help text to display at the bottom of the screen when a field or control is pointed to.

```xpp
public str helpText([str value])
```

### Parameters - helpText

value  

### Return Value - helpText

The string to be displayed at the bottom of the screen.

### Remarks - helpText

Set the HelpText property for an object by using the property sheet. The help text must not exceed 250 characters.

## Method hierarchyParent

```xpp
public str hierarchyParent([str value])
```

### Parameters - hierarchyParent

value  

### Return Value - hierarchyParent

## Method highlightActive

```xpp
public boolean highlightActive([boolean value])
```

### Parameters - highlightActive

value  

### Return Value - highlightActive

## Method id

Retrieves the ID of the control.

```xpp
public int id()
```

### Return Value - id

The ID of the control.

## Method isContainer

Retrieves a value that indicates whether the control is a container control.

```xpp
public boolean isContainer()
```

### Return Value - isContainer

A Boolean value that indicates whether the control is a container control.

## Method left

```xpp
public int left(int value, [int mode])
```

### Parameters - left

value  

<!-- -->

mode  

### Return Value - left

## Method leftMargin

```xpp
public int leftMargin([int value])
```

### Parameters - leftMargin

value  

### Return Value - leftMargin

## Method leftMode

```xpp
public int leftMode([int value])
```

### Parameters - leftMode

value  

### Return Value - leftMode

## Method leftValue

```xpp
public int leftValue([int value])
```

### Parameters - leftValue

value  

### Return Value - leftValue

## Method moreRowsIndicator

```xpp
public int moreRowsIndicator([int value])
```

### Parameters - moreRowsIndicator

value  

### Return Value - moreRowsIndicator

## Method moveControl

Moves a specified control to the control.

```xpp
public int moveControl(int controlId, [int insertAfterControlId])
```

### Parameters - moveControl

controlId  

<!-- -->

insertAfterControlId  

### Return Value - moveControl

1 if the control was moved successfully; otherwise, 0.

### Remarks - moveControl

In general, if the specified control can be contained in the control and can be moved from the container that it is currently in, this method should succeed. However, in some cases, such as for the reference group control instance, controls cannot be moved.

## Method multiSelect

```xpp
public boolean multiSelect([boolean value])
```

### Parameters - multiSelect

value  

### Return Value - multiSelect

## Method name

Gets or sets the name that is used in code to identify a form, report, table, query, or other application object.

```xpp
public str name([str value])
```

### Parameters - name

value  

### Return Value - name

The name that is used in code to identify an application object.

### Remarks - name

The name property value of an object must meet the following criteria to avoid code conflicts:

-   It must start with a letter.
-   It cannot exceed 250 characters.
-   It can include numbers and underscore (\_) characters.
-   It cannot include punctuation or spaces.
-   Tables cannot have the same name as other public objects, such as extended data types, base enumerations, or classes.

## Method neededPermission

```xpp
public int neededPermission([int value])
```

### Parameters - neededPermission

value  

### Return Value - neededPermission

## Method rightMargin

```xpp
public int rightMargin([int value])
```

### Parameters - rightMargin

value  

### Return Value - rightMargin

## Method scrollbars

```xpp
public int scrollbars([int value])
```

### Parameters - scrollbars

value  

### Return Value - scrollbars

## Method securityKey

```xpp
public SecurityKeyId securityKey([SecurityKeyId value])
```

### Parameters - securityKey

value  

### Return Value - securityKey

## Method showColLabels

```xpp
public boolean showColLabels([boolean value])
```

### Parameters - showColLabels

value  

### Return Value - showColLabels

## Method showRowLabels

```xpp
public boolean showRowLabels([boolean value])
```

### Parameters - showRowLabels

value  

### Return Value - showRowLabels

## Method skip

Sets or returns a value that indicates whether the control is skipped when the user presses the TAB key to move to the control.

```xpp
public boolean skip([boolean value])
```

### Parameters - skip

value  
The value to assign to the skip property of the control.

### Return Value - skip

true if the control is skipped when the user presses the TAB key to move to the control; otherwise, false.

## Method style

```xpp
public int style([int value])
```

### Parameters - style

value  

### Return Value - style

## Method top

```xpp
public int top(int value, [int mode])
```

### Parameters - top

value  

<!-- -->

mode  

### Return Value - top

## Method topMargin

```xpp
public int topMargin([int value])
```

### Parameters - topMargin

value  

### Return Value - topMargin

## Method topMode

```xpp
public int topMode([int value])
```

### Parameters - topMode

value  

### Return Value - topMode

## Method topValue

```xpp
public int topValue([int value])
```

### Parameters - topValue

value  

### Return Value - topValue

## Method type

```xpp
public int type([int value])
```

### Parameters - type

value  

### Return Value - type

## Method userData

```xpp
public int userData([int value])
```

### Parameters - userData

value  

### Return Value - userData

## Method userDataItem

```xpp
public int userDataItem([int value])
```

### Parameters - userDataItem

value  

### Return Value - userDataItem

## Method userDataItems

```xpp
public int userDataItems([int value])
```

### Parameters - userDataItems

value  

### Return Value - userDataItems

## Method useUserLayout

```xpp
public boolean useUserLayout([boolean value])
```

### Parameters - useUserLayout

value  

### Return Value - useUserLayout

## Method verticalSpacing

```xpp
public int verticalSpacing([int value], [AutoMode mode])
```

### Parameters - verticalSpacing

value  

<!-- -->

mode  

### Return Value - verticalSpacing

## Method verticalSpacingMode

```xpp
public AutoMode verticalSpacingMode([AutoMode mode])
```

### Parameters - verticalSpacingMode

mode  

### Return Value - verticalSpacingMode

## Method verticalSpacingValue

```xpp
public int verticalSpacingValue([int value])
```

### Parameters - verticalSpacingValue

value  

### Return Value - verticalSpacingValue

## Method visible

```xpp
public boolean visible([boolean value])
```

### Parameters - visible

value  

### Return Value - visible

## Method visibleCols

```xpp
public int visibleCols([int value], [AutoMode mode])
```

### Parameters - visibleCols

value  

<!-- -->

mode  

### Return Value - visibleCols

## Method visibleColsMode

```xpp
public AutoMode visibleColsMode([AutoMode mode])
```

### Parameters - visibleColsMode

mode  

### Return Value - visibleColsMode

## Method visibleColsValue

```xpp
public int visibleColsValue([int value])
```

### Parameters - visibleColsValue

value  

### Return Value - visibleColsValue

## Method visibleRows

```xpp
public int visibleRows([int value], [AutoMode mode])
```

### Parameters - visibleRows

value  

<!-- -->

mode  

### Return Value - visibleRows

## Method visibleRowsMode

```xpp
public AutoMode visibleRowsMode([AutoMode mode])
```

### Parameters - visibleRowsMode

mode  

### Return Value - visibleRowsMode

## Method visibleRowsValue

```xpp
public int visibleRowsValue([int value])
```

### Parameters - visibleRowsValue

value  

### Return Value - visibleRowsValue

## Method width

Gets or sets the width of the control.

```xpp
public int width(int value, [int mode])
```

### Parameters - width

value  

<!-- -->

mode  

### Return Value - width

The width of the control in pixels.

### Remarks - width

Exact mode is used if the value parameter is omitted. Calculate the width according to the following table:

| Mode.           | Width calculation.                                                                       |
|-----------------|------------------------------------------------------------------------------------------|
| -1 Exact.       | The exact width in pixels of the controls is used.                                       |
| 0 Auto.         | The width of the control is calculated automatically and the value parameter is ignored. |
| 1 Column width. | The layout of the form determines the width of the control.                              |

The width and width calculation mode can be set separately.

## Method widthMode

Gets or sets the calculation mode of the width of the control.

```xpp
public int widthMode([int value])
```

### Parameters - widthMode

value  

### Return Value - widthMode

An integer value that indicates the current calculation mode.

### Remarks - widthMode

Calculate the width according to the following table:

| Mode.         | Width Calculation.                                                                       |
|---------------|------------------------------------------------------------------------------------------|
| Exact.        | The exact width in pixels of the controls is used.                                       |
| Auto.         | The width of the control is calculated automatically and the value parameter is ignored. |
| Column width. | The layout of the form determines the width of the control.                              |

The width of the control might change when the mode is set to auto or column width.

## Method widthValue

Gets or sets the width of the control.

```xpp
public int widthValue([int value])
```

### Parameters - widthValue

value  

### Return Value - widthValue

The width in pixels of the control.

### Remarks - widthValue

To change the width of the control, use the exact width calculation mode.

## Method registerOverrideMethod

```xpp
public void registerOverrideMethod(str methodToOverride, str objectMethodToCall, [Object overrideObject])
```

### Parameters - registerOverrideMethod

methodToOverride  

<!-- -->

objectMethodToCall  

<!-- -->

overrideObject  

