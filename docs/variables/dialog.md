## Dialog
Following dialog variables are available for customization:

| Variable                                       | Default value        | Description                                                  |
| -----------------------------------------------|----------------------|--------------------------------------------------------------|
| $ace-lib-dialog-title-font-size                | 1.5rem               | Sets the font size property for the title in a dialog.                 |
| $ace-lib-dialog-title-line-height              | 1.5                  | Sets the line height for the title in a dialog.                        |
| $ace-lib-dialog-title-close-button-color       | #212529              | Sets the text color of close button.                         |
| $ace-lib-dialog-title-close-button-color-focus | #6200ee              | Sets the text color of close button in focus mode.           |
| $ace-lib-dialog-actions-border-width           | 1px                  | Sets the border thickness of dialog action section.          |
| $ace-lib-dialog-actions-border-radius          | 0                    | Sets the border radius of the dialog action section.             |
| $ace-lib-dialog-actions-primary-color          | #6200ee              | Sets the primary color property for the action section.              |
| $ace-lib-dialog-actions-primary-color-hover    | #6211ee              | Sets the primary color property in hover mode for the action section.|
| $ace-lib-dialog-actions-secondary-color        | #6211ee              | Sets the secondary color property for the action section.            |
| $ace-lib-dialog-actions-cancel-color           | #343a40              | Sets the text color for the cancel button.                        |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-dialog-title-close-button-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-dialog-actions-border-width: 5px;
```
