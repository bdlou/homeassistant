# Inovelli LZW31-SN Red Dimmer (Z-Wave JS) - Firmware v1.57+

This blueprint supports Inovelli Red Series LZW31-SN dimmers running firmware v1.57+ that emit numeric Central Scene values via the Z-Wave JS integration.

## Supported Actions

- Up/Down paddle: single, double, triple, 4x, 5x
- Up/Down held
- Config button single press

## Requirements

- Home Assistant with Z-Wave JS integration
- LZW31-SN dimmer with firmware v1.57 or newer

## Installation

1. Copy `inovelli_lzw31_sn_dimmer_zwave_js_fw157.yaml` to: config/blueprints/automation/louis-martinez/inovelli_lzw31_sn_dimmer_zwave_js_fw157.yaml
2. Reload Blueprints under **Settings > Automations & Scenes > Blueprints**
3. Create a new automation using the blueprint titled: Inovelli Red Series LZW31-SN Dimmer (ZWave-JS, FW v1.57)

## Credits

Authored by Louis Martinez, based on the original Jeremy Johnson blueprint.
