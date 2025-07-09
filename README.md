# 11pixels/XYZenix's Themes

this repo contains various website themes made by 11pixels (with a few exceptions)

## Themes: Discord

* [DTM-08](https://github.com/XYZenix/DTM-08) - a skeuomorphic/glossy theme for discord.
  * the original version (v1) was written entirely in css, and has not been maintained since 2023
  * **the current version (v2)** is the main version you're probably looking for and is just barely being maintained
  * the rewrite (v3) is very slowly being worked on due to a lack of motivation
* [DTM-16](https://github.com/XYZenix/DTM-16) - a theme that brings back the 2016 discord ui
  * v5 is the previous and now abandoned version of the theme
  * v6 was a planned rewrite which took too long to get going so i gave up on it
  * **v7 is the current version** which is somewhat actively maintained
* [ActivityStyleEmbeds](https://github.com/XYZenix/ActivityStyleEmbeds) - a small theme that restyles embeds to look like the old activity feed embeds from 2019. this theme is barely being maintained and might break and not be fixed for a long time.
* ~~DTM-12~~ - refers to several different themes all labeled DTM-12, all abandoned a long time ago
  * first one was based on a concept by disctr4k, it was the most finished of these but was abandoned because i couldn't follow the style it was going for.
  * second one was based on an AIMP skin, it was never finished but i took inspiration from it in a part of DTM-08
  * third one was meant to be based on youtube's 2012 refresh ui, it was never finished
* ~~DTM-17~~ - a theme that was meant to bring back the 2017 discord ui. this theme was a fork of DTM-16 and has been abandoned. i suggest checking out [dav's DTM-18](https://github.com/davart154/DTM-18)
* ~~DTM-20~~ - was a planned theme that never got made. check [milbits's oldcord](https://github.com/milbits/oldcord) instead
* ~~DTM-2K~~ - an abandoned theme based on windows 2000's system ui
* ~~discord sword/shield~~ - was a theme based on pokémon sword & shield's ui. this theme was abandoned
* ~~NewDragNDropModal~~ - was a mini theme based on a modal i saw in a short promo video in discord's game store back when that existed. this theme was abandoned

## Themes: Twitch

Name | Description | State
-----|-------------|------
[Twitch 2014](/Twitch2014.css) | Brings back the 2014 look of Twitch to some extent. **THIS IS MEANT TO BE USED ON STYLUS AS USERCSS** | Active

## Themes: [YouTube](/YoutubeThemes/)

all youtube themes are located in [YoutubeThemes](/YoutubeThemes/), view the [README.md](/YoutubeThemes/README.md) there for a list

## Themes: [Steam](/SteamThemes/)

all steam themes are located in [SteamThemes](/SteamThemes/), view the [README.md](/SteamThemes/README.md) there for a list

## Themes: [osu! site](/Other/osu/)

all osu! site themes are located in [/Other/osu](/Other/osu/), view the [README.md](/Other/osu/README.md) there for a list

## Contributing
if you want to contribute, you can open pull requests i guess

most themes use scss, compiled using [dart-sass](https://sass-lang.com/dart-sass/)
so if you're going to open a pull request modifying those themes, either don't provide a modified .css file, or use dart-sass with the default settings so the output is the same and doesn't end up changing 500 other unrelated things due to slight formatting differences

if there is no scss file, it's safe to assume there was no scss used so just modify the css file itself