# Credits and licences of the Manhunt resource pack

Every model and texture of this pack comes from a source whose licence allows this use (including
sharing it), or was made for this pack. Nothing paid, nothing leaked, nothing with an unclear licence. The pack is built
by `tools/pack/build.py` of the (private) server project from the files listed here.

| In the pack | Source | Author | Licence | What was done |
|---|---|---|---|---|
| The feathered wings `angel_wings`, `parrot_wings`, `bat_wings`, `drake_wings`, `demon_wings`, `fire_wings` (models `*_left`, `*_right`; textures `textures/item/<name>.png`) | [Wings](https://github.com/pau101/Wings): `assets/wings/textures/entity/{angel,parrot,bat,dragon,evil,fire}_wings.png` and the bone and feather layout of `ModelWingsAvian` (commit 1749298) | Paul Fulham (pau101) | MIT (below) | Each wing rebuilt as an item model: the mod's bones as boxes, its feather sprites as planes, laid out in one spread pose; textures unchanged (renamed: dragon -> drake, evil -> demon) |
| The insect wings `blue_butterfly_wings`, `monarch_wings`, `fairy_wings`, `slime_wings` (models `*_left`, `*_right`; textures `textures/item/<name>.png`) | [Wings](https://github.com/pau101/Wings): `assets/wings/textures/entity/{blue_butterfly,monarch_butterfly,fairy,slime}_wings.png` and the sheet of `ModelWingsInsectoid` (commit 1749298) | Paul Fulham (pau101) | MIT (below) | One sheet per side as an item model; textures unchanged (renamed: monarch_butterfly -> monarch) |
| The flat wings `ax_dove_wings`, `ax_astronaut_wings`, `ax_bluefire_wings`, `ax_sparrow_wings`, `ax_rose_butterfly_wings`, `ax_crimson_wings`, `ax_shadow_dragon_wings`, `ax_eagle_wings`, `ax_golden_wings`, `ax_ocean_wings`, `ax_ember_wings`, `ax_amethyst_wings` (models `*_left`, `*_right`; textures `textures/item/ax_*.png`) | [Wing Cosmetics](https://builtbybit.com/resources/wing-cosmetics.53932/) on BuiltByBit (its Oraxen models and textures) | Artillex Studios ([Discord](https://dc.artillex-studios.com/)) | BuiltByBit Free EULA ([the licences](https://builtbybit.com/wiki/resource-eulas/): modification and redistribution allowed, attribution kept) | Each design split into a right and a left model, the backward sweep taken out (the server moves the wings), the inner edge moved onto the hinge; textures unchanged; renamed (angel -> dove, brown -> sparrow, butterfly -> rose butterfly, demon -> crimson, dragon -> shadow dragon, phoenix -> ember, purple -> amethyst) |
| `katana` (model), `textures/item/katana.png` | [Loy's Goodies](https://github.com/SL0ANE/Loy-s-Goodies), `models/java-model/tools & weapons/swords/230419_katana.bbmodel` (commit afbb769) | Loy (SL0ANE) | CC0 1.0 (public domain) | Converted from Blockbench to an item model; hand and menu positions added |
| The held items and the hat of Loy's Goodies, each from `models/java-model/` of [Loy's Goodies](https://github.com/SL0ANE/Loy-s-Goodies) (commit afbb769): `necro_staff` (tools & weapons/wands/230419_necro_wand), `crescent_staff` (wands/220207_wand), `emerald_wand` (wands/230418_wizard_wand), `runeguard_greatsword` (swords/230419_sword_3), `gilded_rapier` (swords/230419_sword_4), `crimson_dao` (swords/231014_dao), `hunters_knife` (swords/230502_dagger), `gemguard_dagger` (swords/230419_dagger), `golden_mace` (swords/230418_mace_1), `iron_mace` (swords/230418_mace_0), `battle_labrys` (axes/230429_double_axe), `viking_axe` (axes/230419_viking_axe), `copper_axe` (axes/220329_copper_axe), `elven_bow` (bows/230419_bow_1_0), `hunters_bow` (bows/230418_bow_0_0), `crusader_shield` (shields/230419_shield_0_0), `templar_shield` (shields/230419_shield_0_1), `heater_shield` (shields/230618_small_shield), `wizard_hat` (armor & costumes/hats/230418_wizard_hat) - all `.bbmodel` | Loy's Goodies | Loy (SL0ANE) | CC0 1.0 (public domain) | Converted from Blockbench to item models; hand, menu and (hat) head positions set; renamed |

Thanks to all three authors. Loy asks for a link to the repository as credit, gladly given above.

## MIT licence of the Wings mod

```
MIT License

Copyright (c) 2018 Paul Fulham

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## CC0 1.0 of Loy's Goodies

The assets of Loy's Goodies are dedicated to the public domain under Creative Commons Zero 1.0
Universal (https://creativecommons.org/publicdomain/zero/1.0/).
