# ESPHome micro_wake_word Model collection

This repository serves to host micro_wake_word model files (.tflite) for ease of use with the micro_wake_word ESPHome component.

# Usage

These files can be used by referencing them by the filename without .tflite.
```
micro_wake_word:
  ...
  models:
    - model: github://dijkstrar/custom-openwakewords/models/hey_homie.json
    - model: github://dijkstrar/custom-openwakewords/models/hey_aivd.json
    - model: github://dijkstrar/custom-openwakewords/models/ok_boss.json
    - model: github://dijkstrar/custom-openwakewords/models/r2d2.json
```