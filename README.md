local ui = game:GetService("CoreGui"):FindFirstChild("FluxLib")
if ui then
    ui:Destroy()
end
local Flux = loadstring(game:HttpGet"https://raw.githubusercontent.com/DookDekDEE/gui/main/fairyhub.txt")()

local win = Flux:Window("Blox Fruit (Bete)", "Kotaro HUB", Color3.fromRGB(199, 211, 70) ,Enum.KeyCode.RightAlt)
local tab = win:Tab("Teleport", "http://www.roblox.com/asset/?id=6034989568")
tab:Toggle("auto fream","",false,function(t)
end)

local tab = win:Tab("Teleport", "http://www.roblox.com/asset/?id=6034989568")

tab: Button("Windmill","",function()
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1108.86755, 16.273613, 1434.51074)
    end)
    tab: Button("Marine Start","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2573.3374, 6.88881731, 2046.99817)
    end) 
    tab: Button("Middle Town","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582.941345, 7.85286522, 1713.93726)
    end) 
    tab: Button("Desert","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1094.14587, 6.43846321, 4192.88721)
    end) 
    tab: Button("Underwater City","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(61348.6992, 19.4723473, 1475.9884)
    end)
    tab: Button("Pirate Village","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1120.14856, 4.75204945, 3855.31763)
    end)
    tab: Button("Jungle","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1255.14795, 11.8520441, 349.906677)
    end)
    tab: Button("Skylands 1","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4967.83691, 717.67218, -2623.84326)
    end)
    tab: Button("Skylands 2","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7946.89844, 5545.49316, -318.856445)
    end)
    tab: Button("Magma Village","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5193.37549, 8.5906744, 8569.57129)
    end)
    tab: Button("Frozen Village","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1185.63379, 7.30343723, -1143.36987)
    end)
    tab: Button("Colosseum","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1332.94006, 7.28907108, -2896.56055)
    end)
    tab: Button("Fountain City","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5158.63184, 4.50128746, 4028.94678)
    end)
    tab: Button("Military Frotress","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4828.9751, 20.652029, 4374.35791)
    end)
    tab: Button("Prison","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5136.59277, 3.53421378, 785.520813)
    end)
    tab: Button("Mob Island","",function ()

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2850.20068, 7.39224529, 5354.99268)
    end)
