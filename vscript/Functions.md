## Functions
```
TF2 Classified build 5011
Squirrel 3.1 stable (_versionnumber_ = 310)
API dump taken: 2026-07-22
```
### AI_EnemyInfo_t::DangerMemory
  - **Description**: Get the memory of danger position w/o enemy pointer.
  - **Signature**: boolean AI_EnemyInfo_t::DangerMemory()

### AI_EnemyInfo_t::EludedMe
  - **Description**: Get whether the enemy is not at the last known location.
  - **Signature**: boolean AI_EnemyInfo_t::EludedMe()

### AI_EnemyInfo_t::Enemy
  - **Signature**: hscript AI_EnemyInfo_t::Enemy()

### AI_EnemyInfo_t::LastKnownLocation
  - **Description**: Get
  - **Signature**: vector AI_EnemyInfo_t::LastKnownLocation()

### AI_EnemyInfo_t::LastSeenLocation
  - **Description**: Get
  - **Signature**: vector AI_EnemyInfo_t::LastSeenLocation()

### AI_EnemyInfo_t::MobbedMe
  - **Description**: Get whether the enemy was part of a mob at some point.
  - **Signature**: boolean AI_EnemyInfo_t::MobbedMe()

### AI_EnemyInfo_t::SetDangerMemory
  - **Description**: Set the memory of danger position w/o enemy pointer.
  - **Signature**: void AI_EnemyInfo_t::SetDangerMemory(boolean)

### AI_EnemyInfo_t::SetEludedMe
  - **Description**: Set whether the enemy is not at the last known location.
  - **Signature**: void AI_EnemyInfo_t::SetEludedMe(boolean)

### AI_EnemyInfo_t::SetEnemy
  - **Signature**: void AI_EnemyInfo_t::SetEnemy(hscript)

### AI_EnemyInfo_t::SetLastKnownLocation
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetLastKnownLocation(vector)

### AI_EnemyInfo_t::SetLastSeenLocation
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetLastSeenLocation(vector)

### AI_EnemyInfo_t::SetMobbedMe
  - **Description**: Set whether the enemy was part of a mob at some point.
  - **Signature**: void AI_EnemyInfo_t::SetMobbedMe(boolean)

### AI_EnemyInfo_t::SetTimeAtFirstHand
  - **Description**: Set the time at which the enemy was seen firsthand.
  - **Signature**: void AI_EnemyInfo_t::SetTimeAtFirstHand(float)

### AI_EnemyInfo_t::SetTimeFirstSeen
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetTimeFirstSeen(float)

### AI_EnemyInfo_t::SetTimeLastReacquired
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetTimeLastReacquired(float)

### AI_EnemyInfo_t::SetTimeLastReceivedDamageFrom
  - **Description**: Set the last time damage was received from this enemy.
  - **Signature**: void AI_EnemyInfo_t::SetTimeLastReceivedDamageFrom(float)

### AI_EnemyInfo_t::SetTimeLastSeen
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetTimeLastSeen(float)

### AI_EnemyInfo_t::SetTimeValidEnemy
  - **Description**: Set the time at which the enemy can be selected (reaction delay).
  - **Signature**: void AI_EnemyInfo_t::SetTimeValidEnemy(float)

### AI_EnemyInfo_t::SetUnforgettable
  - **Description**: Set
  - **Signature**: void AI_EnemyInfo_t::SetUnforgettable(boolean)

### AI_EnemyInfo_t::TimeAtFirstHand
  - **Description**: Get the time at which the enemy was seen firsthand.
  - **Signature**: float AI_EnemyInfo_t::TimeAtFirstHand()

### AI_EnemyInfo_t::TimeFirstSeen
  - **Description**: Get
  - **Signature**: float AI_EnemyInfo_t::TimeFirstSeen()

### AI_EnemyInfo_t::TimeLastReacquired
  - **Description**: Get
  - **Signature**: float AI_EnemyInfo_t::TimeLastReacquired()

### AI_EnemyInfo_t::TimeLastReceivedDamageFrom
  - **Description**: Get the last time damage was received from this enemy.
  - **Signature**: float AI_EnemyInfo_t::TimeLastReceivedDamageFrom()

### AI_EnemyInfo_t::TimeLastSeen
  - **Description**: Get
  - **Signature**: float AI_EnemyInfo_t::TimeLastSeen()

### AI_EnemyInfo_t::TimeValidEnemy
  - **Description**: Get the time at which the enemy can be selected (reaction delay).
  - **Signature**: float AI_EnemyInfo_t::TimeValidEnemy()

### AI_EnemyInfo_t::Unforgettable
  - **Description**: Get
  - **Signature**: boolean AI_EnemyInfo_t::Unforgettable()

### ActivateTeam
  - **Signature**: void ActivateTeam(integer)

### AddPhysVelocity
  - **Description**: Adds physics velocity for the given VPhysics object
  - **Signature**: void AddPhysVelocity(hscript, vector, vector)

### AddThinkToEnt
  - **Description**: This will put a think function onto an entity, or pass null to remove it. This is NOT chained, so be careful.
  - **Signature**: void AddThinkToEnt(hscript, cstring)

### AllowThirdPersonCamera
  - **Signature**: boolean AllowThirdPersonCamera()

### AngleDiff
  - **Description**: Returns the degrees difference between two yaw angles.
  - **Signature**: float AngleDiff(float, float)

### AngleDistance
  - **Signature**: float AngleDistance(float, float)

### AngleIMatrix
  - **Description**: Sets the inverted angles and position of a matrix.
  - **Signature**: void AngleIMatrix(qangle, vector, hscript)

### AngleMatrix
  - **Description**: Sets the angles and position of a matrix.
  - **Signature**: void AngleMatrix(qangle, vector, hscript)

### AngleNormalize
  - **Description**: Clamps an angle to be in between -360 and 360.
  - **Signature**: float AngleNormalize(float)

### AngleNormalizePositive
  - **Description**: Clamps an angle to be in between 0 and 360.
  - **Signature**: float AngleNormalizePositive(float)

### AngleVectors
  - **Description**: Turns an angle into a direction vector.
  - **Signature**: vector AngleVectors(qangle)

### AnglesAreEqual
  - **Description**: Checks if two angles are equal based on a given tolerance value.
  - **Signature**: boolean AnglesAreEqual(float, float, float)

### AppearsToBeANumber
  - **Description**: Checks if the given string appears to be a number.
  - **Signature**: boolean AppearsToBeANumber(cstring)

### Approach
  - **Signature**: float Approach(float, float, float)

### ApproachAngle
  - **Description**: Returns an angle which approaches the target angle from the input angle with the specified speed.
  - **Signature**: float ApproachAngle(float, float, float)

### ArePlayersInHell
  - **Signature**: boolean ArePlayersInHell()

### Bias
  - **Description**: The curve is biased towards 0 or 1 based on biasAmt, which is between 0 and 1.
  - **Signature**: float Bias(float, float)

### CAI_BaseActor::AddLookTarget
  - **Description**: Add a potential look target for this actor with the specified importance, duration, and ramp.
  - **Signature**: void CAI_BaseActor::AddLookTarget(hscript, float, float, float)

### CAI_BaseActor::AddLookTargetPos
  - **Description**: Add a potential look target position for this actor with the specified importance, duration, and ramp.
  - **Signature**: void CAI_BaseActor::AddLookTargetPos(vector, float, float, float)

### CAI_BaseNPC::AddSleepFlags
  - **Description**: Add to the NPC's sleep flags. (see AI_SLEEP_ set of constants)
  - **Signature**: void CAI_BaseNPC::AddSleepFlags(integer)

### CAI_BaseNPC::CapabilitiesAdd
  - **Description**: Add capabilities to the NPC.
  - **Signature**: integer CAI_BaseNPC::CapabilitiesAdd(integer)

### CAI_BaseNPC::CapabilitiesClear
  - **Description**: Clear capabilities for the NPC.
  - **Signature**: void CAI_BaseNPC::CapabilitiesClear()

### CAI_BaseNPC::CapabilitiesGet
  - **Description**: Get the capabilities the NPC currently possesses.
  - **Signature**: integer CAI_BaseNPC::CapabilitiesGet()

### CAI_BaseNPC::CapabilitiesRemove
  - **Description**: Remove capabilities from the NPC.
  - **Signature**: integer CAI_BaseNPC::CapabilitiesRemove(integer)

### CAI_BaseNPC::ChainRunTask
  - **Description**: Use with RunTask to redirect to the specified task.
  - **Signature**: void CAI_BaseNPC::ChainRunTask(cstring, float)

### CAI_BaseNPC::ChainStartTask
  - **Description**: Use with StartTask to redirect to the specified task.
  - **Signature**: void CAI_BaseNPC::ChainStartTask(cstring, float)

### CAI_BaseNPC::ClearCondition
  - **Description**: Clear a condition on the NPC.
  - **Signature**: void CAI_BaseNPC::ClearCondition(cstring)

### CAI_BaseNPC::ClearConditionID
  - **Description**: Clear a condition on the NPC by ID.
  - **Signature**: void CAI_BaseNPC::ClearConditionID(integer)

### CAI_BaseNPC::ClearCustomInterruptCondition
  - **Description**: Use with BuildScheduleTestBits to define conditions which should interrupt the schedule.
  - **Signature**: void CAI_BaseNPC::ClearCustomInterruptCondition(cstring)

### CAI_BaseNPC::ClearEnemyMemory
  - **Description**: Makes the NPC forget about the specified enemy.
  - **Signature**: void CAI_BaseNPC::ClearEnemyMemory(hscript)

### CAI_BaseNPC::ClearSchedule
  - **Description**: Clear the NPC's current schedule for the specified reason.
  - **Signature**: void CAI_BaseNPC::ClearSchedule(cstring)

### CAI_BaseNPC::CompleteTask
  - **Description**: Completes the currently running task.
  - **Signature**: void CAI_BaseNPC::CompleteTask()

### CAI_BaseNPC::Crouch
  - **Description**: Tells the NPC to crouch.
  - **Signature**: boolean CAI_BaseNPC::Crouch()

### CAI_BaseNPC::FailTask
  - **Description**: Fails the currently running task with the specified error message.
  - **Signature**: void CAI_BaseNPC::FailTask(cstring)

### CAI_BaseNPC::FindEnemyMemory
  - **Description**: Get information about the NPC's current enemy.
  - **Signature**: hscript CAI_BaseNPC::FindEnemyMemory(hscript)

### CAI_BaseNPC::GetActivity
  - **Description**: Get the NPC's current activity.
  - **Signature**: cstring CAI_BaseNPC::GetActivity()

### CAI_BaseNPC::GetActivityID
  - **Description**: Get the NPC's current activity ID.
  - **Signature**: integer CAI_BaseNPC::GetActivityID()

### CAI_BaseNPC::GetBestSound
  - **Description**: Get the NPC's best sound of the specified type(s). Use 'ALL_SOUNDS' to get any sound.
  - **Signature**: hscript CAI_BaseNPC::GetBestSound(integer)

### CAI_BaseNPC::GetCine
  - **Description**: Get the NPC's currently running scripted sequence if it has one.
  - **Signature**: hscript CAI_BaseNPC::GetCine()

### CAI_BaseNPC::GetEnemy
  - **Description**: Get the NPC's current enemy.
  - **Signature**: hscript CAI_BaseNPC::GetEnemy()

### CAI_BaseNPC::GetEnemyLKP
  - **Description**: Get the last known position of the NPC's current enemy.
  - **Signature**: vector CAI_BaseNPC::GetEnemyLKP()

### CAI_BaseNPC::GetExpresser
  - **Description**: Get a handle for this NPC's expresser.
  - **Signature**: hscript CAI_BaseNPC::GetExpresser()

### CAI_BaseNPC::GetFirstEnemyMemory
  - **Description**: Get information about the NPC's first enemy.
  - **Signature**: hscript CAI_BaseNPC::GetFirstEnemyMemory()

### CAI_BaseNPC::GetFirstHeardSound
  - **Description**: Get the NPC's first heard sound.
  - **Signature**: hscript CAI_BaseNPC::GetFirstHeardSound()

### CAI_BaseNPC::GetFirstSeenEntity
  - **Description**: Get the NPC's first seen entity in the specified 'SEEN_' list.
  - **Signature**: hscript CAI_BaseNPC::GetFirstSeenEntity(integer)

### CAI_BaseNPC::GetGestureVersionOfActivity
  - **Description**: Get the gesture activity counterpart of the specified sequence activity, if one exists.
  - **Signature**: cstring CAI_BaseNPC::GetGestureVersionOfActivity(cstring)

### CAI_BaseNPC::GetGestureVersionOfActivityID
  - **Description**: Get the gesture activity ID counterpart of the specified sequence activity ID, if one exists.
  - **Signature**: integer CAI_BaseNPC::GetGestureVersionOfActivityID(integer)

### CAI_BaseNPC::GetHintGroup
  - **Description**: Get the name of the NPC's hint group.
  - **Signature**: cstring CAI_BaseNPC::GetHintGroup()

### CAI_BaseNPC::GetHintNode
  - **Description**: Get the NPC's current AI hint.
  - **Signature**: hscript CAI_BaseNPC::GetHintNode()

### CAI_BaseNPC::GetIdealNPCState
  - **Description**: Get the NPC's ideal state.
  - **Signature**: integer CAI_BaseNPC::GetIdealNPCState()

### CAI_BaseNPC::GetLastAttackTime
  - **Description**: Get the last time the NPC has used an attack (e.g. fired a bullet from a gun).
  - **Signature**: float CAI_BaseNPC::GetLastAttackTime()

### CAI_BaseNPC::GetLastDamageTime
  - **Description**: Get the last time the NPC has been damaged.
  - **Signature**: float CAI_BaseNPC::GetLastDamageTime()

### CAI_BaseNPC::GetLastEnemyTime
  - **Description**: Get the last time the NPC has seen an enemy.
  - **Signature**: float CAI_BaseNPC::GetLastEnemyTime()

### CAI_BaseNPC::GetLastPlayerDamageTime
  - **Description**: Get the last time the NPC has been damaged by a player.
  - **Signature**: float CAI_BaseNPC::GetLastPlayerDamageTime()

### CAI_BaseNPC::GetNPCState
  - **Description**: Get the NPC's current state.
  - **Signature**: integer CAI_BaseNPC::GetNPCState()

### CAI_BaseNPC::GetNPCTarget
  - **Description**: Get the NPC's AI target.
  - **Signature**: hscript CAI_BaseNPC::GetNPCTarget()

### CAI_BaseNPC::GetNextEnemyMemory
  - **Description**: Get information about the NPC's next enemy.
  - **Signature**: hscript CAI_BaseNPC::GetNextEnemyMemory(hscript)

### CAI_BaseNPC::GetNextHeardSound
  - **Description**: Get the NPC's next heard sound.
  - **Signature**: hscript CAI_BaseNPC::GetNextHeardSound(hscript)

### CAI_BaseNPC::GetNextSeenEntity
  - **Description**: Get the NPC's next seen entity in the specified 'SEEN_' list.
  - **Signature**: hscript CAI_BaseNPC::GetNextSeenEntity(hscript, integer)

### CAI_BaseNPC::GetSchedule
  - **Description**: Get the NPC's current schedule.
  - **Signature**: cstring CAI_BaseNPC::GetSchedule()

### CAI_BaseNPC::GetScheduleID
  - **Description**: Get the NPC's current schedule ID.
  - **Signature**: integer CAI_BaseNPC::GetScheduleID()

### CAI_BaseNPC::GetScriptState
  - **Description**: Get the NPC's current scripted sequence state.
  - **Signature**: integer CAI_BaseNPC::GetScriptState()

### CAI_BaseNPC::GetSequenceVersionOfGesture
  - **Description**: Get the sequence activity counterpart of the specified gesture activity, if one exists.
  - **Signature**: cstring CAI_BaseNPC::GetSequenceVersionOfGesture(cstring)

### CAI_BaseNPC::GetSequenceVersionOfGestureID
  - **Description**: Get the sequence activity ID counterpart of the specified gesture activity ID, if one exists.
  - **Signature**: integer CAI_BaseNPC::GetSequenceVersionOfGestureID(integer)

### CAI_BaseNPC::GetSleepState
  - **Description**: Get the NPC's sleep state. (see AISS_ set of constants)
  - **Signature**: integer CAI_BaseNPC::GetSleepState()

### CAI_BaseNPC::GetSquad
  - **Description**: Get the NPC's squad if it has one.
  - **Signature**: hscript CAI_BaseNPC::GetSquad()

### CAI_BaseNPC::GetTask
  - **Description**: Get the NPC's current task.
  - **Signature**: cstring CAI_BaseNPC::GetTask()

### CAI_BaseNPC::GetTaskID
  - **Description**: Get the NPC's current task ID.
  - **Signature**: integer CAI_BaseNPC::GetTaskID()

### CAI_BaseNPC::GetTaskStatus
  - **Description**: Gets the current task's status.
  - **Signature**: integer CAI_BaseNPC::GetTaskStatus()

### CAI_BaseNPC::HasCondition
  - **Description**: Get whether the NPC has a condition.
  - **Signature**: boolean CAI_BaseNPC::HasCondition(cstring)

### CAI_BaseNPC::HasConditionID
  - **Description**: Get whether the NPC has a condition ID.
  - **Signature**: boolean CAI_BaseNPC::HasConditionID(integer)

### CAI_BaseNPC::HasSleepFlags
  - **Description**: Return true if the NPC has the specified sleep flags. (see AI_SLEEP_ set of constants)
  - **Signature**: boolean CAI_BaseNPC::HasSleepFlags(integer)

### CAI_BaseNPC::IsCommandable
  - **Description**: Check if the NPC is commandable.
  - **Signature**: boolean CAI_BaseNPC::IsCommandable()

### CAI_BaseNPC::IsCrouching
  - **Description**: Returns true if the NPC is crouching.
  - **Signature**: boolean CAI_BaseNPC::IsCrouching()

### CAI_BaseNPC::IsCustomInterruptConditionSet
  - **Description**: Use with BuildScheduleTestBits to define conditions which should interrupt the schedule.
  - **Signature**: boolean CAI_BaseNPC::IsCustomInterruptConditionSet(cstring)

### CAI_BaseNPC::IsInPlayerSquad
  - **Description**: Check if the NPC is in the player's squad.
  - **Signature**: boolean CAI_BaseNPC::IsInPlayerSquad()

### CAI_BaseNPC::IsInSquad
  - **Description**: Returns true if the NPC is in a squad.
  - **Signature**: boolean CAI_BaseNPC::IsInSquad()

### CAI_BaseNPC::IsMedic
  - **Description**: Returns true if this NPC is a medic.
  - **Signature**: boolean CAI_BaseNPC::IsMedic()

### CAI_BaseNPC::IsMoving
  - **Description**: Check if the NPC is moving.
  - **Signature**: boolean CAI_BaseNPC::IsMoving()

### CAI_BaseNPC::NumEnemies
  - **Description**: Get the number of enemies this NPC knows about.
  - **Signature**: integer CAI_BaseNPC::NumEnemies()

### CAI_BaseNPC::NumWeaponsInSquad
  - **Description**: Get the number of weapons in a squad.
  - **Signature**: integer CAI_BaseNPC::NumWeaponsInSquad(cstring)

### CAI_BaseNPC::RemoveSleepFlags
  - **Description**: Remove from NPC's sleep flags. (see AI_SLEEP_ set of constants)
  - **Signature**: void CAI_BaseNPC::RemoveSleepFlags(integer)

### CAI_BaseNPC::ResetActivity
  - **Description**: Reset the NPC's current activity.
  - **Signature**: void CAI_BaseNPC::ResetActivity()

### CAI_BaseNPC::SetActivity
  - **Description**: Set the NPC's current activity.
  - **Signature**: void CAI_BaseNPC::SetActivity(cstring)

### CAI_BaseNPC::SetActivityID
  - **Description**: Set the NPC's current activity ID.
  - **Signature**: void CAI_BaseNPC::SetActivityID(integer)

### CAI_BaseNPC::SetCondition
  - **Description**: Set a condition on the NPC.
  - **Signature**: void CAI_BaseNPC::SetCondition(cstring)

### CAI_BaseNPC::SetConditionID
  - **Description**: Set a condition on the NPC by ID.
  - **Signature**: void CAI_BaseNPC::SetConditionID(integer)

### CAI_BaseNPC::SetCustomInterruptCondition
  - **Description**: Use with BuildScheduleTestBits to define conditions which should interrupt the schedule.
  - **Signature**: void CAI_BaseNPC::SetCustomInterruptCondition(cstring)

### CAI_BaseNPC::SetEnemy
  - **Description**: Set the NPC's current enemy.
  - **Signature**: void CAI_BaseNPC::SetEnemy(hscript)

### CAI_BaseNPC::SetEnemyDiscardTime
  - **Description**: Sets the amount of time needed before the NPC discards an unseen enemy's memory.
  - **Signature**: void CAI_BaseNPC::SetEnemyDiscardTime(float)

### CAI_BaseNPC::SetFreeKnowledgeDuration
  - **Description**: Sets the amount of time the NPC can always know an enemy's location after losing sight.
  - **Signature**: void CAI_BaseNPC::SetFreeKnowledgeDuration(float)

### CAI_BaseNPC::SetIdealNPCState
  - **Description**: Set the NPC's ideal state.
  - **Signature**: void CAI_BaseNPC::SetIdealNPCState(integer)

### CAI_BaseNPC::SetNPCTarget
  - **Description**: Set the NPC's AI target.
  - **Signature**: void CAI_BaseNPC::SetNPCTarget(hscript)

### CAI_BaseNPC::SetSchedule
  - **Description**: Set the NPC's current schedule.
  - **Signature**: void CAI_BaseNPC::SetSchedule(cstring)

### CAI_BaseNPC::SetScheduleID
  - **Description**: Set the NPC's current schedule ID.
  - **Signature**: void CAI_BaseNPC::SetScheduleID(integer)

### CAI_BaseNPC::SetSleepState
  - **Description**: Set the NPC's sleep state. (see AISS_ set of constants)
  - **Signature**: void CAI_BaseNPC::SetSleepState(integer)

### CAI_BaseNPC::Sleep
  - **Description**: Puts the NPC into a sleeping state.
  - **Signature**: void CAI_BaseNPC::Sleep()

### CAI_BaseNPC::Stand
  - **Description**: Tells the NPC to stand if it is crouching.
  - **Signature**: boolean CAI_BaseNPC::Stand()

### CAI_BaseNPC::TranslateActivity
  - **Description**: Translates the specified activity string and returns the translated activity ID.
  - **Signature**: integer CAI_BaseNPC::TranslateActivity(cstring)

### CAI_BaseNPC::TranslateActivityID
  - **Description**: Translates the specified activity ID and returns the translated activity ID.
  - **Signature**: integer CAI_BaseNPC::TranslateActivityID(integer)

### CAI_BaseNPC::UpdateEnemyMemory
  - **Description**: Update information on this enemy. First parameter is the enemy, second is the position we now know the enemy is at, third parameter is the informer (e.g. squadmate who sees enemy, null if I see it myself). Returns true if this is a new enemy.
  - **Signature**: boolean CAI_BaseNPC::UpdateEnemyMemory(hscript, vector, hscript)

### CAI_BaseNPC::Wake
  - **Description**: Awakens the NPC if it is currently asleep.
  - **Signature**: void CAI_BaseNPC::Wake(hscript)

### CAI_Expresser::BlockSpeechUntil
  - **Description**: Block speech for a certain amount of time. This is stored in curtime.
  - **Signature**: void CAI_Expresser::BlockSpeechUntil(float)

### CAI_Expresser::CanSpeak
  - **Description**: Check if the actor can speak.
  - **Signature**: boolean CAI_Expresser::CanSpeak()

### CAI_Expresser::ForceNotSpeaking
  - **Description**: If the actor is speaking, force the system to recognize them as not speaking.
  - **Signature**: void CAI_Expresser::ForceNotSpeaking()

### CAI_Expresser::GetVoicePitch
  - **Description**: Get the actor's voice pitch. Used in sentences.
  - **Signature**: integer CAI_Expresser::GetVoicePitch()

### CAI_Expresser::IsSpeaking
  - **Description**: Check if the actor is speaking.
  - **Signature**: boolean CAI_Expresser::IsSpeaking()

### CAI_Expresser::SetVoicePitch
  - **Description**: Set the actor's voice pitch. Used in sentences.
  - **Signature**: void CAI_Expresser::SetVoicePitch(integer)

### CAI_Expresser::Speak
  - **Description**: Speak a response concept with the specified modifiers.
  - **Signature**: boolean CAI_Expresser::Speak(cstring, cstring)

### CAI_Expresser::SpeakAutoGeneratedScene
  - **Description**: Speak an automatically generated, instanced VCD scene for this sound as though it were played through the Response System. Return whether the scene successfully plays.
  - **Signature**: boolean CAI_Expresser::SpeakAutoGeneratedScene(cstring, float)

### CAI_Expresser::SpeakRawScene
  - **Description**: Speak a raw, instanced VCD scene as though it were played through the Response System. Return whether the scene successfully plays.
  - **Signature**: boolean CAI_Expresser::SpeakRawScene(cstring, float)

### CAI_Expresser::SpeakRawSentence
  - **Description**: Speak a raw sentence as though it were played through the Response System. Return the sentence's index; -1 if not successfully played.
  - **Signature**: integer CAI_Expresser::SpeakRawSentence(cstring, float)

### CAI_GoalEntity::IsActive
  - **Description**: Check if the goal entity is active.
  - **Signature**: boolean CAI_GoalEntity::IsActive()

### CAI_GoalEntity::NumActors
  - **Description**: Get the number of actors using this goal entity.
  - **Signature**: integer CAI_GoalEntity::NumActors()

### CAI_Hint::GetDirection
  - **Description**: Get the hint's direction.
  - **Signature**: vector CAI_Hint::GetDirection()

### CAI_Hint::GetHintActivity
  - **Description**: Get the name of the hint activity.
  - **Signature**: cstring CAI_Hint::GetHintActivity()

### CAI_Hint::GetHintGroup
  - **Description**: Get the name of the hint's group.
  - **Signature**: cstring CAI_Hint::GetHintGroup()

### CAI_Hint::GetHintType
  - **Description**: Get the hint's type ID.
  - **Signature**: integer CAI_Hint::GetHintType()

### CAI_Hint::GetNodeId
  - **Description**: Get the hint's node ID.
  - **Signature**: integer CAI_Hint::GetNodeId()

### CAI_Hint::GetUser
  - **Description**: Get the hint's current user.
  - **Signature**: hscript CAI_Hint::GetUser()

### CAI_Hint::IsDisabled
  - **Description**: Check if the hint is disabled.
  - **Signature**: boolean CAI_Hint::IsDisabled()

### CAI_Hint::IsLocked
  - **Description**: Check if the hint is locked.
  - **Signature**: boolean CAI_Hint::IsLocked()

### CAI_Hint::Yaw
  - **Description**: Get the hint's yaw.
  - **Signature**: float CAI_Hint::Yaw()

### CAI_Network::GetNodeHint
  - **Description**: Get a node's hint
  - **Signature**: hscript CAI_Network::GetNodeHint(integer)

### CAI_Network::GetNodePosition
  - **Description**: Get position of node using a generic human hull
  - **Signature**: vector CAI_Network::GetNodePosition(integer)

### CAI_Network::GetNodePositionWithHull
  - **Description**: Get position of node using the specified hull
  - **Signature**: vector CAI_Network::GetNodePositionWithHull(integer, integer)

### CAI_Network::GetNodeType
  - **Description**: Get a node's type
  - **Signature**: integer CAI_Network::GetNodeType(integer)

### CAI_Network::GetNodeYaw
  - **Description**: Get yaw of node
  - **Signature**: float CAI_Network::GetNodeYaw(integer)

### CAI_Network::NearestNodeToPoint
  - **Description**: Get ID of nearest node
  - **Signature**: integer CAI_Network::NearestNodeToPoint(vector, boolean)

### CAI_Network::NearestNodeToPointForNPC
  - **Description**: Get ID of nearest node using the specified NPC's properties
  - **Signature**: integer CAI_Network::NearestNodeToPointForNPC(hscript, vector, boolean)

### CAI_Network::NumNodes
  - **Description**: Number of nodes in the level
  - **Signature**: integer CAI_Network::NumNodes()

### CAI_SensedObjectsManager::AddEntity
  - **Description**: Adds an entity to the sensed object list.
  - **Signature**: void CAI_SensedObjectsManager::AddEntity(hscript)

### CAI_SensedObjectsManager::RemoveEntity
  - **Description**: Removes an entity from the sensed object list.
  - **Signature**: void CAI_SensedObjectsManager::RemoveEntity(hscript)

### CAI_Squad::AddToSquad
  - **Description**: Adds a NPC to the squad.
  - **Signature**: void CAI_Squad::AddToSquad(hscript)

### CAI_Squad::GetAnyMember
  - **Description**: Randomly get any one of the squad's members.
  - **Signature**: hscript CAI_Squad::GetAnyMember()

### CAI_Squad::GetFirstMember
  - **Description**: Get the squad's first member. The parameter is for whether to ignore silent members (see CAI_Squad::IsSilentMember() for more info).
  - **Signature**: hscript CAI_Squad::GetFirstMember(boolean)

### CAI_Squad::GetLeader
  - **Description**: Get the squad's leader.
  - **Signature**: hscript CAI_Squad::GetLeader()

### CAI_Squad::GetMember
  - **Description**: Get one of the squad's members by their index.
  - **Signature**: hscript CAI_Squad::GetMember(integer)

### CAI_Squad::GetName
  - **Description**: Get the squad's name.
  - **Signature**: cstring CAI_Squad::GetName()

### CAI_Squad::GetSquadData
  - **Description**: Get the squad data in the specified slot.
  - **Signature**: integer CAI_Squad::GetSquadData(integer)

### CAI_Squad::GetSquadIndex
  - **Description**: Get the index of the specified NPC in the squad.
  - **Signature**: integer CAI_Squad::GetSquadIndex(hscript)

### CAI_Squad::GetSquadMemberNearestTo
  - **Description**: Get the squad member nearest to a point.
  - **Signature**: hscript CAI_Squad::GetSquadMemberNearestTo(vector)

### CAI_Squad::GetVisibleSquadMembers
  - **Description**: Get the number of squad members visible to the specified member.
  - **Signature**: integer CAI_Squad::GetVisibleSquadMembers(hscript)

### CAI_Squad::IsLeader
  - **Description**: Returns true if the specified NPC is the squad's leader.
  - **Signature**: boolean CAI_Squad::IsLeader(hscript)

### CAI_Squad::IsMember
  - **Description**: Returns true if the specified NPC is a member of the squad.
  - **Signature**: boolean CAI_Squad::IsMember(hscript)

### CAI_Squad::IsSilentMember
  - **Description**: Returns true if the specified NPC is a "silent squad member", which means it's only in squads for enemy information purposes and does not actually participate in any tactics. For example, this is used for npc_enemyfinder and vital allies (e.g. Alyx) in the player's squad. Please note that this does not check if the NPC is in the squad first.
  - **Signature**: boolean CAI_Squad::IsSilentMember(hscript)

### CAI_Squad::NearestSquadMember
  - **Description**: Get the squad member nearest to the specified member.
  - **Signature**: hscript CAI_Squad::NearestSquadMember(hscript)

### CAI_Squad::NumMembers
  - **Description**: Get the squad's number of members. The parameter is for whether to ignore silent members (see CAI_Squad::IsSilentMember() for more info).
  - **Signature**: integer CAI_Squad::NumMembers(boolean)

### CAI_Squad::RemoveFromSquad
  - **Description**: Removes a NPC from the squad.
  - **Signature**: void CAI_Squad::RemoveFromSquad(hscript)

### CAI_Squad::SetSquadData
  - **Description**: Set the squad data in the specified slot.
  - **Signature**: void CAI_Squad::SetSquadData(integer, integer)

### CAI_Squad::SquadMemberInRange
  - **Description**: Get the first squad member found around the specified position in the specified range.
  - **Signature**: hscript CAI_Squad::SquadMemberInRange(vector, float)

### CAI_Squad::UpdateEnemyMemory
  - **Description**: Updates the squad's memory of an enemy. The first parameter is the updater, the second parameter is the enemy, and the third parameter is the position.
  - **Signature**: void CAI_Squad::UpdateEnemyMemory(hscript, hscript, vector)

### CAI_SquadManager::FindCreateSquad
  - **Description**: Find the specified squad in the squad list or create it if it doesn't exist.
  - **Signature**: hscript CAI_SquadManager::FindCreateSquad(cstring)

### CAI_SquadManager::FindSquad
  - **Description**: Find the specified squad in the squad list. Returns null if none found.
  - **Signature**: hscript CAI_SquadManager::FindSquad(cstring)

### CAI_SquadManager::GetFirstSquad
  - **Description**: Get the first squad in the squad list.
  - **Signature**: hscript CAI_SquadManager::GetFirstSquad()

### CAI_SquadManager::GetNextSquad
  - **Description**: Get the next squad in the squad list starting from the specified squad.
  - **Signature**: hscript CAI_SquadManager::GetNextSquad(hscript)

### CAI_SquadManager::NumSquads
  - **Description**: Get the number of squads in the list.
  - **Signature**: integer CAI_SquadManager::NumSquads()

### CAmmoDef::DamageForce
  - **Description**: Gets the amount of force this ammo type deals.
  - **Signature**: float CAmmoDef::DamageForce(integer)

### CAmmoDef::DamageType
  - **Description**: Gets the type of damage this ammo type deals.
  - **Signature**: integer CAmmoDef::DamageType(integer)

### CAmmoDef::Flags
  - **Description**: Gets the flags this ammo type uses.
  - **Signature**: integer CAmmoDef::Flags(integer)

### CAmmoDef::GetNumAmmoTypes
  - **Description**: Gets the number of ammo types which currently exist.
  - **Signature**: integer CAmmoDef::GetNumAmmoTypes()

### CAmmoDef::Index
  - **Description**: Gets the index of the specified ammo type name.
  - **Signature**: integer CAmmoDef::Index(cstring)

### CAmmoDef::MaxCarry
  - **Description**: Gets the maximum amount of this ammo type which players should be able to carry.
  - **Signature**: integer CAmmoDef::MaxCarry(integer)

### CAmmoDef::MaxSplashSize
  - **Description**: Gets the maximum size of water splashes caused by impacts from this ammo type.
  - **Signature**: integer CAmmoDef::MaxSplashSize(integer)

### CAmmoDef::MinSplashSize
  - **Description**: Gets the minimum size of water splashes caused by impacts from this ammo type.
  - **Signature**: integer CAmmoDef::MinSplashSize(integer)

### CAmmoDef::NPCDamage
  - **Description**: Gets the damage NPCs deal for the specified ammo type.
  - **Signature**: integer CAmmoDef::NPCDamage(integer)

### CAmmoDef::Name
  - **Description**: Gets the name of the specified ammo type index.
  - **Signature**: cstring CAmmoDef::Name(integer)

### CAmmoDef::PlrDamage
  - **Description**: Gets the damage players deal for the specified ammo type.
  - **Signature**: integer CAmmoDef::PlrDamage(integer)

### CAmmoDef::TracerType
  - **Description**: Gets the type of tracer this ammo type uses.
  - **Signature**: integer CAmmoDef::TracerType(integer)

### CBaseAnimating::BecomeRagdollOnClient
  - **Description**: Becomes a ragdoll with a force
  - **Signature**: boolean CBaseAnimating::BecomeRagdollOnClient(vector)

### CBaseAnimating::CanBecomeRagdoll
  - **Signature**: boolean CBaseAnimating::CanBecomeRagdoll()

### CBaseAnimating::DispatchAnimEvents
  - **Description**: Dispatch animation events to a CBaseAnimating
  - **Signature**: void CBaseAnimating::DispatchAnimEvents(hscript)

### CBaseAnimating::Dissolve
  - **Description**: Use 'sprites/blueglow1.vmt' for the default material, Time() for the default start time, false for npcOnly if you don't want it to check if the entity is a NPC first, 0 for the default dissolve type, Vector(0,0,0) for the default dissolver origin, and 0 for the default magnitude.
  - **Signature**: boolean CBaseAnimating::Dissolve(cstring, float, boolean, integer, vector, integer)

### CBaseAnimating::FindBodygroupByName
  - **Description**: Find a bodygroup id by name
  - **Signature**: integer CBaseAnimating::FindBodygroupByName(cstring)

### CBaseAnimating::GetAttachmentAngles
  - **Description**: Get the attachement id's angles as a p,y,r vector
  - **Signature**: qangle CBaseAnimating::GetAttachmentAngles(integer)

### CBaseAnimating::GetAttachmentBone
  - **Description**: Get the named attachement's parent bone index
  - **Signature**: integer CBaseAnimating::GetAttachmentBone(integer)

### CBaseAnimating::GetAttachmentMatrix
  - **Description**: Get the attachement id's matrix transform
  - **Signature**: hscript CBaseAnimating::GetAttachmentMatrix(integer)

### CBaseAnimating::GetAttachmentOrigin
  - **Description**: Get the attachement id's origin vector
  - **Signature**: vector CBaseAnimating::GetAttachmentOrigin(integer)

### CBaseAnimating::GetBodygroup
  - **Description**: Get a bodygroup by id
  - **Signature**: integer CBaseAnimating::GetBodygroup(integer)

### CBaseAnimating::GetBodygroupCount
  - **Description**: Gets the number of models in a bodygroup
  - **Signature**: integer CBaseAnimating::GetBodygroupCount(integer)

### CBaseAnimating::GetBodygroupName
  - **Description**: Get the bodygroup id's name
  - **Signature**: cstring CBaseAnimating::GetBodygroupName(integer)

### CBaseAnimating::GetBodygroupPartName
  - **Description**: Get name by group and part
  - **Signature**: cstring CBaseAnimating::GetBodygroupPartName(integer, integer)

### CBaseAnimating::GetBoneAngles
  - **Description**: Get the bone id's angles as a p,y,r vector
  - **Signature**: qangle CBaseAnimating::GetBoneAngles(integer)

### CBaseAnimating::GetBoneOrigin
  - **Description**: Get the bone id's origin vector
  - **Signature**: vector CBaseAnimating::GetBoneOrigin(integer)

### CBaseAnimating::GetBoneTransform
  - **Description**: Get the transform for the specified bone
  - **Signature**: void CBaseAnimating::GetBoneTransform(integer, hscript)

### CBaseAnimating::GetCycle
  - **Description**: Gets the models current cycle
  - **Signature**: float CBaseAnimating::GetCycle()

### CBaseAnimating::GetModelScale
  - **Signature**: float CBaseAnimating::GetModelScale()

### CBaseAnimating::GetNumBodyGroups
  - **Description**: Gets the number of bodygroups
  - **Signature**: integer CBaseAnimating::GetNumBodyGroups()

### CBaseAnimating::GetNumBones
  - **Description**: Get the number of bones
  - **Signature**: integer CBaseAnimating::GetNumBones()

### CBaseAnimating::GetPhysicsBone
  - **Description**: Get physics bone from bone index
  - **Signature**: integer CBaseAnimating::GetPhysicsBone(integer)

### CBaseAnimating::GetPlaybackRate
  - **Description**: Set the current playback rate.
  - **Signature**: float CBaseAnimating::GetPlaybackRate()

### CBaseAnimating::GetPoseParameter
  - **Description**: Get the specified pose parameter's value
  - **Signature**: float CBaseAnimating::GetPoseParameter(integer)

### CBaseAnimating::GetSequence
  - **Description**: Get the current sequence id
  - **Signature**: integer CBaseAnimating::GetSequence()

### CBaseAnimating::GetSequenceActivity
  - **Description**: Gets the activity ID of the specified sequence index
  - **Signature**: integer CBaseAnimating::GetSequenceActivity(integer)

### CBaseAnimating::GetSequenceActivityName
  - **Description**: Get the activity name for a sequence by id
  - **Signature**: cstring CBaseAnimating::GetSequenceActivityName(integer)

### CBaseAnimating::GetSequenceDuration
  - **Description**: Get a sequence duration by id
  - **Signature**: float CBaseAnimating::GetSequenceDuration(integer)

### CBaseAnimating::GetSequenceKeyValues
  - **Description**: Get a KeyValue class instance on the specified sequence
  - **Signature**: hscript CBaseAnimating::GetSequenceKeyValues(integer)

### CBaseAnimating::GetSequenceMoveDist
  - **Description**: Gets the move distance of the specified sequence
  - **Signature**: float CBaseAnimating::GetSequenceMoveDist(integer)

### CBaseAnimating::GetSequenceMoveYaw
  - **Description**: Gets the move yaw of the specified sequence
  - **Signature**: float CBaseAnimating::GetSequenceMoveYaw(integer)

### CBaseAnimating::GetSequenceName
  - **Description**: Get a sequence name by id
  - **Signature**: cstring CBaseAnimating::GetSequenceName(integer)

### CBaseAnimating::GetSkin
  - **Description**: Gets the current skin index.
  - **Signature**: integer CBaseAnimating::GetSkin()

### CBaseAnimating::Ignite
  - **Description**: 'NPCOnly' only lets this fall through if the entity is a NPC and 'CalledByLevelDesigner' determines whether to treat this like the Ignite input or just an internal ignition call.
  - **Signature**: void CBaseAnimating::Ignite(float, boolean, float, boolean)

### CBaseAnimating::IsRagdoll
  - **Signature**: boolean CBaseAnimating::IsRagdoll()

### CBaseAnimating::IsSequenceFinished
  - **Description**: Ask whether the main sequence is done playing
  - **Signature**: boolean CBaseAnimating::IsSequenceFinished()

### CBaseAnimating::LookupActivity
  - **Description**: Get the named activity index
  - **Signature**: integer CBaseAnimating::LookupActivity(cstring)

### CBaseAnimating::LookupAttachment
  - **Description**: Get the named attachement id
  - **Signature**: integer CBaseAnimating::LookupAttachment(cstring)

### CBaseAnimating::LookupBone
  - **Description**: Get the named bone index
  - **Signature**: integer CBaseAnimating::LookupBone(cstring)

### CBaseAnimating::LookupPoseParameter
  - **Description**: Looks up a pose parameter index by name
  - **Signature**: integer CBaseAnimating::LookupPoseParameter(cstring)

### CBaseAnimating::LookupSequence
  - **Description**: Looks up a sequence by sequence name or activity name
  - **Signature**: integer CBaseAnimating::LookupSequence(cstring)

### CBaseAnimating::ResetSequence
  - **Description**: Reset a sequence by id. If the id is different than the current sequence, switch to the new sequence
  - **Signature**: void CBaseAnimating::ResetSequence(integer)

### CBaseAnimating::ResetSequenceInfo
  - **Signature**: void CBaseAnimating::ResetSequenceInfo()

### CBaseAnimating::Scorch
  - **Description**: Makes the entity darker from scorching
  - **Signature**: void CBaseAnimating::Scorch(integer, integer)

### CBaseAnimating::SelectHeaviestSequence
  - **Description**: Selects the sequence with the heaviest weight for the specified activity ID
  - **Signature**: integer CBaseAnimating::SelectHeaviestSequence(integer)

### CBaseAnimating::SelectWeightedSequence
  - **Description**: Selects a sequence for the specified activity ID
  - **Signature**: integer CBaseAnimating::SelectWeightedSequence(integer, integer)

### CBaseAnimating::SequenceDuration
  - **Description**: Get the specified sequence duration
  - **Signature**: float CBaseAnimating::SequenceDuration(integer)

### CBaseAnimating::SequenceHasMovement
  - **Description**: Checks if the specified sequence has movement
  - **Signature**: boolean CBaseAnimating::SequenceHasMovement(integer)

### CBaseAnimating::SequenceLoops
  - **Description**: Does the current sequence loop?
  - **Signature**: boolean CBaseAnimating::SequenceLoops()

### CBaseAnimating::SetBodygroup
  - **Description**: Sets a bodygroup
  - **Signature**: void CBaseAnimating::SetBodygroup(integer, integer)

### CBaseAnimating::SetCycle
  - **Description**: Sets the models current cycle
  - **Signature**: void CBaseAnimating::SetCycle(float)

### CBaseAnimating::SetModelScale
  - **Description**: (scale, change_duration) Changes a model's scale over time
  - **Signature**: void CBaseAnimating::SetModelScale(float, float)

### CBaseAnimating::SetModelSimple
  - **Description**: Set a model for this entity. Matches easier behaviour of the SetModel input, automatically precaches, maintains sequence/cycle if possible.
  - **Signature**: void CBaseAnimating::SetModelSimple(cstring)

### CBaseAnimating::SetPlaybackRate
  - **Description**: Set the current playback rate.
  - **Signature**: void CBaseAnimating::SetPlaybackRate(float)

### CBaseAnimating::SetPoseParameter
  - **Description**: (id, value) Sets a pose parameter value
  - **Signature**: float CBaseAnimating::SetPoseParameter(integer, float)

### CBaseAnimating::SetSequence
  - **Description**: Set a sequence by id
  - **Signature**: void CBaseAnimating::SetSequence(integer)

### CBaseAnimating::SetSkin
  - **Description**: Sets the skin.
  - **Signature**: void CBaseAnimating::SetSkin(integer)

### CBaseAnimating::StopAnimation
  - **Description**: Stop the current animation (same as SetPlaybackRate 0.0)
  - **Signature**: void CBaseAnimating::StopAnimation()

### CBaseAnimating::StudioFrameAdvance
  - **Description**: Advance animation frame to some time in the future with an automatically calculated interval
  - **Signature**: void CBaseAnimating::StudioFrameAdvance()

### CBaseAnimating::StudioFrameAdvanceManual
  - **Description**: Advance animation frame to some time in the future with a manual interval
  - **Signature**: void CBaseAnimating::StudioFrameAdvanceManual(float)

### CBaseAnimatingOverlay::AddGesture
  - **Description**: Adds a new animation layer using the specified activity name.
  - **Signature**: integer CBaseAnimatingOverlay::AddGesture(cstring, boolean)

### CBaseAnimatingOverlay::AddGestureID
  - **Description**: Adds a new animation layer using the specified activity index.
  - **Signature**: integer CBaseAnimatingOverlay::AddGestureID(integer, boolean)

### CBaseAnimatingOverlay::AddGestureSequence
  - **Description**: Adds a new animation layer using the specified activity name.
  - **Signature**: integer CBaseAnimatingOverlay::AddGestureSequence(cstring, boolean)

### CBaseAnimatingOverlay::AddGestureSequenceID
  - **Description**: Adds a new animation layer using the specified sequence index.
  - **Signature**: integer CBaseAnimatingOverlay::AddGestureSequenceID(integer, boolean)

### CBaseAnimatingOverlay::FastRemoveLayer
  - **Description**: Removes the specified layer index immediately.
  - **Signature**: void CBaseAnimatingOverlay::FastRemoveLayer(integer)

### CBaseAnimatingOverlay::FindGestureLayer
  - **Description**: Finds and returns the first active animation layer which uses the specified activity name.
  - **Signature**: integer CBaseAnimatingOverlay::FindGestureLayer(cstring)

### CBaseAnimatingOverlay::FindGestureLayerByID
  - **Description**: Finds and returns the first active animation layer which uses the specified activity index.
  - **Signature**: integer CBaseAnimatingOverlay::FindGestureLayerByID(integer)

### CBaseAnimatingOverlay::GetLayerActivity
  - **Description**: Gets the activity name of the specified layer index.
  - **Signature**: cstring CBaseAnimatingOverlay::GetLayerActivity(integer)

### CBaseAnimatingOverlay::GetLayerActivityID
  - **Description**: Gets the activity index of the specified layer index.
  - **Signature**: integer CBaseAnimatingOverlay::GetLayerActivityID(integer)

### CBaseAnimatingOverlay::GetLayerCycle
  - **Description**: Gets the cycle of the specified layer index.
  - **Signature**: float CBaseAnimatingOverlay::GetLayerCycle(integer)

### CBaseAnimatingOverlay::GetLayerDuration
  - **Description**: Gets the duration of the specified layer index.
  - **Signature**: float CBaseAnimatingOverlay::GetLayerDuration(integer)

### CBaseAnimatingOverlay::GetLayerSequence
  - **Description**: Gets the sequence index of the specified layer index.
  - **Signature**: integer CBaseAnimatingOverlay::GetLayerSequence(integer)

### CBaseAnimatingOverlay::GetLayerWeight
  - **Description**: Gets the weight of the specified layer index.
  - **Signature**: float CBaseAnimatingOverlay::GetLayerWeight(integer)

### CBaseAnimatingOverlay::GetNumAnimOverlays
  - **Description**: Gets the current number of animation layers.
  - **Signature**: integer CBaseAnimatingOverlay::GetNumAnimOverlays()

### CBaseAnimatingOverlay::HasActiveLayer
  - **Description**: Returns true if there is currently an active layer.
  - **Signature**: boolean CBaseAnimatingOverlay::HasActiveLayer()

### CBaseAnimatingOverlay::IsValidLayer
  - **Description**: Returns true if the specified layer index is valid.
  - **Signature**: boolean CBaseAnimatingOverlay::IsValidLayer(integer)

### CBaseAnimatingOverlay::RemoveAllGestures
  - **Description**: Removes all animation layers.
  - **Signature**: void CBaseAnimatingOverlay::RemoveAllGestures()

### CBaseAnimatingOverlay::RemoveLayer
  - **Description**: Removes the specified layer index with the specified kill rate and delay.
  - **Signature**: void CBaseAnimatingOverlay::RemoveLayer(integer, float, float)

### CBaseAnimatingOverlay::SetLayerAutokill
  - **Description**: Sets whether or not the specified layer index should remove itself when it's finished playing.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerAutokill(integer, boolean)

### CBaseAnimatingOverlay::SetLayerBlendIn
  - **Description**: Sets the fade-in of the specified layer index, with the fade being a 0-1 fraction of the cycle.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerBlendIn(integer, float)

### CBaseAnimatingOverlay::SetLayerBlendOut
  - **Description**: Sets the fade-out of the specified layer index, with the fade being a 0-1 fraction of the cycle.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerBlendOut(integer, float)

### CBaseAnimatingOverlay::SetLayerCycle
  - **Description**: Sets the cycle of the specified layer index.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerCycle(integer, float)

### CBaseAnimatingOverlay::SetLayerDuration
  - **Description**: Sets the duration of the specified layer index.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerDuration(integer, float)

### CBaseAnimatingOverlay::SetLayerLooping
  - **Description**: Sets whether or not the specified layer index should loop.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerLooping(integer, boolean)

### CBaseAnimatingOverlay::SetLayerNoEvents
  - **Description**: Sets whether or not the specified layer index should fire animation events.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerNoEvents(integer, boolean)

### CBaseAnimatingOverlay::SetLayerNoRestore
  - **Description**: Sets whether or not the specified layer index should restore after a save is loaded.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerNoRestore(integer, boolean)

### CBaseAnimatingOverlay::SetLayerPlaybackRate
  - **Description**: Sets the playback rate of the specified layer index.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerPlaybackRate(integer, float)

### CBaseAnimatingOverlay::SetLayerWeight
  - **Description**: Sets the weight of the specified layer index.
  - **Signature**: void CBaseAnimatingOverlay::SetLayerWeight(integer, float)

### CBaseCombatCharacter::AddGlowEffect
  - **Signature**: void CBaseCombatCharacter::AddGlowEffect()

### CBaseCombatCharacter::BodyAngles
  - **Description**: Get the body's angles.
  - **Signature**: vector CBaseCombatCharacter::BodyAngles()

### CBaseCombatCharacter::BodyDirection2D
  - **Description**: Get the body's 2D direction.
  - **Signature**: vector CBaseCombatCharacter::BodyDirection2D()

### CBaseCombatCharacter::BodyDirection3D
  - **Description**: Get the body's 3D direction.
  - **Signature**: vector CBaseCombatCharacter::BodyDirection3D()

### CBaseCombatCharacter::DoMuzzleFlash
  - **Description**: Does a muzzle flash.
  - **Signature**: void CBaseCombatCharacter::DoMuzzleFlash()

### CBaseCombatCharacter::DropAllWeapons
  - **Description**: Make the character drop all of its weapons.
  - **Signature**: void CBaseCombatCharacter::DropAllWeapons(boolean)

### CBaseCombatCharacter::DropWeapon
  - **Description**: Make the character drop the specified weapon entity if they own it.
  - **Signature**: void CBaseCombatCharacter::DropWeapon(hscript)

### CBaseCombatCharacter::EntInAimCone
  - **Description**: Check if the specified entity is in the character's aim cone.
  - **Signature**: boolean CBaseCombatCharacter::EntInAimCone(hscript)

### CBaseCombatCharacter::EntInViewCone
  - **Description**: Check if the specified entity is in the character's viewcone.
  - **Signature**: boolean CBaseCombatCharacter::EntInViewCone(hscript)

### CBaseCombatCharacter::EquipWeapon
  - **Description**: Make the character equip the specified weapon entity. If they don't already own the weapon, they will acquire it instantly.
  - **Signature**: void CBaseCombatCharacter::EquipWeapon(hscript)

### CBaseCombatCharacter::EyeDirection2D
  - **Description**: Get the eyes' 2D direction.
  - **Signature**: vector CBaseCombatCharacter::EyeDirection2D()

### CBaseCombatCharacter::EyeDirection3D
  - **Description**: Get the eyes' 3D direction.
  - **Signature**: vector CBaseCombatCharacter::EyeDirection3D()

### CBaseCombatCharacter::FindWeapon
  - **Description**: Find a specific weapon in the character's inventory by its classname.
  - **Signature**: hscript CBaseCombatCharacter::FindWeapon(cstring, integer)

### CBaseCombatCharacter::GetActiveWeapon
  - **Description**: Get the character's active weapon entity.
  - **Signature**: hscript CBaseCombatCharacter::GetActiveWeapon()

### CBaseCombatCharacter::GetAllWeapons
  - **Description**: Get the character's weapon inventory.
  - **Signature**: void CBaseCombatCharacter::GetAllWeapons(hscript)

### CBaseCombatCharacter::GetAmmoCount
  - **Description**: Get the ammo count of the specified ammo type.
  - **Signature**: integer CBaseCombatCharacter::GetAmmoCount(integer)

### CBaseCombatCharacter::GetAttackSpread
  - **Description**: Get the attack spread.
  - **Signature**: vector CBaseCombatCharacter::GetAttackSpread(hscript, hscript)

### CBaseCombatCharacter::GetCurrentWeaponProficiency
  - **Description**: Get the character's current proficiency (accuracy) with their current weapon.
  - **Signature**: integer CBaseCombatCharacter::GetCurrentWeaponProficiency()

### CBaseCombatCharacter::GetLastKnownArea
  - **Description**: Return the last nav area occupied - NULL if unknown
  - **Signature**: hscript CBaseCombatCharacter::GetLastKnownArea()

### CBaseCombatCharacter::GetRelationPriority
  - **Description**: Get a character's relationship priority for a specific entity.
  - **Signature**: integer CBaseCombatCharacter::GetRelationPriority(hscript)

### CBaseCombatCharacter::GetRelationship
  - **Description**: Get a character's relationship to a specific entity.
  - **Signature**: integer CBaseCombatCharacter::GetRelationship(hscript)

### CBaseCombatCharacter::GetSpreadBias
  - **Description**: Get the spread bias.
  - **Signature**: float CBaseCombatCharacter::GetSpreadBias(hscript, hscript)

### CBaseCombatCharacter::GetVehicleEntity
  - **Description**: Get the entity for a character's current vehicle if they're in one.
  - **Signature**: hscript CBaseCombatCharacter::GetVehicleEntity()

### CBaseCombatCharacter::GetWeapon
  - **Description**: Get a specific weapon in the character's inventory.
  - **Signature**: hscript CBaseCombatCharacter::GetWeapon(integer)

### CBaseCombatCharacter::GiveAmmo
  - **Description**: Gives the specified amount of the specified ammo type. The third parameter is whether or not to suppress the ammo pickup sound. Returns the amount of ammo actually given, which is 0 if the player's ammo for this type is already full.
  - **Signature**: integer CBaseCombatCharacter::GiveAmmo(integer, integer, boolean)

### CBaseCombatCharacter::HeadDirection2D
  - **Description**: Get the head's 2D direction.
  - **Signature**: vector CBaseCombatCharacter::HeadDirection2D()

### CBaseCombatCharacter::HeadDirection3D
  - **Description**: Get the head's 3D direction.
  - **Signature**: vector CBaseCombatCharacter::HeadDirection3D()

### CBaseCombatCharacter::InAimCone
  - **Description**: Check if the specified position is in the character's aim cone.
  - **Signature**: boolean CBaseCombatCharacter::InAimCone(vector)

### CBaseCombatCharacter::InViewCone
  - **Description**: Check if the specified position is in the character's viewcone.
  - **Signature**: boolean CBaseCombatCharacter::InViewCone(vector)

### CBaseCombatCharacter::IsGlowEffectActive
  - **Signature**: boolean CBaseCombatCharacter::IsGlowEffectActive()

### CBaseCombatCharacter::LastHitGroup
  - **Description**: Get the last hitgroup.
  - **Signature**: integer CBaseCombatCharacter::LastHitGroup()

### CBaseCombatCharacter::RemoveAmmo
  - **Description**: Removes the specified amount of the specified ammo type.
  - **Signature**: void CBaseCombatCharacter::RemoveAmmo(integer, integer)

### CBaseCombatCharacter::RemoveGlowEffect
  - **Signature**: void CBaseCombatCharacter::RemoveGlowEffect()

### CBaseCombatCharacter::SetAmmoCount
  - **Description**: Set the ammo count of the specified ammo type.
  - **Signature**: void CBaseCombatCharacter::SetAmmoCount(integer, integer)

### CBaseCombatCharacter::SetClassRelationship
  - **Description**: Set a character's relationship with a specific Classify() class.
  - **Signature**: void CBaseCombatCharacter::SetClassRelationship(integer, integer, integer)

### CBaseCombatCharacter::SetGlowColor
  - **Signature**: void CBaseCombatCharacter::SetGlowColor(float, float, float, float)

### CBaseCombatCharacter::SetRelationship
  - **Description**: Set a character's relationship with a specific entity.
  - **Signature**: void CBaseCombatCharacter::SetRelationship(hscript, integer, integer)

### CBaseCombatCharacter::ShootPosition
  - **Description**: Get the character's shoot position.
  - **Signature**: vector CBaseCombatCharacter::ShootPosition()

### CBaseCombatCharacter::WeaponCount
  - **Description**: Get the number of weapons a character possesses.
  - **Signature**: integer CBaseCombatCharacter::WeaponCount()

### CBaseCombatWeapon::AddViewKick
  - **Description**: Applies the weapon's view kick.
  - **Signature**: void CBaseCombatWeapon::AddViewKick()

### CBaseCombatWeapon::AltFiresUnderwater
  - **Description**: Returns true if this weapon can alt-fire underwater.
  - **Signature**: boolean CBaseCombatWeapon::AltFiresUnderwater()

### CBaseCombatWeapon::CanBePickedUpByNPCs
  - **Description**: Check if the weapon can be picked up by NPCs.
  - **Signature**: boolean CBaseCombatWeapon::CanBePickedUpByNPCs()

### CBaseCombatWeapon::CanBeSelected
  - **Description**: Can this weapon be selected
  - **Signature**: boolean CBaseCombatWeapon::CanBeSelected()

### CBaseCombatWeapon::CapabilitiesGet
  - **Description**: Get the capabilities the weapon currently possesses.
  - **Signature**: integer CBaseCombatWeapon::CapabilitiesGet()

### CBaseCombatWeapon::Clip1
  - **Description**: Get the weapon's current primary ammo.
  - **Signature**: integer CBaseCombatWeapon::Clip1()

### CBaseCombatWeapon::Clip2
  - **Description**: Get the weapon's current secondary ammo.
  - **Signature**: integer CBaseCombatWeapon::Clip2()

### CBaseCombatWeapon::FireDuration
  - **Description**: Returns the amount of time that the weapon has sustained firing.
  - **Signature**: float CBaseCombatWeapon::FireDuration()

### CBaseCombatWeapon::FiresUnderwater
  - **Description**: Returns true if this weapon can fire underwater.
  - **Signature**: boolean CBaseCombatWeapon::FiresUnderwater()

### CBaseCombatWeapon::GetBulletSpread
  - **Description**: Returns the weapon's default bullet spread.
  - **Signature**: vector CBaseCombatWeapon::GetBulletSpread()

### CBaseCombatWeapon::GetBulletSpreadForProficiency
  - **Description**: Returns the weapon's bullet spread for the specified proficiency level.
  - **Signature**: vector CBaseCombatWeapon::GetBulletSpreadForProficiency(integer)

### CBaseCombatWeapon::GetDefaultAnimSpeed
  - **Description**: Returns the weapon's default animation speed.
  - **Signature**: float CBaseCombatWeapon::GetDefaultAnimSpeed()

### CBaseCombatWeapon::GetDefaultClip1
  - **Description**: Get the weapon's default primary ammo.
  - **Signature**: integer CBaseCombatWeapon::GetDefaultClip1()

### CBaseCombatWeapon::GetDefaultClip2
  - **Description**: Get the weapon's default secondary ammo.
  - **Signature**: integer CBaseCombatWeapon::GetDefaultClip2()

### CBaseCombatWeapon::GetDrawActivity
  - **Description**: Returns the weapon's draw activity.
  - **Signature**: integer CBaseCombatWeapon::GetDrawActivity()

### CBaseCombatWeapon::GetDroppedModel
  - **Description**: Get the weapon's unique dropped model if it has one.
  - **Signature**: cstring CBaseCombatWeapon::GetDroppedModel()

### CBaseCombatWeapon::GetFireRate
  - **Description**: Get the weapon's firing rate.
  - **Signature**: float CBaseCombatWeapon::GetFireRate()

### CBaseCombatWeapon::GetHandRig
  - **Signature**: integer CBaseCombatWeapon::GetHandRig()

### CBaseCombatWeapon::GetMaxClip1
  - **Description**: Get the weapon's maximum primary ammo.
  - **Signature**: integer CBaseCombatWeapon::GetMaxClip1()

### CBaseCombatWeapon::GetMaxClip2
  - **Description**: Get the weapon's maximum secondary ammo.
  - **Signature**: integer CBaseCombatWeapon::GetMaxClip2()

### CBaseCombatWeapon::GetOwner
  - **Description**: Get the weapon's owner.
  - **Signature**: hscript CBaseCombatWeapon::GetOwner()

### CBaseCombatWeapon::GetPosition
  - **Signature**: integer CBaseCombatWeapon::GetPosition()

### CBaseCombatWeapon::GetPrimaryAmmoType
  - **Description**: Get the weapon's primary ammo type.
  - **Signature**: integer CBaseCombatWeapon::GetPrimaryAmmoType()

### CBaseCombatWeapon::GetPrimaryAttackActivity
  - **Description**: Returns the weapon's primary attack activity.
  - **Signature**: integer CBaseCombatWeapon::GetPrimaryAttackActivity()

### CBaseCombatWeapon::GetPrintName
  - **Signature**: cstring CBaseCombatWeapon::GetPrintName()

### CBaseCombatWeapon::GetSecondaryAmmoType
  - **Description**: Get the weapon's secondary ammo type.
  - **Signature**: integer CBaseCombatWeapon::GetSecondaryAmmoType()

### CBaseCombatWeapon::GetSecondaryAttackActivity
  - **Description**: Returns the weapon's secondary attack activity.
  - **Signature**: integer CBaseCombatWeapon::GetSecondaryAttackActivity()

### CBaseCombatWeapon::GetSlot
  - **Signature**: integer CBaseCombatWeapon::GetSlot()

### CBaseCombatWeapon::GetSubType
  - **Description**: Get the weapon's subtype.
  - **Signature**: integer CBaseCombatWeapon::GetSubType()

### CBaseCombatWeapon::GetViewModel
  - **Description**: Get the weapon's view model.
  - **Signature**: cstring CBaseCombatWeapon::GetViewModel(integer)

### CBaseCombatWeapon::GetViewModelSequenceDuration
  - **Description**: Gets the sequence duration of the current view model animation.
  - **Signature**: float CBaseCombatWeapon::GetViewModelSequenceDuration()

### CBaseCombatWeapon::GetWeaponIdleTime
  - **Description**: Returns the next time WeaponIdle() will run.
  - **Signature**: float CBaseCombatWeapon::GetWeaponIdleTime()

### CBaseCombatWeapon::GetWeight
  - **Description**: Get the weapon's weight.
  - **Signature**: integer CBaseCombatWeapon::GetWeight()

### CBaseCombatWeapon::GetWorldModel
  - **Description**: Get the weapon's world model.
  - **Signature**: cstring CBaseCombatWeapon::GetWorldModel()

### CBaseCombatWeapon::GiveDefaultAmmo
  - **Description**: Fill the weapon back up to default ammo.
  - **Signature**: void CBaseCombatWeapon::GiveDefaultAmmo()

### CBaseCombatWeapon::HasAnyAmmo
  - **Description**: Check if the weapon currently has ammo or doesn't need ammo.
  - **Signature**: boolean CBaseCombatWeapon::HasAnyAmmo()

### CBaseCombatWeapon::HasPrimaryAmmo
  - **Description**: Check if the weapon currently has ammo or doesn't need primary ammo.
  - **Signature**: boolean CBaseCombatWeapon::HasPrimaryAmmo()

### CBaseCombatWeapon::HasSecondaryAmmo
  - **Description**: Check if the weapon currently has ammo or doesn't need secondary ammo.
  - **Signature**: boolean CBaseCombatWeapon::HasSecondaryAmmo()

### CBaseCombatWeapon::HasWeaponIdleTimeElapsed
  - **Description**: Returns true if the idle time has elapsed.
  - **Signature**: boolean CBaseCombatWeapon::HasWeaponIdleTimeElapsed()

### CBaseCombatWeapon::IsAllowedToSwitch
  - **Description**: Are we allowed to switch to this weapon?
  - **Signature**: boolean CBaseCombatWeapon::IsAllowedToSwitch()

### CBaseCombatWeapon::IsViewModelSequenceFinished
  - **Description**: Returns true if the current view model animation is finished.
  - **Signature**: boolean CBaseCombatWeapon::IsViewModelSequenceFinished()

### CBaseCombatWeapon::MinRange1
  - **Description**: Returns the closest this weapon can be used.
  - **Signature**: float CBaseCombatWeapon::MinRange1()

### CBaseCombatWeapon::MinRange2
  - **Description**: Returns the closest this weapon can be used.
  - **Signature**: float CBaseCombatWeapon::MinRange2()

### CBaseCombatWeapon::NextPrimaryAttack
  - **Description**: Returns the next time PrimaryAttack() will run when the player is pressing +ATTACK.
  - **Signature**: float CBaseCombatWeapon::NextPrimaryAttack()

### CBaseCombatWeapon::NextSecondaryAttack
  - **Description**: Returns the next time SecondaryAttack() will run when the player is pressing +ATTACK2.
  - **Signature**: float CBaseCombatWeapon::NextSecondaryAttack()

### CBaseCombatWeapon::PrimaryAttack
  - **Description**: Force a primary attack
  - **Signature**: void CBaseCombatWeapon::PrimaryAttack()

### CBaseCombatWeapon::ReloadsSingly
  - **Description**: Returns true if this weapon reloads 1 round at a time.
  - **Signature**: boolean CBaseCombatWeapon::ReloadsSingly()

### CBaseCombatWeapon::SecondaryAttack
  - **Description**: Force a secondary attack
  - **Signature**: void CBaseCombatWeapon::SecondaryAttack()

### CBaseCombatWeapon::SendWeaponAnim
  - **Description**: Sends a weapon animation.
  - **Signature**: boolean CBaseCombatWeapon::SendWeaponAnim(integer)

### CBaseCombatWeapon::SetAltFiresUnderwater
  - **Description**: Sets whether this weapon can alt-fire underwater.
  - **Signature**: void CBaseCombatWeapon::SetAltFiresUnderwater(boolean)

### CBaseCombatWeapon::SetClip1
  - **Description**: Set the weapon's current primary ammo.
  - **Signature**: void CBaseCombatWeapon::SetClip1(integer)

### CBaseCombatWeapon::SetClip2
  - **Description**: Set the weapon's current secondary ammo.
  - **Signature**: void CBaseCombatWeapon::SetClip2(integer)

### CBaseCombatWeapon::SetCustomViewModel
  - **Description**: Sets a custom view model for this weapon by model name
  - **Signature**: void CBaseCombatWeapon::SetCustomViewModel(cstring)

### CBaseCombatWeapon::SetCustomViewModelModelIndex
  - **Description**: Sets a custom view model for this weapon by modelindex
  - **Signature**: void CBaseCombatWeapon::SetCustomViewModelModelIndex(integer)

### CBaseCombatWeapon::SetFireDuration
  - **Description**: Sets the amount of time that the weapon has sustained firing.
  - **Signature**: void CBaseCombatWeapon::SetFireDuration(float)

### CBaseCombatWeapon::SetFiresUnderwater
  - **Description**: Sets whether this weapon can fire underwater.
  - **Signature**: void CBaseCombatWeapon::SetFiresUnderwater(boolean)

### CBaseCombatWeapon::SetMinRange1
  - **Description**: Sets the closest this weapon can be used.
  - **Signature**: void CBaseCombatWeapon::SetMinRange1(float)

### CBaseCombatWeapon::SetMinRange2
  - **Description**: Sets the closest this weapon can be used.
  - **Signature**: void CBaseCombatWeapon::SetMinRange2(float)

### CBaseCombatWeapon::SetNextPrimaryAttack
  - **Description**: Sets the next time PrimaryAttack() will run when the player is pressing +ATTACK.
  - **Signature**: void CBaseCombatWeapon::SetNextPrimaryAttack(float)

### CBaseCombatWeapon::SetNextSecondaryAttack
  - **Description**: Sets the next time SecondaryAttack() will run when the player is pressing +ATTACK2.
  - **Signature**: void CBaseCombatWeapon::SetNextSecondaryAttack(float)

### CBaseCombatWeapon::SetOwner
  - **Description**: Set the weapon's owner.
  - **Signature**: void CBaseCombatWeapon::SetOwner(hscript)

### CBaseCombatWeapon::SetReloadsSingly
  - **Description**: Sets whether this weapon reloads 1 round at a time.
  - **Signature**: void CBaseCombatWeapon::SetReloadsSingly(boolean)

### CBaseCombatWeapon::SetSubType
  - **Description**: Set the weapon's subtype.
  - **Signature**: void CBaseCombatWeapon::SetSubType(integer)

### CBaseCombatWeapon::SetWeaponIdleTime
  - **Description**: Sets the next time WeaponIdle() will run.
  - **Signature**: void CBaseCombatWeapon::SetWeaponIdleTime(float)

### CBaseCombatWeapon::UsesClipsForAmmo1
  - **Description**: Check if the weapon uses clips for primary ammo.
  - **Signature**: boolean CBaseCombatWeapon::UsesClipsForAmmo1()

### CBaseCombatWeapon::UsesClipsForAmmo2
  - **Description**: Check if the weapon uses clips for secondary ammo.
  - **Signature**: boolean CBaseCombatWeapon::UsesClipsForAmmo2()

### CBaseCombatWeapon::UsesHands
  - **Signature**: boolean CBaseCombatWeapon::UsesHands()

### CBaseCombatWeapon::UsesPrimaryAmmo
  - **Description**: Check if the weapon uses primary ammo.
  - **Signature**: boolean CBaseCombatWeapon::UsesPrimaryAmmo()

### CBaseCombatWeapon::UsesSecondaryAmmo
  - **Description**: Check if the weapon uses secondary ammo.
  - **Signature**: boolean CBaseCombatWeapon::UsesSecondaryAmmo()

### CBaseCombatWeapon::VisibleInWeaponSelection
  - **Description**: Is this weapon visible in weapon selection
  - **Signature**: boolean CBaseCombatWeapon::VisibleInWeaponSelection()

### CBaseCombatWeapon::WeaponClassify
  - **Description**: Returns the weapon's classify class from the WEPCLASS_ constant group
  - **Signature**: integer CBaseCombatWeapon::WeaponClassify()

### CBaseCombatWeapon::WeaponSound
  - **Description**: Plays one of the weapon's sounds.
  - **Signature**: void CBaseCombatWeapon::WeaponSound(integer, float)

### CBaseEntity::AcceptInput
  - **Description**: Generate a synchronous I/O event
  - **Signature**: boolean CBaseEntity::AcceptInput(cstring, cstring, hscript, hscript)

### CBaseEntity::Activate
  - **Signature**: void CBaseEntity::Activate()

### CBaseEntity::AddContext
  - **Description**: Add a response context value
  - **Signature**: void CBaseEntity::AddContext(cstring, cstring, float)

### CBaseEntity::AddEFlags
  - **Signature**: void CBaseEntity::AddEFlags(integer)

### CBaseEntity::AddEffects
  - **Description**: Add effect(s)
  - **Signature**: void CBaseEntity::AddEffects(integer)

### CBaseEntity::AddFlag
  - **Signature**: void CBaseEntity::AddFlag(integer)

### CBaseEntity::AddOutput
  - **Description**: Add an output
  - **Signature**: boolean CBaseEntity::AddOutput(cstring, cstring, cstring, cstring, float, integer)

### CBaseEntity::AddSolidFlags
  - **Signature**: void CBaseEntity::AddSolidFlags(integer)

### CBaseEntity::AddSpawnFlags
  - **Description**: Add spawnflag(s)
  - **Signature**: void CBaseEntity::AddSpawnFlags(integer)

### CBaseEntity::ApplyAbsVelocityImpulse
  - **Description**: Apply a Velocity Impulse
  - **Signature**: void CBaseEntity::ApplyAbsVelocityImpulse(vector)

### CBaseEntity::ApplyLocalAngularVelocityImpulse
  - **Description**: Apply an Ang Velocity Impulse
  - **Signature**: void CBaseEntity::ApplyLocalAngularVelocityImpulse(vector)

### CBaseEntity::BodyTarget
  - **Signature**: vector CBaseEntity::BodyTarget(vector, boolean)

### CBaseEntity::Classify
  - **Description**: Get Class_T class ID (corresponds to the CLASS_ set of constants)
  - **Signature**: integer CBaseEntity::Classify()

### CBaseEntity::ClearEffects
  - **Description**: Clear effect(s)
  - **Signature**: void CBaseEntity::ClearEffects()

### CBaseEntity::ClearFlags
  - **Signature**: void CBaseEntity::ClearFlags()

### CBaseEntity::ClearSolidFlags
  - **Signature**: void CBaseEntity::ClearSolidFlags()

### CBaseEntity::ClearSpawnFlags
  - **Description**: Clear spawnflag(s)
  - **Signature**: void CBaseEntity::ClearSpawnFlags()

### CBaseEntity::ConnectOutput
  - **Description**: Adds an I/O connection that will call the named function when the specified output fires
  - **Signature**: void CBaseEntity::ConnectOutput(cstring, cstring)

### CBaseEntity::Destroy
  - **Signature**: void CBaseEntity::Destroy()

### CBaseEntity::DisableDraw
  - **Description**: Enable drawing (removes EF_NODRAW)
  - **Signature**: void CBaseEntity::DisableDraw()

### CBaseEntity::DisconnectOutput
  - **Description**: Removes a connected script function from an I/O event.
  - **Signature**: void CBaseEntity::DisconnectOutput(cstring, cstring)

### CBaseEntity::DispatchInteraction
  - **Description**: Dispatches an interaction on this entity. See the g_interaction set of constants for more information.
  - **Signature**: boolean CBaseEntity::DispatchInteraction(integer, hscript, hscript)

### CBaseEntity::DispatchSpawn
  - **Description**: Alternative dispatch spawn, same as the one in CEntities, for convenience.
  - **Signature**: void CBaseEntity::DispatchSpawn()

### CBaseEntity::EmitSound
  - **Description**: Plays a sound from this entity.
  - **Signature**: void CBaseEntity::EmitSound(cstring)

### CBaseEntity::EnableDraw
  - **Description**: Disable drawing (sets EF_NODRAW)
  - **Signature**: void CBaseEntity::EnableDraw()

### CBaseEntity::EntityToWorldTransform
  - **Description**: Get the entity's transform
  - **Signature**: hscript CBaseEntity::EntityToWorldTransform()

### CBaseEntity::EyeAngles
  - **Description**: Returns the entity's eye angles
  - **Signature**: qangle CBaseEntity::EyeAngles()

### CBaseEntity::EyePosition
  - **Description**: Get vector to eye position - absolute coords
  - **Signature**: vector CBaseEntity::EyePosition()

### CBaseEntity::FireBullets
  - **Description**: Fire bullets from entity with a given info handle
  - **Signature**: void CBaseEntity::FireBullets(hscript)

### CBaseEntity::FireOutput
  - **Description**: Fire an entity output
  - **Signature**: void CBaseEntity::FireOutput(cstring, hscript, hscript, cstring, float)

### CBaseEntity::FirstMoveChild
  - **Signature**: hscript CBaseEntity::FirstMoveChild()

### CBaseEntity::FollowEntity
  - **Description**: Begin following the specified entity. This makes this entity non-solid, parents it to the target entity, and teleports it to the specified entity's origin. The second parameter is whether or not to use bonemerging while following.
  - **Signature**: void CBaseEntity::FollowEntity(hscript, boolean)

### CBaseEntity::GetAbsAngles
  - **Description**: Get entity pitch, yaw, roll as QAngles
  - **Signature**: qangle CBaseEntity::GetAbsAngles()

### CBaseEntity::GetAbsVelocity
  - **Description**: Returns the current absolute velocity of the entity
  - **Signature**: vector CBaseEntity::GetAbsVelocity()

### CBaseEntity::GetAngles
  - **Description**: !!!LEGACY FOR COMPAT!!! DO NOT USE ME. Get entity pitch, yaw, roll as a vector
  - **Signature**: vector CBaseEntity::GetAngles()

### CBaseEntity::GetAngularVelocity
  - **Description**: Get the local angular velocity - returns a vector of pitch,yaw,roll
  - **Signature**: vector CBaseEntity::GetAngularVelocity()

### CBaseEntity::GetBaseVelocity
  - **Description**: Get Base velocity
  - **Signature**: vector CBaseEntity::GetBaseVelocity()

### CBaseEntity::GetBoundingMaxs
  - **Description**: Get a vector containing max bounds, centered on object
  - **Signature**: vector CBaseEntity::GetBoundingMaxs()

### CBaseEntity::GetBoundingMaxsOriented
  - **Description**: Get a vector containing max bounds, centered on object, taking the object's orientation into account
  - **Signature**: vector CBaseEntity::GetBoundingMaxsOriented()

### CBaseEntity::GetBoundingMins
  - **Description**: Get a vector containing min bounds, centered on object
  - **Signature**: vector CBaseEntity::GetBoundingMins()

### CBaseEntity::GetBoundingMinsOriented
  - **Description**: Get a vector containing min bounds, centered on object, taking the object's orientation into account
  - **Signature**: vector CBaseEntity::GetBoundingMinsOriented()

### CBaseEntity::GetCenter
  - **Description**: Get vector to center of object - absolute coords
  - **Signature**: vector CBaseEntity::GetCenter()

### CBaseEntity::GetClassname
  - **Signature**: cstring CBaseEntity::GetClassname()

### CBaseEntity::GetCollisionGroup
  - **Description**: Get the collision group
  - **Signature**: integer CBaseEntity::GetCollisionGroup()

### CBaseEntity::GetContext
  - **Description**: Get a response context value
  - **Signature**: cstring CBaseEntity::GetContext(cstring)

### CBaseEntity::GetContextCount
  - **Description**: Get the number of response contexts
  - **Signature**: integer CBaseEntity::GetContextCount()

### CBaseEntity::GetContextExpireTime
  - **Description**: Get a response context's expiration time
  - **Signature**: float CBaseEntity::GetContextExpireTime(cstring)

### CBaseEntity::GetContextIndex
  - **Description**: Get a response context at a specific index in the form of a table
  - **Signature**: hscript CBaseEntity::GetContextIndex(integer)

### CBaseEntity::GetDebugName
  - **Description**: If name exists returns name, otherwise returns classname
  - **Signature**: cstring CBaseEntity::GetDebugName()

### CBaseEntity::GetEFlags
  - **Signature**: integer CBaseEntity::GetEFlags()

### CBaseEntity::GetEffects
  - **Description**: Get effects
  - **Signature**: integer CBaseEntity::GetEffects()

### CBaseEntity::GetEntityHandle
  - **Description**: Get the entity as an EHANDLE
  - **Signature**: unknown_variant_type CBaseEntity::GetEntityHandle()

### CBaseEntity::GetEntityIndex
  - **Signature**: integer CBaseEntity::GetEntityIndex()

### CBaseEntity::GetFlags
  - **Signature**: integer CBaseEntity::GetFlags()

### CBaseEntity::GetFollowedEntity
  - **Description**: Get the entity we're following.
  - **Signature**: hscript CBaseEntity::GetFollowedEntity()

### CBaseEntity::GetForwardVector
  - **Description**: Get the forward vector of the entity
  - **Signature**: vector CBaseEntity::GetForwardVector()

### CBaseEntity::GetFriction
  - **Signature**: float CBaseEntity::GetFriction()

### CBaseEntity::GetGravity
  - **Signature**: float CBaseEntity::GetGravity()

### CBaseEntity::GetGroundEntity
  - **Description**: Get the entity we're standing on.
  - **Signature**: hscript CBaseEntity::GetGroundEntity()

### CBaseEntity::GetHealth
  - **Signature**: integer CBaseEntity::GetHealth()

### CBaseEntity::GetKeyValue
  - **Description**: Get a keyvalue
  - **Signature**: cstring CBaseEntity::GetKeyValue(cstring)

### CBaseEntity::GetLocalAngles
  - **Signature**: qangle CBaseEntity::GetLocalAngles()

### CBaseEntity::GetLocalOrigin
  - **Signature**: vector CBaseEntity::GetLocalOrigin()

### CBaseEntity::GetLocalVelocity
  - **Description**: Get Entity relative velocity
  - **Signature**: vector CBaseEntity::GetLocalVelocity()

### CBaseEntity::GetMass
  - **Signature**: float CBaseEntity::GetMass()

### CBaseEntity::GetMaxHealth
  - **Signature**: integer CBaseEntity::GetMaxHealth()

### CBaseEntity::GetMaxOutputDelay
  - **Description**: Get the longest delay for all events attached to an output
  - **Signature**: float CBaseEntity::GetMaxOutputDelay(cstring)

### CBaseEntity::GetModelKeyValues
  - **Description**: Get a KeyValue class instance on this entity's model
  - **Signature**: hscript CBaseEntity::GetModelKeyValues()

### CBaseEntity::GetModelName
  - **Description**: Returns the name of the model
  - **Signature**: cstring CBaseEntity::GetModelName()

### CBaseEntity::GetMoveParent
  - **Description**: If in hierarchy, retrieves the entity's parent
  - **Signature**: hscript CBaseEntity::GetMoveParent()

### CBaseEntity::GetMoveType
  - **Description**: Get the move type
  - **Signature**: integer CBaseEntity::GetMoveType()

### CBaseEntity::GetName
  - **Signature**: cstring CBaseEntity::GetName()

### CBaseEntity::GetOrCreatePrivateScriptScope
  - **Description**: Create and retrieve the script-side data associated with an entity
  - **Signature**: hscript CBaseEntity::GetOrCreatePrivateScriptScope()

### CBaseEntity::GetOrigin
  - **Description**: This is GetAbsOrigin with a funny script name for some reason. Not changing it for legacy compat though.
  - **Signature**: vector CBaseEntity::GetOrigin()

### CBaseEntity::GetOwner
  - **Description**: Gets this entity's owner
  - **Signature**: hscript CBaseEntity::GetOwner()

### CBaseEntity::GetPhysAngularVelocity
  - **Signature**: vector CBaseEntity::GetPhysAngularVelocity()

### CBaseEntity::GetPhysVelocity
  - **Signature**: vector CBaseEntity::GetPhysVelocity()

### CBaseEntity::GetPhysicsObject
  - **Description**: Get the entity's physics object if it has one
  - **Signature**: hscript CBaseEntity::GetPhysicsObject()

### CBaseEntity::GetPreTemplateName
  - **Description**: Get the entity name stripped of template unique decoration
  - **Signature**: cstring CBaseEntity::GetPreTemplateName()

### CBaseEntity::GetRenderAlpha
  - **Description**: Get the render color's alpha value
  - **Signature**: integer CBaseEntity::GetRenderAlpha()

### CBaseEntity::GetRenderColorB
  - **Description**: Get the render color's B value
  - **Signature**: integer CBaseEntity::GetRenderColorB()

### CBaseEntity::GetRenderColorG
  - **Description**: Get the render color's G value
  - **Signature**: integer CBaseEntity::GetRenderColorG()

### CBaseEntity::GetRenderColorR
  - **Description**: Get the render color's R value
  - **Signature**: integer CBaseEntity::GetRenderColorR()

### CBaseEntity::GetRenderColorVector
  - **Description**: Get the render color as a vector
  - **Signature**: vector CBaseEntity::GetRenderColorVector()

### CBaseEntity::GetRenderMode
  - **Description**: Get render mode
  - **Signature**: integer CBaseEntity::GetRenderMode()

### CBaseEntity::GetRightVector
  - **Description**: Get the right vector of the entity
  - **Signature**: vector CBaseEntity::GetRightVector()

### CBaseEntity::GetRootMoveParent
  - **Description**: If in hierarchy, walks up the hierarchy to find the root parent
  - **Signature**: hscript CBaseEntity::GetRootMoveParent()

### CBaseEntity::GetScriptId
  - **Description**: Retrieve the unique identifier used to refer to the entity within the scripting system
  - **Signature**: cstring CBaseEntity::GetScriptId()

### CBaseEntity::GetScriptScope
  - **Description**: Retrieve the script-side data associated with an entity
  - **Signature**: hscript CBaseEntity::GetScriptScope()

### CBaseEntity::GetScriptThinkFunc
  - **Description**: Retrieve the name of the current script think func
  - **Signature**: cstring CBaseEntity::GetScriptThinkFunc()

### CBaseEntity::GetSolid
  - **Signature**: integer CBaseEntity::GetSolid()

### CBaseEntity::GetSoundDuration
  - **Description**: Returns float duration of the sound. Takes soundname and optional actormodelname.
  - **Signature**: float CBaseEntity::GetSoundDuration(cstring, cstring)

### CBaseEntity::GetSpawnFlags
  - **Description**: Get spawnflags
  - **Signature**: integer CBaseEntity::GetSpawnFlags()

### CBaseEntity::GetTakeDamage
  - **Description**: Gets this entity's m_takedamage value. (DAMAGE_YES, DAMAGE_NO, etc.)
  - **Signature**: integer CBaseEntity::GetTakeDamage()

### CBaseEntity::GetTeam
  - **Signature**: integer CBaseEntity::GetTeam()

### CBaseEntity::GetTransmitState
  - **Signature**: integer CBaseEntity::GetTransmitState()

### CBaseEntity::GetUpVector
  - **Description**: Get the up vector of the entity
  - **Signature**: vector CBaseEntity::GetUpVector()

### CBaseEntity::GetVelocity
  - **Description**: !!!LEGACY FOR COMPAT!!! Use GetAbsVelocity
  - **Signature**: vector CBaseEntity::GetVelocity()

### CBaseEntity::GetWaterLevel
  - **Description**: Get current level of water submergence
  - **Signature**: integer CBaseEntity::GetWaterLevel()

### CBaseEntity::GetWaterType
  - **Signature**: integer CBaseEntity::GetWaterType()

### CBaseEntity::HasSpawnFlags
  - **Description**: Check if the entity has specific spawnflag(s) ticked
  - **Signature**: boolean CBaseEntity::HasSpawnFlags(integer)

### CBaseEntity::HeadTarget
  - **Signature**: vector CBaseEntity::HeadTarget(vector)

### CBaseEntity::IsAlive
  - **Signature**: boolean CBaseEntity::IsAlive()

### CBaseEntity::IsCombatCharacter
  - **Description**: Returns true if this entity is a combat character (player or NPC).
  - **Signature**: boolean CBaseEntity::IsCombatCharacter()

### CBaseEntity::IsEFlagSet
  - **Signature**: boolean CBaseEntity::IsEFlagSet(integer)

### CBaseEntity::IsEffectActive
  - **Description**: Check if an effect is active
  - **Signature**: boolean CBaseEntity::IsEffectActive(integer)

### CBaseEntity::IsEntVisible
  - **Description**: Check if the specified entity can be visible to this entity.
  - **Signature**: boolean CBaseEntity::IsEntVisible(hscript)

### CBaseEntity::IsFollowingEntity
  - **Description**: Returns true if this entity is following another entity.
  - **Signature**: boolean CBaseEntity::IsFollowingEntity()

### CBaseEntity::IsNPC
  - **Description**: Returns true if this entity is a NPC.
  - **Signature**: boolean CBaseEntity::IsNPC()

### CBaseEntity::IsPlayer
  - **Signature**: boolean CBaseEntity::IsPlayer()

### CBaseEntity::IsSolid
  - **Signature**: boolean CBaseEntity::IsSolid()

### CBaseEntity::IsSolidFlagSet
  - **Signature**: boolean CBaseEntity::IsSolidFlagSet(integer)

### CBaseEntity::IsVisible
  - **Description**: Check if the specified position can be visible to this entity.
  - **Signature**: boolean CBaseEntity::IsVisible(vector)

### CBaseEntity::IsVisibleWithMask
  - **Description**: Check if the specified position can be visible to this entity with a specific trace mask.
  - **Signature**: boolean CBaseEntity::IsVisibleWithMask(vector, integer)

### CBaseEntity::IsWeapon
  - **Description**: Returns true if this entity is a weapon.
  - **Signature**: boolean CBaseEntity::IsWeapon()

### CBaseEntity::IsWorld
  - **Description**: Returns true if this entity is the world.
  - **Signature**: boolean CBaseEntity::IsWorld()

### CBaseEntity::KeyValueFromFloat
  - **Description**: Executes KeyValue with a float
  - **Signature**: boolean CBaseEntity::KeyValueFromFloat(cstring, float)

### CBaseEntity::KeyValueFromInt
  - **Description**: Executes KeyValue with an int
  - **Signature**: boolean CBaseEntity::KeyValueFromInt(cstring, integer)

### CBaseEntity::KeyValueFromString
  - **Description**: Executes KeyValue with a string
  - **Signature**: boolean CBaseEntity::KeyValueFromString(cstring, cstring)

### CBaseEntity::KeyValueFromVector
  - **Description**: Executes KeyValue with a vector
  - **Signature**: boolean CBaseEntity::KeyValueFromVector(cstring, vector)

### CBaseEntity::Kill
  - **Signature**: void CBaseEntity::Kill()

### CBaseEntity::LocalEyeAngles
  - **Description**: Returns the entity's local eye angles
  - **Signature**: qangle CBaseEntity::LocalEyeAngles()

### CBaseEntity::NextMovePeer
  - **Signature**: hscript CBaseEntity::NextMovePeer()

### CBaseEntity::PhysicsDestroyObject
  - **Description**: Destroys the entity's physics object
  - **Signature**: void CBaseEntity::PhysicsDestroyObject()

### CBaseEntity::PhysicsInitNormal
  - **Description**: Initializes the entity's physics object with the specified solid type, solid flags, and whether to start asleep
  - **Signature**: void CBaseEntity::PhysicsInitNormal(integer, integer, boolean)

### CBaseEntity::PrecacheModel
  - **Signature**: void CBaseEntity::PrecacheModel(cstring)

### CBaseEntity::PrecacheScriptSound
  - **Signature**: void CBaseEntity::PrecacheScriptSound(cstring)

### CBaseEntity::PrecacheSoundScript
  - **Description**: Precache a sound for later playing.
  - **Signature**: void CBaseEntity::PrecacheSoundScript(cstring)

### CBaseEntity::RemoveContext
  - **Description**: Remove a response context
  - **Signature**: void CBaseEntity::RemoveContext(cstring)

### CBaseEntity::RemoveEFlags
  - **Signature**: void CBaseEntity::RemoveEFlags(integer)

### CBaseEntity::RemoveEffects
  - **Description**: Remove effect(s)
  - **Signature**: void CBaseEntity::RemoveEffects(integer)

### CBaseEntity::RemoveFlag
  - **Signature**: void CBaseEntity::RemoveFlag(integer)

### CBaseEntity::RemoveSolidFlags
  - **Signature**: void CBaseEntity::RemoveSolidFlags(integer)

### CBaseEntity::RemoveSpawnFlags
  - **Description**: Remove spawnflag(s)
  - **Signature**: void CBaseEntity::RemoveSpawnFlags(integer)

### CBaseEntity::SetAbsAngles
  - **Description**: Set entity pitch, yaw, roll as QAngles
  - **Signature**: void CBaseEntity::SetAbsAngles(qangle)

### CBaseEntity::SetAbsOrigin
  - **Description**: SetAbsOrigin
  - **Signature**: void CBaseEntity::SetAbsOrigin(vector)

### CBaseEntity::SetAbsVelocity
  - **Description**: Sets the current absolute velocity of the entity
  - **Signature**: void CBaseEntity::SetAbsVelocity(vector)

### CBaseEntity::SetAngles
  - **Description**: !!!LEGACY FOR COMPAT!!! DO NOT USE ME. Set entity pitch, yaw, roll
  - **Signature**: void CBaseEntity::SetAngles(float, float, float)

### CBaseEntity::SetAngularVelocity
  - **Description**: Set the local angular velocity - takes float pitch,yaw,roll velocities
  - **Signature**: void CBaseEntity::SetAngularVelocity(float, float, float)

### CBaseEntity::SetCollisionGroup
  - **Description**: Set the collision group
  - **Signature**: void CBaseEntity::SetCollisionGroup(integer)

### CBaseEntity::SetContextThink
  - **Description**: Set a think function on this entity.
  - **Signature**: void CBaseEntity::SetContextThink(cstring, hscript, float)

### CBaseEntity::SetDrawEnabled
  - **Description**: Enables drawing if you pass true, disables drawing if you pass false.
  - **Signature**: void CBaseEntity::SetDrawEnabled(boolean)

### CBaseEntity::SetEFlags
  - **Signature**: void CBaseEntity::SetEFlags(integer)

### CBaseEntity::SetEffects
  - **Description**: Set effect(s)
  - **Signature**: void CBaseEntity::SetEffects(integer)

### CBaseEntity::SetForwardVector
  - **Description**: Set the orientation of the entity to have this forward vector
  - **Signature**: void CBaseEntity::SetForwardVector(vector)

### CBaseEntity::SetFriction
  - **Signature**: void CBaseEntity::SetFriction(float)

### CBaseEntity::SetGravity
  - **Signature**: void CBaseEntity::SetGravity(float)

### CBaseEntity::SetGroundEntity
  - **Description**: Set the entity we're standing on.
  - **Signature**: void CBaseEntity::SetGroundEntity(hscript)

### CBaseEntity::SetHealth
  - **Signature**: void CBaseEntity::SetHealth(integer)

### CBaseEntity::SetLocalAngles
  - **Signature**: void CBaseEntity::SetLocalAngles(qangle)

### CBaseEntity::SetLocalOrigin
  - **Signature**: void CBaseEntity::SetLocalOrigin(vector)

### CBaseEntity::SetMass
  - **Signature**: void CBaseEntity::SetMass(float)

### CBaseEntity::SetMaxHealth
  - **Signature**: void CBaseEntity::SetMaxHealth(integer)

### CBaseEntity::SetModel
  - **Description**: Set a model for this entity
  - **Signature**: void CBaseEntity::SetModel(cstring)

### CBaseEntity::SetMoveType
  - **Description**: Set the move type
  - **Signature**: void CBaseEntity::SetMoveType(integer, integer)

### CBaseEntity::SetName
  - **Signature**: void CBaseEntity::SetName(cstring)

### CBaseEntity::SetOrigin
  - **Description**: THIS DOESNT CALL SetAbsOrigin IT CALLS Teleport
  - **Signature**: void CBaseEntity::SetOrigin(vector)

### CBaseEntity::SetOriginAngles
  - **Description**: Set both the origin and the angles
  - **Signature**: void CBaseEntity::SetOriginAngles(vector, qangle)

### CBaseEntity::SetOriginAnglesVelocity
  - **Description**: Set the origin, the angles, and the velocity
  - **Signature**: void CBaseEntity::SetOriginAnglesVelocity(vector, qangle, vector)

### CBaseEntity::SetOwner
  - **Description**: Sets this entity's owner
  - **Signature**: void CBaseEntity::SetOwner(hscript)

### CBaseEntity::SetParent
  - **Signature**: void CBaseEntity::SetParent(hscript, cstring)

### CBaseEntity::SetPhysAngularVelocity
  - **Signature**: void CBaseEntity::SetPhysAngularVelocity(vector)

### CBaseEntity::SetPhysVelocity
  - **Signature**: void CBaseEntity::SetPhysVelocity(vector)

### CBaseEntity::SetRenderAlpha
  - **Description**: Set the render color's alpha value
  - **Signature**: void CBaseEntity::SetRenderAlpha(integer)

### CBaseEntity::SetRenderColor
  - **Description**: Set the render color
  - **Signature**: void CBaseEntity::SetRenderColor(integer, integer, integer)

### CBaseEntity::SetRenderColorB
  - **Description**: Set the render color's B value
  - **Signature**: void CBaseEntity::SetRenderColorB(integer)

### CBaseEntity::SetRenderColorG
  - **Description**: Set the render color's G value
  - **Signature**: void CBaseEntity::SetRenderColorG(integer)

### CBaseEntity::SetRenderColorR
  - **Description**: Set the render color's R value
  - **Signature**: void CBaseEntity::SetRenderColorR(integer)

### CBaseEntity::SetRenderColorVector
  - **Description**: Set the render color as a vector
  - **Signature**: void CBaseEntity::SetRenderColorVector(vector)

### CBaseEntity::SetRenderMode
  - **Description**: Set render mode
  - **Signature**: void CBaseEntity::SetRenderMode(integer)

### CBaseEntity::SetSize
  - **Signature**: void CBaseEntity::SetSize(vector, vector)

### CBaseEntity::SetSolid
  - **Signature**: void CBaseEntity::SetSolid(integer)

### CBaseEntity::SetSolidFlags
  - **Signature**: void CBaseEntity::SetSolidFlags(integer)

### CBaseEntity::SetTakeDamage
  - **Description**: Sets this entity's m_takedamage value. (DAMAGE_YES, DAMAGE_NO, etc.)
  - **Signature**: void CBaseEntity::SetTakeDamage(integer)

### CBaseEntity::SetTeam
  - **Signature**: void CBaseEntity::SetTeam(integer)

### CBaseEntity::SetThink
  - **Signature**: void CBaseEntity::SetThink(hscript, float)

### CBaseEntity::SetThinkFunction
  - **Signature**: void CBaseEntity::SetThinkFunction(cstring, float)

### CBaseEntity::SetTransmitState
  - **Signature**: integer CBaseEntity::SetTransmitState(integer)

### CBaseEntity::SetVelocity
  - **Description**: !!!LEGACY FOR COMPAT!!! Use SetAbsVelocity
  - **Signature**: void CBaseEntity::SetVelocity(vector)

### CBaseEntity::SetWaterLevel
  - **Signature**: void CBaseEntity::SetWaterLevel(integer)

### CBaseEntity::SetWaterType
  - **Signature**: void CBaseEntity::SetWaterType(integer)

### CBaseEntity::StopFollowingEntity
  - **Description**: Stops following an entity if we're following one.
  - **Signature**: void CBaseEntity::StopFollowingEntity()

### CBaseEntity::StopSound
  - **Description**: Stops a sound on this entity.
  - **Signature**: void CBaseEntity::StopSound(cstring)

### CBaseEntity::StopThink
  - **Signature**: void CBaseEntity::StopThink()

### CBaseEntity::StopThinkFunction
  - **Signature**: void CBaseEntity::StopThinkFunction()

### CBaseEntity::TakeDamage
  - **Description**: Apply damage to this entity with a given info handle
  - **Signature**: void CBaseEntity::TakeDamage(float, integer, hscript)

### CBaseEntity::TakeDamageCustom
  - **Description**: (hInflictor, hAttacker, hWeapon, vecDamageForce, vecDamagePosition, flDamage, nDamageType, nCustomDamageType)
  - **Signature**: void CBaseEntity::TakeDamageCustom(hscript, hscript, hscript, vector, vector, float, integer, integer)

### CBaseEntity::TakeDamageEx
  - **Description**: (hInflictor, hAttacker, hWeapon, vecDamageForce, vecDamagePosition, flDamage, nDamageType)
  - **Signature**: void CBaseEntity::TakeDamageEx(hscript, hscript, hscript, vector, vector, float, integer)

### CBaseEntity::TakeHealth
  - **Description**: Give this entity health
  - **Signature**: integer CBaseEntity::TakeHealth(float, integer)

### CBaseEntity::Teleport
  - **Description**: Teleports this entity
  - **Signature**: void CBaseEntity::Teleport(boolean, vector, boolean, qangle, boolean, vector)

### CBaseEntity::TerminateScriptScope
  - **Description**: Clear the current script scope for this entity
  - **Signature**: void CBaseEntity::TerminateScriptScope()

### CBaseEntity::ToggleFlag
  - **Signature**: void CBaseEntity::ToggleFlag(integer)

### CBaseEntity::ValidateScriptScope
  - **Description**: Ensure that an entity's script scope has been created
  - **Signature**: boolean CBaseEntity::ValidateScriptScope()

### CBaseEntity::entindex
  - **Signature**: integer CBaseEntity::entindex()

### CBaseFilter::BloodAllowed
  - **Description**: Check if the given caller and damage info allow for the production of blood.
  - **Signature**: boolean CBaseFilter::BloodAllowed(hscript, hscript)

### CBaseFilter::DamageMod
  - **Description**: Mods the damage info with the given caller.
  - **Signature**: boolean CBaseFilter::DamageMod(hscript, hscript)

### CBaseFilter::PassesDamageFilter
  - **Description**: Check if the given caller and damage info pass the damage filter, with the second parameter being a CTakeDamageInfo instance. The caller is the one who requests the filter result; For example, the entity being damaged when using this as a damage filter.
  - **Signature**: boolean CBaseFilter::PassesDamageFilter(hscript, hscript)

### CBaseFilter::PassesFilter
  - **Description**: Check if the given caller and entity pass the filter. The caller is the one who requests the filter result; For example, the entity being damaged when using this as a damage filter.
  - **Signature**: boolean CBaseFilter::PassesFilter(hscript, hscript)

### CBaseFilter::PassesFinalDamageFilter
  - **Description**: Used by filter_damage_redirect to distinguish between standalone filter calls and actually damaging an entity. Returns true if there's no unique behavior. Parameters are identical to PassesDamageFilter.
  - **Signature**: boolean CBaseFilter::PassesFinalDamageFilter(hscript, hscript)

### CBaseFlex::GetCurrentScene
  - **Description**: Returns the instance of the oldest active scene entity (if any).
  - **Signature**: hscript CBaseFlex::GetCurrentScene()

### CBaseFlex::GetSceneByIndex
  - **Description**: Returns the instance of the scene entity at the specified index.
  - **Signature**: hscript CBaseFlex::GetSceneByIndex(integer)

### CBaseFlex::SetViewtarget
  - **Description**: Sets the entity's eye target.
  - **Signature**: void CBaseFlex::SetViewtarget(vector)

### CBaseGrenade::GetBlastForce
  - **Description**: Gets the grenade's blast force override. Grenades which use base damage force calculations return 0,0,0
  - **Signature**: vector CBaseGrenade::GetBlastForce()

### CBaseGrenade::GetDamage
  - **Description**: Gets the grenade's blast damage.
  - **Signature**: float CBaseGrenade::GetDamage()

### CBaseGrenade::GetDamageRadius
  - **Description**: Gets the grenade's blast damage radius.
  - **Signature**: float CBaseGrenade::GetDamageRadius()

### CBaseGrenade::GetOriginalThrower
  - **Description**: Gets the grenade's original thrower after the thrower was changed due to being picked up by a gravity gun or something.
  - **Signature**: hscript CBaseGrenade::GetOriginalThrower()

### CBaseGrenade::GetThrower
  - **Description**: Gets the grenade's thrower.
  - **Signature**: hscript CBaseGrenade::GetThrower()

### CBaseGrenade::GetTimer
  - **Description**: Gets the grenade's detonate time if it has one.
  - **Signature**: float CBaseGrenade::GetTimer()

### CBaseGrenade::GetWarnAITime
  - **Description**: Gets the time at which the grenade will warn/has warned AI.
  - **Signature**: float CBaseGrenade::GetWarnAITime()

### CBaseGrenade::HasWarnedAI
  - **Description**: Whether or not the grenade has issued its DANGER sound to the world sound list yet.
  - **Signature**: boolean CBaseGrenade::HasWarnedAI()

### CBaseGrenade::IsLive
  - **Description**: Whether or not the grenade has issued its DANGER sound to the world sound list yet.
  - **Signature**: boolean CBaseGrenade::IsLive()

### CBaseGrenade::SetDamage
  - **Description**: Sets the grenade's blast damage.
  - **Signature**: void CBaseGrenade::SetDamage(float)

### CBaseGrenade::SetDamageRadius
  - **Description**: Sets the grenade's blast damage radius.
  - **Signature**: void CBaseGrenade::SetDamageRadius(float)

### CBaseGrenade::SetThrower
  - **Description**: Sets the grenade's thrower.
  - **Signature**: void CBaseGrenade::SetThrower(hscript)

### CBasePlayer::DeathCount
  - **Description**: Gets the number of deaths this player has had in a multiplayer game.
  - **Signature**: integer CBasePlayer::DeathCount()

### CBasePlayer::DisableButtons
  - **Description**: Disables the specified button mask.
  - **Signature**: void CBasePlayer::DisableButtons(integer)

### CBasePlayer::EnableButtons
  - **Description**: Enables the specified button mask if it was disabled before.
  - **Signature**: void CBasePlayer::EnableButtons(integer)

### CBasePlayer::FlashlightIsOn
  - **Description**: Returns true if the flashlight is on.
  - **Signature**: integer CBasePlayer::FlashlightIsOn()

### CBasePlayer::FlashlightTurnOff
  - **Description**: Turns off the flashlight.
  - **Signature**: void CBasePlayer::FlashlightTurnOff()

### CBasePlayer::FlashlightTurnOn
  - **Description**: Turns on the flashlight.
  - **Signature**: void CBasePlayer::FlashlightTurnOn()

### CBasePlayer::ForceButtons
  - **Description**: Forces the specified button mask.
  - **Signature**: void CBasePlayer::ForceButtons(integer)

### CBasePlayer::FragCount
  - **Description**: Gets the number of frags (kills) this player has in a multiplayer game.
  - **Signature**: integer CBasePlayer::FragCount()

### CBasePlayer::GetArmor
  - **Description**: Gets the player's armor.
  - **Signature**: integer CBasePlayer::GetArmor()

### CBasePlayer::GetAutoaimVector
  - **Description**: Gets the player's autoaim shooting direction with the specified scale.
  - **Signature**: vector CBasePlayer::GetAutoaimVector(float)

### CBasePlayer::GetAutoaimVectorCustomMaxDist
  - **Description**: Gets the player's autoaim shooting direction with the specified scale and a custom max distance.
  - **Signature**: vector CBasePlayer::GetAutoaimVectorCustomMaxDist(float, float)

### CBasePlayer::GetButtonDisabled
  - **Description**: Gets the player's currently unusable buttons.
  - **Signature**: integer CBasePlayer::GetButtonDisabled()

### CBasePlayer::GetButtonForced
  - **Description**: Gets the player's currently forced buttons.
  - **Signature**: integer CBasePlayer::GetButtonForced()

### CBasePlayer::GetButtonLast
  - **Description**: Gets the player's previously active buttons.
  - **Signature**: integer CBasePlayer::GetButtonLast()

### CBasePlayer::GetButtonPressed
  - **Description**: Gets the player's currently pressed buttons.
  - **Signature**: integer CBasePlayer::GetButtonPressed()

### CBasePlayer::GetButtonReleased
  - **Description**: Gets the player's just-released buttons.
  - **Signature**: integer CBasePlayer::GetButtonReleased()

### CBasePlayer::GetButtons
  - **Description**: Gets the player's active buttons.
  - **Signature**: integer CBasePlayer::GetButtons()

### CBasePlayer::GetExpresser
  - **Description**: Gets a handle for this player's expresser.
  - **Signature**: hscript CBasePlayer::GetExpresser()

### CBasePlayer::GetEyeForward
  - **Description**: Gets the player's forward eye vector.
  - **Signature**: vector CBasePlayer::GetEyeForward()

### CBasePlayer::GetEyeRight
  - **Description**: Gets the player's right eye vector.
  - **Signature**: vector CBasePlayer::GetEyeRight()

### CBasePlayer::GetEyeUp
  - **Description**: Gets the player's up eye vector.
  - **Signature**: vector CBasePlayer::GetEyeUp()

### CBasePlayer::GetFOV
  - **Signature**: integer CBasePlayer::GetFOV()

### CBasePlayer::GetFOVOwner
  - **Description**: Gets current view owner.
  - **Signature**: hscript CBasePlayer::GetFOVOwner()

### CBasePlayer::GetForceLocalDraw
  - **Description**: Gets the state of whether the player is being forced by SetForceLocalDraw to be drawn
  - **Signature**: boolean CBasePlayer::GetForceLocalDraw()

### CBasePlayer::GetHeldObject
  - **Description**: Gets the player's currently held object IF it is being held by a gravity gun. To check for the player's held +USE object, use the standalone GetPlayerHeldEntity function.
  - **Signature**: hscript CBasePlayer::GetHeldObject()

### CBasePlayer::GetNetworkIDString
  - **Description**: Gets the player's network (i.e. Steam) ID.
  - **Signature**: cstring CBasePlayer::GetNetworkIDString()

### CBasePlayer::GetPlayerMaxs
  - **Signature**: unknown_variant_type CBasePlayer::GetPlayerMaxs()

### CBasePlayer::GetPlayerMins
  - **Signature**: unknown_variant_type CBasePlayer::GetPlayerMins()

### CBasePlayer::GetPlayerName
  - **Description**: Gets the player's name.
  - **Signature**: cstring CBasePlayer::GetPlayerName()

### CBasePlayer::GetPotentialUseEntity
  - **Description**: Gets the player's current potential use entity.
  - **Signature**: hscript CBasePlayer::GetPotentialUseEntity()

### CBasePlayer::GetScriptOverlayMaterial
  - **Description**: Gets the current view overlay material
  - **Signature**: cstring CBasePlayer::GetScriptOverlayMaterial()

### CBasePlayer::GetUseEntity
  - **Description**: Gets the player's current use entity.
  - **Signature**: hscript CBasePlayer::GetUseEntity()

### CBasePlayer::GetUserID
  - **Description**: Gets the player's user ID.
  - **Signature**: integer CBasePlayer::GetUserID()

### CBasePlayer::GetViewModel
  - **Description**: Returns the viewmodel of the specified index.
  - **Signature**: hscript CBasePlayer::GetViewModel(integer)

### CBasePlayer::IsConnected
  - **Description**: Returns true if this player is connected.
  - **Signature**: boolean CBasePlayer::IsConnected()

### CBasePlayer::IsDisconnecting
  - **Description**: Returns true if this player is disconnecting.
  - **Signature**: boolean CBasePlayer::IsDisconnecting()

### CBasePlayer::IsNoclipping
  - **Description**: Returns true if the player is in noclip mode.
  - **Signature**: boolean CBasePlayer::IsNoclipping()

### CBasePlayer::IsSuitEquipped
  - **Description**: Returns true if this player had the HEV suit equipped.
  - **Signature**: boolean CBasePlayer::IsSuitEquipped()

### CBasePlayer::SetArmor
  - **Description**: Sets the player's armor.
  - **Signature**: void CBasePlayer::SetArmor(integer)

### CBasePlayer::SetFOV
  - **Description**: Sets player FOV regardless of view owner.
  - **Signature**: void CBasePlayer::SetFOV(integer, float)

### CBasePlayer::SetForceLocalDraw
  - **Description**: Forces the player to be drawn as if they are third person
  - **Signature**: void CBasePlayer::SetForceLocalDraw(boolean)

### CBasePlayer::SetMuzzleFlashTime
  - **Description**: Sets the player's muzzle flash time for AI.
  - **Signature**: void CBasePlayer::SetMuzzleFlashTime(float)

### CBasePlayer::SetScriptOverlayMaterial
  - **Description**: Sets a view overlay material
  - **Signature**: void CBasePlayer::SetScriptOverlayMaterial(cstring)

### CBasePlayer::SetSuitUpdate
  - **Description**: Sets an update for the player's HEV suit.
  - **Signature**: void CBasePlayer::SetSuitUpdate(cstring, integer, integer)

### CBasePlayer::ShouldAutoaim
  - **Description**: Returns true if the player should be autoaiming.
  - **Signature**: boolean CBasePlayer::ShouldAutoaim()

### CBasePlayer::SnapEyeAngles
  - **Description**: Snap the player's eye angles to this.
  - **Signature**: void CBasePlayer::SnapEyeAngles(qangle)

### CBasePlayer::UnforceButtons
  - **Description**: Unforces the specified button mask if it was forced before.
  - **Signature**: void CBasePlayer::UnforceButtons(integer)

### CBasePlayer::ViewPunch
  - **Description**: Punches the player's view with the specified vector.
  - **Signature**: void CBasePlayer::ViewPunch(qangle)

### CBasePlayer::ViewPunchReset
  - **Description**: Reset's the player's view punch
  - **Signature**: void CBasePlayer::ViewPunchReset(float)

### CBasePropDoor::DoorCanClose
  - **Description**: Return true if the door has room to close. Boolean is for whether or not this is an automatic close and not manually triggered by someone.
  - **Signature**: boolean CBasePropDoor::DoorCanClose(boolean)

### CBasePropDoor::DoorCanOpen
  - **Description**: Return true if there are other doors connected to this one.
  - **Signature**: boolean CBasePropDoor::DoorCanOpen()

### CBasePropDoor::GetActivator
  - **Signature**: hscript CBasePropDoor::GetActivator()

### CBasePropDoor::GetDoorList
  - **Description**: Get connected door entity by index.
  - **Signature**: hscript CBasePropDoor::GetDoorList(integer)

### CBasePropDoor::GetDoorListCount
  - **Description**: Get number of connected doors.
  - **Signature**: integer CBasePropDoor::GetDoorListCount()

### CBasePropDoor::GetFullyClosedSound
  - **Signature**: cstring CBasePropDoor::GetFullyClosedSound()

### CBasePropDoor::GetFullyOpenSound
  - **Signature**: cstring CBasePropDoor::GetFullyOpenSound()

### CBasePropDoor::GetLockedSound
  - **Signature**: cstring CBasePropDoor::GetLockedSound()

### CBasePropDoor::GetMovingSound
  - **Signature**: cstring CBasePropDoor::GetMovingSound()

### CBasePropDoor::GetUnlockedSound
  - **Signature**: cstring CBasePropDoor::GetUnlockedSound()

### CBasePropDoor::HasSlaves
  - **Signature**: boolean CBasePropDoor::HasSlaves()

### CBasePropDoor::IsDoorAjar
  - **Signature**: boolean CBasePropDoor::IsDoorAjar()

### CBasePropDoor::IsDoorBlocked
  - **Signature**: boolean CBasePropDoor::IsDoorBlocked()

### CBasePropDoor::IsDoorClosed
  - **Signature**: boolean CBasePropDoor::IsDoorClosed()

### CBasePropDoor::IsDoorClosing
  - **Signature**: boolean CBasePropDoor::IsDoorClosing()

### CBasePropDoor::IsDoorLocked
  - **Signature**: boolean CBasePropDoor::IsDoorLocked()

### CBasePropDoor::IsDoorOpen
  - **Signature**: boolean CBasePropDoor::IsDoorOpen()

### CBasePropDoor::IsDoorOpening
  - **Signature**: boolean CBasePropDoor::IsDoorOpening()

### CBaseTrigger::Disable
  - **Signature**: void CBaseTrigger::Disable()

### CBaseTrigger::Enable
  - **Signature**: void CBaseTrigger::Enable()

### CBaseTrigger::GetTouchedEntityOfType
  - **Description**: Gets the first touching entity which matches the specified class.
  - **Signature**: hscript CBaseTrigger::GetTouchedEntityOfType(cstring)

### CBaseTrigger::GetTouchingEntities
  - **Description**: Gets all entities touching this trigger (and satisfying its criteria). This function copies them to a table with a maximum number of elements.
  - **Signature**: void CBaseTrigger::GetTouchingEntities(hscript)

### CBaseTrigger::IsTouching
  - **Description**: Checks whether the passed entity is touching the trigger.
  - **Signature**: boolean CBaseTrigger::IsTouching(hscript)

### CBaseTrigger::PassesTriggerFilters
  - **Description**: Returns whether a target entity satisfies the trigger's spawnflags, filter, etc.
  - **Signature**: boolean CBaseTrigger::PassesTriggerFilters(hscript)

### CBaseTrigger::PointIsWithin
  - **Description**: Checks if the given vector is within the trigger's volume.
  - **Signature**: boolean CBaseTrigger::PointIsWithin(vector)

### CBaseTrigger::TouchTest
  - **Signature**: void CBaseTrigger::TouchTest()

### CBaseTrigger::UsesFilter
  - **Description**: Returns true if this trigger uses a filter.
  - **Signature**: boolean CBaseTrigger::UsesFilter()

### CConvars::GetBool
  - **Description**: Returns the convar as a bool. May return null if no such convar.
  - **Signature**: boolean CConvars::GetBool(cstring)

### CConvars::GetClientConvarValue
  - **Description**: Get a convar keyvalue for a specified client
  - **Signature**: cstring CConvars::GetClientConvarValue(integer, cstring)

### CConvars::GetCommandClient
  - **Description**: returns the player who issued this console command.
  - **Signature**: hscript CConvars::GetCommandClient()

### CConvars::GetDefaultValue
  - **Description**: Returns the convar's default value as a string. May return null if no such convar.
  - **Signature**: cstring CConvars::GetDefaultValue(cstring)

### CConvars::GetFloat
  - **Description**: Returns the convar as a float. May return null if no such convar.
  - **Signature**: float CConvars::GetFloat(cstring)

### CConvars::GetInt
  - **Description**: Returns the convar as an int. May return null if no such convar.
  - **Signature**: integer CConvars::GetInt(cstring)

### CConvars::GetStr
  - **Description**: Returns the convar as a string. May return null if no such convar.
  - **Signature**: cstring CConvars::GetStr(cstring)

### CConvars::IsConVarOnAllowList
  - **Description**: Checks if the cvar is allowed to be changed.
  - **Signature**: boolean CConvars::IsConVarOnAllowList(cstring)

### CConvars::IsFlagSet
  - **Description**: Returns the convar's flags. May return null if no such convar.
  - **Signature**: boolean CConvars::IsFlagSet(cstring, integer)

### CConvars::RegisterCommand
  - **Description**: register a console command.
  - **Signature**: void CConvars::RegisterCommand(cstring, hscript, cstring, integer)

### CConvars::RegisterConvar
  - **Description**: register a new console variable.
  - **Signature**: void CConvars::RegisterConvar(cstring, cstring, cstring, integer)

### CConvars::SetBool
  - **Description**: Sets the value of the convar as a bool.
  - **Signature**: void CConvars::SetBool(cstring, boolean)

### CConvars::SetChangeCallback
  - **Description**: callback is called with 5 parameters (var, szOldValue, flOldValue, szNewValue, flNewValue)
  - **Signature**: void CConvars::SetChangeCallback(cstring, hscript)

### CConvars::SetCompletionCallback
  - **Description**: callback is called with 3 parameters (cmd, partial, commands), user strings must be appended to 'commands' array
  - **Signature**: void CConvars::SetCompletionCallback(cstring, hscript)

### CConvars::SetFloat
  - **Description**: Sets the value of the convar as a float.
  - **Signature**: void CConvars::SetFloat(cstring, float)

### CConvars::SetInt
  - **Description**: Sets the value of the convar as an int.
  - **Signature**: void CConvars::SetInt(cstring, integer)

### CConvars::SetStr
  - **Description**: Sets the value of the convar as a string.
  - **Signature**: void CConvars::SetStr(cstring, cstring)

### CConvars::SetValue
  - **Description**: Sets the value of the convar with any applicable type.
  - **Signature**: void CConvars::SetValue(cstring, variant)

### CConvars::UnregisterCommand
  - **Description**: unregister a console command.
  - **Signature**: void CConvars::UnregisterCommand(cstring)

### CDebugOverlayScriptHelper::Axis
  - **Description**: Draws an axis. Specify origin + orientation in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Axis(vector, qangle, float, boolean, float)

### CDebugOverlayScriptHelper::Box
  - **Description**: Draws a world-space axis-aligned box. Specify bounds in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Box(vector, vector, vector, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::BoxAngles
  - **Description**: Draws an oriented box at the origin. Specify bounds in local space.
  - **Signature**: void CDebugOverlayScriptHelper::BoxAngles(vector, vector, vector, qangle, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::BoxDirection
  - **Description**: Draw box oriented to a Vector direction
  - **Signature**: void CDebugOverlayScriptHelper::BoxDirection(vector, vector, vector, vector, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::Circle
  - **Description**: Draws a circle. Specify center in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Circle(vector, vector, vector, float, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::CircleOriented
  - **Description**: Draws a circle oriented. Specify center in world space.
  - **Signature**: void CDebugOverlayScriptHelper::CircleOriented(vector, qangle, float, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::ClearAllOverlays
  - **Description**: Clear all debug overlays at once
  - **Signature**: void CDebugOverlayScriptHelper::ClearAllOverlays()

### CDebugOverlayScriptHelper::Cross3D
  - **Description**: Draws a world-aligned cross. Specify origin in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Cross3D(vector, float, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::Cross3DOriented
  - **Description**: Draws an oriented cross. Specify origin in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Cross3DOriented(vector, qangle, float, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::DrawTickMarkedLine
  - **Description**: Draws a dashed line. Specify endpoints in world space.
  - **Signature**: void CDebugOverlayScriptHelper::DrawTickMarkedLine(vector, vector, float, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::EntityBounds
  - **Description**: Draws bounds of an entity
  - **Signature**: void CDebugOverlayScriptHelper::EntityBounds(hscript, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::EntityText
  - **Description**: Draws text on an entity
  - **Signature**: void CDebugOverlayScriptHelper::EntityText(integer, integer, cstring, float, integer, integer, integer, integer)

### CDebugOverlayScriptHelper::EntityTextAtPosition
  - **Description**: Draw entity text overlay at a specific position
  - **Signature**: void CDebugOverlayScriptHelper::EntityTextAtPosition(vector, integer, cstring, float, integer, integer, integer, integer)

### CDebugOverlayScriptHelper::Grid
  - **Description**: Add grid overlay
  - **Signature**: void CDebugOverlayScriptHelper::Grid(vector)

### CDebugOverlayScriptHelper::HorzArrow
  - **Description**: Draws a horizontal arrow. Specify endpoints in world space.
  - **Signature**: void CDebugOverlayScriptHelper::HorzArrow(vector, vector, float, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::Line
  - **Description**: Draws a line between two points
  - **Signature**: void CDebugOverlayScriptHelper::Line(vector, vector, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::ScreenText
  - **Description**: Draws 2D text. Specify coordinates in screen space.
  - **Signature**: void CDebugOverlayScriptHelper::ScreenText(float, float, cstring, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::SetDebugBits
  - **Description**: Set debug bits on entity
  - **Signature**: void CDebugOverlayScriptHelper::SetDebugBits(hscript, integer)

### CDebugOverlayScriptHelper::Sphere
  - **Description**: Draws a wireframe sphere. Specify center in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Sphere(vector, float, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::SweptBox
  - **Description**: Draws a swept box. Specify endpoints in world space and the bounds in local space.
  - **Signature**: void CDebugOverlayScriptHelper::SweptBox(vector, vector, vector, vector, qangle, integer, integer, integer, integer, float)

### CDebugOverlayScriptHelper::Text
  - **Description**: Draws 2D text. Specify origin in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Text(vector, cstring, float)

### CDebugOverlayScriptHelper::Triangle
  - **Description**: Draws a filled triangle. Specify vertices in world space.
  - **Signature**: void CDebugOverlayScriptHelper::Triangle(vector, vector, vector, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::VertArrow
  - **Description**: Draws a vertical arrow. Specify endpoints in world space.
  - **Signature**: void CDebugOverlayScriptHelper::VertArrow(vector, vector, float, integer, integer, integer, integer, boolean, float)

### CDebugOverlayScriptHelper::YawArrow
  - **Description**: Draws a arrow associated with a specific yaw. Specify endpoints in world space.
  - **Signature**: void CDebugOverlayScriptHelper::YawArrow(vector, float, float, float, integer, integer, integer, integer, boolean, float)

### CEconEntity::AddAttribute
  - **Description**: Add an attribute to the entity
  - **Signature**: void CEconEntity::AddAttribute(cstring, float, float)

### CEconEntity::GetAttribute
  - **Description**: Get an attribute float from the entity
  - **Signature**: float CEconEntity::GetAttribute(cstring, float)

### CEconEntity::ReapplyProvision
  - **Description**: Flush any attribute changes we provide onto our owner
  - **Signature**: void CEconEntity::ReapplyProvision()

### CEconEntity::RemoveAttribute
  - **Description**: Remove an attribute to the entity
  - **Signature**: void CEconEntity::RemoveAttribute(cstring)

### CEntities::AddCustomProcedural
  - **Description**: Adds a custom '!' target name. The first parameter is the name of the procedural (which should NOT include the '!'), the second parameter is a function which should support 5 arguments (name, startEntity, searchingEntity, activator, caller), and the third parameter is whether or not this procedural can return multiple entities. Note that these are NOT saved and must be redeclared on restore!
  - **Signature**: void CEntities::AddCustomProcedural(cstring, hscript, boolean)

### CEntities::CreateByClassname
  - **Description**: Creates an entity by classname
  - **Signature**: hscript CEntities::CreateByClassname(cstring)

### CEntities::DisableEntityListening
  - **Description**: Disables the 'OnEntity' hooks.
  - **Signature**: void CEntities::DisableEntityListening()

### CEntities::DispatchSpawn
  - **Description**: Dispatches spawn of an entity!
  - **Signature**: void CEntities::DispatchSpawn(hscript)

### CEntities::EnableEntityListening
  - **Description**: Enables the 'OnEntity' hooks. This function must be called before using them.
  - **Signature**: void CEntities::EnableEntityListening()

### CEntities::FindByClassNearestFacing
  - **Description**: Find the nearest entity along the facing direction from the given origin within the angular threshold with the given classname.
  - **Signature**: hscript CEntities::FindByClassNearestFacing(vector, vector, float, cstring)

### CEntities::FindByClassname
  - **Description**: Find entities by class name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByClassname(hscript, cstring)

### CEntities::FindByClassnameNearest
  - **Description**: Find entities by class name nearest to a point.
  - **Signature**: hscript CEntities::FindByClassnameNearest(cstring, vector, float)

### CEntities::FindByClassnameNearest2D
  - **Description**: Find entities by class name nearest to a point in 2D space.
  - **Signature**: hscript CEntities::FindByClassnameNearest2D(cstring, vector, float)

### CEntities::FindByClassnameWithin
  - **Description**: Find entities by class name within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByClassnameWithin(hscript, cstring, vector, float)

### CEntities::FindByClassnameWithinBox
  - **Description**: Find entities by class name within an AABB. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByClassnameWithinBox(hscript, cstring, vector, vector)

### CEntities::FindByModel
  - **Description**: Find entities by model name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByModel(hscript, cstring)

### CEntities::FindByName
  - **Description**: Find entities by name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByName(hscript, cstring)

### CEntities::FindByNameNearest
  - **Description**: Find entities by name nearest to a point.
  - **Signature**: hscript CEntities::FindByNameNearest(cstring, vector, float)

### CEntities::FindByNameWithin
  - **Description**: Find entities by name within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByNameWithin(hscript, cstring, vector, float)

### CEntities::FindByTarget
  - **Description**: Find entities by targetname. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindByTarget(hscript, cstring)

### CEntities::FindInSphere
  - **Description**: Find entities within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
  - **Signature**: hscript CEntities::FindInSphere(hscript, vector, float)

### CEntities::First
  - **Description**: Begin an iteration over the list of entities
  - **Signature**: hscript CEntities::First()

### CEntities::GetLocalPlayer
  - **Description**: Get local player or listen server host
  - **Signature**: hscript CEntities::GetLocalPlayer()

### CEntities::Next
  - **Description**: Continue an iteration over the list of entities, providing reference to a previously found entity
  - **Signature**: hscript CEntities::Next(hscript)

### CEntities::RemoveCustomProcedural
  - **Description**: Removes a custom '!' target name previously defined with AddCustomProcedural.
  - **Signature**: void CEntities::RemoveCustomProcedural(cstring)

### CEnvEntityMaker::SpawnEntity
  - **Description**: Create an entity at the location of the maker
  - **Signature**: void CEnvEntityMaker::SpawnEntity()

### CEnvEntityMaker::SpawnEntityAtEntityOrigin
  - **Description**: Create an entity at the location of a specified entity instance
  - **Signature**: void CEnvEntityMaker::SpawnEntityAtEntityOrigin(hscript)

### CEnvEntityMaker::SpawnEntityAtLocation
  - **Description**: Create an entity at a specified location and orientaton, orientation is Euler angle in degrees (pitch, yaw, roll)
  - **Signature**: void CEnvEntityMaker::SpawnEntityAtLocation(vector, vector)

### CEnvEntityMaker::SpawnEntityAtNamedEntityOrigin
  - **Description**: Create an entity at the location of a named entity
  - **Signature**: void CEnvEntityMaker::SpawnEntityAtNamedEntityOrigin(cstring)

### CFourWheelVehiclePhysics::BoostTimeLeft
  - **Description**: Gets how much time is left in any current boost.
  - **Signature**: integer CFourWheelVehiclePhysics::BoostTimeLeft()

### CFourWheelVehiclePhysics::DisableMotion
  - **Description**: Disables vehicle motion.
  - **Signature**: void CFourWheelVehiclePhysics::DisableMotion()

### CFourWheelVehiclePhysics::EnableMotion
  - **Description**: Enables vehicle motion.
  - **Signature**: void CFourWheelVehiclePhysics::EnableMotion()

### CFourWheelVehiclePhysics::GetHLSpeed
  - **Description**: Gets HL speed.
  - **Signature**: float CFourWheelVehiclePhysics::GetHLSpeed()

### CFourWheelVehiclePhysics::GetMaxSpeed
  - **Description**: Gets the max speed.
  - **Signature**: integer CFourWheelVehiclePhysics::GetMaxSpeed()

### CFourWheelVehiclePhysics::GetRPM
  - **Description**: Gets the RPM.
  - **Signature**: integer CFourWheelVehiclePhysics::GetRPM()

### CFourWheelVehiclePhysics::GetSpeed
  - **Description**: Gets the speed.
  - **Signature**: integer CFourWheelVehiclePhysics::GetSpeed()

### CFourWheelVehiclePhysics::GetSteering
  - **Description**: Gets the steeering.
  - **Signature**: float CFourWheelVehiclePhysics::GetSteering()

### CFourWheelVehiclePhysics::GetSteeringDegrees
  - **Description**: Gets the degrees of steeering.
  - **Signature**: float CFourWheelVehiclePhysics::GetSteeringDegrees()

### CFourWheelVehiclePhysics::GetThrottle
  - **Description**: Gets the throttle.
  - **Signature**: float CFourWheelVehiclePhysics::GetThrottle()

### CFourWheelVehiclePhysics::HasBoost
  - **Description**: Checks if the vehicle has the ability to boost.
  - **Signature**: boolean CFourWheelVehiclePhysics::HasBoost()

### CFourWheelVehiclePhysics::IsBoosting
  - **Description**: Checks if the vehicle is boosting.
  - **Signature**: boolean CFourWheelVehiclePhysics::IsBoosting()

### CFourWheelVehiclePhysics::IsEngineDisabled
  - **Description**: Checks whether the engine is disabled.
  - **Signature**: boolean CFourWheelVehiclePhysics::IsEngineDisabled()

### CFourWheelVehiclePhysics::SetAction
  - **Description**: Sets the action.
  - **Signature**: void CFourWheelVehiclePhysics::SetAction(float)

### CFourWheelVehiclePhysics::SetBoost
  - **Description**: Sets the boost.
  - **Signature**: void CFourWheelVehiclePhysics::SetBoost(float)

### CFourWheelVehiclePhysics::SetDisableEngine
  - **Description**: Sets whether the engine is disabled.
  - **Signature**: void CFourWheelVehiclePhysics::SetDisableEngine(boolean)

### CFourWheelVehiclePhysics::SetHandbrake
  - **Description**: Sets the handbrake.
  - **Signature**: void CFourWheelVehiclePhysics::SetHandbrake(boolean)

### CFourWheelVehiclePhysics::SetHasBrakePedal
  - **Description**: Sets whether a handbrake pedal exists.
  - **Signature**: void CFourWheelVehiclePhysics::SetHasBrakePedal(boolean)

### CFourWheelVehiclePhysics::SetMaxReverseThrottle
  - **Description**: Sets the max reverse throttle.
  - **Signature**: void CFourWheelVehiclePhysics::SetMaxReverseThrottle(float)

### CFourWheelVehiclePhysics::SetMaxThrottle
  - **Description**: Sets the max throttle.
  - **Signature**: void CFourWheelVehiclePhysics::SetMaxThrottle(float)

### CFourWheelVehiclePhysics::SetSteering
  - **Description**: Sets the steering.
  - **Signature**: void CFourWheelVehiclePhysics::SetSteering(float, float)

### CFourWheelVehiclePhysics::SetSteeringDegrees
  - **Description**: Sets the degrees of steering.
  - **Signature**: void CFourWheelVehiclePhysics::SetSteeringDegrees(float)

### CFourWheelVehiclePhysics::SetThrottle
  - **Description**: Sets the throttle.
  - **Signature**: void CFourWheelVehiclePhysics::SetThrottle(float)

### CFuncTrackTrain::GetFuturePosition
  - **Description**: Get a position on the track x seconds in the future
  - **Signature**: vector CFuncTrackTrain::GetFuturePosition(float, float)

### CGameRules::AllowFlashlight
  - **Description**: Returns true if players are allowed to switch on their flashlight.
  - **Signature**: boolean CGameRules::AllowFlashlight()

### CGameRules::AllowNPCs
  - **Description**: Returns true if NPCs are allowed.
  - **Signature**: boolean CGameRules::AllowNPCs()

### CGameRules::AllowSPRespawn
  - **Signature**: boolean CGameRules::AllowSPRespawn()

### CGameRules::AllowThirdPersonCamera
  - **Description**: Returns true if third-person camera is allowed.
  - **Signature**: boolean CGameRules::AllowThirdPersonCamera()

### CGameRules::Damage_IsTimeBased
  - **Description**: Damage types that are time-based.
  - **Signature**: boolean CGameRules::Damage_IsTimeBased(integer)

### CGameRules::Damage_NoPhysicsForce
  - **Description**: Damage types that don't have to supply a physics force & position.
  - **Signature**: boolean CGameRules::Damage_NoPhysicsForce(integer)

### CGameRules::Damage_ShouldGibCorpse
  - **Description**: Damage types that gib the corpse.
  - **Signature**: boolean CGameRules::Damage_ShouldGibCorpse(integer)

### CGameRules::Damage_ShouldNotBleed
  - **Description**: Damage types that don't make the player bleed.
  - **Signature**: boolean CGameRules::Damage_ShouldNotBleed(integer)

### CGameRules::Damage_ShowOnHUD
  - **Description**: Damage types that have client HUD art.
  - **Signature**: boolean CGameRules::Damage_ShowOnHUD(integer)

### CGameRules::DefaultFOV
  - **Description**: Default player FOV in this game.
  - **Signature**: integer CGameRules::DefaultFOV()

### CGameRules::GetDamageMultiplier
  - **Description**: Ammo type damage multiplier.
  - **Signature**: float CGameRules::GetDamageMultiplier()

### CGameRules::GetGameDescription
  - **Description**: This is the game description that gets seen in server browsers.
  - **Signature**: cstring CGameRules::GetGameDescription()

### CGameRules::GetGameType
  - **Signature**: integer CGameRules::GetGameType()

### CGameRules::GetGameTypeName
  - **Signature**: cstring CGameRules::GetGameTypeName()

### CGameRules::GetSkillLevel
  - **Description**: Returns the game's difficulty/skill level.
  - **Signature**: integer CGameRules::GetSkillLevel()

### CGameRules::InRoundRestart
  - **Description**: Returns true if the round is restarting.
  - **Signature**: boolean CGameRules::InRoundRestart()

### CGameRules::IsCoOp
  - **Signature**: boolean CGameRules::IsCoOp()

### CGameRules::IsDeathmatch
  - **Signature**: boolean CGameRules::IsDeathmatch()

### CGameRules::IsMultiplayer
  - **Description**: Returns true if this is a multiplayer game (like co-op or deathmatch).
  - **Signature**: boolean CGameRules::IsMultiplayer()

### CGameRules::IsSkillLevel
  - **Description**: Returns true if the game is set to the specified difficulty/skill level.
  - **Signature**: boolean CGameRules::IsSkillLevel(integer)

### CGameRules::IsTeamplay
  - **Signature**: boolean CGameRules::IsTeamplay()

### CGameRules::Name
  - **Description**: Gets the name of these rules.
  - **Signature**: cstring CGameRules::Name()

### CGameRules::RefreshSkillData
  - **Signature**: void CGameRules::RefreshSkillData(boolean)

### CGameRules::SetSkillLevel
  - **Description**: Sets the game's difficulty/skill level.
  - **Signature**: void CGameRules::SetSkillLevel(integer)

### CGameRules::ShouldCollide
  - **Description**: Returns whether two collision groups collide with each other in this game.
  - **Signature**: boolean CGameRules::ShouldCollide(integer, integer)

### CGameTrace::AllSolid
  - **Description**: Returns whether the trace is completely within a solid.
  - **Signature**: boolean CGameTrace::AllSolid()

### CGameTrace::Contents
  - **Description**: Gets the contents of the surface the trace has hit.
  - **Signature**: integer CGameTrace::Contents()

### CGameTrace::DidHit
  - **Description**: Returns whether the trace hit anything.
  - **Signature**: boolean CGameTrace::DidHit()

### CGameTrace::DidHitNonWorldEntity
  - **Description**: Returns whether the trace hit something other than the world entity.
  - **Signature**: boolean CGameTrace::DidHitNonWorldEntity()

### CGameTrace::DidHitWorld
  - **Description**: Returns whether the trace hit the world entity or not.
  - **Signature**: boolean CGameTrace::DidHitWorld()

### CGameTrace::DispFlags
  - **Description**: Gets the displacement flags of the surface the trace has hit.
  - **Signature**: integer CGameTrace::DispFlags()

### CGameTrace::EndPos
  - **Description**: Gets the trace's end position.
  - **Signature**: vector CGameTrace::EndPos()

### CGameTrace::Entity
  - **Description**: Returns the entity this trace has hit.
  - **Signature**: hscript CGameTrace::Entity()

### CGameTrace::Fraction
  - **Description**: Gets the fraction of the trace completed. For example, if the trace stopped exactly halfway to the end position, this would be 0.5.
  - **Signature**: float CGameTrace::Fraction()

### CGameTrace::FractionLeftSolid
  - **Description**: If this trace started within a solid, this is the point in the trace's fraction at which it left that solid.
  - **Signature**: float CGameTrace::FractionLeftSolid()

### CGameTrace::GetEntityIndex
  - **Description**: Returns the index of whatever entity this trace hit.
  - **Signature**: integer CGameTrace::GetEntityIndex()

### CGameTrace::HitBox
  - **Description**: Returns the hitbox of the entity this trace has hit. If it hit the world entity, this returns the static prop index.
  - **Signature**: integer CGameTrace::HitBox()

### CGameTrace::HitGroup
  - **Description**: Returns the specific hit group this trace hit if it hit an entity.
  - **Signature**: integer CGameTrace::HitGroup()

### CGameTrace::IsDispSurface
  - **Description**: Returns whether this trace hit a displacement.
  - **Signature**: boolean CGameTrace::IsDispSurface()

### CGameTrace::IsDispSurfaceBuildable
  - **Description**: Returns whether DISPSURF_FLAG_BUILDABLE is ticked on the displacement this trace hit.
  - **Signature**: boolean CGameTrace::IsDispSurfaceBuildable()

### CGameTrace::IsDispSurfaceProp1
  - **Description**: Returns whether DISPSURF_FLAG_SURFPROP1 is ticked on the displacement this trace hit.
  - **Signature**: boolean CGameTrace::IsDispSurfaceProp1()

### CGameTrace::IsDispSurfaceProp2
  - **Description**: Returns whether DISPSURF_FLAG_SURFPROP2 is ticked on the displacement this trace hit.
  - **Signature**: boolean CGameTrace::IsDispSurfaceProp2()

### CGameTrace::IsDispSurfaceWalkable
  - **Description**: Returns whether DISPSURF_FLAG_WALKABLE is ticked on the displacement this trace hit.
  - **Signature**: boolean CGameTrace::IsDispSurfaceWalkable()

### CGameTrace::PhysicsBone
  - **Description**: Returns the physics bone this trace hit if it hit an entity.
  - **Signature**: integer CGameTrace::PhysicsBone()

### CGameTrace::Plane
  - **Signature**: hscript CGameTrace::Plane()

### CGameTrace::StartPos
  - **Description**: Gets the trace's start position.
  - **Signature**: vector CGameTrace::StartPos()

### CGameTrace::StartSolid
  - **Description**: Returns whether the trace started within a solid.
  - **Signature**: boolean CGameTrace::StartSolid()

### CGameTrace::Surface
  - **Signature**: hscript CGameTrace::Surface()

### CGlobalState::AddGlobal
  - **Description**: Adds a new global with a specific map name and state. Returns its index.
  - **Signature**: integer CGlobalState::AddGlobal(cstring, cstring, integer)

### CGlobalState::AddToCounter
  - **Description**: Adds to the counter of the specified global.
  - **Signature**: integer CGlobalState::AddToCounter(integer, integer)

### CGlobalState::GetCounter
  - **Description**: Gets the counter of the specified global.
  - **Signature**: integer CGlobalState::GetCounter(integer)

### CGlobalState::GetIndex
  - **Description**: Gets the index of the specified global name. Returns -1 if it does not exist.
  - **Signature**: integer CGlobalState::GetIndex(cstring)

### CGlobalState::GetState
  - **Description**: Gets the state of the specified global.
  - **Signature**: integer CGlobalState::GetState(integer)

### CGlobalState::SetCounter
  - **Description**: Sets the counter of the specified global.
  - **Signature**: void CGlobalState::SetCounter(integer, integer)

### CGlobalState::SetState
  - **Description**: Sets the state of the specified global.
  - **Signature**: void CGlobalState::SetState(integer, integer)

### CGlobalSys::CommandLineCheck
  - **Description**: returns true if the command line param was used, otherwise false.
  - **Signature**: boolean CGlobalSys::CommandLineCheck(cstring)

### CGlobalSys::CommandLineCheckFloat
  - **Description**: returns the command line param as a float.
  - **Signature**: float CGlobalSys::CommandLineCheckFloat(cstring)

### CGlobalSys::CommandLineCheckInt
  - **Description**: returns the command line param as an int.
  - **Signature**: integer CGlobalSys::CommandLineCheckInt(cstring)

### CGlobalSys::CommandLineCheckStr
  - **Description**: returns the command line param as a string.
  - **Signature**: cstring CGlobalSys::CommandLineCheckStr(cstring)

### CGlobalSys::GetCommandLine
  - **Description**: returns the command line
  - **Signature**: cstring CGlobalSys::GetCommandLine()

### CLocalize::AddStringAsUTF8
  - **Description**: Adds a new localized token as a UTF-8 string (not Unicode).
  - **Signature**: void CLocalize::AddStringAsUTF8(cstring, cstring)

### CLocalize::GetTokenAsUTF8
  - **Description**: Gets the current language's token as a UTF-8 string (not Unicode).
  - **Signature**: cstring CLocalize::GetTokenAsUTF8(cstring)

### CLogicExternalData::GetKeyValueBlock
  - **Description**: Gets the current external data block expressed in CScriptKeyValues.
  - **Signature**: hscript CLogicExternalData::GetKeyValueBlock()

### CLogicExternalData::GetKeyValues
  - **Description**: Gets the external data expressed in CScriptKeyValues.
  - **Signature**: hscript CLogicExternalData::GetKeyValues()

### CLogicExternalData::LoadFile
  - **Description**: Loads external data from the external file.
  - **Signature**: void CLogicExternalData::LoadFile()

### CLogicExternalData::SaveFile
  - **Description**: Saves the external data to the external file.
  - **Signature**: void CLogicExternalData::SaveFile()

### CLogicExternalData::SetKeyValueBlock
  - **Description**: Sets the current external data block from a CScriptKeyValues object.
  - **Signature**: void CLogicExternalData::SetKeyValueBlock(hscript)

### CLogicExternalData::SetKeyValues
  - **Description**: Sets the external data from a CScriptKeyValues object.
  - **Signature**: void CLogicExternalData::SetKeyValues(hscript)

### CMapbaseSystem::AddManifestFile
  - **Description**: Loads a manifest file.
  - **Signature**: void CMapbaseSystem::AddManifestFile(cstring)

### CMapbaseSystem::GetModName
  - **Description**: Gets the name of the mod. This is the name which shows up on Steam, RPC, etc.
  - **Signature**: cstring CMapbaseSystem::GetModName()

### CMapbaseSystem::IsCoreMapbase
  - **Description**: Indicates whether this is one of the original Mapbase mods or just a separate mod using its code.
  - **Signature**: boolean CMapbaseSystem::IsCoreMapbase()

### CMapbaseSystem::LoadCustomActbusyFile
  - **Description**: Loads a custom actbusy file.
  - **Signature**: void CMapbaseSystem::LoadCustomActbusyFile(cstring)

### CMapbaseSystem::LoadCustomChoreoSentenceFile
  - **Description**: Loads a custom choreo sentence file.
  - **Signature**: void CMapbaseSystem::LoadCustomChoreoSentenceFile(cstring)

### CMapbaseSystem::LoadCustomLocalizationFile
  - **Description**: Loads a custom localization file.
  - **Signature**: void CMapbaseSystem::LoadCustomLocalizationFile(cstring)

### CMapbaseSystem::LoadCustomSoundscriptFile
  - **Description**: Loads a custom soundscript file.
  - **Signature**: void CMapbaseSystem::LoadCustomSoundscriptFile(cstring)

### CMapbaseSystem::LoadCustomSurfacePropsFile
  - **Description**: Loads a custom surface properties file.
  - **Signature**: void CMapbaseSystem::LoadCustomSurfacePropsFile(cstring)

### CMapbaseSystem::LoadCustomTalkerFile
  - **Description**: Loads a custom talker file.
  - **Signature**: void CMapbaseSystem::LoadCustomTalkerFile(cstring)

### CNavMesh::FindNavAreaAlongRay
  - **Description**: Arguments: ( startpos, endpos, ignoreAreaID ) - get nav area from ray
  - **Signature**: hscript CNavMesh::FindNavAreaAlongRay(vector, vector, hscript)

### CNavMesh::GetAllAreas
  - **Description**: Arguments: ( table ) - fills a passed in table of all nav areas
  - **Signature**: void CNavMesh::GetAllAreas(hscript)

### CNavMesh::GetAreasWithAttributes
  - **Description**: Arguments: ( bits, table ) - fills a passed in table of all nav areas that have the specified attributes
  - **Signature**: void CNavMesh::GetAreasWithAttributes(integer, hscript)

### CNavMesh::GetNavArea
  - **Description**: Arguments: ( origin, flBeneath ) - given a position in the world, return the nav area that is closest to or below that height.
  - **Signature**: hscript CNavMesh::GetNavArea(vector, float)

### CNavMesh::GetNavAreaByID
  - **Description**: Arguments: ( areaID ) - get nav area by ID
  - **Signature**: hscript CNavMesh::GetNavAreaByID(integer)

### CNavMesh::GetNavAreaCount
  - **Description**: return total number of nav areas
  - **Signature**: integer CNavMesh::GetNavAreaCount()

### CNavMesh::GetNavAreasFromBuildPath
  - **Description**: Arguments: ( table ) - Fills the table with areas from a path. Returns whether a path was found
  - **Signature**: boolean CNavMesh::GetNavAreasFromBuildPath(hscript, hscript, vector, float, integer, boolean, hscript)

### CNavMesh::GetNavAreasInRadius
  - **Description**: Arguments: ( origin, radius, table ) - fills a passed in table of nav areas within radius
  - **Signature**: void CNavMesh::GetNavAreasInRadius(vector, float, hscript)

### CNavMesh::GetNavAreasOverlappingEntityExtent
  - **Description**: Arguments: ( entity, table ) - fills passed in table with areas overlapping entity's extent
  - **Signature**: void CNavMesh::GetNavAreasOverlappingEntityExtent(hscript, hscript)

### CNavMesh::GetNearestNavArea
  - **Description**: Arguments: ( origin, maxDist, checkLOS, checkGround ) - given a position in the world, return the nav area that is closest to or below that height.
  - **Signature**: hscript CNavMesh::GetNearestNavArea(vector, float, boolean, boolean)

### CNavMesh::GetObstructingEntities
  - **Description**: Arguments: ( table ) - fills a passed in table of all obstructing entities
  - **Signature**: void CNavMesh::GetObstructingEntities(hscript)

### CNavMesh::NavAreaBuildPath
  - **Description**: Arguments: ( area, area, goalPos, flMaxPathLength, teamID, ignoreNavBlockers ) - returns true if a path exists
  - **Signature**: boolean CNavMesh::NavAreaBuildPath(hscript, hscript, vector, float, integer, boolean)

### CNavMesh::NavAreaTravelDistance
  - **Description**: Arguments: ( area, area, flMaxPathLength ) - compute distance between two areas. Return -1 if can't reach 'endArea' from 'startArea'
  - **Signature**: float CNavMesh::NavAreaTravelDistance(hscript, hscript, float)

### CNavMesh::RegisterAvoidanceObstacle
  - **Description**: Arguments: ( entity ) - registers avoidance obstacle
  - **Signature**: void CNavMesh::RegisterAvoidanceObstacle(hscript)

### CNavMesh::UnregisterAvoidanceObstacle
  - **Description**: Arguments: ( entity ) - unregisters avoidance obstacle
  - **Signature**: void CNavMesh::UnregisterAvoidanceObstacle(hscript)

### CNetMsg::GetNumBitsWritten
  - **Signature**: integer CNetMsg::GetNumBitsWritten()

### CNetMsg::ReadAngle
  - **Signature**: float CNetMsg::ReadAngle()

### CNetMsg::ReadAngles
  - **Signature**: qangle CNetMsg::ReadAngles()

### CNetMsg::ReadBool
  - **Signature**: boolean CNetMsg::ReadBool()

### CNetMsg::ReadByte
  - **Signature**: integer CNetMsg::ReadByte()

### CNetMsg::ReadChar
  - **Signature**: integer CNetMsg::ReadChar()

### CNetMsg::ReadCoord
  - **Signature**: float CNetMsg::ReadCoord()

### CNetMsg::ReadEHandle
  - **Signature**: hscript CNetMsg::ReadEHandle()

### CNetMsg::ReadEntity
  - **Signature**: hscript CNetMsg::ReadEntity()

### CNetMsg::ReadFloat
  - **Signature**: float CNetMsg::ReadFloat()

### CNetMsg::ReadInt
  - **Signature**: integer CNetMsg::ReadInt(integer)

### CNetMsg::ReadLong
  - **Signature**: integer CNetMsg::ReadLong()

### CNetMsg::ReadNormal
  - **Signature**: float CNetMsg::ReadNormal()

### CNetMsg::ReadShort
  - **Signature**: integer CNetMsg::ReadShort()

### CNetMsg::ReadString
  - **Signature**: cstring CNetMsg::ReadString()

### CNetMsg::ReadUInt
  - **Signature**: integer CNetMsg::ReadUInt(integer)

### CNetMsg::ReadVec3Coord
  - **Signature**: vector CNetMsg::ReadVec3Coord()

### CNetMsg::ReadVec3Normal
  - **Signature**: vector CNetMsg::ReadVec3Normal()

### CNetMsg::ReadWord
  - **Signature**: integer CNetMsg::ReadWord()

### CNetMsg::Receive
  - **Description**: Set custom network message callback
  - **Signature**: void CNetMsg::Receive(cstring, hscript)

### CNetMsg::Reset
  - **Description**: Reset the current network message buffer
  - **Signature**: void CNetMsg::Reset()

### CNetMsg::Send
  - **Description**: Send a custom network message from the server to the client (max 251 bytes)
  - **Signature**: void CNetMsg::Send(hscript, boolean)

### CNetMsg::SendEntityMessage
  - **Description**: Send a message from a server side entity to its client side counterpart
  - **Signature**: void CNetMsg::SendEntityMessage(hscript, boolean)

### CNetMsg::SendUserMessage
  - **Description**: Send a usermessage from the server to the client
  - **Signature**: void CNetMsg::SendUserMessage(hscript, cstring, boolean)

### CNetMsg::Start
  - **Description**: Start writing new custom network message
  - **Signature**: void CNetMsg::Start(cstring)

### CNetMsg::WriteAngle
  - **Description**: 8 bit unsigned char
  - **Signature**: void CNetMsg::WriteAngle(float)

### CNetMsg::WriteAngles
  - **Signature**: void CNetMsg::WriteAngles(qangle)

### CNetMsg::WriteBool
  - **Description**: 1 bit
  - **Signature**: void CNetMsg::WriteBool(boolean)

### CNetMsg::WriteByte
  - **Description**: 8 bit unsigned char
  - **Signature**: void CNetMsg::WriteByte(integer)

### CNetMsg::WriteChar
  - **Description**: 8 bit char
  - **Signature**: void CNetMsg::WriteChar(integer)

### CNetMsg::WriteCoord
  - **Signature**: void CNetMsg::WriteCoord(float)

### CNetMsg::WriteEHandle
  - **Description**: 32 bit long
  - **Signature**: void CNetMsg::WriteEHandle(hscript)

### CNetMsg::WriteEntity
  - **Description**: 11 bit (entindex)
  - **Signature**: void CNetMsg::WriteEntity(hscript)

### CNetMsg::WriteFloat
  - **Description**: 32 bit float
  - **Signature**: void CNetMsg::WriteFloat(float)

### CNetMsg::WriteInt
  - **Description**: variable bit signed int
  - **Signature**: void CNetMsg::WriteInt(integer, integer)

### CNetMsg::WriteLong
  - **Description**: 32 bit long
  - **Signature**: void CNetMsg::WriteLong(integer)

### CNetMsg::WriteNormal
  - **Description**: 12 bit
  - **Signature**: void CNetMsg::WriteNormal(float)

### CNetMsg::WriteShort
  - **Description**: 16 bit short
  - **Signature**: void CNetMsg::WriteShort(integer)

### CNetMsg::WriteString
  - **Description**: max 512 bytes at once
  - **Signature**: void CNetMsg::WriteString(cstring)

### CNetMsg::WriteUInt
  - **Description**: variable bit unsigned int
  - **Signature**: void CNetMsg::WriteUInt(integer, integer)

### CNetMsg::WriteVec3Coord
  - **Signature**: void CNetMsg::WriteVec3Coord(vector)

### CNetMsg::WriteVec3Normal
  - **Description**: 27 bit
  - **Signature**: void CNetMsg::WriteVec3Normal(vector)

### CNetMsg::WriteWord
  - **Description**: 16 bit unsigned short
  - **Signature**: void CNetMsg::WriteWord(integer)

### CNetPropManager::GetPropArraySize
  - **Description**: Returns the size of an array.
  - **Signature**: integer CNetPropManager::GetPropArraySize(hscript, cstring)

### CNetPropManager::GetPropEntity
  - **Description**: Reads an entity.
  - **Signature**: hscript CNetPropManager::GetPropEntity(hscript, cstring)

### CNetPropManager::GetPropEntityArray
  - **Description**: Reads an entity from an array.
  - **Signature**: hscript CNetPropManager::GetPropEntityArray(hscript, cstring, integer)

### CNetPropManager::GetPropFloat
  - **Description**: Reads a float.
  - **Signature**: float CNetPropManager::GetPropFloat(hscript, cstring)

### CNetPropManager::GetPropFloatArray
  - **Description**: Reads a float from an array.
  - **Signature**: float CNetPropManager::GetPropFloatArray(hscript, cstring, integer)

### CNetPropManager::GetPropInfo
  - **Description**: Fills in a passed table with property info for the provided entity.
  - **Signature**: boolean CNetPropManager::GetPropInfo(hscript, cstring, integer, hscript)

### CNetPropManager::GetPropInt
  - **Description**: Reads an integer.
  - **Signature**: integer CNetPropManager::GetPropInt(hscript, cstring)

### CNetPropManager::GetPropIntArray
  - **Description**: Reads an integer from an array.
  - **Signature**: integer CNetPropManager::GetPropIntArray(hscript, cstring, integer)

### CNetPropManager::GetPropString
  - **Description**: Reads a string.
  - **Signature**: cstring CNetPropManager::GetPropString(hscript, cstring)

### CNetPropManager::GetPropStringArray
  - **Description**: Reads a string from an array.
  - **Signature**: cstring CNetPropManager::GetPropStringArray(hscript, cstring, integer)

### CNetPropManager::GetPropType
  - **Description**: Returns the netprop type as a string.
  - **Signature**: cstring CNetPropManager::GetPropType(hscript, cstring)

### CNetPropManager::GetPropVector
  - **Description**: Reads a 3D vector.
  - **Signature**: vector CNetPropManager::GetPropVector(hscript, cstring)

### CNetPropManager::GetPropVectorArray
  - **Description**: Reads a 3D vector from an array.
  - **Signature**: vector CNetPropManager::GetPropVectorArray(hscript, cstring, integer)

### CNetPropManager::GetTable
  - **Description**: Fills in a passed table with all props of a specified type for the provided entity (set prop_type to 0 for SendTable or 1 for DataMap).
  - **Signature**: void CNetPropManager::GetTable(hscript, integer, hscript)

### CNetPropManager::HasProp
  - **Description**: Checks if netprop/datafield exists.
  - **Signature**: boolean CNetPropManager::HasProp(hscript, cstring)

### CNetPropManager::SetPropEntity
  - **Description**: Sets an entity.
  - **Signature**: void CNetPropManager::SetPropEntity(hscript, cstring, hscript)

### CNetPropManager::SetPropEntityArray
  - **Description**: Sets an entity in an array.
  - **Signature**: void CNetPropManager::SetPropEntityArray(hscript, cstring, hscript, integer)

### CNetPropManager::SetPropFloat
  - **Description**: Sets to the specified float.
  - **Signature**: void CNetPropManager::SetPropFloat(hscript, cstring, float)

### CNetPropManager::SetPropFloatArray
  - **Description**: Sets a float in an array.
  - **Signature**: void CNetPropManager::SetPropFloatArray(hscript, cstring, float, integer)

### CNetPropManager::SetPropInt
  - **Description**: Sets to the specified integer.
  - **Signature**: void CNetPropManager::SetPropInt(hscript, cstring, integer)

### CNetPropManager::SetPropIntArray
  - **Description**: Sets an integer in an array.
  - **Signature**: void CNetPropManager::SetPropIntArray(hscript, cstring, integer, integer)

### CNetPropManager::SetPropString
  - **Description**: Sets to the specified string.
  - **Signature**: void CNetPropManager::SetPropString(hscript, cstring, cstring)

### CNetPropManager::SetPropStringArray
  - **Description**: Sets a string in an array.
  - **Signature**: void CNetPropManager::SetPropStringArray(hscript, cstring, cstring, integer)

### CNetPropManager::SetPropVector
  - **Description**: Sets to the specified vector.
  - **Signature**: void CNetPropManager::SetPropVector(hscript, cstring, vector)

### CNetPropManager::SetPropVectorArray
  - **Description**: Sets a 3D vector in an array.
  - **Signature**: void CNetPropManager::SetPropVectorArray(hscript, cstring, vector, integer)

### CPlayerVoiceListener::GetPlayerSpeechDuration
  - **Description**: Returns the number of seconds the player has been continuously speaking.
  - **Signature**: float CPlayerVoiceListener::GetPlayerSpeechDuration(integer)

### CPlayerVoiceListener::IsPlayerSpeaking
  - **Description**: Returns whether the player specified is speaking.
  - **Signature**: boolean CPlayerVoiceListener::IsPlayerSpeaking(integer)

### CPointCommentaryNode::AbortPlaying
  - **Description**: Stops playing the node and snaps out of its camera control immediately. The game uses this function to shut down commentary while in the middle of playing a node, as it can't smoothly blend out (since the commentary entities need to be removed).
  - **Signature**: void CPointCommentaryNode::AbortPlaying()

### CPointCommentaryNode::CannotBeStopped
  - **Signature**: boolean CPointCommentaryNode::CannotBeStopped()

### CPointCommentaryNode::GetCommentaryFile
  - **Signature**: cstring CPointCommentaryNode::GetCommentaryFile()

### CPointCommentaryNode::GetCommentaryType
  - **Signature**: integer CPointCommentaryNode::GetCommentaryType()

### CPointCommentaryNode::GetFootnote
  - **Signature**: cstring CPointCommentaryNode::GetFootnote()

### CPointCommentaryNode::GetPrintName
  - **Signature**: cstring CPointCommentaryNode::GetPrintName()

### CPointCommentaryNode::GetSpeakers
  - **Signature**: cstring CPointCommentaryNode::GetSpeakers()

### CPointCommentaryNode::HasViewTarget
  - **Signature**: boolean CPointCommentaryNode::HasViewTarget()

### CPointCommentaryNode::IsActive
  - **Signature**: boolean CPointCommentaryNode::IsActive()

### CPointCommentaryNode::IsDisabled
  - **Signature**: boolean CPointCommentaryNode::IsDisabled()

### CPointCommentaryNode::PreventsMovement
  - **Signature**: boolean CPointCommentaryNode::PreventsMovement()

### CPointCommentaryNode::SetCommentaryFile
  - **Signature**: void CPointCommentaryNode::SetCommentaryFile(cstring)

### CPointCommentaryNode::SetCommentaryType
  - **Signature**: void CPointCommentaryNode::SetCommentaryType(integer)

### CPointCommentaryNode::SetDisabled
  - **Signature**: void CPointCommentaryNode::SetDisabled(boolean)

### CPointCommentaryNode::SetFootnote
  - **Signature**: void CPointCommentaryNode::SetFootnote(cstring)

### CPointCommentaryNode::SetPrintName
  - **Signature**: void CPointCommentaryNode::SetPrintName(cstring)

### CPointCommentaryNode::SetSpeakers
  - **Signature**: void CPointCommentaryNode::SetSpeakers(cstring)

### CPropVehicle::GetPhysics
  - **Description**: Get a vehicle's physics.
  - **Signature**: hscript CPropVehicle::GetPhysics()

### CPropVehicle::GetVehicleType
  - **Description**: Get a vehicle's type.
  - **Signature**: integer CPropVehicle::GetVehicleType()

### CPropVehicleDriveable::GetDriver
  - **Description**: Get a vehicle's driver, which could be either a player or a npc_vehicledriver.
  - **Signature**: hscript CPropVehicleDriveable::GetDriver()

### CPropVehicleDriveable::IsEngineOn
  - **Description**: Check if the engine is on.
  - **Signature**: boolean CPropVehicleDriveable::IsEngineOn()

### CPropVehicleDriveable::IsOverturned
  - **Description**: Check if the vehicle is overturned.
  - **Signature**: boolean CPropVehicleDriveable::IsOverturned()

### CPropVehicleDriveable::IsVehicleBodyInWater
  - **Description**: Check if the vehicle's body is submerged in water.
  - **Signature**: boolean CPropVehicleDriveable::IsVehicleBodyInWater()

### CPropVehicleDriveable::StartEngine
  - **Description**: Start the engine.
  - **Signature**: void CPropVehicleDriveable::StartEngine()

### CPropVehicleDriveable::StopEngine
  - **Description**: Stop the engine.
  - **Signature**: void CPropVehicleDriveable::StopEngine()

### CRagdollProp::GetRagdollObject
  - **Description**: Gets the ragdoll object of the specified index.
  - **Signature**: hscript CRagdollProp::GetRagdollObject(integer)

### CRagdollProp::GetRagdollObjectCount
  - **Description**: Gets the number of ragdoll objects on this ragdoll.
  - **Signature**: integer CRagdollProp::GetRagdollObjectCount()

### CRagdollProp::GetSourceClassName
  - **Description**: Gets the ragdoll's source classname.
  - **Signature**: cstring CRagdollProp::GetSourceClassName()

### CRagdollProp::HasPhysgunInteraction
  - **Description**: Checks if the ragdoll has the specified interaction.
  - **Signature**: boolean CRagdollProp::HasPhysgunInteraction(cstring, cstring)

### CRagdollProp::SetSourceClassName
  - **Description**: Sets the ragdoll's source classname.
  - **Signature**: void CRagdollProp::SetSourceClassName(cstring)

### CSceneEntity::AddBroadcastTeamTarget
  - **Description**: Adds a team (by index) to the broadcast list
  - **Signature**: void CSceneEntity::AddBroadcastTeamTarget(integer)

### CSceneEntity::EstimateLength
  - **Description**: Returns length of this scene in seconds.
  - **Signature**: float CSceneEntity::EstimateLength()

### CSceneEntity::FindNamedEntity
  - **Description**: given an entity reference, such as !target, get actual entity from scene object
  - **Signature**: hscript CSceneEntity::FindNamedEntity(cstring)

### CSceneEntity::IsPaused
  - **Description**: If this scene is currently paused.
  - **Signature**: boolean CSceneEntity::IsPaused()

### CSceneEntity::IsPlayingBack
  - **Description**: If this scene is currently playing.
  - **Signature**: boolean CSceneEntity::IsPlayingBack()

### CSceneEntity::LoadSceneFromString
  - **Description**: given a dummy scene name and a vcd string, load the scene
  - **Signature**: boolean CSceneEntity::LoadSceneFromString(cstring, cstring)

### CSceneEntity::RemoveBroadcastTeamTarget
  - **Description**: Removes a team (by index) from the broadcast list
  - **Signature**: void CSceneEntity::RemoveBroadcastTeamTarget(integer)

### CSceneListManager::GetScene
  - **Description**: Gets the specified scene index from this manager.
  - **Signature**: hscript CSceneListManager::GetScene(integer)

### CScriptEntityOutputs::AddOutput
  - **Description**: Arguments: ( entity, outputName, targetName, inputName, parameter, delay, timesToFire ) - add a new output to the entity
  - **Signature**: void CScriptEntityOutputs::AddOutput(hscript, cstring, cstring, cstring, cstring, float, integer)

### CScriptEntityOutputs::GetNumElements
  - **Description**: Arguments: ( entity, outputName ) - returns the number of array elements
  - **Signature**: integer CScriptEntityOutputs::GetNumElements(hscript, cstring)

### CScriptEntityOutputs::GetOutputTable
  - **Description**: Arguments: ( entity, outputName, table, arrayElement ) - returns a table of output information
  - **Signature**: void CScriptEntityOutputs::GetOutputTable(hscript, cstring, hscript, integer)

### CScriptEntityOutputs::HasAction
  - **Description**: Arguments: ( entity, outputName ) - returns true if an action exists for the output
  - **Signature**: boolean CScriptEntityOutputs::HasAction(hscript, cstring)

### CScriptEntityOutputs::HasOutput
  - **Description**: Arguments: ( entity, outputName ) - returns true if the output exists
  - **Signature**: boolean CScriptEntityOutputs::HasOutput(hscript, cstring)

### CScriptEntityOutputs::RemoveOutput
  - **Description**: Arguments: ( entity, outputName, targetName, inputName, parameter ) - remove an output from the entity
  - **Signature**: void CScriptEntityOutputs::RemoveOutput(hscript, cstring, cstring, cstring, cstring)

### CScriptKeyValues::FindKey
  - **Description**: Given a KeyValues object and a key name, find a KeyValues object associated with the key name
  - **Signature**: hscript CScriptKeyValues::FindKey(cstring)

### CScriptKeyValues::FindOrCreateKey
  - **Description**: Given a KeyValues object and a key name, find or create a KeyValues object associated with the key name
  - **Signature**: hscript CScriptKeyValues::FindOrCreateKey(cstring)

### CScriptKeyValues::GetBool
  - **Description**: Given a KeyValues object, return its own associated bool value
  - **Signature**: boolean CScriptKeyValues::GetBool()

### CScriptKeyValues::GetFirstSubKey
  - **Description**: Given a KeyValues object, return the first sub key object
  - **Signature**: hscript CScriptKeyValues::GetFirstSubKey()

### CScriptKeyValues::GetFloat
  - **Description**: Given a KeyValues object, return its own associated float value
  - **Signature**: float CScriptKeyValues::GetFloat()

### CScriptKeyValues::GetInt
  - **Description**: Given a KeyValues object, return its own associated integer value
  - **Signature**: integer CScriptKeyValues::GetInt()

### CScriptKeyValues::GetKeyBool
  - **Description**: Given a KeyValues object and a key name, return associated bool value
  - **Signature**: boolean CScriptKeyValues::GetKeyBool(cstring)

### CScriptKeyValues::GetKeyFloat
  - **Description**: Given a KeyValues object and a key name, return associated float value
  - **Signature**: float CScriptKeyValues::GetKeyFloat(cstring)

### CScriptKeyValues::GetKeyInt
  - **Description**: Given a KeyValues object and a key name, return associated integer value
  - **Signature**: integer CScriptKeyValues::GetKeyInt(cstring)

### CScriptKeyValues::GetKeyString
  - **Description**: Given a KeyValues object and a key name, return associated string value
  - **Signature**: cstring CScriptKeyValues::GetKeyString(cstring)

### CScriptKeyValues::GetName
  - **Description**: Given a KeyValues object, return its name
  - **Signature**: cstring CScriptKeyValues::GetName()

### CScriptKeyValues::GetNextKey
  - **Description**: Given a KeyValues object, return the next key object in a sub key group
  - **Signature**: hscript CScriptKeyValues::GetNextKey()

### CScriptKeyValues::GetString
  - **Description**: Given a KeyValues object, return its own associated string value
  - **Signature**: cstring CScriptKeyValues::GetString()

### CScriptKeyValues::IsKeyEmpty
  - **Description**: Given a KeyValues object and a key name, return true if key name has no value
  - **Signature**: boolean CScriptKeyValues::IsKeyEmpty(cstring)

### CScriptKeyValues::SetBool
  - **Description**: Given a KeyValues object, set its own associated bool value
  - **Signature**: void CScriptKeyValues::SetBool(boolean)

### CScriptKeyValues::SetFloat
  - **Description**: Given a KeyValues object, set its own associated float value
  - **Signature**: void CScriptKeyValues::SetFloat(float)

### CScriptKeyValues::SetInt
  - **Description**: Given a KeyValues object, set its own associated integer value
  - **Signature**: void CScriptKeyValues::SetInt(integer)

### CScriptKeyValues::SetKeyBool
  - **Description**: Given a KeyValues object and a key name, set associated bool value
  - **Signature**: void CScriptKeyValues::SetKeyBool(cstring, boolean)

### CScriptKeyValues::SetKeyFloat
  - **Description**: Given a KeyValues object and a key name, set associated float value
  - **Signature**: void CScriptKeyValues::SetKeyFloat(cstring, float)

### CScriptKeyValues::SetKeyInt
  - **Description**: Given a KeyValues object and a key name, set associated integer value
  - **Signature**: void CScriptKeyValues::SetKeyInt(cstring, integer)

### CScriptKeyValues::SetKeyString
  - **Description**: Given a KeyValues object and a key name, set associated string value
  - **Signature**: void CScriptKeyValues::SetKeyString(cstring, cstring)

### CScriptKeyValues::SetName
  - **Description**: Given a KeyValues object, set its name
  - **Signature**: void CScriptKeyValues::SetName(cstring)

### CScriptKeyValues::SetString
  - **Description**: Given a KeyValues object, set its own associated string value
  - **Signature**: void CScriptKeyValues::SetString(cstring)

### CScriptKeyValues::SubKeysToTable
  - **Description**: Converts to script table.
  - **Signature**: void CScriptKeyValues::SubKeysToTable(hscript)

### CScriptKeyValues::TableToSubKeys
  - **Description**: Converts a script table to KeyValues.
  - **Signature**: void CScriptKeyValues::TableToSubKeys(hscript)

### CSound::DoesSoundExpire
  - **Description**: Returns true if the sound expires.
  - **Signature**: boolean CSound::DoesSoundExpire()

### CSound::FreeSound
  - **Description**: Frees the sound from the sound list.
  - **Signature**: void CSound::FreeSound()

### CSound::GetOwner
  - **Description**: Gets the sound's owner.
  - **Signature**: hscript CSound::GetOwner()

### CSound::GetSoundOrigin
  - **Description**: Gets the sound's origin.
  - **Signature**: vector CSound::GetSoundOrigin()

### CSound::GetSoundReactOrigin
  - **Description**: Gets the sound's react origin.
  - **Signature**: vector CSound::GetSoundReactOrigin()

### CSound::GetTarget
  - **Description**: Gets the sound's target.
  - **Signature**: hscript CSound::GetTarget()

### CSound::IsScent
  - **Description**: Returns true if this is a type of scent (as opposed to a sound).
  - **Signature**: boolean CSound::IsScent()

### CSound::IsSound
  - **Description**: Returns true if this is a type of sound (as opposed to a scent).
  - **Signature**: boolean CSound::IsSound()

### CSound::IsSoundType
  - **Description**: Returns true if the sound type is the specified type.
  - **Signature**: boolean CSound::IsSoundType(integer)

### CSound::OccludedVolume
  - **Description**: Gets the sound's occluded volume.
  - **Signature**: float CSound::OccludedVolume()

### CSound::Reset
  - **Description**: Clears the volume, type, and origin for the sound without actually removing it.
  - **Signature**: void CSound::Reset()

### CSound::SetSoundOrigin
  - **Description**: Sets the sound's origin.
  - **Signature**: void CSound::SetSoundOrigin(vector)

### CSound::SoundChannel
  - **Description**: Gets the sound's channel.
  - **Signature**: integer CSound::SoundChannel()

### CSound::SoundContext
  - **Description**: Gets the sound type with contexts only.
  - **Signature**: integer CSound::SoundContext()

### CSound::SoundExpirationTime
  - **Description**: Gets the sound's expiration time.
  - **Signature**: float CSound::SoundExpirationTime()

### CSound::SoundType
  - **Description**: Gets the raw sound type.
  - **Signature**: integer CSound::SoundType()

### CSound::SoundTypeNoContext
  - **Description**: Gets the sound type with contexts excluded.
  - **Signature**: integer CSound::SoundTypeNoContext()

### CSound::ValidateOwner
  - **Description**: Returns true if the sound's owner is still valid or if the sound never had an owner in the first place.
  - **Signature**: boolean CSound::ValidateOwner()

### CSound::Volume
  - **Description**: Gets the sound's volume.
  - **Signature**: integer CSound::Volume()

### CTFBaseBoss::SetResolvePlayerCollisions
  - **Signature**: void CTFBaseBoss::SetResolvePlayerCollisions(boolean)

### CTFBot::AddBotAttribute
  - **Description**: Sets attribute flags on this TFBot
  - **Signature**: void CTFBot::AddBotAttribute(integer)

### CTFBot::AddBotTag
  - **Description**: Adds a bot tag
  - **Signature**: void CTFBot::AddBotTag(cstring)

### CTFBot::AddWeaponRestriction
  - **Description**: Adds weapon restriction flags
  - **Signature**: void CTFBot::AddWeaponRestriction(integer)

### CTFBot::ClearAllBotAttributes
  - **Description**: Clears all attribute flags on this TFBot
  - **Signature**: void CTFBot::ClearAllBotAttributes()

### CTFBot::ClearAllBotTags
  - **Description**: Clears bot tags
  - **Signature**: void CTFBot::ClearAllBotTags()

### CTFBot::ClearAllWeaponRestrictions
  - **Description**: Removes all weapon restriction flags
  - **Signature**: void CTFBot::ClearAllWeaponRestrictions()

### CTFBot::ClearAttentionFocus
  - **Description**: Clear current focus
  - **Signature**: void CTFBot::ClearAttentionFocus()

### CTFBot::ClearBehaviorFlag
  - **Description**: Clear the given behavior flag(s) for this bot
  - **Signature**: void CTFBot::ClearBehaviorFlag(integer)

### CTFBot::ClearImmobileStatus
  - **Description**: Clear immobile status
  - **Signature**: void CTFBot::ClearImmobileStatus()

### CTFBot::DelayedThreatNotice
  - **Signature**: void CTFBot::DelayedThreatNotice(hscript, float)

### CTFBot::DisbandCurrentSquad
  - **Description**: Forces the current squad to be entirely disbanded by everyone
  - **Signature**: void CTFBot::DisbandCurrentSquad()

### CTFBot::FindVantagePoint
  - **Description**: Get the nav area of the closest vantage point (within distance)
  - **Signature**: hscript CTFBot::FindVantagePoint(float)

### CTFBot::FlagForUpdate
  - **Description**: Flag this bot for update
  - **Signature**: void CTFBot::FlagForUpdate(boolean)

### CTFBot::GenerateAndWearItem
  - **Description**: Give me an item!
  - **Signature**: void CTFBot::GenerateAndWearItem(cstring)

### CTFBot::GetActionPoint
  - **Description**: Get the given action point for this bot
  - **Signature**: hscript CTFBot::GetActionPoint()

### CTFBot::GetAllBotTags
  - **Description**: Get all bot tags
  - **Signature**: void CTFBot::GetAllBotTags(hscript)

### CTFBot::GetBodyInterface
  - **Description**: Get this bot's body interface
  - **Signature**: hscript CTFBot::GetBodyInterface()

### CTFBot::GetBotId
  - **Description**: Get this bot's id
  - **Signature**: integer CTFBot::GetBotId()

### CTFBot::GetDifficulty
  - **Description**: Returns the bot's difficulty level
  - **Signature**: integer CTFBot::GetDifficulty()

### CTFBot::GetHomeArea
  - **Description**: Sets the home nav area of the bot
  - **Signature**: hscript CTFBot::GetHomeArea()

### CTFBot::GetImmobileDuration
  - **Description**: How long have we been immobile
  - **Signature**: float CTFBot::GetImmobileDuration()

### CTFBot::GetImmobileSpeedThreshold
  - **Description**: Return units/second below which this actor is considered immobile
  - **Signature**: float CTFBot::GetImmobileSpeedThreshold()

### CTFBot::GetIntentionInterface
  - **Description**: Get this bot's intention interface
  - **Signature**: hscript CTFBot::GetIntentionInterface()

### CTFBot::GetLocomotionInterface
  - **Description**: Get this bot's locomotion interface
  - **Signature**: hscript CTFBot::GetLocomotionInterface()

### CTFBot::GetMaxVisionRangeOverride
  - **Description**: Gets the max vision range override for the bot
  - **Signature**: float CTFBot::GetMaxVisionRangeOverride()

### CTFBot::GetMission
  - **Description**: Get this bot's current mission
  - **Signature**: integer CTFBot::GetMission()

### CTFBot::GetMissionTarget
  - **Description**: Get this bot's current mission target
  - **Signature**: hscript CTFBot::GetMissionTarget()

### CTFBot::GetNearestKnownSappableTarget
  - **Description**: Gets the nearest known sappable target
  - **Signature**: hscript CTFBot::GetNearestKnownSappableTarget()

### CTFBot::GetPrevMission
  - **Description**: Get this bot's previous mission
  - **Signature**: integer CTFBot::GetPrevMission()

### CTFBot::GetSpawnArea
  - **Description**: Return the nav area of where we spawned
  - **Signature**: hscript CTFBot::GetSpawnArea()

### CTFBot::GetSquadFormationError
  - **Description**: Gets our formation error coefficient.
  - **Signature**: float CTFBot::GetSquadFormationError()

### CTFBot::GetTickLastUpdate
  - **Description**: Get last update tick
  - **Signature**: integer CTFBot::GetTickLastUpdate()

### CTFBot::GetVisionInterface
  - **Description**: Get this bot's vision interface
  - **Signature**: hscript CTFBot::GetVisionInterface()

### CTFBot::HasBotAttribute
  - **Description**: Checks if this TFBot has the given attributes
  - **Signature**: boolean CTFBot::HasBotAttribute(integer)

### CTFBot::HasBotTag
  - **Description**: Checks if this TFBot has the given bot tag
  - **Signature**: boolean CTFBot::HasBotTag(cstring)

### CTFBot::HasMission
  - **Description**: Return true if the given mission is this bot's current mission
  - **Signature**: boolean CTFBot::HasMission(integer)

### CTFBot::HasWeaponRestriction
  - **Description**: Checks if this TFBot has the given weapon restriction flags
  - **Signature**: boolean CTFBot::HasWeaponRestriction(integer)

### CTFBot::IsAmmoFull
  - **Signature**: boolean CTFBot::IsAmmoFull()

### CTFBot::IsAmmoLow
  - **Signature**: boolean CTFBot::IsAmmoLow()

### CTFBot::IsAttentionFocused
  - **Description**: Is our attention focused right now?
  - **Signature**: boolean CTFBot::IsAttentionFocused()

### CTFBot::IsAttentionFocusedOn
  - **Description**: Is our attention focused on this entity
  - **Signature**: boolean CTFBot::IsAttentionFocusedOn(hscript)

### CTFBot::IsBehaviorFlagSet
  - **Description**: Return true if the given behavior flag(s) are set for this bot
  - **Signature**: boolean CTFBot::IsBehaviorFlagSet(integer)

### CTFBot::IsDifficulty
  - **Description**: Returns true/false if the bot's difficulty level matches.
  - **Signature**: boolean CTFBot::IsDifficulty(integer)

### CTFBot::IsEnemy
  - **Description**: Return true if given entity is our enemy
  - **Signature**: boolean CTFBot::IsEnemy(hscript)

### CTFBot::IsFlaggedForUpdate
  - **Description**: Is this bot flagged for update
  - **Signature**: boolean CTFBot::IsFlaggedForUpdate()

### CTFBot::IsFriend
  - **Description**: Return true if given entity is our friend
  - **Signature**: boolean CTFBot::IsFriend(hscript)

### CTFBot::IsImmobile
  - **Description**: Return true if we haven't moved in awhile
  - **Signature**: boolean CTFBot::IsImmobile()

### CTFBot::IsInASquad
  - **Description**: Checks if we are in a squad
  - **Signature**: boolean CTFBot::IsInASquad()

### CTFBot::IsOnAnyMission
  - **Description**: Return true if this bot has a current mission
  - **Signature**: boolean CTFBot::IsOnAnyMission()

### CTFBot::IsWeaponRestricted
  - **Description**: Checks if the given weapon is restricted for use on the bot
  - **Signature**: boolean CTFBot::IsWeaponRestricted(hscript)

### CTFBot::LeaveSquad
  - **Description**: Makes us leave the current squad (if any)
  - **Signature**: void CTFBot::LeaveSquad()

### CTFBot::PressAltFireButton
  - **Signature**: void CTFBot::PressAltFireButton(float)

### CTFBot::PressFireButton
  - **Signature**: void CTFBot::PressFireButton(float)

### CTFBot::PressSpecialFireButton
  - **Signature**: void CTFBot::PressSpecialFireButton(float)

### CTFBot::RemoveBotAttribute
  - **Description**: Removes attribute flags on this TFBot
  - **Signature**: void CTFBot::RemoveBotAttribute(integer)

### CTFBot::RemoveBotTag
  - **Description**: Removes a bot tag
  - **Signature**: void CTFBot::RemoveBotTag(cstring)

### CTFBot::RemoveWeaponRestriction
  - **Description**: Removes weapon restriction flags
  - **Signature**: void CTFBot::RemoveWeaponRestriction(integer)

### CTFBot::SetActionPoint
  - **Description**: Set the given action point for this bot
  - **Signature**: void CTFBot::SetActionPoint(hscript)

### CTFBot::SetAttentionFocus
  - **Description**: Sets our current attention focus to this entity
  - **Signature**: void CTFBot::SetAttentionFocus(hscript)

### CTFBot::SetAutoJump
  - **Description**: Sets if the bot should automatically jump
  - **Signature**: void CTFBot::SetAutoJump(float, float)

### CTFBot::SetBehaviorFlag
  - **Description**: Set the given behavior flag(s) for this bot
  - **Signature**: void CTFBot::SetBehaviorFlag(integer)

### CTFBot::SetDifficulty
  - **Description**: Sets the bots difficulty level
  - **Signature**: void CTFBot::SetDifficulty(integer)

### CTFBot::SetHomeArea
  - **Description**: Returns the home nav area of the bot -- may be nil.
  - **Signature**: void CTFBot::SetHomeArea(hscript)

### CTFBot::SetMaxVisionRangeOverride
  - **Description**: Sets max vision range override for the bot
  - **Signature**: void CTFBot::SetMaxVisionRangeOverride(float)

### CTFBot::SetMission
  - **Description**: Set this bot's current mission to the given mission
  - **Signature**: void CTFBot::SetMission(integer, boolean)

### CTFBot::SetMissionTarget
  - **Description**: Set this bot's mission target to the given entity
  - **Signature**: void CTFBot::SetMissionTarget(hscript)

### CTFBot::SetPrevMission
  - **Description**: Set this bot's previous mission to the given mission
  - **Signature**: void CTFBot::SetPrevMission(integer)

### CTFBot::SetScaleOverride
  - **Description**: Sets the scale override for the bot
  - **Signature**: void CTFBot::SetScaleOverride(float)

### CTFBot::SetShouldQuickBuild
  - **Description**: Sets if the bot should build instantly
  - **Signature**: void CTFBot::SetShouldQuickBuild(boolean)

### CTFBot::SetSquadFormationError
  - **Description**: Sets our formation error coefficient.
  - **Signature**: void CTFBot::SetSquadFormationError(float)

### CTFBot::ShouldAutoJump
  - **Description**: Returns if the bot should automatically jump
  - **Signature**: boolean CTFBot::ShouldAutoJump()

### CTFBot::ShouldQuickBuild
  - **Description**: Returns if the bot should build instantly
  - **Signature**: boolean CTFBot::ShouldQuickBuild()

### CTFBot::UpdateDelayedThreatNotices
  - **Signature**: void CTFBot::UpdateDelayedThreatNotices()

### CTFNavArea::AddIncomingConnection
  - **Description**: ( area, dir ) - Add areas that connect TO this area by a ONE-WAY link
  - **Signature**: void CTFNavArea::AddIncomingConnection(hscript, integer)

### CTFNavArea::ClearAttributeTF
  - **Description**: Clear TF-specific area attribute bits
  - **Signature**: void CTFNavArea::ClearAttributeTF(uint64)

### CTFNavArea::ComputeClosestPointInPortal
  - **Description**: Compute closest point within the portal between to adjacent areas.
  - **Signature**: vector CTFNavArea::ComputeClosestPointInPortal(hscript, integer, vector)

### CTFNavArea::ComputeDirection
  - **Description**: ( point ) - Return direction from this area to the given point
  - **Signature**: integer CTFNavArea::ComputeDirection(vector)

### CTFNavArea::ConnectTo
  - **Description**: ( area, dir ) - Connect this area to given area in given direction
  - **Signature**: void CTFNavArea::ConnectTo(hscript, integer)

### CTFNavArea::Contains
  - **Description**: ( area ) - Return true if other area is on or above this area, but no others
  - **Signature**: boolean CTFNavArea::Contains(hscript)

### CTFNavArea::ContainsOrigin
  - **Description**: ( point ) - Return true if given point is on or above this area, but no others
  - **Signature**: boolean CTFNavArea::ContainsOrigin(vector)

### CTFNavArea::DebugDrawFilled
  - **Description**: Draw area as a filled rect of the given color
  - **Signature**: void CTFNavArea::DebugDrawFilled(integer, integer, integer, integer, float, boolean, float)

### CTFNavArea::Disconnect
  - **Description**: ( area ) - Disconnect this area from given area
  - **Signature**: void CTFNavArea::Disconnect(hscript)

### CTFNavArea::FindRandomSpot
  - **Description**: Get random origin within extent of area
  - **Signature**: vector CTFNavArea::FindRandomSpot()

### CTFNavArea::GetAdjacentArea
  - **Description**: ( dir, n ) - Return the i'th adjacent area in the given direction
  - **Signature**: hscript CTFNavArea::GetAdjacentArea(integer, integer)

### CTFNavArea::GetAdjacentAreas
  - **Description**: ( dir, table ) - Fills a passed in table with all adjacent areas in the given direction
  - **Signature**: void CTFNavArea::GetAdjacentAreas(integer, hscript)

### CTFNavArea::GetAdjacentCount
  - **Description**: ( dir ) - Get the number of adjacent areas in the given direction
  - **Signature**: integer CTFNavArea::GetAdjacentCount(integer)

### CTFNavArea::GetAttributes
  - **Description**: Get area attribute bits
  - **Signature**: integer CTFNavArea::GetAttributes()

### CTFNavArea::GetAvoidanceObstacleHeight
  - **Description**: Returns the maximum height of the obstruction above the ground
  - **Signature**: float CTFNavArea::GetAvoidanceObstacleHeight()

### CTFNavArea::GetCenter
  - **Description**: Get center origin of area
  - **Signature**: vector CTFNavArea::GetCenter()

### CTFNavArea::GetCorner
  - **Description**: ( corner ) - Get corner origin of area
  - **Signature**: vector CTFNavArea::GetCorner(integer)

### CTFNavArea::GetDistanceSquaredToPoint
  - **Description**: ( pos ) - Return shortest distance between point and this area
  - **Signature**: float CTFNavArea::GetDistanceSquaredToPoint(vector)

### CTFNavArea::GetDoor
  - **Description**: Returns the door entity above the area
  - **Signature**: hscript CTFNavArea::GetDoor()

### CTFNavArea::GetElevator
  - **Description**: Returns the elevator if in an elevator's path
  - **Signature**: hscript CTFNavArea::GetElevator()

### CTFNavArea::GetElevatorAreas
  - **Description**: ( table ) - Fills table with a collection of areas reachable via elevator from this area
  - **Signature**: void CTFNavArea::GetElevatorAreas(hscript)

### CTFNavArea::GetID
  - **Description**: Get area ID.
  - **Signature**: integer CTFNavArea::GetID()

### CTFNavArea::GetIncomingConnections
  - **Description**: ( dir, table ) - Fills a passed in table with areas connected TO this area by a ONE-WAY link (ie: we have no connection back to them)
  - **Signature**: void CTFNavArea::GetIncomingConnections(integer, hscript)

### CTFNavArea::GetParent
  - **Description**: Returns the area just prior to this one in the search path
  - **Signature**: hscript CTFNavArea::GetParent()

### CTFNavArea::GetParentHow
  - **Description**: Returns how we get from parent to us
  - **Signature**: integer CTFNavArea::GetParentHow()

### CTFNavArea::GetPlaceName
  - **Description**: Get place name
  - **Signature**: cstring CTFNavArea::GetPlaceName()

### CTFNavArea::GetPlayerCount
  - **Description**: ( team ) - Return number of players of given team currently within this area (team of zero means any/all)
  - **Signature**: integer CTFNavArea::GetPlayerCount(integer)

### CTFNavArea::GetRandomAdjacentArea
  - **Description**: ( dir ) - Return a random adjacent area in the given direction
  - **Signature**: hscript CTFNavArea::GetRandomAdjacentArea(integer)

### CTFNavArea::GetSizeX
  - **Description**: Return the area size along the X axis
  - **Signature**: float CTFNavArea::GetSizeX()

### CTFNavArea::GetSizeY
  - **Description**: Return the area size along the Y axis
  - **Signature**: float CTFNavArea::GetSizeY()

### CTFNavArea::GetTravelDistanceToBombTarget
  - **Description**: Gets the travel distance to the MvM bomb target
  - **Signature**: float CTFNavArea::GetTravelDistanceToBombTarget()

### CTFNavArea::GetZ
  - **Description**: ( pos ) - Return Z of area at (x,y) of 'pos'
  - **Signature**: float CTFNavArea::GetZ(vector)

### CTFNavArea::HasAttributeTF
  - **Description**: Has TF-specific area attribute bits
  - **Signature**: boolean CTFNavArea::HasAttributeTF(uint64)

### CTFNavArea::HasAttributes
  - **Description**: Has area attribute bits
  - **Signature**: boolean CTFNavArea::HasAttributes(integer)

### CTFNavArea::HasAvoidanceObstacle
  - **Description**: ( maxheight ) - Returns true if there's a large, immobile object obstructing this area
  - **Signature**: boolean CTFNavArea::HasAvoidanceObstacle(float)

### CTFNavArea::IsBlocked
  - **Description**: ( team ) - Return true if team is blocked in this area
  - **Signature**: boolean CTFNavArea::IsBlocked(integer, boolean)

### CTFNavArea::IsBottleneck
  - **Description**: Returns true if area is a bottleneck
  - **Signature**: boolean CTFNavArea::IsBottleneck()

### CTFNavArea::IsCompletelyVisibleToTeam
  - **Description**: ( team ) - Return true if given area is completely visible from somewhere in this area by someone on the team
  - **Signature**: boolean CTFNavArea::IsCompletelyVisibleToTeam(integer)

### CTFNavArea::IsConnected
  - **Description**: ( area, dir ) - Return true if given area is connected in given direction
  - **Signature**: boolean CTFNavArea::IsConnected(hscript, integer)

### CTFNavArea::IsCoplanar
  - **Description**: ( area ) - Return true if this area and given area are approximately co-planar
  - **Signature**: boolean CTFNavArea::IsCoplanar(hscript)

### CTFNavArea::IsDamaging
  - **Description**: Return true if continuous damage (ie: fire) is in this area
  - **Signature**: boolean CTFNavArea::IsDamaging()

### CTFNavArea::IsDegenerate
  - **Description**: Return true if this area is badly formed
  - **Signature**: boolean CTFNavArea::IsDegenerate()

### CTFNavArea::IsEdge
  - **Description**: ( dir ) - Return true if there are no bi-directional links on the given side
  - **Signature**: boolean CTFNavArea::IsEdge(integer)

### CTFNavArea::IsFlat
  - **Description**: Return true if this area is approximately flat
  - **Signature**: boolean CTFNavArea::IsFlat()

### CTFNavArea::IsOverlapping
  - **Description**: ( area ) - Return true if 'area' overlaps our 2D extents
  - **Signature**: boolean CTFNavArea::IsOverlapping(hscript)

### CTFNavArea::IsOverlappingOrigin
  - **Description**: ( pos, tolerance ) - Return true if 'pos' is within 2D extents of area
  - **Signature**: boolean CTFNavArea::IsOverlappingOrigin(vector, float)

### CTFNavArea::IsPotentiallyVisibleToTeam
  - **Description**: ( team ) - Return true if any portion of this area is visible to anyone on the given team
  - **Signature**: boolean CTFNavArea::IsPotentiallyVisibleToTeam(integer)

### CTFNavArea::IsReachableByTeam
  - **Description**: Is this area reachable by the given team?
  - **Signature**: boolean CTFNavArea::IsReachableByTeam(integer)

### CTFNavArea::IsRoughlySquare
  - **Description**: Return true if this area is approximately square
  - **Signature**: boolean CTFNavArea::IsRoughlySquare()

### CTFNavArea::IsTFMarked
  - **Description**: Is this nav area marked with the current marking scope?
  - **Signature**: boolean CTFNavArea::IsTFMarked()

### CTFNavArea::IsUnderwater
  - **Description**: Return true if area is underwater
  - **Signature**: boolean CTFNavArea::IsUnderwater()

### CTFNavArea::IsValidForWanderingPopulation
  - **Description**: Returns true if area is valid for wandering population
  - **Signature**: boolean CTFNavArea::IsValidForWanderingPopulation()

### CTFNavArea::IsVisible
  - **Description**: ( point ) - Return true if area is visible from the given eyepoint
  - **Signature**: boolean CTFNavArea::IsVisible(vector)

### CTFNavArea::MarkAsBlocked
  - **Description**: ( team ) - Mark this area as blocked for team
  - **Signature**: void CTFNavArea::MarkAsBlocked(integer)

### CTFNavArea::MarkAsDamaging
  - **Description**: ( duration ) - Mark this area is damaging for the next 'duration' seconds
  - **Signature**: void CTFNavArea::MarkAsDamaging(float)

### CTFNavArea::MarkObstacleToAvoid
  - **Description**: ( height ) - Marks the obstructed status of the nav area
  - **Signature**: void CTFNavArea::MarkObstacleToAvoid(float)

### CTFNavArea::RemoveAttributes
  - **Description**: Removes area attribute bits
  - **Signature**: void CTFNavArea::RemoveAttributes(integer)

### CTFNavArea::RemoveOrthogonalConnections
  - **Description**: ( dir ) - Removes all connections in directions to left and right of specified direction
  - **Signature**: void CTFNavArea::RemoveOrthogonalConnections(integer)

### CTFNavArea::SetAttributeTF
  - **Description**: Set TF-specific area attributes
  - **Signature**: void CTFNavArea::SetAttributeTF(uint64)

### CTFNavArea::SetAttributes
  - **Description**: Set area attribute bits
  - **Signature**: void CTFNavArea::SetAttributes(integer)

### CTFNavArea::SetPlaceName
  - **Description**: ( name ) - Set place name
  - **Signature**: void CTFNavArea::SetPlaceName(cstring)

### CTFNavArea::TFMark
  - **Description**: Mark this nav area with the current marking scope.
  - **Signature**: void CTFNavArea::TFMark()

### CTFNavArea::UnblockArea
  - **Description**: Unblocks this area
  - **Signature**: void CTFNavArea::UnblockArea()

### CTFPlayer::AddCond
  - **Signature**: void CTFPlayer::AddCond(integer)

### CTFPlayer::AddCondEx
  - **Signature**: void CTFPlayer::AddCondEx(integer, float, hscript)

### CTFPlayer::AddCurrency
  - **Description**: Kaching! Give the player some cash for game modes with upgrades, ie. MvM
  - **Signature**: void CTFPlayer::AddCurrency(integer)

### CTFPlayer::AddCustomAttribute
  - **Description**: Add a custom attribute to the player
  - **Signature**: void CTFPlayer::AddCustomAttribute(cstring, float, float)

### CTFPlayer::AddHudHideFlags
  - **Description**: Hides a hud element based on Constants.FHideHUD.
  - **Signature**: void CTFPlayer::AddHudHideFlags(integer)

### CTFPlayer::ApplyAbsVelocityImpulse
  - **Signature**: void CTFPlayer::ApplyAbsVelocityImpulse(vector)

### CTFPlayer::ApplyPunchImpulseX
  - **Signature**: boolean CTFPlayer::ApplyPunchImpulseX(float)

### CTFPlayer::BleedPlayer
  - **Signature**: void CTFPlayer::BleedPlayer(float)

### CTFPlayer::BleedPlayerEx
  - **Signature**: void CTFPlayer::BleedPlayerEx(float, integer, boolean, integer)

### CTFPlayer::CanAirDash
  - **Signature**: boolean CTFPlayer::CanAirDash()

### CTFPlayer::CanBeDebuffed
  - **Signature**: boolean CTFPlayer::CanBeDebuffed()

### CTFPlayer::CanBreatheUnderwater
  - **Signature**: boolean CTFPlayer::CanBreatheUnderwater()

### CTFPlayer::CanDuck
  - **Description**: Can the player duck?
  - **Signature**: boolean CTFPlayer::CanDuck()

### CTFPlayer::CanGetWet
  - **Signature**: boolean CTFPlayer::CanGetWet()

### CTFPlayer::CanJump
  - **Description**: Can the player jump?
  - **Signature**: boolean CTFPlayer::CanJump()

### CTFPlayer::CanPlayerMove
  - **Description**: Can the player move?
  - **Signature**: boolean CTFPlayer::CanPlayerMove()

### CTFPlayer::CancelTaunt
  - **Signature**: void CTFPlayer::CancelTaunt()

### CTFPlayer::ClearCustomModelRotation
  - **Signature**: void CTFPlayer::ClearCustomModelRotation()

### CTFPlayer::ClearSpells
  - **Signature**: void CTFPlayer::ClearSpells()

### CTFPlayer::ClearTauntAttack
  - **Signature**: void CTFPlayer::ClearTauntAttack()

### CTFPlayer::DoTauntAttack
  - **Signature**: void CTFPlayer::DoTauntAttack()

### CTFPlayer::DropFlag
  - **Description**: Force player to drop the flag.
  - **Signature**: void CTFPlayer::DropFlag(boolean)

### CTFPlayer::DropRune
  - **Description**: Force player to drop the rune.
  - **Signature**: void CTFPlayer::DropRune(boolean, integer)

### CTFPlayer::EndLongTaunt
  - **Signature**: void CTFPlayer::EndLongTaunt()

### CTFPlayer::EquipWearableViewModel
  - **Signature**: void CTFPlayer::EquipWearableViewModel(hscript)

### CTFPlayer::ExtinguishPlayerBurning
  - **Signature**: void CTFPlayer::ExtinguishPlayerBurning()

### CTFPlayer::FiringTalk
  - **Description**: Makes eg. a heavy go AAAAAAAAAAaAaa like they are firing their minigun.
  - **Signature**: void CTFPlayer::FiringTalk()

### CTFPlayer::ForceChangeTeam
  - **Description**: Force player to change their team.
  - **Signature**: void CTFPlayer::ForceChangeTeam(integer, boolean)

### CTFPlayer::ForceRegenerateAndRespawn
  - **Description**: Force regenerates and respawns the player
  - **Signature**: void CTFPlayer::ForceRegenerateAndRespawn()

### CTFPlayer::ForceRespawn
  - **Description**: Force respawns the player
  - **Signature**: void CTFPlayer::ForceRespawn()

### CTFPlayer::GetActiveWeapon
  - **Description**: Get the player's current weapon
  - **Signature**: hscript CTFPlayer::GetActiveWeapon()

### CTFPlayer::GetBackstabs
  - **Signature**: integer CTFPlayer::GetBackstabs()

### CTFPlayer::GetBonusPoints
  - **Signature**: integer CTFPlayer::GetBonusPoints()

### CTFPlayer::GetBotType
  - **Signature**: integer CTFPlayer::GetBotType()

### CTFPlayer::GetBuildingsDestroyed
  - **Signature**: integer CTFPlayer::GetBuildingsDestroyed()

### CTFPlayer::GetCaptures
  - **Signature**: integer CTFPlayer::GetCaptures()

### CTFPlayer::GetClassEyeHeight
  - **Description**: Gets the eye height of the player
  - **Signature**: vector CTFPlayer::GetClassEyeHeight()

### CTFPlayer::GetCondDuration
  - **Signature**: float CTFPlayer::GetCondDuration(integer)

### CTFPlayer::GetCurrency
  - **Description**: Get player's cash for game modes with upgrades, ie. MvM
  - **Signature**: integer CTFPlayer::GetCurrency()

### CTFPlayer::GetCurrentTauntMoveSpeed
  - **Signature**: float CTFPlayer::GetCurrentTauntMoveSpeed()

### CTFPlayer::GetCustomAttribute
  - **Description**: Get a custom attribute float from the player
  - **Signature**: float CTFPlayer::GetCustomAttribute(cstring, float)

### CTFPlayer::GetDefenses
  - **Signature**: integer CTFPlayer::GetDefenses()

### CTFPlayer::GetDisguiseAmmoCount
  - **Signature**: integer CTFPlayer::GetDisguiseAmmoCount()

### CTFPlayer::GetDisguiseTarget
  - **Signature**: hscript CTFPlayer::GetDisguiseTarget()

### CTFPlayer::GetDisguiseTeam
  - **Signature**: integer CTFPlayer::GetDisguiseTeam()

### CTFPlayer::GetDominations
  - **Signature**: integer CTFPlayer::GetDominations()

### CTFPlayer::GetGrapplingHookTarget
  - **Description**: What entity is the player grappling?
  - **Signature**: hscript CTFPlayer::GetGrapplingHookTarget()

### CTFPlayer::GetHeadshots
  - **Signature**: integer CTFPlayer::GetHeadshots()

### CTFPlayer::GetHealPoints
  - **Signature**: integer CTFPlayer::GetHealPoints()

### CTFPlayer::GetHealTarget
  - **Description**: Who is the medic healing?
  - **Signature**: hscript CTFPlayer::GetHealTarget()

### CTFPlayer::GetHudHideFlags
  - **Description**: Gets current hidden hud elements
  - **Signature**: integer CTFPlayer::GetHudHideFlags()

### CTFPlayer::GetKillAssists
  - **Signature**: integer CTFPlayer::GetKillAssists()

### CTFPlayer::GetLastWeapon
  - **Signature**: hscript CTFPlayer::GetLastWeapon()

### CTFPlayer::GetNextChangeClassTime
  - **Description**: Get next change class time.
  - **Signature**: float CTFPlayer::GetNextChangeClassTime()

### CTFPlayer::GetNextChangeTeamTime
  - **Description**: Get next change team time.
  - **Signature**: float CTFPlayer::GetNextChangeTeamTime()

### CTFPlayer::GetNextRegenTime
  - **Description**: Get next health regen time.
  - **Signature**: float CTFPlayer::GetNextRegenTime()

### CTFPlayer::GetPadJumps
  - **Signature**: integer CTFPlayer::GetPadJumps()

### CTFPlayer::GetPlayerClass
  - **Signature**: integer CTFPlayer::GetPlayerClass()

### CTFPlayer::GetRageMeter
  - **Signature**: float CTFPlayer::GetRageMeter()

### CTFPlayer::GetResupplyPoints
  - **Signature**: integer CTFPlayer::GetResupplyPoints()

### CTFPlayer::GetRevenges
  - **Signature**: integer CTFPlayer::GetRevenges()

### CTFPlayer::GetScoutHypeMeter
  - **Signature**: float CTFPlayer::GetScoutHypeMeter()

### CTFPlayer::GetSpyCloakMeter
  - **Signature**: float CTFPlayer::GetSpyCloakMeter()

### CTFPlayer::GetTauntAttack
  - **Signature**: unknown_variant_type CTFPlayer::GetTauntAttack()

### CTFPlayer::GetTauntAttackTime
  - **Signature**: float CTFPlayer::GetTauntAttackTime()

### CTFPlayer::GetTauntRemoveTime
  - **Signature**: float CTFPlayer::GetTauntRemoveTime()

### CTFPlayer::GetTeleports
  - **Signature**: integer CTFPlayer::GetTeleports()

### CTFPlayer::GetTimeSinceCalledForMedic
  - **Description**: When did the player last call medic
  - **Signature**: float CTFPlayer::GetTimeSinceCalledForMedic()

### CTFPlayer::GetUbercharges
  - **Signature**: integer CTFPlayer::GetUbercharges()

### CTFPlayer::GetVehicleReverseTime
  - **Signature**: float CTFPlayer::GetVehicleReverseTime()

### CTFPlayer::GrantOrRemoveAllUpgrades
  - **Description**: Grants or removes all upgrades the player has purchased.
  - **Signature**: void CTFPlayer::GrantOrRemoveAllUpgrades(boolean, boolean)

### CTFPlayer::HandleTauntCommand
  - **Signature**: void CTFPlayer::HandleTauntCommand(integer)

### CTFPlayer::HasItem
  - **Description**: Currently holding an item? Eg. capture flag
  - **Signature**: boolean CTFPlayer::HasItem()

### CTFPlayer::IgnitePlayer
  - **Signature**: void CTFPlayer::IgnitePlayer()

### CTFPlayer::IgnitePlayerEx
  - **Signature**: void CTFPlayer::IgnitePlayerEx(float)

### CTFPlayer::InAirDueToExplosion
  - **Signature**: boolean CTFPlayer::InAirDueToExplosion()

### CTFPlayer::InAirDueToKnockback
  - **Signature**: boolean CTFPlayer::InAirDueToKnockback()

### CTFPlayer::InCond
  - **Signature**: boolean CTFPlayer::InCond(integer)

### CTFPlayer::IsAirDashing
  - **Signature**: boolean CTFPlayer::IsAirDashing()

### CTFPlayer::IsAllowedToRemoveTaunt
  - **Signature**: boolean CTFPlayer::IsAllowedToRemoveTaunt()

### CTFPlayer::IsAllowedToTaunt
  - **Signature**: boolean CTFPlayer::IsAllowedToTaunt()

### CTFPlayer::IsBotOfType
  - **Signature**: boolean CTFPlayer::IsBotOfType(integer)

### CTFPlayer::IsCallingForMedic
  - **Description**: Is this player calling for medic?
  - **Signature**: boolean CTFPlayer::IsCallingForMedic()

### CTFPlayer::IsCarryingRune
  - **Signature**: boolean CTFPlayer::IsCarryingRune()

### CTFPlayer::IsControlStunned
  - **Signature**: boolean CTFPlayer::IsControlStunned()

### CTFPlayer::IsCritBoosted
  - **Signature**: boolean CTFPlayer::IsCritBoosted()

### CTFPlayer::IsFakeClient
  - **Signature**: boolean CTFPlayer::IsFakeClient()

### CTFPlayer::IsFireproof
  - **Signature**: boolean CTFPlayer::IsFireproof()

### CTFPlayer::IsFullyInvisible
  - **Signature**: boolean CTFPlayer::IsFullyInvisible()

### CTFPlayer::IsHypeBuffed
  - **Signature**: boolean CTFPlayer::IsHypeBuffed()

### CTFPlayer::IsImmuneToPushback
  - **Signature**: boolean CTFPlayer::IsImmuneToPushback()

### CTFPlayer::IsInspecting
  - **Signature**: boolean CTFPlayer::IsInspecting()

### CTFPlayer::IsInvulnerable
  - **Signature**: boolean CTFPlayer::IsInvulnerable()

### CTFPlayer::IsJumping
  - **Signature**: boolean CTFPlayer::IsJumping()

### CTFPlayer::IsMiniBoss
  - **Description**: Is this player an MvM mini-boss?
  - **Signature**: boolean CTFPlayer::IsMiniBoss()

### CTFPlayer::IsParachuteEquipped
  - **Signature**: boolean CTFPlayer::IsParachuteEquipped()

### CTFPlayer::IsPlacingSapper
  - **Description**: Returns true if we placed a sapper in the last few moments
  - **Signature**: boolean CTFPlayer::IsPlacingSapper()

### CTFPlayer::IsRageDraining
  - **Signature**: boolean CTFPlayer::IsRageDraining()

### CTFPlayer::IsRegenerating
  - **Signature**: boolean CTFPlayer::IsRegenerating()

### CTFPlayer::IsSapping
  - **Description**: Returns true if we are currently sapping
  - **Signature**: boolean CTFPlayer::IsSapping()

### CTFPlayer::IsSnared
  - **Signature**: boolean CTFPlayer::IsSnared()

### CTFPlayer::IsStealthed
  - **Signature**: boolean CTFPlayer::IsStealthed()

### CTFPlayer::IsTaunting
  - **Signature**: boolean CTFPlayer::IsTaunting()

### CTFPlayer::IsUsingActionSlot
  - **Signature**: boolean CTFPlayer::IsUsingActionSlot()

### CTFPlayer::IsViewingCYOAPDA
  - **Signature**: boolean CTFPlayer::IsViewingCYOAPDA()

### CTFPlayer::Regenerate
  - **Description**: Resupplies a player. If regen health/ammo is set, clears negative conds, gives back player health/ammo
  - **Signature**: void CTFPlayer::Regenerate(boolean)

### CTFPlayer::RemoveAllCond
  - **Signature**: void CTFPlayer::RemoveAllCond()

### CTFPlayer::RemoveAllItems
  - **Signature**: void CTFPlayer::RemoveAllItems(boolean)

### CTFPlayer::RemoveAllObjects
  - **Description**: Remove all player objects. Eg. dispensers/sentries.
  - **Signature**: void CTFPlayer::RemoveAllObjects(boolean)

### CTFPlayer::RemoveCond
  - **Signature**: void CTFPlayer::RemoveCond(integer)

### CTFPlayer::RemoveCondEx
  - **Signature**: void CTFPlayer::RemoveCondEx(integer, boolean)

### CTFPlayer::RemoveCurrency
  - **Description**: Take away money from a player for reasons such as ie. spending.
  - **Signature**: void CTFPlayer::RemoveCurrency(integer)

### CTFPlayer::RemoveCustomAttribute
  - **Description**: Remove a custom attribute to the player
  - **Signature**: void CTFPlayer::RemoveCustomAttribute(cstring)

### CTFPlayer::RemoveDisguise
  - **Description**: Undisguise a spy.
  - **Signature**: void CTFPlayer::RemoveDisguise()

### CTFPlayer::RemoveHudHideFlags
  - **Description**: Unhides a hud element based on Constants.FHideHUD.
  - **Signature**: void CTFPlayer::RemoveHudHideFlags(integer)

### CTFPlayer::RemoveInvisibility
  - **Description**: Un-invisible a spy.
  - **Signature**: void CTFPlayer::RemoveInvisibility()

### CTFPlayer::RemoveTeleportEffect
  - **Signature**: void CTFPlayer::RemoveTeleportEffect()

### CTFPlayer::ResetScores
  - **Signature**: void CTFPlayer::ResetScores()

### CTFPlayer::RollRareSpell
  - **Signature**: void CTFPlayer::RollRareSpell()

### CTFPlayer::SetCondDuration
  - **Signature**: void CTFPlayer::SetCondDuration(integer, float)

### CTFPlayer::SetCurrency
  - **Description**: Set player's cash for game modes with upgrades, ie. MvM
  - **Signature**: void CTFPlayer::SetCurrency(integer)

### CTFPlayer::SetCurrentTauntMoveSpeed
  - **Signature**: void CTFPlayer::SetCurrentTauntMoveSpeed(float)

### CTFPlayer::SetCustomModel
  - **Signature**: void CTFPlayer::SetCustomModel(cstring)

### CTFPlayer::SetCustomModelOffset
  - **Signature**: void CTFPlayer::SetCustomModelOffset(vector)

### CTFPlayer::SetCustomModelRotates
  - **Signature**: void CTFPlayer::SetCustomModelRotates(boolean)

### CTFPlayer::SetCustomModelRotation
  - **Signature**: void CTFPlayer::SetCustomModelRotation(qangle)

### CTFPlayer::SetCustomModelVisibleToSelf
  - **Signature**: void CTFPlayer::SetCustomModelVisibleToSelf(boolean)

### CTFPlayer::SetCustomModelWithClassAnimations
  - **Signature**: void CTFPlayer::SetCustomModelWithClassAnimations(cstring)

### CTFPlayer::SetDisguiseAmmoCount
  - **Signature**: void CTFPlayer::SetDisguiseAmmoCount(integer)

### CTFPlayer::SetForcedTauntCam
  - **Signature**: void CTFPlayer::SetForcedTauntCam(integer)

### CTFPlayer::SetGrapplingHookTarget
  - **Description**: Set the player's target grapple entity
  - **Signature**: void CTFPlayer::SetGrapplingHookTarget(hscript, boolean)

### CTFPlayer::SetHudHideFlags
  - **Description**: Force hud hide flags to a value
  - **Signature**: void CTFPlayer::SetHudHideFlags(integer)

### CTFPlayer::SetIsMiniBoss
  - **Description**: Make this player an MvM mini-boss.
  - **Signature**: void CTFPlayer::SetIsMiniBoss(boolean)

### CTFPlayer::SetNextChangeClassTime
  - **Description**: Set next change class time.
  - **Signature**: void CTFPlayer::SetNextChangeClassTime(float)

### CTFPlayer::SetNextChangeTeamTime
  - **Description**: Set next change team time.
  - **Signature**: void CTFPlayer::SetNextChangeTeamTime(float)

### CTFPlayer::SetNextRegenTime
  - **Description**: Set next health regen time.
  - **Signature**: void CTFPlayer::SetNextRegenTime(float)

### CTFPlayer::SetPlayerClass
  - **Signature**: void CTFPlayer::SetPlayerClass(integer)

### CTFPlayer::SetRPSResult
  - **Signature**: void CTFPlayer::SetRPSResult(integer)

### CTFPlayer::SetRageMeter
  - **Signature**: void CTFPlayer::SetRageMeter(float)

### CTFPlayer::SetScoutHypeMeter
  - **Signature**: void CTFPlayer::SetScoutHypeMeter(float)

### CTFPlayer::SetSpyCloakMeter
  - **Signature**: void CTFPlayer::SetSpyCloakMeter(float)

### CTFPlayer::SetUseBossHealthBar
  - **Signature**: void CTFPlayer::SetUseBossHealthBar(boolean)

### CTFPlayer::SetVehicleReverseTime
  - **Signature**: void CTFPlayer::SetVehicleReverseTime(float)

### CTFPlayer::StopTaunt
  - **Signature**: void CTFPlayer::StopTaunt(boolean)

### CTFPlayer::StunPlayer
  - **Signature**: void CTFPlayer::StunPlayer(float, float, integer, hscript)

### CTFPlayer::Taunt
  - **Signature**: void CTFPlayer::Taunt(integer, integer)

### CTFPlayer::TryToPickupBuilding
  - **Description**: Make the player attempt to pick up a building in front of them
  - **Signature**: boolean CTFPlayer::TryToPickupBuilding()

### CTFPlayer::UpdateSkin
  - **Signature**: void CTFPlayer::UpdateSkin(integer)

### CTFPlayer::WasInCond
  - **Signature**: boolean CTFPlayer::WasInCond(integer)

### CTFPlayer::Weapon_CanUse
  - **Signature**: boolean CTFPlayer::Weapon_CanUse(hscript)

### CTFPlayer::Weapon_Drop
  - **Signature**: void CTFPlayer::Weapon_Drop(hscript)

### CTFPlayer::Weapon_DropEx
  - **Signature**: void CTFPlayer::Weapon_DropEx(hscript, vector, vector)

### CTFPlayer::Weapon_Equip
  - **Signature**: void CTFPlayer::Weapon_Equip(hscript)

### CTFPlayer::Weapon_SetLast
  - **Signature**: void CTFPlayer::Weapon_SetLast(hscript)

### CTFPlayer::Weapon_ShootPosition
  - **Signature**: vector CTFPlayer::Weapon_ShootPosition()

### CTFPlayer::Weapon_Switch
  - **Signature**: void CTFPlayer::Weapon_Switch(hscript)

### CTakeDamageInfo::AddDamage
  - **Description**: Adds to the damage.
  - **Signature**: void CTakeDamageInfo::AddDamage(float)

### CTakeDamageInfo::AddDamageType
  - **Description**: Adds to the damage type.
  - **Signature**: void CTakeDamageInfo::AddDamageType(integer)

### CTakeDamageInfo::BaseDamageIsValid
  - **Description**: Checks if the base damage is valid.
  - **Signature**: boolean CTakeDamageInfo::BaseDamageIsValid()

### CTakeDamageInfo::GetAmmoName
  - **Description**: Gets the ammo type name.
  - **Signature**: cstring CTakeDamageInfo::GetAmmoName()

### CTakeDamageInfo::GetAmmoType
  - **Description**: Gets the ammo type.
  - **Signature**: integer CTakeDamageInfo::GetAmmoType()

### CTakeDamageInfo::GetAttacker
  - **Description**: Gets the attacker.
  - **Signature**: hscript CTakeDamageInfo::GetAttacker()

### CTakeDamageInfo::GetBaseDamage
  - **Description**: Gets the base damage.
  - **Signature**: float CTakeDamageInfo::GetBaseDamage()

### CTakeDamageInfo::GetDamage
  - **Description**: Gets the damage.
  - **Signature**: float CTakeDamageInfo::GetDamage()

### CTakeDamageInfo::GetDamageBonus
  - **Description**: Gets the damage bonus.
  - **Signature**: float CTakeDamageInfo::GetDamageBonus()

### CTakeDamageInfo::GetDamageCustom
  - **Description**: Gets the damage custom.
  - **Signature**: integer CTakeDamageInfo::GetDamageCustom()

### CTakeDamageInfo::GetDamageForce
  - **Description**: Gets the damage force.
  - **Signature**: vector CTakeDamageInfo::GetDamageForce()

### CTakeDamageInfo::GetDamagePosition
  - **Description**: Gets the damage position.
  - **Signature**: vector CTakeDamageInfo::GetDamagePosition()

### CTakeDamageInfo::GetDamageStats
  - **Description**: Gets the damage stats.
  - **Signature**: integer CTakeDamageInfo::GetDamageStats()

### CTakeDamageInfo::GetDamageType
  - **Description**: Gets the damage type.
  - **Signature**: integer CTakeDamageInfo::GetDamageType()

### CTakeDamageInfo::GetDamagedOtherPlayers
  - **Description**: Gets whether other players have been damaged.
  - **Signature**: integer CTakeDamageInfo::GetDamagedOtherPlayers()

### CTakeDamageInfo::GetInflictor
  - **Description**: Gets the inflictor.
  - **Signature**: hscript CTakeDamageInfo::GetInflictor()

### CTakeDamageInfo::GetMaxDamage
  - **Description**: Gets the max damage.
  - **Signature**: float CTakeDamageInfo::GetMaxDamage()

### CTakeDamageInfo::GetPlayerPenetrationCount
  - **Description**: Gets the player penetration count.
  - **Signature**: integer CTakeDamageInfo::GetPlayerPenetrationCount()

### CTakeDamageInfo::GetReportedPosition
  - **Description**: Gets the reported damage position.
  - **Signature**: vector CTakeDamageInfo::GetReportedPosition()

### CTakeDamageInfo::GetWeapon
  - **Description**: Gets the weapon.
  - **Signature**: hscript CTakeDamageInfo::GetWeapon()

### CTakeDamageInfo::IsForceFriendlyFire
  - **Description**: Gets force friendly fire.
  - **Signature**: boolean CTakeDamageInfo::IsForceFriendlyFire()

### CTakeDamageInfo::ScaleDamage
  - **Description**: Scales the damage.
  - **Signature**: void CTakeDamageInfo::ScaleDamage(float)

### CTakeDamageInfo::ScaleDamageForce
  - **Description**: Scales the damage force.
  - **Signature**: void CTakeDamageInfo::ScaleDamageForce(float)

### CTakeDamageInfo::SetAmmoType
  - **Description**: Sets the ammo type.
  - **Signature**: void CTakeDamageInfo::SetAmmoType(integer)

### CTakeDamageInfo::SetAttacker
  - **Description**: Sets the attacker.
  - **Signature**: void CTakeDamageInfo::SetAttacker(hscript)

### CTakeDamageInfo::SetDamage
  - **Description**: Sets the damage.
  - **Signature**: void CTakeDamageInfo::SetDamage(float)

### CTakeDamageInfo::SetDamageBonus
  - **Description**: Sets the damage bonus.
  - **Signature**: void CTakeDamageInfo::SetDamageBonus(float)

### CTakeDamageInfo::SetDamageCustom
  - **Description**: Sets the damage custom.
  - **Signature**: void CTakeDamageInfo::SetDamageCustom(integer)

### CTakeDamageInfo::SetDamageForce
  - **Description**: Sets the damage force.
  - **Signature**: void CTakeDamageInfo::SetDamageForce(vector)

### CTakeDamageInfo::SetDamagePosition
  - **Description**: Sets the damage position.
  - **Signature**: void CTakeDamageInfo::SetDamagePosition(vector)

### CTakeDamageInfo::SetDamageStats
  - **Description**: Sets the damage stats.
  - **Signature**: void CTakeDamageInfo::SetDamageStats(integer)

### CTakeDamageInfo::SetDamageType
  - **Description**: Sets the damage type.
  - **Signature**: void CTakeDamageInfo::SetDamageType(integer)

### CTakeDamageInfo::SetDamagedOtherPlayers
  - **Description**: Sets whether other players have been damaged.
  - **Signature**: void CTakeDamageInfo::SetDamagedOtherPlayers(integer)

### CTakeDamageInfo::SetForceFriendlyFire
  - **Description**: Sets force friendly fire.
  - **Signature**: void CTakeDamageInfo::SetForceFriendlyFire(boolean)

### CTakeDamageInfo::SetInflictor
  - **Description**: Sets the inflictor.
  - **Signature**: void CTakeDamageInfo::SetInflictor(hscript)

### CTakeDamageInfo::SetMaxDamage
  - **Description**: Sets the max damage.
  - **Signature**: void CTakeDamageInfo::SetMaxDamage(float)

### CTakeDamageInfo::SetPlayerPenetrationCount
  - **Description**: Sets the player penetration count.
  - **Signature**: void CTakeDamageInfo::SetPlayerPenetrationCount(integer)

### CTakeDamageInfo::SetReportedPosition
  - **Description**: Sets the reported damage position.
  - **Signature**: void CTakeDamageInfo::SetReportedPosition(vector)

### CTakeDamageInfo::SetWeapon
  - **Description**: Sets the weapon.
  - **Signature**: void CTakeDamageInfo::SetWeapon(hscript)

### CTakeDamageInfo::SubtractDamage
  - **Description**: Removes from the damage.
  - **Signature**: void CTakeDamageInfo::SubtractDamage(float)

### CTriggerCamera::GetFov
  - **Description**: get camera's current fov setting as integer
  - **Signature**: integer CTriggerCamera::GetFov()

### CTriggerCamera::SetFov
  - **Description**: set camera's current fov in integer degrees and fov change rate as float
  - **Signature**: void CTriggerCamera::SetFov(integer, float)

### CUserCmd::GetButtons
  - **Description**: Input button state.
  - **Signature**: integer CUserCmd::GetButtons()

### CUserCmd::GetCommandNumber
  - **Description**: For matching server and client commands for debugging.
  - **Signature**: integer CUserCmd::GetCommandNumber()

### CUserCmd::GetForwardMove
  - **Signature**: float CUserCmd::GetForwardMove()

### CUserCmd::GetImpulse
  - **Description**: Impulse command issued.
  - **Signature**: integer CUserCmd::GetImpulse()

### CUserCmd::GetMouseX
  - **Description**: Mouse accum in x from create move.
  - **Signature**: integer CUserCmd::GetMouseX()

### CUserCmd::GetMouseY
  - **Description**: Mouse accum in y from create move.
  - **Signature**: integer CUserCmd::GetMouseY()

### CUserCmd::GetRandomSeed
  - **Description**: For shared random functions.
  - **Signature**: integer CUserCmd::GetRandomSeed()

### CUserCmd::GetSideMove
  - **Signature**: float CUserCmd::GetSideMove()

### CUserCmd::GetTickCount
  - **Description**: The tick the client created this command.
  - **Signature**: integer CUserCmd::GetTickCount()

### CUserCmd::GetUpMove
  - **Signature**: float CUserCmd::GetUpMove()

### CUserCmd::GetViewAngles
  - **Description**: Player instantaneous view angles.
  - **Signature**: qangle CUserCmd::GetViewAngles()

### CUserCmd::GetWeaponSelect
  - **Description**: Current weapon id.
  - **Signature**: integer CUserCmd::GetWeaponSelect()

### CUserCmd::GetWeaponSubtype
  - **Description**: Current weapon subtype id.
  - **Signature**: integer CUserCmd::GetWeaponSubtype()

### CUserCmd::SetButtons
  - **Description**: Sets input button state.
  - **Signature**: void CUserCmd::SetButtons(integer)

### CUserCmd::SetForwardMove
  - **Signature**: void CUserCmd::SetForwardMove(float)

### CUserCmd::SetImpulse
  - **Description**: Sets impulse command issued.
  - **Signature**: void CUserCmd::SetImpulse(integer)

### CUserCmd::SetMouseX
  - **Description**: Sets mouse accum in x from create move.
  - **Signature**: void CUserCmd::SetMouseX(integer)

### CUserCmd::SetMouseY
  - **Description**: Sets mouse accum in y from create move.
  - **Signature**: void CUserCmd::SetMouseY(integer)

### CUserCmd::SetSideMove
  - **Signature**: void CUserCmd::SetSideMove(float)

### CUserCmd::SetUpMove
  - **Signature**: void CUserCmd::SetUpMove(float)

### CUserCmd::SetViewAngles
  - **Description**: Sets player instantaneous view angles.
  - **Signature**: void CUserCmd::SetViewAngles(qangle)

### CUserCmd::SetWeaponSelect
  - **Description**: Sets current weapon id.
  - **Signature**: void CUserCmd::SetWeaponSelect(integer)

### CUserCmd::SetWeaponSubtype
  - **Description**: Sets current weapon subtype id.
  - **Signature**: void CUserCmd::SetWeaponSubtype(integer)

### CalcClosestPointOnAABB
  - **Description**: Returns the closest point on a bounding box.
  - **Signature**: vector CalcClosestPointOnAABB(vector, vector, vector)

### CalcClosestPointOnLine
  - **Description**: Returns the closest point on a line.
  - **Signature**: vector CalcClosestPointOnLine(vector, vector, vector)

### CalcClosestPointOnLineSegment
  - **Description**: Returns the closest point on a line segment.
  - **Signature**: vector CalcClosestPointOnLineSegment(vector, vector, vector)

### CalcDistanceToLine
  - **Description**: Returns the distance to a line.
  - **Signature**: float CalcDistanceToLine(vector, vector, vector)

### CalcDistanceToLineSegment
  - **Description**: Returns the distance to a line segment.
  - **Signature**: float CalcDistanceToLineSegment(vector, vector, vector)

### CalcSqrDistanceToAABB
  - **Description**: Returns the squared distance to a bounding box.
  - **Signature**: float CalcSqrDistanceToAABB(vector, vector, vector)

### CalculateBulletDamageForce
  - **Description**: Fill out a damage info handle with a damage force for a bullet impact.
  - **Signature**: void CalculateBulletDamageForce(hscript, integer, vector, vector, float)

### CalculateExplosiveDamageForce
  - **Description**: Fill out a damage info handle with a damage force for an explosive.
  - **Signature**: void CalculateExplosiveDamageForce(hscript, vector, vector, float)

### CalculateMeleeDamageForce
  - **Description**: Fill out a damage info handle with a damage force for a melee impact.
  - **Signature**: void CalculateMeleeDamageForce(hscript, vector, vector, float)

### CancelEntityIOEvent
  - **Description**: Remove entity I/O event.
  - **Signature**: boolean CancelEntityIOEvent(integer)

### ClearSavedTable
  - **Description**: Removes the table with the given context.
  - **Signature**: void ClearSavedTable(cstring)

### ClientPrint
  - **Description**: Print a client message
  - **Signature**: void ClientPrint(hscript, integer, cstring)

### Color::GetRawColor
  - **Description**: Gets the raw color integer.
  - **Signature**: integer Color::GetRawColor()

### Color::SetColor
  - **Description**: Sets the color.
  - **Signature**: void Color::SetColor(integer, integer, integer, integer)

### Color::SetRawColor
  - **Description**: Sets the raw color integer.
  - **Signature**: void Color::SetRawColor(integer)

### ConcatTransforms
  - **Description**: Concatenates two transformation matrices into another matrix.
  - **Signature**: void ConcatTransforms(hscript, hscript, hscript)

### CreateDamageInfo
  - **Signature**: hscript CreateDamageInfo(hscript, hscript, vector, vector, float, integer)

### CreateFireBulletsInfo
  - **Signature**: hscript CreateFireBulletsInfo(integer, vector, vector, vector, float, hscript)

### CreateProp
  - **Description**: Create a physics prop
  - **Signature**: hscript CreateProp(cstring, vector, cstring, integer)

### CreateRope
  - **Description**: Creates a single rope between two entities. Can optionally follow specific attachments.
  - **Signature**: hscript CreateRope(hscript, hscript, integer, integer, float, cstring, integer, integer)

### CreateRopeWithSecondPointDetached
  - **Description**: Creates a single detached rope hanging from a point. Can optionally follow a specific start attachment.
  - **Signature**: hscript CreateRopeWithSecondPointDetached(hscript, integer, integer, float, cstring, integer, boolean, integer)

### CreateSceneEntity
  - **Description**: Create a scene entity to play the specified scene.
  - **Signature**: hscript CreateSceneEntity(cstring)

### DeactivateTeam
  - **Signature**: void DeactivateTeam(integer)

### DebugDrawBox
  - **Description**: Draw a debug overlay box
  - **Signature**: void DebugDrawBox(vector, vector, vector, integer, integer, integer, integer, float)

### DebugDrawBoxAngles
  - **Description**: Draw a debug oriented box (cent, min, max, angles(p,y,r), vRgb, a, duration)
  - **Signature**: void DebugDrawBoxAngles(vector, vector, vector, qangle, vector, float, float)

### DebugDrawBoxDirection
  - **Description**: Draw a debug forward box (cent, min, max, forward, vRgb, a, duration)
  - **Signature**: void DebugDrawBoxDirection(vector, vector, vector, vector, vector, float, float)

### DebugDrawCircle
  - **Description**: Draw a debug circle (center, rad, vRgb, a, ztest, duration)
  - **Signature**: void DebugDrawCircle(vector, vector, float, float, boolean, float)

### DebugDrawClear
  - **Description**: Try to clear all the debug overlay info
  - **Signature**: void DebugDrawClear()

### DebugDrawLine
  - **Description**: Draw a debug overlay line
  - **Signature**: void DebugDrawLine(vector, vector, integer, integer, integer, boolean, float)

### DebugDrawLine_vCol
  - **Description**: Draw a debug line using color vec (start, end, vRgb, a, ztest, duration)
  - **Signature**: void DebugDrawLine_vCol(vector, vector, vector, boolean, float)

### DebugDrawScreenTextLine
  - **Description**: Draw text with a line offset
  - **Signature**: void DebugDrawScreenTextLine(float, float, integer, cstring, integer, integer, integer, integer, float)

### DebugDrawText
  - **Description**: Draw text in 3d (origin, text, bViewCheck, duration)
  - **Signature**: void DebugDrawText(vector, cstring, boolean, float)

### DecalTrace
  - **Description**: Creates a dynamic decal based on the given trace info. The trace information can be generated by TraceLineComplex() and the decal name must be from decals_subrect.txt.
  - **Signature**: void DecalTrace(hscript, cstring)

### DispatchParticleEffect
  - **Description**: Dispatches a one-off particle system
  - **Signature**: function DispatchParticleEffect(particleName, origin, angles, entity)

### DispatchSpawn
  - **Description**: Spawns an unspawned entity.
  - **Signature**: void DispatchSpawn(hscript)

### DoIncludeScript
  - **Description**: Execute a script (internal)
  - **Signature**: boolean DoIncludeScript(cstring, hscript)

### EmitAmbientSoundOn
  - **Description**: Play named ambient sound on an entity.
  - **Signature**: void EmitAmbientSoundOn(cstring, float, integer, integer, hscript)

### EmitSoundEx
  - **Description**: Play a sound. Takes in a script table of params.
  - **Signature**: void EmitSoundEx(hscript)

### EmitSoundOn
  - **Description**: Play named sound on Entity. Legacy only, use EmitSoundEx.
  - **Signature**: void EmitSoundOn(cstring, hscript)

### EmitSoundOnClient
  - **Description**: Play named sound only on the client for the passed in player. NOTE: This only supports soundscripts. Legacy only, use EmitSoundEx.
  - **Signature**: void EmitSoundOnClient(cstring, hscript)

### EmitSoundParamsOn
  - **Description**: Play EmitSound_t params on an entity.
  - **Signature**: void EmitSoundParamsOn(hscript, hscript)

### EmitSound_t::ClearOrigin
  - **Description**: Clears the sound's origin override if it has one.
  - **Signature**: void EmitSound_t::ClearOrigin()

### EmitSound_t::GetChannel
  - **Signature**: integer EmitSound_t::GetChannel()

### EmitSound_t::GetEmitCloseCaption
  - **Description**: Gets whether or not the sound will emit closed captioning/subtitles.
  - **Signature**: float EmitSound_t::GetEmitCloseCaption()

### EmitSound_t::GetFlags
  - **Description**: Gets the sound's flags. See the 'SND_' set of constants.
  - **Signature**: integer EmitSound_t::GetFlags()

### EmitSound_t::GetOrigin
  - **Description**: Gets the sound's origin override.
  - **Signature**: vector EmitSound_t::GetOrigin()

### EmitSound_t::GetSoundLevel
  - **Description**: Gets the sound's level in decibels. (Note that this may not apply to soundscripts)
  - **Signature**: integer EmitSound_t::GetSoundLevel()

### EmitSound_t::GetSoundName
  - **Description**: Gets the sound's file path or soundscript name.
  - **Signature**: cstring EmitSound_t::GetSoundName()

### EmitSound_t::GetSoundScriptHandle
  - **Signature**: integer EmitSound_t::GetSoundScriptHandle()

### EmitSound_t::GetSoundTime
  - **Description**: Gets the time the sound will begin, relative to Time().
  - **Signature**: float EmitSound_t::GetSoundTime()

### EmitSound_t::GetSpeakerEntity
  - **Description**: Gets the sound's original source if it is being transmitted by a microphone.
  - **Signature**: integer EmitSound_t::GetSpeakerEntity()

### EmitSound_t::GetSpecialDSP
  - **Signature**: integer EmitSound_t::GetSpecialDSP()

### EmitSound_t::GetVolume
  - **Description**: (Note that this may not apply to soundscripts)
  - **Signature**: float EmitSound_t::GetVolume()

### EmitSound_t::GetWarnOnDirectWaveReference
  - **Description**: Gets whether or not the sound will send a message to the console if it references a direct sound file instead of a soundscript.
  - **Signature**: float EmitSound_t::GetWarnOnDirectWaveReference()

### EmitSound_t::GetWarnOnMissingCloseCaption
  - **Description**: Gets whether or not the sound will send a message to the console if there is no corresponding closed captioning token.
  - **Signature**: float EmitSound_t::GetWarnOnMissingCloseCaption()

### EmitSound_t::HasOrigin
  - **Description**: Returns true if the sound has an origin override.
  - **Signature**: boolean EmitSound_t::HasOrigin()

### EmitSound_t::SetChannel
  - **Signature**: void EmitSound_t::SetChannel(integer)

### EmitSound_t::SetEmitCloseCaption
  - **Description**: Sets whether or not the sound will emit closed captioning/subtitles.
  - **Signature**: void EmitSound_t::SetEmitCloseCaption(boolean)

### EmitSound_t::SetFlags
  - **Description**: Sets the sound's flags. See the 'SND_' set of constants.
  - **Signature**: void EmitSound_t::SetFlags(integer)

### EmitSound_t::SetOrigin
  - **Description**: Sets the sound's origin override.
  - **Signature**: void EmitSound_t::SetOrigin(vector)

### EmitSound_t::SetSoundLevel
  - **Description**: Sets the sound's level in decibels. (Note that this may not apply to soundscripts)
  - **Signature**: void EmitSound_t::SetSoundLevel(integer)

### EmitSound_t::SetSoundName
  - **Description**: Sets the sound's file path or soundscript name.
  - **Signature**: void EmitSound_t::SetSoundName(cstring)

### EmitSound_t::SetSoundScriptHandle
  - **Signature**: void EmitSound_t::SetSoundScriptHandle(integer)

### EmitSound_t::SetSoundTime
  - **Description**: Sets the time the sound will begin, relative to Time().
  - **Signature**: void EmitSound_t::SetSoundTime(float)

### EmitSound_t::SetSpeakerEntity
  - **Description**: Sets the sound's original source if it is being transmitted by a microphone.
  - **Signature**: void EmitSound_t::SetSpeakerEntity(integer)

### EmitSound_t::SetSpecialDSP
  - **Signature**: void EmitSound_t::SetSpecialDSP(integer)

### EmitSound_t::SetVolume
  - **Description**: (Note that this may not apply to soundscripts)
  - **Signature**: void EmitSound_t::SetVolume(float)

### EmitSound_t::SetWarnOnDirectWaveReference
  - **Description**: Sets whether or not the sound will send a message to the console if it references a direct sound file instead of a soundscript.
  - **Signature**: void EmitSound_t::SetWarnOnDirectWaveReference(boolean)

### EmitSound_t::SetWarnOnMissingCloseCaption
  - **Description**: Sets whether or not the sound will send a message to the console if there is no corresponding closed captioning token.
  - **Signature**: void EmitSound_t::SetWarnOnMissingCloseCaption(boolean)

### EntFire
  - **Description**: Generate and entity i/o event
  - **Signature**: function EntFire(target, action, value, delay, activator, caller)

### EntFireByHandle
  - **Description**: Generate an entity i/o event. First parameter is an entity instance.
  - **Signature**: function EntFireByHandle(target, action, value, delay, activator, caller)

### EntIndexToHScript
  - **Description**: Returns the script handle for the given entity index.
  - **Signature**: hscript EntIndexToHScript(integer)

### EntitiesAtPoint
  - **Description**: Gets all entities which are intersecting a point in space. This function copies them to an array with a maximum number of elements.
  - **Signature**: void EntitiesAtPoint(hscript, integer, vector, integer)

### EntitiesInBox
  - **Description**: Gets all entities which are within a worldspace box. This function copies them to an array with a maximum number of elements.
  - **Signature**: void EntitiesInBox(hscript, integer, vector, vector, integer)

### EntitiesInSphere
  - **Description**: Gets all entities which are within a sphere. This function copies them to an array with a maximum number of elements.
  - **Signature**: void EntitiesInSphere(hscript, integer, vector, float, integer)

### ExponentialDecay
  - **Description**: decayTo is factor the value should decay to in decayTime
  - **Signature**: float ExponentialDecay(float, float, float)

### FLerp
  - **Signature**: float FLerp(float, float, float, float, float)

### FileExists
  - **Description**: Returns true if the file exists.
  - **Signature**: boolean FileExists(cstring)

### FileToKeyValues
  - **Description**: Returns the CScriptKeyValues from the file, null if no file or file is too big.
  - **Signature**: hscript FileToKeyValues(cstring)

### FileToString
  - **Description**: Returns the string from the file, null if no file or file is too big.
  - **Signature**: cstring FileToString(cstring)

### FireBulletsInfo_t::GetAdditionalIgnoreEnt
  - **Signature**: hscript FireBulletsInfo_t::GetAdditionalIgnoreEnt()

### FireBulletsInfo_t::GetAmmoType
  - **Signature**: integer FireBulletsInfo_t::GetAmmoType()

### FireBulletsInfo_t::GetAttacker
  - **Signature**: hscript FireBulletsInfo_t::GetAttacker()

### FireBulletsInfo_t::GetDamage
  - **Description**: Gets the damage the bullets should deal. 0 = use ammo type
  - **Signature**: float FireBulletsInfo_t::GetDamage()

### FireBulletsInfo_t::GetDamageForceScale
  - **Signature**: float FireBulletsInfo_t::GetDamageForceScale()

### FireBulletsInfo_t::GetDirShooting
  - **Signature**: vector FireBulletsInfo_t::GetDirShooting()

### FireBulletsInfo_t::GetDistance
  - **Description**: Gets the distance the bullets should travel.
  - **Signature**: float FireBulletsInfo_t::GetDistance()

### FireBulletsInfo_t::GetFlags
  - **Description**: Gets the flags the bullets should use.
  - **Signature**: integer FireBulletsInfo_t::GetFlags()

### FireBulletsInfo_t::GetPlayerDamage
  - **Description**: Gets the damage the bullets should deal when hitting the player. 0 = use regular damage
  - **Signature**: integer FireBulletsInfo_t::GetPlayerDamage()

### FireBulletsInfo_t::GetPrimaryAttack
  - **Description**: Gets whether the bullets came from a primary attack.
  - **Signature**: boolean FireBulletsInfo_t::GetPrimaryAttack()

### FireBulletsInfo_t::GetShots
  - **Description**: Gets the number of shots which should be fired.
  - **Signature**: integer FireBulletsInfo_t::GetShots()

### FireBulletsInfo_t::GetSource
  - **Signature**: vector FireBulletsInfo_t::GetSource()

### FireBulletsInfo_t::GetSpread
  - **Signature**: vector FireBulletsInfo_t::GetSpread()

### FireBulletsInfo_t::GetTracerFreq
  - **Signature**: integer FireBulletsInfo_t::GetTracerFreq()

### FireBulletsInfo_t::SetAdditionalIgnoreEnt
  - **Signature**: void FireBulletsInfo_t::SetAdditionalIgnoreEnt(hscript)

### FireBulletsInfo_t::SetAmmoType
  - **Signature**: void FireBulletsInfo_t::SetAmmoType(integer)

### FireBulletsInfo_t::SetAttacker
  - **Signature**: void FireBulletsInfo_t::SetAttacker(hscript)

### FireBulletsInfo_t::SetDamage
  - **Description**: Sets the damage the bullets should deal. 0 = use ammo type
  - **Signature**: void FireBulletsInfo_t::SetDamage(float)

### FireBulletsInfo_t::SetDamageForceScale
  - **Signature**: void FireBulletsInfo_t::SetDamageForceScale(float)

### FireBulletsInfo_t::SetDirShooting
  - **Signature**: void FireBulletsInfo_t::SetDirShooting(vector)

### FireBulletsInfo_t::SetDistance
  - **Description**: Sets the distance the bullets should travel.
  - **Signature**: void FireBulletsInfo_t::SetDistance(float)

### FireBulletsInfo_t::SetFlags
  - **Description**: Sets the flags the bullets should use.
  - **Signature**: void FireBulletsInfo_t::SetFlags(float)

### FireBulletsInfo_t::SetPlayerDamage
  - **Description**: Sets the damage the bullets should deal when hitting the player. 0 = use regular damage
  - **Signature**: void FireBulletsInfo_t::SetPlayerDamage(float)

### FireBulletsInfo_t::SetPrimaryAttack
  - **Description**: Sets whether the bullets came from a primary attack.
  - **Signature**: void FireBulletsInfo_t::SetPrimaryAttack(boolean)

### FireBulletsInfo_t::SetShots
  - **Description**: Sets the number of shots which should be fired.
  - **Signature**: void FireBulletsInfo_t::SetShots(integer)

### FireBulletsInfo_t::SetSource
  - **Signature**: void FireBulletsInfo_t::SetSource(vector)

### FireBulletsInfo_t::SetSpread
  - **Signature**: void FireBulletsInfo_t::SetSpread(vector)

### FireBulletsInfo_t::SetTracerFreq
  - **Signature**: void FireBulletsInfo_t::SetTracerFreq(integer)

### FireGameEvent
  - **Description**: Fire a game event.
  - **Signature**: void FireGameEvent(cstring, hscript)

### FireGameEventLocal
  - **Description**: Fire a game event without broadcasting to the client.
  - **Signature**: void FireGameEventLocal(cstring, hscript)

### FireScriptHook
  - **Description**: Fire a script hoook to a listening callback function in script. Parameters are passed in a squirrel table.
  - **Signature**: boolean FireScriptHook(cstring, hscript)

### FlagsMayBeCapped
  - **Description**: May a flag be captured?
  - **Signature**: boolean FlagsMayBeCapped()

### ForceEnableUpgrades
  - **Description**: Whether to force on MvM-styled upgrades on/off. 0 -> default, 1 -> force off, 2 -> force on
  - **Signature**: void ForceEnableUpgrades(integer)

### ForceEscortPushLogic
  - **Description**: Forces payload pushing logic. 0 -> default, 1 -> force off, 2 -> force on
  - **Signature**: void ForceEscortPushLogic(integer)

### FrameTime
  - **Description**: Get the time spent on the server in the last frame
  - **Signature**: float FrameTime()

### FreeMatrixInstance
  - **Description**: Frees an allocated matrix instance.
  - **Signature**: void FreeMatrixInstance(hscript)

### FreeQuaternionInstance
  - **Description**: Frees an allocated quaternion instance.
  - **Signature**: void FreeQuaternionInstance(hscript)

### Gain
  - **Description**: Gain is similar to Bias, but biasAmt biases towards or away from 0.5.
  - **Signature**: float Gain(float, float)

### GameModeUsesCurrency
  - **Description**: Does the current gamemode have currency?
  - **Signature**: boolean GameModeUsesCurrency()

### GameModeUsesMiniBosses
  - **Description**: Does the current gamemode have minibosses?
  - **Signature**: boolean GameModeUsesMiniBosses()

### GameModeUsesUpgrades
  - **Description**: Does the current gamemode have upgrades?
  - **Signature**: boolean GameModeUsesUpgrades()

### GetActivityName
  - **Description**: Gets the name of the specified activity index.
  - **Signature**: cstring GetActivityName(integer)

### GetCPUUsage
  - **Description**: Get CPU usage percentage.
  - **Signature**: float GetCPUUsage()

### GetClassLimit
  - **Description**: Get class limit for class. See Constants.ETFClass
  - **Signature**: integer GetClassLimit(integer)

### GetDeveloperLevel
  - **Description**: Gets the level of 'developer'
  - **Signature**: integer GetDeveloperLevel()

### GetEntityIOEventTimeLeft
  - **Description**: Get time left on entity I/O event.
  - **Signature**: float GetEntityIOEventTimeLeft(integer)

### GetFrameCount
  - **Description**: Absolute frame counter
  - **Signature**: integer GetFrameCount()

### GetFriction
  - **Description**: Returns the Friction on a player entity, meaningless if not a player
  - **Signature**: float GetFriction(hscript)

### GetGravityMultiplier
  - **Signature**: float GetGravityMultiplier()

### GetListenServerHost
  - **Description**: Get the local player on a listen server.
  - **Signature**: hscript GetListenServerHost()

### GetLoadType
  - **Description**: Get the way the current game was loaded (corresponds to the MapLoad enum)
  - **Signature**: integer GetLoadType()

### GetMannVsMachineAlarmStatus
  - **Signature**: boolean GetMannVsMachineAlarmStatus()

### GetMapName
  - **Description**: Get the name of the map.
  - **Signature**: cstring GetMapName()

### GetModelIndex
  - **Description**: Returns the index of the named model.
  - **Signature**: integer GetModelIndex(cstring)

### GetNumTeamsActive
  - **Signature**: integer GetNumTeamsActive()

### GetOvertimeAllowedForCTF
  - **Signature**: boolean GetOvertimeAllowedForCTF()

### GetPhysAngVelocity
  - **Description**: Gets physics angular velocity for the given VPhysics object
  - **Signature**: vector GetPhysAngVelocity(hscript)

### GetPhysVelocity
  - **Description**: Gets physics velocity for the given VPhysics object
  - **Signature**: vector GetPhysVelocity(hscript)

### GetPlayerFromUserID
  - **Description**: Given a user id, return the entity, or null
  - **Signature**: hscript GetPlayerFromUserID(integer)

### GetRoundState
  - **Description**: Get current round state. See Constants.ERoundState
  - **Signature**: integer GetRoundState()

### GetSoundDuration
  - **Description**: Returns float duration of the sound. Takes soundname and optional actormodelname.
  - **Signature**: float GetSoundDuration(cstring, cstring)

### GetStopWatchState
  - **Description**: Get the current stopwatch state. See Constants.EStopwatchState
  - **Signature**: integer GetStopWatchState()

### GetWinningTeam
  - **Description**: Who won!
  - **Signature**: integer GetWinningTeam()

### GuessDamageForce
  - **Description**: Try and guess the physics force to use.
  - **Signature**: void GuessDamageForce(hscript, vector, vector, float)

### HaveStopWatchWinner
  - **Signature**: boolean HaveStopWatchWinner()

### ILocomotion::Approach
  - **Description**: The primary locomotive method. Sets the goal destination for the bot
  - **Signature**: void ILocomotion::Approach(vector, float)

### ILocomotion::ClearStuckStatus
  - **Description**: Reset stuck status to un-stuck
  - **Signature**: void ILocomotion::ClearStuckStatus(cstring)

### ILocomotion::ClimbUpToLedge
  - **Description**: Initiate a jump to an adjacent high ledge, return false if climb can't start
  - **Signature**: boolean ILocomotion::ClimbUpToLedge(vector, vector, hscript)

### ILocomotion::DriveTo
  - **Description**: Move the bot to the precise given position immediately, updating internal state
  - **Signature**: void ILocomotion::DriveTo(vector)

### ILocomotion::FaceTowards
  - **Description**: Rotate body to face towards target
  - **Signature**: void ILocomotion::FaceTowards(vector)

### ILocomotion::FractionPotentialGap
  - **Description**: If the locomotor cannot jump over the gap, returns the fraction of the jumpable ray
  - **Signature**: float ILocomotion::FractionPotentialGap(vector, vector)

### ILocomotion::FractionPotentiallyTraversable
  - **Description**: If the locomotor could not move along the line given, returns the fraction of the walkable ray.
  - **Signature**: float ILocomotion::FractionPotentiallyTraversable(vector, vector, boolean)

### ILocomotion::GetDeathDropHeight
  - **Description**: Distance at which we will die if we fall
  - **Signature**: float ILocomotion::GetDeathDropHeight()

### ILocomotion::GetDesiredSpeed
  - **Description**: Get desired speed for locomotor movement
  - **Signature**: float ILocomotion::GetDesiredSpeed()

### ILocomotion::GetFeet
  - **Description**: Return position of feet - the driving point where the bot contacts the ground
  - **Signature**: vector ILocomotion::GetFeet()

### ILocomotion::GetGround
  - **Description**: Return the current ground entity or NULL if not on the ground
  - **Signature**: hscript ILocomotion::GetGround()

### ILocomotion::GetGroundMotionVector
  - **Description**: Return unit vector in XY plane describing our direction of motion - even if we are currently not moving
  - **Signature**: vector ILocomotion::GetGroundMotionVector()

### ILocomotion::GetGroundNormal
  - **Description**: Surface normal of the ground we are in contact with
  - **Signature**: vector ILocomotion::GetGroundNormal()

### ILocomotion::GetGroundSpeed
  - **Description**: Return current world space speed in XY plane
  - **Signature**: float ILocomotion::GetGroundSpeed()

### ILocomotion::GetMaxAcceleration
  - **Description**: Return maximum acceleration of locomotor
  - **Signature**: float ILocomotion::GetMaxAcceleration()

### ILocomotion::GetMaxDeceleration
  - **Description**: Return maximum deceleration of locomotor
  - **Signature**: float ILocomotion::GetMaxDeceleration()

### ILocomotion::GetMaxJumpHeight
  - **Description**: Return maximum height of a jump
  - **Signature**: float ILocomotion::GetMaxJumpHeight()

### ILocomotion::GetMotionVector
  - **Description**: Return unit vector describing our direction of motion - even if we are currently not moving
  - **Signature**: vector ILocomotion::GetMotionVector()

### ILocomotion::GetRunSpeed
  - **Description**: Get maximum running speed
  - **Signature**: float ILocomotion::GetRunSpeed()

### ILocomotion::GetSpeed
  - **Description**: Return current world space speed (magnitude of velocity)
  - **Signature**: float ILocomotion::GetSpeed()

### ILocomotion::GetSpeedLimit
  - **Description**: Get maximum speed bot can reach, regardless of desired speed
  - **Signature**: float ILocomotion::GetSpeedLimit()

### ILocomotion::GetStepHeight
  - **Description**: If delta Z is greater than this, we have to jump to get up
  - **Signature**: float ILocomotion::GetStepHeight()

### ILocomotion::GetStuckDuration
  - **Description**: Return how long we've been stuck
  - **Signature**: float ILocomotion::GetStuckDuration()

### ILocomotion::GetTraversableSlopeLimit
  - **Description**: Return Z component of unit normal of steepest traversable slope
  - **Signature**: float ILocomotion::GetTraversableSlopeLimit()

### ILocomotion::GetVelocity
  - **Description**: Return current world space velocity
  - **Signature**: vector ILocomotion::GetVelocity()

### ILocomotion::GetWalkSpeed
  - **Description**: Get maximum walking speed
  - **Signature**: float ILocomotion::GetWalkSpeed()

### ILocomotion::HasPotentialGap
  - **Description**: Return true if there is a possible gap that will need to be jumped over
  - **Signature**: float ILocomotion::HasPotentialGap(vector, vector)

### ILocomotion::IsAbleToClimb
  - **Description**: Return true if this bot can climb arbitrary geometry it encounters
  - **Signature**: boolean ILocomotion::IsAbleToClimb()

### ILocomotion::IsAbleToJumpAcrossGaps
  - **Description**: Return true if this bot can jump across gaps in its path
  - **Signature**: boolean ILocomotion::IsAbleToJumpAcrossGaps()

### ILocomotion::IsAreaTraversable
  - **Description**: Return true if given area can be used for navigation
  - **Signature**: boolean ILocomotion::IsAreaTraversable(hscript)

### ILocomotion::IsAttemptingToMove
  - **Description**: Return true if we have tried to Approach() or DriveTo() very recently
  - **Signature**: boolean ILocomotion::IsAttemptingToMove()

### ILocomotion::IsClimbingOrJumping
  - **Description**: Is jumping in any form
  - **Signature**: boolean ILocomotion::IsClimbingOrJumping()

### ILocomotion::IsClimbingUpToLedge
  - **Description**: Is climbing up to a high ledge
  - **Signature**: boolean ILocomotion::IsClimbingUpToLedge()

### ILocomotion::IsEntityTraversable
  - **Description**: Return true if the entity handle is traversable
  - **Signature**: boolean ILocomotion::IsEntityTraversable(hscript, boolean)

### ILocomotion::IsGap
  - **Description**: Return true if there is a gap here when moving in the given direction
  - **Signature**: boolean ILocomotion::IsGap(vector, vector)

### ILocomotion::IsJumpingAcrossGap
  - **Description**: Is jumping across a gap to the far side
  - **Signature**: boolean ILocomotion::IsJumpingAcrossGap()

### ILocomotion::IsOnGround
  - **Description**: Return true if standing on something
  - **Signature**: boolean ILocomotion::IsOnGround()

### ILocomotion::IsPotentiallyTraversable
  - **Description**: Return true if this locomotor could potentially move along the line given.
  - **Signature**: float ILocomotion::IsPotentiallyTraversable(vector, vector, boolean)

### ILocomotion::IsRunning
  - **Description**: Is running?
  - **Signature**: boolean ILocomotion::IsRunning()

### ILocomotion::IsScrambling
  - **Description**: Is in the middle of a complex action (climbing a ladder, climbing a ledge, jumping, etc) that shouldn't be interrupted
  - **Signature**: boolean ILocomotion::IsScrambling()

### ILocomotion::IsStuck
  - **Description**: Return true if bot is stuck. If the locomotor cannot make progress, it becomes stuck and can only leave this stuck state by successfully movingand becoming un-stuck.
  - **Signature**: boolean ILocomotion::IsStuck()

### ILocomotion::Jump
  - **Description**: Initiate a simple undirected jump in the air
  - **Signature**: void ILocomotion::Jump()

### ILocomotion::JumpAcrossGap
  - **Description**: Initiate a jump across an empty volume of space to far side
  - **Signature**: void ILocomotion::JumpAcrossGap(vector, vector)

### ILocomotion::OnLandOnGround
  - **Description**: Manually run the OnLandOnGround callback. Typically invoked when bot lands on the ground after being in the air
  - **Signature**: void ILocomotion::OnLandOnGround(hscript)

### ILocomotion::OnLeaveGround
  - **Description**: Manually run the OnLeaveGround callback. Typically invoked when bot leaves ground for any reason
  - **Signature**: void ILocomotion::OnLeaveGround(hscript)

### ILocomotion::Run
  - **Description**: Set desired movement speed to running
  - **Signature**: void ILocomotion::Run()

### ILocomotion::SetDesiredSpeed
  - **Description**: Set desired speed for locomotor movement
  - **Signature**: void ILocomotion::SetDesiredSpeed(float)

### ILocomotion::SetSpeedLimit
  - **Description**: Set maximum speed bot can reach, regardless of desired speed
  - **Signature**: void ILocomotion::SetSpeedLimit(float)

### ILocomotion::Stop
  - **Description**: Set desired movement speed to stopped
  - **Signature**: void ILocomotion::Stop()

### ILocomotion::Walk
  - **Description**: Set desired movement speed to walking
  - **Signature**: void ILocomotion::Walk()

### INextBotComponent::ComputeUpdateInterval
  - **Description**: Recomputes the component update interval
  - **Signature**: boolean INextBotComponent::ComputeUpdateInterval()

### INextBotComponent::GetUpdateInterval
  - **Description**: Returns the component update interval
  - **Signature**: float INextBotComponent::GetUpdateInterval()

### INextBotComponent::Reset
  - **Description**: Resets the internal update state
  - **Signature**: void INextBotComponent::Reset()

### IPhysicsObject::ApplyForceCenter
  - **Signature**: void IPhysicsObject::ApplyForceCenter(vector)

### IPhysicsObject::ApplyForceOffset
  - **Signature**: void IPhysicsObject::ApplyForceOffset(vector, vector)

### IPhysicsObject::ApplyTorqueCenter
  - **Signature**: void IPhysicsObject::ApplyTorqueCenter(vector)

### IPhysicsObject::EnableCollisions
  - **Signature**: void IPhysicsObject::EnableCollisions(boolean)

### IPhysicsObject::EnableDrag
  - **Signature**: void IPhysicsObject::EnableDrag(boolean)

### IPhysicsObject::EnableGravity
  - **Signature**: void IPhysicsObject::EnableGravity(boolean)

### IPhysicsObject::EnableMotion
  - **Signature**: void IPhysicsObject::EnableMotion(boolean)

### IPhysicsObject::GetInertia
  - **Signature**: vector IPhysicsObject::GetInertia()

### IPhysicsObject::GetInvInertia
  - **Signature**: vector IPhysicsObject::GetInvInertia()

### IPhysicsObject::GetInvMass
  - **Signature**: float IPhysicsObject::GetInvMass()

### IPhysicsObject::GetMass
  - **Signature**: float IPhysicsObject::GetMass()

### IPhysicsObject::GetName
  - **Signature**: cstring IPhysicsObject::GetName()

### IPhysicsObject::IsAsleep
  - **Signature**: boolean IPhysicsObject::IsAsleep()

### IPhysicsObject::IsAttachedToConstraint
  - **Signature**: boolean IPhysicsObject::IsAttachedToConstraint(boolean)

### IPhysicsObject::IsCollisionEnabled
  - **Signature**: boolean IPhysicsObject::IsCollisionEnabled()

### IPhysicsObject::IsDragEnabled
  - **Signature**: boolean IPhysicsObject::IsDragEnabled()

### IPhysicsObject::IsFluid
  - **Signature**: boolean IPhysicsObject::IsFluid()

### IPhysicsObject::IsGravityEnabled
  - **Signature**: boolean IPhysicsObject::IsGravityEnabled()

### IPhysicsObject::IsHinged
  - **Signature**: boolean IPhysicsObject::IsHinged()

### IPhysicsObject::IsMotionEnabled
  - **Signature**: boolean IPhysicsObject::IsMotionEnabled()

### IPhysicsObject::IsMoveable
  - **Signature**: boolean IPhysicsObject::IsMoveable()

### IPhysicsObject::IsStatic
  - **Signature**: boolean IPhysicsObject::IsStatic()

### IPhysicsObject::IsTrigger
  - **Signature**: boolean IPhysicsObject::IsTrigger()

### IPhysicsObject::SetInertia
  - **Signature**: void IPhysicsObject::SetInertia(vector)

### IPhysicsObject::SetMass
  - **Signature**: void IPhysicsObject::SetMass(float)

### IPhysicsObject::Sleep
  - **Signature**: void IPhysicsObject::Sleep()

### IPhysicsObject::Wake
  - **Signature**: void IPhysicsObject::Wake()

### ImpulseScale
  - **Description**: Returns an impulse scale required to push an object.
  - **Signature**: float ImpulseScale(float, float)

### InMatchStartCountdown
  - **Description**: Are we in the pre-match state?
  - **Signature**: boolean InMatchStartCountdown()

### InOvertime
  - **Description**: Currently in overtime?
  - **Signature**: boolean InOvertime()

### InsertAISound
  - **Description**: Inserts an AI sound.
  - **Signature**: void InsertAISound(integer, vector, integer, float, hscript, integer, hscript)

### IntervalPerTick
  - **Description**: Simulation tick interval
  - **Signature**: float IntervalPerTick()

### IsAttackDefenseMode
  - **Signature**: boolean IsAttackDefenseMode()

### IsBirthday
  - **Description**: Are we in birthday mode?
  - **Signature**: boolean IsBirthday()

### IsClient
  - **Description**: Returns true if the script is being run on the client.
  - **Signature**: boolean IsClient()

### IsDedicatedServer
  - **Description**: Returns true if this server is a dedicated server.
  - **Signature**: boolean IsDedicatedServer()

### IsDefaultGameMode
  - **Description**: The absence of arena, mvm, tournament mode, etc
  - **Signature**: boolean IsDefaultGameMode()

### IsHolidayActive
  - **Description**: Is the given holiday active? See Constants.EHoliday
  - **Signature**: boolean IsHolidayActive(integer)

### IsHolidayMap
  - **Description**: Playing a holiday map? See Constants.EHoliday
  - **Signature**: boolean IsHolidayMap(integer)

### IsInArenaMode
  - **Description**: Playing arena mode?
  - **Signature**: boolean IsInArenaMode()

### IsInKothMode
  - **Description**: Playing king of the hill mode?
  - **Signature**: boolean IsInKothMode()

### IsInMedievalMode
  - **Description**: Playing medieval mode?
  - **Signature**: boolean IsInMedievalMode()

### IsInWaitingForPlayers
  - **Description**: Are we waiting for some stragglers?
  - **Signature**: boolean IsInWaitingForPlayers()

### IsLinux
  - **Description**: Returns true if the game is being run on a Linux machine.
  - **Signature**: boolean IsLinux()

### IsMannVsMachineMode
  - **Description**: Playing MvM? Beep boop
  - **Signature**: boolean IsMannVsMachineMode()

### IsMannVsMachineRespecEnabled
  - **Description**: Are players allowed to refund their upgrades?
  - **Signature**: boolean IsMannVsMachineRespecEnabled()

### IsModelPrecached
  - **Description**: Checks if the modelname is precached.
  - **Signature**: boolean IsModelPrecached(cstring)

### IsMultiTeamGame
  - **Signature**: boolean IsMultiTeamGame()

### IsOSX
  - **Description**: Returns true if the game is being run on an OSX machine.
  - **Signature**: boolean IsOSX()

### IsPVEModeActive
  - **Signature**: boolean IsPVEModeActive()

### IsPasstimeMode
  - **Description**: No ball games.
  - **Signature**: boolean IsPasstimeMode()

### IsPlayerABot
  - **Description**: Is this player/entity a bot
  - **Signature**: boolean IsPlayerABot(hscript)

### IsPosix
  - **Description**: Returns true if the game is being run on a Posix machine.
  - **Signature**: boolean IsPosix()

### IsPowerupMode
  - **Description**: Playing powerup mode? Not compatible with MvM
  - **Signature**: boolean IsPowerupMode()

### IsQuickBuildTime
  - **Description**: If an engie places a building, will it immediately upgrade? Eg. MvM pre-round etc.
  - **Signature**: boolean IsQuickBuildTime()

### IsServer
  - **Description**: Returns true if the script is being run on the server.
  - **Signature**: boolean IsServer()

### IsSoundPrecached
  - **Description**: Takes a sound name
  - **Signature**: boolean IsSoundPrecached(cstring)

### IsTeamActive
  - **Signature**: boolean IsTeamActive(integer)

### IsTruceActive
  - **Signature**: boolean IsTruceActive()

### IsUsingGrapplingHook
  - **Signature**: boolean IsUsingGrapplingHook()

### IsUsingSpells
  - **Signature**: boolean IsUsingSpells()

### IsWindows
  - **Description**: Returns true if the game is being run on a Windows machine.
  - **Signature**: boolean IsWindows()

### KeyValuesToFile
  - **Description**: Stores the CScriptKeyValues into the file
  - **Signature**: boolean KeyValuesToFile(cstring, hscript)

### Lerp
  - **Signature**: float Lerp(float, float, float)

### ListenToGameEvent
  - **Description**: Register as a listener for a game event from script.
  - **Signature**: integer ListenToGameEvent(cstring, hscript, cstring)

### LocalTime
  - **Description**: Fills out a table with the local time (second, minute, hour, day, month, year, dayofweek, dayofyear, daylightsavings)
  - **Signature**: void LocalTime(hscript)

### MapHasMatchSummaryStage
  - **Signature**: boolean MapHasMatchSummaryStage()

### Matcher_Match
  - **Description**: Compares a string to a query using Mapbase's matcher system, supporting wildcards, RS matchers, etc.
  - **Signature**: boolean Matcher_Match(cstring, cstring)

### Matcher_NamesMatch
  - **Description**: Compares a string to a query using Mapbase's matcher system using wildcards only.
  - **Signature**: boolean Matcher_NamesMatch(cstring, cstring)

### MatchmakingShouldUseStopwatchMode
  - **Signature**: boolean MatchmakingShouldUseStopwatchMode()

### MatricesAreEqual
  - **Description**: Checks if two matrices are equal.
  - **Signature**: void MatricesAreEqual(hscript, hscript)

### MatrixAngles
  - **Description**: Gets the angles and position of a matrix.
  - **Signature**: void MatrixAngles(hscript, qangle, vector)

### MatrixCopy
  - **Description**: Copies a matrix to another matrix.
  - **Signature**: void MatrixCopy(hscript, hscript)

### MatrixGetColumn
  - **Description**: Gets the column of a matrix.
  - **Signature**: vector MatrixGetColumn(hscript, integer)

### MatrixGetTranslation
  - **Description**: Gets a matrix's translation.
  - **Signature**: vector MatrixGetTranslation(hscript)

### MatrixInvert
  - **Description**: Inverts a matrix and copies the result to another matrix.
  - **Signature**: void MatrixInvert(hscript, hscript)

### MatrixQuaternion
  - **Description**: Converts a matrix to a quaternion.
  - **Signature**: void MatrixQuaternion(hscript, hscript)

### MatrixScaleBy
  - **Description**: Scales a matrix.
  - **Signature**: void MatrixScaleBy(float, hscript)

### MatrixScaleByZero
  - **Description**: Scales a matrix by zero.
  - **Signature**: void MatrixScaleByZero(hscript)

### MatrixSetColumn
  - **Description**: Sets the column of a matrix.
  - **Signature**: void MatrixSetColumn(vector, integer, hscript)

### MatrixSetTranslation
  - **Description**: Sets a matrix's translation.
  - **Signature**: void MatrixSetTranslation(vector, hscript)

### MaxClients
  - **Description**: Get the current number of max clients set by the maxplayers command.
  - **Signature**: float MaxClients()

### MaxPlayers
  - **Description**: Get the maximum number of players allowed on this server
  - **Signature**: integer MaxPlayers()

### Msg
  - **Signature**: void Msg(cstring)

### NPrint
  - **Description**: Notification print
  - **Signature**: void NPrint(integer, cstring)

### NXPrint
  - **Description**: Notification print, customised
  - **Signature**: void NXPrint(integer, integer, integer, integer, boolean, float, cstring)

### NextBotCombatCharacter::ClearImmobileStatus
  - **Description**: Clear immobile status
  - **Signature**: void NextBotCombatCharacter::ClearImmobileStatus()

### NextBotCombatCharacter::FlagForUpdate
  - **Description**: Flag this bot for update
  - **Signature**: void NextBotCombatCharacter::FlagForUpdate(boolean)

### NextBotCombatCharacter::GetBodyInterface
  - **Description**: Get this bot's body interface
  - **Signature**: hscript NextBotCombatCharacter::GetBodyInterface()

### NextBotCombatCharacter::GetBotId
  - **Description**: Get this bot's id
  - **Signature**: integer NextBotCombatCharacter::GetBotId()

### NextBotCombatCharacter::GetImmobileDuration
  - **Description**: How long have we been immobile
  - **Signature**: float NextBotCombatCharacter::GetImmobileDuration()

### NextBotCombatCharacter::GetImmobileSpeedThreshold
  - **Description**: Return units/second below which this actor is considered immobile
  - **Signature**: float NextBotCombatCharacter::GetImmobileSpeedThreshold()

### NextBotCombatCharacter::GetIntentionInterface
  - **Description**: Get this bot's intention interface
  - **Signature**: hscript NextBotCombatCharacter::GetIntentionInterface()

### NextBotCombatCharacter::GetLocomotionInterface
  - **Description**: Get this bot's locomotion interface
  - **Signature**: hscript NextBotCombatCharacter::GetLocomotionInterface()

### NextBotCombatCharacter::GetTickLastUpdate
  - **Description**: Get last update tick
  - **Signature**: integer NextBotCombatCharacter::GetTickLastUpdate()

### NextBotCombatCharacter::GetVisionInterface
  - **Description**: Get this bot's vision interface
  - **Signature**: hscript NextBotCombatCharacter::GetVisionInterface()

### NextBotCombatCharacter::IsEnemy
  - **Description**: Return true if given entity is our enemy
  - **Signature**: boolean NextBotCombatCharacter::IsEnemy(hscript)

### NextBotCombatCharacter::IsFlaggedForUpdate
  - **Description**: Is this bot flagged for update
  - **Signature**: boolean NextBotCombatCharacter::IsFlaggedForUpdate()

### NextBotCombatCharacter::IsFriend
  - **Description**: Return true if given entity is our friend
  - **Signature**: boolean NextBotCombatCharacter::IsFriend(hscript)

### NextBotCombatCharacter::IsImmobile
  - **Description**: Return true if we haven't moved in awhile
  - **Signature**: boolean NextBotCombatCharacter::IsImmobile()

### PhysDisableEntityCollisions
  - **Description**: Disables collisions between two VPhysics objects
  - **Signature**: void PhysDisableEntityCollisions(hscript, hscript)

### PhysEnableEntityCollisions
  - **Description**: Enables collisions between two VPhysics objects
  - **Signature**: void PhysEnableEntityCollisions(hscript, hscript)

### PickupObject
  - **Description**: Have a player pickup a nearby named entity
  - **Signature**: void PickupObject(hscript, hscript)

### PlayerInstanceFromIndex
  - **Description**: Get a script instance of a player by index.
  - **Signature**: hscript PlayerInstanceFromIndex(integer)

### PlayerReadyStatus_ArePlayersOnTeamReady
  - **Signature**: boolean PlayerReadyStatus_ArePlayersOnTeamReady(integer)

### PlayerReadyStatus_HaveMinPlayersToEnable
  - **Signature**: boolean PlayerReadyStatus_HaveMinPlayersToEnable()

### PlayerReadyStatus_ResetState
  - **Signature**: void PlayerReadyStatus_ResetState()

### PlayersAreOnMatchSummaryStage
  - **Signature**: boolean PlayersAreOnMatchSummaryStage()

### PointsMayBeCaptured
  - **Description**: Are points able to be captured?
  - **Signature**: boolean PointsMayBeCaptured()

### PrecacheEntityFromTable
  - **Description**: Precache an entity from KeyValues in a table.
  - **Signature**: function PrecacheEntityFromTable(a, b)

### PrecacheMaterial
  - **Description**: Precaches a material for later usage.
  - **Signature**: void PrecacheMaterial(cstring)

### PrecacheModel
  - **Description**: Precaches a model for later usage.
  - **Signature**: function PrecacheModel(a, b)

### PrecacheOther
  - **Description**: Precaches an entity class for later usage.
  - **Signature**: function PrecacheOther(a, b)

### PrecacheParticleSystem
  - **Description**: Precaches a particle system for later usage.
  - **Signature**: void PrecacheParticleSystem(cstring)

### PrecacheScriptSound
  - **Description**: Precache a sound.
  - **Signature**: boolean PrecacheScriptSound(cstring)

### PrecacheSound
  - **Description**: Precache a sound.
  - **Signature**: boolean PrecacheSound(cstring)

### PredictedPosition
  - **Description**: Predicts what an entity's position will be in a given amount of time.
  - **Signature**: vector PredictedPosition(hscript, float)

### Quaternion::Init
  - **Description**: Creates a quaternion with the given values.
  - **Signature**: void Quaternion::Init(float, float, float, float)

### QuaternionAdd
  - **Description**: Adds two quaternions together into another quaternion.
  - **Signature**: void QuaternionAdd(hscript, hscript, hscript)

### QuaternionAngles
  - **Description**: Converts a quaternion to angles.
  - **Signature**: qangle QuaternionAngles(hscript)

### QuaternionMatrix
  - **Description**: Converts a quaternion to a matrix.
  - **Signature**: void QuaternionMatrix(hscript, hscript)

### RandomFloat
  - **Description**: Generate a random floating point number within a range, inclusive.
  - **Signature**: float RandomFloat(float, float)

### RandomInt
  - **Description**: Generate a random integer within a range, inclusive.
  - **Signature**: integer RandomInt(integer, integer)

### RegisterActivityConstants
  - **Description**: Registers all activity IDs as usable constants.
  - **Signature**: void RegisterActivityConstants()

### RegisterScriptGameEventListener
  - **Description**: Register as a listener for a game event from script.
  - **Signature**: void RegisterScriptGameEventListener(cstring)

### RegisterScriptHookListener
  - **Description**: Register as a listener for a script hook from script.
  - **Signature**: void RegisterScriptHookListener(cstring)

### RemapVal
  - **Signature**: float RemapVal(float, float, float, float, float)

### RemapValClamped
  - **Signature**: float RemapValClamped(float, float, float, float, float)

### RestoreTable
  - **Description**: Retrieves a table from storage. Write into input table.
  - **Signature**: void RestoreTable(cstring, hscript)

### RotateOrientation
  - **Description**: Rotate a QAngle by another QAngle.
  - **Signature**: qangle RotateOrientation(qangle, qangle)

### RotatePosition
  - **Description**: Rotate a Vector around a point.
  - **Signature**: vector RotatePosition(vector, qangle, vector)

### SaveEntityKVToTable
  - **Description**: Saves an entity's keyvalues to a table.
  - **Signature**: void SaveEntityKVToTable(hscript, hscript)

### SaveTable
  - **Description**: Store a table with primitive values that will persist across level transitions and save loads.
  - **Signature**: void SaveTable(cstring, hscript)

### Say
  - **Description**: Have Entity say string, and teamOnly or not
  - **Signature**: void Say(hscript, cstring, boolean)

### ScreenFade
  - **Description**: Start a screenfade with the following parameters. player, red, green, blue, alpha, flFadeTime, flFadeHold, flags
  - **Signature**: void ScreenFade(hscript, integer, integer, integer, integer, float, float, integer)

### ScreenShake
  - **Description**: Start a screenshake with the following parameters. vecCenter, flAmplitude, flFrequency, flDuration, flRadius, eCommand( SHAKE_START = 0, SHAKE_STOP = 1 ), bAirShake
  - **Signature**: void ScreenShake(vector, float, float, float, float, integer, boolean)

### ScriptHooksEnabled
  - **Description**: Returns whether script hooks are currently enabled.
  - **Signature**: boolean ScriptHooksEnabled()

### SendGlobalGameEvent
  - **Description**: Sends a real game event to everything. Parameters are passed in a squirrel table.
  - **Signature**: boolean SendGlobalGameEvent(cstring, hscript)

### SendToConsole
  - **Description**: Send a string to the console as a command
  - **Signature**: void SendToConsole(cstring)

### SendToConsoleServer
  - **Description**: Copy of SendToServerConsole with another name for compat.
  - **Signature**: void SendToConsoleServer(cstring)

### SendToServerConsole
  - **Description**: Send a string that gets executed on the server as a ServerCommand. Respects sv_allow_point_servercommand.
  - **Signature**: void SendToServerConsole(cstring)

### SetDefaultActiveTeams
  - **Signature**: void SetDefaultActiveTeams()

### SetFakeClientConVarValue
  - **Description**: Sets a USERINFO client ConVar for a fakeclient
  - **Signature**: void SetFakeClientConVarValue(hscript, cstring, cstring)

### SetGravityMultiplier
  - **Signature**: void SetGravityMultiplier(float)

### SetIdentityMatrix
  - **Description**: Turns a matrix into an identity matrix.
  - **Signature**: void SetIdentityMatrix(hscript)

### SetMannVsMachineAlarmStatus
  - **Signature**: void SetMannVsMachineAlarmStatus(boolean)

### SetOvertimeAllowedForCTF
  - **Signature**: void SetOvertimeAllowedForCTF(boolean)

### SetPhysVelocity
  - **Description**: Sets physics velocity for the given VPhysics object
  - **Signature**: void SetPhysVelocity(hscript, vector, vector)

### SetPlayersInHell
  - **Signature**: void SetPlayersInHell(boolean)

### SetScaleMatrix
  - **Description**: Builds a scale matrix.
  - **Signature**: void SetScaleMatrix(float, float, float, hscript)

### SetSkyboxTexture
  - **Description**: Sets the current skybox texture
  - **Signature**: void SetSkyboxTexture(cstring)

### SetUsingSpells
  - **Signature**: void SetUsingSpells(boolean)

### ShowMessage
  - **Description**: Print a hud message on all clients
  - **Signature**: void ShowMessage(cstring)

### SimpleSpline
  - **Signature**: float SimpleSpline(float)

### SimpleSplineRemapVal
  - **Description**: remaps a value in \[startInterval, startInterval+rangeInterval] from linear to spline using SimpleSpline
  - **Signature**: float SimpleSplineRemapVal(float, float, float, float, float)

### SimpleSplineRemapValClamped
  - **Description**: remaps a value in \[startInterval, startInterval+rangeInterval] from linear to spline using SimpleSpline
  - **Signature**: float SimpleSplineRemapValClamped(float, float, float, float, float)

### SmoothCurve
  - **Description**: SmoothCurve maps a 0-1 value into another 0-1 value based on a cosine wave
  - **Signature**: float SmoothCurve(float)

### SmoothCurve_Tweak
  - **Description**: SmoothCurve peaks at flPeakPos, flPeakSharpness controls the sharpness of the peak
  - **Signature**: float SmoothCurve_Tweak(float, float, float)

### SpawnEntityFromKeyValues
  - **Description**: Spawns an entity with the keyvalues in a CScriptKeyValues handle.
  - **Signature**: hscript SpawnEntityFromKeyValues(cstring, hscript)

### SpawnEntityFromTable
  - **Description**: Native function for entity spawning.
  - **Signature**: hscript SpawnEntityFromTable(cstring, hscript)

### StopAmbientSoundOn
  - **Description**: Stop named ambient sound on an entity.
  - **Signature**: void StopAmbientSoundOn(cstring, hscript)

### StopListeningToAllGameEvents
  - **Description**: Stop listening to all game events within a specific context.
  - **Signature**: void StopListeningToAllGameEvents(cstring)

### StopListeningToGameEvent
  - **Description**: Stop the specified event listener.
  - **Signature**: boolean StopListeningToGameEvent(integer)

### StopSoundOn
  - **Description**: Stop named sound on Entity.
  - **Signature**: void StopSoundOn(cstring, hscript)

### StringToFile
  - **Description**: Stores the string into the file
  - **Signature**: boolean StringToFile(cstring, cstring)

### Time
  - **Description**: Get the current server time
  - **Signature**: float Time()

### TraceHull
  - **Description**: Pass table - Inputs: start, end, hullmin, hullmax, mask, ignore  -- outputs: pos, fraction, hit, enthit, allsolid, startpos, endpos, startsolid, plane_normal, plane_dist, surface_name, surface_flags, surface_props
  - **Signature**: boolean TraceHull(hscript)

### TraceHullComplex
  - **Description**: Takes 2 points, min/max hull bounds, an ent to ignore, a trace mask, and a collision group to trace to a point using a hull. Returns a handle which can access all trace info.
  - **Signature**: hscript TraceHullComplex(vector, vector, vector, vector, hscript, integer, integer)

### TraceLine
  - **Description**: given 2 points & ent to ignore, return fraction along line that hits world or models
  - **Signature**: float TraceLine(vector, vector, hscript)

### TraceLineComplex
  - **Description**: Complex version of TraceLine which takes 2 points, an ent to ignore, a trace mask, and a collision group. Returns a handle which can access all trace info.
  - **Signature**: hscript TraceLineComplex(vector, vector, hscript, integer, integer)

### TraceLineEx
  - **Description**: Pass table - Inputs: start, end, mask, ignore  -- outputs: pos, fraction, hit, enthit, allsolid, startpos, endpos, startsolid, plane_normal, plane_dist, surface_name, surface_flags, surface_props
  - **Signature**: boolean TraceLineEx(hscript)

### TraceLinePlayersIncluded
  - **Description**: given 2 points & ent to ignore, return fraction along line that hits world, models, players or npcs
  - **Signature**: float TraceLinePlayersIncluded(vector, vector, hscript)

### UniqueString
  - **Description**: Generate a string guaranteed to be unique across the life of the script VM, with an optional root string. Useful for adding data to tables when not sure what keys are already in use in that table.
  - **Signature**: function UniqueString(string)

### UsePlayerReadyStatusMode
  - **Signature**: boolean UsePlayerReadyStatusMode()

### Vector::Cross
  - **Description**: Return the vector product of two vectors.
  - **Signature**: float Vector::Cross(vector)

### Vector::Dot
  - **Description**: Return the dot/scalar product of two vectors.
  - **Signature**: float Vector::Dot(vector)

### Vector::Length
  - **Description**: Return the vector's length.
  - **Signature**: float Vector::Length()

### Vector::Length2D
  - **Description**: Return the vector's 2D length.
  - **Signature**: float Vector::Length2D()

### Vector::Length2DSqr
  - **Description**: Return the vector's squared 2D length.
  - **Signature**: float Vector::Length2DSqr()

### Vector::LengthSqr
  - **Description**: Return the vector's squared length.
  - **Signature**: float Vector::LengthSqr()

### Vector::Norm
  - **Description**: Normalize the vector in place.
  - **Signature**: void Vector::Norm()

### Vector::Normalized
  - **Description**: Return a normalized version of the vector.
  - **Signature**: float Vector::Normalized()

### Vector::Scale
  - **Description**: Scale the vector's magnitude and return the result.
  - **Signature**: vector Vector::Scale(float)

### Vector::ToKVString
  - **Description**: Return a vector as a string in KeyValue form, without separation commas.
  - **Signature**: string Vector::ToKVString()

### VectorAngles
  - **Description**: Turns a direction vector into an angle.
  - **Signature**: qangle VectorAngles(vector)

### VectorIRotate
  - **Description**: Rotates a vector with the inverse of a matrix.
  - **Signature**: vector VectorIRotate(vector, hscript)

### VectorITransform
  - **Description**: Transforms a vector with the inverse of a matrix.
  - **Signature**: vector VectorITransform(vector, hscript)

### VectorRotate
  - **Description**: Rotates a vector with a matrix.
  - **Signature**: vector VectorRotate(vector, hscript)

### VectorTransform
  - **Description**: Transforms a vector with a matrix.
  - **Signature**: vector VectorTransform(vector, hscript)

### clamp
  - **Signature**: float clamp(float, float, float)

### csurface_t::Name
  - **Signature**: cstring csurface_t::Name()

### csurface_t::SurfaceProps
  - **Description**: The surface's properties.
  - **Signature**: hscript csurface_t::SurfaceProps()

### matrix3x4_t::Init
  - **Description**: Creates a matrix where the X axis = forward, the Y axis = left, and the Z axis = up.
  - **Signature**: void matrix3x4_t::Init(vector, vector, vector, vector)

### max
  - **Signature**: float max(float, float)

### min
  - **Signature**: float min(float, float)

### printc
  - **Description**: Version of print() which takes a color before the message.
  - **Signature**: void printc(integer, integer, integer, cstring)

### printcl
  - **Description**: Version of printl() which takes a color before the message.
  - **Signature**: void printcl(integer, integer, integer, cstring)

### scriptanimevent_t::GetCycle
  - **Signature**: float scriptanimevent_t::GetCycle()

### scriptanimevent_t::GetEvent
  - **Signature**: integer scriptanimevent_t::GetEvent()

### scriptanimevent_t::GetEventTime
  - **Signature**: float scriptanimevent_t::GetEventTime()

### scriptanimevent_t::GetOptions
  - **Signature**: cstring scriptanimevent_t::GetOptions()

### scriptanimevent_t::GetSource
  - **Description**: Gets the event's source entity.
  - **Signature**: hscript scriptanimevent_t::GetSource()

### scriptanimevent_t::GetType
  - **Description**: Gets the event's type flags. See the 'AE_TYPE_' set of constants for valid flags.
  - **Signature**: integer scriptanimevent_t::GetType()

### scriptanimevent_t::SetCycle
  - **Signature**: void scriptanimevent_t::SetCycle(float)

### scriptanimevent_t::SetEvent
  - **Signature**: void scriptanimevent_t::SetEvent(integer)

### scriptanimevent_t::SetEventTime
  - **Signature**: void scriptanimevent_t::SetEventTime(float)

### scriptanimevent_t::SetOptions
  - **Signature**: void scriptanimevent_t::SetOptions(cstring)

### scriptanimevent_t::SetSource
  - **Description**: Sets the event's source entity.
  - **Signature**: void scriptanimevent_t::SetSource(hscript)

### scriptanimevent_t::SetType
  - **Description**: Sets the event's type flags. See the 'AE_TYPE_' set of constants for valid flags.
  - **Signature**: void scriptanimevent_t::SetType(integer)

### surfacedata_t::GetFriction
  - **Signature**: float surfacedata_t::GetFriction()

### surfacedata_t::GetJumpFactor
  - **Signature**: float surfacedata_t::GetJumpFactor()

### surfacedata_t::GetMaterialChar
  - **Signature**: character surfacedata_t::GetMaterialChar()

### surfacedata_t::GetSoundBreak
  - **Signature**: cstring surfacedata_t::GetSoundBreak()

### surfacedata_t::GetSoundBulletImpact
  - **Signature**: cstring surfacedata_t::GetSoundBulletImpact()

### surfacedata_t::GetSoundImpactHard
  - **Signature**: cstring surfacedata_t::GetSoundImpactHard()

### surfacedata_t::GetSoundImpactSoft
  - **Signature**: cstring surfacedata_t::GetSoundImpactSoft()

### surfacedata_t::GetSoundRolling
  - **Signature**: cstring surfacedata_t::GetSoundRolling()

### surfacedata_t::GetSoundScrapeRough
  - **Signature**: cstring surfacedata_t::GetSoundScrapeRough()

### surfacedata_t::GetSoundScrapeSmooth
  - **Signature**: cstring surfacedata_t::GetSoundScrapeSmooth()

### surfacedata_t::GetSoundStepLeft
  - **Signature**: cstring surfacedata_t::GetSoundStepLeft()

### surfacedata_t::GetSoundStepRight
  - **Signature**: cstring surfacedata_t::GetSoundStepRight()

### surfacedata_t::GetSoundStrain
  - **Signature**: cstring surfacedata_t::GetSoundStrain()

### surfacedata_t::GetThickness
  - **Signature**: float surfacedata_t::GetThickness()
