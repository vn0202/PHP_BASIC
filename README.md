# PHP-Basic 
## Introduce to Web Technnology ( Giới thiệu về công nghệ web) 
Công nghệ web là một thuật ngữ chung để chỉ các ngôn ngữ và các gói đa phương tiện kết hợp với nhau để tạo nên một trang web. Mỗi công nghệ web có 1 chức năng riêng biệt và cần sử dụng kết hợp với các công nghệ khác.  
### Các công nghệ web phổ biến : 
##### HTML
- Là công cụ chủ chốt trong phát triển web, xây dựng lên cấu trúc  của trang web.
##### CSS
- Mô tả các hiển thị của các phần tử trên trang web.
##### Javascript 
- Là một ngôn ngữ lập trình động có thể chạy trên trình duyệt.
- Có thể tương tác trực tiếp với DOM của 1 trang web dẫn đến có thể thay đổi cấu trúc của 1 trang web trong lập trình. 
##### Server-side rending
- Các trang web và ứng dụng web được xây dựng trên cơ sở logic của server. Trong đó các trang web được lưu trữ 
trên server. Các dòng lệnh HTML, CSS và JS được gửi từ server về trình duyệt. 
##### client-side rending 
- Với sự phát triển của trình duyệt và Javascript, xu hướng chuyển dần sang client-side rending
- Các trang web được dựng trên trình duyệt thông qua JS thay vì trên server . Máy chủ gửi các lệnh JS tới trình duyệt và  thực thi các dòng lệnh  này. JS được tạo ra và thao 
tác với các phần tử DOM của trang web. Tạo ra HTML và CSS của trang web và các ứng dụng trên trang.
- Công nghệ này khiến cho người dùng có trải nghiệm mượt mà hơn. Bởi vì lúc này trình duyệt không cần gửi yêu cầu tới server 
để có thể hiện lên 1 trang web hoàn chỉnh. mà chỉ cần thêm yêu cầu thêm dữ liệu và được thực thi ngay trên trình duyệt 
## Introduce HTML5 and CSS
### HTML5 
       HTML viết tắt cho Hyper Text Markup Language,có nghĩa là ngôn ngữ đánh dấu siêu văn bản,
       là khung xương của bất kỳ trang web nào. Chúng bao gồm các thẻ, nói cho các trình duyệt nội dung, thứ tự, các thuộc tính của chúng. 
       Trình duyệt sẽ không hiển thị các thẻ này mà dựa vào nó để 
       để quyết định cách hiển thị nội dung của các thẻ đó.
  **HTML5**  là phiên bản thứ 5 của HTML phát hành năm 2014, với nhiều tính năng được bổ sung: như audio, video, canas, SG,xác định vị trí người dùng...
  Với HTMl vẫn có thể sử dụng nhưng cần tích hợp thêm các phương tiện hỗ trợ .   

  **Sự khác biệt giữa HTML5 và HTML**
  - HTML5 thân thiện với các thiết bị di động
  - HTML5 có thêm các thẻ semantic mới : header, footer, nav, section...
  - HTML5 hỗ trợ video và audio, trong khi HTML thì không
  - HTML có tích hợp theo dõi người dùng, còn HTML có hỗ trợ nhưng khó khi ngươi dùng dùng di động 
  - HTML5 có nhiều tùy chọn để lưu trữ như Application Cache, SQL database, web socket,..Còn HTML sử dụng bộ nhớ cache của trình duyệt làm bộ nhớ tạm 
  - HTML5 hỗ trợ web socket giúp giao tiếp song song giữa client và server, trong khi HTML không hỗ trợ web socket nên giao tiếp giữa server và client là Streaming .
  - HTML5 hỗ trợ đồ họa mặc định là canas và SGV.
  - HTML5 hỗ trợ xử lý lỗi liên tục thông qua quy trình xử lý lỗi ứng biến, trong khi HTML thì không.
  - HTML5 cho phép chạy JS trong nền, còn HTML chạy js trong trình duyệt gây hiệu suất thấp.

### CSS 
   - Viết tắt của Cascading Style Sheets, là ngôn ngữ được sử dụng định kiểu trang web, mô tả các phần tử HTML được hiển thị như nào: như màu sắc, font chữ, kích thước,..
   - Có 3 cách để thêm CSS vào trang web của bạn: inline, internal và external. 
   - Độ ưu tiên hiển thị theo thứ tư: inline, internal và external. Khuyên dùng kiểu external.
   - Độ ưu tiên của id > class > tag. 
   - Khi có thêm thuộc tính !**important** thì có độ ưu tiên hiển thị lớn nhất.
## Introduction PHP 
### Khái niệm
- PHP là viết tắt của PHP: HyperText Preprocessor.
- PHP là ngôn ngữ kịch bản (scripting language) , mã nguồn mở được sử dụng rộng rãi và hoàn toàn miễn phí.
- Các câu lệnh PHP thực thi phía máy chủ và đưọc sử dụng để tạo các ứng dụng web.

### Đặc điểm:
- PHP chạy trên nhiều nền tảng khác nhau 
- PHP tương thích với hầu hết các máy chủ ngày nay (Apache, nginx,IIS,,)
- Hỗ trợ nhiều loại cơ sở dữ liệu 
- PHP là hoàn tòan miễn phí.
### Tệp php 
- có phần mở rộng là .php 
- Có thể chứa văn bản, HTML, JS và mã PHP.
- Được thưc thi trên máy chủ và trả về trình duyệt dưới dạng HTML thuần túy
### Cú pháp:
- Mỗi tệp PHP được thực thi trên máy chủ và trả về dưới dạng HTML thuần túy.
- Mỗi tệp lệnh PHP bắt đầu và kết thúc bằng cặp thẻ `<?php  ?>`.Kết thúc câu lệnh bằng dấu `;`. Với câu lệnh kết thúc trước thẻ đóng có thể bỏ qua dấu `;`. Thậm chí có thể bỏ thẻ đóng nếu sau tệp không có câu lệnh nào.
- Có thể đặt tập lệnh ở bắt kỳ đâu trong tài liệu.
- Trong php các hàm , các lớp, và các hàm do người dùng định nghĩa là không phan biệt chữ hoa chữ thường. Khuyến khich sử dụng chữ thường.
- Các biến trong PHP phân biệt chữ hoa chữ thường. 

   ``` <?php echo "Hello world";?> ```


### PHP data type 
 PHP không có kiểu dữ liệu một rõ ràng, nhưng kiểu của 1  biến được xác định bằng giá trị của nó được gắn hoặc bởi kiểu nó được ép.   
 Một vài kiểu dữ liệu trong php: 
- null: Đại diện cho môt biến không được gắn giá trị hoặc có thể gán trực tiếp.
