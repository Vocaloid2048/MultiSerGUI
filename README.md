This is a Kotlin Multiplatform project targeting Desktop.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…


Draft :
一個整合幾個遊戲的伺服器架設GUI工具
- Satisfactory
- Valheim
- ...
- 應該不會有帕魯 & Minecraft
當中有以下内容：
- 允許用戶創建實例（選擇哪個遊戲）
 - 一個實例列表
 - 可指定icon, 名稱
 - 如支援MOD，介面需要做一個展示MOD庫的列表
- 每一個實例的存放位置預設為App内，可自行決定路徑
- 簡潔、不需過多複雜動畫
- 有調整世界選項、即時Log＆指令行功能、MOD、環境變數的設定
- 備份功能
目標是方便新手開伺服器，所以東西應該相對直觀和簡潔