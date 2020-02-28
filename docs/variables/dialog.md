## Dialog
Below dialog variables are available for customizing.

| Variable                                       | Default value        | Description                                                  |
| -----------------------------------------------|----------------------|--------------------------------------------------------------|
| $ace-lib-dialog-title-font-size                | 1.5rem               | Sets the title font size property of dialog.                 |
| $ace-lib-dialog-title-line-height              | 1.5                  | Sets the title line height of dialog.                        |
| $ace-lib-dialog-title-close-button-color       | #212529              | Sets the text color of close button.                         |
| $ace-lib-dialog-title-close-button-color-focus | #6200ee              | Sets the text color of close button in focus mode.           |
| $ace-lib-dialog-actions-border-width           | 1px                  | Sets the border thinkness of dialog action section.          |
| $ace-lib-dialog-actions-border-radius          | 0                    | Sets the border radius of dialog action section.             |
| $ace-lib-dialog-actions-primary-color          | #6200ee              | Sets the action section primary color property.              |
| $ace-lib-dialog-actions-primary-color-hover    | #6211ee              | Sets the action section primary color property in hover mode.|
| $ace-lib-dialog-actions-secondary-color        | #6211ee              | Sets the action section secondary color property.            |
| $ace-lib-dialog-actions-cancel-color           | #343a40              | Sets the text color of cancel button.                        |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-dialog-title-close-button-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-dialog-actions-border-width: 5px;
```
