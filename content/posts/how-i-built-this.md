---
title: 'Building Atmanautica: How This Happened'
date: 2019-02-20 12:06:00 +0000
layout: code
tags:
  - code
  - devsign
title_lead: Oh yeah, well now this is happening…
title_main: Building Atmanautica
title_sub: Howsits and Whatsits
draft: true
---

A couple years back a message came through clear as a bell. "Love is the answer." An oft-repeated platitude, yes, but this time it stuck and took over, like an amorous prion.

The next day this name came to me: "Atmanauts! Is that what we are?" I still don't know how to fully explain this transformation, but at least I have a word for it.<!--more--> Atmanaut: an explorer of the farthest reaches of the soul we share. Anyone that understands and appreciates this occupation, this coinage, will be a compadre, comrade, y en mi cadre. There could be millions of practicing atmanauts and we wouldn't know unless they can self-identify.

So I reserved use some space. Atmanaut.me is for personal Atmanaut matters. Atmanaut.us is for all of us to collaborate: this site here, which will become the Atlas. The Atlas is built on Hugo at the moment.

## What are you, nuts and bolts?

Delightfully often, when I've combed the web for help designing, developing, and publishing sites, apps, I land on someone's "How I Made This" post on their custom blog. That, or on StackOverflow, or on a Github issue, or increasingly these days on [DEV](dev.to). So this one goes out to all those paid it forward and lent me a hand.

It still feels like nothing short of a miracle to publish a new site. After so many tees dotted (with coffee stains) and eyes crossed through those long nights at the terminal, it's hard to describe the feeling when **It Just Works**™.

In the present case, thanks to a hoard of wunderkinder that open sourced their brilliance, the design, development, and deployment experience on this new site are as good as it gets. **It Just Works™** in such a Teflon-coated Slip 'n' Slide sorta way that I'm elated to pop the hood for you.

## TL;DR: The Stack

- [Hugo](https://gohugo.io/about/ 'Hugo'), which generates a lightning-fast, theme-able static site with plenty of Go power, a thriving community, and a stellar dev team.
- [Chakra](https://github.com/krry/chakra-hugo-theme/ 'Chakra Hugo Theme'), my handrolled Hugo theme
- [Forestry.io](https://forestry.io) for handling content. It's like Minecraft meets Wordpress with a woodsy musk.
- [Now.sh](https://zeit.co/now), for no-frills, full-auto deployment/hosting/DNS from the terminal, or straight from the `master` branch to you
- iA Writer - for hipster purity XP, LVL 99. I've been trying out Typora too, but ol' faithful iA really knows how to make me love to write.

The squirrel gets it when we ships it.
![The ShipIt! squirrel gets it.](/img/ship-it-squirrel.jpg)

### Something for the Code Blockheads

Hugo comes with all kinds of built-in goodies. Like syntax highlighting, powered by chromastyles and pygments.

```js
!function (name, definition) {

  if (typeof module != 'undefined') module.exports = definition()
  else if (typeof define == 'function' && typeof define.amd == 'object') define(definition)
  else this[name] = definition()

}('domready', function () {}
```

### Moo-ve over Oracle

If you pipe fortune into cowsay into lolcat and randomize the cows, you get a pretty amazing command line soothsayer I call [Kamadhenu](https://github.com/krry/kamadhenu). Next version will be AI-powered.
