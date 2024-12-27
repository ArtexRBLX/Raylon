--[=[
 d888   db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88 
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER
]=]

-- Instances: 114 | Scripts: 22 | Modules: 12
local G2L = {};

-- StarterGui.SylonX
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["Name"] = [[Raylon 1.2]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

-- StarterGui.SylonX.MainUI
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["Active"] = true;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 139);
G2L["2"]["Size"] = UDim2.new(0, 641, 0, 282);
G2L["2"]["Position"] = UDim2.new(0.11153730750083923, 0, 0.21357615292072296, 0);
G2L["2"]["Name"] = [[MainUI]];

-- StarterGui.SylonX.MainUI.UICorner
G2L["3"] = Instance.new("UICorner", G2L["2"]);


-- StarterGui.SylonX.MainUI.Panel
G2L["4"] = Instance.new("Frame", G2L["2"]);
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(49, 49, 49);
G2L["4"]["Size"] = UDim2.new(0, 641, 0, 37);
G2L["4"]["Name"] = [[Panel]];

-- StarterGui.SylonX.MainUI.Panel.UICorner
G2L["5"] = Instance.new("UICorner", G2L["4"]);


-- StarterGui.SylonX.MainUI.Panel.Frame
G2L["6"] = Instance.new("Frame", G2L["4"]);
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Size"] = UDim2.new(0, 122, 0, 37);
G2L["6"]["Position"] = UDim2.new(0.009360373951494694, 0, 0, 0);

-- StarterGui.SylonX.MainUI.Panel.Frame.UICorner
G2L["7"] = Instance.new("UICorner", G2L["6"]);


-- StarterGui.SylonX.MainUI.Panel.Frame.name
G2L["8"] = Instance.new("TextLabel", G2L["6"]);
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8"]["TextSize"] = 22;
G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 139);
G2L["8"]["Size"] = UDim2.new(0, 61, 0, 37);
G2L["8"]["Text"] = [[Raylon]];
G2L["8"]["Name"] = [[name]];
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Position"] = UDim2.new(0.30322766304016113, 0, 0, 0);

-- StarterGui.SylonX.MainUI.Panel.Frame.ImageLabel
G2L["9"] = Instance.new("ImageLabel", G2L["6"]);
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Image"] = [[rbxassetid://12823941607]];
G2L["9"]["Size"] = UDim2.new(0, 37, 0, 37);

-- StarterGui.SylonX.MainUI.Panel.Frame.ImageLabel.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);


-- StarterGui.SylonX.MainUI.Panel.Cloes
G2L["b"] = Instance.new("TextButton", G2L["4"]);
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["TextSize"] = 31;
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["Size"] = UDim2.new(0, 37, 0, 37);
G2L["b"]["Name"] = [[Cloes]];
G2L["b"]["Text"] = [[X]];
G2L["b"]["Position"] = UDim2.new(0.9219968914985657, 0, 0, 0);
G2L["b"]["BackgroundTransparency"] = 1;

-- StarterGui.SylonX.MainUI.Panel.Cloes.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["b"]);


-- StarterGui.SylonX.MainUI.TabSection
G2L["d"] = Instance.new("Frame", G2L["2"]);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["d"]["Size"] = UDim2.new(0, 128, 0, 245);
G2L["d"]["Position"] = UDim2.new(0, 0, 0.13120567798614502, 0);
G2L["d"]["Name"] = [[TabSection]];

-- StarterGui.SylonX.MainUI.TabSection.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);


-- StarterGui.SylonX.MainUI.TabSection.Home
G2L["f"] = Instance.new("TextButton", G2L["d"]);
G2L["f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 139);
G2L["f"]["TextSize"] = 21;
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(251, 251, 251);
G2L["f"]["Size"] = UDim2.new(0, 115, 0, 23);
G2L["f"]["Name"] = [[Home]];
G2L["f"]["Text"] = [[    Home]];
G2L["f"]["Position"] = UDim2.new(0.046875, 0, 0.02857142873108387, 0);

-- StarterGui.SylonX.MainUI.TabSection.Home.UICorner
G2L["10"] = Instance.new("UICorner", G2L["f"]);


-- StarterGui.SylonX.MainUI.TabSection.Home.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["f"]);


-- StarterGui.SylonX.MainUI.TabSection.Executor
G2L["12"] = Instance.new("TextButton", G2L["d"]);
G2L["12"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 139);
G2L["12"]["TextSize"] = 21;
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(251, 251, 251);
G2L["12"]["Size"] = UDim2.new(0, 115, 0, 23);
G2L["12"]["Name"] = [[Executor]];
G2L["12"]["Text"] = [[    Executor]];
G2L["12"]["Position"] = UDim2.new(0.046875, 0, 0.15102040767669678, 0);

-- StarterGui.SylonX.MainUI.TabSection.Executor.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);


-- StarterGui.SylonX.MainUI.TabSection.Executor.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["12"]);


-- StarterGui.SylonX.MainUI.TabSection.Scripts
G2L["15"] = Instance.new("TextButton", G2L["d"]);
G2L["15"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 139);
G2L["15"]["TextSize"] = 21;
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["15"]["TextColor3"] = Color3.fromRGB(251, 251, 251);
G2L["15"]["Size"] = UDim2.new(0, 115, 0, 23);
G2L["15"]["Name"] = [[Scripts]];
G2L["15"]["Text"] = [[    Scripts]];
G2L["15"]["Position"] = UDim2.new(0.046875, 0, 0.26938775181770325, 0);

-- StarterGui.SylonX.MainUI.TabSection.Scripts.UICorner
G2L["16"] = Instance.new("UICorner", G2L["15"]);


-- StarterGui.SylonX.MainUI.TabSection.Scripts.LocalScript
G2L["17"] = Instance.new("LocalScript", G2L["15"]);


-- StarterGui.SylonX.MainUI.TabSection.Scripts.LocalScript
G2L["18"] = Instance.new("LocalScript", G2L["15"]);


-- StarterGui.SylonX.MainUI.TabSection.Credit
G2L["19"] = Instance.new("TextButton", G2L["d"]);
G2L["19"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 139);
G2L["19"]["TextSize"] = 21;
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(251, 251, 251);
G2L["19"]["Size"] = UDim2.new(0, 115, 0, 23);
G2L["19"]["Name"] = [[Credit]];
G2L["19"]["Text"] = [[    Credits]];
G2L["19"]["Position"] = UDim2.new(0.046875, 0, 0.8530611991882324, 0);

-- StarterGui.SylonX.MainUI.TabSection.Credit.UICorner
G2L["1a"] = Instance.new("UICorner", G2L["19"]);


-- StarterGui.SylonX.MainUI.TabSection.Credit.LocalScript
G2L["1b"] = Instance.new("LocalScript", G2L["19"]);


-- StarterGui.SylonX.MainUI.Tabs
G2L["1c"] = Instance.new("Folder", G2L["2"]);
G2L["1c"]["Name"] = [[Tabs]];

-- StarterGui.SylonX.MainUI.Tabs.Home
G2L["1d"] = Instance.new("Frame", G2L["1c"]);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundTransparency"] = 1;
G2L["1d"]["Size"] = UDim2.new(0, 513, 0, 245);
G2L["1d"]["Position"] = UDim2.new(0.19968798756599426, 0, 0.13120567798614502, 0);
G2L["1d"]["Name"] = [[Home]];

-- StarterGui.SylonX.MainUI.Tabs.Home.name
G2L["1e"] = Instance.new("TextLabel", G2L["1d"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1e"]["TextSize"] = 22;
G2L["1e"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["1e"]["Size"] = UDim2.new(0, 146, 0, 37);
G2L["1e"]["Text"] = [[Hi, User!]];
G2L["1e"]["Name"] = [[name]];
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Position"] = UDim2.new(0.014728687703609467, 0, 0.02857142873108387, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.name.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);


-- StarterGui.SylonX.MainUI.Tabs.Home.time
G2L["20"] = Instance.new("TextLabel", G2L["1d"]);
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["20"]["TextSize"] = 22;
G2L["20"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["20"]["Size"] = UDim2.new(0, 49, 0, 37);
G2L["20"]["Text"] = [[88:88]];
G2L["20"]["Name"] = [[time]];
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Position"] = UDim2.new(0.014728687703609467, 0, 0.47755101323127747, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.time.LocalScript
G2L["21"] = Instance.new("LocalScript", G2L["20"]);


-- StarterGui.SylonX.MainUI.Tabs.Home.clock
G2L["22"] = Instance.new("TextLabel", G2L["1d"]);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["22"]["TextSize"] = 22;
G2L["22"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["22"]["Size"] = UDim2.new(0, 63, 0, 37);
G2L["22"]["Text"] = [[Clock:]];
G2L["22"]["Name"] = [[clock]];
G2L["22"]["BackgroundTransparency"] = 1;
G2L["22"]["Position"] = UDim2.new(0.014728687703609467, 0, 0.3469387888908386, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.date
G2L["23"] = Instance.new("TextLabel", G2L["1d"]);
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["23"]["TextSize"] = 22;
G2L["23"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["23"]["Size"] = UDim2.new(0, 63, 0, 37);
G2L["23"]["Text"] = [[Date:]];
G2L["23"]["Name"] = [[date]];
G2L["23"]["BackgroundTransparency"] = 1;
G2L["23"]["Position"] = UDim2.new(0.1375357061624527, 0, 0.3469387888908386, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.datec
G2L["24"] = Instance.new("TextLabel", G2L["1d"]);
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["24"]["TextSize"] = 22;
G2L["24"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["24"]["Size"] = UDim2.new(0, 83, 0, 37);
G2L["24"]["Text"] = [[88:88]];
G2L["24"]["Name"] = [[datec]];
G2L["24"]["BackgroundTransparency"] = 1;
G2L["24"]["Position"] = UDim2.new(0.1375357061624527, 0, 0.47755101323127747, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.datec.LocalScript
G2L["25"] = Instance.new("LocalScript", G2L["24"]);


-- StarterGui.SylonX.MainUI.Tabs.Home.Frame
G2L["26"] = Instance.new("Frame", G2L["1d"]);
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Size"] = UDim2.new(0, 122, 0, 37);
G2L["26"]["Position"] = UDim2.new(0.7247599959373474, 0, 0.795918345451355, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.Frame.UICorner
G2L["27"] = Instance.new("UICorner", G2L["26"]);


-- StarterGui.SylonX.MainUI.Tabs.Home.Frame.name
G2L["28"] = Instance.new("TextLabel", G2L["26"]);
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["28"]["TextSize"] = 22;
G2L["28"]["TextColor3"] = Color3.fromRGB(0, 0, 139);
G2L["28"]["Size"] = UDim2.new(0, 61, 0, 37);
G2L["28"]["Text"] = [[Raylon]];
G2L["28"]["Name"] = [[name]];
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Position"] = UDim2.new(0.30322766304016113, 0, 0, 0);

-- StarterGui.SylonX.MainUI.Tabs.Home.Frame.ImageLabel
G2L["29"] = Instance.new("ImageLabel", G2L["26"]);
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["Image"] = [[rbxassetid://12823941607]];
G2L["29"]["Size"] = UDim2.new(0, 37, 0, 37);

-- StarterGui.SylonX.MainUI.Tabs.Home.Frame.ImageLabel.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);


-- StarterGui.SylonX.MainUI.Tabs.Home.name
G2L["2b"] = Instance.new("TextLabel", G2L["1d"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2b"]["TextSize"] = 40;
G2L["2b"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["2b"]["Size"] = UDim2.new(0, 284, 0, 74);
G2L["2b"]["Text"] = [[Welcome to Raylon! Thanks for using the up-to-date version]];
G2L["2b"]["Name"] = [[name]];
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Position"] = UDim2.new(0.3246701955795288, 0, 0.02857142686843872, 0);

-- StarterGui.SylonX.MainUI.Tabs.Executor
G2L["2c"] = Instance.new("Frame", G2L["1c"]);
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundTransparency"] = 1;
G2L["2c"]["Size"] = UDim2.new(0, 513, 0, 245);
G2L["2c"]["Position"] = UDim2.new(0.19968798756599426, 0, 0.13120567798614502, 0);
G2L["2c"]["Visible"] = false;
G2L["2c"]["Name"] = [[Executor]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar
G2L["2d"] = Instance.new("Frame", G2L["2c"]);
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["BackgroundTransparency"] = 0.8999999761581421;
G2L["2d"]["Size"] = UDim2.new(0.9533820152282715, 0, 0.7485234141349792, 0);
G2L["2d"]["Position"] = UDim2.new(0.026000019162893295, 0, 0.04687291383743286, 0);
G2L["2d"]["Name"] = [[TextboxBar]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript
G2L["2e"] = Instance.new("LocalScript", G2L["2d"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor
G2L["2f"] = Instance.new("ModuleScript", G2L["2e"]);
G2L["2f"]["Name"] = [[ScriptEditor]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Syntax
G2L["30"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["30"]["Name"] = [[Syntax]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Theme
G2L["31"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["31"]["Name"] = [[Theme]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.GetLines
G2L["32"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["32"]["Name"] = [[GetLines]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.FakeEditor
G2L["33"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["33"]["Name"] = [[FakeEditor]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.GetLine
G2L["34"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["34"]["Name"] = [[GetLine]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.TweenLibrary
G2L["35"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["35"]["Name"] = [[TweenLibrary]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.GetWord
G2L["36"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["36"]["Name"] = [[GetWord]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Lexer
G2L["37"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["37"]["Name"] = [[Lexer]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Suggestions
G2L["38"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["38"]["Name"] = [[Suggestions]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Words
G2L["39"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["39"]["Name"] = [[Words]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor
G2L["3a"] = Instance.new("Frame", G2L["2f"]);
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(23, 27, 23);
G2L["3a"]["BackgroundTransparency"] = 0.4000000059604645;
G2L["3a"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(28, 43, 54);
G2L["3a"]["Name"] = [[Editor]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll
G2L["3b"] = Instance.new("ScrollingFrame", G2L["3a"]);
G2L["3b"]["Active"] = true;
G2L["3b"]["CanvasSize"] = UDim2.new(0, 0, 0, 0);
G2L["3b"]["ElasticBehavior"] = Enum.ElasticBehavior.Always;
G2L["3b"]["TopImage"] = [[rbxasset://textures/ui/Scroll/scroll-middle.png]];
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["3b"]["BackgroundTransparency"] = 0.9990000128746033;
G2L["3b"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3b"]["ScrollBarImageColor3"] = Color3.fromRGB(64, 64, 64);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(53, 53, 53);
G2L["3b"]["Name"] = [[Scroll]];
G2L["3b"]["BottomImage"] = [[rbxasset://textures/ui/Scroll/scroll-middle.png]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source
G2L["3c"] = Instance.new("TextBox", G2L["3b"]);
G2L["3c"]["TextSize"] = 17;
G2L["3c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3c"]["TextStrokeColor3"] = Color3.fromRGB(41, 41, 41);
G2L["3c"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["3c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3c"]["MultiLine"] = true;
G2L["3c"]["BackgroundTransparency"] = 0.9990000128746033;
G2L["3c"]["Size"] = UDim2.new(1, -44, 1, -5);
G2L["3c"]["Text"] = [[]];
G2L["3c"]["Position"] = UDim2.new(0, 44, 0, 5);
G2L["3c"]["AutomaticSize"] = Enum.AutomaticSize.XY;
G2L["3c"]["Name"] = [[Source]];
G2L["3c"]["ClearTextOnFocus"] = false;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.LineHighlight
G2L["3d"] = Instance.new("Frame", G2L["3c"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["AnchorPoint"] = Vector2.new(0, 0.5);
G2L["3d"]["BackgroundTransparency"] = 0.9399999976158142;
G2L["3d"]["Size"] = UDim2.new(1, 0, 0, 17);
G2L["3d"]["Position"] = UDim2.new(0, -10, 0, 9);
G2L["3d"]["Name"] = [[LineHighlight]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.Hidden
G2L["3e"] = Instance.new("TextLabel", G2L["3c"]);
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(27, 32, 27);
G2L["3e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["TextSize"] = 22;
G2L["3e"]["TextColor3"] = Color3.fromRGB(249, 66, 164);
G2L["3e"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[*script hidden*]];
G2L["3e"]["Name"] = [[Hidden]];
G2L["3e"]["Visible"] = false;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.Suggestion
G2L["3f"] = Instance.new("TextButton", G2L["3c"]);
G2L["3f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(40, 40, 40);
G2L["3f"]["TextSize"] = 17;
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["3f"]["TextColor3"] = Color3.fromRGB(244, 244, 244);
G2L["3f"]["Visible"] = false;
G2L["3f"]["Size"] = UDim2.new(0, 130, 0, 26);
G2L["3f"]["Name"] = [[Suggestion]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(60, 60, 60);
G2L["3f"]["Text"] = [[keyword]];
G2L["3f"]["AutomaticSize"] = Enum.AutomaticSize.X;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.Suggestion.TextPadding
G2L["40"] = Instance.new("UIPadding", G2L["3f"]);
G2L["40"]["Name"] = [[TextPadding]];
G2L["40"]["PaddingLeft"] = UDim.new(0, 30);

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.Suggestion.Icon
G2L["41"] = Instance.new("ImageLabel", G2L["3f"]);
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Image"] = [[rbxassetid://413365069]];
G2L["41"]["Size"] = UDim2.new(0, 26, 0, 26);
G2L["41"]["Name"] = [[Icon]];
G2L["41"]["BackgroundTransparency"] = 1;
G2L["41"]["Position"] = UDim2.new(0, -30, 0, 0);

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Source.Suggestion.Icon.UIAspectRatioConstraint
G2L["42"] = Instance.new("UIAspectRatioConstraint", G2L["41"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left
G2L["43"] = Instance.new("Frame", G2L["3b"]);
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["43"]["BackgroundTransparency"] = 0.4000000059604645;
G2L["43"]["Size"] = UDim2.new(0, 27, 1, 0);
G2L["43"]["AutomaticSize"] = Enum.AutomaticSize.Y;
G2L["43"]["Name"] = [[Left]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Right
G2L["44"] = Instance.new("Frame", G2L["43"]);
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["44"]["BackgroundTransparency"] = 0.4000000059604645;
G2L["44"]["Size"] = UDim2.new(0, 8, 1, 0);
G2L["44"]["Position"] = UDim2.new(1, 0, 0, 0);
G2L["44"]["AutomaticSize"] = Enum.AutomaticSize.Y;
G2L["44"]["Name"] = [[Right]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Right.BottomFade
G2L["45"] = Instance.new("UIGradient", G2L["44"]);
G2L["45"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.931, 0),NumberSequenceKeypoint.new(1.000, 1)};
G2L["45"]["Name"] = [[BottomFade]];
G2L["45"]["Rotation"] = 90;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Right.Shadow
G2L["46"] = Instance.new("Frame", G2L["44"]);
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["BackgroundTransparency"] = 0.800000011920929;
G2L["46"]["Size"] = UDim2.new(0, 5, 1, 0);
G2L["46"]["Position"] = UDim2.new(1, 0, 0, 0);
G2L["46"]["AutomaticSize"] = Enum.AutomaticSize.Y;
G2L["46"]["Name"] = [[Shadow]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Right.Shadow.UIGradient
G2L["47"] = Instance.new("UIGradient", G2L["46"]);
G2L["47"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Lines
G2L["48"] = Instance.new("TextLabel", G2L["43"]);
G2L["48"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["48"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["48"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["48"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["48"]["TextSize"] = 17;
G2L["48"]["TextColor3"] = Color3.fromRGB(242, 242, 242);
G2L["48"]["AutomaticSize"] = Enum.AutomaticSize.X;
G2L["48"]["Size"] = UDim2.new(1, -5, 1, -7);
G2L["48"]["Text"] = [[1]];
G2L["48"]["Name"] = [[Lines]];
G2L["48"]["BackgroundTransparency"] = 0.980000128746033;
G2L["48"]["Position"] = UDim2.new(0, 5, 0, 7);

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.Lines.BottomFade
G2L["49"] = Instance.new("UIGradient", G2L["48"]);
G2L["49"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.931, 0),NumberSequenceKeypoint.new(1.000, 1)};
G2L["49"]["Name"] = [[BottomFade]];
G2L["49"]["Rotation"] = 90;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.AdaptSize
G2L["4a"] = Instance.new("LocalScript", G2L["43"]);
G2L["4a"]["Name"] = [[AdaptSize]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.BottomFade
G2L["4b"] = Instance.new("UIGradient", G2L["43"]);
G2L["4b"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.931, 0),NumberSequenceKeypoint.new(1.000, 1)};
G2L["4b"]["Name"] = [[BottomFade]];
G2L["4b"]["Rotation"] = 90;

-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.TextFixer
G2L["4c"] = Instance.new("ModuleScript", G2L["2f"]);
G2L["4c"]["Name"] = [[TextFixer]];

-- StarterGui.SylonX.MainUI.Tabs.Executor.Execute
G2L["4d"] = Instance.new("TextButton", G2L["2c"]);
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["4d"]["TextSize"] = 26;
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["4d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["4d"]["Name"] = [[Execute]];
G2L["4d"]["Text"] = [[Execute]];
G2L["4d"]["Position"] = UDim2.new(0.025341130793094635, 0, 0.8285714387893677, 0);

-- StarterGui.SylonX.MainUI.Tabs.Executor.Execute.UICorner
G2L["4e"] = Instance.new("UICorner", G2L["4d"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.Execute.LocalScript
G2L["4f"] = Instance.new("LocalScript", G2L["4d"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.Clear
G2L["50"] = Instance.new("TextButton", G2L["2c"]);
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["50"]["TextSize"] = 26;
G2L["50"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["50"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["50"]["Name"] = [[Clear]];
G2L["50"]["Text"] = [[Clear]];
G2L["50"]["Position"] = UDim2.new(0.27290448546409607, 0, 0.8285714387893677, 0);

-- StarterGui.SylonX.MainUI.Tabs.Executor.Clear.UICorner
G2L["51"] = Instance.new("UICorner", G2L["50"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.Clear.LocalScript
G2L["52"] = Instance.new("LocalScript", G2L["50"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.Save
G2L["53"] = Instance.new("TextButton", G2L["2c"]);
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["53"]["TextSize"] = 26;
G2L["53"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["53"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["53"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["53"]["Name"] = [[Save]];
G2L["53"]["Text"] = [[Save]];
G2L["53"]["Position"] = UDim2.new(0.7465887069702148, 0, 0.8285714387893677, 0);

-- StarterGui.SylonX.MainUI.Tabs.Executor.Save.UICorner
G2L["54"] = Instance.new("UICorner", G2L["53"]);


-- StarterGui.SylonX.MainUI.Tabs.Executor.Save.LocalScript
G2L["55"] = Instance.new("LocalScript", G2L["53"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts
G2L["56"] = Instance.new("Frame", G2L["1c"]);
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["BackgroundTransparency"] = 1;
G2L["56"]["Size"] = UDim2.new(0, 513, 0, 245);
G2L["56"]["Position"] = UDim2.new(0.19968798756599426, 0, 0.13120567798614502, 0);
G2L["56"]["Visible"] = false;
G2L["56"]["Name"] = [[Scripts]];

-- StarterGui.SylonX.MainUI.Tabs.Scripts.IY
G2L["57"] = Instance.new("TextButton", G2L["56"]);
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["57"]["TextSize"] = 21;
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["57"]["Name"] = [[IY]];
G2L["57"]["Text"] = [[Infinite Yield]];
G2L["57"]["Position"] = UDim2.new(0.037037044763565063, 0, 0.15102040767669678, 0);

-- StarterGui.SylonX.MainUI.Tabs.Scripts.IY.UICorner
G2L["58"] = Instance.new("UICorner", G2L["57"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.IY.LocalScript
G2L["59"] = Instance.new("LocalScript", G2L["57"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.Dex
G2L["5a"] = Instance.new("TextButton", G2L["56"]);
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["5a"]["TextSize"] = 21;
G2L["5a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["5a"]["Name"] = [[Dex]];
G2L["5a"]["Text"] = [[Dex Explorer]];
G2L["5a"]["Position"] = UDim2.new(0.037037044763565063, 0, 0.3265306055545807, 0);

-- StarterGui.SylonX.MainUI.Tabs.Scripts.Dex.UICorner
G2L["5b"] = Instance.new("UICorner", G2L["5a"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.Dex.LocalScript
G2L["5c"] = Instance.new("LocalScript", G2L["5a"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.Owl
G2L["5d"] = Instance.new("TextButton", G2L["56"]);
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["5d"]["TextSize"] = 21;
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["5d"]["Name"] = [[Owl]];
G2L["5d"]["Text"] = [[Owl Hub]];
G2L["5d"]["Position"] = UDim2.new(0.037037044763565063, 0, 0.514285683631897, 0);

-- StarterGui.SylonX.MainUI.Tabs.Scripts.Owl.UICorner
G2L["5e"] = Instance.new("UICorner", G2L["5d"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.Owl.LocalScript
G2L["5f"] = Instance.new("LocalScript", G2L["5d"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.FatesEsp
G2L["60"] = Instance.new("TextButton", G2L["56"]);
G2L["60"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["60"]["TextSize"] = 21;
G2L["60"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["60"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["60"]["Size"] = UDim2.new(0, 119, 0, 35);
G2L["60"]["Name"] = [[FatesEsp]];
G2L["60"]["Text"] = [[Fates ESP]];
G2L["60"]["Position"] = UDim2.new(0.037037044763565063, 0, 0.7102040648460388, 0);

-- StarterGui.SylonX.MainUI.Tabs.Scripts.FatesEsp.UICorner
G2L["61"] = Instance.new("UICorner", G2L["60"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.FatesEsp.LocalScript
G2L["62"] = Instance.new("LocalScript", G2L["60"]);


-- StarterGui.SylonX.MainUI.Tabs.Scripts.name
G2L["63"] = Instance.new("TextLabel", G2L["56"]);
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["63"]["TextSize"] = 22;
G2L["63"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["63"]["Size"] = UDim2.new(0, 152, 0, 37);
G2L["63"]["Text"] = [[Raylon Recommends]];
G2L["63"]["Name"] = [[name]];
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["Position"] = UDim2.new(0.03617112338542938, 0, 0, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit
G2L["64"] = Instance.new("Frame", G2L["1c"]);
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["BackgroundTransparency"] = 1;
G2L["64"]["Size"] = UDim2.new(0, 513, 0, 245);
G2L["64"]["Position"] = UDim2.new(0.19968798756599426, 0, 0.13120567798614502, 0);
G2L["64"]["Visible"] = false;
G2L["64"]["Name"] = [[Credit]];

-- StarterGui.SylonX.MainUI.Tabs.Credit.CEO
G2L["65"] = Instance.new("TextLabel", G2L["64"]);
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["65"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["65"]["TextSize"] = 22;
G2L["65"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["65"]["Size"] = UDim2.new(0, 152, 0, 37);
G2L["65"]["Text"] = [[CEO:]];
G2L["65"]["Name"] = [[CEO]];
G2L["65"]["BackgroundTransparency"] = 1;
G2L["65"]["Position"] = UDim2.new(0.03617112338542938, 0, 0, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.CEOName
G2L["66"] = Instance.new("TextLabel", G2L["64"]);
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["66"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["66"]["TextSize"] = 18;
G2L["66"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["66"]["Size"] = UDim2.new(0, 152, 0, 21);
G2L["66"]["Text"] = [[SunRayHD]];
G2L["66"]["Name"] = [[CEOName]];
G2L["66"]["BackgroundTransparency"] = 1;
G2L["66"]["Position"] = UDim2.new(0.03617112338542938, 0, 0.11836734414100647, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.CEOName.CopyCeo
G2L["67"] = Instance.new("TextButton", G2L["66"]);
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["67"]["TextSize"] = 21;
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["67"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["67"]["Name"] = [[CopyCeo]];
G2L["67"]["Text"] = [[Copy]];
G2L["67"]["Position"] = UDim2.new(0.7950778603553772, 0, -0.02857171930372715, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.CEOName.CopyCeo.UICorner
G2L["68"] = Instance.new("UICorner", G2L["67"]);


-- StarterGui.SylonX.MainUI.Tabs.Credit.CEOName.CopyCeo.LocalScript
G2L["69"] = Instance.new("LocalScript", G2L["67"]);


-- StarterGui.SylonX.MainUI.Tabs.Credit.UI
G2L["6a"] = Instance.new("TextLabel", G2L["64"]);
G2L["6a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6a"]["TextSize"] = 22;
G2L["6a"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["6a"]["Size"] = UDim2.new(0, 152, 0, 37);
G2L["6a"]["Text"] = [[Dev/CoOwner:]];
G2L["6a"]["Name"] = [[Dev/CoOwner]];
G2L["6a"]["BackgroundTransparency"] = 1;
G2L["6a"]["Position"] = UDim2.new(0.03617112338542938, 0, 0.26938775181770325, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.UIName
G2L["6b"] = Instance.new("TextLabel", G2L["64"]);
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["TextSize"] = 18;
G2L["6b"]["TextColor3"] = Color3.fromRGB(239, 239, 239);
G2L["6b"]["Size"] = UDim2.new(0, 152, 0, 21);
G2L["6b"]["Text"] = [[Yusuf]];
G2L["6b"]["Name"] = [[UIName]];
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Position"] = UDim2.new(0.03617112338542938, 0, 0.3877550959587097, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.UIName.CopyCeo
G2L["6c"] = Instance.new("TextButton", G2L["6b"]);
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 255);
G2L["6c"]["TextSize"] = 21;
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["6c"]["Name"] = [[CopyCeo]];
G2L["6c"]["Text"] = [[Copy]];
G2L["6c"]["Position"] = UDim2.new(0.7950778603553772, 0, -0.02857171930372715, 0);

-- StarterGui.SylonX.MainUI.Tabs.Credit.UIName.CopyCeo.UICorner
G2L["6d"] = Instance.new("UICorner", G2L["6c"]);


-- StarterGui.SylonX.MainUI.Tabs.Credit.UIName.CopyCeo.LocalScript
G2L["6e"] = Instance.new("LocalScript", G2L["6c"]);


-- StarterGui.SylonX.MainUI.LocalScript
G2L["6f"] = Instance.new("LocalScript", G2L["2"]);


-- StarterGui.SylonX.ImageButton
G2L["70"] = Instance.new("ImageButton", G2L["1"]);
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["Image"] = [[rbxassetid://12823941607]];
G2L["70"]["Size"] = UDim2.new(0, 50, 0, 50);
G2L["70"]["Visible"] = false;
G2L["70"]["Position"] = UDim2.new(0.8731203079223633, 0, 0.1307947039604187, 0);

-- StarterGui.SylonX.ImageButton.UICorner
G2L["71"] = Instance.new("UICorner", G2L["70"]);
G2L["71"]["CornerRadius"] = UDim.new(0, 13);

-- StarterGui.SylonX.ImageButton.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["70"]);


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["2f"]] = {
Closure = function()
    local script = G2L["2f"];
-- Lexer by sleitnick
-- Everything else by me, bread. lol.


local module = {}

local syntax 	   = require(script.Syntax)
local getLines 	   = require(script.GetLines)
local fakeEditor   = require(script.FakeEditor)
local textFixer    = require(script.TextFixer)
local getLine 	   = require(script.GetLine)
local tween 	   = require(script.TweenLibrary)
local suggestions  = require(script.Suggestions)

function module.new(frame)
	local newEditor = script.Editor:Clone()
	newEditor.Parent = frame

	local editorObj  	= fakeEditor.new(newEditor)
	local textbox 	 	= newEditor.Scroll.Source
	local linesLabel 	= newEditor.Scroll.Left.Lines
	local lineHighlight = textbox.LineHighlight

	local highlightBox = Instance.new("TextLabel")
	highlightBox.Size = UDim2.new(1, 0,1, 0)
	highlightBox.Position = UDim2.new(0, 0,0, 0)
	highlightBox.TextColor3 = textbox.TextColor3
	highlightBox.BackgroundTransparency = 1
	highlightBox.Name = "Syntax"
	highlightBox.RichText = true
	highlightBox.TextSize = textbox.TextSize
	highlightBox.Font = textbox.Font
	highlightBox.TextXAlignment = Enum.TextXAlignment.Left
	highlightBox.TextYAlignment = Enum.TextYAlignment.Top
	highlightBox.TextStrokeColor3 = Color3.fromRGB(40, 40, 40)
	highlightBox.TextStrokeTransparency = 0.1
	highlightBox.Text = ""
	highlightBox.Parent = textbox
	
	editorObj:SetTheme("default")
	textFixer.Fix(highlightBox)
	suggestions:Start(newEditor)

	textbox:GetPropertyChangedSignal("Text"):Connect(function()
		syntax.Highlight(highlightBox, textbox.Text)

		-- Fix tabs
		textbox.Text = textbox.Text:gsub("\t", "    ")
		--textbox.CursorPosition += 4
		
		-- Update line count
		linesLabel.Text = getLines.GetLinesString(textbox.Text)
	end)
	
	textbox:GetPropertyChangedSignal("CursorPosition"):Connect(function()
		-- Position line highlight
		local lineYPos = ((getLine:GetCurrentLine(textbox) * textbox.TextSize) - math.ceil(lineHighlight.AbsoluteSize.Y / 2)) + 4

		if lineYPos ~= lineHighlight.Position.Y.Offset then
			tween.TweenPosition(lineHighlight, UDim2.new(0, -10,0, lineYPos), 0.1, Enum.EasingStyle.Quad)
		end
	end)

	return editorObj
end

return module

end;
};
G2L_MODULES[G2L["30"]] = {
Closure = function()
    local script = G2L["30"];
local module = {}

local lexer 	= require(script.Parent.Lexer)
local theme 	= require(script.Parent.Theme)
local textFixer = require(script.Parent.TextFixer)

local function ColorToFont(text, color)
	return string.format(
		'<font color="rgb(%s,%s,%s)">%s</font>',
		tostring(math.floor(color.R * 255)),
		tostring(math.floor(color.G * 255)),
		tostring(math.floor(color.B * 255)),
		text
	)
end

function module.Highlight(textbox, source)
	textbox.Text = ""

	for tokenType, text in lexer.scan(source) do
		local currentTheme = theme.current
		local tokenCol = currentTheme[tokenType]

		if tokenCol then
			textbox.Text = textbox.Text .. ColorToFont(text, tokenCol)
		else
			textbox.Text = textbox.Text .. text
		end
	end

	textFixer.Fix(textbox)
end

return module

end;
};
G2L_MODULES[G2L["31"]] = {
Closure = function()
    local script = G2L["31"];
local theme = {
	current = nil,
	themes = {
		["default"] = {
			["keyword"] = Color3.fromRGB(248, 109, 124),
			["builtin"] = Color3.fromRGB(84, 184, 247),
			["string"] = Color3.fromRGB(130, 241, 149),
			["number"] = Color3.fromRGB(255, 198, 0),
			["comment"] = Color3.fromRGB(106, 106, 100),
			["thingy"] = Color3.fromRGB(253, 251, 154)
		},
		["extra 2"] = {
			["keyword"] = Color3.fromRGB(249, 36, 114),
			["builtin"] = Color3.fromRGB(95, 209, 250),
			["string"] = Color3.fromRGB(217, 219, 88),
			["number"] = Color3.fromRGB(161, 118, 209),
			["comment"] = Color3.fromRGB(116, 122, 101),
			["thingy"] = Color3.fromRGB(248, 245, 139)
		}
	}
}

return theme

end;
};
G2L_MODULES[G2L["32"]] = {
Closure = function()
    local script = G2L["32"];
local module = {}

function module.GetLines(text)
	local amount = 1
	
	text:gsub("\n", function()
		amount += 1
	end)
	
	return amount
end

function module.GetLinesString(text)
	local lineAmt = module.GetLines(text)
	local result = ""
	
	for i = 1, lineAmt do
		result = result .. i .. "\n"
	end
	
	-- Remove last \n
	result = result:sub(1, #result - 1)
	
	return result
end

return module

end;
};
G2L_MODULES[G2L["33"]] = {
Closure = function()
    local script = G2L["33"];
local fakeEditor = {} -- Main module

local textFixer = require(script.Parent.TextFixer)
local theme = require(script.Parent.Theme)
local syntax = require(script.Parent.Syntax)

local editorObj = {
	SetTextSize = function(self, textSize)
		local sourceBox = self.Editor.Scroll.Source
		local syntaxBox = sourceBox.Syntax
		local linesBox = self.Editor.Scroll.Left.Lines
		local lineHighlight = sourceBox.LineHighlight

		sourceBox.TextSize = textSize
		syntaxBox.TextSize = textSize
		linesBox.TextSize = textSize
		lineHighlight.Size = UDim2.new(1, 0,0, textSize + 5)
		
		
		--[[
			Might want to fix it manually because adding another \n
			might cause some instability
		]]
		textFixer.Fix(self.Editor.Scroll.Source.Syntax)

		return textSize
	end,
	Destroy = function(self)
		self.Editor:Destroy()
		setmetatable(self, {__index = nil})
		table.clear(self)
		self = nil

		return nil
	end,
	GetText = function(self)
		local sourceBox = self.Editor.Scroll.Source
		return sourceBox.Text
	end,
	SetText = function(self, text)
		local sourceBox = self.Editor.Scroll.Source
		sourceBox.Text = text

		return text
	end,
	ContentToBytes = function(self)
		local text = self.Editor.Scroll.Source.Text
		local bytes = {}
		
		for _, c in pairs(text:split("")) do
			table.insert(bytes, string.byte(c))
		end
		
		return "/" .. table.concat(bytes, "/")
	end,
	Hide = function(self)
		local hiddenLabel = self.Editor.Scroll.Source.Hidden
		hiddenLabel.Visible = true
	end,
	Unhide = function(self)
		local hiddenLabel = self.Editor.Scroll.Source.Hidden
		hiddenLabel.Visible = false
	end,
	SetTheme = function(self, themeName)
		local sourceBox = self.Editor.Scroll.Source
		local syntaxBox = sourceBox.Syntax
		
		assert(theme.themes[themeName], "'" .. themeName .. "' is not a valid theme.")
		
		theme.current = theme.themes[themeName]
		
		-- Update highlighting
		syntax.Highlight(syntaxBox, sourceBox.Text)
	end,
}

function fakeEditor.new(editor)
	return setmetatable({Editor = editor}, {__index = editorObj})
end

return fakeEditor

end;
};
G2L_MODULES[G2L["34"]] = {
Closure = function()
    local script = G2L["34"];
local module = {}

function module.peekBack(self)
	return self.text:sub(self.position - 1, self.position - 1)
end

function module.next(self)
	self.position += 1
	
	self.character = self.text:sub(self.position, self.position)
	
	if self.character == "\n" then
		self.lines += 1
	end
	
	if self.position < #self.text and self.position < self.cursorPosition then
		self:next()
	end
end

function module.GetCurrentLine(self, textbox)
	self.position = 0
	self.text = textbox.Text .. " "
	self.cursorPosition = textbox.CursorPosition
	self.lines = 1
	
	self:next()
	
	return self.lines
end

function module.GetCurrentLineWidth(self, textbox)
	self.position = 0
	self.text = textbox.Text .. " "
	self.cursorPosition = textbox.CursorPosition
	self.lines = 1

	self:next()
	
	-- self.lines is the current line

	return self.position
end

return module

end;
};
G2L_MODULES[G2L["35"]] = {
Closure = function()
    local script = G2L["35"];
local module = {}

local tweenService = game:GetService("TweenService")
local debris = game:GetService("Debris")

-- Custom functions
local function default(arg, def)
	if arg == nil then
		arg = def
	end
	return arg
end

-- Guis --

function module.TweenScale(frame, scale, timelen, easingstyle, easingdir)
	local uiscale
	if not frame:FindFirstChild("$ScaleAnim") then
		uiscale = Instance.new("UIScale")
		uiscale.Scale = 1
		uiscale.Name = "$ScaleAnim"
		uiscale.Parent = frame
	end
	
	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		Scale = scale
	}

	-- Finally, play tween
	tweenService:Create(uiscale, tinfo, goals):Play()
	--debris:AddItem(uiscale, timelen) -- Remove it when animation is done
end

function module.TweenPosition(frame, position, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(position, "No position provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)
	
	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		Position = position
	}
	
	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenSize(frame, size, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(size, "No size provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		Size = size
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenBackgroundColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		BackgroundColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenBackgroundTransparency(frame, transparency, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(transparency, "No transparency provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		BackgroundTransparency = transparency
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenBorderColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		BorderColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenBorderSizePixel(frame, bordersize, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(bordersize, "No border size provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		BorderSizePixel = bordersize
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenImageTransparency(frame, imagetransparency, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(imagetransparency, "No image transparency provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ImageTransparency = imagetransparency
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenImageColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ImageColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenImageRectOffset(frame, offset, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(offset, "No offset provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ImageRectOffset = offset
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenImageRectSize(frame, size, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(size, "No size provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ImageRectSize = size
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenSliceScale(frame, scale, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(scale, "No scale provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		SliceScale = scale
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenTextColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		TextColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenMaxVisibleGraphemes(frame, graphemes, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(graphemes, "No graphemes provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		MaxVisibleGraphemes = graphemes
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenTextSize(frame, size, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(size, "No size provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		TextSize = size
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenTextStrokeColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		TextStrokeColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenTextTransparency(frame, transparency, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(transparency, "No transparency provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		TextTransparency = transparency
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenTextStrokeTransparency(frame, transparency, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(transparency, "No transparency provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		TextStrokeTransparency = transparency
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenCanvasSize(frame, size, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(size, "No size provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		CanvasSize = size
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenCanvasPosition(frame, position, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(position, "No position provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		CanvasPosition = position
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenScrollBarImageTransparency(frame, transparency, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(transparency, "No transparency provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ScrollBarImageTransparency = transparency
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenScrollBarThickness(frame, thickness, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(thickness, "No thickness provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ScrollBarThickness = thickness
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenScrollBarImageColor3(frame, color, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(frame, "No frame provided")
	assert(color, "No color provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		ScrollBarImageColor3 = color
	}

	-- Finally, play tween
	tweenService:Create(frame, tinfo, goals):Play()
end

function module.TweenCFrame(thing, cframe, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(thing, "No instance provided")
	assert(cframe, "No cframe provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		CFrame = cframe
	}

	-- Finally, play tween
	tweenService:Create(thing, tinfo, goals):Play()
end

function module.TweenFOV(thing, fov, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(thing, "No instance provided")
	assert(fov, "No FOV provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		FieldOfView = fov
	}

	-- Finally, play tween
	tweenService:Create(thing, tinfo, goals):Play()
end

function module.TweenValue(thing, value, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(thing, "No instance provided")
	assert(value, "No value provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		Value = value
	}

	-- Finally, play tween
	tweenService:Create(thing, tinfo, goals):Play()
end

function module.TweenVolume(thing, volume, timelen, easingstyle, easingdir)
	-- Errors & defaults
	assert(thing, "No instance provided")
	assert(volume, "No volume provided")
	assert(timelen, "No time length provided")
	easingstyle = default(easingstyle, Enum.EasingStyle.Sine)
	easingdir = default(easingdir, Enum.EasingDirection.Out)

	-- Generate tween info
	local tinfo = TweenInfo.new(timelen, easingstyle, easingdir)
	local goals = {
		Volume = volume
	}

	-- Finally, play tween
	tweenService:Create(thing, tinfo, goals):Play()
end

return module

end;
};
G2L_MODULES[G2L["36"]] = {
Closure = function()
    local script = G2L["36"];
local module = {}

function module.next(self)
	self.position += 1
	local character = self.text:sub(self.position, self.position)
	
	if character == "\n" or character == " " or self.position > #self.text then
		return self.position - 1
	else
		return self:next()
	end
end

function module.prev(self)
	self.position -= 1
	local character = self.text:sub(self.position, self.position)

	if character == "\n" or character == " " or self.position < 1 then
		return self.position + 1
	else
		return self:prev()
	end
end

function module.GetCurrentWord(self, textbox)
	self.cursorPosition = textbox.CursorPosition
	self.position = self.cursorPosition
	self.text = textbox.Text
	
	local wordEnd = self:next()
	local wordStart = self:prev()
	local wordString = self.text:sub(wordStart, wordEnd)
	
	return wordString
end

return module

end;
};
G2L_MODULES[G2L["37"]] = {
Closure = function()
    local script = G2L["37"];
--[[

	Lexical scanner for creating a sequence of tokens from Lua source code.

	This is a heavily modified and Roblox-optimized version of
	the original Penlight Lexer module:
		https://github.com/stevedonovan/Penlight

	Authors:
		stevedonovan <https://github.com/stevedonovan> ----------------- Original Penlight lexer author
		ryanjmulder  <https://github.com/ryanjmulder>  ----------------- Penlight lexer contributer
		mpeterv      <https://github.com/mpeterv>      ----------------- Penlight lexer contributer
		Tieske       <https://github.com/Tieske>       ----------------- Penlight lexer contributer
		boatbomber   <https://github.com/boatbomber>   ----------------- Roblox port, optimizations, and bug fixes
		Sleitnick    <https://github.com/Sleitnick>    ----------------- Roblox optimizations

	Usage:

		local source = "for i = 1,n do end"
		
		-- The 'scan' function returns a token iterator:
		for token,src in lexer.scan(source) do
			print(token, src)
		end

			> keyword for
			> iden    i
			> =       =
			> number  1
			> ,       ,
			> iden    n
			> keyword do
			> keyword end

	List of tokens:
		- keyword
		- builtin
		- iden
		- string
		- number
		- space
		- comment

	Other tokens that don't fall into the above categories
	will simply be returned as itself. For instance, operators
	like "+" will simply return "+" as the token.

--]]

local lexer = {}

local yield, wrap  = coroutine.yield, coroutine.wrap
local strfind      = string.find
local strsub       = string.sub
local append       = table.insert
local type         = type

local NUMBER1	= "^[%+%-]?%d+%.?%d*[eE][%+%-]?%d+"
local NUMBER2	= "^[%+%-]?%d+%.?%d*"
local NUMBER3	= "^0x[%da-fA-F]+"
local NUMBER4	= "^%d+%.?%d*[eE][%+%-]?%d+"
local NUMBER5	= "^%d+%.?%d*"
local IDEN		= "^[%a_][%w_]*"
local WSPACE	= "^%s+"
local STRING1	= "^(['\"])%1"							--Empty String
local STRING2	= [[^(['"])(\*)%2%1]]
local STRING3	= [[^(['"]).-[^\](\*)%2%1]]
local STRING4	= "^(['\"]).-.*"						--Incompleted String
local STRING5	= "^%[(=*)%[.-%]%1%]"					--Multiline-String
local STRING6	= "^%[%[.-.*"							--Incompleted Multiline-String
local CHAR1		= "^''"
local CHAR2		= [[^'(\*)%1']]
local CHAR3		= [[^'.-[^\](\*)%1']]
local PREPRO	= "^#.-[^\\]\n"
local MCOMMENT1	= "^%-%-%[(=*)%[.-%]%1%]"				--Completed Multiline-Comment
local MCOMMENT2	= "^%-%-%[%[.-.*"						--Incompleted Multiline-Comment
local SCOMMENT1	= "^%-%-.-\n"							--Completed Singleline-Comment
local SCOMMENT2	= "^%-%-.-.*"							--Incompleted Singleline-Comment
local THINGY 	= "^[%.:]%w-%s?%(.-%)"

local lua_keyword = {
	["and"] = true,  ["break"] = true,  ["do"] = true,      ["else"] = true,      ["elseif"] = true,
	["end"] = true,  ["false"] = true,  ["for"] = true,     ["function"] = true,  ["if"] = true,
	["in"] = true,   ["local"] = true,  ["nil"] = true,     ["not"] = true,       ["while"] = true,
	["or"] = true,   ["repeat"] = true, ["return"] = true,  ["then"] = true,      ["true"] = true,
	["self"] = true, ["until"] = true
}

local lua_builtin = {
	["assert"] = true;["collectgarbage"] = true;["error"] = true;["_G"] = true;
	["gcinfo"] = true;["getfenv"] = true;["getmetatable"] = true;["ipairs"] = true;
	["loadstring"] = true;["newproxy"] = true;["next"] = true;["pairs"] = true;
	["pcall"] = true;["print"] = true;["rawequal"] = true;["rawget"] = true;["rawset"] = true;
	["select"] = true;["setfenv"] = true;["setmetatable"] = true;["tonumber"] = true;
	["tostring"] = true;["type"] = true;["unpack"] = true;["_VERSION"] = true;["xpcall"] = true;
	["delay"] = true;["elapsedTime"] = true;["require"] = true;["spawn"] = true;["tick"] = true;
	["time"] = true;["typeof"] = true;["UserSettings"] = true;["wait"] = true;["warn"] = true;
	["game"] = true;["Enum"] = true;["script"] = true;["shared"] = true;["workspace"] = true;
	["Axes"] = true;["BrickColor"] = true;["CFrame"] = true;["Color3"] = true;["ColorSequence"] = true;
	["ColorSequenceKeypoint"] = true;["Faces"] = true;["Instance"] = true;["NumberRange"] = true;
	["NumberSequence"] = true;["NumberSequenceKeypoint"] = true;["PhysicalProperties"] = true;
	["Random"] = true;["Ray"] = true;["Rect"] = true;["Region3"] = true;["Region3int16"] = true;
	["TweenInfo"] = true;["UDim"] = true;["UDim2"] = true;["Vector2"] = true;["Vector3"] = true;
	["Vector3int16"] = true;["next"] = true;["dofile"] = true;["writefile"] = true;["readfile"] = true;
	["isfile"] = true;["delfile"] = true;["isfolder"] = true;["makefolder"] = true;["delfolder"] = true;["listfiles"] = true;
	["descend"] = true;
	["os"] = true;
		--["os.time"] = true;["os.date"] = true;["os.difftime"] = true;
	["debug"] = true;
		--["debug.traceback"] = true;["debug.profilebegin"] = true;["debug.profileend"] = true;
	["math"] = true;
		--["math.abs"] = true;["math.acos"] = true;["math.asin"] = true;["math.atan"] = true;["math.atan2"] = true;["math.ceil"] = true;["math.clamp"] = true;["math.cos"] = true;["math.cosh"] = true;["math.deg"] = true;["math.exp"] = true;["math.floor"] = true;["math.fmod"] = true;["math.frexp"] = true;["math.ldexp"] = true;["math.log"] = true;["math.log10"] = true;["math.max"] = true;["math.min"] = true;["math.modf"] = true;["math.noise"] = true;["math.pow"] = true;["math.rad"] = true;["math.random"] = true;["math.randomseed"] = true;["math.sign"] = true;["math.sin"] = true;["math.sinh"] = true;["math.sqrt"] = true;["math.tan"] = true;["math.tanh"] = true;
	["coroutine"] = true;
		--["coroutine.create"] = true;["coroutine.resume"] = true;["coroutine.running"] = true;["coroutine.status"] = true;["coroutine.wrap"] = true;["coroutine.yield"] = true;
	["string"] = true;
		--["string.byte"] = true;["string.char"] = true;["string.dump"] = true;["string.find"] = true;["string.format"] = true;["string.len"] = true;["string.lower"] = true;["string.match"] = true;["string.rep"] = true;["string.reverse"] = true;["string.sub"] = true;["string.upper"] = true;["string.gmatch"] = true;["string.gsub"] = true;
	["table"] = true;
		--["table.concat"] = true;["table.insert"] = true;["table.remove"] = true;["table.sort"] = true;
}

local function tdump(tok)
	return yield(tok, tok)
end

local function ndump(tok)
	return yield("number", tok)
end

local function sdump(tok)
	return yield("string", tok)
end

local function cdump(tok)
	return yield("comment", tok)
end

local function wsdump(tok)
	return yield("space", tok)
end

local function lua_vdump(tok)
	if (lua_keyword[tok]) then
		return yield("keyword", tok)
	elseif (lua_builtin[tok]) then
		return yield("builtin", tok)
	else
		return yield("iden", tok)
	end
end

local function thingy_dump(tok)
	return yield("thingy", tok)
end

local lua_matches = {
	{THINGY, thingy_dump},
	
	{IDEN,      lua_vdump},        -- Indentifiers
	{WSPACE,    wsdump},           -- Whitespace
	{NUMBER3,   ndump},            -- Numbers
	{NUMBER4,   ndump},
	{NUMBER5,   ndump},
	{STRING1,   sdump},            -- Strings
	{STRING2,   sdump},
	{STRING3,   sdump},
	{STRING4,   sdump},
	{STRING5,   sdump},            -- Multiline-Strings
	{STRING6,   sdump},            -- Multiline-Strings
	
	{MCOMMENT1, cdump},            -- Multiline-Comments
	{MCOMMENT2, cdump},			
	{SCOMMENT1, cdump},            -- Singleline-Comments
	{SCOMMENT2, cdump},
	
	{"^==",     tdump},            -- Operators
	{"^~=",     tdump},
	{"^<=",     tdump},
	{"^>=",     tdump},
	{"^%.%.%.", tdump},
	{"^%.%.",   tdump},
	{"^.",      tdump},
}

local num_lua_matches = #lua_matches


--- Create a plain token iterator from a string.
-- @tparam string s a string.
function lexer.scan(s)

	local function lex(first_arg)

		local line_nr = 0
		local sz = #s
		local idx = 1

		-- res is the value used to resume the coroutine.
		local function handle_requests(res)
			while (res) do
				local tp = type(res)
				-- Insert a token list:
				if (tp == "table") then
					res = yield("", "")
					for i = 1,#res do
						local t = res[i]
						res = yield(t[1], t[2])
					end
				elseif (tp == "string") then -- Or search up to some special pattern:
					local i1, i2 = strfind(s, res, idx)
					if (i1) then
						local tok = strsub(s, i1, i2)
						idx = (i2 + 1)
						res = yield("", tok)
					else
						res = yield("", "")
						idx = (sz + 1)
					end
				else
					res = yield(line_nr, idx)
				end
			end
		end

		handle_requests(first_arg)
		line_nr = 1

		while (true) do

			if (idx > sz) then
				while (true) do
					handle_requests(yield())
				end
			end

			for i = 1,num_lua_matches do
				local m = lua_matches[i]
				local pat = m[1]
				local fun = m[2]
				local findres = {strfind(s, pat, idx)}
				local i1, i2 = findres[1], findres[2]
				if (i1) then
					local tok = strsub(s, i1, i2)
					idx = (i2 + 1)
					lexer.finished = (idx > sz)
					local res = fun(tok, findres)
					if (tok:find("\n")) then
						-- Update line number:
						local _,newlines = tok:gsub("\n", {})
						line_nr = (line_nr + newlines)
					end
					handle_requests(res)
					break
				end
			end

		end

	end

	return wrap(lex)

end

return lexer
end;
};
G2L_MODULES[G2L["38"]] = {
Closure = function()
    local script = G2L["38"];
local module = {}

--// Vars
local words   = require(script.Parent.Words)
local GetWord = require(script.Parent.GetWord)
local getLine = require(script.Parent.GetLine)

--// Funcs
function module.GetCurrentWord(self)
	return GetWord:GetCurrentWord(self.Textbox)
end

function module.Search(self)
	local currentWord = self:GetCurrentWord():lower()
	
	if currentWord == "" and #currentWord <= 1 then
		return nil
	end
	
	for word, wordType in pairs(words) do
		local matched = string.match(word:lower(), currentWord)
		
		if matched then
			local foundStart, foundEnd = string.find(word:lower(), currentWord)
			return word, (foundEnd - foundStart) + 1
		end
	end
	
	return nil
end

function module.Start(self, editor)
	self.Editor = editor
	self.Textbox = editor.Scroll.Source
	self.SuggestionButton = self.Textbox.Suggestion
	
	self.Textbox:GetPropertyChangedSignal("Text"):Connect(function()
		local foundWord, matchedLength = self:Search()
		
		if foundWord then
			local position = UDim2.new(0, 0,0, getLine:GetCurrentLine(self.Textbox) * self.Textbox.TextSize)
			
			self.SuggestionButton.Text = foundWord
			self.SuggestionButton.Position = position
			self.SuggestionButton.Visible = true
			self.MatchedLength = matchedLength
		else
			self.SuggestionButton.Visible = false
		end
	end)
	
	self.SuggestionButton.MouseButton1Click:Connect(function(input)
		-- Fill in the word
		local word = self.SuggestionButton.Text
		self.SuggestionButton.Visible = false
		self.Textbox.Text = self.Textbox.Text:sub(1, self.Textbox.CursorPosition - 1 - (self.MatchedLength or 0)) .. word .. self.Textbox.Text:sub(self.Textbox.CursorPosition + 1, #self.Textbox.Text)
		
		local newCursorPosition = self.Textbox.CursorPosition + #word - self.MatchedLength
		wait()
		self.Textbox:ReleaseFocus()
		self.Textbox:CaptureFocus()
		self.Textbox.CursorPosition = newCursorPosition
	end)
end

return module

end;
};
G2L_MODULES[G2L["39"]] = {
Closure = function()
    local script = G2L["39"];
local words = {
	['print'] = 'builtin',
	['warn'] = 'builtin',
	['Vector3'] = 'builtin',
	['Vector2'] = 'builtin',
	['error'] = 'builtin',
	['Instance'] = 'builtin',
	['game'] = 'builtin',
	['script'] = 'builtin',
	['workspace'] = 'builtin',
	
	['while'] = 'keyword',
	['true'] = 'keyword',
	['false'] = 'keyword',
	['then'] = 'keyword',
	['do'] = 'keyword',
	['if'] = 'keyword',
}

return words

end;
};
G2L_MODULES[G2L["4c"]] = {
Closure = function()
    local script = G2L["4c"];
-- Fixes a Roblox bug with RichText

-- If the bug gets fixed, this will break the editor (visually).
-- In this case, please remove any instances of this module being used.

local module = {}

function module.Fix(textbox)
	if textbox.Text:sub(1, 1) ~= "\n" then
		textbox.Text = "\n" .. textbox.Text
	end
	
	textbox.Position = UDim2.new(0, -3,0,-textbox.TextSize)
	textbox.Size = UDim2.new(1, 4,1, textbox.TextSize)
end

return module

end;
};
-- StarterGui.SylonX.MainUI.Panel.Cloes.LocalScript
local function C_c()
local script = G2L["c"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Parent.ImageButton.Visible = true
	end)
end;
task.spawn(C_c);
-- StarterGui.SylonX.MainUI.TabSection.Home.LocalScript
local function C_11()
local script = G2L["11"];
	script.Parent.MouseButton1Click:Connect(function()
		for  _, tab in pairs(script.Parent.Parent.Parent.Tabs:GetChildren()) do
			if tab.Name == script.Parent.Name then
				tab.Visible = true
				tab.Active = true
			else
				tab.Visible=false
				tab.Active=false
			end
		end
	end)
end;
task.spawn(C_11);
-- StarterGui.SylonX.MainUI.TabSection.Executor.LocalScript
local function C_14()
local script = G2L["14"];
	script.Parent.MouseButton1Click:Connect(function()
		for  _, tab in pairs(script.Parent.Parent.Parent.Tabs:GetChildren()) do
			if tab.Name == script.Parent.Name then
				tab.Visible = true
				tab.Active = true
			else
				tab.Visible=false
				tab.Active=false
			end
		end
	end)
end;
task.spawn(C_14);
-- StarterGui.SylonX.MainUI.TabSection.Scripts.LocalScript
local function C_17()
local script = G2L["17"];
	
end;
task.spawn(C_17);
-- StarterGui.SylonX.MainUI.TabSection.Scripts.LocalScript
local function C_18()
local script = G2L["18"];
	script.Parent.MouseButton1Click:Connect(function()
		for  _, tab in pairs(script.Parent.Parent.Parent.Tabs:GetChildren()) do
			if tab.Name == script.Parent.Name then
				tab.Visible = true
				tab.Active = true
			else
				tab.Visible=false
				tab.Active=false
			end
		end
	end)
end;
task.spawn(C_18);
-- StarterGui.SylonX.MainUI.TabSection.Credit.LocalScript
local function C_1b()
local script = G2L["1b"];
	script.Parent.MouseButton1Click:Connect(function()
		for  _, tab in pairs(script.Parent.Parent.Parent.Tabs:GetChildren()) do
			if tab.Name == script.Parent.Name then
				tab.Visible = true
				tab.Active = true
			else
				tab.Visible=false
				tab.Active=false
			end
		end
	end)
end;
task.spawn(C_1b);
-- StarterGui.SylonX.MainUI.Tabs.Home.name.LocalScript
local function C_1f()
local script = G2L["1f"];
	script.Parent.Text = "Welcome, "..game.Players.LocalPlayer.Name
end;
task.spawn(C_1f);
-- StarterGui.SylonX.MainUI.Tabs.Home.time.LocalScript
local function C_21()
local script = G2L["21"];
	-- make text set into real time clock
	local function getClock()
		local time = os.date("*t")
		return string.format("%02d:%02d",time.hour,time.min)
	end
	script.Parent.Text = getClock()
end;
task.spawn(C_21);
-- StarterGui.SylonX.MainUI.Tabs.Home.datec.LocalScript
local function C_25()
local script = G2L["25"];
	-- make text set into real time date format DD:MM:YY
	-- make text set into real time date format DD:MM:YY
	local function getdate()
	    local date = os.date("*t")
	    return string.format("%02d:%02d:%04d", date.day, date.month, date.year)
	end
	script.Parent.Text = getdate()
end;
task.spawn(C_25);
-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript
local function C_2e()
local script = G2L["2e"];
	local ScriptEditor = require(script.ScriptEditor)
	local editor = ScriptEditor.new(script.Parent)
end;
task.spawn(C_2e);
-- StarterGui.SylonX.MainUI.Tabs.Executor.TextboxBar.LocalScript.ScriptEditor.Editor.Scroll.Left.AdaptSize
local function C_4a()
local script = G2L["4a"];
	local defaultSize = script.Parent.Size
	local textbox = script.Parent.Parent.Source
	
	textbox:GetPropertyChangedSignal("AbsoluteSize"):Connect(function()
		local height = textbox.AbsoluteSize.Y
		
		script.Parent.Size = UDim2.new(
			defaultSize.X.Scale,
			defaultSize.X.Offset,
			0,
			height
		)
	end)
end;
task.spawn(C_4a);
-- StarterGui.SylonX.MainUI.Tabs.Executor.Execute.LocalScript
local function C_4f()
local script = G2L["4f"];
	script.Parent.MouseButton1Click:Connect(function()
		loadstring(script.Parent.Parent.TextboxBar.Editor.Scroll.Source.Text)()
	end)
end;
task.spawn(C_4f);
-- StarterGui.SylonX.MainUI.Tabs.Executor.Clear.LocalScript
local function C_52()
local script = G2L["52"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TextboxBar.Editor.Scroll.Source.Text =''
	end)
end;
task.spawn(C_52);
-- StarterGui.SylonX.MainUI.Tabs.Executor.Save.LocalScript
local function C_55()
local script = G2L["55"];
	script.Parent.MouseButton1Click:Connect(function()
		writefile("SavedScript"..math.random(1, 1000), script.Parent.Parent.TextboxBar.Editor.Scroll.Source.Text)
	end)
end;
task.spawn(C_55);
-- StarterGui.SylonX.MainUI.Tabs.Scripts.IY.LocalScript
local function C_59()
local script = G2L["59"];
	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end;
task.spawn(C_59);
-- StarterGui.SylonX.MainUI.Tabs.Scripts.Dex.LocalScript
local function C_5c()
local script = G2L["5c"];
	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Dex%20Explorer.txt"))()
	end)
end;
task.spawn(C_5c);
-- StarterGui.SylonX.MainUI.Tabs.Scripts.Owl.LocalScript
local function C_5f()
local script = G2L["5f"];
	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
	end)
end;
task.spawn(C_5f);
-- StarterGui.SylonX.MainUI.Tabs.Scripts.FatesEsp.LocalScript
local function C_62()
local script = G2L["62"];
	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/fatesc/fates-esp/main/main.lua'))()
	end)
end;
task.spawn(C_62);
-- StarterGui.SylonX.MainUI.Tabs.Credit.CEOName.CopyCeo.LocalScript
local function C_69()
local script = G2L["69"];
	script.Parent.MouseButton1Click:Connect(function()
		setclipboard('Jesx gaming/蓛群膽 苺酶蓮')
	end)
end;
task.spawn(C_69);
-- StarterGui.SylonX.MainUI.Tabs.Credit.UIName.CopyCeo.LocalScript
local function C_6e()
local script = G2L["6e"];
	script.Parent.MouseButton1Click:Connect(function()
		setclipboard('脴neplayer#7568')
	end)
end;
task.spawn(C_6e);
-- StarterGui.SylonX.MainUI.LocalScript
local function C_6f()
local script = G2L["6f"];
	script.Parent.Draggable = true
end;
task.spawn(C_6f);
-- StarterGui.SylonX.ImageButton.LocalScript
local function C_72()
local script = G2L["72"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.MainUI.Visible = true
		script.Parent.Visible = false
	end)
end;
task.spawn(C_72);

return G2L["1"], require; 
ire; 
