## Datepicker
Below date picker variables are available for customizing.

| Variable                                          | Default value    | Description                               |
| --------------------------------------------------|------------------|-------------------------------------------|
| $ace-lib-datepicker-background-color              | #fff             | Sets the background color for date-picker.|
| $ace-lib-datepicker-border-width                  | 1px              | Sets the border thickness for datepicker.|
| $ace-lib-datepicker-border-color                  | #dee2e6          | Sets the border color for datepicker.|
| $ace-lib-datepicker-control-btn-background-color  | #fff             | Sets the background-color for the datepicker.|
| $ace-lib-datepicker-btn-outline-style             | 1px auto #6200ee | Sets the outline property for the datepicker.|
| $ace-lib-datepicker-control-btn-border-radius     | 0                | Sets the border radius of control button for the datepicker.|
| $ace-lib-datepicker-table-cell-radius             | 0                | Sets the cell radius property for the datepicker.|
| $ace-lib-datepicker-table-header-color            | #212529          | Sets the header color property for the datepicker.|
| $ace-lib-datepicker-table-header-font-weight      | 400              | Sets the font weight property of header for the datepicker.|
| $ace-lib-datepicker-date-focus-background-color   | #343a40          | Sets the focused cell background color for the datepicker.|
| $ace-lib-datepicker-date-selected-background-color| #6200ee          | Sets the selected cell background color for the datepicker.|

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-datepicker-date-focus-background-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-datepicker-border-width: 2px;
```
