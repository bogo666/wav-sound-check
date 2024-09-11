# wave-sound-check

Using the Apple Digital Masters tools `afconvert` & `afinfo` on MacOS,
produce Apple Music "sound check" info, useful for Audio Mastering Engineers.

Info about Apple Digital Masters is available here:
<https://www.apple.com/apple-music/apple-digital-masters/>

Copyright (c) 2024 Chris Foote.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.

## Example Output

```text
$ ./wav-sound-check some_premaster.wav 
Sound Check Info for somme_premaster.wav
========================================

Approx Length:          00h:02m:53.54s
Bit Depth:              24
Sample Rate:            48 kbps
Loudness iLUFS:         -21.0245
Max Short-term LUFS:    -17.5142
Loudness Range:         10.9
True Peak:              -3.92289
Crest Factor:           -17.10161
Max Momentary LUFS:     -14.8636
Sound Check Norm Gain:  2.92

                     Left               Right
Noise Floor:         -125.03            -125.15
```
