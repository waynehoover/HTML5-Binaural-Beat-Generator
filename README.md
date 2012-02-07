#HTML5 Binaural Beat Generator

A pure javascript based binaural beat generator.

It has been tested in the latest version of FireFox and Chrome and should work in these browsers. There is no support for IE yet.

This work builds upon my previous [FireFox only binaural beat generator](https://github.com/BlissOfBeing/FF4-Binaural-Beat-Generator), it introduces a new technique for binaural beat generation and chrome support.

##Technique
In my previous firefox only version the requested binaural beat was created by simply adding the binaural beat to the carrier frequency of one channel while the other channel was kept steady at the carrier frequency. This technique proved to not produce binaural beats at large binaural beat frequencies.

This version takes the binaural beat frequency and divides it by two, adding this number to one channel and subtracting it from the other channel. This is the same technique used by SBaGen and Gnaural and seems to work fine for binaural beats of large frequencies.

##Credits
Sliders complementary of jQuery UI and the Aristro theme:
https://github.com/taitems/Aristo-jQuery-UI-Theme

Special thanks to the [AudioLet](https://github.com/oampo/Audiolet) javascript library. The Audiolet library does all the heavy lifting of abstracting the different sound API's, without it this project would not have been possible.

##Licence
Licensed under the [MIT license](http://www.opensource.org/licenses/mit-license)

