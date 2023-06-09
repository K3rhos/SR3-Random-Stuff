Can be used like this:

vanim_find_anim_set -> `E8 ? ? ? ? 4C 63 44 24 ? ` add 1 and rip it.

```cpp
// 'human' struct is needed.

void human::set_anim_set(const char* _name)
{
  animation_set* anim_set = vanim_find_anim_set(_name);

  if (anim_set)
  {
    this->char_inst->vp->anim_set[0] = anim_set;
  }
}
```

This can also be used with the function: `player_swap_rig` on the third parameter.

| Index  | Name |
| ------------- | ------------- |
| 0 | anim_auto |
| 1 | anim_moto_cruiser |
| 2 | anim_moto_rocket |
| 3 | anim_boats_craft |
| 4 | anim_moto_atv |
| 5 | anim_jet |
| 6 | anim_plane_standard |
| 7 | anim_moto_dirt |
| 8 | heli_standard_2 |
| 9 | anim_FACE |
| 10 | anim_Gang_Customization |
| 11 | Drunk |
| 12 | RIOT |
| 13 | SNIPER |
| 14 | RollerBlader |
| 15 | PLYM |
| 16 | PLYF |
| 17 | COP |
| 18 | GANG |
| 19 | GANGF |
| 20 | Life_Default |
| 21 | PEDF |
| 22 | PEDM |
| 23 | anim_Default |
| 24 | BRUTE |
| 25 | anim_Customization |
| 26 | Weap_pistol |
| 27 | Heli_Vault |
| 28 | KillBane |
| 29 | veh_Tank |
| 30 | veh_BlackHawk |
| 31 | veh_Pony |
| 32 | Empty |
| 33 | GarageDoor |
| 34 | Door |
| 35 | CounterWeight |
| 36 | Weap_Minigun |
| 37 | anim_environment |
| 38 | Avatar |
| 39 | veh_heli_MAD03 |
| 40 | Life_Female |
| 41 | veh_apc |
| 42 | Tiger |
| 43 | CargoRamp |
| 44 | Elevator |
| 45 | SpinObject |
| 46 | SpikeTrap |
| 47 | RM_Targets |
| 48 | Weap_RHammer |
| 49 | SearchLight |
| 50 | Life_GANGF |
| 51 | Brute_Zombie |
| 52 | Zombie |
| 53 | STAG |
| 54 | AC_Door |
| 55 | Parachute |
| 56 | Weap_PredComputer |
| 57 | SlideDoor |
| 58 | OverHead door |
| 59 | Plane_Table |
| 60 | DoubleDoor |
| 61 | Giant_Plane |
| 62 | Weap_GangShot |
| 63 | Weap_PoliceShot |
| 64 | veh_VTOL |
| 65 | Josh |
| 66 | Horsie |
| 67 | VTOL |
| 68 | Swat_Rope |
| 69 | Heli_Fighter |
| 70 | veh_VTOL2 |
| 71 | Security_Camera |
| 72 | Container |
| 73 | veh_RIOT |
| 74 | Weap_GangRifle |
| 75 | Weap_NGRifle |
| 76 | anim_heli |
| 77 | Weap_STAGRifle |
| 78 | Weap_STAGShotgun |
| 79 | veh_HeliFighter02 |
| 80 | Weap_SniperRifle |
| 81 | veh_STAG_Tank |
| 82 | Weap_Genki |
| 83 | Weap_GangSMG |
| 84 | anim_moto_jetbike |
| 85 | StagCrate |
| 86 | BruteContainer |
| 87 | M19_Garage |
| 88 | Umbrella |
| 89 | Weap_SonicGun |
| 90 | MB_Crowd_A |
| 91 | Weap_Chum |
| 92 | MB_Crowd_B |
| 93 | Cable |
| 94 | Weap_Chainsaw |
| 95 | VTOL2 |
| 96 | Life_GANG |
| 97 | Weap_GrenadeLauncher |
| 98 | JetBike |
| 99 | Dist_Ped |
| 100 | Weap_Luchadore |
| 101 | Ball_Vehicle |
| 102 | Weap_SniperKS |
