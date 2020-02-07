local Finity = loadstring(game:HttpGet("https://pastebin.com/raw/CXm13r24"))()
local FinityWindow = Finity.new(true)
FinityWindow.ChangeToggleKey(Enum.KeyCode.T)

local DeleteCoreGoldTable = {
  ["GoldShop"] = true
}
for _, v in next, game.CoreGui:GetChildren() do
	if DeleteCoreGoldTable[v.Name] then
    game:GetService("StarterGui").GoldShop:Destroy()
	end
end

local DelPlayerGoldTable = {
	["GoldShop"] = true
}
for _, v in next, game.Players.LocalPlayer.PlayerGui:GetChildren() do
	if DelPlayerGoldTable[v.Name] then
	game.Players.LocalPlayer.PlayerGui.GoldShop:Destroy()
	end
end

local DelRepBoostTable = {
	["UpdateBoost"] = true
}
for _, v in next, game.ReplicatedStorage:GetChildren() do
	if DelRepBoostTable[v.Name] then
	game.ReplicatedStorage.UpdateBoost:Destroy()
	end
end

-- Main Tab

local MainCategory = FinityWindow:Category("Main Cheats")

	local Main = MainCategory:Sector("Main")
		
		_G.AutoSell = false
		Main:Cheat(
		"Checkbox",
		"Auto Sell",
		function(State)
		_G.AutoSell = not _G.AutoSell
		while wait() do
		if _G.AutoSell then
			wait(7)
			local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-344.243011, 5.09499931, -40.8390007, 1, 0, 0, 0, 1, 0, 0, 0, 1)
			wait(0.7)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
			end
			end
		end)
		
		_G.Swing = false
		Main:Cheat(
		"Checkbox",
		"Auto Swing",
		function(State)
		_G.Swing = not _G.Swing
		while wait() do
		if _G.Swing then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
			end
			end
		end)
		
		Main:Cheat("Button", "So Much Coins!", function()
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Fearsome Fortress" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Mysterious Orient" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Desert Stronghold" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Deadly Deadlands" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Enemy Jarldom" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Mysterious Orient" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Peaceful Keep" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait()
			for i,v in pairs(game:GetService("Workspace").Coins:GetDescendants()) do
				if v.Name == "Atlantis Ruins" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait()
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
			end
		end)


	local Others = MainCategory:Sector("Others")
	
		_G.ANTIAFK = false
		Others:Cheat(
		"Checkbox",
		"Anti AFK",
		function(State)
			_G.ANTIAFK = not _G.ANTIAFK
			while wait() do
			if _G.ANTIAFK then
				local vu = game:GetService("VirtualUser")
				game:GetService("Players").LocalPlayer.Idled:connect(function()
				vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
				wait(2)
				vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
				end)
				end
			end
		end)
		
	-- Crates Tab
	
local CrateCategory = FinityWindow:Category("Crate Farms")

	local Crate1 = CrateCategory:Sector("Map 1 Crates Cheats")
	
		_G.TPCrates1 = false
		Crate1:Cheat(
		"Checkbox",
		"TP Crates To You",
		function(State)
		_G.TPCrates = not _G.TPCrates
		while wait() do
		if _G.TPCrates then
			for i,v in pairs(game:GetService("Workspace").Objects.Crate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
				
		_G.CrateFarm1 = false
		Crate1:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm = not _G.CrateFarm
		while wait() do
		if _G.CrateFarm then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.Crate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)
		
		local Crate2 = CrateCategory:Sector("Map 2 Crate Cheats")
		
			_G.TPCrates2 = false
			Crate2:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates2 = not _G.TPCrates2
			while wait() do
			if _G.TPCrates2 then
			for i,v in pairs(game:GetService("Workspace").Objects.IronCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
		
		_G.CrateFarm2 = false
		Crate2:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm2 = not _G.CrateFarm2
		while wait() do
		if _G.CrateFarm2 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.IronCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)
		
		local Crate3 = CrateCategory:Sector("Map 3 Crate Cheats")
		
			_G.TPCrates3 = false
			Crate3:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates3 = not _G.TPCrates3
			while wait() do
			if _G.TPCrates3 then
			for i,v in pairs(game:GetService("Workspace").Objects.GoldCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
		
		_G.CrateFarm3 = false
		Crate3:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm3 = not _G.CrateFarm3
		while wait() do
		if _G.CrateFarm3 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.GoldCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)
		
		local Crate4 = CrateCategory:Sector("Map 4 Crate Cheats")
		
			_G.TPCrates4 = false
			Crate4:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates4 = not _G.TPCrates4
			while wait() do
			if _G.TPCrates4 then
			for i,v in pairs(game:GetService("Workspace").Objects.DesertCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
				wait(5)
			end
			end
			end
			end
		end)
		
		_G.Crate4 = false
		Crate4:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.Crate4 = not _G.Crate4
		while wait() do
		if _G.Crate4 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.OrientCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)

		local Crate5 = CrateCategory:Sector("Map 5 Crate Cheats")
		
			_G.TPCrates5 = false
			Crate5:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates5 = not _G.TPCrates5
			while wait() do
			if _G.TPCrates5 then
			for i,v in pairs(game:GetService("Workspace").Objects.OrientCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
		
		_G.CrateFarm5 = false
		Crate5:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm5 = not _G.CrateFarm5
		while wait() do
		if _G.CrateFarm5 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.OrientCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)		
		
		local Crate6 = CrateCategory:Sector("Map 6 Crate Cheats")
		
			_G.TPCrates6 = false
			Crate6:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates6 = not _G.TPCrates6
			while wait() do
			if _G.TPCrates6 then
			for i,v in pairs(game:GetService("Workspace").Objects.HellCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
		
		_G.CrateFarm6 = false
		Crate6:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm6 = not _G.CrateFarm6
		while wait() do
		if _G.CrateFarm6 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.HellCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)

		local Crate7 = CrateCategory:Sector("Map 7 Crate Cheats")
		
			_G.TPCrates7 = false
			Crate7:Cheat(
			"Checkbox",
			"TP Crates To You",
			function(State)
			_G.TPCrates7 = not _G.TPCrates7
			while wait() do
			if _G.TPCrates7 then
			for i,v in pairs(game:GetService("Workspace").Objects.HellCrate:GetDescendants()) do
				if v.Name == "Part" then 
				v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
			wait(5)
			end
			end
			end
			end
		end)
		
		_G.CrateFarm7 = false
		Crate7:Cheat(
		"Checkbox",
		"Auto Farm Crates",
		function(state)
		_G.CrateFarm7 = not _G.CrateFarm7
		while wait() do
		if _G.CrateFarm7 then
			local Target = game:GetService("ReplicatedStorage").Swing;
			Target:FireServer();
				wait()
			for i, v in pairs(game.Workspace.Objects.HellCrate:GetChildren()) do
			if v.Name == "Part" and v.ClassName == "Part" then 
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
			wait()
			end
			end
			end
			end
		end)
		
-- Shop Tab

local ShopCategory = FinityWindow:Category("Shop Cheats")

	local Swords = ShopCategory:Sector("Swords")
	
		Swords:Cheat("Button", "Buy The Best Sword: ", function()
		local string_1 = "Death Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		end)
	
		_G.Swords = false
		Swords:Cheat(
		"Checkbox",
		"Auto Buy Swords",
		function(state)
		_G.Swords = not _G.Swords
		while wait() do
		if _G.Swords then
			local string_1 = "Acid Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Fire Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Axe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Axe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Axe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Axe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Axe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Battlexe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Scimitar";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Scimitar";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Scimitar";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Scimitar";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Scimitar";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Barbed Blade";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Barbed Blade";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Barbed Blade";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Barbed Blade";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Barbed Blade";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Double Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Double Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Double Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Double Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Double Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Greatsword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Greatsword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Greatsword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Greatsword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Greatsword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Mega Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Mega Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Mega Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Mega Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Mega Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Dual Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Dual Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Dual Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Dual Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Dual Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Hammer";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Hammer";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Hammer";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Hammer";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Death Hammer";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Mace";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Acid Mace";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Lightning Mace";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Power Mace";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Acid Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Lightning Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Power Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Fire Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Death Jagged Sword";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Acid Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Lightning Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Power Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Fire Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Death Katana";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Acid Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Lightning Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Power Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Fire Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		local string_1 = "Death Dual Battleaxe";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		end
	end
end)
		
	local Shields = ShopCategory:Sector("Shields")
	
	Shields:Cheat("Button", "Buy The Best Shield: ", function()
		local string_1 = "Golden Ultimate Shield";
			local Target = game:GetService("ReplicatedStorage").Shop;
			Target:FireServer(string_1);
		end)
			
		_G.AutoBS = false
		Shields:Cheat(
		"Checkbox",
		"Auto Buy Shields",
		function(state)
		_G.AutoBS = not _G.AutoBS
		while wait() do
	if _G.AutoBS then
	local string_1 = "Bronze Round Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Round Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Round Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Round Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Round Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Warrior Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Buckler Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Kite Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Knights Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Legions Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Spiked Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Ornate Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Bronze Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Steel Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Iron Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Obsidian Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Winged Shield";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
		end
	end
end)

	local AutoBuy = ShopCategory:Sector("Bags")
	
		AutoBuy:Cheat("Button", "Buy The Best Bag: ", function()
		local string_1 = "Golden Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);	
		end)
		
		_G.AutoBB = false
		AutoBuy:Cheat(
		"Checkbox",
		"Auto Buy Bags",
		function(state)
		_G.AutoBB = not _G.AutoBB
		while wait() do
	if _G.AutoBB then
	local string_1 = "Leather Small Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Small Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Small Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Small Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Small Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
	local string_1 = "Leather Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Medium Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Leather Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Large Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Leather Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Giant Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Leather Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Massive Sack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Leather Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Leather Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Large Backpack";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wooden Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ivory Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Box";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wooden Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ivory Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Crate";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wooden Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ivory Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Small Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wooden Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ivory Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Decorated Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Ornate Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Golden Large Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wooden Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait(1)
	local string_1 = "Wool Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait()
	local string_1 = "Ivory Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait()
	local string_1 = "Decorated Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait()
	local string_1 = "Ornate Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait()
	local string_1 = "Golden Royal Chest";
		local Target = game:GetService("ReplicatedStorage").Shop;
		Target:FireServer(string_1);
		wait()
		end
	end
end)

-- Tiers Tab

	local Tier = ShopCategory:Sector("Tiers")

		Tier:Cheat("Button", "Buy The Best Tier: ", function()
			local string_1 = "Ravager";
				local Target = game:GetService("ReplicatedStorage").Shop;
				Target:FireServer(string_1);
				wait()
			local string_1 = "Marauder";
				local Target = game:GetService("ReplicatedStorage").Shop;
				Target:FireServer(string_1);
				wait()
			local string_1 = "Marauder";
				local Target = game:GetService("ReplicatedStorage").Shop;
				Target:FireServer(string_1);
				wait()
			local string_1 = "Ravager";
				local Target = game:GetService("ReplicatedStorage").Shop;
				Target:FireServer(string_1);
				wait()
		end)

-- Pets Tab

local PetCategory = FinityWindow:Category("Pets")

	local Shop = PetCategory:Sector("Auto Buy Pet Chests")

	_G.PetToggle1 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 1 Pet Crate",
		function(state)
		_G.PetToggle1 = not _G.PetToggle1
		if _G.PetToggle1 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Peaceful Keep"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end)
		
		_G.PetToggle2 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 2 Pet Crate",
		function(state)
		_G.PetToggle2 = not _G.PetToggle2
		while wait() do
		if _G.PetToggle2 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Fearsome Fortress"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end
		end)
		
		_G.PetToggle3 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 3 Pet Crate",
		function(state)
		_G.PetToggle3 = not _G.PetToggle3
		while wait() do
		if _G.PetToggle3 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Enemy Jarldom"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end
		end)
		
		_G.PetToggle4 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 4 Pet Crate",
		function(state)
		_G.PetToggle4 = not _G.PetToggle4
		while wait() do
		if _G.PetToggle4 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Deadly Deadlands"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end
		end)
		
		_G.PetToggle5 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 5 Pet Crate",
		function(state)
		_G.PetToggle5 = not _G.PetToggle5
		while wait() do
		if _G.PetToggle5 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Deadly Stronghold"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end
		end)
		
		_G.PetToggle6 = false
		Shop:Cheat(
		"Checkbox",
		"Auto Buy Lvl 6 Pet Crate",
		function(state)
		_G.PetToggle6 = not _G.PetToggle6
		while wait() do
		if _G.PetToggle6 then
			local string_1 = "Buy";
			local number_1 = 1;
			local userdata_1 = game:GetService("Workspace").PetBuyers["Mysterious Orient"];
			local Target = game:GetService("ReplicatedStorage").UpdatePets;
			Target:FireServer(string_1, number_1, userdata_1);
		wait(10)
		end
		end
		end)
	
-- NPC Tab

local NPCCategory = FinityWindow:Category("NPCs")

	local NPC = NPCCategory:Sector("Auto Farm NPCs Map 1")
	
		_G.TPCiv1 = false
		NPC:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv1 = not _G.TPCiv1
		while wait() do
		if _G.TPCiv1 then
		for _,v in pairs(game.Workspace.NPCs['Peaceful Keep']:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0
		wait(2)
				end
				end
			end
		end)
		
	local NPC2 = NPCCategory:Sector("Auto Farm NPCs Map 2")
		
		_G.TPCiv2 = false
		NPC2:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv2 = not _G.TPCiv2
		while wait() do
		if _G.TPCiv2 then
		for _,v in pairs(game.Workspace.NPCs['Fearsome Fortress']:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0
		wait(2)
				end
				end
			end
		end)
	
	local NPC3 = NPCCategory:Sector("Auto Farm NPCs Map 3")
	
		_G.TPCiv3 = false
		NPC3:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv3 = not _G.TPCiv3
		while wait() do
	if _G.TPCiv3 then
		for _,v in pairs(game:GetService("Workspace").NPCs["Enemy Jarldom"]:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0 
		wait(2)
				end
				end
			end
		end)

	local NPC4 = NPCCategory:Sector("Auto Farm NPCs Map 4")

		_G.TPCiv4 = false
		NPC4:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv4 = not _G.TPCiv4
		while wait() do
		if _G.TPCiv4 then
		for _,v in pairs(game:GetService("Workspace").NPCs["Desert Stronghold"]:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0
		wait(2)
				end
				end
			end
		end)
		
	local NPC5 = NPCCategory:Sector("Auto Farm NPCs Map 5")
		
		_G.TPCiv5 = false
		NPC5:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv5 = not _G.TPCiv5
		while wait() do
		if _G.TPCiv5 then
	for _,v in pairs(game:GetService("Workspace").NPCs["Mysterious Orient"]:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0
		wait(2)
				end
				end
			end
		end)
		
	local NPC6 = NPCCategory:Sector("Auto Farm NPCs Map 6")
		
		_G.TPCiv6 = false
		NPC6:Cheat(
		"Checkbox",
		"Auto Farm NPCs",
		function(state)
		_G.TPCiv6 = not _G.TPCiv6
		while wait() do
		if _G.TPCiv6 then
		for _,v in pairs(game:GetService("Workspace").NPCs["Deadly Deadlands"]:GetChildren()) do 
		repeat wait()game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.UpperTorso.CFrame game:GetService("ReplicatedStorage").Swing:FireServer()until v.Humanoid.Health == 0 
		wait(2)
				end
				end
			end
		end)
		
-- Settings Tab


local SettingsCategory = FinityWindow:Category("Settings")

	local GUIShit = SettingsCategory:Sector("Gui")
		
		GUIShit:Cheat("Button", "Destroy Gui", function()
			game.CoreGui.FinityUI:Destroy()
		end)
	
		GUIShit:Cheat("Label", "Press T To Show/Hide Synthx Hub")
	
	local Player = SettingsCategory:Sector("Player")
	
		Player:Cheat("Button", "Reset Player", function()
			game.Players.LocalPlayer.Character.Humanoid.Health = 0
		end)
	
	-- Synthx Hub Tab
	
local MiscellaneousCategory = FinityWindow:Category("Synthx Hub")
	
	local Games = MiscellaneousCategory:Sector("Current Supported Games:")
	
		Games:Cheat("Label", "1: Fitness Simulator")
		Games:Cheat("Label", "2: Phantom Forces")
		Games:Cheat("Label", "3: Viking Simulator")
		Games:Cheat("Label", "4: Survive The Disasters 2")
		
	local Discord = MiscellaneousCategory:Sector("Discord:")
		
		Discord:Cheat("Label", "https://discord.gg/QnRX47A")
	
			Discord:Cheat("Button", "Copy Discord Link:", function()
			setclipboard("https://discord.gg/QnRX47A")
		end)
		
-- Credits Tab

local CreditsCategory = FinityWindow:Category("Credits")

	local SynthxCredits = CreditsCategory:Sector("Synthx Hub Team:")
		
		SynthxCredits:Cheat("Label", "aussie#0768")
		
	local UILIB = CreditsCategory:Sector("Main UI Lib:")
		
	UILIB:Cheat("Label", "Finity UI")
	UILIB:Cheat("Label", "Made By: deto#7612")
	
	local Thanks = CreditsCategory:Sector("Special Thanks To:")
		
		Thanks:Cheat("Label", "brably#0001")
