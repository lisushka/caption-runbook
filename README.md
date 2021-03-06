# How do you do your captioning and transcripts?

**NOTE:** These are currently mostly notes to myself; I'm in the process of hardening this workflow before setting it up properly.

* Strip raw audio from file
* Run raw audio through voice recognition software (need to remove the roll-my-own from this and look at how viable Vosk is if you train it with Common Voice/some other open-source voice dataset/your own data, since you take a large accuracy penalty on their default model if your accent isn't `en-US`)
* Manually edit subtitle file using Visual Studio Code
* Spell-check using Vale (this will throw some false positives)
* Set timings (Vosk potentially has some ability to do this; need to investigate it better)
* Convert `.srt` file to `.ass` (need to find an open-source converter that's actually usable)
* Burn subtitles into edited video using FFmpeg

## Resources

* [**The Complete Guide to Captioned Videos**](https://meryl.net/captioned-videos-complete-guide/), by Meryl Evans.  This is the most comprehensive guide to captioning video that I have found on the Internet.
