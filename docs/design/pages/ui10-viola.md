# UI10 · Product / Viola

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
Áp dụng [bố cục và quy tắc tab sản phẩm v2](ui05-hestia.md#bố-cục-sản-phẩm-v2) cho thiết bị này. Các bảng bên dưới ghi frame trong snapshot 22/11 và dùng để tra dữ liệu, hình ảnh và trạng thái theo model.

## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI10 / Product / Viola / Desktop | [369:6025](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6025) | 1440 × 4893 |
| UI10 / Product / Viola / Mobile | [369:6417](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6417) | 390 × 6561 |

Các màn hình sản phẩm UI05–UI12 dùng chung cấu trúc component. Tách dữ liệu theo model. Đối chiếu nội dung, ảnh và thông số thật theo từng thiết bị.

## UI10 / Product / Viola / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:6026](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6026) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:6063](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6063) | 80 | 1440 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 120 / 16 / 120 | — |
| Product hero | [369:6074](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6074) | 132 | 1440 × 640 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 24 / 120 / 56 / 120 | — |
| In-page nav | [369:6136](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6136) | 772 | 1440 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:6151](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6151) | 828 | 1440 × 510 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Thông số | [369:6168](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6168) | 1338 | 1440 × 705 | trục HORIZONTAL, wrap NO_WRAP, gap 80, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Cấu hình & tài liệu | [369:6212](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6212) | 2043 | 1440 × 554 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Đào tạo & hậu mãi | [369:6252](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6252) | 2597 | 1440 × 426 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| FAQ | [369:6288](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6288) | 3023 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Liên quan | [369:6313](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6313) | 3518 | 1440 × 818 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| CTA section | [369:6368](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6368) | 4336 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [369:6380](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6380) | 4512 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [369:6411](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6411) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:6026;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I369:6026;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I369:6026;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I369:6026;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I369:6026;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I369:6026;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I369:6026;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I369:6026;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I369:6026;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:6026;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:6026;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I369:6026;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:6064` | 216 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:6064;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:6064;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:6064;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:6064;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:6064;362:278` | 36 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Viola |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Gallery | `369:6076` | 620 × 560 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:6077` | 620 × 460 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · Viola | `369:6078` | 560 × 440 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 |  |
| ↳ Thumbnails | `369:6087` | 88 × 88 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:6088;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 · radius 4 |  |
| Summary | `369:6075` | 524 × 444 | trục VERTICAL, wrap NO_WRAP, gap 18, W FILL, H HUG, grow 1 | — |  |
| ↳ Overline | `369:6090` | 183 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Nâng cơ – Trẻ hóa | `369:6092` | 149 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nâng cơ – Trẻ hóa |
| ↳ H1 | `369:6093` | 524 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Viola |
| ↳ Technology | `369:6094` | 39 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | HIFU |
| ↳ Summary | `369:6095` | 524 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Siêu âm hội tụ cường độ cao (HIFU) cho liệu trình nâng cơ tại cơ sở chuyên môn. |
| ↳ Primary actions | `369:6096` | 524 × 52 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Viola | `369:6097` | 182 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:6097;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Viola | `369:6105` | 166 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:6105;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Viola | `369:6113` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:5228](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5228) |
| ↳ ↳ Label | `I369:6113;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Viola | `369:6123` | 524 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:6123;365:542` | 297 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Viola |
| ↳ ↳ ↳ Meta | `I369:6123;365:543` | 297 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:6123;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:6136;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:6136;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:6136;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:6136;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:6136;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:6136;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:6136;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:6136;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6136;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6152` | 1200 × 140 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6153` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:6155` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:6156` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:6157` | 720 × 56 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:6158` | 1200 × 130 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:6159` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:6160` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Nâng cơ – Trẻ hóa | `369:6161` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Info · Công nghệ | `369:6162` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:6163` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ HIFU | `369:6164` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | HIFU |
| ↳ Info · Đối tượng triển khai | `369:6165` | 384 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:6166` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:6167` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:6169` | 320 × 160 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Heading | `369:6170` | 320 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:6173` | 286 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:6174` | 320 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:6175` | 320 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:6176` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:6176;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:6184` | 800 × 513 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 1 | — |  |
| ↳ Spec · Công nghệ | `369:6185` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Row |
| ↳ ↳ Label | `I369:6185;365:512` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:6185;365:513` | 536 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | HIFU |
| ↳ Spec · Bước sóng | `369:6188` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6188;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:6188;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:6191` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6191;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:6191;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:6194` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6194;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:6194;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:6197` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6197;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:6197;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:6200` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6200;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:6200;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:6203` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6203;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:6203;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:6206` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6206;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:6206;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:6209` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:6209;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:6209;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6213` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6214` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:6216` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:6217` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bàn giao và hồ sơ thiết bị |
| Config | `369:6218` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:6219` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6219;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:6219;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:6229` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6229;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:6229;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:6239` | 1200 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:6239;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:6239;365:541` | 973 × 46 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:6239;365:542` | 973 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Viola |
| ↳ ↳ Meta | `I369:6239;365:543` | 973 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:6239;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:6239;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6253` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6254` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:6256` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:6257` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Hỗ trợ sau khi bàn giao |
| Support | `369:6258` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:6259` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6259;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:6259;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:6269` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6269;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:6269;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:6279` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6279;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:6279;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6289` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6290` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:6292` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:6293` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Trước khi đầu tư thiết bị |
| FAQ list | `369:6294` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:6295` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6295;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:6301` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6301;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:6307` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6307;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6314` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6315` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:6317` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:6318` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:6319` | 1200 × 506 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:6320` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ Image | `I369:6320;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:6320;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:6320;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:6320;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:6320;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:6320;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:6336` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ Image | `I369:6336;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:6336;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:6336;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:6336;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:6336;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:6336;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Dermaxel | `369:6352` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ Image | `I369:6352;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ Need | `I369:6352;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:6352;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ Technology | `I369:6352;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ Summary | `I369:6352;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ Label | `I369:6352;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:6368;365:685` | 948 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I369:6368;365:686` | 310 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Nhận tư vấn cấu hình Viola |
| ↳ Body | `I369:6368;365:687` | 369 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:6368;365:688` | 228 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I369:6368;365:688;360:273` | 152 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Viola |
| ↳ Trailing | `I369:6368;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:6380;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I369:6380;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I369:6380;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:6411;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI10 / Product / Viola / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:6418](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6418) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:6432](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6432) | 64 | 390 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 20 / 16 / 20 | — |
| Product hero | [369:6443](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6443) | 116 | 390 × 936 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 8 / 20 / 32 / 20 | — |
| In-page nav | [369:6505](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6505) | 1052 | 390 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:6520](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6520) | 1108 | 390 × 694 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Thông số | [369:6537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6537) | 1802 | 390 × 923 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Cấu hình & tài liệu | [369:6581](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6581) | 2725 | 390 × 602 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Đào tạo & hậu mãi | [369:6621](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6621) | 3327 | 390 × 592 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| FAQ | [369:6657](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6657) | 3919 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Liên quan | [369:6682](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6682) | 4332 | 390 × 1252 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| CTA section | [369:6721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6721) | 5584 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [369:6733](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6733) | 5824 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [369:6764](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6764) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:6418;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I369:6418;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:6418;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:6418;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I369:6418;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:6433` | 216 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:6433;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:6433;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:6433;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:6433;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:6433;362:278` | 36 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Viola |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Summary | `369:6444` | 350 × 512 | trục VERTICAL, wrap NO_WRAP, gap 14, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6459` | 183 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Nâng cơ – Trẻ hóa | `369:6461` | 149 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nâng cơ – Trẻ hóa |
| ↳ H1 | `369:6462` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Viola |
| ↳ Technology | `369:6463` | 39 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | HIFU |
| ↳ Summary | `369:6464` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Siêu âm hội tụ cường độ cao (HIFU) cho liệu trình nâng cơ tại cơ sở chuyên môn. |
| ↳ Primary actions | `369:6465` | 350 × 116 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Viola | `369:6466` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:6466;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Viola | `369:6474` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:6474;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Viola | `369:6482` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:6482;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Viola | `369:6492` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:6492;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Viola |
| ↳ ↳ ↳ Meta | `I369:6492;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:6492;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |
| Gallery | `369:6445` | 350 × 364 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:6446` | 350 × 280 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · Viola | `369:6447` | 320 × 260 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 |  |
| ↳ Thumbnails | `369:6456` | 72 × 72 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:6457;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 · radius 4 |  |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:6505;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:6505;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:6505;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:6505;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:6505;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:6505;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:6505;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:6505;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:6505;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6521` | 350 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6522` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:6524` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:6525` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:6526` | 350 × 84 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:6527` | 350 × 382 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:6528` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:6529` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Nâng cơ – Trẻ hóa | `369:6530` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Info · Công nghệ | `369:6531` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:6532` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ HIFU | `369:6533` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | HIFU |
| ↳ Info · Đối tượng triển khai | `369:6534` | 350 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:6535` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:6536` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:6538` | 350 × 150 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Heading | `369:6539` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:6542` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:6543` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:6544` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:6545` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:6545;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:6553` | 350 × 657 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ Spec · Công nghệ | `369:6554` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Stacked |
| ↳ ↳ Label | `I369:6554;365:515` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:6554;365:516` | 350 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | HIFU |
| ↳ Spec · Bước sóng | `369:6557` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6557;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:6557;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:6560` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6560;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:6560;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:6563` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6563;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:6563;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:6566` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6566;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:6566;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:6569` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6569;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:6569;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:6572` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6572;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:6572;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:6575` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6575;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:6575;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:6578` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:6578;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:6578;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6582` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6583` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:6585` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:6586` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bàn giao và hồ sơ thiết bị |
| Config | `369:6587` | 350 × 272 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:6588` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6588;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:6588;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:6598` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6598;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:6598;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:6608` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:6608;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:6608;365:541` | 123 × 90 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:6608;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Viola |
| ↳ ↳ Meta | `I369:6608;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:6608;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:6608;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6622` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6623` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:6625` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:6626` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Hỗ trợ sau khi bàn giao |
| Support | `369:6627` | 350 × 410 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:6628` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6628;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:6628;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:6638` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6638;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:6638;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:6648` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:6648;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:6648;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6658` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6659` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:6661` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:6662` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Trước khi đầu tư thiết bị |
| FAQ list | `369:6663` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:6664` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6664;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:6670` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6670;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:6676` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:6676;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:6683` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:6684` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:6686` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:6687` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:6688` | 350 × 1036 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:6689` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ Image | `I369:6689;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:6689;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:6689;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:6689;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:6689;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:6689;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:6705` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3435](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3435) |
| ↳ ↳ ↳ Image | `I369:6705;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:6705;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:6705;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:6705;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:6705;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:6705;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:6721;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I369:6721;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nhận tư vấn cấu hình Viola |
| ↳ Body | `I369:6721;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:6721;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I369:6721;365:702;360:273` | 152 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Viola |
| ↳ Trailing | `I369:6721;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:6733;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I369:6733;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:6764;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
