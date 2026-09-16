# 曙光 PS4 存档工坊

PS4《怪物猎人：崛起／曙光》存档修改工具，配合 Save Wizard 使用。

[在线使用](https://amaha571.github.io/mhrs-savewizard/) · [下载 Windows 版](https://github.com/Amaha571/mhrs-savewizard/releases/download/v1.0.0/mhrs-savewizard-1.0.0-windows-x64.zip) · [下载离线网页版](https://github.com/Amaha571/mhrs-savewizard/releases/download/v1.0.0/mhrs-savewizard-1.0.0-web-offline.zip)

## 使用方法

1. 备份存档，用 Save Wizard 高级模式导出角色文件。
2. 在工具里导入文件，修改需要的内容。
3. 到「修改预览」检查，导出修改副本。
4. 用 Save Wizard 把副本导回对应角色。

需要的是 Save Wizard 导出的角色文件，不能直接打开 PS4 的加密存档。存档在本机处理，不会上传到网站。

## 支持的修改

- 武器：添加最终形态武器，解锁对应的怪异强化项目，也可以批量添加。
- 防具：新增、防具强化等级、七条怪异炼化效果、单件或批量删除。
- 护石：新增、技能、等级、孔位、单件或批量删除。
- 道具与装饰品：调整数量，一键添加全部道具 ×9999、全部装饰品 ×99。
- 金钱与炎火点数：最高 99,999,999。

武器「全部解锁」是解锁可选的强化项目，具体组合仍需在游戏里按槽位配置。

## 下载后怎么打开

Windows 版：完整解压后，打开「曙光PS4存档工坊.exe」。EXE 和三个 DLL 要放在同一个文件夹，不能只拿走 EXE。需要 64 位 Windows 和 WebView2 Runtime。

离线网页版：解压后用 Edge 或 Chrome 打开 `index.html`。

详细操作见 [使用说明](USAGE.md)，下载文件也可以在 [Releases](https://github.com/Amaha571/mhrs-savewizard/releases) 中找到。

目前仅适配 PS4 的 Save Wizard 导出格式，尚未完成 PS4 实机验证。请保留原始备份。
