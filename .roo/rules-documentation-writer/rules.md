# Documentation Writer 角色規範

## 1. 文件語言
- 所有技術文件、註解、JSDoc 必須使用繁體中文。
- 專有名詞可保留英文，但需於首次出現時加註說明。

## 2. 文件結構
- 文件需有明確標題、目錄（如適用）、章節分明。
- 每個段落前後需空一行，保持可讀性。
- 重要章節（如安裝、使用、API、注意事項）需獨立分節。

## 3. 文件格式
- 優先使用 Markdown 格式（.md）。
- 標題層級需依內容邏輯遞減（#、##、###）。
- 程式碼範例需使用程式碼區塊（\`\`\`），並標註語言。
- 每行建議不超過 100 字元，必要時換行。

## 4. 命名與檔案管理
- 文件檔名採用 kebab-case。
- 文件放置於專案根目錄或 docs/、.roo/ 等專屬資料夾。
- 文件需有明確檔案名稱與用途說明。

## 5. JSDoc 與註解
- 所有公開函式、元件、類別必須加上完整 JSDoc。
- JSDoc 需說明用途、參數、回傳值、例外狀況。
- 重要邏輯、複雜流程需加上繁體中文註解，註解需簡潔明確。

## 6. 範例與圖示
- 文件中如有 API、元件、指令等，需附上實際範例。
- 範例需可直接複製執行，並標註預期結果。
- 如有流程、架構，建議附上圖示（可用 mermaid 或圖片）。

## 7. 一致性與可維護性
- 文件風格需與專案其他文件一致。
- 定期檢查並更新過時內容。
- 移除冗餘或重複文件，確保唯一來源。

## 8. 文件審查流程
- 新增或修改文件需經過審查（Code Review）。
- 文件審查重點：正確性、完整性、易讀性、一致性。
- 審查通過後方可合併至主分支。

## 9. 其他注意事項
- 禁止將敏感資訊（如密碼、API 金鑰）寫入文件。
- 文件需保留一行結尾空白行，使用 Unix (LF) 換行。
- 文件內容需避免主觀評論，保持中立、專業。
