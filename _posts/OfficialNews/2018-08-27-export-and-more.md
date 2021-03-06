---
layout:     page
title:      聊天紀錄匯出工具，更好的通知，及更多
categories:
          - 官方新聞
upstream:   https://telegram.org/blog/export-and-more
preview_image: /images/export-and-more01.jpeg
---
<img alt="" src="{{ site.baseurl | prepend: site.url }}/images/export-and-more01.jpeg">
<br>
今天的 Telegram 更新為您提供了一種在磁碟上保存聊天的簡便方法。只需輕點幾下，您就可以匯出部分（或全部）聊天內容，包括照片和其他媒體。因此，您將可以用JSON格式或精美的HTML格式離線存取所有資料。
<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/export-and-more02.jpeg" width="70%"></center>
<center>資料匯出結果</center>
<br>
要使用此功能，請確保在計算機上安裝了最新版本的 <a href="https://desktop.telegram.org/">Telegram Desktop</a>，然後點擊 **設定 > 進階 > 匯出 Telegram 資料**。此工具對於擁有數百萬則訊息卻無法輕鬆存取其訊息紀錄中最早期部分的用戶特別有用。
<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/export-and-more03.gif" ></center>
<br>
您可以透過在任何聊天中開啟...選單並選擇**匯出聊天紀錄**來匯出個別的聊天。

### 通知中的例外情況
Telegram 是第一款為其用戶提供極其靈活、可以微調其訊息通知工作方式的應用程式。今天，我們透過在通知設定中添加例外來進一步實現這一點（ Android 及 iOS 版），您可以在其中看到哪些聊天是例外於全域設定（ **設定 > 通知和聲音** ）。
<center><img alt="" src="{{ site.baseurl | prepend: site.url }}/images/export-and-more04.jpeg" width="70%"></center>
<center>通知例外</center>
<br>
要將所有聊天關閉通知但少數例外（或相反）從未如此簡單。

### 改進了 Telegram Passport
<a href="https://telegram.how/2018/07/26/passport">Telegram Passport</a> 被廣泛接受讓我們感到有點不知所措 - 這工具用於需要以真實身分登入的第三方應用。發布僅兩週後，Passport 就可以用於註冊許多服務，包括建立**共享經濟服務**到**區塊鏈新創公司**。

僅舉幾個整合 Telegram Passport 的項目：<a href="https://sumsub.com/">Sum＆Substance</a>（ KYC 和用戶驗證），<a href="https://cex.io/">CEX.IO</a> 和 <a href="https://xena.exchange/">Xena</a>（加密貨幣交易），<a href="https://cryptopay.me/">CryptoPay</a>（電子錢包），<a href="https://youdrive.today/">YouDrive</a>（汽車共享），<a href="https://profi.ru/">Profi</a> 和 <a href="https://worki.ru/">Worki</a>（就業市場），<a href="https://www.minter.network/">Minter Network</a> 和 <a href="https://minexcoin.com/">Minexcoin</a>（區塊鏈新創公司），<a href="https://www.kickico.com/">KICKICO</a>，<a href="https://cryptonomos.com/">Cryptonomos</a> 和 <a href="https://icoadm.in/en/">ICOadmin</a>（ICO平台）。

在此成功的基礎上，今天我們正在升級 Passport 以支援原始語言的名稱和其他類型的文件。我們還加強了加密 Passport 資料的<a href="https://core.telegram.org/passport/encryption">演算法</a>，以更好地保護您的資料免於受來自 Telegram 駭客的攻擊（儘管看起來不太可能）。這樣一來，我們更能確保只有您可以存取您自己的私人資料。

### 原始碼和 API
與往常一樣，您無需了解我們的加密工作原理。更新的 Telegram 應用程式原始碼反映了今天的所有變更，可以在 GitHub 上找到並開放供所有人查看。如果您是需要身分驗證的服務之開發人員，請務必查看<a href="https://core.telegram.org/passport">這些文件</a>，那說明了如何將 Telegram Passport 整合到您的應用程式中。


2018年8月27日<br>
Telegram 團隊
