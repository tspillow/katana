<div align="center">
  
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/e8bbf7cb-c1f4-4f24-afc4-92e106f1fd74" /> 

# Katana Linux

###### Katana Linux is an arch-based Linux distribution that adds a declarative system and more.

##### for simple people:

###### declarative arch

## Features
### Kissaki
**The official declarative system for Katana Linux.**

It is:

-- easy to use

-- flexible

-- practical

The config file is stored in `/etc/kissaki/configuration.lua`

#### Commands
 `sudo kissaki rebuild` - self explanatory
 
 `sudo kissaki reset-config` - resets the config back to stock.
 
 `sudo kissaki backup-config` - self explanatory, backs up your config to `/etc/kissaki/backups`
 
 `sudo kissaki restore-backup` - gets your backup and reuses it as the main config.

 `sudo kissaki config` - literally a shortcut to edit the config.
 
 `sudo kissaki version` - shows the version

 #### Syntax

 To learn how to write configs in Kissaki, read the wiki (W.I.P)
 or do `sudo kissaki reset-config` then edit the config file with `sudo kissaki config`.
 
### Performance-optimized:
We use ananicy-cpp, a background service that dynamically adjusts resource usage between
different applications to reduce latency.

### Many flavors
It is to be planned for Katana to have 4 flavors:

-- MATE

-- Xfce

-- bspwm

-- tty

##### Note: The `tty` flavor is a minimal environment and installation, with only the core katana features.

## source code links:

Kissaki - <https://github.com/tspillow/kissaki>
</div>
