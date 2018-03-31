  
# PoGoMaps

Live visualization of all the Pokémon (with option to show gyms, raids and PokéStops) in your area. This is a proof of concept that we can load all the Pokémon visible nearby given a location. Currently runs on a Flask server displaying Google Maps with markers on it.

![logo](https://github.com/The-Real-Ketchum-Dev/PoGoMaps/blob/MIX_MEWTWO/static/images/PoGoMaps.png)


## Discord

[<img src="http://www.tjielup.nl/join2.png">](https://discord.gg/zTwC7sF)


## What does PoGoMaps have that other RM forks don't:

1. Cool navigation-bar filters like filtering/including/excluding per Pokémon type, generation and special tiers.
2. Gen nr. in your Pokémon labels
3. Get notified for Tiny Rats & Big Karps + the option to prio-notify Pokémon (Pokémon in notify filters will ALWAYS be visible)
4. Depending on your -rh (rarity-hours) setting, Pokémon  will get assigned 'New Spawn' when your map hasn't seen this pokemon for `<rh-setting>` hours
5. The option to import/export your customized map settings
6. Keep a list of your favorite locations!

And more to be added!

## Features:

* Shows Pokémon, PokéStops, raids and gyms with a clean GUI.
* Notifications
* Lure information
* Multithreaded mode
* Filters
* Additional dropdown menu filtering by [Tomballer](https://github.com/tomballgithub/RocketMap)
* Independent worker threads (many can be used simultaneously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, ko, ja, zh_tw, zh_cn, zh_hk)
* DB storage (mysql) of all found Pokémon
* Incredibly fast, efficient searching algorithm (compared to everything else available)


## Todo:

* See [Milestones](https://github.com/The-Real-Ketchum-Dev/PoGoMaps)


## Installation

# COMING SOON!!!


## Contributions

Building off [tejado's python pgoapi](https://github.com/tejado/pgoapi), [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s API, [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Current version relies primarily on the pgoapi and Google Maps JS API.

Discord and front-end use [Iconset](http://www.flaticon.com/packs/packs/pokemon-go/) by [Roundicons Freebies](http://www.flaticon.com/authors/roundicons-freebies/) and [icon](http://www.flaticon.com/free-icon/rocket_178158) by [Flat Icons](http://flat-icons.com/) from [www.flaticon.com](http://www.flaticon.com/). Filters by [Tomballer](https://github.com/tomballgithub/RocketMap) License: CC 3.0 BY can be found [here](http://creativecommons.org/licenses/by/3.0/). 
