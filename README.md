# arcturus-tools
Habbo imager for generating badge and avatar images. All credit to Wesley

## Installation

Install dependencies:
```
pip install uvicorn
```
```
pip install starlette
```

Start up the server:
```
python server.py
```

## Usage
Example usage:
```
yourhost:8000/habbo-imaging/badge/?b=b009140s211244s209240s204097
```
```
yourhost:8000/habbo-imaging/avatar?figure=lg-275-78.ch-3110-65-62.fa-1211-62.hr-110-42.ca-1807-64.hd-3093-1
```

## Updating resources
If you want to add more custom clothing or effects use the following program:
https://github.com/dank074/SpriteExtractor/releases

Then copy the output of the program to the resources directory as follows:

`/output/clothes/sprites`  -> `resources/avatar`

 `/output/clothes/manifest` -> `resources/xml/assets`

`/output/effects/sprites` -> `resources/avatar`

`/output/effects/manifest` -> `resources/xml/fx`

## Help
Visit `yourhost:8000/habbo-imaging/avatar/help` for help regarding the avatar imager.
