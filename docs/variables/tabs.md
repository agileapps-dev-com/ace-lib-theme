## Tablist
Below tablist variables are available for customizing.

### Variables

| Variable                                   | Default value        | Description                                                  |
| -------------------------------------------|----------------------|--------------------------------------------------------------|
| $tab-header-border-width                   | 0 0 1px 0            | Defines the border thikness of tab header.|
| $tab-header-border-color                   | transparent transparent #dee2e6 transparent   | Defines the border color tabs header. |
| $tab-header-tab-foucsed-color              | #212529              | Defines the color of tab header in focused mode. |
| $tab-header-tab-active-link-bar-color      | #03dac6              | Defines the link bar color of active tab. |
| $tab-content-border-width                  | 0 0 0 0              | Defines the border thikness of tab content. |
| $tab-content-border-color                  | #212529              | Defines the border color of tab content. |
| $tab-content-padding                       | 0 0 0 0              | Defines the padding property of tab content. |

Each of the above variable can be assigned with different values as below:
```scss
$tab-header-border-color: map-get($theme-colors, "purple"); // This map color must be present in the $theme-colors map.

$tab-content-padding: 2px;
```
