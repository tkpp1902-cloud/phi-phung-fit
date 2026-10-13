# PHI PHỤNG FIT — bản cài lên màn hình chính iPhone

Thư mục này là một trang web tĩnh hoàn chỉnh. Không cần máy tính, VS Code hay Terminal.

## Có gì trong thư mục

| Tệp | Công dụng |
|---|---|
| `index.html` | Toàn bộ ứng dụng |
| `manifest.webmanifest` | Tên, icon, chế độ toàn màn hình (standalone) |
| `sw.js` | Service worker: lưu ứng dụng để mở được khi mất mạng |
| `apple-touch-icon.png` | Icon trên màn hình chính iPhone |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Icon cho Android và trình duyệt |

## Đưa lên web HTTPS miễn phí bằng iPhone (GitHub Pages)

1. Mở tệp `.zip` trong ứng dụng **Tệp**, chạm vào nó để giải nén.
2. Trên Safari, vào **github.com** và tạo tài khoản (hoặc đăng nhập).
3. Bấm **+** → **New repository**. Đặt tên `phi-phung-fit`, chọn **Public**, bấm **Create repository**.
4. Trong trang repository vừa tạo, bấm **uploading an existing file** → **choose your files**.
   Chọn **tất cả các tệp** trong thư mục đã giải nén (README.md có hay không cũng được) → **Commit changes**.
5. Vào **Settings** → **Pages**. Ở mục *Source* chọn **Deploy from a branch**, nhánh **main**, thư mục **/(root)** → **Save**.
6. Chờ 1–2 phút, tải lại trang Pages để thấy địa chỉ dạng
   `https://ten-cua-ban.github.io/phi-phung-fit/`.

## Thêm vào màn hình chính

1. Mở địa chỉ trên bằng **Safari** (không dùng trình duyệt trong Zalo/Facebook).
2. Bấm nút **Chia sẻ** → **Thêm vào MH chính** → **Thêm**.
3. Mở từ icon: ứng dụng chạy toàn màn hình, không có thanh địa chỉ.

## Chuyển dữ liệu từ bản trong Claude

1. Trong bản Claude: **Cá nhân** → **Xuất sao lưu** → lưu tệp `.json` vào ứng dụng Tệp.
2. Trong bản trên màn hình chính: **Cá nhân** → **Khôi phục** → **Chọn tệp sao lưu**.

## Giới hạn cần biết

- **Lưu dữ liệu:** nằm ngay trên iPhone (bộ nhớ của ứng dụng web). Không tự đồng bộ với bản trong Claude hay máy khác. Nên **Xuất sao lưu** mỗi tuần.
- **Offline:** mở ứng dụng ít nhất một lần khi có mạng để lưu ứng dụng, phông chữ và thư viện PDF. Sau đó ghi nhật ký, xem thực đơn, đi chợ và tủ lạnh đều dùng được khi mất mạng.
- **Phụng Coach (AI), chia sẻ cho người thân, đồng bộ đám mây:** chỉ chạy trong bản Claude. Bản này hiện rõ là chưa sẵn sàng, không giả lập câu trả lời.
- **Nhắc uống nước:** chỉ hiện khi ứng dụng đang mở. Thông báo đẩy cần máy chủ riêng (giai đoạn sau).
- **Riêng tư:** repository Public nghĩa là ai cũng xem được mã nguồn. Bản này không chứa thông tin sức khỏe của bạn — phần đó bạn tự nhập trong ứng dụng hoặc khôi phục từ bản sao lưu, và chỉ nằm trên máy.

## Cập nhật bản mới

Tải các tệp mới lên đè vào repository (bước 4). Lần mở sau ứng dụng báo có bản cập nhật; đóng hẳn rồi mở lại để dùng bản mới.
