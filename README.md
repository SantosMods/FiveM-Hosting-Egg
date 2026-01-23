# FiveM-Hosting-Egg

Forked and rebuilt by **SantosMods.dev**.

## Origin

This project is based on the original FiveM egg created by **DEVBenSon**:  
https://github.com/DEVBenSon/pterodactyl-eggs/blob/main/Eggs-Pack/%5B%F0%9F%8E%AE%5D%20Game%20Servers/GTA%20Online%20Servers/fivem/egg-five-m.json

The original egg provided the foundation for this project.

## What remains unchanged

This fork **continues to use the original components**, including:

- **Docker images** provided by the original project  
- The original **server.cfg structure and layout**

No ownership is claimed over these components.

## Why this fork exists

The original egg had become **outdated** with newer txAdmin versions and began producing multiple **deprecation warnings**.

Several variables and startup methods used by txAdmin are marked for **future removal**, which would eventually cause breakage.

This fork exists to address those issues while keeping full compatibility with the original setup.

## Changes made

- Resolved **txAdmin deprecation warnings**
  - Migrated deprecated ConVars to supported environment variables
- Updated **default values** for clarity and usability
- Improved **install script stability**
  - Updated install logic and methods
  - Removed fragile legacy behavior
- Cleaned variable handling and startup flow
- Prepared for **future txAdmin updates**

## Goal

Provide a **modern, stable, and future-safe FiveM egg** while preserving compatibility with the original Docker images and configuration structure.

## License & Credit

- Original egg: **DEVBenSon**  
- Docker images & server.cfg: **DEVBenSon**  
- Framework inspiration: **parkervcp/eggs**  
- Modifications and maintenance: **SantosMods.dev**

This project remains released under the **MIT License**, in accordance with the original work.
