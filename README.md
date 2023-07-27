<div style="display:flex;flex-direction:column;align-items:center;gap:10px">
<img style="width:100px; height:100px; margin:0px auto;border-radius:25px" src=".github/5S5.png" />
<h1 style="width:100%; text-align:center">Skip 5 Seconds</h1>
</div>

<script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Support Me on Ko-fi', '#e05928', 'T6T5NM7U2');kofiwidget2.draw();</script> 

A little Google Chrome extension to skip 5 second ads on YouTube.

## What does it do?

The extension injects a button under the video player that when pressed will skip the currently playing 5 second ad

![screenshot](.github/screenshot.png)

## Usage

- In the project directory

  - Install dependencies

```
    $ npm install
```

- Build the extension

```
  $ npm run build
```

> this will create a `dist` directory in the same folder

- Go to [Manage Extenstions](chrome://extensions/) on Chrome and press the `Load Unpacked` button

- Select the `dist` directory that was generated when building the extension
