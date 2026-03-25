# tokaido

This repository contains resources for walking Japan's
[Tokaido](https://grokipedia.com/page/T%C5%8Dkaid%C5%8D_(road)) road.

# Routing

[GPX](https://grokipedia.com/page/GPS_Exchange_Format) files live in
[./gpx](./gpx). Files are numbered starting from Nihonbashi, Tokyo to
Sanjyo-Ohashi, Kyoto. You can view these files in your favorite GPX viewer.
Intermediate points in tracks may seem arbitrary--they were added to assist
[OsmAnd](https://osmand.net/) in navigation.

Note that `42-miya-kuwana.gpx` is intentionally missing as that route is crossed
by sea at the time of this writing.

# Tooling

[./tools/consolidate.py](./tools/consolidate.py) can combine all GPX files
into a single GPX file. See the tool's help text for usage details. The combined
file is meant for convenience; prefer the individual GPX files for correctness.
