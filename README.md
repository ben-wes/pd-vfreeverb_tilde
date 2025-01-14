# vfreeverb~

Freeverb abstraction around the patch shared here by Katja Vetter:
* https://forum.pdpatchrepo.info/topic/6247/freeverb-in-vanilla-pd

I only made this an abstraction with messages and creation arguments for the parameters.

Expects 2-channel multichannel input (and outputs a 2-channel signal).

Messages:
* `roomsize <0..1>` (default: 0.7)
* `damp <0..2>` (default: 1.8)
* `dry <0..1>` (default: 0.7)
* `wet <0..1>` (default: 0.3)

Creation args:
* 4 float values for the 4 parameters in the order above
