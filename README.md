# bip39-vn

Soạn danh sách từ tiếng Việt để làm seed phrase (mnemonic) cho crypto wallet (bip39 standard).

## Độ cần thiết

Seed phase được phát minh để người dùng dễ nhớ, dễ ghi lại vào giấy, có thể đọc cho người khác chép. Tuy nhiên, khi dùng ngôn ngữ nước ngoài (kể cả tiếng Anh) đối với người không phải native thì các lợi thế trên hoàn toàn mất đi.

Vì vậy, cần có danh sách từ tiếng Việt để sử dụng cho người Việt.

## Quy tắc chọn từ

Cần tổng cộng 2048 từ. Các contributor chia theo chữ cái để nhập.

Quy tắc cơ bản:

- Có 4 chữ cái trở lên
- 4 chữ đầu phải khác nhau
- 4 chữ cái đầu nếu chỉ khác nhau về dấu có thể chấp nhận (ví dụ: uống và uổng)
- chọn các từ đời thường, dễ hiểu
- ưu tiên chọn từ đơn, khi không tìm ra từ đơn nữa mới dùng từ ghép
- nếu là từ ghép, viết dấu - để phân cách (ví dụ: bản-năng). Chú ý "bản-năng" và "bản-thể" được coi là trùng lặp vì trùng 4 kí tự đầu
- không chọn từ ghép có tới 3 âm tiết (chỉ tối đa là 2)
- tránh những từ có 2 cách viết (ví dụ: giữ i ngắn và y dài, như kỷ-niệm vs kỉ-niệm)
- tránh những từ mà như thế nào là đúng chính tả đang không rõ ràng, đặc biệt là `d` và `gi` (như giông-tố vs dông-tố, tranh-giành vs tranh-dành)
- thống nhất bỏ dấu theo chuẩn default của bộ gõ hiện đại. Ví dụ: `hoà` (bỏ dấu chữ à) thay vì hòa (bỏ dấu chữ ò)
- hạn chế chọn các từ mà cách viết khó, dễ sai chính thả (ví dụ "khuynh", "ngoằng")
