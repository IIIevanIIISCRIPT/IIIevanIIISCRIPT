# IIIevanIII00-Cmds-V5
| 5.1.x   | :white_check_mark: |
Config files for my GitHub profile.

local A_1 = "Cmds-By-IIIevanIII00-V5"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)

local A_1 = "~~Thx For Use Me Cmds~~"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)



repeat wait(3) until game:IsLoaded()

           game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Use  *cmds and check Console 'Info' by Pressing F9 and Welcome to Trxsh gang(Trash)";
 
})

local function babaidle()
    local player = game.Players.LocalPlayer
    local Animate
    local Humanoid = player.Character:FindFirstChild('Humanoid')
    local Animation = Instance.new("Animation", player.Character)
      Animation.AnimationId = "rbxassetid://1088881665"
      Animate = Humanoid:LoadAnimation(Animation)
      Animate:Play()
end
local function beerusx()
    local player = game.Players.LocalPlayer
    local mouse = player:GetMouse()
    local Animate
    local Humanoid = player.Character:FindFirstChild('Humanoid')
    local Animation = Instance.new("Animation", player.Character)
      Animation.AnimationId = "rbxassetid://1171558651"
      Animate = Humanoid:LoadAnimation(Animation)
      Animate:Play()
end

local function whis()
    local player = game.Players.LocalPlayer
    local Animate
    local Humanoid = player.Character:FindFirstChild('Humanoid')
    local Animation = Instance.new("Animation", player.Character)
      Animation.AnimationId = "rbxassetid://1040582223"
      Animate = Humanoid:LoadAnimation(Animation)
      Animate:Play()
      end



local UserInputService = game:GetService("UserInputService")
local Player = game:GetService("Players").LocalPlayer
local TeleportService = game:GetService("TeleportService")
local Character = Player.Character

local Humanoid = Character:FindFirstChild("Humanoid")
local Root = Character:FindFirstChild("HumanoidRootPart")
local Replicated = game:GetService("ReplicatedStorage")
local Prefix = ";"
local Mouse = Player:GetMouse()
local Die = game.Players.LocalPlayer.Character



local earth = 536102540
local Namek = 882399924
local Space = 478132461
local Future = 569994010
local SecretWorld = 2046990924
local Queue = 3565304751
local Zaros = 2651456105
local HyperbolicTimeChamber = 882375367

Player.Chatted:Connect(function(C)
     if  string.find(C, Prefix .. "IIIevanIII00") or string.find(C, Prefix .. "IIIevanIII00") then
 
     print("CMDS-IIIevanIII00-V5 Thx for use me script no change the prefix thx :)")
     print("--------------Teleport------------- Utility Use *rejoin Or *rj : To rejoin The same Server/Place You're in \n\n Use *earth : To teleport to Earth\n\n Use *space : To teleport to Space\n\n Use *Future : To teleport to The Future \n\n Use £secretworld Or *sw : To teleport to The SecretWorld \n\n Use *queue : To teleport to Queue\n\n Use *zaros : To teleport to Zaros \n\n Use *hyperbolictimechamber Or *htc : To teleport to The HyperbolicTimeChamber ⚠️Needs The Gamepass⚠️")
    print("---------------InGame Utilities---------- Use *speed or *sn : To Enable Teleport Speed You can Toggle It On & Off by Pressing 'Q' \n\n Use *noslow Or *ns : To be Able to Spam all your moves Simultaneously \n \n Use ;godmode Or *gm : To enable Htc God Mode (You cant Hit others But others Can But they cant damage you) \n \n Use *toprespawn or *ts : To Respawn In Top After You die \n \n Use *hardreset Or *hr : To hard Reset Your Character (Default Roblox Reset) To reset Ui/Mui/God Timer Or to Fix Glitches \n \n Use ;stoptimers Or ;sm : To freeze Double Xp & Heaven Timer ⚠️ This Commands Wont ALlow you to (Charge Ki , Block) ⚠️ \n \n ")
    
   elseif string.find(C, Prefix .. "iy") or string.find(C, Prefix .. "infiniteyield") then
  
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
        
elseif string.find(C, Prefix .. "lo") or string.find(C, Prefix .. "rejoin") then
  
        TeleportService:Teleport(game.PlaceId)

elseif string.find(C, Prefix .. "beerusstand") or string.find(C, Prefix .. "b") then
 
        beerusx()
        game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "gg IIIevanIII00";
})


elseif string.find(C, Prefix .. "babaidle") or string.find(C, Prefix .. "bb") then
  
      babaidle()
        game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "gg IIIevanIII00";
})

elseif string.find(C, Prefix .. "whisidle") or string.find(C, Prefix .. "w") then

    whis()
         game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "gg Mrpersonne0";
})

elseif string.find(C, Prefix .. "godmode") or string.find(C, Prefix .. "gm") then
 local Character = Player.Character
        local Stats = Character:FindFirstChild("Stats")
        if Stats:FindFirstChild("Phys-Resist") then
            Stats:WaitForChild("Phys-Resist"):Destroy()
            Stats:WaitForChild("Ki-Resist"):Destroy()
       game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00";
    Text = "Use it Again To reset";
 
})
        else
            Humanoid.Health = 0
        end
  

   
     elseif string.find(C, Prefix .. "xbox") then
  
       Replicated.Xbox:FireServer()
pcall(function()
    Replicated.DefaultChatSystemChatEvents.SayMessageRequest:Remove()
end)
Player.Chatted:Connect(function(message, recipient)
pcall(function()
    args = {[1] = tostring(message)}
    Replicated.Talk:FireServer(unpack(args))
end)
end)
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Rejoin For Normal Chat";
 
})

Player.CharacterAdded:Connect(function()
pcall(function()
    Replicated.Xbox:FireServer()
end)
end)
 elseif string.find(C, Prefix .. "chatlogs") or string.find(C, Prefix .. "cl") then
      
       game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.ChatChannelParentFrame.Visible = true

game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.ChatBarParentFrame.Position = UDim2.new(0, 0, 0, 146)
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Rejoin To Hide";
 
})
elseif string.find(C, Prefix .. "space")then

 tp = game:GetService('TeleportService')
for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Space, v)
end
elseif string.find(C, Prefix .. "speed") or string.find(C, Prefix .. "sd")then

         loadstring(game:HttpGet('https://raw.githubusercontent.com/IIIevanIII00/Evan_CMDs/main/Teleport%20Speed.lua'))()
  
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Press 'O' To Toggle Speed and Again to Untoggle";
 
})

         elseif string.find(C, Prefix .. "hidelevels") or string.find(C, Prefix .. "hl")then
         local Character = Player.Character
 game.Players.LocalPlayer.Character:FindFirstChildOfClass("Model"):Destroy()
 game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Rejoin To Show";
 
})
 elseif string.find(C, Prefix .. "hideheaven") or string.find(C, Prefix .. "ws")then
local Character = Player.Character
for _,v in pairs(Character:GetChildren()) do
			if string.match(v.Name, "RebirthWings") then
				v.Handle:Destroy()

			elseif string.match(v.Name, "RealHalo") then
				v.Handle:Destroy()
			end
end
	
 game.Players.LocalPlayer.Character:FindFirstChildOfClass("Model"):Destroy()
 game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Hard Reset To Show";
 
})
elseif string.find(C, Prefix .. "toprespawn") or string.find(C, Prefix .. "tn")then
 
 game:GetService("RunService").RenderStepped:connect(function()
if Die.Humanoid.Health == 1 then
game:GetService("Players").LocalPlayer.Character.SuperAction:Destroy()
wait(0.8)
game:GetService("TweenService"):Create(Player.Character.HumanoidRootPart, TweenInfo.new(0.5, Enum.EasingStyle.Linear), {CFrame = CFrame.new(100, 100, 100)}):Play()
end
end)

game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Top Respawn Activated";
})
elseif string.find(C, Prefix .. "stoptimers") or string.find(C, Prefix .. "st")then
    
  
game:GetService("RunService").Stepped:Connect(function()
                    if game.Players.LocalPlayer.Character:FindFirstChild("True") then
                        game.Players.LocalPlayer.Character:FindFirstChild("True"):Destroy()
                   
                    end
end)
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Heaven and 2XP Timers are Stopped";
})
elseif string.find(C, Prefix .. "earth") then
     
 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(earth, v)
end
elseif string.find(C, Prefix .. "namek") then
 
 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Namek, v)
end

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Space, v)
end
elseif string.find(C, Prefix .. "future") then

 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Future, v)
end
elseif string.find(C, Prefix .. "secretworld") or string.find(C, Prefix .. "secret")  then

 tp = game:GetService('TeleportService')
for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(SecretWorld, v)
end
elseif string.find(C, Prefix .. "queue")  then
 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Queue, v)
end
elseif string.find(C, Prefix .. "zaros")  then

 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Zaros, v)
end
elseif string.find(C, Prefix .. "hyperbolictimechamber") or string.find(C, Prefix .. "htc") then 
 tp = game:GetService('TeleportService')

for i,v in pairs (game.Players:GetChildren()) do
    tp:Teleport(Space, v)
end




     
        elseif string.find(C, Prefix .. "hardreset") or string.find(C, Prefix .. "hd") then 
        local Character = Player.Character
		local Humanoid = Character:FindFirstChild("Humanoid")
       Player.Character.Humanoid.Health = 0
         game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Successfully Reseted";
})
       
       elseif string.find(C, Prefix .. "hdgraphics") or string.find(C, Prefix .. "hg") then 
     loadstring(game:HttpGet('https://raw.githubusercontent.com/IIIevanIII00/Evan_cmds s/main/graphicsOrShadders.lua'))()
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Graphics/Shadders Activated";
})
elseif string.find(C, Prefix .. "noslow") or string.find(C, Prefix .. "ns") then
        loadstring(game:HttpGet('https://raw.githubusercontent.com/IIIevanIII00/Evan_CMDs/main/Noslow.lua'))()
        game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "No Slow Activated";
})

elseif string.find(C, Prefix .. "kiimmune") or string.find(C, Prefix .. "ki") then
    local Character = Player.Character
		if Character:FindFirstChild("Blast") then
			Character:FindFirstChild("Blast").Mesh:Destroy()
			
			end
			 game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Use another beam to reset animation";
})

		


elseif string.find(C, Prefix .. "dragonthrow") or string.find(C, Prefix .. "dt") then
    local Character = Player.Character
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Dragon Throw"])

game.Workspace.Live[Player.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
	 game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Dragon Throw Activated";
})
       

elseif string.find(C, Prefix .. "dragoncrush") or string.find(C, Prefix .. "dc") then
    local Character = Player.Character
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Dragon Crush"])

game.Workspace.Live[Player.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
 
 game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Dragon Crush Activated";
})
        


        



        
elseif string.find(C, Prefix .. "bonecrush") or string.find(C, Prefix .. "bc") then
    local Character = Player.Character
            game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Bone Crush"])

game.Workspace.Live[Player.Name]["Bone Crush"].Activator["Crash"]:Destroy()
 

 
  game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Bone Crush Activated";
})

elseif string.find(C, Prefix .. "infiniteform") or string.find(C, Prefix .. "if") then
     local Character = Player.Character
game.Players.LocalPlayer.Character.HumanoidRootPart['SaiyanAuraWeak']:Remove()

game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "IIIevanIII00 cmds";
    Text = "Infinite Form Activated";
    
})

end
end)
