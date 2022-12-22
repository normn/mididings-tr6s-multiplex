# mididings-tr6s-multiplex
Quick PoC for multiplexing a single Roland TR6S across multiple channels in detached sound engine mode for use in Renoise primarily. Uses the mididings python library

In this mock-up the Roland TR6S 'Kit' control on channel 10 defines 16 scenes / channels.

On the TR6S you should set 'Utility > Sw: Off' and 'Utility > Kit Control: Patten' to allow kit control via program changes on channel 10 aka Pattern select.

# TODO / Planned / Explore

* Setup Track 1 as midi control loop for actual TR6S sound engine. All other tracks will control various other instruments.
* Create a Renoise purposed kit configurations to match kit color to track color; upload TR6S config here
* Add auto track select based on kit select
* Upload xrnx instruments from renoise to here with midi channels 1-16 defined
* Setup Volume, Delay, and Panning midi controls to a templated Renoise config to use the TR6S 'TUNE, DECAY, and CTRL' knobs for these params per track
* Setup sliders to control track effect instruments

# See also
https://das.nasophon.de/mididings/

http://dsacre.github.io/mididings/doc/

https://static.roland.com/assets/media/pdf/TR-6S_MIDIImpleChart_eng01_W.pdf
