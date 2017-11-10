# Touch Bar iStats

<img src="resources/screenshot.png" width="100%">

Touch Bar iStats shows temperature of CPU/GPU/MEM or [whatever you want](https://github.com/Chris911/iStats#advanced-usage) on your touch bar.

## How to install

1. Install [BetterTouchTool](https://www.boastr.net/)
2. Install [iStats](https://github.com/Chris911/iStats) ruby gem with `sudo gem install iStats`
   (you can use macOS embeded ruby, `rbenv` or `rvm`)
3. Pull this repo contents
4. Open BetterTouchTool/Preferences/Touch Bar and import JSON files

Gauges will turn red when safe temperature is exceeded:
* CPU >75
* GPU >85
* MEM >90

## Authors

* [Marek Kaczkowski](https://github.com/marekkaczkowski)

## Credits

* Thanks to [Christophe Naud-Dulude](https://github.com/Chris911) for [iStats](https://github.com/Chris911/iStats), which ties together the hardware info stuff with [BetterTouchTool](https://www.boastr.net/).
* Thanks to [Smashicons](https://smashicons.com/) for awesome [Technology Elements](https://www.flaticon.com/packs/technology-elements) icon set.

## License

Touch Bar iStats is published under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
