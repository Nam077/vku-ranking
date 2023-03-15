# Hướng dẫn sử dụng API

## 1. Lấy thông tin bảng xếp hạng

1. Di chuyển vào file `gameScore.js`
2. Thay `nameGameRanking` bằng tên game của bạn
3. Nếu muốn lấy thông tin của 1 game cụ thể thì thay `nameGameRanking` bằng tên game cần lấy
4. Nếu muốn lấy thông tin của tất cả các game thì thay `nameGameRanking` bằng `all`
5. Lưu ý cần thêm tất cả các thư viện trong file `index.html`

## 2. Lấy thông tin người chơi

1. Sử dụng function `getInforGamePlayer(nameGame, phone)` trong file `main.js`
2. Thay `nameGame` bằng tên game của bạn
3. Thay `phone` bằng số điện thoại của người chơi

## 3. Thêm điểm cho người chơi

1. Sử dụng function `funcCreateScore()` trong file `main.js`
2. Thay `namePlayer` bằng tên người chơi
3. Thay `nameGame` bằng tên game của bạn
4. Thay `phone` bằng số điện thoại của người chơi
5. Thay `score` bằng điểm của người chơi

## 4. Refresh bảng xếp hạng

1. Sử dụng function `getRanking()` trong file `gameScore.js`
2. Thay `nameGameRanking` bằng tên game của bạn
