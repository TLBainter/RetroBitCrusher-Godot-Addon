# RetroBitCrush
Real-time, configurable bit crusher audio bus effect for Godot 4 by T. L. Bainter

## Requirements
Godot 4.6+
Linux/Windows

## Install
Copy the **/addons/** folder into your Godot project root as** res://addons/retroBitCrush/**.
Restart the editor.
In Godot's _Audio_ panel, the _RetroBitCrush_ effect will be selectable from the _Effect_ dropdown on any audio bus.

## Properties
**Target Rate**: sample rate at which the audio is capped.

**Bit Depth**: bits per sample.

**Lowpass Cutoff**: cut off to minimize harsh sounds that result from real-time crushing.

## Recommended/Default Values
**Target Rate**: 11025Hz

**Bit Depth**: 16

**Lowpass Cutoff**: 5500Hz

# License
This addon is released under Creative Commons with no attribution requirement. You are free to use it commercially or non-commercially without crediting me. If you do choose to credit me, I'd greatly appreciate it! You may do so with text such as:

### RetroBitCrush Addon for Godot Created by T. L. Bainter

Troubleshooting
**Linux**: There is a known error that may cause the editor to crash on first load of this addon. Simply restart the editor after the crash and the problem should subside.

**MacOS**: I have not been able to fully test this addon for MacOS, but the system should function the same way on MacOS as it does for Linux/Windows. Please let me know if you it works for you on MacOS so I can confirm!
