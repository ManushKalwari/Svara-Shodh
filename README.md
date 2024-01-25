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

## Song Samples
![download (4)](https://github.com/ManushKalwari/Svara-Shodh/assets/125916187/0a5315c4-a58c-4197-9a61-b421bfb48e21)
![download (5)](https://github.com/ManushKalwari/Svara-Shodh/assets/125916187/2e66b496-0dcf-4d14-9e0c-96463184fa5e)
![download (1)](https://github.com/ManushKalwari/Svara-Shodh/assets/125916187/1238b71c-3e22-46ef-ac15-ca45b5a7b5e0)
