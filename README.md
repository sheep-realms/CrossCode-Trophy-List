**中文** | [English](README_en.md)

# CrossCode Trophy List

本项目列出了《CrossCode》中所有成就的内部名称，数据来源于游戏资产文件夹中的 `database.json`。

由于该游戏的成就具有实际作用，可以大幅度提升二周目的游戏体验，但我竟然没有找到有人分享全成就存档或成就内部名称列表，于是我创建了这个仓库。

## 存档编辑指南

**强烈建议您在编辑存档前先备份存档文件！**

1. 找到游戏的存档文件（在 Windows 系统中通常位于 `<系统盘>:\Users\<用户名>\AppData\Local\CrossCode\cc.save`）。
2. 打开存档文件并提取 `globals` 字段的值。
3. 使用存档编辑器（例如 [CCSaveEdit](https://insyg.github.io/CCSaveEdit/)）解码提取的数据。
4. 打开本项目的 `trophy.json` 文件，复制 `feats` 字段的值，粘贴替换存档数据中的 `feats` 字段的值。
5. 在存档编辑器中应用更改并输出编码数据，替换存档文件中 `globals` 字段的值。
