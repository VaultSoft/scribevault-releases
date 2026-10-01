# ScribeVault

**ScribeVault — offline transcription for Windows.** Turns recordings into text on your own
PC; ScribeVault itself never opens a network connection. Free trial; £49 licence coming soon.

A transcript is a first draft to check, not a certified record. ScribeVault marks the lines
it is least sure of, so you know where to listen again. Marked lines are the likeliest
mistakes. Unmarked lines can still be wrong — check anything that matters against the audio.

**Product page:** <https://vaultsoft.co.uk/scribevault/> · by VaultSoft

This repository holds release downloads only. ScribeVault's source code isn't here.

## Download

Get the latest version from [Releases](https://github.com/VaultSoft/scribevault-releases/releases).
Each release lists its ZIP's SHA256 checksum. To check a download, run this in PowerShell and
compare the result:

```powershell
Get-FileHash .\ScribeVault-v1.0.0-trial-win64.zip
```

## Third-party software

ScribeVault includes open-source software, including Qt, PySide6 and FFmpeg under the LGPL.
Each ZIP carries the full notices and licence texts in its `LICENSES` folder. The portable ZIP
is where the LGPL libraries can be replaced with your own builds; `LICENSES\README.md`
explains how, and where to get their source.

## Contact

support@vaultsoft.co.uk
