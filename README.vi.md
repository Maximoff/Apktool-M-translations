# Apktool-M-tiếng việt
Các tệp bản địa hóa (dịch giao diện) cho Apktool M.

## Cách gửi yêu cầu thay đổi (Pull Request)
Để gửi yêu cầu thay đổi (pull request) cho tôi, bạn cần thực hiện các bước sau:

1. **Fork** kho lưu trữ (repository) này về tài khoản GitHub của bạn;  
2. **Clone** bản fork đó về thiết bị của bạn;  
3. Thực hiện các chỉnh sửa cần thiết;  
4. Lưu và **gửi Pull Request** (yêu cầu hợp nhất) vào nhánh của tôi.

📘 [Tài liệu GitHub: Sử dụng Pull Requests](https://help.github.com/articles/using-pull-requests/ "Tài liệu GitHub")

---

## Hướng dẫn về ký tự đặc biệt

Vui lòng sử dụng **trình dịch tích hợp của Apktool M**, hoặc chỉnh sửa thủ công các ký tự sau:

1. Thay `<` bằng `&lt;`  
2. Thay `&` bằng `&amp;`  
3. Thay `"` bằng `\"`  
4. Thay `'` bằng `\'`  
5. Ký tự `%` phải được viết **gấp đôi** thành `%%`, nếu nó **không được dùng để định dạng chuỗi**.  
   - Hoặc nếu chuỗi đó không cần định dạng, hãy thêm thuộc tính `formatted="false"`.

---

📄 **Ghi chú:**  
Các bản dịch phải được kiểm tra kỹ trước khi gửi, để tránh lỗi định dạng chuỗi và ký tự đặc biệt.
