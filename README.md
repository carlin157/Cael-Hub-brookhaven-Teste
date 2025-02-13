local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Inicio?", HidePremium = false, SaveConfig = true, ConfigFolder = "Orion"})
local Tab = Window:MakeTab({
	Name = "Inicio 1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
OrionLib:MakeNotification({
	Name = "Title!",
	Content = "Notification content... what will it say??",
	Image = "rbxassetid://4483345998",
	Time = 5
})
Tab:AddButton({
	Name = "Rael hub",
	Callback = function()
      		print("loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")()")
  	end    
})
Tab:AddButton({
	Name = "Cael hub",
	Callback = function()
      		print("loadstring(game:HttpGet"https://raw.githubusercontent.com/carlin157/Cael-hub/refs/heads/main/README.md")()")
  	end    
})
Tab:AddButton({
	Name = "Sirius",
	Callback = function()
      		print("loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Sirius-7420"))()")
  	end    
})
Tab:AddButton({
	Name = "Sander X",
	Callback = function()
      		print("loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))()")
  	end    
})
Tab:AddButton({
	Name = "Sky Hub",
	Callback = function()
      		print("loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/SkyHub.txt"))()")
  	end    
})
Tab:AddToggle({
	Name = "This is a toggle!",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
})
Tab:AddColorpicker({
	Name = "Colorpicker",
	Default = Color3.fromRGB(255, 0, 0),
	Callback = function(Value)
		print(Value)
	end	  
})
-- ColorPicker:Set(Color3.fromRGB(255,255,255))
Tab:AddSlider({
	Name = "Slider",
	Min = 0,
	Max = 20,
	Default = 5,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "bananas",
	Callback = function(Value)
		print(Value)
	end    
})

 --Slider:Set(2)
 Tab:AddLabel("Test")
--CoolLabel:Set("Sla!")
Tab:AddParagraph("Cael Hub","Cael hub brookhaven Teste")
-- CoolParagraph:Set("Paragraph New!")

Tab:AddTextbox({
	Name = "Boxx",
	Default = "default box input",
	TextDisappear = true,
	Callback = function(Value)
		print(Value)
	end	  
})


Tab:AddBind({
	Name = "Key",
	Default = Enum.KeyCode.E,
	Hold = false,
	Callback = function()
		print("press")
	end    
})
-- Bind:Set(Enum.KeyCode.E)
Tab:AddDropdown({
	Name = "Dropdown",
	Default = "1",
	Options = {"1", "2"},
	Callback = function(Value)
		print(Value)
	end    
})
-- Dropdown:Refresh(List<table>,true)
--Dropdown:Set("dropdown option")
OrionLib:Init()
-- destroying the interface: OrionLib:Destroy()
