# 套件資訊配置表

請填寫以下資訊，這些資訊將用於套件化過程中的各種配置文件。

## 📦 基本套件資訊

### 套件名稱

- **PyPI 套件名稱**: `superyngo-logger`
- **Python 模組名稱**: `superyngo_logger`
- **顯示名稱**: `Superyngo Logger`

### 版本資訊

- **初始版本**: `0.0.1`
- **Python 最低版本要求**: `>=3.8`
- **開發狀態**: `4 - Beta` (可選：3 - Alpha, 4 - Beta, 5 - Production/Stable)

### 描述資訊

- **簡短描述**: `A simple and efficient logging utility for Python applications`
- **詳細描述**: `My Logger provides an easy-to-use logging solution with file rotation, custom formatting, and log cleanup capabilities.`
- **關鍵字**: `logging, python, utility, file-rotation, cleanup`

## 👤 作者資訊

### 主要作者

- **姓名**: `Wenyang`
- **Email**: `superyngo@gmail.com`

<!-- ### 維護者（如果與作者不同）

- **姓名**: `Your Name`
- **Email**: `your.email@example.com` -->

## 🔗 倉庫資訊

### GitHub 資訊

- **GitHub 使用者名稱**: `superyngo`
- **倉庫名稱**: `my_logger`
- **完整 GitHub URL**: `https://github.com/superyngo/my_logger`

### PyPi 資訊

- **Pending project name**: `superyngo_logger`
- **Publisher**: `GitHub`
- **Repository**: `superyngo/my_logger`
- **Workflow**: `publish.yml`
- **Environment name**: `(Any)`

<!-- ### 其他連結（可選）

- **文檔網站**: `https://yourusername.github.io/my-logger/`
- **個人網站**: `https://yourwebsite.com` -->

## 📄 授權資訊

### 授權類型

- **授權**: `MIT`
- **授權年份**: `2025`
- **版權持有人**: `Wenyang`

## 🏷️ 分類標籤

### PyPI 分類器

請根據您的套件特性選擇適當的分類器：

#### 開發狀態

- [ ] `Development Status :: 3 - Alpha`
- [x] `Development Status :: 4 - Beta`
- [ ] `Development Status :: 5 - Production/Stable`

#### 目標受眾

- [x] `Intended Audience :: Developers`
- [ ] `Intended Audience :: End Users/Desktop`
- [ ] `Intended Audience :: System Administrators`

#### 主題分類

- [x] `Topic :: Software Development :: Libraries :: Python Modules`
- [x] `Topic :: System :: Logging`
- [ ] `Topic :: Utilities`
- [ ] `Topic :: Software Development :: Debugging`

#### 作業系統

- [x] `Operating System :: OS Independent`
- [ ] `Operating System :: POSIX`
- [ ] `Operating System :: Microsoft :: Windows`

## 📚 依賴資訊

### 運行時依賴

請列出您的套件需要的外部依賴：

```
# 範例：
# requests>=2.25.0
# pyyaml>=5.4.0

目前無外部依賴
```

### 開發依賴

以下是建議的開發依賴（通常不需要修改）：

```
pytest>=6.0
pytest-cov
black
isort
flake8
mypy
build
twine
```

## 🔧 套件功能

### 主要功能

請簡要描述您套件的主要功能：

1. **日誌初始化**: 簡單的日誌配置和初始化
2. **文件輪轉**: 自動的日誌文件大小和數量管理
3. **日誌清理**: 自動清理舊的日誌文件
4. **靈活配置**: 支援自定義日誌格式和輸出路徑

### 使用場景

請描述您的套件適用的場景：

- Python 應用程式需要結構化日誌記錄
- 需要自動管理日誌文件大小和數量
- 希望簡化日誌配置流程的開發者

## 📋 發佈配置

### PyPI 發佈

- **是否發佈到 PyPI**: `是`
- **是否先測試 Test PyPI**: `是`

### GitHub Actions

- **是否啟用自動化測試**: `是`
- **測試的 Python 版本**: `3.8, 3.9, 3.10, 3.11, 3.12`
- **是否啟用代碼覆蓋率檢查**: `是`
- **是否啟用代碼品質檢查**: `是`

## 🎯 版本策略

### 語義化版本控制

請確認您的版本控制策略：

- **主版本號變更**: 不相容的 API 變更
- **次版本號變更**: 向後相容的功能新增
- **修訂版本號變更**: 向後相容的問題修正

### 發佈觸發條件

- [x] 推送以 `v` 開頭的標籤到 Test PyPI
- [x] 發佈 GitHub Release 到正式 PyPI
- [ ] 手動觸發工作流程

## 📝 其他配置

### README 徽章

請選擇您想要在 README 中顯示的徽章：

- [x] PyPI 版本徽章
- [x] Python 版本支援徽章
- [x] 授權徽章
- [x] 代碼風格徽章
- [ ] 測試覆蓋率徽章
- [ ] 下載統計徽章

### 文檔

- **是否需要生成 API 文檔**: `是`（目前）
- **文檔格式**: `Markdown`
- **是否需要 GitHub Pages**: `是`（目前）

---

## 📋 檢查清單

在開始套件化之前，請確認以上資訊已完整填寫：

- [x] 套件名稱和版本已確定
- [x] 作者和維護者資訊已填寫
- [x] GitHub 倉庫資訊已準備
- [x] 授權資訊已確認
- [x] 分類標籤已選擇
- [x] 依賴資訊已列出
- [x] 功能描述已完成
- [x] 發佈策略已確定

## 🔄 更新記錄

請在此記錄資訊的更新：

- **2025-06-04**: 初始創建

---

**注意**: 填寫完成後，您可以使用這些資訊來更新 `pyproject.toml`、`README.md` 等配置文件。建議將此文件加入版本控制，但在公開倉庫中要注意不要包含敏感資訊。
