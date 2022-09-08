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
```php 
$foo = null;
```
 Câu lệnh này vô hiệu hóa biến và giá trị của nó là void hoặc undifined nếu được gọi. Biến bị xóa khỏi bộ nhớ.  
 
 - boolean: `true` hoặc `false`. Thường được sử dụng trong cấu trúc điều khiển.   
 **Note**: các giá trị sau khi ép kiểu sang boolean có giá trị là `false`:
     - Một mảng rỗng hay 1 chuỗi rỗng.
     - Một giá trị zero : 0 , 0.00, "0" 
     - null   
       Các giá trị còn lại sẽ là true. (kể cả chuỗi 'false' cũng là true). Do đó cần lưu ý khi so sánh, nên dùng `===` để bảo đảm. 
 ```php 
 $foo= true;
$bar = false;
 if($foo){
//code }
els{
//code
}
   $foo= "0";
var_dumb((bool)$foo) // result: (boolean) false;
   $bar ='false';
var_dump((bool)$bar) //result: (boolean) true;
```
- Integer: là kiểu số nguyên dương hoặc âm. Kích thường của số nguyên php tủy thuộc vào môi trường. Không hỗ trợ số nguyên không dấu.
- Float : số chấm động, double hoặc float là các số thập phân.
 ```php 
$number1= 0.5;
$number2 = 9.4;
$number3 = -INF;
```
- Array : là một biến đặc biệt, chứa nhiều giá trị trong cùng 1 tên biến. Có các dạng mảng sau : mảng lập chỉ mục, mảng liên kết và mảng đa chiều.  

  - Mảng chỉ mục: được đánh số thứ tự từ 0 đến phần tử ( số lượng phần tử mảng - 1) 
       ```php 
    $array = array( 1,2,3);
    $array = ["hello", "world"];
    ```
  - Mảng kết hợp: là mảng có các khóa được đặt tên ứng với giá trị tương ứng  

       ```php
         $array = ['fistname'=>'hello', 'lastname'=>'world'];
       ```
  - Mảng đa chiều: là mảng có chứa nhiều hơn 1 hoặc nhiều mảng .
      ```php 
    $array = [
               [1,2,3],
               [4,5,6],
               [7,8,9] 
              ];
      ```
- String: Giống như 1 mảng các ký tự: 
      ```php 
           $string = "hello world";
      ``` 
- Object: là thực thể của 1 lớp. Các thuộc tinh và phương thức của nó có thể truy cập bằng toán tử trích xuất `->` 
- Resource: là các biến nắm giữ quyền điều khiển để mở file, kết nối với cơ sở dữ liệu , luồng...  
      ```php 
          $variable = fopen('file.txt','r')
      ```
 ### PHP variable, constant and Array 

#### Variable 
 - Biến được  dùng để lưu trữ các giá trị Một biến đưọc bắt đầu với ký tự `$` và theo sau là tên biến. 
 -  Biến có thể truy cập qua tên biến. Tên của 1 biến có thể được lưu trữ trong biến khác   
    ```php
           $variablename = 'foo';  
           $foo= "bar";   
           echo $$variablename ; // "bar"; 
           
    ```

   - Quy tắc đặt  tên biến:

       -Tên biến bắt đầu bằng $ và theo sau là tên biến.
       - Tên biến bắt đầu bằng ký tự hoặc dấu gạch duới.
       - Tên biến không được bắt đầu bằng số 
       - Tên biến chỉ chứa các ký tự số , chữ và dấu gạch duới. 
       - Tên biến phân biệt chữ hoa và chữ thường. 
   - Phạm vi biến: Là vùng mà biến có thể truy cập sử dụng.   
      
      - Super-global : Là các biến dựng sẵn và có thể truy cập ở bất kỳ đâu trong kịch bản mà không cần các keyword `global`.Bao gồm : `$GLOBALS`,`$_POST`,`$_GET`,
`$_SERVER`, `$_ENV`, `$_FILE`,`$_COOKIES`,`$_SESSION`.
       ```php 
        echo $_POST['username'];
     
      ```
      - Global: Các biến khai báo bên ngoài hàm  và chỉ có thể truy cập ngoài phạm vi hàm. Muốn sử dụng trong hàm cần keyword `global` hoặc biến superglobal `$GLOBALS`  
      - Local: biến được khai báo bên trong hàm và chỉ được sử dụng bên trong hàm. 

#### Constants
  
 - Hằng cũng tưong tự như biến, chỉ khác là khi được khai báo thì giá trị của nó trong suốt quá trình chạy. 
 - Tên hằng thường quy ước viết hoa. 
 - Không giống như biến, hằng có phạm vi super global;
 - Cú pháp khai báo hằng bằng hàm `define()` hoặc từ khóa `const`
  ```php 
define(name,vaule, case-insentise); 
 const NAME = VALUE;
  ```
 -  Điểm khác biệt giữa `define` và `const` là `define` có thể gắn với các giá trị linh hoạt (như các biến khác, thực hiện các phép toán,...), còn `const` thì không 
 ```php 
   $x = 10;
   define('NUMBER',$x) //valid;
   const MY_NUM = $x; //invalid;
 ```
- Để kiểm tra xem hằng đã được khai báo chưa, sử dụng `defined(name)` để xác định. Chú ý: hàm này chỉ quan tâm đến việc hằng đã khai báo chưa, không quan tâm đến giá trị 
của hằng, kể cả hăng có giá trị `false`, kết quả vẫn là `true`;
- Để xem danh sách các hằng, sử dụng làm `get_defined_constants`;
 

### Array 

 - Là một biến đặc biệt có thể lưu trữ nhiêu giá trị trong 1 tên biến .
 - Cú pháp có thể sử dụng : `array(vaule,vaule,...)` hoặc cú phú `$array = [vaule,value,...]`. 
 - Có các dạng mảng : 
  
   - Mảng chỉ mục: Chỉ mục của mảng được đánh số thứ tự từ không và phần tử cuối mảng có chỉ mục là `số phần tử mảng - 1`;
   ```php 
    $array = [1,2,45,7];
   ```
   - Mảng liên kết: Là mảng sử dụng các tên khóa  và gán giá trị cho nó. 
      ```php 
      $array = [ 
       'first_name'=>"VU";
       'last_name'=>"Nghia";
               ];
      ```
   - Mảng đa chiều: là một mảng chứa một hay nhiều mảng con. 
    
      ```php 
     $array = [
     [1,2,34,5],
     [ 
     'last_name'=>'Nghia',
     'first_name'=>"vu" 
     ]
     ];
      ```
 ### Toán tử (Operator) 
 
 Được sử dụng để thực hiện các hành động trên biến và giá trị :
   
#### Toán tử số học: 


 <table>
 <tr>
<th>Tóan tử </th>
<th>Tên</th>
<th>Ví dụ</th>
<th>Giải thích</th>
</tr>
<tr>
<td>+</td>
<td>Phép cộng</td>
<td>$a + $b </td>
<td>Cộng hai toán hạng</td>
</tr>
<tr>
<td>-</td>
<td>Phép trừ</td>
<td>$a - $b </td>
<td>Trừ hai toán hạng</td>
</tr>
<tr>
<td>*</td>
<td>Phép nhân</td>
<td>$a * $b </td>
<td>Nhân hai toán hạng</td>
</tr>
<tr>
<td>\</td>
<td>Phép chia lấy dư</td>
<td>$a % $b </td>
<td>Chia lấy dư </td>
</tr>
<tr>
<td>%</td>
<td>Phép cộng</td>
<td>$a + $b </td>
<td>Cộng hai toán hạng</td>
</tr>
<tr>
<td>+**/td>
<td>Lũy thừa</td>
<td>$a ** $b </td>
<td>lũy thừa</td>
</tr>





</table>


#### Tóan tử gán 
 
<table>
<tr>
<th>Toán tử</th>
<th>Tên </th>
<th>Ví dụ</th>
<th>Giải thích </th>
</tr>
<tr>
<td>=</td>
<td>Gán</td>
<td>$a = $b </td>
<td>Giá trị của vế phải được gán cho vế trái</td>
</tr>
<tr>
<td>+= </td>
<td> Thêm rồi gán </td>
<td>$a += $b </td>
<td>$a được tăng thêm giá trị $b. Tương tự: $a = $a + $b </td>
</tr>
<tr>
<td>-=</td>
<td>Trừ rồi gán </td>
<td>$a -= $b</td>
<td>$a giảm đi giá trị $b. Tương tự: $a = $a- $b</td>
</tr>
<tr>
<td>*=</td>
<td>Nhân rồi gán </td>
<td>$a *= $b</td>
<td>$a sẽ là tích của $a và $b. Tương tự: $a = $a * $b</td>
</tr>
<tr>
<td>/=</td>
<td>Chia rồi gán </td>
<td>$a /= $b</td>
<td>$a sẽ là thương của $a và $b . Tương tự: $a = $a / $b</td>
</tr>
<tr>
<td>%=</td>
<td>chia lấy dư rồi gán </td>
<td>$a %= $b</td>
<td>$a là số dư của phép chia $a / $b.  Tương tự: $a = $a % $b</td></tr>
</table>
  
#### Toán tử so sánh 
 
 <table>
<tr>
<th>Toán tử</th>
<th>Tên </th>
<th>Ví dụ</th>
<th>Giải thích </th>
</tr>
<tr>
<td>==</td>
<td>so sánh bằng </td>
<td>$a == $b</td>
<td>Trả về true nếu $a bằng $b ngược lại trả về fasle. (Không quan tâm tới kiểu của biến )</td>
</tr>
<tr>
<td>===</td>
<td>so sánh bằng </td>
<td>$a === $b</td>
<td>Trả về true nếu $a bằng $b và $a, $b phải cùng loại, ngược lại trả về fasle.</td>
</tr>
<tr>
<td>!==</td>
<td>so sánh không bằng  </td>
<td>$a !== $b</td>
<td>Trả về true nếu $a và $b không bằng nhau và không giống nhau về kiểu dữ liệu</td>
</tr>
<tr>
<td>!=</td>
<td>so sánh không  bằng </td>
<td>$a != $b</td>
<td>Trả về true nếu $a và $b không bằng nhau . (Không quan tâm tới kiểu của biến )</td>
</tr>
<tr>
<td><></td>
<td>so sánh không bằng</td>
<td>$a <> $b</td>
<td>Giống $a != %b </td>
</tr>
<tr>
<td> > </td>
<td> Lớn hơn </td>
<td>$a > $b</td>
<td>Trả về true nếu $a lơn hơn $b</td>
</tr>
<tr>
<td> >= </td>
<td> Lớn hơn hoặc bằng </td>
<td>$a >= $b</td>
<td>Trả về true nếu $a lơn hơn hoặc bằng  $b</td>
</tr>
<tr>
<td> < </td>
<td> nhở hơn </td>
<td>$a < $b</td>
<td>Trả về true nếu $a nhỏ hơn $b  </td>
</tr>
<tr>
<td> <= </td>
<td> Nhỏ hơn hoặc bằng </td>
<td>$a <= $b</td>
<td>Trả về true nếu $a nhỏ  hơn hoặc bằng  $b</td>
</tr>
<tr>
<td> <=> </td>
<td> space ship </td>
<td>$a <=> $b</td>
<td>Trả về -1 nếu $a  nhỏ hơn $b, 0 nếu $a bằng $b và 1 nếu $a > $b</td>
</tr>

</table>

#### Toán tử tăng giảm 
 <table> 
 <tr>
<th>Toán tử</th>
<th>Tên </th>
<th>Ví dụ</th>
<th>Giải thích</th></tr>
<tr>
<td>++</td>
<td>Tăng sau  </td>
<td>$a++</td>
<td>Trả về $a sau đó tăng $a lên 1 đơn vị. Ví dụ : $a = 4; echo $a++ Kết quả là 4</td>
</tr>
<tr>
<td>++</td>
<td>Tăng trước </td>
<td>++$a</td>
<td>Tăng $a lên 1 đơn vị sau đó gán lại cho $a. Ví dụ; $a= 4; echo ++$a;  Kết quả là 5</td>
</tr>
<tr>
<td>--</td>
<td>Giảm trước  </td>
<td>--$a</td>
<td>Giảm $a đi 1 đơn vị rồi gán lại</td>
</tr>
<tr>
<td>--</td>
<td>Giam sau  </td>
<td>$a--</td>
<td>Trả về $a sau đó giảm $a đi 1 đơn vị</td>
</tr>
</table>

 #### Toán tử logic 

 <table>
<tr>
<th>Toán tử</th>
<th>Tên</th>
<th>Ví dụ</th>
<th>Giải thích</th>

</tr>
<tr>
<td>
and
</td>
<td>và</td>
<td>$a and $b</td>
<td>Trả về true nếu $a và $b đúng </td>
</tr>
<tr>
<td>&&</td>
<td> và </td>
<td>$a && $b</td>
<td>Trả về true nếu $a và $b đều đúng. (an toàn hơn and )</td>
</tr>
<tr>
<td>or</td>
<td>Hoặc</td>
<td>$a  or $b</td>
<td>Trả về true nếu có ít nhất 1 biến true</td>
</tr>
<tr>
<td>||</td>
<td>Hoặc</td>
<td>$a  || $b</td>
<td>Trả về true nếu có ít nhất 1 biến true ( an toàn hơn or )</td>
</tr>
<tr>
<td>xor</td>
<td>Tự do</td>
<td>$a  xor $b</td>
<td>Trả về true nếu $a true hoặc $b true nhưng không được cả hai cùng true</td>
</tr>
<tr>
<td>!</td>
<td>Phủ định</td>
<td>!$a</td>
<td>Trả về true nếu $a false</td>
</tr>
</table>
 
#### Toán tử chuyển nhượng có điều kiện 

 <table> 
<tr>
<th>Toán tử</th>
<th>Tên</th>
<th>Ví dụ</th>
<td>Giải thích</td></tr>
<tr>
<td>?:</td>
<td>Toán tử 3 ngôi</td>
<td> $x= condtional ? value1 : value2 </td>
<td>$x nhận giá trị là value1 nếu condition đúng và ngược lại là value2</td>
</tr>
<tr>
<td>??</td>
<td>Toán tử null coaching</td>
<td> $x= $value1 ?? $value2 </td>
<td>$x nhận giá trị là value1 nếu $value1 tồn tai và không null</td>
</tr>

</table>

### Cấu trúc điều khiển 
 
  #### if else statements 

- Câu lệnh điều khiển if /else thực thi khối mã nếu điều kiện là đúng, nếu điều kiện sai sẽ thực hiện khối mã khác 
  ```php 
   if(condition){
  //your code
  }
  else{
  //your code
  }
  ```
  - Câu lệnh if (condition1).. elseif(condition2).. else .Sẽ kiểm tra condition nếu đúng thì sẽ thực thi khối mã, nếu sai sẽ kiểm tra condition2.. nếu không có không có condtion nào true sẽ thực thi khối mã else  
  ```php 
   if(condition1){
  //your code}
  elseif(condition2){
  //your code
  }
  ...
  else{
  //your code
  }
  ```
#### Cấu trúc switch case 
- Cho phép thực thi các hành động khác nhau dựa trên điều kiện  
- Cú pháp : 

    ```php 
  switch(n){
  case label1 : 
  //your code 
  break;
  case label2 : 
  //your code
  break;
  case label3: 
  //your code 
  break ;
  ...
  default: 
  // your code
    ```
 - Khi thực thi mã, biểu thức n sẽ được đánh giá 1 lần và so sánh với từng trường hợp. Nếu thỏa mãn trường hợp nào sẽ thực thi khôi mã của trường hợp đó. 
lệnh `break` được dùng để thoát lệnh. Khối mã trong `default` sẽ được chay khi không có trường hợp nào thỏa mãn 
 
#### Vòng lặp 
 Được sử dụng để thực thi các khối code giống nhau, miễn là điều kiện đúng 
 
#### for  
 - Lặp qua một khối code với số lần cụ thể 
 - cú pháp : 
    ```php 
    for( int counter, conditional , increament counter){
   //your code
   }
   ```
  Khi bắt đầu vòng lặp, biến đếm counter được khởi tạo 1 lần duy nhất trong lần đầu, sau đó kiểm tra điều kiện. Nếu điều kiện đúng, thực thi mã, sau đó tăng giá trị biển đểm lên,
sau đó kiểm tra điều kiện, nếu điều kiện đúng thực hiện lại các bước như trên, ngược lại kết thúc vòng lặp. 
#### foreach: 
 - Dùng để lặp qua các phần tử của 1 mảng.
 - Cú pháp:
   ```php 
    foreach ( $array as $val) 
   {
   // your code
   }
   foreach( $array as $key=>$val){
   //your code 
   }
   ```
#### while : 
 - Thường đưọc dùng cho lặp lại khối mã vơi số lần không biết chính xác 
 - Cú pháp : 
     ```php 
    while(condition)
   {
   //your code
    
   }
     ```
   - Vòng lặp sẽ luôn diễn ra khi điều kiện đúng. chú ý, khi sử dụng while, nếu không chú ý tới điều kiện dễ xảy ra trường hợp lặp vô hạn. 
   
#### Do while 
- Tương tự như `while`, khác là `do while` sẽ thực thi câu lệnh ít nhất 1 lần dù cho điều kiện có đúng không 
- Cú pháp : 
     ```php 
   do{
  //your c
  ode
  }while(condition)
     ```
##### break and contine : 
 Được sử dụng để kết thúc vòng lặp hoặc bỏ qua vòng lặp 
  ###  String  function 

 - Hàm chop(): Dùng để loại bỏ các khoảng trắng hoặc các ký tự được chỉ định .Cú pháp : `chop($string, charlist)`
  ```php 
  $string = "Hello world   ";
 $string2 = "Vu Van Nghia";
 echo $string .$string2 //Hello world  Vu Van Nghia;
 echo chop($string) . $string2 // Hello worldVu Van Nghia;
  ``` 
- chunk_split: Cắt chuỗi thành nhiều chuỗi nhỏ hơn .Cú pháp `chunk_split($string, lengtg, separator)`
   ```php 
   $string = "Hello world";
  echo chunk_split($string,1,'.') 
   ```
- explode: Ngắt 1 chuỗi sang 1 mảng: Cú pháp : `explode(separator,$string, $limit )`
 ```php 
 $string = "hello world, Im a dev";
 $newarr= explode(" ", $string, 2);
 print_r($newarr) 
```
- html_entity_decode: Chuyển các thực thể HTML sang ký tự:  `html_entity_decode($str, flag, character_set)`
  ```php 
   $str = '&lt;a href=&quot;https://www.w3schools.com&quot;&gt;w3schools.com&lt;/a&gt;';
   echo html_entity_decode($str);
  ```
- htmlentities: Chuyển các ký tự HTML sang thực thể : `html_encode(string, flag, character_set,double_encode`
 
 ```php 
 $str = '<a href="https://www.w3schools.com">Go to w3schools.com</a>';
echo htmlentities($str);
 ```
- htmlspecialchars_decode: Chuyển đổi các thực thể HTML được định nghĩa trước sang ký tự. `htmlspecialchars_decode($string, $flag)`

  ```php 
  $string = "Hello world"; 
  echo htmlspecialchars_decode($string);
  ```
- htmlspecialchars: Chuyển đổi các ký tự HTML định nghĩa trước sang thực thể. 
 
  ```php 
  $str = "This is some <b>bold</b> text.";
  echo htmlspecialchars($str); // output: This is some &lt;b&gt;bold&lt;/b&gt; text.
  ```
- implode: Chuyển 1 mảng sang chuỗi : `implode(separator, $array)  `
 
  ```php 
   $array = ['hello', 'world', "how", "are", "you"];
  echo implode('-',$array) //output : hello-world-how-are-you
  ```
- join: Bí danh của hàm implode: `join(separator, $array)`
- ltrim: Loại bỏ các ký tự khoảng trắng hay các ký tự được chỉ định ở bên trái chuỗi. `ltrim($string,listchar)`

  ```php 
   $string = "TThis is test" ;
  echo ltrim($string, "T")//output: his is test
  ```
- md5(): Băm chuỗi . Dùng cho các chữ ký số 
- number_format: Dùng để định dạng số : `number_format(number, decimal, decimalpoint, separator)` 

   ```php 
   echo number_format( 19999.9,2,'-') //output: 19,999-20
   ```
- trim: Loại bỏ các ký tự khoảng trắng hoặc các ký tự chỉ định ở hai đầu của chuỗi :`trim(string, charlist)`

  ```php 
   $string = " Vu Van Nghia ";
  echo "hello world" . $string . "is a dev" //output : hello world Vu Van Nghia is a dev ;
  echo "hello world". trim($string) . "is a dev; //output : hello worldVu Van Nghiais a dev;
  ```
- str_replace: dùng để thay thế các ký tự trong chuỗi . `str_replace(find,replace,string,count)`

   ```php 
  $string = "Hello world";
   echo str_replace ('H','h', $string) //output: hello world
   ```
- str_ireplace: giống `str_replace` nhưng tìm kiếm không phân biệt chữ hoa hay chữ thường

   ```php
  $string = "Hello world , hi you ";
  echo str_ireplace('h','a', $string )//output: aello world , ai you 
   
   ```
- str_repeat: Dùng để lặp lại chuỗi với số lần đưược chỉ định . str_repeat($string, number)
  
  ```php 
   echo str_repeat('nghia',3); //output: nghianghianghia
  ```
- str_shuffle: thay đổi ngẫu nhiên các ký tự của chuỗi `str_shuffle(string)`
- str_split: Tách 1 chuỗi sang mảng. `str_split(string,number)`. Tra về `false` nếu number nhỏ hơn 1
  
   ```php 
   print_r str_split('hello',3)//output: array( [0]=>'hel',[1]=>'lo')
   ```
  
- str_word_count: đếm số từ của chuỗi .`str_word_count(string, return, char). Tham số return nhận 3 giá trị là 0,1,2 xác định cách hàm trả về
 
   ```php  
  print_r str_word_count('vu van nghia' , 1) //output: array( [0]=>'vu',[1]=>'van', [2]=>'nghia']
   ```
- 