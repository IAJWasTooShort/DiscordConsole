# System

Gives you the "System" tag (client side)

![System](https://raw.githubusercontent.com/IAJWasTooShort/DiscordConsole/main/screenshots/system.png)

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser().system = true;
```

![CustomTag](https://raw.githubusercontent.com/IAJWasTooShort/DiscordConsole/main/screenshots/customtag.png)

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;

findModule('Messages').Messages.SYSTEM_DM_TAG_SYSTEM = 'Tag Text';
```