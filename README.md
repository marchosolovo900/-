if not game:IsLoaded() then
	local loadedcheck = Instance.new("Message",workspace)
	loadedcheck.Text = 'Loading...'
	game.Loaded:Wait()
	loadedcheck:Destroy()
end

while wait() do
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if v.Name == "Justice Combination" then
local action = game.Players.LocalPlayer.Character:WaitForChild("Action")
    if action then wait() action:Destroy() end end
    if v.Name == "Action" then
v:Destroy()
end
    if v.Name == "Attacking" then
v:Destroy()
end
    if v.Name == "Using" then
v:Destroy()
end
    if v.Name == "hyper" then
    v:Destroy()
    end
    if v.Name == "Hyper" then
    v:Destroy()
    end
    if v.Name == "heavy" then
    v:Destroy()
    end
    if v.Name == "KiBlasted" then
        v:Destroy()
        end
        if v.Name == "Tele" then
        v:Destroy()
        end
        if v.Name == "tele" then
        v:Destroy()
        end
        if v.Name == "Killed" then
            v:Destroy()
            end
            if v.Name == "Slow" then
            v:Destroy()
            end
if v.Name == "Block" and v.Value == true then
v.Value = false
end
end
end
