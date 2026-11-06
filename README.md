PHẦN 1 – GOOGLING ĐÚNG CÁCH
Câu 1. Vì sao câu hỏi văn nói tìm kiếm kém?

Vì câu hỏi dài, thiếu từ khóa kỹ thuật như npm, PATH, Windows 11, khiến Google khó tìm đúng kết quả.

Câu 2. Bóc tách lỗi
Thành phần	Nội dung
Phần mềm / HĐH	Node.js / Windows 11
Lỗi nguyên văn	npm is not recognized as an internal or external command
Thao tác	Gõ npm -v trong Terminal VS Code.

Câu 3. Ba câu truy vấn Google
1. site:stackoverflow.com npm not recognized Windows 11
2. "npm is not recognized as an internal or external command"
3. npm not recognized PATH -windows-xp
PHẦN 2 – THẨM ĐỊNH STACKOVERFLOW
Câu 1. So sánh A và B
Tiêu chí	A	B
Vote / Tích xanh	+186, có	+2, không
Thời gian	2 năm	9 năm
Tags	Node.js, Windows, npm	Node.js, Windows XP

Câu 2. Kết luận

Chọn A vì có tích xanh, nhiều Upvote và phù hợp Windows. B là bẫy vì hướng dẫn cài driver mạng Windows XP, không liên quan lỗi npm.

Câu 3. Quy trình đọc lướt 30 giây
1. Kiểm tra Tags.
2. Kiểm tra tích xanh.
3. Xem số Upvote.
4. Kiểm tra thời gian đăng.
5. Đọc nội dung giải pháp.
PHẦN 3 – HỎI AI VÀ NHẬN DIỆN RỦI RO
Câu 1. Prompt 3 thành phần
[CONTEXT]

Tôi sử dụng Windows 11, đã cài Node.js và kiểm tra npm trong Terminal VS Code. Đã thêm đường dẫn Node.js vào PATH và mở Terminal mới nhưng vẫn lỗi.

[RAW ERROR]
'npm' is not recognized as an internal or external command, operable program or batch file.
[INSTRUCTION]

Hãy giải thích nguyên nhân và hướng dẫn cách kiểm tra, khắc phục an toàn bằng tiếng Việt. Không đề xuất lệnh xóa dữ liệu hệ thống.




Câu 2. Đánh giá câu trả lời AI
Không an toàn
- Vi phạm nguyên tắc 1: Lệnh xóa file System32 có thể phá hỏng Windows.
- Vi phạm nguyên tắc 2: Đoán sai nguyên nhân lỗi PATH.
- Nguyên tắc 3: Không cung cấp thông tin bí mật như mật khẩu, API Key, OTP.
Câu 3. Phản hồi AI

"Tại sao lỗi npm lại cần xóa System32? Lệnh này có gây hỏng Windows không? Hãy đưa ra cách kiểm tra PATH an toàn, không xóa dữ liệu."
PHẦN 4 – VIẾT BUG REPORT
Câu 1. Tin nhắn kém

"Thầy ơi máy em bị lỗi npm, thầy giúp em với ạ!"

Câu 2. Tin nhắn chuẩn 4 thành phần
Em chào thầy, em gặp lỗi khi kiểm tra npm:

1. Context: Em dùng Windows 11, đã cài Node.js và mở Terminal trong VS Code.

2. Expected: Mong muốn lệnh npm -v hiển thị phiên bản npm.

3. Actual: Terminal báo lỗi npm is not recognized. Em đã thêm PATH và mở Terminal mới nhưng vẫn lỗi.

4. Log & Screenshot: Em gửi kèm thông báo lỗi và ảnh chụp màn hình.

Mong thầy hỗ trợ. Em cảm ơn thầy ạ!




Câu 3. Phím tắt và bảo mật
- Phím tắt: Windows + Shift + S.
- Lưu ý: Che mật khẩu, API Key và thông tin cá nhân trước khi gửi ảnh.