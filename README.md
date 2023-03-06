# geode-mod-action

This repository serves as a reference build.yml for building a geode mod for windows and macos via github actions.

it is highly recommended that you edit this to your own preferences

unfortunately we can't make this a github workflow action as those cant invoke another os, and cross compiling from linux -> macOS is tricky (i couldnt figure it out, besides, cross compiling requires a lot more setup)

do not use this repo as a template, use [`geode new`](https://docs.geode-sdk.org/geode/creating) instead, and then copy the .github folder