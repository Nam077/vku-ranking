## Mục lục
- [Hướng dẫn sử dụng API](#huong-dan-su-dung-api)
  - [Lấy thông tin bảng xếp hạng](#lay-thong-tin-bang-xep-hang)
  - [Lấy thông tin người chơi](#lay-thong-tin-nguoi-choi)
  - [Thêm điểm cho người chơi](#them-diem-cho-nguoi-choi)
  - [Refresh bảng xếp hạng](#refresh-bang-xep-hang)

## Hướng dẫn sử dụng API

### Lấy thông tin bảng xếp hạng {#huong-dan-su-dung-api}
- Di chuyển vào file `gameScore.js`
- Thay `nameGameRanking` bằng tên game của bạn
- Nếu muốn lấy thông tin của 1 game cụ thể thì thay `nameGameRanking` bằng tên game cần lấy
- Nếu muốn lấy thông tin của tất cả các game thì thay `nameGameRanking` bằng `all`
- Lưu ý cần thêm tất cả các thư viện trong file `index.html`

### Lấy thông tin người chơi
- Sử dụng function `getInforGamePlayer(nameGame, phone)` trong file `main.js`
- Thay `nameGame` bằng tên game của bạn
- Thay `phone` bằng số điện thoại của người chơi

### Thêm điểm cho người chơi
- Sử dụng function `funcCreateScore()` trong file `main.js`
- Thay `namePlayer` bằng tên người chơi
- Thay `nameGame` bằng tên game của bạn
- Thay `phone` bằng số điện thoại của người chơi
- Thay `score` bằng điểm của người chơi

### Refresh bảng xếp hạng
- Sử dụng function `getRanking()` trong file `gameScore.js`
- Thay `nameGameRanking` bằng tên game của bạn
