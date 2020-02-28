## Paginator
Following paginator variables are available for customization:

| Variable                                      | Default value    | Description                                       |
| ----------------------------------------------|----------------- |---------------------------------------------------|
| $ace-lib-paginator-button-color               | #6200ee          | Sets the button color for paginator.              |
| $ace-lib-paginator-button-color-hover         | #6211ee          | Sets the button color in the hover mode for paginator.|
| $ace-lib-paginator-button-disabled-opacity    | 0.65             | Sets the disabled-opacity property for the paginator. |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-paginator-button-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-paginator-button-disabled-opacity: 0.5;
```
