# **Yêu cầu đầu ra**
## **Phần 1. Phân tích:**
- Field (Trường dữ liệu / Cột): Là các thuộc tính định danh cho thông tin, chẳng hạn như Mã giao dịch (ID), Ngày giờ, Số tiền, hay Trạng thái. Mỗi cột đóng vai trò là một loại thông tin độc lập.

- Record (Bản ghi / Dòng): Là một dòng dữ liệu hoàn chỉnh gom tất cả các thuộc tính (Field) lại với nhau để mô tả trọn vẹn cho một giao dịch riêng biệt của một người dùng cụ thể.

## **Phần 2. Triển khai:** Bộ 3 file Word, Excel, PowerPoint.

## **Phần 3. Kiểm thử:** 
- Lỗi khoảng trắng ẩn: Dữ liệu có thể bị dính dấu cách thừa ở đầu hoặc cuối -> Khắc phục bằng hàm TRIM().

- Lỗi lệch kiểu dữ liệu (Data Type): Một bên là kiểu chữ (Text) và bên kia là kiểu số (Number) -> Cần chuẩn hóa đồng nhất kiểu dữ liệu.

- Lỗi vùng tham chiếu (Table_array): Cột cần tìm kiếm không nằm ở cột đầu tiên bên phía trái của vùng chọn, hoặc chưa cố định vùng bằng phím F4.

- Lỗi tham số khớp chính xác: Quên đặt tham số cuối cùng thành 0 hoặc FALSE, khiến Excel hiểu nhầm sang chế độ tìm kiếm tương đối (TRUE)
