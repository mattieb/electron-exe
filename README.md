electron-exe
====

This repository demonstrates how to build a Windows executable from an Electron project.

Local build
----

-   `npm install`

-   If on macOS, `brew install wine` (and go enjoy a bottle while you wait for it to build)

-   `npm run build-win32`

CircleCI
----

`circle.yml` is set up to automatically

-   Install WINE

-   Build the Windows executable

-   Keep the executable around in artifacts

The first successful build to do this was [build 6](https://circleci.com/gh/zigg/electron-exe/6).

[![CircleCI](https://circleci.com/gh/zigg/electron-exe.svg?style=svg)](https://circleci.com/gh/zigg/electron-exe)
