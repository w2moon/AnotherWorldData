/////////////////////
pro:
     con->defense
     int->magic
     str->physic

race:
     human physic,fire,water,air,earth,death,life  ,junior
     elf life,water,air master
     dwarf fire,earth,life master
     undead death,fire,air master
     dragon fire,water,air,earth master
     orc physic,earth master
     god fire,water,air,earth,death,life master
     demon fire,water,air,earth,death,life master

physic damage can be add magic effect by weapons.
armor can defense magic or physic damage,or immue to some magic.
trinket can enhance player's trait,got by achieve achievement.

all normal attack is physic

physic:1,all,multi,hero.defense.add physic buff bleed.

magic:every magic have attack 1,all,multi,hero.defense,minor damage,immue damage.add buff.
     fire->add burn buff,add crit buff
     water->add purge buff,add duplicate
     air->lighting damage,add sleep buff.
     earth->big one hit damage.. 
     life->add heal buff,add energy,add pro add buff,special damage to undead
     death->switch buff,give buff to other,add fear buff,add confusion buff,add sub pro buff,special heal to undead

battlefield:
sandstorm all be damaged each turn
rain inc water,dec fire small medium big :10 30 50 30level 10-no cost levelup + 5 15% 35-cost money levelup + 10 45% 75-cost huge,damage reduce max 50%
burning inc fire,dec water
sunny inc life
night inc death


attack:
physic str,con
air str,int,dex,cha    ->speed
earth str,int,dex,cha  ->defense
water str,int,dex,cha  ->control
fire str,int,dex,cha   ->fire
life str,int,dex,cha   ->heal
death str,int,dex,cha  ->rebirth
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