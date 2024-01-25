# Svara-Shodh
Identify 'Svara' (notes) of audio. 

## Uses
1) Learn to sing or play your favourite song.
2) Sharpen your skills to sing and identify the perfect Svara (note).

## Algorithm 
1) Load audio, select scale (eg C, C#)
2) Butterwoth LPF attenuates high frequencies
3) Median filter removes impulse noise, glitches and artifacts
4) Spectrogram analysis
5) Select frequency bin with max energy from each time-step
6) Match selected frequencies with notes
