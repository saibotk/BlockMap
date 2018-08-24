# BlockMap - A Minecraft 1.13 world viewer

*This started as fork of [TMCMR](https://github.com/TOGoS/TMCMR), but has been almost completely rewritten due to the update. If you want something stable that works with 1.12 and before worlds, go check it out.*

## Features:
- A little interactive GUI based on JavaFX
- A gui library to include maps into your own JavaFX applications (mostly done, but not released yet)
- A command line interface to render your worlds from scripts
- The core rendering code as library to use in your own projects (not released yet)
- Faster than MCEdit!

## Requirements:

- Java 8+
- The gui (library and standalone) rely on JavaFX. Make sure you have it on your class path!
  - Java 8 to Java 10 already include it if you are using the Oracle JDK
  - The OpenJDK 8 has it, but not OpenJDK 10
  - If all that does not work, try installing the [OpenJFX Early-Accesss Builds](http://jdk.java.net/openjfx/)
- Minecraft 1.13 worlds. Chunks from before the release (even from 1.13 snapshots) will be ignored. Chunks from before 1.9 will throw errors. Please optimize your worlds in Minecraft before rendering them

## Download:

Download the latest version from the [Release page](https://github.com/piegamesde/BlockMap/releases).

## Usage:

The GUI version should just run by (double)clicking it. Otherwise run one of:

    java -jar BlockMap-cli-1.0.0.jar
    java -jar BlockMap-gui-1.0.0.jar

to start. The commandline version will then tell you how to use it. On Linux even with colors! (The command line isn't included in the gui standalone yet)

If your world has been created before the Minecraft 1.13 release, please optimize it. To do this, start Minecraft, select your world, go to "Edit" and then "Optimize World".
