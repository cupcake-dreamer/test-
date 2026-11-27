# DonutSMP

DonutSMP-inspired utility plugin for Paper 1.21.11.

## Features
- `/pay [player] [amount]`: player picker, amount entry, and sender confirmation GUI
- `/tpa <player>`: asks to teleport to the target
- `/tpahere <player>`: asks the target to teleport to the requester
- Incoming teleport request GUI with Accept and Deny buttons
- `/tpaccept` and `/tpdeny` remain available
- `/settings` GUI: independently allow/deny `/tpa`, `/tpahere`, and incoming payments; toggle sounds and request messages
- Player preferences saved in `plugins/DonutSMP/players.yml`
- Vault economy integration (EssentialsX Economy recommended)
- No home commands are registered; EssentialsX owns `/home`, `/sethome`, `/delhome`, etc.

## Requirements
Paper 1.21.11, Java 21, EssentialsX, EssentialsX Economy, Vault.

## Build
Run `gradle build` in this directory. Output: `build/libs/DonutSMP.jar`.

This is source code, not a compiled JAR. Verify dependency versions against the versions installed on your server before deployment.
