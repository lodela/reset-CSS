# CSS Resetter 2022

_(last updated March 10th 2022)_

> _Special thanks to CSS guru Eric Meyer who inspired me to do this work._

A CSS Resetter style sheet is a list of rules that 'resets' all of the default browser styles.

## Why?

Reset styles seem like a lot of work, don't you?.
Why would you want to do this by yourself?

### Two reasons:

This will save you a **lot of time** and frustration when you are creating complicated layouts with CSS.
You're the developer / designer. You shouldn't let the browser makers decide how any part of your web pages will look.

### We reset the browser styles for two primary reasons:

- Not all browsers apply the same default rules. They may be similar, but not exact. It can be difficult to provide the same designs in each browser if the basic styles are different.
- Once you start designing and coding all of the fine details of your site, you may discover that a lot of what you are doing is simply overriding default browser styles. The reset does this quickly so that you don't have to.

[Download the Latest Version](https://raw.githubusercontent.com/lodela/reset-CSS/main/reset.min.css)

## How to install it with NPM

```
npm install --save css-resetter
```

The package name on NPM is 'css-resetter'.

## USAGE. Import resetter

React, Vue, or Angular project, import it to the main entry file prior to your tailored CSS stylesheet:

```js
import "css-resetter";
```

## Copy and Paste Into Your Own Style Sheet

css-resetter [click here](https://raw.githubusercontent.com/lodela/reset-CSS/main/reset.min.css) to copy and paste

You can also simply copy all of the rules from the reset style sheet and paste them into your own. Make sure that you put them at the top so that they don't override any of your rules.

If you use this method, be sure to clearly mark the reset section of the style sheet and give credit to the author using CSS comments. While the author has made this style sheet available for everyone to use, this isn't your work, so don't pretend like it is.

> Remember, the CSS Reset style sheet should always go first.

## Browser Support

All evergreen browsers

- Chrome, Edge: version 88+
- FireFox: version 84+
- Safari/iOS browsers: version 14+
- Opera: version 75+
- Samsung Browser: version 15+
