## Classes
```
TF2 Classified build 5011
Squirrel 3.1 stable (_versionnumber_ = 310)
API dump taken: 2026-07-22
```
### AI_EnemyInfo_t
  - **Description**: Accessor for information about an enemy.
  - **Base**: None

### CAI_BaseActor
  - **Description**: The base class for NPCs which act in complex choreo scenes.
  - **Base**: CAI_BaseNPC

### CAI_BaseNPC
  - **Description**: The base class all NPCs derive from.
  - **Base**: CBaseCombatCharacter

### CAI_Expresser
  - **Description**: Expresser class for complex speech.
  - **Base**: None

### CAI_GoalEntity
  - **Description**: The base class for goal entities used to control NPC behavior.
  - **Base**: CBaseEntity

### CAI_Hint
  - **Description**: An entity which gives contextual pointers for NPCs.
  - **Base**: CBaseEntity

### CAI_Network
  - **Description**: The global list of AI nodes.
  - **Base**: None

### CAI_SensedObjectsManager
  - **Description**: Manager which handles sensed objects.
  - **Base**: None

### CAI_Squad
  - **Description**: NPC squads used for schedule coordination, sharing information about enemies, etc.
  - **Base**: None

### CAI_SquadManager
  - **Description**: Manager for NPC squads.
  - **Base**: None

### CAmmoDef
  - **Description**: The ammo type definition manager.
  - **Base**: None

### CBaseAnimating
  - **Description**: Animating models
  - **Base**: CBaseEntity

### CBaseAnimatingOverlay
  - **Description**: Animating models which support dynamic animation layers/overlays.
  - **Base**: CBaseAnimating

### CBaseCombatCharacter
  - **Description**: The base class shared by players and NPCs.
  - **Base**: CBaseFlex

### CBaseCombatWeapon
  - **Description**: The base class for all equippable weapons.
  - **Base**: CEconEntity

### CBaseEntity
  - **Description**: Root class of all server-side entities
  - **Base**: None

### CBaseFilter
  - **Description**: All entities which could be used as filters.
  - **Base**: CBaseEntity

### CBaseFlex
  - **Description**: Animated characters who have vertex flex capability.
  - **Base**: CBaseAnimatingOverlay

### CBaseGrenade
  - **Description**: The base class for grenades.
  - **Base**: CBaseAnimating

### CBaseMultiplayerPlayer
  - **Description**: Multiplayer Player
  - **Base**: CBasePlayer

### CBasePlayer
  - **Description**: The player entity.
  - **Base**: CBaseCombatCharacter

### CBasePropDoor
  - **Description**: The base class used by prop doors, such as prop_door_rotating.
  - **Base**: CBaseAnimating

### CBaseTrigger
  - **Description**: Trigger entity
  - **Base**: CBaseEntity

### CConvars
  - **Description**: Provides an interface to convars.
  - **Base**: None

### CDebugOverlayScriptHelper
  - **Description**: CDebugOverlayScriptHelper
  - **Base**: None

### CEconEntity
  - **Description**: Econ Entity
  - **Base**: CBaseAnimating

### CEntities
  - **Description**: The global list of entities
  - **Base**: None

### CEnvEntityMaker
  - **Description**: env_entity_maker
  - **Base**: CBaseEntity

### CFilterScript
  - **Description**: The filter_script entity which allows VScript functions to hook onto filter methods.
  - **Base**: CBaseFilter

### CFourWheelVehiclePhysics
  - **Description**: Handler for four-wheel vehicle physics.
  - **Base**: None

### CFuncTrackTrain
  - **Description**: func_train
  - **Base**: CBaseEntity

### CGameRules
  - **Description**: The container of the game's rules, handling behavior which could be different on a game-by-game basis.
  - **Base**: None

### CGameTrace
  - **Description**: trace_t
  - **Base**: None

### CGlobalState
  - **Description**: Global state system.
  - **Base**: None

### CGlobalSys
  - **Description**: GlobalSys
  - **Base**: None

### CLocalize
  - **Description**: Accesses functions related to localization strings.
  - **Base**: None

### CLogicExternalData
  - **Description**: An entity which loads keyvalues from an external data file.
  - **Base**: CBaseEntity

### CMapbaseSystem
  - **Description**: All-purpose Mapbase system primarily used for map-specific files.
  - **Base**: None

### CNavMesh
  - **Description**: The nav mesh
  - **Base**: None

### CNetMsg
  - **Description**: Network messages
  - **Base**: None

### CNetPropManager
  - **Description**: Allows reading and updating the network properties and data fields of an entity.
  - **Base**: None

### CPlayerVoiceListener
  - **Description**: Player voice listeners
  - **Base**: None

### CPointCommentaryNode
  - **Description**: Commentary nodes which play commentary in commentary mode.
  - **Base**: CBaseAnimating

### CPointScriptTemplate
  - **Description**: point_script_template
  - **Base**: CBaseEntity

### CPropVehicle
  - **Description**: The base class for four-wheel physics vehicles.
  - **Base**: CBaseAnimating

### CPropVehicleDriveable
  - **Description**: The base class for driveable vehicles.
  - **Base**: CPropVehicle

### CRagdollProp
  - **Description**: Ragdoll physics prop.
  - **Base**: CBaseAnimating

### CSceneEntity
  - **Description**: Choreographed scene which controls animation and/or dialog on one or more actors.
  - **Base**: CBaseEntity

### CSceneListManager
  - **Description**: Stores choreo scenes and cleans them up when a later scene in the list begins playing.
  - **Base**: CBaseEntity

### CScriptEntityOutputs
  - **Description**: Used to access entity output data
  - **Base**: None

### CScriptKeyValues
  - **Description**: Wrapper class over KeyValues instance
  - **Base**: None

### CSound
  - **Description**: A sound NPCs can hear.
  - **Base**: None

### CTFBaseBoss
  - **Description**: Team Fortress 2 Base Boss
  - **Base**: NextBotCombatCharacter

### CTFBot
  - **Description**: Beep boop beep boop :3
  - **Base**: CTFPlayer

### CTFLunchBox
  - **Description**: Edible weapons
  - **Base**: CTFWeaponBase

### CTFNavArea
  - **Description**: Navigation areas class
  - **Base**: None

### CTFPlayer
  - **Description**: Team Fortress 2 Player
  - **Base**: CBaseMultiplayerPlayer

### CTFWeaponBase
  - **Description**: Team Fortress 2 Weapon
  - **Base**: CBaseCombatWeapon

### CTakeDamageInfo
  - **Description**: Damage information handler.
  - **Base**: None

### CTriggerCamera
  - **Description**: Server-side camera entity
  - **Base**: CBaseEntity

### CUserCmd
  - **Base**: None

### CWeaponCustomScripted
  - **Description**: Special weapon class with tons of hooks
  - **Base**: CBaseCombatWeapon

### Color
  - **Base**: None

### EmitSound_t
  - **Base**: None

### FireBulletsInfo_t
  - **Base**: None

### ILocomotion
  - **Description**: Next bot locomotion
  - **Base**: INextBotComponent

### INextBotComponent
  - **Description**: Next bot component
  - **Base**: None

### IPhysicsObject
  - **Description**: VPhysics object class.
  - **Base**: None

### NextBotCombatCharacter
  - **Description**: Nextbot combat character
  - **Base**: CBaseCombatCharacter

### Quaternion
  - **Description**: A quaternion.
  - **Base**: None

### Vector
  - **Description**: Basic 3-float Vector class.
  - **Base**: None

### cplane_t
  - **Base**: None

### csurface_t
  - **Base**: None

### matrix3x4_t
  - **Description**: A 3x4 matrix transform.
  - **Base**: None

### scriptanimevent_t
  - **Base**: None

### surfacedata_t
  - **Base**: None
