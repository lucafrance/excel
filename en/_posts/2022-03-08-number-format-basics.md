---
title: Number Formats Basics
tags: [Number formats]
---

## What are number formats?

When adding `0.5`, `50%`, `12:00` O' Clock, `€0,50` in Excel, you get `2`.
Why?
For Excel they are all the same value. 

![]({{ site.baseurl }}/assets/2022/number-format-basics/101-sum-one-half-en.png)

Excel only knows two kind of data: text and numbers.
Text is text, everything else is a number.
- A number is a number.
- A currency is a number.
- A date is a number.
- A time is a number.
- A percentage is a number. 

Excel saves, reads and computes numbers.
The way a number is shown (number format) is a separate property of the cell.
The number format is not directly related to the value in the cell, like its color.

| Value | Kind | Possible representation with number format. |
| --- | --- | --- |
| abcdefg | Text | abcdefg |
| abc123 | Text | abc123 |
| 44628,61624 | Number | 08/03/2022 14:51 |
| 0,121099472 | Number | 12% |
| 4827,611261 | Number | 4,827.61 |
| 29,91 | Number | 29.91 € |

## Adjusting the number format

There are two ways to adjust the number format.
1. Over `Home` > `Number`.
![]({{ site.baseurl }}/assets/2022/number-format-basics/201-ribbon-number-en.png)
1. Over the `Format Cells` window with `Right mouse klick` > `Format cells...` or the shortcut `Ctrl` + `1`. 
![]({{ site.baseurl }}/assets/2022/number-format-basics/202-context-menu-number-en.png)

Over `Home` > `Number` most categories are available, but not all options of the `Format cells` window.  

![]({{ site.baseurl }}/assets/2022/number-format-basics/203-format-categories-ribbon-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/204-cell-format-window-en.png)

## Basic number formats

### General number formats

This is the default number format.
There are no options.

![]({{ site.baseurl }}/assets/2022/number-format-basics/301-dropdown-standard-category-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/302-window-standard-category-en.png)

### *Number* number format

![]({{ site.baseurl }}/assets/2022/number-format-basics/401-dropdown-number-category-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/402-window-number-category-en.png)

This number format allows to show the thousands separator and define how many decimal places to show.

**Use 1000 separator**

![]({{ site.baseurl }}/assets/2022/number-format-basics/403-ribbon-thousands-separator-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/404-window-thousands-separator-en.png)

**Add or remove decimal places**

![]({{ site.baseurl }}/assets/2022/number-format-basics/405-ribbon-decimal-places-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/406-window-decimal-places-en.png)

### Currency and accounting number format

In practice similar to number format, but with a currency symbol in the front.
In general I recommend using accounting over currency. 

![]({{ site.baseurl }}/assets/2022/number-format-basics/501-ribbon-accounting-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/502-dropdown-accounting-en.png)

You define the number of decimal places as in the number format and the currency symbol.

![]({{ site.baseurl }}/assets/2022/number-format-basics/503-window-accounting-en.png)

The currency does not play any role for Excel, you can mix currencies as you please.
Here e.g. is a sum of euro with pound sterling, US-dollar and bitcoin. 

![]({{ site.baseurl }}/assets/2022/number-format-basics/504-sum-different-currencies-en.png)

### Percentage number format

The % symbol means "divided by 100".
For Excel a percentage is a normal number with the decimal place shifted twice to the right.

| Percentage | Number |
| --- | --- |
| 20%	| 0.2 | 
| 9%	| 0.09 | 
| 30%	| 0.3 | 
| 38%	| 0.38 | 
| 52%	| 0.52 | 
| 2%	| 0.02 | 
| 63%	| 0.63 | 
| 16%	| 0.16 | 
| 26%	| 0.26 | 
| 84%	| 0.84 | 
| 26%	| 0.26 | 
 
If you insert a value with the percent symbol, the percent number format is automatically applied.

![]({{ site.baseurl }}/assets/2022/number-format-basics/601-percent-input-cell-en.png)

Alternatively you can define the percentage number format for an existing number afterwards.

![]({{ site.baseurl }}/assets/2022/number-format-basics/602-ribbon-percentage-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/603-dropdown-percentage-en.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/604-window-percentage-en.png)

## Download

- [Example]({{ site.baseurl }}/assets/2022/number-format-basics/01-number-format-basics-example-en.xlsx)
- [Exercise]({{ site.baseurl }}/assets/2022/number-format-basics/02-number-format-basics-exercise-en.xlsx)
- [Solution]({{ site.baseurl }}/assets/2022/number-format-basics/03-number-format-basics-solution-en.xlsx)

## Links

- [Microsoft Support - Available number formats in Excel](https://support.microsoft.com/en-us/office/available-number-formats-in-excel-0afe8f52-97db-41f1-b972-4b46e9f1e8d2)
