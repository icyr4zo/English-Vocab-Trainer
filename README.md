# English Vocab

Ứng dụng flashcard học từ vựng tiếng Anh với giao diện Night Mode. Chạy trực tiếp trên trình duyệt, không cần cài đặt.

## Cách chạy
1. Tải project về và giải nén.
2. Mở `index.html` bằng Chrome, Edge hoặc Firefox.
3. Chọn **Flashcards** để học, **Quiz** để tự kiểm tra, hoặc **Kho từ vựng** để quản lý từ.

## Tính năng
- Giao diện Night Mode, tên **English Vocab** và logo chữ **K**.
- Flashcards có phiên âm, nghĩa tiếng Việt, ví dụ và bản dịch ví dụ.
- Quiz trắc nghiệm và thống kê tiến độ.
- Thêm, sửa, xóa, tìm kiếm và lọc từ theo chủ đề/trạng thái.
- Nhập/xuất JSON để thêm nhiều từ và sao lưu dữ liệu.
- Có 20 từ mẫu ban đầu. Bạn có thể tiếp tục mở rộng kho từ; ứng dụng không đặt giới hạn số từ cố định trong code. Dung lượng thực tế tùy trình duyệt.

## Muốn thêm từ vựng thì làm thế nào?

**Cách 1 — Thêm trực tiếp trong ứng dụng**
1. Mở ứng dụng.
2. Chọn tab **Thêm từ**.
3. Điền từ tiếng Anh, nghĩa tiếng Việt và các thông tin tùy chọn.
4. Bấm **Lưu từ**.

**Cách 2 — Nhập thêm một bộ từ bằng JSON**
1. Chuẩn bị file JSON chứa các từ cần thêm.
2. Trong ứng dụng, bấm **Nhập JSON** ở góc trên.
3. Chọn file JSON của bạn.
4. Xác nhận nhập. Ứng dụng sẽ gộp các từ vào kho hiện tại; dữ liệu có cùng ID sẽ được thay thế.

Ví dụ định dạng JSON tối giản:

```json
[
  {
    "english": "resilient",
    "phonetic": "/rɪˈzɪliənt/",
    "vietnamese": "kiên cường",
    "topic": "Personality",
    "example": "She is resilient.",
    "exampleVi": "Cô ấy rất kiên cường."
  },
  {
    "english": "curious",
    "vietnamese": "tò mò",
    "topic": "Personality"
  }
]
```

Các trường bắt buộc là `english` và `vietnamese`. Những trường khác có thể bỏ qua. File JSON phải đúng cú pháp: dùng dấu ngoặc kép quanh tên trường và giá trị dạng chữ; không thêm dấu phẩy sau phần tử cuối cùng.

**Lưu ý:** Nút **Nhập JSON** dùng để nhập file `.json`, không phải để dán trực tiếp văn bản vào ô nhập. Nếu chỉ muốn thêm một vài từ, tab **Thêm từ** sẽ đơn giản hơn.

## Sao lưu và chuyển dữ liệu
- Bấm **Xuất JSON** để tải file sao lưu.
- Trên thiết bị/trình duyệt khác, mở ứng dụng rồi bấm **Nhập JSON** và chọn file sao lưu.
- Dữ liệu được lưu trong `localStorage` của trình duyệt hiện tại. Xóa dữ liệu trình duyệt có thể làm mất bộ từ, vì vậy hãy sao lưu định kỳ.
- Không có giới hạn từ cố định trong ứng dụng, nhưng dung lượng lưu trữ thực tế phụ thuộc trình duyệt và thiết bị.

## Đưa lên GitHub Pages
1. Tạo repository GitHub mới và tải `index.html` lên thư mục gốc.
2. Vào **Settings → Pages**.
3. Chọn deploy từ branch `main`, thư mục `/ (root)`, rồi lưu.
4. Mở URL GitHub Pages mà GitHub cung cấp.

Sau khi đưa lên GitHub Pages, mỗi người dùng vẫn lưu dữ liệu riêng trong trình duyệt của họ. Bộ từ không tự đồng bộ giữa các người dùng.
