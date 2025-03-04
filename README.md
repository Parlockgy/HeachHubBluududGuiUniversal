
local Script = Instance.new("Frame")
local menu_1 = Instance.new("TextLabel")
local UIStroke_1 = Instance.new("UIStroke")
local Skybutton_1 = Instance.new("TextButton")
local UIStroke_2 = Instance.new("UIStroke")
local UIStroke_3 = Instance.new("UIStroke")
local Messagebutton_1 = Instance.new("TextButton")
local UIStroke_4 = Instance.new("UIStroke")
local UIStroke_5 = Instance.new("UIStroke")
local Texturebutton_1 = Instance.new("TextButton")
local UIStroke_6 = Instance.new("UIStroke")
local UIStroke_7 = Instance.new("UIStroke")
local Lagbutton_1 = Instance.new("TextButton")
local UIStroke_8 = Instance.new("UIStroke")
local UIStroke_9 = Instance.new("UIStroke")

-- Properties:
Script.Name = "Script"
Script.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Script.BackgroundColor3 = Color3.fromRGB(99,99,249)
Script.BorderColor3 = Color3.fromRGB(0,0,0)
Script.BorderSizePixel = 0
Script.Size = UDim2.new(0, 269,0, 103)

menu_1.Name = "menu"
menu_1.Parent = Script
menu_1.BackgroundColor3 = Color3.fromRGB(255,255,255)
menu_1.BackgroundTransparency = 1
menu_1.BorderColor3 = Color3.fromRGB(0,0,0)
menu_1.BorderSizePixel = 0
menu_1.Position = UDim2.new(0.0360857062, 0,-0.000722052995, 0)
menu_1.Size = UDim2.new(0, 179,0, 33)
menu_1.Font = Enum.Font.Unknown
menu_1.Text = "BLUUDUD Gui"
menu_1.TextColor3 = Color3.fromRGB(255,255,255)
menu_1.TextScaled = true
menu_1.TextSize = 14
menu_1.TextWrapped = true

UIStroke_1.Parent = menu_1
UIStroke_1.Thickness = 3

Skybutton_1.Name = "Skybutton"
Skybutton_1.Parent = Script
Skybutton_1.Active = true
Skybutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Skybutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Skybutton_1.BorderSizePixel = 0
Skybutton_1.Position = UDim2.new(0.0324189439, 0,0.407339603, 0)
Skybutton_1.Size = UDim2.new(0, 118,0, 18)
Skybutton_1.Font = Enum.Font.Unknown
Skybutton_1.Text = "Change Sky"
Skybutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Skybutton_1.TextScaled = true
Skybutton_1.TextSize = 14
Skybutton_1.TextWrapped = true

UIStroke_2.Parent = Skybutton_1
UIStroke_2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_2.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_2.Thickness = 3

UIStroke_3.Parent = Skybutton_1
UIStroke_3.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_3.Thickness = 2

Messagebutton_1.Name = "Messagebutton"
Messagebutton_1.Parent = Script
Messagebutton_1.Active = true
Messagebutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Messagebutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Messagebutton_1.BorderSizePixel = 0
Messagebutton_1.Position = UDim2.new(0.516796231, 0,0.407339603, 0)
Messagebutton_1.Size = UDim2.new(0, 118,0, 18)
Messagebutton_1.Font = Enum.Font.Unknown
Messagebutton_1.Text = "Hacking Message"
Messagebutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Messagebutton_1.TextScaled = true
Messagebutton_1.TextSize = 14
Messagebutton_1.TextWrapped = true

UIStroke_4.Parent = Messagebutton_1
UIStroke_4.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_4.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_4.Thickness = 3

UIStroke_5.Parent = Messagebutton_1
UIStroke_5.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_5.Thickness = 2

Texturebutton_1.Name = "Texturebutton"
Texturebutton_1.Parent = Script
Texturebutton_1.Active = true
Texturebutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Texturebutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Texturebutton_1.BorderSizePixel = 0
Texturebutton_1.Position = UDim2.new(0.517590404, 0,0.713406265, 0)
Texturebutton_1.Size = UDim2.new(0, 118,0, 18)
Texturebutton_1.Font = Enum.Font.Unknown
Texturebutton_1.Text = "Textures Changer"
Texturebutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Texturebutton_1.TextScaled = true
Texturebutton_1.TextSize = 14
Texturebutton_1.TextWrapped = true

UIStroke_6.Parent = Texturebutton_1
UIStroke_6.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_6.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_6.Thickness = 3

UIStroke_7.Parent = Texturebutton_1
UIStroke_7.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_7.Thickness = 2

Lagbutton_1.Name = "Lagbutton"
Lagbutton_1.Parent = Script
Lagbutton_1.Active = true
Lagbutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Lagbutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Lagbutton_1.BorderSizePixel = 0
Lagbutton_1.Position = UDim2.new(0.0324189439, 0,0.713406265, 0)
Lagbutton_1.Size = UDim2.new(0, 118,0, 18)
Lagbutton_1.Font = Enum.Font.Unknown
Lagbutton_1.Text = "Lag Game"
Lagbutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Lagbutton_1.TextScaled = true
Lagbutton_1.TextSize = 14
Lagbutton_1.TextWrapped = true

UIStroke_8.Parent = Lagbutton_1
UIStroke_8.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_8.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_8.Thickness = 3

UIStroke_9.Parent = Lagbutton_1
UIStroke_9.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_9.Thickness = 2

local function znZuZEZSLLwYdSGm()
local script = Instance.new("Script",Skybutton_1)
local button = script.Parent
local Lighting = game:GetService("Lighting")

local function replaceSky()
	for _, obj in ipairs(Lighting:GetChildren()) do
		if obj:IsA("Sky") then
			obj:Destroy()
		end
	end

	local newSky = Instance.new("Sky")
	newSky.Name = "BLUUDUDHACKEDYOU"
	newSky.SkyboxBk = "rbxassetid://117040568125131"
	newSky.SkyboxDn = "rbxassetid://117040568125131"
	newSky.SkyboxFt = "rbxassetid://117040568125131"
	newSky.SkyboxLf = "rbxassetid://117040568125131"
	newSky.SkyboxRt = "rbxassetid://117040568125131"
	newSky.SkyboxUp = "rbxassetid://117040568125131"
	newSky.SunTextureId = "rbxassetid://0"

	newSky.Parent = Lighting
end

button.MouseButton1Click:Connect(replaceSky)

end
coroutine.wrap(znZuZEZSLLwYdSGm)()


local function CQxMkihCvsuHkOwy()
local script = Instance.new("Script",Messagebutton_1)
local button = script.Parent
local Workspace = game:GetService("Workspace")

local messages = {"BLUUDUD HACKINGGG", "BLUUDUDTEAMMMMM!", "BLUUDUDSHERE", "BLUUDUDCOOL"}

local function showMessage()
	local index = 1

	while true do
		local message = Instance.new("Message")
		message.Parent = Workspace
		message.Text = messages[index]

		index = (index % #messages) + 1
		wait(6)
		message:Destroy()
		wait(4)
	end
end

button.MouseButton1Click:Connect(showMessage)
end
coroutine.wrap(CQxMkihCvsuHkOwy)()


local function QwxRmTMeieXVHGit()
local script = Instance.new("LocalScript",Script)

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
coroutine.wrap(QwxRmTMeieXVHGit)()


local function qTaEyzMYowodVfII()
local script = Instance.new("Script",Texturebutton_1)
local button = script.Parent

local function applyEffects()
	local function processPart(part)
			if part:IsA("BasePart") then
				
			part.TopSurface = Enum.SurfaceType.Smooth
			part.BottomSurface = Enum.SurfaceType.Smooth
			part.LeftSurface = Enum.SurfaceType.Smooth
			part.RightSurface = Enum.SurfaceType.Smooth
			part.FrontSurface = Enum.SurfaceType.Smooth
			part.BackSurface = Enum.SurfaceType.Smooth

			
			part.Color = Color3.new(0, 0, 0)

			
			local fire = Instance.new("Fire")
			fire.Size = 30
			fire.Heat = 25
			fire.Parent = part

			
			local function addTexture(face)
				local texture = Instance.new("Decal")
				texture.Texture = "rbxassetid://117040568125131"
				texture.Face = face
				texture.Parent = part
			end

			
			addTexture(Enum.NormalId.Front)
			addTexture(Enum.NormalId.Back)
			addTexture(Enum.NormalId.Top)
			addTexture(Enum.NormalId.Bottom)
			addTexture(Enum.NormalId.Left)
			addTexture(Enum.NormalId.Right)
		end
	end

	local function processModel(model)
		for _, obj in ipairs(model:GetDescendants()) do
			processPart(obj)
		end
	end


	for _, obj in ipairs(workspace:GetDescendants()) do
		if obj:IsA("Model") then
			processModel(obj)
		else
			processPart(obj)
		end
	end


	for _, player in ipairs(game.Players:GetPlayers()) do
		if player.Character then
			processModel(player.Character)
		end
	end
end

button.MouseButton1Click:Connect(applyEffects)

end
coroutine.wrap(qTaEyzMYowodVfII)()


local function xvFgmXPaRsQHjEZU()
local script = Instance.new("Script",Lagbutton_1)

local button = script.Parent


button.MouseButton1Click:Connect(function()
	
	local function createPart()
	
		local part = Instance.new("Part")
		part.Size = Vector3.new(4, 1, 4)
		part.Anchored = true
		part.CanCollide = false 
		part.Transparency = 1 
		part.Parent = game.Workspace

		
		part.Position = Vector3.new(
			math.random(-50, 50),
			math.random(5, 50),
			math.random(-50, 50)
		)

		
		while true do
			wait(0.001)
			local clonedPart = part:Clone()
			clonedPart.Parent = game.Workspace
		end
	end


	createPart()
end)

end
coroutine.wrap(xvFgmXPaRsQHjEZU)()
