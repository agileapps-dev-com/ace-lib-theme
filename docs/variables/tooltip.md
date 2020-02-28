## Tooltip
Below tooltip variables are available for customizing.

| Variable                           | Default value        | Description                               |
| -----------------------------------|----------------------|-------------------------------------------|
| $ace-lib-tooltip-background-color  | #343a40              | Sets the background-color of tooltip.     |
| $ace-lib-tooltip-text-color        | #f8f9fa              | Sets the text-color of tooltip.           |
| $ace-lib-tooltip-font-size         | 80%                  | Sets the font-size of tooltip.            |
| $ace-lib-tooltip-max-width         | 100%                 | Sets the max-width for tooltip.           |
| $ace-lib-tooltip-margin            | 0 0 0 0              | Sets the margin property of tooltip.      |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-tooltip-background-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-tooltip-max-width: 5px;
```
