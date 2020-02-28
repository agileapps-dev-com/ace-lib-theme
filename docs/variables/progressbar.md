## Progressbar
Following progressbar variables are available for customization:

| Variable                                      | Default value    | Description                                         |
| ----------------------------------------------|----------------- |-----------------------------------------------------|
| $ace-lib-progressbar-complete-color           | #6200ee          | Sets the color for the completed part of the progressbar.|
| $ace-lib-progressbar-buffer-color             | #6211ee          | Sets the color for the buffered part of the progressbar. |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-progressbar-complete-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-progressbar-buffer-color: #00ff00;
```
