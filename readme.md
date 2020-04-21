# Awesome SuperCollider[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![chaos](chaos-algo.png "chaos")

> A curated list of SuperCollider stuff

# Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Learning resources](#learning-resources)
  - [Written tutorials](#written-tutorials)
  - [Videos](#videos)
  - [Books](#books)
  - [Research papers](#research-papers)
  - [Others](#others)
- [Quarks, plugins and extensions](#quarks-plugins-and-extensions)
  - [Metacontrol, mapping and gestures](#metacontrol-mapping-and-gestures)
  - [Live coding](#live-coding)
  - [Live Performance](#live-performance)
  - [Controllers](#controllers)
  - [Network](#network)
  - [Physics](#physics)
  - [Buffer management](#buffer-management)
  - [Patterns](#patterns)
  - [Maths](#maths)
  - [Immersive audio](#immersive-audio)
  - [FX](#fx)
  - [Synthesis](#synthesis)
  - [GUI](#gui)
  - [Misc](#misc)
- [Synthdefs](#synthdefs)
- [Instruments](#instruments)
  - [Emulations / clones](#emulations--clones)
  - [Granular](#granular)
  - [Other](#other)
- [Physical/embedded computing](#physicalembedded-computing)
- [Clients](#clients)
  - [Language clients](#language-clients)
  - [Livecode interfaces](#livecode-interfaces)
- [IDE alternatives](#ide-alternatives)
- [Community](#community)
- [Tools](#tools)
- [Contribute](#contribute)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Learning resources

### Written tutorials
- [A gentle introduction to SuperCollider](https://ccrma.stanford.edu/~ruviaro/texts/A_Gentle_Introduction_To_SuperCollider.pdf) –  Introduction to SC by Stanford's CCRMA
- [howto_co34pt_liveCode](https://theseanco.github.io/howto_co34pt_liveCode/) - Livecoding tutorial
- [Nick Collins' SuperCollider tutorial](http://composerprogrammer.com/teaching/supercollider/sctutorial/tutorial.html) - Course material for a 12 week course on SuperCollider
- [udk00-Audiovisual_Programming](http://redfrik.github.io/udk00-Audiovisual_Programming/) - Fredrik Olofsson's course materials for UdK Berlin
- [Pseudoclasses with events](https://web.archive.org/web/20141008053015/http://www.tmroyal.com/supercollider-pseudoclasses-with-events.html) - Faking object-oriented programming in SuperCollider with Events
- [SuperCollider_Tutorials](https://github.com/brunoruviaro/SuperCollider_Tutorials) - SC tutorials
- [learn](https://github.com/supercollider/learn) - Official SuperCollider tutorial
- [A-Practical-Guide](http://doc.sccode.org/Browse.html#Streams-Patterns-Events%3EA-Practical-Guide) - A fantastic pattern tutorial (which can also be found in your help files)
- [Minibee Tutorial](http://roosnaflak.com/tech-and-research/minibee-tutorials/) - How to work with the Minibee sensors (for dance performances, etc.) in SuperCollider
- [Mads Kjeldgaard's Tech and research](https://www.madskjeldgaard.dk/tech-and-research) - A blog containing a range of tips, tricks and tutorials

### Videos
- [SuperCollider Tutorials](https://www.youtube.com/watch?v=yRzsOOiJ_p4&list=PLPYzvS8A_rTaNDweXe6PX4CXSGq4iEWYC) - Tutorials by Eli Fieldsteel covering a range of subjects
- [Audio signal processing in SuperCollider](https://www.youtube.com/playlist?list=PL1Zlv_e8Lv9g2NLtDb0X_VhIw9aR7mcJ7) - A series of lectures by Zlatko Baracskai focusing on audio signal processing. 
- [Live Coding Tutorials](https://www.youtube.com/playlist?list=PLlWmK4qVXO37vgyLeNe8ElF15pInARU6x) - Tutorials specifically about live coding
- [Masterclass "The Ambisonic Toolkit"](http://www.ambisonictoolkit.net/documentation/supercollider/tutorials/) - A general introduction to ambisonics and the ATK
- [Ultimate Arduino-To-Supercollider Tutorials- Control Signals for Digital Audio](https://www.youtube.com/playlist?list=PLAXkVXyP6y5PF2Xy0hMWiKuIdf2Zu6xnG) - How to use the Arduino micro computers with SC
- [Unity 5 and SuperCollider(Custom Sound Engine)](https://www.youtube.com/playlist?list=PLKrJig-8xIiKIznvk_0WArP2ne036TeZV) - How to setup the Unity game engine to work with SuperCollider
- [SuperCollider and Time](https://medias.ircam.fr/xb090dd_supercollider-and-time) - James McCartney (author of SuperCollider) giving a talk at IRCAM
- [SoundEngraver](https://www.youtube.com/channel/UCRxJO2INa3EWX19IfoWqS5Q) - video demos showcasing a variety of things in SC

### Books
- [Introduction to SuperCollider](https://www.logos-verlag.de/cgi-bin/engbuchmid?isbn=4017&lng=eng&id=) - Written by Andrea Valle, includes pdf. Published 2016.
- [The SuperCollider Book](https://mitpress.mit.edu/books/supercollider-book) – The essential reference. Edited by Scott Wilson, David Cottle and Nick Collins. Foreword by James McCartney. Published 2011.
- [Thor Magnussons Scoring Sound](https://leanpub.com/ScoringSound) - Cookbook containing synthesis recipes among other things
- [Mapping and Visualization with SuperCollider](https://archive.org/details/MappingAndVisualizationWithSuperCollider) - Create interactive and repsonsive audio-visual applications with SuperCollider
- [OXford Handbook of Algorithmic Music](https://www.oxfordhandbooks.com/view/10.1093/oxfordhb/9780190226992.001.0001/oxfordhb-9780190226992) - Not strictly speaking SuperCollider, but a great resource nevertheless.

### Research papers
- [Influx – Loose Control, Gain Influence](https://www.3dmin.org/research/open-development-and-design/influx/) - Super interesting article about Alberto de Campo's Influx system and gesture control/mapping in general
- [NNdef: Livecoding Digital Musical Instruments in SuperCollider using Functional Reactive Programming](http://www.friendlyvirus.org/files/Miguel-Negrao-NNdef-FARM-2018.pdf)

### Others
- [scinterviews.com](http://scinterviews.com/) - SuperCollider interviews

## Quarks, plugins and extensions

### Metacontrol, mapping and gestures
- [Influx](https://github.com/supercollider-quarks/Influx) - System for complex mapping of gestures

### Live coding
- [SuperDirt](https://github.com/musikinformatik/SuperDirt) - The sound engine of the TidalCycles pattern language
- [JITLibExtensions](https://github.com/supercollider-quarks/JITLibExtensions) - Some extensions to the common JITLib classes
- [ixiLangQt](https://github.com/thormagnusson/ixilangQt) - The ixi lang live coding environment is a simple visual system presenting a high entry-level control over synth definitions and samples in SuperCollider
- [xoxo](https://github.com/lvm/xoxo) - Embedded language for SuperCollider
- [INSTRUMENT](https://github.com/punksnotdev/INSTRUMENT) - This tool is aimed at the creation of musical compositions from scratch, 'on the fly'. INSTRUMENT focuses on musical language: rhythm, harmony, melody, audio processing

### Live Performance

- [CuePlayer](https://github.com/dathinaios/CuePlayer) - A tool for composing and performing real-time and mixed electronic works using SuperCollider.

### Controllers
- [Modality Toolkit](https://github.com/ModalityTeam/Modality-toolkit) - Powerful and modal controller library
- [NanoKontrol2](https://github.com/davidgranstrom/NanoKontrol2) - Interface for using Korg NanoKontrol2
- [NanoKontrol](https://github.com/jesusgollonet/NanoKontrol.sc) - Simple use of the Korg NanoKontrol2

### Network
- [Utopia](https://github.com/muellmusik/Utopia) - Network Music Apps in SuperCollider
- [BenoitLib](https://github.com/cappelnord/BenoitLib) - Collaborative and synchronized performances
- [OpenObject](https://github.com/supercollider-quarks/OpenObject) - Share object contents over the network via osc. 


### Physics
- [TraerPhysics](https://github.com/redFrik/TraerPhysics) - A simple particle system physics engine

### Buffer management
- [PolyBuf](https://github.com/madskjeldgaard/PolyBuf) - Easily load and access a bunch of audio files into collections of buffers in SuperCollider
- [Convenience](https://github.com/salkin-mada/Convenience) - Load entire sample banks or folder structures (folders within folders) of audio files into easily accessible collections of buffers. And more.

### Patterns
- [Repetition.sc](https://github.com/lvm/Repetition.sc) - A set of tools to build a Stream of Events using symbols and a sort of language in the language

### Maths
### Immersive audio
- [The Ambisonic Toolkit](https://github.com/ambisonictoolkit/atk-sc3) - Toolkit for working with spatial sound in the ambisonic domain

### FX
- [vstplugin](https://git.iem.at/pd/vstplugin/releases) – IEM's VST Plugin integration for SuperCollider (and Pure Data)
- [Vowel](https://github.com/supercollider-quarks/Vowel) - Convenience Class for Vowel Creation
- [PitchShiftPA](https://github.com/dyfer/PitchShiftPA) - Phase Aligned pitch shifting

### Synthesis
- [CaosPercLib](https://github.com/josecaos/caosperclib) - a Collection of Percussion Classes for SuperCollider
- [CaosBox](https://github.com/josecaos/caosbox) - a not-so-common LiveCoding/AlgoRave music GUI secuencer/processor for the CaosPercLib
- [f0plugins](https://github.com/redFrik/f0plugins) - chip tune UGens
- [Particular](https://github.com/madskjeldgaard/Particular) - particle synthesis on a per particle basis (to be used with patterns)

### GUI
- [wsGUI](https://github.com/dyfer/wsGUI.quark) - User interfaces displayed in a web browser, locally and over the network
- [Automation](https://github.com/neeels/Automation) - Record and playback live GUI activity in supercollider audio synth


### Misc
- [miSCellaneous_lib](https://github.com/dkmayer/miSCellaneous_lib) - various SuperCollider extensions and tutorials: patterns, fx sequencing, granulation, wave folding, sieves, combined lang and server gui control, live coding, single sample feedback, generalized functional iteration synthesis

## Synthdefs
- [Synthdefs](https://github.com/everythingwillbetakenaway/Synthdefs) - Synthdef Pool
- [SynthDefPool](https://github.com/supercollider-quarks/SynthDefPool) — a public library of handy SynthDefs
- [SCLOrkSynths](https://github.com/brunoruviaro/SynthDefs-for-Patterns) — Collection of SuperCollider SynthDefs (synth definitions) for use with Patterns

## Instruments

### Emulations / clones
- [DX7-SuperCollider](https://github.com/everythingwillbetakenaway/DX7-Supercollider) - accurate Yamaha DX-7 clone. Programmed in Supercollider
- [Benjolis](https://scsynth.org/t/benjolin-inspired-instrument/1074/2) - Instrument inspired by Rob Hordijk's chaotic Benjolin synth

### Granular
- [granular-synth](https://github.com/cagnolone/granular-synth) - A simple granular synth GUI, with a handy time/frequency graph
- [granular from Discrete Structures course](https://raw.githubusercontent.com/redFrik/udk18-Discrete_Structures/master/udk171214/granulator.scd) - loads a folder of files into buffers and granulates everything.

### Other
- [LNX Studio](http://lnxstudio.sourceforge.net/) - a Digital Audio Work Station. [Repository](https://github.com/neilcosgrove/LNX_Studio)

## Physical/embedded computing
- [Prynth](http://prynth.github.io/) - Prynth are programmable sound synthesizers powered by Raspberry Pi
- [supercolliderStandaloneRPI2](https://github.com/redFrik/supercolliderStandaloneRPI2) - Standalone for Raspberry Pi 2 or 3 with Raspbian Stretch including the full IDE
- [supercolliderStandaloneRPI1](https://github.com/redFrik/supercolliderStandaloneRPI1) - Standalone for Raspberry Pi 1 or Zero with Raspbian Stretch including the full IDE
- [Bela](https://blog.bela.io/2017/10/29/bela-and-supercollider-live-coding-sensors/) - Bela is an embedded computing platform for creating responsive interactive applications
- [OpenBCI-SuperCollider](https://github.com/krisztian-hofstadter-tedor/OpenBCI-SuperCollider) - SuperCollider classes for communicating with Open Brain Computer Interface
- [IBVA-BlueVAS-SuperCollider](https://github.com/krisztian-hofstadter-tedor/IBVA-BlueVAS-SuperCollider) -
A SuperCollider class for communicating with the IBVA EEG brain wave measurement headset
- [Monome norns, SuperCollider and Lua](https://medium.com/@kidsputnik/monome-norns-supercollider-and-lua-part-1-d97646306973) - Nice tutorial on getting started with SuperCollider/LUA on the Norns platform

## Clients
### Language clients
- [SuperColliderJS](https://crucialfelix.github.io/supercolliderjs/) - JavaScript client
- [hsc3](http://hackage.haskell.org/package/hsc3) - Haskell client
- [Lua2SC](https://github.com/sonoro1234/Lua2SC) - Lua client
- [ScalaCollider](https://github.com/Sciss/ScalaCollider) - Scala client
- [supriya](https://github.com/josiah-wolf-oberholtzer/supriya) - Python client
- [cl-collider](https://github.com/byulparan/cl-collider) - CommonLisp client

### Livecode interfaces
- [TidalCycles](http://tidalcycles.org/) - Haskell based live coding environment for patterns
- [FoxDot](https://foxdot.org/) – Python based live coding environment running on top of SuperCollider
- [Overtone](http://overtone.github.io/) - Collaborative live coding using Clojure
- [xi](https://github.com/xi-livecode/xi) - A domain-specific language for live coding musical patterns in Ruby

## IDE alternatives
- [atom-supercollider](https://github.com/crucialfelix/atom-supercollider) - SuperCollider integration for Atom
- [scvim](https://github.com/supercollider/scvim) - Vim plugin
- [scnvim](https://github.com/davidgranstrom/scnvim) - NeoVim plugin
- [scel](https://github.com/supercollider/scel) - Emacs interface
- [vscode_supercollider](https://github.com/salkin-mada/vscode_supercollider) - Supercollider syntax for Visual Studio Code
- [Hadron](https://github.com/htor/hadron-editor) - Simple editor with help browser and post window

## Community
- [scsynth.org](http://scsynth.org/) - Official SuperCollider forum
- [sccode.org](http://sccode.org/) - A website containing SuperCollider code. Many years worth of good ideas in here.
- [Slack](https://scsynth.slack.com/) - The SuperCollider Slack
- [Lurk](https://talk.lurk.org/channel/supercollider) – Livecode chat
- [Mailing list](https://www.birmingham.ac.uk/facilities/ea-studios/research/supercollider/mailinglist.aspx) - Official mailing list
- [Telegram](https://t.me/supercollider_en) - Telegram SuperGroup
- [Telegram ES](https://t.me/supercollider_es) - Telegram SuperGroup in Spanish
- [Facebook](https://www.facebook.com/groups/supercollider/) - The SuperCollider facebook group

## Tools
- [Build script for Linux](https://github.com/lvm/build-supercollider) - Easily build SuperCollider with plugins from source on Linux (Ubuntu/Debian)
- [Cookiecutter template for SuperCollider quarks](https://github.com/madskjeldgaard/cookiecutter-quark) - A SuperCollider package (quark) generator using the Cookiecutter cli program. The fastest way to get setup for a quark
- [Cookiecutter template for SuperCollider plugin](https://github.com/supercollider/cookiecutter-supercollider-plugin) - cookiecutter project for SuperCollider server plugins
- [superfomus](https://github.com/smoge/superfomus) - bindings to Fomus Music Notation (FOrmat MUSic)
- [SuperColliderAU](https://github.com/supercollider/SuperColliderAU) - SuperColliderAU is an AudioUnit wrapper that allows using SuperCollider servers inside AudioUnits hosts on macOS. The embedded server may be controlled over OSC as usual
## Contribute

All contributions welcome!

Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mads Kjeldgaard has waived all copyright and
related or neighboring rights to this work.

Table of Contents generated using doctoc
