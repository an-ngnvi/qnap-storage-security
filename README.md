# 💾 Thiết Bị Lưu Trữ và Backup QNAP: Bảo Mật & Phòng Chống Ransomware

**Đồ án môn học:** An ninh mạng  
**Học kỳ - Năm học:** Học kỳ 2 (2025 - 2026)  
**Trường:** Đại học Công nghệ Kỹ thuật TP.HCM (HCMUTE)  
**GVHD:** Th.S Nguyễn Thị Thanh Vân

---

## 📝 Tổng quan đề tài

Đề tài nghiên cứu, cấu hình và thực nghiệm toàn diện hệ thống lưu trữ mạng **QNAP NAS (253B)** chạy hệ điều hành **QTS**, tập trung vào bảo mật dữ liệu, phòng chống Ransomware và giám sát hệ thống. Mô hình triển khai mô phỏng thực tế theo kiến trúc **DC – DR (Data Center – Disaster Recovery)** kết nối qua VPN IPSec.

## 🔬 Nội dung thực nghiệm (13 Lab)

| Lab | Nội dung |
|---|---|
| 1 | Truy cập và làm quen giao diện quản lý QTS |
| 2 | Tạo phân vùng lưu trữ RAID 1, Volume, Shared Folder |
| 3 | Phân quyền người dùng và nhóm truy cập |
| 4 | Backup dữ liệu liên-site (DC → DR) qua VPN IPSec bằng NetBak Replicator |
| 5 | Bảo vệ dữ liệu trước Ransomware bằng Snapshot (phục hồi tức thì) |
| 6 | Chống Brute Force SSH bằng Access Protection + kiểm thử với Hydra |
| 7 | Giám sát QNAP qua SNMP với Zabbix (CPU, HDD, băng thông) |
| 8 | Tối ưu hóa hiệu suất lưu trữ với Qboost |
| 9 | Tăng cường bảo mật với Security Counselor và QuFirewall |
| 10 | Đồng bộ dữ liệu máy tính lên NAS bằng Qsync Client |
| 11 | Quét và phát hiện lỗ hổng bảo mật, Malware Remover |
| 12 | Thiết lập hệ thống cảnh báo sự cố tự động (Incident Response Alerting) qua Gmail SMTP |
| 13 | Cấu hình myQNAPcloud, DDNS và kiểm soát truy cập NAS từ Internet |

## 🛠️ Công nghệ & Công cụ sử dụng

**Phần cứng:**
- Thiết bị: QNAP NAS 253B (hệ điều hành QTS)

**Phần mềm & Giải pháp:**
- Backup: NetBak Replicator, HBS 3 (Hybrid Backup Sync), Snapshot
- Bảo mật: Security Counselor, QuFirewall, Access Protection, Malware Remover
- Giám sát: Zabbix Server, SNMP, Notification Center
- Đồng bộ: Qsync Client, myQNAPcloud, DDNS
- Tối ưu: Qboost

**Công cụ kiểm thử tấn công:**
- Hydra (kiểm thử Brute Force SSH)

## 📁 Cấu trúc thư mục

```
qnap-storage-security/
└── docs/
    └── report.pdf      # Báo cáo đầy đủ 13 Lab thực nghiệm
```

> Đề tài thuần nghiên cứu và thực nghiệm trên thiết bị thật, không có source code đi kèm.

## 📊 Tài liệu dự án

- 📜 **[Báo cáo môn học (PDF)](docs/report.pdf)**

---
