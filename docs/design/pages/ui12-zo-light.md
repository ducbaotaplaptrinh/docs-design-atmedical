# UI12 · Product / ZO Light

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
Áp dụng [bố cục và quy tắc tab sản phẩm v2](ui05-hestia.md#bố-cục-sản-phẩm-v2) cho thiết bị này. Các bảng bên dưới ghi frame trong snapshot 22/11 và dùng để tra dữ liệu, hình ảnh và trạng thái theo model.

## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI12 / Product / ZO Light / Desktop | [369:7513](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7513) | 1440 × 4893 |
| UI12 / Product / ZO Light / Mobile | [369:7905](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7905) | 390 × 6561 |

Các màn hình sản phẩm UI05–UI12 dùng chung cấu trúc component. Tách dữ liệu theo model. Đối chiếu nội dung, ảnh và thông số thật theo từng thiết bị.

## UI12 / Product / ZO Light / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:7514](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7514) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:7551](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7551) | 80 | 1440 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 120 / 16 / 120 | — |
| Product hero | [369:7562](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7562) | 132 | 1440 × 640 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 24 / 120 / 56 / 120 | — |
| In-page nav | [369:7624](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7624) | 772 | 1440 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:7639](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7639) | 828 | 1440 × 510 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Thông số | [369:7656](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7656) | 1338 | 1440 × 705 | trục HORIZONTAL, wrap NO_WRAP, gap 80, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Cấu hình & tài liệu | [369:7700](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7700) | 2043 | 1440 × 554 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Đào tạo & hậu mãi | [369:7740](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7740) | 2597 | 1440 × 426 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| FAQ | [369:7776](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7776) | 3023 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Liên quan | [369:7801](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7801) | 3518 | 1440 × 818 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| CTA section | [369:7856](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7856) | 4336 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [369:7868](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7868) | 4512 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [369:7899](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7899) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:7514;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I369:7514;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I369:7514;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I369:7514;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I369:7514;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I369:7514;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I369:7514;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I369:7514;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I369:7514;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:7514;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:7514;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I369:7514;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:7552` | 240 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:7552;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:7552;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:7552;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:7552;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:7552;362:278` | 60 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | ZO Light |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Gallery | `369:7564` | 620 × 560 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:7565` | 620 × 460 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · ZO Light | `369:7566` | 560 × 440 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 |  |
| ↳ Thumbnails | `369:7575` | 88 × 88 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:7576;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 · radius 4 |  |
| Summary | `369:7563` | 524 × 444 | trục VERTICAL, wrap NO_WRAP, gap 18, W FILL, H HUG, grow 1 | — |  |
| ↳ Overline | `369:7578` | 121 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Triệt lông | `369:7580` | 87 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Triệt lông |
| ↳ H1 | `369:7581` | 524 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | ZO Light |
| ↳ Technology | `369:7582` | 138 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thiết bị triệt lông |
| ↳ Summary | `369:7583` | 524 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thiết bị triệt lông dùng tại phòng khám và spa chuyên nghiệp. |
| ↳ Primary actions | `369:7584` | 524 × 52 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · ZO Light | `369:7585` | 182 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:7585;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · ZO Light | `369:7593` | 166 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:7593;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · ZO Light | `369:7601` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:7601;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · ZO Light | `369:7611` | 524 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:7611;365:542` | 297 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue ZO Light |
| ↳ ↳ ↳ Meta | `I369:7611;365:543` | 297 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:7611;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:7624;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:7624;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:7624;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:7624;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:7624;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:7624;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:7624;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:7624;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7624;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:7640` | 1200 × 140 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7641` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:7643` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:7644` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:7645` | 720 × 56 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:7646` | 1200 × 130 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:7647` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:7648` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Triệt lông | `369:7649` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Triệt lông |
| ↳ Info · Công nghệ | `369:7650` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:7651` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Thiết bị triệt lông | `369:7652` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Thiết bị triệt lông |
| ↳ Info · Đối tượng triển khai | `369:7653` | 384 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:7654` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:7655` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:7657` | 320 × 160 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Heading | `369:7658` | 320 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:7661` | 286 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:7662` | 320 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:7663` | 320 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:7664` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:7664;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:7672` | 800 × 513 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 1 | — |  |
| ↳ Spec · Công nghệ | `369:7673` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Row |
| ↳ ↳ Label | `I369:7673;365:512` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:7673;365:513` | 536 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thiết bị triệt lông |
| ↳ Spec · Bước sóng | `369:7676` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7676;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:7676;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:7679` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7679;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:7679;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:7682` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7682;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:7682;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:7685` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7685;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:7685;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:7688` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7688;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:7688;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:7691` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7691;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:7691;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:7694` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7694;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:7694;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:7697` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:7697;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:7697;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:7701` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7702` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:7704` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:7705` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bàn giao và hồ sơ thiết bị |
| Config | `369:7706` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:7707` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:7707;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:7707;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:7717` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:7717;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:7717;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:7727` | 1200 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:7727;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:7727;365:541` | 973 × 46 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:7727;365:542` | 973 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue ZO Light |
| ↳ ↳ Meta | `I369:7727;365:543` | 973 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:7727;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:7727;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:7741` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7742` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:7744` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:7745` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Hỗ trợ sau khi bàn giao |
| Support | `369:7746` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:7747` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:7747;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:7747;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:7757` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:7757;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:7757;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:7767` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:7767;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:7767;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:7777` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7778` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:7780` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:7781` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Trước khi đầu tư thiết bị |
| FAQ list | `369:7782` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:7783` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:7783;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:7789` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:7789;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:7795` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:7795;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:7802` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7803` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:7805` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:7806` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:7807` | 1200 × 506 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:7808` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ Image | `I369:7808;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:7808;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:7808;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:7808;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:7808;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:7808;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:7824` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ Image | `I369:7824;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:7824;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:7824;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:7824;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:7824;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:7824;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Dermaxel | `369:7840` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ Image | `I369:7840;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ Need | `I369:7840;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:7840;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ Technology | `I369:7840;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ Summary | `I369:7840;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ Label | `I369:7840;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:7856;365:685` | 921 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I369:7856;365:686` | 351 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Nhận tư vấn cấu hình ZO Light |
| ↳ Body | `I369:7856;365:687` | 369 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:7856;365:688` | 255 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I369:7856;365:688;360:273` | 179 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá ZO Light |
| ↳ Trailing | `I369:7856;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:7868;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I369:7868;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I369:7868;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:7899;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI12 / Product / ZO Light / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:7906](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7906) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:7920](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7920) | 64 | 390 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 20 / 16 / 20 | — |
| Product hero | [369:7931](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7931) | 116 | 390 × 936 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 8 / 20 / 32 / 20 | — |
| In-page nav | [369:7993](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7993) | 1052 | 390 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:8008](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8008) | 1108 | 390 × 694 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Thông số | [369:8025](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8025) | 1802 | 390 × 923 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Cấu hình & tài liệu | [369:8069](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8069) | 2725 | 390 × 602 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Đào tạo & hậu mãi | [369:8109](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8109) | 3327 | 390 × 592 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| FAQ | [369:8145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8145) | 3919 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Liên quan | [369:8170](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8170) | 4332 | 390 × 1252 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| CTA section | [369:8209](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8209) | 5584 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [369:8221](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8221) | 5824 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [369:8252](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-8252) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:7906;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I369:7906;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:7906;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:7906;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I369:7906;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:7921` | 240 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:7921;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:7921;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:7921;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:7921;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:7921;362:278` | 60 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | ZO Light |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Summary | `369:7932` | 350 × 512 | trục VERTICAL, wrap NO_WRAP, gap 14, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:7947` | 121 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Triệt lông | `369:7949` | 87 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Triệt lông |
| ↳ H1 | `369:7950` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | ZO Light |
| ↳ Technology | `369:7951` | 138 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thiết bị triệt lông |
| ↳ Summary | `369:7952` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thiết bị triệt lông dùng tại phòng khám và spa chuyên nghiệp. |
| ↳ Primary actions | `369:7953` | 350 × 116 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · ZO Light | `369:7954` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:7954;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · ZO Light | `369:7962` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:7962;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · ZO Light | `369:7970` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:7970;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · ZO Light | `369:7980` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:7980;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue ZO Light |
| ↳ ↳ ↳ Meta | `I369:7980;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:7980;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |
| Gallery | `369:7933` | 350 × 364 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:7934` | 350 × 280 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Image 1 · ZO Light | `369:7935` | 320 × 260 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 |  |
| ↳ Thumbnails | `369:7944` | 72 × 72 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I369:7945;365:507` | 72 × 72 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 · radius 4 |  |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:7993;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:7993;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:7993;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:7993;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:7993;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:7993;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:7993;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:7993;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:7993;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:8009` | 350 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:8010` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:8012` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:8013` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:8014` | 350 × 84 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:8015` | 350 × 382 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:8016` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:8017` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Triệt lông | `369:8018` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Triệt lông |
| ↳ Info · Công nghệ | `369:8019` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:8020` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Thiết bị triệt lông | `369:8021` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Thiết bị triệt lông |
| ↳ Info · Đối tượng triển khai | `369:8022` | 350 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:8023` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:8024` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:8026` | 350 × 150 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Heading | `369:8027` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:8030` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:8031` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:8032` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:8033` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:8033;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:8041` | 350 × 657 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ Spec · Công nghệ | `369:8042` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Verified, Layout=Stacked |
| ↳ ↳ Label | `I369:8042;365:515` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:8042;365:516` | 350 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thiết bị triệt lông |
| ↳ Spec · Bước sóng | `369:8045` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8045;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:8045;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:8048` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8048;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:8048;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:8051` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8051;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:8051;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:8054` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8054;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:8054;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:8057` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8057;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:8057;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:8060` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8060;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:8060;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:8063` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8063;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:8063;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:8066` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:8066;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:8066;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:8070` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:8071` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:8073` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:8074` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bàn giao và hồ sơ thiết bị |
| Config | `369:8075` | 350 × 272 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:8076` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:8076;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:8076;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:8086` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:8086;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:8086;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:8096` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:8096;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:8096;365:541` | 123 × 90 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:8096;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue ZO Light |
| ↳ ↳ Meta | `I369:8096;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:8096;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:8096;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:8110` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:8111` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:8113` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:8114` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Hỗ trợ sau khi bàn giao |
| Support | `369:8115` | 350 × 410 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:8116` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:8116;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:8116;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:8126` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:8126;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:8126;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:8136` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:8136;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:8136;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:8146` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:8147` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:8149` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:8150` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Trước khi đầu tư thiết bị |
| FAQ list | `369:8151` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:8152` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:8152;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:8158` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:8158;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:8164` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:8164;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:8171` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:8172` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:8174` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:8175` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:8176` | 350 × 1036 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:8177` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ Image | `I369:8177;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:8177;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:8177;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:8177;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:8177;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:8177;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:8193` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3435](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3435) |
| ↳ ↳ ↳ Image | `I369:8193;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:8193;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:8193;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:8193;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:8193;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:8193;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:8209;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I369:8209;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nhận tư vấn cấu hình ZO Light |
| ↳ Body | `I369:8209;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:8209;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I369:8209;365:702;360:273` | 179 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá ZO Light |
| ↳ Trailing | `I369:8209;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:8221;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I369:8221;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:8252;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
