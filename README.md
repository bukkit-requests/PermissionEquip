# PermissionEquip
This plugin restricts players from equipping any item that can be worn if listed in the `config.yml` file.

Add the PermissionEquip.jar into the plugins folder of your Minecraft server.

## Commands
- `/pereload` - Reloads the `config.yml` file to prevent restarting the server.
  - permission - pe.reload

## Permissions
Below are all items that can be worn in any armor slot. This is needed if your server has group permissions.

<details>
<summary>Armor</summary>

- pe.netherite_helmet:
  - description: Allows a player to equip a netherite helmet. 
  - default: op 
- pe.netherite_chestplate:
  - description: Allows a player to equip a netherite chestplate.
  - default: op
- pe.netherite_leggings:
  - description: Allows a player to equip a netherite leggings.
  - default: op
- pe.netherite_boots:
  - description: Allows a player to equip a netherite boots.
  - default: op
- pe.diamond_helmet:
  - description: Allows a player to equip a diamond helmet.
  - default: op
- pe.diamond_chestplate:
  - description: Allows a player to equip a diamond chestplate.
  - default: op
- pe.diamond_leggings:
  - description: Allows a player to equip a diamond leggings.
  - default: op
- pe.diamond_boots:
  - description: Allows a player to equip a diamond boots.
  - default: op
- pe.gold_helmet:
  - description: Allows a player to equip a gold helmet.
  - default: op
- pe.gold_chestplate:
  - description: Allows a player to equip a gold chestplate.
  - default: op
- pe.gold_leggings:
  - description: Allows a player to equip a gold leggings.
  - default: op
- pe.gold_boots:
  - description: Allows a player to equip a gold boots.
  - default: op
- pe.iron_helmet:
  - description: Allows a player to equip a iron helmet.
  - default: op
- pe.iron_chestplate:
  - description: Allows a player to equip a iron chestplate.
  - default: op
- pe.iron_leggings:
  - description: Allows a player to equip a iron leggings.
  - default: op
- pe.iron_boots:
  - description: Allows a player to equip a iron boots.
  - default: op
- pe.chainmail_helmet:
  - description: Allows a player to equip a chainmail helmet.
  - default: op
- pe.chainmail_chestplate:
  - description: Allows a player to equip a chainmail chestplate.
  - default: op
- pe.chainmail_leggings:
  - description: Allows a player to equip a chainmail leggings.
  - default: op
- pe.chainmail_boots:
  - description: Allows a player to equip a chainmail boots.
  - default: op
- pe.leather_helmet:
  - description: Allows a player to equip a leather helmet.
  - default: op
- pe.leather_chestplate:
  - description: Allows a player to equip a leather chestplate.
  - default: op
- pe.leather_leggings:
  - description: Allows a player to equip a leather leggings.
  - default: op
- pe.leather_boots:
  - description: Allows a player to equip a leather boots.
  - default: op
</details>

The drop-downs below include items aren't armor but can still be worn in a certain slot.
<details>
<summary>Helmet Pieces</summary>

- pe.turtle_helmet:
  - description: Allows a player to equip a turtle shell.
  - default: op
- pe.carved_pumpkin:
  - description: Allows a player to equip a carved pumpkin.
  - default: op
- pe.player_head:
  - description: Allows a player to equip a player head.
  - default: op
- pe.zombie_head:
  - description: Allows a player to equip a zombie head.
  - default: op
- pe.skeleton_skull:
  - description: Allows a player to equip a skeleton skull.
  - default: op
- pe.wither_skeleton_skull:
  - description: Allows a player to equip a wither skeleton skull.
  - default: op
- pe.creeper_head:
  - description: Allows a player to equip a creeper head.
  - default: op
- pe.dragon_head:
  - description: Allows a player to equip a dragon head.
  - default: op
</details>

<details>
<summary>Chest Pieces</summary>

- pe.elytra:
  - description: Allows a player to equip an elytra.
  - default: op
</details>

## Config
This is the default `config.yml` file and will be generated in your `plugins\PermissionEquip` folder upon starting your Minecraft server.

#### *Note: When adding items to `config.yml` make sure the item matches the item listed under "Permissions" above.*

```
items:
  diamond_helmet:
    deny_message: "&cYou do not have permission to equip a &bDiamond Helmet&c!"
  elytra:
    deny_message: "&cYou do not have permission to equip a &bElytra&c!"
  netherite_chestplate:
    deny_message: "&cYou do not have permission to equip a &bNetherite Chestplate&c!"
