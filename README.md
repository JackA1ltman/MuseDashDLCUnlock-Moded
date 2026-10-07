# Muse Dash DLC Unlock

Wanted to buy Just as Planned but missed the deadline? Don't want to buy DLC at all but still want to freeload? This is the mod for you.

>[!important]
>You should buy the genuine version—it's not that expensive.

## Instructions

1. Install [MelonLoader](https://melonwiki.xyz/#/) to the Muse Dash folder
2. Copy `MuseDashDLCUnlock.dll` to the `Mods` Game folder
3. Profit

## Build Instructions

1. Install [MelonLoader](https://melonwiki.xyz/#/) to the Muse Dash folder
2. Run Muse Dash once to populate Il2Cpp hollowed assemblies
3. Get .Net SDK latest
4. Modify the location of MuseDash in `MuseDashDLCUnlock.csproj` to ensure it is correct
5. Run command `dotnet build MuseDashDLCUnlock\MuseDashDLCUnlock.csproj` in git project folder to build DLL
6. Check DLL in `bin\Debug\net6.0\`
7. Copy `MuseDashDLCUnlock.dll` to the `Mods` Game folder

If build fails, make sure to check the location of referenced assemblies.
