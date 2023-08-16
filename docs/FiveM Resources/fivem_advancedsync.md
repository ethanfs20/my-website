# FiveM Advanced Sync | Ethan4t0r

This script provides enhanced weather control for FiveM servers, allowing for more immersive weather transitions.Yea!

First C# script so plz go easy, lmk if you want any updates or whateves.

## Features

- Somewhat of a weather transition system, allowing for more immersive weather transitions. Like a thunderstorm transitioning to clear weather!
- Special handling for a combined "SNOW" and "BLIZZARD" effect.
- Server-controlled weather system that prevents interference from other sources. In other words, the server has full control over the weather.
- IRL based time that overrides the game. Server owners can change the time it takes for a full day rotation.
- Server owners can select their specific timezones. From [here](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-time-zones?view=windows-11)!!
- Easy configuration via convars in your `server.cfg` file.
- FXDK ENV provided.

## Installation

1. Clone this repository into your FiveM `resources` directory.
   - [CLICK MEEEEEE TOO DUNLOAD](https://github.com/ethanfs20/fivem_advancedsync)
2. Add the following line to your `server.cfg`:
   - `ensure fivem_advancedsync`
3. YAY!

## Configuration

The following convars are available for configuration in your `server.cfg` file:

- `TIME_UPDATE_INTERVAL` - The interval (in milliseconds) at which the time is updated on the client. Default: `60000` (1 minute)
- `WEATHER_DEFAULT` - The default weather to use when the server starts. Default: `EXTRASUNNY`
- `TIMEZONE` - The timezone to use for the server. Default: `local` which is the servers.
- `WEATHER_UPDATE_INTERVAL` - The interval (in milliseconds) at which the weather is changed on the client. Default: `7200000` (2 hours) Change this to `0` to disable automatic weather changes.


## Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change. or join me on Discord and we can talk about it.

## License

[MIT](https://choosealicense.com/licenses/mit/)