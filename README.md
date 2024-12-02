# ReaScripts

## Overview:
Some of my Reaper Scripts.

## Scripts:
* sjrb-fractal-seq.eel - A fractal sequencer, that produces MIDI tracks in Reaper based on the Mandelbrot Set.
* sjrb-surr-arc.eel - This script automates surround panning, in circles or arcs, around the room.  It will operate on MIDI notes or, if no notes are selected, the media items themeselves.  Frequencies & phases can be specified or chosen at random.  Positive frequencies move counterclockwise; negative frequencies move clockwise.
* sjrb-horn-mod.eel - A simple script that adds mod wheel events over time, like a horn player does naturally.  Spices up tracks with long notes.
* sjrb-sin-mod.eel - A simple script that adds controller events in the form of a sin wave.  Frequency, starting phase, etc., are all configurable.  Can be used to drive cutoff filters, resonance, etc.  Note these curves are based on the duration of the note, not the project clock...  This gives each note a distinct shape, not necessarily tied to the project tempo (unless the note starts & ends on beat boundaries...).

## Requirements:
* Reaper...  No other libraries or utilities are required for these scripts.

