# getCurrentUser()

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
