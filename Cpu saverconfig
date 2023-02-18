--@empireundefined

local sv = Instance.new("ScreenGui")
local BG = Instance.new("Frame")
local Some = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local SomeShadow = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")

--@preloadIMAGE
ImageLabel.Image = "http://www.roblox.com/asset/?id=2248101918"

sv.Name = "sv"
sv.Parent = game.CoreGui
sv.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

BG.Name = "BG"
BG.Parent = sv
BG.BackgroundColor3 = Color3.fromRGB(7, 47, 95)
BG.Position = UDim2.new(0, 0, -0.0502008051, 0)
BG.Size = UDim2.new(1, 0, 1.10040164, 0)
BG.Visible = _G.SmoothForEyes

Some.Name = "Some"
Some.Parent = BG
Some.BackgroundColor3 = Color3.fromRGB(18, 97, 160)
Some.Position = UDim2.new(0.030505348, 0, 0.10531909, 0)
Some.Size = UDim2.new(0, 240, 0, 424)

UICorner.Parent = Some

TextLabel.Parent = Some
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.0833333358, 0, 0.0424528308, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = "Saving GPU/CPU"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 22.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Some
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0833333358, 0, 0.120283008, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 59)
TextLabel_2.Font = Enum.Font.Gotham
TextLabel_2.Text = "Scientists state that conserving GPU resources is crucial for optimizing performance and maximizing efficiency in computing systems."
TextLabel_2.TextColor3 = Color3.fromRGB(209, 209, 209)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

ImageLabel.Parent = Some
ImageLabel.BackgroundColor3 = Color3.fromRGB(164, 163, 166)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0, 31, 0, 129)
ImageLabel.Size = UDim2.new(0, 178, 0, 178)
ImageLabel.Image = "http://www.roblox.com/asset/?id=2248101918"
ImageLabel.ScaleType = Enum.ScaleType.Crop

TextLabel_3.Parent = Some
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.0833333433, 0, 0.778301835, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 24)
TextLabel_3.Font = Enum.Font.Unknown
TextLabel_3.Text = "beep boop"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 10.000
TextLabel_3.TextWrapped = true

SomeShadow.Name = "SomeShadow"
SomeShadow.Parent = BG
SomeShadow.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SomeShadow.BackgroundTransparency = 0.250
SomeShadow.Position = UDim2.new(0.0426830649, 0, 0.117689334, 0)
SomeShadow.Size = UDim2.new(0, 240, 0, 424)
SomeShadow.ZIndex = -1

UICorner_2.Parent = SomeShadow


local RunService = game:GetService("RunService")
local UserInputService = game:GetService("UserInputService")

function savegpu(fps, vis)
setfpscap(fps)
BG.Visible = vis
RunService:Set3dRenderingEnabled(false)
end

function unsavegpu(vis)
    setfpscap(60)
BG.Visible = vis
RunService:Set3dRenderingEnabled(true)
end


local WindowFocusReleasedFunction = function()
    if _G.LowFPS and _G.SmoothForEyes then
	savegpu(10, true)
	elseif _G.LowFPS and not _G.SmoothForEyes then
	    savegpu(10, false)
	elseif not _G.LowFPS and _G.SmoothForEyes then
	    savegpu(60, true)
	elseif not _G.LowFPS and not _G.SmoothForEyes then
	    savegpu(60, false)
	end
	return
end

local WindowFocusedFunction = function()
	unsavegpu()
	return
end

local Initialize = function()
	UserInputService.WindowFocusReleased:Connect(WindowFocusReleasedFunction)
	UserInputService.WindowFocused:Connect(WindowFocusedFunction)
	return
end

Initialize()


while wait() do
    if _G.SmoothForEyes then
        ImageLabel.Rotation = ImageLabel.Rotation + 5
    end
end

--@dontremove
for i,v in pairs(game:GetService("CoreGui"):GetChildren()) do
    if v.Name == "sv" then
        v:Destroy()
    end
end
