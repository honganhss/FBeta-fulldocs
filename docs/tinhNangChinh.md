# Tính năng chính
## 1. **Di tản tới khu vực an toàn**
- **Mô tả:**
    - Người dùng có thể xem danh sách các khu vực an toàn.
    - Hỗ trợ bản đồ và chỉ đường đến khu vực an toàn gần nhất.
    ![Image title](assets/KhuDiTan.jpeg){ loading=lazy }
- **Admin:**
    - Quản lý thông tin khu vực an toàn: thêm, sửa, xóa.
    - Các thông tin bao gồm tên, tọa độ, sức chứa, tình trạng hiện tại.
    ![Image title](assets/CapNhatKhuDiTan.jpeg){ loading=lazy }
    ![Image title](assets/CapNhatKhuDiTan2.jpeg){ loading=lazy }
    ![Image title](assets/CapNhatKhuDiTan2.jpeg){ loading=lazy }

---

## 2. **Cung cấp tin tức**
- **Mô tả:**
    - Người dùng có thể xem tin tức cập nhật về tình hình thiên tai theo thời gian thực.
    - Tin tức phân loại theo:
        - **Vùng miền**: Bắc, Trung, Nam.
        - **Loại thiên tai**: Bão, lũ quét, động đất...
![Image title](assets/TinTuc.jpeg){ loading=lazy }
---

## 3. **Gửi thông báo đẩy**
- **Mô tả:**
    - Admin gửi thông báo đến người dùng (toàn bộ hoặc theo khu vực).
    - Nội dung thông báo:
        - Hướng dẫn di tản.
        - Thông tin cảnh báo khẩn cấp.
        - Cập nhật tình hình thiên tai.
    - Sử dụng dịch vụ **Firebase Cloud Messaging (FCM)** hoặc tương tự.
![Image title](assets/TBPush.jpg){ loading=lazy }
    - Admin
![Image title](assets/TB.jpeg){ loading=lazy }
---

## 4. **Cung cấp kiến thức thiên tai**
- **Mô tả:**
    - Cung cấp nội dung về các loại thiên tai ở Việt Nam:
        - Bão, lũ quét, hạn hán...
    - Hướng dẫn kỹ năng phòng tránh và ứng phó khẩn cấp.
    - Nội dung được tổ chức thành các mục dễ tra cứu:
        - Bài viết, hình ảnh, video.
    - Hỗ trợ chức năng tìm kiếm theo từ khóa.
![Image title](assets/kienthuc.png){ loading=lazy }
---
## 5. **Bổ sung nút SOS khẩn cấp**
- **Mô tả:**
    - Giao diện nút SOS ở tất cả các trang. 
    - Gửi yêu cầu khẩn cấp 
![Image title](assets/sos.png){ loading=lazy }
---
## 6. **Yêu cầu hỗ trợ**
- **Mô tả:**
    - Gửi yêu cầu hỗ trợ và quản lý các yêu cầu này 
![Image title](assets/YC1.jpeg){ loading=lazy }
![Image title](assets/YC2.jpeg){ loading=lazy }
![Image title](assets/YC3.jpeg){ loading=lazy }
![Image title](assets/YC4.jpeg){ loading=lazy }
![Image title](assets/YCHoTroAdmin.jpeg){ loading=lazy }

## 7. **Dự báo thời tiết theo khu vực** 
![Image title](assets/dubaothoitiet.png){ loading=lazy }

---

## Kế hoạch triển khai
1. **Phân tích yêu cầu**:
    - Thu thập và phân loại các tính năng cần thiết.
    - Xây dựng các luồng UX/UI cho từng chức năng.
2. **Phát triển backend**:
    - Cài đặt cơ sở dữ liệu để lưu trữ thông tin.
    - Triển khai API hỗ trợ giao tiếp dữ liệu.
3. **Phát triển frontend**:
    - Thiết kế giao diện thân thiện và dễ sử dụng.
    - Tích hợp bản đồ và các API cần thiết.
4. **Kiểm thử và tối ưu hóa**:
    - Thử nghiệm từng chức năng trên các thiết bị khác nhau.
    - Khắc phục lỗi và tối ưu hiệu suất.
5. **Phát hành và bảo trì**:
    - Cung cấp bản cập nhật trên các nền tảng.
    - Đảm bảo hệ thống hoạt động ổn định trong mọi tình huống.

---