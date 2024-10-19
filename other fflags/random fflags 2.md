## this fflag list took me one hour to get

### large zoom distance
``` json
{
    "FIntCameraMaxZoomDistance": "1000000000"
}
```

### max render distance with low graphics
``` json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### no shaders (NEEDS AN EXTRA FASTFLAG TOGET IT WORKING
##### (import this json first below)
#### tip: remove all renders before using
``` json
{
    "FFlagDebugGraphicsPreferOpenGL": true
}
```
##### (then import this json)
``` json
{
    "FFlagGraphicsGLEnableSuperHQShadersExclusion": false,
    "FFlagGraphicsGLEnableHQShadersExclusion": false
}
```

### no texture (very very long)
``` json
{
    "FFlagMSRefactor5": false,
    "FStringPartTexturePackTable2022": "{\"foil\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[207,208,206,254]}}",
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"brick\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[204,201,200,232]},\"cobblestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[212,200,187,250]},\"concrete\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[208,208,208,255]},\"diamondplate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[170,170,170,255]},\"fabric\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[105,104,102,244]},\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[113,113,113,255]},\"grass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[165,165,159,255]},\"ice\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"marble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[199,199,199,255]},\"metal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[199,199,199,255]},\"pebble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[208,208,208,255]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[159,119,95,200]},\"sand\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[220,220,220,255]},\"slate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[193,193,193,255]},\"wood\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[227,227,227,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[212,209,203,255]},\"asphalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[123,123,123,234]},\"basalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[154,154,153,238]},\"crackedlava\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[74,78,80,156]},\"glacier\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[226,229,229,243]},\"ground\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[114,114,112,240]},\"leafygrass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[121,117,113,234]},\"limestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,234,230,250]},\"mud\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[130,130,130,252]},\"pavement\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[142,142,144,236]},\"rock\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[154,154,154,248]},\"salt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[220,220,221,255]},\"sandstone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[174,171,169,246]},\"snow\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,218,218,255]}}"
}
```

### lower latency
``` json
{
    "DFIntConnectionMTUSize": 900
}
```

### frame buffer
``` json
{
    "DFIntMaxFrameBufferSize": "4"
}
```


### for more guidance or details about those fastflags and more fastflags, go join the discord server below (NOT OWNED BY ME, DO NOT QUESTION ANYTHING ABOUT MY CHANNEL THX.)
### https://discord.gg/CyvwPCj3VT
###### it is someone elses, i dont have discord

### CREDITS TO https://www.youtube.com/@bloxstrapfastflags
### <3
