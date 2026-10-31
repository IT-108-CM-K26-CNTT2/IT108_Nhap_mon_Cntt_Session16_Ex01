# Bài 1: Hệ thống Quản lý Tài liệu Dự án Doanh nghiệp

## 3. Yêu cầu nghiệp vụ
- Tải Google Drive for Desktop, chọn thư mục trên ổ D và bật **Sync with Google Drive**.
- `Ctrl + S` lưu file trên máy, biểu tượng **tích xanh** hiện ra là file đã lên Cloud.
- Xóa nhầm nội dung: dùng **Version History** để khôi phục chỉ với 1 cú nhấp chuột.

## 4. Ràng buộc và bẫy dữ liệu
- **Mất Internet đột ngột:** `Ctrl + S` vẫn ghi đè xuống ổ SSD, công việc không bị gián đoạn.
- **Sập nguồn giữa chừng:** bật **Auto-Save** trong phần mềm dựng hình 3D.

## 5. Yêu cầu đầu ra

### Sơ đồ luồng dữ liệu
```
LOCAL (ổ D: chọn file → chỉnh sửa → Ctrl + S)
        ▼
AUTO SYNC (Google Drive for Desktop, Sync bật, tích xanh = đã lên Cloud)
        ▼
CLOUD (Google Drive, tự động lưu Version History)
```

### Xung đột phiên bản (File Version Conflict)
- **Nguyên nhân:** hai người cùng sửa một file lúc ngoại tuyến, hoặc cùng đẩy hai bản khác nhau cùng lúc.
- **Xử lý:** Google Drive không ghi đè. Trưởng nhóm hoặc Designer đối chiếu hai file, hợp nhất nội dung rồi xóa bản dư thừa.

## Quy trình 3 bước thiết lập cho Designer
1. **Cài đặt và cấu hình Mirror files:** cài Google Drive for Desktop, đăng nhập email dự án, vào Settings → Preferences → Google Drive → chọn **Mirror files** (giữ bản sao trên SSD và Cloud).
2. **Thiết lập thư mục dự án:** tạo thư mục trên ổ cá nhân, chọn làm nơi lưu và xuất file trong phần mềm 3D. Chỉ cần `Ctrl + S` là file tự đồng bộ.
3. **Kiểm soát đồng bộ và chia sẻ:** theo dõi dấu tích xanh, chuột phải file → Google Drive → **Copy link to share** để gửi nhóm, không gửi file qua Zalo.
