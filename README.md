# 7.css

[![npm](https://img.shields.io/npm/v/7.css)](http://npm.im/7.css)
[![gzip size](https://img.shields.io/bundlephobia/minzip/7.css)](https://unpkg.com/7.css)

<video src="https://github.com/user-attachments/assets/0da40ca4-f9b1-4082-8c1d-78c031f0530d" width="524" height="294" controls></video>

**7.css** is a CSS framework that takes semantic HTML and styles them to the Windows 7 design.
It is built on top of [XP.css](https://github.com/botoxparty/XP.css), which is an extension of [98.CSS](https://github.com/jdan/98.css).

It does not ship with any JavaScript, so it is compatible with your frontend framework of choice.

## 📦 Installation / Usage

Directly via [unpkg](https://unpkg.com/):

```html
<!DOCTYPE html>
<html>
  <head>
    <title>7.css example</title>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="https://unpkg.com/7.css" />
  </head>

  <body>
    <div class="window" style="margin: 32px; width: 250px">
      <div class="title-bar">
        <div class="title-bar-text">My First Program</div>
      </div>
      <div class="window-body">
        <p>Hello, world!</p>
      </div>
    </div>
  </body>
</html>
```

Via [npm](https://www.npmjs.com/package/7.css):

```sh
npm install 7.css
```

Then import it as below:

```javascript
import "7.css/dist/7.css";
```

## 📚 Documentation / Demo

Refer to the [documentation page](https://khang-nd.github.io/7.css/) for specific instructions on this framework's components.

## 🛠 Developing

Clone the repo and run `npm install`.

The core styles are managed in [`gui`](https://github.com/khang-nd/7.css/tree/main/gui).

You can use `npm start` to start a development environment that will watch for file changes and rebuild the files, reloading your browser in the process.

You can run a build manually with `npm run build`. This will write to the `dist/` directory.

## 📝 Issues, Contributing, etc.

You are so welcome to report issues, help out with contributions or whatever you could think of to improve this lovely UI framework.

## ⚙ Integrations

**7.css** has been seen adopted in the following JS framework projects by the community:

- Vue - [win7-ui](https://github.com/Visnalize/win7-ui)
- Svelte - [svelte-7.css](https://github.com/JericoFX/svelte-7.css) (work in progress)

## 📜 Changelog

Refer to [Releases](https://github.com/khang-nd/7.css/releases).
