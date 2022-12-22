```statblock
name: Test Creature

description: "A test description for this creature, with *markdown* support?"

ac: 5
hd: 5
thac0: 17
saves: [12, 13, 14, 15, 16]

traits:
    - name: Undead
      desc: "Cannot be affected by a bunch of stuff, invisible to infravision"
      
attackRoutine: "3x Test or 1x Trial"
attacks:
    - name: Test Name
      desc: "1d4"
    - name: Trial
      desc: "2d6"
```
