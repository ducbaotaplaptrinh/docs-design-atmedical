# UI03 · All devices

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI03 / All devices / Desktop | [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) | 1440 × 2695 |
| UI03 / All devices / Desktop / Search “Hestia” | [373:13483](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13483) | 1440 × 1603 |
| UI03 / All devices / Desktop / Filtered · Laser CO₂ | [373:13651](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13651) | 1440 × 1671 |
| UI03 / All devices / Desktop / No results | [373:13856](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13856) | 1440 × 1401 |
| UI03 / All devices / Desktop / Loading | [373:14046](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14046) | 1440 × 1445 |
| UI03 / All devices / Desktop / Network error | [373:14221](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14221) | 1440 × 1333 |
| UI03 / All devices / Desktop / Partial data | [373:14392](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14392) | 1440 × 1863 |
| UI03 / All devices / Mobile | [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) | 390 × 5845 |
| UI03 / All devices / Mobile / No results | [373:14626](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14626) | 390 × 1873 |
| UI03 / All devices / Mobile / Search “Hestia” | [373:14770](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14770) | 390 × 2091 |
| UI03 / All devices / Mobile / Network error | [373:14913](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14913) | 390 × 1873 |
| R02 / Catalog / Tablet 768 | [373:16632](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16632) | 768 × 3437 |

## UI03 / All devices / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [368:759](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-759) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [368:798](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-798) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [368:824](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-824) | 272 | 1440 × 1866 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [368:1014](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1014) | 2138 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [368:1035](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1035) | 2314 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [368:1066](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1066) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I368:759;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I368:759;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I368:759;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I368:759;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I368:759;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I368:759;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I368:759;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I368:759;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I368:759;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I368:759;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I368:759;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I368:759;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I368:798;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I368:798;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I368:798;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I368:798;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I368:798;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I368:798;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `368:825` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `368:826` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default · Prototype → [373:13483](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13483) |
| ↳ ↳ ↳ Value | `I368:826;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `368:847` | 63 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `368:848` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 8 thiết bị |
| Need chips | `368:849` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `368:850` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I368:850;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `368:862` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I368:862;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `368:864` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:864;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `368:866` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:866;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `368:868` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:868;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `368:870` | 1200 × 1642 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `368:871` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `368:872` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ Tech · Laser CO₂ | `368:874` | 106 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [373:13651](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13651) |
| ↳ ↳ ↳ ↳ Label | `I368:874;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I368:876;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I368:878;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I368:880;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `368:882` | 908 × 1642 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `368:884` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:884;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:884;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:884;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:884;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:884;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:884;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Andy | `368:901` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:901;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:901;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:901;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:901;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:901;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:901;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Q Master Plus | `368:917` | 285 × 538 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3787](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3787) |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:917;364:412` | 119 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:917;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Q Master Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:917;364:414` | 103 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:917;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thông tin thiết bị đang được cập nhật. Liên hệ A&T để nhận tư vấn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:917;364:416;360:639` | 150 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Thông tin đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:917;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Dermaxel | `368:933` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:933;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:933;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:933;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:933;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:933;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:933;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Antige | `368:949` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:5281](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-5281) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:949;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · c85180ddfda2469430dfc9b195d21ca8d3720dbf |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:949;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:949;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Antige |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:949;364:414` | 184 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Fractional RF Microneedle |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:949;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vi kim RF phân đoạn cho liệu trình tại phòng khám da liễu – thẩm mỹ. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:949;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Viola | `368:965` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:6025](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6025) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:965;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:965;364:412` | 149 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nâng cơ – Trẻ hóa |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:965;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Viola |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:965;364:414` | 34 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:965;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Siêu âm hội tụ cường độ cao (HIFU) cho liệu trình nâng cơ tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:965;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Trisis Plus | `368:981` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:6769](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6769) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:981;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 4962efe977c0b039a814323d325b97e5205828ed |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:981;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:981;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Trisis Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:981;364:414` | 116 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị xóa xăm |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:981;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị hỗ trợ liệu trình xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:981;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · ZO Light | `368:997` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:7513](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7513) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:997;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:997;364:412` | 87 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Triệt lông |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:997;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | ZO Light |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:997;364:414` | 121 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị triệt lông |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:997;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị triệt lông dùng tại phòng khám và spa chuyên nghiệp. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:997;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `368:1013` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I368:1014;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I368:1014;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I368:1014;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I368:1014;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I368:1014;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I368:1014;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I368:1035;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I368:1035;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I368:1035;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I368:1066;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / Search “Hestia”


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:13484](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13484) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:13521](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13521) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:13534](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13534) | 272 | 1440 × 774 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:13602](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13602) | 1046 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:13614](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13614) | 1222 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:13645](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13645) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:13484;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:13484;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:13484;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:13484;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:13484;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:13484;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:13484;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:13484;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:13484;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:13484;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:13484;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:13484;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:13521;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:13521;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:13521;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:13521;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:13521;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:13521;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:13535` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:13536` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Filled |
| ↳ ↳ ↳ Value | `I373:13536;361:351` | 388 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ Result meta | `373:13552` | 149 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:13553` | 149 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 1 thiết bị cho “Hestia” |
| Need chips | `373:13554` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:13555` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:13555;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:13563` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:13563;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:13565` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13565;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:13567` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13567;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:13569` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13569;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:13571` | 1200 × 550 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:13572` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:13573` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:13575;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:13577;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:13579;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:13581;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:13583` | 908 × 550 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `373:13585` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:13585;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:13585;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:13585;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:13585;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:13585;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:13585;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `373:13601` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:13602;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:13602;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:13602;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:13602;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:13602;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:13602;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:13614;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:13614;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:13614;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:13645;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / Filtered · Laser CO₂


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:13652](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13652) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:13689](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13689) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:13702](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13702) | 272 | 1440 × 842 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:13807](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13807) | 1114 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:13819](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13819) | 1290 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:13850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13850) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:13652;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:13652;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:13652;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:13652;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:13652;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:13652;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:13652;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:13652;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:13652;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:13652;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:13652;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:13652;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:13689;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:13689;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:13689;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:13689;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:13689;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:13689;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:13703` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:13704` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:13704;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:13720` | 63 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:13721` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 2 thiết bị |
| Need chips | `373:13722` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:13723` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:13723;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:13731` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:13731;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:13733` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13733;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:13735` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13735;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:13737` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13737;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Applied filters | `373:13739` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Đang lọc: | `373:13740` | 67 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang lọc: |
| ↳ Applied · Laser CO₂ | `373:13741` | 146 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I373:13741;361:447` | 72 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ Clear filters | `373:13749` | 75 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:13749;360:623` | 75 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa bộ lọc |
| Catalogue layout | `373:13754` | 1200 × 550 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:13755` | 260 × 192 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:13756` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:13758;361:447` | 72 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:13766;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:13768;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:13770;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:13772` | 908 × 550 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `373:13774` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:13774;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:13774;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:13774;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:13774;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:13774;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:13774;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Dermaxel | `373:13790` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4537](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4537) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:13790;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:13790;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:13790;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:13790;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:13790;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:13790;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `373:13806` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:13807;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:13807;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:13807;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:13807;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:13807;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:13807;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:13819;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:13819;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:13819;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:13850;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / No results


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:13857](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13857) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:13894](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13894) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:13907](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13907) | 272 | 1440 × 572 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:13997](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13997) | 844 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:14009](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14009) | 1020 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:14040](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14040) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:13857;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:13857;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:13857;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:13857;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:13857;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:13857;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:13857;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:13857;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:13857;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:13857;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:13857;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:13857;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:13894;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:13894;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:13894;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:13894;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:13894;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:13894;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:13908` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:13909` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Filled |
| ↳ ↳ ↳ Value | `I373:13909;361:351` | 388 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | xyz |
| ↳ Result meta | `373:13925` | 63 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:13926` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 0 thiết bị |
| Need chips | `373:13927` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:13928` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:13928;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:13936` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:13936;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:13938` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13938;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:13940` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13940;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:13942` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:13942;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Applied filters | `373:13944` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Đang lọc: | `373:13945` | 67 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang lọc: |
| ↳ Applied · HIFU | `373:13946` | 108 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I373:13946;361:447` | 34 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Clear filters | `373:13954` | 75 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:13954;360:623` | 75 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa bộ lọc |
| Catalogue layout | `373:13959` | 1200 × 280 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:13960` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:13961` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:13963;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:13965;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:13967;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:13969;361:447` | 34 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:13977` | 908 × 280 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Title | `I373:13978;363:381` | 844 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ ↳ ↳ Body | `I373:13978;363:382` | 844 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ ↳ ↳ ↳ Primary action | `I373:13978;363:384` | 127 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:13978;363:384;360:222` | 91 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa tìm kiếm |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:13978;363:396;360:426` | 130 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tất cả thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:13997;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:13997;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:13997;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:13997;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:13997;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:13997;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14009;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:14009;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:14009;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14040;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / Loading


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14047](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14047) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14084](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14084) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:14097](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14097) | 272 | 1440 × 616 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:14172](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14172) | 888 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:14184](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14184) | 1064 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:14215](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14215) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14047;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:14047;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:14047;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:14047;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:14047;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:14047;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:14047;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:14047;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:14047;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14047;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14047;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:14047;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14084;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14084;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14084;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14084;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14084;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:14084;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14098` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:14099` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:14099;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:14115` | 72 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14116` | 72 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang tải… |
| Need chips | `373:14117` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14118` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:14118;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14126` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:14126;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14128` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14128;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14130` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14130;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14132` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14132;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14134` | 1200 × 392 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:14135` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:14136` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:14138;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:14140;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:14142;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:14144;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:14146` | 908 × 392 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:14172;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:14172;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:14172;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:14172;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:14172;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:14172;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14184;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:14184;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:14184;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14215;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / Network error


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14222](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14222) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14259](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14259) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:14272](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14272) | 272 | 1440 × 504 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:14343](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14343) | 776 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:14355](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14355) | 952 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:14386](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14386) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14222;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:14222;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:14222;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:14222;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:14222;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:14222;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:14222;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:14222;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:14222;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14222;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14222;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:14222;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14259;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14259;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14259;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14259;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14259;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:14259;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14273` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:14274` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:14274;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:14290` | 13 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14291` | 13 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | — |
| Need chips | `373:14292` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14293` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:14293;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14301` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:14301;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14303` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14303;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14305` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14305;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14307` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14307;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14309` | 1200 × 280 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:14310` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:14311` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:14313;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:14315;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:14317;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:14319;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:14321` | 908 × 280 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Title | `I373:14322;363:412` | 844 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ ↳ ↳ Body | `I373:14322;363:413` | 844 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ ↳ ↳ ↳ Primary action | `I373:14322;363:415` | 111 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14322;363:415;360:222` | 47 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thử lại |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14322;363:425;360:426` | 97 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Liên hệ tư vấn |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:14343;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:14343;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:14343;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:14343;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:14343;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:14343;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14355;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:14355;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:14355;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14386;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Desktop / Partial data


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14393](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14393) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14430](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14430) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Catalogue | [373:14443](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14443) | 272 | 1440 × 1034 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| CTA section | [373:14560](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14560) | 1306 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:14572](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14572) | 1482 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:14603](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14603) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |
| Toast · partial | [373:14609](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14609) | 96 | 420 × 68 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FIXED, H HUG, căn phụ CENTER, position ABSOLUTE, grow 0, pad 12 / 12 / 12 / 16 | #071F35 · radius 8 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14393;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:14393;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:14393;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:14393;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:14393;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:14393;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:14393;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:14393;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:14393;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14393;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14393;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:14393;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14430;362:301` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14430;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14430;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14430;362:301;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14430;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Thiết bị |
| Description | `I373:14430;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14444` | 1200 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ Catalogue search | `373:14445` | 480 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:14445;361:319` | 416 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:14461` | 130 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14462` | 130 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 2 / 8 thiết bị đã tải |
| Need chips | `373:14463` | 1200 × 44 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14464` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ Label | `I373:14464;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14472` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| ↳ ↳ Label | `I373:14472;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14474` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14474;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14476` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14476;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14478` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14478;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14480` | 1200 × 810 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Filters | `373:14481` | 260 × 140 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ ↳ Công nghệ | `373:14482` | 86 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Công nghệ |
| ↳ ↳ ↳ ↳ Label | `I373:14484;361:442` | 72 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ |
| ↳ ↳ ↳ ↳ Label | `I373:14486;361:442` | 97 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ Label | `I373:14488;361:442` | 109 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | RF Microneedle |
| ↳ ↳ ↳ ↳ Label | `I373:14490;361:442` | 34 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ Results | `373:14492` | 908 × 810 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `373:14494` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:14494;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:14494;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:14494;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:14494;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:14494;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:14494;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Andy | `373:14510` | 285 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:14510;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:14510;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:14510;364:413` | 235 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:14510;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:14510;364:415` | 235 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:14510;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Title | `I373:14526;363:439` | 844 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ ↳ ↳ Body | `I373:14526;363:440` | 844 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14526;363:442;360:222` | 42 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tải lại |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14526;363:452;360:426` | 130 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tất cả thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:14560;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:14560;365:686` | 381 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:14560;365:687` | 468 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:14560;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:14560;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:14560;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14572;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:14572;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:14572;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14603;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

<details>
<summary>Toast · partial</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Icon / alert | `I373:14609;363:339` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / alert |
| ↳ vector | `I373:14609;363:339;360:114` | 20 × 20 | — | — |  |
| Message | `I373:14609;363:343` | 304 × 20 | W FILL, H HUG, grow 1 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Một phần dữ liệu chưa tải được. |
| Dismiss | `I373:14609;363:345` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default |
| ↳ Icon | `I373:14609;363:345;360:577` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / close |

</details>

## UI03 / All devices / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [368:1286](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1286) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [368:1300](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1300) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [368:1322](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1322) | 248 | 390 × 4620 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| CTA section | [368:1503](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1503) | 4868 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [368:1522](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1522) | 5108 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [368:1553](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1553) | 788 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I368:1286;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I368:1286;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I368:1286;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I368:1286;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I368:1286;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I368:1300;362:314` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I368:1300;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I368:1300;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I368:1300;362:314;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I368:1300;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Thiết bị |
| Description | `I368:1300;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `368:1323` | 350 × 108 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Catalogue search | `368:1324` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default · Prototype → [373:14770](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14770) |
| ↳ ↳ ↳ Value | `I368:1324;361:319` | 286 × 48 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `368:1340` | 350 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `368:1341` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 8 thiết bị |
| ↳ ↳ Open filters | `368:1342` | 111 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15984](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15984) |
| ↳ ↳ ↳ Label | `I368:1342;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `368:1354` | 350 × 148 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `368:1355` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I368:1355;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `368:1363` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1558) |
| ↳ ↳ Label | `I368:1363;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `368:1365` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1365;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `368:1367` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1367;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `368:1369` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I368:1369;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `368:1371` | 350 × 4292 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `368:1372` | 350 × 4292 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `368:1374` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1374;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1374;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1374;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1374;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1374;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1374;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Andy | `368:1390` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:3435](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3435) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1390;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1390;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1390;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1390;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1390;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1390;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Q Master Plus | `368:1406` | 350 × 538 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4182](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4182) |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1406;364:412` | 119 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1406;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Q Master Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1406;364:414` | 103 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1406;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thông tin thiết bị đang được cập nhật. Liên hệ A&T để nhận tư vấn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1406;364:416;360:639` | 150 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Thông tin đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1406;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Dermaxel | `368:1422` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:4929](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-4929) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1422;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1422;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1422;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1422;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1422;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1422;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Antige | `368:1438` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:5673](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-5673) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1438;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · c85180ddfda2469430dfc9b195d21ca8d3720dbf |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1438;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1438;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Antige |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1438;364:414` | 184 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Fractional RF Microneedle |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1438;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vi kim RF phân đoạn cho liệu trình tại phòng khám da liễu – thẩm mỹ. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1438;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Viola | `368:1454` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:6417](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-6417) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1454;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1454;364:412` | 149 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nâng cơ – Trẻ hóa |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1454;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Viola |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1454;364:414` | 34 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1454;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Siêu âm hội tụ cường độ cao (HIFU) cho liệu trình nâng cơ tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1454;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · Trisis Plus | `368:1470` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:7161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7161) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1470;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 4962efe977c0b039a814323d325b97e5205828ed |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1470;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1470;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Trisis Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1470;364:414` | 116 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị xóa xăm |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1470;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị hỗ trợ liệu trình xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1470;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ Product card · ZO Light | `368:1486` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:7905](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-7905) |
| ↳ ↳ ↳ ↳ ↳ Image | `I368:1486;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I368:1486;364:412` | 87 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Triệt lông |
| ↳ ↳ ↳ ↳ ↳ Name | `I368:1486;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | ZO Light |
| ↳ ↳ ↳ ↳ ↳ Technology | `I368:1486;364:414` | 121 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị triệt lông |
| ↳ ↳ ↳ ↳ ↳ Summary | `I368:1486;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị triệt lông dùng tại phòng khám và spa chuyên nghiệp. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I368:1486;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `368:1502` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I368:1503;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I368:1503;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I368:1503;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I368:1503;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I368:1503;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I368:1503;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I368:1522;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I368:1522;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I368:1553;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Mobile / No results


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14627](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14627) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14641](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14641) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [373:14654](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14654) | 248 | 390 × 648 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| CTA section | [373:14722](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14722) | 896 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [373:14734](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14734) | 1136 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [373:14765](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14765) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14627;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:14627;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14627;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14627;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:14627;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14641;362:314` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14641;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14641;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14641;362:314;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14641;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Thiết bị |
| Description | `I373:14641;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14655` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0 | — |  |
| ↳ Catalogue search | `373:14656` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Filled |
| ↳ ↳ ↳ Value | `I373:14656;361:351` | 258 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | xyz |
| ↳ Result meta | `373:14672` | 350 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14673` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 0 thiết bị |
| ↳ ↳ ↳ Label | `I373:14674;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `373:14684` | 350 × 148 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14685` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ Label | `I373:14685;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14693` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1558) |
| ↳ ↳ Label | `I373:14693;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14695` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14695;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14697` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14697;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14699` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14699;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14701` | 350 × 332 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `373:14702` | 350 × 332 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Title | `I373:14703;363:381` | 286 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ ↳ ↳ Body | `I373:14703;363:382` | 286 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ ↳ ↳ ↳ Primary action | `I373:14703;363:384` | 127 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14703;363:384;360:222` | 91 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa tìm kiếm |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14703;363:396;360:426` | 130 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tất cả thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:14722;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I373:14722;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:14722;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:14722;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I373:14722;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:14722;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14734;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:14734;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14765;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Mobile / Search “Hestia”


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14771](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14771) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14785](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14785) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [373:14798](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14798) | 248 | 390 × 866 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| CTA section | [373:14865](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14865) | 1114 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [373:14877](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14877) | 1354 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [373:14908](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14908) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14771;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:14771;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14771;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14771;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:14771;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14785;362:314` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14785;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14785;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14785;362:314;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14785;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Thiết bị |
| Description | `I373:14785;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14799` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0 | — |  |
| ↳ Catalogue search | `373:14800` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Filled |
| ↳ ↳ ↳ Value | `I373:14800;361:351` | 258 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ Result meta | `373:14816` | 350 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14817` | 59 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 1 thiết bị |
| ↳ ↳ ↳ Label | `I373:14818;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `373:14828` | 350 × 148 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14829` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ Label | `I373:14829;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14837` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1558) |
| ↳ ↳ Label | `I373:14837;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14839` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14839;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14841` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14841;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14843` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14843;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14845` | 350 × 550 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `373:14846` | 350 × 550 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Product card · Hestia | `373:14848` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:14848;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:14848;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:14848;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:14848;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:14848;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:14848;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `373:14864` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:14865;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I373:14865;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:14865;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:14865;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I373:14865;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:14865;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:14877;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:14877;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:14908;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>

## UI03 / All devices / Mobile / Network error


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:14914](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14914) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:14928](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14928) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [373:14941](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-14941) | 248 | 390 × 648 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| CTA section | [373:15011](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15011) | 896 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [373:15023](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15023) | 1136 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [373:15054](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15054) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:14914;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:14914;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:14914;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:14914;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:14914;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:14928;362:314` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:14928;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:14928;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:14928;362:314;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:14928;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Thiết bị |
| Description | `I373:14928;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:14942` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0 | — |  |
| ↳ Catalogue search | `373:14943` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:14943;361:319` | 286 × 48 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:14959` | 350 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:14960` | 13 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | — |
| ↳ ↳ ↳ Label | `I373:14961;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `373:14971` | 350 × 148 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:14972` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ Label | `I373:14972;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:14980` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default · Prototype → [368:1558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1558) |
| ↳ ↳ Label | `I373:14980;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:14982` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14982;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:14984` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14984;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:14986` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:14986;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:14988` | 350 × 332 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `373:14989` | 350 × 332 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ Title | `I373:14990;363:412` | 286 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ ↳ ↳ Body | `I373:14990;363:413` | 286 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ ↳ ↳ ↳ Primary action | `I373:14990;363:415` | 111 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14990;363:415;360:222` | 47 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thử lại |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:14990;363:425;360:426` | 97 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Liên hệ tư vấn |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:15011;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I373:15011;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:15011;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:15011;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I373:15011;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:15011;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:15023;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:15023;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:15054;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>

## R02 / Catalog / Tablet 768


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:16633](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16633) | 0 | 768 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:16634](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16634) | 64 | 768 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Catalogue | [373:16635](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16635) | 220 | 768 × 2448 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 20 / 24 / 20 / 24 | — |
| CTA section | [373:16659](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16659) | 2668 | 768 × 216 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [373:16660](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16660) | 2884 | 768 × 553 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [373:16661](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16661) | -1620 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:16633;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo |
| Actions | `I373:16633;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:16633;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:16634;362:314` | 150 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:16634;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:16634;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:16634;362:314;362:278` | 52 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị |
| Title | `I373:16634;362:324` | 728 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Thiết bị |
| Description | `I373:16634;362:325` | 728 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Tìm theo nhu cầu điều trị hoặc công nghệ. |

</details>

<details>
<summary>Catalogue</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Toolbar | `373:16636` | 720 × 108 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Catalogue search | `373:16637` | 720 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ ↳ ↳ Value | `I373:16637;361:319` | 656 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm theo tên thiết bị hoặc công nghệ |
| ↳ Result meta | `373:16638` | 720 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Result count | `373:16639` | 63 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | 8 thiết bị |
| ↳ ↳ ↳ Label | `I373:16640;360:426` | 44 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bộ lọc |
| Need chips | `373:16641` | 720 × 96 | trục HORIZONTAL, wrap WRAP, gap 8, gap trục phụ 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Need · Tất cả | `373:16642` | 99 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #0B2D48 · radius 999 | State=Selected |
| ↳ ↳ Label | `I373:16642;361:447` | 45 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Tất cả |
| ↳ Need · Trị sẹo – Trẻ hóa da | `373:16643` | 172 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:16643;361:442` | 138 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da |
| ↳ Need · Xóa xăm – Điều trị sắc tố | `373:16644` | 210 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:16644;361:442` | 176 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xóa xăm – Điều trị sắc tố |
| ↳ Need · Nâng cơ – Trẻ hóa | `373:16645` | 161 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:16645;361:442` | 127 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nâng cơ – Trẻ hóa |
| ↳ Need · Triệt lông | `373:16646` | 101 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 10 / 16 / 10 / 16 | #FFFFFF · viền #8796A1 1 · radius 999 | State=Default |
| ↳ ↳ Label | `I373:16646;361:442` | 67 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Triệt lông |
| Catalogue layout | `373:16647` | 720 × 2172 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| ↳ Results | `373:16648` | 720 × 2172 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 1 | — |  |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16650;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16650;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16650;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16650;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16650;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16650;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16651;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16651;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16651;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Andy |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16651;364:414` | 97 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Nd:YAG |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16651;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser Nd:YAG cho liệu trình xử lý sắc tố và xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16651;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16652;364:412` | 119 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16652;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Q Master Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16652;364:414` | 103 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16652;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thông tin thiết bị đang được cập nhật. Liên hệ A&T để nhận tư vấn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16652;364:416;360:639` | 150 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Thông tin đang cập nhật |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16652;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16653;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · b4552b58048cde627e6027ef2f3a2353df95e396 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16653;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16653;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Dermaxel |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16653;364:414` | 206 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser CO₂ Fractional RF Tube |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16653;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser CO₂ phân đoạn ống RF cho liệu trình tái tạo và trẻ hóa da. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16653;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16654;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · c85180ddfda2469430dfc9b195d21ca8d3720dbf |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16654;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16654;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Antige |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16654;364:414` | 184 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Fractional RF Microneedle |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16654;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vi kim RF phân đoạn cho liệu trình tại phòng khám da liễu – thẩm mỹ. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16654;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16655;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16655;364:412` | 149 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Nâng cơ – Trẻ hóa |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16655;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Viola |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16655;364:414` | 34 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | HIFU |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16655;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Siêu âm hội tụ cường độ cao (HIFU) cho liệu trình nâng cơ tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16655;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16656;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 4962efe977c0b039a814323d325b97e5205828ed |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16656;364:412` | 207 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Xóa xăm – Điều trị sắc tố |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16656;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Trisis Plus |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16656;364:414` | 116 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị xóa xăm |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16656;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị hỗ trợ liệu trình xóa xăm tại cơ sở chuyên môn. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16656;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ ↳ ↳ ↳ Image | `I373:16657;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 33c2a34c855669b15aaa11777e5ee8405cd0b8b1 |  |
| ↳ ↳ ↳ ↳ ↳ Need | `I373:16657;364:412` | 87 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Triệt lông |
| ↳ ↳ ↳ ↳ ↳ Name | `I373:16657;364:413` | 298 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | ZO Light |
| ↳ ↳ ↳ ↳ ↳ Technology | `I373:16657;364:414` | 121 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị triệt lông |
| ↳ ↳ ↳ ↳ ↳ Summary | `I373:16657;364:415` | 298 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị triệt lông dùng tại phòng khám và spa chuyên nghiệp. |
| ↳ ↳ ↳ ↳ ↳ ↳ Label | `I373:16657;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |
| ↳ ↳ Pagination note | `373:16658` | 138 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hiển thị 8 / 8 thiết bị |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:16659;365:699` | 728 × 60 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I373:16659;365:700` | 728 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Chưa chắc thiết bị nào phù hợp? |
| ↳ Body | `I373:16659;365:701` | 728 × 24 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chia sẻ nhu cầu điều trị, đội ngũ A&T gợi ý cấu hình phù hợp. |
| CTA | `I373:16659;365:702` | 728 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default |
| ↳ Label | `I373:16659;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:16659;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:16660;362:537` | 728 × 376 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:16660;362:565` | 728 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:16661;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
