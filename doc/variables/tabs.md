## Tablist
Below tab-list variables are available for customizing.

| Variable                                               | Default value        | Description                                                  |
| -------------------------------------------------------|----------------------|--------------------------------------------------------------|
| $ace-lib-tablist-header-border-width                   | 0 0 1px 0            | Defines the border thikness of tab header.|
| $ace-lib-tablist-header-border-color                   | transparent transparent #dee2e6 transparent   | Defines the border color tabs header. |
| $ace-lib-tablist-header-tab-foucsed-color              | #212529              | Defines the color of tab header in focused mode. |
| $ace-lib-tablist-header-tab-active-link-bar-color      | #03dac6              | Defines the link bar color of active tab. |
| $ace-lib-tablist-content-border-width                  | 0 0 0 0              | Defines the border thikness of tab content. |
| $ace-lib-tablist-content-border-color                  | #212529              | Defines the border color of tab content. |
| $ace-lib-tablist-content-padding                       | 0 0 0 0              | Defines the padding property of tab content. |

Each of the above variable can be assigned with different values as below:
```scss
$ace-lib-tablist-header-border-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$ace-lib-tablist-content-padding: 2px;
```
