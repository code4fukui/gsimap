# gsimap
> The source code for GSI Maps, the web mapping service by the Geospatial Information Authority of Japan (GSI).

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

## Demos
- **Official GSI Maps Site:** http://maps.gsi.go.jp/
- **Demo from this Repository:** http://gsi-cyberjapan.github.io/gsimaps/

## Features
- **Dynamic Map Layers:** Configure base maps and overlays using simple text files (`layers.txt`).
- **Vector Tile Support:** Renders high-performance vector data.
- **3D Terrain Visualization:** Displays a 3D map using GSI's Digital Elevation Model (DEM) data.
- **Rich Data Overlays:** Includes built-in data for magnetic declination, municipal boundaries, and designated emergency evacuation sites.
- **SPARQL Integration:** Queries and displays open data for civic and emergency facilities.
- **Layer Definition Editor:** A built-in tool (`config.html`) to visually manage and edit map layer definitions.

## Getting Started
This project is a static website. No build process is required.

1.  Download or clone this repository.
2.  Place the files on any web server.
3.  Open `index.html` in your browser.

**Note:** While most features work when opening `index.html` directly from your local filesystem, a web server is required for full functionality, including vector tile handling.

## Customization
You can customize the map to suit your needs:
- **Change the Logo:** Edit `index.html` to replace the default logo with your own.
- **Configure Map Layers:** Use the [Layer Definition Editor](http://gsi-cyberjapan.github.io/gsimaps/config.html) to create your own `layers.txt` file, or edit the existing ones in the `/layers_txt/` directory.

## Data Sources & Attribution
- This repository is the source for the official GSI Maps site at http://maps.gsi.go.jp/.
- The geocoding service is provided by the [Center for Spatial Information Science, University of Tokyo](http://newspat.csis.u-tokyo.ac.jp/geocode/).
- The application uses various third-party libraries, including Leaflet and jQuery. See [LICENSE_LIBRARIES.md](LICENSE_LIBRARIES.md) for a full list.
- `fukuno.js` is included under a CC BY license by Taisuke Fukuno.
- **Disclaimer:** Server-side services called from gsimap are not guaranteed to be persistently in operation and may be updated or discontinued without prior notice.

## See Also
- **Layer Definition Editor:** http://gsi-cyberjapan.github.io/gsimaps/config.html
- **Layer Definition Specification:** https://github.com/gsi-cyberjapan/layers-dot-txt-spec
- **Official Layer Examples:** https://maps.gsi.go.jp/development/ichiran.html

## License
The source code created by GSI is licensed under a 2-clause BSD License. See the [LICENSE](LICENSE) file for details.

## Hashtag
The hashtag for this project is #gsimaps.
- **Twitter:** https://twitter.com/hashtag/gsimaps