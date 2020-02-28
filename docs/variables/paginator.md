## Paginator
Below paginator variables are available for customizing.

| Variable                                      | Default value    | Description                                       |
| ----------------------------------------------|----------------- |---------------------------------------------------|
| $ace-lib-paginator-button-color               | #6200ee          | Sets the button color for paginator.              |
| $ace-lib-paginator-button-color-hover         | #6211ee          | Sets the button color in hover mode for paginator.|
| $ace-lib-paginator-button-disabled-opacity    | 0.65             | Sets the disabled-opacity property for paginator. |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-paginator-button-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-paginator-button-disabled-opacity: 0.5;
```
