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
- 🔹 Các tag (thẻ) HTML cơ bản
|Các thẻ định dạng khối văn bản|
| - Tiêu đề (Heading)| `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`|
| - Đoạn văn bản (Paragraph)| `<p>`|
| - Danh sách (List Items)| `<li>`|
|Các thẻ định dạng chuỗi văn bản|
| - Định dạng chữ| `<em>`, `<i>`, `<b>`, `<b>`, `<font>`|
| - Thẻ Link | `<a>`|
| - Xuống dòng| `<br/>`|
|Các thẻ khối|
| - Định nghĩa nội dung mức khối| `<div>`|
| - Định nghĩa nội dung trong dòng| `<span>`|
|Các thẻ bảng, đơn|
|- Thẻ bảng | `<table>`|
|- Thẻ đơn | `<form>`|
- 🔹 Ký tự đặc biệt
|Ký tự đặc biệt| Mô tả| Entity Name| Entity Number|
|" | Dấu ngoặc kép| `&quot`|`&#34`|
|& | Dấu và| `&amp`|`&#38`|
|< | Dấu bé| `&lt`|`&#60`|
|> | Dấu lớn| `&gt`|`&62`|
| space| Khoảng trắng|`&nbsp`|`&#160`|
- 🔹 Một số tag (thẻ) đặc biệt

---

## III. Ngôn ngữ CSS
- 🔹 Giới thiệu CSS - Casscading Style Sheets
- 🔹 Đơn vị kích thước
| Đơn vị | Mô tả|
|Kích thước tương đối|
| % | Phần trăm so với thành phần chứa đối tượng|
|vw| Phần trăm của chiều rộng cửa sổ khung hình |
|vh| Phần trăm của chiều cao của cửa sổ khung hình|
|vmin| Phần trăm của chiều khung nhìn nhỏ nhất|
|vmax| Phần trăm của chiều khung nhìn lớn nhất|
|em| Kích cỡ của font hiện tại đối tướng hoặc thành phần chứa đối tượng|
|rem| Giá trị tương đối với font của thành phần gốc|
|ex| Chiều cao của 1 chữ in thường của font hiện tại|
|ch| chiều rộng của số 0|
|Kích thước thuyệt đối|
|px| pixel|
|pt| point (1 pt = 1/27 in)|
|cm| Xăng ti mét|
|mm| mi li mét|
|in| inch (1 in = 72 pt)|
|pc| pica (1 pc = 12 pt)|

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

### 3. Một số ký tự quan trọng

| STT | ký tự                   | Chức năng                                                       |
|-----|-----------------------------|-----------------------------------------------------------------|
||

---

>📑 Một số thông tin tham khảo, rất mong sẽ hỗ trợ được mọi người
