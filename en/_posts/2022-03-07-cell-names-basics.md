---
title: Cell Names Basics
tags: [Names]
---

Formulas can be understood and manged much easier with *names*.
Names can be defined for cell ranges, functions, constants, or tables.
A name is valid for the whole workbook and can be updated or renamed anytime.

Here is an example of a formula with and without names.
Names show a concrete description of the values, rather than abstract cell addresses.

> ![]({{ site.baseurl }}/assets/2022/cell-names-basics/101-formula-no-names-en.png)
> Formula without names

> ![]({{ site.baseurl }}/assets/2022/cell-names-basics/102-formula-with-names-en.png)
> Formula with names
​​​​​​​

## Naming a cell

1. Select the cell which should be named.
1. Enter a name in the name field and confirm it with `Enter`.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/201-define-name-en.png)

Names cannot include spaces.
You can alternatively use an underscore (e.g. `number_sold_mangos`) or camel case (e.g. `numberSoldMangos`).

## Using names in formulas

To use a name in a formula you just need to type it down.
Suggestions are shown with the first letters, which can be confirmed with `Tab` or by clicking on them.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/301-name-in-formulas-1-en.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/302-name-in-formulas-2-en.png)

## Managing names

Names can be managed with the *Name Manager*.
You can open it over `Formula` > `Name Manager` or with the shortcut `Ctrl` + `F3`.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/401-name-manager-on-ribbon-en.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/402-name-manager-en.png)

By clicking `Edit...` you can change the name (field `Name:`) and corresponding cell reference (field `Refers to:`).

![]({{ site.baseurl }}/assets/2022/cell-names-basics/403-edit-button-en.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/404-edit-window-en.png)

You can delete a name by clicking `Delete`.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/405-delete-buton-en.png)

If a deleted name has already been used in a formula, then a `#NAME?` error is shown.
To fix the error the name must either be defined again or removed from the formula.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/406-name-error-en.png)

## Column names and use of the @ symbol

By selecting a column it is possible to define a name similarly to a single cell.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/501-define-column-name-en.png)

By using the @ symbol with a column name, Excel retrieves the value from the column and on the same row as the formula.

​​​​​​​
![]({{ site.baseurl }}/assets/2022/cell-names-basics/502-at-column-name-1-en.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/503-at-column-name-2-en.png)

**Hint** The @ symbol is only necessary starting with Office 2019.
In previous versions of Office the statement works the same without the @ symbol. 

## Download

- [Example]({{ site.baseurl }}/assets/2022/cell-names-basics/01-cell-names-basics-example-en.xlsx)

## Links

- [Microsoft Support - Define and use names in formulas](https://support.microsoft.com/en-us/office/define-and-use-names-in-formulas-4d0f13ac-53b7-422e-afd2-abd7ff379c64)
