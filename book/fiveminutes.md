# 五分鐘快速理解 GitBook

GitBook 是一個能讓你使用 Markdown 語法快速撰寫、編輯與製作電子書的服務與工具。如果你不知道 Git 是什麼？也從來沒有用過它，請看第一個五分鐘介紹：

## 不懂 Git 也能善用 GitBook

註冊之前，先理解 GitBook 免費帳號是有侷限的：你可以擁有無限制的「開放」書籍專案，但只有「一本」書是私密的（private）。開放的書籍也可以販售，但略懂 Git 的人都可以隨時取得你正在編輯中的原稿；如果你對這個有顧慮，務必先將專案設定為私密。

其次，由於你沒摸過 Git，哪麼你使用 GitBook 就只有兩種方法：使用線上編輯器，或是剛剛重新回籠的桌面版編輯器。

基本操作與大多數網路服務相同，新建一個書籍專案，命名、做些設定，接著就是打開編輯器準備書寫與編輯了。

這時，你要做的第一件事：先看到畫面右上方的 **branch:master** 按鈕，點擊它、選擇 **+ New Branch**，在跳出的窗口中輸入 **draft-date**，按下確認，這時原來的按鈕應該已經變成 **branch:drafts**。好，然後你就可以開始自由使用了。

你一開始進入的 **branch:master** 叫做「主分支」，你可以把它想成「對外發行版」的意思，你每按一次儲存，實際上 GitBook 就在背後辛苦的根據新的內容製作網頁版，以及 ePub、PDF 與 Mobi 電子書。也許你可以這樣更新一般網頁，但書籍這樣可是會讓讀者瘋掉。

比較理想的狀態：你先製作了臨時版的封面、前言，或許還有第一章的內容。繼續撰寫第二章時，不管歷時多久，這些瑣碎的修改與異動都不該讓讀者看到。一直等到寫完第二章、校對過幾次之後，「對外發行版」才正式更新到第二章，讀者收到通知、下載新的版本，開始快樂的閱讀。

前面我們新增的 **branch:draft-date**，就是獨立於「對外發行版」的平行世界，讓你能自由發揮，不用擔心影響讀者。這裏的 **date** 可以是你建立這個分支的日期，也可以是任意的名稱，但最好是不重複。後面我們會解釋為什麼。