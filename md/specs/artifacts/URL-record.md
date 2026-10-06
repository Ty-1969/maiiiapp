# URL 紀錄檔（Privacy / Support pages）

版本：v1.0  
建立日期：2026-10-05  
負責人：Ty-1969

目的：集中紀錄所有用於 App Store / Play Console 的支援 URL 與隱私權政策 URL、對應的 bundle id、公開網址與版本歷史。日後對任一頁面做變更時，務必在此檔案新增一筆變更紀錄（version++ / date / 作者 / 變更說明 / 受影響 URL）。

檔案位置（repo）
- 隱私/支援文件： `docs/`（GitHub Pages 發佈來源）  
- 映射檔： `docs/mapping.json`

當前紀錄（v1.0）

- Happy Poke
  - bundle_id: `com.happypoke.app`
  - privacy (EN): https://ty-1969.github.io/maiiiapp/en/privacy/happypoke.html
  - support (EN): https://ty-1969.github.io/maiiiapp/en/support/happypoke.html
  - repo source: `docs/en/privacy/happypoke.md`, `docs/en/support/happypoke.md`

- Maiii-Focus
  - bundle_id: `tw.maiii.MaiiiFocus`
  - privacy (EN): https://ty-1969.github.io/maiiiapp/en/privacy/maiiifocus.html
  - support (EN): https://ty-1969.github.io/maiiiapp/en/support/maiiifocus.html
  - repo source: `docs/en/privacy/maiiifocus.md`, `docs/en/support/maiiifocus.md`

- MaiiiFinale
  - bundle_id: `com.maiii.MaiiiFinale`
  - privacy (EN): https://ty-1969.github.io/maiiiapp/en/privacy/maiiifinale.html
  - support (EN): https://ty-1969.github.io/maiiiapp/en/support/maiiifinale.html
  - repo source: `docs/en/privacy/maiiifinale.md`, `docs/en/support/maiiifinale.md`

- 共用文件 / 其他
  - common privacy (EN): https://ty-1969.github.io/maiiiapp/en/privacy/common.html (`docs/en/privacy/common.md`)
  - common support (EN): https://ty-1969.github.io/maiiiapp/en/support/common.html (`docs/en/support/common.md`)
  - mapping.json (repo): https://ty-1969.github.io/maiiiapp/mapping.json (`docs/mapping.json`)
  - site homepage: https://ty-1969.github.io/maiiiapp/ (`docs/index.md`)
  - support templates (EN raw): https://raw.githubusercontent.com/Ty-1969/maiiiapp/main/docs/support/artifacts/support-response-templates_en.md
  - support templates (ZH raw): https://raw.githubusercontent.com/Ty-1969/maiiiapp/main/docs/support/artifacts/support-response-templates_zh.md

變更紀錄範本（新增變更時請複製以下格式追加）

- vX.Y — YYYY-MM-DD — 作者（帳號）
  - 變更說明：例如「更新 happypoke 隱私頁內容：新增本機刪除指引」
  - 受影響檔案 / URL：列出 repo 路徑與公開 URL

後續流程（強制）
1. 任何對 `docs/` 下隱私或支援頁的變更（文字、連結、隱私揭露）都必須：  
   a) 在變更 PR 的描述中說明，並在合併後立刻在此檔案追加一筆變更紀錄。  
   b) 變更紀錄需包含版本（自動或手動遞增）、日期、作者、變更說明、受影響 URL。  
2. 若有 mapping.json 改動（URL 變更），請同時更新此檔並註明舊 URL 與新 URL。  
3. 若需回溯歷史，請查 Git commit 與本檔的變更紀錄：本檔為人可讀的快速索引，git commit 保留詳細差異。

附註
- 此檔同步存放於 repo（md/specs/artifacts），並由 GitHub Pages／CI 紀錄每次發佈紀錄。建議將此檔加入 code review 的 checklist（PR 範本）以強制落實。  

