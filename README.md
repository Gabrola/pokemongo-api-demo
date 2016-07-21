# Pokemon Go Maps with Android Fake GPS Manipulation (Root Required)

## Instructions
Generate a Google Maps API key here: https://console.developers.google.com/apis/credentials

Install Android command line tools: https://developer.android.com/studio/index.html#downloads

Install Fake GPS: https://play.google.com/store/apps/details?id=com.lexa.fakegps

Convert Fake GPS app to system app using: https://play.google.com/store/apps/details?id=de.j4velin.systemappmover

Enable USB debugging on android


Double clicking anywhere on the map will move you there instantly

Double clicking any pokemon will move you to that pokemon

Don't go too far very quickly or you will get soft banned

**MAC/LINUX:**

* `pip install -r requirements.txt`
* Put Google Maps API key in `config.json`
* Syntax: `./run.sh [user] [pass] "[location]"`
* Open browser to `http://localhost:8000`

**WINDOWS GUIDE:**

* `pip install -r requirements.txt`
* Put Google Maps API key in `config.json`
* Start `run.bat` and enter in prompts for username, password, and location
* Open browser to `http://localhost:8000`

Additional windows help here: https://www.reddit.com/r/pokemongodev/comments/4t8ohw/autoupdating_pokemon_go_map_scanner/d5g7xh80

## Thanks

Pokemon finding: https://github.com/leegao/pokemongo-api-demo

Scanning algorithm: https://github.com/AHAAAAAAA/PokemonGo-Map

Others: https://github.com/tejado/pokemongo-api-demo, https://github.com/Mila432/Pokemon_Go_API,
