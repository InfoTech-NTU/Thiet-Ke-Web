# 📘 THIẾT KẾ GIAO DIỆN WEB

## I. Giới thiệu tổng quan về Web
- 🔹 Các khái niệm: Web,Webpage, Website, HTML, XHTML,... 
- 🔹 Các ngôn ngữ lập trình web 
- 🔹 Web Server - Web Client - HTTP
- 🔹 URL – Uniform Resource Locator
- 🔹 Mô hình Client – Server
- 🔹 Qui trình thiết kế Website

---

## II. Ngôn ngữ HTML
- 🔹 Giới thiệu HTML - HyperText Markup Language
- 🔹 Cấu trúc của HTML
- 🔹 Các tag (thẻ) HTML cơ bản: '<h1>'
- 🔹 🍀[Nền tảng .NET](https://learn.microsoft.com/en-us/dotnet/)  

---

## III. Lớp và đối tượng - Classes and Objects
- 🔹 Cài đặt lớp  
- 🔹 Thiết lập tính bao đóng  
- 🔹 Tạo, sử dụng và hủy đối tượng
- 🔹 Hàm thiết lập (constructor)
- 🔹 Hàm hủy (destructor/finalizer)  
- 🔹 Lớp tĩnh, thành phần tĩnh
- 🔹 📝 [Ví dụ minh họa static class](https://github.com/nd-hung/oop/blob/main/docs/topics/classes-and-objects/code/TemperatureConverter/Program.cs)
- 🔹 Con trỏ this
- 🔹 Danh sách đối tượng
  - Danh sách tĩnh (array)
  - Danh sách động (list)
- 🔹 Nạp chồng phương thức (method overloading)
- 🔹 Nạp chồng toán tử (operator overloading)
- 🔹 📝 [Ví dụ minh họa](https://github.com/nd-hung/oop/blob/main/docs/topics/classes-and-objects/code/OperatorOverloading/Program.cs) 

---

## IV. Thừa kế - Inheritance
- 🔹 Tổng quát hóa, đặc biệt hóa 
- 🔹 Cài đặt thừa kế
- 🔹 📝 [Các ví dụ thừa kế](https://github.com/nd-hung/oop/tree/main/docs/topics/inheritance/code)
- 🔹 Quy tắc thừa kế
- 🔹 Lớp niêm phong (sealed class)
- 🔹 Nạp chồng phương thức của lớp cơ sở
- 🔹 Ẩn phương thức của lớp cơ sở
- 🔹 📝 [Ví dụ minh họa](https://github.com/nd-hung/oop/tree/main/docs/topics/inheritance/code/HidingBaseMethods)  

---

## V. Đa hình - Polymorphism
- 🔹 Dẫn nhập
- 🔹 Kỹ thuật đa hình
- 🔹 📝 [Ví dụ](https://github.com/nd-hung/oop/tree/main/docs/topics/polymorphism/code/Shape/)
- 🔹 Lớp trừu tượng - AbstractClass, phương thức trừu tượng - Abstract Method
- 🔹 Sự khác nhau giữa từ khóa new và override
- 🔹 Giao diện (interface)
- 🔹 Đa thừa kế
- 🔹 📝 [Ví dụ đa thừa kế](https://github.com/nd-hung/oop/tree/main/docs/topics/polymorphism/code/MultipleInheritance)

---

## 💡 Một số gợi ý - tham khảo
### 1. Một số sách/tài liệu

| STT | Tên tài liệu     | Tác giả                                                     |
|-----|--------------|-----------------------------------------------------------------|
| 1   | [Lập trình hướng đối tượng](https://nd-hung.github.io/oop/)      | Thầy Nguyễn Đình Hưng|
| 2   | Lập trình hướng đối tượng      | Trần Đan Thư, Đinh Bá Tiến, Nguyễn Tấn Trần Minh Khang - NXB Khoa học kỹ thuật, 2010|
| 3  | C# Programming Yellow Book     | Rob Miles, 2016|
| 4   | Beginning C# Object-Oriented Programming    | Dan Clark, 2015|
| 5  | Lập trình hướng đối tượng với C++       | Lê Đăng Hưng, Tạ Tuấn Anh, Nguyễn Hữu Đức, Nguyễn Thanh Thủy - NXB Khoa học kỹ thuật, 2005|
| 6   | C++ How to Program, 10th edition     | Paul Dietel - Pearson, 2017|
| 7  | ...          | ...                                                            |

### 2. Trang Web hỗ trợ thiết kế

| STT | Tên trang     | Chức năng|
|-----|---------------|----------|
| 1   | [clipart.com](https://www.clipart.com/)| Cung cấp hình ảnh cho làm Web|
| 2   | [Free Clip Art](https://free-clip-art.com/)| Cung cấp hình ảnh video|
| 3   | [FontAwesome](https://fontawesome.com/icons)| Thư viện Icon của FontAwesome| 
| 4   | [Google Font](https://fonts.google.com/)| kho font chữ của Google|
| 5   | [Bootstrap 5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)| Hỗ trợ code Bootstrap 5.3
| 6   | [Image Color Picker](https://imagecolorpicker.com/vi)| Lấy tham số màu săc|
| 6   | ...          |

### 3. Một số từ khóa quan trọng

| STT | Từ khóa                   | Chức năng                                                       |
|-----|-----------------------------|-----------------------------------------------------------------|
| 1   | public                 | Truy cập được từ bất kỳ đâu, cả trong và ngoài assembly (dự án).                              |
| 2   | private  | Chỉ truy cập được trong class hoặc struct chứa nó.|
| 3   | protected                  | Truy cập được trong class hiện tại và class dẫn xuất (kế thừa).|
| 4   | internal                | Truy cập được trong cùng một assembly (project), nhưng không từ bên ngoài.|
| 5   | abstract                      | Dùng để khai báo lớp hoặc phương thức trừu tượng|
| 6   | interface                    | Khai báo giao diện, chỉ chứa định nghĩa phương thức, không có thân|
| 7   | virtual    | Từ khóa virtual được dùng để cho phép một phương thức trong lớp cha có thể được ghi đè (override) trong lớp con.|
| 8   | override                   | Dùng trong lớp con để ghi đè (override) một phương thức virtual hoặc abstract trong lớp cha|
| 9   | new                      | Dùng để ẩn (hide) một thành viên kế thừa từ lớp cha, khi bạn không muốn override mà muốn viết lại từ đầu|
| 10  | static             | Dùng để khai báo biến, phương thức, hàm khởi tạo, hoặc lớp mà không cần tạo đối tượng.|
| 11  | ...                         | ...                                                                    |

---

>📑 Một số thông tin tham khảo, rất mong sẽ hỗ trợ được mọi người
