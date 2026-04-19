Do not Copy!
Chặn Logic: Nếu người dùng nhập lãi suất âm hoặc số tiền bằng 0, thay vì tính ra kết quả sai lệch, ứng dụng sẽ đổi màu hộp kết quả sang màu đỏ và hiển thị lời nhắc: "Số tiền mục tiêu phải lớn hơn 0".
Chặn trả trước 100%: Trong thực tế, nếu trả trước 100% thì không gọi là trả góp. Code đã chặn nếu người dùng nhập ≥100% ≥100%.
HTML min & step: Thuộc tính min="0" ngăn việc nhấn nút mũi tên xuống số âm trên trình duyệt. step="0.1" cho phép nhập lãi suất lẻ (ví dụ 6.5%).
Hàm showError: Một hàm dùng chung để hiển thị thông báo lỗi một cách chuyên nghiệp thay vì dùng alert() gây phiền cho người dùng.Chặn Logic: Nếu người dùng nhập lãi suất âm hoặc số tiền bằng 0, thay vì tính ra kết quả sai lệch, ứng dụng sẽ đổi màu hộp kết quả sang màu đỏ và hiển thị lời nhắc: "Số tiền mục tiêu phải lớn hơn 0".
Chặn trả trước 100%: Trong thực tế, nếu trả trước 100% thì không gọi là trả góp. Code đã chặn nếu người dùng nhập ≥100% ≥100%
HTML min & step: Thuộc tính min="0" ngăn việc nhấn nút mũi tên xuống số âm trên trình duyệt. step="0.1" cho phép nhập lãi suất lẻ (ví dụ 6.5%).
Hàm showError: Một hàm dùng chung để hiển thị thông báo lỗi một cách chuyên nghiệp thay vì dùng alert() gây phiền cho người dùng.
Hàm docSoTiengViet: Đây là thuật toán đệ quy/nhóm số phức tạp hơn để đọc chuẩn văn phong Việt Nam (ví dụ: số lẻ đọc là "linh", số 5 ở hàng đơn vị đọc là "lăm").
Sự kiện oninput: Ngay khi người dùng gõ phím hoặc dán số vào, dòng chữ màu xanh phía dưới sẽ xuất hiện ngay lập tức để phản hồi (Real-time feedback).
Validation: Nếu người dùng nhập số âm hoặc số quá lớn (vượt ngưỡng triệu tỷ), hệ thống sẽ hiển thị cảnh báo ngay tại dòng chữ đó.
UI/UX: Dòng chữ được thiết kế nhỏ gọn, in nghiêng và có màu xanh dịu để không làm rối giao diện chính nhưng vẫn đủ để sinh viên kiểm tra lại con số mình vừa nhập.
Ràng buộc monthly >= target: Trong hàm calculateSaving, tôi đã thêm điều kiện kiểm tra này đầu tiên. Nếu vi phạm, chương trình sẽ dừng tính toán và hiển thị thông báo lỗi ngay lập tức.
