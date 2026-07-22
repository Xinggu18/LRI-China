# China LRI Map Prototype

This is a simple static website prototype designed to be easy to edit and publish.

## Features

- A map-centered page focused on China
- Each project is shown as a red marker
- Hovering over a marker shows:
  - project name
  - short name
  - research field
  - location
- Clicking a table row or map marker moves the map to that project

## Files

- `index.html`: page structure and map logic
- `styles.css`: page styling
- `projects.js`: project data

## How to edit project data

Open `projects.js` and add more entries in this format:

```js
{
  name: "Project name",
  shortName: "Abbreviation",
  field: "Research field",
  location: "Place name",
  lat: 31.2304,
  lng: 121.4737,
}
```

## How to open the site

The easiest method:

1. Open the `map_site` folder
2. Double-click `index.html`


- Add coordinates for more projects from your Excel sheet
- Convert Excel data into `projects.js` automatically
- Color markers by research field
- Add filters such as astronomy / biology / fusion
