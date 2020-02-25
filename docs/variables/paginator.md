## Paginator
Below paginator variables are available for customizing.

### Variables

| Variable                              | Default value    | Description                               |
| --------------------------------------|----------------- |-------------------------------------------|
| $paginator-button-color               | #6200ee          | Defines the button color for paginator.|
| $paginator-button-color-hover         | #6211ee          | Defines the button color in hover mode for paginator.|
| $paginator-button-disabled-opacity    | 0.65             | Defines the disabled-opacity property for paginator.|

Each of the above variable can be assigned with different values as below:
```scss
$paginator-button-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$paginator-button-disabled-opacity: 0.5;
```
