# AGENTS.md

115-1 電腦程式設計課程程式碼庫。

## 基本規定

- 所有回應一律使用繁體中文。
- 專案程式語言為 Python。
- 一律使用 conda 管理 Python 套件，禁止使用 pip / venv / poetry 等其他方式安裝。
- 固定使用 conda 環境 `iem_python`：執行 Python 相關操作前先 `conda activate iem_python`。

## 現況

- 儲存庫目前為骨架：僅有 `README.md` + Python 樣板 `.gitignore`，無原始碼、manifest 或工具設定（2026-10-06 確認）。
- 尚無可用的 build、test、lint、typecheck 指令。不得自行假設。
- 新增 manifest / 設定（`pyproject.toml`、`requirements*.txt`、`environment.yml`、`Makefile`、CI workflow）前請先檢查是否已存在；引入新工具鏈時，請同步更新本檔案，記下精確指令（含單一測試 / 聚焦驗證寫法）與必要執行順序。
