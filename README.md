# Gun-PvP 實例

這是基於 PrismLauncher 的 Minecraft Gun-PvP 遊戲實例，內含多款槍械模組與資源包。

## 目錄結構

```
├─ mmc-pack.json         # 實例設定檔
├─ minecraft/
│   ├─ mods/             # Forge & Fabric 模組
│   ├─ saves/新的世界/   # 世界存檔
│   └─ tacz/             # 槍械資源包
```

## 使用方法

1. 安裝 PrismLauncher (或 MultiMC)。  
2. Clone 此倉庫：  
   `git clone https://github.com/Supebuff/minecraft-gun-pvp-instance.git`  
3. 在 PrismLauncher 中選擇「導入實例」並選擇倉庫根目錄下的 `mmc-pack.json`。  
4. 按下「啟動」以啟動客戶端。

## 已包含模組列表 (節錄)

- alltheleaks
- architectury
- Better_Modlist
- chat_heads
- Chloride
- cloth-config
- Connector
- ConnectorExtras
- Controlling
- dynamic-fps
- embeddium
- emi
- explosiveenhancement
- fabric-api
- ferritecore
- packetfixer
- Searchables
- ShoulderSurfing
- sound-physics-remastered
- tacz
- yesstevemodel
- yuushya
- yuushya-modelling

*完整列表請參見* `minecraft/mods` *資料夾*

## 忽略本地變更

本地對 `mmc-pack.json` 的變更已設為 skip-worktree，不會在 `git status` 中顯示。

```bash
git update-index --skip-worktree mmc-pack.json
```

## 授權

本專案未指定授權，使用請遵循各模組原始授權條款。