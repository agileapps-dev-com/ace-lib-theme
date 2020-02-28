## Menu
Below variables are available for customizing.

| Variable                             | Default value                  | Description                                               |
| -------------------------------------|------------------------------- |-----------------------------------------------------------|
| $ace-lib-menu-border-color           | #dee2e6                        | Sets the border color of menu list item.                  |
| $ace-lib-menu-box-shadow             | 0 0.5rem 1rem rgba(#000, 0.15) | Sets the box shadow property of menu list item.           |
| $ace-lib-menu-background-color       | #fff                           | Sets the background color of menu item.                   |
| $ace-lib-menu-hover-background-color | #6200ee                        | Sets the background color of menu item in hover mode.     |
| $ace-lib-menu-hover-color            | #6200ee                        | Sets the color of menu item in hover mode.                |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-menu-border-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-menu-hover-color: #00ff00;
```
