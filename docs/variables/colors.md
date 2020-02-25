
## Colors
Below color variables are available:
### 1. $theme-colors
It is a color [map](https://sass-lang.com/documentation/values/maps). For every color mentioned in this map, corresponding utility css color classes will be generated.

The default map contains the below color Map:
```scss
$theme-colors: (
    "primary": #6200ee,
    "secondary": #03dac6,
    "error": #b00020,
    "light": #f8f9fa,
    "dark": #343a40
  );
``` 
The default `$theme-colors` variable contains only 5 colors, but more number of such colors can be added to this map. See the example below:

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

The `$theme-colors` map values can be accessed as shown below:
```scss
map-get($theme-colors, "purple");
```
#### Utility color classes for $theme-colors map:
Separate color utility classes will be generated for every single color map present in the `$theme-colors` variable.

Below color utility classes are available.

1. **Background colors**: The background color utility classes are prefixed with `ace-bg-`. This can be used to style any elements in the page.

    Below background utility colors are available by default:
    
    | class | Default value | Description |
    | -------------- |------------ |------------ |
    | .ace-bg-primary    | #6200ee | Can be used to highlight the background of any element with the primary color. |
    | .ace-bg-secondary    | #03dac6 | Can be used to highlight the background of any element with the secondary color. |
    | .ace-bg-error    | #b00020 | Can be used to highlight the background of any element with the error color.  |
    | .ace-bg-light    | #f8f9fa | Can be used to highlight the background of any element with the light color. |
    | .ace-bg-dark    | #343a40 | Can be used to highlight the background of any element with the dark color. |
    
    > **Note:** Any colors added to the  `$theme-colors` variable will have a corresponding background color class.

    ##### Sample usage:
    ```html
        <div class="ace-bg-primary">.ace-bg-primary</div>
    ```
2. **Text colors**: The text color utility classes are prefixed with `ace-text-`.
    Below text utility colors are available by default:
    
    | class | Default value | Description |
    | -------------- |------------ |------------ |
    | .ace-text-primary    | #6200ee | Can be used to highlight the text content with the primary color. |
    | .ace-text-secondary    | #03dac6 | Can be used to highlight the text content with the secondary color. |
    | .ace-text-error    | #b00020 | Can be used to highlight the text content with the error color.  |
    | .ace-text-light    | #f8f9fa | Can be used to highlightthe text content with the light color. |
    | .ace-text-dark    | #343a40 | Can be used to highlight the text content with the dark color. |
    
    > **Note:** Any colors added to the  `$theme-colors` variable will have a corresponding text color class.
    
    ##### Sample usage: 
    ```html
        <p class="ace-text-primary">.ace-text-primary</p>
    ```
