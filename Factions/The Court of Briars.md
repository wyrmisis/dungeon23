Fae magicks bind the souls of the Citadel's last inhabitants to this ruin. Led by the Lady-Commander of Briarhedge Hall, 

```statblock
name: Thorned Bones

description: "The thorny animated remains of various living things, amalgamated into roughly humanoid-sized and -shaped beings through habitation by one of the Lady-Commander's snared souls. They are nodes in the Court's hivemind, but are incapable of independent thought. They follow simple commands, such as \"guard\" or \"patrol\". **Note**: the stats given here are for the bony vessel, not for the inhabiting soul."

ac: 7
hd: 1+1
thac0: 18
saves: [12, 13, 14, 15, 16]
movement: 120'
morale: 9
xp: 23

traits:
    - name: Undead
      desc: "Cannot be affected by a bunch of stuff, invisible to infravision"
    - name: Skeletal
      desc: "Resistant to piercing weapons, vulnerable to bludgeoning weapons."
    - name: Vessel
      desc: "Can be temporarily inhabited by a wandering soul. Destroying it releases the soul."
      
attackRoutine: "1x thorned fists or by weapon"
attacks:
    - name: Thorned fists
      desc: "1d6"
```

```statblock
name: Briarsguard

description: "A symbiotic union of bone and plant, these vessels bear a passing resemblance to smaller shambling mounds. These skeletal vessels are wrapped in thin, fibrous plants that form a lace similar to muscle tissue. This lace can be moved around the Briarsguard at will, allowing it to bear weapons and shields or attack with both of its vine-wrapped fists"

ac: 5
hd: 4
thac0: 16
saves: [10, 11, 12, 13, 14]
movement: 90'
morale: 9
xp: 125

traits:
    - name: Undead
      desc: "Cannot be affected by a bunch of stuff, invisible to infravision"
    - name: Bone and Plant
      desc: "Resistant to piercing weapons, vulnerable to slashing weapons."
    - name: Vessel
      desc: "Can be temporarily inhabited by a wandering soul. Destroying it releases the soul."
      
attackRoutine: "2x vine-wrapped fists or by weapon"
attacks:
    - name: Vine-wrapped fist
      desc: "2d4"
```