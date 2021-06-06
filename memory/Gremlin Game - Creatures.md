# Gremlin Game - Creatures



## Giants
Giants create things people want, solitary 

### objective
- Work: create Works in their workshop 
- Stay Home: minimize time spent outside Home 
- Slumber: 

### traits
- live in large Homes

### abilities
- (melee) Crush creature 
- create Works 
- Slumber 
  - lasts 8 hours 

### senses 
- sight 
- hearing

## Gremlins 
Gremlins steal things but can't cause any direct harm 

### objective 
- maximize amount of Gold in the Gremlin Layer
- maximize amount of works in the Gremlin Layer 
- survive

### abilities
- build Gremlin Layer Openings 
- use Gremlin Layer Openings to travel between the normal layer and the Gremlin Layer
- move (fast)

### senses
- sight 
- hearing -- can hear from Gremlin Layer 
- position and identity of all other Gremlins

## Devils 
### objective 
- minimize the highest utility score for other creatures? (need to figure out a way to normalize across creatures)

one way to normalize would be to simulate a parallel world without devils, and then use the utility scores from that to define "100% utility" for each creature. and then devils try to minimize the highest %. 

### abilities
- make any noise 
- become invisible 
- (melee) distract a creature, causing it to do nothing for 1 tick 

### senses 
- omniscience within a certain range 
  - includes "utility-sense" -- can see utility scores for each creature