# Toyota CAN Bus Real-Time Digital Dashboard

Hệ thống Telematics & Cockpit Dashboard thu thập, giải mã dữ liệu CAN Bus xe Toyota thực tế và hiển thị lên giao diện Web theo thời gian thực.

## 🎥 Demo Thử Nghiệm Thực Tế Trên Xe

https://github.com/pat2k3/dashboard/raw/main/dashboard.mp4

---

### 🛠️ Kỹ thuật nổi bật:
* **Protocol & Hardware:** PCAN-USB (500 kbps), OBD-II Active Polling (80ms), Passive CAN Sniffing.
* **Decoding:** Giải mã tín hiệu Motorola Big Endian (Speed, RPM, Wheel Speeds, Steering Angle, Gear State...).
* **Backend & Frontend:** Python Flask Multithreading Server, REST API, Web SVG Gauge Dashboard với thuật toán Exponential Smoothing Filter.
