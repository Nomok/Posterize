# Posterize

## Purpose
A shader that adds a simple posterize effect.

## Compiling:

### Requisites:
FXC (apart of the [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/))

### Windows: 
1. Insert `FXC.exe` into the root directory or insert the path for FXC in line 11 of `CompileShader.bat`
2. Run `CompileShader.bat`
3. You should get a successful compilation message:
```
fxc.exe "Posterize.hlsl" /nologo /WX /Ges /Qstrip_reflect /Qstrip_debug /Tps_4_0 /Eps_main /Fo"Posterize.fxc"
compilation object save succeeded; see ROOT\Posterize.fxc

fxc.exe "Posterize.hlsl" /nologo /WX /Ges /Qstrip_reflect /Qstrip_debug /Tps_4_0 /Eps_main_pm /Fo"Posterize.premultiplied.fxc"
compilation object save succeeded; see ROOT\Posterize.premultiplied.fxc
.
Shaders compiled ok
```

## TODO
- Android Support
- MacOS / IOS Support