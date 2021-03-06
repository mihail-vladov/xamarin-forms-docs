---
title: Elements Display Mode
page_title: Elements Display Mode
description: Check our &quot;Elements Display Mode&quot; documentation article for Telerik Calendar for Xamarin control.
position: 1
slug: calendar-styling-display-mode
---

# Elements Display Mode

Sometimes you would like to change the appearance of the calendar by hiding the day names or week numbers. This article will explain how you can acheive this.

The calendar provides properties that control the visibility of its elements.

- **DayNamesDisplayMode** (DisplayMode): Gets or sets a value that specifies whether the day names will be visible.
- **WeekNumbersDisplayMode** (DisplayMode): Gets or sets a value that specifies whether the day names will be visible.

The two described properties are both of type **DisplayMode**, which is enumeration and has the following values:

- **Show**: The element will be visible.
- **Hide**: The element will not be visible.
- **Automatic**: The visibility of the element will be determined by the value defined in the platform specific resources.

#### Example

This example demonstrates how you can display the week numbers and hide the day names of the calendar:

<snippet id='calendar-styling-elements-display-mode'/>

Here are the results from the code above:

![Display Mode](images/elements-display-mode.png "Display mode")
