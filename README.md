Rottentomatoes-userscript
=====================
A userscript or greasemonkey script that shows the score/meter from rottentomatoes.com on several other websites like amazon, google play and others.

After installing the script, you need to visit [www.rottentomatoes.com](https://www.rottentomatoes.com/) at least once.
Just open [www.rottentomatoes.com](https://www.rottentomatoes.com/) and let the site fully load itself, the script will automatically read
some API keys from the website. You can close the tab when the site has fully loaded.

It's primarily designed for Firefox and Chrome with
[Tampermonkey](https://www.tampermonkey.net/) [![Chrome logo](https://raw.githubusercontent.com/OpenUserJS/OpenUserJS.org/master/public/images/ua/chrome16.png)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) [![Firefox logo](https://raw.githubusercontent.com/OpenUserJS/OpenUserJS.org/master/public/images/ua/firefox16.png)](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
or
[FireMonkey ![Firefox logo](https://raw.githubusercontent.com/OpenUserJS/OpenUserJS.org/master/public/images/ua/firefox16.png)](https://addons.mozilla.org/en-US/firefox/addon/firemonkey/).

[**Click here for install**](https://raw.githubusercontent.com/danzig666/Rottentomatoes-userscript/master/Show_Rottentomatoes_meter.user.js)  
Tested with Firefox/**Tampermonkey** and Chrome/**Tampermonkey**.

> This is a fork of [cvzi/Rottentomatoes-userscript](https://github.com/cvzi/Rottentomatoes-userscript).
> Changes: fixed IMDb (language detection broke after an IMDb redesign), added mobile IMDb support
> (m.imdb.com and the phone layout of www.imdb.com, tap a score bar to see its details), removed trakt.tv support.
> Updates are installed from this fork, not from Greasy Fork.

I develop a similar script for the [Metacritic](https://www.metacritic.com/) score, see [cvzi/Metacritic-userscript](https://github.com/cvzi/Metacritic-userscript/)  
and for the [Letterboxd.com](https://letterboxd.com/) rating, see [cvzi/Letterboxd-userscript](https://github.com/cvzi/Letterboxd-userscript/)

## Symbols:

|Icon | rottentomatoes    | https://www.rottentomatoes.com/about#whatisthetomatometer  |
|-----|-------------------|------------------------------------------------------------|
| 🍓  |  certified fresh  | 75% or higher and at least 5 top critic reviews            |
| 🍅  |  fresh            | 60% positive critic reviews                                |
| 🍏  |  rotten           | less than 60% positive critic reviews                      |
| 🍿  |  full popcorn     | 60% user reviews of 3.5 or higher                          |
| 🥗  |  spilled popcorn  | less than 60% user reviews of 3.5                          |


## Supported sites and products:

 * imdb.com (desktop and mobile)
 * metacritic.com
 * letterboxd.com
 * BoxOfficeMojo
 * serienjunkies.de
 * Amazon
 * tv.com
 * Google Play
 * allmovie.com
 * Wikipedia
 * themoviedb.org
 * fandango.com
 * tvmaze.com
 * tvguide.com
 * followshows.com
 * thetvdb.com
 * tvnfo.com
 * nme.com - New Musical Express
 * itunes.apple.com
 * epguides.com
 * ShareTV
 * save.tv
 * argenteam.net

Screenshot:

![Screenshot of amazon product page](https://raw.githubusercontent.com/cvzi/Rottentomatoes-userscript/master/screenshot_animation.png)

![Screenshot of amazon product page](https://raw.githubusercontent.com/cvzi/Rottentomatoes-userscript/master/screenshot_amazon.jpg)

![Screenshot of amazon product page](https://raw.githubusercontent.com/cvzi/Rottentomatoes-userscript/master/screenshot_audience.png)


