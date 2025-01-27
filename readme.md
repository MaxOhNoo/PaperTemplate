# Maxo's Template for Paper Servers

## Server Configuration

### server.properties

``` properties
difficulty = normal
enable-command-block = true
enforce-secure-profile = false
motd = §d§lMax's Server -- Vanilla -- 1.21.4
spawn-protection = 0
simulation-distance = 12
view-distance = 12
white-list = true
```

MOTD made with <https://mctools.org/motd-creator>

### paper-world-defaults.yml

``` yml
anticheat:
    anti-xray:
        enabled: true
        engine-mode: 1
        hidden-blocks:
        - chest
        - coal_ore
        - deepslate_coal_ore
        - copper_ore
        - deepslate_copper_ore
        - raw_copper_block
        - diamond_ore
        - deepslate_diamond_ore
        - emerald_ore
        - deepslate_emerald_ore
        - gold_ore
        - deepslate_gold_ore
        - iron_ore
        - deepslate_iron_ore
        - raw_iron_block
        - lapis_ore
        - deepslate_lapis_ore
        - redstone_ore
        - deepslate_redstone_ore
        lava-obscures: false
        max-block-height: 72
        replacement-blocks: []
        update-radius: 2
        use-permission: false
```

## Plugins

### [Graves](https://modrinth.com/plugin/axgraves)

#### config.yml

``` yml
despawn-time-seconds: -1
interact-only-own: true
instant-pickup-only-own: true

# Just lets KeepInventory work
override-keep-inventory: true
```

### [Freeze](https://www.spigotmc.org/resources/freeze.31822/)

#### Admin Commands

``` properties
/freeze <player> [time]
/freeze-all
/melt <player>
/melt-all
```

### [PVP Toggle](https://modrinth.com/plugin/slash-pvp)

#### Admin Commands

``` properties
/pvp
```

### [Teleport](https://modrinth.com/plugin/teleport)

#### Admin Commands

``` properties
/tp <player>
/tpto <player | *>
/tphere <player | *>
/vanish <player>
/unvanish <player>
```

### [Grim AC](https://modrinth.com/plugin/grimac)

#### punishments.yml

Alerts only, no automatic punishments

### [FreedomChat](https://modrinth.com/plugin/freedomchat)

#### config.yml

``` yml
# Tells clients that 'secure chat' is enabled, mostly removing the "Chat messages can't be verified" toast notification
claim-secure-chat-enforced: true

send-prevents-chat-reports-to-client: true
```

### [LibertyBans](https://modrinth.com/plugin/libertybans)

#### Admin Commands

``` properties
/ban <player> [time]
/ipban <player> [time]
/unban <player>
/unbanip <player>
/mute <player> [time]
/unmute <player>
/kick <player>
/banlist
/mutelist
/history <player>
```

### [PaperTweaks](https://hangar.papermc.io/Machine_Maker/PaperTweaks)

**Player Head Drops (On kill by Player)**

**Villager Death Messages**

**AFK Display (Gray username after 5 mins)**

**Custom Nether Portals (6 squares minimum, crying obsidian allowed)**

**Fast Leaf Decay**

**Unlock all crafting recipes**
