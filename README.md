-- Gui to Lua
-- Version: 3.2

-- Instances:

local hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg = Instance.new("ScreenGui")
local tpframe = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Spawns = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Flyisland = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local train = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local air = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local sBase = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local water = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local lake = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Misc = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local ScrollingFrame_2 = Instance.new("ScrollingFrame")
local ws = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local jp = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local clip = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local dest = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local sound1 = Instance.new("Sound")

--Properties:

hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg.Name = "hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg"
hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg.Parent = game.CoreGui
hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg.ResetOnSpawn = false

sound1.Name = "Sound"
sound1.Parent = game.Workspace
sound1.SoundId = "rbxassetid://7357292718"
sound1.Looped = false
sound1.Playing = true
sound1.Volume = 5

game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "Made by:";
	Text = "RblxXploitss";
	Duration = 15;
})

game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "RubyBoo4life#9600";
	Text = "If the gui is not visible then you didnt buy the gamepass!";
	Duration = 15;
})


tpframe.Name = "tpframe"
tpframe.Parent = hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg
tpframe.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
tpframe.Position = UDim2.new(0.00843721628, 0, 0.0767946541, 0)
tpframe.Size = UDim2.new(0, 206, 0, 308)

UICorner.Parent = tpframe

ScrollingFrame.Parent = tpframe
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0776699036, 0, 0.149350643, 0)
ScrollingFrame.Size = UDim2.new(0, 176, 0, 248)

Spawns.Name = "Spawn"
Spawns.Parent = ScrollingFrame
Spawns.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
Spawns.Position = UDim2.new(0.0369078927, 0, 0.0196189489, 0)
Spawns.Size = UDim2.new(0, 148, 0, 45)
Spawns.Font = Enum.Font.SourceSansBold
Spawns.Text = "Spawn"
Spawns.TextColor3 = Color3.fromRGB(255, 255, 255)
Spawns.TextScaled = true
Spawns.TextSize = 14.000
Spawns.TextWrapped = true
Spawns.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1192.04443, 57.813324, 1571.15759, -0.999845207, -1.13902274e-08, -0.0175942015, -1.11013243e-08, 1, -1.65180261e-08, 0.0175942015, -1.63201506e-08, -0.999845207) + Vector3.new(0, 10, 0)
end)


UICorner_2.Parent = Spawns

Flyisland.Name = "Flyisland"
Flyisland.Parent = ScrollingFrame
Flyisland.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
Flyisland.Position = UDim2.new(0.0369078927, 0, 0.113774791, 0)
Flyisland.Size = UDim2.new(0, 148, 0, 45)
Flyisland.Font = Enum.Font.SourceSansBold
Flyisland.Text = "Flying Island"
Flyisland.TextColor3 = Color3.fromRGB(255, 255, 255)
Flyisland.TextScaled = true
Flyisland.TextSize = 14.000
Flyisland.TextWrapped = true
Flyisland.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1133.18848, 541.876404, -1211.63159, -0.0971613526, 5.2575345e-08, 0.995268643, -3.00624805e-08, 1, -5.57600757e-08, -0.995268643, -3.5337969e-08, -0.0971613526) + Vector3.new(0, 10, 0)
end)

UICorner_3.Parent = Flyisland

train.Name = "train"
train.Parent = ScrollingFrame
train.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
train.Position = UDim2.new(0.0369078927, 0, 0.209554017, 0)
train.Size = UDim2.new(0, 148, 0, 45)
train.Font = Enum.Font.SourceSansBold
train.Text = "Train Station"
train.TextColor3 = Color3.fromRGB(255, 255, 255)
train.TextScaled = true
train.TextSize = 14.000
train.TextWrapped = true
train.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2291.61035, 9.69396973, 1250.78223, -0.015111208, 1.53197366e-08, 0.999885798, -1.13253755e-07, 1, -1.70330825e-08, -0.999885798, -1.13498217e-07, -0.015111208) + Vector3.new(0, 10, 0)
end)

UICorner_4.Parent = train

air.Name = "air"
air.Parent = ScrollingFrame
air.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
air.Position = UDim2.new(0.0369078927, 0, 0.303709865, 0)
air.Size = UDim2.new(0, 148, 0, 45)
air.Font = Enum.Font.SourceSansBold
air.Text = "Crazy Airport"
air.TextColor3 = Color3.fromRGB(255, 255, 255)
air.TextScaled = true
air.TextSize = 14.000
air.TextWrapped = true
air.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2165.13574, 29.2158642, -1158.33813, 0.0590922162, -6.37593445e-08, 0.998252511, 2.16606253e-08, 1, 6.25887395e-08, -0.998252511, 1.79242665e-08, 0.0590922162) + Vector3.new(0, 10, 0)
end)

UICorner_5.Parent = air

sBase.Name = "sBase"
sBase.Parent = ScrollingFrame
sBase.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
sBase.Position = UDim2.new(0.0369078927, 0, 0.397865713, 0)
sBase.Size = UDim2.new(0, 148, 0, 45)
sBase.Font = Enum.Font.SourceSansBold
sBase.Text = "Secret Base"
sBase.TextColor3 = Color3.fromRGB(255, 255, 255)
sBase.TextScaled = true
sBase.TextSize = 14.000
sBase.TextWrapped = true
sBase.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-379.076569, 96.9739456, -1607.32263, -0.194086015, -6.83021861e-09, 0.980984509, 2.54430743e-09, 1, 7.46600293e-09, -0.980984509, 3.94497279e-09, -0.194086015) + Vector3.new(0, 10, 0)
end)

UICorner_6.Parent = sBase

water.Name = "water"
water.Parent = ScrollingFrame
water.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
water.Position = UDim2.new(0.0369078927, 0, 0.495268315, 0)
water.Size = UDim2.new(0, 148, 0, 45)
water.Font = Enum.Font.SourceSansBold
water.Text = "Water Cave"
water.TextColor3 = Color3.fromRGB(255, 255, 255)
water.TextScaled = true
water.TextSize = 14.000
water.TextWrapped = true
water.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(454.905579, -103.292511, 858.469604, -0.545684338, 1.87938429e-08, 0.83799082, 8.45922443e-08, 1, 3.26576597e-08, -0.83799082, 8.87082976e-08, -0.545684338) + Vector3.new(0, 10, 0)
end)

UICorner_7.Parent = water

lake.Name = "lake"
lake.Parent = ScrollingFrame
lake.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
lake.Position = UDim2.new(0.0369078927, 0, 0.59429431, 0)
lake.Size = UDim2.new(0, 148, 0, 45)
lake.Font = Enum.Font.SourceSansBold
lake.Text = "Test Lake"
lake.TextColor3 = Color3.fromRGB(255, 255, 255)
lake.TextScaled = true
lake.TextSize = 14.000
lake.TextWrapped = true
lake.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(307.416077, 35.0432472, 1883.44568, -0.896851838, -8.67901804e-08, 0.442331105, -6.45060041e-08, 1, 6.54212471e-08, -0.442331105, 3.01401535e-08, -0.896851838) + Vector3.new(0, 10, 0)
end)

UICorner_8.Parent = lake

TextLabel.Parent = ScrollingFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.684174597, 0)
TextLabel.Size = UDim2.new(0, 163, 0, 50)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "More Coming Soon!"
TextLabel.TextColor3 = Color3.fromRGB(255, 170, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = tpframe
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(0, 206, 0, 46)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true
TextLabel_2.Text = "Teleports"

Misc.Name = "Misc"
Misc.Parent = hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg
Misc.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
Misc.Position = UDim2.new(0.18054755, 0, 0.0767946541, 0)
Misc.Size = UDim2.new(0, 206, 0, 308)

UICorner_9.Parent = Misc

ScrollingFrame_2.Parent = Misc
ScrollingFrame_2.Active = true
ScrollingFrame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame_2.BorderSizePixel = 0
ScrollingFrame_2.Position = UDim2.new(0.0776699036, 0, 0.149350643, 0)
ScrollingFrame_2.Size = UDim2.new(0, 176, 0, 248)

ws.Name = "ws"
ws.Parent = ScrollingFrame_2
ws.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
ws.Position = UDim2.new(0.0369078927, 0, 0.113774791, 0)
ws.Size = UDim2.new(0, 148, 0, 45)
ws.Font = Enum.Font.SourceSansBold
ws.Text = "More Walkspeed"
ws.TextColor3 = Color3.fromRGB(255, 255, 255)
ws.TextScaled = true
ws.TextSize = 14.000
ws.TextWrapped = true
ws.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)

UICorner_10.Parent = ws

jp.Name = "jp"
jp.Parent = ScrollingFrame_2
jp.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
jp.Position = UDim2.new(0.0369078927, 0, 0.209554017, 0)
jp.Size = UDim2.new(0, 148, 0, 45)
jp.Font = Enum.Font.SourceSansBold
jp.Text = "More Jump Power"
jp.TextColor3 = Color3.fromRGB(255, 255, 255)
jp.TextScaled = true
jp.TextSize = 14.000
jp.TextWrapped = true
jp.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 150
end)
UICorner_11.Parent = jp

TextLabel_3.Parent = ScrollingFrame_2
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0, 0, 0.684174597, 0)
TextLabel_3.Size = UDim2.new(0, 163, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSansBold
TextLabel_3.Text = "More Coming Soon!"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 170, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

clip.Name = "clip"
clip.Parent = ScrollingFrame_2
clip.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
clip.Position = UDim2.new(0.0369078927, 0, 0.0196189489, 0)
clip.Size = UDim2.new(0, 148, 0, 45)
clip.Font = Enum.Font.SourceSansBold
clip.Text = "Noclip"
clip.TextColor3 = Color3.fromRGB(255, 255, 255)
clip.TextScaled = true
clip.TextSize = 14.000
clip.TextWrapped = true
clip.MouseButton2Click:Connect(function()
	-- Sub Please
	local s = loadstring(game:HttpGet(("https://raw.githubusercontent.com/RobloxScripts52/noclip/main/noclip.lua"), true))()
	print(s)
end)

UICorner_12.Parent = clip

TextLabel_4.Parent = Misc
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.00485432148, 0, 0, 0)
TextLabel_4.Size = UDim2.new(0, 206, 0, 46)
TextLabel_4.Font = Enum.Font.SourceSansBold
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

dest.Name = "dest"
dest.Parent = hgkdfgkjdhfjkfdhkjdhgdkjfghdfkgjhkfdjhkjdfhgdkfjhgdkfjhgdjfkhgdkfjhg
dest.BackgroundColor3 = Color3.fromRGB(255, 64, 64)
dest.Position = UDim2.new(0, 0, 0.916527569, 0)
dest.Size = UDim2.new(0, 200, 0, 50)
dest.Font = Enum.Font.SourceSansBold
dest.Text = "Destroy Gui"
dest.TextColor3 = Color3.fromRGB(255, 255, 255)
dest.TextScaled = true
dest.TextSize = 14.000
dest.TextWrapped = true

UICorner_13.Parent = dest

-- Scripts:

local function LGRVUS_fake_script() -- TextLabel_2.LocalScript 
	local script = Instance.new('LocalScript', TextLabel_2)

	script.Parent.Text = "Teleports"
	wait(9000)
	script.Parent.Text = "lol u been here for 150 minutes! are you still alive?"
end
local function ZBHOJHA_fake_script() -- tpframe.LocalScript 
	local script = Instance.new('LocalScript', tpframe)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
end
coroutine.wrap(ZBHOJHA_fake_script)()
local function WZHHLL_fake_script() -- TextLabel_4.LocalScript 
	local script = Instance.new('LocalScript', TextLabel_4)

	script.Parent.Text = "Misc"
	wait(90000)
	script.Parent.Text = "bro u literally changed the text of this gui so it will say this >:("
end
coroutine.wrap(WZHHLL_fake_script)()
local function YQGEHIF_fake_script() -- Misc.LocalScript 
	local script = Instance.new('LocalScript', Misc)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
end
coroutine.wrap(YQGEHIF_fake_script)()
local function SYYKBSQ_fake_script() -- dest.LocalScript 
	local script = Instance.new('LocalScript', dest)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent:Destroy()
	end)
end
coroutine.wrap(SYYKBSQ_fake_script)()
