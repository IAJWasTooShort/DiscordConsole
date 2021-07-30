# Text Shadow

![Shadow](https://raw.githubusercontent.com/IAJWasTooShort/DiscordConsole/main/screenshots/textshadow.png)

```js
const injectCss = (id, css) => {
    const style = document.createElement('style');
    style.id = id;
    style.innerText = css;
    document.head.appendChild(style);
    return style;
}
injectCss('TextShadow', `
.cozy-3raOZG .header-23xsNx,
.markup-2BOw-j {
    color: white;
    text-shadow: 4px 4px 5px black,2px 3px 5px black;
}
`);
```