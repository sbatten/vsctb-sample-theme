
## VS Code Theme Builder Sample Theme

This theme is based on the default style and palette from VS Code Theme Builder. It houses the palette, style and themes generated from the default flow. It can be used as a reference when creating your own theme.


### Modifying the theme
To modify theme, you should either update the [color palette](./palette/index.js) or the [style](./style/index.js). When you are happy with the changes, you can generate the theme files with the following command.

```
yarn build-theme
```

### Style and Palette Reuse
The style and palette in this repository are published as NPM modules. This allows you to create a new theme by creating your own color palette but reusing an existing style or vice versa. 

### For more information
* [VS Code Theme Builder](https://www.npmjs.com/package/vsctb)
* [VS Code Theme Builder Sample Palette](https://www.npmjs.com/package/vsctb-sample-palette)
* [VS Code Theme Builder Sample Style](https://www.npmjs.com/package/vsctb-sample-style)

