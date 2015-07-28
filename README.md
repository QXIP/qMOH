# qMOH
"Music on Hold" audio collection for VoIP fruition only (Royalty-Free) in PCM/WAV/16/44
(C) QXIP BV



#####Convert WAV/PCM to any FFMPEG supported codec:
```
ffmpeg -i <inputfile>.wav -ar <sampling rate> -ab <bitrate> -acodec <codec> <outputfile>
```

#####Pad WAV/PCM head with 100ms silence using SOX:
```
sox input.wav output.wav pad 0.1 0
```
