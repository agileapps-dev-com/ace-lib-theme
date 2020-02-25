## Date-picker
Below date picker variables are available for customizing.

### Variables

| Variable                          | Default value    | Description                               |
| ----------------------------------|----------------- |-------------------------------------------|
| $input-label-font-weight          | 400              | Defines the label font weight of input field.|
| $input-field-border-width         | 1px              | Defines the border thickness for input field.|
| $input-field-border-color         | #dee2e6          | Defines the border color for input field.|
| $input-field-background-color     | #fff             | Defines the background-color property for the input field.|
| $input-field-border-color-focus   | #6200ee          | Defines the focused border color property for the input field.|
| $input-field-border-radius        | 0                | Defines the border radius property for the input field.|
| $input-field-error-border-color   | #b00020          | Defines the border color property for the input field in error scenario.|
| $input-field-error-text-color     | #b00020          | Defines the text color property for the input field in error scenario.|
| $input-field-error-font-size      | 85%              | Defines the font size property for the input field in error scenario.|

Each of the above variable can be assigned with different values as below:
```scss
$input-field-border-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$input-field-error-font-size: 18px;
```
