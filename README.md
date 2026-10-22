# 成語索引查找

單一靜態網頁，無需伺服器。

## 發佈到 GitHub Pages
1. 在 GitHub 建立新 repository（建議 Private；公開 repo 任何人都能看到網頁內容）。
2. 把本資料夾的 4 個檔案（index.html、manifest.webmanifest、icon.svg、icon.png）上傳到 repository 根目錄。
3. Settings → Pages → Source 選 Deploy from a branch，Branch 選 main、資料夾選 / (root)，儲存。
4. 數分鐘後得到網址：https://你的帳號.github.io/repository名稱/
5. 手機或 iPad 用 Safari 打開，分享 → 加入主畫面。

## 校正與備份
校正內容暫存在該瀏覽器。每校正一輪，按頁面底部「匯出 CSV」存到 iCloud Drive。

## 校正自動同步到 GitHub（選用）
1. GitHub → Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token。
2. Repository access 只選這個 repository；Permissions → Repository permissions → Contents 設為 Read and write。
3. 在網頁底部「GitHub 同步設定」填入帳號、repository 名稱、分支和 token，按「儲存設定並同步」。
4. 之後每次校正約 3 秒後自動上傳到 repository 的 idx-data.json；換裝置時填入同樣設定，網頁會自動載入最新校正。
5. token 只保存在該瀏覽器，不會寫進 repository。
