## PHẦN 1 – GOOGLING ĐÚNG CÁCH

**1.** Câu hỏi văn nói quá dài, chứa nhiều từ thừa, thiếu từ khóa kỹ thuật nên Google trả về nhiều kết quả không liên quan.

**2. Bóc tách lỗi:**

- Tên phần mềm / Hệ điều hành: Node.js / Windows 11.
- Mã lỗi nguyên văn: `'npm' is not recognized as an internal or external command, operable program or batch file.`
- Thao tác đang làm: Gõ lệnh `npm -v` trong Terminal VS Code.

**3. Ba câu truy vấn Google:**

- `site:stackoverflow.com npm not recognized Windows 11 PATH`
- `"npm is not recognized as an internal or external command"`
- `npm not recognized Windows 11 -windows-xp -driver`

## PHẦN 2 – THẨM ĐỊNH STACKOVERFLOW

**1. So sánh hai câu trả lời:**

- Vote & Tích xanh: A có +186 vote và tích xanh; B có +2 vote, không tích xanh.
- Thời gian đăng: A đăng 2 năm trước; B đăng 9 năm trước.
- Tags: A có Node.js, Windows, npm; B có Node.js, Windows XP.

**2.** Chọn câu trả lời A vì có nhiều lượt bình chọn, được chấp nhận và phù hợp với hệ điều hành. B là bẫy nguy hiểm vì hướng dẫn cho Windows XP, không liên quan đến Windows 11 và có thể gây mất thời gian.

**3. Quy trình 30 giây:**
- Xem số Upvote và tích xanh.
- Kiểm tra thời gian đăng.
- Kiểm tra Tags.
- Đọc nội dung giải pháp.

## PHẦN 3 – HỎI AI ĐÚNG CÁCH VÀ NHẬN DIỆN RỦI RO

**1. Prompt 3 thành phần:**

[Context]: Tôi vừa cài Node.js trên Windows 11 và sử dụng Terminal trong VS Code. Tôi đã thêm đường dẫn Node.js vào biến PATH nhưng vẫn bị lỗi.

[Raw Error]: `'npm' is not recognized as an internal or external command, operable program or batch file.`

[Instruction]: Hãy giải thích nguyên nhân bằng tiếng Việt và hướng dẫn các bước kiểm tra, khắc phục an toàn.

**2.** Đây không phải câu trả lời an toàn vì lệnh `del /f /s /q C:\Windows\System32\*` có thể xóa các tệp hệ thống quan trọng, khiến Windows bị hỏng hoặc không khởi động được.

**3.** Tôi sẽ hỏi lại AI: Tại sao cần xóa thư mục System32 để sửa lỗi PATH? Có cách kiểm tra biến môi trường và khắc phục nào an toàn hơn không? Hãy giải thích trước khi đưa ra lệnh.

## PHẦN 4 – VIẾT BUG REPORT CHUẨN

**1. Tin nhắn kém:**

Thầy ơi, máy em bị lỗi npm rồi, thầy giúp em với ạ!

**2. Tin nhắn chuẩn:**

Chào thầy, em đang gặp lỗi khi kiểm tra Node.js trên Windows 11.

- Context: Em đã cài Node.js và sử dụng Terminal trong VS Code.
- Expected: Lệnh `npm -v` hiển thị phiên bản npm.
- Actual: Terminal báo lỗi `'npm' is not recognized as an internal or external command, operable program or batch file.` Em đã thêm PATH và mở Terminal mới nhưng lỗi vẫn còn.
- Log & Screenshot: Em gửi kèm nội dung thông báo lỗi và ảnh chụp màn hình để thầy kiểm tra.

Mong thầy hướng dẫn em cách khắc phục. Em cảm ơn thầy!

**3. Phím tắt và bảo mật:**

- Phím tắt: `Windows + Shift + S`.
- Lưu ý: Che thông tin nhạy cảm như mật khẩu, API Key và Token trước khi gửi ảnh.
