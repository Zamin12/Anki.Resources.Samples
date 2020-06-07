# Anki Resources SDK Sample applications

This solution contains tutorial applications for the Anki Resources SDK.

## Getting Started

### Documentation

* [Anki Resources SDK Documentation](https://randym32.github.io/Anki.Resources.SDK/)


## Sample Projects

There are three examples for now.

### Example 1 - Playing a Sound

This shows how to open the assets, list the sounds, and to play them.

### Example 2 - Playing a Sprite Sequence

This shows how to open the assets, list the sprite sequence, and to display the
frames on the screen.  This example includes some code to colourize the otherwise
grayscale PNGs (using a "ColorMatrix").  Note: set the colour to white to leave the
sprite sequences with colours alone.

### Example 3 - Playing a Composite Image animation

An example of how to play the composite images -- the image layers which can
contain sprite sequences.  Note: Not composite images reference sprite sequences.
Most of the ones are in the "Weather" groupings.

Note: these composite images often expect to layer sprite sequences on top of
the eyes, which are are rendered by the procedural face module (which isn't
emulated here...

