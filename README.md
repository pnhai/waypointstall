# Waypointstalls — website

Trang giới thiệu của **Waypointstalls**, ứng dụng tìm sạp nông sản ven đường
(honesty box / farm gate stall) tại Úc.

<https://pnhai.github.io/waypointstall-privacy/>

## Về repo này

Repo chứa **bản build tĩnh đã hoàn chỉnh** (HTML/CSS/JS), không chứa mã nguồn.
Trang được sinh ra từ một project Next.js nằm ở repo khác rồi đồng bộ sang đây,
nên đừng sửa file trong repo này bằng tay — lần build sau sẽ ghi đè.

Hosting: GitHub Pages, phục vụ thẳng từ nhánh mặc định, ở thư mục con
`/waypointstall-privacy/`. Bản build đã được sinh ra với `basePath` đúng theo
đường dẫn đó, nên **không** bê nguyên sang một URL khác được — đổi chỗ thì phải
build lại.

- `.nojekyll` — bắt buộc. Không có file này, Pages chạy Jekyll và Jekyll bỏ qua
  mọi thư mục bắt đầu bằng dấu gạch dưới, tức toàn bộ `_next/` (CSS + JS) sẽ
  404 và trang hiện ra không có định dạng.

## Giấy phép

Nội dung và thương hiệu Waypointstalls thuộc về tác giả. Mã nguồn bên thứ ba
trong bản build tuân theo giấy phép gốc của từng thư viện.
