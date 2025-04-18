# 難民潮

大家熟悉的社群平台 Meta (前 Facebook)，進日因為用於內容顯示的演算法、隱私以及內容審查等疑慮，讓大家閃避不急，紛紛開始尋找其他社交工具的替代方案。

其實類似的事情不僅這一次，2022 年年末，Elon Musk 買下 Twitter 後，修改演算法、開始推動部份功能收費，也造成恐慌。

參考資料：
- [仇恨言論、煽動暴力是否該審查？馬斯克收購Twitter，但他口中的「言論自由」受到外界質疑 - TNL The News Lens 關鍵評論網
](https://www.thenewslens.com/article/166075)
- [使用者冒充嘲諷新認證制遭停權，馬斯克揚言強化推特帳號管制 | iThome](https://www.ithome.com.tw/news/154075)
- [軟體自由電子報 #9 | 聯邦宇宙的七月砲火(上)：巨獸 Threads 來襲 | SLAT 中華民國軟體自由協會](https://slat.org.tw/index.php/node/190)
- [軟體自由電子報 #10 | 聯邦宇宙的七月砲火(下)：流離尋岸 | SLAT 中華民國軟體自由協會](https://slat.org.tw/index.php/node/191)
- [前臉書總監指中國介入 Meta 審查台港用戶發文 ｜ 公視新聞網 PNN](https://news.pts.org.tw/article/746619)
- [追蹤馬斯克私人飛機的推特帳號遭永久停權 | iThome](https://www.ithome.com.tw/news/154712)


----


# awesome-fediverse-in-taiwan

在台灣的聯邦宇宙站台與服務

聯邦宇宙站台（只列出有開放註冊的）

 - https://g0v.social (Mastodon)：台灣人數最多的站台，和 g0v 計劃有關，需遵守 g0v 社群守則
 - https://klog.tw (Mastodon)：分享流行音樂，影視作品與記錄生活
 - https://taiwan.wtf (Mastodon)：這裡是台灣幹網 3.0，我們僅存的網路自由越來越少，這是一個自由網路海洋的幹話王國，歡迎嚮往自由的您在尊重他人的前提下進來與我們同樂 ~
 - https://seediqbale.xyz (Misskey)：歡迎來到真正的人！運行在 fediverse 中的分散式社群網路服務
 - https://mistyreverie.org (Misskey)：使用 Misskey 架設的去中心化社群網路，類似 Twitter。本站的特色以動畫、漫畫與遊戲為主，但不僅限於此。本站主要使用的語言是中文、日文、英文。
 - https://social.slat.org (Mastodon)：這是中華民國軟體自由協會 (SLAT) 的 Mastodon 社交平台。


中繼器（Relay）

 - https://aode.seediqbale.xyz/
 - https://relay-tw.seediqbale.xyz/ （繁中和Tâi-gí臺語的實例）
 - https://relay.mistyreverie.org/
 - https://pass.zeroplex.tw/

----

# 行動裝置 apps

這裡列出常見的 app，但不是全部的 app，若有遺漏歡迎大家推薦。

備註：Misskey 網站 [設計為 PWA](https://misskey-hub.net/tw/docs/for-users/resources/apps/)，所以並沒有官方 app

## Android Apps

- [Mastodon](https://play.google.com/store/apps/details?id=org.joinmastodon.android) (Mastodon 官方 app，支援多帳號)
- [Tusky](https://play.google.com/store/apps/details?id=com.keylesspalace.tusky) (Mastodon，[原始碼](https://github.com/tuskyapp/Tusky))
- [Milktea](https://play.google.com/store/apps/details?id=jp.panta.misskeyandroidclient) (Misskey、Mastodon)
- Aria ([Google Play](https://play.google.com/store/apps/details?id=com.poppingmoon.aria&hl=zh_TW) 或 [F-Droid](https://f-droid.org/packages/com.poppingmoon.aria/)) (Misskey)
- Moshidon ([Google Play](https://play.google.com/store/apps/details?id=org.joinmastodon.android.moshinda) 或 [F-Droid](https://f-droid.org/zh_Hant/packages/org.joinmastodon.android.moshinda/)) (Mastodon、Pleroma、Akkoma，支援多帳號)
  - 特色是支援 Emoji Reaction，還有能連轉嘟也能控制可見度。Mastodon 的話 Emoji Reaction 功能只有極少數站點實裝 (例如 fedibird.com），但就算站點不支援也不會影響使用。
  - 目前穩定性較差，暫時不推薦作為主力使用。[作者](https://floss.social/@moshidon) 正在把 App 重寫，在這之後可以再考慮看看。

## iOS Apps

- [IceCubes](https://apps.apple.com/us/app/ice-cubes-for-mastodon/id6444915884) (mastodon)
- [Mona](https://apps.apple.com/jp/app/%E3%83%A2%E3%83%8A-%E3%83%95%E3%82%A9%E3%83%BC-%E3%83%9E%E3%82%B9%E3%83%88%E3%83%89%E3%83%B3-mona-for-mastodon/id1659154653?uo=4&mt=8) (Mastodon)
- [Miria](https://apps.apple.com/jp/app/miria/id6449201469) (Misskey)
- [MissCat](https://apps.apple.com/us/app/misscat-misskey-%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88/id1505059993) (Misskey)
- [SocialHub](https://apps.apple.com/us/app/socialhub-socialmedia-client/id1474451582) (Mastodon、Misskey、Bluesky)

## 網頁介面 / PWA

可以作為網頁介面登入 Mastodon，也可以通過新增手機網頁捷徑成為 PWA

- [Phanpy](https://phanpy.social/)
- [Elk](https://elk.zone/)