# 猛兽之地/Roguelands v1.5.1 汉化补丁

**补丁版本 v1.2**

---

感谢 B 站 UP 主 @Icetric冰介 分享的汉化教程与工具，
感谢游侠网发布的 Roguelands v1.0 版本汉化补丁。

本补丁部分使用了非商业资源，任何人均可以基于此补丁进行修改与分享，但严禁将本补丁或其修改版本用于任何商业用途。

**！使用前请务必阅读此文本！**

**！！！使用前请务必备份存档以及需要替换的文件！！！**

---

存档位置：

```text
C:\Users\你的用户名\AppData\LocalLow\DefaultCompany\Roguelands\PlayerPrefs.txt
```

其他文件位置：

```text
你的 Steam 安装路径\Steam\steamapps\common\Roguelands\...
```

如果想游玩mod请自行查询wiki

---

虽然是以mod版为基础做的补丁，但经过测试貌似也适用于游戏本体，所以不单独给本体做了

根据以下需求情况查看对应文件说明进行安装。

* 仅游玩游戏本体，不安装包括GadgetCore在内的任何额外附加内容：

​		Part A/B

* 游玩mod版，但不使用任何扩展游戏内容的mod（仅使用功能性mod），或者不想对mod内容进行汉化：

  Part A/B/C

* 游玩mod并希望对mod进行汉化

  * 完全通过mod对游戏进行汉化

    Part A/D/E

  * 通过补丁汉化游戏本体，通过mod汉化mod内容

    Part A/B/C/D/F

注意：
由mod实现的汉化（小部分本体和所有mod内容）存在最高0.2s的延迟
3.1方案中不排除汉化mod和其他mod Patch了本体的同一个方法，这可能会导致二者只有一个生效；目前暂时没有发现这类冲突但不排除该冲突存在。同时该方案存在一部分文本未汉化，但不影响游玩。
3.2方案，如果mod作者使用字符串查询原版物品，可能会导致mod失效，没发现也应该不会有作者这么做

---

文件说明

**下面提到需要替换的文件均从Roguelands安装目录开始查找**

* Part A：字体文件
  在Font文件夹下

​		选择你喜欢的一版字体，替换Roguelands_Data目录下的对应文件`sharedassets0.assets`, `sharedassets1.assets`;

* Part B：本体汉化补丁
  在Patch文件夹下
  替换Roguelands_Data目录下的`level0`, `level1`, `resources.assets`
  替换Roguelands_Data/Managed目录下的`Assembly-CSharp.dll`

* Part C：模组框架汉化修复补丁（这个框架覆写了原版的两处文本，需要重新汉化，不汉化也不影响）
  在Patch/GadgetCore x.x.x.x目录下
  选择对应的版本替换Roguelands_Data/Managed目录下的`GadgetCore.dll`

* Part D：字体修复模组
  在Mod文件夹下，将`ZhFontsFixForMods_v1.1.zip`放进Mods目录
  ScarpYard/Dresser/CombatChipChest/AncientReassembler这几个mod由于增加了独立的界面，需要修复中文字体显示

* Part E：本体与mod汉化模组
  在Mod文件夹下，将`RoguelandsChinese_v1.2.zip`放进Mods目录

* Part F：mod汉化模组
  在Mod文件夹下，将`ZhForMods_v1.2.zip`放进Mods目录

已汉化mod：

```
Ancient Ressembler
Combat Chip Chest
Crystal Crevasse
Dresser
Engines Deluxe
Extra Potions
Item Frames
More Lights
More Vanity Items
Multiplayer Client Spawn
Original Vanity Items
Platform Block
Scarp Yard
Stasis Pod
Subworlds
TiersPlus
Ultimate NPC Weapons
Ultimate Rings
```

以下mod存在文本但没有翻译

```
Splash Texts：真正的副标题，但是翻译的话有些标题看着好尬，可能是英文语境下的一些梗，干脆不翻了
Utimate Fusion：把究极boss装备的属性打到其他装备上，本质是的外观mod，但既然已经有外观槽（虚荣槽）就没啥用了
Tien Contenet Mod：对一些内容进行了大修和扩展，可惜mod内部打架装不了
```

---

如果该补丁无法用于本体，可以尝试使用旧版Release里原来基于本体制作的补丁



有问题可以在百度贴吧-roguelands吧 

```
https://tieba.baidu.com/p/10928782464
```

这个贴子里找我



千般难述
2026.10.10
