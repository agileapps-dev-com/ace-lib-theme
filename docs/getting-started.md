# Theming the ace-lib Components
## What is an 'ace-lib-theme'?
An 'ace-lib-theme' is a set of colors and typography definitions that are applied on the ace-lib components. Using the ace-lib-theme package, you can customize the color and typography of the ace-lib components. 

The ace-lib-theme package contains the core `scss` files that are used to create a theme. Compile these `scss` files as `css`.

Explore the available [Theme-variables](theme-variables.md).

## Creating a custom theme
You can create a theme file using the below steps:
1. Install the ace-lib-theme package.
Install the 'ace-lib-theme` from the npm package manager using the below command:
    ```javascript
    npm i ace-lib-theme
    ```
2. Create a new file named `my-theme.scss` file inside the assets' directory in my template package. eg: `~/mytemplate/assets/theme/scss/my-theme.scss`
3. Open `my-theme.scss` file and assign values to the [theme-variables](theme-variables.md) (Optional step).
4. Towards the end of the file, import the core theme scss definitions using the below syntax:
    > @import "node_modules/ace-lib-theme/assets/scss/theme.scss";
5. Compile the scss files into css using the `node-sass` npm utility. Execute the below `node-sass` command  to compile the scss files into the theme css file:

    ```javascript
    node-sass -c ~path\to\mytemplate\assets\theme\scss\ -o ~path\to\mytemplate\assets\theme\css\
    ```
    > **Tips:** 
    > 1. If you have not installed the `node-sass` package globally, you will need to install it, before you use the above command. Use `npm i node-sass -g` to install it.
    >2. If you get any compile error, review the path reference for the @import statement in step 4. It should be relative to the directory from which you execute the compile command.
6. Import the generated `css` file into the template's `index.html` using the below HTML code.

    ```html
    <link href="assets/theme/css/my-theme.css" rel="stylesheet">
    ```
    
