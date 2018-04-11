Summary of Music Projects
=========================

PureScript
----------


| Name                       | Description                                        |
| -----------------------    | -------------------------------------------------- |
| [purescript-abc-editor](https://github.com/newlandsvalley/purescript-abc-editor)   | edit, play and see scores of tunes in ABC notation    |
| [purescript-abc-tutorial](https://github.com/newlandsvalley/purescript-abc-tutorial)    | interactive ABC tutorial                           |
| [purescript-school-of-music](https://github.com/newlandsvalley/purescript-school-of-music) | port of the Haskell School of Music |
| [MIDI keyboard player](https://github.com/newlandsvalley/purescript-midi-keyboard)            | play a MIDI keyboard through the browser  |
| [purescript-audiograph](https://github.com/newlandsvalley/purescript-audiograph)            | declarative interface into web-audio  |


All these projects run in the browser, use Pux/smolder or Halogen to generate the HTML and web-audio to generate sound. The last project is an experiment built solely around purescript-webaudio. The first four projects share various libraries whose interdependencies are shown below. These include various players which are implemented as autonomous Pux modules. 

![dependencies](https://github.com/newlandsvalley/music-projects/blob/master/ps-dependencies.jpg)

The audio libraries include:


| Name                             | Description                                        |
| -------------------------------- | -------------------------------------------------- |
| [purescript-soundfonts](https://github.com/newlandsvalley/purescript-soundfonts) | play notes using web-audio soundfonts              |
| [purescript-midi](https://github.com/newlandsvalley/purescript-midi)                  | General MIDI, Web-MIDI and MIDI instruments                  |
| [purescript-abc-parser](https://github.com/newlandsvalley/purescript-abc-parser)            | parser for the ABC notation                        |
| [purescript-scores](https://github.com/newlandsvalley/purescript-scores)                | generate music scores using VexTab                 |
| various players                  | play a variety of music using a common interface   |

Note that these libraries are for use in the browser and are not available for Node.


Elm
---

Much of the same ground is covered in the Elm projects.  However, these are no longer being actively maintained - in favour of the purescript implementations. It is unlikely that I will continue to maintain them beyond Elm 0.18 although I may accept PRs.

Scala
-----

[musicrest](https://github.com/newlandsvalley/musicrest) is the backend for [tradtunedb](http://www.tradtunedb.org.uk/).

Haskell
-------

[MidiToAbc](https://github.com/newlandsvalley/MidiToAbc) attempts to convert a monophonic MIDI melody into the ABC notation.