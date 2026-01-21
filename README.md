# shawnb61's Reaper Scripts & JSFX

## Overview:
My Reaper Scripts & JSFX that I use & figured I'd share.

## ReaPack Installation:
This repository is available through the ReaPack REAPER extension, the free scripts/packages download manager made by cfillion. You can simply use ReaPack to batch download all scripts or scripts of your choice right from REAPER.  Further, you will automatically receive updates each time your synchronize packages.

You need to add the link to this repo by importing the following index.xml link from the Import a repository window.

https://github.com/sbulen/ReaScripts/raw/master/index.xml

## Scripts:
* sjrb-fractal-seq.eel - A fractal sequencer, that produces MIDI tracks in Reaper based on the Mandelbrot Set.
* sjrb-surr-arc.eel - This script automates surround panning, in circles or arcs, around the room.  It will operate on MIDI notes or, if no notes are selected, the media items themeselves.  Frequencies & phases can be specified or chosen at random.  Positive frequencies move counterclockwise; negative frequencies move clockwise.
* sjrb-horn-mod.eel - A simple script that adds mod wheel events over time, like a horn player does naturally.  Spices up tracks with long notes.
* sjrb-sin-mod.eel - A simple script that adds controller events in the form of a sin wave.  Frequency, starting phase, etc., are all configurable.  Can be used to drive cutoff filters, resonance, etc.  Note these curves are based on the duration of the note, not the project clock...  This gives each note a distinct shape, not necessarily tied to the project tempo (unless the note starts & ends on beat boundaries...).

## Effects:
* sjrb-MIDI-Harmonist.jsfx - This .jsfx will generate chords in realtime, with features oriented towards jamming & improvisation.  Just specify a chord, scale & intervals, then play.
* sjrb-MIDI-Transposer.jsfx - This .jsfx will transpose your performance in realtime, from one specified key/scale to another.  Just specify a "From" key and scale, a "To" key and scale, then play.
* sjrb-MIDI-ChordGen.jsfx - This .jsfx will also generate chords in realtime, useful for exploring chords in different keys.  Just specify a chord, scale & intervals, then play.
* sjrb-MIDI-CC-Compressor.jsfx - This .jsfx acts as a MIDI CC compressor and fattens up the CC curve, by increasing the input CC values.

## Requirements:
* Reaper...  No other libraries or utilities are required for these scripts.

