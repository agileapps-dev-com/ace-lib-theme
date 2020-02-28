## Tablist
Following tab-list variables are available for customization:

| Variable                                               | Default value        | Description                                                  |
| -------------------------------------------------------|----------------------|--------------------------------------------------------------|
| $ace-lib-tablist-header-border-width                   | 0 0 1px 0            | Defines the border thickness of the tab header.|
| $ace-lib-tablist-header-border-color                   | transparent transparent #dee2e6 transparent   | Defines the border color tabs header. |
| $ace-lib-tablist-header-tab-foucsed-color              | #212529              | Defines the color of tab header in focused mode. |
| $ace-lib-tablist-header-tab-active-link-bar-color      | #03dac6              | Defines the link bar color of the active tab. |
| $ace-lib-tablist-content-border-width                  | 0 0 0 0              | Defines the border thickness of the tab content. |
| $ace-lib-tablist-content-border-color                  | #212529              | Defines the border color of the tab content. |
| $ace-lib-tablist-content-padding                       | 0 0 0 0              | Defines the padding property of the tab content. |

You can assign different values to each of the above variables as follows:
```scss
$ace-lib-tablist-header-border-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-tablist-content-padding: 2px;
```
