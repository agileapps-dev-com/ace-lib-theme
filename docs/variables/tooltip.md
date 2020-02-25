$tooltip-background-color: theme-color("dark") !default;
$tooltip-font-size: 80% !default;
$tooltip-max-width: 100% !default;
$tooltip-margin: 0 0 0 0 !default;



## Tooltip
Below tooltip variables are available for customizing.

### Variables

| Variable                   | Default value        | Description                               |
| ---------------------------|----------------------|-------------------------------------------|
| $tooltip-background-color  | #343a40              | Defines the background-color of tooltip.  |
| $tooltip-text-color        | #f8f9fa              | Defines the text-color of tooltip.  |
| $tooltip-font-size         | 80%                  | Defines the font-size of tooltip.         |
| $tooltip-max-width         | 100%                 | Defines the max-width for tooltip.        |
| $tooltip-margin            | 0 0 0 0              | Defines the margin property of tooltip.   |

Each of the above variable can be assigned with different values as below:
```scss
$tooltip-background-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$tooltip-max-width: 5px;
```
