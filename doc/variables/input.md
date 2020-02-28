## Input
Below date picker variables are available for customizing.

| Variable                                       | Default value | Description                                                    |
| -----------------------------------------------|---------------|----------------------------------------------------------------|
| $ace-lib-input-label-font-weight               | 400           | Sets the label font weight of input field.                     |
| $ace-lib-input-field-border-width              | 1px           | Sets the border thickness for input field.                     |
| $ace-lib-input-field-border-color              | #dee2e6       | Sets the border color for input field.                         |
| $ace-lib-input-field-background-color          | #fff          | Sets the background-color property for the input field.        |
| $ace-lib-input-field-text-color                | #212529       | Sets the background-color property for the input field.        |
| $ace-lib-input-field-disabled-background-color | #f8f9fa       | Sets the background-color property for the input field.        |
| $ace-lib-input-field-background-color-focus    | #f8f9fa       | Sets the background-color property for the input field.        |
| $ace-lib-input-field-border-color-focus        | #6200ee       | Sets the focused border color property for the input field.    |
| $ace-lib-input-field-border-radius             | 0             | Sets the border radius property for the input field.           |
| $ace-lib-input-field-placeholder-color         | #6200ee       | Sets the placeholder text color for the input field.           |
| $ace-lib-input-field-error-border-color        | #b00020       | Sets the border color for the input field in error state.      |
| $ace-lib-input-field-error-text-color          | #b00020       | Sets the text color for the input field in error state.        |
| $ace-lib-input-field-error-font-size           | 85%           | Sets the font size property for the input field in error state.|

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-input-field-border-color : map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-input-field-error-font-size: 18px;
```
