![preview image](https://i.imgur.com/DTlq0ph.png)

# ckeyboard

A simple jQuery on screen keyboard.
## Features
- Easy Setup
- Switch layout on the Fly
- Supports multiple input fields
- Custom layout

## 1. Getting Setup

#### 1.1. Installation

- First, copy and paste `dist/ckeyboard.min.js` in your project, and link to it before the closing `</body>` element. Make sure *jQuery* is linked before this.
- Next, you'll need to copy and paste the plugin's CSS into your project.
- Lastly, link to the keyboard *CSS* file `ckeyboard.css` file before the closing `</head>` element.

**Note:** This *plugin* requires your website or application already runs a copy of [jQuery](http://jquery.com/), version 3.x.x or higher.


```html
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="ckeyboard.min.js"></script>
<link rel="stylesheet" href="ckeyboard.css">
```

#### 1.2 The Basics

The first thing you will require is a keyboard holder that will hold the keyboard, and an input field on which the keyboard will operate.

```html
<input type="text" id="search_field" maxlength="25">
<div id="keyboard"></div>
<div id="keyboard_numeric"></div>
```
```js           
cKeyboard_config.input_target = "#search_field";
cKeyboard();
```

## License

MIT License: See [the LICENSE file](https://github.com/c42759/ckeyboard/blob/master/LICENSE).
