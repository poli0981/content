---
title: "Trợ năng / Accessibility"
order: 7
effectiveDate: "2026-11-10"
---

## English

**1. Commitment.** I want everyone to be able to read and use this Site, including people who use only a keyboard, a screen reader, screen magnification, high-contrast settings or reduced motion. The Site aims to follow the Web Content Accessibility Guidelines (WCAG) 2.2 at Level AA. That is a target I work toward, not a certificate: the Site has not been audited by a third party.

**2. What is in place.** Every page works with a keyboard alone: there is a "Skip to content" link, a visible focus indicator, and focus returns to where you were when the menu, the search or the photo viewer closes. Pages declare their language, use headings and named landmarks, and give icon-only buttons a name. Text and controls meet Level AA contrast in both the dark and the light theme. Text can be enlarged to 200% and pages reflow down to a 320-pixel-wide screen. Animation is short, never loops and is switched off when your system asks for reduced motion. Nothing plays on its own: a video loads only after you press play. Windows High Contrast (forced colours) and the "increase contrast" setting are respected. Stories add their own reading settings: three text sizes and a paper, sepia or dark background.

**3. How it is tested.** By hand: with the keyboard only, with Windows Narrator in Edge, Chrome and Brave on Windows 11, and with VoiceOver in Safari on iPhone. Automatically: every change to the Site is scanned with axe-core and run through keyboard tests before it can be published, and a separate test checks every colour pair against Level AA. Not yet tested by me: NVDA, JAWS, TalkBack and VoiceOver on macOS. I expect them to work — please tell me if they do not.

**4. Known limitations.**

- **Bot check.** A first visit passes through a Cloudflare Turnstile check. It usually needs no action from you, but it is a third-party component I cannot change. If it stops you, write to me and I will send you what you were trying to read.
- **Videos.** Videos are embedded from YouTube. Captions are whatever YouTube provides for each video; I do not publish transcripts.
- **Older images.** Gallery photos always carry a caption in both languages. A few images inside older posts may still lack a text description.
- **Offline mini-game.** The small game on the offline page is drawn on a canvas. It can be played with the Space key, but a screen reader cannot follow it. It is an extra, not content.
- **Search.** Search needs JavaScript. Without it, every page is still reachable from the menu and the links in the footer.
- **Other sites.** Pages I link to (YouTube, Steam, GitHub, Discord and others) are outside my control.

**5. Tell me about a barrier.** Email accessibility@poli0981.dev, or use "Report a bug" at the bottom of every page — it needs no account. If you use GitHub, you can also open an issue with the Accessibility template at https://github.com/poli0981/poli0981-dev/issues/new/choose. It helps to say which page, what you were trying to do, what happened instead, and which browser and assistive technology you use. You do not have to diagnose anything, and you never need to tell me about a disability.

**6. What to expect.** I reply within 7 days. Barriers that stop someone from reading or using a page come first. This is a personal site run by one person in their spare time, so I cannot promise a date for every fix — but I will tell you what I plan to do, and a workaround if there is one.

**7. Scope and review.** This statement covers poli0981.dev. It does not cover the private admin area or the third-party sites linked from here. I review it at least once a year and whenever the interface changes; the date above is the last review. Notes for people who work on the code are in ACCESSIBILITY.md at https://github.com/poli0981/poli0981-dev.

## Tiếng Việt

**1. Cam kết.** Mình muốn ai cũng đọc và dùng được Trang web này, kể cả người chỉ dùng bàn phím, dùng trình đọc màn hình, phóng to màn hình, chế độ tương phản cao hay giảm chuyển động. Trang web hướng tới Web Content Accessibility Guidelines (WCAG) 2.2 mức AA. Đó là mục tiêu mình đang theo, không phải chứng nhận: Trang web chưa được bên thứ ba kiểm định.

**2. Những gì đã có.** Mọi trang đều dùng được chỉ bằng bàn phím: có liên kết "Bỏ qua đến nội dung", viền focus nhìn thấy rõ, và focus quay về đúng chỗ cũ khi đóng menu, ô tìm kiếm hay trình xem ảnh. Trang khai báo ngôn ngữ, dùng tiêu đề và các vùng có tên, nút chỉ có biểu tượng đều có tên. Chữ và nút đạt độ tương phản mức AA ở cả giao diện tối và sáng. Chữ phóng được tới 200% và trang tự dàn lại đến màn hình rộng 320 pixel. Hiệu ứng ngắn, không lặp, và tắt hẳn khi hệ thống của bạn yêu cầu giảm chuyển động. Không có gì tự phát: video chỉ tải sau khi bạn bấm phát. Trang tôn trọng chế độ Tương phản cao của Windows (forced colours) và thiết lập "tăng tương phản". Phần truyện có thêm thiết lập đọc: ba cỡ chữ và nền giấy, sepia hoặc tối.

**3. Cách kiểm thử.** Bằng tay: chỉ dùng bàn phím, dùng Narrator của Windows trên Edge, Chrome và Brave (Windows 11), và VoiceOver trên Safari của iPhone. Tự động: mọi thay đổi của Trang web đều được quét bằng axe-core và chạy qua các bài kiểm thử bàn phím trước khi được đưa lên, và một bài kiểm thử riêng đối chiếu mọi cặp màu với mức AA. Mình chưa tự thử: NVDA, JAWS, TalkBack và VoiceOver trên macOS. Mình tin là dùng được — nếu không, hãy báo cho mình.

**4. Hạn chế đã biết.**

- **Kiểm tra bot.** Lần truy cập đầu phải qua bước kiểm tra Cloudflare Turnstile. Thường bạn không cần làm gì, nhưng đây là thành phần của bên thứ ba mà mình không sửa được. Nếu nó chặn bạn, hãy viết cho mình, mình sẽ gửi nội dung bạn đang muốn đọc.
- **Video.** Video được nhúng từ YouTube. Phụ đề là những gì YouTube cung cấp cho từng video; mình không đăng bản chép lời.
- **Ảnh cũ.** Ảnh trong thư viện luôn có chú thích bằng cả hai ngôn ngữ. Một vài ảnh trong bài viết cũ có thể vẫn thiếu mô tả bằng chữ.
- **Mini-game ngoại tuyến.** Trò chơi nhỏ ở trang ngoại tuyến được vẽ trên canvas. Chơi được bằng phím Space, nhưng trình đọc màn hình không theo được. Đây là phần phụ, không phải nội dung.
- **Tìm kiếm.** Tìm kiếm cần JavaScript. Không có nó, mọi trang vẫn vào được từ menu và các liên kết ở chân trang.
- **Trang khác.** Các trang mình dẫn link tới (YouTube, Steam, GitHub, Discord…) nằm ngoài tầm kiểm soát của mình.

**5. Báo cho mình khi gặp rào cản.** Gửi email tới accessibility@poli0981.dev, hoặc dùng nút "Báo lỗi" ở cuối mọi trang — không cần tài khoản. Nếu bạn dùng GitHub, bạn cũng có thể mở issue theo mẫu Accessibility tại https://github.com/poli0981/poli0981-dev/issues/new/choose. Sẽ rất có ích nếu bạn cho biết trang nào, bạn đang định làm gì, điều gì đã xảy ra, và bạn dùng trình duyệt cùng công nghệ hỗ trợ nào. Bạn không cần tự tìm nguyên nhân, và không bao giờ phải nói với mình về tình trạng khuyết tật của bạn.

**6. Mình sẽ phản hồi thế nào.** Mình trả lời trong vòng 7 ngày. Rào cản khiến ai đó không đọc hay không dùng được một trang sẽ được xử lý trước. Đây là trang cá nhân do một người làm lúc rảnh, nên mình không hứa được ngày sửa cho mọi lỗi — nhưng mình sẽ nói rõ định làm gì, và cách tạm thời nếu có.

**7. Phạm vi và rà soát.** Tuyên bố này áp dụng cho poli0981.dev. Nó không bao gồm khu quản trị riêng và các trang bên thứ ba được dẫn link từ đây. Mình rà lại ít nhất mỗi năm một lần và mỗi khi giao diện thay đổi; ngày ở trên là lần rà gần nhất. Ghi chú cho người làm việc với mã nguồn nằm trong ACCESSIBILITY.md tại https://github.com/poli0981/poli0981-dev.
