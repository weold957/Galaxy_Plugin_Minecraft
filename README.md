# GOG Galaxy Minecraft Integration

An Minecraft integration for GOG Galaxy 2.0. Installable via GOG Galaxy (just use the search).

![example](example.gif)

[![1.0.0](https://img.shields.io/badge/version-1.0.0-blue)](https://GitHub.com/urwrstkn8mare/galaxy-riot-integration/releases/)
[![MIT License](https://img.shields.io/github/license/TouwaStar/Galaxy_Plugin_Minecraft)](https://github.com/urwrstkn8mare/TouwaStar/Galaxy_Plugin_Minecraft/fog_release/LICENSE)
[![1.0.0 Downloads](https://img.shields.io/github/downloads/FriendsOfGalaxy/galaxy-integration-minecraft/1.0.0/total.svg)](https://github.com/FriendsOfGalaxy/galaxy-integration-minecraft/releases)

_To see [releases](https://github.com/FriendsOfGalaxy/galaxy-integration-minecraft/releases), go to [FriendsOfGalaxy](https://github.com/FriendsOfGalaxy)'s [fork](https://github.com/FriendsOfGalaxy/galaxy-integration-minecraft)._

## Build

`python3 build.py -r` This will make a zip with the integration and all necessary packages for the operating system run on. You can specify a platform but I've found that to not work well when building for another platform on a platform (eg. building for mac on windows). For more information run `python build.py -h`.

## FAQ

_How to change what games I own (owned games selection)?_ Just disconnect and reconnect. The play time should be kept. If there is an issue please submit an issue.

## Credits

- Minecraft Dungeons and MultiMC support by [urwrstkn8mare](https://github.com/urwrstkn8mare).
- Build script ([build.py](build.py)) by [urwrstkn8mare](https://github.com/urwrstkn8mare). ([Source](https://gist.github.com/urwrstkn8mare/78d8377562d8719f3bd1f72f9c4e7516))
- `double_click_effect` decorator ([decorators.py](src/decorators.py)) by [UncleGoogle](https://github.com/UncleGoogle). ([Source](https://github.com/UncleGoogle/galaxy-integration-humblebundle/blob/b11918aefac05b904964a8d5330ee1547f11793c/src/utils/decorators.py) - a little modified)
- [style.css](src/page/css/style.css), [fonts](src/page/fonts/), [icon-error.svg](src/page/img/icon-error.svg) by [FriendsOfGalaxy](https://github.com/FriendsOfGalaxy). ([Source](https://github.com/FriendsOfGalaxy/galaxy-integration-steam/commit/ddc594dee637eabda2743370f17efbe4d1dad1bc))
- Info icon ([icon-info.svg](src/page/img/icon-info.svg)) made by [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](http://www.flaticon.com/). ([Source](https://www.flaticon.com/free-icon/information-button_1176) - changed colour and made smaller)
- Uses [imgCheckbox](https://jcuenod.github.io/imgCheckbox/) by [jcuenod](https://github.com/jcuenod)
- Uses [jQuery](https://jquery.com/)
- Uses [galaxyutils](https://pypi.org/project/galaxyutils/) by [tylerbrawl](https://github.com/tylerbrawl) and other python packages. Look at [requirements.txt](requirements.txt) for other packages used by this integration.
