local keys = {
     "UPPER-3ed-56gf",
     "UPPER-7fds4-ed456",
     "UPPER-2efrtt-g6te",
     "UPPER-9dfe0-eda5",
     "ใส่คีย์เพิ่มได้", -- ใส่คีย์เพิ่มได้
}

local counter = 1
local keyCheck
for i,v in pairs(keys) do
    if counter == #keys then
        keys = ""
        game.Players.LocalPlayer:Kick("please enter your key")
    else
        if v == getgenv().Key then 
            -- check succes
            print("Succesfully, enjoy :]")
            -- your script
            
shared.LoaderTitle = 'UpperCut Hub' -- ใส่ชื่อ
shared.LoaderKeyFrames = {
   [1] = {1, 30}, -- [Time (s), Percentage] 
   [2] = {3, 100} -- [เวลา, เปอร์เซ็น]
}
local Metadata = {
    LoaderData = {
        Name = (shared.LoaderTitle or 'Loader'),
        Colors = shared.LoaderColors or {
            Main = Color3.fromRGB(24, 24, 24),
            Topic = Color3.fromRGB(255, 255, 255),
            Title = Color3.fromRGB(0, 255, 255),
            LoaderBackground = Color3.fromRGB(30, 30, 30),
            LoaderSplash = Color3.fromRGB(0, 255, 255)
        }
    },
    Keyframes = shared.LoaderKeyFrames or {
        [1] = {1, 10}, -- [Time (s), Percentage]
        [2] = {2, 30},
        [3] = {3, 60},
        [4] = {2, 100}
    }
}
