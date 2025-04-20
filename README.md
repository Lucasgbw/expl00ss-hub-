debugX = true

local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "expl00ss hub",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "made by expl00ss",
   LoadingSubtitle = "criado por expl00ss",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

 local args = {
    [1] = "RolePlayName",
    [2] = "expl0ss executado!"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))

-- ID do som a ser reproduzido quando o código for executado
local soundId = "rbxassetid://1836973601"

-- Função para tocar o som
local function playSound()
    local sound = Instance.new("Sound")
    sound.SoundId = soundId
    sound.Parent = game.Workspace -- Coloque no Workspace para garantir que seja ouvido
    sound:Play()
end

-- Tocar o som assim que o script for executado
playSound()

local Tab = Window:CreateTab("scripts v1🎶", 103006981698580) -- Title, Image

local Section = Tab:CreateSection("Veja os melhores scritps para você!!🥶")

local Button = Tab:CreateButton({
   Name = "FLY GUI",
   Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Nameless Admin(muito op)",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Nameless-Admin-V2-24856"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
   Name = "script de reverso",
   Callback = function()loadstring(game:HttpGet("https://mscripts.vercel.app/scfiles/reverse-script.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de animação r15 para r6|animation r6",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua", true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypasser op",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-AK-CHAT-BYPASSER-26254"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
   Name = "the darkones",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/TheDarkoneMarcillisePex/Other-Scripts/main/Brook%20Haven%20Gui'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "blackhole op",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/GoofyBlox/GoofyZ/refs/heads/main/Best/Vortex.lua", true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "infinite yield🤖",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "fake lag🏺",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FAKE-LAG-22520"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "redz hub para blox fruits",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypass ",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FilterEvader-v1-Chat-Bypass-26225"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypasser",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Chat-bypass-v2-chatglyph-26394"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypassee",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Gaze-bypass-REIMAGINED-26354"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Fe orbitar o player",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FE-Orbit-14486"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "copiar avatar/ VISUAL!!!!",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/refs/heads/main/Copy%20Avatar'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de salvar o servidor que você estava antes.",
   Callback = function() loadstring(game:HttpGet('https://pastefy.app/S7xNJSXX/raw'))()execute("Script17")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "cannon FE",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Cannon%20Ball'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "serpente x",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/SerpenteXbetaByDefense129/main/Serpente.Scripts"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "rochips painel🔑",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Rochips-Universal-21865"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "fe animação",
   Callback = function()loadstring(game:HttpGet('https://pastefy.app/S7xNJSXX/raw'))()execute("Script9")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script freecam",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Freecam'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script vfly",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Flat-Kurdish-Vfly-13538"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Script de matemática (ou jogo da velha)",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/refs/heads/main/Math%20Problem'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "ghost hub",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-GhostHub-16534"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "hitbox op",
   Callback = function()-- Gui to Lua
-- Version: 3.2

-- Instances:

local Close = Instance.new("TextButton")
local Open2 = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local FightingGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local Cre = Instance.new("TextLabel")
local HitBox = Instance.new("TextBox")
local Red = Instance.new("TextBox")
local Green = Instance.new("TextBox")
local Blue = Instance.new("TextBox")
local TextLabel = Instance.new("TextLabel")

--Properties:

FightingGui.Name = "FightingGui"
FightingGui.Parent = game.CoreGui
FightingGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling


Open2.Name = "Tools"
Open2.Parent = game.CoreGui
Open2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Open.Name = "Open"
Open.Parent = Open2
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.Position = UDim2.new(0, 0, 0.451871663, 0)
Open.Size = UDim2.new(0, 78, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(250, 0, 0)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true
Open.MouseButton1Down:Connect(function()
 FightingGui.Enabled = true
end)

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(1, 0, -0.226244345, 0)
Close.Size = UDim2.new(0, 60, 0, 50)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Down:Connect(function()
 FightingGui.Enabled = false
end)

main.Parent = FightingGui
main.Active = true
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.Position = UDim2.new(0.073011741, 0, 0.237333342, 0)
main.Size = UDim2.new(0, 273, 0, 221)
main.Draggable = true

Cre.Name = "Cre"
Cre.Parent = main
Cre.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Cre.Position = UDim2.new(0, 0, -0.226244345, 0)
Cre.Size = UDim2.new(0, 273, 0, 50)
Cre.Font = Enum.Font.SourceSans
Cre.Text = "Script made by seu pai☄️"
Cre.TextColor3 = Color3.fromRGB(0, 0, 0)
Cre.TextScaled = true
Cre.TextSize = 14.000
Cre.TextWrapped = true

HitBox.Name = "HitBox frost"
HitBox.Parent = main
HitBox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
HitBox.Position = UDim2.new(0.0586080588, 0, 0.0995475128, 0)
HitBox.Size = UDim2.new(0, 65, 0, 50)
HitBox.Font = Enum.Font.SourceSans
HitBox.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
HitBox.PlaceholderText = "Hitbox"
HitBox.Text = ""
HitBox.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBox.TextScaled = true
HitBox.TextSize = 14.000
HitBox.TextWrapped = true

Red.Name = "Red"
Red.Parent = main
Red.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Red.Position = UDim2.new(0.485832304, 0, 0.0995475128, 0)
Red.Size = UDim2.new(0, 37, 0, 31)
Red.Font = Enum.Font.SourceSans
Red.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Red.PlaceholderText = "Red"
Red.Text = ""
Red.TextColor3 = Color3.fromRGB(0, 0, 0)
Red.TextSize = 14.000

Green.Name = "Green"
Green.Parent = main
Green.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Green.Position = UDim2.new(0.665319502, 0, 0.0995475128, 0)
Green.Size = UDim2.new(0, 37, 0, 31)
Green.Font = Enum.Font.SourceSans
Green.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Green.PlaceholderText = "Green"
Green.Text = ""
Green.TextColor3 = Color3.fromRGB(0, 0, 0)
Green.TextSize = 14.000

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(0.47118023, 0, 0.325791866, 0)
TextLabel.Size = UDim2.new(0, 140, 0, 37)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Colors"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Blue.Name = "Blue"
Blue.Parent = main
Blue.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
Blue.Position = UDim2.new(0.837480664, 0, 0.0995475128, 0)
Blue.Size = UDim2.new(0, 37, 0, 31)
Blue.Font = Enum.Font.SourceSans
Blue.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Blue.PlaceholderText = "Blue"
Blue.Text = ""
Blue.TextColor3 = Color3.fromRGB(0, 0, 0)
Blue.TextSize = 14.000
game:GetService('RunService').RenderStepped:connect(function()
 for i,v in next, game:GetService('Players'):GetPlayers() do
  if v.Name ~= game:GetService('Players').LocalPlayer.Name then
   v.Character.HumanoidRootPart.Size = Vector3.new(HitBox.Text,HitBox.Text,HitBox.Text)
   v.Character.HumanoidRootPart.Transparency = 0.8
   v.Character.HumanoidRootPart.Color = Color3.new(Red.Text,Green.Text,Blue.Text)
   v.Character.HumanoidRootPart.Material = "Neon"
   v.Character.HumanoidRootPart.CanCollide = false
  end
 end
end)
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "sander x💀⛎",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))()
   -- The function that takes place when the button is pressed
   end,
})

local Section = Tab:CreateSection("a key do yhub e esta daqui👉YFDQMASrE")

local Button = Tab:CreateButton({
   Name = "YHUB(somente para brookhaven rp.)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Luarmor123/community-Y-HUB/refs/heads/main/YHUB%20ENGLISH"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "tiger x📿",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-tiger-x-hub-21766"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "",
   Callback = function()
       -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("misc📟", 103006981698580) -- Title, Image
