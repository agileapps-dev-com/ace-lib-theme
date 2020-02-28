
## Colors
Following color variables are available:
### 1. $theme-colors
It is a color [map](https://sass-lang.com/documentation/values/maps). For every color mentioned in this map, corresponding utility css color classes are generated.

The default map contains the following color Map:
```scss
$theme-colors: (
    "primary": #6200ee,
    "secondary": #03dac6,
    "error": #b00020,
    "light": #f8f9fa,
    "dark": #343a40
  );
``` 
The default `$theme-colors` variable contains only 5 colors, but you can add more number of such colors to this map. See the following example:

```scss
$theme-colors: (
    "primary": #6200ee,
    "secondary": #03dac6,
    "error": #b00020,
    "light": #f8f9fa,
    "dark": #343a40,
    "blue-gray":#607D8B,
    "blue-color":#03A9F4,
    "purple":#9C27B0
  );
```

You can access the `$theme-colors` map values as shown here:
```scss
map-get($theme-colors, "purple");
```
#### Utility color classes for $theme-colors map:
Separate color utility classes are generated for every single color map present in the `$theme-colors` variable.

Following color utility classes are available:

1. **Background colors**: The background color utility classes are prefixed with `ace-bg-`. You can use this to style any elements in the page.

    Following background utility colors are available by default:
    
    | class | Default value | Description |
    | -------------- |------------ |------------ |
    | .ace-bg-primary    | #6200ee | Use this to highlight the background of any element with the primary color. |
    | .ace-bg-secondary    | #03dac6 | Use this to highlight the background of any element with the secondary color. |
    | .ace-bg-error    | #b00020 | Use this to highlight the background of any element with the error color.  |
    | .ace-bg-light    | #f8f9fa | Use this to highlight the background of any element with the light color. |
    | .ace-bg-dark    | #343a40 | Use this to highlight the background of any element with the dark color. |
    
    > **Note:** Any colors added to the  `$theme-colors` variable have a corresponding background color class.

    ##### Sample usage:
    ```html
        <div class="ace-bg-primary">.ace-bg-primary</div>
    ```
2. **Text colors**: The text color utility classes are prefixed with `ace-text-`.
    Following text utility colors are available by default:
    
    | class | Default value | Description |
    | -------------- |------------ |------------ |
    | .ace-text-primary    | #6200ee | Use this to highlight the text content with the primary color. |
    | .ace-text-secondary    | #03dac6 | Use this to highlight the text content with the secondary color. |
    | .ace-text-error    | #b00020 | Use this to highlight the text content with the error color.  |
    | .ace-text-light    | #f8f9fa | Use this to highlightthe text content with the light color. |
    | .ace-text-dark    | #343a40 | Use this to highlight the text content with the dark color. |
    
    > **Note:** Any colors you add to the  `$theme-colors` variable will have a corresponding text color class.
    
    ##### Sample usage: 
    ```html
        <p class="ace-text-primary">.ace-text-primary</p>
    ```
