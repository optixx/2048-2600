2048 2600
=========

A port of the [2048][1] game to the [Atari 2600][4].

(because there aren't enough [versions of this game]([11])! :laughing:)

## Running

You will need either an emulator (e.g., [Stella][13]) or a real Atari with an [Harmony][14] cart. In either case, just download [2048.rom][2] and run as a normal Atari game.

## Bulding / Development info

All the juicy details are included on [2048.asm][3], the main source file, and a bit more nicely formatted [here][12].

## Author and License

© 2014 by Carlos Duarte do Nascimento (Chester)

Based on the [original 2048 game][1] by Gabriele Cirulli

Released under the [MIT license][9].

If you have any questions/comments/rants, feel free to contact me on [Twitter][7], on my [blog][8] or simply [write an e-mail][10]!

## Special Thanks

- [Lucas][30], [Diogo][31], and [Bani][32], for support and suggestions.
- All the nice people at the [AtariAge forum][http://atariage.com/forums/forum/50-atari-2600-programming/], for making lots of information available.

## Pending
### Known Bugs
- Very infrequently we have an extra scanline. Seems to happen when lots of tiles are shifted.

### Things that would be nice

- Animation for new tiles
- Animation for merged tiles
- Counting points
- Time-based multiplayer like [Emil Stolarsky's][6]
- Turn-based multiplayer (survival-style), one or two players
- An easter egg (after all, Atari 2600 [pioneered][5] the genre)
- Different colors for each tile value (this one is **hard**. I've almost
managed to do it, but I'm missing a few cycles to change the colors quick enough)

[1]: https://github.com/gabrielecirulli/2048
[2]: https://github.com/chesterbr/2048-2600/blob/master/2048.bin?raw=true
[3]: https://github.com/chesterbr/2048-2600/blob/master/2048.asm
[4]: http://atariage.com/2600/history.html
[5]: https://www.youtube.com/watch?v=Pw02kibMs3E
[6]: http://emils.github.io/2048-multiplayer/
[7]: http://twitter.com/chesterbr
[8]: http://chester.me
[9]: https://github.com/gabrielecirulli/2048/blob/master/LICENSE.txt
[10]: mailto:cd@pobox.com?subject=2048+2600
[11]: http://phenomist.wordpress.com/2048-variants/
[12]: http://chester.me/2014/03/2048-2600
[13]: http://stella.sourceforge.net/
[14]: http://harmony.atariage.com/Site/Harmony.html
[30]: http://github.com/lxfontes
[31]: http://github.com/dterror
[32]: http://github.com/bani
