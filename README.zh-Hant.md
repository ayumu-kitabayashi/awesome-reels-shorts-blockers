# iPhone 隱藏 IG Reels 和 YouTube Shorts 的 App 與設定整理（私訊照用）
[English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt-BR.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Bahasa Indonesia](README.id.md) | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Русский](README.ru.md) | **繁體中文**

這份清單整理了 iPhone 上能隱藏 **Instagram Reels、YouTube Shorts 和 TikTok「為你推薦」** 的 App 與設定，同時每個 App 的其他功能都照常能用：私訊、群組聊天、搜尋，以及你追蹤的帳號。

> **揭露：** 這份清單由 [minulo](https://minulo.app/zh-Hant/) 的開發者維護，minulo 也是下面列出的 App 之一。所有資訊只取自各 App 的美國 App Store 頁面或官方網站（2026 年 10 月確認；評分數最後更新於 2026-10-24）。評分數每天都會變動。歡迎透過 issue 或 pull request 指正或補充。


<a id="quick-answers"></a>
## 快速解答
- **哪些免費的 iPhone App 能隱藏 Instagram Reels 和 YouTube Shorts，又保留私訊？** 在自家 App 裡，minulo（10 個平台）、Reelmute（6 個）、Stillfeed（Instagram 和 YouTube）和 Awhile（只有 Instagram）的基本隱藏功能免費。Nope 和 ScrollGuard 以 Safari 延伸功能的形式免費做到，所以只在 Safari 裡有效。noShorts 免費，也沒有 App 內購買。各自哪些部分免費：[免費封鎖 Reels 和 Shorts 的 App](https://minulo.app/zh-Hant/free-reels-blocker.html)。
- **怎麼去掉 YouTube Shorts，但保留一般影片？** YouTube 的 Shorts 動態限制可以設成 0，但成人帳號可以直接關掉提醒。minulo、Stillfeed、Reelmute 和 noShorts 會在自家 App 裡開啟沒有 Shorts 的 YouTube；Nope 則是在 Safari 裡做到。在 minulo 裡，一般影片、搜尋和訂閱內容都照常可用。（[做法](https://minulo.app/zh-Hant/block-youtube-shorts.html)）
- **Instagram 能只用來私訊嗎？** Instagram 本身沒有只用私訊的模式。minulo 的「私訊以外的分頁」設定是免費的；UNDOOMED、Stillfeed、Reelmute 和 Konvo 的只看訊息畫面則要付費。（[做法](https://minulo.app/zh-Hant/instagram-dms-only.html)、[只用私訊的免費 App](https://minulo.app/zh-Hant/free-instagram-dms-only-app.html)）
- **有哪些 App 用起來像 SocialLite？** 同樣能用「螢幕使用時間」鎖住官方 App，並把你帶到自家畫面的 App：minulo、noShorts、snowscroll、Reelmute 和 Konvo。（[比較](https://minulo.app/zh-Hant/sociallite-alternatives.html)）
- **SocialLite 免費嗎？** 可以免費下載，並提供 App 內購買；Pro 依方案不同，每月 $6.99 至 $17.99 或每年 $19.99 至 $47.90，家庭方案每月 $12.99（美國 App Store，2026-10-26 確認）。minulo、Stillfeed 和 Reelmute 免費隱藏 Reels 和 Shorts；Nope 在 Safari 裡完全免費。（[價格和免費的替代 App](https://minulo.app/zh-Hant/is-sociallite-free.html)）
- **晚上怎麼停止一直滑 Reels 和 Shorts？** iPhone「螢幕使用時間」裡的「停用時間」會封鎖整個 App，私訊也包括在內。在 minulo，隱藏 Reels 和 Shorts 是免費的，minulo 自家的畫面也會保留私訊；鎖住官方 App 每次最多 2 小時免費，每晚的排程屬於 Pro。下面其他 App 也有排程，請看各 App 的介紹。（[做法](https://minulo.app/zh-Hant/stop-doomscrolling-at-night.html)、[晚上停不下來滑 TikTok](https://minulo.app/zh-Hant/stop-scrolling-tiktok-at-night.html)）


## 目錄
- [快速解答](#quick-answers)
- [內建設定（不用裝 App）](#built-in-settings)
- [把動態拿掉後再開社群的 App](#in-app-browsers)
- [Safari 延伸功能](#safari-extensions)
- [整個 App 一起封鎖的 App（私訊也會被擋）](#whole-app-blockers)
- [怎麼選](#how-to-choose)
- [教學](#guides)
- [其他語言的教學](#guides-other-languages)
- [資料（CSV）](#data)


<a id="built-in-settings"></a>
## 內建設定（不用裝 App）
- **YouTube 的 Shorts 動態限制**：YouTube 可以替 Shorts 動態設定每天的上限（也可以設成 0）。成人帳號的提醒可以直接關掉，而且只在 YouTube App 裡有效。（[做法](https://minulo.app/zh-Hant/youtube-shorts-feed-limit.html)）
- **Instagram 的「追蹤中」動態（Following）**：把首頁動態切換成只顯示你追蹤的帳號。Reels 分頁和「探索」還是會在。
- **Instagram 的「暫停建議貼文」（Snooze suggested posts）**：在建議貼文上點 ⋯ →「沒興趣」→ 將動態中所有建議貼文暫停 30 天。30 天後就會恢復，而且不影響 Reels 分頁。（[做法](https://minulo.app/zh-Hant/hide-suggested-posts-instagram.html)）
- **Instagram 的「重設建議內容」（Reset suggested content）**：從「設定」→「內容偏好設定」→「重設建議內容」，可以清掉 Instagram 在「探索」、Reels 和動態裡推薦給你的內容。這個動作無法復原，而且你繼續看下去，推薦又會重新學習。（[做法](https://minulo.app/zh-Hant/reset-instagram-reels-recommendations.html)）
- **關閉 YouTube 自動播放**：下一部影片不會再自己開始播。除非觀看記錄已關閉而且是空的，否則推薦還是會出現。（[做法](https://minulo.app/zh-Hant/turn-off-youtube-autoplay-recommendations.html)）
- **iPhone 的「螢幕使用時間」**：限制或封鎖整個 App。私訊和群組聊天也會跟著動態一起被擋住。


<a id="in-app-browsers"></a>
## 把動態拿掉後再開社群的 App
這些 App 會在自己的 App 裡開啟各社群的網站，並隱藏 Reels、Shorts 或「為你推薦」。有些還能用「螢幕使用時間」鎖住官方 App，讓你不會因為習慣又點回去。

- **[SocialLite](https://apps.apple.com/us/app/id6757661674)**：在 App 裡用專注模式瀏覽社群；根據版本說明，可以用「螢幕使用時間」封鎖官方 App，並轉到 SocialLite。支援平台：Instagram、YouTube、Snapchat、X、Reddit 等（未提到 TikTok）。價格：免費下載；Pro 依方案為每月 $6.99 或 $9.99，或每年 $19.99 到 $47.90（美國）。保留私訊：是。美國 App Store 評分數：約 15,000（★4.7）。
- **[UNDOOMED](https://apps.apple.com/us/app/id6751837079)**：在自己的私密瀏覽器中開啟各社群的行動版網站，並過濾頁面內容。支援平台：Instagram、Threads、Reddit、Facebook、X、YouTube、LinkedIn（不支援 TikTok 和 Snapchat）。價格：許多功能免費；Plus 每月 $1.99 或每年 $11.99，Pro 每月 $2.99、每年 $17.99 或終身 $29.99（美國）。保留私訊：是（Messages Only 模式）。美國 App Store 評分數：108。
- **[Dull](https://apps.apple.com/us/app/id6759723829)**：在自己的瀏覽器中開啟各平台，拿掉 Reels、Shorts、「為你推薦」和「探索」。支援平台：Instagram、YouTube、Facebook、X、Reddit。價格：免費下載。保留私訊：是。美國 App Store 評分數：55。其他：每日上限、安靜時段，放寬過濾前需等待 24 小時。
- **[WallHabit](https://apps.apple.com/us/app/id6751423279)**：封鎖 Reels 和 Shorts 或整個 App，解鎖前要先長按按鈕（說明中沒有寫 Reels 是怎麼被擋的）。支援平台：未列出。價格：免費，含 App 內購買。保留私訊：未說明。美國 App Store 評分數：35。其他：需要 iOS 18。
- **[LoomWeb](https://apps.apple.com/us/app/id6754727620)**：專為社群設計的瀏覽器，每個網站可以分開設定。支援平台：Instagram、YouTube、X、Facebook。價格：免費，另有 Pro 方案。保留私訊：是（有「只用私訊」選項）。美國 App Store 評分數：34。其他：需要 iOS 18。
- **[Scroll Less](https://apps.apple.com/us/app/id6741134096)**：在自己的極簡瀏覽器（WebView）中開啟 YouTube、Instagram 等平台，拿掉演算法推薦動態。支援平台：YouTube、Instagram 等（沒有完整清單）。價格：免費下載。保留私訊：未說明。美國 App Store 評分數：23。
- **[Sociano](https://apps.apple.com/us/app/id6760568406)**：在自己可控管的瀏覽器中開啟支援的社群，封鎖 Reels、Shorts 和動態；也能用「螢幕使用時間」封鎖你選的 iPhone App。支援平台：Instagram、YouTube、X、Facebook、LinkedIn 等。價格：免費下載。保留私訊：是。美國 App Store 評分數：10。其他：App 封鎖、排程和每日上限。
- **[snowscroll](https://apps.apple.com/us/app/id6778488660)**：在專注的 App 內瀏覽器中開啟各社群的行動版網站並隱藏動態；搭配「螢幕使用時間」，點真正的 Instagram App 時會改開 snowscroll。支援平台：Instagram、YouTube、Facebook、X、TikTok、LinkedIn。價格：免費下載。保留私訊：是。美國 App Store 評分數：10。其他：官方 App 的封鎖畫面。
- **[Awhile](https://apps.apple.com/us/app/id6763551826)**：在自己的 App 內瀏覽器載入 instagram.com，並隱藏你選的部分。支援平台：只有 Instagram。價格：過濾功能免費；Premium 每月 €2.99 或一次買斷 €9.99。保留私訊：是。美國 App Store 評分數：4。
- **[Fluid Friction](https://apps.apple.com/us/app/id6782510849)**：在 App 裡開啟社群，讓滑動態變得比較費力；也能隱藏 Reels、Shorts、限時動態和「探索」。支援平台：Instagram、TikTok、YouTube、Reddit、X、Snapchat、Facebook、LinkedIn。價格：免費下載。保留私訊：是（訊息照常可用）。美國 App Store 評分數：6。其他：可用「螢幕使用時間」封鎖其他 App。
- **[minulo](https://apps.apple.com/us/app/id6809352229)**：在 App 裡開啟各社群的官方網站，並隱藏你選的部分。也能用「螢幕使用時間」鎖住官方 App，改帶你到 minulo。支援平台：Instagram、YouTube、TikTok、X、Threads、Facebook、Pinterest、Reddit、LinkedIn、Snapchat（10 個）。價格：隱藏功能免費，鎖住官方 App 每次最多 2 小時也免費；Pro（美國每月 $9.99 或每年 $39.99）加上排程、Hard Mode、更長的封鎖時間和多組封鎖清單。保留私訊：是。美國 App Store 評分數：0。其他：支援 iPhone 和 Mac；沒有 Android 版。由這份清單的作者維護。
- **[Stillfeed](https://apps.apple.com/us/app/id6792934511)**：在內建瀏覽器中開啟 Instagram 和 YouTube，拿掉 Reels、「探索」和 Shorts。支援平台：Instagram、YouTube。價格：封鎖 Reels 和 Shorts 免費；Pro 加上只看追蹤對象的動態、封鎖限時動態和動態，以及只用私訊模式。保留私訊：是。美國 App Store 評分數：0。其他：每週封鎖統計。
- **[Unfeed](https://apps.apple.com/us/app/id6814847686)**：在自己的 App 裡開啟社群，用過濾器讓動態載入不出來。支援平台：Instagram、TikTok、YouTube、X。價格：免費下載；Pro 加上隱藏廣告、建議貼文和限時動態，以及多帳號。保留私訊：是。美國 App Store 評分數：0。其他：單次使用計時、每日額度、睡眠模式。
- **[Konvo](https://apps.apple.com/us/app/id6794756261)**：打開 Instagram 直接進收件匣；動態、Reels 和「探索」完全不會載入。支援平台：Instagram（只有訊息）。價格：要在 App 裡使用 Instagram 私訊，需付費訂閱。保留私訊：是。美國 App Store 評分數：1。其他：可以鎖住 Instagram App；每天兩次短暫通行。
- **[Scrollout](https://apps.apple.com/us/app/id6802054477)**：在支援的平台上隱藏 Reels、Shorts、建議內容和廣告。支援平台：YouTube 等（沒有完整清單）。價格：免費下載。保留私訊：是。美國 App Store 評分數：0。
- **[Reelmute](https://apps.apple.com/us/app/id6808963180)**（在日本的名稱是「リールとショートを非表示」）：在 App 裡開啟社群，在頁面顯示前就隱藏 Reels、Shorts 和「為你推薦」；Premium 可以鎖住原本的 App。支援平台：Instagram、YouTube、TikTok、Facebook、Reddit、X。價格：隱藏功能免費；Premium 加上只用私訊、隱藏建議貼文和鎖住 App（3 天試用或終身）。保留私訊：是。美國 App Store 評分數：0。其他：小工具、睡眠模式、灰階。
- **[Noreel](https://apps.apple.com/us/app/id6760568462)**：在你瀏覽動態、看限時動態、傳私訊和搜尋時拿掉 Reels。支援平台：未列出（「social media」）。價格：免費使用，沒有訂閱。保留私訊：是。美國 App Store 評分數：8。
- **[LockedIn](https://apps.apple.com/us/app/id6767055765)**：永久封鎖 Instagram Reels 和 YouTube Shorts，另有選用開關可關掉 Instagram 首頁動態、限時動態、搜尋和「探索」、私訊裡的影片播放，以及 YouTube 首頁的推薦和訂閱內容（說明中沒有寫運作方式）。支援平台：Instagram、YouTube。價格：免費下載。保留私訊：是。美國 App Store 評分數：1。其他：不需帳號，沒有分析或追蹤。
- **[Dome](https://apps.apple.com/us/app/id6756055866)**：拿掉 Reels、Shorts 和「探索」頁面，其他部分保留。支援平台：未列出。價格：免費，沒有付費牆和廣告。保留私訊：未說明。美國 App Store 評分數：1。
- **[SocialRouter](https://apps.apple.com/us/app/id6758858307)**：替多個社群帳號分開的瀏覽空間；可以隱藏 Instagram 的 Reels、動態和「探索」，以及 YouTube 的 Shorts。支援平台：Instagram、YouTube 等。價格：免費下載。保留私訊：未說明。美國 App Store 評分數：13。其他：每個平台可用多個帳號，每個帳號可設定不同的 proxy。
- **[noShorts](https://apps.apple.com/us/app/id6821704649)**：在 App 裡開啟社群，拿掉 Reels、Shorts、「為你推薦」和 Spotlight；跟著引導設定，就能用「螢幕使用時間」封鎖各社群自己的 App，並轉到 noShorts。支援平台：Instagram、YouTube、TikTok、Snapchat、Facebook、X（可加入 Reddit、Bluesky 和 Tumblr）。價格：免費，沒有訂閱和 App 內購買。保留私訊：未說明（「use it as usual」）。美國 App Store 評分數：0。其他：每日上限、安靜時段、小工具，不需帳號也沒有分析。
- **[TheSNSisMine](https://apps.apple.com/us/app/id6765809922)**：用來看 Instagram、YouTube、Facebook 和 X 網頁版的瀏覽器 App，會隱藏推薦貼文、Reels 和 Shorts，動態只留下你追蹤的人。支援平台：Instagram、YouTube、Facebook、X。價格：需要訂閱（說明中寫每月 ¥200，可免費試用 7 天）。保留私訊：未說明。美國 App Store 評分數：0。
- **[Feather](https://apps.apple.com/us/app/id6787193472)**：透過 App 開啟社群，拿掉 Reels、Shorts、「為你推薦」和「探索」。支援平台：Instagram、YouTube、Snapchat、TikTok、Facebook、LinkedIn、X、Threads、Reddit。價格：要使用完整功能需訂閱（月繳、6 個月或年繳）。保留私訊：是（訊息、個人檔案和搜尋都保留）。美國 App Store 評分數：7。其他：家長控制，最多 5 個小孩。
- **[Yava](https://apps.apple.com/us/app/id6800918860)**：封鎖 Reels、Shorts、Facebook 的 Reels 和 Watch、「探索」頁面以及自動播放，同時還能傳訊息給朋友（說明中沒有寫封鎖的方式）。支援平台：Instagram、YouTube、Facebook 等。價格：功能需要訂閱。保留私訊：是。美國 App Store 評分數：8。
- **[Close](https://apps.apple.com/kr/app/id6817441004)**（韓國）：沒有 Reels 和「探索」分頁的 Instagram；私訊、限時動態和有限的朋友動態都保留，還能用「螢幕使用時間」鎖住真正的 Instagram App。支援平台：Instagram。價格：所有功能免費；可自由贊助。保留私訊：是。App Store 評分數：美國 App Store 未上架；韓國 3 則。

<a id="safari-extensions"></a>
## Safari 延伸功能
用 Safari 瀏覽時，隱藏 instagram.com / youtube.com 上的動態。官方 App 不受影響。

- **[SocialFocus](https://apps.apple.com/us/app/id1661093205)**：隱藏網站上你選的部分，例如動態、Reels、Shorts 和留言的 Safari 延伸功能。支援平台：Safari 中的 YouTube、Facebook、X、Instagram、Reddit、LinkedIn 和 Gmail 網站。價格：付費 App（美國 $4.99）；可選 PRO 訂閱。保留私訊：未列出。美國 App Store 評分數：326。其他：設定可匯入／匯出。
- **[ScrollGuard](https://apps.apple.com/us/app/id6754183872)**：在社群網站上隱藏動態、Reels、限時動態和「探索」的 Safari 延伸功能。支援平台：Safari 中的社群網站。價格：免費，另有 Premium 功能。保留私訊：是，依其官網（scrollguard.app，2026-10-17 確認）。美國 App Store 評分數：117。其他：需要 iOS 18。
- **[Slowth](https://apps.apple.com/us/app/id6764140763)**：隱藏 Shorts、Reels 和 X 的「探索」的 Safari 延伸功能；在 YouTube 和 Instagram App 裡，能透過螢幕錄影偵測 Shorts 或 Reels 並封鎖 App。支援平台：Safari 中的 YouTube、Instagram、Facebook、X、TikTok 網站。價格：免費下載。保留私訊：未列出。美國 App Store 評分數：3。其他：限制會鎖定 24 小時。
- **[Nope](https://apps.apple.com/us/app/id6768192042)**：適用 instagram.com 和 youtube.com 的 Safari 網頁延伸功能。支援平台：Instagram、YouTube。價格：完全免費，沒有訂閱和 App 內購買。保留私訊：是。美國 App Store 評分數：2。其他：有 Chrome 擴充功能。
- **[#blockit](https://apps.apple.com/us/app/id1492879257)**：從熱門網站拿掉 Shorts、Reels 和無限滑動的動態，也能依網址封鎖整個網站的 Safari 延伸功能。支援平台：Safari 中的熱門網站。價格：免費下載，可免費試用 7 天。保留私訊：是（「leaves everything else」）。美國 App Store 評分數：168。其他：從 2020 年持續維護，不需帳號。
- **[No Reel For Instagram](https://apps.apple.com/us/app/id6752605548)**：適用 instagram.com 的 Safari 延伸功能，隱藏 Reels 導覽、搜尋和「探索」裡的 Reels、限時動態、「為你推薦」分頁和推薦帳號。支援平台：Instagram。價格：$3.39。保留私訊：是。美國 App Store 評分數：0。其他：iPhone、iPad 和 Mac。
- **[No Shorts: Blocker for YouTube](https://apps.apple.com/us/app/id6502996298)**：隱藏 youtube.com 上 Shorts 動態、預覽和推薦的 Safari 延伸功能。支援平台：YouTube。價格：一次買斷 $2.99。保留私訊：不適用。美國 App Store 評分數：15。
- **[ShortformBlock](https://apps.apple.com/us/app/id6761337873)**：免費的 Safari 延伸功能，隱藏動態、搜尋結果和導覽列中的 YouTube Shorts。支援平台：YouTube。價格：免費。保留私訊：不適用。美國 App Store 評分數：13。
- **[Still](https://apps.apple.com/us/app/id6784061138)**：拿掉 YouTube Shorts 以及 Instagram 和 Facebook 的 Reels，並封鎖 TikTok 網站的 Safari 延伸功能；可選擇免費登入，讓設定和 Chrome、Firefox 擴充功能同步。支援平台：YouTube、Instagram、Facebook、TikTok 網站。價格：免費；封鎖不需帳號也不用購買。保留私訊：是（訊息保留）。美國 App Store 評分數：0。其他：iPhone、iPad 和 Mac。
- **[tubetidy](https://apps.apple.com/us/app/id6780741579)**：隱藏所有地方的 YouTube Shorts、首頁推薦、相關影片、留言等，並提供關鍵字和頻道過濾的 Safari 延伸功能。支援平台：YouTube。價格：一次買斷 $2.99（日本 ¥500）。保留私訊：不適用。美國 App Store 評分數：0。其他：iPhone、iPad 和 Mac。

<a id="whole-app-blockers"></a>
## 整個 App 一起封鎖的 App（私訊也會被擋）
適合想完全停用某個 App 的人；這些 App 沒辦法只拿掉 Reels 而保留訊息。
- **[Opal](https://apps.apple.com/us/app/id1497465230)**：用「螢幕使用時間」依排程封鎖你選的 App。
- **[one sec](https://apps.apple.com/us/app/id1532875441)**：開啟 App 前先插入一段深呼吸的暫停。
- **[ScreenZen](https://apps.apple.com/us/app/id1541027222)**：開啟 App 前要先等一下；靠使用者贊助營運。
- **[No Scroll](https://apps.apple.com/us/app/id6474079216)**：開啟 App 前先選使用時間，時間到了 App 會鎖住 5 分鐘。
- **[DMOnly](https://apps.apple.com/us/app/id6773196876)**：把你選的社群 App 一直鎖著，每次只能開 15 分鐘。
- **[Curfew](https://apps.apple.com/us/app/id6755434607)**：用「螢幕使用時間」依排程鎖住你選的 App（例如 Instagram 或 YouTube）；解鎖時要等 5 分鐘。一組排程免費；Pro 為一次買斷。
- **[숏패스 (ShortPass)](https://apps.apple.com/kr/app/id6803353215)**（韓國）：在讀書時間或超過每日上限後鎖住你選的 App，並有考試倒數（D-day）；鎖定功能在 Pro 裡（不會自動續訂的通行券）。

<a id="how-to-choose"></a>
## 怎麼選
- **Instagram 只用來私訊和群組聊天？** 找有「只用私訊」／Messages Only 模式的 App（UNDOOMED、LoomWeb、Konvo、minulo、Reelmute、Stillfeed）。
- **也需要 TikTok 或 Snapchat？** 先看支援平台，不是每個 App 都支援。
- **總是習慣性點開官方 App？** 選能用「螢幕使用時間」鎖住官方 App 的（SocialLite、minulo、noShorts、snowscroll、Reelmute、Konvo）。
- **想全部免費？** Nope、ShortformBlock 和 Still 是免費的 Safari 延伸功能；noShorts、Dome、Noreel 和 Close 表示自己是免費的；App 內瀏覽器類型中，minulo、Stillfeed、Reelmute 和 Awhile 的基本隱藏功能免費。各自哪些部分免費：[iPhone 上免費封鎖 IG Reels 和 YouTube Shorts 的 App（2026）](https://minulo.app/zh-Hant/free-reels-blocker.html)。

更多細節：[比較表](https://minulo.app/zh-Hant/alternatives.html) · [能把 iPhone 上 Instagram App 裡的 Reels 拿掉嗎？](https://minulo.app/zh-Hant/remove-reels-from-instagram-app.html)

和特定 App 比較：[ScreenZen 的替代 App](https://minulo.app/zh-Hant/screenzen-alternatives.html) · [one sec 的替代 App](https://minulo.app/zh-Hant/one-sec-alternatives.html) · [Opal 的替代 App](https://minulo.app/zh-Hant/opal-alternatives.html)


<a id="guides"></a>
## 教學
一步步的教學文章（由 minulo 的開發者撰寫；每篇都先介紹內建做法）。dev.to、Hashnode 和 Substack 上的文章是英文。
- [Instagram Screen Time limit not working on iPhone? The 5 settings behind it](https://dev.to/ayumu_kitabayashi_8e0de96/instagram-screen-time-limit-not-working-on-iphone-the-5-settings-behind-it-2026-1bf7)
- [How to turn off YouTube Shorts on iPhone in 2026 (and why no app can fully remove them)](https://minulo.hashnode.dev/how-to-turn-off-youtube-shorts-on-iphone-in-2026-and-why-no-app-can-fully-remove-them)
- [Keep Instagram DMs, lose Reels: 5 ways to do it on iPhone (2026, compared)](https://dev.to/ayumu_kitabayashi_8e0de96/keep-instagram-dms-lose-reels-5-ways-to-do-it-on-iphone-2026-compared-17dh)
- [5 timing bugs I hit building timed blocks with Screen Time's DeviceActivity (iOS)](https://dev.to/ayumu_kitabayashi_8e0de96/5-timing-bugs-i-hit-building-timed-blocks-with-screen-times-deviceactivity-ios-5dnc)（給開發者）
- [Using TikTok just for messages on iPhone: 5 options and their catches](https://minulo.substack.com/p/using-tiktok-just-for-messages-on)
- [When people reach for Reels: what an app's first month of usage data shows (and what it can't)](https://minulo.substack.com/p/when-people-reach-for-reels-what)
- [Three ways to build a Reels blocker on iOS: content blocker, Safari extension, or WKWebView](https://minulo.hashnode.dev/three-ways-to-build-a-reels-blocker-on-ios-content-blocker-safari-extension-or-wkwebview)（給開發者）
- [What's actually free when you block Reels and Shorts on iPhone (2026)](https://minulo.substack.com/p/whats-actually-free-when-you-block)
- [晚上停不下來滑手機？iPhone 睡前不再狂滑的設定（2026）](https://minulo.app/zh-Hant/stop-doomscrolling-at-night.html)
- [minulo 安全嗎？它看得到什麼、看不到什麼，以及它的限制（2026）](https://minulo.app/zh-Hant/is-minulo-safe.html)（並排比較 minulo、SocialLite 和 UNDOOMED 的隱私權標籤）
- [iPhone 上怎麼封鎖 Instagram：App、Safari，以及中間的做法（2026）](https://minulo.app/zh-Hant/block-instagram-on-iphone.html)
- [iPhone 上怎麼封鎖 TikTok：App、網站，以及中間的做法（2026）](https://minulo.app/zh-Hant/block-tiktok-on-iphone.html)
- [怎麼隱藏 Instagram 的「探索」](https://minulo.app/zh-Hant/hide-instagram-explore.html)和[只看追蹤對象的貼文](https://minulo.app/zh-Hant/instagram-following-feed-only.html)
- [iPhone 上怎麼關掉 Snapchat 的 Spotlight（2026）](https://minulo.app/zh-Hant/turn-off-snapchat-spotlight.html)
- [不用 Brick 硬體的 iPhone 替代方案（2026）](https://minulo.app/zh-Hant/brick-alternative-iphone.html)
- [Why you can't set a time limit on just Instagram Reels on iPhone (and what Screen Time's API can do)](https://dev.to/ayumu_kitabayashi_8e0de96/why-you-cant-set-a-time-limit-on-just-instagram-reels-on-iphone-and-what-screen-times-api-can-522)
- [How I ship an iPhone app and its website in 13 languages as a solo developer](https://dev.to/ayumu_kitabayashi_8e0de96/how-i-ship-an-iphone-app-and-its-website-in-13-languages-as-a-solo-developer-10gk)（給開發者）


### 一個問題一頁（2026 年 10 月）
minulo.app 上的短篇頁面，每頁回答一個問題，並以該平台的官方說明頁面為出處。
- [關掉 Instagram 和 Facebook 的影片自動播放](https://minulo.app/zh-Hant/instagram-autoplay-off.html)
- [按了「沒興趣」Reels 還是一直出現？原因在這裡](https://minulo.app/zh-Hant/not-interested-reels-still-showing.html)
- [可以拿掉 Instagram 的 Reels 分頁嗎？（2026）](https://minulo.app/zh-Hant/instagram-reels-tab-remove.html)
- [iPad 版 Instagram 的 Reels：哪些可以關掉](https://minulo.app/zh-Hant/instagram-reels-ipad.html)
- [Instagram 可以只看摯友的貼文嗎？](https://minulo.app/zh-Hant/instagram-close-friends-feed.html)
- [隱藏 Instagram 按讚數有用嗎？](https://minulo.app/zh-Hant/hide-instagram-likes-counts.html)
- [在 iPad 和 Mac 上使用沒有 Shorts 的 YouTube](https://minulo.app/zh-Hant/youtube-shorts-ipad-mac.html)
- [躺在床上停不下 YouTube Shorts 的對策（iPhone）](https://minulo.app/zh-Hant/stop-youtube-shorts-at-night.html)
- [關閉 YouTube 觀看記錄後，首頁會怎樣](https://minulo.app/zh-Hant/youtube-history-off-home-feed.html)
- [怎麼重設 YouTube 的推薦（iPhone）](https://minulo.app/zh-Hant/youtube-reset-recommendations.html)
- [YouTube 只看訂閱頻道的方法（iPhone）](https://minulo.app/zh-Hant/youtube-subscriptions-only.html)
- [YouTube 只收訂閱頻道的通知](https://minulo.app/zh-Hant/youtube-notifications-subscriptions-only.html)
- [怎麼拿掉 YouTube 網站首頁的 Shorts 區塊](https://minulo.app/zh-Hant/youtube-shorts-remove-from-home-web.html)
- [青少年、兒童和成人帳號的 YouTube Shorts 限制](https://minulo.app/zh-Hant/youtube-kids-vs-shorts.html)
- [TikTok 限制模式能做到和做不到的事](https://minulo.app/zh-Hant/tiktok-restricted-mode.html)
- [Snapchat 只用聊天和限時動態的方法](https://minulo.app/zh-Hant/snapchat-stories-only.html)
- [Snapchat Spotlight 可以設定時間限制嗎？](https://minulo.app/zh-Hant/snapchat-spotlight-time-limit.html)
- [Facebook 的 Reels 可以關掉嗎？（iPhone）](https://minulo.app/zh-Hant/facebook-reels-off.html)
- [iPhone 上可以關掉 LinkedIn 的影片動態嗎？](https://minulo.app/zh-Hant/linkedin-video-feed-off.html)
- [WhatsApp 怎麼隱藏動態（iPhone）](https://minulo.app/zh-Hant/whatsapp-status-updates-hide.html)
- [iPhone「停用時間」擋不住 Instagram？解決方法](https://minulo.app/zh-Hant/downtime-not-working-instagram.html)
- [iPhone 的「忽略限制」：怎麼讓它消失](https://minulo.app/zh-Hant/app-limit-ignore-button.html)
- [忘記「螢幕使用時間」密碼？Apple 的官方步驟](https://minulo.app/zh-Hant/screen-time-passcode-forgot.html)
- [iPhone「螢幕使用時間」每週報告怎麼看](https://minulo.app/zh-Hant/screen-time-weekly-report.html)
- [只允許訊息的 iPhone 專注模式：Instagram 私訊會怎樣](https://minulo.app/zh-Hant/focus-mode-messages-only.html)
- [iPhone 開灰階就能少滑手機嗎？](https://minulo.app/zh-Hant/grayscale-to-stop-scrolling.html)

<a id="guides-other-languages"></a>
## 其他語言的教學
由 minulo 的開發者撰寫；每篇都先介紹內建做法。

**日本語**
- [インスタの DM は残してリールだけ消す：iPhone でできる5つの方法を比べた（2026）](https://zenn.dev/minulo/articles/a66d0db9b53459)
- [YouTube のショートだけ止めて、ふつうの動画は見たい：iPhone でできる方法を全部並べた（2026）](https://zenn.dev/minulo/articles/f9990e19d36744)
- [スクリーンタイムでインスタを制限したのに開けてしまう5つの原因（iOS 26／27）](https://minulo.hatenablog.com/entry/2026/10/21/123232)
- [テスト2週間前から、インスタのリールだけを断つ（クラスの連絡は残す）](https://note.com/minulo/n/n9204c425bb03)
- [iOS で「リールだけ消す」はなぜ難しいか：3つの作り方を比べる](https://zenn.dev/minulo/articles/61f2fade3b78c5)
- [WKWebView の SNS からリールだけ消す ― CSS が黙って効かなくなるのを数えて気づく話](https://zenn.dev/minulo/articles/cb2aee59efbf0a)
- [Screen Time API（DeviceActivity）で決めた時刻に外れるブロックを作ったら時刻で5回つまずいた話](https://qiita.com/feedminus47/items/7f206f820b4163b6356c)
- [リールを見てしまうのは夜20時から深夜1時：利用データから分かった一番危ない時間と対策](https://note.com/minulo/n/nd473fdf6bd09)
- [インスタの「DMだけ使いたい」をかなえる方法を全部並べて比べた（2026年10月）](https://minulo.hatenablog.com/entry/2026/10/22/114919)
- [日本語で先に書くと「1 days」が出る：1人で13言語に対応したアプリの穴と検査](https://qiita.com/feedminus47/items/b50d7ef8b71366c93dec)

**한국어**
- [인스타 DM은 남기고 릴스만 없애는 법: 아이폰에서 쓸 수 있는 5가지 방법 비교 (2026)](https://velog.io/@barcaak1011/인스타-DM은-남기고-릴스만-없애는-법-아이폰에서-쓸-수-있는-5가지-방법-비교-2026)
- [공부할 때 유튜브 강의는 보고 쇼츠만 끄는 법 (아이폰, 2026)](https://velog.io/@barcaak1011/공부할-때-유튜브-강의는-보고-쇼츠만-끄는-법-아이폰-2026)
- [iOS에서 '릴스만' 숨기는 앱을 만들 때 고를 수 있는 3가지 방법](https://velog.io/@barcaak1011/iOS에서-릴스만-숨기는-앱을-만들-때-고를-수-있는-3가지-방법-콘텐츠-차단기Safari-확장WKWebView) (개발자용)
- [틱톡을 DM(메시지)용으로만 쓰는 법 (아이폰, 2026)](https://velog.io/@barcaak1011/틱톡을-DM메시지용으로만-쓰는-법-아이폰-2026)

**Tiếng Việt**
- [Mở app của mình từ màn hình chặn Screen Time trên iOS: ShieldAction không mở được URL, nên đi qua thông báo](https://viblo.asia/p/mo-app-cua-minh-tu-man-hinh-chan-screen-time-tren-ios-shieldaction-khong-mo-duoc-url-nen-di-qua-thong-bao-ZjJYWRrpVOE) (cho lập trình viên)
- [Ba cách làm app chặn Reels trên iOS: content blocker, tiện ích Safari hay WKWebView](https://viblo.asia/p/ba-cach-lam-app-chan-reels-tren-ios-content-blocker-tien-ich-safari-hay-wkwebview-kNLr3ezoVgA) (cho lập trình viên)

**Français / Español / Português / Deutsch**
- [Garder Instagram pour les messages, sans les Reels : les options sur iPhone (2026)](https://medium.com/@feedminus47/garder-instagram-pour-les-messages-sans-les-reels-les-options-sur-iphone-2026-e93d51214f90)
- [Instagram solo para mensajes en el iPhone: el grupo de la clase sin los Reels (2026)](https://medium.com/@feedminus47/instagram-solo-para-mensajes-en-el-iphone-el-grupo-de-la-clase-sin-los-reels-2026-27b47d3ea5e2)
- [Como estudar sem cair nos Reels e Shorts, sem sair do grupo da turma (iPhone, 2026)](https://medium.com/@feedminus47/como-estudar-sem-cair-nos-reels-e-shorts-sem-sair-do-grupo-da-turma-iphone-2026-926073dca5a8)
- [Esconder os Reels no iPhone com Expo: três caminhos (content blocker, extensão do Safari ou WebView)](https://dev.to/ayumu_kitabayashi_8e0de96/esconder-os-reels-no-iphone-com-expo-tres-caminhos-content-blocker-extensao-do-safari-ou-h07) (para devs)
- [Lo que la API de Tiempo en pantalla de iOS puede y no puede hacer, y las tres formas que quedan para esconder los Reels](https://dev.to/ayumu_kitabayashi_8e0de96/lo-que-la-api-de-tiempo-en-pantalla-de-ios-puede-y-no-puede-hacer-y-las-tres-formas-que-quedan-33h2) (para devs)
- [Instagram nur für Nachrichten: Bevor du die App löschst, probier das (iPhone, 2026)](https://medium.com/@feedminus47/instagram-nur-f%C3%BCr-nachrichten-bevor-du-die-app-l%C3%B6schst-probier-das-iphone-2026-322f89d370d5)
- [Aus dem Screen-Time-Sperrbildschirm die eigene App öffnen: ShieldAction kann es nicht, eine Mitteilung schon](https://dev.to/ayumu_kitabayashi_8e0de96/aus-dem-screen-time-sperrbildschirm-die-eigene-app-offnen-shieldaction-kann-es-nicht-eine-3o82) (für Entwickler)
- [DeviceActivity sur iOS : un blocage qui se lève à l'heure prévue, et les cinq pièges d'horaire que j'ai rencontrés](https://dev.to/ayumu_kitabayashi_8e0de96/deviceactivity-sur-ios-un-blocage-qui-se-leve-a-lheure-prevue-et-les-cinq-pieges-dhoraire-que-5hb9) (pour les devs)


<a id="data"></a>
## 資料
上面的比較整理成 CSV（每個 App 一列：做法、支援平台、價格、私訊是否照常可用、美國評分數和確認日期）：[data/ios-reels-shorts-blockers.csv](data/ios-reels-shorts-blockers.csv)。評分數是當下的快照，每天都會變動；歡迎指正。


## 授權
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)：可自由使用。
