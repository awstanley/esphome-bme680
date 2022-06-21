# BME680 Component Update/Test

This is an external component used to update the BME680 code against the BME68X requirements.  At the moment it's in live testing on my sensors (all BME688s) and *most* of them seem to be updating.  (It is possible the gas is stable for some.)

## Usage

If you really need it, you can add it as an external component.  From there it's just the standard BME680 component (no changes to configuration).

```yaml
external_components:
  - source: github://awstanley/esphome-bme680
```

## Licence

ESPHome Licence (as it's sourced from the ESPHome component).