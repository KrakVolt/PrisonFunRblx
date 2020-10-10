1local PrisonFunV3 = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local PlaceHolder = Instance.new("Frame")
local Main = Instance.new("ImageLabel")
local ArrestAll = Instance.new("TextButton")
local TextButton_Roundify_12px = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Invisible = Instance.new("TextButton")
local TextButton_Roundify_12px_2 = Instance.new("ImageLabel")
local TextLabel_2 = Instance.new("TextLabel")
local OnePunch = Instance.new("TextButton")
local TextButton_Roundify_12px_3 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local Guns = Instance.new("TextButton")
local TextButton_Roundify_12px_4 = Instance.new("ImageLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Fling = Instance.new("TextButton")
local TextButton_Roundify_12px_5 = Instance.new("ImageLabel")
local TextLabel_5 = Instance.new("TextLabel")
local AutoRespawn = Instance.new("TextButton")
local TextButton_Roundify_12px_6 = Instance.new("ImageLabel")
local TextLabel_6 = Instance.new("TextLabel")
local SpeedGui = Instance.new("TextButton")
local TextButton_Roundify_12px_7 = Instance.new("ImageLabel")
local TextLabel_7 = Instance.new("TextLabel")
local Neutral = Instance.new("TextButton")
local TextButton_Roundify_12px_8 = Instance.new("ImageLabel")
local TextLabel_8 = Instance.new("TextLabel")
local Btools = Instance.new("TextButton")
local TextButton_Roundify_12px_9 = Instance.new("ImageLabel")
local TextLabel_9 = Instance.new("TextLabel")
local ModGuns = Instance.new("TextButton")
local TextButton_Roundify_12px_10 = Instance.new("ImageLabel")
local TextLabel_10 = Instance.new("TextLabel")
local Helicopter = Instance.new("TextButton")
local TextButton_Roundify_12px_11 = Instance.new("ImageLabel")
local TextLabel_11 = Instance.new("TextLabel")
local Admin = Instance.new("TextButton")
local TextButton_Roundify_12px_12 = Instance.new("ImageLabel")
local TextLabel_12 = Instance.new("TextLabel")
local Police = Instance.new("TextButton")
local TextButton_Roundify_12px_13 = Instance.new("ImageLabel")
local TextLabel_13 = Instance.new("TextLabel")
local Prisoner = Instance.new("TextButton")
local TextButton_Roundify_12px_14 = Instance.new("ImageLabel")
local TextLabel_14 = Instance.new("TextLabel")
local Criminal = Instance.new("TextButton")
local TextButton_Roundify_12px_15 = Instance.new("ImageLabel")
local TextLabel_15 = Instance.new("TextLabel")
local FlyCar = Instance.new("TextButton")
local TextButton_Roundify_12px_16 = Instance.new("ImageLabel")
local TextLabel_16 = Instance.new("TextLabel")
local More = Instance.new("TextButton")
local TextButton_Roundify_12px_17 = Instance.new("ImageLabel")
local TextLabel_17 = Instance.new("TextLabel")
local Frame = Instance.new("ImageLabel")
local RemoveDoors = Instance.new("TextButton")
local TextButton_Roundify_12px_18 = Instance.new("ImageLabel")
local TextLabel_18 = Instance.new("TextLabel")
local RemoveFences = Instance.new("TextButton")
local TextButton_Roundify_12px_19 = Instance.new("ImageLabel")
local TextLabel_19 = Instance.new("TextLabel")
local RemoveTrees = Instance.new("TextButton")
local TextButton_Roundify_12px_20 = Instance.new("ImageLabel")
local TextLabel_20 = Instance.new("TextLabel")
local RemoveWalls = Instance.new("TextButton")
local TextButton_Roundify_12px_21 = Instance.new("ImageLabel")
local TextLabel_21 = Instance.new("TextLabel")
local Exit = Instance.new("TextButton")
local Rage = Instance.new("ImageLabel")
local Killall = Instance.new("TextButton")
local TextButton_Roundify_12px_22 = Instance.new("ImageLabel")
local TextLabel_22 = Instance.new("TextLabel")
local Killaura = Instance.new("TextButton")
local TextButton_Roundify_12px_23 = Instance.new("ImageLabel")
local TextLabel_23 = Instance.new("TextLabel")
local Teleports = Instance.new("ImageLabel")
local CrimBaseTP = Instance.new("TextButton")
local TextButton_Roundify_12px_24 = Instance.new("ImageLabel")
local TextLabel_24 = Instance.new("TextLabel")
local CtrlClickTP = Instance.new("TextButton")
local TextButton_Roundify_12px_25 = Instance.new("ImageLabel")
local TextLabel_25 = Instance.new("TextLabel")
local CarSpawnTP = Instance.new("TextButton")
local TextButton_Roundify_12px_26 = Instance.new("ImageLabel")
local TextLabel_26 = Instance.new("TextLabel")
local TopPrisonTP = Instance.new("TextButton")
local TextButton_Roundify_12px_27 = Instance.new("ImageLabel")
local TextLabel_27 = Instance.new("TextLabel")
local PrisonTP = Instance.new("TextButton")
local TextButton_Roundify_12px_28 = Instance.new("ImageLabel")
local TextLabel_28 = Instance.new("TextLabel")
local YardTP = Instance.new("TextButton")
local TextButton_Roundify_12px_29 = Instance.new("ImageLabel")
local TextLabel_29 = Instance.new("TextLabel")
local CrimBaseTP_2 = Instance.new("TextButton")
local TextButton_Roundify_12px_30 = Instance.new("ImageLabel")
local TextLabel_30 = Instance.new("TextLabel")
local CrimBaseTP_3 = Instance.new("TextButton")
local TextButton_Roundify_12px_31 = Instance.new("ImageLabel")
local TextLabel_31 = Instance.new("TextLabel")
local TabControl = Instance.new("Frame")
local MainMain = Instance.new("TextButton")
local MainRage = Instance.new("TextButton")
local MainTeleports = Instance.new("TextButton")
local TopBar = Instance.new("ImageLabel")
local Frame_2 = Instance.new("Frame")
local TextLabel_32 = Instance.new("TextLabel")
local Exit_2 = Instance.new("TextButton")

--Properties:

PrisonFunV3.Name = "PrisonFunV3"
PrisonFunV3.Parent = game.CoreGui

Open.Name = "Open"
Open.Parent = PrisonFunV3
Open.BackgroundColor3 = Color3.fromRGB(75, 255, 147)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0, 0, 0.715719104, 0)
Open.Size = UDim2.new(0, 66, 0, 37)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true
Open.MouseButton1Down:connect(function()
	Main.Visible = true
	Open.Visible = false
	TabControl.Visible = true
	TopBar.Visible = true
	PlaceHolder.Visible = true
end)

PlaceHolder.Name = "PlaceHolder"
PlaceHolder.Parent = PrisonFunV3
PlaceHolder.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlaceHolder.BackgroundTransparency = 1.000
PlaceHolder.Position = UDim2.new(0.474330366, 0, 0.177257538, 0)
PlaceHolder.Size = UDim2.new(0, 422, 0, 284)
PlaceHolder.Active = true 
PlaceHolder.Draggable = true
PlaceHolder.Visible = false

Main.Name = "Main"
Main.Parent = PlaceHolder
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(-0.000487621874, 0, -0.00108341035, 0)
Main.Size = UDim2.new(0, 422, 0, 284)
Main.Image = "rbxassetid://3570695787"
Main.ImageColor3 = Color3.fromRGB(75, 255, 147)
Main.ScaleType = Enum.ScaleType.Slice
Main.SliceCenter = Rect.new(100, 100, 100, 100)
Main.SliceScale = 0.120
Main.Visible = false

ArrestAll.Name = "Arrest-All"
ArrestAll.Parent = Main
ArrestAll.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
ArrestAll.BackgroundTransparency = 1.000
ArrestAll.BorderSizePixel = 0
ArrestAll.Position = UDim2.new(0.0853080601, 0, 0.309859157, 0)
ArrestAll.Size = UDim2.new(0, 81, 0, 36)
ArrestAll.Font = Enum.Font.SourceSans
ArrestAll.Text = ""
ArrestAll.TextColor3 = Color3.fromRGB(0, 0, 0)
ArrestAll.TextSize = 14.000
ArrestAll.MouseButton1Down:connect(function()
	local Player = game.Players.LocalPlayer
	local cpos = Player.Character.HumanoidRootPart.CFrame
	for i,v in pairs(game.Teams.Criminals:GetPlayers()) do
		if v.Name ~= Player.Name then
			local i = 10
			repeat
				wait()
				i = i-1
				game.Workspace.Remote.arrest:InvokeServer(v.Character.HumanoidRootPart)
				Player.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, 1)
			until i == 0
		end
	end
	Player.Character.HumanoidRootPart.CFrame = cpos
	Notify("Success", "Everyoe is in Jail", "Epic")
end)


TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = ArrestAll
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

TextLabel.Parent = ArrestAll
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(0, 81, 0, 36)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Arrest-All"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

Invisible.Name = "Invisible"
Invisible.Parent = Main
Invisible.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Invisible.BackgroundTransparency = 1.000
Invisible.BorderSizePixel = 0
Invisible.Position = UDim2.new(0.0853080601, 0, 0.461267591, 0)
Invisible.Size = UDim2.new(0, 81, 0, 36)
Invisible.Font = Enum.Font.SourceSans
Invisible.Text = ""
Invisible.TextColor3 = Color3.fromRGB(0, 0, 0)
Invisible.TextSize = 14.000
Invisible.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	position     = player.Character.HumanoidRootPart.Position
	wait(0.1)
	player.Character:MoveTo(position + Vector3.new(0, 1000000, 0))
	wait(0.1)
	humanoidrootpart = player.Character.HumanoidRootPart:clone()
	wait(0.1)
	player.Character.HumanoidRootPart:Destroy()
	humanoidrootpart.Parent = player.Character
	player.Character:MoveTo(position)
	wait()
end)


TextButton_Roundify_12px_2.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_2.Parent = Invisible
TextButton_Roundify_12px_2.Active = true
TextButton_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_2.BackgroundTransparency = 1.000
TextButton_Roundify_12px_2.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_2.Selectable = true
TextButton_Roundify_12px_2.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_2.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_2.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_2.SliceScale = 0.120

TextLabel_2.Parent = Invisible
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(0, 81, 0, 36)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Invisible"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

OnePunch.Name = "One-Punch"
OnePunch.Parent = Main
OnePunch.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
OnePunch.BackgroundTransparency = 1.000
OnePunch.BorderSizePixel = 0
OnePunch.Position = UDim2.new(0.296208531, 0, 0.309859157, 0)
OnePunch.Size = UDim2.new(0, 81, 0, 36)
OnePunch.Font = Enum.Font.SourceSans
OnePunch.Text = ""
OnePunch.TextColor3 = Color3.fromRGB(0, 0, 0)
OnePunch.TextSize = 14.000
OnePunch.MouseButton1Down:connect(function()
	mainRemotes = game.ReplicatedStorage meleeRemote = mainRemotes['meleeEvent'] mouse = game.Players.LocalPlayer:GetMouse() punching = false cooldown = false function punch() cooldown = true local part = Instance.new("Part", game.Players.LocalPlayer.Character) part.Transparency = 1 part.Size = Vector3.new(5, 2, 3) part.CanCollide = false local w1 = Instance.new("Weld", part) w1.Part0 = game.Players.LocalPlayer.Character.Torso w1.Part1 = part w1.C1 = CFrame.new(0,0,2) part.Touched:connect(function(hit) if game.Players:FindFirstChild(hit.Parent.Name) then local plr = game.Players:FindFirstChild(hit.Parent.Name) if plr.Name ~= game.Players.LocalPlayer.Name then part:Destroy() for i = 1,100 do meleeRemote:FireServer(plr) end end end end) wait(1) cooldown = false part:Destroy() end mouse.KeyDown:connect(function(key) if cooldown == false then if key:lower() == "f" then punch() end end end)
end)


TextButton_Roundify_12px_3.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_3.Parent = OnePunch
TextButton_Roundify_12px_3.Active = true
TextButton_Roundify_12px_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_3.BackgroundTransparency = 1.000
TextButton_Roundify_12px_3.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_3.Selectable = true
TextButton_Roundify_12px_3.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_3.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_3.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_3.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_3.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_3.SliceScale = 0.120

TextLabel_3.Parent = OnePunch
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Size = UDim2.new(0, 81, 0, 36)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "One-Punch"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

Guns.Name = "Guns"
Guns.Parent = Main
Guns.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Guns.BackgroundTransparency = 1.000
Guns.BorderSizePixel = 0
Guns.Position = UDim2.new(0.296208531, 0, 0.461267591, 0)
Guns.Size = UDim2.new(0, 81, 0, 36)
Guns.Font = Enum.Font.SourceSans
Guns.Text = ""
Guns.TextColor3 = Color3.fromRGB(0, 0, 0)
Guns.TextSize = 14.000
Guns.MouseButton1Down:connect(function()
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver.M9.ITEMPICKUP)
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["AK-47"].ITEMPICKUP)
end)


TextButton_Roundify_12px_4.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_4.Parent = Guns
TextButton_Roundify_12px_4.Active = true
TextButton_Roundify_12px_4.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_4.BackgroundTransparency = 1.000
TextButton_Roundify_12px_4.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_4.Selectable = true
TextButton_Roundify_12px_4.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_4.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_4.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_4.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_4.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_4.SliceScale = 0.120

TextLabel_4.Parent = Guns
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Size = UDim2.new(0, 81, 0, 36)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Guns"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000

Fling.Name = "Fling"
Fling.Parent = Main
Fling.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Fling.BackgroundTransparency = 1.000
Fling.BorderSizePixel = 0
Fling.Position = UDim2.new(0.0853080601, 0, 0.612676024, 0)
Fling.Size = UDim2.new(0, 81, 0, 36)
Fling.Font = Enum.Font.SourceSans
Fling.Text = ""
Fling.TextColor3 = Color3.fromRGB(0, 0, 0)
Fling.TextSize = 14.000
Fling.MouseButton1Down:connect(function()
	power = 300 
	
	game:GetService('RunService').Stepped:connect(function()
		game.Players.LocalPlayer.Character.Head.CanCollide = false
		game.Players.LocalPlayer.Character.Torso.CanCollide = false
		game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
		game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
	end)
	
	wait(.1)
	local bambam = Instance.new("BodyThrust")
	bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
	bambam.Force = Vector3.new(power,0,power)
	bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
end)


TextButton_Roundify_12px_5.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_5.Parent = Fling
TextButton_Roundify_12px_5.Active = true
TextButton_Roundify_12px_5.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_5.BackgroundTransparency = 1.000
TextButton_Roundify_12px_5.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_5.Selectable = true
TextButton_Roundify_12px_5.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_5.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_5.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_5.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_5.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_5.SliceScale = 0.120

TextLabel_5.Parent = Fling
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Size = UDim2.new(0, 81, 0, 36)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Fling"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextSize = 14.000

AutoRespawn.Name = "AutoRespawn"
AutoRespawn.Parent = Main
AutoRespawn.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
AutoRespawn.BackgroundTransparency = 1.000
AutoRespawn.BorderSizePixel = 0
AutoRespawn.Position = UDim2.new(0.296208531, 0, 0.612676024, 0)
AutoRespawn.Size = UDim2.new(0, 81, 0, 36)
AutoRespawn.Font = Enum.Font.SourceSans
AutoRespawn.Text = ""
AutoRespawn.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoRespawn.TextSize = 14.000
AutoRespawn.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Health = 0
	local BackupCFrame = nil
	game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function(character)
		local HumanoidRootPart = character:WaitForChild("HumanoidRootPart")
		if BackupCFrame then
			HumanoidRootPart.CFrame = BackupCFrame
		end
		character:WaitForChild("Humanoid").Died:Connect(function()
			BackupCFrame = HumanoidRootPart.CFrame
			local A_1 = "\66\114\111\121\111\117\98\97\100\100"
			local Event = game:GetService("Workspace").Remote.loadchar
			Event:InvokeServer(A_1)
			game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
			game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver.M9.ITEMPICKUP)
			game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["AK-47"].ITEMPICKUP)
			local Player = game:GetService('Players').LocalPlayer
			local Backpack = Player.Backpack
			
			local gun = Backpack.M9 
			
			gs = require(gun.GunStates)
			
			
			
			gs.MaxAmmo = math.huge      
			gs.CurrentAmmo = math.huge
			gs.AutoFire = true          
			gs.Spread = 0
			gs.FireRate = 0 
			gs.Range = math.huge
			gs.Damage = 300
			
			local Player = game:GetService('Players').LocalPlayer
			local Backpack = Player.Backpack
			
			local gun = Backpack['AK-47']
			
			gs = require(gun.GunStates)
			
			
			
			gs.MaxAmmo = math.huge      
			gs.CurrentAmmo = math.huge
			gs.AutoFire = true          
			gs.Spread = 0
			gs.FireRate = 0 
			gs.Range = math.huge
			gs.Damage = 300
			
			local Player = game:GetService('Players').LocalPlayer
			local Backpack = Player.Backpack
			
			local gun = Backpack['Remington 870']
			
			gs = require(gun.GunStates)
			
			
			
			gs.MaxAmmo = math.huge      
			gs.CurrentAmmo = math.huge
			gs.AutoFire = true          
			gs.Spread = 0
			gs.FireRate = 0 
			gs.Range = math.huge
			gs.Damage = 300
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
		end)
	end)
end)


TextButton_Roundify_12px_6.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_6.Parent = AutoRespawn
TextButton_Roundify_12px_6.Active = true
TextButton_Roundify_12px_6.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_6.BackgroundTransparency = 1.000
TextButton_Roundify_12px_6.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_6.Selectable = true
TextButton_Roundify_12px_6.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_6.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_6.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_6.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_6.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_6.SliceScale = 0.120

TextLabel_6.Parent = AutoRespawn
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Size = UDim2.new(0, 81, 0, 36)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "Auto-Respawn"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextSize = 14.000

SpeedGui.Name = "Speed-Gui"
SpeedGui.Parent = Main
SpeedGui.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
SpeedGui.BackgroundTransparency = 1.000
SpeedGui.BorderSizePixel = 0
SpeedGui.Position = UDim2.new(0.0853080601, 0, 0.764084458, 0)
SpeedGui.Size = UDim2.new(0, 81, 0, 36)
SpeedGui.Font = Enum.Font.SourceSans
SpeedGui.Text = ""
SpeedGui.TextColor3 = Color3.fromRGB(0, 0, 0)
SpeedGui.TextSize = 14.000
SpeedGui.MouseButton1Down:connect(function()
	--Made by KrakVolt#3460
	local ScreenGui = Instance.new("ScreenGui")
	local Test = Instance.new("Frame")
	local TextButton = Instance.new("TextButton")
	local TextButton_2 = Instance.new("TextButton")
	local TextButton_3 = Instance.new("TextButton")
	local TextButton_4 = Instance.new("TextButton")
	local TextButton_5 = Instance.new("TextButton")
	local TextButton_6 = Instance.new("TextButton")
	local TextButton_7 = Instance.new("TextButton")
	local TextButton_8 = Instance.new("TextButton")
	local TextButton_9 = Instance.new("TextButton")
	local TextButton_10 = Instance.new("TextButton")
	local TextLabel = Instance.new("TextLabel")
	local TextLabel_2 = Instance.new("TextLabel")
	local TextButton_11 = Instance.new("TextButton")
	
	
	ScreenGui.Parent = game.CoreGui
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
	Test.Name = "Test"
	Test.Parent = ScreenGui
	Test.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Test.Position = UDim2.new(0.645542443, 0, 0.526530683, 0)
	Test.Size = UDim2.new(0, 292, 0, 193)
	Test.Active = true
	Test.Draggable = true
	
	TextButton.Parent = Test
	TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton.Size = UDim2.new(0, 48, 0, 26)
	TextButton.Font = Enum.Font.SourceSans
	TextButton.Text = "Close"
	TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton.TextSize = 14.000
	
	
	TextButton_2.Parent = Test
	TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_2.Position = UDim2.new(0.717990041, 0, 0.247499257, 0)
	TextButton_2.Size = UDim2.new(0, 69, 0, 25)
	TextButton_2.Font = Enum.Font.SourceSans
	TextButton_2.Text = "100"
	TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_2.TextSize = 14.000
	
	TextButton_3.Parent = Test
	TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_3.Position = UDim2.new(0.718162894, 0, 0.480945349, 0)
	TextButton_3.Size = UDim2.new(0, 69, 0, 25)
	TextButton_3.Font = Enum.Font.SourceSans
	TextButton_3.Text = "50"
	TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_3.TextSize = 14.000
	
	
	TextButton_4.Parent = Test
	TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_4.Position = UDim2.new(0.37912184, 0, 0.485513359, 0)
	TextButton_4.Size = UDim2.new(0, 69, 0, 25)
	TextButton_4.Font = Enum.Font.SourceSans
	TextButton_4.Text = "300"
	TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_4.TextSize = 14.000
	
	
	TextButton_5.Parent = Test
	TextButton_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_5.Position = UDim2.new(0.0433324575, 0, 0.714106023, 0)
	TextButton_5.Size = UDim2.new(0, 69, 0, 25)
	TextButton_5.Font = Enum.Font.SourceSans
	TextButton_5.Text = "500"
	TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_5.TextSize = 14.000
	
	
	TextButton_6.Parent = Test
	TextButton_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_6.Position = UDim2.new(0.378948927, 0, 0.252352744, 0)
	TextButton_6.Size = UDim2.new(0, 69, 0, 25)
	TextButton_6.Font = Enum.Font.SourceSans
	TextButton_6.Text = "400"
	TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_6.TextSize = 14.000
	
	
	TextButton_7.Parent = Test
	TextButton_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_7.Position = UDim2.new(0.379294604, 0, 0.713820338, 0)
	TextButton_7.Size = UDim2.new(0, 69, 0, 25)
	TextButton_7.Font = Enum.Font.SourceSans
	TextButton_7.Text = "200"
	TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_7.TextSize = 14.000
	
	TextButton_8.Parent = Test
	TextButton_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_8.Position = UDim2.new(0.0400806665, 0, 0.25268057, 0)
	TextButton_8.Size = UDim2.new(0, 69, 0, 25)
	TextButton_8.Font = Enum.Font.SourceSans
	TextButton_8.Text = "700"
	TextButton_8.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_8.TextSize = 14.000
	
	
	TextButton_9.Parent = Test
	TextButton_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_9.Position = UDim2.new(0.0435053408, 0, 0.486126602, 0)
	TextButton_9.Size = UDim2.new(0, 69, 0, 25)
	TextButton_9.Font = Enum.Font.SourceSans
	TextButton_9.Text = "600"
	TextButton_9.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_9.TextSize = 14.000
	
	
	TextButton_10.Parent = Test
	TextButton_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_10.Position = UDim2.new(0.714910984, 0, 0.713492632, 0)
	TextButton_10.Size = UDim2.new(0, 69, 0, 25)
	TextButton_10.Font = Enum.Font.SourceSans
	TextButton_10.Text = "Normal"
	TextButton_10.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_10.TextSize = 14.000
	
	TextLabel.Parent = Test
	TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel.Position = UDim2.new(-0.000378847122, 0, 0.880681038, 0)
	TextLabel.Size = UDim2.new(0, 292, 0, 23)
	TextLabel.Font = Enum.Font.SourceSans
	TextLabel.Text = "Made by KrakVolt#3460"
	TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextLabel.TextSize = 14.000
	
	TextLabel_2.Parent = Test
	TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel_2.Position = UDim2.new(0.278405249, 0, -0.000243246555, 0)
	TextLabel_2.Size = UDim2.new(0, 129, 0, 38)
	TextLabel_2.Font = Enum.Font.SourceSans
	TextLabel_2.Text = "Speed GUI"
	TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextLabel_2.TextSize = 14.000
	
	TextButton_11.Parent = ScreenGui
	TextButton_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextButton_11.Position = UDim2.new(0, 0, 0.602040768, 0)
	TextButton_11.Size = UDim2.new(0, 80, 0, 36)
	TextButton_11.Font = Enum.Font.SourceSans
	TextButton_11.Text = "Open"
	TextButton_11.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextButton_11.TextSize = 14.000
	
	
	
	local function JXOKKG_fake_script() 
		local script = Instance.new('LocalScript', TextButton)
		
		script.Parent.MouseButton1Click:Connect(function()
			script.Parent.Parent.Visible = false
		end)
		
	end
	coroutine.wrap(JXOKKG_fake_script)()
	local function VSCV_fake_script() 
		local script = Instance.new('LocalScript', TextButton_2)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 100
		end)
		
		
	end
	coroutine.wrap(VSCV_fake_script)()
	local function MLPFZNJ_fake_script()  
		local script = Instance.new('LocalScript', TextButton_3)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 50
		end)
		
		
	end
	coroutine.wrap(MLPFZNJ_fake_script)()
	local function VJWBP_fake_script()  
		local script = Instance.new('LocalScript', TextButton_4)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 300
		end)
		
	end
	coroutine.wrap(VJWBP_fake_script)()
	local function DZCNBT_fake_script()  
		local script = Instance.new('LocalScript', TextButton_5)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 500
		end)
		
	end
	coroutine.wrap(DZCNBT_fake_script)()
	local function QXXRXD_fake_script() 
		local script = Instance.new('LocalScript', TextButton_6)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 400
		end)
		
	end
	coroutine.wrap(QXXRXD_fake_script)()
	local function RNZCO_fake_script()  
		local script = Instance.new('LocalScript', TextButton_7)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 200
		end)
		
	end
	coroutine.wrap(RNZCO_fake_script)()
	local function NEXKVCQ_fake_script() 
		local script = Instance.new('LocalScript', TextButton_8)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 700
		end)
		
		
	end
	coroutine.wrap(NEXKVCQ_fake_script)()
	local function TSQHR_fake_script()  
		local script = Instance.new('LocalScript', TextButton_9)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 600
		end)
		
	end
	coroutine.wrap(TSQHR_fake_script)()
	local function OIMICBX_fake_script()  
		local script = Instance.new('LocalScript', TextButton_10)
		
		
		
		
		Plr = game.Players.LocalPlayer
		
		script.Parent.MouseButton1Click:connect(function()
			Plr.Character.Humanoid.WalkSpeed = 16
		end)
		
	end
	coroutine.wrap(OIMICBX_fake_script)()
	local function LJMHB_fake_script() 
		local script = Instance.new('LocalScript', TextButton_11)
		
		local frame = script.Parent.Parent.Test  
		local open = false
		
		script.Parent.MouseButton1Click:Connect(function()
			if frame.Visible == false then
				frame.Visible = true
			end
		end)
		
		
	end
	coroutine.wrap(LJMHB_fake_script)()
end)


TextButton_Roundify_12px_7.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_7.Parent = SpeedGui
TextButton_Roundify_12px_7.Active = true
TextButton_Roundify_12px_7.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_7.BackgroundTransparency = 1.000
TextButton_Roundify_12px_7.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_7.Selectable = true
TextButton_Roundify_12px_7.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_7.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_7.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_7.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_7.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_7.SliceScale = 0.120

TextLabel_7.Parent = SpeedGui
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Size = UDim2.new(0, 81, 0, 36)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Speed-Gui"
TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.TextSize = 14.000

Neutral.Name = "Neutral"
Neutral.Parent = Main
Neutral.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Neutral.BackgroundTransparency = 1.000
Neutral.BorderSizePixel = 0
Neutral.Position = UDim2.new(0.71563983, 0, 0.764084458, 0)
Neutral.Size = UDim2.new(0, 81, 0, 36)
Neutral.Font = Enum.Font.SourceSans
Neutral.Text = ""
Neutral.TextColor3 = Color3.fromRGB(0, 0, 0)
Neutral.TextSize = 14.000
Neutral.MouseButton1Down:connect(function()
	Workspace.Remote.TeamEvent:FireServer("Medium stone grey")
end)


TextButton_Roundify_12px_8.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_8.Parent = Neutral
TextButton_Roundify_12px_8.Active = true
TextButton_Roundify_12px_8.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_8.BackgroundTransparency = 1.000
TextButton_Roundify_12px_8.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_8.Selectable = true
TextButton_Roundify_12px_8.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_8.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_8.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_8.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_8.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_8.SliceScale = 0.120

TextLabel_8.Parent = Neutral
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.Size = UDim2.new(0, 81, 0, 36)
TextLabel_8.Font = Enum.Font.SourceSans
TextLabel_8.Text = "Neutral"
TextLabel_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_8.TextSize = 14.000

Btools.Name = "Btools"
Btools.Parent = Main
Btools.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Btools.BackgroundTransparency = 1.000
Btools.BorderSizePixel = 0
Btools.Position = UDim2.new(0.504739344, 0, 0.309859157, 0)
Btools.Size = UDim2.new(0, 81, 0, 36)
Btools.Font = Enum.Font.SourceSans
Btools.Text = ""
Btools.TextColor3 = Color3.fromRGB(0, 0, 0)
Btools.TextSize = 14.000
Btools.MouseButton1Down:connect(function()
	wait(0.1)
	local tool1 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool2 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool3 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	tool1.BinType = "Clone"
	tool2.BinType = "Hammer"
	tool3.BinType = "Grab"
end)


TextButton_Roundify_12px_9.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_9.Parent = Btools
TextButton_Roundify_12px_9.Active = true
TextButton_Roundify_12px_9.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_9.BackgroundTransparency = 1.000
TextButton_Roundify_12px_9.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_9.Selectable = true
TextButton_Roundify_12px_9.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_9.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_9.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_9.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_9.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_9.SliceScale = 0.120

TextLabel_9.Parent = Btools
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.Size = UDim2.new(0, 81, 0, 36)
TextLabel_9.Font = Enum.Font.SourceSans
TextLabel_9.Text = "Btools"
TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_9.TextSize = 14.000

ModGuns.Name = "Mod-Guns"
ModGuns.Parent = Main
ModGuns.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
ModGuns.BackgroundTransparency = 1.000
ModGuns.BorderSizePixel = 0
ModGuns.Position = UDim2.new(0.504739344, 0, 0.461267591, 0)
ModGuns.Size = UDim2.new(0, 81, 0, 36)
ModGuns.Font = Enum.Font.SourceSans
ModGuns.Text = ""
ModGuns.TextColor3 = Color3.fromRGB(0, 0, 0)
ModGuns.TextSize = 14.000
ModGuns.MouseButton1Down:connect(function()
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver.M9.ITEMPICKUP)
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["AK-47"].ITEMPICKUP)
	local Player = game:GetService('Players').LocalPlayer
	local Backpack = Player.Backpack
	
	local gun = Backpack.M9 
	
	gs = require(gun.GunStates)
	
	
	
	gs.MaxAmmo = math.huge      
	gs.CurrentAmmo = math.huge
	gs.AutoFire = true          
	gs.Spread = 0
	gs.FireRate = 0 
	gs.Range = math.huge
	gs.Damage = 300
	
	local Player = game:GetService('Players').LocalPlayer
	local Backpack = Player.Backpack
	
	local gun = Backpack['AK-47']
	
	gs = require(gun.GunStates)
	
	
	
	gs.MaxAmmo = math.huge      
	gs.CurrentAmmo = math.huge
	gs.AutoFire = true          
	gs.Spread = 0
	gs.FireRate = 0 
	gs.Range = math.huge
	gs.Damage = 300
	
	local Player = game:GetService('Players').LocalPlayer
	local Backpack = Player.Backpack
	
	local gun = Backpack['Remington 870']
	
	gs = require(gun.GunStates)
	
	
	
	gs.MaxAmmo = math.huge      
	gs.CurrentAmmo = math.huge
	gs.AutoFire = true          
	gs.Spread = 0
	gs.FireRate = 0 
	gs.Range = math.huge
	gs.Damage = 300
end)


TextButton_Roundify_12px_10.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_10.Parent = ModGuns
TextButton_Roundify_12px_10.Active = true
TextButton_Roundify_12px_10.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_10.BackgroundTransparency = 1.000
TextButton_Roundify_12px_10.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_10.Selectable = true
TextButton_Roundify_12px_10.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_10.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_10.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_10.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_10.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_10.SliceScale = 0.120

TextLabel_10.Parent = ModGuns
TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.BackgroundTransparency = 1.000
TextLabel_10.Size = UDim2.new(0, 81, 0, 36)
TextLabel_10.Font = Enum.Font.SourceSans
TextLabel_10.Text = "Mod-Guns"
TextLabel_10.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_10.TextSize = 14.000

Helicopter.Name = "Helicopter"
Helicopter.Parent = Main
Helicopter.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Helicopter.BackgroundTransparency = 1.000
Helicopter.BorderSizePixel = 0
Helicopter.Position = UDim2.new(0.71563983, 0, 0.309859157, 0)
Helicopter.Size = UDim2.new(0, 81, 0, 36)
Helicopter.Font = Enum.Font.SourceSans
Helicopter.Text = ""
Helicopter.TextColor3 = Color3.fromRGB(0, 0, 0)
Helicopter.TextSize = 14.000
Helicopter.MouseButton1Down:connect(function()
	local Player = game:GetService("Players").LocalPlayer
	local ReplicatedFirst = game:GetService("ReplicatedFirst")
	local Players = game:GetService("Players")
	local HttpService = game:GetService("HttpService")
	local RunService = game:GetService("RunService")
	local UserInputService = game:GetService("UserInputService")
	local function getCharacter()
		local new = Player.Character or Player.CharacterAdded:Wait()
		return new
	end
	
	local function getHumanoid()
		local new = getCharacter():WaitForChild("Humanoid")
		return new
	end
	
	local function getPart(part)
		local new = getCharacter():WaitForChild(part,10)
		return new
	end
	
	local function getHats()
		local hatTable = {}
		for i,v in ipairs(getCharacter():GetChildren()) do
			if v:IsA("Accessory") then
				table.insert(hatTable,v.Handle)
			end
		end
		return hatTable
	end
	
	pcall(function()
		while true do 
			wait()
			p.MaximumSimulationRadius = math.huge
			p.SimulationRadius = math.huge
		end
	end)
	
	local function noMesh(part)
		local mesh = part:FindFirstChildWhichIsA("DataModelMesh")
		if mesh then mesh:Destroy() end
	end
	
	local function newGUID()
		local new = HttpService:GenerateGUID(false)
		return new
	end
	
	local function bindRS(functionToBind)
		local id = newGUID()
		RunService:BindToRenderStep(id,300,functionToBind)
		getHumanoid().Died:Connect(function()
			RunService:UnbindFromRenderStep(id)
		end)
	end
	
	local function zeroGrav(part)
		local BodyForce = Instance.new("BodyForce")
		BodyForce.force = Vector3.new(0, workspace.Gravity, 0) * part:GetMass()
		BodyForce.Parent = part
	end
	
	local function cpos(part,base,xOffset,yOffset,zOffset,xRotate,yRotate,zRotate)
		if not part then warn("Part missing") return end
		if not base then warn("Base missing") return end
		zeroGrav(part)
		part:BreakJoints()
		bindRS(function()
			part.CFrame = base.CFrame * CFrame.new(xOffset,yOffset,zOffset) * CFrame.Angles(math.rad(xRotate),math.rad(yRotate),math.rad(zRotate))
		end)
	end
	
	
	local function spinpos(part,base,spinOffset,speed,x,y,z)
		if not part then warn("Part missing") return end
		if not base then warn("Base missing") return end
		local count = 0
		zeroGrav(part)
		part:BreakJoints()
		bindRS(function()
			part.CFrame = base.CFrame * CFrame.Angles(count+spinOffset,0,count+spinOffset) * CFrame.new(x,y,z)
			count = count + speed
		end)
	end
	
	local function ringpos(part,base,spinOffset,speed,x,y,z)
		if not part then warn("Part missing") return end
		if not base then warn("Base missing") return end
		local count = 0
		zeroGrav(part)
		part:BreakJoints()
		bindRS(function()
			part.CFrame = base.CFrame  * CFrame.new(x,y,z) * CFrame.Angles(count+spinOffset,0,count+spinOffset)
			count = count + speed
		end)
	end
	
	local function helipos(part,base,angle,spinOffset,distance,speed)
		if not part then warn("Part missing") return end
		if not base then warn("Base missing") return end
		local count = 0
		local anew = math.rad(angle)
		local offsetnew = math.rad(spinOffset)
		zeroGrav(part)
		part:BreakJoints()
		bindRS(function()
			part.CFrame = (base.CFrame * CFrame.Angles(anew,0,count+offsetnew)) * CFrame.new(0,distance,0)
			count = count + speed
		end)
	end
	
	local function sidehelipos(part,base,angle,spinOffset,distance,speed)
		if not part then warn("Part missing") return end
		if not base then warn("Base missing") return end
		local count = 0
		local anew = math.rad(angle)
		local offsetnew = math.rad(spinOffset)
		zeroGrav(part)
		part:BreakJoints()
		bindRS(function()
			part.CFrame = (base.CFrame * CFrame.new(0,-1,0) * CFrame.Angles(count+offsetnew,0,anew)) * CFrame.new(0,distance,0)
			count = count + speed
		end)
	end
	local torso = getPart("Torso")
	local head = getPart("Head")
	helipos(getPart("Left Arm"),head,90,-90,-1.5,0.4)
	helipos(getPart("Right Arm"),head,90,90,-1.5,0.4)
	cpos(getPart("Left Leg"),torso,0,0,1.5,270,0,0)
	sidehelipos(getPart("Right Leg"),getPart("Left Leg"),0,90,0,0.5)
	coroutine.wrap(GQYAP_fake_script)()
end)


TextButton_Roundify_12px_11.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_11.Parent = Helicopter
TextButton_Roundify_12px_11.Active = true
TextButton_Roundify_12px_11.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_11.BackgroundTransparency = 1.000
TextButton_Roundify_12px_11.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_11.Selectable = true
TextButton_Roundify_12px_11.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_11.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_11.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_11.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_11.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_11.SliceScale = 0.120

TextLabel_11.Parent = Helicopter
TextLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.BackgroundTransparency = 1.000
TextLabel_11.Size = UDim2.new(0, 81, 0, 36)
TextLabel_11.Font = Enum.Font.SourceSans
TextLabel_11.Text = "Helicopter"
TextLabel_11.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_11.TextSize = 14.000

Admin.Name = "Admin"
Admin.Parent = Main
Admin.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Admin.BackgroundTransparency = 1.000
Admin.BorderSizePixel = 0
Admin.Position = UDim2.new(0.71563983, 0, 0.461267591, 0)
Admin.Size = UDim2.new(0, 81, 0, 36)
Admin.Font = Enum.Font.SourceSans
Admin.Text = ""
Admin.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin.TextSize = 14.000
Admin.MouseButton1Down:connect(function()
	--Made by KrakVolt
	--Credit to Zeezy#7203 for the helicopter script!!
	--Enjoy
	local Player = game.Players.LocalPlayer
	
	Player.Chatted:Connect(function(cht)
		if cht:match("/btools") then
			wait(0.1)
			local tool1 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool2 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool3 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			tool1.BinType = "Clone"
			tool2.BinType = "Hammer"
			tool3.BinType = "Grab"
			
		elseif cht:match("/fly") then
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Fly Activated";
				Text = "Press E to Unfly!";
			})
			repeat wait()
			until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
			local mouse = game.Players.LocalPlayer:GetMouse()
			repeat wait() until mouse
			local plr = game.Players.LocalPlayer
			local torso = plr.Character.Torso
			local flying = true
			local deb = true
			local ctrl = {f = 0, b = 0, l = 0, r = 0}
			local lastctrl = {f = 0, b = 0, l = 0, r = 0}
			local maxspeed = 50
			local speed = 0
			
			function Fly()
				local bg = Instance.new("BodyGyro", torso)
				bg.P = 9e4
				bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
				bg.cframe = torso.CFrame
				local bv = Instance.new("BodyVelocity", torso)
				bv.velocity = Vector3.new(0,0.1,0)
				bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
				repeat wait()
					plr.Character.Humanoid.PlatformStand = true
					if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
						speed = speed+.5+(speed/maxspeed)
						if speed > maxspeed then
							speed = maxspeed
						end
					elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
						speed = speed-1
						if speed < 0 then
							speed = 0
						end
					end
					if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
						bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
						lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
					elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
						bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
					else
						bv.velocity = Vector3.new(0,0.1,0)
					end
					bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
				until not flying
				ctrl = {f = 0, b = 0, l = 0, r = 0}
				lastctrl = {f = 0, b = 0, l = 0, r = 0}
				speed = 0
				bg:Destroy()
				bv:Destroy()
				plr.Character.Humanoid.PlatformStand = false
			end
			mouse.KeyDown:connect(function(key)
				if key:lower() == "e" then
					if flying then flying = false
					else
						flying = true
						Fly()
					end
				elseif key:lower() == "w" then
					ctrl.f = 1
				elseif key:lower() == "s" then
					ctrl.b = -1
				elseif key:lower() == "a" then
					ctrl.l = -1
				elseif key:lower() == "d" then
					ctrl.r = 1
				end
			end)
			mouse.KeyUp:connect(function(key)
				if key:lower() == "w" then
					ctrl.f = 0
				elseif key:lower() == "s" then
					ctrl.b = 0
				elseif key:lower() == "a" then
					ctrl.l = 0
				elseif key:lower() == "d" then
					ctrl.r = 0
				end
			end)
			Fly()
			
		elseif cht:match("/noclip") then
			local noclip = true -- Gets if you want the noclip
			char = game.Players.LocalPlayer.Character -- Gets your player
			while true do -- Make sure someone is in game
				if noclip == true then
					for _,v in pairs(char:children()) do
						pcall(function()
							if v.className == "Part" then
								v.CanCollide = false
							end
						end)
					end
				end
				game:service("RunService").Stepped:wait()
			end
			
		elseif cht:match("/ctrl tp") then
			local Plr = game:GetService("Players").LocalPlayer
			local Mouse = Plr:GetMouse()
			
			Mouse.Button1Down:connect(function()
				if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
				if not Mouse.Target then return end
				Plr.Character:MoveTo(Mouse.Hit.p)
			end)
			
		elseif cht:match("/cmds") then
			local Cmds = Instance.new("ScreenGui")
			local Frame = Instance.new("ImageLabel")
			local ScrollingFrame = Instance.new("ScrollingFrame")
			local TextLabel = Instance.new("TextLabel")
			local TextLabel_2 = Instance.new("TextLabel")
			local TextLabel_3 = Instance.new("TextLabel")
			local TextLabel_4 = Instance.new("TextLabel")
			local TextLabel_5 = Instance.new("TextLabel")
			local TextLabel_6 = Instance.new("TextLabel")
			local TextLabel_7 = Instance.new("TextLabel")
			local TextLabel_8 = Instance.new("TextLabel")
			local TextLabel_9 = Instance.new("TextLabel")
			local TextLabel_10 = Instance.new("TextLabel")
			local Close = Instance.new("TextButton")
			
			--Properties:
			
			Cmds.Name = "Cmds"
			Cmds.Parent = game.CoreGui
			
			Frame.Name = "Frame"
			Frame.Parent = Cmds
			Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Frame.BackgroundTransparency = 1.000
			Frame.Position = UDim2.new(0.735620618, 0, 0.308163285, 0)
			Frame.Size = UDim2.new(0, 242, 0, 300)
			Frame.Image = "rbxassetid://3570695787"
			Frame.ScaleType = Enum.ScaleType.Slice
			Frame.SliceCenter = Rect.new(100, 100, 100, 100)
			Frame.SliceScale = 0.120
			Frame.Active = true
			Frame.Draggable = true
			
			ScrollingFrame.Parent = Frame
			ScrollingFrame.Active = true
			ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			ScrollingFrame.Position = UDim2.new(0, 0, 0.144625857, 0)
			ScrollingFrame.Size = UDim2.new(0, 242, 0, 256)
			ScrollingFrame.CanvasPosition = Vector2.new(0, 150)
			
			TextLabel.Parent = ScrollingFrame
			TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel.BorderSizePixel = 0
			TextLabel.Position = UDim2.new(-0.115702465, 0, 0, 0)
			TextLabel.Size = UDim2.new(0, 126, 0, 44)
			TextLabel.Font = Enum.Font.SourceSans
			TextLabel.Text = "/fly"
			TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel.TextScaled = true
			TextLabel.TextSize = 14.000
			TextLabel.TextWrapped = true
			
			TextLabel_2.Parent = ScrollingFrame
			TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_2.BorderSizePixel = 0
			TextLabel_2.Position = UDim2.new(-0.0289256275, 0, 0.219999984, 0)
			TextLabel_2.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_2.Font = Enum.Font.SourceSans
			TextLabel_2.Text = "/ctrl tp"
			TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_2.TextScaled = true
			TextLabel_2.TextSize = 14.000
			TextLabel_2.TextWrapped = true
			
			TextLabel_3.Parent = ScrollingFrame
			TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_3.BorderSizePixel = 0
			TextLabel_3.Position = UDim2.new(0, 0, 0.146666661, 0)
			TextLabel_3.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_3.Font = Enum.Font.SourceSans
			TextLabel_3.Text = "/btools"
			TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_3.TextScaled = true
			TextLabel_3.TextSize = 14.000
			TextLabel_3.TextWrapped = true
			
			TextLabel_4.Parent = ScrollingFrame
			TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_4.BorderSizePixel = 0
			TextLabel_4.Position = UDim2.new(0, 0, 0.073333323, 0)
			TextLabel_4.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_4.Font = Enum.Font.SourceSans
			TextLabel_4.Text = "/noclip"
			TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_4.TextScaled = true
			TextLabel_4.TextSize = 14.000
			TextLabel_4.TextWrapped = true
			
			TextLabel_5.Parent = ScrollingFrame
			TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_5.BorderSizePixel = 0
			TextLabel_5.Position = UDim2.new(-0.0289256256, 0, 0.293333322, 0)
			TextLabel_5.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_5.Font = Enum.Font.SourceSans
			TextLabel_5.Text = "/cmds"
			TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_5.TextScaled = true
			TextLabel_5.TextSize = 14.000
			TextLabel_5.TextWrapped = true
			
			TextLabel_6.Parent = ScrollingFrame
			TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_6.BorderSizePixel = 0
			TextLabel_6.Position = UDim2.new(-5.58793545e-09, 0, 0.366666675, 0)
			TextLabel_6.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_6.Font = Enum.Font.SourceSans
			TextLabel_6.Text = "/funcar"
			TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_6.TextScaled = true
			TextLabel_6.TextSize = 14.000
			TextLabel_6.TextWrapped = true
			
			TextLabel_7.Parent = ScrollingFrame
			TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_7.BorderSizePixel = 0
			TextLabel_7.Position = UDim2.new(0.0247933809, 0, 0.439999998, 0)
			TextLabel_7.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_7.Font = Enum.Font.SourceSans
			TextLabel_7.Text = "/autorespawn"
			TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_7.TextScaled = true
			TextLabel_7.TextSize = 14.000
			TextLabel_7.TextWrapped = true
			
			TextLabel_8.Parent = ScrollingFrame
			TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_8.BorderSizePixel = 0
			TextLabel_8.Position = UDim2.new(0.0247933809, 0, 0.513333321, 0)
			TextLabel_8.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_8.Font = Enum.Font.SourceSans
			TextLabel_8.Text = "/speed 16-150"
			TextLabel_8.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_8.TextScaled = true
			TextLabel_8.TextSize = 14.000
			TextLabel_8.TextWrapped = true
			
			TextLabel_9.Parent = ScrollingFrame
			TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_9.BorderSizePixel = 0
			TextLabel_9.Position = UDim2.new(0.0247933827, 0, 0.585000038, 0)
			TextLabel_9.Size = UDim2.new(0, 126, 0, 44)
			TextLabel_9.Font = Enum.Font.SourceSans
			TextLabel_9.Text = "/helicopter"
			TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_9.TextScaled = true
			TextLabel_9.TextSize = 14.000
			TextLabel_9.TextWrapped = true
			
			TextLabel_10.Parent = Frame
			TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			TextLabel_10.Size = UDim2.new(0, 201, 0, 43)
			TextLabel_10.Font = Enum.Font.SourceSans
			TextLabel_10.Text = "Cmds"
			TextLabel_10.TextColor3 = Color3.fromRGB(0, 0, 0)
			TextLabel_10.TextScaled = true
			TextLabel_10.TextSize = 14.000
			TextLabel_10.TextWrapped = true
			
			Close.Name = "Close"
			Close.Parent = Frame
			Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			Close.Position = UDim2.new(0.830578506, 0, 0, 0)
			Close.Size = UDim2.new(0, 41, 0, 43)
			Close.Font = Enum.Font.SourceSans
			Close.Text = "X"
			Close.TextColor3 = Color3.fromRGB(0, 0, 0)
			Close.TextScaled = true
			Close.TextSize = 14.000
			Close.TextWrapped = true
			Close.MouseButton1Down:connect(function()
				game.CoreGui.Cmds:Destroy()
			end)
		elseif cht:match("/funcar") then
			local hint = Instance.new("Hint",game.Players.LocalPlayer.PlayerGui)
			hint.Text = "Press Q To Toggle"
			hint.Name = game.JobId
			repeat wait()
			until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
			local mouse = game.Players.LocalPlayer:GetMouse()
			repeat wait() until mouse
			local plr = game.Players.LocalPlayer
			local torso = plr.Character.Torso
			local flying = true
			local deb = true
			local ctrl = {f = 0, b = 0, l = 0, r = 0}
			local lastctrl = {f = 0, b = 0, l = 0, r = 0}
			local maxspeed = 500
			local speed = 0
			
			function Fly()
				local bg = Instance.new("BodyGyro", torso)
				bg.P = 9e4
				bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
				bg.cframe = torso.CFrame
				local bv = Instance.new("BodyVelocity", torso)
				bv.velocity = Vector3.new(0,0.1,0)
				bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
				repeat wait()
					plr.Character.Humanoid.PlatformStand = false
					if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
						speed = speed+125.0+(speed/maxspeed)
						if speed > maxspeed then
							speed = maxspeed
						end
					elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
						speed = speed-250
						if speed < 0 then
							speed = 0
						end
					end
					if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
						bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
						lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
					elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
						bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
					else
						bv.velocity = Vector3.new(0,0.1,0)
					end
					bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
				until not flying
				ctrl = {f = 0, b = 0, l = 0, r = 0}
				lastctrl = {f = 0, b = 0, l = 0, r = 0}
				speed = 0
				bg:Destroy()
				bv:Destroy()
				plr.Character.Humanoid.PlatformStand = false
			end
			mouse.KeyDown:connect(function(key)
				if key:lower() == "q" then
					if flying then flying = false
					else
						flying = true
						Fly()
					end
				elseif key:lower() == "w" then
					ctrl.f = 1
				elseif key:lower() == "s" then
					ctrl.b = -1
				elseif key:lower() == "a" then
					ctrl.l = -1
				elseif key:lower() == "d" then
					ctrl.r = 1
				end
			end)
			mouse.KeyUp:connect(function(key)
				if key:lower() == "w" then
					ctrl.f = 0
				elseif key:lower() == "s" then
					ctrl.b = 0
				elseif key:lower() == "a" then
					ctrl.l = 0
				elseif key:lower() == "d" then
					ctrl.r = 0
				end
				wait(5)
				hint:Destroy()
			end)
			Fly()
			
		elseif cht:match("/autorespawn") then
			game.Players.LocalPlayer.Character.Humanoid.Health = 0
			local BackupCFrame = nil
			game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function(character)
				local HumanoidRootPart = character:WaitForChild("HumanoidRootPart")
				if BackupCFrame then
					HumanoidRootPart.CFrame = BackupCFrame
				end
				character:WaitForChild("Humanoid").Died:Connect(function()
					BackupCFrame = HumanoidRootPart.CFrame
				end)
			end)
		elseif cht:match("/speed 16") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
			
		elseif cht:match("/speed 17") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 17
			
		elseif cht:match("/speed 18") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 18
			
		elseif cht:match("/speed 19") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 19
			
		elseif cht:match("/speed 20") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 20
			
		elseif cht:match("/speed 21") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 21
			
		elseif cht:match("/speed 22") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 22
			
		elseif cht:match("/speed 23") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 23
			
		elseif cht:match("/speed 24") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 24
			
		elseif cht:match("/speed 25") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 25
			
		elseif cht:match("/speed 26") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 26
			
		elseif cht:match("/speed 27") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 27
			
		elseif cht:match("/speed 28") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 28
			
		elseif cht:match("/speed 29") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 29
			
		elseif cht:match("/speed 30") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
			
		elseif cht:match("/speed 31") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 31
			
		elseif cht:match("/speed 32") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 32
			
		elseif cht:match("/speed 33") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 33
			
		elseif cht:match("/speed 34") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 34
			
		elseif cht:match("/speed 35") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 35
			
		elseif cht:match("/speed 36") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 36
			
		elseif cht:match("/speed 37") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 37
			
		elseif cht:match("/speed 38") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 38
			
		elseif cht:match("/speed 39") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 39
			
		elseif cht:match("/speed 40") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 40
			
		elseif cht:match("/speed 41") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 41
			
		elseif cht:match("/speed 42") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 42
			
		elseif cht:match("/speed 43") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 43	
			
		elseif cht:match("/speed 41") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 41
			
		elseif cht:match("/speed 42") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 42
			
		elseif cht:match("/speed 43") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 43
			
		elseif cht:match("/speed 44") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 44
			
		elseif cht:match("/speed 45") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 45
			
		elseif cht:match("/speed 46") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 46
			
		elseif cht:match("/speed 47") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 47
			
		elseif cht:match("/speed 48") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 48
			
		elseif cht:match("/speed 49") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 49
			
		elseif cht:match("/speed 50") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
			
		elseif cht:match("/speed 51") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 51
			
		elseif cht:match("/speed 52") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 52
			
		elseif cht:match("/speed 53") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 53
			
		elseif cht:match("/speed 54") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 54
			
		elseif cht:match("/speed 55") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 55
			
		elseif cht:match("/speed 56") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 56
			
		elseif cht:match("/speed 57") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 57
			
		elseif cht:match("/speed 58") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 58
			
		elseif cht:match("/speed 59") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 59
			
		elseif cht:match("/speed 60") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 60
			
		elseif cht:match("/speed 61") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 61
			
		elseif cht:match("/speed 62") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 62
			
		elseif cht:match("/speed 63") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 63
			
		elseif cht:match("/speed 64") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 64
			
		elseif cht:match("/speed 65") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 65
			
		elseif cht:match("/speed 66") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 66
			
		elseif cht:match("/speed 67") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 67
			
		elseif cht:match("/speed 68") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 68
			
		elseif cht:match("/speed 69") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 69
			
		elseif cht:match("/speed 70") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 70
			
		elseif cht:match("/speed 71") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 71
			
		elseif cht:match("/speed 72") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 72
			
		elseif cht:match("/speed 73") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 73
			
		elseif cht:match("/speed 74") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 74
			
		elseif cht:match("/speed 75") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 75
			
		elseif cht:match("/speed 76") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 76
			
		elseif cht:match("/speed 77") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 77
			
		elseif cht:match("/speed 78") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 78
			
		elseif cht:match("/speed 79") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 79
			
		elseif cht:match("/speed 80") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 80
			
		elseif cht:match("/speed 81") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 81
			
		elseif cht:match("/speed 82") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 82
			
		elseif cht:match("/speed 83") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 83
			
		elseif cht:match("/speed 84") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 84
			
		elseif cht:match("/speed 85") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 85
			
		elseif cht:match("/speed 86") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 86
			
		elseif cht:match("/speed 87") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 87
			
		elseif cht:match("/speed 88") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 88
			
		elseif cht:match("/speed 89") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 89
			
		elseif cht:match("/speed 90") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 90
			
		elseif cht:match("/speed 91") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 91
			
		elseif cht:match("/speed 92") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 92
			
		elseif cht:match("/speed 93") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 93
			
		elseif cht:match("/speed 94") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 94
			
		elseif cht:match("/speed 95") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 95
			
		elseif cht:match("/speed 96") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 96
			
		elseif cht:match("/speed 97") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 97
			
		elseif cht:match("/speed 98") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 98
			
		elseif cht:match("/speed 99") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 99
			
		elseif cht:match("/speed 100") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
			
		elseif cht:match("/speed 101") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 101
			
		elseif cht:match("/speed 102") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 102
			
		elseif cht:match("/speed 103") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 103
			
		elseif cht:match("/speed 104") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 104
			
		elseif cht:match("/speed 105") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 105
			
		elseif cht:match("/speed 106") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 106
			
		elseif cht:match("/speed 107") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 107
			
		elseif cht:match("/speed 108") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 108
			
		elseif cht:match("/speed 109") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 109
			
		elseif cht:match("/speed 110") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 110
			
		elseif cht:match("/speed 111") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 111
			
		elseif cht:match("/speed 112") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 112
			
		elseif cht:match("/speed 113") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 113
			
		elseif cht:match("/speed 114") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 114
			
		elseif cht:match("/speed 115") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 115
			
		elseif cht:match("/speed 116") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 116
			
		elseif cht:match("/speed 117") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 117
			
		elseif cht:match("/speed 118") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 118
			
		elseif cht:match("/speed 119") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 119
			
		elseif cht:match("/speed 120") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
			
		elseif cht:match("/speed 121") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 121
			
		elseif cht:match("/speed 122") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 122
			
		elseif cht:match("/speed 123") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 123
			
		elseif cht:match("/speed 124") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 124
			
		elseif cht:match("/speed 125") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 125
			
		elseif cht:match("/speed 126") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 126
			
		elseif cht:match("/speed 127") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 127
			
		elseif cht:match("/speed 128") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 128
			
		elseif cht:match("/speed 129") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 129
			
		elseif cht:match("/speed 130") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 130
			
		elseif cht:match("/speed 131") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 131
			
		elseif cht:match("/speed 132") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 132
			
		elseif cht:match("/speed 133") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 133
			
		elseif cht:match("/speed 134") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 134
			
		elseif cht:match("/speed 135") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 135
			
		elseif cht:match("/speed 136") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 136
			
		elseif cht:match("/speed 137") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 137
			
		elseif cht:match("/speed 138") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 138
			
		elseif cht:match("/speed 139") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 139
			
		elseif cht:match("/speed 140") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 140
			
		elseif cht:match("/speed 141") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 141
			
		elseif cht:match("/speed 142") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 142
			
		elseif cht:match("/speed 143") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 143
			
		elseif cht:match("/speed 144") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 144
			
		elseif cht:match("/speed 145") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 145
			
		elseif cht:match("/speed 146") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 146
			
		elseif cht:match("/speed 147") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 147
			
		elseif cht:match("/speed 148") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 148
			
		elseif cht:match("/speed 149") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 149
			
		elseif cht:match("/speed 150") then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 150	
			
		elseif cht:match("/helicopter") then
			local Player = game:GetService("Players").LocalPlayer
			local ReplicatedFirst = game:GetService("ReplicatedFirst")
			local Players = game:GetService("Players")
			local HttpService = game:GetService("HttpService")
			local RunService = game:GetService("RunService")
			local UserInputService = game:GetService("UserInputService")
			local function getCharacter()
				local new = Player.Character or Player.CharacterAdded:Wait()
				return new
			end
			
			local function getHumanoid()
				local new = getCharacter():WaitForChild("Humanoid")
				return new
			end
			
			local function getPart(part)
				local new = getCharacter():WaitForChild(part,10)
				return new
			end
			
			local function getHats()
				local hatTable = {}
				for i,v in ipairs(getCharacter():GetChildren()) do
					if v:IsA("Accessory") then
						table.insert(hatTable,v.Handle)
					end
				end
				return hatTable
			end
			
			pcall(function()
				while true do 
					wait()
					p.MaximumSimulationRadius = math.huge
					p.SimulationRadius = math.huge
				end
			end)
			
			local function noMesh(part)
				local mesh = part:FindFirstChildWhichIsA("DataModelMesh")
				if mesh then mesh:Destroy() end
			end
			
			local function newGUID()
				local new = HttpService:GenerateGUID(false)
				return new
			end
			
			local function bindRS(functionToBind)
				local id = newGUID()
				RunService:BindToRenderStep(id,300,functionToBind)
				getHumanoid().Died:Connect(function()
					RunService:UnbindFromRenderStep(id)
				end)
			end
			
			local function zeroGrav(part)
				local BodyForce = Instance.new("BodyForce")
				BodyForce.force = Vector3.new(0, workspace.Gravity, 0) * part:GetMass()
				BodyForce.Parent = part
			end
			
			local function cpos(part,base,xOffset,yOffset,zOffset,xRotate,yRotate,zRotate)
				if not part then warn("Part missing") return end
				if not base then warn("Base missing") return end
				zeroGrav(part)
				part:BreakJoints()
				bindRS(function()
					part.CFrame = base.CFrame * CFrame.new(xOffset,yOffset,zOffset) * CFrame.Angles(math.rad(xRotate),math.rad(yRotate),math.rad(zRotate))
				end)
			end
			
			
			local function spinpos(part,base,spinOffset,speed,x,y,z)
				if not part then warn("Part missing") return end
				if not base then warn("Base missing") return end
				local count = 0
				zeroGrav(part)
				part:BreakJoints()
				bindRS(function()
					part.CFrame = base.CFrame * CFrame.Angles(count+spinOffset,0,count+spinOffset) * CFrame.new(x,y,z)
					count = count + speed
				end)
			end
			
			local function ringpos(part,base,spinOffset,speed,x,y,z)
				if not part then warn("Part missing") return end
				if not base then warn("Base missing") return end
				local count = 0
				zeroGrav(part)
				part:BreakJoints()
				bindRS(function()
					part.CFrame = base.CFrame  * CFrame.new(x,y,z) * CFrame.Angles(count+spinOffset,0,count+spinOffset)
					count = count + speed
				end)
			end
			
			local function helipos(part,base,angle,spinOffset,distance,speed)
				if not part then warn("Part missing") return end
				if not base then warn("Base missing") return end
				local count = 0
				local anew = math.rad(angle)
				local offsetnew = math.rad(spinOffset)
				zeroGrav(part)
				part:BreakJoints()
				bindRS(function()
					part.CFrame = (base.CFrame * CFrame.Angles(anew,0,count+offsetnew)) * CFrame.new(0,distance,0)
					count = count + speed
				end)
			end
			
			local function sidehelipos(part,base,angle,spinOffset,distance,speed)
				if not part then warn("Part missing") return end
				if not base then warn("Base missing") return end
				local count = 0
				local anew = math.rad(angle)
				local offsetnew = math.rad(spinOffset)
				zeroGrav(part)
				part:BreakJoints()
				bindRS(function()
					part.CFrame = (base.CFrame * CFrame.new(0,-1,0) * CFrame.Angles(count+offsetnew,0,anew)) * CFrame.new(0,distance,0)
					count = count + speed
				end)
			end
			local torso = getPart("Torso")
			local head = getPart("Head")
			helipos(getPart("Left Arm"),head,90,-90,-1.5,0.4)
			helipos(getPart("Right Arm"),head,90,90,-1.5,0.4)
			cpos(getPart("Left Leg"),torso,0,0,1.5,270,0,0)
			sidehelipos(getPart("Right Leg"),getPart("Left Leg"),0,90,0,0.5)
			coroutine.wrap(GQYAP_fake_script)()
		end
	end)
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "Welcome!";
		Text = "Admin by KrakVolt";
	})
	wait(.1)
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "Admin";
		Text = "Chat /cmds";
	})
end)

TextButton_Roundify_12px_12.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_12.Parent = Admin
TextButton_Roundify_12px_12.Active = true
TextButton_Roundify_12px_12.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_12.BackgroundTransparency = 1.000
TextButton_Roundify_12px_12.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_12.Selectable = true
TextButton_Roundify_12px_12.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_12.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_12.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_12.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_12.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_12.SliceScale = 0.120

TextLabel_12.Parent = Admin
TextLabel_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_12.BackgroundTransparency = 1.000
TextLabel_12.Size = UDim2.new(0, 81, 0, 36)
TextLabel_12.Font = Enum.Font.SourceSans
TextLabel_12.Text = "Admin"
TextLabel_12.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_12.TextSize = 14.000

Police.Name = "Police"
Police.Parent = Main
Police.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Police.BackgroundTransparency = 1.000
Police.BorderSizePixel = 0
Police.Position = UDim2.new(0.504739344, 0, 0.612676024, 0)
Police.Size = UDim2.new(0, 81, 0, 36)
Police.Font = Enum.Font.SourceSans
Police.Text = ""
Police.TextColor3 = Color3.fromRGB(0, 0, 0)
Police.TextSize = 14.000
Police.MouseButton1Down:connect(function()
	workspace.Remote.TeamEvent:FireServer("Bright blue")
end)


TextButton_Roundify_12px_13.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_13.Parent = Police
TextButton_Roundify_12px_13.Active = true
TextButton_Roundify_12px_13.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_13.BackgroundTransparency = 1.000
TextButton_Roundify_12px_13.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_13.Selectable = true
TextButton_Roundify_12px_13.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_13.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_13.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_13.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_13.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_13.SliceScale = 0.120

TextLabel_13.Parent = Police
TextLabel_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_13.BackgroundTransparency = 1.000
TextLabel_13.Size = UDim2.new(0, 81, 0, 36)
TextLabel_13.Font = Enum.Font.SourceSans
TextLabel_13.Text = "Police"
TextLabel_13.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_13.TextSize = 14.000

Prisoner.Name = "Prisoner"
Prisoner.Parent = Main
Prisoner.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Prisoner.BackgroundTransparency = 1.000
Prisoner.BorderSizePixel = 0
Prisoner.Position = UDim2.new(0.71563983, 0, 0.612676024, 0)
Prisoner.Size = UDim2.new(0, 81, 0, 36)
Prisoner.Font = Enum.Font.SourceSans
Prisoner.Text = ""
Prisoner.TextColor3 = Color3.fromRGB(0, 0, 0)
Prisoner.TextSize = 14.000
Prisoner.MouseButton1Down:connect(function()
	workspace.Remote.TeamEvent:FireServer("Bright orange")
end)

TextButton_Roundify_12px_14.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_14.Parent = Prisoner
TextButton_Roundify_12px_14.Active = true
TextButton_Roundify_12px_14.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_14.BackgroundTransparency = 1.000
TextButton_Roundify_12px_14.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_14.Selectable = true
TextButton_Roundify_12px_14.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_14.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_14.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_14.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_14.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_14.SliceScale = 0.120

TextLabel_14.Parent = Prisoner
TextLabel_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_14.BackgroundTransparency = 1.000
TextLabel_14.Size = UDim2.new(0, 81, 0, 36)
TextLabel_14.Font = Enum.Font.SourceSans
TextLabel_14.Text = "Prisoner"
TextLabel_14.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_14.TextSize = 14.000

Criminal.Name = "Criminal"
Criminal.Parent = Main
Criminal.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Criminal.BackgroundTransparency = 1.000
Criminal.BorderSizePixel = 0
Criminal.Position = UDim2.new(0.504739344, 0, 0.764084458, 0)
Criminal.Size = UDim2.new(0, 81, 0, 36)
Criminal.Font = Enum.Font.SourceSans
Criminal.Text = ""
Criminal.TextColor3 = Color3.fromRGB(0, 0, 0)
Criminal.TextSize = 14.000
Criminal.MouseButton1Down:connect(function()
	local Apart = Instance.new("Part")
	
	Apart.Name = "PlrsPos"
	Apart.Parent = workspace
	Apart.Anchored = true
	Apart.Archivable = true
	Apart.CFrame = CFrame.new(9e99, 9e99, 9e99)
	
	LCS = game.Workspace["Criminals Spawn"].SpawnLocation
	
	_G.killAura = true
	wait(0.2)
	
	Apart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	Apart.Transparency = 1
	Apart.Anchored = true
	Apart.CanCollide = false
	
	istptoplr = true
	wait(0.004)
	
	
	LCS = game.Workspace["Criminals Spawn"].SpawnLocation
	
	LCS.CanCollide = false
	LCS.Size = Vector3.new(51.05, 24.12, 54.76)
	LCS.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	LCS.Transparency = 1
	
	wait(2)
	
	istptoplr = false
	_G.killAura = false
	
	wait(0.04)
	
	if istptoplr == false then
		LCS.CFrame = CFrame.new(-920.510803, 92.2271957, 2138.27002, 0, 0, -1, 0, 1, 0, 1, 0, 0)
		LCS.Size = Vector3.new(6, 0.2, 6)
		LCS.Transparency = 0
		istptoplr = false
	end
end)


TextButton_Roundify_12px_15.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_15.Parent = Criminal
TextButton_Roundify_12px_15.Active = true
TextButton_Roundify_12px_15.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_15.BackgroundTransparency = 1.000
TextButton_Roundify_12px_15.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_15.Selectable = true
TextButton_Roundify_12px_15.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_15.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_15.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_15.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_15.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_15.SliceScale = 0.120

TextLabel_15.Parent = Criminal
TextLabel_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_15.BackgroundTransparency = 1.000
TextLabel_15.Size = UDim2.new(0, 81, 0, 36)
TextLabel_15.Font = Enum.Font.SourceSans
TextLabel_15.Text = "Criminal"
TextLabel_15.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_15.TextSize = 14.000

FlyCar.Name = "Fly-Car"
FlyCar.Parent = Main
FlyCar.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
FlyCar.BackgroundTransparency = 1.000
FlyCar.BorderSizePixel = 0
FlyCar.Position = UDim2.new(0.29620856, 0, 0.764084458, 0)
FlyCar.Size = UDim2.new(0, 81, 0, 36)
FlyCar.Font = Enum.Font.SourceSans
FlyCar.Text = ""
FlyCar.TextColor3 = Color3.fromRGB(0, 0, 0)
FlyCar.TextSize = 14.000
FlyCar.MouseButton1Down:connect(function()
	local hint = Instance.new("Hint",game.Players.LocalPlayer.PlayerGui)
	hint.Text = "Press E To Toggle"
	hint.Name = game.JobId
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local flying = true
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 500
	local speed = 0
	
	function Fly()
		local bg = Instance.new("BodyGyro", torso)
		bg.P = 9e4
		bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		bg.cframe = torso.CFrame
		local bv = Instance.new("BodyVelocity", torso)
		bv.velocity = Vector3.new(0,0.1,0)
		bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
		repeat wait()
			plr.Character.Humanoid.PlatformStand = false
			if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
				speed = speed+125.0+(speed/maxspeed)
				if speed > maxspeed then
					speed = maxspeed
				end
			elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
				speed = speed-250
				if speed < 0 then
					speed = 0
				end
			end
			if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
				bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
				lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
			elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
				bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
			else
				bv.velocity = Vector3.new(0,0.1,0)
			end
			bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
		until not flying
		ctrl = {f = 0, b = 0, l = 0, r = 0}
		lastctrl = {f = 0, b = 0, l = 0, r = 0}
		speed = 0
		bg:Destroy()
		bv:Destroy()
		plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
		if key:lower() == "e" then
			if flying then flying = false
			else
				flying = true
				Fly()
			end
		elseif key:lower() == "w" then
			ctrl.f = 1
		elseif key:lower() == "s" then
			ctrl.b = -1
		elseif key:lower() == "a" then
			ctrl.l = -1
		elseif key:lower() == "d" then
			ctrl.r = 1
		end
	end)
	mouse.KeyUp:connect(function(key)
		if key:lower() == "w" then
			ctrl.f = 0
		elseif key:lower() == "s" then
			ctrl.b = 0
		elseif key:lower() == "a" then
			ctrl.l = 0
		elseif key:lower() == "d" then
			ctrl.r = 0
		end
		wait(5)
		hint:Destroy()
	end)
	Fly()
end)


TextButton_Roundify_12px_16.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_16.Parent = FlyCar
TextButton_Roundify_12px_16.Active = true
TextButton_Roundify_12px_16.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_16.BackgroundTransparency = 1.000
TextButton_Roundify_12px_16.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_16.Selectable = true
TextButton_Roundify_12px_16.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_16.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_16.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_16.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_16.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_16.SliceScale = 0.120

TextLabel_16.Parent = FlyCar
TextLabel_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_16.BackgroundTransparency = 1.000
TextLabel_16.Size = UDim2.new(0, 81, 0, 36)
TextLabel_16.Font = Enum.Font.SourceSans
TextLabel_16.Text = "Fly-Car"
TextLabel_16.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_16.TextSize = 14.000

More.Name = "More"
More.Parent = Main
More.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
More.BackgroundTransparency = 1.000
More.BorderSizePixel = 0
More.Position = UDim2.new(0.376777232, 0, 0.911971807, 0)
More.Size = UDim2.new(0, 101, 0, 25)
More.Font = Enum.Font.SourceSans
More.Text = "More"
More.TextColor3 = Color3.fromRGB(0, 0, 0)
More.TextSize = 14.000
More.Visible = true
More.MouseButton1Down:connect(function()
	Frame.Visible = true
end)


TextButton_Roundify_12px_17.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_17.Parent = More
TextButton_Roundify_12px_17.Active = true
TextButton_Roundify_12px_17.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_17.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_17.BackgroundTransparency = 1.000
TextButton_Roundify_12px_17.Position = UDim2.new(0.504999995, 0, 0.479166269, 0)
TextButton_Roundify_12px_17.Selectable = true
TextButton_Roundify_12px_17.Size = UDim2.new(1.01000011, 0, 1.04166663, 0)
TextButton_Roundify_12px_17.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_17.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_17.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_17.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_17.SliceScale = 0.120

TextLabel_17.Parent = More
TextLabel_17.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_17.BackgroundTransparency = 1.000
TextLabel_17.Position = UDim2.new(0, 0, -0.0416662581, 0)
TextLabel_17.Size = UDim2.new(0, 101, 0, 25)
TextLabel_17.Font = Enum.Font.SourceSans
TextLabel_17.Text = "More"
TextLabel_17.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_17.TextSize = 14.000

Frame.Name = "Frame"
Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.298578203, 0, 1.04577482, 0)
Frame.Size = UDim2.new(0, 169, 0, 115)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(75, 255, 147)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120
Frame.Active = true
Frame.Visible = false

RemoveDoors.Name = "Remove-Doors"
RemoveDoors.Parent = Frame
RemoveDoors.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
RemoveDoors.BackgroundTransparency = 1.000
RemoveDoors.BorderSizePixel = 0
RemoveDoors.Position = UDim2.new(0.0654394403, 0, 0.237495825, 0)
RemoveDoors.Size = UDim2.new(0, 70, 0, 34)
RemoveDoors.Font = Enum.Font.SourceSans
RemoveDoors.Text = ""
RemoveDoors.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveDoors.TextSize = 14.000
RemoveDoors.MouseButton1Down:connect(function()
	game.Workspace.Doors:Destroy()
end)


TextButton_Roundify_12px_18.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_18.Parent = RemoveDoors
TextButton_Roundify_12px_18.Active = true
TextButton_Roundify_12px_18.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_18.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_18.BackgroundTransparency = 1.000
TextButton_Roundify_12px_18.Position = UDim2.new(0.506719947, 0, 0.515151501, 0)
TextButton_Roundify_12px_18.Selectable = true
TextButton_Roundify_12px_18.Size = UDim2.new(1.01343918, 0, 1.030303, 0)
TextButton_Roundify_12px_18.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_18.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_18.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_18.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_18.SliceScale = 0.120

TextLabel_18.Parent = RemoveDoors
TextLabel_18.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_18.BackgroundTransparency = 1.000
TextLabel_18.Size = UDim2.new(0, 70, 0, 34)
TextLabel_18.Font = Enum.Font.SourceSans
TextLabel_18.Text = "Remove-Doors"
TextLabel_18.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_18.TextScaled = true
TextLabel_18.TextSize = 14.000
TextLabel_18.TextWrapped = true

RemoveFences.Name = "Remove-Fences"
RemoveFences.Parent = Frame
RemoveFences.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
RemoveFences.BackgroundTransparency = 1.000
RemoveFences.BorderSizePixel = 0
RemoveFences.Position = UDim2.new(0.521060765, 0, 0.237495825, 0)
RemoveFences.Size = UDim2.new(0, 70, 0, 34)
RemoveFences.Font = Enum.Font.SourceSans
RemoveFences.Text = ""
RemoveFences.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveFences.TextSize = 14.000
RemoveFences.MouseButton1Down:connect(function()
	game.Workspace.Prison_Fences:Destroy()
	game.Workspace.Town_Fence:Destroy()
end)

TextButton_Roundify_12px_19.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_19.Parent = RemoveFences
TextButton_Roundify_12px_19.Active = true
TextButton_Roundify_12px_19.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_19.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_19.BackgroundTransparency = 1.000
TextButton_Roundify_12px_19.Position = UDim2.new(0.506719947, 0, 0.515151501, 0)
TextButton_Roundify_12px_19.Selectable = true
TextButton_Roundify_12px_19.Size = UDim2.new(1.01343918, 0, 1.030303, 0)
TextButton_Roundify_12px_19.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_19.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_19.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_19.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_19.SliceScale = 0.120

TextLabel_19.Parent = RemoveFences
TextLabel_19.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_19.BackgroundTransparency = 1.000
TextLabel_19.Size = UDim2.new(0, 70, 0, 34)
TextLabel_19.Font = Enum.Font.SourceSans
TextLabel_19.Text = "Remove-Fences"
TextLabel_19.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_19.TextScaled = true
TextLabel_19.TextSize = 14.000
TextLabel_19.TextWrapped = true

RemoveTrees.Name = "Remove-Trees"
RemoveTrees.Parent = Frame
RemoveTrees.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
RemoveTrees.BackgroundTransparency = 1.000
RemoveTrees.BorderSizePixel = 0
RemoveTrees.Position = UDim2.new(0.0654394403, 0, 0.607479095, 0)
RemoveTrees.Size = UDim2.new(0, 70, 0, 34)
RemoveTrees.Font = Enum.Font.SourceSans
RemoveTrees.Text = ""
RemoveTrees.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveTrees.TextSize = 14.000
RemoveTrees.MouseButton1Down:connect(function()
	game.Workspace.Trees:Destroy()
	game.Workspace.Prison_Trees:Destroy()
	game.Workspace.Square_trees:Destroy()
end)

TextButton_Roundify_12px_20.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_20.Parent = RemoveTrees
TextButton_Roundify_12px_20.Active = true
TextButton_Roundify_12px_20.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_20.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_20.BackgroundTransparency = 1.000
TextButton_Roundify_12px_20.Position = UDim2.new(0.506719947, 0, 0.515151501, 0)
TextButton_Roundify_12px_20.Selectable = true
TextButton_Roundify_12px_20.Size = UDim2.new(1.01343918, 0, 1.030303, 0)
TextButton_Roundify_12px_20.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_20.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_20.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_20.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_20.SliceScale = 0.120

TextLabel_20.Parent = RemoveTrees
TextLabel_20.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_20.BackgroundTransparency = 1.000
TextLabel_20.Size = UDim2.new(0, 70, 0, 34)
TextLabel_20.Font = Enum.Font.SourceSans
TextLabel_20.Text = "Remove-Trees"
TextLabel_20.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_20.TextScaled = true
TextLabel_20.TextSize = 14.000
TextLabel_20.TextWrapped = true

RemoveWalls.Name = "Remove-Walls"
RemoveWalls.Parent = Frame
RemoveWalls.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
RemoveWalls.BackgroundTransparency = 1.000
RemoveWalls.BorderSizePixel = 0
RemoveWalls.Position = UDim2.new(0.521060765, 0, 0.607479095, 0)
RemoveWalls.Size = UDim2.new(0, 70, 0, 34)
RemoveWalls.Font = Enum.Font.SourceSans
RemoveWalls.Text = ""
RemoveWalls.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveWalls.TextSize = 14.000
RemoveWalls.MouseButton1Down:connect(function()
	wait(0.1)
	game.Workspace.Prison_Guard_Outpost:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.building:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.glass:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.oven:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.shelves:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.vents:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.accents:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.vendingmachine:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.Prison_table1:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.counter:Remove()
	
	wait(0.1)
	game.Workspace.Prison_Cafeteria.boxes:Remove()
end)


TextButton_Roundify_12px_21.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_21.Parent = RemoveWalls
TextButton_Roundify_12px_21.Active = true
TextButton_Roundify_12px_21.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_21.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_21.BackgroundTransparency = 1.000
TextButton_Roundify_12px_21.Position = UDim2.new(0.506719947, 0, 0.515151501, 0)
TextButton_Roundify_12px_21.Selectable = true
TextButton_Roundify_12px_21.Size = UDim2.new(1.01343918, 0, 1.030303, 0)
TextButton_Roundify_12px_21.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_21.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_21.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_21.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_21.SliceScale = 0.120

TextLabel_21.Parent = RemoveWalls
TextLabel_21.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_21.BackgroundTransparency = 1.000
TextLabel_21.Size = UDim2.new(0, 70, 0, 34)
TextLabel_21.Font = Enum.Font.SourceSans
TextLabel_21.Text = "Remove-Walls"
TextLabel_21.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_21.TextScaled = true
TextLabel_21.TextSize = 14.000
TextLabel_21.TextWrapped = true

Exit.Name = "Exit"
Exit.Parent = Frame
Exit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Exit.BackgroundTransparency = 1.000
Exit.BorderSizePixel = 0
Exit.Position = UDim2.new(0.79289943, 0, 0, 0)
Exit.Size = UDim2.new(0, 35, 0, 35)
Exit.Font = Enum.Font.SourceSans
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(255, 0, 0)
Exit.TextScaled = true
Exit.TextSize = 14.000
Exit.TextWrapped = true
Exit.MouseButton1Down:connect(function()
	Frame.Visible = false
end)

Rage.Name = "Rage"
Rage.Parent = PlaceHolder
Rage.Active = true
Rage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Rage.BackgroundTransparency = 1.000
Rage.Position = UDim2.new(-0.000487621874, 0, -0.00108341035, 0)
Rage.Size = UDim2.new(0, 422, 0, 284)
Rage.Visible = false
Rage.Image = "rbxassetid://3570695787"
Rage.ImageColor3 = Color3.fromRGB(75, 255, 147)
Rage.ScaleType = Enum.ScaleType.Slice
Rage.SliceCenter = Rect.new(100, 100, 100, 100)
Rage.SliceScale = 0.120
Rage.Active = true

Killall.Name = "Kill all"
Killall.Parent = Rage
Killall.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Killall.BackgroundTransparency = 1.000
Killall.BorderSizePixel = 0
Killall.Position = UDim2.new(0.0853080601, 0, 0.309859157, 0)
Killall.Size = UDim2.new(0, 81, 0, 36)
Killall.Font = Enum.Font.SourceSans
Killall.Text = ""
Killall.TextColor3 = Color3.fromRGB(0, 0, 0)
Killall.TextSize = 14.000
Killall.MouseButton1Down:connect(function()
	workspace.Remote.TeamEvent:FireServer("Medium stone grey")
	
	game.Workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP) 
	
	wait(0.5)
	function kill(a)
		local A_1 =
			{
			[1] =
				{
				["RayObject"] = Ray.new(Vector3.new(845.555908, 101.429337, 2269.43945), Vector3.new(-391.152252, 8.65560055, -83.2166901)),
				["Distance"] = 3.2524313926697,
				["Cframe"] = CFrame.new(840.310791, 101.334137, 2267.87988, 0.0636406094, 0.151434347, -0.986416459, 0, 0.988420188, 0.151741937, 0.997972965, -0.00965694897, 0.0629036576),
				["Hit"] = a.Character.Head
			},
			[2] =
				{
				["RayObject"] = Ray.new(Vector3.new(845.555908, 101.429337, 2269.43945), Vector3.new(-392.481476, -8.44939327, -76.7261353)),
				["Distance"] = 3.2699294090271,
				["Cframe"] = CFrame.new(840.290466, 101.184189, 2267.93506, 0.0964837447, 0.0589403138, -0.993587971, 4.65661287e-10, 0.998245299, 0.0592165813, 0.995334625, -0.00571343815, 0.0963144377),
				["Hit"] = a.Character.Head
			},
			[3] =
				{
				["RayObject"] = Ray.new(Vector3.new(845.555908, 101.429337, 2269.43945), Vector3.new(-389.21701, -2.50536323, -92.2163162)),
				["Distance"] = 3.1665518283844,
				["Cframe"] = CFrame.new(840.338867, 101.236496, 2267.80371, 0.0166504811, 0.0941716284, -0.995416701, 1.16415322e-10, 0.995554805, 0.0941846818, 0.999861419, -0.00156822044, 0.0165764652),
				["Hit"] = a.Character.Head
			},
			[4] =
				{
				["RayObject"] = Ray.new(Vector3.new(845.555908, 101.429337, 2269.43945), Vector3.new(-393.353973, 3.13988972, -72.5452042)),
				["Distance"] = 3.3218522071838,
				["Cframe"] = CFrame.new(840.277222, 101.285957, 2267.9707, 0.117109694, 0.118740402, -0.985994935, -1.86264515e-09, 0.992826641, 0.119563118, 0.993119001, -0.0140019981, 0.116269611),
				["Hit"] = a.Character.Head
			},
			[5] =
				{
				["RayObject"] = Ray.new(Vector3.new(845.555908, 101.429337, 2269.43945), Vector3.new(-390.73172, 3.2097764, -85.5477524)),
				["Distance"] = 3.222757101059,
				["Cframe"] = CFrame.new(840.317993, 101.286423, 2267.86035, 0.0517584644, 0.123365127, -0.991010666, 0, 0.992340803, 0.123530701, 0.99865967, -0.00639375951, 0.0513620302),
				["Hit"] = a.Character.Head
			}
		}
		local A_2 = game.Players.LocalPlayer.Backpack["Remington 870"]
		local Event = game:GetService("ReplicatedStorage").ShootEvent
		Event:FireServer(A_1, A_2)
		Event:FireServer(A_1, A_2)
	end
	
	for i,v in pairs(game.Players:GetChildren())do
		if v.Name ~= game.Players.LocalPlayer.Name then
			kill(v)
		end
	end
	wait(1)
	workspace.Remote.TeamEvent:FireServer("Bright orange")
end)


TextButton_Roundify_12px_22.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_22.Parent = Killall
TextButton_Roundify_12px_22.Active = true
TextButton_Roundify_12px_22.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_22.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_22.BackgroundTransparency = 1.000
TextButton_Roundify_12px_22.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_22.Selectable = true
TextButton_Roundify_12px_22.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_22.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_22.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_22.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_22.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_22.SliceScale = 0.120

TextLabel_22.Parent = Killall
TextLabel_22.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_22.BackgroundTransparency = 1.000
TextLabel_22.Size = UDim2.new(0, 81, 0, 36)
TextLabel_22.Font = Enum.Font.SourceSans
TextLabel_22.Text = "Kill all"
TextLabel_22.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_22.TextSize = 14.000

Killaura.Name = "Kill aura"
Killaura.Parent = Rage
Killaura.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
Killaura.BackgroundTransparency = 1.000
Killaura.BorderSizePixel = 0
Killaura.Position = UDim2.new(0.296208531, 0, 0.309859157, 0)
Killaura.Size = UDim2.new(0, 81, 0, 36)
Killaura.Font = Enum.Font.SourceSans
Killaura.Text = ""
Killaura.TextColor3 = Color3.fromRGB(0, 0, 0)
Killaura.TextSize = 14.000
Killaura.MouseButton1Down:connect(function()
	mainRemotes = game.ReplicatedStorage
	meleeRemote = mainRemotes['meleeEvent']
	
	killAura = true
	
	contextactionservice = game.ContextActionService
	
	function toggleKillAura(actionName, inputState, inputObject)
		print('Doing the action : ' .. actionName)
		if inputState == Enum.UserInputState.Begin then
			if killAura == true then
				killAura = false
			else
				killAura = true
			end
		end
	end
	
	contextactionservice:BindAction('ToggleKillAura', toggleKillAura, false, Enum.KeyCode.K)
	
	while wait() do
		if killAura == true then
			for _, plr in pairs (game:GetService('Players'):GetChildren()) do
				if plr.Name ~= game.Players.LocalPlayer.Name then
					meleeRemote:FireServer(plr)
				end
			end
		end
	end
end)


TextButton_Roundify_12px_23.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_23.Parent = Killaura
TextButton_Roundify_12px_23.Active = true
TextButton_Roundify_12px_23.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_23.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_23.BackgroundTransparency = 1.000
TextButton_Roundify_12px_23.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_23.Selectable = true
TextButton_Roundify_12px_23.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_23.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_23.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_23.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_23.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_23.SliceScale = 0.120

TextLabel_23.Parent = Killaura
TextLabel_23.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_23.BackgroundTransparency = 1.000
TextLabel_23.Size = UDim2.new(0, 81, 0, 36)
TextLabel_23.Font = Enum.Font.SourceSans
TextLabel_23.Text = "Kill aura"
TextLabel_23.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_23.TextSize = 14.000

Teleports.Name = "Teleports"
Teleports.Parent = PlaceHolder
Teleports.Active = true
Teleports.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Teleports.BackgroundTransparency = 1.000
Teleports.Position = UDim2.new(0.00066709891, 0, 0.00393331889, 0)
Teleports.Size = UDim2.new(0, 422, 0, 284)
Teleports.Visible = false
Teleports.Image = "rbxassetid://3570695787"
Teleports.ImageColor3 = Color3.fromRGB(75, 255, 147)
Teleports.ScaleType = Enum.ScaleType.Slice
Teleports.SliceCenter = Rect.new(100, 100, 100, 100)
Teleports.SliceScale = 0.120

CrimBaseTP.Name = "Crim-BaseTP"
CrimBaseTP.Parent = Teleports
CrimBaseTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
CrimBaseTP.BackgroundTransparency = 1.000
CrimBaseTP.BorderSizePixel = 0
CrimBaseTP.Position = UDim2.new(0.0853080601, 0, 0.309859157, 0)
CrimBaseTP.Size = UDim2.new(0, 81, 0, 36)
CrimBaseTP.Font = Enum.Font.SourceSans
CrimBaseTP.Text = ""
CrimBaseTP.TextColor3 = Color3.fromRGB(0, 0, 0)
CrimBaseTP.TextSize = 14.000
CrimBaseTP.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-943.46,94.13,2063.63)
end)


TextButton_Roundify_12px_24.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_24.Parent = CrimBaseTP
TextButton_Roundify_12px_24.Active = true
TextButton_Roundify_12px_24.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_24.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_24.BackgroundTransparency = 1.000
TextButton_Roundify_12px_24.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_24.Selectable = true
TextButton_Roundify_12px_24.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_24.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_24.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_24.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_24.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_24.SliceScale = 0.120

TextLabel_24.Parent = CrimBaseTP
TextLabel_24.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_24.BackgroundTransparency = 1.000
TextLabel_24.Size = UDim2.new(0, 81, 0, 36)
TextLabel_24.Font = Enum.Font.SourceSans
TextLabel_24.Text = "Crim-Base"
TextLabel_24.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_24.TextSize = 14.000

CtrlClickTP.Name = "Ctrl-Click-TP"
CtrlClickTP.Parent = Teleports
CtrlClickTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
CtrlClickTP.BackgroundTransparency = 1.000
CtrlClickTP.BorderSizePixel = 0
CtrlClickTP.Position = UDim2.new(0.293838859, 0, 0.64084506, 0)
CtrlClickTP.Size = UDim2.new(0, 81, 0, 36)
CtrlClickTP.Font = Enum.Font.SourceSans
CtrlClickTP.Text = ""
CtrlClickTP.TextColor3 = Color3.fromRGB(0, 0, 0)
CtrlClickTP.TextSize = 14.000
CtrlClickTP.MouseButton1Down:connect(function()
	--[[local Plr = game:GetService("Players").LocalPlayer
local Mouse = Plr:GetMouse()
 
Mouse.Button1Down:connect(function()
if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
if not Mouse.Target then return end
Plr.Character:MoveTo(Mouse.Hit.p)
end)
--]]
	game:GetService("StarterGui"):SetCore("SendNotification",{
		Title = "CTRL click tp",
		Text = "Hold Ctrl then press click to a place you want to teleport to.",
		Duration = 6,
	})
	local speed = 100 -- set this lower to make it slower
	local bodyvelocityenabled = true -- set this to false if you are getting kicked
	
	local Imput = game:GetService("UserInputService")
	local Plr = game.Players.LocalPlayer
	local Mouse = Plr:GetMouse()
	
	function To(position)
		local Chr = Plr.Character
		if Chr ~= nil then
			local ts = game:GetService("TweenService")
			local char = game.Players.LocalPlayer.Character
			local hm = char.HumanoidRootPart
			local dist = (hm.Position - Mouse.Hit.p).magnitude
			local tweenspeed = dist/tonumber(speed)
			local ti = TweenInfo.new(tonumber(tweenspeed), Enum.EasingStyle.Linear)
			local tp = {CFrame = CFrame.new(position)}
			ts:Create(hm, ti, tp):Play()
			if bodyvelocityenabled == true then
				local bv = Instance.new("BodyVelocity")
				bv.Parent = hm
				bv.MaxForce = Vector3.new(100000,100000,100000)
				bv.Velocity = Vector3.new(0,0,0)
				wait(tonumber(tweenspeed))
				bv:Destroy()
			end
		end
	end
	
	Imput.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 and Imput:IsKeyDown(Enum.KeyCode.LeftControl) then
			To(Mouse.Hit.p)
		end
	end)
end)

TextButton_Roundify_12px_25.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_25.Parent = CtrlClickTP
TextButton_Roundify_12px_25.Active = true
TextButton_Roundify_12px_25.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_25.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_25.BackgroundTransparency = 1.000
TextButton_Roundify_12px_25.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_25.Selectable = true
TextButton_Roundify_12px_25.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_25.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_25.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_25.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_25.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_25.SliceScale = 0.120

TextLabel_25.Parent = CtrlClickTP
TextLabel_25.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_25.BackgroundTransparency = 1.000
TextLabel_25.Size = UDim2.new(0, 81, 0, 36)
TextLabel_25.Font = Enum.Font.SourceSans
TextLabel_25.Text = "Ctrl-Click-Tp"
TextLabel_25.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_25.TextSize = 14.000
TextLabel_25.TextWrapped = true

CarSpawnTP.Name = "Car-SpawnTP"
CarSpawnTP.Parent = Teleports
CarSpawnTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
CarSpawnTP.BackgroundTransparency = 1.000
CarSpawnTP.BorderSizePixel = 0
CarSpawnTP.Position = UDim2.new(0.0853080601, 0, 0.64084506, 0)
CarSpawnTP.Size = UDim2.new(0, 81, 0, 36)
CarSpawnTP.Font = Enum.Font.SourceSans
CarSpawnTP.Text = ""
CarSpawnTP.TextColor3 = Color3.fromRGB(0, 0, 0)
CarSpawnTP.TextSize = 14.000
CarSpawnTP.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-910.46,94.13,2150.63)
end)

TextButton_Roundify_12px_26.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_26.Parent = CarSpawnTP
TextButton_Roundify_12px_26.Active = true
TextButton_Roundify_12px_26.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_26.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_26.BackgroundTransparency = 1.000
TextButton_Roundify_12px_26.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_26.Selectable = true
TextButton_Roundify_12px_26.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_26.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_26.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_26.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_26.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_26.SliceScale = 0.120

TextLabel_26.Parent = CarSpawnTP
TextLabel_26.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_26.BackgroundTransparency = 1.000
TextLabel_26.Size = UDim2.new(0, 81, 0, 36)
TextLabel_26.Font = Enum.Font.SourceSans
TextLabel_26.Text = "Car-Spawn"
TextLabel_26.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_26.TextSize = 14.000

TopPrisonTP.Name = "Top-PrisonTP"
TopPrisonTP.Parent = Teleports
TopPrisonTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
TopPrisonTP.BackgroundTransparency = 1.000
TopPrisonTP.BorderSizePixel = 0
TopPrisonTP.Position = UDim2.new(0.293838859, 0, 0.475352108, 0)
TopPrisonTP.Size = UDim2.new(0, 81, 0, 36)
TopPrisonTP.Font = Enum.Font.SourceSans
TopPrisonTP.Text = ""
TopPrisonTP.TextColor3 = Color3.fromRGB(0, 0, 0)
TopPrisonTP.TextSize = 14.000
TopPrisonTP.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(918.77,120,2379.07)
end)


TextButton_Roundify_12px_27.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_27.Parent = TopPrisonTP
TextButton_Roundify_12px_27.Active = true
TextButton_Roundify_12px_27.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_27.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_27.BackgroundTransparency = 1.000
TextButton_Roundify_12px_27.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_27.Selectable = true
TextButton_Roundify_12px_27.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_27.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_27.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_27.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_27.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_27.SliceScale = 0.120

TextLabel_27.Parent = TopPrisonTP
TextLabel_27.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_27.BackgroundTransparency = 1.000
TextLabel_27.Size = UDim2.new(0, 81, 0, 36)
TextLabel_27.Font = Enum.Font.SourceSans
TextLabel_27.Text = "Top-Prison"
TextLabel_27.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_27.TextSize = 14.000

PrisonTP.Name = "PrisonTP"
PrisonTP.Parent = Teleports
PrisonTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
PrisonTP.BackgroundTransparency = 1.000
PrisonTP.BorderSizePixel = 0
PrisonTP.Position = UDim2.new(0.293838859, 0, 0.309859157, 0)
PrisonTP.Size = UDim2.new(0, 81, 0, 36)
PrisonTP.Font = Enum.Font.SourceSans
PrisonTP.Text = ""
PrisonTP.TextColor3 = Color3.fromRGB(0, 0, 0)
PrisonTP.TextSize = 14.000
PrisonTP.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(918.77,100,2379.07)
end)


TextButton_Roundify_12px_28.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_28.Parent = PrisonTP
TextButton_Roundify_12px_28.Active = true
TextButton_Roundify_12px_28.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_28.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_28.BackgroundTransparency = 1.000
TextButton_Roundify_12px_28.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_28.Selectable = true
TextButton_Roundify_12px_28.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_28.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_28.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_28.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_28.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_28.SliceScale = 0.120

TextLabel_28.Parent = PrisonTP
TextLabel_28.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_28.BackgroundTransparency = 1.000
TextLabel_28.Size = UDim2.new(0, 81, 0, 36)
TextLabel_28.Font = Enum.Font.SourceSans
TextLabel_28.Text = "Prison"
TextLabel_28.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_28.TextSize = 14.000

YardTP.Name = "YardTP"
YardTP.Parent = Teleports
YardTP.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
YardTP.BackgroundTransparency = 1.000
YardTP.BorderSizePixel = 0
YardTP.Position = UDim2.new(0.0853080601, 0, 0.475352108, 0)
YardTP.Size = UDim2.new(0, 81, 0, 36)
YardTP.Font = Enum.Font.SourceSans
YardTP.Text = ""
YardTP.TextColor3 = Color3.fromRGB(0, 0, 0)
YardTP.TextSize = 14.000
YardTP.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(779.87,98,2458.93)
end)


TextButton_Roundify_12px_29.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_29.Parent = YardTP
TextButton_Roundify_12px_29.Active = true
TextButton_Roundify_12px_29.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_29.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_29.BackgroundTransparency = 1.000
TextButton_Roundify_12px_29.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_29.Selectable = true
TextButton_Roundify_12px_29.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_29.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_29.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_29.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_29.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_29.SliceScale = 0.120

TextLabel_29.Parent = YardTP
TextLabel_29.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_29.BackgroundTransparency = 1.000
TextLabel_29.Size = UDim2.new(0, 81, 0, 36)
TextLabel_29.Font = Enum.Font.SourceSans
TextLabel_29.Text = "Yard"
TextLabel_29.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_29.TextSize = 14.000
TextLabel_29.TextWrapped = true

CrimBaseTP_2.Name = "Crim-BaseTP"
CrimBaseTP_2.Parent = Teleports
CrimBaseTP_2.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
CrimBaseTP_2.BackgroundTransparency = 1.000
CrimBaseTP_2.BorderSizePixel = 0
CrimBaseTP_2.Position = UDim2.new(0.0853080601, 0, 0.806338072, 0)
CrimBaseTP_2.Size = UDim2.new(0, 81, 0, 36)
CrimBaseTP_2.Font = Enum.Font.SourceSans
CrimBaseTP_2.Text = ""
CrimBaseTP_2.TextColor3 = Color3.fromRGB(0, 0, 0)
CrimBaseTP_2.TextSize = 14.000
CrimBaseTP_2.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(800.77,130,2580.07)
end)


TextButton_Roundify_12px_30.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_30.Parent = CrimBaseTP_2
TextButton_Roundify_12px_30.Active = true
TextButton_Roundify_12px_30.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_30.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_30.BackgroundTransparency = 1.000
TextButton_Roundify_12px_30.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_30.Selectable = true
TextButton_Roundify_12px_30.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_30.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_30.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_30.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_30.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_30.SliceScale = 0.120

TextLabel_30.Parent = CrimBaseTP_2
TextLabel_30.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_30.BackgroundTransparency = 1.000
TextLabel_30.Size = UDim2.new(0, 81, 0, 36)
TextLabel_30.Font = Enum.Font.SourceSans
TextLabel_30.Text = "Guard-Tower"
TextLabel_30.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_30.TextSize = 14.000

CrimBaseTP_3.Name = "Crim-BaseTP"
CrimBaseTP_3.Parent = Teleports
CrimBaseTP_3.BackgroundColor3 = Color3.fromRGB(0, 255, 217)
CrimBaseTP_3.BackgroundTransparency = 1.000
CrimBaseTP_3.BorderSizePixel = 0
CrimBaseTP_3.Position = UDim2.new(0.293838859, 0, 0.806338072, 0)
CrimBaseTP_3.Size = UDim2.new(0, 81, 0, 36)
CrimBaseTP_3.Font = Enum.Font.SourceSans
CrimBaseTP_3.Text = ""
CrimBaseTP_3.TextColor3 = Color3.fromRGB(0, 0, 0)
CrimBaseTP_3.TextSize = 14.000
CrimBaseTP_3.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(818.77,100,2279.07)
end)

TextButton_Roundify_12px_31.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_31.Parent = CrimBaseTP_3
TextButton_Roundify_12px_31.Active = true
TextButton_Roundify_12px_31.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_31.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_31.BackgroundTransparency = 1.000
TextButton_Roundify_12px_31.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_31.Selectable = true
TextButton_Roundify_12px_31.Size = UDim2.new(1.00000012, 0, 1, 0)
TextButton_Roundify_12px_31.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_31.ImageColor3 = Color3.fromRGB(0, 255, 217)
TextButton_Roundify_12px_31.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_31.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_31.SliceScale = 0.120

TextLabel_31.Parent = CrimBaseTP_3
TextLabel_31.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_31.BackgroundTransparency = 1.000
TextLabel_31.Size = UDim2.new(0, 81, 0, 36)
TextLabel_31.Font = Enum.Font.SourceSans
TextLabel_31.Text = "Guard-Spawn"
TextLabel_31.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_31.TextSize = 14.000

TabControl.Name = "TabControl"
TabControl.Parent = PlaceHolder
TabControl.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TabControl.BackgroundTransparency = 1.000
TabControl.Position = UDim2.new(0.00136566162, 0, 0.171204478, 0)
TabControl.Size = UDim2.new(0, 421, 0, 20)
TabControl.Visible = false

MainMain.Name = "MainMain"
MainMain.Parent = TabControl
MainMain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainMain.BackgroundTransparency = 1.000
MainMain.Position = UDim2.new(0, 0, 0.161971822, 0)
MainMain.Size = UDim2.new(0, 135, 0, 20)
MainMain.Font = Enum.Font.SourceSans
MainMain.Text = "Main"
MainMain.TextColor3 = Color3.fromRGB(0, 0, 0)
MainMain.TextScaled = true
MainMain.TextSize = 13.000
MainMain.TextWrapped = true
MainMain.MouseButton1Down:connect(function()
	Main.Visible = true
	Rage.Visible = false
	Teleports.Visible = false
end)

MainRage.Name = "MainRage"
MainRage.Parent = TabControl
MainRage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainRage.BackgroundTransparency = 1.000
MainRage.Position = UDim2.new(0.677725136, 0, 0.161971837, 0)
MainRage.Size = UDim2.new(0, 136, 0, 20)
MainRage.Font = Enum.Font.SourceSans
MainRage.Text = "Rage"
MainRage.TextColor3 = Color3.fromRGB(0, 0, 0)
MainRage.TextScaled = true
MainRage.TextSize = 14.000
MainRage.TextWrapped = true
MainRage.MouseButton1Down:connect(function()
	Main.Visible = false
	Rage.Visible = true
	Teleports.Visible = false
end)

MainTeleports.Name = "MainTeleports"
MainTeleports.Parent = TabControl
MainTeleports.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainTeleports.BackgroundTransparency = 1.000
MainTeleports.Position = UDim2.new(0.319905221, 0, 0.161971837, 0)
MainTeleports.Size = UDim2.new(0, 151, 0, 20)
MainTeleports.Font = Enum.Font.SourceSans
MainTeleports.Text = "Teleports"
MainTeleports.TextColor3 = Color3.fromRGB(0, 0, 0)
MainTeleports.TextScaled = true
MainTeleports.TextSize = 14.000
MainTeleports.TextWrapped = true
MainTeleports.MouseButton1Down:connect(function()
	Main.Visible = false
	Rage.Visible = false
	Teleports.Visible = true
end)

TopBar.Name = "TopBar"
TopBar.Parent = PlaceHolder
TopBar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopBar.BackgroundTransparency = 1.000
TopBar.Position = UDim2.new(0.00136562437, 0, -0.00156628247, 0)
TopBar.Size = UDim2.new(0, 421, 0, 47)
TopBar.Image = "rbxassetid://3570695787"
TopBar.ImageColor3 = Color3.fromRGB(32, 221, 70)
TopBar.ImageTransparency = 0.010
TopBar.ScaleType = Enum.ScaleType.Slice
TopBar.SliceCenter = Rect.new(100, 100, 100, 100)
TopBar.SliceScale = 0.120
TopBar.Visible = false

Frame_2.Parent = TopBar
Frame_2.BackgroundColor3 = Color3.fromRGB(32, 221, 70)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 0.595744669, 0)
Frame_2.Size = UDim2.new(0, 423, 0, 19)

TextLabel_32.Parent = TopBar
TextLabel_32.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_32.BackgroundTransparency = 1.000
TextLabel_32.Position = UDim2.new(-0.00475059403, 0, 0, 0)
TextLabel_32.Size = UDim2.new(0, 421, 0, 47)
TextLabel_32.Font = Enum.Font.SourceSans
TextLabel_32.Text = "Prison Fun"
TextLabel_32.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_32.TextScaled = true
TextLabel_32.TextSize = 14.000
TextLabel_32.TextWrapped = true

Exit_2.Name = "Exit"
Exit_2.Parent = TopBar
Exit_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Exit_2.BackgroundTransparency = 1.000
Exit_2.Position = UDim2.new(0.889424324, 0, -0.0503098518, 0)
Exit_2.Size = UDim2.new(0, 47, 0, 49)
Exit_2.Font = Enum.Font.SourceSans
Exit_2.Text = "X"
Exit_2.TextColor3 = Color3.fromRGB(255, 0, 4)
Exit_2.TextScaled = true
Exit_2.TextSize = 14.000
Exit_2.TextWrapped = true
Exit_2.MouseButton1Down:connect(function()
	Main.Visible = false
	Rage.Visible = false
	Teleports.Visible = false
	TopBar.Visible = false
	TabControl.Visible = false
	Open.Visible = true
	PlaceHolder.Visible = false
end)
game:GetService("StarterGui"):SetCore("SendNotification", {
	Title = "Welcome!";
	Text = "Made by KrakVolt";
})
wait(.1)
game:GetService("StarterGui"):SetCore("SendNotification", {
	Title = "Credits";
	Text = "Thanks to Jake11Price for some of the scripts";
})
wait(.1)
game:GetService("StarterGui"):SetCore("SendNotification", {
	Title = "Credits";
	Text = "Thanks to Jmuse for the fly car script";
})
