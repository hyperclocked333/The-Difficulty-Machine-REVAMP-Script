script for https://www.roblox.com/games/11915606459/The-Difficulty-Machine-REVAMP (reqs brain)

features:
alt account optimization (mostly for luck boost) and auto clicker (standalone in the "standalone" file)


Script:
```
--[[SYNAPSE X ONLY, MEANT TO BE USED WITH ROBLOX ALT ACCOUNT MANAGER]]--

--[[PUT THIS SCRIPT IN YOUR AUTOEXEC]]--

--[[say "!rein" or "!sac" on your main youre playing on to telport all the accounts to the respective locations]]--

getgenv().settings = {
    MainAccount = "coolDude23_1", --the main acc, case sensitve
    Rendering = false, --rendering or no (recommended off)
    AltFps = 5, --fps you want the alt at
    DestroyMap = true, -- destroys the map on the alts client (also recommended)
    
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/hyperclocked333/The-Difficulty-Machine-REVAMP-Script/main/script"))()
