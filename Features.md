# Getter/setter
- set, get
# Iteration
- live_loop
- .times method
# Scope
- do, end
# Built-in Functions
- use_bpm
- use_octave
# Effects 
- with_fx, :pan, :reverb, :panslicer etc
## Effect Options
- room options
- mix options
- phase options
# Samples
- sample options
- :drum_heavy_kick, :drum_snare_hard, :drum_cymbal_closed, :drum_cymbal_pedal, etc
## Sample Options
- amplitude options
# Synth
- use_synth :fm
- use_synth :pnoise etc
# Playback and Options
- sleep
- play
- attack
- release
- sustain
# Chords
- chord(:c2 :major7)
- chord(:c3, :major7, num_octaves: 2)
# Randomization
- choose(chord(:c3, :major7, num_octaves: 2))
- one_in()
- dice
- rand(), rrand(), rrand_i()

--------

# Features in Tracks

|                                            | Ditty                               | Track 1                                   | Track 2        | Track 3 |
| ---                                        | -----                               | ----                                   | ------        | ---- |
| Built-in Functions                         | sleep                               | "use\_bpm, live\_loop,                 |               |      |
| with\_fx, use\_synth"                      | "chords, sync, cue,                 |                                        |               |      |
| use\_octave, define"                       | range, ring (step, inclusive, tick) |                                        |               |      |
| Effect Options                             |                                     | room, mix, amp, pan                    |               |      |
| Effects                                    |                                     | reverb, pan                            |               |      |
| Getter/setter                              |                                     |                                        | get, set      |      |
| Iteration                                  |                                     | .times                                 | live\_loop    |      |
| Playback                                   | play                                |                                        |               |      |
| Playback Options                           |                                     | "attack, release, sustain, amp,        |               |      |
| cutoff"                                    |                                     |                                        |               |      |
| Randomization                              |                                     |                                        | .choose, rand |      |
| Rings                                      |                                     |                                        |               | ring |
| Sample Options                             |                                     | amp                                    |               |      |
| Samples                                    |                                     | "drum\_heavy\_kick, drum\_snare\_hard, |               |      |
| drum\_cymbal\_closed, drum\_cymbal\_pedal" |                                     | bass\_drop\_c                          |               |      |
| Scope                                      |                                     | do, end                                |               |      |
| Synth                                      |                                     | fm, blade, pnoise                      |               |      |
|                                            | (tutorial example)                  |                                        |               |      |
|                                            | (common melody)                     |                                        |               |      |
