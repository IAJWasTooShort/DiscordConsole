# Discord Console Stuff

To open the discord console press Ctrl + Shift+ I and make sure you are in the console tab

[Console](https://github.com/IAJWasTooShort/DiscordConsole/blob/main/screenshots/console.png)

## getCurrentUser()

```js
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser()
```
Returns:

```js
accentColor: null
avatar: "avatar"
banner: "banner"
bio: "YOURBIO"
bot: true/false
desktop: true/false
discriminator: "1234"
email: "Youremail@email.com"
flags: 15
guildMemberAvatars:
    __proto__:
        constructor: ƒ Object()
        hasOwnProperty: ƒ hasOwnProperty()
        isPrototypeOf: ƒ isPrototypeOf()
        propertyIsEnumerable: ƒ propertyIsEnumerable()
        toLocaleString: ƒ toLocaleString()
        toString: ƒ toString()
        valueOf: ƒ valueOf()
        __defineGetter__: ƒ __defineGetter__()
        __defineSetter__: ƒ __defineSetter__()
        __lookupGetter__: ƒ __lookupGetter__()
        __lookupSetter__: ƒ __lookupSetter__()
        get __proto__: ƒ __proto__()
        set __p
id: "YOURID"
mfaEnabled: true/false
mobile: true/false
nsfwAllowed: true/false
phone: "YOURPHONE"
premiumType: 2
publicFlags: 64
purchasedFlags: 0
system: true/false
username: "USERNAME"
usernameNormalized: "username"
verified: true/false
bannerURL: url
createdAt: date
hasPremiumPerks: true/false
tag: "username#1234"
__proto__: e
    ldAvatarHash: ƒ (e,t)
    constructor: ƒ t(t)
    getAvatarSource: ƒ (e,t)
    getAvatarURL: ƒ (e,t)
    getBannerSource: ƒ (e)
    getBannerURL: ƒ (e)
    hasAvatarForGuild: ƒ (e)
    hasFlag: ƒ (e)
    hasFreePremium: ƒ ()
    hasHadSKU: ƒ (e)
    hasPurchasedFlag: ƒ (e)
    hasUrgentMessages: ƒ ()
    isClaimed: ƒ ()
    isLocalBot: ƒ ()
    isNonUserBot: ƒ ()
    isPhoneVerified: ƒ ()
    isStaff: ƒ ()
    isSystemUser: ƒ ()
    isVerifiedBot: ƒ ()
    removeGuildAvatarHash: ƒ (e)
    toString: ƒ ()
    bannerURL: (...)
    createdAt: (...)
    hasPremiumPerks: (...)
    tag: (...)
    get bannerURL: ƒ ()
    get createdAt: ƒ ()
    get hasPremiumPerks: ƒ ()
    get tag: ƒ ()
    __proto_
```

### Flags (badges):

```js
Object.values(webpackJsonp.push([
    [], {
        ['']: (_, e, r) => {
            e.cache = r.c
        }
    },
    [
        ['']
    ]
]).cache).find(m => m.exports && m.exports.default && m.exports.default.getCurrentUser !== void 0).exports.default.getCurrentUser().flags = [num(listed below)]
```

```
-1  all flags
 1  Discord Staff
 2  Discord Partner
 3  Discord Staff, Discord Partner
 4  Hype Squad Events
 5  Discord Staff, Hype Squad Events
 6  Discord Partner, Hype Squad Events
 7  Discord Staff, Discord Partner, Hype Squad Events
 8  Discord Bug Hunter
 9  Discord Staff, Discord Bug Hunter
 10 Discord Partner, Discord Bug Hunter
 11 Discord Staff, Discord Partner, Discord Bug Hunter
 12 Hype Squad Events, Discord Bug Hunter
 13 Discord Staff, Hype Squad Events, Discord Bug Hunter
 14 Discord Partner, Hype Squad Events, Discord Bug Hunter
 15 Discord Staff, Discord Partner, Hype Squad Events, Discord Bug Hunter
```


## getGuild()

```js
Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}},[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getGuilds!==void 0).exports.default.getGuild('SERVERID')
```
Returns

```js
ChannelId: id
afkTimeout: 300
applicationCommandCount: 0
applicationCommandCounts: {1: 0, 2: 0, 3: 0}
    1: 0
    2: 0
    3: 0
    __proto__:
    constructor: ƒ Object()
    hasOwnProperty: ƒ hasOwnProperty()
    isPrototypeOf: ƒ isPrototypeOf()
    propertyIsEnumerable: ƒ propertyIsEnumerable()
    toLocaleString: ƒ toLocaleString()
    toString: ƒ toString()
    valueOf: ƒ valueOf()
    __defineGetter__: ƒ __defineGetter__()
    __defineSetter__: ƒ __defineSetter__()
    __lookupGetter__: ƒ __lookupGetter__()
    __lookupSetter__: ƒ __lookupSetter__()
    get __proto__: ƒ __proto__()
    set __proto__: ƒ __proto__()
application_id: id
banner: banner
defaultMessageNotifications: 0
description: desc
discoverySplash: splash
explicitContentFilter: 0
features: Set(3)
    features: Set(3)
    [[Entries]]
    0: "Feature"
    1: "PARTNERED"
    2: "VERIFIED"
    size: (...)
    __proto__: Set
        toJSON: ƒ ()
        add: ƒ add()
        clear: ƒ clear()
        constructor: ƒ Set()
        delete: ƒ delete()
        entries: ƒ entries()
        forEach: ƒ forEach()
        has: ƒ has()
        keys: ƒ values()
        size: (...)
        values: ƒ values()
        Symbol(Symbol.iterator): ƒ values()
        Symbol(Symbol.toStringTag): "Set"
        get size: ƒ size()
        __proto__: Object
icon: icon
id: "id"
joinedAt: joindate
    __proto__:
        constructor: ƒ Date()
        getDate: ƒ getDate()
        getDay: ƒ getDay()
        getFullYear: ƒ getFullYear()
        getHours: ƒ getHours()
        getMilliseconds: ƒ getMilliseconds()
        getMinutes: ƒ getMinutes()
        getMonth: ƒ getMonth()
        getSeconds: ƒ getSeconds()
        getTime: ƒ getTime()
        getTimezoneOffset: ƒ getTimezoneOffset()
        getUTCDate: ƒ getUTCDate()
        getUTCDay: ƒ getUTCDay()
        getUTCFullYear: ƒ getUTCFullYear()
        getUTCHours: ƒ getUTCHours()
        getUTCMilliseconds: ƒ getUTCMilliseconds()
        getUTCMinutes: ƒ getUTCMinutes()
        getUTCMonth: ƒ getUTCMonth()
        getUTCSeconds: ƒ getUTCSeconds()
        getYear: ƒ getYear()
        setDate: ƒ setDate()
        setFullYear: ƒ setFullYear()
        setHours: ƒ setHours()
        setMilliseconds: ƒ setMilliseconds()
        setMinutes: ƒ setMinutes()
        setMonth: ƒ setMonth()
        setSeconds: ƒ setSeconds()
        setTime: ƒ setTime()
        setUTCDate: ƒ setUTCDate()
        setUTCFullYear: ƒ setUTCFullYear()
        setUTCHours: ƒ setUTCHours()
        setUTCMilliseconds: ƒ setUTCMilliseconds()
        setUTCMinutes: ƒ setUTCMinutes()
        setUTCMonth: ƒ setUTCMonth()
        setUTCSeconds: ƒ setUTCSeconds()
        setYear: ƒ setYear()
        toDateString: ƒ toDateString()
        toGMTString: ƒ toUTCString()
        toISOString: ƒ toISOString()
        toJSON: ƒ toJSON()
        toLocaleDateString: ƒ toLocaleDateString()
        toLocaleString: ƒ toLocaleString()
        toLocaleTimeString: ƒ toLocaleTimeString()
        toString: ƒ toString()
        toTimeString: ƒ toTimeString()
        toUTCString: ƒ toUTCString()
        valueOf: ƒ valueOf()
        Symbol(Symbol.toPrimitive): ƒ [Symbol.toPrimitive]()
        __proto__: Object
maxMembers: maxMembers
maxVideoChannelUsers: maxVideoChannelUsers
mfaLevel: 0
name: "servername"
nsfwLevel: 0
ownerId: "OwnerID"
preferredLocale: "en-US"
premiumSubscriberCount: 0
premiumTier: 0
publicUpdatesChannelId: publicUpdatesChannelId
region: "europe"
roles: {...}
rulesChannelId: rulesChannelId
splash: splash
systemChannelFlags: 0
systemChannelId: "systemChannelId"
vanityURLCode: "rename"
verificationLevel: 0
acronym: (...)
__proto__ : e
    constructor: ƒ t(t)
    getApplicationId: ƒ ()
    getIconSource: ƒ (e)
    getIconURL: ƒ (e)
    getMaxEmojiSlots: ƒ ()
    getRole: ƒ (e)
    hasFeature: ƒ (e)
    isLurker: ƒ ()
    isNew: ƒ (e)
    isOwner: ƒ (e)
    isOwnerWithRequiredMfaLevel: ƒ (e)
    toString: ƒ ()
    acronym: (...)
    get acronym: ƒ ()
    __proto__: Object
```