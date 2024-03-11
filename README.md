getgenv().SpamSkill = true
getgenv().AutoUseRaceV3 = true
getgenv().AutoUseRacev4 = true
getgenv().SpamSkillOnRaceV4 = true
getgenv().Invisible = true
getgenv().InCombatNoReset = false
getgenv().Team = "Pirates" -- Marines
getgenv().TweenSpeed = 340 -- 350 max or Get Tp Back
 getgenv().Setting = { -- Select Weapon, Self Explain
        ["Melee"] = {["Enable"] = true,["Delay"] = 4,
          ["Skills"] = {
            ["Z"] = {["Enable"] = true,["HoldTime"] = 0.2,["TimeToNextSkill"] = 0.9,},
            [ "X"] = {["Enable"] = true,["HoldTime"] = 0.2, ["TimeToNextSkill"] = 0.2,},
            ["C"] = {["Enable"] = true,["HoldTime"] = 0.3, ["TimeToNextSkill"] = 0.7,},
            },
        },
        ["Blox Fruit"] = {["Enable"] = true, ["Delay"] = 6,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.2, ["TimeToNextSkill"] = 0.4,},
                ["X"] = { ["Enable"] = true, ["HoldTime"] = 0.2, ["TimeToNextSkill"] = 0.3,},
                ["C"] = { ["Enable"] = true, ["HoldTime"] = 0.2,["TimeToNextSkill"] = 0.2, },
                ["V"] = { ["Enable"] = false, ["HoldTime"] = 0,["TimeToNextSkill"] = 0,},
                ["F"] = {["Enable"] = true, ["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
            },
        },
        ["Sword"] = { ["Enable"] = false, ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true,  ["HoldTime"] = 0.65,["TimeToNextSkill"] = 0.2,},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.2, ["TimeToNextSkill"] = 0.2,},
            },
        },
        ["Gun"] = {["Enable"] = false, ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.5,["TimeToNextSkill"] = 0,},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.5,["TimeToNextSkill"] = 0,
                },
            },
        }
    }
 loadstring(game:HttpGet('https://raw.githubusercontent.com/vinhuchi/temp-repos/main/FreeAutoBounty.lua'))()
