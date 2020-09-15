# React Native Entry Test
## Yêu cầu
 - Sử dụng ngôn ngữ JavaScript để thực hiện các đề bài
 - Sử dụng một số trang share code JavaScript như: [CodePen](https://codepen.io/), [JS Bin](https://jsbin.com/), [SSFiddle](https://jsfiddle.net/), [CodeSandbox](https://codesandbox.io/) ... hoặc một số trang tương tự để upload code và lấy link
## Đề bài
### Bài 1
Viết một hàm (***isValidPassword***) kiểm tra xem một mật khẩu có hợp lệ hay không<br/>
Một mật khẩu được xem là hợp lệ nếu đạt được tất cả các điều kiện sau:
- Dài ít nhất 8 ký tự
- Chứa ít nhất 1 ký tự chữ số
- Chứa ít nhất 2 ký tự chữ thường
- Chứa ít nhất 1 ký tự chữ hoa
- Chứa ít nhất 1 ký tự đặc biệt trong danh sách ***!@#$%^&*()-+***
#### Ví dụ:
- password = ***"a1bc2A"*** thì isValidPassword(password) trả về ***false***
- password = ***"a1bc2A!"*** thì isValidPassword(password) trả về ***false***
- password = ***"a1bc2A!@"*** thì isValidPassword(password) trả về ***true***
#### Đầu vào/Đầu ra:
[Đầu vào] Chuỗi password. ***1 ≤ password.length ≤ 10<sup>5</sup>***<br/>
[Đầu ra] Boolean. Trả về true nếu password là mật khẩu hợp lệ và ngược lại<br/>
### Bài 2 (Không bắt buộc)
Trả lời các câu hỏi sau
#### Câu 1 
Cho đoạn code sau
```javascript
console.log('1');
setTimeout(
  function() {
    console.log('2');
  },
  100
);
console.log('3');
//  với hàm console.log(x); là in x ra màn hình console
```
Hãy dự đoán màn hình console sẽ in ra các số như thế nào, giải thích
#### Câu 2
Cho đoạn code sau
```javascript
const object1 = {
  name: {
    first: "Luca",
    last: "Die"
  }
}

const object2 = object1
object2.name.first = "David"

console.log(object1.name.first);
//  với hàm console.log(x); là in x ra màn hình console
```
Hãy dự đoán màn hình console sẽ in ra giá trị như thế nào, giải thích
