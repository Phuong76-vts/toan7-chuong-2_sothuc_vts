# Hành Trình Số Thực · Toán 7 KNTT

Bài giảng tương tác Chương II (Số thực): Bài 5, 6, 7, mỗi bài có 6 chặng (Khởi động, Khám phá, Kiến thức, Ví dụ, Luyện tập, Vận dụng), khu trò chơi, thử thách 10 câu, đấu trường cả lớp và chế độ trình chiếu.

Đây là trang web tĩnh: chỉ có một file `index.html`, không cần cài đặt hay build.

## Đưa lên Vercel (qua GitHub)

1. Vào github.com, tạo kho mới (New repository), ví dụ `so-thuc-toan7`. Chọn Public hoặc Private đều được.
2. Bấm "uploading an existing file", kéo thả 3 file `index.html`, `vercel.json`, `.gitignore` (và `README.md` nếu muốn) vào, rồi bấm Commit changes.
3. Vào vercel.com/new, đăng nhập bằng tài khoản GitHub, chọn kho `so-thuc-toan7`, bấm Import.
4. Ở màn hình cấu hình giữ nguyên: Framework Preset là **Other**, để trống Build Command và Output Directory. Bấm **Deploy**.
5. Sau khoảng 30 giây Vercel cấp một đường link dạng `https://so-thuc-toan7.vercel.app`. Gửi link này cho học sinh.

## Cập nhật nội dung

Sửa file `index.html` trên GitHub (hoặc trên máy rồi push). Vercel tự động triển khai lại sau mỗi lần commit.

## Triển khai nhanh bằng dòng lệnh (không cần GitHub)

```
npm i -g vercel
cd so-thuc-toan7
vercel --prod
```

## Ghi chú

- Tiến độ, XP và huy hiệu của học sinh lưu ngay trên trình duyệt của từng em, không gửi về máy chủ nào.
- Trang dùng phông chữ Google Fonts nên cần có mạng lần đầu. Nếu mất mạng, trang vẫn chạy với phông thay thế.
- Muốn dùng tên miền riêng: Vercel, Settings, Domains.
