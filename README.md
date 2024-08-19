local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "DRE4M HUB", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Tab = Window:MakeTab({
    Name = "BLOX FRUIT",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]
Tab:AddButton({
    Name = "AUTO FARM 1",
    Callback = function()    loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-FREE-AUTOFARM-GUI-17261"))()
      end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "AUTO FARM 2",
    Callback = function() 
loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-Stingray-Keyless-Autofarm-17241"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "AUTO FARM 3",
    Callback = function() 
loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-BEST-FREE-AUTOFARM-16383"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "AUTO FARM 4",
    Callback = function() 
loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-Stingray-Keyless-Autofarm-11278"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "AUTO FARM 5",
    Callback = function() 
loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-Stingray-Keyless-Autofarm-17241"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "HOHO HUB",
    Callback = function() 
loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "OMG HUB",
    Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/ORG-hubb/ORG/main/ORG-Hub.lua"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "HIRU HUB",
    Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/NGUYENVUDUY1/V3PRO/main/main.lua"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "REDZ HUB",
    Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "YTB HUB",
    Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/KhanhTranVan/Guest/main/thankforbuying"))()
     end    
})
--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
