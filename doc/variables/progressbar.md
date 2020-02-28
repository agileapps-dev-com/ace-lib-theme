## Progressbar
Below progressbar variables are available for customizing.

| Variable                                      | Default value    | Description                                         |
| ----------------------------------------------|----------------- |-----------------------------------------------------|
| $ace-lib-progressbar-complete-color           | #6200ee          | Sets the color of completed part of the progressbar.|
| $ace-lib-progressbar-buffer-color             | #6211ee          | Sets the color of buffered part of the progressbar. |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-progressbar-complete-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-progressbar-buffer-color: #00ff00;
```
