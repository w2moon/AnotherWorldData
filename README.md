

attack:
physic str,con
air str,int,dex,cha
earth str,int,dex,cha
water str,int,dex,cha
fire str,int,dex,cha
life str,int,dex,cha
death str,int,dex,cha
-------------130*3*(buffernum+1)
1hit 6*4+2 one,6*4+2 all,6*4+2 hero 78
2hit 6*4+2 random 26
6hit 6*4+2 random 26

defense:
shield
immune
shieldstack
shieldsuck
-----8*2*4*(buffernum+1)*3

heal:
all
one
-----2*3*(buffernum+1)

buffer:
1stack
5stack

control:
silence can not use skill
fear can not act,short
sleep can not act,long
confusion
mindcontrol

damage:

property:
constitution
strength
intelligence
dexterity
charisma
---------65*3
add property 5initself,5initall,5attack,5defense,5heal 25
sub property 5initself,5initall,5attack,5defense,5heal 25
suck property 5all,5attack,5defense 15



battlefield:
wind
sandstorm
rain
burning
sunny
night
----6

support:
purge: one,all
dispel:one,all

trait:
crit
dodge
parry
guard
counter
hemophagia
assist_attack
assist_heal
instant_kill