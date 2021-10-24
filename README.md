local petsimxgui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local title = Instance.new("TextLabel")
local spawnTP = Instance.new("TextButton")
local teleportsTITLE = Instance.new("TextLabel")
local beachTP = Instance.new("TextButton")
local townTP = Instance.new("TextButton")
local mineTP = Instance.new("TextButton")
local volcanoTP = Instance.new("TextButton")
local desertTP = Instance.new("TextButton")
local glacierTP = Instance.new("TextButton")
local winterTP = Instance.new("TextButton")
local othersTITLE = Instance.new("TextLabel")
local fusepets = Instance.new("TextButton")
local gamepasses = Instance.new("TextButton")
local autofarm = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")


petsimxgui.Name = "petsimxgui"
petsimxgui.Parent = game.CoreGui
petsimxgui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
petsimxgui.ResetOnSpawn = false

main.Name = "main"
main.Parent = petsimxgui
main.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
main.BorderColor3 = Color3.fromRGB(60, 60, 60)
main.Position = UDim2.new(0.232695103, 0, 0.187370062, 0)
main.Size = UDim2.new(0, 317, 0, 218)
main.Active = true
main.Draggable = true

title.Name = "title"
title.Parent = main
title.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
title.BorderColor3 = Color3.fromRGB(60, 60, 60)
title.Position = UDim2.new(0.275470227, 0, 0.0275229365, 0)
title.Size = UDim2.new(0, 146, 0, 18)
title.Font = Enum.Font.SourceSans
title.Text = "pet sim x gui | by DH sus#2733"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextSize = 14.000

spawnTP.Name = "spawnTP"
spawnTP.Parent = main
spawnTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
spawnTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
spawnTP.Position = UDim2.new(0.0237460956, 0, 0.258095622, 0)
spawnTP.Size = UDim2.new(0, 66, 0, 23)
spawnTP.Font = Enum.Font.SourceSans
spawnTP.Text = "spawn"
spawnTP.TextColor3 = Color3.fromRGB(255, 255, 255)
spawnTP.TextSize = 14.000
spawnTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(157,95,242)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
teleportsTITLE.Name = "teleportsTITLE"
teleportsTITLE.Parent = main
teleportsTITLE.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
teleportsTITLE.BorderColor3 = Color3.fromRGB(27, 42, 53)
teleportsTITLE.Position = UDim2.new(0.389655173, 0, 0.145161286, 0)
teleportsTITLE.Size = UDim2.new(0, 63, 0, 22)
teleportsTITLE.Font = Enum.Font.SourceSans
teleportsTITLE.Text = "teleports"
teleportsTITLE.TextColor3 = Color3.fromRGB(255, 255, 255)
teleportsTITLE.TextSize = 14.000

beachTP.Name = "beachTP"
beachTP.Parent = main
beachTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
beachTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
beachTP.Position = UDim2.new(0.534090877, 0, 0.252719283, 0)
beachTP.Size = UDim2.new(0, 66, 0, 23)
beachTP.Font = Enum.Font.SourceSans
beachTP.Text = "beach"
beachTP.TextColor3 = Color3.fromRGB(255, 255, 255)
beachTP.TextSize = 14.000
beachTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-612,95,222)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
townTP.Name = "townTP"
townTP.Parent = main
townTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
townTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
townTP.Position = UDim2.new(0.275470257, 0, 0.258095622, 0)
townTP.Size = UDim2.new(0, 66, 0, 23)
townTP.Font = Enum.Font.SourceSans
townTP.Text = "town"
townTP.TextColor3 = Color3.fromRGB(255, 255, 255)
townTP.TextSize = 14.000
townTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-260,95,190)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
mineTP.Name = "mineTP"
mineTP.Parent = main
mineTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
mineTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
mineTP.Position = UDim2.new(0.772021949, 0, 0.244334161, 0)
mineTP.Size = UDim2.new(0, 66, 0, 23)
mineTP.Font = Enum.Font.SourceSans
mineTP.Text = "mine"
mineTP.TextColor3 = Color3.fromRGB(255, 255, 255)
mineTP.TextSize = 14.000
mineTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-975,95,230)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
volcanoTP.Name = "volcanoTP"
volcanoTP.Parent = main
volcanoTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
volcanoTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
volcanoTP.Position = UDim2.new(0.772021949, 0, 0.407134086, 0)
volcanoTP.Size = UDim2.new(0, 66, 0, 23)
volcanoTP.Font = Enum.Font.SourceSans
volcanoTP.Text = "volcano"
volcanoTP.TextColor3 = Color3.fromRGB(255, 255, 255)
volcanoTP.TextSize = 14.000
volcanoTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-2408,95,241)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
desertTP.Name = "desertTP"
desertTP.Parent = main
desertTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
desertTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
desertTP.Position = UDim2.new(0.530642629, 0, 0.407134086, 0)
desertTP.Size = UDim2.new(0, 66, 0, 23)
desertTP.Font = Enum.Font.SourceSans
desertTP.Text = "desert"
desertTP.TextColor3 = Color3.fromRGB(255, 255, 255)
desertTP.TextSize = 14.000
desertTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-2066,95,256)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
glacierTP.Name = "glacierTP"
glacierTP.Parent = main
glacierTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
glacierTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
glacierTP.Position = UDim2.new(0.275470227, 0, 0.407134086, 0)
glacierTP.Size = UDim2.new(0, 66, 0, 23)
glacierTP.Font = Enum.Font.SourceSans
glacierTP.Text = "glacier"
glacierTP.TextColor3 = Color3.fromRGB(255, 255, 255)
glacierTP.TextSize = 14.000
glacierTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-1695,96,215)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
winterTP.Name = "winterTP"
winterTP.Parent = main
winterTP.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
winterTP.BorderColor3 = Color3.fromRGB(50, 50, 50)
winterTP.Position = UDim2.new(0.0237460956, 0, 0.407134086, 0)
winterTP.Size = UDim2.new(0, 66, 0, 23)
winterTP.Font = Enum.Font.SourceSans
winterTP.Text = "winter"
winterTP.TextColor3 = Color3.fromRGB(255, 255, 255)
winterTP.TextSize = 14.000
winterTP.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
		local location = CFrame.new(-1322,95,231)
			local humanoid = game.Players.LocalPlayer.Character.Humanoid
				humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					wait(0.1)
						pl.CFrame = location
						end)
othersTITLE.Name = "othersTITLE"
othersTITLE.Parent = main
othersTITLE.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
othersTITLE.Position = UDim2.new(0.126824588, 0, 0.544125199, 0)
othersTITLE.Size = UDim2.new(0, 240, 0, 22)
othersTITLE.Font = Enum.Font.SourceSans
othersTITLE.Text = "other (gamepass and fuse made by yZii#4041)"
othersTITLE.TextColor3 = Color3.fromRGB(255, 255, 255)
othersTITLE.TextSize = 14.000

fusepets.Name = "fusepets"
fusepets.Parent = main
fusepets.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
fusepets.BorderColor3 = Color3.fromRGB(50, 50, 50)
fusepets.Position = UDim2.new(0.274958968, 0, 0.678437412, 0)
fusepets.Size = UDim2.new(0, 66, 0, 23)
fusepets.Font = Enum.Font.SourceSans
fusepets.Text = "fuse pets"
fusepets.TextColor3 = Color3.fromRGB(255, 255, 255)
fusepets.TextSize = 14.000
fusepets.MouseButton1Down:connect(function()
	while wait() do
			for i,v in pairs(game:GetService("Workspace")["__THINGS"].Pets:GetChildren()) do
						local A_1 = {
										[1] = {
															[1] = tostring(v.Name),
																				[2] = tostring(v.Name),
																									[3] = tostring(v.Name),
																														[4] = tostring(v.Name),
																																			[5] = tostring(v.Name),
																																								[6] = tostring(v.Name),
																																													[7] = tostring(v.Name),
																																																		[8] = tostring(v.Name),
																																																							[9] = tostring(v.Name),
																																																												[10] = tostring(v.Name),
																																																																	[11] = tostring(v.Name),
																																																																						[12] = tostring(v.Name)
																																																																										}
																																																																													}
																																																																																local Event = game:GetService("Workspace")["THINGS"]["REMOTES"]["fuse pets"]
																																																																																			Event:InvokeServer(A_1)
																																																																																					end
																																																																																						end
																																																																																						end)
gamepasses.Name = "gamepasses"
gamepasses.Parent = main
gamepasses.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
gamepasses.BorderColor3 = Color3.fromRGB(50, 50, 50)
gamepasses.Position = UDim2.new(0.0237460956, 0, 0.678437471, 0)
gamepasses.Size = UDim2.new(0, 72, 0, 23)
gamepasses.Font = Enum.Font.SourceSans
gamepasses.Text = "all gamepasses"
gamepasses.TextColor3 = Color3.fromRGB(255, 255, 255)
gamepasses.TextSize = 13.000
gamepasses.MouseButton1Down:connect(function()
	local gmppath = require(game:GetService("ReplicatedStorage").Framework.Modules.Client["5 | Gamepasses"])
		gmppath.Owns = function() return true end
		end)
autofarm.Name = "autofarm"
autofarm.Parent = main
autofarm.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
autofarm.BorderColor3 = Color3.fromRGB(50, 50, 50)
autofarm.Position = UDim2.new(0.564668298, 0, 0.6784513, 0)
autofarm.Size = UDim2.new(0, 129, 0, 60)
autofarm.Font = Enum.Font.SourceSans
autofarm.Text = "AUTOFARM BY vlxne.spinxo#5577"
autofarm.TextColor3 = Color3.fromRGB(255, 255, 255)
autofarm.TextSize = 14.000
autofarm.TextWrapped = true
autofarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/Alleexxi/releasedscritps/main/script%20(1).lua'))()
	end)
UICorner.Parent = main

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.01, Color3.fromRGB(124, 124, 124)), ColorSequenceKeypoint.new(0.80, Color3.fromRGB(226, 226, 226)), ColorSequenceKeypoint.new(0.99, Color3.fromRGB(252, 252, 252)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(122, 122, 122))}
UIGradient.Parent = main


game:GetService("StarterGui"):SetCore("SendNotification",{     
	Title = "CREDITS",     
		Text = "made by DH sus#2733 and yZii#4041",
			Button1 = ":D",     Duration = 20, })
