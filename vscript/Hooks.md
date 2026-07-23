## Hooks
```
TF2 Classified build 5011
Squirrel 3.1 stable (_versionnumber_ = 310)
API dump taken: 2026-07-22
```
### CAI_BaseNPC -> BuildScheduleTestBits
  - **Description**: Called when the NPC is determining which conditions can interrupt the current schedule.
  - **Signature**: void CAI_BaseNPC -> BuildScheduleTestBits()

### CAI_BaseNPC -> CanBeAnEnemyOf
  - **Description**: Whether or not this NPC can be an enemy of another NPC.
  - **Signature**: boolean CAI_BaseNPC -> CanBeAnEnemyOf(hscript \[enemy])

### CAI_BaseNPC -> GetActualShootPosition
  - **Description**: Called when the NPC is getting their actual shoot position, using the default shoot position as the parameter. (NOTE: NPCs which override this themselves might not always use this hook!)
  - **Signature**: vector CAI_BaseNPC -> GetActualShootPosition(vector \[shootOrigin], hscript \[target])

### CAI_BaseNPC -> IsValidEnemy
  - **Description**: Whether or not the specified enemy should be considered valid.
  - **Signature**: boolean CAI_BaseNPC -> IsValidEnemy(hscript \[enemy])

### CAI_BaseNPC -> NPC_TranslateActivity
  - **Description**: Called when the NPC is translating their current activity. The activity is provided in both string and ID form. Should return either an activity string or an activity ID. Return -1 to not translate.
  - **Signature**: variant CAI_BaseNPC -> NPC_TranslateActivity(cstring \[activity], integer \[activity_id])

### CAI_BaseNPC -> NPC_TranslateSchedule
  - **Description**: Called when the NPC is translating their current schedule. The schedule is provided in both string and ID form. Should return either a schedule string or a schedule ID. Return -1 to not translate.
  - **Signature**: variant CAI_BaseNPC -> NPC_TranslateSchedule(cstring \[schedule], integer \[schedule_id])

### CAI_BaseNPC -> OnListened
  - **Description**: Called when the NPC assigns sound conditions after checking for sounds it hears.
  - **Signature**: void CAI_BaseNPC -> OnListened()

### CAI_BaseNPC -> OnSeeEntity
  - **Description**: Called when the NPC sees an entity.
  - **Signature**: void CAI_BaseNPC -> OnSeeEntity(hscript \[entity])

### CAI_BaseNPC -> OverrideMove
  - **Description**: Called when the NPC runs movement code, allowing the NPC's movement to be overridden by some other method. (NOTE: NPCs which override this themselves might not always use this hook!)
  - **Signature**: void CAI_BaseNPC -> OverrideMove(float \[interval])

### CAI_BaseNPC -> QueryHearSound
  - **Description**: Called when the NPC is deciding whether to hear a CSound or not.
  - **Signature**: boolean CAI_BaseNPC -> QueryHearSound(hscript \[sound])

### CAI_BaseNPC -> QuerySeeEntity
  - **Description**: Called when the NPC is deciding whether to see an entity or not.
  - **Signature**: boolean CAI_BaseNPC -> QuerySeeEntity(hscript \[entity])

### CAI_BaseNPC -> RunTask
  - **Description**: Called every think while the task is running. The task is provided in both string and ID form. Return false to override actual task functionality.
  - **Signature**: void CAI_BaseNPC -> RunTask(cstring \[task], integer \[task_id], float \[task_data])

### CAI_BaseNPC -> ShouldPlayFakeSequenceGesture
  - **Description**: Called when an activity is set on a NPC. Returning true will make the NPC convert the activity into a gesture (if a gesture is available) and continue their current activity instead.
  - **Signature**: boolean CAI_BaseNPC -> ShouldPlayFakeSequenceGesture(cstring \[activity], cstring \[translatedActivity])

### CAI_BaseNPC -> StartTask
  - **Description**: Called when a task is starting. The task is provided in both string and ID form. Return false to override actual task functionality.
  - **Signature**: void CAI_BaseNPC -> StartTask(cstring \[task], integer \[task_id], float \[task_data])

### CAI_BaseNPC -> UpdateEnemyMemory
  - **Description**: Whether or not this NPC can be an enemy of another NPC.
  - **Signature**: boolean CAI_BaseNPC -> UpdateEnemyMemory(hscript \[enemy], vector \[position], hscript \[informer])

### CBaseAnimating -> HandleAnimEvent
  - **Description**: Called when handling animation events. Return false to cancel base handling.
  - **Signature**: boolean CBaseAnimating -> HandleAnimEvent(hscript \[event])

### CBaseAnimating -> OnServerRagdoll
  - **Description**: Called when this entity creates/turns into a server-side ragdoll.
  - **Signature**: void CBaseAnimating -> OnServerRagdoll(hscript \[ragdoll], boolean \[submodel])

### CBaseCombatCharacter -> RelationshipPriority
  - **Description**: Called when a character's relationship priority for another entity is requested. Returning a number will make the game use that priority instead of the default priority. (note: 'default' in this case includes overrides from ai_relationship/SetRelationship)
  - **Signature**: integer CBaseCombatCharacter -> RelationshipPriority(hscript \[entity], integer \[def])

### CBaseCombatCharacter -> RelationshipType
  - **Description**: Called when a character's relationship to another entity is requested. Returning a disposition will make the game use that disposition instead of the default relationship. (note: 'default' in this case includes overrides from ai_relationship/SetRelationship)
  - **Signature**: integer CBaseCombatCharacter -> RelationshipType(hscript \[entity], integer \[def])

### CBaseEntity -> CanBeSeenBy
  - **Description**: Whether or not this entity can be seen by the specified NPC.
  - **Signature**: boolean CBaseEntity -> CanBeSeenBy(hscript \[npc])

### CBaseEntity -> FireBullets
  - **Description**: Called when the entity fires bullets from itself or from a weapon. The parameter is the associated FireBulletsInfo_t handle. Return false to cancel bullet firing.
  - **Signature**: void CBaseEntity -> FireBullets(hscript \[info])

### CBaseEntity -> HandleInteraction
  - **Description**: Called for internal game interactions. See the g_interaction set of constants for more information. Returning true or false will return that value without falling to any internal handling. Returning nothing will allow the interaction to fall to any internal handling.
  - **Signature**: boolean CBaseEntity -> HandleInteraction(integer \[interaction], hscript \[sourceEnt])

### CBaseEntity -> ModifyEmitSoundParams
  - **Description**: Called every time a sound is emitted on this entity, allowing for its parameters to be modified.
  - **Signature**: void CBaseEntity -> ModifyEmitSoundParams(hscript \[params])

### CBaseEntity -> ModifyOrAppendCriteria
  - **Description**: Called when the criteria set is collected for a response. Return a table of keyvalues to add to the criteria set.
  - **Signature**: hscript CBaseEntity -> ModifyOrAppendCriteria()

### CBaseEntity -> ModifySentenceParams
  - **Description**: Called every time a sentence is emitted on this entity, allowing for its parameters to be modified.
  - **Signature**: void CBaseEntity -> ModifySentenceParams(hscript \[params])

### CBaseEntity -> OnDeath
  - **Description**: Called when the entity dies (Event_Killed). Returning false makes the entity cancel death, although this could have unforeseen consequences. For hooking any damage instead of just death, use OnTakeDamage.
  - **Signature**: boolean CBaseEntity -> OnDeath(hscript \[info])

### CBaseEntity -> OnEntText
  - **Description**: Called every frame when ent_text is enabled on the entity. Return a string to be added to the ent_text printout.
  - **Signature**: cstring CBaseEntity -> OnEntText()

### CBaseEntity -> OnKilledOther
  - **Description**: Called when the entity kills another entity.
  - **Signature**: void CBaseEntity -> OnKilledOther(hscript \[victim], hscript \[info])

### CBaseEntity -> OnTakeDamage
  - **Description**: Called when the entity takes damage (OnTakeDamage). Returning false makes the entity cancel the damage, similar to a damage filter. This is called after any damage filter operations.
  - **Signature**: boolean CBaseEntity -> OnTakeDamage(hscript \[info])

### CBaseEntity -> UpdateOnRemove
  - **Description**: Called when the entity is being removed.
  - **Signature**: void CBaseEntity -> UpdateOnRemove()

### CBaseEntity -> VPhysicsCollision
  - **Description**: Called for every single VPhysics-related collision experienced by this entity.
  - **Signature**: void CBaseEntity -> VPhysicsCollision(hscript \[entity], float \[speed], vector \[point], vector \[normal])

### CBasePlayer -> FindUseEntity
  - **Description**: Called when finding an entity to use. The 'entity' parameter is for the entity found by the default function. If 'is_radius' is true, then this entity was found by searching in a radius around the cursor, rather than being directly used. Return a different entity to use something else.
  - **Signature**: hscript CBasePlayer -> FindUseEntity(hscript \[entity], boolean \[is_radius])

### CBasePlayer -> PlayerRunCommand
  - **Description**: Called when running a player command on the server.
  - **Signature**: void CBasePlayer -> PlayerRunCommand(hscript \[command])

### CEntities -> OnEntityCreated
  - **Description**: Called when an entity is created. Requires EnableEntityListening() to be fired beforehand.
  - **Signature**: void CEntities -> OnEntityCreated(hscript \[entity])

### CEntities -> OnEntityDeleted
  - **Description**: Called when an entity is deleted. Requires EnableEntityListening() to be fired beforehand.
  - **Signature**: void CEntities -> OnEntityDeleted(hscript \[entity])

### CEntities -> OnEntitySpawned
  - **Description**: Called when an entity spawns. Requires EnableEntityListening() to be fired beforehand.
  - **Signature**: void CEntities -> OnEntitySpawned(hscript \[entity])

### CFilterScript -> BloodAllowed
  - **Description**: A completely optional hook used by filter_script to determine if a caller is allowed to emit blood after taking damage. Return true if blood should be allowed or false if it should not. If this hook is not defined, it will always return true.
  - **Signature**: boolean CFilterScript -> BloodAllowed(hscript \[caller], hscript \[info])

### CFilterScript -> DamageMod
  - **Description**: A completely optional hook used by filter_script to modify damage being taken by an entity. You are free to use CTakeDamageInfo functions on the damage info handle and it will change how the caller is damaged. Returning true or false currently has no effect on vanilla code, but you should generally return true if the damage info has been modified by your code and false if it was not. If this hook is not defined, it will always return false.
  - **Signature**: boolean CFilterScript -> DamageMod(hscript \[caller], hscript \[info])

### CFilterScript -> PassesDamageFilter
  - **Description**: A hook used by filter_script to determine what damage should pass it when it's being used as a damage filter. Return true if the info should pass or false if it should not. If this hook is not defined in a filter_script, damage filter requests will instead check PassesFilter with the attacker as the activator.
  - **Signature**: boolean CFilterScript -> PassesDamageFilter(hscript \[caller], hscript \[info])

### CFilterScript -> PassesFilter
  - **Description**: A hook used by filter_script to determine what entities should pass it. Return true if the entity should pass or false if it should not. This hook is required for regular filtering.
  - **Signature**: boolean CFilterScript -> PassesFilter(hscript \[caller], hscript \[activator])

### CFilterScript -> PassesFinalDamageFilter
  - **Description**: A completely optional hook used by filter_script which only runs when the entity will take damage. This is different from PassesDamageFilter, which is sometimes used in cases where damage is not actually about to be taken. This also runs after a regular PassesDamageFilter check. Return true if the info should pass or false if it should not. If this hook is not defined, it will always return true.
  - **Signature**: boolean CFilterScript -> PassesFinalDamageFilter(hscript \[caller], hscript \[info])

### CPointCommentaryNode -> PreStartCommentary
  - **Description**: Called just before commentary begins. Use this to modify variables or commentary behavior before it begins. Returning false will prevent the commentary from starting.
  - **Signature**: boolean CPointCommentaryNode -> PreStartCommentary()

### CTFLunchBox -> ApplyBiteEffects
  - **Description**: Called when owner takes a bite at this weapon. Return false to cancel any effects it would normally apply.
  - **Signature**: boolean CTFLunchBox -> ApplyBiteEffects(hscript \[hPlayer])

### CWeaponCustomScripted -> AbortReload
  - **Signature**: void CWeaponCustomScripted -> AbortReload()

### CWeaponCustomScripted -> ActivityList
  - **Signature**: hscript CWeaponCustomScripted -> ActivityList()

### CWeaponCustomScripted -> AddViewKick
  - **Signature**: void CWeaponCustomScripted -> AddViewKick()

### CWeaponCustomScripted -> CanDeploy
  - **Description**: Should return true if weapon can be deployed
  - **Signature**: boolean CWeaponCustomScripted -> CanDeploy()

### CWeaponCustomScripted -> CanHolster
  - **Description**: Should return true if weapon can be holstered
  - **Signature**: boolean CWeaponCustomScripted -> CanHolster()

### CWeaponCustomScripted -> CheckReload
  - **Signature**: void CWeaponCustomScripted -> CheckReload()

### CWeaponCustomScripted -> Deploy
  - **Description**: Called when weapon is being deployed
  - **Signature**: boolean CWeaponCustomScripted -> Deploy()

### CWeaponCustomScripted -> FinishReload
  - **Signature**: void CWeaponCustomScripted -> FinishReload()

### CWeaponCustomScripted -> GetBulletSpread
  - **Signature**: vector CWeaponCustomScripted -> GetBulletSpread()

### CWeaponCustomScripted -> GetBulletSpreadForProficiency
  - **Description**: Returns the bullet spread of a specific proficiency level. If this isn't defined, it will fall back to GetBulletSpread.
  - **Signature**: vector CWeaponCustomScripted -> GetBulletSpreadForProficiency(integer \[proficiency])

### CWeaponCustomScripted -> GetDefaultAnimSpeed
  - **Signature**: float CWeaponCustomScripted -> GetDefaultAnimSpeed()

### CWeaponCustomScripted -> GetDrawActivity
  - **Signature**: variant CWeaponCustomScripted -> GetDrawActivity()

### CWeaponCustomScripted -> GetFireRate
  - **Signature**: float CWeaponCustomScripted -> GetFireRate()

### CWeaponCustomScripted -> GetMaxBurst
  - **Signature**: integer CWeaponCustomScripted -> GetMaxBurst()

### CWeaponCustomScripted -> GetMaxRestTime
  - **Signature**: float CWeaponCustomScripted -> GetMaxRestTime()

### CWeaponCustomScripted -> GetMinBurst
  - **Signature**: integer CWeaponCustomScripted -> GetMinBurst()

### CWeaponCustomScripted -> GetMinRestTime
  - **Signature**: float CWeaponCustomScripted -> GetMinRestTime()

### CWeaponCustomScripted -> GetPrimaryAttackActivity
  - **Signature**: variant CWeaponCustomScripted -> GetPrimaryAttackActivity()

### CWeaponCustomScripted -> GetSecondaryAttackActivity
  - **Signature**: variant CWeaponCustomScripted -> GetSecondaryAttackActivity()

### CWeaponCustomScripted -> HandleFireOnEmpty
  - **Description**: Called when they have the attack button down but they are out of ammo. The default implementation either reloads, switches weapons, or plays an empty sound.
  - **Signature**: void CWeaponCustomScripted -> HandleFireOnEmpty()

### CWeaponCustomScripted -> HasAnyAmmo
  - **Description**: Should return true if weapon has ammo
  - **Signature**: boolean CWeaponCustomScripted -> HasAnyAmmo()

### CWeaponCustomScripted -> HasPrimaryAmmo
  - **Description**: Should return true if weapon has primary ammo
  - **Signature**: boolean CWeaponCustomScripted -> HasPrimaryAmmo()

### CWeaponCustomScripted -> HasSecondaryAmmo
  - **Description**: Should return true if weapon has secondary ammo
  - **Signature**: boolean CWeaponCustomScripted -> HasSecondaryAmmo()

### CWeaponCustomScripted -> Holster
  - **Description**: Called when weapon is being holstered
  - **Signature**: boolean CWeaponCustomScripted -> Holster(hscript \[switchingto])

### CWeaponCustomScripted -> ItemBusyFrame
  - **Description**: Called each frame by the player PostThink, if the player's not ready to attack yet
  - **Signature**: void CWeaponCustomScripted -> ItemBusyFrame()

### CWeaponCustomScripted -> ItemHolsterFrame
  - **Description**: Called each frame by the player PreThink, if the weapon is holstered
  - **Signature**: void CWeaponCustomScripted -> ItemHolsterFrame()

### CWeaponCustomScripted -> ItemPostFrame
  - **Description**: Called each frame by the player PostThink
  - **Signature**: void CWeaponCustomScripted -> ItemPostFrame()

### CWeaponCustomScripted -> ItemPreFrame
  - **Description**: Called each frame by the player PreThink
  - **Signature**: void CWeaponCustomScripted -> ItemPreFrame()

### CWeaponCustomScripted -> PrimaryAttack
  - **Signature**: void CWeaponCustomScripted -> PrimaryAttack()

### CWeaponCustomScripted -> Reload
  - **Signature**: boolean CWeaponCustomScripted -> Reload()

### CWeaponCustomScripted -> Reload_NPC
  - **Signature**: void CWeaponCustomScripted -> Reload_NPC()

### CWeaponCustomScripted -> SecondaryAttack
  - **Signature**: void CWeaponCustomScripted -> SecondaryAttack()

### CWeaponCustomScripted -> WeaponIdle
  - **Description**: Called when no buttons pressed
  - **Signature**: void CWeaponCustomScripted -> WeaponIdle()

### CWeaponCustomScripted -> WeaponLOSCondition
  - **Signature**: boolean CWeaponCustomScripted -> WeaponLOSCondition()

### CWeaponCustomScripted -> WeaponMeleeAttack1Condition
  - **Signature**: integer CWeaponCustomScripted -> WeaponMeleeAttack1Condition()

### CWeaponCustomScripted -> WeaponMeleeAttack2Condition
  - **Signature**: integer CWeaponCustomScripted -> WeaponMeleeAttack2Condition()

### CWeaponCustomScripted -> WeaponRangeAttack1Condition
  - **Signature**: integer CWeaponCustomScripted -> WeaponRangeAttack1Condition()

### CWeaponCustomScripted -> WeaponRangeAttack2Condition
  - **Signature**: integer CWeaponCustomScripted -> WeaponRangeAttack2Condition()

### OnRestore
  - **Description**: Called when the game is restored.
  - **Signature**: void OnRestore()

### OnSave
  - **Description**: Called when the game is saved.
  - **Signature**: void OnSave()
