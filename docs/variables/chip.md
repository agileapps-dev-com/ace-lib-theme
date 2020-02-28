## Chip
Following variables are available for customization:

| Variable                                   | Default value                 | Description                                       |
| -------------------------------------------|-------------------------------|---------------------------------------------------|
| $ace-lib-chip-background-color             | #6200ee                       | Sets the background color of chip.                |
| $ace-lib-chip-border-width                 | 0 0 0 0                       | Sets the border thickness of a chip.              |
| $ace-lib-chip-border-color                 | #dee2e6                       | Sets the border color of a chip.                  |
| $ace-lib-chip-border-radius                | 16px                          | Sets the border radius property of a chip.        |
| $ace-lib-chip-hover-focus-background-color | #6200ee                       | Sets the background color of chip in hover mode.  |
| $ace-lib-chip-hover-focus-color            | #6200ee                       | Sets the color of chip in hover mode.             |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-chip-background-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-chip-border-radius: 15%;
```
