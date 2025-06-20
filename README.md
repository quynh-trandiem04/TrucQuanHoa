# 📱 Phân Tích Dữ Liệu Ứng Dụng Trên Google Play Store

## 🎓 Thông tin đồ án
- **Môn học:** Trực quan hóa dữ liệu
- **Giảng viên:** TS. Lê Quang Thái
- **Nhóm thực hiện:** Nhóm 04 – Học kỳ 2, năm học 2024–2025
- **Lớp:** Tương tác dữ liệu trực quan – Nhóm 01

## 👩‍💻 Thành viên nhóm
| Họ và tên             | MSSV      | Vai trò       |
|----------------------|-----------|----------------|
| Trần Diễm Quỳnh       | 22133046 | Nhóm trưởng    |
| Phạm Quỳnh Thư        | 22133060 | Thành viên     |
| Nguyễn Thị Hồng Thơ   | 22151305 | Thành viên     |

---

## 📌 Mục tiêu dự án
- Phân tích các yếu tố ảnh hưởng đến sự thành công của ứng dụng trên Google Play Store.
- Trực quan hóa dữ liệu để khám phá mối quan hệ giữa **rating**, **số lượt tải**, **dung lượng**, **thể loại**, và **giá**.
- Xây dựng mô hình dự đoán để xác định nhóm ứng dụng tiềm năng.

---

## 📊 Tập dữ liệu
- **Nguồn:** [Google Play Store Dataset](https://github.com/krishnaik06/playstore-Dataset)
- **Số mẫu:** ~10,000 ứng dụng
- **Số thuộc tính:** 13 cột bao gồm `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Genres`, `Content Rating`, `Last Updated`, `Current Ver`, `Android Ver`

---

## 🧹 Tiền xử lý dữ liệu
- Loại bỏ giá trị thiếu và trùng lặp
- Chuẩn hóa dữ liệu số và ký tự (`Reviews`, `Price`, `Size`, `Installs`)
- Trích xuất ngày, tháng, năm từ `Last Updated`

---

## 📈 Trực quan hóa & phân tích
- Sử dụng biểu đồ cột, tròn, scatter plot, box plot và heatmap để khám phá:
  - Tác động của `Size`, `Price`, `Last Updated` đến `Rating` và `Installs`
  - Sự khác biệt giữa ứng dụng miễn phí và trả phí
  - Phân bố rating theo `Category`
  - Các xu hướng phát triển và tăng trưởng ứng dụng từ 2010–2018

---

## 🤖 Mô hình phân tích & dự đoán
- **Phân cụm K-Means**: phân loại ứng dụng theo 7 cụm dựa trên hành vi và đặc điểm kỹ thuật
- **Phân loại (Decision Tree, Random Forest)**: dự đoán khả năng thành công dựa vào rating
- **Dự báo chuỗi thời gian**: đánh giá xu hướng rating, installs, và kích thước ứng dụng

---

## 🌿 Kết luận nổi bật
- Ứng dụng **dưới 30MB** có khả năng tiếp cận và đánh giá tốt hơn
- Cập nhật thường xuyên giúp tăng **rating** và **số lượt cài đặt**
- Ứng dụng **miễn phí** chiếm >93% nhưng **trả phí** có điểm rating cao hơn
- Các **danh mục tiềm năng**: `GAME`, `COMMUNICATION`, `TOOLS`, `SOCIAL`
- Chiến lược tốt cần kết hợp **Tối ưu hóa – Cập nhật định kỳ – Trải nghiệm người dùng**

---
