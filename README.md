# Codex 宠物

## 异环薄荷 · NTE Mint

以《异环》薄荷为参考制作的非官方 Codex 宠物，包含动画素材、预览和 Windows 安装脚本。

![跳跃预览](nte-mint/nte-mint-preview-jump.gif)
![挥手预览](nte-mint/nte-mint-preview-wave.gif)

## 安装

需使用支持本地宠物的 Codex 客户端。

1. [下载仓库 ZIP](https://codeload.github.com/CQin04/codex-pets/zip/refs/heads/main) 并解压。
2. 进入解压后的 `nte-mint` 文件夹，双击 `安装异环薄荷-NTE-Mint.bat`。
3. 安装完成后，重新打开 Codex 宠物选择面板，选择“薄荷”。

默认安装目录：`%USERPROFILE%\.codex\pets\nte-mint`。

脚本会复制 `pet.json` 和 `nte-mint-spritesheet.webp`。已有同名目录时，会先在旁边创建带时间戳的备份，再覆盖这两个文件。

**手动安装：** 在上述安装目录中放入 `pet.json` 和 `nte-mint-spritesheet.webp`，再重新打开宠物选择面板。

## 文件

所有宠物文件位于 [nte-mint](nte-mint/) 目录。

| 文件 | 用途 |
| --- | --- |
| `pet.json`、`nte-mint-spritesheet.webp` | 宠物配置与动画精灵图，安装必需 |
| `install.ps1`、`安装异环薄荷-NTE-Mint.bat` | Windows 安装脚本 |
| `nte-mint-preview-*` | 动画预览 |
| `nte-mint-contact-sheet.png` | 动作总览 |
| `checksums.sha256` | `nte-mint` 目录内文件的 SHA256 校验值 |

角色来源：[《异环》官方介绍](https://nte.perfectworld.com/en/article/news/gamenews/20240830/252475.html)。本项目为非官方制作。
