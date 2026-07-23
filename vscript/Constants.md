## Constants
```
TF2 Classified build 5011
Squirrel 3.1 stable (_versionnumber_ = 310)
API dump taken: 2026-07-22
```
### AE_TYPE_CLIENT
  - **Value**: 16 (_integer_)
  - **Description**: Animation event flag which indicates an event is supposed to be clientside only.

### AE_TYPE_FACEPOSER
  - **Value**: 32 (_integer_)
  - **Description**: Animation event flag with an unknown purpose. Presumably related to Faceposer.

### AE_TYPE_NEWEVENTSYSTEM
  - **Value**: 1024 (_integer_)
  - **Description**: Animation event flag which indicates an event is using the new system. This is often used by class-specific events from NPCs.

### AE_TYPE_SCRIPTED
  - **Value**: 2 (_integer_)
  - **Description**: Animation event flag with an unknown purpose.

### AE_TYPE_SERVER
  - **Value**: 1 (_integer_)
  - **Description**: Animation event flag which indicates an event is supposed to be serverside only.

### AE_TYPE_SHARED
  - **Value**: 4 (_integer_)
  - **Description**: Animation event flag which indicates an event is supposed to be shared between the server and client.

### AE_TYPE_WEAPON
  - **Value**: 8 (_integer_)
  - **Description**: Animation event flag which indicates an event is part of a weapon.

### AISS_AWAKE
  - **Value**: 0 (_integer_)
  - **Description**: NPC is awake. (NPC sleep state used in Get/SetSleepState())

### AISS_WAITING_FOR_INPUT
  - **Value**: 3 (_integer_)
  - **Description**: NPC is asleep and will only awaken upon receiving the Wake input. (NPC sleep state used in Get/SetSleepState())

### AISS_WAITING_FOR_PVS
  - **Value**: 2 (_integer_)
  - **Description**: NPC is asleep and will awaken upon entering a player's PVS. (NPC sleep state used in Get/SetSleepState())

### AISS_WAITING_FOR_THREAT
  - **Value**: 1 (_integer_)
  - **Description**: NPC is asleep and will awaken upon seeing an enemy. (NPC sleep state used in Get/SetSleepState())

### AI_SLEEP_FLAGS_NONE
  - **Value**: 0 (_integer_)
  - **Description**: No sleep flags. (NPC sleep flag used in Add/Remove/HasSleepFlags())

### AI_SLEEP_FLAG_AUTO_PVS
  - **Value**: 1 (_integer_)
  - **Description**: Indicates a NPC will sleep upon exiting PVS. (NPC sleep flag used in Add/Remove/HasSleepFlags())

### AI_SLEEP_FLAG_AUTO_PVS_AFTER_PVS
  - **Value**: 2 (_integer_)
  - **Description**: Indicates a NPC will sleep upon exiting PVS after entering PVS for the first time(?) (NPC sleep flag used in Add/Remove/HasSleepFlags())

### ALL_CONTEXTS
  - **Value**: -1048576 (_integer_)
  - **Description**: All sound contexts useable in QueryHearSound hooks, etc.

### ALL_SCENTS
  - **Value**: 224 (_integer_)
  - **Description**: All "scent" sound types useable in QueryHearSound hooks, etc.

### ALL_SOUNDS
  - **Value**: 1048351 (_integer_)
  - **Description**: All sound types useable in QueryHearSound hooks, etc.

### ALL_VISIBLE_CONTENTS
  - **Value**: 255 (_integer_)
  - **Description**: Contains all visible spatial content flags.

### AUTOAIM_10DEGREES
  - **Value**: 0.173648 (_float64_)
  - **Description**: 10-degree autoaim cone.

### AUTOAIM_20DEGREES
  - **Value**: 0.349066 (_float64_)
  - **Description**: 20-degree autoaim cone.

### AUTOAIM_2DEGREES
  - **Value**: 0.034899 (_float64_)
  - **Description**: 2-degree autoaim cone.

### AUTOAIM_5DEGREES
  - **Value**: 0.087156 (_float64_)
  - **Description**: 5-degree autoaim cone.

### AUTOAIM_8DEGREES
  - **Value**: 0.139173 (_float64_)
  - **Description**: 8-degree autoaim cone.

### AUTOAIM_SCALE_DEFAULT
  - **Value**: 1.000000 (_float_)
  - **Description**: Indicates default auto aim scale.

### AUTOAIM_SCALE_DIRECT_ONLY
  - **Value**: 0.000000 (_float_)
  - **Description**: Indicates auto aim should not be used except for direct hits.

### CHAN_AUTO
  - **Value**: 0 (_integer_)
  - **Description**: The default generic sound channel.

### CHAN_BODY
  - **Value**: 4 (_integer_)
  - **Description**: The sound channel used for clothing, ragdoll impacts, footsteps, knocking/pounding/punching etc.

### CHAN_ITEM
  - **Value**: 3 (_integer_)
  - **Description**: The sound channel used for generic physics impact sounds, health/suit chargers, +use sounds.

### CHAN_REPLACE
  - **Value**: -1 (_integer_)
  - **Description**: The sound channel used when playing sounds through console commands.

### CHAN_STATIC
  - **Value**: 6 (_integer_)
  - **Description**: The sound channel for constant/background sound that doesn't require any reaction.

### CHAN_STREAM
  - **Value**: 5 (_integer_)
  - **Description**: The sound channel for sounds that can be delayed by an async load, i.e. aren't responses to particular events.

### CHAN_VOICE
  - **Value**: 2 (_integer_)
  - **Description**: The sound channel used for dialogue, voice lines, etc.

### CHAN_VOICE2
  - **Value**: 7 (_integer_)
  - **Description**: An additional sound channel for voices. Used in TF2 for the announcer.

### CHAN_VOICE_BASE
  - **Value**: 8 (_integer_)
  - **Description**: The sound channel used for network voice data (online voice communications).

### CHAN_WEAPON
  - **Value**: 1 (_integer_)
  - **Description**: The sound channel for player and NPC weapons.

### CLASS_NONE
  - **Value**: 0 (_integer_)
  - **Description**: No class.

### CLASS_PLAYER
  - **Value**: 1 (_integer_)
  - **Description**: Used by players.

### CLASS_PLAYER_ALLY
  - **Value**: 2 (_integer_)
  - **Description**: Used by player allies.

### CLIENT_DLL
  - **Value**: 0 (_integer_)

### COLLISION_GROUP_BREAKABLE_GLASS
  - **Value**: 6 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_DEBRIS
  - **Value**: 1 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_DEBRIS_TRIGGER
  - **Value**: 2 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_DISSOLVING
  - **Value**: 16 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_DOOR_BLOCKER
  - **Value**: 14 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_INTERACTIVE
  - **Value**: 4 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_INTERACTIVE_DEBRIS
  - **Value**: 3 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_IN_VEHICLE
  - **Value**: 10 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_NONE
  - **Value**: 0 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_NPC
  - **Value**: 9 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_NPC_ACTOR
  - **Value**: 18 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_NPC_SCRIPTED
  - **Value**: 19 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_PASSABLE_DOOR
  - **Value**: 15 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_PLAYER
  - **Value**: 5 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_PLAYER_MOVEMENT
  - **Value**: 8 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_PROJECTILE
  - **Value**: 13 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_PUSHAWAY
  - **Value**: 17 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_VEHICLE
  - **Value**: 7 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_VEHICLE_CLIP
  - **Value**: 12 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### COLLISION_GROUP_WEAPON
  - **Value**: 11 (_integer_)
  - **Description**: Collision group used in GetCollisionGroup(), etc.

### CONTENTS_AREAPORTAL
  - **Value**: 32768 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_AUX
  - **Value**: 4 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_BLOCKLOS
  - **Value**: 64 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_0
  - **Value**: 262144 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_180
  - **Value**: 1048576 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_270
  - **Value**: 2097152 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_90
  - **Value**: 524288 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_DOWN
  - **Value**: 8388608 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_CURRENT_UP
  - **Value**: 4194304 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_DEBRIS
  - **Value**: 67108864 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_DETAIL
  - **Value**: 134217728 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_EMPTY
  - **Value**: 0 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_GRATE
  - **Value**: 8 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_HITBOX
  - **Value**: 1073741824 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_IGNORE_NODRAW_OPAQUE
  - **Value**: 8192 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_LADDER
  - **Value**: 536870912 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_MONSTER
  - **Value**: 33554432 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_MONSTERCLIP
  - **Value**: 131072 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_MOVEABLE
  - **Value**: 16384 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_OPAQUE
  - **Value**: 128 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_ORIGIN
  - **Value**: 16777216 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_PLAYERCLIP
  - **Value**: 65536 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_SLIME
  - **Value**: 16 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_SOLID
  - **Value**: 1 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_TEAM1
  - **Value**: 2048 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_TEAM2
  - **Value**: 4096 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_TESTFOGVOLUME
  - **Value**: 256 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_TRANSLUCENT
  - **Value**: 268435456 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_WATER
  - **Value**: 32 (_integer_)
  - **Description**: Spatial content flags.

### CONTENTS_WINDOW
  - **Value**: 2 (_integer_)
  - **Description**: Spatial content flags.

### DAMAGE_AIM
  - **Value**: 3 (_integer_)
  - **Description**: (Use with GetTakeDamage/SetTakeDamage)

### DAMAGE_EVENTS_ONLY
  - **Value**: 1 (_integer_)
  - **Description**: Call damage functions, but don't modify health (Use with GetTakeDamage/SetTakeDamage)

### DAMAGE_NO
  - **Value**: 0 (_integer_)
  - **Description**: Don't take damage (Use with GetTakeDamage/SetTakeDamage)

### DAMAGE_YES
  - **Value**: 2 (_integer_)
  - **Description**: Allow damage to be taken (Use with GetTakeDamage/SetTakeDamage)

### DEG2RAD
  - **Value**: 0.017453 (_float_)

### DMG_ACID
  - **Value**: 1048576 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_AIRBOAT
  - **Value**: 33554432 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_ALWAYSGIB
  - **Value**: 8192 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_BLAST
  - **Value**: 64 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_BLAST_SURFACE
  - **Value**: 134217728 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_BUCKSHOT
  - **Value**: 536870912 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_BULLET
  - **Value**: 2 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_BURN
  - **Value**: 8 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_CLUB
  - **Value**: 128 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_CRUSH
  - **Value**: 1 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_DIRECT
  - **Value**: 268435456 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_DISSOLVE
  - **Value**: 67108864 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_DROWN
  - **Value**: 16384 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_DROWNRECOVER
  - **Value**: 524288 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_ENERGYBEAM
  - **Value**: 1024 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_FALL
  - **Value**: 32 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_GENERIC
  - **Value**: 0 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_NERVEGAS
  - **Value**: 65536 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_NEVERGIB
  - **Value**: 4096 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_PARALYZE
  - **Value**: 32768 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_PHYSGUN
  - **Value**: 8388608 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_PLASMA
  - **Value**: 16777216 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_POISON
  - **Value**: 131072 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_PREVENT_PHYSICS_FORCE
  - **Value**: 2048 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_RADIATION
  - **Value**: 262144 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_REMOVENORAGDOLL
  - **Value**: 4194304 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_SHOCK
  - **Value**: 256 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_SLASH
  - **Value**: 4 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_SLOWBURN
  - **Value**: 2097152 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_SONIC
  - **Value**: 512 (_integer_)
  - **Description**: Damage type used in damage information.

### DMG_VEHICLE
  - **Value**: 16 (_integer_)
  - **Description**: Damage type used in damage information.

### D_ER
  - **Value**: 0 (_integer_)
  - **Description**: 'Error' relationship definition. Used by NPCs and players for relationship disposition.

### D_FR
  - **Value**: 2 (_integer_)
  - **Description**: Denotes a 'Fear' relationship. Used by NPCs and players for relationship disposition.

### D_HT
  - **Value**: 1 (_integer_)
  - **Description**: Denotes a 'Hate' relationship. Used by NPCs and players for relationship disposition.

### D_LI
  - **Value**: 3 (_integer_)
  - **Description**: Denotes a 'Like' relationship. Used by NPCs and players for relationship disposition.

### D_NU
  - **Value**: 4 (_integer_)
  - **Description**: Denotes a 'Neutral' relationship. Used by NPCs and players for relationship disposition.

### EFL_BOT_FROZEN
  - **Value**: 256 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_CHECK_UNTOUCH
  - **Value**: 16777216 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_ABSANGVELOCITY
  - **Value**: 8192 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_ABSTRANSFORM
  - **Value**: 2048 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_ABSVELOCITY
  - **Value**: 4096 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_SHADOWUPDATE
  - **Value**: 32 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_SPATIAL_PARTITION
  - **Value**: 32768 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DIRTY_SURROUNDING_COLLISION_BOUNDS
  - **Value**: 16384 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DONTBLOCKLOS
  - **Value**: 33554432 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DONTWALKON
  - **Value**: 67108864 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_DORMANT
  - **Value**: 2 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_FORCE_ALLOW_MOVEPARENT
  - **Value**: 65536 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_FORCE_CHECK_TRANSMIT
  - **Value**: 128 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_HAS_PLAYER_CHILD
  - **Value**: 16 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_IN_SKYBOX
  - **Value**: 131072 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_IS_BEING_LIFTED_BY_BARNACLE
  - **Value**: 1048576 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_KEEP_ON_RECREATE_ENTITIES
  - **Value**: 16 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_KILLME
  - **Value**: 1 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NOCLIP_ACTIVE
  - **Value**: 4 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NOTIFY
  - **Value**: 64 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_AUTO_EDICT_ATTACH
  - **Value**: 1024 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_DAMAGE_FORCES
  - **Value**: -2147483648 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_DISSOLVE
  - **Value**: 134217728 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_GAME_PHYSICS_SIMULATION
  - **Value**: 8388608 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_MEGAPHYSCANNON_RAGDOLL
  - **Value**: 268435456 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_PHYSCANNON_INTERACTION
  - **Value**: 1073741824 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_ROTORWASH_PUSH
  - **Value**: 2097152 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_THINK_FUNCTION
  - **Value**: 4194304 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_NO_WATER_VELOCITY_CHANGE
  - **Value**: 536870912 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_SERVER_ONLY
  - **Value**: 512 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_SETTING_UP_BONES
  - **Value**: 8 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_TOUCHING_FLUID
  - **Value**: 524288 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EFL_USE_PARTITION_WHEN_NOT_SOLID
  - **Value**: 262144 (_integer_)
  - **Description**: Entity flag used in GetEFlags(), etc.

### EF_BONEMERGE
  - **Value**: 1 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_BONEMERGE_FASTCULL
  - **Value**: 128 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_BRIGHTLIGHT
  - **Value**: 2 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_DIMLIGHT
  - **Value**: 4 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_ITEM_BLINK
  - **Value**: 256 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_NODRAW
  - **Value**: 32 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_NOINTERP
  - **Value**: 8 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_NORECEIVESHADOW
  - **Value**: 64 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_NOSHADOW
  - **Value**: 16 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### EF_PARENT_ANIMATES
  - **Value**: 512 (_integer_)
  - **Description**: Effect flag used in GetEffects(), etc.

### FCVAR_ACCESSIBLE_FROM_THREADS
  - **Value**: 33554432 (_integer_)
  - **Description**: If this convar flag is set, it will be accessible from the material system thread.

### FCVAR_ARCHIVE
  - **Value**: 128 (_integer_)
  - **Description**: If this convar flag is set, its value will be saved when the game is exited.

### FCVAR_ARCHIVE_XBOX
  - **Value**: 16777216 (_integer_)
  - **Description**: If this convar flag is set, it will be archived on the Xbox config.

### FCVAR_CHEAT
  - **Value**: 16384 (_integer_)
  - **Description**: Only useable in singleplayer / debug / multiplayer & sv_cheats

### FCVAR_CLIENTCMD_CAN_EXECUTE
  - **Value**: 1073741824 (_integer_)
  - **Description**: If this convar flag is set, any client will be allowed to execute this command.

### FCVAR_CLIENTDLL
  - **Value**: 8 (_integer_)
  - **Description**: This convar flag is defined in client DLL convars.

### FCVAR_DEMO
  - **Value**: 65536 (_integer_)
  - **Description**: If this convar flag is set, it will be recorded when starting a demo file.

### FCVAR_DEVELOPMENTONLY
  - **Value**: 2 (_integer_)
  - **Description**: If this convar flag is set, it's hidden in "retail" DLLs.

### FCVAR_DONTRECORD
  - **Value**: 131072 (_integer_)
  - **Description**: If this convar flag is set, it will NOT be recorded when starting a demo file.

### FCVAR_GAMEDLL
  - **Value**: 4 (_integer_)
  - **Description**: This convar flag is defined in server DLL convars.

### FCVAR_HIDDEN
  - **Value**: 16 (_integer_)
  - **Description**: If this convar flag is set, it doesn't appear in the console or any searching tools, but it can still be set.

### FCVAR_MATERIAL_SYSTEM_THREAD
  - **Value**: 8388608 (_integer_)
  - **Description**: This convar flag indicates it's read from the material system thread.

### FCVAR_NEVER_AS_STRING
  - **Value**: 4096 (_integer_)
  - **Description**: If this convar flag is set, it will never be printed as a string.

### FCVAR_NONE
  - **Value**: 0 (_integer_)
  - **Description**: Empty convar flag.

### FCVAR_NOTIFY
  - **Value**: 256 (_integer_)
  - **Description**: If this convar flag is set, it will notify players when it is changed.

### FCVAR_NOT_CONNECTED
  - **Value**: 4194304 (_integer_)
  - **Description**: If this convar flag is set, it cannot be changed by a client connected to the server.

### FCVAR_PRINTABLEONLY
  - **Value**: 1024 (_integer_)
  - **Description**: If this convar flag is set, it cannot contain unprintable characters. Used for player name cvars, etc.

### FCVAR_PROTECTED
  - **Value**: 32 (_integer_)
  - **Description**: This convar flag prevents convars with secure data (e.g. passwords) from sending full data to clients, only sending 1 if non-zero and 0 otherwise.

### FCVAR_RELOAD_MATERIALS
  - **Value**: 1048576 (_integer_)
  - **Description**: If this convar flag is set, it will force a material reload when it changes.

### FCVAR_RELOAD_TEXTURES
  - **Value**: 2097152 (_integer_)
  - **Description**: If this convar flag is set, it will force a texture reload when it changes.

### FCVAR_REPLICATED
  - **Value**: 8192 (_integer_)
  - **Description**: If this convar flag is set, it will enforce a serverside value on any clientside counterparts. (also known as FCVAR_SERVER)

### FCVAR_SERVER_CANNOT_QUERY
  - **Value**: 536870912 (_integer_)
  - **Description**: If this convar flag is set, the server will not be allowed to query its value.

### FCVAR_SERVER_CAN_EXECUTE
  - **Value**: 268435456 (_integer_)
  - **Description**: If this convar flag is set, the server will be allowed to execute it as a client command.

### FCVAR_SPONLY
  - **Value**: 64 (_integer_)
  - **Description**: If this convar flag is set, it can't be changed by clients connected to a multiplayer server.

### FCVAR_UNLOGGED
  - **Value**: 2048 (_integer_)
  - **Description**: If this convar flag is set, it will not log its changes if a log is being created.

### FCVAR_UNREGISTERED
  - **Value**: 1 (_integer_)
  - **Description**: If this convar flag is set, it isn't added to linked list, etc.

### FCVAR_USERINFO
  - **Value**: 512 (_integer_)
  - **Description**: If this convar flag is set, it will be marked as info which plays a part in how the server identifies a client.

### FL_AIMTARGET
  - **Value**: 131072 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_ATCONTROLS
  - **Value**: 128 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_BASEVELOCITY
  - **Value**: 16777216 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_CLIENT
  - **Value**: 256 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_CONVEYOR
  - **Value**: 8192 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_DISSOLVING
  - **Value**: 536870912 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_DONTTOUCH
  - **Value**: 8388608 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_DUCKING
  - **Value**: 2 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_FAKECLIENT
  - **Value**: 512 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_FLY
  - **Value**: 2048 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_FROZEN
  - **Value**: 64 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_GODMODE
  - **Value**: 32768 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_GRAPHED
  - **Value**: 1048576 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_GRENADE
  - **Value**: 2097152 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_INRAIN
  - **Value**: 32 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_INWATER
  - **Value**: 1024 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_KILLME
  - **Value**: 134217728 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_NOTARGET
  - **Value**: 65536 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_NPC
  - **Value**: 16384 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_OBJECT
  - **Value**: 67108864 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_ONFIRE
  - **Value**: 268435456 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_ONGROUND
  - **Value**: 1 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_ONTRAIN
  - **Value**: 16 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_PARTIALGROUND
  - **Value**: 262144 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_STATICPROP
  - **Value**: 524288 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_STEPMOVEMENT
  - **Value**: 4194304 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_SWIM
  - **Value**: 4096 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_TRANSRAGDOLL
  - **Value**: 1073741824 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_UNBLOCKABLE_BY_PLAYER
  - **Value**: -2147483648 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_WATERJUMP
  - **Value**: 8 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FL_WORLDBRUSH
  - **Value**: 33554432 (_integer_)
  - **Description**: Flag used in GetFlags(), etc.

### FSOLID_COLLIDE_WITH_OWNER
  - **Value**: 1024 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_CUSTOMBOXTEST
  - **Value**: 2 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_CUSTOMRAYTEST
  - **Value**: 1 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_FORCE_WORLD_ALIGNED
  - **Value**: 64 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_NOT_SOLID
  - **Value**: 4 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_NOT_STANDABLE
  - **Value**: 16 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_ROOT_PARENT_ALIGNED
  - **Value**: 256 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_TRIGGER
  - **Value**: 8 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_TRIGGER_TOUCH_DEBRIS
  - **Value**: 512 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_USE_TRIGGER_BOUNDS
  - **Value**: 128 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### FSOLID_VOLUME_CONTENTS
  - **Value**: 32 (_integer_)
  - **Description**: Solid flag used in GetSolidFlags(), etc.

### GENDER_FEMALE
  - **Value**: 2 (_integer_)
  - **Description**: A standard value used to represent female gender. Usually used for sounds.

### GENDER_MALE
  - **Value**: 1 (_integer_)
  - **Description**: A standard value used to represent male gender. Usually used for sounds.

### GENDER_NONE
  - **Value**: 0 (_integer_)
  - **Description**: A standard value used to represent no specific gender. Usually used for sounds.

### GLOBAL_DEAD
  - **Value**: 2 (_integer_)
  - **Description**: Global state used by the Globals singleton.

### GLOBAL_OFF
  - **Value**: 0 (_integer_)
  - **Description**: Global state used by the Globals singleton.

### GLOBAL_ON
  - **Value**: 1 (_integer_)
  - **Description**: Global state used by the Globals singleton.

### Hitgroup.Chest
  - **Value**: 2 (_integer_)

### Hitgroup.Gear
  - **Value**: 10 (_integer_)

### Hitgroup.Generic
  - **Value**: 0 (_integer_)

### Hitgroup.Head
  - **Value**: 1 (_integer_)

### Hitgroup.LeftArm
  - **Value**: 4 (_integer_)

### Hitgroup.LeftLeg
  - **Value**: 6 (_integer_)

### Hitgroup.RightArm
  - **Value**: 5 (_integer_)

### Hitgroup.RightLeg
  - **Value**: 7 (_integer_)

### Hitgroup.Stomach
  - **Value**: 3 (_integer_)

### IN.ALT1
  - **Value**: 16384 (_integer_)
  - **Description**: Button for +alt1

### IN.ALT2
  - **Value**: 32768 (_integer_)
  - **Description**: Button for +alt2

### IN.ATTACK
  - **Value**: 1 (_integer_)
  - **Description**: Button for +attack

### IN.ATTACK2
  - **Value**: 2048 (_integer_)
  - **Description**: Button for +attack2

### IN.ATTACK3
  - **Value**: 33554432 (_integer_)
  - **Description**: Button for +attack3

### IN.BACK
  - **Value**: 16 (_integer_)
  - **Description**: Button for +back

### IN.BULLRUSH
  - **Value**: 4194304 (_integer_)
  - **Description**: Unused button

### IN.CANCEL
  - **Value**: 64 (_integer_)
  - **Description**: Special button flag for attack cancel

### IN.DUCK
  - **Value**: 4 (_integer_)
  - **Description**: Button for +duck

### IN.FORWARD
  - **Value**: 8 (_integer_)
  - **Description**: Button for +forward

### IN.GRENADE1
  - **Value**: 8388608 (_integer_)
  - **Description**: Button for +grenade1

### IN.GRENADE2
  - **Value**: 16777216 (_integer_)
  - **Description**: Button for +grenade2

### IN.JUMP
  - **Value**: 2 (_integer_)
  - **Description**: Button for +jump

### IN.LEFT
  - **Value**: 128 (_integer_)
  - **Description**: Button for +left

### IN.MOVELEFT
  - **Value**: 512 (_integer_)
  - **Description**: Button for +moveleft

### IN.MOVERIGHT
  - **Value**: 1024 (_integer_)
  - **Description**: Button for +moveright

### IN.RELOAD
  - **Value**: 8192 (_integer_)
  - **Description**: Button for +reload

### IN.RIGHT
  - **Value**: 256 (_integer_)
  - **Description**: Button for +right

### IN.RUN
  - **Value**: 4096 (_integer_)
  - **Description**: Unused button (see IN.SPEED for sprint)

### IN.SCORE
  - **Value**: 65536 (_integer_)
  - **Description**: Button for +score

### IN.SPEED
  - **Value**: 131072 (_integer_)
  - **Description**: Button for +speed

### IN.USE
  - **Value**: 32 (_integer_)
  - **Description**: Button for +use

### IN.WALK
  - **Value**: 262144 (_integer_)
  - **Description**: Button for +walk

### IN.WEAPON1
  - **Value**: 1048576 (_integer_)
  - **Description**: Special button used by weapons themselves

### IN.WEAPON2
  - **Value**: 2097152 (_integer_)
  - **Description**: Special button used by weapons themselves

### IN.ZOOM
  - **Value**: 524288 (_integer_)
  - **Description**: Button for +zoom

### LAST_VISIBLE_CONTENTS
  - **Value**: 128 (_integer_)
  - **Description**: Contains last visible spatial content flags.

### MAPBASE_VERSION
  - **Value**: "8.0" (_cstring_)
  - **Description**: The current Mapbase version according to when the VScript library was last compiled.

### MAPBASE_VER_INT
  - **Value**: 8000 (_integer_)
  - **Description**: The current Mapbase version integer according to when the VScript library was last compiled.

### MASK_BLOCKLOS
  - **Value**: 16449 (_integer_)
  - **Description**: Spatial content mask representing objects which block LOS for AI (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_BLOCKLOS)

### MASK_BLOCKLOS_AND_NPCS
  - **Value**: 33570881 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_BLOCKLOS, but also including NPCs (MASK_BLOCKLOS|CONTENTS_MONSTER)

### MASK_NPCSOLID
  - **Value**: 33701899 (_integer_)
  - **Description**: Spatial content mask representing objects solid to NPCs, including NPC clips (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_MONSTERCLIP|CONTENTS_WINDOW|CONTENTS_MONSTER|CONTENTS_GRATE)

### MASK_NPCSOLID_BRUSHONLY
  - **Value**: 147467 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_NPCSOLID, but without NPCs (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_WINDOW|CONTENTS_MONSTERCLIP|CONTENTS_GRATE)

### MASK_NPCWORLDSTATIC
  - **Value**: 131083 (_integer_)
  - **Description**: Spatial content mask representing objects static to NPCs, used for nodegraph rebuilding (CONTENTS_SOLID|CONTENTS_WINDOW|CONTENTS_MONSTERCLIP|CONTENTS_GRATE)

### MASK_OPAQUE
  - **Value**: 16513 (_integer_)
  - **Description**: Spatial content mask representing objects which block lighting (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_OPAQUE)

### MASK_OPAQUE_AND_NPCS
  - **Value**: 33570945 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_OPAQUE, but also including NPCs (MASK_OPAQUE|CONTENTS_MONSTER)

### MASK_PLAYERSOLID
  - **Value**: 33636363 (_integer_)
  - **Description**: Spatial content mask representing objects solid to the player, including player clips (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_PLAYERCLIP|CONTENTS_WINDOW|CONTENTS_MONSTER|CONTENTS_GRATE)

### MASK_PLAYERSOLID_BRUSHONLY
  - **Value**: 81931 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_PLAYERSOLID, but without NPCs (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_WINDOW|CONTENTS_PLAYERCLIP|CONTENTS_GRATE)

### MASK_SHOT
  - **Value**: 1174421507 (_integer_)
  - **Description**: Spatial content mask representing objects solid to bullets (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_MONSTER|CONTENTS_WINDOW|CONTENTS_DEBRIS|CONTENTS_HITBOX)

### MASK_SHOT_HULL
  - **Value**: 100679691 (_integer_)
  - **Description**: Spatial content mask representing objects solid to non-raycasted weapons, including grates (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_MONSTER|CONTENTS_WINDOW|CONTENTS_DEBRIS|CONTENTS_GRATE)

### MASK_SHOT_PORTAL
  - **Value**: 33570819 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_SHOT, but excluding debris and not using expensive hitbox calculations (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_WINDOW|CONTENTS_MONSTER)

### MASK_SOLID
  - **Value**: 33570827 (_integer_)
  - **Description**: Spatial content mask representing solid objects (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_WINDOW|CONTENTS_MONSTER|CONTENTS_GRATE)

### MASK_SOLID_BRUSHONLY
  - **Value**: 16395 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_SOLID, but without NPCs (CONTENTS_SOLID|CONTENTS_MOVEABLE|CONTENTS_WINDOW|CONTENTS_GRATE)

### MASK_SPLITAREAPORTAL
  - **Value**: 48 (_integer_)
  - **Description**: Spatial content mask representing objects which can split areaportals (CONTENTS_WATER|CONTENTS_SLIME)

### MASK_VISIBLE
  - **Value**: 24705 (_integer_)
  - **Description**: Spatial content mask representing objects which block LOS for players (MASK_OPAQUE|CONTENTS_IGNORE_NODRAW_OPAQUE)

### MASK_VISIBLE_AND_NPCS
  - **Value**: 33579137 (_integer_)
  - **Description**: Spatial content mask equivalent to MASK_VISIBLE, but also including NPCs (MASK_OPAQUE_AND_NPCS|CONTENTS_IGNORE_NODRAW_OPAQUE)

### MASK_WATER
  - **Value**: 16432 (_integer_)
  - **Description**: Spatial content mask representing water and slime solids (CONTENTS_WATER|CONTENTS_MOVEABLE|CONTENTS_SLIME)

### MAX_COORD_FLOAT
  - **Value**: 16384.000000 (_float_)
  - **Description**: Maximum float coordinate.

### MAX_TRACE_LENGTH
  - **Value**: 56755.840862 (_float64_)
  - **Description**: Maximum traceable distance (assumes cubic world and trace from one corner to opposite).

### MOVETYPE_CUSTOM
  - **Value**: 11 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_FLY
  - **Value**: 4 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_FLYGRAVITY
  - **Value**: 5 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_ISOMETRIC
  - **Value**: 1 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_LADDER
  - **Value**: 9 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_NOCLIP
  - **Value**: 8 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_NONE
  - **Value**: 0 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_OBSERVER
  - **Value**: 10 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_PUSH
  - **Value**: 7 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_STEP
  - **Value**: 3 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_VPHYSICS
  - **Value**: 6 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MOVETYPE_WALK
  - **Value**: 2 (_integer_)
  - **Description**: Move type used in GetMoveType(), etc.

### MapLoad.Background
  - **Value**: 3 (_integer_)
  - **Description**: Map was loaded as a background map

### MapLoad.LoadGame
  - **Value**: 1 (_integer_)
  - **Description**: Map was loaded from a save file

### MapLoad.NewGame
  - **Value**: 0 (_integer_)
  - **Description**: Map was loaded from a new game

### MapLoad.Transition
  - **Value**: 2 (_integer_)
  - **Description**: Map was loaded from a level transition

### NPC_STATE_ALERT
  - **Value**: 2 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_COMBAT
  - **Value**: 3 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_DEAD
  - **Value**: 7 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_IDLE
  - **Value**: 1 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_INVALID
  - **Value**: -1 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_NONE
  - **Value**: 0 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_PLAYDEAD
  - **Value**: 5 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NPC_STATE_PRONE
  - **Value**: 6 (_integer_)
  - **Description**: When in clutches of barnacle (NPC state type used in GetNPCState(), etc.)

### NPC_STATE_SCRIPT
  - **Value**: 4 (_integer_)
  - **Description**: NPC state type used in GetNPCState(), etc.

### NUM_AI_CLASSES
  - **Value**: 3 (_integer_)
  - **Description**: Number of AI classes.

### PITCH_HIGH
  - **Value**: 120 (_integer_)
  - **Description**: The standard high pitch value.

### PITCH_LOW
  - **Value**: 95 (_integer_)
  - **Description**: The standard low pitch value.

### PITCH_NORM
  - **Value**: 100 (_integer_)
  - **Description**: The standard pitch value.

### RAD2DEG
  - **Value**: 57.295780 (_float_)

### ROPE_BARBED
  - **Value**: 2 (_integer_)
  - **Description**: Hack option to draw like a barbed wire. (for use in rope flags)

### ROPE_BREAKABLE
  - **Value**: 16 (_integer_)
  - **Description**: Can the endpoints detach? (for use in rope flags)

### ROPE_COLLIDE
  - **Value**: 4 (_integer_)
  - **Description**: Collide with the world. (for use in rope flags)

### ROPE_GRAVITY
  - **Value**: Vector( 0.000000, 0.000000, -1500.000000 ) (_vector_)
  - **Description**: Default rope gravity vector.

### ROPE_INITIAL_HANG
  - **Value**: 64 (_integer_)
  - **Description**: By default, ropes will simulate for a bit internally when they are created so they sag, but dynamically created ropes for things like harpoons don't want this. (for use in rope flags)

### ROPE_NO_GRAVITY
  - **Value**: 256 (_integer_)
  - **Description**: Disable gravity on this rope. (for use in rope flags)

### ROPE_NUMFLAGS
  - **Value**: 9 (_integer_)
  - **Description**: The number of rope flags recognized by the game.

### ROPE_PLAYER_WPN_ATTACH
  - **Value**: 128 (_integer_)
  - **Description**: If this flag is set, then the second attachment must be a player. The rope will attach to "buff_attach" on the player's active weapon. This is a flag because it requires special code on the client to find the weapon. (for use in rope flags)

### ROPE_RESIZE
  - **Value**: 1 (_integer_)
  - **Description**: Try to keep the rope dangling the same amount even as the rope length changes. (for use in rope flags)

### ROPE_SIMULATE
  - **Value**: 8 (_integer_)
  - **Description**: Is the rope valid? (for use in rope flags)

### ROPE_USE_WIND
  - **Value**: 32 (_integer_)
  - **Description**: Wind simulation on this rope. (for use in rope flags)

### RenderMode.Additive
  - **Value**: 5 (_integer_)

### RenderMode.AdditiveFractionalFrame
  - **Value**: 7 (_integer_)

### RenderMode.AlphaAdd
  - **Value**: 8 (_integer_)

### RenderMode.Color
  - **Value**: 1 (_integer_)

### RenderMode.Environmental
  - **Value**: 6 (_integer_)

### RenderMode.Glow
  - **Value**: 3 (_integer_)

### RenderMode.None
  - **Value**: 10 (_integer_)

### RenderMode.Normal
  - **Value**: 0 (_integer_)

### RenderMode.Solid
  - **Value**: 4 (_integer_)

### RenderMode.Texture
  - **Value**: 2 (_integer_)

### RenderMode.WorldSpaceGlow
  - **Value**: 9 (_integer_)

### SCRIPT_CLEANUP
  - **Value**: 3 (_integer_)
  - **Description**: Cancelling the script / cleaning up.

### SCRIPT_PLAYING
  - **Value**: 0 (_integer_)
  - **Description**: Moving to the scripted sequence position while playing a custom movement animation.

### SCRIPT_POST_IDLE
  - **Value**: 2 (_integer_)
  - **Description**: Playing the post idle animation after playing the action animation.

### SCRIPT_RUN_TO_MARK
  - **Value**: 5 (_integer_)
  - **Description**: Running to the scripted sequence position.

### SCRIPT_WAIT
  - **Value**: 1 (_integer_)
  - **Description**: Waiting on everyone in the script to be ready. Plays the pre idle animation if there is one.

### SCRIPT_WALK_TO_MARK
  - **Value**: 4 (_integer_)
  - **Description**: Walking to the scripted sequence position.

### SEEN_ALL
  - **Value**: -1 (_integer_)
  - **Description**: All NPC sight arrays. Used in GetFirstSeenEntity, etc.

### SEEN_HIGH_PRIORITY
  - **Value**: 0 (_integer_)
  - **Description**: NPC sight array for players. Used in GetFirstSeenEntity, etc.

### SEEN_MISC
  - **Value**: 2 (_integer_)
  - **Description**: NPC sight array for objects. Used in GetFirstSeenEntity, etc.

### SEEN_NPCS
  - **Value**: 1 (_integer_)
  - **Description**: NPC sight array for other NPCs. Used in GetFirstSeenEntity, etc.

### SERVER_DLL
  - **Value**: 1 (_integer_)

### SNDLVL_100dB
  - **Value**: 100 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_105dB
  - **Value**: 105 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_110dB
  - **Value**: 110 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_120dB
  - **Value**: 120 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_130dB
  - **Value**: 130 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_140dB
  - **Value**: 140 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_150dB
  - **Value**: 150 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_180dB
  - **Value**: 180 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_20dB
  - **Value**: 20 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_25dB
  - **Value**: 25 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_30dB
  - **Value**: 30 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_35dB
  - **Value**: 35 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_40dB
  - **Value**: 40 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_45dB
  - **Value**: 45 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_50dB
  - **Value**: 50 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_55dB
  - **Value**: 55 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_60dB
  - **Value**: 60 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_65dB
  - **Value**: 65 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_70dB
  - **Value**: 70 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_75dB
  - **Value**: 75 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_80dB
  - **Value**: 80 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_85dB
  - **Value**: 85 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_90dB
  - **Value**: 90 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_95dB
  - **Value**: 95 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_GUNFIRE
  - **Value**: 140 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_IDLE
  - **Value**: 60 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_NONE
  - **Value**: 0 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_NORM
  - **Value**: 75 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_STATIC
  - **Value**: 66 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SNDLVL_TALKING
  - **Value**: 80 (_integer_)
  - **Description**: A standard value used for a sound's sound level.

### SND_CHANGE_PITCH
  - **Value**: 2 (_integer_)
  - **Description**: Indicates a sound is a pitch change to an already-playing sound.

### SND_CHANGE_VOL
  - **Value**: 1 (_integer_)
  - **Description**: Indicates a sound is a volume change to an already-playing sound.

### SND_DELAY
  - **Value**: 16 (_integer_)
  - **Description**: Indicates a sound has an initial delay.

### SND_DO_NOT_OVERWRITE_EXISTING_ON_CHANNEL
  - **Value**: 1024 (_integer_)
  - **Description**: Prevents a sound from interrupting other sounds on a channel (if the channel supports interruption).

### SND_IGNORE_NAME
  - **Value**: 512 (_integer_)
  - **Description**: Used to change all sounds emitted by an entity, regardless of name.

### SND_IGNORE_PHONEMES
  - **Value**: 256 (_integer_)
  - **Description**: Prevents the entity emitting this sound from using its phonemes (no lip-syncing).

### SND_SHOULDPAUSE
  - **Value**: 128 (_integer_)
  - **Description**: Forces a sound to pause if the game is paused.

### SND_SPAWNING
  - **Value**: 8 (_integer_)
  - **Description**: Indicates a sound is spawning, used in some cases for ambients. Not networked.

### SND_SPEAKER
  - **Value**: 64 (_integer_)
  - **Description**: Indicates a sound is being played again by a microphone through a speaker.

### SND_STOP
  - **Value**: 4 (_integer_)
  - **Description**: Indicates a sound is stopping an already-playing sound.

### SND_STOP_LOOPING
  - **Value**: 32 (_integer_)
  - **Description**: Stops all looping sounds on an entity.

### SOLID_BBOX
  - **Value**: 2 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_BSP
  - **Value**: 1 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_CUSTOM
  - **Value**: 5 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_NONE
  - **Value**: 0 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_OBB
  - **Value**: 3 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_OBB_YAW
  - **Value**: 4 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOLID_VPHYSICS
  - **Value**: 6 (_integer_)
  - **Description**: Solid type used by VPhysics

### SOUNDENT_CHANNEL_BULLET_IMPACT
  - **Value**: 6 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_INJURY
  - **Value**: 5 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_NPC_FOOTSTEP
  - **Value**: 7 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_REPEATED_DANGER
  - **Value**: 2 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_REPEATED_PHYSICS_DANGER
  - **Value**: 3 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_REPEATING
  - **Value**: 1 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_SPOOKY_NOISE
  - **Value**: 8 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_UNSPECIFIED
  - **Value**: 0 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_WEAPON
  - **Value**: 4 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_CHANNEL_ZOMBINE_GRENADE
  - **Value**: 9 (_integer_)
  - **Description**: Sound channel used in QueryHearSound hooks, etc.

### SOUNDENT_VOLUME_MACHINEGUN
  - **Value**: 1500 (_integer_)
  - **Description**: Sound volume preset for use in InsertAISound, etc.

### SOUNDENT_VOLUME_PISTOL
  - **Value**: 500 (_integer_)
  - **Description**: Sound volume preset for use in InsertAISound, etc.

### SOUNDENT_VOLUME_SHOTGUN
  - **Value**: 1500 (_integer_)
  - **Description**: Sound volume preset for use in InsertAISound, etc.

### SOUND_BUGBAIT
  - **Value**: 512 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_BULLET_IMPACT
  - **Value**: 16 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_CARCASS
  - **Value**: 32 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_COMBAT
  - **Value**: 1 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_ALLIES_ONLY
  - **Value**: 268435456 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_COMBINE_ONLY
  - **Value**: 8388608 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_DANGER_APPROACH
  - **Value**: 134217728 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_EXCLUDE_COMBINE
  - **Value**: 67108864 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_EXPLOSION
  - **Value**: 33554432 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_FROM_SNIPER
  - **Value**: 1048576 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_GUNFIRE
  - **Value**: 2097152 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_MORTAR
  - **Value**: 4194304 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_OWNER_ALLIES
  - **Value**: 1073741824 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_PLAYER_VEHICLE
  - **Value**: 536870912 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_CONTEXT_REACT_TO_SOURCE
  - **Value**: 16777216 (_integer_)
  - **Description**: Sound context used in QueryHearSound hooks, etc.

### SOUND_DANGER
  - **Value**: 8 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_DANGER_SNIPERONLY
  - **Value**: 2048 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_GARBAGE
  - **Value**: 128 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_MEAT
  - **Value**: 64 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_MOVE_AWAY
  - **Value**: 4096 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_NONE
  - **Value**: 0 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_PHYSICS_DANGER
  - **Value**: 1024 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_PLAYER
  - **Value**: 4 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_PLAYER_VEHICLE
  - **Value**: 8192 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_READINESS_HIGH
  - **Value**: 65536 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_READINESS_LOW
  - **Value**: 16384 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_READINESS_MEDIUM
  - **Value**: 32768 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_THUMPER
  - **Value**: 256 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### SOUND_WORLD
  - **Value**: 2 (_integer_)
  - **Description**: Sound type used in QueryHearSound hooks, etc.

### VECTOR_CONE_10DEGREES
  - **Value**: Vector( 0.087160, 0.087160, 0.087160 ) (_vector_)
  - **Description**: 10-degree weapon vector cone.

### VECTOR_CONE_15DEGREES
  - **Value**: Vector( 0.130530, 0.130530, 0.130530 ) (_vector_)
  - **Description**: 15-degree weapon vector cone.

### VECTOR_CONE_1DEGREES
  - **Value**: Vector( 0.008730, 0.008730, 0.008730 ) (_vector_)
  - **Description**: 1-degree weapon vector cone.

### VECTOR_CONE_20DEGREES
  - **Value**: Vector( 0.173650, 0.173650, 0.173650 ) (_vector_)
  - **Description**: 20-degree weapon vector cone.

### VECTOR_CONE_2DEGREES
  - **Value**: Vector( 0.017450, 0.017450, 0.017450 ) (_vector_)
  - **Description**: 2-degree weapon vector cone.

### VECTOR_CONE_3DEGREES
  - **Value**: Vector( 0.026180, 0.026180, 0.026180 ) (_vector_)
  - **Description**: 3-degree weapon vector cone.

### VECTOR_CONE_4DEGREES
  - **Value**: Vector( 0.034900, 0.034900, 0.034900 ) (_vector_)
  - **Description**: 4-degree weapon vector cone.

### VECTOR_CONE_5DEGREES
  - **Value**: Vector( 0.043620, 0.043620, 0.043620 ) (_vector_)
  - **Description**: 5-degree weapon vector cone.

### VECTOR_CONE_6DEGREES
  - **Value**: Vector( 0.052340, 0.052340, 0.052340 ) (_vector_)
  - **Description**: 6-degree weapon vector cone.

### VECTOR_CONE_7DEGREES
  - **Value**: Vector( 0.061050, 0.061050, 0.061050 ) (_vector_)
  - **Description**: 7-degree weapon vector cone.

### VECTOR_CONE_8DEGREES
  - **Value**: Vector( 0.069760, 0.069760, 0.069760 ) (_vector_)
  - **Description**: 8-degree weapon vector cone.

### VECTOR_CONE_9DEGREES
  - **Value**: Vector( 0.078460, 0.078460, 0.078460 ) (_vector_)
  - **Description**: 9-degree weapon vector cone.

### VECTOR_CONE_PRECALCULATED
  - **Value**: Vector( 0.000000, 0.000000, 0.000000 ) (_vector_)
  - **Description**: This is just a zero vector, but it adds some context indicating that the person writing the code is not allowing FireBullets() to modify the direction of the shot because the shot direction being passed into the function has already been modified by another piece of code and should be fired as specified.

### VOL_NORM
  - **Value**: 1.000000 (_float_)
  - **Description**: The standard volume value.

### VSCRIPT_PRIORITIZE_TF2_SYNTAX
  - **Value**: 1 (_integer_)
  - **Description**: Whether this mod prioritizes TF2 VScript syntax over Mapbase VScript syntax.

### WEAPON_PROFICIENCY_AVERAGE
  - **Value**: 1 (_integer_)
  - **Description**: Average weapon proficiency. Causes average accuracy.

### WEAPON_PROFICIENCY_GOOD
  - **Value**: 2 (_integer_)
  - **Description**: Good weapon proficiency. Causes good accuracy.

### WEAPON_PROFICIENCY_INVALID
  - **Value**: -1 (_integer_)
  - **Description**: Invalid weapon proficiency.

### WEAPON_PROFICIENCY_PERFECT
  - **Value**: 4 (_integer_)
  - **Description**: Perfect weapon proficiency. Causes perfect accuracy.

### WEAPON_PROFICIENCY_POOR
  - **Value**: 0 (_integer_)
  - **Description**: Poor weapon proficiency. Causes low accuracy.

### WEAPON_PROFICIENCY_VERY_GOOD
  - **Value**: 3 (_integer_)
  - **Description**: Very good weapon proficiency. Causes very good accuracy.

### WEPCLASS_HANDGUN
  - **Value**: 1 (_integer_)
  - **Description**: Weapon class for pistols, revolvers, etc.

### WEPCLASS_HEAVY
  - **Value**: 4 (_integer_)
  - **Description**: Weapon class for RPGs, etc.

### WEPCLASS_INVALID
  - **Value**: 0 (_integer_)
  - **Description**: Invalid weapon class.

### WEPCLASS_MELEE
  - **Value**: 5 (_integer_)
  - **Description**: Weapon class for melee weapons.

### WEPCLASS_RIFLE
  - **Value**: 2 (_integer_)
  - **Description**: Weapon class for (assault) rifles, SMGs, etc.

### WEPCLASS_SHOTGUN
  - **Value**: 3 (_integer_)
  - **Description**: Weapon class for shotguns.

### WeaponSound.BURST
  - **Value**: 5 (_integer_)

### WeaponSound.DEPLOY
  - **Value**: 15 (_integer_)

### WeaponSound.DOUBLE_NPC
  - **Value**: 4 (_integer_)

### WeaponSound.EMPTY
  - **Value**: 0 (_integer_)

### WeaponSound.MELEE_HIT
  - **Value**: 9 (_integer_)

### WeaponSound.MELEE_HIT_WORLD
  - **Value**: 10 (_integer_)

### WeaponSound.MELEE_MISS
  - **Value**: 8 (_integer_)

### WeaponSound.NUM_SHOOT_SOUND_TYPES
  - **Value**: 16 (_integer_)

### WeaponSound.RELOAD
  - **Value**: 6 (_integer_)

### WeaponSound.RELOAD_NPC
  - **Value**: 7 (_integer_)

### WeaponSound.SINGLE
  - **Value**: 1 (_integer_)

### WeaponSound.SINGLE_NPC
  - **Value**: 2 (_integer_)

### WeaponSound.SPECIAL1
  - **Value**: 11 (_integer_)

### WeaponSound.SPECIAL2
  - **Value**: 12 (_integer_)

### WeaponSound.SPECIAL3
  - **Value**: 13 (_integer_)

### WeaponSound.TAUNT
  - **Value**: 14 (_integer_)

### WeaponSound.WPN_DOUBLE
  - **Value**: 3 (_integer_)

### bits_CAP_AIM_GUN
  - **Value**: 536870912 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_ANIMATEDFACE
  - **Value**: 8388608 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_AUTO_DOORS
  - **Value**: 1024 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_DOORS_GROUP
  - **Value**: 3072 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_DUCK
  - **Value**: 134217728 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_FRIENDLY_DMG_IMMUNE
  - **Value**: 33554432 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_INNATE_MELEE_ATTACK1
  - **Value**: 524288 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_INNATE_MELEE_ATTACK2
  - **Value**: 1048576 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_INNATE_RANGE_ATTACK1
  - **Value**: 131072 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_INNATE_RANGE_ATTACK2
  - **Value**: 262144 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MELEE_ATTACK_GROUP
  - **Value**: 98304 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_CLIMB
  - **Value**: 8 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_CRAWL
  - **Value**: 32 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_FLY
  - **Value**: 4 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_GROUND
  - **Value**: 1 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_JUMP
  - **Value**: 2 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_SHOOT
  - **Value**: 64 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_MOVE_SWIM
  - **Value**: 16 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_NO_HIT_PLAYER
  - **Value**: 268435456 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_NO_HIT_SQUADMATES
  - **Value**: 1073741824 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_OPEN_DOORS
  - **Value**: 2048 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_RANGE_ATTACK_GROUP
  - **Value**: 24576 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_SIMPLE_RADIUS_DAMAGE
  - **Value**: -2147483648 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_SKIP_NAV_GROUND_CHECK
  - **Value**: 128 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_SQUAD
  - **Value**: 67108864 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_TURN_HEAD
  - **Value**: 4096 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_USE
  - **Value**: 256 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_USE_SHOT_REGULATOR
  - **Value**: 16777216 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_USE_WEAPONS
  - **Value**: 2097152 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_WEAPON_MELEE_ATTACK1
  - **Value**: 32768 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_WEAPON_MELEE_ATTACK2
  - **Value**: 65536 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_WEAPON_RANGE_ATTACK1
  - **Value**: 8192 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.

### bits_CAP_WEAPON_RANGE_ATTACK2
  - **Value**: 16384 (_integer_)
  - **Description**: NPC/player/weapon capability used in GetCapabilities(), etc.
