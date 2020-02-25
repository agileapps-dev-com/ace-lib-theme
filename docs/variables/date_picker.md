## Date-picker
Below date picker variables are available for customizing.

### Variables

| Variable                                  | Default value    | Description                               |
| ------------------------------------------|----------------- |-------------------------------------------|
| $datepicker-background-color              | #fff             | Defines the background color for date-picker.|
| $datepicker-border-width                  | 1px              | Defines the border thickness for datepicker.|
| $datepicker-border-color                  | #dee2e6          | Defines the border color for datepicker.|
| $datepicker-control-btn-background-color  | #fff             | Defines the background-color for the datepicker.|
| $datepicker-btn-outline-style             | 1px auto #6200ee | Defines the outline property for the datepicker.|
| $datepicker-control-btn-border-radius     | 0                | Defines the border radius of control button for the datepicker.|
| $datepicker-table-cell-radius             | 0                | Defines the cell radius property for the datepicker.|
| $datepicker-table-header-color            | #212529          | Defines the header color property for the datepicker.|
| $datepicker-table-header-font-weight      | 400              | Defines the font weight property of header for the datepicker.|
| $datepicker-date-focus-background-color   | #343a40          | Defines the focused cell background color for the datepicker.|
| $datepicker-date-selected-background-color| #6200ee          | Defines the selected cell background color for the datepicker.|

Each of the above variable can be assigned with different values as below:
```scss
$datepicker-date-focus-background-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$datepicker-border-width: 2px;
```
