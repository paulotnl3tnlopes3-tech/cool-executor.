--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 

designed using localmaze gui creator
]=]

-- Instances: 22 | Scripts: 6 | Modules: 0 | Tags: 0
local LMG2L = {};

-- Players.paulotnl3.PlayerGui.ScreenGui
LMG2L["ScreenGui_1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
LMG2L["ScreenGui_1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame
LMG2L["Frame_2"] = Instance.new("Frame", LMG2L["ScreenGui_1"]);
LMG2L["Frame_2"]["BorderSizePixel"] = 0;
LMG2L["Frame_2"]["BackgroundColor3"] = Color3.fromRGB(24, 24, 24);
LMG2L["Frame_2"]["Size"] = UDim2.new(0.34277, 0, 0.39572, 0);
LMG2L["Frame_2"]["Position"] = UDim2.new(0.35635, 0, 0.14127, 0);
LMG2L["Frame_2"]["BackgroundTransparency"] = 0.5;


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.Frame4
LMG2L["Frame4_3"] = Instance.new("Frame", LMG2L["Frame_2"]);
LMG2L["Frame4_3"]["BorderSizePixel"] = 0;
LMG2L["Frame4_3"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["Frame4_3"]["Size"] = UDim2.new(0.0099, 0, 1.00909, 0);
LMG2L["Frame4_3"]["Position"] = UDim2.new(0.99505, 0, -0.00909, 0);
LMG2L["Frame4_3"]["Name"] = [[Frame4]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.LocalScript
LMG2L["LocalScript_4"] = Instance.new("LocalScript", LMG2L["Frame_2"]);



-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.UIAspectRatioConstraint
LMG2L["UIAspectRatioConstraint_5"] = Instance.new("UIAspectRatioConstraint", LMG2L["Frame_2"]);
LMG2L["UIAspectRatioConstraint_5"]["AspectRatio"] = 1.94231;


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.Frame3
LMG2L["Frame3_6"] = Instance.new("Frame", LMG2L["Frame_2"]);
LMG2L["Frame3_6"]["BorderSizePixel"] = 0;
LMG2L["Frame3_6"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["Frame3_6"]["Size"] = UDim2.new(1, 0, 0.01818, 0);
LMG2L["Frame3_6"]["Position"] = UDim2.new(0, 0, -0.00909, 0);
LMG2L["Frame3_6"]["Name"] = [[Frame3]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.execute
LMG2L["execute_7"] = Instance.new("TextButton", LMG2L["Frame_2"]);
LMG2L["execute_7"]["BorderSizePixel"] = 0;
LMG2L["execute_7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["execute_7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["execute_7"]["Size"] = UDim2.new(0.19802, 0, 0.10909, 0);
LMG2L["execute_7"]["Text"] = [[executar]];
LMG2L["execute_7"]["Name"] = [[execute]];
LMG2L["execute_7"]["Position"] = UDim2.new(0.0396, 0, 0.82727, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.execute.LocalScript
LMG2L["LocalScript_8"] = Instance.new("LocalScript", LMG2L["execute_7"]);



-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.script
LMG2L["script_9"] = Instance.new("TextBox", LMG2L["Frame_2"]);
LMG2L["script_9"]["Name"] = [[script]];
LMG2L["script_9"]["TextXAlignment"] = Enum.TextXAlignment.Left;
LMG2L["script_9"]["BorderSizePixel"] = 0;
LMG2L["script_9"]["TextSize"] = 6;
LMG2L["script_9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["script_9"]["TextYAlignment"] = Enum.TextYAlignment.Top;
LMG2L["script_9"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["script_9"]["PlaceholderText"] = [[scripts]];
LMG2L["script_9"]["Size"] = UDim2.new(0.91089, 0, 0.66346, 0);
LMG2L["script_9"]["Position"] = UDim2.new(0.0396, 0, 0.14423, 0);
LMG2L["script_9"]["Text"] = [[print("hello world")]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.UIDragDetector
LMG2L["UIDragDetector_a"] = Instance.new("UIDragDetector", LMG2L["Frame_2"]);



-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.apagar
LMG2L["apagar_b"] = Instance.new("TextButton", LMG2L["Frame_2"]);
LMG2L["apagar_b"]["BorderSizePixel"] = 0;
LMG2L["apagar_b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["apagar_b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["apagar_b"]["Size"] = UDim2.new(0.17822, 0, 0.10909, 0);
LMG2L["apagar_b"]["BorderColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["apagar_b"]["Text"] = [[limpar]];
LMG2L["apagar_b"]["Name"] = [[apagar]];
LMG2L["apagar_b"]["Position"] = UDim2.new(0.26733, 0, 0.82727, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.r6
LMG2L["r6_c"] = Instance.new("TextButton", LMG2L["Frame_2"]);
LMG2L["r6_c"]["BorderSizePixel"] = 0;
LMG2L["r6_c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["r6_c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["r6_c"]["Size"] = UDim2.new(0.05941, 0, 0.10909, 0);
LMG2L["r6_c"]["Text"] = [[R6]];
LMG2L["r6_c"]["Name"] = [[r6]];
LMG2L["r6_c"]["Position"] = UDim2.new(0.5099, 0, 0.82727, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.r6.LocalScript
LMG2L["LocalScript_d"] = Instance.new("LocalScript", LMG2L["r6_c"]);



-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.LocalScript2
LMG2L["LocalScript2_e"] = Instance.new("LocalScript", LMG2L["Frame_2"]);
LMG2L["LocalScript2_e"]["Name"] = [[LocalScript2]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.sky
LMG2L["sky_f"] = Instance.new("TextButton", LMG2L["Frame_2"]);
LMG2L["sky_f"]["BorderSizePixel"] = 0;
LMG2L["sky_f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["sky_f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["sky_f"]["Size"] = UDim2.new(0.15842, 0, 0.10577, 0);
LMG2L["sky_f"]["BorderColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["sky_f"]["Text"] = [[skybox]];
LMG2L["sky_f"]["Name"] = [[sky]];
LMG2L["sky_f"]["Position"] = UDim2.new(0.74752, 0, 0.82727, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.sky.LocalScript
LMG2L["LocalScript_10"] = Instance.new("LocalScript", LMG2L["sky_f"]);



-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.TextLabel
LMG2L["TextLabel_11"] = Instance.new("TextLabel", LMG2L["Frame_2"]);
LMG2L["TextLabel_11"]["BorderSizePixel"] = 0;
LMG2L["TextLabel_11"]["TextSize"] = 10;
LMG2L["TextLabel_11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["TextLabel_11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["TextLabel_11"]["BackgroundTransparency"] = 1;
LMG2L["TextLabel_11"]["Size"] = UDim2.new(0.34158, 0, 0.07692, 0);
LMG2L["TextLabel_11"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["TextLabel_11"]["Text"] = [[c00lkidd 2026]];
LMG2L["TextLabel_11"]["Position"] = UDim2.new(0.53465, 0, 0.01923, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.TextLabel.ImageLabel
LMG2L["ImageLabel_12"] = Instance.new("ImageLabel", LMG2L["TextLabel_11"]);
LMG2L["ImageLabel_12"]["BorderSizePixel"] = 0;
LMG2L["ImageLabel_12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- LMG2L["ImageLabel_12"]["ImageContent"] = ;
LMG2L["ImageLabel_12"]["Image"] = [[rbxassetid://158118263]];
LMG2L["ImageLabel_12"]["Size"] = UDim2.new(0.89855, 0, 7.375, 0);
LMG2L["ImageLabel_12"]["ClipsDescendants"] = true;
LMG2L["ImageLabel_12"]["BackgroundTransparency"] = 1;
LMG2L["ImageLabel_12"]["Rotation"] = 10;
LMG2L["ImageLabel_12"]["Position"] = UDim2.new(0.66667, 0, -2.375, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.re
LMG2L["re_13"] = Instance.new("TextButton", LMG2L["Frame_2"]);
LMG2L["re_13"]["BorderSizePixel"] = 0;
LMG2L["re_13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
LMG2L["re_13"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
LMG2L["re_13"]["Size"] = UDim2.new(0.08911, 0, 0.11538, 0);
LMG2L["re_13"]["Text"] = [[resetar]];
LMG2L["re_13"]["Name"] = [[re]];
LMG2L["re_13"]["Position"] = UDim2.new(0.61386, 0, 0.82727, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.re.LocalScript3
LMG2L["LocalScript3_14"] = Instance.new("LocalScript", LMG2L["re_13"]);
LMG2L["LocalScript3_14"]["Name"] = [[LocalScript3]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.Frame
LMG2L["Frame_15"] = Instance.new("Frame", LMG2L["Frame_2"]);
LMG2L["Frame_15"]["BorderSizePixel"] = 0;
LMG2L["Frame_15"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["Frame_15"]["Size"] = UDim2.new(0.0099, 0, 1.00909, 0);
LMG2L["Frame_15"]["Position"] = UDim2.new(0, 0, -0.00909, 0);


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.Frame2
LMG2L["Frame2_16"] = Instance.new("Frame", LMG2L["Frame_2"]);
LMG2L["Frame2_16"]["BorderSizePixel"] = 0;
LMG2L["Frame2_16"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
LMG2L["Frame2_16"]["Size"] = UDim2.new(1, 0, 0.01818, 0);
LMG2L["Frame2_16"]["Position"] = UDim2.new(0, 0, 0.98182, 0);
LMG2L["Frame2_16"]["Name"] = [[Frame2]];


-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.LocalScript
local function C_4()
	local script = LMG2L["LocalScript_4"];
	local gui = script.Parent	
	
	local botaoApagar = gui:FindFirstChild("apagar", true)	
	local caixaScript = gui:FindFirstChild("script", true)	
	
	botaoApagar.MouseButton1Click:Connect(function()	
	    caixaScript.Text = ""	
	end)	
end;
task.spawn(C_4);
-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.execute.LocalScript
local function C_8()
	local script = LMG2L["LocalScript_8"];
	local button = script.Parent	
	local textbox = script.Parent.Parent:WaitForChild("script") -- nome da caixa onde você digita	
	
	button.MouseButton1Click:Connect(function()	
		local comando = textbox.Text	
	
		if comando ~= "" then	
			if _G.AddToConsole then	
				_G.AddToConsole(comando)	
			end	
		end	
	end)	
end;
task.spawn(C_8);
-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.r6.LocalScript
local function C_d()
	local script = LMG2L["LocalScript_d"];
	local button = script.Parent  -- ESTE É O BOTÃO "R6"	
	local Players = game:GetService("Players")	
	local LocalPlayer = Players.LocalPlayer	
	
	local storedAppearance = nil	
	
	-- Salvar aparência	
	local function storeAppearance(char)	
	    local appearance = {}	
	    appearance.shirt = char:FindFirstChildOfClass("Shirt") and char:FindFirstChildOfClass("Shirt").ShirtTemplate or ""	
	    appearance.pants = char:FindFirstChildOfClass("Pants") and char:FindFirstChildOfClass("Pants").PantsTemplate or ""	
	    appearance.bodyColors = char:FindFirstChild("Body Colors") and char:FindFirstChild("Body Colors"):Clone() or nil	
	    return appearance	
	end	
	
	-- Aplicar aparência	
	local function applyAppearance(char)	
	    if not char or not storedAppearance then return end	
	
	    -- remover antigas	
	    for _, item in pairs(char:GetChildren()) do	
	        if item:IsA("Shirt") or item:IsA("Pants") or item.Name == "Body Colors" then	
	            item:Destroy()	
	        end	
	    end	
	
	    -- aplicar shirt	
	    if storedAppearance.shirt ~= "" then	
	        local shirt = Instance.new("Shirt")	
	        shirt.ShirtTemplate = storedAppearance.shirt	
	        shirt.Parent = char	
	    end	
	
	    -- aplicar pants	
	    if storedAppearance.pants ~= "" then	
	        local pants = Instance.new("Pants")	
	        pants.PantsTemplate = storedAppearance.pants	
	        pants.Parent = char	
	    end	
	
	    -- aplicar body colors	
	    if storedAppearance.bodyColors then	
	        storedAppearance.bodyColors:Clone().Parent = char	
	    end	
	end	
	
	-- Converter para R6	
	local function convertToR6()	
	    local oldChar = LocalPlayer.Character	
	    if not oldChar then return end	
	
	    -- salvar aparência antes de mudar	
	    storedAppearance = storeAppearance(oldChar)	
	
	    -- esconder R15	
	    for _, part in pairs(oldChar:GetChildren()) do	
	        if part:IsA("BasePart") or part:IsA("Accessory") then	
	            part.Transparency = 1	
	            if part:IsA("BasePart") then	
	                part.CanCollide = false	
	            end	
	        end	
	    end	
	
	    -- rodar o script externo de R6	
	    spawn(function()	
	        pcall(function()	
	            loadstring(game:HttpGet("https://pastebin.com/raw/jHGVauVX", true))()	
	        end)	
	
	        -- esperar o novo R6 nascer	
	        repeat task.wait() until LocalPlayer.Character and LocalPlayer.Character ~= oldChar	
	
	        -- aplicar aparência no novo R6	
	        task.wait(1)	
	        applyAppearance(LocalPlayer.Character)	
	    end)	
	end	
	
	-- ➤ AGORA SIM: SÓ EXECUTA QUANDO CLICA NO BOTÃO "R6"	
	button.MouseButton1Click:Connect(function()	
	    print("Botão R6 clicado!")	
	    convertToR6()	
	end)	
	
	-- reaplica skin ao respawn	
	LocalPlayer.CharacterAdded:Connect(function(char)	
	    task.wait(1)	
	    if storedAppearance then	
	        applyAppearance(char)	
	    end	
	end)	
end;
task.spawn(C_d);
-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.LocalScript2
local function C_e()
	local script = LMG2L["LocalScript2_e"];
	local gui = script.Parent	
	
	local caixa = gui:WaitForChild("script") -- TextBox	
	local botao = gui:WaitForChild("execute") -- Botão execute	
	
	botao.MouseButton1Click:Connect(function()	
	    local code = caixa.Text	
	
	    if code == "" then	
	        warn("Nenhum código para executar!")	
	        return	
	    end	
	
	    local fn, loadErr = loadstring(code)	
	    if not fn then	
	        warn("Erro ao carregar código:", loadErr)	
	        return	
	    end	
	
	    local ok, execErr = pcall(fn)	
	    if not ok then	
	        warn("Erro ao executar:", execErr)	
	    end	
	end)	
end;
task.spawn(C_e);
-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.sky.LocalScript
local function C_10()
	local script = LMG2L["LocalScript_10"];
	-- LocalScript dentro do botão "Sky"	
	
	local botao = script.Parent  -- O botão Sky	
	
	botao.MouseButton1Click:Connect(function()	
	-- Cria o Skybox	
	local sky = Instance.new("Sky")	
	sky.SkyboxBk = "rbxassetid://158118263"	
	sky.SkyboxDn = "rbxassetid://158118263"	
	sky.SkyboxFt = "rbxassetid://158118263"	
	sky.SkyboxLf = "rbxassetid://158118263"	
	sky.SkyboxRt = "rbxassetid://158118263"	
	sky.SkyboxUp = "rbxassetid://158118263"	
	sky.Parent = game.Lighting	
	
	-- Música adicionada	
	local music = Instance.new("Sound", game.Workspace)	
	music.Name = "BackgroundMusic"	
	music.SoundId = "rbxassetid://102193217451832"	
	music.Volume = 1500	
	music.Looped = true	
	music.PlaybackSpeed = 0.3 -- 🔊 Velocidade ajustada	
	music:Play()	
	end)	
end;
task.spawn(C_10);
-- Players.paulotnl3.PlayerGui.ScreenGui.Frame.re.LocalScript3
local function C_14()
	local script = LMG2L["LocalScript3_14"];
	local button = script.Parent	
	local Players = game:GetService("Players")	
	local player = Players.LocalPlayer	
	
	button.MouseButton1Click:Connect(function()	
	    local char = player.Character	
	    if not char then return end	
	
	    local hrp = char:FindFirstChild("HumanoidRootPart")	
	    local hum = char:FindFirstChild("Humanoid")	
	
	    if hrp and hum then	
	        -- Salvar posição atual	
	        local pos = hrp.CFrame	
	
	        -- Matar rapidamente	
	        hum.Health = 0	
	
	        -- Esperar renascer	
	        player.CharacterAdded:Wait()	
	
	        -- Aplicar a posição salva ao novo personagem	
	        local newChar = player.Character	
	        local newHrp = newChar:WaitForChild("HumanoidRootPart")	
	        newHrp.CFrame = pos	
	    end	
	end)	
end;
task.spawn(C_14);

return LMG2L["ScreenGui_1"], require;
