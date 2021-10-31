# takt2
updates to the monome takt script to incorporate global clock updates etc.
original documentation below

Current additions:
- updated to global clock
- will sync to Ableton Link and crow
- will send sync via crow
- can select 1-4 MIDI devices as a synth output 
- can select JF via crow as a synth output 
- can selet W/syn via crow as an output 
- W/syn paramters can be edited as part of the patch
- can select chords of various types instead of just single notes on syth page
- chord types can be p-locked, just like notes
- added LFO support for midi CC

To Do:
- further adjust synth page depending on output for the track
- replace PGM with ARP for JF?
- replace CC controls with Arp controls for JF? 
- enable W/syn PGM to load various presets?
- replace CC controls with W/Syn controls for W/syn
- enable Linn input for JF and W/syn
- enable crow output
- Instead of blank space in Synth device, display "JF", "W/" or "Crow" greyed out in they are not enabled.

Current issues:

- metronome seems to get faster when the tempo slows down 
- some crockles occasionally - maybe compare cpu load to original takt
- Linn input on grid doesn't play JF or W/syn
- Saving a project restarts the clock even if the clock is stopped 
- Note symbol gets highlighted when selecting the DEL tile on the main page - fixed?
- MIDI PGM change gets sent every time instead of just once when track starts
- Loading a project which is saved on the midi view page doesn't display correctly at first


![docs](lib/doc.png)
