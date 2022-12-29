﻿CallbackType: `AfterModsLoaded`  
=======  
Method type: System.Action<System.Collections.Generic.List<ModLoader.ModDescription>>  
Called after parsing all modinfo files  
No registered uses  


CallbackType: `OnItemTypeRegistered`  
=======  
Method type: System.Action<ItemTypes.ItemType>  
Called once for each type that is being registered to ItemTypes  
Registered callbacks: 1  
0.	'pipliz.client.processitemtype' -> 'ItemTypesClient+Callbacks.OnItemTypeRegistered'   


CallbackType: `OnUpdateStart`  
=======  
Method type: System.Action  
Called early on in unity's Update method  
Registered callbacks: 3  
0.	'threadphase.startmainthreadonly' -> 'ThreadPhase+Callbacks.OnUpdateStart' index: -1000000  
1.	'pipliz.server.setsecondsthisframe' -> 'Pipliz.Time.SetThisFrame' index: -1000  
2.	'mainthreadactions' -> 'ThreadManager+Callbacks.OnUpdateStart' index: -100  


CallbackType: `OnUpdate`  
=======  
Method type: System.Action  
Registered callbacks: 21  
0.	'network.receivepackets' -> 'ClientWrapper+Callbacks.OnUpdate' index: -1000  
1.	'controlledmeshes.update' -> 'Client.ControlledMeshes.ControlledMeshes+Callbacks.OnUpdate'   
		 Child @ 3 : 'controller.updatestatic'  
2.	'input.process' -> 'InputManager+Callbacks.OnUpdate' index: -500  
		 Parent @ 1 : 'controlledmeshes.update'  
3.	'controller.updatestatic' -> 'PlayerController+Callbacks.OnUpdate' index: -350  
4.	'playerbody.updatestatic' -> 'PlayerBody+Callbacks.OnUpdate' index: -300  
5.	'controller.updateoffset' -> 'PlayerController+Callbacks2.OnUpdate' index: -250  
6.	'world.checkorigin' -> 'World+Callbacks.OnUpdate' index: -200  
7.	'AudioManager+Callbacks.OnUpdate' -> 'AudioManager+Callbacks.OnUpdate'   
8.	'update_receiveratetracker' -> 'ChunkRequests+Callbacks2.OnUpdate'   
9.	'ChunkManager+Callbacks.OnUpdate' -> 'ChunkManager+Callbacks.OnUpdate'   
		 Parent @ 8 : 'update_receiveratetracker'  
10.	'ChunkRequests+Callbacks.OnUpdate' -> 'ChunkRequests+Callbacks.OnUpdate'   
11.	'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnUpdate' -> 'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnUpdate'   
12.	'CursorWrapper+Callbacks.OnUpdate' -> 'CursorWrapper+Callbacks.OnUpdate'   
13.	'draw_on_npc_debug' -> 'Pipliz.Tools.ToolJobs.OnNPCUpdate'   
14.	'heartbeattracker.update' -> 'CongestionTracker+Callbacks.OnUpdate'   
15.	'NPC.NPCManager+Callbacks.OnUpdate' -> 'NPC.NPCManager+Callbacks.OnUpdate'   
16.	'pipliz.client.ragdollupdate' -> 'ColonySurvival.Client.RagdollTracker.Update'   
17.	'Pipliz.Tools.HoverCheck.OnUpdate' -> 'Pipliz.Tools.HoverCheck.OnUpdate'   
18.	'pipliz.updateparticles' -> 'ParticleManager.UpdateParticles'   
19.	'SteamManager+Callbacks.OnUpdate' -> 'SteamManager+Callbacks.OnUpdate'   
20.	'WorldContext+Callbacks.OnUpdate' -> 'WorldContext+Callbacks.OnUpdate'   


CallbackType: `OnUpdateEnd`  
=======  
Method type: System.Action  
Registered callbacks: 4  
0.	'update_selected_type' -> 'Inventory+Callbacks.OnUpdateEnd'   
1.	'mainthreadactions' -> 'ThreadManager+Callbacks.OnUpdateEnd' index: 100  
2.	'network.flushpackets' -> 'ClientWrapper+Callbacks.OnUpdateEnd' index: 1000  
3.	'threadphase.endmainthreadonly' -> 'ThreadPhase+Callbacks.OnUpdateEnd' index: 1000000  


CallbackType: `OnLateUpdate`  
=======  
Method type: System.Action  
Called inside unity's LateUpdate method  
Registered callbacks: 3  
0.	'flush_controlledmesh_input' -> 'Client.ControlledMeshes.ControlledMeshes.UpdateInput'   
1.	'render_areas' -> 'Pipliz.AI.Areas.AreaTracker+AreasRenderer.Render'   
2.	'update_networkbody' -> 'NetworkBody.AllInterpolate'   


CallbackType: `AfterItemTypesDefined`  
=======  
Method type: System.Action  
Registered callbacks: 1  
0.	'create_lut_texture' -> 'Rendering.CreateLUTTexture'   


CallbackType: `OnQuit`  
=======  
Method type: System.Action  
Called in the quit method queue  
Registered callbacks: 14  
0.	'pipliz.shared.waitforasyncquitsearly' -> 'Pipliz.Application.WaitForQuits' index: -1000  
1.	'ChunkManager+Callbacks.OnQuit' -> 'ChunkManager+Callbacks.OnQuit'   
2.	'ChunkRequests+Callbacks.OnQuit' -> 'ChunkRequests+Callbacks.OnQuit'   
3.	'Clear temp file cache' -> 'GameManager.ClearCache'   
4.	'dispose colorbuffers' -> 'PipBurst+ColorBuffer.DisposePool'   
5.	'dispose gamemanager' -> 'GameManager.Dispose'   
6.	'ItemTypesClient+Callbacks.OnQuit' -> 'ItemTypesClient+Callbacks.OnQuit'   
7.	'Rendering+Callbacks.OnQuit' -> 'Rendering+Callbacks.OnQuit'   
8.	'VoxelPhysics+Callbacks.OnQuit' -> 'VoxelPhysics+Callbacks.OnQuit'   
9.	'WorldRenderer+Callbacks.OnQuit' -> 'WorldRenderer+Callbacks.OnQuit'   
10.	'steamnetworking.close' -> 'Pipliz.Networking.SteamNetworking+ModRegistering.OnQuit' index: 1  
11.	'pipliz.jointhreads' -> 'Pipliz.Threading.ThreadSafeQuitWrapper.JoinThread' index: 500  
12.	'pipliz.shared.waitforasyncquitslate' -> 'Pipliz.Application.WaitForQuits' index: 1000  
13.	'LZ4DecoderFreeing' -> 'Pipliz.LZ4.LZ4Codec+Callbacks.OnQuit' index: 10000  


CallbackType: `OnConnectionScreenDone`  
=======  
Method type: System.Action  
No registered uses  


CallbackType: `OnMainMenuLoaded`  
=======  
Method type: System.Action  
Registered callbacks: 26  
0.	'ChunkManager+Callbacks.OnMainMenuLoaded' -> 'ChunkManager+Callbacks.OnMainMenuLoaded'   
1.	'ChunkRequests+Callbacks.OnMainMenuLoaded' -> 'ChunkRequests+Callbacks.OnMainMenuLoaded'   
2.	'clear_label_cache' -> 'colonyclient.Assets.Scripts.UI.Ingame.UIGeneration.UILabel.ClearCache'   
3.	'clear_lut_texture' -> 'Rendering.ClearLUTTexture'   
4.	'clear_uiimage_cache' -> 'colonyclient.Assets.Scripts.UI.Ingame.UIGeneration.UIImage.ClearCache'   
5.	'clear_worldmarker_cache' -> 'colonyclient.Assets.Scripts.UI.Ingame.UIGeneration.WorldMarker.ClearCache'   
6.	'collidergen.reset' -> 'ColonySurvival.Client.Physics.ColliderGeneration.Reset'   
7.	'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnMainMenuLoaded' -> 'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnMainMenuLoaded'   
8.	'heartbeattracker.reset' -> 'CongestionTracker+Callbacks.OnMainMenuLoaded'   
9.	'pipliz.client.clearactionqueue' -> 'Shared.ItemManagementAction+ActionQueue.Clear'   
10.	'pipliz.client.clearaudiomanager' -> 'AudioManager.Clear'   
11.	'pipliz.client.clearnpcmaterial' -> 'NPCMaterial.ClearNPCMaterial'   
12.	'pipliz.client.clearterrainmaterial' -> 'TerrainMaterial.ClearTerrainMaterial'   
13.	'pipliz.client.clearwatermaterial' -> 'WaterMaterial.ClearMaterial'   
14.	'pipliz.client.gamemanagerclear' -> 'GameManager.OnMainMenuLoaded'   
15.	'pipliz.client.refreshlocale' -> 'GameManager.RefreshLocale'   
16.	'pipliz.client.resetareatracker' -> 'Pipliz.AI.Areas.AreaTracker+FilledAreaRenderer.Reset'   
17.	'pipliz.client.resetbanners' -> 'Client.Rendering.BannerRenderer.Reset'   
18.	'pipliz.client.resetinventory' -> 'Inventory.Release'   
19.	'pipliz.client.resetprojectiles' -> 'Projectile.Clear'   
20.	'pipliz.client.servercontrolledmeshes.resetsettingstable' -> 'Client.ControlledMeshes.MeshTypeSettings.OnReloaded'   
21.	'pipliz.resetparticlemanager' -> 'ParticleManager.Reset'   
22.	'reset_controlledmeshes' -> 'Client.ControlledMeshes.ControlledMeshes.Reset'   
23.	'reset_npc_debug' -> 'Pipliz.Tools.ToolJobs.OnNPCReset'   
24.	'resetcrafting' -> 'Crafting.Reset'   
25.	'VoxelPhysics+Callbacks.OnMainMenuLoaded' -> 'VoxelPhysics+Callbacks.OnMainMenuLoaded'   


CallbackType: `OnOriginShift`  
=======  
Method type: System.Action<Pipliz.Vector3Int>  
Registered callbacks: 8  
0.	'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnOriginShift' -> 'ColonySurvival.Client.UI.Ingame.NPCIndicator+Callbacks.OnOriginShift'   
1.	'pipliz.client.collidergenerationmove' -> 'ColonySurvival.Client.Physics.ColliderGeneration.OnShift'   
2.	'pipliz.client.npcbodyshift' -> 'NPC.NPCBase+Statics.OnOriginShift'   
3.	'pipliz.client.playeroriginshift' -> 'PlayerBody.OnShift'   
4.	'pipliz.client.projectilesshift' -> 'Projectile.OnShift'   
5.	'pipliz.client.ragdollmove' -> 'ColonySurvival.Client.RagdollTracker.OnShift'   
6.	'pipliz.client.shiftaudio' -> 'AudioManager.Shift'   
7.	'pipliz.shiftparticles' -> 'ParticleManager.Shift'   


CallbackType: `OnPlayerPositionReceived`  
=======  
Method type: System.Action<UnityEngine.Vector3>  
Registered callbacks: 1  
0.	'ChunkRequests+Callbacks.OnPlayerPositionReceived' -> 'ChunkRequests+Callbacks.OnPlayerPositionReceived'   


CallbackType: `OnNetworkButtonPress`  
=======  
Method type: System.Action<string, Newtonsoft.Json.Linq.JToken>  
No registered uses  


CallbackType: `OnEndReadOnly`  
=======  
Method type: System.Action  
Registered callbacks: 2  
0.	'ChunkManager+Callbacks.OnEndReadOnly' -> 'ChunkManager+Callbacks.OnEndReadOnly'   
1.	'Lighting.LightingManager+Callbacks.OnEndReadOnly' -> 'Lighting.LightingManager+Callbacks.OnEndReadOnly'   


CallbackType: `OnStartReadOnly`  
=======  
Method type: System.Action  
Registered callbacks: 3  
0.	'Lighting.LightingManager+Callbacks.OnStartReadOnly' -> 'Lighting.LightingManager+Callbacks.OnStartReadOnly'   
1.	'WorldRenderer+Callbacks.OnStartReadOnly' -> 'WorldRenderer+Callbacks.OnStartReadOnly'   
2.	'mesher.startjobs' -> 'ChunkManager+Callbacks.OnStartReadOnly' index: 100  


CallbackType: `OnStartMainthread`  
=======  
Method type: System.Action  
No registered uses  


CallbackType: `OnEndMainthread`  
=======  
Method type: System.Action  
No registered uses  


CallbackType: `OnBlockChange`  
=======  
Method type: System.Action<Callbacks.BlockChangeData>  
Registered callbacks: 2  
0.	'ColonySurvival.Client.Physics.ColliderGeneration+Callbacks.OnBlockChange' -> 'ColonySurvival.Client.Physics.ColliderGeneration+Callbacks.OnBlockChange'   
1.	'Lighting.LightingManager+Callbacks.OnBlockChange' -> 'Lighting.LightingManager+Callbacks.OnBlockChange'   

