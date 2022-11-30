if game.PlaceId == 9992339729 then
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("Longest Answer Wins GUI By Scarlet Witch", "DarkTheme")
    local Main = Window:NewTab("Main")
    local MainSection = Main:NewSection("Main")
    MainSection:NewButton("Auto Answer (Press to Auto)", "Press it when the game starts", function()
        local mmt = 50 -- how many blocks do you want?
-- don't do over 1000 because it takes forever to stop
game:GetService("ReplicatedStorage").SubmittedAnswer:FireServer(game:GetService("ReplicatedStorage").HintAnswer.Value,mmt)
        print("Clicked")
    end)
    local Others = Window:NewTab("Others")
    local OthersSection = Others:NewSection("Others")
    OthersSection:NewButton("Infinite yield", "Free Admin", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
        print("Clicked")
    end)
    local Credits = Window:NewTab("Credits")
    local CreditsSection = Credits:NewSection("Credits")
    local CreditsSection = Credits:NewSection("Discord: Scarlet Witch #9326")
end
