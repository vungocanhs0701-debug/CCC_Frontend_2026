# PHIẾU BÀI TẬP 01 — HTML5 FUNDAMENTALS
## Câu A1 (5đ) — HTTP & Browser
### A1.1. Khi gõ https://shopee.vn vào trình duyệt và nhấn Enter, liệt kê ít nhất 5 bước xảy ra (đúng thứ tự)
Khi người dùng nhập địa chỉ `https://shopee.vn` và nhấn Enter, trình duyệt sẽ thực hiện các bước sau (theo đúng trình tự):
1.Request từ laptop → truyền qua router WiFi  
2.→ đi vào hệ thống của nhà mạng  
3.→ chạy qua hàng loạt server trung gian  
4.→ đến server chính của Shopee  
5.→ server xử lý: "Người dùng muốn truy cập trang chủ"  
6.→ Response quay ngược lại theo đường cũ  
7.→ Chrome nhận HTML  
8.→ tải thêm CSS, JS, hình ảnh  
9.→ render giao diện hoàn chỉnh lên màn hình.
Nguồn tham chiếu:** `tuan_1_html5/01_introduction_html_universe.md` → phần mục 1.1 Client-Server, mục 1.2 HTTP, mục 1.3 Browser Rendering
### A1.2. Trong DevTools của Chrome, tab Network cho thấy thông tin gì?
Tab **Network** cho phép quan sát toàn bộ hoạt động request/response của trang web, bao gồm:
- Danh sách các request tải về (HTML, CSS, JS, image, API…)
- URL của request
- HTTP method (GET, POST…)
- Status code (200, 404, 500, 301…)
- Thời gian tải (load time) và dung lượng từng request
- Kiểm tra file nào làm trang web tải chậm
Nguồn tham chiếu: `tuan_1_html5/01_introduction_html_universe.md` → mục 4.3 Developer Tools (F12), tab Network
### A1.3. Screenshot tab Network và đánh dấu
