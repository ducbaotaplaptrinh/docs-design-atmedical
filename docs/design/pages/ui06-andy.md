# UI06 · Product / Andy

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
Áp dụng [bố cục và quy tắc tab sản phẩm v2](ui05-hestia.md#bố-cục-sản-phẩm-v2) cho thiết bị này. Các bảng bên dưới ghi frame trong snapshot 22/11 và dùng để tra dữ liệu, hình ảnh và trạng thái theo model.

## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI06 / Product / Andy / Desktop | [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) | 1440 × 4893 |
| UI06 / Product / Andy / Mobile | [369:3435](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3435) | 390 × 6561 |

Các màn hình sản phẩm UI05–UI12 dùng chung cấu trúc component. Tách dữ liệu theo model. Đối chiếu nội dung, ảnh và thông số thật theo từng thiết bị.

## UI06 / Product / Andy / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:3044](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3044) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:3081](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3081) | 80 | 1440 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 120 / 16 / 120 | — |
| Product hero | [369:3092](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3092) | 132 | 1440 × 640 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 24 / 120 / 56 / 120 | — |
| In-page nav | [369:3154](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3154) | 772 | 1440 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:3169](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3169) | 828 | 1440 × 510 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Thông số | [369:3186](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3186) | 1338 | 1440 × 705 | trục HORIZONTAL, wrap NO_WRAP, gap 80, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Cấu hình & tài liệu | [369:3230](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3230) | 2043 | 1440 × 554 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Đào tạo & hậu mãi | [369:3270](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3270) | 2597 | 1440 × 426 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| FAQ | [369:3306](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3306) | 3023 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Liên quan | [369:3331](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3331) | 3518 | 1440 × 818 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| CTA section | [369:3386](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3386) | 4336 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [369:3398](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3398) | 4512 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [369:3429](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3429) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:3044;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I369:3044;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I369:3044;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I369:3044;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I369:3044;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I369:3044;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I369:3044;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I369:3044;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I369:3044;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:3044;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:3044;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I369:3044;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:3082` | 216 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:3082;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:3082;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:3082;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:3082;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:3082;362:278` | 36 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Andy |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Gallery | `369:3094` | 620 × 560 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:3095` | 620 × 460 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · Andy | `369:3096` | 560 × 440 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ Thumbnails | `369:3105` | 88 × 88 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:3106;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 4 |  |
| Summary | `369:3093` | 524 × 444 | trục VERTICAL, wrap NO_WRAP, gap 18, W FILL, H HUG, grow 1 | — |  |
| ↳ Overline | `369:3108` | 241 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Xóa xăm – Điều trị sắc tố | `369:3110` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ H1 | `369:3111` | 524 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Andy |
| ↳ Technology | `369:3112` | 111 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Laser Nd:YAG |
| ↳ Summary | `369:3113` | 524 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ Primary actions | `369:3114` | 524 × 52 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Andy | `369:3115` | 182 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:3115;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Andy | `369:3123` | 166 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:4156](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4156) |
| ↳ ↳ ↳ Label | `I369:3123;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Andy | `369:3131` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:3131;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Andy | `369:3141` | 524 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:3141;365:542` | 297 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Andy |
| ↳ ↳ ↳ Meta | `I369:3141;365:543` | 297 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:3141;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:3154;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:3154;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:3154;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:3154;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:3154;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:3154;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:3154;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:3154;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3154;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3170` | 1200 × 140 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3171` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:3173` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:3174` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:3175` | 720 × 56 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:3176` | 1200 × 130 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:3177` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:3178` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Xóa xăm – Điều trị sắc tố | `369:3179` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Info · Công nghệ | `369:3180` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:3181` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Laser Nd:YAG | `369:3182` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Laser Nd:YAG |
| ↳ Info · Đối tượng triển khai | `369:3183` | 384 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:3184` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:3185` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:3187` | 320 × 160 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Heading | `369:3188` | 320 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:3191` | 286 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:3192` | 320 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:3193` | 320 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:3194` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:3194;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:3202` | 800 × 513 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 1 | — |  |
| ↳ Spec · Công nghệ | `369:3203` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Row |
| ↳ ↳ Label | `I369:3203;365:512` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:3203;365:513` | 536 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Laser Nd:YAG |
| ↳ Spec · Bước sóng | `369:3206` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3206;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:3206;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:3209` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3209;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:3209;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:3212` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3212;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:3212;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:3215` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3215;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:3215;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:3218` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3218;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:3218;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:3221` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3221;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:3221;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:3224` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3224;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:3224;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:3227` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3227;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:3227;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3231` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3232` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:3234` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:3235` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bàn giao và hồ sơ thiết bị |
| Config | `369:3236` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:3237` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3237;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:3237;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:3247` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3247;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:3247;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:3257` | 1200 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:3257;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:3257;365:541` | 973 × 46 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:3257;365:542` | 973 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Andy |
| ↳ ↳ Meta | `I369:3257;365:543` | 973 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:3257;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:3257;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3271` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3272` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:3274` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:3275` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Hỗ trợ sau khi bàn giao |
| Support | `369:3276` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:3277` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3277;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:3277;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:3287` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3287;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:3287;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:3297` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3297;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:3297;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3307` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3308` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:3310` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:3311` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Trước khi đầu tư thiết bị |
| FAQ list | `369:3312` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:3313` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3313;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:3319` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3319;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:3325` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3325;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3332` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3333` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:3335` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:3336` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:3337` | 1200 × 506 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Trisis Plus | `369:3338` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:6769](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6769) |
| ↳ ↳ ↳ Image | `I369:3338;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 4962efe977c0b039a814323d325b97e5205828ed |  |
| ↳ ↳ ↳ Need | `I369:3338;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:3338;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Trisis Plus |
| ↳ ↳ ↳ Technology | `I369:3338;364:414` | 116 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị xóa xăm |
| ↳ ↳ ↳ Summary | `I369:3338;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị hỗ trợ liệu trình xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:3338;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Hestia | `369:3354` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ Image | `I369:3354;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:3354;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:3354;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:3354;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:3354;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:3354;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Dermaxel | `369:3370` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ Image | `I369:3370;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ Need | `I369:3370;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:3370;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ Technology | `I369:3370;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ Summary | `I369:3370;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ Label | `I369:3370;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:3386;365:685` | 948 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I369:3386;365:686` | 311 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Nhận tư vấn cấu hình Andy |
| ↳ Body | `I369:3386;365:687` | 369 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:3386;365:688` | 228 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I369:3386;365:688;360:273` | 152 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Andy |
| ↳ Trailing | `I369:3386;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:3398;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I369:3398;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I369:3398;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:3429;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI06 / Product / Andy / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:3436](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3436) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:3450](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3450) | 64 | 390 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 20 / 16 / 20 | — |
| Product hero | [369:3461](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3461) | 116 | 390 × 936 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 8 / 20 / 32 / 20 | — |
| In-page nav | [369:3523](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3523) | 1052 | 390 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:3538](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3538) | 1108 | 390 × 694 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Thông số | [369:3555](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3555) | 1802 | 390 × 923 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Cấu hình & tài liệu | [369:3599](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3599) | 2725 | 390 × 602 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Đào tạo & hậu mãi | [369:3639](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3639) | 3327 | 390 × 592 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| FAQ | [369:3675](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3675) | 3919 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Liên quan | [369:3700](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3700) | 4332 | 390 × 1252 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| CTA section | [369:3739](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3739) | 5584 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [369:3751](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3751) | 5824 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [369:3782](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3782) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:3436;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I369:3436;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:3436;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:3436;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I369:3436;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:3451` | 216 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:3451;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:3451;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:3451;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:3451;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:3451;362:278` | 36 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Andy |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Summary | `369:3462` | 350 × 512 | trục VERTICAL, wrap NO_WRAP, gap 14, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3477` | 241 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Xóa xăm – Điều trị sắc tố | `369:3479` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ H1 | `369:3480` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Andy |
| ↳ Technology | `369:3481` | 111 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Laser Nd:YAG |
| ↳ Summary | `369:3482` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ Primary actions | `369:3483` | 350 × 116 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Andy | `369:3484` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:3484;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Andy | `369:3492` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:3492;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Andy | `369:3500` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:3500;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Andy | `369:3510` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:3510;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Andy |
| ↳ ↳ ↳ Meta | `I369:3510;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:3510;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |
| Gallery | `369:3463` | 350 × 364 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:3464` | 350 × 280 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · Andy | `369:3465` | 320 × 260 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ Thumbnails | `369:3474` | 72 × 72 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:3475;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 4 |  |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:3523;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:3523;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:3523;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:3523;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:3523;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:3523;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:3523;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:3523;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3523;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3539` | 350 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3540` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:3542` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:3543` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:3544` | 350 × 84 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:3545` | 350 × 382 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:3546` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:3547` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Xóa xăm – Điều trị sắc tố | `369:3548` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Info · Công nghệ | `369:3549` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:3550` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Laser Nd:YAG | `369:3551` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Laser Nd:YAG |
| ↳ Info · Đối tượng triển khai | `369:3552` | 350 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:3553` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:3554` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:3556` | 350 × 150 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Heading | `369:3557` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:3560` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:3561` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:3562` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:3563` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:3563;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:3571` | 350 × 657 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ Spec · Công nghệ | `369:3572` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Stacked |
| ↳ ↳ Label | `I369:3572;365:515` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:3572;365:516` | 350 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Laser Nd:YAG |
| ↳ Spec · Bước sóng | `369:3575` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3575;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:3575;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:3578` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3578;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:3578;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:3581` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3581;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:3581;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:3584` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3584;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:3584;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:3587` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3587;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:3587;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:3590` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3590;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:3590;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:3593` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3593;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:3593;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:3596` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:3596;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:3596;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3600` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3601` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:3603` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:3604` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bàn giao và hồ sơ thiết bị |
| Config | `369:3605` | 350 × 272 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:3606` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3606;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:3606;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:3616` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3616;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:3616;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:3626` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:3626;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:3626;365:541` | 123 × 90 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:3626;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Andy |
| ↳ ↳ Meta | `I369:3626;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:3626;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:3626;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3640` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3641` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:3643` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:3644` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Hỗ trợ sau khi bàn giao |
| Support | `369:3645` | 350 × 410 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:3646` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3646;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:3646;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:3656` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3656;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:3656;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:3666` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3666;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:3666;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3676` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3677` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:3679` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:3680` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Trước khi đầu tư thiết bị |
| FAQ list | `369:3681` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:3682` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3682;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:3688` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3688;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:3694` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:3694;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3701` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3702` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:3704` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:3705` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:3706` | 350 × 1036 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Trisis Plus | `369:3707` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:7161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7161) |
| ↳ ↳ ↳ Image | `I369:3707;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 4962efe977c0b039a814323d325b97e5205828ed |  |
| ↳ ↳ ↳ Need | `I369:3707;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:3707;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Trisis Plus |
| ↳ ↳ ↳ Technology | `I369:3707;364:414` | 116 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị xóa xăm |
| ↳ ↳ ↳ Summary | `I369:3707;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị hỗ trợ liệu trình xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:3707;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Hestia | `369:3723` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ Image | `I369:3723;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:3723;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:3723;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:3723;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:3723;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:3723;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:3739;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I369:3739;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nhận tư vấn cấu hình Andy |
| ↳ Body | `I369:3739;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:3739;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I369:3739;365:702;360:273` | 152 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Andy |
| ↳ Trailing | `I369:3739;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:3751;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I369:3751;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:3782;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
