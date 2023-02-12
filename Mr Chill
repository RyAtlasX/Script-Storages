--[[
   Binds:
   z: Default (Chill)
   x: Floating
   c: Glitch (Not Chill)
   v: Sprint Toggle
]]


clickfling = true -- set this to false if u dont want click fling or use torso fling



function rmesh(a)

if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end

old=game.Players.LocalPlayer.Character

game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]

for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do

if v:IsA('Mesh') or v:IsA('SpecialMesh') then

v:Remove()

end

end

for i = 1 , 2 do

game.Players.LocalPlayer.Character=old

end

end



a=game.Players.LocalPlayer b=game.Players.LocalPlayer.Character c={}d=table.insert e=false for D,E in next,game:GetService("Players").LocalPlayer.Character:GetDescendants()do if E:IsA("BasePart")then d(c,game:GetService("RunService").Heartbeat:connect(function()pcall(function()E.Velocity=Vector3.new(-30,0,0)sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge)sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999)game.Players.LocalPlayer.ReplicationFocus=workspace end)end))end end function f(D,E,F)game.StarterGui:SetCore("SendNotification",{Title=D;Text=E;Duration=F or 5;})end local x=game:GetService("RunService")g=Instance.new('Folder',b)g.Name='CWExtra'b.Archivable=true local y=b:Clone()y.Name='NexoPD'for D,E in next,y:GetDescendants()do if E:IsA('BasePart')or E:IsA('Decal')then E.Transparency=1 end end h=5.65 a.Character=nil a.Character=b b.Humanoid.AutoRotate=false b.Humanoid.WalkSpeed=0 b.Humanoid.JumpPower=0 b.Torso.Anchored=true f('Nexo','Reanimating...\nPlease wait '..h..' seconds.')wait(h)b.Torso.Anchored=false f('Nexo','Reanimated..')b.Humanoid.Health=0 y.Animate.Disabled=true y.Parent=g y.HumanoidRootPart.CFrame=b.HumanoidRootPart.CFrame*CFrame.new(0,5,0)function i(D,E,F,G)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("AlignOrientation",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignOrientation.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]D.AlignOrientation.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D[D.Name].Orientation=G or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.AlignOrientation.Responsiveness=math.huge D.AlignPosition.RigidityEnabled=false D.AlignOrientation.MaxTorque=999999999 D.Massless=true end function j(D,E,F)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.Massless=true end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('Accessory')then i(E.Handle,y[E.Name].Handle)end end i(b['Head'],y['Head'])i(b['Torso'],y['Torso'])j(b['HumanoidRootPart'],y['Torso'],Vector3.new(0,0,0))i(b['Right Arm'],y['Right Arm'])i(b['Left Arm'],y['Left Arm'])i(b['Right Leg'],y['Right Leg'])i(b['Left Leg'],y['Left Leg'])k=a:GetMouse()local z=Instance.new("Part",g)z.CanCollide=false z.Transparency=1 d(c,x.RenderStepped:Connect(function()local D=workspace.CurrentCamera.CFrame.lookVector local E=y["HumanoidRootPart"]z.Position=E.Position z.CFrame=CFrame.new(z.Position,Vector3.new(D.X*10000,D.Y,D.Z*10000))end))l=false m=false n=false o=false p=false function q(D)r=Instance.new('BodyAngularVelocity',D)r.AngularVelocity=Vector3.new(9e9,9e9,9e9)r.MaxTorque=Vector3.new(9e9,9e9,9e9)end q(b.HumanoidRootPart)k=a:GetMouse()s=Instance.new('BodyPosition',b.HumanoidRootPart)s.P=9e9 s.D=9e9 s.MaxForce=Vector3.new(99999,99999,99999)local A d(c,x.Heartbeat:Connect(function()if A==true then s.Position=k.Hit.p b.HumanoidRootPart.Position=k.Hit.p else s.Position=y.Torso.Position b.HumanoidRootPart.Position=y.Torso.Position end end))local B=Instance.new("SelectionBox")B.Adornee=b.HumanoidRootPart B.LineThickness=0.02 B.Color3=Color3.fromRGB(250,0,0)B.Parent=b.HumanoidRootPart B.Name="RAINBOW"t=B if clickfling then d(c,k.Button1Down:Connect(function()A=true end))d(c,k.Button1Up:Connect(function()A=false end))end d(c,k.KeyDown:Connect(function(D)if D==' 'then p=true end if D=='w'then l=true end if D=='s'then m=true end if D=='a'then n=true end if D=='d'then o=true end end))d(c,k.KeyUp:Connect(function(D)if D==' 'then p=false end if D=='w'then l=false end if D=='s'then m=false end if D=='a'then n=false end if D=='d'then o=false end end))local function C(D,E,F)z.CFrame=z.CFrame*CFrame.new(-D,E,-F)y.Humanoid.WalkToPoint=z.Position end d(c,x.RenderStepped:Connect(function()if l==true then C(0,0,1e4)end if m==true then C(0,0,-1e4)end if n==true then C(1e4,0,0)end if o==true then C(-1e4,0,0)end if p==true then y.Humanoid.Jump=true end if l~=true and n~=true and m~=true and o~=true then y.Humanoid.WalkToPoint=y.HumanoidRootPart.Position end end))workspace.CurrentCamera.CameraSubject=y.Humanoid u=Instance.new('BindableEvent')d(c,u.Event:Connect(function()y:Destroy()e=true v=false for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then E.Anchored=true end end w=b.Humanoid:Clone()b.Humanoid:Destroy()w.Parent=b game.Players:Chat('-re')for D,E in pairs(c)do E:Disconnect()end game:GetService("StarterGui"):SetCore("ResetButtonCallback",true)u:Remove()end))game:GetService("StarterGui"):SetCore("ResetButtonCallback",u)



IT = Instance.new

CF = CFrame.new

VT = Vector3.new

RAD = math.rad

C3 = Color3.new

UD2 = UDim2.new

BRICKC = BrickColor.new

ANGLES = CFrame.Angles

EULER = CFrame.fromEulerAnglesXYZ

COS = math.cos

ACOS = math.acos

SIN = math.sin

ASIN = math.asin

ABS = math.abs

MRANDOM = math.random

FLOOR = math.floor



speed = 1

sine = 1

srv = game:GetService('RunService')



reanim = workspace.Camera.CameraSubject.Parent



function hat(h,p,c1,c0,m)

reanim[h].Handle.AccessoryWeld.Part1=reanim[p]

reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()

reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)

if m == true then

rmesh(h)

end

end



m=game.Players.LocalPlayer:GetMouse()

RJ = reanim.HumanoidRootPart.RootJoint

RS = reanim.Torso['Right Shoulder']

LS = reanim.Torso['Left Shoulder']

RH = reanim.Torso['Right Hip']

LH = reanim.Torso['Left Hip']

Root = reanim.HumanoidRootPart

NECK = reanim.Torso.Neck

NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))

NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))

LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))

LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))



-- for modes u can go in this link : https://Nexo.notxeneon15.repl.co/nexo/modes.lua



-- ^^ Don't use that it's fucking shit



local Mouse = a:GetMouse()



local CurMode = 'Default'

local ModeChanger = Mouse.KeyDown:Connect(function(key)

   if key == "z" then

       CurMode = 'Default'

   elseif key == "x" then

       CurMode = 'Floating'

   elseif key == "c" then

       CurMode = 'Glitch'

   elseif key == "v" then

       if reanim.Humanoid.WalkSpeed == 32 then

           reanim.Humanoid.WalkSpeed = 16

       else

           reanim.Humanoid.WalkSpeed = 32

       end

   end

end)



coroutine.wrap(function()

while true do -- anim changer

if HumanDied then ModeChanger:Disconnect() break end

sine = sine + speed

local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))

local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)

local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))

local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)

local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z

local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z

if lookvector > reanim.Humanoid.WalkSpeed then

lookvector = reanim.Humanoid.WalkSpeed

end

if lookvector < -reanim.Humanoid.WalkSpeed then

lookvector = -reanim.Humanoid.WalkSpeed

end

if rightvector > reanim.Humanoid.WalkSpeed then

rightvector = reanim.Humanoid.WalkSpeed

end

if rightvector < -reanim.Humanoid.WalkSpeed then

rightvector = -reanim.Humanoid.WalkSpeed

end

local lookvel = lookvector / reanim.Humanoid.WalkSpeed

local rightvel = rightvector / reanim.Humanoid.WalkSpeed

if CurMode == 'Default' then

   if reanim.Humanoid.Jump then -- jump

   --jump clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(170+-5*math.cos(sine/10)),math.rad(-15+-5*math.cos(sine/10)),math.rad(10+-5*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(170+5*math.cos(sine/10)),math.rad(15+5*math.cos(sine/10)),math.rad(-10+5*math.cos(sine/10))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+5*math.cos(sine/5)),math.rad(-15+5*math.cos(sine/5)),math.rad(10+5*math.cos(sine/10))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-5*math.cos(sine/5)),math.rad(15+-5*math.cos(sine/5)),math.rad(-10+-5*math.cos(sine/10))),.2)elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall

   --fall clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(170+-5*math.cos(sine/10)),math.rad(-15+-5*math.cos(sine/10)),math.rad(10+-5*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(170+5*math.cos(sine/10)),math.rad(15+5*math.cos(sine/10)),math.rad(-10+5*math.cos(sine/10))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+5*math.cos(sine/5)),math.rad(-15+5*math.cos(sine/5)),math.rad(10+5*math.cos(sine/10))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-5*math.cos(sine/5)),math.rad(15+-5*math.cos(sine/5)),math.rad(-10+-5*math.cos(sine/10))),.2)elseif Root.Velocity.Magnitude < 2 then -- idle

   --idle clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   elseif Root.Velocity.Magnitude < 20 then -- walk

   --walk clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-10+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-28*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-28*math.cos(sine/10)),math.rad(0+-15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28*math.cos(sine/10)),math.rad(0+-15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   elseif Root.Velocity.Magnitude > 20 then -- run

   --run clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+5*math.cos(sine/5)),math.rad(0+-3*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+38*math.cos(sine/5)),math.rad(0+15*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-38*math.cos(sine/5)),math.rad(0+15*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(10+-38*math.cos(sine/5)),math.rad(0+-15*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(10+38*math.cos(sine/5)),math.rad(0+-15*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   end

elseif CurMode == 'Floating' then

   if reanim.Humanoid.Jump then -- jump

   --jump clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+5*math.cos(sine/20)),math.rad(-15+5*math.cos(sine/20)),math.rad(36+5*math.cos(sine/20))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+-5*math.cos(sine/20)),math.rad(15+-5*math.cos(sine/20)),math.rad(-36+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+5*math.cos(sine/20)),math.rad(-32+5*math.cos(sine/20)),math.rad(13+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+-5*math.cos(sine/20)),math.rad(32+-5*math.cos(sine/20)),math.rad(-13+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall

   --fall clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+5*math.cos(sine/20)),math.rad(-15+5*math.cos(sine/20)),math.rad(36+5*math.cos(sine/20))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+-5*math.cos(sine/20)),math.rad(15+-5*math.cos(sine/20)),math.rad(-36+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+5*math.cos(sine/20)),math.rad(-32+5*math.cos(sine/20)),math.rad(13+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+-5*math.cos(sine/20)),math.rad(32+-5*math.cos(sine/20)),math.rad(-13+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.Magnitude < 2 then -- idle

   --idle clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-60+5*math.cos(sine/20)),math.rad(-15+5*math.cos(sine/20)),math.rad(36+5*math.cos(sine/20))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-60+5*math.cos(sine/20)),math.rad(15+5*math.cos(sine/20)),math.rad(-36+5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+5*math.cos(sine/20)),math.rad(-32+5*math.cos(sine/20)),math.rad(13+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+-5*math.cos(sine/20)),math.rad(32+-5*math.cos(sine/20)),math.rad(-13+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.Magnitude < 20 then -- walk

   --walk clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+5*math.cos(sine/20)),math.rad(-15+5*math.cos(sine/20)),math.rad(36+5*math.cos(sine/20))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+-5*math.cos(sine/20)),math.rad(15+-5*math.cos(sine/20)),math.rad(-36+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+5*math.cos(sine/20)),math.rad(-32+5*math.cos(sine/20)),math.rad(13+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+-5*math.cos(sine/20)),math.rad(32+-5*math.cos(sine/20)),math.rad(-13+-5*math.cos(sine/20))),.2)elseif Root.Velocity.Magnitude > 20 then -- run

   --run clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+2*math.cos(sine/10)),math.rad(0+-1*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+5*math.cos(sine/20)),math.rad(-15+5*math.cos(sine/20)),math.rad(36+5*math.cos(sine/20))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(112+-5*math.cos(sine/20)),math.rad(15+-5*math.cos(sine/20)),math.rad(-36+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+5*math.cos(sine/20)),math.rad(-32+5*math.cos(sine/20)),math.rad(13+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40+-5*math.cos(sine/20)),math.rad(32+-5*math.cos(sine/20)),math.rad(-13+-5*math.cos(sine/20))),.2)end

elseif CurMode == 'Glitch' then

   if reanim.Humanoid.Jump then -- jump

   --jump clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+15*math.cos(sine/10)),math.rad(0+-1280*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+5*math.cos(sine/10)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/5)),math.rad(0+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+5*math.cos(sine/20)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/20)),math.rad(0+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall

   --fall clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+15*math.cos(sine/10)),math.rad(0+-1280*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+5*math.cos(sine/10)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/5)),math.rad(0+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+5*math.cos(sine/20)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/20)),math.rad(0+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.Magnitude < 2 then -- idle

   --idle clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+15*math.cos(sine/10)),math.rad(0+-1280*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-78+5*math.cos(sine/10)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-78+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/5)),math.rad(0+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+5*math.cos(sine/20)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(45+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/20)),math.rad(0+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.Magnitude < 20 then -- walk

   --walk clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+15*math.cos(sine/10)),math.rad(0+-1280*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-64+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+5*math.cos(sine/10)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/5)),math.rad(0+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-25+5*math.cos(sine/20)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-25+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/20)),math.rad(0+-5*math.cos(sine/20))),.2)

   elseif Root.Velocity.Magnitude > 20 then -- run

   --run clerp here

   NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+15*math.cos(sine/10)),math.rad(0+-1280*math.cos(sine/10)),math.rad(0+15*math.cos(sine/10))),.2)

   RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),3+0.52*math.cos(sine/5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-64+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

   RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+5*math.cos(sine/10)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+0*math.cos(sine/10))),.2)

   LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.01*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/5)),math.rad(0+-5*math.cos(sine/20))),.2)

   RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-25+5*math.cos(sine/20)),math.rad(0+1280*math.cos(sine/5)),math.rad(0+5*math.cos(sine/20))),.2)

   LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.02*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-25+-5*math.cos(sine/20)),math.rad(0+-1280*math.cos(sine/20)),math.rad(0+-5*math.cos(sine/20))),.2)

   end

end

srv.RenderStepped:Wait()

end

end)()
