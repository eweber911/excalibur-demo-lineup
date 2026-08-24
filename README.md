# Excalibur demo lineup

A small demo channel lineup and XMLTV guide, published so that Excalibur, an Apple TV
player, can be evaluated by anyone who does not have an IPTV subscription of their own.
It exists mainly so an App Store reviewer has something to watch.

- `playlist.m3u` — nine channels in three groups
- `guide.xml` — an XMLTV guide covering all nine

## What the channels are

| Group | Channels |
|---|---|
| Live | Unified Streaming Live, Mux Live Test |
| Open Cinema | Tears of Steel, Big Buck Bunny, Tears of Steel HD |
| Reference Streams | Apple Advanced Sample, Apple 16:9 Sample, Apple 4:3 Sample, Mux Timing Sample |

Every entry is either a public HLS reference stream published for developer testing, or a
Blender Foundation short film released under [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/).
*Tears of Steel* (2012) and *Big Buck Bunny* (2008) are both © Blender Foundation, used
under that license.

Nothing here is a broadcast signal, and nothing here is anyone's subscription content.

## Note on the guide

`guide.xml` carries real clock times and is regenerated periodically. If the listings look
empty, the file has aged out and needs regenerating.
