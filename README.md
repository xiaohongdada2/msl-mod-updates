# MSL Mod Updates

这个仓库只用于发布 MSL 自动更新文件。源码仓库可以继续保持私有或审计状态。

目录约定：

```text
mods/<Mod包名>/<Mod包名>.sml
mods/<Mod包名>/manifest.json
```

更新时重新生成对应目录里的 `.sml` 和 `manifest.json`，然后提交并推送。超过普通 Git 推送链路稳定承载范围的大包可以改用固定版本 GitHub Release 资产，manifest 的 `DownloadUrl` 指向该资产，并继续用 `Sha256` 校验下载内容。

当前包含的 Mod：

| sml 文件 | Mod 名 | 版本 |
| --- | --- | --- |
| `A TheCosmeticMod.sml` | 姿色紧实(血兆版本) | `3.7.2.0` |
| `Bule_Stoneshard.sml` | 蓝色晶石(血兆版本) | `0.2.22.9` |
| `C Red_Stoneshard.sml` | 鸿色晶石 | `1.4.0.1` |
| `D Green_Stoneshard.sml` | 绿色晶石 | `0.1.2.3` |
| `Daphne.sml` | 达芙妮(哈基蜗)(血兆版本) | `1.1.1.1` |
| `E WuweiZhanshi.sml` | 无畏战士 | `0.1.0.1` |
| `Expanded Enemy Inspection 1.2.2.sml` | 详细观察面板ExpandedEnemyInspection | `1.2.2` |
| `Falyn.sml` | 流放勇士-法林(血兆版本) | `1.3.0.1` |
| `HardMode.sml` | 困难模式 | `0.1.0.0` |
| `health_bar.sml` | 生命条-复刻兼容版 | `1.0.0` |
| `HolyDiagonal.sml` | Holy Diagonal | `2.0.0.0` |
| `LinYuXia.sml` | 明日方舟-林雨霞 | `0.1.0.4` |
| `Origami.sml` | 可爱的雪嫣酱们(血兆版本) | `1.2.0.1` |
| `OrigamiWhiteSocks.sml` | 白袜折纸约稿 | `1.1.2` |
| `RanXiaYi.sml` | 绯月精灵-染霞衣 | `0.3.5.2` |
| `Ruby.sml` | RWBY:露比(血兆版本) | `1.11.2.1` |
| `Shadow_of_Another_World.sml` | 异界之影 | `0.1.0.2` |
| `Shire.sml` | 黑雀社德鲁伊-夏尔 | `1.4.8.5` |
| `The Gift For You.sml` | 雪嫣的馈赠喵~ | `4.2.4.0` |
| `tracker.sml` | 黑月君临-追踪者(血兆版本) | `1.4.1.0` |
| `UI_Plus.sml` | UI+汉化版 v0.9.4.21+ | `2.3.0` |
| `velin_and_celestines_weapon_package.sml` | 维林族与天羽族定制武器包(血兆版本) | `1.2.0.0` |
| `Z-DevTools.sml` | 雪嫣酱控制台 | `2.4.0.0` |
