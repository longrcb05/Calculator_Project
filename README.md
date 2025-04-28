Ứng dụng Máy tính - CMU-CS 246 NIS (2025S) - Nhóm 3
Giới thiệu dự án
Nhóm 4 thực hiện phát triển Ứng dụng Máy tính trong môn học CMU-CS 246: Application Development Practices (2025S), do ThS. Nguyễn Đăng Quang Huy giảng dạy. Ứng dụng được thiết kế nhằm hỗ trợ thực hiện các phép tính cơ bản, phép toán khoa học nâng cao và cung cấp giao diện người dùng trực quan, thân thiện, hướng tới trải nghiệm sử dụng hiệu quả và tiện lợi.
Thành viên nhóm: 
•	Nguyễn Nhật Long (Trưởng nhóm)
Nhiệm vụ: Các phép toán khoa học
o	Tính giai thưa (n!), logarit (log₁₀ x, ln x), các hàm lượng giác: sin(x), cos(x)
o	Chuyển đổi đơn vị góc: Độ ↔ Radian
•	Nguyễn Văn Trường
Nhiệm vụ: Các phép toán khoa học + Update Test Case
o	Các hàm lượng giác: tan(x), cot(x)
o	Cập nhật Test Case
•	Nguyễn Huy Quý 
Nhiệm vụ: Lịch sử tính toán
o	Lưu trữ lịch sử phép tính vào file JSON hoặc text
o	Cho phép người dùng tìm kiếm lại phép tính cũ trong lịch sử
o	Cho phép người dùng xóa từng dòng lịch sử
•	Phạm Văn Nhật
Nhiệm vụ: Giao diện người dùng + Các chức năng điều khiển
o	Thêm chế độ Dark mode và Light mode
o	Cho phép người dùng chọn phông chữ và màu sắc giao diện
o	Hỗ trợ keyboard shortcuts
o	Thêm nút CE để xóa một số duy nhất mà không làm thay đổi phép tính
o	Thêm chức năng ← (Backspace) và → (Forward) để xóa một ký tự ở hai chiều con trỏ
•	Võ Trung Đức
Nhiệm vụ: Các tính năng bổ sung khác + Xử lí lỗi nâng cao
o	Kiểm thử các tình huống lỗi đầu vào như phép tính vượt quá giới hạn, hay phép toán không hợp lệ (ví dụ: chia cho 0, căn bậc hai của số âm)
o	Thêm thông báo lỗi chi tiết khi nhập sai dữ liệu (ví dụ: "5++2", "√-9")
o	Copy/Paste kết quả vào clipboard
o	Hỗ trợ tính toán theo biểu thức phức tạp như: "5 + (3 * 2) - √9"
Tính năng
Các phép toán khoa học
•	Giai thừa (n!).
•	Logarit (log₁₀ x, ln x).
•	Hàm lượng giác: sin(x), cos(x), tan(x), cot(x).
•	Chuyển đổi đơn vị góc: Độ ↔ Radian.
Lịch sử tính toán
•	Lưu trữ lịch sử phép tính vào file JSON hoặc text.
•	Cho phép tìm kiếm các phép tính cũ.
•	Hỗ trợ xóa từng dòng lịch sử.
Giao diện người dùng
•	Chuyển đổi giữa chế độ tối (Dark Mode) và sáng (Light Mode).
•	Tùy chỉnh phông chữ và màu sắc giao diện.
•	Hỗ trợ phím tắt để nhập phép tính.
Chức năng điều khiển
•	Nút CE (Clear Entry) để xóa một số mà không ảnh hưởng phép tính.
•	Chức năng Backspace (←) và Forward (→) để chỉnh sửa ký tự theo hai hướng.
•	Xử lý nhập liệu cho các biểu thức phức tạp.
Tính năng bổ sung
•	Sao chép/dán kết quả vào/ra clipboard.
•	Hỗ trợ tính toán biểu thức phức tạp (ví dụ: "5 + (3 * 2) - √9").
•	Xử lý lỗi nâng cao với thông báo chi tiết cho các đầu vào không hợp lệ (ví dụ: chia cho 0, "5++2", "√-9").
Xử lý lỗi
•	Kiểm tra các trường hợp lỗi như vượt giới hạn, phép toán không hợp lệ.
•	Cung cấp thông báo lỗi rõ ràng (ví dụ: "Đầu vào không hợp lệ: √-9").
