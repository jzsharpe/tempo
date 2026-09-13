# Tempo

A tiny workout tempo trainer. Set your reps and the seconds for each phase of the
rep, press Go, and follow the beat.

Each rep runs through four phases, in order:

| Field | Meaning |
| --- | --- |
| Neg | negative / lowering |
| Hold | hold at the bottom |
| Pos | positive / lifting |
| Pause | pause at the top |

Each phase takes any whole number of seconds from 0 to 99. A 0 skips that phase.
So the classic `1114` is Neg 1, Hold 1, Pos 1, Pause 4.

While a set runs you get the phase name, a countdown, the current rep, a puck
that slides down and back up a track, and a beep on every phase change. Your
settings are remembered between visits, and the screen is kept awake.

Sound on iPhone: beeps play through media volume even with the ringer on silent.
Leaving the app pauses the set, and tapping Resume brings back the timer and the
sound together. If iOS cuts the sound mid-set, the app says so and any tap
restores it. While a set runs with sound on, other audio such as music may pause;
turn Sound off to keep your music playing.

Live: https://jzsharpe.github.io/tempo/

Add to iPhone home screen: open the link in Safari, then Share, then Add to Home Screen.
