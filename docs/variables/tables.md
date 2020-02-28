## Tables
Following table variables are available for customization:

| Variable                         | Default value     | Description                                                                                   |
| ---------------------------------|------------------ |-----------------------------------------------------------------------------------------------|
| $ace-lib-table-cell-padding      | 0.25rem           | Tabel cell padding.                                                                           |
| $ace-lib-table-select-cell-width | 0                 | Select column width. This is applicable only for the column with check boxes.                   |
| $ace-lib-table-color             | #212529           | The text color inside the table.                                                              |
| $ace-lib-table-bg                | null              | Background color for the table.                                                               |
| $ace-lib-table-accent-bg         | rgba(#000, 0.05)  | Background color for the stripped rows. Applicable only on `.ace-table-striped` applied table.|
| $ace-lib-table-hover-color       | #212529           | Text color for the hovered row. Applicable only for `.ace-table-hover` applied table.        |
| $ace-lib-table-hover-bg          | rgba(#000, 0.075) |Background color for the stripped rows. Applicable only for `.ace-table-hover` applied table. |
| $ace-lib-table-border-width      | 1px               | Border width for the table cells. Applicable only for `.ace-table-bordered` applied table.    |
| $ace-lib-table-border-color      | #dee2e6           | Border color for the table. Applicable only for `.ace-table-bordered` applied table.          |
| $ace-lib-table-head-bg           | #e9ecef           | Table header background color.                                                                 |
| $ace-lib-table-head-color        | #495057           | Table header text color.                                                                       |
| $ace-lib-table-striped-order     | odd               | The row order selector config for `.ace-table-striped` applied table.                          |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-table-head-bg : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-table-border-width: 2px;
```
### Table utility classes

| classes |  Description |
| -------------- |------------ |
| .ace-table-bordered    | Adds borders all around the table and between all the columns. |
| .ace-table-borderless    | Removes borders all around the table and between all the columns. |
| .ace-table-striped    | Applies Zebra-striping effect. |
| .ace-table-hover   | Placed here since it has to come after the potential zebra striping. |