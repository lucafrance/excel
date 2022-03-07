---
title: $ Symbol Basics
tags: [Dollar symbol]
---

## Create a cell reference

A cell reference links values in the given input field (cells).
The easiest form of cell reference is taking 1:1 the value from another cell.
Here e.g. the cell  `A4` contains the value `44` and the cell `B4` contains the formula `=A4`.
As result the value `44` is shown in the cell `B4`. 

![]({{ site.baseurl }}/assets/2022/dollar-basics/101-cell-reference.png)

## Relative reference

The default reference is the so-called *relative reference*.
It means that by copy/pasting the cell with the formula the column and row of the reference are updated accordingly. 

Here e.g. the cell `G8` contains the formula `=A8`.
By copying the cell `G8` over the range `G8:K12` the cell reference is updated accordingly.
The cell `K12` no longer contains the formula `=A8`, but `=E12`.
The *relative* distance of the reference stayed the same: 6 columns to the left and the same row. 

![]({{ site.baseurl }}/assets/2022/dollar-basics/102-no-dollar.png)

## Mixed reference

The reference to the column or row can be locked with the $ symbol.
A $ in front of the letter locks the reference to the column, a $ in front of the number locks the reference to the row.

Here e.g. the cell `G16` contains the formula `=$A16`.
Since the $ stands in front of the `A`, the reference to the column does not change when copying over the range `G16:K20`.
Since there is no $ in front of the `16`, the reference to the row is updated anyway.  

![]({{ site.baseurl }}/assets/2022/dollar-basics/103-dollar-column.png)

You can similarly lock the reference to the row with a dollar in front of the number.
Here e.g. the cell `G24` contains the formula `=A$24`.
When copying `G24` to the range `G24:K28`, the column stays the same while the column is updated.
 
![]({{ site.baseurl }}/assets/2022/dollar-basics/104-dollar-row.png)

This is a so-called *mixed reference*, as the dimension with the $ in the front is no longer relative.

## Absolute reference

You can define an *absolute cell reference* by writing a $ in front of bot the letter and the number.
The reference will always stay on the same cell, independently from where the formula gets copied.

Here e.g. the cell `G32` contains the formula `=$A$32`.
The reference now remains `=$A$32` over the whole range `G32:K36`.

![]({{ site.baseurl }}/assets/2022/dollar-basics/105-dollar-column-and-row.png)

## Shortcut

You can cycle all possible combinations of the $ by repeatedly pressing `F4`.
This way it is not necessary to enter the $ at the right spot manually.

> ![]({{ site.baseurl }}/assets/2022/dollar-basics/201-dollar-f4-1.png)
>
> `F4` ↓
>
> ![]({{ site.baseurl }}/assets/2022/dollar-basics/202-dollar-f4-2.png)
>
> `F4` ↓
>
> ![]({{ site.baseurl }}/assets/2022/dollar-basics/203-dollar-f4-3.png)
>
> `F4` ↓
>
> ![]({{ site.baseurl }}/assets/2022/dollar-basics/204-dollar-f4-4.png)
>
> `F4` ↓
>
> ![]({{ site.baseurl }}/assets/2022/dollar-basics/201-dollar-f4-1.png)

## Download

- [Example](/assets/2022/dollar-basics/01-dollar-basics-example-en.xlsx)

## Links

- [Microsoft Support - Create or change a cell reference](https://support.microsoft.com/en-us/office/create-or-change-a-cell-reference-c7b8b95d-c594-4488-947e-c835903cebaa)
- [Microsoft Support - Switch between relative, absolute, and mixed references](https://support.microsoft.com/en-us/office/switch-between-relative-absolute-and-mixed-references-dfec08cd-ae65-4f56-839e-5f0d8d0baca9)
