
**Loadstring**
```
loadstring(game:HttpGet("https://raw.githubusercontent.com/PowerStormReal/LobsterUi/refs/heads/main/Source.lua"))()
```

Lobester is a free and open sourced Roblox UI library.

# Features:
- Customizable (Themes)
- Browser-Like navigation
- Buttons
- Sliders
- Dropdowns
- Inputs
- Color Picker
- Notifications
- Prompts
... more to be added.

Created by CyberAnonymous

Documentation

# Get the Library
```
local Lobster = loadstring(game:HttpGet("https://raw.githubusercontent.com/PowerStormReal/LobsterUi/refs/heads/main/Source.lua"))()
```
# Create the GUI
```
local GUI = Mercury:Create{
    Name = "Lobster",
    Size = UDim2.fromOffset(600, 400),
    Theme = Mercury.Themes.Dark,
    Link = "https://github.com/deeeity/mercury-lib"
}
```

# Tabs
```
local Tab = GUI:Tab{
	Name = "New Tab",
	Icon = "rbxassetid://8569322835"
}
```

**Buttons**
```
Tab:Button{
	Name = "Button",
	Description = nil,
	Callback = function() end
}
```
