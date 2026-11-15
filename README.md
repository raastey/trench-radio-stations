# Trench Radio station list

Remote override for the Trench Radio app, served by GitHub Pages at
`https://raastey.github.io/trench-radio-stations/stations.json`.

The app reads this file once a day. When `version` is equal to or higher than the
bundled seed, it replaces the curated dial (stations, presets, archive shows).

- Live streams are resolved at runtime through Radio Browser (`rbUUID`); no stream
  addresses are stored here.
- Archive (`band: otr`) entries must be Internet Archive items marked public domain
  or released under an open Creative Commons licence.
- Bump `version` with every change.
