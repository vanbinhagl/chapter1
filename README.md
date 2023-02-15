# Cơ chế hoạt động của internet!
Khi bạn truy cập một trang web, máy tính của bạn sẽ gửi một request tới máy chủ. Máy chủ là nơi lưu trữ các trang web và nó hoạt động giống như ổ cứng máy tính của bạn. Khi yêu cầu đến, máy chủ sẽ truy xuất trang web và gửi response chính xác trở lại máy tính và hiển thị trang web ở client.
# Protocol của HTTP/HTTPS
 - **HTTP**: Sử dụng giao thức TCP/IP hoạt động theo mô hình Client – Server. Khi truy cập một trang web qua giao thức HTTP, trình duyệt sẽ thực hiện các phiên kết nối đến server của trang web đó thông qua địa chỉ IP do hệ thống phân giải tên miền DNS cung cấp. Máy chủ sau khi nhận lệnh, sẽ trả về lệnh tương ứng giúp hiển thị website, bao gồm các nội dung như: văn bản, ảnh, video, âm thanh,…
 - **HTTPS**:  là giao thức HTTP nhưng tích hợp thêm Chứng chỉ bảo mật SSL (Secure Sockets Layer) hoặc TLS (Transport Layer Security) và cả 2 sử dụng hệ thống PKI (Public Key Infrastructure). Hệ thống này sử dụng hai “khóa” để mã hóa thông tin liên lạc, “khóa công khai” (public key) và “khóa riêng” (private key). Những gì được mã hóa bằng khóa công khai chỉ có thể được giải mã bởi khóa riêng và ngược lại.
## Cách hoạt động của Browsers
Rendering engine sẽ bắt đầu nhận được nội dung của tài liệu yêu cầu từ lớp networking, Rendering engine sẽ bắt đầu phân tích cú pháp tài liệu HTML và chuyển đổi các elements sang các nút DOM trong một cây gọi là "content tree". Engine sẽ phân tích dữ liệu và khi kết thúc quá trình này sẽ tạo một cây khác gọi là render tree. Sau khi xây dựng render tree nó đi qua một "layout" process. Giai đoạn tiếp theo là painting–the render, tại đây mỗi nút sẽ được vẽ bằng cách sử dụng lớp UI backend. Các phần của nội dung sẽ được phân tích cú pháp và hiển thị, trong khi quá trình tiếp tục với phần còn lại của nội dung tiếp tục đến từ mạng (network).
## Cơ chế hoạt động của DNS và domain
 - **DNS**: Là hệ thống phân giải tên miền và có nhiệm vụ phân giải tên miền thành một địa chỉ IP tương ứng với tên miền đó.
 - **Domain**: Hay tên miền là địa chỉ đại diện cho trang web trên internet, sử dụng domain để tìm kiếm trang web trên mạng thay vì phải nhớ IP dài dòng của trang
   web.
## Giải thích về hosting server
Hosting Servers là việc quản lý offsite và duy trì các tài nguyên phần cứng được chỉ định cho việc sử dụng của công ty. Bằng cách trả phí hàng tháng cho dịch vụ hosting, các công ty có thể thu được lợi ích từ việc có cơ sở hạ tầng CNTT đầy đủ, mà không phải trả chi phí liên quan đến bảo trì, đào tạo và cập nhật thiết bị.
Hosting cấp cho bạn một không gian lưu trữ web trên server. Web host của bạn sẽ chứa toàn bộ files, tài liệu, và database. Bất kể có người nào gõ tên miền lên thanh địa chỉ của trình duyệt, hosting sẽ chuyển toàn bộ files cần thiết từ server xuống trình duyệt đó.
