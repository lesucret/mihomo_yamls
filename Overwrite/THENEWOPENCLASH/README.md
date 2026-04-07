# 📦 OpenClash 新版覆写配置仓库

自动生成基于新版 OpenClash 覆写模块格式的配置文件（`.yaml`）。
每个文件的 `[General]` 功能配置**全部注释**（附详细说明），按需取消注释即可；
`[YAML]` 块仅启用 `proxy-providers` 的 URL 覆写，其余操作均已注释供参考。

## 📋 与旧版 (.conf) 的区别

| 对比项 | 旧版 (.conf) | 新版 (.yaml) |
| :--- | :--- | :--- |
| 覆写方式 | `ruby_map_edit` 脚本调用 | `[YAML]` 块操作符（原生） |
| YAML 操作 | 仅支持 key-path 替换 | 支持合并/强制覆盖/追加/删除/条件批量更新 |
| 文件扩展名 | `.conf` | `.yaml` |
| 输出目录 | `Overwrite/THEOPENCLASH/` | `Overwrite/THENEWOPENCLASH/` |

## 📂 目录总览

| 分类目录 | 包含配置数 | 说明 |
| :--- | :--- | :--- |
| 📁 **[General_Config/666OS](./General_Config/666OS/README.md)** | 2 个 | [点击浏览详细列表](./General_Config/666OS/README.md) |
| 📁 **[General_Config/ClashConnectRules](./General_Config/ClashConnectRules/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/ClashConnectRules/README.md) |
| 📁 **[General_Config/HenryChiao](./General_Config/HenryChiao/README.md)** | 3 个 | [点击浏览详细列表](./General_Config/HenryChiao/README.md) |
| 📁 **[General_Config/Kerronex](./General_Config/Kerronex/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/Kerronex/README.md) |
| 📁 **[General_Config/Lanlan13-14](./General_Config/Lanlan13-14/README.md)** | 3 个 | [点击浏览详细列表](./General_Config/Lanlan13-14/README.md) |
| 📁 **[General_Config/Mitchell](./General_Config/Mitchell/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/Mitchell/README.md) |
| 📁 **[General_Config/Repcz](./General_Config/Repcz/README.md)** | 2 个 | [点击浏览详细列表](./General_Config/Repcz/README.md) |
| 📁 **[General_Config/SHICHUNHUI88](./General_Config/SHICHUNHUI88/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/SHICHUNHUI88/README.md) |
| 📁 **[General_Config/Seven1echo](./General_Config/Seven1echo/README.md)** | 2 个 | [点击浏览详细列表](./General_Config/Seven1echo/README.md) |
| 📁 **[General_Config/echs-top](./General_Config/echs-top/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/echs-top/README.md) |
| 📁 **[General_Config/fufu](./General_Config/fufu/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/fufu/README.md) |
| 📁 **[General_Config/iKeLee](./General_Config/iKeLee/README.md)** | 2 个 | [点击浏览详细列表](./General_Config/iKeLee/README.md) |
| 📁 **[General_Config/liandu2024](./General_Config/liandu2024/README.md)** | 5 个 | [点击浏览详细列表](./General_Config/liandu2024/README.md) |
| 📁 **[General_Config/liuran001](./General_Config/liuran001/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/liuran001/README.md) |
| 📁 **[General_Config/lvbibir](./General_Config/lvbibir/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/lvbibir/README.md) |
| 📁 **[General_Config/qichiyuhub](./General_Config/qichiyuhub/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/qichiyuhub/README.md) |
| 📁 **[General_Config/wanswu](./General_Config/wanswu/README.md)** | 1 个 | [点击浏览详细列表](./General_Config/wanswu/README.md) |
| 📁 **[General_Config/yyhhyyyyyy](./General_Config/yyhhyyyyyy/README.md)** | 2 个 | [点击浏览详细列表](./General_Config/yyhhyyyyyy/README.md) |
| 📁 **[Mobile_Modules/AkashaProxy](./Mobile_Modules/AkashaProxy/README.md)** | 1 个 | [点击浏览详细列表](./Mobile_Modules/AkashaProxy/README.md) |
| 📁 **[Mobile_Modules/BoxProxy](./Mobile_Modules/BoxProxy/README.md)** | 1 个 | [点击浏览详细列表](./Mobile_Modules/BoxProxy/README.md) |
| 📁 **[Mobile_Modules/ClashMix](./Mobile_Modules/ClashMix/README.md)** | 1 个 | [点击浏览详细列表](./Mobile_Modules/ClashMix/README.md) |
| 📁 **[Mobile_Modules/Surfing](./Mobile_Modules/Surfing/README.md)** | 1 个 | [点击浏览详细列表](./Mobile_Modules/Surfing/README.md) |
| 📁 **[Official_Examples/Metacubex](./Official_Examples/Metacubex/README.md)** | 2 个 | [点击浏览详细列表](./Official_Examples/Metacubex/README.md) |
| 📁 **[Smart_Mode/666OS](./Smart_Mode/666OS/README.md)** | 2 个 | [点击浏览详细列表](./Smart_Mode/666OS/README.md) |
| 📁 **[Smart_Mode/HenryChiao](./Smart_Mode/HenryChiao/README.md)** | 4 个 | [点击浏览详细列表](./Smart_Mode/HenryChiao/README.md) |
| 📁 **[Smart_Mode/echs-top](./Smart_Mode/echs-top/README.md)** | 1 个 | [点击浏览详细列表](./Smart_Mode/echs-top/README.md) |
| 📁 **[Smart_Mode/edison](./Smart_Mode/edison/README.md)** | 1 个 | [点击浏览详细列表](./Smart_Mode/edison/README.md) |
| 📁 **[Smart_Mode/liandu2024](./Smart_Mode/liandu2024/README.md)** | 3 个 | [点击浏览详细列表](./Smart_Mode/liandu2024/README.md) |
| 📁 **[Smart_Mode/qichiyuhub](./Smart_Mode/qichiyuhub/README.md)** | 1 个 | [点击浏览详细列表](./Smart_Mode/qichiyuhub/README.md) |

## 🚀 使用方法
1. 进入上方分类目录找到需要的 `.yaml` 文件。
2. 复制文件 Raw URL。
3. 在 OpenClash -> 覆写设置 -> 覆写模块中添加该 URL。
4. **重要**：在覆写设置 -> 开发者选项中设置对应的环境变量（`EN_KEY1`, `EN_KEY2` 等为你的订阅链接）。

[🏠 返回项目主页](../../README.md)