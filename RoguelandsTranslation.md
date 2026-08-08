# Roguelands汉化翻译记录

**带(!)说明旧汉化组对其进行了可疑的汉化或者当前汉化计划进一步改进**

**我们仍未知道当年的汉化组为什么钟情于翻译路径、键值和方法名**

* [角色创建界面](#角色创建界面)
* [游戏内文本](#游戏内文本)
* [旧实体](#旧实体)

---

## 角色创建界面

* Class: `Menuu`

* File：`Assembly-CSharp.dll`


---

### · 角色构成项

**Line：112-119**

```
Variant = 造型
Race = 种族
Augment = 头饰
Uniform = 制服
```

### · 玩家预设名

**Line：142-289**


```
Wedge = 韦奇
Biggs = 比格斯
Plop = 普洛普
Larry = 拉里
Bob = 鲍勃
Newt = 纽特
Scrub = 菜鸟
Noob = 萌新
Doof = 笨蛋
Notch = Notch
Gaben = 加布
Frog = 青蛙
Harry = 哈利
Apple = 苹果
Gandalf = 甘道夫
Sephiroth = 萨菲罗斯
Earl = 伯爵
Weasley = 韦斯莱
Dart = 达特
Lavitz = 拉维兹
Blank = 无名
Tidus = 提达
Sean = 肖恩
Albert = 阿尔伯特
Rose = 罗丝
Cloud = 克劳德
Squall = 斯考尔
Rikku = 莉库
Sora = 索拉
Donald = 唐纳德
Eevee = 伊布
Link = 林克
Zelda = 塞尔达
Blue = 小蓝
Ash = 小智
Bucky = 巴基
Hagrid = 海格
Dood = 都德
Misty = 小霞
Brock = 小刚
Ben = 本
Steve = 史蒂夫
Alex = 艾利克斯
Cid = 希德
Tifa = 蒂法
Lloyd = 洛伊德
Paul = 保罗
Seymour = 西摩
Pete = 皮特
Barret = 巴雷特
```

### · 造型

**Line：324**

```
Variant: = 造型：
```

### · 存档相关(!)

**Line：368-383**

```
musicLevel = 
soundLevle = 
name = 名称
race = 种族
variant = 造型
uiniform = 支付
augment = 头饰
allegiance = 效忠
prof = 
trait0 = 
trait1 = 
curLevel = 
class = 级别
Menu Flush = 刷新菜单
```

### · 存档相关(!)

**Line：446-467**

```
name = 名称
Lv. = 
exp = 
race = 种族
variant = 造型
augment = 头饰
prof = 
只改：
EMPTY = 空槽位
```

### · 删档

**Line：530-533**

```
Delete All Data = 清空数据
Reset Ship = 重置飞船
```

### · 属性

**Line：563-578**

```
Vitality = 体质
Strength = 力量
Dexterity = 敏捷
Tech = 科技
Magic = 魔法
Faith = 信仰
```

### · 存档相关(!)

**Line: 831-850 参考Line: 368-383（疑似存档字段，先不翻）**

### · 造型

**Line: 1054，1076**

```
Variant: = 造型
```

### · 存档时间相关(!)

**Line: 1090-1150**

```
ship = 飞船
wall = 墙壁
lifetime = 生存时间
上面的不改
下面可能可以改
Reset Ship = 重置飞船
Delete All Data = 清空数据
```

### · 全屏

**Line: 1739-1754**

```
Fullscreen: ON = 全屏：开启
Fullscreen: OFF = 全屏：关闭
```

### · 存档相关(!)

**Line: 1831-1907**

```
nodmg = 
urugorak = 
mechcity = 
tyrannog = 
plague = 
molochP = 
caiusP = 
aq = 
name = 
exp = 
isChar = 
starting = 
hp = 
tier = 层
corrupted = 已损坏
Menu Flush = 刷新菜单
```

### · 种族枚举

**Line: 1925-2073**

```
Wanderer = 流浪者
Royalite = 皇族
Centurion = 百夫长
Illuminate = 启示者
Shlaami = 什拉米
Fishfolk = 鱼人
Gekko = 壁虎
Nomad = 游牧民
Deathrazor = 死亡利刃
Hiveling = 蜂巢子民
Ancient = 远古遗民
Lightsworn = 誓光者
Drifter = 漂泊者
Goblin = 地精
Swampfolk = 沼泽人
Tiki = 提基
Titan = 泰坦
Trogon = 咬鹃
Scaled = 鳞裔
Florbgon = 弗洛博贡
Oompa = 乌姆帕
Wizened = 智者
Necro = 死灵
Golem = 魔像
Avalancher = 斫霜者
Boogoo = 布古
Afflicted = 受难者
Runefolk = 符文使徒
Overseer = 监察者
Bunyip = 本耶普
Infernal = 炼狱种
Worg = 座狼
Broccolite = 西兰花人
Ironclad = 铁缚者
Savior = 救世主
Phantom = 幻影
```

### · 头饰枚举

**Line: 2086-2155**

```
None = 无
Crusader Hat = 十字军帽
Rogue Bandana = 盗贼头巾
Berserker Scarf = 狂战士围巾
Mage Hat = 法师帽
Crown = 王冠
Shmoo Hat = 什穆帽
Glibglob Hat = 格里布格洛布帽
Beats by Boizu = 博祖耳击
Eyepod Hat = 眼荚帽
Slime Hat = 史莱姆帽
Mech City Beanie = 机械城针织帽
Lucky Pumpkin = 幸运南瓜
Eye Gadget = 鹰眼目镜
Baby Sliver = 小银
Oculus Goggles = Oculus护目镜
Chamcham Hat = 查姆查姆帽
Demon Horns = 恶魔角
Forsaker Mask = 背誓者面具
Shroom Hat = 蘑菇帽
Halo = 光环
Creator Mask = 造物主面具
Rebellion Headpiece = 叛军头饰
Gas Mask = 防毒面具
```

### · 制服枚举

**Line: 2242-2311**

```
Fleet Cadet = 舰队学员
Hero = 英雄
Scholar = 学者
Explorer = 探险家
Pyromancer = 炽焰术士
Fairy = 仙灵
Seer = 先知
Soldier = 士兵
Blacksmith = 铁匠
President = 总统
Gadget Worker = 装置工程师
Minister = 神官
Antihero = 反英雄
Dirtmage = 尘埃法师
Beehive = 蜂巢
Monster Trainer = 驯兽师
Scientist = 科学家
Crusader = 十字军
Echo = 回响
Metalgear = 合金装备
Pheonix = 凤凰
Cobalt Mage = 钴蓝法师
Peasant = 农民
Overworld = 主宰
```

### · 种族描述

**Line: 3125-3230**

```
Wanderer = 流浪者
Wanderers are believed to be direct descendants of the ones who ruled planet Earth. Ambitious and selfish, these people have spent countless years building and inventing new Droid Combat Technology to maintain a powerful position within the Galaxy.
流浪者们被认为是地球统治者的直系后裔。受野心和自私所驱使，这些人花费了无数时间建造和发明新的机器人战争科技以维持其在银河内的强大地位。

Royalite = 皇族
Deep within the Astero System lies the Grand Citadel. Many laws that govern the Galaxy are formed here, often created by Royalites. This race is highly intelligent and seeks to spread fairness and justice.
在阿斯特罗星系的深处坐落着宏伟的城堡，许多统治银河系的法律在这里制定。而这些法律通常由皇族确立。这个种族具有高度的智慧，致力于传播公平与正义。

Centurion = 百夫长
Centurions are highly skilled warriors who take pride in their Aether-rich home planet of Gallatria. Many factions across the Galaxy have sought to control the Centurion home planet, only to find failure due to the Centurions' combat skills and massive flying insectoid mounts.
百夫长是一群技艺高超的战士，以其富含以太的母星加拉特里亚为傲。银河系中许多势力都试图控制百夫长的木星，但皆因百夫长的战斗技能和巨大的飞行昆虫坐骑而以失败告终。

Illuminate = 启示者
The Illuminate reside within the Chaos System, forging new types of life with their Arcane Thread. Some say that staring into an Illuminate's eyes will grant you a glimpse into the future. That is if you don't melt into a steamy pile of goo first.
启示者驻留在混沌星系之中，用他们的奥术之线锻造出新的生命形态。有人说，凝视启示者的双眼，可以让你窥见未来。当然，前提是你没先融化成一滩黏糊糊的液体。

Shlaami = 什拉米
Want a pack of Slithium Slugs? A gram of Floob? The only way to get your hands on illegal galactic drugs is to meet a Shlaami. They are cunning, mischievous, and know how to throw a party.
想要一包锂蛞蝓？还是来一克浮布？想要获得非法银河毒品，唯一的办法就是结识什拉米人。他们狡猾、顽皮，还懂得如何举办派对。

Fishfolk = 鱼人
Fishfolk are deployed at any aquatic planet to cultivate and gather nutrient filled plants. Some of the most potent healing products are crafted from extremely rare underwater materials, which is only possible due to the happy and hard working Fishfolk.
鱼人们被安排到各个水生星球，负责培育和采集富含营养的植物。一些最具强效的疗愈药剂都是由极其稀有的水下材料制成，这一切都离不开这些快乐而又勤劳的鱼人。

Gekko = 壁虎
Gekkos are often found in high ranking Galactic Squads due to their unmatched acrobatic combat style and deadly finesse on the battlefield. It is rumored that coming in contact with Gekko blood will leave your wounds with rotting tissue and poisonus fungus.
壁虎族凭借无与伦比的杂技式战斗风格，以及在战场上致命而精湛的技巧，常常活跃于银河精英部队之中。据传，接触到壁虎族的血液会使伤口组织溃烂，并滋生剧毒真菌。

Nomad = 游牧民
Climbing over mountains of junk and waste on the desert planet Bagdaboo, Nomads have mastered the art of exploration in harsh terrain. They scavenge for Droid fuel and rare antique metals to sell at the Galactic Market for profit.
穿行在沙漠星球巴格达布堆积如山的废料与垃圾之间，游牧民们早已掌握了在恶劣地形中探索的技巧。他们搜寻机器人燃料和稀有古董金属，并将其出售到银河市场中以获取利润。

Deathrazor = 死亡利刃
Half machine and half Centurion, Deathrazors are the elite tactical assassins of the Gallatrian Army. There are few beings who have entered combat with a Deathrazor and lived to tell the tale; Most die instantly in a flurry of blades and toxic smoke.
半机械、半百夫长的死亡利刃，是加拉特里亚军队中的精英战术刺客。很少有人能与死亡利刃交战后活着讲述这段经历；大多数敌人都毙命在漫天刀锋与剧毒烟雾中。

Hiveling = 蜂巢子民
Hivelings use their agility and teamwork to swarm opponents and attack from above. It's believed that Hivelings communicate with one another from hundreds of miles away, making them useful for tracking goods and managing commerce. These people will die of loneliness if they cannot find a colony to be a part of.
蜂巢子民利用敏捷的身手与团队协作能力，以蜂群般的攻势包围敌人，并从空中发动袭击。据说，蜂巢族之间能够跨越数百里的距离进行交流，这使他们在追踪货物和管理贸易方面拥有得天独厚的优势。如果无法找到一个能够归属的族群，他们便会因孤独而逐渐消亡。

Ancient = 远古遗民
Not much is known of these Aether-sensitive warlocks. What all races do know is that when crossing paths with an Ancient, something catastrophic is coming. Ancients only emerge from their tombs when they sense a great disturbance in the Galaxy.
关于这些能够感知以太之力的战争术士，人们所知甚少。所有种族都明白一件事：与远古遗民相遇，往往意味着一场灾难即将降临。只有在感受到银河中出现巨大的动荡时，远古遗民才会从沉眠的墓穴中苏醒。

Lightsworn = 誓光者
Divine. Elegant. Powerful. The fabled Lightsworn are only unleashed upon the galaxy after a hero sacrifices himself for the greater good. These holy beings destroy anything evil standing in their path.
神圣。优雅。强大。传说中的誓光者只会在英雄牺牲小我成就大我之后降临银河。他们是圣洁的存在，会摧毁一切阻挡在他们道路上的邪恶之物。

Drifter = 漂泊者
Exiled from the inner planetary council for trying to overthrow the government, Drifters can be found scattered across the outer rim planets. Nimble in both mind and body, they still seek to overthrow the corrupt Galactic council and enact their perfect vision of democracy.
因试图推翻政府而被逐出内行星议会的漂泊者，如今散落于银河边缘的各个星球。他们身心敏锐，仍然追寻着推翻腐败银河议会、实现理想民主制度的愿景。

Goblin = 地精
Deep within planet-stone mines you will find Goblins at work. These hard working and sometimes troublesome people are employed in fields of intense physcal labor due to their immense strength and strong work ethic. Just don't piss one off.
深入行星岩层矿坑，你便能发现地精忙碌工作的身影。这些勤劳却有时令人头疼的种族，凭借惊人的力量和强烈的职业精神，广泛受雇于高强度体力劳动领域。不过，最好不要招惹他们。

Swampfolk = 沼泽人
Swampfolk are Fishfolk gone mad. It is said that in Fishfolk culture, one must consume a rotting Chaosberry in order to test one's mental fortitude. Those who do not pass the test go insane, experiencing physical mutations and the unexpected amplification of magical abilities.
沼泽人是陷入疯狂的鱼人族。据说，在鱼人文化中，人们必须吞食一颗腐烂的混沌莓，以此证明自己的精神意志。那些未能通过考验的人会陷入疯狂，产生身体变异，并意外获得被强化的魔法能力。

Tiki = 提基
The Tiki are an accidental race created from a Gallatrian Alchemist. By infusing a Great White Tree with liquid Aether, the tree bore magical fruit. Eventually the fruit fell and bursted, allowing the magical Tiki to emerge. They quickly found and ate their creator.
提基族是由一名加拉特里亚炼金术士意外创造出的种族。通过将液态以太注入一棵巨大的白色古树，这棵树结出了蕴含魔力的果实。最终，果实坠落并炸裂，孕育出了神秘的提基族。而他们诞生后的第一件事，就是找到并吃掉自己的创造者。

Titan = 泰坦
Titans are pure mechanical beings used for constructing massive planetary structures. Despite them being just moving metal parts, some say they make the greatest of friends and can have real feelings. The Council is currently at odds with the legalization of intermechanical marriage.
泰坦是纯粹的机械种族，被用于建造巨型行星设施。尽管他们只是不断运转的金属零件组成的机器，但有人认为，他们能成为最好的伙伴，并拥有真正的情感。目前，银河议会仍在争论是否应允许机械生命之间的婚姻合法化。

Trogon = 咬鹃
The Trogon are a bird-like race that are mainly used for transporting goods. They can travel at high speeds in the air, carrying weight that is well over a ton. Some say that their planet of origin was overtaken by a big purple monstrosity.
咬鹃是一种类鸟种族，主要负责运输货物。他们能够在空中高速飞行，同时携带超过一吨的重量。据说，他们的母星曾被一只巨大的紫色怪物占领。

Scaled = 鳞裔
The harsh desert planet of Bagdaboo is home to many types of creatures, one of which is the armored-like Scaled. These reptilians ride across the dunes in hopes of pillaging weak colonies and stealing their precious metals.
严酷的沙漠星球巴格达布孕育了许多种生物，其中之一便是身披装甲般鳞片的鳞裔。这些爬行动物穿行于沙丘之间，寻找弱小的殖民地进行掠夺，并窃取其中珍贵的金属资源。

Florbgon = 弗洛博贡
Florbgon love to eat. Florbgon love to sleep. Florbgon love to dance. Florbgon love to sneak up behind you to suck the brain matter out of your ears with their writhing tentacle mouth.
弗洛博贡喜欢进食。弗洛博贡喜欢睡觉。弗洛博贡喜欢跳舞。弗洛博贡也喜欢悄悄绕到你的身后，用蠕动的触手状口器从你的耳朵吮吸你的脑浆。

Oompa = 乌姆帕
The jolly Oompa are dumb as they come. They like to sit at popular intersections of galactic freeways with their mouths open, consuming whatever passerbys throw at them. Jumping into an Oompa's mouth and trying to escape was a national pastime for awhile until too many people got eaten. It is now illegal to do.
快乐的乌姆帕一如既往的愚笨。他们喜欢张着嘴坐在银河高速公路的热门交汇处，吞下路人随手丢给他们的一切。有段时间，跳进乌姆帕嘴里并尝试逃出来是一项全民娱乐活动——直到太多人被吃掉。如今，这种行为已经被法律所禁止。

Wizened = 智者
Studying for thousands of years, the Wizened are a mythical race that form new philosophies of government. They've seen the rise and fall of many nations, and believe that the Galactic Council is the best we can achieve despite widespread inequality and poverty in the galaxy.
经过数千年的研究，智者成为了塑造新政府理念的神秘种族。他们见证了无数国家的兴衰，并相信，即使银河中仍存在严重的不平等与贫困，银河议会依然是目前能够达到的最佳制度。

Necro = 死灵
The Necro is a remnant of the dark ages. Tales are told of a flowing darkness that could take any form and consume planets whole. This darkness eventually was encased in a magical ore, but recent reports show that these ores are releasing darkness at an astounding rate. The Necro are born out of this darkness.
死灵是黑暗时代残留下来的存在。传说中，一股流动的黑暗能够变幻成任何形态，并吞噬整颗星球。最终，这股黑暗被封印于一种魔法矿石之中。但近期报告显示，这些矿石正在以惊人的速度释放黑暗。而死灵，正是诞生于此黑暗之中。

Golem = 魔像
Golems were first discovered on the massive earthen planet of Roc. They are a peaceful race that don't want much contact with the the galaxy. Unfortunately, their home planet was blasted to dust in the 10 year war. It is quite rare to come across a Golem.
魔像最初在巨大的岩质星球洛克上被发现。他们是一个热爱和平的种族，并不希望与银河产生过多联系。不幸的是，他们的母星在持续十年的战争中被轰成了尘埃。如今，遇见魔像可是相当罕见的事。

Avalancher = 斫霜者
Avalanchers roam the frost worlds in the Galaxy's outer rim. The rare Ice Crystals they harvest are widely used due to their 100+ year lifecycles of energy production. Despite tough work conditions and low pay, Avalanchers still find joy from the simple things in life.
斫霜者游荡于银河边缘的冰霜星球。他们采集的稀有冰晶拥有超过百年的能源循环寿命，因此被广泛应用于各种领域。尽管工作环境恶劣、报酬微薄，斫霜者仍能从生活中的简单事物里找到快乐。

Boogoo = 布古
The mysterious Boogoo are constantly screaming. Being the only race banned from Galactic Markets, Boogoos generally stick to themselves. Many people believe Boogoos are easily scared of everything around them, promting them to scream bloody murder nearly every second of their existence.
神秘的布古总是在不停尖叫。作为唯一被禁止进入银河市场的种族，他们通常选择独自生活。许多人认为，布古极易受到周围一切事物的惊吓，因此几乎在生命中的每一刻都在发出惨叫。

Afflicted = 受难者
Over 1000 years ago there was a curse set upon the people of Palamecia. They were imbued with immense power, but would forever be disfigured as a cost for their greed. The Afflicted are descendents of the Palamecians but they no longer want power; they just want to be loved.
一千多年前，帕拉梅西亚人遭受了一场诅咒。他们获得了强大的力量，却必须永远承受因贪婪而付出的代价——扭曲的外貌。受难者便是帕拉梅西亚人的后裔，但如今他们已不再追究力量；他们只渴望被爱。

Runefolk = 符文使徒
At the dawn of the Galaxy's existence was a massive planet-like structure that floated through the void of space. For unknown reasons this Mega Rune exploded in on itself, spreading magical shards throughout space and time. The Runefolk collect these fragments and aim to discover their true purpose.
在银河诞生之初，一颗巨大的类行星结构体漂浮于虚空之中。由于未知原因，这颗巨型符文自行崩毁，将魔法碎片散播至时空各处。符文使徒收集这些碎片，并试图揭开它们的真正用途。

Overseer = 监察者
The Overseer spawns minions to do its bidding. These slimey eyeball creatures conduct their work within the shadows, for one day the great Overseer will consume the sun and rule the Galaxy of darkness.
监察者能够召唤仆从听命于它。这些黏糊糊的眼球生物潜伏在阴影中执行任务，只为等待伟大的监察者吞噬太阳，让整个银河陷入永恒黑暗的那一天。

Bunyip = 本耶普
Bunyips are from the flower planet Begonia where they pick flowers all day. Some of the most potent potions are crafted and brewed on this planet, all thanks to the magical Bunyips. Any visitors who bring weapons are immediately ripped to shreds because Bunyips have really sharp teeth and a deep hatred for weapons.
本耶普来自花之星贝戈尼亚，他们每天在那里采摘鲜花。得益于拥有魔力的本耶普，这颗星球上调制成了许多银河中最为强效的药剂。任何携带武器的访客都会立即被撕成碎片，因为本耶普拥有锋利的牙齿，并且对武器深恶痛绝。

Infernal = 炼狱种
An Infernal is born within a dying star every 1000 years. They travel the cosmos in hopes of finding another of their kind, but always die before another Infernal is born. Their misery and frustration is reflected in the whipping flames that writhe along their bodies.
每隔一千年，都会有一只炼狱种诞生于一颗垂死的恒星之中。他们在宇宙中游荡，只为寻找另一个同族，却总是在下一只炼狱种诞生之前孤独死去。他们身上肆虐的火焰，翻涌着他们的痛苦与绝望。

Worg = 座狼
Worgs have been banned from all Galactic Markets. They simply cannot behave themselves due to an insatiable hunger for flesh and blood. Some say that Worgs eating their own family members is not that uncommon.
座狼已被禁止进入所有银河市场。由于对血肉无法满足的渴望，它们根本无法控制自己。据说，座狼吃掉自己的家人也并非什么罕见之事。

Broccolite = 西兰花人
The highly intelligent and skilled Broccolites beam from planet to planet in search of rare materials. Typical lifespans for Broccolites range from 120 to 300 years since they can regrow body parts. Broccolite fingers are a famous delicacy in the Eastern Grid of the Galaxy, and no one even has to die!
高度智慧且技艺高超的西兰花人乘坐传送装置穿梭于各个星球，寻找稀有材料。由于能够再生身体部位，他们通常拥有120至300年的寿命。银河东部区域中，西兰花人的手指是一种著名美食——而且根本不需要牺牲任何生命！

Ironclad = 铁缚者
Ever since the Age of Metal swept across the Galaxy, pioneers and adventurers have mysteriously disappeared when mining for rare ores. Some believe that those  missing people are actually imprisoned within an Ironclad, forced to travel the Galaxy as a lumbering mass of armor.
自金属时代席卷银河以来，许多先驱者与探险者在开采稀有矿石时神秘失踪。有人认为，那些失踪者其实被囚禁在铁缚者体内，被迫以一副沉重的铠甲之躯游荡于银河之中。

Savior = 救世主
Saviors are Wanderers that have ascended time and space. They freely travel from dimension to dimension, making profound impacts on timelines everywhere. One can only hope that beings as powerful as these do not possess malevolent intentions.
救世主是超越时间与空间的流浪者。祂们自由穿梭于不同维度之间，对无数时间线产生深远影响。人们只能祈祷，如此强大的存在不会心存恶意。

Phantom = 幻影
To see a Phantom is to see the universe. They are the perfect beings, forged when millions of dimensions clash into a single entity. A Phantom freely moves  through time and space, and has witnessed the birth of existence as well as the end of it.
见到幻影，便意味着看见整个宇宙。祂们是完美的存在，在数百万个维度碰撞融合时诞生。幻影能够自由穿越时间与空间，见证了存在的诞生，也目睹了万物的终结。
```

### · 种族解锁条件

**Line: 3285-3390**

```
50% Chance to Unlock after dying.
	死亡后有5%几率解锁。
50% Chance to Unlock after achieving level 5.
	达到5级后有50%几率解锁。
50% Chance to Unlock after achieving level 10.
	达到10级后有50%几率解锁。
25% Chance to Unlock after mining 10 Ore.
	采集10块矿石后有25%几率解锁。
50% Chance to Unlock after purchasing 10 items.
	购买10个物品后有50%几率解锁。
25% Chance to Unlock after completing 5 Objectives.
	完成5个任务目标后有25%几率解锁。
50% Chance to Unlock after chopping 20 Trees.
	砍伐20棵树后有50%几率解锁。
25% Chance to Unlock after opening 10 Chests.
	打开10个箱子后有25%几率解锁。
25% Chance to Unlock after defeating 100 Enemies.
	击败100个敌人后有25%几率解锁。
50% Chance to Unlock after harvesting 10 Bugspots.
	收获10个虫巢后有50%几率解锁。
10% Chance to Unlock after dying.
	死亡后有10%几率解锁。
100% Chance to Unlock after using a Lightsworn Crystal.
	使用光誓水晶后100%解锁。
25% Chance to Unlock after defeating Urugorak.
	击败乌拉格拉克后有25%几率解锁。
25% Chance to Unlock after defeating a Tyrannog.
	击败泰伦罗格后有25%几率解锁。
25% Chance to Unlock after defeating a Plaguebeast.
	击败疫病兽后有25%几率解锁。
25% Chance to Unlock after chopping 100 Trees.
	砍伐100棵树后有25%几率解锁。
25% Chance to Unlock after mining 100 Ore.
	采集100块矿石后有25%几率解锁。
100% Chance to Unlock after defeating Moloch without taking any damage.
	无伤击败莫洛克后100%解锁。
25% Chance to Unlock after defeating 200 Enemies.
	击败200个敌人后有25%几率解锁。
25% Chance to Unlock after harvesting 100 Bugspots.
	收获100个虫巢后有25%几率解锁。
10% Chance to Unlock after dying.
	死亡后有10%几率解锁。
100% Chance to Unlock after defeating Caius without taking any damage.
	无伤击败凯厄斯后100%解锁。
100% Chance to Unlock after reaching level 100 without taking any damage.
	无伤到达100级后100%解锁。
25% Chance to Unlock after achieving level 100.
	达到100级后有25%几率解锁。
100% Chance to Unlock after achieving level 150.
	达到150级后100%解锁。
100% Chance to Unlock after discovering all Alchemy recipes
	发现所有炼金配方后100%解锁。
5% Chance to Unlock after dying.
	死亡后有5%几率解锁。
5% Chance to Unlock after dying.
	死亡后有5%几率解锁。
100% Chance to Unlock after crafting every Ultimate Helm.
	打造终极头盔后100%解锁。
100% Chance to Unlock after crafting every Ultimate Armor.
	打造终极护甲后100%解锁。
100% Chance to Unlock after crafting every Ultimate Sword & Lance.
	打造终极剑与矛后100%解锁。
100% Chance to Unlock after crafting every Ultimate Gun & Cannon.
	打造终极枪械和加农炮后100%解锁。
100% Chance to Unlock after crafting every Ultimate Gauntlet & Staff.
	打造终极手套与法杖后100%解锁。
100% Chance to Unlock after dying in all Legendary Gear.
	穿戴所有传奇装备死亡后100%解锁。
100% Chance to Unlock after achieving level 200 in Ironman Mode.
	在铁人模式下达到200级后100%解锁。
100% Chance to Unlock after naming your character something special.
	为你的角色取一个特别的名字后100%解锁。
```

### · 头饰描述

**Line: 2887-2954**

```
None = 无

Crusader Hat = 十字军帽
A sacred hat passed down from the ancient Crusader lineage. Max HP is now 125.
传承自古老十字军血脉的神圣帽子。/n最大生命值提升至125。/nMax HP is now 125.

Rogue Bandana = 盗贼头巾
Rogues that roam Gallatria's streets are nimble navigators with unmatched dexterity. Jumping and dashing no longer uses Stamina.
游荡在加拉特里亚街头的盗贼，身手敏捷，是无人能及的灵巧行者。/n跳跃与冲刺不再消耗耐力。/nJumping and dashing no longer uses Stamina.

Berserker Scarf = 狂战士围巾
This scarf was worn by the legendary warriors who died fighting the dark monstrosity long ago. Gain 1 STR upon level up.
这条围巾曾属于很久以前那些与黑暗怪物殊死搏斗而陨落的传奇战士。/n升级时获得1[力量]。/nGain 1 STR upon level up.

Mage Hat = 法师帽
Infused with Aether, this Mage Hat is standard attire for budding Cobalt Mages during their pilgrimage. Max Mana is now 125.
注入了以太能量的法师帽，是崭露头角的钴蓝法师在朝圣旅途中的标准着装。/n最大魔素值提升至125。/nMax Mana is now 125.

Crown = 王冠
A Crown fit for kings. Its protective magic radiates around the majestic spires. Reduce incoming damage by 5, to a minimum of 1.
与王者匹配的王冠。其守护魔法环绕着庄严的冠尖。/n受到的伤害减少5，最低为1。/nReduce incoming damage by 5, to a minimum of 1.

Shmoo Hat = 什穆帽
A decorative hat worn during the Aether Festival. You can no longer dash.
以太节期间佩戴的装饰性帽子。/n你无法再进行冲刺。/nYou can no longer dash.

Glibglob Hat = 格里布格洛布帽
A decorative hat worn during the Aether Festival. Your max mana is now 0.
以太节期间佩戴的装饰性帽子。/n你的最大魔素值变为0。/nYour max mana is now 0.

Beats by Boizu = 博祖耳击
You feel Boizu's sick tunes coursing through your veins. Their rhythmic power grants bonus dash speed and jump height.
你能感受到博祖的疯狂旋律在血管中奔涌。/n它们富有节奏的力量赋予冲刺速度和跳跃高度加成。/nTheir rhythmic power grants bonus dash speed and jump height.

Eyepod Hat = 眼荚帽
A decorative hat worn during the Aether Festival. Your movement speed is now 0.
以太节期间佩戴的装饰性帽子。/n你的移动速度变为0。/nYour movement speed is now 0.

Slime Hat = 史莱姆帽
A decorative hat worn during the Aether Festival. You look awesome.
以太节期间佩戴的装饰性帽子。/n你看起来真棒。/nYou look awesome.

Mech City Beanie = 机械城针织帽
Mech City is all about the fashion, and this is what the cool kids are wearing. Beaming to and from planets will now heal you for 5 hp.
机械城追求时尚，而这就是酷孩子们的穿着。/n在星球间传送时，回复5点生命。/nBeaming to and from planets will now heal you for 5 hp.

Lucky Pumpkin = 幸运南瓜
Lucky Pumpkins are scattered throughout the night markets in the Galactic Square. It is said to bring the wearer great fortune. Gain Double loot from chests.
幸运南瓜散布于银河广场的夜市之中。据说能为佩戴者带来好运。/n从宝箱中获得双倍战利品。/nGain Double loot from chests.

Eye Gadget = 鹰眼目镜
Designed for the Special Galaxy Attack Force, Eye Gadgets provide excellent data for sharp shooting. 50% chance to gain 1 DEX upon level up.
鹰眼目镜专为银河特殊攻击部队设计，能为精准射击提供卓越的数据支持。\n升级时有50%概率获得1点[敏捷]。\n50% chance to gain 1 DEX upon level up.\nbug: 获得1点[科技]而非[敏捷]

Baby Sliver = 小银
Baby Slivers are all the rage nowadays. Some say that sticking them to your forehead can actually be healthy for you. Upon level up, gain 3 points in a random stat and reduce your HP to 1.
小银如今风靡一时。有人认为，把它贴在额头上能够带来健康。\n升级时随机获得3点属性，并将生命值降低至1。\nUpon level up, gain 3 points in a random stat and reduce your HP to 1.

Oculus Goggles = Oculus护目镜
These goggles are worn by master Datamancers. Gain bonus movement speed and gain 1 TEC upon level up.
数卜师们所佩戴的护目镜。\n提升移动速度，并在升级时获得1点[科技]。\nGain bonus movement speed and gain 1 TEC upon level up.\nbug: 不会获得1点[科技]

Chamcham Hat = 查姆查姆帽
A decorative hat worn during the Aether Festival. You can't access the Combat Chip Terminal.
以太节期间佩戴的装饰性帽子。/n你将无法访问战术芯片终端。/nYou can't access the Combat Chip Terminal.

Demon Horns = 恶魔角
Masters of the darkness become so obsessed with learning about demons that they slowly turn into one! Max HP is now 50. Gain 3 STR per level.
沉迷于研究恶魔之力的黑暗大师，最终会逐渐化身为恶魔本身！\n最大生命变为50。每级获得3点[力量]。\nMax HP is now 50. Gain 3 STR per level.

Forsaker Mask = 背誓者面具
A mask worn by the Forsakers, ancient Arcanists who created the magic arts. Halves the cost of all Combat Chips.
背誓者所佩戴的面具——他们是穿凿魔法体系的远古奥术师。\n所有战术芯片消耗减半。\nHalves the cost of all Combat Chips.

Shroom Hat = 蘑菇帽
A decorative hat worn during the Aether Festival. Quite a pungent smell.
以太节期间佩戴的装饰性帽子。/n散发着相当浓烈的气味。/nQuite a pungent smell.

Halo = 光环
Symbol of a being that has ascended into a higher plane of existence. You can fly!
象征着超越凡俗、升入更高存在层面的生物。\n你可以飞啦！\nYou can fly!\nbug：与物品摊位或宝箱互动会停止飞行

Creator Mask = 创造者面具
A mask crafted by the fabric of time and space.
由时空本身的织物编织而成的面具。

Rebellion Headpiece = 叛军头饰
Headgear worn by a true Rebel of the Starlight Empire.
真正的星光帝国叛军所佩戴的头饰。

Gas Mask = 防毒面具
Gray Enigma's standard gas mask to protect the wearer from noxious gases.
灰色谜团的标准防毒面具，防止佩戴者计入有毒气体。
```

### · 头饰解锁条件

**Line: 3044-3112**

```
10% Chance to Unlock upon dying.
	死亡后有10%几率解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 100.
	达到100级后有25%几率解锁。
100% Chance to Unlock after defeating 5000 enemies.
	击败5000个敌人后100%解锁。
100% Chance to Unlock after mining 1000 ores.
	采集1000块矿石后100%解锁。
5% Chance to Unlock upon dying.
	死亡后有5%几率解锁。
100% Chance to Unlock after harvesting 1000 bugspots.
	收获1000个虫巢后100%解锁。
100% Chance to Unlock after chopping 1000 trees.
	砍伐1000棵树后100%解锁。
25% Chance to Unlock after visiting Mech City.
	抵达机械城后有25%几率解锁。
100% Chance to Unlock after opening 500 chests.
	打开500个箱子后100%解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
25% Chance to Unlock after reaching level 100.
	达到100级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
100% Chance to Unlock after purchasing max storage slots.
	购买最大存储插槽后100%解锁。
100% Chance to Unlock after reaching level 50 in Ironman mode.
	在铁人模式中达到50级后100%解锁。
100% Chance to Unlock after reaching level 100 in Ironman mode.
	在铁人模式中达到100级后100%解锁。
100% Chance to Unlock after maxing out Ship Droids.
	用尽飞船机器人后100%解锁。
100% Chance to Unlock after beating the Galactic Fleet storyline.
	完成“银河舰队”剧情后100%解锁。
100% Chance to Unlock after beating the Church of Faust storyline.
	完成“浮士德教会”剧情后100%解锁。
100% Chance to Unlock after beating the Starlight Rebellion storyline.
	完成“星光叛军”剧情后100%解锁。
100% Chance to Unlock after beating the Gray Enigma storyline.
	完成“灰色谜团”剧情后100%解锁。
```

### · 制服描述

**Line: 3199-3269**

```
Fleet Cadet = 舰队学员
Standard attire for a cadet.
学员的标准制服。

Hero = 英雄
The Hero Uniform is awarded to citizens who have done a great deed. The wearer recieves 5 bonus Crit Chance.
那些立下伟大功绩的公民被授予英雄制服。/n穿戴者获得5%暴击率加成。/nThe wearer recieves 5 bonus Crit Chance.

Scholar = 学者
Scholars practice their magic relentlessly, aiming to perfect the art. Scholars regen 2 mana per tick instead of 1.
学者日复一日精进魔法，只为追求极致。\n魔素回复提升为每次恢复2点而非原来的1点。\nScholars regen 2 mana per tick instead of 1.

Explorer = 探险家
Explorers value discovery more than anything. Dashing has a 20% chance to regain Mana & Stamina.
探险家把发现看的比任何东西都珍贵。\n冲刺时有20%概率恢复魔素与耐力。\nDashing has a 20% chance to regain Mana & Stamina.

Pyromancer = 炽焰术士
Pyromancers sometimes can't control their hunger for destruction. While in combat mode, you will cast Blaze every 2 seconds without cost.
炽焰术士有时难以抑制对毁灭的渴望。\n处于战斗模式时，每2秒无消耗施放一次「火焰」。\nWhile in combat mode, you will cast Blaze every 2 seconds without cost.

Fairy = 仙灵
The Fairy Uniform is bestowed upon those who aid others in battle. Gain 1 additional FTH upon level up.
那些在战斗中帮助他人的人被授予仙灵制服。\升级时额外获得1点[信仰]。\nGain 1 additional FTH upon level up.

Seer = 先知
eers value offensive and defensive magic equally. Randomly gain 1 FTH or MAG upon level up.
先知把进攻和防守看得同样重要。\n升级时随机获得1点[信仰]或[魔法]。\nRandomly gain 1 FTH or MAG upon level up.

Soldier = 士兵
Soldier Uniforms are adorned with various badges of honor. Gain 1 additional DEX upon level up.
士兵制服上缀满各式荣誉徽章。\n升级时额外获得1点[敏捷]。\nGain 1 additional DEX upon level up.


Blacksmith = 铁匠
Blacksmiths are expert craftsmen. Recieve a bonus 1% towards crafting higher tiered gear for every 20 player levels.
铁匠是精湛的工匠大师。\n每20级使制作高阶装备的概率提升1%。\nRecieve a bonus 1% towards crafting higher tiered gear for every 20 player levels.

President = 总统
The President's Uniform is only for true leaders. Touching a relic will grant 6 portals uses instead of 3.
总统制服只属于真正的领导者。\n触碰遗物时，将获得6次传送门使用次数而非原来的3次。\nTouching a relic will grant 6 portals uses instead of 3.

Gadget Worker = 装置工程师
Gadget Workers are experts in anything TEC related. Gain 1 additional TEC upon level up.
装置工程师精通一切与科技相关的领域。\n升级时额外获得1点[科技]。\nGain 1 additional TEC upon level up.

Minister = 神官
Ministers have mastered their faith of the unknown. Randomly gain 1 VIT or FTH upon level up.
神官掌握了对未知信仰的奥秘。\n升级时随机获得1点[体质]或[信仰]。\nRandomly gain 1 VIT or FTH upon level up.

Antihero = 反英雄
The Antihero knows when to take action and fight for what they believe in. Gain 2 points towards a random stat upon level up.
反英雄懂得何时出手，为信念而战。\n升级时获得2点随机属性。\nGain 2 points towards a random stat upon level up.

Dirtmage = 尘埃法师
Dirtmages use the power of nature magic to shield them from damage. Reduce all incoming damage by 5 points to a minimum of 1.
尘埃法师借助自然魔法的力量保护自己免受伤害。\n所有受到的伤害减少5，最低为1。\nReduce all incoming damage by 5 points to a minimum of 1.

Beehive = 蜂巢
The Beehive Uniform smells like honey and is extremely light weight. The wearer's fall speed is greatly reduced.
蜂巢制服散发着蜂蜜气味，且极为轻盈。\n大幅降低穿戴者的下落速度。\nThe wearer's fall speed is greatly reduced.

Monster Trainer = 驯兽师
Monster Trainers know anything and everything about the creatures in the galaxy. Gain immunity to Poison, Frost, & Burn.
驯兽师对银河中的生物无所不知。\n免疫中毒、冰冻与燃烧效果。\nGain immunity to Poison, Frost, & Burn.

Scientist = 科学家
Scientists seek to unravel the mysteries of the universe. Randomly gain 1 TEC or MAG upon level up.
科学家致力于揭开宇宙的奥秘。\n升级时随机获得1点[科技]或[魔法]。\nRandomly gain 1 STR or FTH upon level up.

Crusader = 十字军
The Crusader Uniform is a symbol of vigilance during a lifelong journey of spreading justice. Randomly gain 1 STR or FTH upon level up.
十字军制服象征着终身守望与传播正义的使命。\n升级时随机获得1点[力量]或[信仰]。\nRandomly gain 1 STR or FTH upon level up.

Echo = 回响
The Echo Uniform is granted to individuals who have remarkable skill on the battlefield. Randomly gain 1 DEX OR TEC upon level up.
那些在战场上拥有非凡技艺的人被授予回响制服。\n升级时随机获得1点[敏捷]或[科技]。\nRandomly gain 1 DEX OR TEC upon level up.

Metalgear = 合金装备
Metalgears are masters of combat tactics and espionage. Randomly gain 1 STR or TEC upon level up.
合金装备时战术与潜行的大师。\n升级时随机获得1点[力量]或[科技]。\nRandomly gain 1 STR or TEC upon level up.

Pheonix = 凤凰
The Pheonix Uniform is symbolic of a higher being. 20% chance to immediately restore all HP when HP reduced to 1.
凤凰制服是高等生命的象征。\n当生命值降至1时，有20%概率立即恢复全部生命。\n20% chance to immediately restore all HP when HP reduced to 1.

Cobalt Mage = 钴蓝法师
Cobalt Mages travel on a pilgrimage to the Cobalt Citadel in order to learn powerful magic. Gain 1 MAG upon level up.
钴蓝法师踏上前往钴蓝要塞的朝圣之旅，以学习强大魔法。\n升级时获得1点[魔法]。\nGain 1 MAG upon level up.

Peasant = 农民
Peasants are useless and not skilled at anything. All damage recieved is 9999 points of damage.
农民毫无用处，也没有任何特长。\n受到的所有伤害为9999点。\nAll damage recieved is 9999 points of damage.

Overworld = 主宰
Overlords have immense power in the galaxy. Damage recieved has a 25% chance to be reduce to 1.
银河中的主宰拥有无与伦比的力量。\n受到伤害时，有25%概率将伤害降至1。\nDamage recieved has a 25% chance to be reduce to 1.
```

### · 制服解锁条件

**Line: 3358-3426**

```
25% Chance to Unlock after dying.
	死亡后有25%几率解锁。
25% Chance to Unlock after reaching level 20.
	达到20级后有25%几率解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
25% Chance to Unlock after reaching level 100.
	达到100级后有25%几率解锁。
25% Chance to Unlock after reaching level 100.
	达到100级后有25%几率解锁。
100% Chance to Unlock after reaching level 10 in Ironman Mode.
	在铁人模式中达到10级后100%解锁。
100% Chance to Unlock after reaching level 75 in Ironman Mode.
	在铁人模式中达到75级后100%解锁。
100% Chance to Unlock after reaching level 30 in Ironman Mode.
	在铁人模式中达到30级后100%解锁。
100% Chance to Unlock after reaching level 40 in Ironman Mode.
	在铁人模式中达到40级后100%解锁。
100% Chance to Unlock after reaching level 50 in Ironman Mode.
	在铁人模式中达到50级后100%解锁。
100% Chance to Unlock after reaching level 60 in Ironman Mode.
	在铁人模式中达到60级后100%解锁。
100% Chance to Unlock after taking at least 10,000 damage.
	累计承受至少10000伤害后100%解锁。
25% Chance to Unlock after reaching level 75.
	达到75级后有25%几率解锁。
100% Chance to Unlock after reaching level 70 in Ironman Mode.
	在铁人模式中达到70级后100%解锁。
25% Chance to Unlock after reaching level 50.
	达到50级后有25%几率解锁。
100% Chance to Unlock after defeating any ChLv.3 boss in the Forbidden Arena.
	在禁忌竞技场击败任意挑战等级3的Boss后100%解锁。
100% Chance to Unlock after defeating The Creator in Ironman Mode.
	在铁人模式中击败造物主后100%解锁。
```

### · 战术芯片

**Line: 3513-3546**

```
Blood-Infused Stimpack = 注血兴奋剂
Molten Temper = 熔火淬炼
Sharpshooting = 精准射击
Gambler's Delight = 赌徒狂喜
Arcane Aura = 奥术光环
Ancient Enlightenment = 远古启迪
Energy Overload = 能量超载
Rage = 狂暴
Rapid Shot = 速射
Pineapple Mine = 菠萝地雷
Aetherblast = 以太爆发
Laser Gadget = 激光装置
```

### · 职业

**Line: 3670-3712**

```
Enforcer = 执法者
Gunner = 枪手
Machinist = 机械师
Darkmage = 暗法师
Aethermage = 以太法师
Blademaster = 剑圣
Dragoon = 龙骑兵
Spellblade = 魔剑士
Aetherknight = 以太骑士
Bounty Hunter = 赏金猎人
Gunmage = 枪炮法师
Commander = 指挥官
Datamancer = 数卜师
Alchemist = 炼金术士
Arcanist = 奥术师
```

### · 职业描述

**Line: 3724-3767**

```
Enforcer = 执法者
Enforcers balance their offense and defense in combat. As loyal warriors, they hope to bring peace to the galaxy.
执法者在战斗中兼顾进攻与防御。\n作为忠诚的战士，他们致力于为银河带来和平。

Gunner = 枪手
Gunners utilize their skills with both guns and cannons on the battlefield to defeat their enemies from afar.
枪手精通枪械与火炮，\n在战场上远程歼灭敌人。

Machinist = 机械师
Rather than using traditional Aetherweapons, Machinists unlock their true potential with Gadgets and Combat Chips.
机械师并不依赖传统的以太武器，\n而是通过装置与战术芯片释放真正的潜能。

Darkmage = 暗法师
Darkmages destroy foes with powerful Magic Combat Chips, and use the mysterious Gauntlet weapon.
暗法师通过强力的魔法型战术芯片毁灭敌人，\n并使用神秘的臂环武器作战。

Aethermage = 以太法师
These devout cadets utilize support magic in order to aid allies in need.
这些虔诚的学员擅长运用支援魔法，\n为有需要的队友提供帮助。

Blademaster = 剑圣
Blademasters are unmatched in Aetherblade combat, destroying anyone who challenges them.
剑圣在以太之刃的交锋中无人能敌，\n将斩灭一切挑战者。

Dragoon = 龙骑兵
Specializing in high tech gear and wielding massive Aetherlances, Dragoons are an elite force of combatants.
龙骑兵专精于高科技装备，挥舞巨型以太长枪，\n是一支精锐的战斗力量。

Spellblade = 魔剑士
Spellblades combine the ferocity of melee combat with powerful magic to excel in all facets of battle.
魔剑士将近战的狂猛与强大魔法结合，\n在战斗各方面都表现卓越。

Aetherknight = 以太骑士
Aetherknights are stalwart warriors who cut down foes while simultaneously wielding support magic.
以太骑士是坚毅的战士，\n在斩杀敌人的同时还能施展支援魔法。

Bounty Hunter = 赏金猎人
Masters of ranged weapons and tech gear, Bounty Hunters complete their missions with efficiency and destruction.
赏金猎人精通远程武器与科技装备，\n以高效与毁灭性的方式完成任务。

Gunmage = 枪炮法师
Gunmages have the ultimate arsenal of ranged weaponry, utilizing both damage spells and powerful guns.
枪炮法师拥有终极远程武装，\n同时运用伤害法术与强力枪械作战。

Commander = 指挥官
Commanders are natural leaders on the battlefield. They attack from afar while also using support Combat Chips.
指挥官是战场上的天生领袖，\n既能远程攻击，也能运用支援型战术芯片。

Datamancer = 数卜师
Using both destructive magic and technolgy, Datamancers watch from afar as opponets collapse into nothing.
数卜师融合毁灭性魔法与科技之力，\n在远处观望敌人化为虚无。

Alchemist = 炼金术士
Alchemists combine various potions and magical concotions to provide the ultimate aid on the battlefield.
炼金术士调配各类药剂与魔法合剂，\n在战场上提供极致支援。

Arcanist = 奥术师
Arcanists are masters of both dark and light magic, allowing them to fill multiple roles in any Combat Squad.
奥术师精通光与暗两系魔法，\n能够在任何战斗小队中承担多种职责。
```

### · 阵营与模式

**Line: 4164-4179**

```
The Galactic Fleet = 银河舰队
Starlight Rebellion = 星光叛军
Church of Faust = 浮士德教会
Gray Enigma = 灰色谜团
Junkbelt Mercenaries = 废弃带佣兵团
Droidtech Enterprise = 机械科技企业
Ironman: No Storage/Multiplayer = 铁人模式：无仓库/多人
Standard = 标准模式
```



---

## 游戏内文本

* Class: `GameScript`
* File：`Assembly-CSharp.dll`

---

### · 杂项

**不好说翻不翻**

```
Line102: FROST = 冻结
Line138: BURN = 灼烧
Line179: POISON = 中毒

Line 294+
Deliver = 交付
" " = 单位
"s"删掉
Defeat = 消灭
" " = 只
ChLv.不翻译
"s"删掉

Line 366+
Quests Completed: = 已完成任务：
Progress: = 进度：
\nReward: = \n奖励
Progress: = 进度：
\nCOMPLETE! = \n已完成！

Line 671+
THE INTERGALACTIC MARKET = 星际市场
Total EXP: = 总经验：
     EXP to next Lv:  =     下一级还需经验：

Line795: Hostile Lv. = 敌人等级 Lv.
Line842: Portal Uses: = 传送门次数：
Line847: Portal Uses: Infinite = 传送门次数：无限
Line1854: 's Combat Chips = 的战术芯片
Line1914: Upgrade Lv. = 升级至 Lv.
Line1919: MAX LEVEL = 已满级(先不改)

Line 1948+ 
Passive = 被动
Mana = 魔素

Line2141: Stronger Enemies with increased chances of EXP, Credits, and rare items. = 更强的敌人，\n经验、信用点和稀有物品\n掉落概率提升。
Line2972: Fullscreen: ON = 全屏：开启
Line2977: Fullscreen: OFF = 全屏：关闭
Line3838: Page不翻了

Line 3994+: 
Challenge Lv. = 挑战等级 Lv.
数不尽的：
Lv. = 
MAX = 
(EMPTY) = -空槽位-

Line5563: 同Line837
Line6453: Score: = 评分：

Line 6475+
NEW RACE UNLOCKED = 新种族解锁
NEW VARIANT UNLOCKED = 新造型解锁
NEW VARIANT UNLOCKED = 新造型解锁
NEW UNIFORM UNLOCKED = 新制服解锁
NEW AUGMENT UNLOCKED = 新头饰解锁

Line 6787+
Score: = 评分：
Level: = 等级：

Line 6809+
has died. = 已死亡。
Age: = 存活：
Minutes. = 分钟。

Line 17389+
QUIT WITHOUT SAVING = 退出但不保存
SAVE AND QUIT = 保存并退出
```



### · 地图

**Line:1030+/16535**

```
Desolate Canyon = 荒凉峡谷
Deep Jungle = 幽深丛林
Hollow Caverns = 空邃洞窟
Shroomtown = 蘑菇镇
Ancient Ruins = 远古遗迹
Plaguelands = 疫病之地
The Byfrost = 霜境
Molten Crag = 熔火峭岩
Mech City = 机械城
Demon's Rift = 恶魔裂隙
The Whisperwood = 低语林地
Old Earth = 旧地球
Forbidden Arena = 禁忌竞技场
The Cathedral = 圣堂
Return to Ship = 返回飞船
```



### · 属性

```
Line: 2334+/19869+
VIT = 体质
STR = 力量
DEX = 敏捷
TEC = 科技
MAG = 魔法
FTH = 信仰

Line: 19813+
Vitalilty = 体质
Strength = 力量
Dexterity = 敏捷
Tech = 科技
Magic = 魔法
Faith = 信仰
```



### · 属性说明

```
Bonus Hitpoints = 增加生命值
Power with Swords & Lances = 提高剑与长矛的伤害
Power with Guns & Cannons = 提高枪和炮的伤害
Power with certain Combat Chips = 提高部分战术芯片的伤害
Bonus Mana Power with Gauntlets = 提高魔符的魔法伤害
Bonus Mana Power with Staffs = 提高法杖的魔法伤害
```



### · 职业

```
Line: 23527+
Enforcer = 执法者
Gunner = 枪手
Machinist = 机械师
Darkmage = 暗法师
Aethermage = 以太法师
Blademaster = 剑圣
Dragoon = 龙骑兵
Spellblade = 魔剑士
Aetherknight = 以太骑士
Bounty Hunter = 赏金猎人
Gunmage = 枪炮法师
Commander = 指挥官
Datamancer = 数卜师
Alchemist = 炼金术士
Arcanist = 奥术师
```



### · 制作站

```
Line 18581+
Gear Forge = 锻造台
Combine different Emblems of the same tier. [Tier 1-3]
融合同等阶的不同徽印。[等阶1-3]

Alchemy Station = 炼金站
Combine 3 Plants, Bugs, or Monster Parts.
融合3件植物、虫类及怪物部件。

Ultimate Forge = 终极锻造台
Combine a Lv.10 piece of Gear with any Prism.
将一件10级装备与任意棱镜融合。

Creation Machine = 造物机
Combine tier 4-6 Emblems for a chance at RARE Gear.
融合4-6阶徽印，有机会获得稀有装备。
```





### · 配方标题

**Line: 3870-3949**

```
Health/Mana Recipes = 生命/魔素配方
Stamina/Misc. Recipes = 耐力/强化配方
Stamina Recipes = 耐力配方
Misc Recipes = 强化配方
Sword/Lance Recipes = 剑/长矛配方
Gun/Cannon Recipes = 枪/炮配方
Gauntlet/Staff Recipes = 魔符/法杖配方
Shield/Droid Recipes = 盾/无人机配方
Helm Recipes = 头盔配方
Armor Recipes = 盔甲配方
Ultimate Swords/Lances = 终极剑/长矛
Ultimate Guns/Cannons = 终极枪/炮
Ultimate Gauntlets/Staffs = 终极魔符/法杖
Ultimate Shields/Droids = 终极盾/无人机
Ultimate Helms = 终极头盔
Ultimate Armors = 终极盔甲
```



### · 阵营成员

**Line: 6362+**

```
Galactic Cadet = 银河舰队学员
Starlight Rebel = 星光叛军
Faust's Apostle = 浮士德使徒
Enigma Agent = 谜团特工
Junkbelt Mercenary = 废弃带雇佣兵
```



### · 死亡结算

**Line: 6852+**

```
Enemies Defeated = 击败敌人
Credits Collected = 收集信用点
EXP Acquired = 获得经验
Objectives Complete = 完成目标
Trees Chopped = 砍伐树木
Ores Mined = 开采矿石
Bugspots Harvested = 采集虫巢
Damage Taken = 承受伤害
Chests Opened = 开启宝箱
Bosses Defeated = 击败首领
Items Bought = 购买物品
```



### · 提示/警告

**Line: 7044+**

```
Cannot place that there! = 不能放置在这里！
Cannot place that there! = 不能放置在这里！
Not enough Credits! = 信用点不足！
Cannot place that there! = 不能放置在这里！
Emblems must be the same tier! = 徽印必须为同一等阶！
Insufficient Materials! = 材料不足！
Insufficient Credits! = 信用点不足！
Insufficient World Fragments! = 世界碎片不足！
This is not your ship! = 这不是你的飞船！
Insufficient Scrap Metal! = 废金属不足！
Cannot have more than one of these! = 此物品无法拥有多个！
Gear must be Lv.10! = 装备等级必须达到 Lv.10！
```



### · 对话

#### · 阵营剧情 选择支

**Line: 13638-13664**

```
Atlas and his scientists have engineered their MEGA WEAPON, and it's ready for use. The Destroyer looms over Mech City, preparing to devour the planet whole. What do you do?
阿特拉斯和他的科学家们已经制造出了他们的超级武器[MEGA WEAPON]，如今它已准备就绪。毁灭者[The Destroyer]盘踞在机械城上空，准备将整颗星球吞噬殆尽。你会怎么做？

Give me the MEGA WEAPON. I'll take on the Destroyer myself.
把超级武器交给我。我会亲自对抗毁灭者。

We must destroy the MEGA WEAPON, no one man should have all that power.
我们必须摧毁超级武器，没有任何一个人应该掌握如此强大的力量。

Actually I'm gonna side with the Destroyer and kill all of humanity.
事实上，我打算站在毁灭者一边，消灭全人类。

Roland's rebellion and Effie's army will be meeting at Mech City, the birthplace of Starlight's freedom and democracy. The result of this conflict will determine Starlight's entire future.
罗兰的叛军与艾菲的军队将在机械城会合——那里是星光帝国自由与民主的发源地。这场冲突的结果，将决定星光帝国未来的命运。

I believe Roland. Starlight deserves to govern itself, even if there is risk.
我支持罗兰。星光帝国有权进行自治，即使这其中存在风险。

I believe Effie. Starlight's leave of the Federation would be catastrophic.
我支持艾菲。星光帝国脱离联邦将会带来灾难性的后果。

Forget this political crap I'm killing everyone when I go to Mech City.
管他什么政治纷争，到了机械城我就杀光所有人。

Faust has crafted the strongest vial of Aethercite yet. You hold the syringe in your hands as he stands face up towards the sky, calling to the fabled Creator. What do you do?
浮士德制造出了迄今为止最强大的以太晶华[Aethercite]药剂。他仰面朝向天空，呼唤传说中的造物主[Creator]，而你手中握着那支注射器。你会怎么做？

Inject the liquid Aethercite into yourself. For Faust. For the Creator.
将液态以太晶华注入自己体内。为了浮士德。为了造物主。

Throw the syringe on the floor and refuse to join Faust's Church.
将注射器摔在地上，拒绝加入浮士德教会。

Stab Faust in the neck with the syringe, injecting the Aethercite into him.
把注射器刺入浮士德的颈部，将以太晶华注入他的体内。

Zeig offers you the Enigma Bomb, which is to be placed within Mech City. Despite it being filled with innocents civilians and merchants, Mech City's Destruction is your final mission.
泽格将谜因炸弹[Enigma Bomb]交给你，并要求你将它安置于机械城之中。尽管那里充满无辜的平民与商人，但摧毁机械城仍是你的最终任务。

Give me the Bomb. My loyalty lies with Gray Enigma.
把炸弹给我。我的忠诚属于灰色谜团。

I won't do it. I cannot kill thousands more innocent lives.
我不会这么做。我不能夺走数千无辜者的生命。

Gray Enigma is an immoral entity that must be destroyed!
灰色谜团是一个罪恶的组织，它必须被摧毁！
```



#### · 探索对话(含少量剧情)

```
Line 13693-13811

Lenny = 兰尼

LOOK OUT! Urugorak is heading your way and he looks hungry!!!
小心！乌拉格拉克[Urugorak]正朝你这边过来，而且看起来它饿极了！！！

I'd be careful touching those vines if I were you.
如果我是你的话，我可不会随便碰那些藤蔓。

I'm picking up a massive heat source in the area. Be careful.
我的传感器在这个区域发现了一个巨大的热源。小心点。

Oh no, it's a Hivemind! RUN TO THE PORTALS!!!
糟了，是巢灵[Hivemind]！快跑向传送门!!!

Some say these caverns are home to Rock Scarabs.
有人说这些洞窟是岩石圣甲虫[Rock Scarabs]的巢穴。

Don't mine the ore deposits. Rock Scarabs don't like that.
不要开采那些矿脉，岩石圣甲虫[Rock Scarabs]可不喜欢这样。

A Rock Scarab! GET OUTTA THERE!!!
是岩石圣甲虫[Rock Scarabs]！快跑！！！

Shroomys may seem nice, but I wouldn't get too close. Can you believe some folks keep em as pets?
蘑菇怪看起来可能很友善，但我可不想离它们太近。你相信吗，居然有人把它们当宠物养？

Oh no... Report's coming in now about a Bully Shroom in the area. Quit killing his friends!
哦不……刚刚收到报告，这片区域发现了一只蘑菇恶霸[Bully Shroom]，别再杀它的朋友了！

YOU'RE DONE FOR!!! GET TO THE PORTALS NOW!
你死定了！！！快去传送门！

Hey + name +, something doesn't feel right...
嘿，    ,我总感觉有些不对劲……

Space Pirates! They've come to steal your loot!!!
太空海盗[Space Pirates]！它们来抢你的战利品了！！！

My sensors show there's a GLITTERBUG in the area. Try to catch it for some great resources!
我的传感器显示这一块儿有一只闪光虫[GLITTERBUG]。试着抓住它，那可是大把的资源！

Incoming Meteor Shower! Get outta there, cadet!
流星雨[Meteor Shower]来袭！快跑，学员！

Touching those Plague Hives makes the Plague Beast vunerable!
触碰那些疫病虫巢会让疫病兽[Plague Beast]变得脆弱！

He's vulnerable! Attack him now!
它现在很脆弱！快攻击它！

Careful, cadet. The Infernal Watcherdemon is insanely powerful!
当心点，学员。炼狱守望恶魔[The Infernal Watcherdemon]可是非常强大的！

The Destroyer has been weakened! He can now be damaged by any weapon!
毁灭者已经被削弱了！现在任何武器都能对他造成伤害！

The Destroyer's shields are back up! Shoot it again with the MEGA WEAPON.
毁灭者的护盾恢复了！再次使用超级武器攻击它。

Oh no!! The Destroyer is wreaking havoc on Mech City! Shoot at its head with the MEGA WEAPON to weaken it!
糟了！毁灭者[The Destroyer]正在机械城肆虐！使用超级武器[MEGA WEAPON]攻击它的头部来削弱它！

The Destroyer... He killed Atlas...
毁灭者……它杀死了阿特拉斯……

Atlas defeated the Destroyer, but he died in the process...
阿特拉斯击败了毁灭者，但他也在过程中牺牲了……

THE DESTROYER IS INVINCIBLE! GET TO THE PORTALS!!!
毁灭者[The Destroyer]是无敌的！快去传送门！！！

RUN!!! THE SPACE PIRATES SET A TRAP!!!
快跑！！！太空海盗[SPACE PIRATES]设下了陷阱！！！

Uh oh... Effie looks pretty mad!
啊哦……艾菲看起来非常生气！

Roland is coming after you! Watch out!!!
罗兰正在追杀你！小心！！！

Both Roland AND Effie are attacking! Go get em, cadet!
罗兰和艾菲打过来了！去打败他们，学员！

I never got to tell him how I felt. I... I won't let YOU sabotage the Galactic Fleet, TRAITOR!
我从来没跟他说过我的感受。我……我绝不会让你破坏银河舰队，叛徒！

Line 13825+

The Creator = 造物主
Faust was a false disciple. He's unworthy of ascension and so are you... Now I shall destroy this plane of existence forever!
浮士德只是个伪信徒。他不配得到进升，你们也不配……现在，我要让这个位面陷入永恒的毁灭！

Faust's Final Form = 浮士德·最终形态
BLAAAAAAAAAARGHGHHAAAGHAHGAAAAAAAAA!
呃啊啊啊啊啊啊啊啊啊啊！

Zeig = 泽格
Uh oh. Mech City deployed a defense Mech Dragon! It already jammed our bomb!
啊哦。机械城部署了一条防御机械龙！它干扰了我们的炸弹！

Out of my way, traitor. You can't defeat me!
滚开，叛徒。你不可能战胜我！

Line 13877+
HelpBot XVII = 助手机器人 XVII

GOOD EVENING, MASTER. HELPBOT IS HERE TO HELP.
晚上好，主人。助手机器人正在待命。

YOU CAN OPEN YOUR INVENTORY WITH THE (TAB) KEY. TO ACCESS THE MENU AND VIEW OTHER CONTROLS, JUST HIT THE (ESC) KEY.
你可以使用（TAB）键打开你的物品栏。如果要进入菜单界面检视其他控制键的话，按下(ESC)键就行了。

PLZ DON'T DIE LIKE THE OTHERS, MASTER.
请别像其他人那样牺牲了，主人。

Line 14251+
WorkBot MMXII = 工作机器人 MMXII

HELLO, MASTER. WORKBOT IS HERE TO WORK.
您好，主人。工作机器人随时待命。

TIP: YOU CAN VIEW YOUR UNLOCKED RECIPES BY CLICKING ON THE BUTTON IN THE TOP RIGHT CORNER OF THE CRAFTING MENU.
提示：点击制作菜单右上角的按钮，可以查看您已解锁的配方。

ALSO, YOU CAN QUICK CRAFT ITEMS AND GEAR THAT YOU'VE ALREADY UNLOCKED BY CLICKING ON THEIR RECIPES.
此外，点击已解锁的物品配方，即可快速制作对应的物品和装备。

Gafgard = 加夫嘉德

So you wanna be a Galactic Cadet, huh?
所以，你想成为一名银河舰队学员，对吧？

Here's a tip for ya, newbie. Jump with SPACE and dash with E or Q. Jump Dashing is a lot faster than  walkin' around everywhere.
给你这个新人一个建议：按空格键跳跃，按E或Q键冲刺。跳跃冲刺可比到处走路快多了。

And don't forget to enter combat mode. Right click to pull out your weapon, and hit the 1-6 keys to use your Combat Chips.
别忘了进入战斗模式。点击鼠标右键拔出武器，然后按1-6键使用你的战术芯片。

Flora = 弗洛拉

Being a Cadet is tough work, are you sure this is the life for you?
成为一名学员可不是件轻松的事，你确定这就是你想要的生活吗？

Just be sure to put your items in the Storage Chest. Even if you get killed out there, other cadets will be able to access anything you've stored.
记得把你的物品存放进仓库。这样即使你在外面阵亡，其他学员也依然能够取用你储存的物品。

Here, have some Health Packs. Maybe they will save you one day.
来，拿些生命补给包。也许有一天它们能救你一命。

Line 14522+
Kylocke = 肯洛克

HOWDY HO, FELLOW TRAVELER. YOU SURE LOOK TASTY TODAY.
你好啊，旅行者。你今天看起来可真美味。

COME TRY YOUR LUCK AT SOME MYSTERY GIFTS AND OOH WOW I'D SURE LOVE TO EAT YOU UP.
来试试你的运气，看看能得到什么神秘礼物吧。还有，哇，我真的好想把你一口吃掉。

HERE'S A 1/100 CHANCE YOU'LL GET THE RAREST ARMOR IN ALL OF THE GALAXY. THE FABLED 4TH AGE ARMOR!
你有1/100的几率会得到整个星系中最稀有的盔甲。传说中的第四纪元盔甲！

Card Collector Zax = 卡牌收藏家 扎克斯

Hello Cadet. Have you heard about those Collector Cards people are collecting?
你好，学员。你听说过那些大伙正在收集的那些收藏卡了吗？

All Monsters have a 1/75 chance at dropping their unique Collector Card, which you can place in your ship for decoration and prestige.
所有的怪物都有1/75的几率掉落他们独特的收藏卡，你可以把它们放置在你的飞船上作为装饰，同时赢得声望。

MY collection's almost complete.
我的收藏已经快完成了。

Lenny = 兰尼

I'm gonna miss him a lot...
我会非常想念他的……

But I must say that was a great call. He ran in there like an IDIOT and got himself killed!
但我必须说，那真是个勇敢的决定。他像个傻瓜一样冲进了那里，然后送了命！

Now the entire fleet belongs to us. AND we kept his mega weapon.
现在整个舰队都属于我们了。而且我们还拥有了他的超级武器。

Together... You and I... We will rule this galaxy!
携手并肩……你和我……我们将统治这个星系！

HELLO good friend!!!
你好啊，伙计！！！

My name is LENNY and I'll be your personal navigator during missions.
我叫兰尼，我是你在执行任务期间的私人领航员。

Together we will conquer the galaxy and... UHH I mean defeat the monstrous Destroyer.
我们将携手征服整个银河系，并……呃，我是说击败那头可怕的毁灭者[The Destroyer]。

Shroomknight Wallace = 蘑菇骑士 华莱士

Hello traveler!
你好，旅行者！

I'm afraid I've forgotten the whereabouts of Shroom Castle.
我感觉自己恐怕忘了蘑菇城堡在哪来着了。

Lady Portobella will surely have my head for this!
波多贝拉女士一定会为此砍了我的脑袋的！

Well... I should lessen my burden of treasures if I hope to continue my journey.
嗯……如果我还想继续踏上旅程的话，我得丢下一些财宝来减轻我的负担。

Gromwell = 格罗姆威尔

Shh! You can hear her through the vines.
嘘！通过藤蔓你能听到她的声音。

I, the great Gromwell, BOUNTY HUNTER OF THE JUNGLE, will slay the beastly Hivemind.
我，伟大的格罗姆威尔，这片丛林的赏金猎人，将会消灭那只野兽般的巢灵。

She stands no match against my GALACTIC FLAMEBLASTER.
在我的银河爆焰面前她根本没有一战之力。

In case you run into her before I do, why don't you take this!
以防你在我之前就碰到了她，不如把这个给带上吧！

Cobalt Maga Perceval = 钴蓝法师 帕西瓦尔

Meow.
喵。

I'm on a pilgrimage to the Cobalt Citadel.
我正要前往钴蓝城堡朝圣。

I don't have time to hobnob with adventurers like you.
我没时间跟你们这些冒险家闲聊。

But alas, I admire your cause. Here's something I found on the ground a second ago.
不过啊，我很欣赏你现在在做的事。这是我不久之前在地上找到的。

Dragonslayer Ringabolt = 屠龙者 林戈伯特

No... Please don't!
不……请别这样！

I only... Wanted to help...
我只是……想帮忙……

Greetings.
你好。

My Combat Squad was ordered to hunt down the fabled Lava Dragon.
我的战斗小队接到命令，要去狩猎传说中的熔岩龙[Lava Dragon]。

But it seems as though I've beamed to the wrong planet...
不过看起来我似乎被传送到了错误的星球……

In any case, I'd like to grant you this gift, fellow traveler! Send my regards to that big oaf Wallace.
不管怎样，我想把这件礼物送给你，同路人！替我向那个大白痴华莱士问好。

Dune Dredger Winston = 掘沙者 温斯顿

What a pleasure it is to meet a follower of Faust!
真是让人惊喜！竟然能遇见一位浮士德的追随者！

He's wrong.
他错了。

Don't trust this fool. I've dug up all the information about his experiments. He TRICKS people into thinking they will achieve some divine reward...
别相信那个骗子。我已经查到了关于他实验的所有信息。他欺骗了大家，让他们以为会得到某种神圣的恩赐……

Only to be injected with lethal Aethercite into their bloodstreams. He has created MONSTERS.
他们血液里被注射的，只有致命的以太晶华。他创造了那些怪物。

I've updated your portal uses, please go to his Cathedral and see for yourself! We must put an end to Faust's madness.
我已经更新了你的传送门使用次数，亲自去他的圣堂看看吧！我们必须结束浮士德的疯狂行为。

Oh, you startled me!
哦，你吓了我一跳！

I long to travel to other places like you, but this desert is my prison.
我渴望像你一样四处游历，但这个沙漠却像一座囚笼困住了我。

Maybe one day I could follow you into that portal...
或许有朝一日，我能跟着你进入那个传送门……

Oh what's this hidden in the sand!?
哦，那个藏在沙子里的东西是什么！？

Broccolius Seizer = 西兰骑士 塞泽尔

In my many adventures I've never seen a planet in such peril.
在我无数次冒险旅途中，从未见过一颗星球陷入如此危急的境地。

Starlight is a planet of peace. It was one of the first planets to establish itself as a world completely united, and was very capable of governing itself.
星光是一颗和平的星球。它是最早建立起完全统一政权的星球之一，并且曾拥有高度自治的能力。

Roland knows that Starlight's power is slipping away while it remains in the Galactic Federation.
罗兰知道，星光帝国加入银河联邦后，它的力量正在逐渐衰退。

Go speak to Ringabolt in the Desolate Canyon. He's ot a top secret document that will shed light on the corruption going on within the Galactic Federation.
去荒凉峡谷找林戈伯特吧。他手里有一份绝密文件，能够揭露银河联邦内部正在发生的腐败真相。

Hmmmmmmm?
嗯——？

I know, this is a rather cold planet for a Veggyknight.
我知道，对于一名蔬菜骑士来说，这颗星球确实有些寒冷。

What? You've seen Dragonslayer Ringabolt!? That hammer-headed buffoon owes me a rematch.
什么？你见过屠龙者林戈伯特！？那个锤子头蠢货还欠我一场复赛呢。

I've managed to salvage this from the junk I bought in Mech City. Take it!
我设法将这个我在机械城买的东西从垃圾堆中抢救了出来。拿去吧！

Djinnsmith Bolgon = 魔灵铁匠 伯尔根

BLUH BLUH.
呼呼。

Bolgon craft BIG WEAPON. Just need BIG MATERIAL to make.
伯尔根打造巨大的武器。只要把巨大的材料交给伯尔根就行。

Find me material. I make weapon for you.
帮我找到材料。我就帮你打造武器。

you Bolgon's friend.
你是伯尔根的朋友。

Line 15113+
Lenny = 兰尼

I wouldnt talk to him if I were you...
如果我是你的话，我是不会跟他说话的……

We're not really sure where he came from. He doesn't seem to speak very much.
我们不清楚他是从哪来的。他平时的话也不多。

And what the heck kind of tool is that in his hands? Seems primitive.
而且，他手中的那个工具到底是什么玩意儿？看起来也太原始了。

Hmm... He's selling some sort of ticket. But who in their right mind would pay so many credits!? What a scam.
嗯……他正在卖什么票。但是有谁会出这么大一笔钱呢！？真是个大骗子。

Atlas = 阿特拉斯

(Atlas' cold body is nearly torn apart.)
(阿特拉斯冰冷的身体几乎已经支离破碎。)

(You find something next to him...)
(你在他旁边找到了一些东西……)

Line 15714+
Ringabolt's Corpse = 林戈伯特的尸体

(Ringabolt's mutilated corpse is propped up, his own axe lodged into his armor.)
(林戈伯特残破的尸体被架在那里，他自己的战斧贯穿了他的盔甲。)

(Something falls onto the floor...)
(有什么东西掉到了地上。)

(Poor Ringabolt... Who could have done this?)
(可怜的林戈伯特……究竟是谁干的？)

Line 16453+

Monster Crafter Olaf = 怪物匠 奥拉夫

Good day to you, cadet.
日安，学员。

Here are your universal records!
这是你的通用记录！

This monster is one of my greatest creations.
这只怪物是我最伟大的造物之一。

Once you beam to the planet you selected, my creation will attack! Good luck, cadet!
一旦你传送到所选择的星球，我的造物就会发动攻击！祝你好运，学员！

Jonathan = 乔纳森

Whoa chill bro, I'm friendly.
喂，冷静点，兄弟，我没有恶意。
```



#### · 主要剧情NPC对话

```
Line 13900+
Captain Atlas = 阿特拉斯舰长
This damn Aether Reactor ain't workin' anymore. Looks like I'll need a brand new Aethercrystal to get this up and running again.
这该死的以太反应堆已经无法工作了。看来我需要一块全新的以太晶石[Aethercrystal]才能让它重新运转起来。

Hey you're a strong and smart cadet. Why don't ya grab me one in the Desolate Canyon. I hear they drop off of those big round Tyrannog monsters.
嘿，看起来你是个强大而又聪明的学员。不如去荒凉峡谷帮我找一块？听说那些又大又圆的泰伦罗格[Tyrannog]怪物身上会掉落这种东西。

Just uhh don't get bit.
只是……别被咬了。

Good job getting the Aethercrystal, cadet!
干得好，学员！你拿到了以太晶石！

With our reactor back online we'll be able to see the Destroyer's whereabouts.
反应堆重新启动后，我们就能追踪毁灭者[The Destroyer]的位置了。

Lucky for us, our scientists have begun research on a MEGA WEAPON that might be able to defeat the Destroyer. I'll get back to you when they've developed something.
幸运的是，我们的科学家已经开始研究一种可能击败毁灭者[The Destroyer]的超级武器[MEGA WEAPON]。等他们取得成果后，我会再联系你。

In any case, it seems there's a pretty huge disturbance coming from the Ancient Ruins system. Why don't you go check it out and report back to me.
总之，远古遗迹星系似乎传来了巨大的异常波动。你不妨先去那里调查一下，然后再回来向我汇报。

Go check out the Ancient Ruins and report back to me.
去调查远古遗迹，然后回来向我汇报。

I can't believe you came face to face with the Destroyer and lived to tell the tale.
我真不敢相信你竟然与毁灭者面对面相遇后还能活着回来讲述这一切。

The Destroyer is eating up planet cores at an astounding rate. We don't have much time to save what's left of this galaxy.
毁灭者正在以惊人的速度吞噬星球核心。我们已经没有多少时间拯救这个银河系剩下来的部分了。

I'll be sending out cadets and scientists to gather the required materials for our MEGA WEAPON, and you need to be out there helping!
我会派遣学员和科学家去收集制造超级武器所需的材料，而你也务必继续在外协助！

Reports say there's a wild Celestial Slug roaming the Hollow Caverns. Go gather some resources off of it\nand bring em back here.
报告称，一只野生天界蛞蝓[Celestial Slug]正在空寂洞窟中游荡。去从它身上收集一些资源，然后带回来。

Thanks for the Magicite. This stuff seems pretty odd; it's not even from our galaxy.
谢谢你的魔法晶石。这东西似乎非常奇特，它甚至并不属于我们的银河系。

Bring me some resources from the Celestial Slug in the Hollow Caverns!
带一些来自空寂洞窟的天界蛞蝓[Celestial Slug]的资源回来！

Fantastic! We've got all the required materials in order for the MEGA WEAPON to function properly thanks to you.
太棒了！多亏了你，我们已经收集齐了让超级武器正常运作所需的全部材料。

The last bit of materials needed are 100 Planet Stones, 50 Oricalcum, and 20 Flamethysts.
最后还需要100个行星岩晶[Planet Stone]、50个奥里哈钢[Oricalcum]以及20个炽焰晶石[Flamethyst]。

Hurry back with these materials so we can launch a full scale assault on the Destroyer!
快带着这些材料回来，这样我们就能对毁灭者发动全面攻击！

This weapon... We could defeat the Destroyer and then rule the galaxy...
这件武器……我们可以击败毁灭者，然后统治整个银河系……

NO ONE CAN STAND IN OUR WAY.
没.有.人.能.够.阻.挡.我.们。

You better hurry up. The Destroyer is about to swallow Mech City's planet core.
你最好快一点。毁灭者马上就要吞噬机械城的星球核心了。

Good luck, cadet. I believe in you.
祝你好运，学员。我相信你。

You fool! I'll go to Mech City myself and rid the galaxy of the Destroyer myself!
蠢货！我要亲自前往机械城，亲手消灭毁灭者！

So much power... No one will ever stand in my way!
如此强大的力量……再也没有人能够阻挡我！

WHAT!? How could you...
什么！？你怎么能……

You were my favorite cadet. You had such potential...
你曾是我最看好的学员。你本拥有如此巨大的潜力……

Guess I'll have to kill the Destroyer myself. Out of my way, traitor!
看来只能由我亲手消灭毁灭者[The Destroyer]了。给我让开，叛徒！

The galaxy is saved because of you, cadet.
银河系因你而得救，学员。

Not only is the galaxy free of the Destroyer, but the Galactic Fleet now has the strongest weapon of all. We'll be putting it to good use.
银河系不仅摆脱了毁灭者的威胁，银河舰队如今也拥有了最强大的武器。我们会好好利用它。

HEY! Who allowed you to enter my headquarters?
嘿！谁允许你进入我的指挥部？

I only speak to cadets of the Galactic Fleet.
我只和银河舰队的学员交谈。

So... Get up on outta here. NOW!
所以……赶紧给我离开这里。就现在！

Line 14342+

Minister Odin = 奥丁神官

Greetings, true believer.
欢迎你，真正的信徒。

The Divine prophet himself seeks your audience. Search for him in the Hollow Caverns system.
神圣先知本人希望和你见一面。请前往空寂洞窟星系寻找他。

Trust in Faust. He's seen them.
相信浮士德。他已经见过他们。

This is good news. I've had faith in Faust since the beginning.
这是个好消息。从一开始，我就一直相信浮士德。

He has helped so many. Beings of all types may go visit him in his Cathedral, to ascend and become one with the Creator.
他曾向无数生命伸出援手。所有种族的存在都可以前往他的圣堂，在那里进升，并与造物主[The Creator]融为一体。

I've sent hundreds of people to his cathedral, all of whom will be enlightened about our galaxy and place in the universe.
我已经将数百人指引向他的圣堂，他们都将在那里领悟银河的真相，以及自身在宇宙中的位置。

Now you must do your part in the Grand Ascension. Go spread the word of Faust to the Dredger within the Ancient Ruins.
现在，你必须为“伟大的进升”贡献自己的力量。前往远古遗迹，将浮士德的教义传播给那里的掘沙者。

No... That couldn't have been the Creator. You cannot kill a god!
不……那不可能是造物主[The Creator]。你不可能杀死神明！

There are more... There must be more... I cannot go on without his comforting gaze upon our galaxy...
还有更多……一定还有更多……如果不被银河之上他那安抚众生的目光所注视，我无法继续前行……

It is a shame that you decided to leave our church. I have taken your place as Faust's true disciple and will be ascending soon...
很遗憾，你选择离开了我们的教会。我已经取代了你的位置，成为浮士德真正的门徒，并即将完成进升……

Where is Faust? Why don't I feel his presence anymore?
浮士德在哪？为什么我再也感受不到他的存在？

Praise be to Faust, our true prophet and messenger of the great Creator.
赞美浮士德，伟大造物主真正的先知与使者。

Oh you poor soul. You do not seem to be a follower of Faust.
哦，可怜的灵魂。看来你并不是浮士德的追随者。

He has seen them. We are closer now more than ever to the Grand Ascension.
他已经见过他们。如今，我们比任何时候都更加接近“伟大的进升”。

Line 15191+

Rebel Roland = 反抗军 罗兰

Don't listen to her. Starlight MUST leave the Galactic Federation!
别听她的。星光帝国必须脱离银河联邦。

We've fought for our independence from tyrannical governments before. This is no different.
我们曾经为了摆脱暴政统治而战。这一次也没什么不同。

Please, bring back 10 Orichalcum and give them to me. Don't fall for her lies!
拜托了，带10块奥利哈钢[Orichalcum]回来给我。别中了她的谎言！

Thanks a ton! With this Orichalcum we can construct some weapons in case the Galactic Federation decides to come for us.
太感谢了！有了这些奥利哈钢[Orichalcum]，我们就能制造一些武器，以防银河联邦决定对我们动手。

This rebellion is the single greatest event of our history. Leaving the corrupt Galactic Federation will allow us to soar to new heights as a free planet!
这场反抗是我们历史上最伟大的事件。离开腐败的银河联邦后，我们这个自由星球必将迈向新的高度！

Effie is just a pawn of the Federation scum! I've dedicated the rest of my life to bringing Starlight out of the darkness and into true sovereignty.
艾菲不过是联邦走狗手中的一枚棋子！我愿用余生让星光摆脱黑暗，获得真正的自治权。

I don't know anything about these Space Pirates. This was just a publicity ruse that Effie planned!
我从没听说过那些太空海盗。这不过是艾菲策划的一场宣传骗局！

How convenient is it that the evil ROLAND would illegaly hire Space Pirates to steal Starlight's Treaty.
真是太巧了，邪恶的“罗兰”竟然会非法雇佣太空海盗去偷走星光帝国的条约。

Don't believe her for one second. Please, speak to Broccolius Seizer in the Byfrost. He'll convince you that I'm right about Starlight.
她说的一点也别信。去霜境找西兰骑士塞泽尔，他会让你明白，我对星光帝国的看法才是正确的。

Ringabolt... He was MURDERED! He had what our Rebellion needed to thwart the evil Galactic Federation.
林戈伯特……他被杀害了！他拥有我们反抗军击败邪恶银河联邦所需要的东西。

Effie has deeply rooted ties within the Galactic Federation. She is CORRUPT!
艾菲与银河联邦有着根深蒂固的关系。她已经被腐化了！

It's all over now... I suppose Starlight will be staying in the Galactic Federation and we'll lose all power and sovereignty.
一切都结束了……看来星光帝国会继续留在银河联邦，而我们将失去所有力量与自治权。

I knew you would make the right choice.
我就知道你会做出正确的选择。

Come join me brother, and we'll fight for Starlight's freedom!
加入我吧，兄弟！我们将为星光的自由而战！

What!?! You TOO!? How could you be a such blind pawn in Effie's plans!?!?
什么！？你也一样！？你怎么能成为艾菲计划中如此盲目的棋子！？

You're on the wrong side. Freedom will be victorious in the battle in Mech City.
你站错了队。自由将在机械城之战中赢得胜利。

If you won't help me, then you're my enemy!
如果你不愿帮助我，那你就是我的敌人！

If I see you on the battlefield, I'll kill you myself.
如果我们在战场上相遇，那我会亲手解决你。

We did it. Effie and the Galactic Federation will bother Starlight no more!
我们成功了。艾菲和银河联邦再也无法干涉星光帝国！

A victory well earned, my friend. Starlight's bright future is all thanks to you.
这是一场来之不易的胜利，我的朋友。星光帝国光明的未来，全都归功于你。

You don't look like you're part of the Rebellion.
你看起来不像反抗军的人。

Get lost, buddy. Something real bad is about to happen to my home planet!
走开，伙计。我的母星马上就要发生大事了！

Line 15444+

Starlight Effie = 星光执政 艾菲

Roland is full of nonsense. Starlight won't last a year without being governed by the Galactic Federation.
罗兰满口胡言。如果没有银河联邦的治理，星光帝国连一年都撑不过去。

Economic instability, chaos, and an uncertain future lies with us if we decide to leave.
如果我们选择离开联邦，等待我们的将是经济动荡、混乱，以及无法预测的未来。

Don't listen to Roland!
不要听信罗兰的话！

Starlight is a planet that flourishes because it is a member of the Galactic Federation.
星光帝国正是因为加入了银河联邦，才能繁荣发展至今。

This talk of corruption and 'freedom' is just propoganda to convince people to help further his twisted agenda.
所谓“腐败”和“自由”的言论，不过是他为了煽动民众、推进他的扭曲计划而制造的宣传。

Please go to the Deep Jungle for me and find the Starlight Treaty that was conveniently stolen from us. I won't let Roland plunge Starlight into an age of chaos!
请替我前往幽深丛林，找回那份被“恰巧”偷走的星光条约。我绝不会让罗兰将星光帝国拖入混乱时代！

This treaty... This will change everything! This is the last piece of the puzzle that will convince Starlight to stay within the Federation.
这份条约……它将改变一切！这是说服星光帝国继续留在联邦的最后一块拼图。

What!? Someone hired SPACE PIRATES to steal and guard this treaty!?
什么！？竟然有人雇佣太空海盗来偷走并守住这份条约！？

I'm asking you, PLEASE don't trust Roland. His rebellion has only caused a divide within Starlight. His motives may not be what you think they are!
我请求你，千万不要相信罗兰。他的反抗只会让星光帝国内部分裂。他的动机可能远没有你想象的那么正义！

That Broccolius... He's nothing but a sneaky Vegggie Knight that will do anyone's bidding for the right price.
那个西兰骑士……不过是个卑鄙的蔬菜，只要价格合适，就会为任何人效劳。

Roland thinks he can rule Starlight all by himself without the aid of the federation. Nonsense!
罗兰以为没有联邦的帮助，凭他一个人就能统治星光帝国。简直荒谬！

Ringabolt's death was not my doing.
林戈伯特的死与我无关。

Roland has a murky history of weird events and odd deaths littered throughout his campaign.
罗兰的行动中充满了可疑事件和离奇死亡，他的过去一直笼罩在迷雾之中。

This was probably his last effort to convince you and Starlight's people of how 'corrupt' the federation is. He'll stop at nothing to further his agenda!
这很可能是他最后一次试图让你和星光帝国的人民相信联邦“腐败”。为了实现自己的目的，他会不择手段！

So what will it be, citizen of Starlight? Will you help me preserve our home planet's security? or join Roland and grant HIM ultimate power over Starlight?
那么，星光帝国的公民，你的选择是什么？你会帮助我守护我们的家园？还是加入罗兰，让他获得支配星光帝国的至高权力？

NO! You can't possibly be siding with him!
不！你不可能真的站在他那一边！

My army and I will decimate you and Roland. We will continue to keep Starlight a prosperous planet!
我和我的军队会彻底击败你和罗兰。我们会继续守护星光帝国的繁荣！

I knew you would make the right choice.
我就知道你会做出正确的选择。

Together we will defeat Roland and his twisted agenda once and for all.
我们将共同击败罗兰，以及他那扭曲的计划，让这一切彻底结束。

Fine, I'll destroy you too.
好吧，那我也会摧毁你。

Out of my way!
别挡我的路！

We did it. Roland's rebellion has been quelled and Starlight will remain in the Galactic Federation.
我们成功了。罗兰的反抗已经被平息，星光帝国将继续留在银河联邦之中。

Everything always falls into place...
一切终究都会回归正轨……

You don't look like you're a denizen of Starlight.
你看起来不像是星光帝国的公民。

I don't have time to deal with outsiders like you!
我没时间处理你这样的外来者！

Line 15776+

Faust = 浮士德

(He murmurs to himself, not even noticing your existence.)
(他低声自语着，甚至没有注意到你的存在。)

I see you've met with Minister Odin.
看来你已经见过奥丁神官了。

The beings in the sky... I've finally seen them. When one injects siphoned Aethercite into their bloodstream, their senses become heightened and unbound.
天空中的那些存在……我终于见到他们了。当提炼出的以太晶华注入血液，感官便会得到强化，突破束缚。

But we need more. Bring me 100 Ashen Dust and I'll be able to start the brewing process.
但我们还需要更多。带给我100份灰烬尘[Ashen Dust]，我就能开始调制。

Yes... This is what we needed!
是的……这正是我们需要的东西！

Bring me 100 Ashen Dust and I'll be able to start the brewing process.
带给我100份灰烬尘[Ashen Dust]，我就能开始调制。

The beings in the sky called out to me... They said the Creator is returning.
天空中的存在向我传达了讯息……他们说，造物主[The Creator]即将归来。

We must forge him a gift. Go to Minister Odin and report my findings, so he may spread the word of Faust.
我们必须为他准备一份礼物。去，把我的发现告诉奥丁神官，让他将浮士德的教义传播出去。

(Faust's eyes are closed as he hums lightly.)
(浮士德闭着双眼，轻声哼唱着。)

I see you've made it to my cathedral. What do you think? It's BEAUTIFUL, isn't it!?
我看你已经来到我的圣堂了。感觉如何？它很美，不是吗！？

More and more believers are coming to me. They are all ascending and becoming one with the Creator's visions.
越来越多的信徒来到我身边。他们都在进升，并与造物主的意志融为一体。

But you are my most valuable follower. The strongest, for sure. I've got something VERY special for you...
但你是我最重视的追随者。毫无疑问，你也是最强大的那个。我为你准备了一件非常特别的东西……

I've concocted the strongest catalyst for my strongest follower...
我为我最强的追随者调制出了最强的催化剂……

YOU WILL FINALLY BECOME ONE WITH THE CREATOR.
你.终.于.将.与.造.物.主.融.为.一.体

Yes... Now you are ready for the true test. Use your new found power to defeat the CREATOR himself.
是的……现在，你已经准备好接受真正的考验。使用你新获得的力量，击败造物主[The Creator]本身。

We shall rule the Galaxy and become gods walking amongst mere mortals! Come with me, to Mech City!
我们将统治银河，成为行走于凡人之间的神明！跟我来，前往机械城！

You... You have forsaken me!?
你……你竟然背弃了我！？

I shall meet with the Creator MYSELF in Mech City. You gave up immortality, you pathetic FOOL!
我要亲自在机械城面见造物主[The Creator]。你竟然放弃了永生，你这个可悲的蠢货！

NO! I CANNOT HANDLE THIS AMOUNT OF AETHER...
不！我无法承受如此大量的以太……

I'VE BEEN BETRAYED...
我.被.背.叛.了……

MECH. CITY.
机.械.城。

Good job, my follower.
干得不错，我的追随者。

Together we will ascend time and space and create many things of our own. We are now The Creators.
我们将共同超越时间与空间，创造属于我们自己的万物。现在，我们就是造物主[The Creators]。

You've chosen machines over our Creator.
你选择了机器，而不是我们的造物主。

But he has still chosen you.
但他依然选择了你。

You must be so proud of killing me.
杀死我一定让你感到无比自豪吧。

What is that? You're confused?
怎么了？你感到困惑？

You've forgotten that I am Faust, the Creator's true prophet.
你忘了吗？我是浮士德，是造物主[The Creator]真正的先知[Prophet]。

In another dimension you've already helped me ascend time and space. I am everywhere, I am everything.
在另一个维度中，你已经帮助我超越了时间与空间。我无处不在，我即是一切。

Now excuse me while I alter reality to my liking.
现在请允许我按照自己的意愿改变现实。

Get away from me, you pathetic fool!
离我远点，你这个可悲的蠢货！

I've got no time for non-believers.
我没有时间浪费在不信者身上。

Line 16070+

Commander Zeig = 指挥官 泽格

It's good to see a strong operative join our ranks.
很高兴看到一名强大的行动探员加入我们的行列。

Now for your first real assignment, agent!
现在，特工，你将迎来第一个真正的任务！

Gather up 50 Monster Claws for me. These planets need some cleaning up with all of these monsters roaming around.
为我收集50个怪物爪[Monster Claw]。这些星球上到处都是游荡的怪物，是时候清理一番了。

Really? A puny combat level of + this.GetPlayerLevel() + ?
真的？只有区区[]的战斗等级？

Get out in the field. Come back when you're a little more experienced.
去外面历练吧。等你积累更多经验后再回来。

Took you long enough.
你可真够慢的。

You're looking to be the top of the class, agent.
看来你想成为同批里最顶尖的那个啊，特工。

It's a shame almost all new agents die during this next mission...
真可惜，几乎所有新人都会死在接下来的任务中……

Go to the Hollow Caverns and slay a Gruu. They are always interfering with our mining operations.
前往空寂洞窟，消灭一只格鲁[Gruu]。它们总是在干扰我们的采矿行动。

Hmm I'm afraid you're not quite ready for the next task.
嗯……恐怕你还没有准备好接受下一个任务。

Come back when you're a higher combat level. The next task will be quite... Tough.
等你的战斗等级更高一些再回来。下一个任务会非常……艰难。

Nice job with slaying a Gruu. Those ones are pretty tough.
你干掉格鲁了？干得不错。那些家伙确实很难对付。

You've proven yourself to be quite the killing machine...
你已经证明了自己是一台真正的杀戮机器……

...So now you're going to assassinate someone for us.
……所以现在，你要替我们去暗杀一个人。

I just got a tip from this Starlight chick. She wants one of our operatives to go to the Desolate Canyon and assassinate some Red-Armored guy.
我刚收到一个来自星光帝国那个女人的消息。她希望我们派一名行动探员前往荒凉峡谷，暗杀一个身穿红色盔甲的家伙。

I'll be sending YOU on this one. Prove your loyalty to the Enigma.
这次我会派你去。证明你对谜团的忠诚。

Head over to the Desolate Canyon. Kill that Red-Armored guy named Ringabolt.
前往荒凉峡谷。杀掉那个名叫林戈伯特的穿红色装甲的家伙。

Wow, I didn't think you'd do it.
哇，我没想到你真的做到了。

You're shaping up to be one of our greatest agents, my friend.
我的朋友，你正在成长为我们最优秀的一位特工。

Hold on, getting another call right now.
等一下，我现在有个通讯。

"(Yes? Uh-huh. Are you sure?)
(喂？嗯……你确定吗？)

(Alright. Jeez ok I got it.)
(好吧……行，我明白了。)

I hate to do this to you bud, but you've got one more big job to do...
我真不想让你做这个，伙计，但你还有最后一个重要任务……

Gray Enigma isn't for everyone. We do all the dirty work.
灰色谜团并不适合所有人。我们负责处理所有见不得光的工作。

Our clients pay us large sums of credits to do things that no one else will.
我们的客户支付大量信用点，让我们完成其他人不愿做的事情。

The Galaxy has been shaped and molded into what it is today by the hands of Gray Enigma's ruthless operatives.
银河如今的模样，正是由灰色谜团那些冷酷无情的行动探员一手塑造而成。

And YOU are our most ruthless operative...
而你……正是我们最冷酷的行动探员……

...Which is why we need you to blow up all of Mech City.
……所以我们需要你摧毁整座机械城。

I knew your loyalty was with us.
我就知道你的忠诚属于我们。

Godspeed, Enigma Agent.
愿你一路顺风，谜团特工。

Typical. An Agent full of promise throws his talents away...
老套的剧本。一个本该大有作为的特工，竟然浪费了自己的才能……

Looks like I'll have to do the job myself. Mech City will be destroyed.
看来只能由我亲自动手了。机械城必须被摧毁。

You've made a grave mistake...
你犯下了一个严重的错误……

Don't wander into Mech City, now. Gray Enigma doesn't take kindly to defectors.
别踏入机械城。灰色谜团可不会善待叛徒。

Who would've thought Mech City had a defense like that!?
谁能想到机械城竟然拥有那样的防御系统！？

Looks like we'll have to try destroying Mech City again one day...
看来总有一天，我们必须再次尝试摧毁机械城……

You missed out on becoming something great.
你错过了成为大人物的机会。

Get out of my face!
从我眼前消失！

Hmm...
嗯……

You don't have what it takes to join Gray Enigma.
你没有加入灰色谜团的资格。

We only train the best operatives in the Galaxy.
我们只培养银河中最优秀的行动探员。
```



### · 改装模块

```
Line 19728+/24761+
BonusVIT+ = 体质强化+
BonusSTR+ = 力量强化+
BonusDEX+ = 敏捷强化+
BonusTEC+ = 科技强化+
BonusMAG+ = 魔法强化+
BonusFTH+ = 信仰强化+
ResistHeat+ = 抗火+
ResistFrost+ = 抗寒+
ResistPoison+ = 抗毒+
ProjectileRange+ = 射弹距离+
CritRate+ = 暴击率+
CritDmg+ = 暴击伤害+
HealthRegen+ = 生命回复+
ManaRegen+ = 魔素回复+
StaminaRegen+ = 耐力回复+
MoveSpeed+ = 移动速度+
DashSpeed+ = 冲刺速度+
JumpHeight+ = 跳跃高度+
OreHarvest+ = 矿物采集+
PlantHarvest+ = 植物采集+
MonsterDrops+ = 怪物掉落+
BugHarvest+ = 昆虫采集+
ExpBoost+ = 经验加成+
CreditBoost+ = 信用点加成+
(Empty) = -空槽位-
```



### · 战术芯片

#### 战术芯片

```
Line 23588+
Swiftness = 迅捷
Vitality I = 体质 I
Strength I = 力量 I
Dexterity I = 敏捷 I
Tech I = 科技 I
Intelligence I = 魔法 I
Faith I = 信仰 I
Photon Blade = 光刃环绕
Dancing Slash = 迅舞斩
Triple Shot = 三重射击
Atalanta's Eye = 阿塔兰忒之眼
Plasma Grenade = 等离子手雷
Gadget Turret = 装置炮塔
Blaze = 烈焰
Shock = 雷击
Healing Ward = 治疗结界
Bubble = 泡泡护盾
Berserk = 狂暴
Megaslash = 巨刃回旋
Hyperbeam = 超能光束
Trickster = 诡影
Quadracopter = 四旋翼机
Cluster Bomber = 集束轰炸
Inferno = 炼狱
Enhanced Mind = 提神
Angelic Augur = 天使神谕
Prism = 棱镜护盾
Darkfire = 暗焰

Alacrity = 活化/迅捷（你谁？）
Vitality X = 体质 X
Strength X = 力量 X
Dexterity X = 敏捷 X
Tech X = 科技 X
Intelligence X = 魔法 X
Faith X = 信仰 X

Alacrity = 
Vitality II = 体质 II
Strength II = 力量 II
Dexterity II = 敏捷 II
Tech II = 科技 II
Intelligence II = 魔法 II
Faith II = 信仰 II
```



#### 战术芯片说明

```
+7 Movement speed for 20 seconds.
移动速度提升7点，持续20秒。

+3 Vitality = +3 体质
+3 Strength = +3 力量
+3 Dexterity = +3 敏捷
+3 Tech = +3 科技
+3 Intelligence = +3 魔法
+3 Faith = +3 信仰

Summon massive blades of energy that rotate around you for 20 seconds. Damage scales with Strength.
召唤巨大的能量之刃环绕自身旋转，持续20秒。伤害受力量属性加成。

Dash towards the mouse cursor, shooting a ball of energy in the opposite direciton. Damage scales with Strength.
朝鼠标指向方向冲刺，并向相反方向射出能量球。伤害受力量属性加成。

Next attack with a Gun or Cannon will fire 3 projectiles.
下一次使用枪或炮攻击时，发射3枚投射物。

Summon Atalanta's Eye at the mouse cursor. All Gun or Cannon projectiles that pass through will deal bonus damage. Scales with Dexterity.
在鼠标位置召唤阿塔兰忒之眼。所有穿过它的枪械或炮类投射物都会造成额外伤害。效果受敏捷属性加成。

Throw a Plasma Gadget towards mouse cursor. It explodes after a short duration. Scales with Tech.
向鼠标位置投掷等离子装置，短暂延迟后爆炸。效果受科技属性加成。

Summon a small turret that fires towards your cursor. Scales with Tech.
召唤一座小型炮塔，向鼠标指向方向攻击。效果受科技属性加成。

Conjure a ball of fire that hurls towards the mouse cursor. Scales with Magic.
凝聚一枚火球，向鼠标位置投射。效果受魔法属性加成。

A bolt of lightning deals damage in a vertical pillar. Scales with Magic.
召唤一道雷电柱造成伤害。效果受魔法属性加成。

Summon a Healing Ward at your location, healing allies 1HP per second. Duration is equal to your Faith stat.
在当前位置召唤治疗结界，每秒为友方恢复1点生命值。持续时间等于你的信仰属性。

All nearby allies gain a bubble shield for 20 seconds, Reducing the next hit by 1/4th of your Faith stat. Damage reduction caps at 25.
附近所有友方获得持续20秒的泡泡护盾。护盾可减少下一次受到伤害，减伤值为你信仰属性的四分之一，最高减少25点伤害。

Double your STR for 15 seconds.
力量提升至2倍，持续15秒。

Summon massive blades of energy that rotate around you for 20 seconds. Damage scales with 2x Strength.
召唤巨大的能量之刃环绕自身旋转，持续20秒。伤害受2倍力量属性加成。

Fire a huge beam that scales with 5x DEX.
发射巨大的光束。伤害受5倍敏捷属性加成。

When equipped with a gun or cannon, gain 15 Movement speed, 15 dash speed, and 25% chance to nullify damage for 20 seconds.
装备枪械或炮类武器时，移动速度提升15，冲刺速度提升15，并有25%概率免疫伤害，持续20秒。

Summon a Quadracopter that shoots 15 projectiles. Scales with 3x TEC.
召唤四旋翼无人机，发射15枚投射物。效果受3倍科技属性加成。

Summon 20 Plasma Grenades over 10 seconds.
在10秒内召唤20枚等离子手雷。

Shoot a fast fireball that ricochets around your mouse cursor for 5 seconds. Scales with MAG.
发射高速火球，使其在鼠标位置附近反弹，持续5秒。效果受魔法属性加成。

Recover 70 Mana over 35 seconds.
在35秒内恢复70点魔素。

Summon a Healing Augur at your location, healing allies 2HP per second. Duration is equal to your Faith stat.
在当前位置召唤愈疗神谕，每秒为友方恢复2点生命值。持续时间等于你的信仰属性。

All nearby allies gain a prism shield that nullifies all incoming status effects. Duration is equal to FTH/6.
附近所有友方获得棱镜护盾，可免疫所有受到的异常状态。持续时间等于信仰属性的六分之一。

+15 Vitality = +15 体质
+15 Strength = +15 力量
+15 Dexterity = +15 敏捷
+15 Tech = +15 科技
+15 Intelligence = +15 魔法
+15 Faith = +15 信仰

Darkfire rotates around you for 20 seconds. Damage scales with MAG+VIT.
暗焰环绕自身旋转，持续20秒。伤害受魔法与体质属性共同加成。

+7 Vitality = +7 体质
+7 Strength = +7 力量
+7 Dexterity = +7 敏捷
+7 Tech = +7 科技
+7 Intelligence = +7 魔法
+7 Faith = +7 信仰
```



### · 敌人

**Line 23977+**

```
Shmoo = 什穆
Eyepod = 眼荚
Dunebug = 沙丘虫
Worm = 蠕虫
Wasp = 黄蜂
Urugorak = 乌拉格拉克
Sluglord = 蛞蝓领主
Slugmother = 蛞蝓之母
Chamcham = 查姆查姆
Rhinobug = 犀牛虫
Hivemind = 巢灵
Glibglob = 粘团
Slime = 史莱姆
Rock Spider = 岩蜘蛛
Sploopy = 鳞团怪
Rock Scarab = 岩石圣甲虫
Shroom = 蘑菇
Blue Shroom = 蓝蘑菇
Shroom Bully = 蘑菇恶霸
Relicfish = 遗迹鱼
Ancient Guard = 远古守卫
Ancient Beast = 远古巡兽
Roach = 沙螂
Ancient Golem = 远古魔像
Squirm = 蠕首
Plague Caster = 疫病法施
Glitterbug = 闪光虫
Plaguebeast = 疫病兽
Space Pirate = 太空海盗
Wicked = 小邪灵
Wisp = 幽火
Yeti = 雪怪
Mammoth = 猛犸
Wyvern = 双足飞龙
Lava Blob = 熔岩粘团
Fire Slime = 火史莱姆
Lava Dragon = 熔岩龙
```



### · 可持有物

#### 武器

```
Line 24098+
Aetherblade = 以太之刃
Bolt Edge = 雷电之锋
Colossus = 巨像
Doomguard = 末日守卫
Gadget Saber = 机巧军刀
Ragnarok = 诸神黄昏
Magemasher = 破法者
Fractured Soul = 破碎之魂
Arcwind = 弧风
Trigoddess = 三相女神
Flamberge = 焰之形
Key of Hearts = 心之钥
Excalibur = 誓约胜利之剑
Zweihander = 兹维尔之握
Heaven's Cloud = 天坠云
Death Exalted = 死之升华
Dark Messenger = 黑暗使者
Ruin = 毁灭
Claymore = 阔剑克莱莫尔
Forgeblade = 熔铸之刃
Lost Voice = 失落之声
Valflame = 瓦尔之火
Helswath = 冥界收割者
Awakened Force = 觉醒之力

Line 24832+
Azazel's Blade = 阿撒兹勒之刃
Ringabolt's Axe = 林戈伯特之斧
Caius' Demonblade = 凯厄斯魔刃
Glitterblade = 闪光虫之刃
4th Age Sword = 第四纪元之剑
Aetherlance = 以太长枪
Runelance = 符文长枪
The Highwind = 高天疾风
Gallatria's Spire = 加拉特里亚尖塔
Abraxas = 阿布拉克萨斯
Cain's Lance = 该隐之枪

Line 24883+
Galaxy Lance = 银河长枪
World's End = 世界终焉
Emblem Fates = 命运徽印
Doombringer = 末日使者
Darkforce = 黑暗之力
World Reborn = 世界新生
King's Lance = 王者长枪
Gungnir = 冈格尼尔
Spirit Lance = 灵魂之枪
Firestorm = 烈焰风暴
Heartseeker = 索心者
Longinus = 朗基努斯之枪
Stormbringer = 风暴使者
Devilsbane = 弑魔
Rampart Golem = 堡垒魔像
Dragon Whisker = 龙须
Vengeful Spirit = 复仇之魂
Dragoon Lance = 龙骑兵长枪
Wallace's Lance = 华莱士的长矛
Urugorak's Tooth = 乌拉格拉克之牙
4th Age Lance = 第四纪元长枪
Aethergun Mk.IV = 以太枪 MK.IV
Arcfire = 弧焰
Frost = 霜冻
Vengeance = 复仇
Judgement = 审判
Golden Eye = 黄金眼
Thrasher = 碎灭者
Athena XVI = 雅典娜 XVI

Line 24982+
Star Destroyer = 星之毁灭者
Quicksilver = 快银
Repeater = 回响
Magma = 熔岩
Chaingun = 链火
Oblivion = 湮灭
Avalanche = 雪崩
Atma Weapon = 亚特玛武装
Coldsnap = 骤霜
Sirius = 天狼星
Sonicsteel = 音速钢
Death Penalty = 死亡裁决
Fomalhaut = 北落师门
Cataclysm = 天灾
Betrayer = 背叛者
Golden Suns = 耀金群阳
Cerberus = 地狱犬
Poopmaker = 便便枪
Axelark's Blaster = 阿克拉塞克的爆能枪
Plaguesteel = 瘟疫之源
4th Age Gun = 第四纪元枪
Aethercannon = 以太重炮
Typhoon IX = 台风 IX
Auto Rifle = 自动步枪
Viking XXVII = 维京 XXVII
Bazooka = 巴祖卡
The Wyvern = 双足飞龙
Aqualung = 水肺
Heat Cannon = 灼热重炮
Commando = 突击手
Hypercannon = 超能重炮
Missile RPG = 导弹火箭筒
Vorpal RPG = 斩裂火箭筒
The Dominator = 支配者
The Zapper = 电刑
Stormcannon = 风暴重炮
The Machine = 毁灭机器
Volt Sniper = 伏特狙击枪
War-Forged Gun = 战火铸就
Carbine = 卡宾枪
Gadget RPG = 机巧火箭筒
Tropic Thunder = 热带雷霆
Hand Cannon = 手炮
Flak Cannon = 高射炮
Dragon Cannon = 飞龙加农炮
Flame Swathe = 覆火
Wyvern Bone = 双足飞龙骨
Scheg's Bow = 谢格之弓
MEGA WEAPON = 超级武器
GALACTIC FLAMEBLASTER = 银河爆焰
Pirate Musket = 海盗火枪
4th Age Cannon = 第四纪元重炮
Mage Gauntlet = 法师魔符
Soul Reaver = 噬魂者
Flame Lash = 火焰之鞭
Wolt's Thunder = 沃尔特之雷
Gaia's Gale = 盖亚之飓风
Decimator = 十步一杀
Dargon Idol = 龙偶
Red Lightning = 赤雷
Mystic Arrow = 秘术之箭
Elementalizer = 元素化身
Flareblade = 耀焰之刃
Ice Wall = 寒冰壁垒
Wrath Aura = 暴怒灵环
Nether Torrent = 冥界洪流
Bolganone = 波尔加农
Caius' Pyre = 凯厄斯祭火
Elfire = 精灵之火
Gafgard's Maelstrom = 加夫嘉德的漩涡
Maalurk Totem = 马路可的图腾
Monk Gauntlet = 僧侣魔符
Tornado = 天旋风暴
Airsplitter = 裂空者
Gruu's Talisman = 格鲁护符
Destruction Wave = 毁灭之潮
Annihilation = 湮灭
Banana = 香蕉
Baalfog's Avalanche = 巴尔雾之雪崩
Moloch's Wrath = 莫洛克之怒
Shroomhazzard = 蘑菇灾变
4th Age Gauntlet = 第四纪元魔符
Aetherstaff = 以太法杖
Pyroclasm = 烈焰爆裂
Astra = 阿斯特拉
Thornwall = 荆棘壁垒
Seraphim = 炽天使
Nirvana = 涅槃

Line 25264+
Twilight Staff = 暮光法杖
Enigma = 谜团
Summoner's Staff = 召唤师法杖
Armageddon = 灭世天劫
Doomsayer = 末日预言者
Merciless Gladiator = 无情斗士
Bubblegum Staff = 泡泡糖法杖
Cherry Blossom = 樱花绽放
The Whitemage = 白魔导
Vinewhip = 藤蔓鞭
Jungle King = 丛林王者
Sage's Staff = 贤者法杖
Lightning Rod = 雷霆权杖
Caster Sword = 施法者之剑
Seeker of Stars = 逐星者
Maelstrom = 漩涡风暴
Darkness = 黑暗
The Blackmage = 黑魔导
Dragonbolt's Mast = 龙雷之桅
Plain Stick = 普通木棍
Perceval's Wand = 帕西瓦尔的魔杖
Hivemind Rod = 巢灵魔杖
4th Age Staff = 第四纪元法杖

Aethershield = 以太之盾
Cadet Buckler = 学员圆盾
Aegis = 神盾
Bolt Shield = 雷电之盾
Gallatria Sigil = 加拉特里亚纹章
Force Guard = 力量护卫
Eagle Shield = 鹰之盾
Leader's Crest = 领袖纹章
Twilight Shield = 暮光之盾
Arc's Buckler = 弧光圆盾
Soul Infusion = 灵魂灌注
Supernova = 超新星
Purifier = 净化者
Oathkeeper = 誓言守护者
Tower Aegis = 高塔神盾
King's Crest = 王者纹章
Champion Shield = 冠军之盾
Spiked Lightning = 雷刺
Blood Shield = 血之盾
Heater Shield = 灼热之盾
Fungi Shield = 真菌之盾
Sunlight = 圣阳之光
Peacekeeper = 维和部队
Aether Shield = 以太圣盾
4th Age Shield = 第四纪元之盾
Scarab Shell = 圣甲虫甲壳
```



#### 头盔

**Line 25414+**

```
Recruit Helm = 新兵头盔
Dunerider Hood = 沙丘风帽
Nautilus Helm = 鹦鹉螺头盔
Vorpal Hood = 斩界兜帽
Titan Helm = 泰坦头盔
Isaac Helm = 以撒头盔
Ultrom Helm = 奥创头盔
Brute Helm = 暴君头盔
Yoshimitsu Helm = 吉光头盔
Ghost Helm = 幽灵头盔
Vigilante Helm = 义警头盔
Wraith Helm = 怨灵头盔
4th Age Helm [STR] = 第四纪元头盔[力量]
4th Age Helm [DEX] = 第四纪元头盔[敏捷]
4th Age Helm [MAG] = 第四纪元头盔[魔法]
Captain's Hat = 船长帽
Urugorak's Hat = 乌拉格拉克帽
Bolgon's Helm = 伯尔根头盔
Broccoli Helm = 西兰头盔
Dredger Helm = 掘沙者头盔
Overworld Helm = 上界头盔
Scourge Helm = 灾厄头盔
Wallace's Helm = 华莱士头盔
Gromwell'S Helm = 格罗姆威尔头盔
Ringabolt's Helm = 林戈伯特头盔
Perceval's Helm = 帕西瓦尔头盔
Baalfog's Eye = 巴尔雾之眼
Azazel's Helm = 阿萨兹勒头盔
Axelark's Helm = 阿克塞拉克头盔
Queen's Helm = 女王头盔
Nolic Beats = 诺利克耳机
Elite Helm = 精英头盔
Voyager Helm = 远航者头盔
Siege Helm = 攻城头盔
Krabshell Helm = 蟹壳头盔
Dunecloth Helm = 沙织头巾
Drifter Helm = 漂泊者头盔
Leviathan Helm = 利维坦头盔
Kraken Helm = 克拉肯头盔
Chaos Helm = 混沌头盔
Ultima Helm = 终极头盔
Destruction Helm = 毁灭头盔
Ithaca's Helm = 伊萨卡头盔
Champion Helm = 冠军头盔
Heroic Helm = 英雄头盔
Deathgod Helm = 死神头盔
Shatterspell Helm = 碎法头盔
Towermage Helm = 高塔法师头盔
Deus Helm = 神之盔
Plasma Helm = 等离子头盔
Rapture Helm = 狂喜头盔
Firegod Helm = 火神头盔
Bruiser Helm = 狂战头盔
Inferno Helm = 炼狱头盔
Ironforge Helm = 铁铸头盔
Yojimbo Helm = 用心棒头盔
Oni Helm = 鬼神头盔
Aku Helm = 阿库头盔
Recon Helm = 侦察头盔
Force Helm = 原力头盔
Helloworld Helm = Hello World头盔
Darknight Helm = 暗夜头盔
Onslaught Helm = 猛攻头盔
Whitewhorl Helm = 白涡头盔
Maelstrom Helm = 大漩涡头盔
Ruin Helm = 废墟头盔
Pyroclasm Helm = 爆炎头盔
Aether Helm = 以太头盔
Slimecraft Helm = 史莱姆工艺头盔
Mykonogre H = 迈科诺格冠盔 H
Catastrophia H = 灾厄面甲 H
Fellbug H = 邪虫祭冠 H
Might Shroom H = 神威菌兜 H
Ironclad H = 铁缚之颅 H
Apocalypse H = 天启之相 H
Glaedria H = 格莱德里亚注视着你 H
Exodus H = 幽世出离 H
Kawaii Lemon = 可爱柠檬帽
Old Chap's Hat = 老伙计的帽子
```



#### 盔甲

**Line 25651+**

```
Recruit Armor = 新兵盔甲
Dunerider Armor = 沙丘盔甲
Nautilus Armor = 鹦鹉螺盔甲
Vorpal Armor = 斩界盔甲
Titan Armor = 泰坦盔甲
Isaac Armor = 以撒盔甲
Ultrom Armor = 奥创盔甲
Brute Armor = 暴君盔甲
Yoshimitsu Armor = 吉光盔甲
Ghost Armor = 幽灵盔甲
Vigilante Armor = 义警盔甲
Wraith Armor = 怨灵盔甲
4th Age Armor = 第四纪元盔甲
Bolgon's Armor = 伯尔根盔甲
Broccoli Armor = 西兰盔甲
Dredger Armor = 掘沙者盔甲
Baalfog's Suit = 巴尔雾之衣
Azazel's Armor = 阿萨兹勒盔甲
Axelark's Armor = 阿克塞拉克盔甲
Queen's Armor = 女王盔甲
Elite Armor = 精英盔甲
Voyager Armor = 远航者盔甲
Siege Armor = 攻城盔甲
Krabshell Armor = 蟹壳盔甲
Dunecloth Armor = 沙织布甲
Drifter Armor = 漂泊者盔甲
Leviathan Armor = 利维坦盔甲
Kraken Armor = 克拉肯盔甲
Chaos Armor = 混沌盔甲
Ultima Armor = 终极盔甲
Destruction Armor = 毁灭盔甲
Ithaca's Armor = 伊萨卡盔甲
Champion Armor = 冠军盔甲
Heroic Armor = 英雄盔甲
Deathgod Armor = 死神盔甲
Shatterspell Armor = 碎法盔甲
Towermage Armor = 高塔法师盔甲
Deus Armor = 神之铠
Plasma Armor = 等离子盔甲
Rapture Armor = 狂喜盔甲
Firegod Armor = 火神盔甲
Bruiser Armor = 狂战盔甲
Inferno Armor = 炼狱盔甲
Ironforge Armor = 铁铸盔甲
Yojimbo Armor = 用心棒盔甲
Oni Armor = 鬼神盔甲
Aku Armor = 阿库盔甲
Recon Armor = 侦察盔甲
Force Armor = 原力盔甲
Helloworld Armor = Hello World盔甲
Darknight Armor = 暗夜盔甲
Onslaught Armor = 猛攻盔甲
Whitewhorl Armor = 白涡盔甲
Maelstrom Armor = 大漩涡盔甲
Ruin Armor = 废墟盔甲
Pyroclasm Armor = 爆炎盔甲
Aether Armor = 以太盔甲
Mykonogre A = 迈科诺格御铠 A
Catastrophia A = 灾厄之体 A
Fellbug A = 邪虫祭袍 A
Might Shroom A = 神威菌甲 A
Ironclad A = 铁缚之躯 A
Apocalypse A = 天启之形 A
Glaedria A = 格莱德里亚与你同在 A
Exodus A = 幽世迁徙 A
```



#### 戒指

**Line 25846+**

```
Gallahad Ring = 加拉哈德戒指
Ezerius Ring = 伊泽瑞斯戒指
Anelice Ring = 安妮莉丝戒指
Gromwell Ring = 格罗姆威尔戒指
Brym Ring = 布瑞姆戒指
Falstadt Ring = 法斯塔德戒指
Roehn Ring = 荣恩戒指
Perceval Ring = 帕西瓦尔戒指
Owain Ring = 欧文戒指
Tydus Ring = 泰达斯戒指
Vaati Ring = 瓦提戒指
```



#### 物品

```
Line 24191+
Planet Stone = 行星岩晶
Orichalcum = 奥利哈钢
Galacticite = 银河晶岩
Zephyr = 翠风晶
Flamethyst = 炽焰晶石
Existence Gem = 存在宝石

Line 24473+
Tasty Herb = 甘美药草
Glowshroom = 荧光蘑菇
Spicy Seed = 辣焰种子
Star Fruit = 星辰果实
Aether Bulb = 以太球根
Chaos Leaf = 混沌叶
Creature Eyeball = 生物眼球
Monster Claw = 怪物利爪
Chitin Fragment = 甲壳碎片
Beast Heart = 野兽心脏
Shiny Scale = 闪光鳞片
Ectoplasm = 灵质
Flutterfly = 扑翼蝶
Dung Beetle = 屎壳郎
Ghast Bug = 幽影虫
Thunderworm = 雷霆虫
Glowfly = 光辉飞虫
Plasma Moth = 等离子飞蛾

Darkfire Scroll = 暗焰卷轴
Ruined Clue = 残破的线索
Starlight Treaty = 星光条约
Arena Ticket = 竞技场门票
Magicite = 魔法晶石
Aethercrystal = 以太晶石
Platinum Badge = 白金徽章
Remembrance Ticket = 纪念券
Champion Badge = 冠军徽章
Glob of Aether = 以太凝团
World Fragment = 世界碎片
Credit = 信用点
Ashen Dust = 灰烬尘
Mystery Gift = 神秘礼盒
Ion Ticket = 离子券
Lightsworn Crystal = 光誓水晶
Scrap Metal = 废金属
Quest Prize = 任务奖赏
Wealth Trophy = 财富奖杯
Health Pack I = 生命补给 I
Mana Pack I = 魔素补给 I
Energy Pack I = 耐力补给 I
Nuldmg Potion = 神佑药剂
Anti-Poison = 抗毒剂
Health Pack II = 生命补给 II
Mana Pack II = 魔素补给 II
Energy Pack II = 耐力补给 II
Anti-Frost = 抗寒剂
Anti-Heat = 抗火剂
Health Pack III = 生命补给 III
Mana Pack III = 魔素补给 III
Energy Pack III = 耐力补给 III
Elixir = 秘药
Aetherdew = 以太露
Aetherlite Shard = 以太碎片
Darkened Shard = 黑暗碎片
Omega Shard = 欧米伽碎片
Aetherlite Prism = 以太棱镜
Darkened Prism = 黑暗棱镜
Omega Prism = 欧米伽棱镜
```



#### 徽印

**Line 24686+**

```
Planet Emblem = 行星徽印
Orichalcum Emblem = 山铜徽印
Galacticite Emblem = 星河徽印
Zephyr Emblem = 翠风徽印
Flame Emblem = 炽焰徽印
Existence Emblem = 存在徽印
Herb Emblem = 甘草徽印
Shroom Emblem = 菌光徽印
Seed Emblem = 种源徽印
Star Emblem = 星辰徽印
Aether Emblem = 以太徽印
Chaos Emblem = 混沌徽印
Eyeball Emblem = 眼瞳徽印
Claw Emblem = 利爪徽印
Fragment Emblem = 碎壳徽印
Beast Emblem = 野兽徽印
Shiny Emblem = 鳞光徽印
Ectoplasm Emblem = 灵质徽印
Flutterfly Emblem = 翼蝶徽印
Beetle Emblem = 甲虫徽印
Ghast Emblem = 幽虫徽印
Thunderworm Emblem = 雷虫徽印
Glowfly Emblem = 辉虫徽印
Plasma Emblem = 等离子徽印
```





#### 卡牌

**Line 24212+**

````
Shmoo Card = 什穆卡牌
Eyepod Card = 眼荚卡牌
Dunebug Card = 沙丘虫卡牌
Worm Card = 蠕虫卡牌
Wasp Card = 黄蜂卡牌
Urugorak Card = 乌拉格拉克卡牌
Sluglord Card = 蛞蝓领主卡牌
Slugmother Card = 蛞蝓之母卡牌
Chamcham Card = 查姆查姆卡牌
Rhinobug Card = 犀牛虫卡牌
Hivemind Card = 巢灵卡牌
Glibglob Card = 粘团卡牌
Slime Card = 史莱姆卡牌
Rock Spider Card = 岩蜘蛛卡牌
Sploopy Card = 鳞团怪卡牌
Rock Scarab Card = 岩石圣甲虫卡牌
Shroom Card = 蘑菇卡牌
Blue Shroom Card = 蓝蘑菇卡牌
Shroom Bully Card = 蘑菇恶霸卡牌
Relicfish Card = 遗迹鱼卡牌
Ancient Guard Card = 远古守卫卡牌
Ancient Beast Card = 远古巡兽卡牌
Roach Card = 沙螂卡牌
 Card = 卡牌
Squirm Card = 蠕首卡牌
Plague Caster Card = 疫病法施卡牌
Glitterbug Card = 闪光虫卡牌
Plaguebeast Card = 疫病兽卡牌
Space Pirate Card = 太空海盗卡牌
Wicked Card = 小邪灵卡牌
Wisp Card = 幽火卡牌
Yeti Card = 雪怪卡牌
Mammoth Card = 猛犸卡牌
Wyvern Card = 双足飞龙卡牌
Lava Blob Card = 熔岩粘团卡牌
Fire Slime Card = 火史莱姆卡牌
Lava Dragon Card = 熔岩龙卡牌
Tyrannog Card = 泰伦罗格卡牌
Beelzeblob Card = 别西卜粘团卡牌
Gruu Card = 格鲁卡牌
Treant Card = 树精卡牌
Willowwart Card = 柳疣怪卡牌
Caius Card = 凯厄斯卡牌
Moloch Card = 莫洛克卡牌
````



#### 徽章

**Line 24353+**

```
Brave Badge = 勇者徽章
Magicite Badge = 魔晶徽章
Destroyer Badge = 毁灭者徽章
Faust Badge = 浮士德徽章
Creator Badge = 造物主徽章
Machine Badge = 机械徽章
Rebellion Badge = 反叛者徽章
Starlight Badge = 星光徽章
Justice Badge = 正义徽章
Enigma Badge = 迷团徽章
Darkweapon Badge = 暗兵器徽章
Zeig Badge = 泽格徽章
```



#### 飞船方块

**Line 24392+**

```
Storage Block = 仓库组件
Forge Block = 锻造台组件
Emblem Block = 徽印凝练所组件
Combat Block = 战术芯片组件
Alchemy Block = 炼金站组件
Computer Block = 控制终端组件
Portal Block = 传送门组件
Ship Droid Block = 舰载无人机组件
Door Block = 舱门组件

Engine Block = 引擎组件
Blue Light = 蓝色灯
Red Light = 红色灯
Spawn Location = 返程点

Scrap Metal Block = 废金属方块
Glass Block = 玻璃方块
Firesteel Block = 火钢方块

Scrap Metal Platform = 废金属平台

Scrap Metal Wall = 废金属墙
```



### · 物品说明

**Line 25967+**

```
LOOT = 战利品
ORE = 矿石
PLANT = 植物
MONSTER PART = 怪物部件
BUG = 虫类
TIER = 等阶

Use this to acquire the Darkfire Combat Chip.
使用后获得「暗焰」战术芯片。

QUEST ITEM Return this document to Roland.
[任务物品]将此文件交给罗兰。

QUEST ITEM Return this document to Effie.
[任务物品]将此文件交给艾菲。

Grants 3 portal uses to Forbidden Arena.
获得3次前往「禁忌竞技场」的传送次数。

QUEST ITEM Give to Captain Atlas.
[任务物品]交给阿特拉斯舰长。

QUEST ITEM Activate near Captain Atlas.
[任务物品]在阿特拉斯舰长附近激活。

Use for a random message and GetComponent.<Animation>().
使用后触发随机消息与特殊动画效果。
(!)怪，先别动

Grants 3 portal uses to Old Earth.
获得3次前往「旧世界」的传送次数。

Symbol of experience. Used for purchasing special items.
经验的象征，用于购买特殊物品。

Consume to gain a random amount of EXP.
消耗后获得随机数量的经验值。

A unique form of currency.
一种独特的货币。

The Galaxy's primary form of currency.
银河通用货币。

Alchemy gone wrong.
失败的炼金产物。

Open to get a random gift!
打开后获得随机奖励！

Grants 3 portal uses to Mech City.
获得3次前往「机械城」的传送次数。

Use to sacrifice yourself & unlock a powerful being.
使用后献祭自身并解锁强大存在。

Pieces of scrap. Used to build things.
废料碎片，用于制造物品。

Open to get a random epic gift!
打开后获得随机史诗奖励！

Symbol of vast wealth. Used for purchasing\nspecial items.
巨额财富的象征，用于购买特殊物品。

Restores 2 HP.
恢复2点生命。

Restores 5 Mana.
恢复5点魔素。

Restores 10 Stamina.
恢复10点耐力。

Reduces incoming damage by half for 5 mins.
5分钟内所受伤害减半。

Reduce Poison by 50%.
中毒效果降低50%。

Restores 5 HP.
恢复5点生命。

Restores 15 Mana.
恢复15点魔素。

Restores 30 Stamina.
恢复30点耐力。

Reduces Frost.
降低冻结值。

Reduces Heat.
降低灼烧值。

Restores 12 Health.
恢复12点生命。

Restores 30 Mana.
恢复30点魔素。

Restores 100 Stamina.
恢复100点耐力。

Restores 12 Health, 30 Mana, and 100 Stamina.
恢复12点生命、30点魔素和100点耐力。

Grants 3 portal uses to The Cathedral.
获得3次前往「圣堂」的传送次数。

A rare card. Can be placed in your ship.
一张稀有的卡片，可放置于飞船中。

A prestigious badge. Can be placed in your ship for decoration.
一枚荣誉徽章，可用于飞船装饰。

Used to forge Prisms at Mech city.
用于在「机械城」打造棱镜。

Used to forge Ultimate Gear at Mech City.
用于在「机械城」打造终极装备。

Tier 1. A shiny Token. Used to forge items.
等阶1。闪亮的印记。用于打造物品。

GEAR MOD Attach to weapons and armor in Mech City.
[装备模组]可在「机械城」附加到武器和护甲上。
```



### · 无人机(!先不翻)

**Line 25879+**

```
RCK 22 = 矿式 RCK-22
FLWR 08 = 花式 FLWR-08
BAT 17 = 蝠型 BAT-17
OBSIDIAN 64 = 黑曜石 OBSIDIAN-64
HELPR 55 = 辅助者 HELPR-55
GUARDIAN 07 = 守卫 GUARDIAN-07
SOLAR 05 = 太阳 SOLAR-05
PRISM 88 = 棱镜 PRISM-88
MONOLTH 25 = 巨碑 MONOLTH-25
FARMHAND 78 = 农务 FARMHAND-78
BULB 88 = 球根 BULB-88
BTTRFLY 8 = 蝶型 BTTRFLY-8
DRAGON 67 = 龙型 DRAGON-67
WYVRN 77 = 飞龙 WYVRN-77
MEGAZORD 36 = 巨虎机甲 MEGAZORD-36
STEEL 65 = 钢铁 STEEL-65
DIAMND 66 = 晶钻 DIAMND-66
BOGBOT 67 = 沼泽 BOGBOT-67
AIDBOT 56 = 支援 AIDBOT-56
HELLBOT 57 = 地狱 HELLBOT-57
iBOT 58 = 智能 iBOT-58
WHITEMAG 09 = 白魔 WHITEMAG-09
OVERSEER 06 = 监察 OVERSEER-06
MRGRGRR 05 = 咕噜 MRGRGRR-05
GOLD 15 = 
```



### · 种族&头饰&制服

**Line 26673-27059**

**见 角色创建界面**





---

## 杂项

### Class: `Cinematic`

```
"COLLECT RESOURCES\nFOR CRAFTING",
"SAVE THE GALAXY",
"COLLECT\nEPIC LOOT",
"CRAFT AN ARSENAL\nOF WEAPONS",
"BUILD & UNLOCK\nNEW DROIDS"

"收集资源\n打造装备",
"拯救银河系",
"收集\n史诗战利品",
"打造武器\n组建军械库",
"建造并解锁\n全新机器人"
```



### Class: `GearChailce`

```
WEAPON = 武器
SHIELD = 盾牌
HELM = 头盔
ARMOR = 盔甲
RING = 戒指
 EXP = 经验
```



### 物品

**Class: `KylockeStand` (飞船商店用)**

**Class: `RuneChalice`(抽奖用)**

**Class: `ItemStandScript`（过图商店用）**

**参考 游戏内文本-可持有物等**

**K/R武器，装备，戒指，卡牌先不翻**

**I卡牌先不翻**

**补充**

```
Droid Fuel = 无人机燃料
Demonbrew = 恶魔酒酿

id异常先不动
Peacemaker - Poopmaker
```







### Class: `PortalScript` 

```
Challenge Lv. = 挑战等级 Lv.
地图参考 游戏内文本-地图
```



### Class: `Seany` 

```
Thank you for your support!
感谢你的支持！

You're the best!
你是最棒的！

PUT ME DOWN!!!
放我下来！！！

Roguelands is better than Magicite.
猛兽之地比魔力遗迹还要棒。

I should've added poop to this game.
我当初应该把便便加入游戏的。

GO WRITE A POSITIVE STEAM REVIEW IF YOU HAVEN'T ALREADY.
如果你还没有，请为我在Steam留下好评。

YOU ARE AMAZING.
你太厉害了。

Roguelands has the best community.
猛兽之地拥有最棒的社区。

FOLLOW YOUR DREAMS.
追随你的梦想。

I OWE EVERYTHING TO THE ROGUELANDS/MAGICITE COMMUNITY.
我的一切都归功于猛兽之地/魔力遗迹社区。
```



### Class: `TxtScript` 

```
WEAPON EXP = 武器经验
SHIELD EXP = 盾牌经验
HELM EXP = 头盔经验
ARMOR EXP = 盔甲经验
RING EXP = 戒指经验
```



## 文本 UABEA

**牛魔的，藏的真阴啊**

**?: 没找到，先不翻 / !: 估计没用，不翻了**

* File：`level1`

```
pathID: 5864&5865&5878&5879&5882&5883&17817&17819& 17831&17833
Hostile Zone = 敌对区域

pathID: 5866&5867&5880&5881&5884&5885  !
Challenge Lv.3 = 

pathID: 5868&5870  ?
Apply = 应用

pathID: 5869&5876
OPTIONS = 选项

pathID: 5872&5877
Sound Effects = 音效

pathID: 5873&5875
Music = 音乐

pathID: 5888&6075
'Bosses Defeated: ' = 击败首领：

pathID: 5889&5917&5939&5988&6011&6057&6072&6085&6098 &6124&6139&6160&6171&6175&6187&6191&6198&6207&6220& 6299&6329&6338&6355&6366&6371&6376&6407&6410  !
Scrap Metal Block = 

pathID: 5891&6303  !
Spellsword Lv.100 = 

pathID: 5895
'Bugspots Harvested:' = 收获虫巢：

pathID: 5897&5929&5970&6000&6013&6340  ?
CHOICES SO MANY CHOICES = 

pathID: 5901&6007  !
'Quests Completed: 22' = 

pathID: 5903&6128
CONNECT TO SERVER = 连接服务器

pathID: 5904&6244
"Select a legendary foe to fight.\n\n[Unlocked by completing Storlyines]"
选择一个传奇对手进行战斗。\n\n[通过完成剧情解锁]

pathID: 5905&6122
Emblem Forge = 徽印凝炼 

pathID: 5906&6101
Click a stack of 10 pieces of loot.
点击一组包含10个战利品的堆叠。

pathID: 5907&6172  !
POISONED 12% = 

pathID: 5908&6233  ?
Seanzillaaa = 

pathID: 5909&6232
The Creator = 造物主

pathID: 5910&6208
Ultimate Helms = 终极头盔

pathID: 5913&6223
Ship Droids = 舰载无人机

pathID: 5914&6352
Server List = 服务器列表

pathID: 5916&6300
Prism Forge = 棱镜熔铸

pathID: 5919&6115
Storyline Choice = 剧情选择

pathID: 5920&6369
RESUME = 返回游戏

pathID: 5921&6166
Planet Selector = 星球选择

pathID: 5923&5949
A Rock Scarab is hot on your trails! Get outta there!
岩石圣甲虫正在追踪你！赶紧离开！

pathID: 5926&6053
Storage = 仓库

pathID: 5928
Apocalypse = 天启

pathID: 5930&6082
'Refresh Quests ' = 刷新任务

pathID: 5933&6089
HOST SERVER = 创建服务器

pathID: 5934&6310 !
Galactic Cadet Lv.10 = 

pathID: 5935&6181
'EXP Acquired:' = 获得经验：

pathID: 5937&6147
Add a Server to connect to = 添加要连接的服务器

pathID: 5938&6002  !
'Portal uses: 3' = 

pathID: 5940&6384  !
'Age: 348 Minutes' = 

pathID: 5941&6315
'Right Click: Remove Block' = 右键：移除方块

pathID: 5943&6361
Baalfog, Overseer of the Ice Dimension = 冰之维度的守望者·巴尔雾

pathID: 5948&6367
'Items Collected:' = 收集物品：

pathID: 5951&6259
'WASD: Movement' = WASD：移动

pathID: 5952&6176  !
'Level: 42' = 

pathID: 5953&6184
Gear Modification = 装备改装

pathID: 5957&5984&6028&6052&6077&6155
Click the button. = 点击按钮

pathID: 5958&6001
Accept = 接受

pathID: 5959&6027&6108&6224
BACK = 返回

pathID: 5960&6126
'1-6: Use Item ' = 1-6：使用物品

pathID: 5963&6189  !
PETRIFIED 25% = 

pathID: 5964&6216
'Left Click: Place Block' = 左键：放置方块

pathID: 5966&6136
'[b Key] Enter Build Mode' = [B键]进入建造模式

pathID: 5972&6180  !
Challenge Lv.1 = 

pathID: 5977&6015&6067&6177
RECIPE UNLOCKED! = 配方已解锁！

pathID: 5985&6146
'Objectives Complete:' = 完成目标：

pathID: 5989&6141  !
+1 STR = 

pathID: 5990&6283
'Chests Opened: ' = 开启宝箱：

pathID: 5993&6037&6094&6154&6247&6268&6282&6370  ?
Firesteel Block = 

pathID: 5994&6362  !
'Galaxy Depth: 1' = 

pathID: 5995&6069
'Enemies Defeated:' = 击败敌人：

pathID: 5998&6305
'Ores Mined: ' = 开采矿石：

pathID: 6003&6359  ?
Scrap Metal Wall = 

pathID: 6004&6210
Retry = 重试

pathID: 6008&6157  !
+1 FTH = 

pathID: 6009&6131  !
Page 1/6 = 

pathID: 6020&6364
'Q/E: Dash' = Q/E：冲刺

pathID: 6022&6390
'Fullscreen: On' = 全屏：开启

pathID: 6031&6290
Axelark IV, The Machine Knight = 机械骑士·阿克塞拉克 IV

pathID: 6032&6120
'TAB: Open Inventory' = TAB：打开背包

pathID: 6033&6074
Item Trasher = 物品回收

pathID: 6038&6150  !
Deliver 20 Tasty Herbs = 

pathID: 6039&6415
CONTROLS = 操作

pathID: 6041&6125
SINGLEPLAYER = 单人玩家

pathID: 6042&6262
SELECT = 选择

pathID: 6043&6196
'Tab/ESC: Exit Build Mode' = Tab/ESC：退出建造模式

pathID: 6048&6304
NEW RACE UNLOCKED = 新种族解锁

pathID: 6051&6179  ?
DESCRIPTION OF SHIT = 

pathID: 6060&6379  !
'Score: 105' = 

pathID: 6063&6169  !
Deliver 500 Tasty Herbs = 

pathID: 6064&6145
Mods can stack up to 5 times each = 同类改造最多叠加5层

pathID: 6066&6417
ipAddress = IP地址

pathID: 6068&6301
'Right Click: Combat' = 右键：进入战斗

pathID: 6070&6250&6280&6335  ?
PASTE = 粘贴

pathID: 6081&6092  !
VIT +1 = 

pathID: 6084&6404  !
Deliver 100 Tasty Herbs = 

pathID: 6086&6185  !
+1 TEC = 

pathID: 6090&6190  ?
Add = 增加

pathID: 6091
Enemies Defeated by Region = 各地区击败敌人数

pathID: 6093&6260
Combine 3 different Emblems of the same tier.
融合同等阶的3个不同徽印。

pathID: 6097&6344
'Port:' = 端口：

pathID: 6099&6254
Click on an item to convert into Credits
点击一个物品以将其转换为信用点

pathID: 6118&6395
Gear Forge = 装备锻造

pathID: 6119&6408  !
+1 DEX = 

pathID: 6132&6357
Add Gear Mods to your Weapons & Armor. = 
在武器和装备上添加改装模组。

pathID: 6133&6238
Pegelda, Queen of the 4th Age = 第4纪元女王·佩格尔达

pathID: 6135
Catastrophia = 灾厄

pathID: 6140&6245
Waiting on other players... = 等待其他玩家……

pathID: 6143&6365
Forbidden Arena = 禁忌竞技场

pathID: 6148&6203  !
Seanzilla's Combat Chips = 

pathID: 6151&6234  !
+1 MAG = 

pathID: 6158
Might Shroom = 神威蘑菇

pathID: 6162&6197
CONTINUE = 继续

pathID: 6167&6322
'Credits Collected:' = 收集信用点：

pathID: 6168&6200  ?
Desolate Crag = 荒凉峭壁

pathID: 6178&6331
CENTURION = 百夫长

pathID: 6186&6226
Azazel, Messenger of Destruction = 毁灭之信使·阿撒兹勒

pathID: 6188&6319
A Rock Scarab is coming after you! = 
岩石圣甲虫追过来了！

pathID: 6192&6419  !
Hostile Lv.1 = 

pathID: 6202&6281
Main Menu = 主菜单

pathID: 6206&6296  ?
Noobdude has died. = 

pathID: 6213&6292
port = 端口

pathID: 6215&6349  !
Upgrade Lv.2 = 

pathID: 6218&6297  !
CONFUSED 12% = 

pathID: 6225&6354  !
FROSTBITE 25% = 

pathID: 6228&6392
'Items Bought: ' = 购买物品：

pathID: 6231&6323
Questbot's Quests = 任务机器人的任务清单

pathID: 6240&6406  !
SILENCE 25% = 

pathID: 6242
Ironclad = 铁缚者

pathID: 6248
Select an Ultra Boss to fight = 选择一个究极Boss进行挑战

pathID: 6253&6324 !
'[1-6 Keys]' = 

pathID: 6257&6311
'SPACEBAR: Jump' = 空格：跳跃

pathID: 6265&6420
Quit = 退出

pathID: 6271
Fellbug = 邪虫

pathID: 6279&6317
Click on a stack of 10 Shards. = 点击一堆包含10个碎片的堆叠。

pathID: 6284&6298
'Trees Chopped:' = 砍伐树木：

pathID: 6287&6288&6386&6389&6396&6399&6401&6403
Lightsworn Crystal = 光誓水晶

pathID: 6291&6393
Lenny = 兰尼

pathID: 6302
"Desolate Canyon: 0 / 1000\nDeep Jungle: 0 / 1000\nHollow Caverns: 0 / 1000\nShroomtown: 0 / 1000\nAncient Ruins: 0 / 1000\nPlaguelands: 0 / 1000\nByfrost: 0 / 1000\nMolten Crag: 0 / 1000\n"
荒凉峡谷：0 / 1000\n幽深丛林：0 / 1000\n空邃洞窟：0 / 1000\n蘑菇镇：0 / 1000\n远古遗迹：0 / 1000\n疫病之地：0 / 1000\n霜境：0 / 1000\n熔火峭岩：0 / 1000\n

pathID: 6320&6377
'Damage Taken: ' = 承受伤害：

pathID: 6327&6346  ?
Glass Block = 

pathID: 6328
Glaedria = 格莱德里亚

pathID: 6343
Mykonogre = 迈科诺格

pathID: 6348
Exodus = 幽世行者

pathID: 6356&6385
Upgrade = 升级

pathID: 6368&6373  !
'Exp: 20/564' = 

pathID: 6383
Saving Game... = 保存游戏中……

pathID: 6394&6416  !
BURNING 25% = 

pathID: 6414
'Bugspots Harvested:' = 收获虫巢：

pathID: 17826&17840
FORBIDDEN ARENA BOSS UNLOCKED = 禁忌竞技场BOSS已解锁

pathID: 17829&17843
+3 Portal Uses = +3 传送次数

pathID: 17875&17878
CRIT! = 
```





---

## 旧实体（弃用，仅作字库扩展）

* Class: `ItemStandScript`
* File：`Assembly-CSharp.dll`

---

### · 武器 Weapons

```
Line 597-686
Aetherblade = 以太之刃
Bolt Edge = 闪电刃
Colossus = 巨像
Doomguard = 末日守卫
Gadget Saber = 小剑士
Ragnarok = 诸神黄昏
Magemasher = 法师杀手
Fractured Soul = 破碎之魂
Arcwind = 弧风
Trigoddess = 三女神
Flamberge = 焰形剑
Key of Hearts = 心之钥
Excalibur = 石中剑
Zweihander = 双手剑
Heaven's Cloud = 天丛云
Death Exalted = 崇高死亡
Dark Messenger = 黑暗使者
Ruin = 废墟
Claymore = 双刃宽剑
Forgeblade = 银熔剑
Lost Voice = 失落之声
Valflame = 瓦尔之火
Helswath = 赫尔镰刀
Awakened Force = 觉醒之力

Line 1316-1344
Ringabolt's Axe = 林戈伯特的斧子
Caius' Demonblade = 凯厄斯的恶魔之刃
Glitterblade = 闪光虫之刃
4th Age Sword = 第四纪元之剑
Aetherlance = 以太长矛
Runelance = 符文长矛
The Highwind = 疾风
Gallatria's Spire = 加拉特里亚的螺旋桨
Abraxas = 阿布拉克萨斯
Cain's Lance = 该隐长矛

Line 1364-1447
Galaxy Lance = 银河长矛
World's End = 世界终焉
Emblem Fates = 徽印命运
Doombringer = 末日双手剑
Darkforce = 黑暗力量
World Reborn = 世界重生
King's Lance = 国王长矛
Gungnir = 永恒之枪
Spirit Lance = 灵魂长矛
Firestorm = 烈焰风暴
Heartseeker = 穿心剑
Longinus = 朗基努斯之枪
Stormbringer = 风暴使者
Devilsbane = 魔鬼灾厄
Rampart Golem = 堡垒魔像
Dragon Whisker = 龙须
Vengeful Spirit = 复仇之魂
Dragoon Lance = 龙骑兵长矛
Wallace's Lance = 华莱士的长矛
Urugorak's Tooth = 乌拉格拉克的牙齿
4th Age Lance = 第四纪元长矛
Aethergun Mk.IV = 以太枪MK4
Arcfire = 弧焰
Frost = 霜冻
Vengeance = 复仇
Judgement = 审判
Golden Eye = 黄金眼
Thrasher = 瑟拉什
Athena XVI = 雅典娜XVI

Line 1463-1712
Star Destroyer = 星球毁灭者
Quicksilver = 快银
Repeater = 转轮枪
Magma = 熔岩
Chaingun = 小型机枪
Oblivion = 湮灭
Avalanche = 崩落
Atma Weapon = 亚特玛武器
Coldsnap = 骤霜
Sirius = 天狼星
Sonicsteel = 音速
Death Penalty = 死刑
Fomalhaut = 北落师门
Cataclysm = 天灾
Betrayer = 背叛者
Golden Suns = 金太阳
Cerberus = 地狱犬
Peacemaker = 和平使者
Plaguesteel = 瘟疫之源
4th Age Gun = 第四纪元枪
Aethercannon = 以太加农炮
Typhoon IX = 台风IX
Auto Rifle = 自动步枪
Viking XXVII = 维京XXVII
Bazooka = 巴祖卡
The Wyvern = 双足飞龙
Aqualung = 水肺
Heat Cannon = 灼热加农炮
Commando = 突击手
Hypercannon = 兴奋火箭炮
Missile RPG = 火箭筒
Vorpal RPG = 利刃火箭筒
The Dominator = 统治者
The Zapper = 灭杀器
Stormcannon = 风暴加农炮
The Machine = 毁灭机器
Volt Sniper = 伏特狙击枪
War-Forged Gun = 战枪
Carbine = 卡宾枪
Gadget RPG = 小型RPG
Tropic Thunder = 热带雷霆
Hand Cannon = 手持加农炮
Flak Cannon = 防空加农炮
Dragon Cannon = 飞龙加农炮
Flame Swathe = 覆火
Wyvern Bone = 双足飞龙骨
GALACTIC FLAMEBLASTER = 银河爆焰
Pirate Musket = 海盗毛瑟枪
4th Age Cannon = 第四纪元加农炮
Mage Gauntlet = 法师魔符
Soul Reaver = 灵魂掠夺者
Flame Lash = 火焰之鞭
Wolt's Thunder = 沃尔特之雷
Gaia's Gale = 吉莉亚的飓风
Decimator = 十步一杀
Dargon Idol = 龙偶
Red Lightning = 红色闪电
Mystic Arrow = 神秘箭
Elementalizer = 元素结晶
Flareblade = 闪耀之刃
Ice Whip = Ice Whip
Wrath Aura = 愤怒光环
Nether Torrent = 地狱洪流
Bolganone = 波拉贡
Caius' Pyre = 凯厄斯的火堆
Elfire = 精灵之火
Gafgard's Maelstrom = 加夫嘉德的漩涡
Maalurk Totem = 马路可的图腾
Monk Gauntlet = 僧侣魔符
Tornado = 龙卷风
Airsplitter = 空气分离器
Gruu's Talisman = 格鲁的法宝
Destruction Wave = 毁灭波动
Annihilation = 湮灭
Banana = 香蕉
Moloch's Wrath = 莫洛克的愤怒
Shroomhazzard = 蘑菇赫萨特
4th Age Gauntlet = 第四纪元魔符
Aetherstaff = 以太杖
Pyroclasm = 烈火
Astra = 阿斯特拉
Thornwall = 荆棘之墙
Seraphim = 炽天使
Nirvana = 涅槃

Line 1733-2243
Twilight Staff = 暮光之杖
Enigma = 谜团
Summoner's Staff = 召唤师之杖
Armageddon = 绝世天劫
Doomsayer = 灾难预言者
Merciless Gladiator = 无情角斗士
Bubblegum Staff = 泡泡糖法杖
Cherry Blossom = 樱花盛开
The Whitemage = 白魔法师
Vinewhip = 蔓藤鞭
Jungle King = 丛林之王
Sage's Staff = 贤者之杖
Lightning Rod = 闪电杖
Caster Sword = 法师长剑
Seeker of Stars = 寻星者
Maelstrom = 漩涡风暴
Darkness = 黑暗
The Blackmage = 黑魔法师
Perceval's Wand = 帕西瓦尔的魔杖
Hivemind Rod = 巢灵法杖
4th Age Staff = 第四纪元法杖
Aethershield = 以太盾
Cadet Buckler = 学员圆盾
Aegis = 庇护
Bolt Shield = 闪电盾
Gallatria Sigil = 加拉特里亚魔符
Force Guard = 力量守卫
Eagle Shield = 鹰盾
Leader's Crest = 领导者之印
Twilight Shield = 暮光之盾
Arc's Buckler = 弧形圆盾
Soul Infusion = 灵魂灌注
Supernova = 超新星
Purifier = 净化者
Oathkeeper = 誓言守卫者
Tower Aegis = 高塔庇护者
King's Crest = 国王之印
Champion Shield = 勇士盾
Spiked Lightning = 尖刺闪电
Blood Shield = 血盾
Heater Shield = 灼热之盾
Fungi Shield = 真菌之盾
Sunlight = 日光
Peacekeeper = 和平守卫者
Scarab Shell = 甲虫盾



Line 2256-2367
Swiftness = 
Vitality I = 体质 I
Strength I = 力量 I
Dexterity I = 敏捷 I
Tech I = 科技 I
Intelligence I = 魔法 I
Faith I = 信仰 I
Photon Blade = 
Dancing Slash = 
Triple Shot = 
Atalanta's Eye = 
Plasma Grenade = 
Gadget Turret = 
Blaze = 
Shock = 
Healing Ward = 
Bubble = 
Berserk = 
Megaslash = 
Hyperbeam = 
Trickster = 
Quadracopter = 
Cluster Bomber = 
Inferno = 
Enhanced Mind = 
Angelic Augur = 
Prism = 
Photon Blade = 
Dancing Slash = 
Triple Shot = 
Atalanta's Eye = 
Plasma Grenade = 
Gadget Turret = 
Blaze = 
Shock = 
Healing Ward = 
Bubble = 

Line 2370-2412
Alacrity = 
Vitality X = 体质 X
Strength X = 力量 X
Dexterity X = 敏捷 X
Tech X = 科技 X
Intelligence X = 魔法 X
Faith X = 信仰 X

Alacrity = 
Vitality II = 体质 II
Strength II = 力量 II
Dexterity II = 敏捷 II
Tech II = 科技 II
Intelligence II = 魔法 II
Faith II = 信仰 II
```



### · 头盔

**Line: 1876-2059**

```
Recruit Helm = 新兵头盔
Dunerider Hood = 沙丘风帽
Nautilus Helm = 鹦鹉头盔
Vorpal Hood = 利刃兜帽
Titan Helm = 泰坦头盔
Isaac Helm = 以撒头盔
Ultrom Helm = 风暴头盔
Brute Helm = 暴君头盔
Yoshimitsu Helm = 吉光头盔
Ghost Helm = 幽灵头盔
Vigilante Helm = 警戒头盔
Wraith Helm = 灵魂头盔
4th Age Helm [STR] = 第四纪元头盔[力量]
4th Age Helm [DEX] = 第四纪元头盔[敏捷]
4th Age Helm [MAG] = 第四纪元头盔[魔法]
Captain's Hat = 船长帽
Urugorak's Hat = 乌拉格拉克帽
Bolgon's Helm = 伯尔根帽
Broccoli Helm = 布洛克留斯帽
Dredger Helm = 挖掘头盔
Overworld Helm = 天国头盔
Scourge Helm = 灾祸头盔
Wallace's Helm = 华莱士头盔
Gromwell'S Helm = 紫草头盔
Ringabolt's Helm = 林戈波特的头盔
Perceval's Helm = 帕西瓦尔的头盔
Elite Helm = 精英头盔
Voyager Helm = 远行者头盔
Siege Helm = 贤者头盔
Krabshell Helm = 蟹壳头盔
Dunecloth Helm = 沙布头盔
Drifter Helm = 漂泊者头盔
Leviathan Helm = 利维坦头盔
Kraken Helm = 海怪头盔
Chaos Helm = 混沌头盔
Ultima Helm = 终极头盔
Destruction Helm = 毁灭头盔
Ithaca's Helm = 伊萨卡的头盔
Champion Helm = 勇士头盔
Heroic Helm = 史诗头盔
Deathgod Helm = 死神头盔
Shatterspell Helm = 粉碎法术头盔
Towermage Helm = 高塔法师头盔
Deus Helm = 上帝头盔
Plasma Helm = 等离子头盔
Rapture Helm = 欣喜头盔
Firegod Helm = 火焰神头盔
Bruiser Helm = 强者头盔
Inferno Helm = 炼狱头盔
Ironforge Helm = 熔铁头盔
Yojimbo Helm = 镖客头盔
Oni Helm = 恶鬼头盔
Aku Helm = 阿克苏头盔
Recon Helm = 侦察兵头盔
Force Helm = 力量头盔
Helloworld Helm = 迎世头盔
Darknight Helm = 暗夜头盔
Onslaught Helm = 突击头盔
Whitewhorl Helm = 深渊头盔
Maelstrom Helm = 漩涡头盔
Ruin Helm = 废墟头盔
Pyroclasm Helm = 烈火头盔
```



### · 盔甲

**Line: 2062-2215**

```
Recruit Armor = 新兵盔甲
Dunerider Armor = 沙丘盔甲
Nautilus Armor = 鹦鹉盔甲
Vorpal Armor = 利刃盔甲
Titan Armor = 泰坦盔甲
Isaac Armor = 以撒盔甲
Ultrom Armor = 风暴盔甲
Brute Armor = 暴君盔甲
Yoshimitsu Armor = 吉光盔甲
Ghost Armor = 幽灵盔甲
Vigilante Armor = 警戒盔甲
Wraith Armor = 灵魂盔甲
4th Age Armor = 第四纪元盔甲
Bolgon's Armor = 伯尔根的盔甲
Broccoli Armor = 布洛克留斯的盔甲
Dredger Armor = 挖掘盔甲
Elite Armor = 精英盔甲
Voyager Armor = 远行者盔甲
Siege Armor = 贤者盔甲
Krabshell Armor = 蟹壳盔甲
Dunecloth Armor = 沙布盔甲
Drifter Armor = 漂泊者盔甲
Leviathan Armor = 利维坦盔甲
Kraken Armor = 海怪盔甲
Chaos Armor = 混沌盔甲
Ultima Armor = 终极盔甲
Destruction Armor = 毁灭盔甲
Ithaca's Armor = 伊萨卡的盔甲
Champion Armor = 勇士盔甲
Heroic Armor = 史诗盔甲
Deathgod Armor = 死神盔甲
Shatterspell Armor = 法术碎片盔甲
Towermage Armor = 高塔法师盔甲
Deus Armor = 上帝盔甲
Plasma Armor = 等离子盔甲
Rapture Armor = 欣喜盔甲
Firegod Armor = 火焰神盔甲
Bruiser Armor = 强者盔甲
Inferno Armor = 炼狱盔甲
Ironforge Armor = 熔铁盔甲
Yojimbo Armor = 镖客盔甲
Oni Armor = 恶鬼盔甲
Aku Armor = 阿克苏盔甲
Recon Armor = 侦察兵盔甲
Force Armor = 力量盔甲
Helloworld Armor = 迎世盔甲
Darknight Armor = 暗夜盔甲
Onslaught Armor = 突袭盔甲
Whitewhorl Armor = 深渊盔甲
Maelstrom Armor = 漩涡盔甲
Ruin Armor = 废墟盔甲
Pyroclasm Armor = 烈火盔甲
```



### · 戒指

**Line: 2218-2248**

```
Gallahad Ring = 盖拉汉德戒指
Ezerius Ring = 伊泽瑞斯戒指
Anelice Ring = 安里克戒指
Gromwell Ring = 紫草戒指
Brym Ring = 布瑞姆戒指
Falstadt Ring = 法斯塔德戒指
Roehn Ring = 荣恩戒指
Perceval Ring = 帕西瓦尔戒指
Owain Ring = 欧文戒指
Tydus Ring = 泰多斯戒指
Vaati Ring = 提瓦戒指
```



### · 改装模块 Gear Mods

```
Line 829-898
BonusVIT+ = 体质强化+
BonusSTR+ = 力量强化+
BonusDEX+ = 敏捷强化+
BonusTEC+ = 科技强化+
BonusMAG+ = 魔法强化+
BonusFTH+ = 信仰强化+
ResistHeat+ = 抗火+
ResistFrost+ = 抗寒+
ResistPoison+ = 抗毒+
ProjectileRange+ = 射弹距离+
CritRate+ = 暴击率+
CritDmg+ = 暴击伤害+
HealthRegen+ = 生命回复+
ManaRegen+ = 魔素回复+
StaminaRegen+ = 耐力回复+
MoveSpeed+ = 移动速度+
DashSpeed+ = 冲刺速度+
JumpHeight+ = 跳跃高度+
OreHarvest+ = 矿物采集+
PlantHarvest+ = 植物采集+
MonsterDrops+ = 怪物掉落+
BugHarvest+ = 昆虫采集+
ExpBoost+ = 经验加成+
CreditBoost+ = 信用点加成+
(Empty) = -空槽位-
```



### · 飞船方块 Ship Blocks

```
Line 924-994
Storage Block = 仓库组件
Forge Block = 锻造台组件
Emblem Block = 徽印凝练所组件
Combat Block = 战术芯片组件
Alchemy Block = 炼金组件
Computer Block = 计算机组件
Portal Block = 传送门组件
Ship Droid Block = 舰载机器人组件
Door Block = 舱门组件

Engine Block = 引擎组件
Blue Light = 蓝色灯
Red Light = 红色灯
Spawn Location = 返程点

Scrap Metal Block = 废金属方块
Glass Block = 玻璃方块
Firesteel Block = 火钢方块

Scrap Metal Platform = 废金属平台

Scrap Metal Wall = 废金属墙
```



### · 卡牌 Collector Cards

```
Line 712-821
Shmoo Card = 什穆卡牌
Eyepod Card = 眼荚卡牌
Dunebug Card = 沙丘虫卡牌
Worm Card = 蠕虫卡牌
Wasp Card = 黄蜂卡牌
Urugorak Card = 乌拉格拉克卡牌
Sluglord Card = 蛞蝓领主卡牌
Slugmother Card = 蛞蝓之母卡牌
Chamcham Card = 查姆查姆卡牌
Rhinobug Card = 犀牛虫卡牌
Hivemind Card = 巢灵卡牌
Glibglob Card = 油团卡牌
Slime Card = 史莱姆卡牌
Rock Spider Card = 岩石蜘蛛卡牌
Sploopy Card = 斯洛皮卡牌
Rock Scarab Card = 岩石甲虫卡牌
Shroom Card = 蘑菇卡牌
Blue Shroom Card = 蓝蘑菇卡牌
Shroom Bully Card = 蘑菇恶霸卡牌
Relicfish Card = 古鱼卡牌
Ancient Guard Card = 远古守卫卡牌
Ancient Beast Card = 远古野兽卡牌
Roach Card = 石斑鱼卡牌
 Card = 卡牌
Squirm Card = 食肉虫卡牌
Plague Caster Card = 疫病释放者卡牌
Glitterbug Card = 萤火虫卡牌
Plaguebeast Card = 疫病兽卡牌
Space Pirate Card = 太空海盗卡牌
Wicked Card = 邪恶卡牌
Wisp Card = 小精灵卡牌
Yeti Card = 雪猿卡牌
Mammoth Card = 猛犸卡牌
Wyvern Card = 翼龙卡牌
Lava Blob Card = 熔岩粘液卡牌
Fire Slime Card = 火焰史莱姆卡牌
Lava Dragon Card = 熔岩飞龙卡牌
```



### · 徽印 Emblems

```
Line 1242-1311
Planet Emblem = 行星徽印
Orichalcum Emblem = 山铜徽印
Galacticite Emblem = 星河徽印
Zephyr Emblem = 翠风徽印
Flame Emblem = 炽焰徽印
Existence Emblem = 存在徽印
Herb Emblem = 甘草徽印
Shroom Emblem = 菌光徽印
Seed Emblem = 种源徽印
Star Emblem = 星辰徽印
Aether Emblem = 以太徽印
Chaos Emblem = 混沌徽印
Eyeball Emblem = 眼瞳徽印
Claw Emblem = 利爪徽印
Fragment Emblem = 碎壳徽印
Beast Emblem = 野兽徽印
Shiny Emblem = 鳞光徽印
Ectoplasm Emblem = 灵质徽印
Flutterfly Emblem = 翼蝶纹章
Beetle Emblem = 甲虫徽印
Ghast Emblem = 幽虫徽印
Thunderworm Emblem = 雷虫徽印
Glowfly Emblem = 辉虫徽印
Plasma Emblem = 等离子徽印
```





### · 物品 Loot

```
矿物 Line 691-706
Planet Stone = 行星岩晶
Orichalcum = 奥利哈钢
Galacticite = 银河晶岩
Zephyr = 翠风晶
Flamethyst = 炽焰晶石
Existence Gem = 存在宝石

Line 1062-1211
Tasty Herb = 甘美药草
Glowshroom = 荧光蘑菇
Spicy Seed = 辣焰种子
Star Fruit = 星辰果实
Aether Bulb = 以太球根
Chaos Leaf = 混沌叶
Creature Eyeball = 生物眼球
Monster Claw = 怪物利爪
Chitin Fragment = 甲壳碎片
Beast Heart = 野兽心脏
Shiny Scale = 闪光鳞片
Ectoplasm = 灵质
Flutterfly = 扑翼蝶
Dung Beetle = 屎壳郎
Ghast Bug = 幽影虫
Thunderworm = 雷霆虫
Glowfly = 光辉飞虫
Plasma Moth = 等离子飞蛾
Remembrance Ticket = 纪念券
Champion Badge = 冠军徽章
Glob of Aether = 以太凝团
World Fragment = 世界碎片
Credit = 信用点
Ashen Dust = 灰烬尘
Mystery Gift = 神秘礼盒
Ion Ticket = 离子券
Lightsworn Crystal = 光誓水晶
Scrap Metal = 废金属
Quest Prize = 任务奖赏
Wealth Trophy = 财富奖杯
Health Pack I = 生命补给 I
Mana Pack I = 魔素补给 I
Energy Pack I = 耐力补给 I
Droid Fuel = 无人机燃料
Anti-Poison = 抗毒剂
Health Pack II = 生命补给 II
Mana Pack II = 魔素补给 II
Energy Pack II = 耐力补给 II
Anti-Frost = 抗寒剂
Anti-Heat = 抗火剂
Health Pack III = 生命补给 III
Mana Pack III = 魔素补给 III
Energy Pack III = 耐力补给 III
Elixir = 秘药
Demonbrew = 恶魔酒酿
Aetherlite Shard = 以太碎片
Darkened Shard = 黑暗碎片
Omega Shard = 欧米伽碎片
Aetherlite Prism = 以太棱镜
Darkened Prism = 黑暗棱镜
Omega Prism = 欧米伽棱镜
```



### · 无人机 Droids (!先不翻)

```
Line 904-919
RCK 22 = 矿式 RCK-22
FLWR 08 = 花式 FLWR-08
BAT 17 = 蝠型 BAT-17
OBSIDIAN 64 = 黑曜石 OBSIDIAN-64
HELPR 55 = 辅助者 HELPR-55
GUARDIAN 07 = 守卫 GUARDIAN-07

Line 1001-1054
SOLAR 05 = 太阳 SOLAR-05
PRISM 88 = 棱镜 PRISM-88
MONOLTH 25 = 巨碑 MONOLTH-25
FARMHAND 78 = 农务 FARMHAND-78
BULB 88 = 球根 BULB-88
BTTRFLY 8 = 蝶型 BTTRFLY-8
DRAGON 67 = 龙型 DRAGON-67
WYVRN 77 = 飞龙 WYVRN-77
MEGAZORD 36 = 巨虎机甲 MEGAZORD-36
STEEL 65 = 钢铁 STEEL-65
DIAMND 66 = 晶钻 DIAMND-66
BOGBOT 67 = 沼泽 BOGBOT-67
AIDBOT 56 = 支援 AIDBOT-56
HELLBOT 57 = 地狱 HELLBOT-57
iBOT 58 = 智能 iBOT-58
WHITEMAG 09 = 白魔 WHITEMAG-09
OVERSEER 06 = 监察 OVERSEER-06
MRGRGRR 05 = 咕噜 MRGRGRR-05
```



---

# ToDo

```
MenuScript(?应该是废案)
UI
徽印凝练所、仓库界面
怪物匠奥拉夫记录
提示界面
```

