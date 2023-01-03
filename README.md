# Lesnov's DRG Mods Source
![Deep Rock Galactic Screenshot 2022 12 20 - 03 38 45 97](https://user-images.githubusercontent.com/104094945/210460885-7388560c-7d01-455c-98f2-e87de1bff3ad.png)
---
> I put my mods source here. Content/_DRGModding/_Frameworks is used for the most of BPs, so please contain that.  
> Several mods are still work-in-progress.
> 
> I don't allow to release my un-released mods from here. 
---

## Un-release mod list
- MeleeSystem
- Aimbot
- PreCustomVanityFramework
- BashSystem
- ShoulderWeaponSystem
- 3D-HUD

## Mod_3DHUD
<details>
  <summary>Add 3D-Based HUD like Crysis's HUD.</summary>

```
..\Content/_DRGModding/Mod_3DHUD

..\AssetRegistry.*
```
</details>

## Mod_ShoulderWeaponSystem
<details>
  <summary>Add shoulder mounted weapons like Doom Eternal's shoulder weapon.</summary>

```
..\Content/_DRGModding/Mod_ShoulderWeaponSystem
..\Content/_DRGModding/_Frameworks/Widget

..\AssetRegistry.*
```
</details>

## Mod_BashSystem
<details>
  <summary>Add Bash System to perform bash with weapons. Part of Melee System but made as separated mod.</summary>

```
..\Content/_DRGModding/Mod_BashSystem
..\Content/_DRGModding/_Frameworks/Widget

..\AssetRegistry.*
```
</details>

## Mod_TakuyaSan
<details>
  <summary>Replace BP_Spring_Dwarf with Takuya-San from 真夏の夜の淫夢.</summary>

```
..\Content\_DRGModding\_Cosmetics\Mod_TakuyaSan

..\AssetRegistry.*
```
</details>

## Mod_FocusADS
<details>
  <summary>Add animation based ADS for M1000. ADS is performed automatically when Focus-shot is active. Also it has other forcus-shot indicator. </summary>

```
..\Content\_DRGModding\Mod_FocusADS

..\AssetRegistry.*
```
</details>

## Mod_Aimbot
<details>
  <summary>(Un-released)Add view-based Aimbot. Aimbot is automatically disabled when sprinting or certain weapon is equipped. </summary>

```
..\Content\_DRGModding\Mod_Aimbot

..\AssetRegistry.*
```
</details>

## Mod_LeftHandedWeapon
<details>
  <summary>(Currently cause crash)Allow to change the first person view to the left-sided. </summary>

```
..\Content\_DRGModding\Mod_LeftHandedWeapon

..\AssetRegistry.*
```
</details>

## Mod_TrueFPS
<details>
  <summary>Add a showable leg for First Person View. </summary>

```
..\Content\_DRGModding\Mod_TrueFPS

..\AssetRegistry.*
```
</details>

## Mod_BoscoChan
<details>
  <summary>Add a pettable Bosco-chan stand. </summary>

```
..\Content\_DRGModding\Mod_BoscoChan

..\AssetRegistry.*
```
</details>

## Mod_FullArmorBosco
<details>
  <summary>Add FA-Bosco to perform several new actions for Bosco. Doesn't contain any audio file due to license.  </summary>

```
..\Content/_DRGModding/Mod_FullArmorBosco
..\Content/_DRGModding/_Frameworks/Widget

..\AssetRegistry.*
```
</details>

## Mod_AdditionalWeaponSlot 
<details>
  <summary>Reuse BP from _MeleeSystem to add other weapons.</summary>

```
..\Content/_DRGModding/_MeleeSystem/_HandleWeaponEquip  
..\Content/_DRGModding/_Frameworks/Widget  
..\Content/_DRGModding/Mod_AdditionalWeaponSlot  

..\AssetRegistry.*  
```
</details>

## _MeleeSystem 
<details>
  <summary>Add melee system and weapons. Doesn't contain any audio file due to license.  </summary>

```
..\Content/_DRGModding/_MeleeSystem  
..\Content/_DRGModding/_Frameworks/Widget  

..\AssetRegistry.*  
```
</details>

## _CustomVanityFramework
<details>
  <summary>Proper Custom Vanity Framework, started to work on this after Pre Custom Vanity Framework. Can add new vanity via asset registry.</summary>

```
..\Content\_CustomVanityFramework

..\AssetRegistry.*
```
</details>

## _PreCustomVanityFramework
<details>
  <summary>Pre Custom Vanity Framework. It has dynamic vanity changing, and also dynamic weapon skin changer. Development of this was stopped after I started Custom Vanity Framework. Quite old, codes might hard to read.</summary>

```
..\Content/_PreCustomVanityFramework

..\AssetRegistry.*
```
</details>

## _OverclockFramework
<details>
  <summary>Add new way to add overclocks dynamically, This one suppress conflict with another overclock mod.</summary>

```
..\Content/_OverclockFramework

..\AssetRegistry.*
```
</details>


