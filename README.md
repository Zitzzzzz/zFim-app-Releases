# 🎬 zFim - Kênh Phát Hành & Cập Nhật Chính Thức (Official Releases)

Kho phân phối chính thức bộ cài đặt và dịch vụ Cập nhật Tự động (OTA) cho ứng dụng xem phim đa nền tảng **zFim** (Android TV, Mobile, Windows x64, macOS Apple Silicon/Intel, iOS).

---

## 🔗 Liên Kết Tải Nhanh Cố Định Vĩnh Viễn (Permanent Latest Links)

> [!TIP]
> **Các đường dẫn dưới đây là CỐ ĐỊNH VĨNH VIỄN**. Khi có bất kỳ bản cập nhật mới nào được phát hành, hệ thống sẽ tự động chuyển hướng (302 Redirect) về tệp tin mới nhất. Bạn **KHÔNG CẦN** phải tạo lại link hay đổi mã mới cho tester!

| Nền tảng | Tệp cài đặt | Link tải cố định vĩnh viễn (Latest Release) |
| :--- | :--- | :--- |
| **Android TV / Mobile (Phổ thông)** | `app-release.apk` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-release.apk`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-release.apk) |
| **Android TV (Tối ưu TV Leanback)** | `app-tv-release.apk` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-tv-release.apk`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-tv-release.apk) |
| **Android ARM64 (Tối ưu dung lượng ~18MB)** | `app-arm64-v8a-release.apk` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-arm64-v8a-release.apk`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-arm64-v8a-release.apk) |
| **Android ARMv7 (Thiết bị 32-bit cũ)** | `app-armeabi-v7a-release.apk` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-armeabi-v7a-release.apk`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-armeabi-v7a-release.apk) |
| **Windows Desktop x64 (Bộ cài đặt Setup)** | `zFim-Setup.exe` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Setup.exe`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Setup.exe) |
| **Windows Desktop x64 (Chạy ngay Portable)** | `zFim-Portable.exe` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Portable.exe`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Portable.exe) |
| **macOS (Apple Silicon & Intel DMG)** | `zFim-macOS.dmg` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.dmg`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.dmg) |
| **macOS (Apple Silicon & Intel ZIP)** | `zFim-macOS.zip` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.zip`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.zip) |
| **iOS (TrollStore / Sideloadly / AltStore)** | `zFim-iOS.ipa` | [`https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-iOS.ipa`](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-iOS.ipa) |

---

## 📺 Hướng Dẫn Tạo Mã Tải Cố Định Bằng AFTVnews (Downloader Code)

Để phân phối cho nhóm test trên **Android TV / Fire TV / Mi Box / Chromecast** mà **chỉ cần 1 mã số duy nhất dùng mãi mãi**:

1. Truy cập vào trang web rút gọn liên kết chính thức: **[https://go.aftvnews.com/](https://go.aftvnews.com/)**
2. Dán link cố định vào ô nhập liệu:
   ```text
   https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-release.apk
   ```
   *(Hoặc link dành riêng cho TV: `https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-tv-release.apk`)*
3. Bấm **Create Short URL**.
4. Hệ thống sẽ cấp cho bạn:
   - Một đường link ngắn dạng: `https://go.aftvnews.com/XXXXX`
   - Một **mã số gồm 5-6 chữ số** (ví dụ: `74921`)
5. **Gửi mã số này cho nhóm Tester**:
   - Mở ứng dụng **Downloader** trên TV.
   - Nhập trực tiếp mã số (ví dụ: `74921`) vào thanh URL rồi bấm **Go**.
   - Downloader sẽ tự động tải phiên bản APK mới nhất về TV và hiện màn hình Cài đặt!
6. **Kể từ nay về sau**: Mỗi khi phát hành bản cập nhật mới (v0.0.91, v0.0.92...), bạn chỉ cần đẩy release lên GitHub repo này, người dùng nhập lại mã số cũ vẫn sẽ tự động tải được bản mới nhất mà bạn **không cần tạo lại link mới**!

---

## 🔄 Cấu Trúc Cập Nhật Tự Động (Universal OTA)

Ứng dụng zFim tích hợp sẵn module tự động kiểm tra bản cập nhật mỗi khi khởi động:
* **Manifest chính:** `https://raw.githubusercontent.com/Zitzzzzz/zFim-app-Releases/main/version.json`
* **CDN Tốc độ cao (jsDelivr):** `https://cdn.jsdelivr.net/gh/Zitzzzzz/zFim-app-Releases@main/version.json`
* **Kho nguồn phim mặc định:** `https://cdn.jsdelivr.net/gh/Zitzzzzz/zFim-app-Releases@main/zFim01.json`

<!-- update ping 2026-11-11T10:12:57Z -->
