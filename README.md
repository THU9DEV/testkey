local keys = {
     "UPPER-e3Dfg-fgt6",
     "UPPER-kwkkf-34f",
     "UpperCut-JUOP-UNM0",
     "UpperCut-HJOP-MKOP0",
     "UpperCut-MOKP-89MK",
     "UpperCut-LOVE-KUY",
     "UpperCut-YUYOIP-UJUM9",
     "UpperCut-HUYHGU-7676",
     "UpperCut-UJUKM-898M",
     "UpperCut-87879-NESKJ",
     "SEED-NHUIL-7890M",
     "UpperCut-NJKOL-78U8U",
     "UpperCut-787-MJMKO",
     "UpperCut-JKOPY-9MLO",
     "UpperCut-MKLL-POI0",
     "UpperCut-HIOPT-MKO9",
     "Admin-888-999",
     "OOOOOOOOOOOO",
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
