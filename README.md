## Chest loot
Place the block chestloot:chestcopy to make new loot chest

## Config explain
`LootTable` is list of items for give this to player, needed to be in sequience like [Others,ammo,weapons,armors], and for weapons needed to be "tacz:modern_kinetic_gun {\"GunId\":\"tacz:aug\",\"GunCurrentAmmoCount\":30\"HasBulletInBarrel\":1b,\"GunFireMode\":\"AUTO\"}" and without spaces in {} brackets, weapon "tacz:ammo {\"AmmoId\":\"id\"}"

`amountOfWeaponItems..` amount of selected items, needed to be in sequience like [Others,ammo,weapons,armors]

`chestPositions` chest positions which will respawning every 9000 ticks

`procentOnAmmo..` Procent on items in all of them must be value of 1, 0.1 is 10%, 0.5 is 50% 

`delayOnRespawn` adjustable delay on respawn chests 

### Config located in .minecraft\saves\map\serverconfig\chestloot-server.toml
