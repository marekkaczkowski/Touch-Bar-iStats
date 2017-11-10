# Touch Bar iStats

Touch Bar iStats shows temperature of CPU/GPU/MEM or [whatever you want](https://github.com/Chris911/iStats#advanced-usage) sensor on your touch bar.

<img src="shot.jpg" width="100%">

## How to install

1. Install [BetterTouchTool](https://www.boastr.net/)
2. Install [iStats](https://github.com/Chris911/iStats) ruby gem with `sudo gem install iStats`
   (you can use macOS embeded ruby, `rbenv` or `rvm`)
3. Pull this repo contents
4. Open BetterTouchTool/Preferences/Touch Bar and import `JSON` files

Gauges will turn red when safe temperature is exceeded:
* CPU >75°C | 30s
* GPU >85°C | 30s
* MEM >75°C | 5m

You can chnage probing interval in BetterTouchTool on widget's Advanced Configuration dialog.

## Authors

* [Marek Kaczkowski](https://github.com/marekkaczkowski)

## Credits

* Thanks to [Christophe Naud-Dulude](https://github.com/Chris911) for [iStats](https://github.com/Chris911/iStats), which ties together the hardware info stuff with [BetterTouchTool](https://www.boastr.net/).
* Thanks to [Smashicons](https://smashicons.com/) for awesome [Technology Elements](https://www.flaticon.com/packs/technology-elements) icon set.

## License

Touch Bar iStats is published under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
