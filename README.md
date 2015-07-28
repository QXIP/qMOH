# qMOH
"Music on Hold" collection for VoIP fruition (Royalty-Free) offered by QXIP BV



#####Convert WAV/PCM to any FFMPEG supported codec:
```
ffmpeg -i <inputfile>.wav -ar <sampling rate> -ab <bitrate> -acodec <codec> <outputfile>
```

#####Pad WAV/PCM head with 100ms silence using SOX:
```
sox input.wav output.wav pad 0.1 0
```
