# Foxlim

Foxlim is a slim, compact, and simple oneline chrome stylesheet for the Proton UI Refresh in Firefox Desktop.

![Preview](foxlim-firefox-150-preview.png)

inspired by [Waterfall](https://github.com/crambaud/waterfall).

## Features

- oneline - tabs on the left, URL bar on the right
- layout-only (which means that it doesn't break chrome themes)
- simple - most elements are hidden
- sharp - no border radii
- compact - as little padding as possible

Other properly-made chrome stylesheets:
- [gwfox](https://github.com/akkva/gwfox)
- [FoxOne](https://github.com/Firnschnee/FoxOne)
- [LittleFox](https://github.com/biglavis/LittleFox)
- [Malevich](https://github.com/hermitm0nk/malevich)


> [!CAUTION]
> 
> Proton UI Refresh is still broken and custom chrome stylesheets can only fix some of the superficial problems.
> 
> https://discourse.mozilla.org/t/so-now-we-can-not-even-turn-off-proton/83108/

> [!TIP]
> 
> If you can do without Firefox, use Basilisk, Pale Moon, or a fork of them.

This stylesheet is a little broken (eg. alert() is too small), because Mozilla employees, as all bike-shedders, love to break everything.

The reason Mozilla doesn't officially support custom browser CSS stylesheets is because they don't know how to use CSS properly. Just open the Browser Toolbox to see the nonsense CSS they wrote for the browser. It's worse than AI-generated.

Mozilla broke Firefox beyond repair, but the least they should to do is give userChrome.css and userContent.css highest priority, instead of having to put thousands of "!important" rules in them.

Mozilla isn't the only one, and these problems are symptoms of a much bigger problem, which I'm working on solving once and for all.
