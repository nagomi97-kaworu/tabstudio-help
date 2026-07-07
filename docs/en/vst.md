*English | [日本語](../ja/vst.md)*

# VST Plugins (Instruments & Effects)

TAB Studio lets you assign VST3 instrument (VSTi) and effect (FX) plugins to each track
in your TAB, so playback uses that sound.

## 1. Scan for plugins

Open **File → Settings** and click **VST3 Scan**. This scans your PC's standard VST3
install location (`C:\Program Files\Common Files\VST3`) and refreshes the list of
available plugins.

- Plugins themselves must be installed separately beforehand, following each
  manufacturer's instructions (TAB Studio does not bundle any plugins), just like with
  a DAW
- Plugins installed outside the standard location are not currently detected by the scan

## 2. Assign an instrument (VSTi) to a track

Click the **Instrument (INST)** field in the Track Mixer to see the list of scanned
VSTi plugins. Selecting one makes that track play through that plugin.

- Right-click for **Open Settings** (shows the plugin's GUI) or **Unload**
- Instruments can only be swapped while playback is **fully stopped** (not while playing
  or paused)

## 3. Add effects (FX) to a track

Each track in the Track Mixer has up to 3 FX slots.

- Click an empty slot to see the list of scanned VST effect plugins
- Click a loaded slot to open the plugin's settings screen
- Right-click for **Open Settings** / **Unload**

## 4. Saving to a project

**Save Project** stores each track's instrument/FX assignments along with the plugins'
internal settings (tone, parameters, etc.). **Open Project** restores the same state
next time.

> Some plugins have a known limitation where internal settings don't save/restore
> correctly. If you can identify steps that reproduce this, please let us know via
> "Report a Bug".

## Common issues

- **A plugin doesn't show up in the list**: Confirm you ran **Settings → VST3 Scan**.
  Plugins outside the standard install location aren't currently detected
- **Can't switch instruments**: Instruments can't be swapped during playback or while
  paused. Stop playback first and try again
- **Saved instrument settings don't restore**: See also
  [Troubleshooting](troubleshooting.md)

## Related docs

- [Getting Started](getting-started.md)
- [FAQ](faq.md)
- [Troubleshooting](troubleshooting.md)
