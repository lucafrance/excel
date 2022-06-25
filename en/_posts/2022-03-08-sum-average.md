---
title: SUM and AVERAGE Functions
tags: [SUM, AVERAGE, Tables]
last_update: 2022-06-25
---

## SUM function

The `SUM` function can take a cell range as argument.

![]({{ site.baseurl }}/assets/2022/sum-average/101-sum-one-range-en.png)

You can sum multiple ranges of potentially different sizes by separating them with a coma.

![]({{ site.baseurl }}/assets/2022/sum-average/102-sum-more-ranges-en.png)


## SUM with tables

A table column can be easily be used as argument of `SUM`.

> Type `=SUM(`.
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/201-sum-table-step1-en.png)
>
> Select one cell from the column which should be summed.
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/202-sum-table-step2-en.png)
>
> Press `Ctrl` + `Space bar`, the whole column is selected.
> 
> ![]({{ site.baseurl }}/assets/2022/sum-average/203-sum-table-step3-en.png)
>
> Done
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/204-sum-table-step4-en.png)

When adding or removing rows from the table the formula remains valid.
This is in general not the case without a table.

![]({{ site.baseurl }}/assets/2022/sum-average/301-sum-table-few-row-en.png)
![]({{ site.baseurl }}/assets/2022/sum-average/302-sum-table-many-rows-en.png)

## AVERAGE function

`AVERAGE` works similarly to `SUM`.

**`AVERAGE` on one range**

![]({{ site.baseurl }}/assets/2022/sum-average/401-average-one-range-en.png)

**`AVERAGE` on multiple ranges**

![]({{ site.baseurl }}/assets/2022/sum-average/402-average-more-ranges-en.png)

**`AVERAGE` on a table**

![]({{ site.baseurl }}/assets/2022/sum-average/403-average-table-en.png)

## Download

- [Example]({{ site.baseurl }}/assets/2022/sum-average/01-sum-average-example-en.xlsx)
- [Exercise]({{ site.baseurl }}/assets/2022/sum-average/02-sum-average-exercise-en.xlsx)
- [Solution]({{ site.baseurl }}/assets/2022/sum-average/03-sum-average-solution-en.xlsx)

## Links

- [Microsoft Support - SUM function](https://support.microsoft.com/en-us/office/sum-function-043e1c7d-7726-4e80-8f32-07b23e057f89)
- [Microsoft Support - AVERAGE function](https://support.microsoft.com/en-us/office/average-function-047bac88-d466-426c-a32b-8f33eb960cf6)
