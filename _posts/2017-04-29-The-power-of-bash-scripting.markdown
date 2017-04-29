---
layout: post
title:  "The power of bash scripting"
author: "Dokter Waldijk"
date:   2017-04-29
---
[fnugg](https://github.com/dokterw/fnugg) started out as a simple weather script to let me keep an eye on temperature, feels-like temperature, wind and forecast summary while at work (I have one terminal open running tmux with several panes).

In just a few days it now also shows sunrise and sunset time and the week's summary. Plans are to add an extra view to show the forecast one week ahead (or less).

Not what I really planned, but more of a why-not progression of the script, and a way to show, when done right, bash scripting can be very powerful.

fnugg is powered by [Dark Sky](https://darksky.net/dev)'s rest API. Again, a weather app (it's still a script, but with all these functions it feels more like an app) written in bash script fetching data from an API.

The weather data is fetched every 10 minutes and put in a variable. That variable is parsed several times to get the specific data I need to avoid making several calls every 10th minute.

I have written a few cryptography focused scripts, but writing a script that fetches data from a rest API makes you wonder why bash scripting is so underestimated and undervalued by some coders. Done right, you can build a lot of cool and handy stuff only using bash script.
