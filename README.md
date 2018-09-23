# OSM-Tiles-Joint

OSM Tile Server test run.

## Usage

```
git clone {PROJECT};
cd {PROJECT};

# Import file in tiles
docker-compose -f docker-compose.build.yml up;

# Load the server up
docker-compose up;
```

Your tiles will now be available at http://localhost:80/tile/{z}/{x}/{y}.png. If you open `leaflet-demo.html` in your browser, you should be able to see the tiles served by your own machine. Note that it will initially quite a bit of time to render the larger tiles for the first time.

## References

Copyright 2018 Alexander Overvoorde
Built on top of https://github.com/Overv/openstreetmap-tile-server

## License

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
