# VLC Marker prototype — reviewed draft

This archive is a source-code prototype only. It has not been compiled or tested on an Android device.

## Prototype changes
- Floating capsule menu entry in the video player's options.
- Three controls: previous marker, add marker, next marker.
- Marker timestamps stored per media URI in preferences.
- Capsule position and opacity saved in preferences.
- Center button supports tap to add, drag to move, and long-press to open opacity control.
- Dragging is constrained to the player root bounds.

## Known limitations
- No build validation has been performed.
- Previous/next navigation does not wrap.
- Marker data has no user-facing list, delete, or count.
- The source archive has no Git metadata and no Gradle Wrapper. The project build script reads Git revision during configuration, so a clean archive may need Git metadata or a small build-script adjustment before Gradle configuration.
- VLC Android's build scripts are shell-based; a Windows-native build path is not confirmed.

## Build configuration observed in the source
- Android Gradle Plugin: 9.4.1
- Gradle required by AGP: 9.6.0
- JDK: 17
- Compile SDK / Build Tools: 36 / 36.0.0
- VLC 3 NDK configured by project: 21.4.7075529

These versions are extracted from project files and are not a tested installation recipe.
