# BÀI THỰC HÀNH 3: PHÂN TÍCH VÀ GIẢI QUYẾT TÌNH HUỐNG KHÁCH HÀNG KHIẾU NẠI

## 1. Mục tiêu thực hiện

Sử dụng AI để phân tích khiếu nại của khách hàng theo từng bước bằng kỹ thuật Chain-of-Thought (CoT), xác định vấn đề, đánh giá mức độ nghiêm trọng và đề xuất phương án giải quyết phù hợp.

## 2. Tình huống

Khách hàng mua laptop được 10 ngày nhưng máy thường xuyên nóng, quạt kêu to và pin chỉ sử dụng được khoảng 2 tiếng. Khách đã mang máy đến cửa hàng kiểm tra nhưng nhân viên chỉ vệ sinh máy. Sau 2 ngày, tình trạng vẫn tiếp diễn. Khách yêu cầu đổi máy hoặc hoàn tiền.

## 3. Quy trình thực hiện bằng AI

### Bước 1: Xác định vấn đề và đánh giá mức độ nghiêm trọng

**Prompt 1:**

Đóng vai nhân viên bán laptop. Phân tích, đánh giá tình huống khiếu nại khách hàng. Hãy xác định các vấn đề khách hàng gặp phải và phân tích mức độ nghiêm trọng của từng vấn đề. Trình bày theo từng bước, nội dung Markdown khoảng 100 từ.

**Kết quả thực hiện:**

- Laptop mới mua 10 ngày nhưng thường xuyên bị nóng, quạt tản nhiệt kêu to.
- Pin chỉ sử dụng được khoảng 2 tiếng.
- Đã vệ sinh máy nhưng lỗi vẫn tiếp diễn sau 2 ngày.
- Mức độ nghiêm trọng: Nghiêm trọng.
- Ảnh hưởng đến trải nghiệm, hiệu suất sử dụng và niềm tin của khách hàng.

### Bước 2: Đề xuất hai phương án giải quyết

**Prompt 2:**

Dựa trên nội dung phân tích ở bước 1, hãy đề xuất 2 phương án giải quyết phù hợp với khách hàng. Phương án cần có tính thực tế, bảo vệ quyền lợi khách hàng và cửa hàng. Không tự ý đưa ra cam kết hoàn tiền. Trình bày Markdown khoảng 100 từ.

**Kết quả thực hiện:**

**Phương án 1: Đổi máy mới**
- Kiểm tra và xác nhận lỗi kỹ thuật.
- Hỗ trợ đổi sang laptop mới cùng model hoặc tương đương.
- Kiểm tra kỹ máy mới trước khi bàn giao.

**Phương án 2: Kiểm tra chuyên sâu và sửa chữa**
- Kiểm tra pin, quạt và hệ thống tản nhiệt.
- Xác định nguyên nhân và khắc phục lỗi.
- Ưu tiên xử lý nhanh, bảo đảm quyền lợi khách hàng.

### Bước 3: So sánh ưu điểm và nhược điểm

**Prompt 3:**

Hãy so sánh ưu điểm và nhược điểm của hai phương án: đổi máy mới và kiểm tra chuyên sâu, sửa chữa. Phân tích theo các tiêu chí chi phí, thời gian xử lý và mức độ hài lòng của khách hàng. Trình bày dưới dạng bảng Markdown, khoảng 120 từ.

**Kết quả thực hiện:**

| Tiêu chí | Đổi máy mới | Kiểm tra và sửa chữa |
|---|---|---|
| Ưu điểm | Giải quyết nhanh, tăng sự hài lòng và niềm tin. | Tiết kiệm chi phí, xác định nguyên nhân lỗi. |
| Nhược điểm | Phát sinh chi phí, cần xác nhận lỗi. | Khách phải chờ, có nguy cơ lỗi tái diễn. |
| Thời gian | Nhanh nếu có máy thay thế. | Có thể mất nhiều thời gian. |
| Mức độ hài lòng | Thường cao hơn. | Phụ thuộc kết quả sửa chữa. |

**Kết luận:** Ưu tiên phương án đổi máy mới nếu xác nhận lỗi kỹ thuật và đáp ứng chính sách đổi trả.

### Bước 4: Soạn phản hồi gửi khách hàng

**Prompt 4:**

Đóng vai nhân viên chăm sóc khách hàng của cửa hàng laptop. Hãy soạn phản hồi chuyên nghiệp gửi khách hàng, có lời chào, lời cảm ơn, lời xin lỗi và đề xuất hai phương án: đổi máy mới hoặc kiểm tra chuyên sâu và sửa chữa. Ưu tiên giải pháp giúp khách hàng tin tưởng, đồng thời cân bằng chi phí và lợi ích cửa hàng. Không tự cam kết hoàn tiền hoặc khẳng định chính sách chưa được xác minh.

**Kết quả thực hiện:**

Kính chào Quý khách!

Trước tiên, cửa hàng chân thành cảm ơn Quý khách đã tin tưởng và lựa chọn sản phẩm. Chúng tôi thành thật xin lỗi vì những bất tiện mà Quý khách gặp phải khi laptop thường xuyên nóng, quạt kêu to và pin nhanh hết dù đã được vệ sinh.

Để đảm bảo quyền lợi và sự hài lòng của Quý khách, cửa hàng xin đề xuất hai phương án:

1. Đổi máy mới: Sau khi xác nhận lỗi kỹ thuật, cửa hàng hỗ trợ đổi máy mới cùng model hoặc tương đương theo chính sách đổi trả.
2. Kiểm tra và sửa chữa: Bộ phận kỹ thuật kiểm tra chuyên sâu pin, quạt và hệ thống tản nhiệt, ưu tiên khắc phục trong thời gian sớm nhất.

Chúng tôi ưu tiên phương án đổi máy mới nếu đủ điều kiện, nhằm giúp Quý khách yên tâm sử dụng.

Cảm ơn Quý khách đã thông cảm và tiếp tục đồng hành cùng cửa hàng!

## 4. Prompt hoàn chỉnh sử dụng kỹ thuật Chain-of-Thought

**Prompt tổng hợp:**

Đóng vai chuyên viên chăm sóc khách hàng có kinh nghiệm trong lĩnh vực bán laptop. Hãy sử dụng kỹ thuật Chain-of-Thought (CoT) để phân tích tình huống theo trình tự từng bước. Không đưa ra kết luận ngay khi chưa đủ thông tin.

Thực hiện lần lượt:

1. Xác định các vấn đề khách hàng gặp phải.
2. Đánh giá mức độ nghiêm trọng và ảnh hưởng của từng vấn đề.
3. Phân biệt rõ dữ kiện đã biết, giả thuyết và thông tin chưa xác định.
4. Liệt kê thông tin cần xác minh như tình trạng pin, nhiệt độ, lỗi kỹ thuật và chính sách bảo hành, đổi trả.
5. Đề xuất 2 phương án giải quyết, phân tích ưu điểm và hạn chế.
6. Soạn phản hồi chuyên nghiệp gửi khách hàng, có lời chào, cảm ơn và xin lỗi.

Yêu cầu:
- Không tự giả định chính sách đổi trả hoặc bảo hành.
- Không tự cam kết hoàn tiền hay đổi máy khi chưa xác minh điều kiện.
- Ưu tiên quyền lợi và sự hài lòng của khách hàng, đồng thời cân bằng chi phí và lợi ích cửa hàng.
- Trình bày bằng Markdown, rõ ràng, có tiêu đề và bảng khi cần thiết.

## 5. Thông tin cần xác minh

| Nội dung | Mục đích |
|---|---|
| Nhiệt độ laptop | Xác định máy có quá nhiệt hay không. |
| Tình trạng pin | Kiểm tra dung lượng và độ chai pin. |
| Quạt tản nhiệt | Xác định nguyên nhân tiếng ồn. |
| Phiếu mua hàng | Xác nhận thời gian và điều kiện mua hàng. |
| Chính sách bảo hành | Xác định quyền lợi khách hàng. |
| Chính sách đổi trả | Kiểm tra điều kiện đổi máy. |
