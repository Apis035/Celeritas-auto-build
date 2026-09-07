# Celeritas-auto-build 

Auto build of [Celeritas](https://git.taumc.org/embeddedt/celeritas), a fork of Iris 1.7 and Sodium 0.5.11 made to work on almost every Minecraft version.

This repository builds Celeritas for Minecraft 1.20.1, other version will follow up soon™ when I can figure out why 1.16.5 build is failing. For Minecraft 1.12.2, check [here](https://github.com/kappa-maintainer/Celeritas-auto-build).

## Usage on Minecraft 1.20.1

I've tried playing some 1.20.1 modpacks using Celeritas with not much issues and it performs much better than Embeddium or any other Sodium forks. ([DeceasedCraft](https://www.curseforge.com/minecraft/modpacks/deceasedcraft), [Star Technology](https://www.curseforge.com/minecraft/modpacks/star-technology), [Reclamation](https://www.curseforge.com/minecraft/modpacks/reclamation-reclaim-the-world))

What you need to do is drop Celeritas jar file into mods folder and disable any of these mods if they exist:
- Embeddium
- Oculus
- Oculus Flywheel Compat
- Colorwheel
- Sodium Options API
- Sodium Extras
- Sodium Dynamic Lights
- Chloride
- any other mods that depends on these mods
