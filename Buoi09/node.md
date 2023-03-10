- CSS: Display, Position, Animation

- Cách nhúng Fonts mới vào Website mà máy tính chưa có sẵn. Ví dụ font-family: Roboto
  - Truy cập: https://fonts.google.com/?query=Roboto
  - Copy đoạn code CSS từ Google vào file html
  - Dùng cú pháp: font-family: 'Roboto', sans-serif; để khai báo fonts cho một phần tử.
  - 'Roboto' -> Tên fonts do Google đặt
  - 'sans-serif' -> Là một dạng font mặc định trong máy tính có sẵn, giống với Arial
  - Cú pháp 'Roboto', sans-serif -> Dạng liệt kê, nếu font Roboto không được cài ở trong máy tính hoặc tải file từ google về bị thất bại (Mạng chậm, Server chết, ...) sẽ thay thế bằng font `sans-serif`
  - Lưu ý: Tuỳ vào Website sẽ thấy thông tin Tên font chữ từ file thiết kế được cung cấp bởi Design (Có thể là file photoshop, có thể dùng một công cụ thiết kế trên Web như Figma, ...)


- Icon:
  - Cách nhúng Icon vào Website. Icon có nhiều dạng 
    Dạng 1: Coi như Icon giống fonts chữ. 
      -> Lợi ở điểm có thể thay đổi màu sắc của icon và kích thước của icon giống như một chữ cái bằng cách sử dụng thuộc tính của CSS: font-size, color, ...
    Dạng 2: Dạng thẻ vector trong HTML như là một thẻ. Thẻ này có tên là <svg>

  1. Tự làm Website chơi sẽ dùng những Icon có sẵn cung cấp trên Internet
    - https://www.flaticon.com/
    - https://ionic.io/ionicons/v2
    - https://ionic.io/ionicons

  2. Làm cho công ty (Có thể có đội ngũ Design) thiết kế icons riêng cho công ty.