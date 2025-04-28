# Vue 練習專案倉庫 (vue-training-with-team4)

本倉庫為 Vue 練習專案，請依照以下規則完成作業並提交。

---

## 【作業繳交規則】

1. 每位成員請在 `exercises/練習題編號/` 資料夾內新增自己的作業檔案。
2. 檔案命名格式統一為：  
   `index_學號.html`
    學號就是簽到的號碼
   - 例如：學號04 ➔ `index_04.html`
3. 分支命名格式：  
   `vue-test-學號`
   - 例如：學號04 ➔ `vue-test-04`
4. 每個人**只編輯自己的檔案**，**不要修改到其他人的檔案**。
5. **不會的可以看 solutions 資料夾解答**
6. 完成作業後，**Push 到自己的分支**，並開 Pull Request (PR)。

---

## 【Git 使用步驟】


1. 打開terminal
2. 用git clone https://github.com/chingyu0713/vue-training-with-team4.git 把目前的程式碼下載到本地端
3. 切換到倉庫名稱cd vue-training-with-team4

4. 創建新分支git checkout -b <你分支被指定的名稱>
 分支命名格式：  
   `vue-test-學號`
   - 例如：學號04 ➔ `vue-test-04`

5. 完成後 用git add .把所有檔案加入本地git
6. 再用git commit -m "你新增了什麼"把東西都commit確認
7. git push -u origin <你分支被指定的名稱>推上git

01 — 練習題目：資料綁定 (v-model)
練習內容說明：

建立一個 <input> 輸入框，使用 v-model 綁定。

底下即時顯示使用者輸入的內容。

額外挑戰：新增「清除」按鈕，清空輸入欄位。

畫面範例：`assets/01.png`


02 — 練習題目：條件渲染 (v-if / v-show)
練習內容說明：

建立一個按鈕，點擊後切換「顯示/隱藏」一段文字。

額外挑戰：按鈕文字根據狀態變化（顯示/隱藏）。

畫面範例：`assets/02.png`

