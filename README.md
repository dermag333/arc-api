# ARC Raiders Companion - Item Locations API

Simple JSON API providing location information for items in ARC Raiders.

## Structure

Each item has a JSON file in the `items/` directory named after the item ID (lowercase).

## Format

```json
{
  "itemId": "lemon",
  "location": {
    "text": "Lemons can be found in areas with Nature loot like Buried City",
    "screenshotUrl": "https://raw.githubusercontent.com/dermag333/arc-api/main/images/lemon_location.png"
  }
}
```

## Usage

Fetch location data for an item:
```
https://raw.githubusercontent.com/dermag333/arc-api/main/items/{itemId}.json
```

Example:
```
https://raw.githubusercontent.com/dermag333/arc-api/main/items/lemon.json
```

## Images

Screenshots are stored in the `images/` directory and referenced via raw GitHub URLs.
