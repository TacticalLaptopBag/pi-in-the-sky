# pi-in-the-sky
Yet another Raspberry Pi eInk clock + weather forecast, this time running on Rust

Currently in the very early stages of conceptualization.


## Another one? Why?
There's already a number of cool projects such as [InkyPi] and [rpi-weather-clock].
While I could just put those together, that wouldn't be as fun as making it myself.
I've been itching to use Rust in a full project,
and I've also been wanting to try some actual CAD design.

## Planned Features
* Time & date display, in any format you like
* Current weather and 5-day forecast using [Open-Meteo]
* Configurable via a web UI or desktop application, maybe even an Android app?
  * Use mDNS to make Pis easy to access without memorizing hostnames
* Displays with an eInk display


<!-- links -->
[InkyPi]: https://github.com/fatihak/InkyPi
[rpi-weather-clock]: https://github.com/mkgeiger/rpi-weather-clock
[Open-Meteo]: https://open-meteo.com/
