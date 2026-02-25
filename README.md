# FiveM-Hosting-Egg

Forked and rebuilt by **SantosMods.dev**.

## Origin

This project builds on the FiveM egg created by **DEVBenSon**:  
https://github.com/DEVBenSon/pterodactyl-eggs/blob/main/Eggs-Pack/%5B%F0%9F%8E%AE%5D%20Game%20Servers/GTA%20Online%20Servers/fivem/egg-five-m.json

The original egg forms the base.

## What remains unchanged

This fork keeps the original core parts:

- **Docker images** from the original project  
- Original **server.cfg structure and layout**

No ownership is claimed over these parts.

## Why this fork exists

The original egg showed **txAdmin deprecation warnings** on newer builds.

Some ConVars and startup methods face **future removal**. This would lead to breakage.

This fork fixes those risks while keeping compatibility.

## Changes made

- Resolved **txAdmin deprecation warnings**
  - Migrated deprecated ConVars to supported environment variables
- Added **new environment variables**
  - Expanded configuration control
  - Improved deploy flexibility
- Updated **default values**
  - Clearer first run experience
- Improved **install script stability**
  - Updated install logic
  - Removed legacy behavior
- Cleaned variable handling and startup flow
- Prepared for **future txAdmin changes**

## Goal

Provide a **stable and future safe FiveM egg** while preserving compatibility with the original Docker images and configuration structure.

## License and Credit

- Original egg: **DEVBenSon**  
- Docker images and server.cfg: **DEVBenSon**  
- Framework inspiration: **parkervcp/eggs**  
- Modifications and maintenance: **SantosMods.dev**

This project stays released under the **MIT License**, aligned with the original work.
