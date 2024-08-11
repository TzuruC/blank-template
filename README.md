# blank-template

- 僅安裝 sass 的全裸開發環境，
- 使用時需先安裝 sass，
- 並使用 npx sass --watch main.scss:output.css 監聽 sass 轉譯。

# 使用說明

1. 複製完template包後，先執行 npm i 安裝 node_modules (裡面只有sass)

2. 在 src/scss 下新增 scss 檔案，不要新增任何檔案在 src/css 底下

3. 執行 npx sass --watch main.scss:output.css 監聽整個 scss 資料夾檔案

4. html 檔案中載入 link 的路徑，使用 css 檔案的路徑即可 (map可以不使用)
