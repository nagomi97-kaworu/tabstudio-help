*English | [日本語](../ja/faq.md)*

# Frequently Asked Questions

### Q. What file formats are supported?

TAB loading supports Guitar Pro formats (.gp/.gp5, etc.). Audio import supports common
video file formats as well as YouTube URLs.

### Q. AI transcription accuracy seems lower than expected

Accuracy depends on the song (number of instruments, overlapping notes, mix balance,
etc.). Adjusting "minimum note length," "quantize," "capo position," and "string
assignment" in the analysis panel may help.

If it still doesn't improve, please let us know via **Report a Bug / Send Feedback**,
including the song (a YouTube URL or audio characteristics if possible).

### Q. I want to add a VSTi instrument (plugin)

You can select from VST3 plugins already installed on your PC from the instrument (INST)
field in the Track Mixer. You need to install the plugin itself separately beforehand.

### Q. I saved a project but the instrument settings are gone when I reopen it

This may be related to a known limitation around how some VSTi plugins save/restore
their internal state. If you can identify the steps that reproduce it, please let us
know via "Report a Bug" — we'll prioritize investigating it.

### Q. Can I sync video and TAB playback?

Automatic video/TAB synchronization is currently under development. We'll announce
availability via release notes and updates to this repository.

### Q. Which OS is supported?

TAB Studio is currently available for Windows.

### Q. Where do I send bug reports or feature requests?

Use **Help → Report a Bug / Send Feedback** in the app menu. A template including your
environment info is generated and copied to your clipboard — paste it into the GitHub
Issue page that opens.
