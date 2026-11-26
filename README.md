<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 泡泡堂（Crazy Arcade / BnB）

一款通过水球困住对手的 PC 在线动作游戏。

> **警告：仅限获准参加 Lab Track 的创作者使用。** 未经批准的使用一律禁止，不因其属于内部制作、学习、研究、个人学习或商业用途而例外。

> 使用条件以仓库根目录中的 [LICENSE](LICENSE) 和 [NOTICE](NOTICE) 为准。查看器：[在查看器中浏览本游戏](https://nexon-replay.github.io/Boomhill/#/g/bnb)。其他游戏请访问[资源中心](https://nexon-replay.github.io/Boomhill/)。

## 目录

| 目录 | 内容 |
|---|---|
| `2d/` | 2D 图像，按资源包分别存放；图像为 PNG，多帧图像使用精灵图集，并附有图集 JSON |
| `2d/manifest.json` | 记录每个文件的大小和 SHA-256 |

## 2D 图像

| 资源包 | 内容 | 图像数 | 帧数 |
|---|---|---:|---:|
| `010_ui` | UI | 1,222 | 5,795 |
| `020_bomber` | 角色 | 2,127 | 17,100 |
| `030_avatar` | 头像、表情动作 | 9,116 | 134,189 |
| `040_tile` | 地块、装饰 | 3,404 | 9,324 |
| `050_item` | 道具 | 144 | 413 |
| `060_effect` | 特效 | 697 | 7,153 |
| `070_monster` | 怪物 | 1,127 | 7,205 |
| `080_hiddencatch` | 隐藏找图 | 248 | 1,203 |
| | 合计 | 18,085 | 182,382 |

文件格式见[资源中心仓库的 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md)，使用方法见[资料指南](https://nexon-replay.github.io/Boomhill/guide.html)。
