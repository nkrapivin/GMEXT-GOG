# GMEXT-GOG
Repository for GameMaker's GOG Extension

This repository was created with the intent of presenting users with the lastest version available of the extension (even previous to marketplace updates) and also provide a way for the community to contribute with bug fixes and feature implementation.

This extension will work on Windows and macOS.

VISUAL STUDIO SOURCE: `source/GOG_vs/`

XCODE SOURCE: `source/GOG_xcode/`

After compilation the exported dll/dylib file is automatically copied into the extension folder inside the included GameMaker project folder.

## Requirements

In order to compile for Windows/macOS you are required to [download the EpicOnlineSerives SDK v1.150](https://devportal.gog.com/welcome) and place it inside `source/GOG_sdk/`

## Documentation

We provide both a PDF version of the documentation included with the extension and inside the demo project (datafiles) and a fully converted version to the [Github Wiki](https://github.com/YoYoGames/GMEXT-GOG/wiki) format (the latter will be the most up-to-date version, the other will follow shortly after). *If there are any PR requests with new feature implementation please make sure you also provide the documentation for the implemented features.*