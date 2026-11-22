# Ứng dụng Trí tuệ nhân tạo Tạo sinh và Công nghệ số trong Phân tích Dữ liệu Học tập Thông minh

**Tác giả:** Phạm Trọng Nguyễn  
**Đơn vị:** Trường Công nghệ Thông tin và Truyền thông – Đại học Cần Thơ  
**ORCID:** [0009-0009-4441-2115](https://orcid.org/0009-0009-4441-2115)

## 1. Giới thiệu đề tài
Dự án nghiên cứu khung kiến trúc tích hợp giữa Trí tuệ nhân tạo tạo sinh (Generative AI) và các công cụ phân tích dữ liệu hiện đại nhằm khai thác hiệu quả dữ liệu nhật ký học tập từ hệ thống LMS.

## 2. Mục tiêu
- Xây dựng quy trình xử lý, ẩn danh hóa và phân tích hành vi người học tự động.
- Đánh giá mức độ cải thiện độ chính xác dự báo kết quả học tập và khả năng phát hiện sớm sinh viên có nguy cơ rớt môn.

## 3. Phương pháp thực hiện
Quy trình gồm 4 giai đoạn: **(1) KNIME** (làm sạch & huấn luyện Decision Tree, k-Means, Linear Regression) $\rightarrow$ **(2) Looker Studio** (trực quan hóa Dashboard) $\rightarrow$ **(3) Gemini / Julius AI** (gợi ý khám phá & phân tích khảo sát) $\rightarrow$ **(4) Kiểm chứng thống kê**.

## 4. Kết quả chính
- Khung tích hợp đạt độ chính xác dự báo **89.5%** (cao hơn so với Cây quyết định đơn lẻ 82.1% và Hồi quy tuyến tính 78.4%).
- Xác định tỉ lệ nộp bài đúng hạn và mức độ truy cập tài liệu hằng tuần là hai chỉ số tác động mạnh nhất đến điểm số.

## 5. Cấu trúc thư mục
- `data/`: Dữ liệu mẫu đã được ẩn danh hóa phục vụ thử nghiệm.
- `src/`: Luồng xử lý KNIME và mã nguồn tiền xử lý dữ liệu.
- `docs/`: Bài báo khoa học toàn văn (LaTeX/PDF) và Poster khoa học A0.
- `results/`: Biểu đồ trực quan hóa và bảng tổng hợp kết quả thực nghiệm.

## 6. Giấy phép (License)
Dự án này được phát hành theo giấy phép **MIT License** – xem chi tiết tại tệp [LICENSE](./LICENSE).
