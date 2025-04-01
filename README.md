local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/Library-ui/refs/heads/main/Redzhubui"))()
local Window = redzlib:MakeWindow({
  Title = "Star Hub",
  SubTitle = "by Star",
  SaveFolder = "testando | redz lib v5.lua"
})
Tab1:AddDiscordInvite({
    Name = "Star Hub",
    Description = "Entre no nosso Servidor!",
    Logo = "rbxassetid://128382232008547",
    Invite = "https://discord.gg/kBDk5YMR2R",
})
Window:AddMinimizeButton({
    Button = { Image = "rbxassetid://128382232008547", BackgroundTransparency = 0 },
    Corner = { CornerRadius = UDim.new(35, 1) },
})
local Tab1 = Window:MakeTab({"Star", "Hub"})
  redzlib:SetTheme("Dark")
  Window:SelectTab(Tab1)
  Tab1:AddButton({"Chaos Hub", function(Value)
loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))()
end})
