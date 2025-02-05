<div align="center">

<img src=https://github.com/fxmorin/MoreCulling/blob/master/src/main/resources/assets/moreculling/MoreCulling.png>

# More Culling

[![Mod Environment](https://img.shields.io/badge/Enviroment-Client-blue?style=round)](https://github.com/fxmorin/moreculling)
[![Latest Minecraft Version](https://img.shields.io/badge/Latest%20MC%20Support-1.19-green?style=round)](https://github.com/fxmorin/moreculling/releases)
[![Hits Of Code](https://hitsofcode.com/github/fxmorin/moreculling?branch=master)](https://github.com/fxmorin/moreculling)

[![Modrinth Downloads](https://img.shields.io/badge/dynamic/json?color=5da545&label=downloads&prefix=+%20&query=downloads&url=https://api.modrinth.com/api/v1/mod/51shyZVL&style=round&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMSAxMSIgd2lkdGg9IjE0LjY2NyIgaGVpZ2h0PSIxNC42NjciICB4bWxuczp2PSJodHRwczovL3ZlY3RhLmlvL25hbm8iPjxkZWZzPjxjbGlwUGF0aCBpZD0iQSI+PHBhdGggZD0iTTAgMGgxMXYxMUgweiIvPjwvY2xpcFBhdGg+PC9kZWZzPjxnIGNsaXAtcGF0aD0idXJsKCNBKSI+PHBhdGggZD0iTTEuMzA5IDcuODU3YTQuNjQgNC42NCAwIDAgMS0uNDYxLTEuMDYzSDBDLjU5MSA5LjIwNiAyLjc5NiAxMSA1LjQyMiAxMWMxLjk4MSAwIDMuNzIyLTEuMDIgNC43MTEtMi41NTZoMGwtLjc1LS4zNDVjLS44NTQgMS4yNjEtMi4zMSAyLjA5Mi0zLjk2MSAyLjA5MmE0Ljc4IDQuNzggMCAwIDEtMy4wMDUtMS4wNTVsMS44MDktMS40NzQuOTg0Ljg0NyAxLjkwNS0xLjAwM0w4LjE3NCA1LjgybC0uMzg0LS43ODYtMS4xMTYuNjM1LS41MTYuNjk0LS42MjYuMjM2LS44NzMtLjM4N2gwbC0uMjEzLS45MS4zNTUtLjU2Ljc4Ny0uMzcuODQ1LS45NTktLjcwMi0uNTEtMS44NzQuNzEzLTEuMzYyIDEuNjUxLjY0NSAxLjA5OC0xLjgzMSAxLjQ5MnptOS42MTQtMS40NEE1LjQ0IDUuNDQgMCAwIDAgMTEgNS41QzExIDIuNDY0IDguNTAxIDAgNS40MjIgMCAyLjc5NiAwIC41OTEgMS43OTQgMCA0LjIwNmguODQ4QzEuNDE5IDIuMjQ1IDMuMjUyLjgwOSA1LjQyMi44MDljMi42MjYgMCA0Ljc1OCAyLjEwMiA0Ljc1OCA0LjY5MSAwIC4xOS0uMDEyLjM3Ni0uMDM0LjU2bC43NzcuMzU3aDB6IiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGZpbGw9IiM1ZGE0MjYiLz48L2c+PC9zdmc+)](https://modrinth.com/mod/moreculling)
[![GitHub Downloads via the Releases section](https://img.shields.io/github/downloads/fxmorin/moreculling/total?style=round&logo=github)](https://github.com/fxmorin/moreculling)
[![CurseForge downloads](https://cf.way2muchnoise.eu/moreculling.svg)](https://curseforge.com/minecraft/mc-mods/moreculling)

### A mod that changes how multiple types of culling are handled in order to improve performance  
###### Culling is when you don't render things that the player can't see, to improve performance

**Make sure to report any bugs [here](https://github.com/fxmorin/moreculling/issues)!**  

</div>
  
## Current Bugs fixed:  
- [MC-249693](https://bugs.mojang.com/browse/MC-249693) - Chorus plant culling  
- [MC-238739](https://bugs.mojang.com/browse/MC-238739) - Bamboo culling (without leaves)  
- [MC-209633](https://bugs.mojang.com/browse/MC-209633) - Glass pane culling  
- [MC-139620](https://bugs.mojang.com/browse/MC-139620) - Fence culling (some exceptions)  
- [MC-217653](https://bugs.mojang.com/browse/MC-217653) - End Rod culling (some exceptions)

**Plus a lot more that haven't been reported or tested**  

## Other Features:  
- Item Frame culling  
  
## Comparing Performance  
**Results may vary drastically!**  
Without MoreCulling, I get around ~136 frames  
![Normal - FPS ~136](https://github.com/fxmorin/MoreCulling/blob/master/images/normally.png)  
With MoreCulling, I get around ~210 frames  
![MoreCulling - FPS ~210](https://github.com/fxmorin/MoreCulling/blob/master/images/moreculling.png)  
Don't mind that bar, it was a screenshot.  
Do not expect these results all the time. Bamboo renders 2 extra faces for each block without MoreCulling, which is why the results are so drastic here!  
  
## More Info    
Feel free to contribute to the project!  
I'm also fine if you use this mod in your modpacks  

### My other optimization/bugfix mods:  
* [MemoryLeakFix](https://github.com/fxmorin/memoryLeakFix) - self-explanatory
* [Carpet-Fixes](https://github.com/fxmorin/carpet-fixes) - Largest Server-Side Bug fixing mod  
* [Blanket](https://github.com/BlanketMC/blanket-client-tweaks) - Client-side tweaks/fixes  

---
  
I don't give consent to Debugify to use this mod (or any mod) to merge my mod into another mod and [there's a reason for that](https://gist.github.com/fxmorin/9770473614e3e5e0703e44273dab33f7).
