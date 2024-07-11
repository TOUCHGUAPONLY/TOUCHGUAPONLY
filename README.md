local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "TG | TOUCH GUAP TRY HARD DAHOOD SCRIPT Hub",
   LoadingTitle = "TouchGuap TryHard Script Hub",
   LoadingSubtitle = "by TG | TOUCHGUAP Hub",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "touchguap tryhard hub"
   },
   Discord = {
      Enabled = true,
      Invite = "TskcyYMpCc", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "TOUCH GUAP KEY SYSTEM HUB",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"https://pastebin.com/raw/DKEZYAzi"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab(" Home ",17421664486) -- Title, Image
local MainSection = MainTab:CreateSection("TOUCHGUAP")

Rayfield:Notify({
   Title = "GOD LOVES U BIG TOUCHGUAP",
   Content = "Notification Content",
   Duration = 6.5,
   Image = 17421664486,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Inject! ",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Button = MainTab:CreateButton({
   Name = "Headless And Korblox",
   Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet('https://pastebin.com/raw/H5yx10Jq'))()
   end,
})

local Button = MainTab:CreateButton({
   Name = "FAKE MARCO",
   Callback = function()
       game.StarterGui:SetCore("SendNotification", {
    Title = "FAKE MARCO";
    Text = "USE Q";
 
})  

getgenv()["Key To Macro Speed"] = "Z"
getgenv()["Key To Macro Abuse"] = "Q"
getgenv()["God Speed"] = "God Speed"
getgenv()["Auto Crouch"] = false -- Switch to true if you want it look more real
 
loadstring(game:HttpGet("https://pastebin.com/raw/ZzgE78a0"))()
 
local keybind = "c"
 
--The Script
 
yes = false
    plr = game.Players.LocalPlayer
    mouse = plr:GetMouse()
    mouse.KeyDown:connect(function(key)
        if key == keybind and yes == false then
            yes = true
            game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
            game.Players.LocalPlayer.Character.Humz.WalkSpeed = 270
            game.Players.LocalPlayer.Character.Humz.JumpPower = 40
        elseif key == keybind and yes == true then
            yes = false
            game.Players.LocalPlayer.Character.Humz.WalkSpeed = 20
            game.Players.LocalPlayer.Character.Humz.JumpPower = 50
            game.Players.LocalPlayer.Character.Humz.Name = "Humanoid"
        end
    end)
   end,
})

local Button = MainTab:CreateButton({
   Name = "Aimbot",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Actyrn/Scripts/main/AzureModded"))()
   end,
})

local Button = MainTab:CreateButton({
   Name = "TryHard Animation",
   Callback = function()
       while true do
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
wait(1)
end
   end,
})


local Button = MainTab:CreateButton({
   Name = "Shazam Fly",
   Callback = function()
        -- Da Hood Shazam Fly made by Raycodex#9595
 
--// Settings
_G.ShazamFlySpeed = 3
 
--// Script
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Raycodex/Exploiting/main/Roblox/DaHoodShazamFly"), true))()
   end,
})

local MainTab = Window:CreateTab(" Menu ",17421664486) -- Title, Image
local MainSection = MainTab:CreateSection("TOUCHGUAP")

local Button = MenuTab:CreateButton({
   Name = "Enclosed",
   Callback = function()
       loadstring(game:HttpGet('https://raw.githubusercontent.com/dylannpro123/enclosed/main/enclosed'))()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "Swagmode Might Crash ",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002"))()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "Da Hub (Toggle V)",
   Callback = function()
        getgenv().Toggle = "v"
getgenv().Intro = false
loadstring(game:HttpGet("https://raw.githubusercontent.com/NoUGotbannedlol/DaHubV3/main/Launch"))()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "CapsLock",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/whoiscapslock/capslock/main/main", true))()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "Avatar Changer (might not work)",
   Callback = function()
  loadstring(game:HttpGet'https://raw.githubusercontent.com/ao-0/djd/main/wenaki.cc.lua')()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "Vortex (might crash)",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/ImagineProUser/vortexdahood/main/vortex", true))()
   end,
})

local Button = MenuTab:CreateButton({
   Name = "Serenity",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/cypherdh/Serenity/main/script"))()
   end,
})

local MainTab = Window:CreateTab(" Credits /rejoin ",17421664486) -- Title, Image
local MainSection = MainTab:CreateSection("TOUCHGUAP")

local Button = Credits /rejoinTab:CreateButton({
   Name = "Rejoin",
   Callback = function()
     -- rejoin		
local TeleportService = game:GetService("TeleportService")
local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
 
local Rejoin = coroutine.create(function()
    local Success, ErrorMessage = pcall(function()
        TeleportService:Teleport(game.PlaceId, LocalPlayer)
    end)
 
    if ErrorMessage and not Success then
        warn(ErrorMessage)
    end
end)
 
coroutine.resume(Rejoin)
   end,
})

TOUCH GUAP  THIS IS NOT MADE BY THE ORGIN OWNER THIS IS MADE BY A MEMEBER OF TG TG YIKES

local MainTab = Window:CreateTab(" RAGE ",17421664486) -- Title, Image
local MainSection = MainTab:CreateSection("TOUCHGUAP")

local Button = RAGETab:CreateButton({
   Name = "Dahood Victim Script",
   Callback = function()
       --VictimMenu DH
loadstring(game:HttpGet("https://raw.githubusercontent.com/GS21Official/DH-VictimMenu-Script/main/Dh%20VictimMenu%3A%20Script"))()
   end,
})
