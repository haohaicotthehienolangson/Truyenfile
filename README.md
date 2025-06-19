- Giới thiệu:
Với công nghệ ngày càng phát triển việc băo mật thông tin cũng tăng tiến lên theo. Ký số cũng là một trong những giải pháp bảo mật quan trọng và hữu dụng nhất để xác thực thông tin. Vậy nên ứng dụng này được phát triển và ra đời bản hoàn thiện. 
- Chức năng:
Ban đầu người gửi sẽ chọn file và gửi qua bên người nhận. Người nhận khi nhận file có thể kiếm tra lại chữ ký để xem file có bị chỉnh sửa hay không.
- Công nghệ sử dụng:
+ Flask: Đoạn code sử dụng Flask để tạo các route cho các chức năng như gửi, nhận, tải lên, tải xuống, và xác minh tệp tin.
+ Cryptography (RSA, SHA-256): Đây là thuật toán ký số và hàm băm để băm và ký dữ liệu.
+ PKCS#1 v1.5: Được sử dụng để ký và xác minh chữ ký cho dữ liệu bằng cách sử dụng khóa RSA.
+ Base64: Được sử dụng để mã hóa chữ ký số thành định dạng có thể truyền tải qua HTTP.
+ JSON: Được sử dụng để trả về dữ liệu trong định dạng JSON cho các API, giúp giao tiếp giữa client và server.
+ HTML Templating: Cung cấp giao diện người dùng cho các chức năng của ứng dụng.
- Ảnh minh họa:
    ![image](https://github.com/user-attachments/assets/8ef43309-3be5-4e14-81cb-1e3c6abe2310)
  ![image](https://github.com/user-attachments/assets/c6162427-accf-4f0e-8855-583ffdd39edf)

