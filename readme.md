#Hacker News - Make it readable your way

I was Inspired to build this by an article by [David Kadavy] (https://twitter.com/kadavy) on how to improve readability of the Hacker News list.

All you need to build a native app using electron and nativefier and use that to inject custom javascript and css into the site to suit your need.

clone this repo and get the `javascript`, `icon` and `stylesheet` files.

`nativefier https://news.ycombinator.com/ --inject HNCustomCSS.css --inject HNCustomJS.js --icon ycombinator.icns --name "my Hacker News"`

#Note
To install [electron] (http://electron.atom.io/) and [nativefier] (https://github.com/jiahaog/nativefier), please goto the links provided
