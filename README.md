# Free Starter Template to make your Minecraft Lobby Server

Simple Lobby for your Minecraft Server with DeluxeHub 3.

Feel free to contribute ;)

## Requirements

* Spigot / Paper 1.15

## Plugins Pack

* [DeluxeHub 3](https://www.spigotmc.org/resources/deluxehub-3-professional-hub-management-1-8-1-14-4.49425/)
* [LuckPerms](https://www.spigotmc.org/resources/luckperms-an-advanced-permissions-plugin.28140/)
* [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)
* [Vault](https://dev.bukkit.org/projects/vault)
* [Matrix AntiCheat](https://www.spigotmc.org/resources/matrix-anticheat-advanced-cheat-detection-1-8-1-12-1-13-1-14.64635/)

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
