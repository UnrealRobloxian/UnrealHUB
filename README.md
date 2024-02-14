local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Unreal HUB | Gen v1", HidePremium = false, IntroText = "Unreal HUB", Icon = "rbxassetid://6228805211" SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Farm",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Auto Farm"
})

Tab:AddToggle({
	Name = "Auto Farm Level",
	Default = false,
	Callback = function(Value)
		print(Value)
	end
})
