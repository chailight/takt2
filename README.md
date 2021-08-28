# takt2
updates to the monome takt script to incorporate global clock updates etc.
original documentation below

Current issues:

- stop will work but won't restart
- you need to run sq clock.run(sequencer) from maiden to get it starting again
- the tempo seems to be too fast - not sure I have the clock.sync argument correct
- midi integration is untested
- midi stop and start messages need to be added
- link integration is untests


![docs](lib/doc.png)
