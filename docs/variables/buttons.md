## Buttons
It is essential to apply the `.ace-btn` css class to all buttons which needs to be styled using the `ace-lib-theme`. 

Below variables are available for buttons:

| variable                    | Default value  | Description                                                                                                   |
| --------------------------- |--------------- |-------------------------------------------------------------------------------------------------------------- |
|$ace-lib-btn-padding         | 0.5rem 0.75rem | padding for the button. The value should be valid as per the css standards (`top right bottom left` pattern). |;
|$ace-lib-btn-white-space     | null           |  White space definition for the button. Set to `nowrap` to prevent text wrapping |
|$ace-lib-btn-line-height     | 1.5            | line-height property value|
|$ace-lib-btn-border-width    | 1px            | Border width property for the button|
|$ace-lib-btn-disabled-opacity| 0.65           | Opacity factor applied to the disabled button.|
|$ace-lib-btn-border-radius   | 0              | Allows for customizing button radius independently from global border radius|

> **Notes:** 
* The button variant classes will be availble for only those elements which has the `.ace-btn` class attached.
* Darker shade of the assigned color variant is used for the hover and focused states.
* The text color is calcuated in contrast with the assigned background color.
* If the `$theme-colors` variable contains more number of custom color maps, corresponding utility css classes will be generated.

Below button variants are available for buttons. 

1. **Base variants:**

    Creates a simple button.
    
    | class          | Default value | Description                                     |
    | -------------- |---------------|------------------------------------------------ |
    | .ace-primary   | #6200ee       | The button base variant with the primary color. |
    | .ace-secondary | #03dac6       | The button base variant with the secondary color.  |
    | .ace-error     | #b00020       | The button base variant with the error color.  |
    | .ace-light     | #f8f9fa       | The button base variant with the light color. Note: This variant color will be visible only on a dark background. |
    | .ace-dark      | #343a40       | The button base variant with the dark color. Note: This variant color will be visible only on a light background.|

    ### Sample usage:
    ```html
    <button class="ace-btn ace-primary">click me </button>

    <!-- If the '$theme-colors' map contains a color map named, "purple"-->
    <button class="ace-btn ace-purple">click me </button> 

    ```

2. **Outline variants:**  
    Creates an outlined button.
    
    | class                   | Default value | Description                             |
    | ----------------------- |---------------|-----------------------------------------|
    | .ace-outline-primary    | #6200ee       | Outline variant with the primary color. |
    | .ace-outline-secondary  | #03dac6       | Outline variant with the secondary color.  |
    | .ace-outline-error      | #b00020       | Outline variant with the error color.  |
    | .ace-outline-light      | #f8f9fa       | Outline variant with the light color. Note: This variant color will be visible only on a dark background. |
    | .ace-outline-dark       | #343a40       | Outline variant with the dark color. Note: This variant color will be visible only on a light background.|

    ### Sample usage:
    ```html
    <button class="ace-btn ace-outline-primary">click me </button>

    <!-- If the '$theme-colors' map contains a color map named, "purple"-->
    <button class="ace-btn ace-outline-purple">click me </button> 
    ```

>