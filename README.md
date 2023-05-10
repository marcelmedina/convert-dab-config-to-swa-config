# convert-dab-config-to-swa-config

If you are working on Data-Api-Builder in isolation, but then you decide to leverage Static Web Apps, you will need to transition from DAB CLI to SWA CLI.

In this repo we have `Before` and `After`.

## Before
- Separate `index.html` launched on any web server.
```
python -m http.server
```
- Running DAB.
```
dab start
```

## After
- Running all together
```
swa start --data-api-location .\swa-db-connections\ 
```
