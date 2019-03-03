---
layout:     page
title:      介紹 iOS 平台的 Telegram 5.0
categories:
          - 官方新聞
upstream:   https://telegram.org/blog/telegram-5-ios
---
<img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios01.jpeg">
<br>
在過去的幾年裡，我們一直在悄悄地用 Swift 重建 iOS 版的 Telegram。而 Swift 為 Apple 用來取代 Objective C 的程式語言，它的速度比 Objective C 更快。

今天 Telegram 5.0 正式推出給**我們所有的 iOS 用戶**，並成為完全使用 Swift 編寫的通訊程式中最受歡迎的。這新版本的 Telegram 看起來和舊版一樣，但更**流暢**、更**省電**，而速度也**更快**（和原有的速度相比較，它的進步是令人驚豔地）。

<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios02.gif" width="70%"></center>
<br>
新應用程式在許多方面都很出色。我們喜歡聊天室中新的**平滑動畫**。即使您長時間沒有開啟 Telegram 並且有很多訊息需要同步的，訊息現在也會**快速同步**。我們也改進了應用程式在背景的活動，以確保所有**已關閉通知的聊天**始終**保持最新狀態**。
<br>
### 退一步 - 然後回來
新的**可擴展應用內通知**將幫助您專注於您在程式中所做的任何事情，而無需忽略傳入的消息。通知到達時，將其拉下以開啟相關聊天室。當您完成後，只需將其關閉即可直接回到您正在做的事情。
<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios03.jpeg" width="70%"></center>
<center>擴展通知</center>
<br>
這可運作於應用程式的**每一處**，包括您在查看媒體或閱讀即時瀏覽的文章時。

### 讓每個聊天計數
之前，在您加入一個或兩個擁有100,000名成員的群組後，未讀數量標記可能會變得不那麼有用。今天我們讓私聊再次變得偉大。

您現在可以將計數器原本顯示的未讀訊息數量改為未讀聊天數量。取代已關閉通知群組中的一千則訊息，而顯示一則來自您寵物的重要訊息息，您的未讀數量標記將如下所示：
<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios04.jpeg" width="70%"></center>
<center>一個未讀聊天</center>
<br>
您可以在「設定」>「通知和聲音」中調整此行為。

### 從哪裡開始的？
我們改進了熱鬧聊天室的閱覽方式。稍微捲動聊天頁面會浮現您正在觀看訊息的傳送**日期**，然後點擊日期可前往該日期的**第一則**訊息。
（譯者：手機版是這樣，而桌面版點擊浮現的日期則會出現月曆，讓您可以任意跳轉到某日期訊息的開始。）

### 蟲子已死。蟲子萬歲！
儘管我們非常喜歡，但我們無法移植 Objective C 版本中的任何錯誤。所有舊的錯誤現在都永遠消失了 - 或者，我們應該說，**修復了**。在編寫新版本時，我們可能會產生一些新的臭蟲。但不要擔心，我們很快就會解決這些問題。同理，任何缺少的小功能也可以很快被加入。

### 而在 macOS 上…
您現在可以在 <a href="https://macos.telegram.org/">macOS 專用版的 Telegram</a> 上使用**滑動手勢**來操作介面。最值得注意的是，您可以滑動回覆，聊天清單現在的運作方式與 iOS 版相同：向右滑動標記為「已讀/未讀」，然後向左滑動可「置頂」、「關閉通知」或「刪除」。

<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios05.jpeg" width="70%"></center>
<center>向左或向右滑動以選擇選項</center>
<br>
昂貴 MacBook Pro 的用戶只需獲得進階的**觸控欄**支援，即可幫助他們傳送貼圖和媒體，控制提示和彈出視窗中的按鈕等。

<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios06.jpeg" width="70%"></center>
<center>MacBook Pro 上的貼圖及更多</center>
<br>
其他新功能包括**自動夜間模式**設定和照片編輯器，可在傳送前**旋轉**和**裁剪**圖片。您還可以拖放照片、媒體和檔案以**更改傳送順序**。

### …還有 Telegram Desktop
至於我們的通用 Telegram Desktop 應用程式，它只是在**設定**的部份進行了大規模的改造。新的版面設計類似於我們在行動App中使用的：

<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios07.jpeg" width="70%"></center>
<center>Telegram Desktop 設定</center>
<br>
最新的 Telegram Desktop 還改進了**圖片**和**動圖**的**快取**功能，以及新的**本地儲存設定**。前往「設定」>「進階」>「管理本地儲存」以控制 Telegram 在電腦上使用的硬碟空間。

我們還重新設計了**主題選擇器**，以便更輕鬆地選擇最適合您的日夜主題。提醒您，您可以製作自己的主題 - 或查看<a href="https://t.me/themes">其他用戶創建的主題</a>。

<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/telegram-5-ios08.jpeg" width="70%"></center>
<center>挑選您要的顏色</center>
<br>
今天就這樣了。請繼續關注我們所有平台上的更多更新。


2018年10月1日<br>
Telegram 團隊
