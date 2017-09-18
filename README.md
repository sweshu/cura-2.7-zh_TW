# cura 2.7 繁體中文翻譯

寫在前面
----------
- 本專案的翻譯工作已告一段落，並提交給官方。等官方繁中版釋出後本專案就會關閉
- 若有任何意見，歡迎透過 issues 加入討論。但修改會等到下一次的翻譯（如果有的話）再進行


安裝方式
----------
1. 點擊網頁右上方 `Clone or download` 綠色按鈕，選擇 `Download ZIP`
2. 解壓 zip 檔後，將 `Cura 2.7\` 目錄複製到你 cura 2.7 的目錄下即可。
3. Windows 的 cura 2.7 目錄通常是在 `c:\Program Files\Cura 2.7\`


設定方式
----------

### 方法一 ( 官方建議方式 )
1. 打開 cura
2. 點擊選單 Help 的第一項 `Show Configuration Folder`，打開設定檔所在的資料夾
3. 使用文字編輯器編輯 cura.cfg 這個檔案
4. 找到 `language = xxxx` 這一行，改成 `language = zh_TW`
5. 如果找不到 `language = xxxx` ，可以直接把 `language = zh_TW` 加在 `[general]` 下面一行
6. 關閉 cura 再重新打開

### 方法二
1. 使用文字編輯器編輯下面的檔案
   `c:\Program Files\Cura 2.7\resources\qml\Preferences\GeneralPage.qml`
2. 搜尋這一行
   `append({ text: "简体中文", code: "zh_CN" })`
3. 在底下增加一行
   `append({ text: "繁體中文", code: "zh_TW" })`
4. 執行 cura ，在設定中就會多出繁體中文可以選擇了


問題回報
----------
1. 請連到 [cura-2.7-zh_TW](https://github.com/dinowchang/cura-2.7-zh_TW) 的網頁
2. 登入 github ，如果沒有帳號請先申請一個
3. 點選網頁上方的 Issues 分頁
4. 請先搜尋一下，你的問題是否已經有人回報。如果已有人回報，直接參與討論即可
5. 點選右上方 `New issue` 的綠色按鈕，回報新的問題
6. 回報內容請包含下列項目
   * 原始翻譯句子
   * 建議翻譯句子
   * 最好能提供該翻譯句出現的地方或是使用的情境，因為有時按照情境翻譯會比照原文字面翻更好
