firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Executed!")
firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "exploit0005 and Muh")
firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "This is still developed, don't go in ur dms and say it's broken")
firesignal(game.ReplicatedStorage.Bricks.Caption.OnClientEvent, "Executed!  Enjoy, fatties")


if game:GetService("ReplicatedStorage"):FindFirstChild("HardCoreIntForExploitandMosHardcore") then
    warn("You have Already Loaded")

    return false
end
local Test = Instance.new("Part")
Test.Name = "HardCoreIntForExploitandMosHardcore"
Test.Parent = game:GetService("ReplicatedStorage")
Test = nil







local HardCore = {
    Title = "The Pain!", 
    Desc = "Join a Match of HardCore For the First Time.",
    Reason = "You executed the Hardcore script.",
    Image = "https://github.com/MuhXd/Models/blob/main/HardCoreDoors.png?raw=true",
    id = 1,
}


local ModName = "HardCoreForExploitandMosHardcore"
local foldername = "HardCoreIntForExploitandMosHardcore"
local Slipt = string.split(foldername,"|")
local valid2 = isfolder(foldername)
if not valid2 then
    makefolder(foldername)
end

local fileName = "ExtraInfo.txt"
local filePath = foldername.. "/".. fileName
local valid = isfile(filePath)

local Achievements = loadstring(game:HttpGet("https://raw.githubusercontent.com/MuhXd/Models/main/RegularVynixu's%20Achievement%20Modifyer"))()

function AchievementsGet(Achievement)
    local read = readfile(filePath)  
    local read2 = tostring(read)
    local read2 = string.split(read,"|")
    FOUND = false
    Find = ""
    for i,v in pairs(Achievement) do
        if i == "id" then
            Find=Find.." "..v
        end
    end

    for i,v in pairs(read2) do
        if v == Find then
            FOUND = true
        end
    end -- Desc
    if FOUND == false then
        Achievements.Get(Achievement)
        Write = ""
        for i,v in pairs(Achievement) do
            if i == "id" then
                Write=Write.." "..v
            end
        end
        appendfile(filePath,Write.."|")
    end
end
-- Creates and displays your custom achievement
-- readfile(<string> path)  
if not valid then
    writefile(filePath, "Exploit is Goat")
end

AchievementsGet(HardCore)



game:GetService("ReplicatedStorage").GameData.LatestRoom.Changed:Connect(function(v)
    L = game:GetService("Workspace").CurrentRooms[v].PathfindNodes:Clone()
    L.Parent = game:GetService("Workspace").CurrentRooms[v]
    L = game:GetService("Workspace").CurrentRooms[v].PathfindNodes:Clone()
    L.Parent = game:GetService("Workspace").CurrentRooms[v]
    L.Name = 'Nodes'
end)
function ChangeRoomModel(room)
    
for i,v in pairs(room:GetDescendants()) do
    if v.Parent.Name ~= 'Colors' then
   
    if v.Name == "Wall" or  v.Name == "WallAlt"  then
        v.Material = Enum.Material.Limestone
        v.Color = Color3.new(0.3411764705882353, 0.3333333333333333, 0.3333333333333333)
elseif v.Name == "Wall_Strip"  or v.Name == 'Wall_StripALT' then
        v.Material = Enum.Material.Limestone
        v.Color = Color3.new(0.3411764705882353, 0.3333333333333333, 0.3333333333333333)   
elseif v.Name == 'StonePillar' then
    v:Destroy()
end 
end
end
end

local SelfModules = {
    Functions = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Functions.lua"))(),
}
local GoodTest = LoadCustomInstance or false

if GoodTest == false then
    error("Unable to Find GetObjects :(")
else
game.ReplicatedStorage.GameData.LatestRoom.Changed:Connect(function(latestroom)
    local roomlatestworkspace = workspace.CurrentRooms[latestroom]
    ChangeRoomModel(roomlatestworkspace) 
end)
local roomlatestworkspace = workspace.CurrentRooms[game.ReplicatedStorage.GameData.LatestRoom.Value]
ChangeRoomModel(roomlatestworkspace) 
    game.ReplicatedStorage.GameData.LatestRoom.Changed:Wait()
end




print('Loaded')
Char =  game:GetService("Players").LocalPlayer.Character
LocalPlayer = game:GetService("Players").LocalPlayer
local function GetGitSound(GithubSnd,SoundName)
	SoundName=tostring(SoundName)
	local url=GithubSnd
	FileName = SoundName
	writefile("customObject_Sound_"..FileName..".mp3", game:HttpGet(url))

	local sound=Instance.new("Sound")
	sound.SoundId=(getcustomasset or getsynasset)("customObject_Sound_"..FileName..".mp3")
	return sound
end

function SpawnControl()
PlayWisp = GetGitSound('https://github.com/MuhXd/Models/blob/main/small-group-whispering.mp3?raw=true','ControlSound')
PlayWisp.Looped = true
PlayWisp.Volume = 1
    PlayWisp.Parent = Char.Head
    PlayWisp:Play()
        local Color = Instance.new("ColorCorrectionEffect",game.Lighting) game.Debris:AddItem(Color,24)
        Color.Name = "ColorWarn"
        Color.TintColor = Color3.fromRGB(150, 0, 0) Color.Saturation = -0.7 Color.Contrast = 0.2
        ModuleEvents = require(game:GetService("ReplicatedStorage").ClientModules.Module_Events)
        ModuleEvents.flicker(workspace.CurrentRooms[game:GetService("ReplicatedStorage").GameData.LatestRoom.Value],3)
        --- Spawns Entity
    local Entity = LoadCustomInstance('https://github.com/MuhXd/Models/blob/main/Template.rbxm?raw=true') or nil
    Entity.Attachment.Face.Texture = LoadCustomAsset('https://github.com/MuhXd/Images/blob/main/imageasasasasas.png?raw=true') or nil
    for laaaaaaaaaaaa=1,5 do
    blacknesss = Entity.Attachment.BlackTrail:Clone()
    blacknesss.Parent = Entity.Attachment
    end
    Entity.Name=math.random(1,100)..math.random(1,100)..math.random(1,100)..math.random(1,100)..math.random(1,100)..math.random(1,100)
    nodes = game:GetService("Workspace").CurrentRooms[game.ReplicatedStorage.GameData.LatestRoom.Value].PathfindNodes:GetChildren()
    local function round(n)
        return math.floor(n + 0.5)
    end
    
    MiddelNodea = round(#nodes/2) -- Middel Node

    
    MiddelNode= game:GetService("Workspace").CurrentRooms[game.ReplicatedStorage.GameData.LatestRoom.Value].PathfindNodes[MiddelNodea]


-- Sets to Corect Node
task.wait(0.5)
if MiddelNode.Name == '1' then
    Entity.Position = (MiddelNode.Position + Vector3.new(3,5,3)) 
else
Entity.Position = (MiddelNode.Position + Vector3.new(0,5,0))
end
Entity.Parent = game:GetService("Workspace")
task.wait(2)

i=1
repeat
  
coroutine.wrap(function()
    -- Kills Player 
    if  Char.Humanoid.MoveDirection ~= Vector3.new(0,0,0) and not Char:GetAttribute("IsDead")   then
        Char:SetAttribute("IsDead")
        game:GetService("ReplicatedStorage").GameStats["Player_".. LocalPlayer.Name].Total.DeathCause.Value = "Control"
        firesignal(game:GetService("ReplicatedStorage").EntityInfo.DeathHint.OnClientEvent, {"You died to Control."," It only appears when the lights flicker in an dark red colour."," It will appear in the middle of the room, what you must do is stay still"},'Blue')
        Char.Humanoid.Health = 0
        firesignal(game:GetService("ReplicatedStorage").EntityInfo.DeathHint.OnClientEvent, {"You died to Control."," It only appears when the lights flicker in an dark red colour."," It will appear in the middle of the room, what you must do is stay still"},'Blue')
        elseif  Char:GetAttribute("Hiding") and  not Char:GetAttribute("IsDead") then
            Char:SetAttribute("IsDead")
            game:GetService("ReplicatedStorage").GameStats["Player_".. LocalPlayer.Name].Total.DeathCause.Value = "Control"
            firesignal(game:GetService("ReplicatedStorage").EntityInfo.DeathHint.OnClientEvent, {"You died to Control."," It only appears when the lights flicker in an dark red colour."," It will appear in the middle of the room, what you must do is stay still","Do not Hide In a Closet, Even If your Standing still"},'Blue')
            Char.Humanoid.Health = 0
            firesignal(game:GetService("ReplicatedStorage").EntityInfo.DeathHint.OnClientEvent, {"You died to Control."," It only appears when the lights flicker in an dark red colour."," It will appear in the middle of the room, what you must do is stay still","Do not Hide In a Closet, Even If your Standing still"},'Blue')
        end
    --
end)()
wait(1)
    i=i+1
until i==15
i=1
PlayWisp:Stop()
PlayWisp.Parent = workspace
Entity:Destroy()
Color:Destroy()

end



coroutine.wrap(function()
while task.wait(5) do
    game.ReplicatedStorage.GameData.LatestRoom.Changed:Wait()
    task.wait(15)
    game.ReplicatedStorage.GameData.LatestRoom.Changed:Wait()
    task.wait(15)
    game.ReplicatedStorage.GameData.LatestRoom.Changed:Wait()
    task.wait(30)
    game.ReplicatedStorage.GameData.LatestRoom.Changed:Wait()
    task.wait(10)
    SpawnControl()
end
end)()
-- Create entity
local entityTable = Spawner.createEntity({
CustomName = "Dread", -- Custom name of your entity
Model = "rbxassetid://12401716327", -- Can be GitHub file or rbxassetid
Speed = 100, -- Percentage, 100 = default Rush speed
DelayTime = 2, -- Time before starting cycles (seconds)
HeightOffset = 0,
CanKill = true,
KillRange = 50,
BackwardsMovement = false,
BreakLights = true,
FlickerLights = {
true, -- Enabled/Disabled
1, -- Time (seconds)
},
Cycles = {
Min = 1,
Max = 4,
WaitTime = 2,
},
CamShake = {
true, -- Enabled/Disabled
{3.5, 20, 0.1, 1}, -- Shake values (don't change if you don't know)
100, -- Shake start distance (from Entity to you)
},
Jumpscare = {
false, -- Enabled/Disabled
{
Image1 = "rbxassetid://10483855823", -- Image1 url
Image2 = "rbxassetid://10483999903", -- Image2 url
Shake = true,
Sound1 = {
10483790459, -- SoundId
{ Volume = 0.5 }, -- Sound properties
},
Sound2 = {
10483837590, -- SoundId
{ Volume = 0.5 }, -- Sound properties
},
Flashing = {
true, -- Enabled/Disabled
Color3.fromRGB(255, 255, 255), -- Color
},
Tease = {
true, -- Enabled/Disabled
Min = 1,
Max = 3,
},
},
},
CustomDialog = {"You died to the one you call Dread...", "I haven't seen this one before.", "It seems to mimic ambush.", "Use what you learned from it."}, -- Custom death message
})


-----[[ Debug -=- Advanced ]]-----
entityTable.Debug.OnEntitySpawned = function()
print("Entity has spawned:", entityTable)
end

entityTable.Debug.OnEntityDespawned = function()
print("Entity has despawned:", entityTable)
end

entityTable.Debug.OnEntityStartMoving = function()
print("Entity has started moving:", entityTable)
end

entityTable.Debug.OnEntityFinishedRebound = function()
print("Entity has finished rebound:", entityTable)
end

entityTable.Debug.OnEntityEnteredRoom = function(room)
print("Entity:", entityTable, "has entered room:", room)
end

entityTable.Debug.OnLookAtEntity = function()
print("Player has looked at entity:", entityTable)
end

entityTable.Debug.OnDeath = function()
warn("Player has died.")
end
------------------------------------


