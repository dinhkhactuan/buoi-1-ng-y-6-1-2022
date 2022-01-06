var test = 20
--tất cả những biến đc khai báo = var là biến toàn cục nghĩa tất cả khối code đều sử dụng được biến này
--và được thay đổi giá trị
let
--chỉ dùng được trong khối code , vùng phạm vi
và được thay đổi giá trị
const
--chỉ dùng được trong khối code , vùng phạm vi
và ko thay đổi giá trị
--muốn thay đổi giá trị phải gán = 1 biến (let const var đều được)
--khi khai báo biến const thì nhất định phải có 1 giá trị
chú ý : tất cả những hàm , if else ... có dấu {} (trừ object) là khối code và phạm vi

\*toán tử
những toán tử có độ ưu tiên cao hơn sẽ thực hiện trc
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence?retiredLocale=vi

chuỗi
khia báo = '' hoặc "" (ko thể chèn được biến)
chuỗi mẫu
khai báo = `` (dùng để chèn biến = chuỗi dùng ${})
if else
nếu nhiều câu lệnh if mà muốn nó thực thi 1 câu lệnh if thì cuối câu lệnh dùng return
\*\* chuyển đổi và cưỡng chế
\*dấu cộng
nếu đằng trước dấu cộng mà là chuỗi thì giá trị đằng sau sẽ chuyển đổi thành chuỗi hết và nối chuỗi
nếu trc dấu cộng ko có gì thì sẽ chuyển giá trị đằng sau thành số(ví dụ +'10')

- dấu trừ
  chuyển đổi chuỗi về số là tính toán như bình thường

toán tử ==
so sánh tương đối (so sánh ko quan tâm về kiểu dữ liệu)
toán tử ===
so sánh tuyệt đối (so sánh cả kiểu dữ liệu)
trả về tru hoặc false
function

// cách 1
function ok() {
console.log("ok"); // function declaration (để bất kỳ đâu gọi cx được)
}
ok();

// cách 2
const oks = function () {
console.log("ok"); (trc khi gọi hàm nó phải được khai báo trc lời gọi hàm)
};
oks();
//cách 3
const okc = () => {
console.log("ok");trc khi gọi hàm nó phải được khai báo trc lời gọi hàm
};
okc();
