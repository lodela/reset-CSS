# reset.css

CSS reset 2022.

# CSS Resetter 2022

A CSS Resetter style sheet, its a list of rules that 'reset' all of the default browser styles.

## Why?

Reset styles seem like a lot of work, don't you?.
Why would you want to do this?

Two reasons:

This will save you a **lot of time** and frustration when you are creating complicated layouts with CSS.
You're the designer. You shouldn't let the browser makers decide how any part of your web pages will look.

Two reasons:

This will save you a lot time and frustration when you are creating complicated layouts with CSS.
You're the designer. You shouldn't let the browser makers decide how any part of your web pages will look.

[Download the Latest Version](https://raw.githubusercontent.com/elad2412/the-new-css-reset/main/css/reset.css)

## NPM and How to Use?

The package name on NPM is 'the-new-css-reset'.

Import `/css/reset.css` before the regular styles of the project.

In a React project, insert it to the main entry file:

```js
import "the-new-css-reset/css/reset.css";
```

## Accessibility Recommendation

To keep your website accessibly, don't forget to take care of the `:focus` states.

```css
:focus {
  /* focus styles */
}

/* or/and */

:focus-visible {
  /* keyboard only focus styles */
}
```

## Browser Support

All evergreen browsers

- Chrome, Edge: version 88+
- FireFox: version 84+
- Safari/iOS browsers: version 14+
- Opera: version 75+
- Samsung Browser: version 15+
