local module = {}
function module:Killall(player)
	script.Killall:Clone().Parent = game:GetService("Players")[player].PlayerGui
end

return module
