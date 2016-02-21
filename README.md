# DragonCodePack
<html>
<head>

///Title: Knights & Dragons

---------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------

//Object: Bulky_Knight

/Create Event

Player = 1
Hp = 100;
Atk=18
Def=22
SPD=4
JUP=12.5 //Minimum is 10
friction=0
Hurt=false
Launch=false
invincible=false

/Step Event

gravity=0.7
gravity_direction=270

/?/What does it do?

if vspeed > 10
{                          
vspeed=10
}

/Collision Event with Wall
direction=directtion
maximum=12
vspeed = 0
</head>

<body>
<p>//Object:Wall
/Create Event
solid = true</p>
</body>
</html>
