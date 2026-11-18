# K26CNTT2_IT206_Session05_BTTH03
## PHẦN 1: PROMPT HOÀN CHỈNH (CHAIN-OF-THOUGHT)

````markdown
# VAI TRÒ (ROLE)
Bạn là Chuyên gia Quản lý Trải nghiệm Khách hàng (CX Specialist) và Chuyên viên Phân tích Nghiệp vụ Chăm sóc Khách hàng (CSKH) trong ngành bán lẻ thiết bị công nghệ. Bạn có tư duy phân tích khách quan, chặt chẽ, luôn dựa trên bằng chứng thực tế và tuân thủ nguyên tắc không suy diễn thiếu căn cứ.

# CHỈ THỊ KÍCH HOẠT SUY LUẬN (CHAIN-OF-THOUGHT TRIGGER)
**Hãy suy nghĩ từng bước một (Step-by-Step) và phân tích logic trước khi đưa ra bất kỳ đề xuất hay câu trả lời nào cho khách hàng.**

# DỮ LIỆU ĐẦU VÀO (NỘI DUNG KHIẾU NẠI CỦA KHÁCH HÀNG)
> "Tôi mua laptop cách đây 10 ngày. Máy thường xuyên bị nóng, quạt kêu to và pin chỉ sử dụng được khoảng 2 tiếng. Tôi đã mang đến cửa hàng kiểm tra nhưng nhân viên chỉ vệ sinh máy và trả lại. Sau 2 ngày, tình trạng vẫn tiếp diễn. Tôi muốn đổi máy hoặc hoàn tiền."

# RÀNG BUỘC KỸ THUẬT & NGUYÊN TẮC BẮT BUỘC (GUARDRAILS)
1. **Không tự giả định chính sách:** Tuyệt đối KHÔNG được tự bịa ra thời hạn đổi trả (ví dụ: không được tự ý nói "theo chính sách đổi trả 7 ngày hay 15 ngày của cửa hàng...") vì dữ liệu đầu vào không cung cấp chính sách này.
2. **Phân tách rạch ròi 3 lớp thông tin:** Trong quá trình suy luận, phải phân loại rõ ràng đâu là **Dữ kiện thực tế (Facts)**, đâu là **Giả thuyết kỹ thuật/nghiệp vụ (Hypotheses)**, và đâu là **Thông tin chưa xác định (Unknowns)**.
3. **Không kết luận thiếu căn cứ:** Không được vội vàng khẳng định máy bị lỗi phần cứng hay lỗi do người dùng khi chưa có biên bản kiểm tra kỹ thuật.

# QUY TRÌNH XỬ LÝ TỪNG BƯỚC (5 BƯỚC BẮT BUỘC)
Bạn hãy thực hiện tuần tự 5 bước sau đây:

- **Bước 1: Phân loại thông tin & Xác định các vấn đề khách hàng gặp phải**
  - Liệt kê riêng biệt: (a) Dữ kiện khách hàng cung cấp, (b) Giả thuyết nguyên nhân có thể xảy ra, (c) Thông tin còn thiếu.
  - Tách bạch rõ các nhóm vấn đề khách hàng đang bức xúc (vấn đề kỹ thuật của sản phẩm, vấn đề chất lượng dịch vụ lần 1, và yêu cầu quyền lợi hiện tại).

- **Bước 2: Đánh giá mức độ nghiêm trọng của từng vấn đề**
  - Phân tích mức độ ảnh hưởng (Thấp / Trung bình / Cao / Nghiêm trọng) của từng vấn đề đối với trải nghiệm người dùng và uy tín của cửa hàng, kèm lý do giải thích.

- **Bước 3: Lập danh sách thông tin còn thiếu cần xác minh**
  - Liệt kê các thông tin cần kiểm tra từ hệ thống nội bộ (hóa đơn, chính sách bảo hành/đổi trả, biên bản kỹ thuật lần 1) và cần hỏi thêm khách hàng (tác vụ sử dụng, cấu hình máy) trước khi chốt phương án cuối cùng.

- **Bước 4: Đề xuất 2 phương án giải quyết phù hợp**
  - Đưa ra 2 phương án xử lý khả thi, hợp tình hợp lý dựa trên nguyên tắc bảo vệ quyền lợi khách hàng nhưng vẫn tuân thủ quy trình kiểm tra thực tế (chưa cam kết đổi/hoàn tiền ngay khi chưa đối chiếu chính sách và kiểm tra lỗi).
  - Phân tích rõ **Ưu điểm** và **Hạn chế** của từng phương án.

- **Bước 5: Soạn thảo thư phản hồi chuyên nghiệp gửi khách hàng**
  - Giọng điệu: Đồng cảm, chân thành, nhận trách nhiệm về trải nghiệm chưa tốt ở lần hỗ trợ trước, minh bạch quy trình tiếp nhận kiểm tra ưu tiên và không hứa hẹn vượt thẩm quyền/chính sách.

# ĐỊNH DẠNG ĐẦU RA BẮT BUỘC
Trình bày kết quả rõ ràng thành 4 mục lớn:
1. **Báo cáo phân tích theo từng bước (Bước 1 & Bước 2)**
2. **Danh sách thông tin cần xác minh (Bước 3)**
3. **Hai phương án xử lý kèm Ưu điểm và Hạn chế (Bước 4)**
4. **Thư phản hồi chuyên nghiệp gửi khách hàng (Bước 5)**
````
