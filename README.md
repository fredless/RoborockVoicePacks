# RoborockVoicePacks
Custom voice prompt packages for Xiaomi\Roborock vacuums

This repo was the culmination of my personal efforts to get our new Roborock S5 gen2 vacuum 
(whom we affectionately started referring to as Philip, and then later Phil, but who came to us out
of the box with a distinctly feminine voice package) to sound a little more British-butler-esque.

All credits to others for the research, time and free tools that allow us to both [generate custom 
encrypted voice packages](https://github.com/dgiese/dustcloud) and [conveniently upload them to
our vacuums](https://github.com/rytilahti/python-miio).  
 
Along the way I had to refresh the prompt dictionary used by dustcloud's audio_generator script,
as firmware v3.5.7_002008 shipped with a [significant refresh](
https://github.com/dgiese/dustcloud/issues/261) of both existing prompts as well as 16 additional
prompts.  As far as I know, this voice package should be fully compatible with this present version
as well as versions prior.  If new prompts show up in future firmwares this will need to be updated.

While presently this repo only contains a voice package for Phil, if I am inspired at some point
I may create more and post them here as well.