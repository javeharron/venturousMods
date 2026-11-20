=====================================================================

  VENTUROUS - ITALIAN WEAPONS ADD-ON, ALT EXPLORER SKIN, and Expanded Weapons
  venturous_italy_weapons5.pk3
  
=====================================================================

Six new weapons for Venturous: five WW2 Italian arms and one blessed
bullwhip. Every weapon has a primary fire and an alt fire.


REQUIREMENTS
------------
- GZDoom (or LZDoom) with Venturous loaded first.
- Load order:   gzdoom -file Venturous.pk3 venturous_italy_weapons5.pk3
- The add-on only adds weapons, sprites, two sounds and two console
  aliases. It replaces no Venturous files and adds no new ammo types.


GETTING THE WEAPONS
-------------------
Console:  give <ClassName>   (see each weapon below)
          italy_give         gives the five Italian weapons
          whip_give          gives the Blessed Bullwhip
Map editors: DoomEdNums 12600-12605 (listed below). Weapons are also
placeable in the editor under the "MyWeapons" category.
All gunshots alert monsters. The saber is silent.


THE WEAPONS
-----------

1. STEYR M1912 / CAVALRY SABER                         Slot 1
   Class: SteyrSaber    DoomEdNum: 12600    Ammo: Bullets (pickup: 24)
   FIRE      3-round burst of 9mm hitscan, 9-14 damage per round, tight
             spread. If you have fewer than 3 bullets it fires what is
             left. Hold to keep bursting.
   ALT FIRE  Cavalry saber. Lunges forward when you are on the ground,
             then slashes twice per swing (100-200, then 30-60 damage,
             range 120). Hold to keep swinging. Uses no ammo.

2. BERETTA MODEL 38                                    Slot 2
   Class: Beretta38     DoomEdNum: 12601    Ammo: Bullets (pickup: 20)
   FIRE      Full-auto 9mm submachine gun, 5-15 damage per round, with
             the same spread and feel as the Owen.
   ALT FIRE  Toggle iron sights (1.3x zoom). While sighted the gun fires
             with much tighter spread and less muzzle climb, and the
             view stops bobbing. Press again to lower.

3. BODEO M1889 REVOLVER / TORCH                        Slot 3
   Class: BodeoRevolver DoomEdNum: 12602   Ammo: Shells4 (pickup: 8)
                                            + TorchAmmo (pickup: 4)
   FIRE      Fanning the hammer: up to 3 rapid slaps per trigger pull,
             1 shell each. Every slap fires a hitscan round (6-9 dmg)
             and a ricochet round (4-8 dmg) that bounces off walls up
             to 3 times. The cylinder stops fanning when shells run out.
             With the torch raised your off hand is busy, so you get a
             single double-action shot per pull instead of the fan.
   ALT FIRE  Raise or lower the torch. A raised torch lights the area
             around you. Costs no ammo.

4. FUCILE ARMAGUERRA MOD. 39                           Slot 4
   Class: Armaguerra39  DoomEdNum: 12603   Ammo: RifleAmmo (pickup: 10)
   FIRE      Semi-automatic rifle (one shot per click). 22-48 damage with
             a small spread, moderate recoil. A middle ground between
             the Nambu MG and the Arisaka/K98.
   ALT FIRE  Toggle iron sights (1.5x zoom). Sighted shots are perfectly
             accurate and hit harder (34-70 damage), but kick the view
             up sharply (-6) and recover slowly.

5. SOLOTHURN S-18/100                                  Slot 5
   Class: Solothurn     DoomEdNum: 12604   Ammo: RocketAmmo (pickup: 3)
   FIRE      Anti-tank rifle. Hitscan round for 120-200 damage that also
             detonates on impact with a small blast (about 40-70 damage,
             radius 128; it does not hurt you). Heavy muzzle climb (-8),
             screen shake, and it shoves you backwards. Slow to cycle.
   ALT FIRE  Brace the rifle. Deploying takes about a second (24 tics);
             press again to un-brace. While braced, each shot waits a
             moment (10 tics) to settle, then fires with half the climb
             and half the knockback. Hold your ground and pick your
             target.

6. THE BLESSED BULLWHIP                                Slot 6 (magic)
   Class: BlessedBullwhip DoomEdNum: 12605  Ammo: Mana family / CellB
                                            (pickup: 50)
   FIRE      Whipcrack that throws five Khopesh crescents in a fan:
             0, +/-30 and +/-60 degrees. The volley costs 10 Mana in
             total (not 10 per crescent). Alerts monsters. With less
             than 10 Mana you get a dry flick and no cost; the weapon
             does not auto-switch away.
   ALT FIRE  Sweeping lash with a swish. No projectiles and no Mana.
             A short-range melee hit for 100-200 damage (range 100)
             when something is close enough.


AMMO SUMMARY
------------
Steyr / Beretta ... Bullets        Bodeo ...... Shells4 (+TorchAmmo)
Armaguerra ........ RifleAmmo      Solothurn .. RocketAmmo
Bullwhip .......... Mana / CellB (all Mana-family pickups feed it)

-Also added 'Expanded Weapons' from the potential journal entries. 

NOTES
-----
- Damage numbers are anchored to the closest base weapon of each class
  (Owen, C96, Trenchgun, Nambu, Arisaka/K98, PSchreck, Khopesh). If a
  weapon feels weak or strong against your monsters, only the damage
  values in DECORATE.txt / BWHIP.txt need changing.
- Muzzle flash positions and sprite scale may need a small nudge
  depending on how your Venturous build scales weapon sprites (TEXTURES).
- Bullwhip sounds are original synthesized audio (CC0). To reuse the
  Khopesh sounds instead, see the fallback lines in SNDINFO.txt.
- Not tested against every Venturous version; report oddities.

CREDITS
-------
Venturous belongs to its original author, Pixelfox; this add-on is unofficial and
has mp no affiliation.
