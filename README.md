# Lancer Token Tooltip Alt Configs

This repo was created to store [Token Tooltip Alt](https://foundryvtt.com/packages/token-tooltip-alt) configurations for the [Foundry VTT Lancer System](https://foundryvtt.com/packages/lancer).

In order to use these config options, make sure to open the tooltip manager in the module's settings, and then import one of the json files in this repo.

![Token Tooltip Alt json Import Example](jsonImport.png)

Following that, there may be extra configuration for each config - the TTA settings are held below.

## Bolts TTA Config

- File: `bolts-tta.json`
- Actor Data: `actor.data.data`
- Max Rows: `4`  

![Bolts TTA Preview](bolts-preview.png)

## Eranziel TTA Config

- File: `eranziel-tta.json`
- Actor Data: `actor.system`
- Max Rows: `4`
- Tooltip Manager:
  - Custom:
    - [x] Deployable

![Eranziel TTA Preview](eranziel-preview.png)

## KuroKitten TTA Config

- File: `kurokitten-tta.json`
- Actor Data: `actor.data.data.derived`
- Max Rows: `4`
- Tooltip Manager:
  - Custom:
    - [x] Pilot
    - [x] Mech
    - [x] NPC
    - [x] Deployable

![KuroKitten TTA Preview](kurokitten-preview.png)

## Valkyrion
### TTA Config 1
Variant of Eranziel's.
- File: `valkyrion-tta-1.json`
- Actor Data: `actor.data.data.derived`
- Max Rows: `4`
- Tooltip Manager:
  - Custom:
    - [x] Pilot
    - [ ] Mech
    - [ ] NPC
    - [x] Deployable

### TTA Config 2
Variant of KuroKitten's.  Includes Frame type (e.g. `BLACKBEARD`) and Pilot's Callsign for friendly mechs.  Allows token name to accommodate longer Mech names instead of just the pilot Callsign.  Works best with token display names never displayed.
- File: `valkyrion-tta-2.json`
- Actor Data: `actor.data.data.derived`
- Max Rows: `4`
- Tooltip Manager:
  - Custom:
    - [x] Pilot
    - [x] Mech
    - [x] NPC
    - [x] Deployable

![Valkyrion TTA 2 Preview](valkyrion-2-preview.png)
