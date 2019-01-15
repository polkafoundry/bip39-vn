Tham khảo danh sách từ (có nhiều trang): https://vi.wiktionary.org/wiki/%C4%90%E1%BA%B7c_bi%E1%BB%87t:M%E1%BB%8Di_b%C3%A0i?namespace=0

> **Assignment**
>
> **pic1**: m,n (nh, ng, ngh),l,h,k (kh)
>
> **brick**: a (ă, â), b, c
>
> **pic2**: d, đ, e (ê), g (gh)
>
> **Huy**: i, o (ô, ơ), p (ph)
>
> **Tín**: q, r
>
> **Việt**: s, y
>
> **Teddy**: t, th, tr, u, ư
>
> **Dương**: v, x

# bip39-vn

Soạn danh sách từ tiếng Việt để làm seed phrase (mnemonic) cho crypto wallet (bip39 standard).

## Độ cần thiết

Seed phase được phát minh để người dùng dễ nhớ, dễ ghi lại vào giấy, có thể đọc cho người khác chép. Tuy nhiên, khi dùng ngôn ngữ nước ngoài (kể cả tiếng Anh) đối với người không phải native thì các lợi thế trên hoàn toàn mất đi.

Vì vậy, cần có danh sách từ tiếng Việt để sử dụng cho người Việt.

## Quy tắc chọn từ

Cần tổng cộng 2048 từ. Các contributor chia theo chữ cái để nhập. Nên sử dụng từ điển để đi theo.

Quy tắc cơ bản:

- Có 4 chữ cái trở lên
- 4 chữ đầu phải khác nhau
- 4 chữ cái đầu nếu chỉ khác nhau về dấu có thể chấp nhận (ví dụ: uống và uổng)
- chọn các từ đời thường, dễ hiểu
- ưu tiên chọn từ đơn
- nếu là từ ghép, viết dấu - để phân cách (ví dụ: bản-năng). Chú ý "bản-năng" và "bản-thể" được coi là trùng lặp vì trùng 4 kí tự đầu
- không chọn từ ghép có tới 3 âm tiết (chỉ tối đa là 2)
- tránh những từ có 2 cách viết (ví dụ: giữ i ngắn và y dài, như kỷ-niệm vs kỉ-niệm)
- tránh những từ mà như thế nào là đúng chính tả đang không rõ ràng, đặc biệt là `d` và `gi` (như giông-tố vs dông-tố, tranh-giành vs tranh-dành)
- thống nhất bỏ dấu theo chuẩn default của bộ gõ hiện đại. Ví dụ: `hoà` (bỏ dấu chữ à) thay vì hòa (bỏ dấu chữ ò)
- hạn chế chọn các từ mà cách viết khó, dễ sai chính thả (ví dụ "khuynh", "ngoằng")
- không dùng các từ vi phạm thuần phong

## Ví dụ

### Vần `b`:
```
bàng-bạc
bằng-lòng
bác-bỏ
bản-năng
bướng
buông
```

> Tham khảo danh sách từ của các ngôn ngữ khác: https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md
