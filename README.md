local DiscordLib = loadstring(game:HttpGet"https://pastebin.com/raw/XMBepAJH")()

local win = DiscordLib:Window("DesolateHub")

local serv = win:Server("AFS", "")
local SAOD = serv:Channel("Main")
local Misc = serv:Channel("Server")

SAOD:Toggle("Anit AFK",true, function(vu)
	print("Anit AFK Start")
	local vu = game:GetService("VirtualUser")
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	end)
end)
SAOD:Seperator()
SAOD:Label("=== Open Star ===")
SAOD:Toggle("Max Open",false,function(bool)
ood = bool
end)
spawn(function()
	while wait() do
		if ood then
		

local args = {
    [1] = "OPWanoEgg"
}

game:GetService("ReplicatedStorage").Remote.AttemptMultiOpen:FireServer(unpack(args))
end
end
end)
SAOD:Toggle("Normal Open",false,function(bool)
    jood = bool
    end)
    spawn(function()
        while wait() do
            if jood then
                local args = {
                    [1] = workspace.Worlds.OPWano.OPWanoEgg,
                    [2] = 8
                }
                
                game:GetService("ReplicatedStorage").Remote.OpenEgg:InvokeServer(unpack(args))
            end
        end                
    end)
    SAOD:Seperator()
    SAOD:Label("=== Auto Item ===")
SAOD:Toggle("Auto Shiny Boost (Use Every 10 Mins)",false,function(bool)
    jeed = bool
    end)
    spawn(function()

        while wait() do
            if jeed then
local args = {
    [1] = "ShinyBoost"
}

game:GetService("ReplicatedStorage").Remote.UseItem:FireServer(unpack(args))
 wait(600)
            end
        end                
    end)
    SAOD:Toggle("Auto Luck Boost (Use Every 10 Mins)",false,function(bool)
    eed = bool
    end)
    spawn(function()
        while wait() do
            if eed then
local args = {
    [1] = "LuckBoost"
}

game:GetService("ReplicatedStorage").Remote.UseItem:FireServer(unpack(args))
wait(600)
            end
        end                
    end)
    SAOD:Toggle("Auto Super Luck Boost (Use Every 30 Mins)",false,function(bool)
    eoeo = bool
    end)
    spawn(function()
        while wait() do
            if eoeo then
local args = {
    [1] = "SuperLuckBoost"
}

game:GetService("ReplicatedStorage").Remote.UseItem:FireServer(unpack(args))
wait(1800)
            end
        end                
    end)
    Misc:Button("FPS Boost",function()
        local decalsyeeted = true 
        local g = game- Le
        local w = g.Workspace
        local l = g.Lighting
        local t = w.Terrain
        t.WaterWaveSize = 0
        t.WaterWaveSpeed = 0
        t.WaterReflectance = 0
        t.WaterTransparency = 0
        l.GlobalShadows = false
        l.FogEnd = 9e9
        l.Brightness = 0
        settings().Rendering.QualityLevel = "Level01"
        for i, v in pairs(g:GetDescendants()) do
        if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
        v.Material = "Plastic"
        v.Reflectance = 0
        elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
        v.Transparency = 1
        elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
        v.Lifetime = NumberRange.new(0)
        elseif v:IsA("Explosion") then
        v.BlastPressure = 1
        v.BlastRadius = 1
        elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
        v.Enabled = false
        elseif v:IsA("MeshPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
        v.TextureID = 10385902758728957
        end
        end
        for i, e in pairs(l:GetChildren()) do
        if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
        e.Enabled = false
        end
        end
        end)
        Misc:Button("Super FPS Boost",function()
        for i,v in pairs(game.Workspace.Map:GetDescendants()) do
        if v.Name == "Tavern" or v.Name == "SmileFactory" or v.Name == "Tree" or v.Name == "Rocks" or v.Name == "PartHouse" or v.Name == "Hotel" or v.Name == "WallPiece" or v.Name == "MiddlePillars" or v.Name == "Cloud" or v.Name == "PluginGrass" or v.Name == "BigHouse" or v.Name == "SmallHouse" or v.Name == "Detail" then
        v:Destroy()
        end
        end 
        for i,v in pairs(game.ReplicatedStorage.Unloaded:GetDescendants()) do
        if v.Name == "Tavern" or v.Name == "SmileFactory" or v.Name == "Tree" or v.Name == "Rocks" or v.Name == "PartHouse" or v.Name == "Hotel" or v.Name == "WallPiece" or v.Name == "MiddlePillars" or v.Name == "Cloud" or v.Name == "PluginGrass" or v.Name == "BigHouse" or v.Name == "SmallHouse" or v.Name == "Detail" then
        v:Destroy()
        end
        end
        for i,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
        if v:IsA("Accessory") or v.Name == "Pants" or v.Name == "Shirt" then
        v:Destroy()
        end
        end
        local decalsyeeted = true 
        local g = game
        local w = g.Workspace
        local l = g.Lighting
        local t = w.Terrain
        t.WaterWaveSize = 0
        t.WaterWaveSpeed = 0
        t.WaterReflectance = 0
        t.WaterTransparency = 0
        l.GlobalShadows = false
        l.FogEnd = 9e9
        l.Brightness = 0
        settings().Rendering.QualityLevel = "Level01"
        for i, v in pairs(g:GetDescendants()) do
        if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
        elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
        v.Transparency = 1
        elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
        v.Lifetime = NumberRange.new(0)
        elseif v:IsA("Explosion") then
        v.BlastPressure = 1
        v.BlastRadius = 1
        elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
        v.Enabled = false
        elseif v:IsA("MeshPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
        v.TextureID = 10385902758728957
        end
        end
        for i, e in pairs(l:GetChildren()) do
        if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
        e.Enabled = false
        end
        end
        end)
      Misc:Button("Full Brightness",function()
         local Light = game:GetService("Lighting")
         
         function dofullbright()
         Light.Ambient = Color3.new(1, 1, 1)
         Light.ColorShift_Bottom = Color3.new(1, 1, 1)
         Light.ColorShift_Top = Color3.new(1, 1, 1)
         end
         
         dofullbright()
         
         Light.LightingChanged:Connect(dofullbright)
         end)
         Misc:Button("Rejoin",function()
            local ts = game:GetService("TeleportService") local p = game.Players.LocalPlayer ts:Teleport(game.PlaceId, p) 
         end)
         Misc:Button("Server Hop",function()
            local PlaceID = game.PlaceId
            local AllIDs = {}
            local foundAnything = ""
            local actualHour = os.date("!*t").hour
            local Deleted = false
            function TPReturner()
                local Site;
                if foundAnything == "" then
                    Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
                else
                    Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
                end
                local ID = ""
                if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then
                    foundAnything = Site.nextPageCursor
                end
                local num = 0;
                for i,v in pairs(Site.data) do
                    local Possible = true
                    ID = tostring(v.id)
                    if tonumber(v.maxPlayers) > tonumber(v.playing) then
                        for _,Existing in pairs(AllIDs) do
                            if num ~= 0 then
                                if ID == tostring(Existing) then
                                    Possible = false
                                end
                            else
                                if tonumber(actualHour) ~= tonumber(Existing) then
                                    local delFile = pcall(function()
                                        -- delfile("NotSameServers.json")
                                        AllIDs = {}
                                        table.insert(AllIDs, actualHour)
                                    end)
                                end
                            end
                            num = num + 1
                        end
                        if Possible == true then
                            table.insert(AllIDs, ID)
                            wait()
                            pcall(function()
                                -- writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
                                wait()
                                game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)
                            end)
                            wait(.1)
                        end
                    end
                end
            end
            function Teleport() 
                while wait() do
                    pcall(function()
                        TPReturner()
                        if foundAnything ~= "" then
                            TPReturner()
                        end
                    end)
                end
            end
            Teleport()
    
         end)
 Misc:Toggle("Ctrl + Click = TP",false,function(vu)
     CTRL = vu
 end)
 local Plr = game:GetService("Players").LocalPlayer
 local Mouse = Plr:GetMouse()
 Mouse.Button1Down:connect(
     function()
         if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
             return
         end
         if not Mouse.Target then
             return
         end
         if CTRL then
             Plr.Character:MoveTo(Mouse.Hit.p)
         end
     end
 )
	  
   Misc:Toggle("White Screen",_G.WhiteScreen,function(value)
      _G.WhiteScreen = value
    if _G.WhiteScreen == true then
      game:GetService("RunService"):Set3dRenderingEnabled(false)
    elseif _G.WhiteScreen == false then
      game:GetService("RunService"):Set3dRenderingEnabled(true)
    end
    end)
