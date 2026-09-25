# MSL Mod Updates

这个仓库只用于发布 MSL 自动更新文件。源码仓库可以继续保持私有或审计状态。

目录约定：

```text
mods/<Mod包名>/<Mod包名>.sml
mods/<Mod包名>/manifest.json
```

更新时重新生成对应目录里的 `.sml` 和 `manifest.json`，然后提交并推送。超过普通 Git 推送链路稳定承载范围的大包可以改用固定版本 GitHub Release 资产，manifest 的 `DownloadUrl` 指向该资产，并继续用 `Sha256` 校验下载内容。

当前包含的 Mod：

| Mod 目录 | 版本 | 下载 |
| --- | --- | --- |
| A TheCosmeticMod | 3.8.1.7 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-f804ec419c9b-3.8.1.7-a39f556e6704/package.sml) |
| Bule_Stoneshard | 0.4.3.46 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-531f1c286e29-0.4.3.46-e7bf5ebaa1b2/Bule_Stoneshard.sml) |
| C Red_Stoneshard | 1.7.0.5 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-73309adbb479-1.7.0.5-358c4754a642/package.sml) |
| D Green_Stoneshard | 0.1.4.36 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-669d8902e332-0.1.4.36-f50aa203d706/package.sml) |
| Daphne | 1.1.1.6 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-3daeaacf3cce-1.1.1.6-a7f76b67d0f4/package.sml) |
| E WuweiZhanshi | 0.2.1.9 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-37d058fbf50b-0.2.1.9-88e1d9eeb6fd/package.sml) |
| Falyn | 1.3.0.4 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-328b43ff6c19-1.3.0.4-a2e36abd1891/package.sml) |
| LinYuXia | 0.1.0.7 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-ae54eb6548dd-0.1.0.7-e410f6cb3b3b/package.sml) |
| Origami | 1.2.0.6 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-501073e4a4a7-1.2.0.6-e2980f45067f/package.sml) |
| OrigamiWhiteSocks | 1.1.4 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-0a4e59612232-1.1.4-0c051851e734/package.sml) |
| RanXiaYi | 0.4.10.7 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-2476bcd31ba4-0.4.10.7-41d2988882d8/package.sml) |
| Ruby | 1.12.3.5 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-108040ac289a-1.12.3.5-a82d0d14f184/package.sml) |
| Shadow_of_Another_World | 0.1.1.2 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-f901d444e8d2-0.1.1.2-b5711848ecf4/package.sml) |
| ShardUIEnhanced | 0.10.0.18 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-eb274b0f1f2e-0.10.0.18-383163984daa/package.sml) |
| Shire | 1.5.1.4 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-d23f986a9541-1.5.1.4-2b8ccef74e6f/package.sml) |
| The Gift For You | 4.2.4.3 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-74e390a16ab4-4.2.4.3-7204f962d998/package.sml) |
| Yang | 0.1.0.6 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-fef1114f2d1a-0.1.0.6-b7d1d115e503/package.sml) |
| Z-DevTools | 2.8.0.6 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-8a2fcf819300-2.8.0.6-c2f6597133fd/package.sml) |
| tracker | 1.4.4.5 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-7ae4495c83dd-1.4.4.5-0b7e6bfba366/package.sml) |
| velin_and_celestines_weapon_package | 1.2.0.3 | [下载 SML](https://github.com/xiaohongdada2/msl-mod-updates/releases/download/mod-cc6e9c86c503-1.2.0.3-f227b51700bf/package.sml) |

下载请以各目录 manifest.json 的 DownloadUrl 为准；目录中的历史 SML 不一定是最新版本。
