Music Stream Visualizer for Garry's Mod
=======================================

This is an add-on for Garry's Mod which pipes in music from an external
source (e.g. Internet Radio) and visualizes the audio stream while
also playing it. It looks something like the below:

![Icon](icon.jpg)

Its primary intention is to be used in the creation of a virtual-club
environment (with multiple visualizers around the room) for use in on-line DJ
sets but works fine as a general internet radio / visualizer as well.

Features
--------

A number of features are touted here which set this apart visualizer from
other options in the Steam Workshop:

- Visual simplicity and smooth playback
- 3D audio (where supported) for positional audio
- Global audio/video synchronization between multiple visualizers
- Reliable, chat-based interface for admin control

Commands
--------

As an admin you may issue the following commands through (global) chat.
Parameters listed in *[Brackets]* are optional.

### Loading a Stream

Command: `/loadstream *URL*`

Loads and plays [URL] across all visualizers; defaults to the `stream_url`
cvar if not specified within the command itself.

### Stopping a Stream

Command: `/stopstream`

Stops audio / video from all visualizers.

Contributing / Source Code
--------------------------

All development of this add-on is done on [the Github page for this
project](https://github.com/yumi-xx/gmod-stream-visualizer)
so all issues / feature requests should be submitted there by creating a new
issue. Pull requests are respected and are actually very helpful in developing
/ maintaining this project.
