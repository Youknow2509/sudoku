
# Contact:
- **Mail**: *lytranvinh.work@gmail.com*
- **Github**: *https://github.com/Youknow2509*

# Luật chơi:
    - Game sẽ cho bạn một mảng 9 * 9, một vài giá trị sẽ đc xuất hiện và một vài giá trị sẽ bị ẩn.
    - Bạn hãy tìm hết tất cả giá trị ẩn sao cho: 
        + Tại mỗi hàng và cột mỗi giá trị chỉ xuất hiện một lần.
        + Tại một khu vực 3*3 các giá trị chỉ xuất hiện 1 lần(Các giá trị được sắp xếp chỉ bao gồm 9 khu vực).

# Cách khởi tạo trò chơi ngẫu nhiên:

- Đầu tiên khởi tạo 3 nhóm trên đường chéo bằng phương thức random.
- Xử dụng tư tưởng quay lui để điền các giá trị hợp lệ vào bảng => Đc một bảng giá trị chuẩn.
- Xoá đi một số ô để khiến người chơi dùng qui luật của game để tìm ra.

# Use:
## Libary:
    javafx-sdk-22.0.1 ( it fix err open window for macos 14) 
    Java OpenJDK 17.0.10 Corretto
## DataBase:
    MySQL
## Scene Builder 21.0.0

## How to run:
- Clone project về máy.
- Mở project bằng IntelliJ IDEA (hoặc bất kỳ IDE nào khác).
- Cài đặt thư viện `javafx-sdk-22.0.1` vào project.
- Cài đặt `Java OpenJDK 17.0.10 Corretto`.
- Cài đặt `Scene Builder 21.0.0`.
- Cài đặt driver `sqljdbc_12.6` (để kết nối database MySQL).
    + File query base: `src/DataGame/Querry/SQLQuery_1.sql`.
    + Sửa lại user và pass để đăng nhập trong `src/DataGame/Handle/HandleDataSql.java`.
- Thêm VM options vào project
- Chạy file `main.java` trong thư mục `src/Test/Main.java`.

# Figma: 
- https://www.figma.com/file/5uljFBQ2N18PUXL189NlnY/Sodoku?type=design&node-id=0%3A1&mode=design&t=IKcUN1p2mMKyHdUQ-1

