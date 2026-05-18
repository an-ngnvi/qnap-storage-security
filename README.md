# 💾 QNAP NAS Storage Security & Ransomware Defense Strategies

**Đồ án/Đề tài môn học:** Tấn công mạng  
**Học kỳ - Năm học:** Học kỳ 2 (2025 - 2026) | Năm 3  
**Trường:** Đại học Sư phạm Kỹ thuật TP.HCM (HCMUTE)

---

## 📝 Tổng quan đề tài
Kho lưu trữ này chứa tài liệu nghiên cứu chi tiết và kịch bản thực nghiệm về đề tài **"Thiết Bị Lưu Trữ và Backup QNAP: Phân tích bề mặt tấn công và giải pháp phòng chống"**.

Thiết bị lưu trữ mạng (NAS) QNAP là hạ tầng cốt lõi lưu trữ và sao lưu dữ liệu cho nhiều doanh nghiệp. Tuy nhiên, đây cũng là mục tiêu tấn công hàng đầu của các chủng loại mã độc tống tiền (Ransomware). Nghiên cứu này tập trung khảo sát các vec-tơ tấn công phổ biến nhắm vào hệ điều hành QTS, phân tích các lỗ hổng bảo mật nghiêm trọng đã từng bị khai thác, từ đó xây dựng mô hình phòng thủ chủ động và cấu hình chiến lược sao lưu an toàn tuyệt đối cho dữ liệu doanh nghiệp.

### Các nội dung nghiên cứu cốt lõi:
- **Phân tích bề mặt tấn công QNAP:** Nghiên cứu cách thức kẻ tấn công dò quét (Reconnaissance), khai thác các dịch vụ công khai (UPnP, SSH, Web Admin) và các lỗ hổng bảo mật phổ biến (SQL Injection, Command Injection, Authentication Bypass) trên thiết bị lưu trữ.
- **Khảo sát mã độc tống tiền (Ransomware Analysis):** Phân tích cơ chế hoạt động của các chiến dịch tấn công ransomware kinh điển nhắm vào QNAP (như *Qlocker*, *DeadBolt*) để mã hóa tập tin bẻ khóa và đòi tiền chuộc bằng tiền điện tử.
- **Chiến lược Backup chống Ransomware (Hardening & DR):** Thiết lập các giải pháp bảo mật và quy trình khôi phục dữ liệu toàn diện:
  - Cấu hình **QTS Smart Shield**, chặn truy cập IP bất thường và tắt các dịch vụ không cần thiết.
  - Triển khai công nghệ **Snapshot (Bản sao thời điểm)** cô lập, đảm bảo dữ liệu có thể khôi phục ngay cả khi hệ thống tệp chính bị mã hóa.
  - Áp dụng chiến lược sao lưu **3-2-1** thông qua ứng dụng Hybrid Backup Sync (HBS 3) để đồng bộ dữ liệu an toàn sang các nền tảng đám mây hoặc thiết bị NAS từ xa.

## 🛠️ Công nghệ & Mô hình nghiên cứu
- **Hệ thống khảo sát:** QNAP NAS (Hệ điều hành QTS / QuTS hero).
- **Giải pháp bảo mật:** QNAP Snapshot, HBS 3 (Hybrid Backup Sync), Malware Remover, Security Counselor.
- **Nền tảng quản lý:** Git & GitHub.

## 📊 Tài liệu nghiên cứu chi tiết
Toàn bộ nội dung phân tích lỗ hổng, hướng dẫn cấu hình thiết bị an toàn và kịch bản thiết lập hệ thống dự phòng giảm thiểu rủi ro được trình bày chi tiết trong file báo cáo PDF:  
👉 **[Đọc báo cáo nghiên cứu bảo mật QNAP tại đây (docs/report.pdf)](docs/report.pdf)**

---

## 👥 Sinh viên thực hiện
- **Họ và tên:** Nguyễn Văn An  
- **Mã số sinh viên:** [Điền MSSV của bạn vào đây]