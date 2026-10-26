# รวมแอปบล็อก Reels ของ Instagram และ YouTube Shorts บน iPhone (DM ยังใช้ได้)
[English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt-BR.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Bahasa Indonesia](README.id.md) | **ไทย** | [Tiếng Việt](README.vi.md) | [Русский](README.ru.md) | [繁體中文](README.zh-Hant.md)

รวมแอปและการตั้งค่าบน iPhone ที่ซ่อน **Reels ของ Instagram, YouTube Shorts และฟีด "สำหรับคุณ" ของ TikTok** แต่ส่วนอื่นของแต่ละแอปยังใช้ได้ตามปกติ ทั้ง DM แชทกลุ่ม การค้นหา และบัญชีที่คุณติดตาม

> **การเปิดเผยข้อมูล:** รายการนี้ดูแลโดยผู้พัฒนา [minulo](https://minulo.app/th/) ซึ่งเป็นหนึ่งในแอปด้านล่าง ข้อมูลทั้งหมดมาจากหน้า App Store สหรัฐฯ หรือเว็บไซต์ทางการของแต่ละแอปเท่านั้น (ตรวจสอบเมื่อตุลาคม 2026 อัปเดตจำนวนเรตติ้งล่าสุดเมื่อ 2026-10-24) จำนวนเรตติ้งเปลี่ยนทุกวัน ยินดีรับการแก้ไขและข้อมูลเพิ่มเติมผ่าน issue หรือ pull request


<a id="quick-answers"></a>
## คำตอบสั้น ๆ
- **แอป iPhone ฟรีตัวไหนซ่อน Reels ของ Instagram และ YouTube Shorts ได้ โดยที่ DM ยังใช้ได้?** แอปที่ซ่อนพื้นฐานได้ฟรีภายในแอปของตัวเอง ได้แก่ minulo (10 แพลตฟอร์ม), Reelmute (6), Stillfeed (Instagram และ YouTube) และ Awhile (Instagram อย่างเดียว) ส่วน Nope และ ScrollGuard ทำได้ฟรีในรูปแบบส่วนขยาย Safari จึงใช้ได้แค่ใน Safari และ noShorts ใช้ฟรีโดยไม่มีการซื้อภายในแอป แต่ละแอปฟรีแค่ไหน: [แอปฟรีบล็อก Reels และ Shorts](https://minulo.app/th/free-reels-blocker.html)
- **จะเอา YouTube Shorts ออกแต่ยังดูวิดีโอปกติได้อย่างไร?** ขีดจำกัดฟีด Shorts ของ YouTube ตั้งเป็น 0 ได้ แต่บัญชีผู้ใหญ่กดปิดการแจ้งเตือนได้ minulo, Stillfeed, Reelmute และ noShorts เปิด YouTube แบบไม่มี Shorts ภายในแอปของตัวเอง ส่วน Nope ทำแบบนี้ใน Safari ใน minulo วิดีโอปกติ การค้นหา และช่องที่ติดตามยังใช้ได้ตามเดิม ([วิธีทำ](https://minulo.app/th/block-youtube-shorts.html))
- **ใช้ Instagram แค่ DM ได้ไหม?** ตัว Instagram เองไม่มีโหมดแค่ DM ใน minulo การตั้งค่าทุกแท็บยกเว้น DM ใช้ได้ฟรี ส่วนใน UNDOOMED, Stillfeed, Reelmute และ Konvo มุมมองแบบแค่ข้อความต้องจ่ายเงิน ([วิธีทำ](https://minulo.app/th/instagram-dms-only.html), [แอปฟรีสำหรับใช้ Instagram แค่ DM](https://minulo.app/th/free-instagram-dms-only-app.html))
- **แอปไหนใช้งานคล้าย SocialLite?** แอปที่ล็อกแอปทางการด้วยเวลาหน้าจอแล้วพาไปหน้าของแอปตัวเองเหมือนกัน ได้แก่ minulo, noShorts, snowscroll, Reelmute และ Konvo ([เปรียบเทียบ](https://minulo.app/th/sociallite-alternatives.html))
- **SocialLite ใช้ฟรีไหม?** ดาวน์โหลดฟรีและมีการซื้อภายในแอป Pro ราคา $6.99 ถึง $17.99 ต่อเดือน หรือ $19.99 ถึง $47.90 ต่อปี ขึ้นอยู่กับข้อเสนอ และแพ็กเกจครอบครัวราคา $12.99 ต่อเดือน (App Store สหรัฐฯ ตรวจสอบเมื่อ 2026-10-26) minulo, Stillfeed และ Reelmute ซ่อน Reels และ Shorts ได้ฟรี ส่วน Nope ฟรีทั้งหมดใน Safari ([ราคาและแอปทางเลือกที่ฟรี](https://minulo.app/th/is-sociallite-free.html))
- **จะหยุดไถ Reels และ Shorts ตอนกลางคืนได้อย่างไร?** เวลาไม่ใช้งานในเวลาหน้าจอของ iPhone บล็อกทั้งแอป รวมถึง DM ด้วย ใน minulo การซ่อน Reels และ Shorts ใช้ได้ฟรี และหน้าของ minulo เองยังเก็บ DM ไว้ การล็อกแอปทางการใช้ได้ฟรีครั้งละไม่เกิน 2 ชั่วโมง ส่วนการตั้งเวลาทุกคืนอยู่ใน Pro แอปอื่นด้านล่างก็เพิ่มการตั้งเวลาได้เช่นกัน ดูรายละเอียดของแต่ละแอป ([วิธีทำ](https://minulo.app/th/stop-doomscrolling-at-night.html), [TikTok ตอนกลางคืน](https://minulo.app/th/stop-scrolling-tiktok-at-night.html))
- **ปิด YouTube Shorts ได้ไหม?** ไม่มีสวิตช์ปิด ใน YouTube ทำได้แค่ตั้งขีดจำกัดฟีด Shorts เป็น 0 (ผู้ใหญ่กดปิดได้) เลือกแสดง Shorts น้อยลง หรือปิดประวัติการดู ส่วนเวลาหน้าจอของ iPhone บล็อกทั้งแอป YouTube minulo ซ่อนชั้น Shorts และแท็บ Shorts ได้ฟรี โดยวิดีโอปกติ การค้นหา และการติดตามยังใช้ได้ตามเดิม แต่ได้ผลเฉพาะใน minulo ส่วน Nope ทำแบบนี้ใน Safari ([วิธีที่ใช้ได้](https://minulo.app/th/can-you-turn-off-youtube-shorts.html))
- **ซ่อนชั้น Shorts ด้วยปุ่ม X แล้วจะหายไปตลอดไหม?** ไม่ตลอด SlashGear และ GeekChamp อ้างข้อความว่าชั้นจะถูกซ่อน 30 วัน แต่ความช่วยเหลือของ YouTube ไม่ได้อธิบายปุ่ม X และไม่ได้บอกระยะเวลา ปุ่ม X ไม่ได้มีในทุกบัญชี และ Shorts ยังอยู่ในแท็บ Shorts การค้นหา การติดตาม และหน้าช่อง minulo ซ่อนชั้น Shorts และแท็บ Shorts ได้ฟรีจนกว่าคุณจะเปลี่ยนการตั้งค่า แต่ได้ผลเฉพาะใน minulo ([ปุ่ม X ซ่อนได้นานแค่ไหน](https://minulo.app/th/youtube-hide-shorts-shelf.html))
- **เปิด Instagram แล้วเข้า DM ทันทีได้ไหม?** ตัว Instagram เองไม่มีการตั้งค่านี้ การแตะการแจ้งเตือนข้อความจะเปิดแชทนั้น แต่ในแอป ฟีดและ Reels ก็ยังอยู่ห่างไปแค่แตะเดียว ใน minulo การตั้งค่าทุกแท็บยกเว้น DM ใช้ได้ฟรี และเหลือแค่ DM กับแท็บการแจ้งเตือน แต่ได้ผลเฉพาะใน minulo ([วิธีทำ](https://minulo.app/th/instagram-open-straight-to-dms.html))
- **ใช้ Instagram หรือ YouTube ใน Safari แทนแอปแล้วจะเลี่ยง Reels และ Shorts ได้ไหม?** แค่นั้นไม่พอ instagram.com ก็มี Reels และสำรวจ youtube.com ก็มี Shorts และถ้าไม่มีแอป Instagram ก็จะไม่ได้รับการแจ้งเตือน ถ้าจะซ่อนใน Safari ต้องใช้ส่วนขยายอย่าง Nope (ฟรี) หรือ ScrollGuard ส่วน minulo เปิดทั้งสองเว็บไซต์แบบไม่มี Reels และ Shorts ได้ฟรี แต่ได้ผลเฉพาะใน minulo ([Instagram ใน Safari](https://minulo.app/th/instagram-in-safari-instead-of-app.html), [YouTube ใน Safari](https://minulo.app/th/youtube-in-safari-without-shorts.html))


## สารบัญ
- [คำตอบสั้น ๆ](#quick-answers)
- [การตั้งค่าในตัว (ไม่ต้องใช้แอป)](#built-in-settings)
- [แอปที่เปิดโซเชียลแบบไม่มีฟีด](#in-app-browsers)
- [ส่วนขยาย Safari](#safari-extensions)
- [แอปที่บล็อกทั้งแอป (DM ก็โดนบล็อกด้วย)](#whole-app-blockers)
- [เลือกแบบไหนดี](#how-to-choose)
- [คู่มือ](#guides)
- [คู่มือภาษาอื่น](#guides-other-languages)
- [ข้อมูล (CSV)](#data)


<a id="built-in-settings"></a>
## การตั้งค่าในตัว (ไม่ต้องใช้แอป)
- **ขีดจำกัดฟีด Shorts ของ YouTube**: YouTube ให้ตั้งขีดจำกัดรายวันสำหรับฟีด Shorts ได้ (ตั้งเป็น 0 ก็ได้) สำหรับบัญชีผู้ใหญ่ การแจ้งเตือนกดปิดได้ และมีผลแค่ในแอป YouTube เท่านั้น ([วิธีทำ](https://minulo.app/th/youtube-shorts-feed-limit.html))
- **ฟีด "กำลังติดตาม" ของ Instagram (Following)**: เปลี่ยนฟีดหน้าแรกให้แสดงแค่บัญชีที่คุณติดตาม แท็บ Reels และหน้าสำรวจยังอยู่
- **"เลื่อนโพสต์แนะนำ" ของ Instagram (Snooze suggested posts)**: ที่โพสต์แนะนำ แตะ ⋯ → ไม่สนใจ → เลื่อนโพสต์แนะนำทั้งหมดในฟีดออกไป 30 วัน จะหมดผลหลัง 30 วัน และไม่มีผลกับแท็บ Reels ([วิธีทำ](https://minulo.app/th/hide-suggested-posts-instagram.html))
- **"รีเซ็ตเนื้อหาที่แนะนำ" ของ Instagram (Reset suggested content)**: ไปที่การตั้งค่า → การตั้งค่าเนื้อหา → รีเซ็ตเนื้อหาที่แนะนำ เพื่อล้างสิ่งที่ Instagram แนะนำในหน้าสำรวจ Reels และฟีด ย้อนกลับไม่ได้ และระบบจะเริ่มเรียนรู้ใหม่เมื่อคุณดูต่อ ([วิธีทำ](https://minulo.app/th/reset-instagram-reels-recommendations.html))
- **ปิดเล่นอัตโนมัติของ YouTube**: วิดีโอถัดไปจะไม่เล่นเอง วิดีโอแนะนำยังอยู่ เว้นแต่จะปิดประวัติการดูและประวัติว่างเปล่า ([วิธีทำ](https://minulo.app/th/turn-off-youtube-autoplay-recommendations.html))
- **เวลาหน้าจอของ iPhone**: จำกัดหรือบล็อกทั้งแอป DM และแชทกลุ่มจะโดนบล็อกไปพร้อมกับฟีดด้วย


<a id="in-app-browsers"></a>
## แอปที่เปิดโซเชียลแบบไม่มีฟีด
แอปกลุ่มนี้เปิดเว็บไซต์ของแต่ละโซเชียลในแอปของตัวเอง แล้วซ่อน Reels, Shorts หรือ "สำหรับคุณ" บางแอปยังล็อกแอปทางการด้วยเวลาหน้าจอได้ด้วย จะได้ไม่เผลอกลับไปเปิดเพราะความเคยชิน

- **[SocialLite](https://apps.apple.com/us/app/id6757661674)**: มุมมองโซเชียลแบบเน้นโฟกัสในแอป ตามบันทึกประจำรุ่น บล็อกแอปทางการด้วยเวลาหน้าจอและพาไปที่ SocialLite แทนได้ แพลตฟอร์ม: Instagram, YouTube, Snapchat, X, Reddit และอื่น ๆ (ไม่ได้พูดถึง TikTok) ราคา: ดาวน์โหลดฟรี Pro ราคา $6.99 หรือ $9.99 ต่อเดือน หรือ $19.99 ถึง $47.90 ต่อปี แล้วแต่ข้อเสนอ (สหรัฐฯ) ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: ประมาณ 15,000 (★4.7)
- **[UNDOOMED](https://apps.apple.com/us/app/id6751837079)**: เปิดเว็บไซต์มือถือของแต่ละโซเชียลในเบราว์เซอร์ส่วนตัวของแอป แล้วกรองหน้าเว็บ แพลตฟอร์ม: Instagram, Threads, Reddit, Facebook, X, YouTube, LinkedIn (ไม่มี TikTok และ Snapchat) ราคา: ฟีเจอร์ส่วนใหญ่ฟรี Plus $1.99/เดือน หรือ $11.99/ปี Pro $2.99/เดือน, $17.99/ปี หรือ $29.99 ตลอดชีพ (สหรัฐฯ) ยังใช้ DM ได้: ใช่ (โหมด Messages Only) เรตติ้งใน App Store สหรัฐฯ: 108
- **[Dull](https://apps.apple.com/us/app/id6759723829)**: เปิดแต่ละแพลตฟอร์มในเบราว์เซอร์ของแอปเอง โดยเอา Reels, Shorts, "สำหรับคุณ" และหน้าสำรวจออก แพลตฟอร์ม: Instagram, YouTube, Facebook, X, Reddit ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 55 อื่น ๆ: ขีดจำกัดรายวัน ช่วงเวลาเงียบ และต้องรอ 24 ชั่วโมงก่อนผ่อนตัวกรอง
- **[WallHabit](https://apps.apple.com/us/app/id6751423279)**: บล็อก Reels และ Shorts หรือทั้งแอป และให้กดปุ่มค้างไว้ก่อนปลดล็อก (คำอธิบายไม่ได้บอกรายละเอียดว่าบล็อก Reels อย่างไร) แพลตฟอร์ม: ไม่ได้ระบุ ราคา: ฟรี มีซื้อในแอป ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 35 อื่น ๆ: ต้องใช้ iOS 18
- **[LoomWeb](https://apps.apple.com/us/app/id6754727620)**: เบราว์เซอร์สำหรับโซเชียลที่ตั้งค่าแยกได้ทีละเว็บ แพลตฟอร์ม: Instagram, YouTube, X, Facebook ราคา: ฟรี มีแพ็กเกจ Pro ยังใช้ DM ได้: ใช่ (มีตัวเลือกแค่ DM) เรตติ้งใน App Store สหรัฐฯ: 34 อื่น ๆ: ต้องใช้ iOS 18
- **[Scroll Less](https://apps.apple.com/us/app/id6741134096)**: เปิด YouTube, Instagram และแพลตฟอร์มอื่นในเบราว์เซอร์แบบเรียบง่ายของแอปเอง (WebView) แล้วเอาฟีดแนะนำตามอัลกอริทึมออก แพลตฟอร์ม: YouTube, Instagram และอื่น ๆ (ไม่ได้ให้รายการครบ) ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 23
- **[Sociano](https://apps.apple.com/us/app/id6760568406)**: เปิดโซเชียลที่รองรับในเบราว์เซอร์ที่ควบคุมได้ของแอปเอง และบล็อก Reels, Shorts และฟีด ยังบล็อกแอปบน iPhone ที่เลือกด้วยเวลาหน้าจอได้ด้วย แพลตฟอร์ม: Instagram, YouTube, X, Facebook, LinkedIn และอื่น ๆ ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 10 อื่น ๆ: บล็อกแอป ตั้งเวลา และขีดจำกัดรายวัน
- **[snowscroll](https://apps.apple.com/us/app/id6778488660)**: เปิดเว็บไซต์มือถือของแต่ละโซเชียลในเบราว์เซอร์ในแอปแบบเน้นโฟกัส และซ่อนฟีด เมื่อใช้ร่วมกับเวลาหน้าจอ เวลาเปิดแอป Instagram จริงจะเปิด snowscroll แทน แพลตฟอร์ม: Instagram, YouTube, Facebook, X, TikTok, LinkedIn ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 10 อื่น ๆ: หน้าจอบล็อกสำหรับแอปทางการ
- **[Awhile](https://apps.apple.com/us/app/id6763551826)**: โหลด instagram.com ในเบราว์เซอร์ในแอปของตัวเอง และซ่อนส่วนที่เลือก แพลตฟอร์ม: Instagram เท่านั้น ราคา: การกรองใช้ฟรี Premium €2.99/เดือน หรือ €9.99 จ่ายครั้งเดียว ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 4
- **[Fluid Friction](https://apps.apple.com/us/app/id6782510849)**: เปิดโซเชียลในแอปและทำให้ไถฟีดได้ยากขึ้น ซ่อน Reels, Shorts, สตอรี่ และหน้าสำรวจได้ด้วย แพลตฟอร์ม: Instagram, TikTok, YouTube, Reddit, X, Snapchat, Facebook, LinkedIn ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ (ข้อความยังใช้ได้) เรตติ้งใน App Store สหรัฐฯ: 6 อื่น ๆ: หน้าจอบล็อกด้วยเวลาหน้าจอสำหรับแอปอื่น
- **[minulo](https://apps.apple.com/us/app/id6809352229)**: เปิดเว็บไซต์ทางการของแต่ละโซเชียลในแอป และซ่อนส่วนที่เลือก ล็อกแอปทางการด้วยเวลาหน้าจอแล้วพาไปที่ minulo แทนได้ด้วย แพลตฟอร์ม: Instagram, YouTube, TikTok, X, Threads, Facebook, Pinterest, Reddit, LinkedIn, Snapchat (10) ราคา: การซ่อนใช้ฟรี และล็อกแอปทางการได้ฟรีครั้งละไม่เกิน 2 ชั่วโมง Pro ($9.99/เดือน หรือ $39.99/ปี ในสหรัฐฯ) เพิ่มการตั้งเวลา, Hard Mode, ล็อกได้นานขึ้น และรายการบล็อกหลายชุด ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: iPhone และ Mac ไม่มีเวอร์ชัน Android ดูแลโดยผู้เขียนรายการนี้
- **[Stillfeed](https://apps.apple.com/us/app/id6792934511)**: เปิด Instagram และ YouTube ในเบราว์เซอร์ในตัว โดยเอา Reels, หน้าสำรวจ และ Shorts ออก แพลตฟอร์ม: Instagram, YouTube ราคา: บล็อก Reels และ Shorts ใช้ฟรี Pro เพิ่มฟีดเฉพาะคนที่ติดตาม การบล็อกสตอรี่และฟีด และโหมดแค่ DM ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: สถิติการบล็อกรายสัปดาห์
- **[Unfeed](https://apps.apple.com/us/app/id6814847686)**: เปิดโซเชียลในแอปของตัวเอง พร้อมตัวกรองที่ไม่ให้ฟีดโหลด แพลตฟอร์ม: Instagram, TikTok, YouTube, X ราคา: ดาวน์โหลดฟรี Pro เพิ่มการซ่อนโฆษณา โพสต์แนะนำ และสตอรี่ รวมถึงใช้หลายบัญชี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: ตัวจับเวลาต่อครั้ง โควตารายวัน โหมดนอน
- **[Konvo](https://apps.apple.com/us/app/id6794756261)**: เปิด Instagram ตรงไปที่กล่องข้อความ ฟีด, Reels และหน้าสำรวจไม่โหลดเลย แพลตฟอร์ม: Instagram (แค่ข้อความ) ราคา: ต้องสมัครแบบเสียเงินถึงจะใช้ DM ของ Instagram ในแอปได้ ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 1 อื่น ๆ: ล็อกแอป Instagram ได้ มีสิทธิ์เปิดสั้น ๆ วันละ 2 ครั้ง
- **[Scrollout](https://apps.apple.com/us/app/id6802054477)**: ซ่อน Reels, Shorts, เนื้อหาแนะนำ และโฆษณาบนแพลตฟอร์มที่รองรับ แพลตฟอร์ม: YouTube และอื่น ๆ (ไม่ได้ให้รายการครบ) ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0
- **[Reelmute](https://apps.apple.com/us/app/id6808963180)** (ในญี่ปุ่นใช้ชื่อ 「リールとショートを非表示」): เปิดโซเชียลในแอป และซ่อน Reels, Shorts และ "สำหรับคุณ" ก่อนหน้าเว็บจะแสดง Premium ล็อกแอปต้นฉบับได้ แพลตฟอร์ม: Instagram, YouTube, TikTok, Facebook, Reddit, X ราคา: การซ่อนใช้ฟรี Premium เพิ่มโหมดแค่ DM การซ่อนโพสต์แนะนำ และการล็อกแอป (ทดลองใช้ 3 วัน หรือแบบตลอดชีพ) ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: วิดเจ็ต โหมดนอน ระดับสีเทา
- **[Noreel](https://apps.apple.com/us/app/id6760568462)**: เอา Reels ออกในขณะที่คุณดูฟีด ดูสตอรี่ ส่ง DM และค้นหา แพลตฟอร์ม: ไม่ได้ระบุ ("social media") ราคา: ใช้ฟรี ไม่มีการสมัครสมาชิก ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 8
- **[LockedIn](https://apps.apple.com/us/app/id6767055765)**: บล็อก Reels ของ Instagram และ YouTube Shorts แบบถาวร มีสวิตช์เสริมสำหรับฟีดหน้าแรกของ Instagram, สตอรี่, การค้นหาและหน้าสำรวจ, การเล่นวิดีโอใน DM และวิดีโอแนะนำกับช่องที่ติดตามในหน้าแรก YouTube (คำอธิบายไม่ได้บอกว่าทำงานอย่างไร) แพลตฟอร์ม: Instagram, YouTube ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 1 อื่น ๆ: ไม่มีบัญชี ไม่มีการวิเคราะห์หรือติดตาม
- **[Dome](https://apps.apple.com/us/app/id6756055866)**: เอา Reels, Shorts และหน้าสำรวจออก ส่วนอื่นยังอยู่ แพลตฟอร์ม: ไม่ได้ระบุ ราคา: ฟรี ไม่มีเพย์วอลล์หรือโฆษณา ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 1
- **[SocialRouter](https://apps.apple.com/us/app/id6758858307)**: แยกพื้นที่เบราว์เซอร์สำหรับบัญชีโซเชียลหลายบัญชี ซ่อน Reels, ฟีด และหน้าสำรวจของ Instagram และ Shorts ของ YouTube ได้ แพลตฟอร์ม: Instagram, YouTube และอื่น ๆ ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 13 อื่น ๆ: หลายบัญชีต่อแพลตฟอร์ม พร็อกซีแยกต่อบัญชี
- **[noShorts](https://apps.apple.com/us/app/id6821704649)**: เปิดโซเชียลในแอป โดยเอา Reels, Shorts, "สำหรับคุณ" และ Spotlight ออก มีขั้นตอนตั้งค่าแบบแนะนำที่บล็อกแอปของโซเชียลนั้น ๆ ด้วยเวลาหน้าจอและพาไปที่ noShorts แพลตฟอร์ม: Instagram, YouTube, TikTok, Snapchat, Facebook, X (เพิ่ม Reddit, Bluesky และ Tumblr ได้) ราคา: ฟรี ไม่มีการสมัครสมาชิกหรือซื้อในแอป ยังใช้ DM ได้: ไม่ได้ระบุ ("use it as usual") เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: ขีดจำกัดรายวัน ช่วงเวลาเงียบ วิดเจ็ต ไม่มีบัญชีหรือการวิเคราะห์
- **[TheSNSisMine](https://apps.apple.com/us/app/id6765809922)**: แอปเบราว์เซอร์สำหรับเวอร์ชันเว็บของ Instagram, YouTube, Facebook และ X ที่ซ่อนโพสต์แนะนำ, Reels และ Shorts และให้ฟีดแสดงแค่คนที่คุณติดตาม แพลตฟอร์ม: Instagram, YouTube, Facebook, X ราคา: ต้องสมัครสมาชิก (¥200/เดือน ตามคำอธิบาย ทดลองใช้ฟรี 7 วัน) ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 0
- **[Feather](https://apps.apple.com/us/app/id6787193472)**: เปิดโซเชียลผ่านแอป โดยเอา Reels, Shorts, "สำหรับคุณ" และหน้าสำรวจออก แพลตฟอร์ม: Instagram, YouTube, Snapchat, TikTok, Facebook, LinkedIn, X, Threads, Reddit ราคา: ใช้ได้เต็มรูปแบบต้องสมัครสมาชิก (รายเดือน 6 เดือน หรือรายปี) ยังใช้ DM ได้: ใช่ (ข้อความ โปรไฟล์ และการค้นหายังอยู่) เรตติ้งใน App Store สหรัฐฯ: 7 อื่น ๆ: การควบคุมโดยผู้ปกครองสำหรับเด็กได้สูงสุด 5 คน
- **[Yava](https://apps.apple.com/us/app/id6800918860)**: บล็อก Reels, Shorts, Reels และ Watch ของ Facebook, หน้าสำรวจ และการเล่นอัตโนมัติ โดยยังส่งข้อความหาเพื่อนได้ (คำอธิบายไม่ได้บอกรายละเอียดว่าบล็อกอย่างไร) แพลตฟอร์ม: Instagram, YouTube, Facebook และอื่น ๆ ราคา: ฟีเจอร์ต้องสมัครสมาชิก ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 8
- **[Close](https://apps.apple.com/kr/app/id6817441004)** (เกาหลี): Instagram ที่ไม่มีแท็บ Reels และหน้าสำรวจ DM, สตอรี่ และฟีดเพื่อนแบบจำกัดยังอยู่ และล็อกแอป Instagram จริงด้วยเวลาหน้าจอได้ แพลตฟอร์ม: Instagram ราคา: ทุกฟีเจอร์ฟรี ให้ทิปได้ตามสมัครใจ ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store: ไม่มีใน App Store สหรัฐฯ มี 3 ในเกาหลี

<a id="safari-extensions"></a>
## ส่วนขยาย Safari
ส่วนขยายกลุ่มนี้ซ่อนฟีดบน instagram.com / youtube.com ระหว่างที่คุณใช้ Safari แอปทางการไม่เปลี่ยนแปลง

- **[SocialFocus](https://apps.apple.com/us/app/id1661093205)**: ส่วนขยาย Safari ที่ซ่อนส่วนที่เลือกของเว็บไซต์ เช่น ฟีด Reels Shorts และคอมเมนต์ แพลตฟอร์ม: เว็บไซต์ YouTube, Facebook, X, Instagram, Reddit, LinkedIn และ Gmail ใน Safari ราคา: แอปเสียเงิน ($4.99 ในสหรัฐฯ) มีการสมัคร PRO เสริม ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 326 อื่น ๆ: นำเข้า/ส่งออกการตั้งค่า
- **[ScrollGuard](https://apps.apple.com/us/app/id6754183872)**: ส่วนขยาย Safari ที่ซ่อนฟีด Reels สตอรี่ และหน้าสำรวจบนเว็บไซต์โซเชียล แพลตฟอร์ม: เว็บไซต์โซเชียลใน Safari ราคา: ฟรี มีฟีเจอร์ Premium ยังใช้ DM ได้: ใช่ ตามเว็บไซต์ของแอป (scrollguard.app ตรวจสอบเมื่อ 2026-10-17) เรตติ้งใน App Store สหรัฐฯ: 117 อื่น ๆ: ต้องใช้ iOS 18
- **[Slowth](https://apps.apple.com/us/app/id6764140763)**: ส่วนขยาย Safari ที่ซ่อน Shorts, Reels และหน้าสำรวจของ X ในแอป YouTube และ Instagram ตรวจจับ Shorts หรือ Reels ผ่านการบันทึกหน้าจอแล้วบล็อกแอปได้ แพลตฟอร์ม: เว็บไซต์ YouTube, Instagram, Facebook, X, TikTok ใน Safari ราคา: ดาวน์โหลดฟรี ยังใช้ DM ได้: ไม่ได้ระบุ เรตติ้งใน App Store สหรัฐฯ: 3 อื่น ๆ: ข้อจำกัดจะล็อกไว้ 24 ชั่วโมง
- **[Nope](https://apps.apple.com/us/app/id6768192042)**: ส่วนขยายเว็บของ Safari สำหรับ instagram.com และ youtube.com แพลตฟอร์ม: Instagram, YouTube ราคา: ฟรีทั้งหมด ไม่มีการสมัครสมาชิกหรือซื้อในแอป ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 2 อื่น ๆ: มีส่วนขยาย Chrome
- **[#blockit](https://apps.apple.com/us/app/id1492879257)**: ส่วนขยาย Safari ที่เอา Shorts, Reels และฟีดที่ไถได้ไม่รู้จบออกจากเว็บไซต์ยอดนิยม และบล็อกทั้งเว็บไซต์ด้วย URL ได้ แพลตฟอร์ม: เว็บไซต์ยอดนิยมใน Safari ราคา: ดาวน์โหลดฟรี ทดลองใช้ฟรี 7 วัน ยังใช้ DM ได้: ใช่ ("leaves everything else") เรตติ้งใน App Store สหรัฐฯ: 168 อื่น ๆ: ดูแลมาตั้งแต่ปี 2020 ไม่ต้องมีบัญชี
- **[No Reel For Instagram](https://apps.apple.com/us/app/id6752605548)**: ส่วนขยาย Safari สำหรับ instagram.com ที่ซ่อนเมนู Reels, Reels ในการค้นหาและหน้าสำรวจ, สตอรี่, แท็บ "สำหรับคุณ" และบัญชีแนะนำ แพลตฟอร์ม: Instagram ราคา: $3.39 ยังใช้ DM ได้: ใช่ เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: iPhone, iPad และ Mac
- **[No Shorts: Blocker for YouTube](https://apps.apple.com/us/app/id6502996298)**: ส่วนขยาย Safari ที่ซ่อนฟีด Shorts ตัวอย่าง และวิดีโอแนะนำบน youtube.com แพลตฟอร์ม: YouTube ราคา: $2.99 จ่ายครั้งเดียว ยังใช้ DM ได้: ไม่เกี่ยวข้อง เรตติ้งใน App Store สหรัฐฯ: 15
- **[ShortformBlock](https://apps.apple.com/us/app/id6761337873)**: ส่วนขยาย Safari ฟรีที่ซ่อน YouTube Shorts ในฟีด ผลการค้นหา และเมนูนำทาง แพลตฟอร์ม: YouTube ราคา: ฟรี ยังใช้ DM ได้: ไม่เกี่ยวข้อง เรตติ้งใน App Store สหรัฐฯ: 13
- **[Still](https://apps.apple.com/us/app/id6784061138)**: ส่วนขยาย Safari ที่เอา YouTube Shorts และ Reels ของ Instagram กับ Facebook ออก และบล็อกเว็บไซต์ TikTok การตั้งค่าซิงค์กับส่วนขยาย Chrome และ Firefox ได้ถ้าเข้าสู่ระบบฟรี (ไม่บังคับ) แพลตฟอร์ม: เว็บไซต์ YouTube, Instagram, Facebook, TikTok ราคา: ฟรี การบล็อกไม่ต้องใช้บัญชีหรือซื้ออะไร ยังใช้ DM ได้: ใช่ (ข้อความยังอยู่) เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: iPhone, iPad และ Mac
- **[tubetidy](https://apps.apple.com/us/app/id6780741579)**: ส่วนขยาย Safari ที่ซ่อน YouTube Shorts ทุกที่ วิดีโอแนะนำหน้าแรก วิดีโอที่เกี่ยวข้อง คอมเมนต์ และอื่น ๆ พร้อมตัวกรองคำและช่อง แพลตฟอร์ม: YouTube ราคา: $2.99 จ่ายครั้งเดียว (¥500 ในญี่ปุ่น) ยังใช้ DM ได้: ไม่เกี่ยวข้อง เรตติ้งใน App Store สหรัฐฯ: 0 อื่น ๆ: iPhone, iPad และ Mac

<a id="whole-app-blockers"></a>
## แอปที่บล็อกทั้งแอป (DM ก็โดนบล็อกด้วย)
เหมาะถ้าคุณอยากเลิกใช้แอปนั้นไปเลย แอปกลุ่มนี้ไม่ได้เอา Reels ออกโดยเก็บข้อความไว้
- **[Opal](https://apps.apple.com/us/app/id1497465230)**: บล็อกแอปที่เลือกตามตารางเวลาด้วยเวลาหน้าจอ
- **[one sec](https://apps.apple.com/us/app/id1532875441)**: ให้หยุดหายใจสักครู่ก่อนแอปจะเปิด
- **[ScreenZen](https://apps.apple.com/us/app/id1541027222)**: ให้รอสักพักก่อนเปิดแอป อยู่ได้ด้วยทิปจากผู้ใช้
- **[No Scroll](https://apps.apple.com/us/app/id6474079216)**: คุณเลือกเวลาจำกัดก่อนเปิดแอป เมื่อหมดเวลา แอปจะถูกล็อก 5 นาที
- **[DMOnly](https://apps.apple.com/us/app/id6773196876)**: ล็อกแอปโซเชียลที่เลือกไว้ และให้เปิดได้เป็นช่วงละ 15 นาที
- **[Curfew](https://apps.apple.com/us/app/id6755434607)**: ล็อกแอปที่เลือก (เช่น Instagram หรือ YouTube) ตามตารางเวลาด้วยเวลาหน้าจอ เมื่อปลดล็อกต้องรอ 5 นาที ตารางเวลาหนึ่งชุดใช้ฟรี Pro เป็นการซื้อครั้งเดียว
- **[숏패스 (ShortPass)](https://apps.apple.com/kr/app/id6803353215)** (เกาหลี): ล็อกแอปที่เลือกระหว่างช่วงอ่านหนังสือหรือหลังเกินขีดจำกัดรายวัน มีนับถอยหลังวันสอบ (D-day) การล็อกอยู่ใน Pro (พาสแบบไม่ต่ออายุอัตโนมัติ)

<a id="how-to-choose"></a>
## เลือกแบบไหนดี
- **ใช้ Instagram แค่ DM กับแชทกลุ่ม?** มองหาโหมดแค่ DM / Messages Only (UNDOOMED, LoomWeb, Konvo, minulo, Reelmute, Stillfeed)
- **ต้องใช้ TikTok หรือ Snapchat ด้วย?** ดูแพลตฟอร์มที่รองรับก่อน เพราะไม่ใช่ทุกแอปที่รองรับ
- **เผลอเปิดแอปทางการเพราะความเคยชินอยู่เรื่อย ๆ?** เลือกแอปที่ล็อกแอปทางการด้วยเวลาหน้าจอได้ (SocialLite, minulo, noShorts, snowscroll, Reelmute, Konvo)
- **อยากได้ฟรีทั้งหมด?** Nope, ShortformBlock และ Still เป็นส่วนขยาย Safari ฟรี noShorts, Dome, Noreel และ Close บอกว่าใช้ฟรี ส่วนเบราว์เซอร์ในแอปที่ให้ซ่อนพื้นฐานได้ฟรีก็มี minulo, Stillfeed, Reelmute และ Awhile แต่ละแอปฟรีแค่ไหน: [แอปฟรีบล็อก Reels ของ Instagram และ YouTube Shorts บน iPhone (2026)](https://minulo.app/th/free-reels-blocker.html)

รายละเอียดเพิ่มเติม: [ตารางเปรียบเทียบ](https://minulo.app/th/alternatives.html) · [เอา Reels ออกจากแอป Instagram บน iPhone ได้ไหม](https://minulo.app/th/remove-reels-from-instagram-app.html)

เทียบกับแอปที่เจาะจง (ภาษาอังกฤษ): [ScreenZen alternatives](https://minulo.app/en/screenzen-alternatives.html) · [one sec alternatives](https://minulo.app/en/one-sec-alternatives.html) · [Opal alternatives](https://minulo.app/en/opal-alternatives.html)


<a id="guides"></a>
## คู่มือ
บทความแบบทีละขั้นตอน (เขียนโดยผู้พัฒนา minulo ทุกบทเริ่มจากวิธีที่ทำได้ในตัวก่อน) บทความบน dev.to, Hashnode และ Substack เป็นภาษาอังกฤษ
- [Instagram Screen Time limit not working on iPhone? The 5 settings behind it](https://dev.to/ayumu_kitabayashi_8e0de96/instagram-screen-time-limit-not-working-on-iphone-the-5-settings-behind-it-2026-1bf7)
- [How to turn off YouTube Shorts on iPhone in 2026 (and why no app can fully remove them)](https://minulo.hashnode.dev/how-to-turn-off-youtube-shorts-on-iphone-in-2026-and-why-no-app-can-fully-remove-them)
- [Keep Instagram DMs, lose Reels: 5 ways to do it on iPhone (2026, compared)](https://dev.to/ayumu_kitabayashi_8e0de96/keep-instagram-dms-lose-reels-5-ways-to-do-it-on-iphone-2026-compared-17dh)
- [5 timing bugs I hit building timed blocks with Screen Time's DeviceActivity (iOS)](https://dev.to/ayumu_kitabayashi_8e0de96/5-timing-bugs-i-hit-building-timed-blocks-with-screen-times-deviceactivity-ios-5dnc) (สำหรับนักพัฒนา)
- [Using TikTok just for messages on iPhone: 5 options and their catches](https://minulo.substack.com/p/using-tiktok-just-for-messages-on)
- [When people reach for Reels: what an app's first month of usage data shows (and what it can't)](https://minulo.substack.com/p/when-people-reach-for-reels-what)
- [Three ways to build a Reels blocker on iOS: content blocker, Safari extension, or WKWebView](https://minulo.hashnode.dev/three-ways-to-build-a-reels-blocker-on-ios-content-blocker-safari-extension-or-wkwebview) (สำหรับนักพัฒนา)
- [What's actually free when you block Reels and Shorts on iPhone (2026)](https://minulo.substack.com/p/whats-actually-free-when-you-block)
- [วิธีเลิกไถฟีดตอนกลางคืนบน iPhone (2026)](https://minulo.app/th/stop-doomscrolling-at-night.html)
- [minulo ปลอดภัยไหม เห็นอะไรได้และเห็นอะไรไม่ได้ (2026)](https://minulo.app/th/is-minulo-safe.html) (เทียบป้ายความเป็นส่วนตัวของ minulo, SocialLite และ UNDOOMED)
- [วิธีบล็อก Instagram บน iPhone (แอปและ Safari)](https://minulo.app/th/block-instagram-on-iphone.html)
- [วิธีบล็อก TikTok บน iPhone (แอปและเว็บไซต์)](https://minulo.app/th/block-tiktok-on-iphone.html)
- [วิธีซ่อนหน้าสำรวจของ Instagram](https://minulo.app/th/hide-instagram-explore.html) และ [ดูแค่โพสต์จากคนที่ติดตาม](https://minulo.app/th/instagram-following-feed-only.html)
- [วิธีปิด Spotlight ของ Snapchat บน iPhone (2026)](https://minulo.app/th/turn-off-snapchat-spotlight.html)
- [ทางเลือกแทน Brick บน iPhone แบบไม่ต้องใช้อุปกรณ์ (2026)](https://minulo.app/th/brick-alternative-iphone.html)
- [Why you can't set a time limit on just Instagram Reels on iPhone (and what Screen Time's API can do)](https://dev.to/ayumu_kitabayashi_8e0de96/why-you-cant-set-a-time-limit-on-just-instagram-reels-on-iphone-and-what-screen-times-api-can-522)
- [How I ship an iPhone app and its website in 13 languages as a solo developer](https://dev.to/ayumu_kitabayashi_8e0de96/how-i-ship-an-iphone-app-and-its-website-in-13-languages-as-a-solo-developer-10gk) (สำหรับนักพัฒนา)


### หนึ่งคำถาม หนึ่งหน้า (ตุลาคม 2026)
หน้าสั้น ๆ บน minulo.app ที่แต่ละหน้าตอบคำถามเดียว โดยอ้างอิงหน้าช่วยเหลือทางการของแพลตฟอร์มนั้น
- [ปิดวิดีโอเล่นอัตโนมัติใน Instagram และ Facebook](https://minulo.app/th/instagram-autoplay-off.html)
- [กด ไม่สนใจ แล้ว Reels ยังขึ้นอยู่ เพราะอะไร](https://minulo.app/th/not-interested-reels-still-showing.html)
- [เอาแท็บ Reels ออกจาก Instagram ได้ไหม (2026)](https://minulo.app/th/instagram-reels-tab-remove.html)
- [Reels ใน Instagram บน iPad: ปิดอะไรได้บ้าง](https://minulo.app/th/instagram-reels-ipad.html)
- [ดูแค่โพสต์ของเพื่อนสนิทใน Instagram ได้ไหม](https://minulo.app/th/instagram-close-friends-feed.html)
- [ซ่อนจำนวนไลก์ใน Instagram ช่วยได้ไหม](https://minulo.app/th/hide-instagram-likes-counts.html)
- [ใช้ YouTube โดยไม่มี Shorts บน iPad และ Mac](https://minulo.app/th/youtube-shorts-ipad-mac.html)
- [วิธีเลิกดู YouTube Shorts บนเตียง](https://minulo.app/th/stop-youtube-shorts-at-night.html)
- [ปิดประวัติการดู YouTube แล้วหน้าแรกเป็นอย่างไร](https://minulo.app/th/youtube-history-off-home-feed.html)
- [วิธีรีเซ็ตวิดีโอแนะนำของ YouTube (iPhone)](https://minulo.app/th/youtube-reset-recommendations.html)
- [วิธีดู YouTube เฉพาะช่องที่ติดตาม (iPhone)](https://minulo.app/th/youtube-subscriptions-only.html)
- [รับการแจ้งเตือน YouTube เฉพาะช่องที่ติดตาม](https://minulo.app/th/youtube-notifications-subscriptions-only.html)
- [วิธีเอาชั้น Shorts ออกจากหน้าแรก YouTube บนเว็บ](https://minulo.app/th/youtube-shorts-remove-from-home-web.html)
- [ขีดจำกัด YouTube Shorts สำหรับวัยรุ่น เด็ก และผู้ใหญ่](https://minulo.app/th/youtube-kids-vs-shorts.html)
- [โหมดจำกัดของ TikTok ทำอะไรได้และทำอะไรไม่ได้](https://minulo.app/th/tiktok-restricted-mode.html)
- [ใช้ Snapchat แค่แชทและสตอรี่ของเพื่อน](https://minulo.app/th/snapchat-stories-only.html)
- [ตั้งเวลาจำกัด Spotlight ของ Snapchat ได้ไหม](https://minulo.app/th/snapchat-spotlight-time-limit.html)
- [ปิด Reels ใน Facebook ได้ไหม (iPhone)](https://minulo.app/th/facebook-reels-off.html)
- [ปิดฟีดวิดีโอของ LinkedIn บน iPhone ได้ไหม](https://minulo.app/th/linkedin-video-feed-off.html)
- [วิธีซ่อนสถานะใน WhatsApp (iPhone)](https://minulo.app/th/whatsapp-status-updates-hide.html)
- [เวลาไม่ใช้งานไม่บล็อก Instagram บน iPhone? วิธีแก้](https://minulo.app/th/downtime-not-working-instagram.html)
- [ไม่สนใจขีดจำกัดบน iPhone: วิธีปิดปุ่มนี้](https://minulo.app/th/app-limit-ignore-button.html)
- [ลืมรหัสเวลาหน้าจอ? วิธีแก้จาก Apple](https://minulo.app/th/screen-time-passcode-forgot.html)
- [วิธีอ่านรายงานเวลาหน้าจอรายสัปดาห์บน iPhone](https://minulo.app/th/screen-time-weekly-report.html)
- [โฟกัสของ iPhone ที่ให้แจ้งเตือนแค่แอปแชท](https://minulo.app/th/focus-mode-messages-only.html)
- [ตั้ง iPhone เป็นระดับสีเทาช่วยให้ไถฟีดน้อยลงไหม](https://minulo.app/th/grayscale-to-stop-scrolling.html)

<a id="guides-other-languages"></a>
## คู่มือภาษาอื่น
เขียนโดยผู้พัฒนา minulo ทุกบทเริ่มจากวิธีที่ทำได้ในตัวก่อน

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
## ข้อมูล
ข้อมูลเปรียบเทียบด้านบนในรูปแบบ CSV (หนึ่งแถวต่อหนึ่งแอป: วิธีการ แพลตฟอร์ม ราคา DM ยังใช้ได้หรือไม่ จำนวนเรตติ้งในสหรัฐฯ และวันที่ตรวจสอบ): [data/ios-reels-shorts-blockers.csv](data/ios-reels-shorts-blockers.csv) จำนวนเรตติ้งเป็นข้อมูล ณ วันที่บันทึกและเปลี่ยนทุกวัน ยินดีรับการแก้ไข


## สัญญาอนุญาต
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/): นำไปใช้ได้อย่างอิสระ
