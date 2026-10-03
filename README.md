# FunProgression

Android instrument by skiAudio. Piano, guitar, oud, chord patterns, and a ringtone bounce.

Package: `com.skiaudio.funprogression`

## Install

Download [funprogression.apk](funprogression.apk) (1.0.1) and install it. Uninstall the old build first — this APK is signed with a new key.

The 1.0.0 build opened `/index.html`. The router has no such route, so the WebView stayed on a black **Not Found** page. 1.0.1 opens `/`.

## Site

GitHub Pages serves this folder. Asset URLs are relative so the app works both inside the WebView and under `/FunProgression/`.

## 1.0.2

UI is fitted inside the status bar and gesture area. Leaving the app suspends every audio context and pauses media, so sound does not keep playing after close.
