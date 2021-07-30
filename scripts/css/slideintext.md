# Slide In Text

![Slide](https://raw.githubusercontent.com/IAJWasTooShort/DiscordConsole/main/screenshots/slide.gif)

```js
const injectCss = (id, css) => {
    const style = document.createElement('style');
    style.id = id;
    style.innerText = css;
    document.head.appendChild(style);
    return style;
}
injectCss('Slide', `
@keyframes slide-up {
    0% {
        opacity: 0;
        transform: translateX(20px);
    }
    100% {
        opacity: 1;
        transform: translateX(0);
    }
}
.message-2qnXI6 {
  animation: slide-up 0.4s ease;
}
`);
```