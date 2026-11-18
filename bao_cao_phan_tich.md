# 1. Báo cáo phân tích theo từng bước

## Bước 1: Phân loại thông tin & Xác định các vấn đề của khách hàng

* **Phân tách lớp thông tin:**
  * **Dữ kiện thực tế (Facts):**
    * Thời điểm mua máy: Cách đây 10 ngày.
    * Triệu chứng khách hàng mô tả: Máy thường xuyên nóng, quạt kêu to, thời lượng pin thực tế khoảng 2 tiếng.
    * Lịch sử xử lý lần 1: Khách đã mang máy đến cửa hàng; nhân viên chỉ thực hiện vệ sinh máy và trả lại.
    * Diễn biến tiếp theo: Sau 2 ngày kể từ lần kiểm tra đầu, tình trạng cũ vẫn lặp lại.
    * Yêu cầu hiện tại của khách hàng: Muốn đổi máy mới hoặc hoàn tiền.
  * **Giả thuyết nguyên nhân (Hypotheses):**
    * *Giả thuyết 1 (Phần cứng/Phần mềm):* Máy có thể gặp lỗi tản nhiệt (khô keo tản nhiệt, lỗi quạt), lỗi cell pin, hoặc xung đột phần mềm/ứng dụng chạy ngầm gây ngốn tài nguyên CPU.
    * *Giả thuyết 2 (Nhu cầu sử dụng):* Khách hàng có thể đang sử dụng các tác vụ nặng (render video, chơi game đồ họa cao) trên một dòng laptop văn phòng mỏng nhẹ (vốn có pin thực tế thấp và dễ nóng khi tải nặng).
    * *Giả thuyết 3 (Quy trình nội bộ):* Nhân viên kỹ thuật lần 1 có thể đã kiểm tra sơ sài, chưa chạy bài test tải nặng (stress test) hoặc chưa giải thích rõ nguyên nhân cho khách hàng.
  * **Thông tin chưa xác định (Unknowns):**
    * Mã sản phẩm/cấu hình cụ thể của laptop và thông số pin tiêu chuẩn của nhà sản xuất.
    * Chính sách đổi trả và điều kiện hoàn tiền cụ thể của cửa hàng (số ngày áp dụng, điều kiện lỗi phần cứng...).
    * Biên bản tiếp nhận và kết quả kiểm tra kỹ thuật trong lần khách mang máy đến trước đó.
    * Môi trường và thói quen sử dụng máy của khách hàng (cắm sạc hay dùng pin, bật chế độ hiệu năng nào, chạy ứng dụng gì).

* **Các vấn đề cốt lõi khách hàng đang gặp phải:**
  1. **Vấn đề hiệu năng & phần cứng sản phẩm:** Máy nóng bất thường, tiếng ồn quạt lớn và thời lượng pin ngắn (2 giờ) trên một thiết bị mới mua 10 ngày.
  2. **Vấn đề chất lượng dịch vụ hậu mãi (Lần 1):** Việc chỉ vệ sinh một chiếc máy mới mua chưa đầy 10 ngày mà không xử lý dứt điểm lỗi khiến khách hàng cảm thấy không được tôn trọng và mất niềm tin.
  3. **Xung đột kỳ vọng về quyền lợi:** Khách hàng yêu cầu giải pháp cao nhất (đổi máy/hoàn tiền) ngay lập tức do trải nghiệm tệ lặp lại lần thứ hai.

## Bước 2: Đánh giá mức độ nghiêm trọng của từng vấn đề

| Vấn đề | Mức độ nghiêm trọng | Giải thích cơ sở đánh giá |
| :--- | :---: | :--- |
| **1. Trải nghiệm dịch vụ lần 1 kém (chỉ vệ sinh máy mới)** | **Nghiêm trọng** | Đây là nguyên nhân chính đẩy sự việc thành khiếu nại đòi hoàn tiền. Máy mới 10 ngày hiếm khi nóng do bụi bẩn; cách xử lý qua loa làm khách hàng mất niềm tin vào năng lực kỹ thuật của cửa hàng. |
| **2. Lỗi nhiệt độ, tiếng ồn quạt & pin 2 tiếng** | **Cao** | Ảnh hưởng trực tiếp đến công việc hàng ngày và tính di động của laptop. Nếu là lỗi phần cứng từ nhà sản xuất, đây là cơ sở quan trọng để xét duyệt đổi trả. |
| **3. Yêu cầu đổi máy hoặc hoàn tiền** | **Cao** | Nếu không khéo léo tiếp nhận và xác minh minh bạch, cửa hàng có nguy cơ mất khách hàng hoặc gặp khủng hoảng truyền thông (đánh giá xấu trên mạng xã hội). |
