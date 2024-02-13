local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Unreal HUB: Blox Fruits | Gen v1", "Synapse")

local Misc = Window:NewTab("Misc")
local MiscSection = Misc:NewSection("Misc 🕳️")

MiscSection:NewToggle("Speed", "ToggleInfo", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
end)
