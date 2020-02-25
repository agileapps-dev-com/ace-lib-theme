## Progressbar
Below progressbar variables are available for customizing.

### Variables

| Variable                              | Default value    | Description                                  |
| --------------------------------------|----------------- |----------------------------------------------|
| $progressbar-complete-color           | #6200ee          | Defines the color of completed part of the progressbar.|
| $progressbar-buffer-color             | #6211ee          | Defines the color of buffered part of the progressbar.|

Each of the above variable can be assigned with different values as below:
```scss
$progressbar-complete-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$progressbar-buffer-color: #00ff00;
```
