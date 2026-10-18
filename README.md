# 金苹果工坊 · Golden Apple Workshop

一个轻松、有趣、可以“吃”的 Fabric 装备模组。新增 7 件围绕食物与金苹果设计的装备：从会回血的**金苹果剑**，到能把敌人击飞的法棍、会黏人的蜂蜜剑，再到随机传送的末影苹果。

> 适用版本：**Minecraft 1.20.1 · Fabric**
>
> 模组版本：**1.0.0**
>
> 前置：**Fabric Loader ≥ 0.15.0**、**Fabric API 0.92.9+1.20.1**、**Java 17+**


## 安装

1. 为 Minecraft 1.20.1 安装 Fabric Loader。
2. 将 [Fabric API 0.92.9+1.20.1](https://modrinth.com/mod/fabric-api) 放入 `mods` 文件夹。
3. 将 `golden-apple-workshop-1.0.0.jar` 放入 `mods` 文件夹。
4. 启动游戏。多人游戏中，**客户端和服务端都需要安装本模组**。

## 七件装备

| 装备 | 攻击力 | 攻速 | 耐久 | 一句话玩法 |
| --- | ---: | ---: | ---: | --- |
| 金苹果剑 | 5.5 | 2.0 | 420 | 攻击概率回血；饿了可以啃一口 |
| 附魔金苹果剑 | 7.0 | 1.8 | 999 | 更强的吸血与增益，自带附魔光效 |
| 胡萝卜剑 | 4.0 | 2.8 | 220 | 攻速极快，边打边获得跑跳增益 |
| 法棍面包剑 | 5.0 | 1.2 | 380 | 攻速慢，但可以把敌人打飞 |
| 蜂蜜剑 | 4.5 | 1.9 | 300 | 让敌人沾上蜂蜜，陷入缓慢与虚弱 |
| 末影苹果 | — | — | 可堆叠 16 | 随机传送，逃命与整活兼备 |
| 金苹果头盔 | 3 护甲 | — | 275 | 饿了会自己“治疗”你，猪灵也爱你 |

### 金苹果剑

- **攻击**：35% 概率回复 1 颗心，并获得伤害吸收。
- **食用**：长按右键 1.2 秒，回复 2.5 格饥饿值，获得生命恢复与伤害吸收。
- **代价**：每咬一口消耗 14 点耐久，8 秒冷却；剑不会消失。
- 可用金苹果在铁砧上修复。

### 附魔金苹果剑

- **攻击**：60% 概率回复生命、获得生命恢复与伤害吸收，并让目标虚弱、发光。
- **食用**：回复 4 格饥饿值，获得生命恢复 II、伤害吸收 II、抗性提升与抗火。
- **代价**：每咬一口消耗 24 点耐久，20 秒冷却。
- 稀有度史诗，自带附魔光效；可用附魔金苹果修复。

### 胡萝卜剑

- **攻击**：30% 概率获得速度与跳跃提升；10% 概率让目标掉一根胡萝卜。
- **食用**：回复 1.5 格饥饿值，获得速度 II 与跳跃提升 II。
- **代价**：每咬一口消耗 10 点耐久，4 秒冷却。
- 适合快速连击和跑图。可用胡萝卜修复。

### 法棍面包剑

- **攻击**：额外击退目标，并附加短暂缓慢。
- **食用**：回复 3 格饥饿值，获得力量。
- **代价**：每咬一口消耗 12 点耐久，6 秒冷却。
- 攻击速度慢，但击退手感很“法棍”。可用面包修复。

### 蜂蜜剑

- **攻击**：50% 概率让目标沾满蜂蜜，陷入缓慢 II 与虚弱。
- **食用**：回复 2 格饥饿值，获得生命恢复与速度。
- **代价**：每咬一口消耗 10 点耐久，5 秒冷却。
- 可用蜜脾修复。

### 末影苹果

- **食用**：向随机方向传送 8~24 格，并获得抗性提升与缓降。
- **安全机制**：最多尝试 40 个落点，避开岩浆和实心墙体；找不到安全落点时会给予反胃并提示。
- **代价**：每次消耗 1 个，8 秒冷却；可堆叠 16 个。

### 金苹果头盔

- **穿戴时**：饥饿值 ≥ 8 且未满血，每 5 秒获得一次短暂生命恢复。
- **代价**：治疗会缓慢消耗饥饿值。
- **额外效果**：猪灵会把你视为穿着金质装备。
- 可用金苹果修复。

## 合成配方

![合成配方](docs/recipes.png)

文字版：

- **金苹果剑**：竖排 2 个金苹果 + 1 根木棍。
- **附魔金苹果剑**：竖排 2 个附魔金苹果 + 1 根木棍。
- **胡萝卜剑**：竖排 2 根胡萝卜 + 1 根木棍。
- **法棍面包剑**：竖排 2 个面包 + 1 根木棍。
- **蜂蜜剑**：竖排 2 个蜜脾 + 1 根木棍。
- **末影苹果 ×2**：苹果 + 2 个末影珍珠 + 糖（无序合成）。
- **金苹果头盔**：金苹果 + 4 个金锭（无序合成）。

所有装备都会出现在创造模式物品栏的**“金苹果工坊”**页签中，并加入了 `minecraft:swords` / `minecraft:head_armor` 等原版标签。

## 指令速查

```mcfunction
/give @s goldenappleworkshop:golden_apple_sword
/give @s goldenappleworkshop:enchanted_golden_apple_sword
/give @s goldenappleworkshop:carrot_sword
/give @s goldenappleworkshop:baguette_sword
/give @s goldenappleworkshop:honey_sword
/give @s goldenappleworkshop:ender_apple 8
/give @s goldenappleworkshop:golden_apple_helmet
```

## 开发与构建

需要 JDK 21+（构建用）和 Gradle Wrapper：

```bash
./gradlew build
```

Windows：

```powershell
.\gradlew.bat build
```

产物：`build/libs/golden-apple-workshop-1.0.0.jar`

本仓库还提供了预构建文件：`dist/golden-apple-workshop-1.0.0.jar`。

本地测试：

```bash
./gradlew runClient    # 启动带模组的客户端
./gradlew runServer    # 启动带模组的服务端（首次需同意 EULA）
```

### 项目结构

```text
src/main/java/com/dsh/goldenappleworkshop/
├── GoldenAppleWorkshop.java      # 模组入口
├── client/
│   ├── GoldenAppleWorkshopClient.java   # 客户端入口
│   ├── GoldenAppleHelmetRenderer.java   # 头盔 3D 模型渲染
│   └── HelmetModelTextures.java
├── event/AppleHelmetEvents.java  # 头盔每 5 秒的服务器 tick 效果
├── item/
│   ├── TastySwordItem.java       # 可食用剑的通用逻辑
│   ├── EnderAppleItem.java       # 随机传送苹果
│   └── GoldenAppleHelmetItem.java
└── registry/
    ├── ModItems.java             # 物品注册与效果配置
    ├── ModItemGroup.java         # 创造模式页签
    ├── ModTiers.java             # 武器材料
    └── ModArmorMaterials.java    # 头盔材料
```

资源文件全部是数据驱动的：物品模型、配方、标签、进度和 `zh_cn` / `en_us` 语言文件都在 `src/main/resources` 下。


## 已知限制

- 仅支持 **Minecraft 1.20.1**；迁移到其他版本需要调整 mappings 与少量 API。
- 没有配置文件；数值直接写在代码里。
- 目前是 7 件装备的轻量内容包，不添加新维度、生物或 Boss。

## 许可

代码与生成的贴图以 **MIT License** 发布。项目不包含 Minecraft 原版资源文件；`docs/` 中的预览图由本模组自己的贴图生成。

此代码由DeepSeek生成。

Minecraft 是 Mojang Studios 的商标。本项目与 Mojang / Microsoft 无关联。
