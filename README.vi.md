# Ứng dụng chặn Reels Instagram và Shorts YouTube trên iPhone (vẫn giữ tin nhắn)
[English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt-BR.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Bahasa Indonesia](README.id.md) | [ไทย](README.th.md) | **Tiếng Việt** | [Русский](README.ru.md) | [繁體中文](README.zh-Hant.md)

Danh sách ứng dụng và cài đặt trên iPhone giúp ẩn **Reels Instagram, Shorts YouTube và bảng tin Dành cho bạn của TikTok**, trong khi phần còn lại của mỗi ứng dụng vẫn dùng được: tin nhắn (DM), nhóm chat, tìm kiếm và các tài khoản bạn theo dõi.

> **Công khai:** danh sách này do nhà phát triển [minulo](https://minulo.app/vi/), một trong các ứng dụng bên dưới, duy trì. Thông tin chỉ lấy từ trang App Store Mỹ hoặc trang web chính thức của từng ứng dụng (kiểm tra vào tháng 10/2026; số lượt đánh giá cập nhật lần cuối ngày 2026-10-24). Số lượt đánh giá thay đổi hằng ngày. Mọi chỉnh sửa và bổ sung đều được hoan nghênh qua issue hoặc pull request.


<a id="quick-answers"></a>
## Trả lời nhanh
- **Ứng dụng iPhone miễn phí nào ẩn được Reels Instagram và Shorts YouTube mà vẫn giữ tin nhắn?** Ngay trong ứng dụng của mình, minulo (10 mạng xã hội), Reelmute (6), Stillfeed (Instagram và YouTube) và Awhile (chỉ Instagram) cho ẩn cơ bản miễn phí. Nope và ScrollGuard làm việc này miễn phí dưới dạng tiện ích Safari, nên chỉ dùng được trong Safari. noShorts miễn phí và không có mua hàng trong ứng dụng. Mỗi ứng dụng miễn phí những gì: [Ứng dụng miễn phí chặn Reels và Shorts](https://minulo.app/vi/free-reels-blocker.html).
- **Làm sao bỏ Shorts YouTube mà vẫn xem video thường?** Giới hạn bảng tin Shorts của YouTube có thể đặt về 0, nhưng với tài khoản người lớn, lời nhắc có thể tắt đi. minulo, Stillfeed, Reelmute và noShorts mở YouTube không có Shorts ngay trong ứng dụng của mình; Nope làm việc này trong Safari. Trong minulo, video thường, tìm kiếm và kênh đăng ký vẫn dùng được. ([cách làm](https://minulo.app/vi/block-youtube-shorts.html))
- **Có thể dùng Instagram chỉ để nhắn tin không?** Bản thân Instagram không có chế độ chỉ tin nhắn. Trong minulo, cài đặt Mọi tab trừ tin nhắn là miễn phí; còn trong UNDOOMED, Stillfeed, Reelmute và Konvo, chế độ xem chỉ tin nhắn phải trả phí. ([cách làm](https://minulo.app/vi/instagram-dms-only.html), [ứng dụng miễn phí để chỉ nhắn tin](https://minulo.app/vi/free-instagram-dms-only-app.html))
- **Ứng dụng nào dùng giống SocialLite?** Các ứng dụng cũng khóa ứng dụng chính thức bằng Thời gian sử dụng và đưa bạn sang giao diện riêng của chúng: minulo, noShorts, snowscroll, Reelmute và Konvo. ([so sánh](https://minulo.app/vi/sociallite-alternatives.html))
- **SocialLite có miễn phí không?** Tải về miễn phí và có mua trong ứng dụng; Pro giá từ $6.99 đến $17.99 mỗi tháng hoặc từ $19.99 đến $47.90 mỗi năm tùy ưu đãi, còn gói Family giá $12.99 mỗi tháng (App Store Mỹ, kiểm tra ngày 2026-10-26). minulo, Stillfeed và Reelmute ẩn Reels và Shorts miễn phí; Nope hoàn toàn miễn phí trên Safari. ([giá và lựa chọn miễn phí](https://minulo.app/vi/is-sociallite-free.html))
- **Làm sao ngừng lướt Reels và Shorts vào ban đêm?** Giờ nghỉ trong Thời gian sử dụng của iPhone chặn cả ứng dụng, kể cả tin nhắn. Trong minulo, ẩn Reels và Shorts là miễn phí và giao diện riêng của minulo vẫn giữ tin nhắn; khóa ứng dụng chính thức miễn phí tối đa 2 giờ mỗi lần, còn lịch tự động mỗi đêm thuộc Pro. Các ứng dụng khác bên dưới cũng có lịch hẹn giờ; xem từng mục. ([cách làm](https://minulo.app/vi/stop-doomscrolling-at-night.html), [TikTok ban đêm](https://minulo.app/vi/stop-scrolling-tiktok-at-night.html))


## Mục lục
- [Trả lời nhanh](#quick-answers)
- [Cài đặt có sẵn (không cần ứng dụng)](#built-in-settings)
- [Ứng dụng mở mạng xã hội mà không có bảng tin](#in-app-browsers)
- [Tiện ích mở rộng Safari](#safari-extensions)
- [Ứng dụng chặn cả ứng dụng (chặn luôn tin nhắn)](#whole-app-blockers)
- [Nên chọn thế nào](#how-to-choose)
- [Hướng dẫn](#guides)
- [Hướng dẫn bằng ngôn ngữ khác](#guides-other-languages)
- [Dữ liệu (CSV)](#data)


<a id="built-in-settings"></a>
## Cài đặt có sẵn (không cần ứng dụng)
- **Giới hạn bảng tin Shorts của YouTube**: YouTube cho phép đặt giới hạn mỗi ngày cho bảng tin Shorts (kể cả 0). Với tài khoản người lớn, lời nhắc có thể tắt đi, và giới hạn chỉ áp dụng trong ứng dụng YouTube. ([cách làm](https://minulo.app/vi/youtube-shorts-feed-limit.html))
- **Bảng tin "Đang theo dõi" của Instagram (Following)**: chuyển bảng tin trang chủ sang chỉ các tài khoản bạn theo dõi. Tab Reels và Khám phá vẫn còn.
- **"Tạm ẩn bài viết gợi ý" của Instagram (Snooze suggested posts)**: ở một bài viết gợi ý, chạm ⋯ → Không quan tâm → tạm ẩn mọi bài viết gợi ý trong bảng tin trong 30 ngày. Hết 30 ngày là thôi, và không ảnh hưởng đến tab Reels. ([cách làm](https://minulo.app/vi/hide-suggested-posts-instagram.html))
- **"Đặt lại nội dung gợi ý" của Instagram (Reset suggested content)**: vào Cài đặt → Tùy chọn nội dung → Đặt lại nội dung gợi ý để xóa những gì Instagram đề xuất ở Khám phá, Reels và Bảng tin. Không thể hoàn tác, và đề xuất sẽ học lại từ đầu khi bạn xem tiếp. ([cách làm](https://minulo.app/vi/reset-instagram-reels-recommendations.html))
- **Tắt tự động phát trên YouTube**: video tiếp theo không còn tự chạy. Đề xuất vẫn còn, trừ khi nhật ký xem đã tắt và trống. ([cách làm](https://minulo.app/vi/turn-off-youtube-autoplay-recommendations.html))
- **Thời gian sử dụng trên iPhone**: giới hạn hoặc chặn cả một ứng dụng. Tin nhắn và nhóm chat của bạn cũng bị chặn cùng với bảng tin.


<a id="in-app-browsers"></a>
## Ứng dụng mở mạng xã hội mà không có bảng tin
Các ứng dụng này mở trang web của từng mạng xã hội ngay trong ứng dụng của mình và ẩn Reels, Shorts hoặc Dành cho bạn. Một số còn khóa được ứng dụng chính thức bằng Thời gian sử dụng, để bạn không quay lại đó theo thói quen.

- **[SocialLite](https://apps.apple.com/us/app/id6757661674)**: giao diện mạng xã hội gọn gàng, tập trung ngay trong ứng dụng; theo ghi chú phát hành, có thể chặn ứng dụng chính thức bằng Thời gian sử dụng và chuyển sang SocialLite. Mạng xã hội: Instagram, YouTube, Snapchat, X, Reddit và các mạng khác (không nhắc đến TikTok). Giá: tải miễn phí; Pro $6.99 hoặc $9.99 mỗi tháng, hoặc từ $19.99 đến $47.90 mỗi năm tùy ưu đãi (Mỹ). Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: khoảng 15,000 (★4.7).
- **[UNDOOMED](https://apps.apple.com/us/app/id6751837079)**: mở trang web di động của từng mạng xã hội trong trình duyệt riêng tư của ứng dụng và lọc trang. Mạng xã hội: Instagram, Threads, Reddit, Facebook, X, YouTube, LinkedIn (không có TikTok và Snapchat). Giá: nhiều tính năng miễn phí; Plus $1.99/tháng hoặc $11.99/năm, Pro $2.99/tháng, $17.99/năm hoặc $29.99 trọn đời (Mỹ). Giữ tin nhắn: Có (chế độ Messages Only). Số lượt đánh giá trên App Store Mỹ: 108.
- **[Dull](https://apps.apple.com/us/app/id6759723829)**: mở từng nền tảng trong trình duyệt riêng, đã bỏ Reels, Shorts, Dành cho bạn và Khám phá. Mạng xã hội: Instagram, YouTube, Facebook, X, Reddit. Giá: tải miễn phí. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 55. Khác: giới hạn hằng ngày, giờ yên tĩnh, phải chờ 24 giờ mới nới bộ lọc được.
- **[WallHabit](https://apps.apple.com/us/app/id6751423279)**: chặn Reels và Shorts hoặc cả ứng dụng, và bắt bạn giữ một nút trước khi mở khóa (phần mô tả không nói rõ cách chặn Reels). Mạng xã hội: không ghi. Giá: miễn phí, có mua trong ứng dụng. Giữ tin nhắn: không nêu. Số lượt đánh giá trên App Store Mỹ: 35. Khác: cần iOS 18.
- **[LoomWeb](https://apps.apple.com/us/app/id6754727620)**: trình duyệt cho mạng xã hội, cài đặt riêng cho từng trang. Mạng xã hội: Instagram, YouTube, X, Facebook. Giá: miễn phí, có gói Pro. Giữ tin nhắn: Có (tùy chọn chỉ tin nhắn). Số lượt đánh giá trên App Store Mỹ: 34. Khác: cần iOS 18.
- **[Scroll Less](https://apps.apple.com/us/app/id6741134096)**: mở YouTube, Instagram và các nền tảng khác trong trình duyệt tối giản của ứng dụng (WebView) và bỏ các bảng tin đề xuất theo thuật toán. Mạng xã hội: YouTube, Instagram và các mạng khác (không có danh sách đầy đủ). Giá: tải miễn phí. Giữ tin nhắn: không nêu. Số lượt đánh giá trên App Store Mỹ: 23.
- **[Sociano](https://apps.apple.com/us/app/id6760568406)**: mở các mạng xã hội được hỗ trợ trong trình duyệt có kiểm soát của ứng dụng và chặn Reels, Shorts và bảng tin; còn chặn được các ứng dụng iPhone bạn chọn bằng Thời gian sử dụng. Mạng xã hội: Instagram, YouTube, X, Facebook, LinkedIn và các mạng khác. Giá: tải miễn phí. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 10. Khác: chặn ứng dụng, lịch và giới hạn hằng ngày.
- **[snowscroll](https://apps.apple.com/us/app/id6778488660)**: mở trang web di động của từng mạng xã hội trong trình duyệt tập trung ngay trong ứng dụng và ẩn bảng tin; khi dùng cùng Thời gian sử dụng, mở ứng dụng Instagram thật sẽ ra snowscroll. Mạng xã hội: Instagram, YouTube, Facebook, X, TikTok, LinkedIn. Giá: tải miễn phí. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 10. Khác: màn hình chặn cho ứng dụng chính thức.
- **[Awhile](https://apps.apple.com/us/app/id6763551826)**: tải instagram.com trong trình duyệt riêng của ứng dụng và ẩn những phần bạn chọn. Mạng xã hội: chỉ Instagram. Giá: lọc miễn phí; Premium €2.99/tháng hoặc €9.99 trả một lần. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 4.
- **[Fluid Friction](https://apps.apple.com/us/app/id6782510849)**: mở mạng xã hội trong ứng dụng và khiến việc lướt bảng tin nặng nề hơn; cũng ẩn được Reels, Shorts, Tin và Khám phá. Mạng xã hội: Instagram, TikTok, YouTube, Reddit, X, Snapchat, Facebook, LinkedIn. Giá: tải miễn phí. Giữ tin nhắn: Có (tin nhắn vẫn hoạt động). Số lượt đánh giá trên App Store Mỹ: 6. Khác: màn hình chặn Thời gian sử dụng cho các ứng dụng khác.
- **[minulo](https://apps.apple.com/us/app/id6809352229)**: mở trang web chính thức của từng mạng xã hội trong ứng dụng và ẩn những phần bạn chọn. Cũng khóa được ứng dụng chính thức bằng Thời gian sử dụng và chuyển bạn sang minulo. Mạng xã hội: Instagram, YouTube, TikTok, X, Threads, Facebook, Pinterest, Reddit, LinkedIn, Snapchat (10). Giá: ẩn miễn phí, và khóa ứng dụng chính thức miễn phí tối đa 2 giờ mỗi lần; Pro ($9.99/tháng hoặc $39.99/năm ở Mỹ) thêm lịch, Hard Mode, khóa lâu hơn và nhiều danh sách chặn. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0. Khác: iPhone và Mac; không có bản Android. Do tác giả danh sách này duy trì.
- **[Stillfeed](https://apps.apple.com/us/app/id6792934511)**: mở Instagram và YouTube trong trình duyệt tích hợp, đã bỏ Reels, Khám phá và Shorts. Mạng xã hội: Instagram, YouTube. Giá: chặn Reels và Shorts miễn phí; Pro thêm bảng tin chỉ người đang theo dõi, chặn Tin và bảng tin, và chế độ chỉ tin nhắn. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0. Khác: thống kê lượt chặn hằng tuần.
- **[Unfeed](https://apps.apple.com/us/app/id6814847686)**: mở mạng xã hội trong ứng dụng của mình với bộ lọc ngăn bảng tin tải lên. Mạng xã hội: Instagram, TikTok, YouTube, X. Giá: tải miễn phí; Pro thêm ẩn quảng cáo, bài viết gợi ý và tin, cùng nhiều tài khoản. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0. Khác: hẹn giờ phiên, hạn mức hằng ngày, chế độ ngủ.
- **[Konvo](https://apps.apple.com/us/app/id6794756261)**: mở Instagram thẳng vào hộp thư; bảng tin, Reels và Khám phá không bao giờ được tải. Mạng xã hội: Instagram (chỉ tin nhắn). Giá: cần gói trả phí để dùng tin nhắn Instagram trong ứng dụng. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 1. Khác: khóa được ứng dụng Instagram; hai lượt mở ngắn mỗi ngày.
- **[Scrollout](https://apps.apple.com/us/app/id6802054477)**: ẩn Reels, Shorts, nội dung gợi ý và quảng cáo trên các nền tảng được hỗ trợ. Mạng xã hội: YouTube và các mạng khác (không có danh sách đầy đủ). Giá: tải miễn phí. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0.
- **[Reelmute](https://apps.apple.com/us/app/id6808963180)** (ở Nhật có tên 「リールとショートを非表示」): mở mạng xã hội trong ứng dụng và ẩn Reels, Shorts và Dành cho bạn trước khi trang hiện ra; bản Premium khóa được ứng dụng gốc. Mạng xã hội: Instagram, YouTube, TikTok, Facebook, Reddit, X. Giá: ẩn miễn phí; Premium thêm chế độ chỉ tin nhắn, ẩn bài viết gợi ý và khóa ứng dụng (dùng thử 3 ngày hoặc trọn đời). Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0. Khác: widget, chế độ ngủ, thang độ xám.
- **[Noreel](https://apps.apple.com/us/app/id6760568462)**: bỏ Reels trong lúc bạn xem bảng tin, xem Tin, gửi tin nhắn và tìm kiếm. Mạng xã hội: không ghi ("social media"). Giá: miễn phí, không có gói đăng ký. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 8.
- **[LockedIn](https://apps.apple.com/us/app/id6767055765)**: chặn vĩnh viễn Reels Instagram và Shorts YouTube, kèm các công tắc tùy chọn cho bảng tin trang chủ Instagram, Tin, Tìm kiếm và Khám phá, phát video trong tin nhắn, cùng đề xuất và kênh đăng ký ở trang chủ YouTube (phần mô tả không nói cách hoạt động). Mạng xã hội: Instagram, YouTube. Giá: tải miễn phí. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 1. Khác: không tài khoản, không phân tích hay theo dõi.
- **[Dome](https://apps.apple.com/us/app/id6756055866)**: bỏ Reels, Shorts và trang Khám phá, phần còn lại giữ nguyên. Mạng xã hội: không ghi. Giá: miễn phí, không paywall, không quảng cáo. Giữ tin nhắn: không nêu. Số lượt đánh giá trên App Store Mỹ: 1.
- **[SocialRouter](https://apps.apple.com/us/app/id6758858307)**: không gian trình duyệt riêng cho nhiều tài khoản mạng xã hội; ẩn được Reels, bảng tin và Khám phá trên Instagram, và Shorts trên YouTube. Mạng xã hội: Instagram, YouTube và các mạng khác. Giá: tải miễn phí. Giữ tin nhắn: không nêu. Số lượt đánh giá trên App Store Mỹ: 13. Khác: nhiều tài khoản cho mỗi mạng, proxy riêng cho từng tài khoản.
- **[noShorts](https://apps.apple.com/us/app/id6821704649)**: mở mạng xã hội trong ứng dụng, đã bỏ Reels, Shorts, Dành cho bạn và Spotlight; phần thiết lập có hướng dẫn sẽ chặn ứng dụng của các mạng đó bằng Thời gian sử dụng và chuyển bạn sang noShorts. Mạng xã hội: Instagram, YouTube, TikTok, Snapchat, Facebook, X (có thể thêm Reddit, Bluesky và Tumblr). Giá: miễn phí, không gói đăng ký hay mua trong ứng dụng. Giữ tin nhắn: không nêu ("use it as usual"). Số lượt đánh giá trên App Store Mỹ: 0. Khác: giới hạn hằng ngày, giờ yên tĩnh, widget, không tài khoản hay phân tích.
- **[TheSNSisMine](https://apps.apple.com/us/app/id6765809922)**: ứng dụng trình duyệt cho bản web của Instagram, YouTube, Facebook và X, ẩn bài viết đề xuất, Reels và Shorts và chỉ giữ người bạn theo dõi trong bảng tin. Mạng xã hội: Instagram, YouTube, Facebook, X. Giá: cần gói đăng ký (¥200/tháng theo phần mô tả, dùng thử miễn phí 7 ngày). Giữ tin nhắn: không nêu. Số lượt đánh giá trên App Store Mỹ: 0.
- **[Feather](https://apps.apple.com/us/app/id6787193472)**: mở mạng xã hội qua ứng dụng, đã bỏ Reels, Shorts, Dành cho bạn và Khám phá. Mạng xã hội: Instagram, YouTube, Snapchat, TikTok, Facebook, LinkedIn, X, Threads, Reddit. Giá: muốn dùng đầy đủ phải đăng ký (theo tháng, 6 tháng hoặc theo năm). Giữ tin nhắn: Có (tin nhắn, trang cá nhân và tìm kiếm vẫn còn). Số lượt đánh giá trên App Store Mỹ: 7. Khác: kiểm soát của phụ huynh cho tối đa 5 trẻ.
- **[Yava](https://apps.apple.com/us/app/id6800918860)**: chặn Reels, Shorts, Reels và Watch của Facebook, trang Khám phá và tự động phát, trong khi bạn vẫn nhắn tin với bạn bè được (phần mô tả không nói rõ cách chặn). Mạng xã hội: Instagram, YouTube, Facebook và các mạng khác. Giá: các tính năng cần gói đăng ký. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 8.
- **[Close](https://apps.apple.com/kr/app/id6817441004)** (Hàn Quốc): Instagram không có tab Reels và Khám phá; tin nhắn, Tin và bảng tin bạn bè có giới hạn vẫn còn, và khóa được ứng dụng Instagram thật bằng Thời gian sử dụng. Mạng xã hội: Instagram. Giá: mọi tính năng miễn phí; ủng hộ tùy ý. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store: không có trên App Store Mỹ; 3 ở Hàn Quốc.

<a id="safari-extensions"></a>
## Tiện ích mở rộng Safari
Các tiện ích này ẩn bảng tin trên instagram.com / youtube.com khi bạn lướt web bằng Safari. Ứng dụng chính thức không thay đổi gì.

- **[SocialFocus](https://apps.apple.com/us/app/id1661093205)**: tiện ích Safari ẩn những phần bạn chọn trên trang web, như bảng tin, Reels, Shorts và bình luận. Mạng xã hội: trang web YouTube, Facebook, X, Instagram, Reddit, LinkedIn và Gmail trong Safari. Giá: ứng dụng trả phí ($4.99 ở Mỹ); gói PRO tùy chọn. Giữ tin nhắn: không ghi. Số lượt đánh giá trên App Store Mỹ: 326. Khác: nhập/xuất cài đặt.
- **[ScrollGuard](https://apps.apple.com/us/app/id6754183872)**: tiện ích Safari ẩn bảng tin, Reels, Tin và Khám phá trên các trang mạng xã hội. Mạng xã hội: các trang mạng xã hội trong Safari. Giá: miễn phí, có tính năng Premium. Giữ tin nhắn: Có, theo trang web của ứng dụng (scrollguard.app, kiểm tra ngày 2026-10-17). Số lượt đánh giá trên App Store Mỹ: 117. Khác: cần iOS 18.
- **[Slowth](https://apps.apple.com/us/app/id6764140763)**: tiện ích Safari ẩn Shorts, Reels và mục Khám phá của X; trong ứng dụng YouTube và Instagram, nó có thể nhận ra Shorts hoặc Reels qua tính năng ghi màn hình rồi chặn ứng dụng. Mạng xã hội: trang web YouTube, Instagram, Facebook, X, TikTok trong Safari. Giá: tải miễn phí. Giữ tin nhắn: không ghi. Số lượt đánh giá trên App Store Mỹ: 3. Khác: các giới hạn bị khóa trong 24 giờ.
- **[Nope](https://apps.apple.com/us/app/id6768192042)**: tiện ích web Safari cho instagram.com và youtube.com. Mạng xã hội: Instagram, YouTube. Giá: hoàn toàn miễn phí, không gói đăng ký hay mua trong ứng dụng. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 2. Khác: có tiện ích Chrome.
- **[#blockit](https://apps.apple.com/us/app/id1492879257)**: tiện ích Safari bỏ Shorts, Reels và các bảng tin cuộn vô tận khỏi những trang web phổ biến, và chặn được cả trang theo URL. Mạng xã hội: các trang web phổ biến trong Safari. Giá: tải miễn phí, dùng thử miễn phí 7 ngày. Giữ tin nhắn: Có ("leaves everything else"). Số lượt đánh giá trên App Store Mỹ: 168. Khác: duy trì từ năm 2020, không cần tài khoản.
- **[No Reel For Instagram](https://apps.apple.com/us/app/id6752605548)**: tiện ích Safari cho instagram.com, ẩn mục điều hướng Reels, Reels trong Tìm kiếm và Khám phá, Tin, tab Dành cho bạn và tài khoản gợi ý. Mạng xã hội: Instagram. Giá: $3.39. Giữ tin nhắn: Có. Số lượt đánh giá trên App Store Mỹ: 0. Khác: iPhone, iPad và Mac.
- **[No Shorts: Blocker for YouTube](https://apps.apple.com/us/app/id6502996298)**: tiện ích Safari ẩn bảng tin Shorts, bản xem trước và gợi ý trên youtube.com. Mạng xã hội: YouTube. Giá: $2.99 trả một lần. Giữ tin nhắn: không áp dụng. Số lượt đánh giá trên App Store Mỹ: 15.
- **[ShortformBlock](https://apps.apple.com/us/app/id6761337873)**: tiện ích Safari miễn phí ẩn Shorts YouTube trong bảng tin, kết quả tìm kiếm và thanh điều hướng. Mạng xã hội: YouTube. Giá: miễn phí. Giữ tin nhắn: không áp dụng. Số lượt đánh giá trên App Store Mỹ: 13.
- **[Still](https://apps.apple.com/us/app/id6784061138)**: tiện ích Safari bỏ Shorts YouTube cùng Reels Instagram và Facebook, và chặn trang web TikTok; cài đặt đồng bộ được với tiện ích Chrome và Firefox nếu đăng nhập miễn phí (không bắt buộc). Mạng xã hội: trang web YouTube, Instagram, Facebook, TikTok. Giá: miễn phí; chặn không cần tài khoản hay mua gì. Giữ tin nhắn: Có (tin nhắn vẫn còn). Số lượt đánh giá trên App Store Mỹ: 0. Khác: iPhone, iPad và Mac.
- **[tubetidy](https://apps.apple.com/us/app/id6780741579)**: tiện ích Safari ẩn Shorts YouTube ở mọi nơi, đề xuất ở trang chủ, video liên quan, bình luận và nhiều thứ khác, kèm bộ lọc từ khóa và kênh. Mạng xã hội: YouTube. Giá: $2.99 trả một lần (¥500 ở Nhật). Giữ tin nhắn: không áp dụng. Số lượt đánh giá trên App Store Mỹ: 0. Khác: iPhone, iPad và Mac.

<a id="whole-app-blockers"></a>
## Ứng dụng chặn cả ứng dụng (chặn luôn tin nhắn)
Hữu ích nếu bạn muốn bỏ hẳn một ứng dụng; chúng không bỏ Reels mà vẫn giữ tin nhắn.
- **[Opal](https://apps.apple.com/us/app/id1497465230)**: chặn các ứng dụng bạn chọn theo lịch bằng Thời gian sử dụng.
- **[one sec](https://apps.apple.com/us/app/id1532875441)**: thêm một nhịp hít thở trước khi ứng dụng mở ra.
- **[ScreenZen](https://apps.apple.com/us/app/id1541027222)**: bắt chờ một chút trước khi mở ứng dụng; duy trì nhờ tiền ủng hộ.
- **[No Scroll](https://apps.apple.com/us/app/id6474079216)**: bạn chọn giới hạn thời gian trước khi mở ứng dụng; hết giờ thì ứng dụng bị khóa 5 phút.
- **[DMOnly](https://apps.apple.com/us/app/id6773196876)**: khóa các ứng dụng mạng xã hội bạn chọn và cho mở theo từng khung 15 phút.
- **[Curfew](https://apps.apple.com/us/app/id6755434607)**: khóa các ứng dụng bạn chọn (như Instagram hay YouTube) theo lịch bằng Thời gian sử dụng; mở khóa thì phải chờ 5 phút. Một lịch miễn phí; Pro mua một lần.
- **[숏패스 (ShortPass)](https://apps.apple.com/kr/app/id6803353215)** (Hàn Quốc): khóa các ứng dụng bạn chọn trong giờ học hoặc sau khi hết giới hạn hằng ngày, kèm đếm ngược ngày thi (D-day); tính năng khóa nằm trong Pro (gói không tự gia hạn).

<a id="how-to-choose"></a>
## Nên chọn thế nào
- **Chỉ cần Instagram để nhắn tin và nhóm chat?** Tìm chế độ chỉ tin nhắn / Messages Only (UNDOOMED, LoomWeb, Konvo, minulo, Reelmute, Stillfeed).
- **Cần cả TikTok hoặc Snapchat?** Xem mục mạng xã hội được hỗ trợ, vì không phải ứng dụng nào cũng có.
- **Cứ mở ứng dụng chính thức theo thói quen?** Chọn ứng dụng khóa được ứng dụng chính thức bằng Thời gian sử dụng (SocialLite, minulo, noShorts, snowscroll, Reelmute, Konvo).
- **Muốn mọi thứ miễn phí?** Nope, ShortformBlock và Still là tiện ích Safari miễn phí; noShorts, Dome, Noreel và Close cho biết là miễn phí; các trình duyệt trong ứng dụng cho ẩn cơ bản miễn phí gồm minulo, Stillfeed, Reelmute và Awhile. Mỗi ứng dụng miễn phí những gì: [Ứng dụng miễn phí chặn Reels Instagram và YouTube Shorts trên iPhone (2026)](https://minulo.app/vi/free-reels-blocker.html).

Chi tiết hơn: [bảng so sánh](https://minulo.app/vi/alternatives.html) · [Có xóa được Reels khỏi ứng dụng Instagram trên iPhone không?](https://minulo.app/vi/remove-reels-from-instagram-app.html)

So với một ứng dụng cụ thể: [Thay thế ScreenZen](https://minulo.app/vi/screenzen-alternatives.html) · [Thay thế one sec](https://minulo.app/vi/one-sec-alternatives.html) · [Thay thế Opal](https://minulo.app/vi/opal-alternatives.html)


<a id="guides"></a>
## Hướng dẫn
Bài viết từng bước (của nhà phát triển minulo; bài nào cũng nói về các tùy chọn có sẵn trước). Các bài trên dev.to, Hashnode và Substack viết bằng tiếng Anh.
- [Instagram Screen Time limit not working on iPhone? The 5 settings behind it](https://dev.to/ayumu_kitabayashi_8e0de96/instagram-screen-time-limit-not-working-on-iphone-the-5-settings-behind-it-2026-1bf7)
- [How to turn off YouTube Shorts on iPhone in 2026 (and why no app can fully remove them)](https://minulo.hashnode.dev/how-to-turn-off-youtube-shorts-on-iphone-in-2026-and-why-no-app-can-fully-remove-them)
- [Keep Instagram DMs, lose Reels: 5 ways to do it on iPhone (2026, compared)](https://dev.to/ayumu_kitabayashi_8e0de96/keep-instagram-dms-lose-reels-5-ways-to-do-it-on-iphone-2026-compared-17dh)
- [5 timing bugs I hit building timed blocks with Screen Time's DeviceActivity (iOS)](https://dev.to/ayumu_kitabayashi_8e0de96/5-timing-bugs-i-hit-building-timed-blocks-with-screen-times-deviceactivity-ios-5dnc) (cho lập trình viên)
- [Using TikTok just for messages on iPhone: 5 options and their catches](https://minulo.substack.com/p/using-tiktok-just-for-messages-on)
- [When people reach for Reels: what an app's first month of usage data shows (and what it can't)](https://minulo.substack.com/p/when-people-reach-for-reels-what)
- [Three ways to build a Reels blocker on iOS: content blocker, Safari extension, or WKWebView](https://minulo.hashnode.dev/three-ways-to-build-a-reels-blocker-on-ios-content-blocker-safari-extension-or-wkwebview) (cho lập trình viên)
- [What's actually free when you block Reels and Shorts on iPhone (2026)](https://minulo.substack.com/p/whats-actually-free-when-you-block)
- [Cách ngừng lướt điện thoại ban đêm trên iPhone (2026)](https://minulo.app/vi/stop-doomscrolling-at-night.html)
- [minulo có an toàn không? Ứng dụng thấy được gì và không thấy gì (2026)](https://minulo.app/vi/is-minulo-safe.html) (đặt nhãn quyền riêng tư của minulo, SocialLite và UNDOOMED cạnh nhau)
- [Cách chặn Instagram trên iPhone (ứng dụng và Safari, 2026)](https://minulo.app/vi/block-instagram-on-iphone.html)
- [Cách chặn TikTok trên iPhone (ứng dụng và trang web, 2026)](https://minulo.app/vi/block-tiktok-on-iphone.html)
- [Cách ẩn trang Khám phá trên Instagram](https://minulo.app/vi/hide-instagram-explore.html) và [chỉ xem bài của tài khoản bạn theo dõi](https://minulo.app/vi/instagram-following-feed-only.html)
- [Cách tắt Spotlight của Snapchat và thông báo của nó trên iPhone](https://minulo.app/vi/turn-off-snapchat-spotlight.html)
- [Ứng dụng thay thế Brick trên iPhone không cần thiết bị](https://minulo.app/vi/brick-alternative-iphone.html)
- [Why you can't set a time limit on just Instagram Reels on iPhone (and what Screen Time's API can do)](https://dev.to/ayumu_kitabayashi_8e0de96/why-you-cant-set-a-time-limit-on-just-instagram-reels-on-iphone-and-what-screen-times-api-can-522)
- [How I ship an iPhone app and its website in 13 languages as a solo developer](https://dev.to/ayumu_kitabayashi_8e0de96/how-i-ship-an-iphone-app-and-its-website-in-13-languages-as-a-solo-developer-10gk) (cho lập trình viên)


### Mỗi câu hỏi một trang (tháng 10/2026)
Các trang ngắn trên minulo.app, mỗi trang trả lời một câu hỏi, lấy trang trợ giúp chính thức của nền tảng làm nguồn.
- [Tắt tự động phát video trên Instagram và Facebook](https://minulo.app/vi/instagram-autoplay-off.html)
- [Đã chọn Không quan tâm mà Reels vẫn hiện? Vì sao](https://minulo.app/vi/not-interested-reels-still-showing.html)
- [Có xóa được tab Reels trên Instagram không? (2026)](https://minulo.app/vi/instagram-reels-tab-remove.html)
- [Reels trên Instagram cho iPad: tắt được gì](https://minulo.app/vi/instagram-reels-ipad.html)
- [Có xem riêng bài của Bạn thân trên Instagram được không?](https://minulo.app/vi/instagram-close-friends-feed.html)
- [Ẩn số lượt thích trên Instagram: có giúp gì không?](https://minulo.app/vi/hide-instagram-likes-counts.html)
- [Dùng YouTube không có Shorts trên iPad và Mac](https://minulo.app/vi/youtube-shorts-ipad-mac.html)
- [Cách thôi xem YouTube Shorts trên giường](https://minulo.app/vi/stop-youtube-shorts-at-night.html)
- [Tắt nhật ký xem YouTube thì Trang chủ ra sao](https://minulo.app/vi/youtube-history-off-home-feed.html)
- [Cách đặt lại đề xuất YouTube (iPhone)](https://minulo.app/vi/youtube-reset-recommendations.html)
- [Cách chỉ xem kênh đăng ký trên YouTube (iPhone)](https://minulo.app/vi/youtube-subscriptions-only.html)
- [Chỉ nhận thông báo YouTube từ kênh đã đăng ký](https://minulo.app/vi/youtube-notifications-subscriptions-only.html)
- [Cách bỏ kệ Shorts khỏi Trang chủ YouTube trên web](https://minulo.app/vi/youtube-shorts-remove-from-home-web.html)
- [Giới hạn YouTube Shorts cho thiếu niên, trẻ em và người lớn](https://minulo.app/vi/youtube-kids-vs-shorts.html)
- [Chế độ hạn chế của TikTok làm được gì và không làm được gì](https://minulo.app/vi/tiktok-restricted-mode.html)
- [Dùng Snapchat chỉ để chat và xem Câu chuyện của bạn bè](https://minulo.app/vi/snapchat-stories-only.html)
- [Có đặt giới hạn thời gian cho Snapchat Spotlight được không?](https://minulo.app/vi/snapchat-spotlight-time-limit.html)
- [Có tắt được Reels trên Facebook không? (iPhone)](https://minulo.app/vi/facebook-reels-off.html)
- [Có tắt được bảng tin video của LinkedIn trên iPhone không?](https://minulo.app/vi/linkedin-video-feed-off.html)
- [Cách ẩn trạng thái trên WhatsApp (iPhone)](https://minulo.app/vi/whatsapp-status-updates-hide.html)
- [Giờ nghỉ không chặn Instagram trên iPhone? Cách sửa](https://minulo.app/vi/downtime-not-working-instagram.html)
- [Bỏ qua giới hạn trên iPhone: cách tắt nút này](https://minulo.app/vi/app-limit-ignore-button.html)
- [Quên mật mã Thời gian sử dụng? Cách của Apple](https://minulo.app/vi/screen-time-passcode-forgot.html)
- [Cách đọc Báo cáo thời gian sử dụng hàng tuần trên iPhone](https://minulo.app/vi/screen-time-weekly-report.html)
- [Chế độ tập trung trên iPhone chỉ cho ứng dụng nhắn tin](https://minulo.app/vi/focus-mode-messages-only.html)
- [Chế độ thang độ xám trên iPhone có giúp bớt lướt không?](https://minulo.app/vi/grayscale-to-stop-scrolling.html)

<a id="guides-other-languages"></a>
## Hướng dẫn bằng ngôn ngữ khác
Do nhà phát triển minulo viết; bài nào cũng nói về các tùy chọn có sẵn trước.

**Tiếng Việt**
- [Mở app của mình từ màn hình chặn Screen Time trên iOS: ShieldAction không mở được URL, nên đi qua thông báo](https://viblo.asia/p/mo-app-cua-minh-tu-man-hinh-chan-screen-time-tren-ios-shieldaction-khong-mo-duoc-url-nen-di-qua-thong-bao-ZjJYWRrpVOE) (cho lập trình viên)
- [Ba cách làm app chặn Reels trên iOS: content blocker, tiện ích Safari hay WKWebView](https://viblo.asia/p/ba-cach-lam-app-chan-reels-tren-ios-content-blocker-tien-ich-safari-hay-wkwebview-kNLr3ezoVgA) (cho lập trình viên)

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
## Dữ liệu
Bảng so sánh ở trên dưới dạng CSV (mỗi ứng dụng một dòng: cách làm, mạng xã hội, giá, tin nhắn có còn dùng được không, số lượt đánh giá ở Mỹ và ngày kiểm tra): [data/ios-reels-shorts-blockers.csv](data/ios-reels-shorts-blockers.csv). Số lượt đánh giá chỉ là ảnh chụp tại một thời điểm và thay đổi hằng ngày; rất mong được góp ý chỉnh sửa.


## Giấy phép
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/): dùng tự do.
