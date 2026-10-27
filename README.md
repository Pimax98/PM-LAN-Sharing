<div align="center">

# 🚀 PIMAX STUDIO - LAN SHARING MANAGER
### Phần mềm quản lý mạng LAN và chia sẻ ổ cứng siêu tốc (D - Z) trên Windows

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)]()
[![Performance](https://img.shields.io/badge/Speed-%3C%200.5s-success?style=flat-square&logo=lightning)]()
[![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Stable%20%7C%20Production-brightgreen?style=flat-square)]()

*Công cụ tối ưu hóa mạng nội bộ và chia sẻ ổ cứng dữ liệu cho Studio và cá nhân, chạy trực tiếp không cần cài đặt rườm rà.*

</div>

---

## 📸 Giao diện phần mềm

<div align="center">
 <img width="890" height="654" alt="Screenshot 2026-10-27 135323" src="https://github.com/user-attachments/assets/93ab0a31-2a9b-4f03-88cc-a2e4bff6291b" />

</div>

---

## ✨ Tính năng nổi bật

* **⚡ Siêu tốc độ (&lt; 0.5 giây):** Quét toàn bộ hệ thống ổ đĩa từ `D` đến `Z` (bỏ qua ổ hệ thống `C`) chớp nhoáng nhờ cơ chế thuần túy .NET `[System.IO.DriveInfo]`.
* **🏷️ Giữ nguyên tên gốc thông minh:** Tự động nhận diện Volume Label của từng ổ đĩa và định dạng tên chia sẻ chuẩn xác theo cấu trúc `[ D - Tên ổ ]` (Ví dụ: `D - PHAN MEM`, `E - DU LIEU ANH`).
* **🛡️ Phân quyền chuẩn xác (Bỏ qua lỗi truy cập):** Tự động thiết lập quyền truy cập mạng và mở khóa bảo mật NTFS cục bộ (`(NP)F`) giúp máy tính khác trong mạng LAN truy cập mượt mà, triệt để lỗi *You do not have permission*.
* **🖥️ Giao diện Desktop trực quan (GUI):** Thiết kế Dark Mode hiện đại, tích hợp bảng điều khiển nút bấm nhanh từ `[1]` đến `[6]` kèm theo khung nhật ký (Real-time Log) hiển thị thời gian thực.
* **🔄 Tự động làm mới Explorer:** Tự động kích hoạt lệnh Refresh Windows Explorer để icon mạng hiển thị ngay lập tức mà không cần bấm F5 thủ công.

---

## 🎛️ Chi tiết các chức năng trên giao diện

| Phím / Nút | Chức năng chi tiết |
| :---: | :---|
| **[ 1 ]** | **Fix lỗi mạng và phân quyền:** Cấu hình mạng sang chế độ Private, bật Network Discovery, File & Printer Sharing và kích hoạt tài khoản Guest (Chạy 1 lần duy nhất). |
| **[ 2 ]** | **Share toàn bộ ổ cứng (D - Z):** Quét và chia sẻ tất cả các ổ dữ liệu hiện có trong máy, giữ nguyên tên gốc với tốc độ chưa tới 0.5 giây. |
| **[ 3 ]** | **Share 1 ổ cứng bất kỳ:** Cho phép chọn riêng lẻ một ký tự ổ đĩa muốn mở chia sẻ trong mạng LAN. |
| **[ 4 ]** | **Ngắt share toàn bộ ổ cứng:** Thu hồi quyền chia sẻ, xóa sạch toàn bộ icon mạng ngay lập tức. |
| **[ 5 ]** | **Ngắt share 1 ổ cứng bất kỳ:** Đóng chia sẻ cho một ổ đĩa cụ thể theo lựa chọn. |
| **[ 6 ]** | **Mở bảng Network:** Truy cập nhanh cửa sổ Windows Network để kiểm tra các máy tính đang kết nối trong cùng mạng LAN/Wi-Fi. |

---

## 🛠️ Yêu cầu hệ thống & Hướng dẫn sử dụng

1. **Hệ điều hành:** Windows 10 hoặc Windows 11.
2. **Quyền hạn:** Do phần mềm can thiệp sâu vào thiết lập mạng và phân quyền hệ thống (`net share`, `Firewall`), bạn **bắt buộc phải chạy ứng dụng với quyền Administrator** (Chuột phải chọn *Run as administrator*).
3. **Mạng LAN:** 2 máy tính cần kết nối chung một mạng Wi-Fi, mạng dây LAN nội bộ hoặc thông qua mạng LAN ảo bảo mật (như Tailscale/ZeroTier nếu ở các dải mạng khác nhau).

---

## 📦 Download & Cài đặt

1. Tải file thực thi mới nhất `PimaxLanManager.exe` tại mục [Releases](../../releases).
2. Click chuột phải chọn **Run as administrator**.
3. Bấm nút **[1]** để fix mạng lần đầu, sau đó bấm **[2]** để chia sẻ toàn bộ ổ cứng là xong!

---

## 👨‍💻 Tác giả

* **Pimax Studio** - Base in Tam Kỳ, Quảng Nam, Việt Nam.
* Chuyên gia thiết kế nội thất, sáng tạo nội dung & phát triển giải pháp phần mềm tối ưu workflow.

---
<div align="center">
  <i>Copyright © 2026 Pimax Studio. All rights reserved.</i>
</div>
