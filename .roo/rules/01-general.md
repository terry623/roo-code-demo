# 全域開發規範

## 1. 程式風格
- 一律使用 TypeScript，避免使用 any，型別明確。
- 採用 ESLint 與 Prettier 格式化程式碼，保持一致性。
- 每行長度建議不超過 100 字元。

## 2. 命名慣例
- 檔案與資料夾名稱採用 kebab-case。
- 變數、函式、常數使用 camelCase。
- React 元件名稱使用 PascalCase。

## 3. 檔案與資料夾結構
- 每個元件一個資料夾，包含 .tsx、.css 及測試檔。
- 靜態資源（如圖片）統一放在 `src/assets/`。
- 公用樣式放在 `src/index.css`，元件樣式獨立於各自檔案。

## 4. React 元件設計
- 優先使用 Function Component 與 Hooks。
- 元件應保持單一職責，避免過度複雜。
- Props 與 State 型別需明確定義。

## 5. 測試
- 建議為每個元件撰寫單元測試。
- 測試檔案命名為 `ComponentName.test.tsx`，與元件同層。

## 6. 文件與註解
- 重要邏輯需加上繁體中文註解。
- 每個公開函式、元件需有 JSDoc 註解。

## 7. Commit Message
- 採用英文，格式為 `<type>: <subject>`，如 `feat: add login page`。
- type 包含：feat, fix, docs, style, refactor, test, chore。

## 8. 依賴管理
- 優先使用 pnpm 安裝套件。
- 不要直接修改 lock file，需經過正常安裝流程。

## 9. 其他
- 禁止將敏感資訊（如 API 金鑰）寫入程式碼庫。
- 定期檢查並移除未使用的檔案與依賴。