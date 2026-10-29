# survival-ai-maps

Offline map packs for the Survival AI app.

The **Build map packs** workflow cuts each region in `regions.txt` out of the latest
[Protomaps](https://protomaps.com) build of OpenStreetMap and publishes it as a file
under **Releases → maps-v1**. The app downloads these files and shows them with no
internet connection.

To add a region, add a line to `regions.txt` (`id|west,south,east,north|maxzoom`) and push.

## License

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors,
available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/).
Map tiles by Protomaps.
