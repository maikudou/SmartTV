# KeyCodes of key events
## Samsung Tizen
```
[{"name":"0","code":48},
{"name":"1","code":49},
{"name":"2","code":50},
{"name":"3","code":51},
{"name":"3D","code":10199},
{"name":"4","code":52},
{"name":"5","code":53},
{"name":"6","code":54},
{"name":"7","code":55},
{"name":"8","code":56},
{"name":"9","code":57},
{"name":"Caption","code":10221},
{"name":"ChannelDown","code":428},
{"name":"ChannelList","code":10073},
{"name":"ChannelUp","code":427},
{"name":"ColorF0Red","code":403},
{"name":"ColorF1Green","code":404},
{"name":"ColorF2Yellow","code":405},
{"name":"ColorF3Blue","code":406},
{"name":"E-Manual","code":10146},
{"name":"Exit","code":10182},
{"name":"Extra","code":10253},
{"name":"Guide","code":458},
{"name":"Info","code":457},
{"name":"MTS","code":10195},
{"name":"MediaFastForward","code":417},
{"name":"MediaPause","code":19},
{"name":"MediaPlay","code":415},
{"name":"MediaPlayPause","code":10252},
{"name":"MediaRecord","code":416},
{"name":"MediaRewind","code":412},
{"name":"MediaStop","code":413},
{"name":"Menu","code":457},
{"name":"Minus","code":189},
{"name":"PictureSize","code":10140},
{"name":"PreviousChannel","code":10190},
{"name":"Search","code":10225},
{"name":"Soccer","code":10228},
{"name":"Source","code":10072},
{"name":"Teletext","code":10200},
{"name":"Tools","code":10135},
{"name":"VolumeDown","code":448},
{"name":"VolumeMute","code":449},
{"name":"VolumeUp","code":447}]
```

If you want to listen to key events of this buttons you should register it like this:
```
tizen.tvinputdevice.registerKey("MediaPlay")
```

When you don't want it anymore, unregister it:
```
tizen.tvinputdevice.unregisterKey("MediaPlay")
```
