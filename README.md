# zFim App Releases (Official Public Distribution)

Kênh phát hành chính thức của ứng dụng **zFim** (đa nền tảng: Android Mobile, Android TV, macOS, iOS, Windows) và kho nguồn phim đồng bộ (`zFim01.json`).

---

## 🔗 Đường dẫn tải về vĩnh viễn (Luôn trỏ về phiên bản mới nhất)

> 💡 **Lưu ý dung lượng Android TV (`app-tv-release.apk` vs bản riêng theo chip):**
> * **`app-tv-release.apk` (~52 MB)** và **`app-release.apk` (~52 MB)** là gói **Universal All-in-One** gộp đủ cả 3 kiến trúc CPU (`armeabi-v7a` + `arm64-v8a` + `x86_64`) nên dung lượng ~52 MB.
> * Nếu chọn đúng bản riêng theo chip cho TV hoặc điện thoại, dung lượng giảm hơn một nửa chỉ còn **~23 MB** (và tính năng OTA trong app từ v0.1.38+ tự động ưu tiên tải đúng bản ~23 MB này).

### 📺 Android TV (MiTV4, MiBox 3, Android TV Box)
| Gói cài đặt | Dung lượng | Phù hợp với | Link GitHub Vĩnh Viễn | Link Cloudflare Gateway (Tốc độ cao) |
| :--- | :--- | :--- | :--- | :--- |
| **TV 32-bit (MiTV4 / MiBox 3)** | **~23 MB** | Android TV 32-bit (`armeabi-v7a`, Android 6.0+) | [app-armeabi-v7a-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-armeabi-v7a-release.apk) | [/download/tv-v7a](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/tv-v7a) |
| **TV 64-bit đời mới** | **~23 MB** | Android TV 64-bit (`arm64-v8a`) | [app-arm64-v8a-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-arm64-v8a-release.apk) | [/download/tv-arm64](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/tv-arm64) |
| **TV Giả lập / x86_64** | **~24 MB** | Android TV x86_64 / Emulator | [app-x86_64-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-x86_64-release.apk) | [/download/app-x86_64-release.apk](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/app-x86_64-release.apk) |
| **TV All-in-One (Universal)** | **~52 MB** | Dùng chung mọi chip TV (khi không rõ 32/64-bit) | [app-tv-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-tv-release.apk) | [/download/tv](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/tv) |

### 📱 Android Mobile / Tablet
| Gói cài đặt | Dung lượng | Phù hợp với | Link GitHub Vĩnh Viễn | Link Cloudflare Gateway |
| :--- | :--- | :--- | :--- | :--- |
| **Android 64-bit (`arm64-v8a`)** | **~23 MB** | Hầu hết điện thoại Android hiện đại (Khuyên dùng) | [app-arm64-v8a-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-arm64-v8a-release.apk) | [/download/arm64](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/arm64) |
| **Android 32-bit (`armeabi-v7a`)** | **~23 MB** | Điện thoại / máy tính bảng đời cũ | [app-armeabi-v7a-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-armeabi-v7a-release.apk) | [/download/v7a](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/v7a) |
| **Android All-in-One (Universal)** | **~52 MB** | Gộp mọi kiến trúc | [app-release.apk](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/app-release.apk) | [/download/apk](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/apk) |

### 🖥️ Windows (64-bit)
| Gói cài đặt | Link GitHub Vĩnh Viễn (`main` / `latest`) | Link Cloudflare Gateway |
| :--- | :--- | :--- |
| **Bộ cài đặt (Setup .exe)** | [zFim-Setup.exe](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Setup.exe) · [Raw main](https://github.com/Zitzzzzz/zFim-app-Releases/raw/main/zFim-Setup.exe) | [/download/windows](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/windows) |
| **Bản Portable (ZIP giải nén chạy ngay)** | [zFim-Windows-Portable.zip](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Windows-Portable.zip) · [Raw main](https://github.com/Zitzzzzz/zFim-app-Releases/raw/main/zFim-Windows-Portable.zip) | [/download/windows-portable](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/windows-portable) |
| **Bản Portable (1-file .exe)** | [zFim-Portable.exe](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-Portable.exe) | — |

### 🍎 macOS (Apple Silicon / Universal)
| Gói cài đặt | Dung lượng | Link GitHub Vĩnh Viễn | Link Cloudflare Gateway |
| :--- | :--- | :--- | :--- |
| **macOS DMG (Kéo thả Cài đặt)** | ~23 MB | [zFim-macOS.dmg](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.dmg) | [/download/mac](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/mac) |
| **macOS ZIP (.app)** | ~20 MB | [zFim-macOS.zip](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-macOS.zip) | — |

### 📱 iOS / iPadOS (TrollStore / AltStore / SideStore / Simulator)
| Gói cài đặt | Dung lượng | Link GitHub Vĩnh Viễn | Link Cloudflare Gateway |
| :--- | :--- | :--- | :--- |
| **iOS Device IPA (`arm64`)** | ~18 MB | [zFim-iOS.ipa](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-iOS.ipa) | [/download/ios](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/ios) |
| **iOS Simulator IPA** | ~15 MB | [zFim-iOS-Simulator.ipa](https://github.com/Zitzzzzz/zFim-app-Releases/releases/latest/download/zFim-iOS-Simulator.ipa) | [/download/ios-sim](https://zfim-edge-telemetry.vietph-eng.workers.dev/download/ios-sim) |

---

## 🔄 Kênh OTA & Kho nguồn phim (`zFim01.json`)
* **Tự động nhận diện thiết bị (Auto-Detect):** `https://zfim-edge-telemetry.vietph-eng.workers.dev/download`
* **Manifest OTA chính:** `https://raw.githubusercontent.com/Zitzzzzz/zFim-app-Releases/main/version.json`
* **CDN Tốc độ cao (jsDelivr):** `https://cdn.jsdelivr.net/gh/Zitzzzzz/zFim-app-Releases@main/version.json`
* **Kho nguồn phim mặc định (`zFim01`):** `https://cdn.jsdelivr.net/gh/Zitzzzzz/zFim-app-Releases@main/zFim01.json`
