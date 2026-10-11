# Credits and licences of the Manhunt resource pack

Every model and texture of this pack comes from a source whose licence allows this use, or was
made for this pack. Nothing paid, nothing leaked, nothing with an unclear licence. The pack is built
by `tools/pack/build.py` of the (private) server project from the files listed here.

| In the pack | Source | Author | Licence | What was done |
|---|---|---|---|---|
| The feathered wings `angel_wings`, `parrot_wings`, `bat_wings`, `drake_wings`, `demon_wings`, `fire_wings` (models `*_left`, `*_right`; textures `textures/item/<name>.png`) | [Wings](https://github.com/pau101/Wings): `assets/wings/textures/entity/{angel,parrot,bat,dragon,evil,fire}_wings.png` and the bone and feather layout of `ModelWingsAvian` (commit 1749298) | Paul Fulham (pau101) | MIT (below) | Each wing rebuilt as an item model: the mod's bones as boxes, its feather sprites as planes, laid out in one spread pose; textures unchanged (renamed: dragon -> drake, evil -> demon) |
| The insect wings `blue_butterfly_wings`, `monarch_wings`, `fairy_wings`, `slime_wings` (models `*_left`, `*_right`; textures `textures/item/<name>.png`) | [Wings](https://github.com/pau101/Wings): `assets/wings/textures/entity/{blue_butterfly,monarch_butterfly,fairy,slime}_wings.png` and the sheet of `ModelWingsInsectoid` (commit 1749298) | Paul Fulham (pau101) | MIT (below) | One sheet per side as an item model; textures unchanged (renamed: monarch_butterfly -> monarch) |
| `katana` (model), `textures/item/katana.png` | [Loy's Goodies](https://github.com/SL0ANE/Loy-s-Goodies), `models/java-model/tools & weapons/swords/230419_katana.bbmodel` (commit afbb769) | Loy (SL0ANE) | CC0 1.0 (public domain) | Converted from Blockbench to an item model; hand and menu positions added |

Thanks to both authors. Loy asks for a link to the repository as credit, gladly given above.

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
