## Compiling the SCSS files

The changes for the pixel art theme have been applied to the SCSS (`.scss`) files. To see the changes on the website, you need to compile the main SCSS file (`assets/scss/risen.scss`) into a CSS file (`assets/css/risen.css`).

Here are a couple of ways to do this:

### 1. Using a Command-Line Tool (like Dart SASS)

If you have [Sass](https://sass-lang.com/install) installed, you can run the following command in your terminal from the root of the project:

```bash
sass assets/scss/risen.scss assets/css/risen.css
```

This will watch for changes in the scss file and automatically compile it to css.

### 2. Using a VS Code Extension

If you are using Visual Studio Code, you can install the [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension.

Once installed, you can open the `assets/scss/risen.scss` file and click the "Watch Sass" button in the status bar at the bottom of the window. This will automatically compile the SCSS to CSS whenever you save a `.scss` file.

After you have compiled the SCSS, simply open the `index.html` file in your browser to see the pixel art-themed resume.
