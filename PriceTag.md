# PriceTag

Viên thuốc hiển thị giá dịch vụ phụ, luôn ghi USD và VND: `$30/800.000VND`.

- **Bản đỏ (mặc định)**: nền `price-red`, bo `radius-pill`, chữ `on-dark` kiểu `price` (DT-Phudu 700), padding `space-2` × `space-3`, viền sáng `cream` 3px và bóng `shadow-card`. Dùng trên thẻ `sky-tint`/`surface` và tem đè giá in rời (16 × 3,2 cm).
- **Bản sáng (trên ảnh)**: nền gradient `brand-ice` → `sky-tint`, chữ `brand-navy`, viền trắng 3px, bóng `shadow-card`. Dùng trên poster báo giá onsite có ảnh ruộng bậc thang, xếp dọc dưới tên gói (“Drone HOẶC Insta360”, “COMBO Drone VÀ Insta360”) và kèm chú thích `caption` “*áp dụng theo từng khách” / “*per person” ngay dưới.
- **Nội dung người dùng cung cấp**: giá USD và giá VND. Viết `$<USD>/<VND có dấu chấm>VND`, không cách giữa số và “VND”.
- **Nên**: một PriceTag cho mỗi dịch vụ; kèm nhãn “★ SAVE 20%” (Phudu, `brand-navy`) phía trên khi là combo; chữ “COMBO / BOTH” trong tên gói tô `brand-gold`.
- **Không nên**: dùng bản đỏ trực tiếp trên ảnh; viết giá chỉ một loại tiền; dùng PriceTag cho giá gói bay chính (dùng PriceHero).
