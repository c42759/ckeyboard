![preview image](https://i.imgur.com/DTlq0ph.png)

# ckeyboard

A simple jQuery on screen keyboard.
## Feautures
- Easy Setup
- Switch layout on the Fly
- Supports multiple input fields
- Custom layout

## 1. Getting Setup

#### 1.1. Installation

- First, copy and paste `dist/ckeyboard.min.js` in your project, and link to it before the closing `</body>` element. Make sure jquery is linked before this.
- Next, you'll need to copy and paste the plugin's css into your project.
- Lastly, link to the keyboard css file `ckeyboard.css` file before the closing `</head>` element.

Note: This plugin requires your website or application already runs a copy of [jQuery](http://jquery.com/), version 3.x.x or higher.


    <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
    <script src="ckeyboard.min.js"></script>
    <link rel="stylesheet" href="ckeyboard.css">
 
#### 1.2 The Basics

The first thing you will require is a keyboard holder that will hold the keyboard, and an input field on which the keyboard will operate.

```html
<input type="text" id="search_field">
<div id="keyboard"></div>
<div id="keyboard_numeric"></div>
```
```js           
cKeyboard_config.input_target = "#search_field";
cKeyboard();
```

## Credits

*Markdown Here* was coded on the shoulders of giants.

* Markdown-to-HTML: [chjj / marked](https://github.com/chjj/marked)
* Syntax highlighting: [isagalaev / highlight.js](https://github.com/isagalaev/highlight.js)
* HTML-to-text: [mtrimpe / jsHtmlToText](https://github.com/mtrimpe/jsHtmlToText)

## Feedback

All bugs, feature requests, pull requests, feedback, etc., are welcome. [Create an issue](https://github.com/adam-p/markdown-here/issues). Or [post to the "markdown-here" Google Group](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here).

## License

### Code

MIT License: See [the `LICENSE` file](https://github.com/c42759/ckeyboard/blob/master/LICENSE).
