# UI07 · Product / Q Master Plus

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI07 / Product / Q Master Plus / Desktop | [369:3787](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3787) | 1440 × 4905 |
| UI07 / Product / Q Master Plus / Mobile | [369:4182](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4182) | 390 × 6589 |

Các màn hình sản phẩm UI05–UI12 dùng chung cấu trúc component. Tách dữ liệu theo model. Đối chiếu nội dung, ảnh và thông số thật theo từng thiết bị.

## UI07 / Product / Q Master Plus / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:3788](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3788) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:3825](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3825) | 80 | 1440 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 120 / 16 / 120 | — |
| Product hero | [369:3836](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3836) | 132 | 1440 × 652 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 24 / 120 / 56 / 120 | — |
| In-page nav | [369:3901](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3901) | 784 | 1440 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:3916](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3916) | 840 | 1440 × 510 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Thông số | [369:3933](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3933) | 1350 | 1440 × 705 | trục HORIZONTAL, wrap NO_WRAP, gap 80, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Cấu hình & tài liệu | [369:3977](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3977) | 2055 | 1440 × 554 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Đào tạo & hậu mãi | [369:4017](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4017) | 2609 | 1440 × 426 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| FAQ | [369:4053](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4053) | 3035 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Liên quan | [369:4078](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4078) | 3530 | 1440 × 818 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| CTA section | [369:4133](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4133) | 4348 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [369:4145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4145) | 4524 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [369:4176](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4176) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:3788;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I369:3788;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I369:3788;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I369:3788;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I369:3788;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I369:3788;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I369:3788;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I369:3788;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I369:3788;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:3788;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:3788;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I369:3788;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:3826` | 274 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:3826;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:3826;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:3826;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:3826;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:3826;362:278` | 94 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Q Master Plus |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Gallery | `369:3838` | 620 × 572 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:3839` | 620 × 460 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Hình ảnh đang cập nhật | `369:3845` | 189 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hình ảnh đang cập nhật |
| ↳ Thumbnails | `369:3854` | 100 × 100 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |
| Summary | `369:3837` | 524 × 444 | trục VERTICAL, wrap NO_WRAP, gap 18, W FILL, H HUG, grow 1 | — |  |
| ↳ Overline | `369:3855` | 153 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đang cập nhật | `369:3857` | 119 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đang cập nhật |
| ↳ H1 | `369:3858` | 524 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Q Master Plus |
| ↳ Technology | `369:3859` | 118 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Summary | `369:3860` | 524 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thông tin thiết bị đang được cập nhật. Liên hệ A&T để nhận tư vấn. |
| ↳ Primary actions | `369:3861` | 524 × 52 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Q Master Plus | `369:3862` | 182 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:3862;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Q Master Plus | `369:3870` | 166 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ ↳ Label | `I369:3870;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Q Master Plus | `369:3878` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:3878;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Q Master Plus | `369:3888` | 524 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:3888;365:542` | 297 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Q Master Plus |
| ↳ ↳ ↳ Meta | `I369:3888;365:543` | 297 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:3888;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:3901;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:3901;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:3901;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:3901;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:3901;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:3901;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:3901;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:3901;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:3901;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3917` | 1200 × 140 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3918` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:3920` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:3921` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:3922` | 720 × 56 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:3923` | 1200 × 130 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:3924` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:3925` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Đang cập nhật | `369:3926` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đang cập nhật |
| ↳ Info · Công nghệ | `369:3927` | 384 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:3928` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Đang cập nhật | `369:3929` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đang cập nhật |
| ↳ Info · Đối tượng triển khai | `369:3930` | 384 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:3931` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:3932` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:3934` | 320 × 160 | trục VERTICAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, grow 0 | — |  |
| ↳ Heading | `369:3935` | 320 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:3938` | 286 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:3939` | 320 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:3940` | 320 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:3941` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ ↳ Label | `I369:3941;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:3949` | 800 × 513 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 1 | — |  |
| ↳ Spec · Công nghệ | `369:3950` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3950;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:3950;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Bước sóng | `369:3953` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3953;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:3953;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:3956` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3956;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:3956;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:3959` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3959;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:3959;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:3962` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3962;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:3962;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:3965` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3965;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:3965;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:3968` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3968;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:3968;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:3971` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3971;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:3971;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:3974` | 800 × 57 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 16 / 0 / 16 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Row |
| ↳ ↳ Label | `I369:3974;365:518` | 240 × 20 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:3974;365:519` | 536 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:3978` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:3979` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:3981` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:3982` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Bàn giao và hồ sơ thiết bị |
| Config | `369:3983` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:3984` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3984;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:3984;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:3994` | 588 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:3994;364:609` | 588 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:3994;364:610` | 588 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:4004` | 1200 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:4004;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:4004;365:541` | 973 × 46 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:4004;365:542` | 973 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Q Master Plus |
| ↳ ↳ Meta | `I369:4004;365:543` | 973 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:4004;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:4004;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4018` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4019` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:4021` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:4022` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Hỗ trợ sau khi bàn giao |
| Support | `369:4023` | 1200 × 114 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:4024` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4024;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:4024;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:4034` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4034;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:4034;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:4044` | 384 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4044;364:609` | 384 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:4044;364:610` | 384 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4054` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4055` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:4057` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:4058` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Trước khi đầu tư thiết bị |
| FAQ list | `369:4059` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:4060` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4060;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:4066` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4066;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:4072` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4072;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4079` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4080` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:4082` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:4083` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:4084` | 1200 × 506 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:4085` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ Image | `I369:4085;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:4085;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:4085;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:4085;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:4085;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:4085;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:4101` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ Image | `I369:4101;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:4101;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:4101;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:4101;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:4101;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:4101;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Dermaxel | `369:4117` | 384 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ Image | `I369:4117;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ Need | `I369:4117;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:4117;364:413` | 334 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ Technology | `I369:4117;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ Summary | `I369:4117;364:415` | 334 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ Label | `I369:4117;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:4133;365:685` | 881 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I369:4133;365:686` | 411 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Nhận tư vấn cấu hình Q Master Plus |
| ↳ Body | `I369:4133;365:687` | 369 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:4133;365:688` | 295 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I369:4133;365:688;360:273` | 219 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Q Master Plus |
| ↳ Trailing | `I369:4133;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:4145;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I369:4145;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I369:4145;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:4176;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI07 / Product / Q Master Plus / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [369:4183](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4183) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [369:4197](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4197) | 64 | 390 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 20 / 16 / 20 | — |
| Product hero | [369:4208](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4208) | 116 | 390 × 964 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 8 / 20 / 32 / 20 | — |
| In-page nav | [369:4273](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4273) | 1080 | 390 × 56 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H FIXED, căn phụ MAX, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Tổng quan | [369:4288](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4288) | 1136 | 390 × 694 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Thông số | [369:4305](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4305) | 1830 | 390 × 923 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Cấu hình & tài liệu | [369:4349](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4349) | 2753 | 390 × 602 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Đào tạo & hậu mãi | [369:4389](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4389) | 3355 | 390 × 592 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| FAQ | [369:4425](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4425) | 3947 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Liên quan | [369:4450](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4450) | 4360 | 390 × 1252 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| CTA section | [369:4489](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4489) | 5612 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [369:4501](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4501) | 5852 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [369:4532](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4532) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I369:4183;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I369:4183;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I369:4183;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I369:4183;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I369:4183;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `369:4198` | 274 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I369:4198;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I369:4198;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I369:4198;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I369:4198;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I369:4198;362:278` | 94 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Q Master Plus |

</details>

<details>
<summary>Product hero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Summary | `369:4209` | 350 × 512 | trục VERTICAL, wrap NO_WRAP, gap 14, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4227` | 153 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đang cập nhật | `369:4229` | 119 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đang cập nhật |
| ↳ H1 | `369:4230` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Q Master Plus |
| ↳ Technology | `369:4231` | 118 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Summary | `369:4232` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thông tin thiết bị đang được cập nhật. Liên hệ A&T để nhận tư vấn. |
| ↳ Primary actions | `369:4233` | 350 × 116 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ CTA · Quote · Q Master Plus | `369:4234` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:4234;360:273` | 106 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ CTA · Demo · Q Master Plus | `369:4242` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ ↳ Label | `I369:4242;360:375` | 115 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ CTA · Showroom · Q Master Plus | `369:4250` | 286 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | radius 8 | Emphasis=Tertiary, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:4250;360:477` | 250 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy tại showroom |
| ↳ Document · Q Master Plus | `369:4260` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ ↳ ↳ Title | `I369:4260;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Q Master Plus |
| ↳ ↳ ↳ Meta | `I369:4260;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ ↳ ↳ Label | `I369:4260;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |
| Gallery | `369:4210` | 350 × 392 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Gallery main | `369:4211` | 350 × 280 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #F5F8FA · radius 16 |  |
| ↳ ↳ Hình ảnh đang cập nhật | `369:4217` | 189 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hình ảnh đang cập nhật |
| ↳ Thumbnails | `369:4226` | 100 × 100 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, grow 0 | — |  |

</details>

<details>
<summary>In-page nav</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Anchor · Tổng quan | `I369:4273;362:328` | 91 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ Label | `I369:4273;362:328;361:459` | 83 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tổng quan |
| Anchor · Ứng dụng | `I369:4273;362:330` | 84 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:330;361:457` | 76 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Ứng dụng |
| Anchor · Công nghệ | `I369:4273;362:332` | 94 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:332;361:457` | 86 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| Anchor · Thông số | `I369:4273;362:334` | 82 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:334;361:457` | 74 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông số |
| Anchor · Cấu hình & tài liệu | `I369:4273;362:336` | 151 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:336;361:457` | 143 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cấu hình & tài liệu |
| Anchor · Đào tạo & hậu mãi | `I369:4273;362:338` | 156 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:338;361:457` | 148 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đào tạo & hậu mãi |
| Anchor · FAQ | `I369:4273;362:340` | 42 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ Label | `I369:4273;362:340;361:457` | 34 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | FAQ |

</details>

<details>
<summary>Tổng quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4289` | 350 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4290` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Tổng quan & ứng dụng | `369:4292` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tổng quan & ứng dụng |
| ↳ Title | `369:4293` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Thiết bị dành cho cơ sở chuyên môn |
| ↳ Description | `369:4294` | 350 × 84 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chỉ định, chống chỉ định và quy trình áp dụng theo hướng dẫn của nhà sản xuất và đào tạo chuyên môn. |
| Application cards | `369:4295` | 350 × 382 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Info · Nhóm ứng dụng | `369:4296` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Nhóm ứng dụng | `369:4297` | 125 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nhóm ứng dụng |
| ↳ ↳ Đang cập nhật | `369:4298` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đang cập nhật |
| ↳ Info · Công nghệ | `369:4299` | 350 × 102 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Công nghệ | `369:4300` | 87 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Công nghệ |
| ↳ ↳ Đang cập nhật | `369:4301` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đang cập nhật |
| ↳ Info · Đối tượng triển khai | `369:4302` | 350 × 130 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 24 / 24 / 24 / 24 | #FFFFFF · viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ Đối tượng triển khai | `369:4303` | 169 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đối tượng triển khai |
| ↳ ↳ Phòng khám da liễu, thẩm mỹ viện có bác  | `369:4304` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Phòng khám da liễu, thẩm mỹ viện có bác sĩ chuyên môn |

</details>

<details>
<summary>Thông số</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Specs heading | `369:4306` | 350 × 150 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Heading | `369:4307` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Thông số kỹ thuật | `369:4310` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thông số kỹ thuật |
| ↳ ↳ Title | `369:4311` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bảng thông số |
| ↳ Giá trị và đơn vị theo tài liệu nhà sản  | `369:4312` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Giá trị và đơn vị theo tài liệu nhà sản xuất. |
| ↳ CTA · Spec sheet | `369:4313` | 230 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ ↳ Label | `I369:4313;360:426` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận bảng thông số đầy đủ |
| Spec table | `369:4321` | 350 × 657 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ Spec · Công nghệ | `369:4322` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4322;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công nghệ |
| ↳ ↳ Value | `I369:4322;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Bước sóng | `369:4325` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4325;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bước sóng |
| ↳ ↳ Value | `I369:4325;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Năng lượng xung | `369:4328` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4328;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Năng lượng xung |
| ↳ ↳ Value | `I369:4328;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước điểm (spot size) | `369:4331` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4331;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước điểm (spot size) |
| ↳ ↳ Value | `I369:4331;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Công suất | `369:4334` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4334;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Công suất |
| ↳ ↳ Value | `I369:4334;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Chế độ hoạt động | `369:4337` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4337;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Chế độ hoạt động |
| ↳ ↳ Value | `I369:4337;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Nguồn điện | `369:4340` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4340;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nguồn điện |
| ↳ ↳ Value | `I369:4340;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Kích thước / trọng lượng | `369:4343` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4343;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Kích thước / trọng lượng |
| ↳ ↳ Value | `I369:4343;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |
| ↳ Spec · Xuất xứ | `369:4346` | 350 × 73 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 12 / 0 / 12 / 0 | viền #D9E2E8 0 | Status=Updating, Layout=Stacked |
| ↳ ↳ Label | `I369:4346;365:521` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xuất xứ |
| ↳ ↳ Value | `I369:4346;365:522` | 350 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Đang cập nhật |

</details>

<details>
<summary>Cấu hình & tài liệu</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4350` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4351` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Cấu hình & tài liệu | `369:4353` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Cấu hình & tài liệu |
| ↳ Title | `369:4354` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Bàn giao và hồ sơ thiết bị |
| Config | `369:4355` | 350 × 272 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:4356` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4356;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cấu hình bàn giao |
| ↳ ↳ Body | `I369:4356;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thân máy, tay cầm và phụ kiện theo hợp đồng. |
| ↳ AT / Trust item | `369:4366` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4366;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hồ sơ thiết bị |
| ↳ ↳ Body | `I369:4366;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Catalogue, hướng dẫn sử dụng và giấy tờ theo quy định. |
| AT / Document link | `369:4376` | 350 × 124 | trục HORIZONTAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 16 / 20 / 16 / 20 | #FFFFFF · viền #D9E2E8 1 · radius 8 | State=Unavailable |
| ↳ AT / Icon / file | `I369:4376;365:537` | 24 × 24 | W FIXED, H FIXED, grow 0 | — | AT / Icon / file |
| ↳ Text | `I369:4376;365:541` | 123 × 90 | trục VERTICAL, wrap NO_WRAP, gap 2, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ Title | `I369:4376;365:542` | 123 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Catalogue Q Master Plus |
| ↳ ↳ Meta | `I369:4376;365:543` | 123 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Gửi yêu cầu để nhận tài liệu |
| ↳ Link · Yêu cầu tài liệu | `I369:4376;365:544` | 129 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default |
| ↳ ↳ Label | `I369:4376;365:544;360:623` | 105 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Yêu cầu tài liệu |

</details>

<details>
<summary>Đào tạo & hậu mãi</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4390` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4391` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đào tạo & hậu mãi | `369:4393` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đào tạo & hậu mãi |
| ↳ Title | `369:4394` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Hỗ trợ sau khi bàn giao |
| Support | `369:4395` | 350 × 410 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `369:4396` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4396;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt & đào tạo |
| ↳ ↳ Body | `I369:4396;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt tại cơ sở và hướng dẫn vận hành cho đội ngũ. |
| ↳ AT / Trust item | `369:4406` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4406;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành |
| ↳ ↳ Body | `I369:4406;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của thiết bị. |
| ↳ AT / Trust item | `369:4416` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I369:4416;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I369:4416;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4426` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4427` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `369:4429` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `369:4430` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Trước khi đầu tư thiết bị |
| FAQ list | `369:4431` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `369:4432` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4432;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | A&T có hỗ trợ trải nghiệm máy tại showroom không? |
| ↳ FAQ · 2 | `369:4438` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4438;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gói đào tạo vận hành gồm những nội dung gì? |
| ↳ FAQ · 3 | `369:4444` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I369:4444;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chính sách bảo hành áp dụng thế nào? |

</details>

<details>
<summary>Liên quan</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `369:4451` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `369:4452` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Thiết bị liên quan | `369:4454` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Thiết bị liên quan |
| ↳ Title | `369:4455` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Cùng nhóm hoặc công nghệ gần |
| Related grid | `369:4456` | 350 × 1036 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Product card · Hestia | `369:4457` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ Image | `I369:4457;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I369:4457;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I369:4457;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I369:4457;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I369:4457;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I369:4457;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ Product card · Andy | `369:4473` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3435](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3435) |
| ↳ ↳ ↳ Image | `I369:4473;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ Need | `I369:4473;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Name | `I369:4473;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ Technology | `I369:4473;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ Summary | `I369:4473;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ Label | `I369:4473;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I369:4489;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I369:4489;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Nhận tư vấn cấu hình Q Master Plus |
| ↳ Body | `I369:4489;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Biểu mẫu giữ sẵn thiết bị và mục đích bạn chọn. |
| CTA | `I369:4489;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I369:4489;365:702;360:273` | 219 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá Q Master Plus |
| ↳ Trailing | `I369:4489;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I369:4501;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I369:4501;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I369:4532;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
