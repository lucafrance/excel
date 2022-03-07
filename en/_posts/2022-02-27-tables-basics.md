---
title: Tables Basics
tags: [Tables, Names]
last_update: 2022-03-05
---

## Creating a table

*Table*  is a general term, but it also describes a specific Excel functionality.
These calculations could for example be called a table, but they are not yet a *Table* according to Excel.

![]({{ site.baseurl }}/assets/2022/tables-basics/101-example-cell-range-en.png)

To create a table first select the corresponding cell range, then click on `Home` > `Format as Table`.

![]({{ site.baseurl }}/assets/2022/tables-basics/102-table-button-on-ribbon-en.png)

You can pick any table style.
They all offer the same functionalities and can be changed afterwards.

![]({{ site.baseurl }}/assets/2022/tables-basics/103-table-template-menu-en.png)

The cell range can be changed if necessary.
If you already selected the correct cell range, click directly on `OK`.

![]({{ site.baseurl }}/assets/2022/tables-basics/104-confirm-range-en.png)

## Main advantages of tables 

### Easier formulas

The header of a table is recognized automatically and can be used directly in formulas.
A formula created this way is much easier to follow.

> Formula with table
> ![]({{ site.baseurl }}/assets/2022/tables-basics/201-formula-with-table-en.png)

> Formula without table
> ![]({{ site.baseurl }}/assets/2022/tables-basics/202-formula-without-table-en.png)

### Automatic sort and filter

A table creates automatically a *filter* for each column.

![]({{ site.baseurl }}/assets/2022/tables-basics/301-sort-filter-table-en.png)

This is the same kind of filter which can be created over `Home` > `Sort & Filter` > `Filter`.
It is recommended to create a table as soon as a filter is needed.
This provides directly all the advantages of a table.

## Table Design tab

When selecting a table, an additional *Table Design* tab is shown on the ribbon.

![]({{ site.baseurl }}/assets/2022/tables-basics/401-ribbon-table-en.png)

### Table name 

Each table automatically gets a name, which is show together with other cell names on the Name Manager.
Differently from other kind of names the field `Refers to` cannot be updated, as this is tied to the table range.

![]({{ site.baseurl }}/assets/2022/tables-basics/501-table-in-name-manager-en.png)

The table name can be changed over `Table Design` > `Properties`.

![]({{ site.baseurl }}/assets/2022/tables-basics/502-ribbon-table-properties-en.png)

### Total Row

You can add a *Total Row* over `Table Design` > `Table Style Options`.

![]({{ site.baseurl }}/assets/2022/tables-basics/601-checkbox-total-row-en.png)

A different operation can be defined for each column on the total row, e.g. sum, average, max.

![]({{ site.baseurl }}/assets/2022/tables-basics/603-total-operation-drop-down-en.png)

When applying a filter on one or more columns, then the operations on the total row are only calculated for the filtered values.
Here is shown an example with the average of the net unit price and the sum of the total gross price.

> All rows
> ![]({{ site.baseurl }}/assets/2022/tables-basics/604-subtotal-without-filter-en.png)

> Filtered by year 2022
> ![]({{ site.baseurl }}/assets/2022/tables-basics/605-subtotal-with-filter-en.png)

## Download

- [Example]({{ site.baseurl }}/assets/2022/tables-basics/01-tables-basics-example-en.xlsx)
