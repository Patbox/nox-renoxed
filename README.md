# Nox

Minecraft mob and difficulty overhaul for Fabric.

## Misc Changes

### In general..
* Strafing is faster
* Pouncing goes farther and faster
* Melee Goal checks are done more often (barely noticable)
* (Almost all) Mobs can see through walls
* Target finding is more immediate, no random delay

## Monster Changes

### All monsters..
* Do not have friendly fire 
* Projectiles phase through allies
* Are angered when ran into (relevant to neutral monsters like Endermen)
* +50% base health
* +50% base follow range

### Bow AI..
* Prefers a farther range
* Does not shoot shielding entities (you must bait it out)

### Crossbow AI..
* Charges crossbow first and foremost
* Prefers a farther range
* Does not shoot shielding entities (unless the user has piercing)
* Strafes

### Projectile AI..
* Prefers a farther range
* Strafes

### All Zombies..
* Take reduced knockback (unless they're a baby)
* Periodically pounce at their target
* Avoid and flee from the sun (if it affects them)
* Can mine blocks

### All Skeletons..
* Flee from the sun
* Can swim

### Spiders..
* Avoid the sun
* Are immune to fall damage
* Places a cobweb at the victims location upon successful attack

### Cave Spiders..
* Inherent changes from Spiders
* Instead of placing a cobweb, apply 10 seconds of Slowness II

### Creepers..
* Flee blocking entities
* Pounce at their target
* Move during ignition
* Breach walls
* Continue to ignite without line of sight
* Only continue to ignite within a 4 block radius (originally 7 blocks)

### Endermen..
* Can break walls
* Apply 10 seconds of Blindness on aggro
* Apply 10 seconds of Blindness upon successful attack
* Teleport when damaged
* Do not teleport when damaged by being on fire or magic

### Slimes..
* +150% base health
* +30% base speed
* +450% base follow range
* Spawn naturally
* Jump constantly
* Are invulnerable to fall and non-armor-piercing projectile damage
* Spawn a short-lived Poison II effect cloud on death, with a radius proportional to their size

### Witches..
* Spawn more frequently
* Use lingering potions with buffed effect clouds
* Use stronger Slowness
* Are invulnerable to magic and non-armor-piercing projectile damage
* Use better beneficial potions (stronger or longer duration)
* Do not drink when target is in close proximety (7 blocks)

### Wither Skeletons..
* Spawn naturally (in the Nether)
* Take reduced knockback
* Can spawn with a bow
* Wither Skeleton Archers: +50% damage
* Apply 4 seconds of Wither to the target when in close proximety (2 blocks)
* Wither Skeleton Skulls are fire resistant

### Blazes..
* Strafe
* Prefer a farther range
* Spawn naturally (in the Nether)
* Shoot fireballs twice as often
* Do not shoot shielding entities (you must bait it out)
* Ignite the target on fire for 4 seconds when in close proximety (2 blocks)
* Blaze Rods are fire resistant (as well as Blaze Powder)

### Ghasts..
* +150% base health
* Spawn more frequently
* Fireballs are twice as powerful
* Fireballs no longer deal 1000 damage to Ghasts (:concern:)
* Fireball cooldown is 3 times less
* Fireballs from Ghasts bypass shields
* Ghast Tears are fire resistent

### Magma Cubes
* Inherent changes from Slimes
* Ignite the target on fire for 4 seconds upon successful attack
* On death, instead of a Poison II cloud, Magma Cubes generate lava proportionate to their size
* Magma Cream is fire resistant

### Piglins..
* Can mine blocks (Brutes as well)
* Aggro unless a Player is wearing only golden armor (you can wear just golden boots)

### Pillagers..
* Can mine blocks

### Vindicators..
* Can mine blocks
* Take reduced knockback

### Evokers..
* +50% base health
* Are invulnerable to magic and non-armor-piercing projectile damage

### Shulkers..
* Apply 5 seconds of Blindness via their projectiles

### Phantoms..
* Phase through blocks (but do not attempt attacks through them)
* Apply 15 seconds of Weakness upon successful attack
* Attacks bypass shields

### Silverfish..
* +100% base speed
* Lunge at their target
* Are invulnerable to fall, drown, and suffocation damage
* Apply 15 seconds of Mining Fatique III upon successful attack

### Endermites..
* +60% base speed
* Are invulnerable to fall and suffocation damage
* Teleports the victim like a Chorus Fruit does on successful attack

## Boss Changes

## Golem Changes

### All Golems..
* Projectiles phase through allies
* +100% base health
* +100% base follow range
