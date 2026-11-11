# Firststep · Khảo sát Mèo hay Chó 🐱🐶

Một trang khảo sát người dùng nhỏ xinh với phong cách chibi: **"Bạn thích mèo hay thích chó?"**

## Tính năng

- Câu hỏi rẽ nhánh: mỗi lựa chọn dẫn tới câu hỏi tiếp theo
- Hình mèo, chó chibi vẽ bằng SVG, đổi màu lông theo từng giống (tam thể, mướp, mun, Corgi, Shiba, đốm…)
- Nút **← Quay lại**, thanh tiến trình dấu chân 🐾, hiệu ứng tim bay
- Màn hình kết quả tóm tắt các lựa chọn, ví dụ: *"Bạn hợp với một bé tam thể chuyên ngủ nướng đó!"*
- Hiển thị tốt trên điện thoại

## Cây câu hỏi

```
Bạn thích mèo hay thích chó?
├── Mèooo → Loại mèo?
│   ├── Mèo ta → Tam thể · Mèo mướp · Mèo vàng · Mèo mun
│   ├── Mèo Anh lông ngắn · Mèo Ba Tư · Mèo Xiêm
│   └──► Tính cách: Lười ngủ · Nghịch phá · Bám người
└── Choóo → Loại chó?
    ├── Chó ta → Vàng · Vện · Mực · Đốm
    ├── Corgi · Shiba · Poodle
    └──► Kích cỡ: Nhỏ xíu · Vừa ôm · To bự
```

### Thêm / sửa nhánh

Toàn bộ câu hỏi nằm trong biến `TREE` ở cuối `index.html`. Mỗi lựa chọn có `next` trỏ tới id câu hỏi tiếp theo; bỏ `next` thì lựa chọn đó kết thúc khảo sát. Màu lông của từng giống nằm trong biến `LOOKS`.

## Cấu trúc

```
Firststep/
├── index.html   # Trang khảo sát (HTML + CSS + JS trong một file)
└── README.md
```

## Chạy thử

Mở trực tiếp `index.html` bằng trình duyệt, hoặc xem qua GitHub Pages:
`https://sniarhuynh0112.github.io/firststep/` (cần bật Pages và để repo ở chế độ public).

## Kế hoạch

- [x] Trang câu hỏi đầu tiên
- [x] Câu hỏi rẽ nhánh theo loại mèo / chó
- [ ] Lưu và thống kê kết quả khảo sát

## Tác giả

**sniarhuynh0112** — [GitHub](https://github.com/sniarhuynh0112)
