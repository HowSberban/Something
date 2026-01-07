[简体中文](https://github.com/HowSberban/Something/blob/main/Q%26A/zh_CN.md)  **English**  

# Welcome to Q&A
  Most of the introductions and questions will be listed here.  

## Introduction
Includes basic optimizations and partial OptiFine features, making the game more comfortable to play.  
Version numbers follow the format **Year.Month.Day**(like 26.01.04).

## Requirements
- Java 22 or above  
  > If you don’t want to install Java 22 or higher, please remove the mod **C2ME**.  
  In that case, Java 21 or above is still required.  
- Recommended: Install Java 25, since Minecraft versions after **26.1-snapshot-1** require Java 25.  
- If you are on mobile and encounter issues, please troubleshoot on your own.

## Mod Notes
> If you don’t understand or know how to use a mod, check [Modrinth](https://modrinth.com).  

1. **C2ME (Chunk optimization)**  
   Requires Java 22 or above.  

2. **ViaFabricPlus (Version translation)**  
   Since the game version is too new, ViaFabricPlus is included to allow playing on older servers (modpacks that include this mod are usually released as Beta versions
).  
   However, this is unfriendly to low-performance devices (version translation consumes CPU).  
   If servers requiring version translation are too laggy, please play on the corresponding Minecraft version instead.  

3. **DistantHorizons**  
   An optimization mod. Ultra render distance is just an extra feature.  
   You can set this mod’s render distance to 32, while vanilla render distance is lowered to 12 or less.  
   This reduces far terrain quality for optimization, friendly for integrated graphics.  
   If your CPU is extremely weak, please remove it, otherwise it may cause negative optimization.  

4. **caramelChat (IME mod)**  
   Windows users can skip.  
   Some Linux and macOS systems are incompatible and may freeze. Please remove if needed.  
   You can check the mod’s [GitHub page](https://github.com/LemonCaramel/caramelChat) for system configuration.  

### Q&A
- **Q: Why use DistantHorizons instead of Voxy?**  
  **A:** Voxy currently does not support most features of DistantHorizons, which can be inconvenient for beginners.  

- **Q: Why not add BadOptimizations?**  
  **A:** It causes sky stuttering, breaking immersion.  

- **Q: Why not add Krypton?**  
  **A:** Krypton is a server-side network stack optimization mod.  
  Testing shows that installing it on both server and client causes random packet loss.  
  With few players in simple LAN play, optimization effects are negligible.  

- **Q: Why not add FerriteCore?**  
  **A:** Its memory optimization is aggressive, intended for severely memory-limited systems.  
  Unless allocated memory is below 2GB, optimization is negligible and FPS may drop.  

## Resource Pack Notes
Includes two resource packs, both for mod localization.  

- **Cull Leaves (Leaf rendering optimization)**  
  Provides a resource pack (`cullleaves/smartleaves`), included by default, to make leaves look less ugly.  

## Keybinds
- **C (Hold)** – Zoom in  
- **O** – Shader selection menu  
- **K** – Enable/disable shaders  
- **R** – Reload shaders  
- Other keys follow vanilla settings
