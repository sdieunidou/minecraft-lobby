# Free Simple Minecraft Lobby Server Template

Simple Lobby for your Minecraft Server with DeluxeHub 3.

## Requirements

* Spigot / Paper 1.15

## Plugins Pack

* DeluxeHub
* LuckPerms
* PlaceholderAPI
* Vault
* Matrix AntiCheat 

## Permissions

LuckPerms is included with two groups:

* Admin (admin group
* Default (default permission group)

To add full rights to an user:

```
lp user <username> parent add admin
```

To remove an user from the admin group:

```
lp user <username> parent remove admin
```

## Add permissions to a group

An user inherit of all preconfigured permissions of this group. If you install more plugin, add permissions to groups `admin` and `default` (player) with `lp group <groupName> permission set <permissionName> <permissionValue>`, for example:

```
lp group admin permission set luckperms.* true
lp group admin permission set deluxehub.* true
lp group admin permission set vault.* true
lp group admin permission set matrix.* true
lp group admin permission set placeholderapi.* true
lp group default permission set scoreboard.use true
```
