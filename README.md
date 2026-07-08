# OSClonePro — Chuyển Windows sang ổ cứng mới, miễn phí

Phần mềm tiếng Việt giúp **chuyển toàn bộ Windows + phần mềm + dữ liệu** từ ổ cứng này sang ổ cứng khác mà không cần cài lại Windows. Giao diện đơn giản, ngôn ngữ dễ hiểu, ai cũng dùng được.

> ⚠️ **ĐỌC KỸ [MIỄN TRỪ TRÁCH NHIỆM](DISCLAIMER.md) TRƯỚC KHI DÙNG.** Phần mềm sẽ XÓA SẠCH ổ nhận dữ liệu — chọn nhầm ổ sẽ mất dữ liệu không thể khôi phục. Phần mềm KHÔNG có tính năng sao lưu.

## 📥 Tải về

Tải file `OSClonePro.exe` mới nhất tại mục **[Releases](../../releases)** — chỉ 1 file duy nhất, không cần cài đặt, chạy trực tiếp.

> Lưu ý: Windows SmartScreen có thể cảnh báo vì phần mềm chưa mua chứng chỉ ký số. Bấm **More info → Run anyway** để chạy.

## ✨ Hai chế độ

### 🖥️ 1. Nhân bản Windows của chính máy đang dùng
Chuyển Windows đang chạy trên máy sang ổ SSD/HDD cắm ngoài qua USB. Dùng khi nâng cấp ổ cứng cho chính máy mình.

### 🔌 2. Chuyển từ Ổ CŨ (máy khác) sang Ổ MỚI
Dùng một máy tính làm trung gian: tháo ổ Windows từ máy cũ + ổ mới mua, cắm cả hai vào máy trung gian qua đầu đọc USB, phần mềm chuyển toàn bộ từ ổ cũ sang ổ mới. Sau đó lắp ổ mới vào:
- **Máy cũ** (nâng cấp ổ) — chạy ngay, không mất kích hoạt Windows.
- **Máy khác/laptop mới** — vẫn khởi động được nhờ chế độ tương thích phần cứng (Windows To Go); có hướng dẫn chi tiết ngay trong phần mềm.

## ✅ Tính năng an toàn

- Tự tìm phân vùng Windows trên ổ cũ (không cần biết ổ tên gì)
- Hiện rõ loại kết nối (USB/SATA/NVMe) + cảnh báo nếu chọn nhầm ổ gắn trong
- Kiểm tra lại danh tính ổ ngay trước khi ghi (chống rút/cắm nhầm)
- Phát hiện ổ khóa BitLocker, Windows quá cũ không boot được UEFI
- Cảnh báo nếu ổ cũ còn phân vùng dữ liệu khác không được chuyển
- Ổ lấy dữ liệu **chỉ được đọc** — không bị thay đổi gì
- Tự đặt lại bảng ký tự ổ đĩa để ổ mới luôn nhận đúng tên C: khi khởi động

## 💻 Yêu cầu

- Windows 10/11 64-bit, quyền Administrator
- Ổ cũ chứa Windows 64-bit chuẩn UEFI (phần mềm tự kiểm tra và báo nếu không đạt)
- Đầu đọc/dock USB đúng chuẩn ổ (SATA hoặc M.2 NVMe)

## 📄 Giấy phép

Phần mềm miễn phí, phát hành dạng đóng (closed-source). Xem [DISCLAIMER.md](DISCLAIMER.md) để biết điều khoản sử dụng và miễn trừ trách nhiệm đầy đủ.
