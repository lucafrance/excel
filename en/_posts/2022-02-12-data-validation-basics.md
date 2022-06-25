---
title: Data Validation Basics
tags: [data validation]
last_update: 2022-06-25
---

`Data` > `Data Validation`

![]({{ site.baseurl }}/assets/2022/data-validation/ribbon-data-validation-en.png)

## Create a drop-down list (most common use)


You can limit the choice of values from a previously defined list.

![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-fruits-en.png)

To create this, click on `Data` > `Data Validation` > `Allow` > `List` and define the values in `Source`.

![]({{ site.baseurl }}/assets/2022/data-validation/data-validation-settings-list-en.png)

There are two ways to enter values.

- Define these explicitly separated by a comma.
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-explicit-en.png)
- Select a range of cells with the desired values.
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-source-1-en.png)
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-source-2-en.png)

An error message is shown when a value not belonging to the list is entered.

![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-pineapple-error-en.png)
 

## Allow other kind of data (not from a list)

The drop-down menu includes 95 % of the uses of data validation, but the functionality is called data validation, not drop-down list.
There are several other kind of data validations to define which are not a list and do not show a drop-down.

### Allow whole numbers

You can e.g. only allow whole numbers between *0* and *20*.
The error message will be shown when entering a negative number (like *-1*) or decimal number (like *3.7*).

![]({{ site.baseurl }}/assets/2022/data-validation/whole-number-0-20-en.png)

### Allow value between 0 % and 100 %

A percentage is interpreted by Excel as any other number, e.g. *21 % = 0.21*.
You can therefore define a percentage input field indirectly with a data validation between  *0 % = 0*, *100 % = 1*, and cell format as percentage.

![]({{ site.baseurl }}/assets/2022/data-validation/percent-0-100-validation-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/percent-0-100-format-en.png)

## Input message (useful even without data validation)

When allowing a values which do not belong to a list, there is in general no indication to the user of which ones can be entered.
You can provide such an indication through the `Input Message` tab.
It will be only shown when the cell is selected.

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-definition-1-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-example-1-en.png)

It is possible to define an input message even if `Any value` is allowed.
This is useful to enter remarks about the content of the cells.

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-definition-2-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-example-2-en.png)

## Error Alert

When entering a non-allowed value, a standard error alert is shown.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-standard-en.png)

This can be personalized on the `Error Alert` tab to show a more meaningful message.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-custom-def-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-custom-msg-en.png)

You can use other kind of error alerts.
These can be picked under `Style`.
- Stop
- Warning
- Information

![]({{ site.baseurl }}/assets/2022/data-validation/error-kind-dropdown-en.png)

### Stop

`Stop` is the default error alert.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-standard-en.png)

- `Retry` selects the cell again to edit the entered value.
- `Cancel` deletes the entered value. 
- `Help` opens the [data validation documentation](https://support.microsoft.com/en-us/office/apply-data-validation-to-cells-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249).

### Warning

With `Warning` a value can be entered anyway if confirmed.
E.g. you might have a situation where in most cases a past date should be entered, while it should still be possible to enter future dates sometimes.

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-standard-en.png)

- `Yes` leaves the entered value, even if it doesn't meet the allowance criterium.
- `No` selects the cell again to edit the value.
- `Cancel` deletes the entered value. 
- `Help` opens the [data validation documentation](https://support.microsoft.com/en-us/office/apply-data-validation-to-cells-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249).

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-custom-def-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-custom-msg-en.png)

### Information

With `Information` the value is entered without explicit confirmation.

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-standard-en.png)

- `OK` leaves the entered value, even if it doesn't meet the allowance criterium.
- `Cancel` deletes the entered value. 
- `Help` opens the [data validation documentation](https://support.microsoft.com/en-us/office/apply-data-validation-to-cells-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249).

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-custom-def-en.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-custom-msg-en.png)

### Deactivate error alert

You can choose to deactivate the error alert, in most cases it will be as if there is no data validation in place.

![]({{ site.baseurl }}/assets/2022/data-validation/error-no-message-en.png)

This is useful to show standard options from a drop-down list while still allowing to entered custom values.

![]({{ site.baseurl }}/assets/2022/data-validation/error-no-message-example-en.png)

## Download

- [Example]({{ site.baseurl }}/assets/2022/data-validation/01-data-validation-example-en.xlsx)
- [Exercise]({{ site.baseurl }}/assets/2022/data-validation/02-data-validation-exercise-en.xlsx)
- [Solution]({{ site.baseurl }}/assets/2022/data-validation/03-data-validation-solution-en.xlsx)
