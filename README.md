# Playing Sounds with the Web Audio API

This is a fix to the **"Safari HTML5 Audio and Video Guide"** example by Apple.  
[Playing Sounds with the Web Audio API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/Using_HTML5_Audio_Video/PlayingandSynthesizingSounds/PlayingandSynthesizingSounds.html#//apple_ref/doc/uid/TP40009523-CH6-SW15)

### Exploring More Possibilities

Access the raw data of the audio output by routing your sound through a real-time analyser node. Use your imagination and creativity to come up with interfaces for playing and visualizing sound.

[Listing 3-1](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/Using_HTML5_Audio_Video/PlayingandSynthesizingSounds/PlayingandSynthesizingSounds.html#//apple_ref/doc/uid/TP40009523-CH6-SW14) selects a sound at random, passes the sound through audio filters, and loops the sound while the audio spectrum is drawn on an HTML5 canvas, as shown in Figure 3-1. It also provides controls for adjusting filter properties and pausing a playing sound.

![alt text](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/Using_HTML5_Audio_Video/art/mysynth.png "Figure 3-1  A simple synthesizer and audio spectrum visualizer")
