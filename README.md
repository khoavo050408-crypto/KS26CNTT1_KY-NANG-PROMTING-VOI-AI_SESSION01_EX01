**BƯỚC 1: PHÂN TÍCH INPUT VÀ OUTPUT**

Áp dụng tư duy "Phân tích trước - Ra lệnh sau", các thành phần dữ liệu đầu vào và đầu ra được xác định cụ thể như sau:

**1. Input (Đầu vào cần cung cấp cho AI):**

**Đối tượng so sánh: **iPhone 16 Pro Max và Samsung Galaxy S24 Ultra.

**Tiêu chí kỹ thuật trọng tâm: **Dung lượng pin (thời lượng phát video/sử dụng thực tế, công suất sạc) và hệ thống camera (độ phân giải camera chính, ống kính tele/tiềm vọng, khả năng zoom).

**Nguồn dữ liệu bắt buộc: **Trang chủ chính thức của Apple và Samsung (hoặc thông số kỹ thuật chuẩn hãng).

**2. Output (Đầu ra mong muốn):**

**Phần 1 (Bảng thông số): **Bảng ngang so sánh trực quan các thông số kỹ thuật (Dung lượng pin, sạc, camera chính, camera tele, khả năng zoom).

**Phần 2 (Điểm nhấn sản phẩm): **Liệt kê 2 điểm mạnh lớn nhất của từng dòng máy dựa trên thông số kỹ thuật.

**Điều kiện ràng buộc (Anti-hallucination): **Nếu thiếu dữ liệu hoặc không tìm thấy nguồn chính thống, AI bắt buộc phải ghi chữ "Chưa xác thực" thay vì tự suy đoán hay bịa đặt số liệu.

**BƯỚC 2: VIẾT PROMPT THEO KHUNG CREATE**** (nguồn chatgpt)**

Dưới đây là cấu trúc Prompt hoàn chỉnh được thiết kế theo 6 thành phần của khung CREATE:

| **[Context]** Bạn là một chuyên gia đánh giá và phân tích công nghệ di động cao cấp. Khách hàng đang cần một bài viết ngắn gọn, chính xác tuyệt đối về thông số kỹ thuật giữa hai dòng flagship là iPhone 16 Pro Max và Samsung Galaxy S24 Ultra để xuất bản cho bản tin công nghệ. **[Request]** Nhiệm vụ của bạn là trích xuất và so sánh chính xác dung lượng pin (thời lượng sử dụng/sạc) và hệ thống camera của iPhone 16 Pro Max và Samsung Galaxy S24 Ultra từ nguồn dữ liệu chính thống của hãng. **[Explanation]** Việc đảm bảo độ chính xác 100% là cực kỳ quan trọng vì bài viết phục vụ cho người tiêu dùng. Bạn phải tuyệt đối tránh việc tự suy đoán hay bịa đặt số liệu kỹ thuật (như dung lượng pin hay thông số thấu kính). Nếu thông số nào không tìm thấy từ nguồn chính thống, hãy điền chính xác cụm từ "Chưa xác thực". **[Action]** Hãy thực hiện theo các bước sau: 1. Trích xuất thông số kỹ thuật chính xác của iPhone 16 Pro Max và Samsung Galaxy S24 Ultra. 2. Trình bày kết quả so sánh dưới dạng một bảng ngang rõ ràng với các cột: Tiêu chí kỹ thuật, iPhone 16 Pro Max, Samsung Galaxy S24 Ultra. 3. Liệt kê rõ ràng 2 điểm mạnh lớn nhất của từng dòng máy ở ngay bên dưới bảng. **[Tone]** Khách quan, chuyên nghiệp, súc tích, mang phong cách báo chí công nghệ. **[Extras]** - Ràng buộc dữ liệu: Cấm tuyệt đối bịa đặt thông số. Nếu không chắc chắn hoặc thiếu dữ liệu, bắt buộc phải ghi rõ "Chưa xác thực". - Định dạng: Trình bày sạch sẽ, dễ đọc, không kèm theo các lời dẫn dài dòng thừa thãi trước và sau bảng. |
| --- |

**BƯỚC 3: KẾT QUẢ CHẠY THỬ PROMPT**

**Bảng so sánh thông số kỹ thuật: iPhone 16 Pro Max vs. Samsung Galaxy S24 Ultra**

| **Tiêu chí kỹ thuật** | **iPhone 16 Pro Max** | **Samsung Galaxy S24 Ultra** |
| --- | --- | --- |
| **Dung lượng Pin / Thời lượng** | Lên đến 33 giờ phát video (Chưa xác thực dung lượng mAh chính xác từ Apple) | 5.000 mAh (Tiêu chuẩn) / Lên đến 30 giờ phát video |
| **Công suất Sạc nhanh** | Sạc đầy 50% trong khoảng 30 phút với bộ chuyển đổi 20W trở lên (hỗ trợ MagSafe/Qi2) | Sạc nhanh 65% trong khoảng 30 phút với củ sạc 45W |
| **Camera Chính (Wide)** | 48 MP, khẩu độ f/1.78, chống rung dịch chuyển cảm biến thế hệ thứ 2 | 200 MP, khẩu độ f/1.7, chống rung quang học OIS |
| **Camera Telephoto** | 12 MP, tiêu cự 120mm, zoom quang học 5x, thiết kế lăng kính tứ giác | 50 MP (zoom quang 5x) và 10 MP (zoom quang 3x) |
| **Khả năng Zoom tối đa** | Zoom quang học 5x, Zoom kỹ thuật số lên đến 25x | Zoom quang học 5x, Space Zoom kỹ thuật số lên đến 100x |

**2 điểm mạnh lớn nhất của từng dòng máy:**

**• iPhone 16 Pro Max:**

**1. Tối ưu hóa thời lượng pin xuất sắc: **Nhờ sự kết hợp giữa chip Apple Silicon tiết kiệm điện và hệ điều hành iOS, thời gian phát video thực tế đạt mức rất cao trong phân khúc.

**2. Hệ thống quay chụp điện ảnh chuyên nghiệp: **Khả năng quay video chuẩn điện ảnh, hỗ trợ định dạng ProRes, Log cùng camera tele 5x sắc nét, đáp ứng tối đa cho nhà sáng tạo nội dung.

**• Samsung Galaxy S24 Ultra:**

**1. Camera độ phân giải cực cao ****&**** Zoom quang học đa dạng: **Cảm biến chính 200MP cùng hệ thống ống kính kép tele (3x và 5x) mang lại khả năng chụp chi tiết cực tốt và tính năng Space Zoom 100x độc đáo.

**2. Dung lượng pin lớn và công nghệ sạc nhanh mạnh mẽ: **Viên pin 5.000 mAh kết hợp sạc nhanh 45W giúp rút ngắn tối đa thời gian chờ đợi nạp đầy năng lượng cho thiết bị.
