# Atari8Bit-fonts
Fonts generated from original bitmaps from Atari 8-Bit computers.

Created by very very talented people many many years ago. Ripped by hackers lost to the mists of time. Collected by archivists for future generations.

[Recoil](http://recoil.sourceforge.net/) was used to convert to PNG. [ImageMagick](https://www.imagemagick.org/script/index.php) took the PNG and reversed, resized, chopped up and output PNM files which [Potrace](http://potrace.sourceforge.net/) then converted into SVG which was fed into [FontForge](https://fontforge.github.io/en-US/) and output as modern fonts using some [Python 2.7](https://www.python.org/) written by me as the software glue that is holding it all together.

All of these fonts are called Atari8Bit. Each one has a different weight name so they won't clutter up your font list but you still probably don't want to install a few hundred weights for a single font. *Atari8Bit-Regular* is the 'real' Atari font.

The starter font for all of these is based upon the hard work of [Mark Simonson](http://members.bitstream.net/marksim/atarimac/fonts.html). The terms of the licence he has released his Atari font under allows no modification so I had to recreate all the glyphs he drew for myself, but I have kept the layout from his font the same, the standard character set is at ASCII+0xE00, the European character set is at ASCII+$E100 and now also the Arabic character set is at ASCII+$E200. I have also mapped all the european and graphics characters to their closest UTF-8 equivalents. I'd appreciate some help with mapping the Arabic, I'm not sure I got it right and it isn't mapped to the correct UTF-8 locations yet either. There are a few fonts here with glyphs not so far mapped (Cyrillic, Greek etc.) I will add those to the correct locations eventually.


Font outlines (c)2018 Steve Boswell, no other copyright is expressed or implied.
Released under the SIL Open Font License, Version 1.1
