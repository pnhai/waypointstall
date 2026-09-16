# Waypointstalls — website

Trang giới thiệu của **Waypointstalls**, ứng dụng tìm sạp nông sản ven đường
(honesty box / farm gate stall) tại Úc.

<https://waypointstalls.permitpal.au>

## Về repo này

Repo chứa **bản build tĩnh đã hoàn chỉnh** (HTML/CSS/JS), không chứa mã nguồn.
Trang được sinh ra từ một project Next.js nằm ở repo khác rồi đồng bộ sang đây,
nên đừng sửa file trong repo này bằng tay — lần build sau sẽ ghi đè.

Hosting: GitHub Pages, phục vụ thẳng từ nhánh mặc định.

- `CNAME` — tên miền tuỳ chỉnh.
- `.nojekyll` — bắt buộc. Không có file này, Pages chạy Jekyll và Jekyll bỏ qua
  mọi thư mục bắt đầu bằng dấu gạch dưới, tức toàn bộ `_next/` (CSS + JS) sẽ
  404 và trang hiện ra không có định dạng.

## Giấy phép

Nội dung và thương hiệu Waypointstalls thuộc về tác giả. Mã nguồn bên thứ ba
trong bản build tuân theo giấy phép gốc của từng thư viện.
