# MO Park

MO Park is a CEP motion panel for Adobe After Effects. It creates fast, adjustable IN, OUT, and continuous motion for complete 2D layers.

## Features

- Works with text, shape, image, solid, and precomp layers
- Independent IN and OUT motion
- Position, Scale, and Opacity modules
- Duration in 10-frame intervals and bipolar easing
- Continuous Position or Scale movement
- Nine-point anchor control with automatic Position compensation
- `MO Park IN` and `MO Park OUT` timeline markers
- Controls stored directly on the animated layer
- Preset library captured from the complete controls of a selected layer
- Cleaner removes only the MO Park setup

## Quick installation on Windows

Close After Effects, open PowerShell in this folder, and run:

```powershell
powershell -ExecutionPolicy Bypass -File .\install.ps1
```

Approve the administrator prompt. The installer copies the CEP extension, enables CEP debug loading, backs up `PresetEffects.xml`, and registers `MO Park Controls`.

Restart After Effects and open **Window > Extensions > MO Park**.

## Compatibility

- Windows
- Adobe After Effects with CEP support
- 2D layers
- Tested with Adobe After Effects 2026

## Author

[Bruno Jorri](https://www.instagram.com/brunojorri_work/)
