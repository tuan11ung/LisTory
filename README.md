LisTory - Website Luyện Nghe Tiếng Anh
LisTory là một ứng dụng web được thiết kế để giúp người dùng luyện tập kỹ năng nghe tiếng Anh thông qua các câu chuyện ngắn. Ứng dụng mang đến trải nghiệm tương tác với các tính năng như điều chỉnh tốc độ phát, kiểm soát âm lượng, thêm âm thanh nền và hiển thị bản dịch tiếng Việt.

Giới thiệu
LisTory hỗ trợ người học tiếng Anh cải thiện khả năng nghe hiểu bằng cách cung cấp các câu chuyện ngắn. Người dùng có thể tùy chỉnh trải nghiệm nghe với nhiều giọng nói, tốc độ phát, hiệu ứng âm thanh và âm thanh nền mô phỏng môi trường thực tế.

Tính năng chính
Lựa chọn câu chuyện: Chọn từ danh sách các câu chuyện ngắn có sẵn.
Tùy chọn giọng nói: Sử dụng các giọng nói tiếng Anh khác nhau để chuyển văn bản thành giọng nói.
Kiểm soát tốc độ và âm lượng: Điều chỉnh tốc độ phát (từ 0.5x đến 2.0x) và âm lượng (từ 0% đến 100%) bằng thanh trượt.
Âm thanh nền: Bật các tiếng ồn thực tế như quán cà phê, giao thông hoặc văn phòng để tăng tính chân thực khi luyện nghe.
Hiệu ứng giọng nói: Áp dụng các hiệu ứng như giọng robot, giọng cao hoặc giọng trầm cho phần kể chuyện.
Chuyển đổi bản dịch: Hiển thị hoặc ẩn bản dịch tiếng Việt cho từng câu.
Thanh tiến trình: Theo dõi tiến độ nghe của bạn trong suốt câu chuyện.

Yêu cầu hệ thống
Trình duyệt web hiện đại hỗ trợ SpeechSynthesis API (ví dụ: Google Chrome, Microsoft Edge).
Kết nối internet để tải các thư viện bên ngoài như Howler.js.

Hướng dẫn cài đặt và chạy
Tải xuống mã nguồn:
Lấy các tệp cần thiết bao gồm index.html, các tệp CSS, JavaScript và tệp âm thanh nền (như coffee-shop-noise.mp3, traffic-noise.mp3, office-noise.mp3).
Sắp xếp tệp âm thanh:
Đặt các tệp âm thanh nền vào thư mục src/ (đảm bảo đường dẫn tương đối so với index.html là chính xác).
Chạy ứng dụng:
Mở tệp index.html trong trình duyệt hỗ trợ SpeechSynthesis API.
Chọn một câu chuyện, giọng nói, sau đó sử dụng các nút điều khiển (Phát, Tạm dừng, Đặt lại) để bắt đầu.

Hướng dẫn sử dụng
Chọn một câu chuyện từ menu thả xuống.
Chọn giọng nói và điều chỉnh tốc độ hoặc âm lượng nếu cần.
Bật âm thanh nền hoặc hiệu ứng giọng nói để tùy chỉnh trải nghiệm.
Sử dụng nút chuyển đổi để hiển thị hoặc ẩn bản dịch tiếng Việt.
Nhấp vào từng câu trong hộp câu chuyện để chuyển đến phần mong muốn.

Cấu trúc mã nguồn
HTML: Xây dựng giao diện người dùng (hộp câu chuyện, nút điều khiển, thanh trượt, v.v.).
CSS: Thiết kế giao diện hiện đại, trực quan (hộp câu chuyện, thanh tiến trình, nút bấm).
JavaScript: Xử lý logic chính, bao gồm tổng hợp giọng nói, quản lý âm thanh nền và tương tác với người dùng.

Phụ thuộc
Howler.js: Thư viện quản lý âm thanh nền, được tải qua CDN.
SpeechSynthesis API: Tích hợp sẵn trong trình duyệt để chuyển văn bản thành giọng nói.
Hướng dẫn phát triển
Thêm câu chuyện mới:
Cập nhật mảng stories trong mã JavaScript với định dạng [["Câu tiếng Anh", "Bản dịch tiếng Việt"], ...].
Thêm âm thanh nền mới:
Thêm tệp âm thanh vào thư mục src/ và cập nhật đối tượng noiseFiles trong mã JavaScript.
Tùy chỉnh giọng nói:
Ứng dụng sử dụng các giọng nói có sẵn trong trình duyệt; kiểm tra xem trình duyệt của bạn có hỗ trợ giọng tiếng Anh hay không.

Ghi chú
Ứng dụng chỉ hoạt động trên các trình duyệt hỗ trợ SpeechSynthesis API. Nếu không được hỗ trợ, bạn sẽ nhận được thông báo lỗi.
Đảm bảo các tệp âm thanh được đặt đúng trong thư mục src/ để tránh lỗi phát.
Bản dịch tiếng Việt có thể tắt để phù hợp với người học nâng cao.

Ví dụ về các câu chuyện
"Never fight over trifles": Câu chuyện về một người lữ hành, con lừa và bài học về tranh cãi vụn vặt.
"Better bent than broken": Hành trình của cây sồi mạnh mẽ và cây sậy linh hoạt khi đối mặt với cơn bão.
"A coward can't teach courage": Bài học về lòng dũng cảm từ một con hươu mẹ và con trai.
Giấy phép
Dự án này được phát triển cho mục đích giáo dục và hiện không có giấy phép cụ thể.

Khắc phục sự cố
Không nghe thấy âm thanh?:
Kiểm tra xem trình duyệt có hỗ trợ SpeechSynthesis API không.
Đảm bảo âm lượng không bị tắt.
Âm thanh nền không hoạt động?:
Xác minh các tệp âm thanh trong thư mục src/ được tham chiếu chính xác.
Kiểm tra quyền phát âm thanh của trình duyệt.
