# UI04 · Device category

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI04 / Device category / Desktop | [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) | 1440 × 1707 |
| UI04 / Device category / Mobile | [368:1558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1558) | 390 × 3303 |

## UI04 / Device category / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [368:1073](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1073) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [368:1110](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1110) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [368:1123](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1123) | 272 | 1440 × 878 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [368:1236](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1236) | 1150 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [368:1248](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1248) | 1326 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [368:1279](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1279) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I368:1073;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I368:1073;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I368:1073;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I368:1073;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I368:1073;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I368:1073;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I368:1073;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I368:1073;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I368:1073;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I368:1073;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I368:1073;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I368:1073;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I368:1110;362:301` | 314 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I368:1110;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I368:1110;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I368:1110;362:301;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I368:1110;362:301;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I368:1110;362:301;362:278` | 134 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| Title | `I368:1110;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Trị sẹo – Trẻ hóa da |
| Description | `I368:1110;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thiết bị cho liệu trình tái tạo bề mặt da tại phòng khám. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `368:1124` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `368:1125` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I368:1125;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `368:1141` | 63 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `368:1142` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 3 thiết bị |
| Need chips | `368:1143` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `368:1144` | 79 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I368:1144;361:442` | 45 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `368:1146` | 192 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I368:1146;361:447` | 138 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `368:1154` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1154;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `368:1156` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1156;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `368:1158` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1158;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `368:1160` | 1200 × 506 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `368:1161` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `368:1162` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I368:1164;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I368:1166;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I368:1168;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I368:1170;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `368:1172` | 908 × 506 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `368:1174` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1174;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1174;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1174;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1174;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1174;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1174;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Dermaxel | `368:1190` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1190;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1190;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1190;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1190;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1190;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1190;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Antige | `368:1206` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:5281](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-5281) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1206;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · c85180ddfda2469430dfc9b195d21ca8d3720dbf |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1206;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1206;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Antige |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1206;364:414` | 184 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Fractional RF Microneedle |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1206;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vi kim RF phân đoạn cho liệu trình tại phòng khám da liễu – thẩm mỹ. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1206;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| Other groups | `368:1222` | 1200 × 80 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Nhóm khác | `368:1223` | 90 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhóm khác |
| ↳ Chips | `368:1224` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I368:1225;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Label | `I368:1227;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ ↳ ↳ Label | `I368:1229;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Link · All devices | `368:1231` | 166 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ Label | `I368:1231;360:623` | 142 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem toàn bộ thiết bị |
| ↳ Arrow | `I368:1231;360:624` | 18 × 18 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I368:1236;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I368:1236;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I368:1236;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I368:1236;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I368:1236;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I368:1236;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I368:1248;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I368:1248;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I368:1279;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI04 / Device category / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [368:1559](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1559) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [368:1573](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1573) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [368:1586](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1586) | 248 | 390 × 2078 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| CTA section | [368:1698](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1698) | 2326 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [368:1710](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1710) | 2566 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [368:1741](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1741) | 788 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I368:1559;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I368:1559;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I368:1559;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I368:1559;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I368:1559;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I368:1573;362:314` | 314 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I368:1573;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I368:1573;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I368:1573;362:314;362:274` | 52 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| ↳ AT / Icon / chevron-right | `I368:1573;362:314;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I368:1573;362:314;362:278` | 134 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| Title | `I368:1573;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Trị sẹo – Trẻ hóa da |
| Description | `I368:1573;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thiết bị cho liệu trình tái tạo bề mặt da tại phòng khám. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `368:1587` | 350 × 108 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Catalogue search | `368:1588` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I368:1588;361:319` | 286 × 48 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `368:1604` | 350 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `368:1605` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 3 thiết bị |
| ↳ ↳ ↳ Label | `I368:1606;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `368:1616` | 350 × 148 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `368:1617` | 79 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ Label | `I368:1617;361:442` | 45 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `368:1619` | 192 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I368:1619;361:447` | 138 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `368:1627` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1627;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `368:1629` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1629;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `368:1631` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1631;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `368:1633` | 350 × 1566 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `368:1634` | 350 × 1566 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `368:1636` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1636;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1636;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1636;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1636;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1636;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1636;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Dermaxel | `368:1652` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4929](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4929) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1652;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1652;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1652;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1652;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1652;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1652;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Antige | `368:1668` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:5673](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-5673) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1668;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · c85180ddfda2469430dfc9b195d21ca8d3720dbf |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1668;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1668;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Antige |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1668;364:414` | 184 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Fractional RF Microneedle |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1668;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vi kim RF phân đoạn cho liệu trình tại phòng khám da liễu – thẩm mỹ. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1668;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| Other groups | `368:1684` | 350 × 132 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Nhóm khác | `368:1685` | 90 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhóm khác |
| ↳ Chips | `368:1686` | 350 × 96 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I368:1687;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ Label | `I368:1689;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ ↳ ↳ Label | `I368:1691;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Link · All devices | `368:1693` | 166 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ Label | `I368:1693;360:623` | 142 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem toàn bộ thiết bị |
| ↳ Arrow | `I368:1693;360:624` | 18 × 18 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I368:1698;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I368:1698;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I368:1698;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I368:1698;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I368:1698;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I368:1698;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I368:1710;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I368:1710;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I368:1741;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
