import random

print("""
A Lv. 90 Charizard (Fire/Flying, Sp. Atk: 205) attacks a Lv. 95
Feraligatr (Water, Sp. Def: 188) with Fire Blast, a Fire-type move
with a Power of 110 and gains a same-type attack bonus.. It hits
the target normally but deals a not very effective damage. The
weather on the field is normal. Given the following conditions,
determine how much damage Charizards attack will deal.
""")

print ("""
Level : 90
Pokemon Name : Charizard
Type: Fire/Flying
Sp. Attack : 205
Power : Fire Blast 110

Battle with:

Level : 95
Pokemon name: Feraligator
Type : Water
Sp. Defense : 188

""")

#modifier
target = 1
weather = 1
badge = 1
crit = random.randint(1,2)
randomm = round(random.uniform(0.85 , 1.00),2)
stab = 1
type = round(random.uniform(0.25 , 0.50),2)
opt = random.randint(0,1)
if opt ==0:
    burn=0.5
elif opt ==1:
    burn=1
other = 1

modifier = target * weather * badge * crit * randomm * stab * type * burn * other
damage =round(((((((2*90)/5)+2) * 110 * (205/188))/50)+2),2) 
fdamage= damage * modifier

print(f"""
MODIFIERS:

target :    {target}
weather :   {weather}
badge :     {badge}
crit :      {crit}
random :    {randomm}
stab :      {stab}
type :      {type}
burn :      {burn}
other :     {other}

total damage :      {damage}
total modifier :    {modifier}
Your final damage:  {round((fdamage),2)}
""")