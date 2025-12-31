### Download
Type `/client gpu` in-game to see whether you need 32 or 64 bit version.

||||
|--|--|--|
[:arrow_down: Windows 32 bit](../../../releases/download/LuaScripting/LuaScripting_windows_32.dll)|[:arrow_down: Windows 64 bit](../../../releases/download/LuaScripting/LuaScripting_windows_64.dll)
[:arrow_down: macOS 64 bit](../../../releases/download/LuaScripting/LuaScripting_macos_64.dylib)
[:arrow_down: Linux 32 bit](../../../releases/download/LuaScripting/LuaScripting_linux_32.so)|[:arrow_down: Linux 64 bit](../../../releases/download/LuaScripting/LuaScripting_linux_64.so)|[:arrow_down: Raspberry Pi](../../../releases/download/LuaScripting/LuaScripting_raspberrypi_32.so)

### Usage

`/client lua [text]`

Executes the given text as a lua script

Additionally, any `.lua` files in the `lua` folder will be automatically loaded and executed on game startup

### API

See the [common API documentation](../readme.md)

**Note:** `bytearray` arguments can be either a string (characters are treated as bytes) or a table (treated as an array of bytes)
