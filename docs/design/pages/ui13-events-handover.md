# UI13 · Events & Handover

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI13 / Events & Handover / Desktop | [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) | 1440 × 2410 |
| UI13 / Events & Handover / Mobile | [372:9499](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9499) | 390 × 3536 |

## UI13 / Events & Handover / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [372:5328](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5328) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [372:5365](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5365) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Events | [372:5378](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5378) | 272 | 1440 × 1019 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Handover | [372:5499](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5499) | 1291 | 1440 × 738 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Footer | [372:5538](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5538) | 2029 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [372:5569](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5569) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I372:5328;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I372:5328;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I372:5328;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I372:5328;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Dịch vụ | `I372:5328;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I372:5328;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I372:5328;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I372:5328;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I372:5328;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I372:5328;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I372:5328;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I372:5365;362:301` | 147 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I372:5365;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I372:5365;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I372:5365;362:301;362:278` | 49 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Sự kiện |
| Title | `I372:5365;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Sự kiện & chuyển giao |
| Description | `I372:5365;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Workshop, hội nghị và hoạt động chuyển giao cùng đối tác. |

</details>

<details>
<summary>Events</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Tabs | `372:5379` | 1200 × 49 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0 | viền #D9E2E8 0 |  |
| ↳ Tab · Sắp diễn ra | `372:5380` | 99 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ ↳ Label | `I372:5380;361:459` | 91 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Sắp diễn ra |
| ↳ Tab · Đã diễn ra | `372:5382` | 90 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ ↳ Label | `I372:5382;361:457` | 82 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đã diễn ra |
| ↳ Tab · Chuyển giao | `372:5384` | 108 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ ↳ Label | `I372:5384;361:457` | 100 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chuyển giao |
| No upcoming | `372:5386` | 1200 × 280 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=No upcoming |
| ↳ Icon | `I372:5386;363:461` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I372:5386;363:466` | 1136 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ Body | `I372:5386;363:467` | 1136 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ Actions | `I372:5386;363:468` | 383 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I372:5386;363:469;360:222` | 156 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem sự kiện đã diễn ra |
| ↳ ↳ ↳ Label | `I372:5386;363:479;360:426` | 112 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận thông báo |
| Heading | `372:5418` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `372:5419` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đã diễn ra | `372:5421` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đã diễn ra |
| ↳ Title | `372:5422` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Hoạt động gần đây |
| Past grid | `372:5423` | 1200 × 442 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Event card · A.P.E.X 2026 – AMI Partner of Excellence | `372:5424` | 384 × 442 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:5575](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5575) |
| ↳ ↳ Image | `I372:5424;364:533` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 9906646dc39cb56f2e7171edd45f6db00f6f18e8 |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:5424;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:5424;364:538` | 130 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Hội nghị đối tác |
| ↳ ↳ ↳ Title | `I372:5424;364:539` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | A.P.E.X 2026 – AMI Partner of Excellence |
| ↳ ↳ ↳ ↳ Date | `I372:5424;364:545` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 08/07/2026 |
| ↳ ↳ ↳ ↳ Venue | `I372:5424;364:551` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | New World Saigon, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:5424;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |
| ↳ Event card · Workshop Laser Fractional CO₂ | `372:5449` | 384 × 414 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:5575](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5575) |
| ↳ ↳ Image | `I372:5449;364:533` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:5449;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:5449;364:538` | 172 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Workshop chuyên đề |
| ↳ ↳ ↳ Title | `I372:5449;364:539` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Workshop Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ Date | `I372:5449;364:545` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 17/06/2025 |
| ↳ ↳ ↳ ↳ Venue | `I372:5449;364:551` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Bệnh viện Thẩm mỹ Sao Hàn, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:5449;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |
| ↳ Event card · Hestia Night Beyond | `372:5474` | 384 × 414 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:5575](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5575) |
| ↳ ↳ Image | `I372:5474;364:533` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · f4fa945cf9b54a1de74ccadac9d0e844b1381e5b |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:5474;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:5474;364:538` | 121 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Sự kiện đối tác |
| ↳ ↳ ↳ Title | `I372:5474;364:539` | 334 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hestia Night Beyond |
| ↳ ↳ ↳ ↳ Date | `I372:5474;364:545` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 2025 |
| ↳ ↳ ↳ ↳ Venue | `I372:5474;364:551` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:5474;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |

</details>

<details>
<summary>Handover</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `372:5500` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `372:5501` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Chuyển giao công nghệ | `372:5503` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Chuyển giao công nghệ |
| ↳ Title | `372:5504` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đào tạo và bàn giao cùng đối tác |
| Handover grid | `372:5505` | 1200 × 426 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Handover card · Workshop | `372:5506` | 384 × 426 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Handover card |
| ↳ ↳ Image | `I372:5506;364:571` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 |  |
| ↳ ↳ ↳ Chuyển giao & đào tạo | `I372:5506;364:573` | 185 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Chuyển giao & đào tạo |
| ↳ ↳ ↳ Title | `I372:5506;364:574` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Workshop chuyển giao công nghệ Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ Product | `I372:5506;364:580` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị: Hestia |
| ↳ ↳ ↳ ↳ Date | `I372:5506;364:586` | 310 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 06/2025 |
| ↳ ↳ ↳ ↳ Label | `I372:5506;364:587;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I372:5538;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I372:5538;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I372:5538;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I372:5569;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI13 / Events & Handover / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [372:9500](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9500) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [372:9514](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9514) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Events | [372:9527](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9527) | 248 | 390 × 1909 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Handover | [372:9635](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9635) | 2157 | 390 × 642 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Footer | [372:9664](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9664) | 2799 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [372:9695](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9695) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I372:9500;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I372:9500;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I372:9500;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I372:9500;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I372:9500;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I372:9514;362:314` | 147 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I372:9514;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I372:9514;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I372:9514;362:314;362:278` | 49 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Sự kiện |
| Title | `I372:9514;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Sự kiện & chuyển giao |
| Description | `I372:9514;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Workshop, hội nghị và hoạt động chuyển giao cùng đối tác. |

</details>

<details>
<summary>Events</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Tabs | `372:9528` | 350 × 49 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0 | viền #D9E2E8 0 |  |
| ↳ Tab · Sắp diễn ra | `372:9529` | 99 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #0B2D48 0 | State=Active |
| ↳ ↳ Label | `I372:9529;361:459` | 91 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Sắp diễn ra |
| ↳ Tab · Đã diễn ra | `372:9531` | 90 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ ↳ Label | `I372:9531;361:457` | 82 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đã diễn ra |
| ↳ Tab · Chuyển giao | `372:9533` | 108 × 48 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 12 / 4 / 12 / 4 | viền #D9E2E8 0 | State=Default |
| ↳ ↳ Label | `I372:9533;361:457` | 100 × 24 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chuyển giao |
| No upcoming | `372:9535` | 350 × 332 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=No upcoming |
| ↳ Icon | `I372:9535;363:461` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I372:9535;363:466` | 286 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tìm thấy kết quả phù hợp |
| ↳ Body | `I372:9535;363:467` | 286 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thử từ khóa khác hoặc xóa bớt bộ lọc. |
| ↳ Actions | `I372:9535;363:468` | 383 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I372:9535;363:469;360:222` | 156 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem sự kiện đã diễn ra |
| ↳ ↳ ↳ Label | `I372:9535;363:479;360:426` | 112 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nhận thông báo |
| Heading | `372:9554` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `372:9555` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Đã diễn ra | `372:9557` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Đã diễn ra |
| ↳ Title | `372:9558` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Hoạt động gần đây |
| Past grid | `372:9559` | 350 × 1366 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Event card · A.P.E.X 2026 – AMI Partner of Excellence | `372:9560` | 350 × 442 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:9700](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9700) |
| ↳ ↳ Image | `I372:9560;364:533` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 9906646dc39cb56f2e7171edd45f6db00f6f18e8 |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:9560;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:9560;364:538` | 130 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Hội nghị đối tác |
| ↳ ↳ ↳ Title | `I372:9560;364:539` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | A.P.E.X 2026 – AMI Partner of Excellence |
| ↳ ↳ ↳ ↳ Date | `I372:9560;364:545` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 08/07/2026 |
| ↳ ↳ ↳ ↳ Venue | `I372:9560;364:551` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | New World Saigon, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:9560;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |
| ↳ Event card · Workshop Laser Fractional CO₂ | `372:9585` | 350 × 462 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:9700](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9700) |
| ↳ ↳ Image | `I372:9585;364:533` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:9585;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:9585;364:538` | 172 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Workshop chuyên đề |
| ↳ ↳ ↳ Title | `I372:9585;364:539` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Workshop Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ Date | `I372:9585;364:545` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 17/06/2025 |
| ↳ ↳ ↳ ↳ Venue | `I372:9585;364:551` | 276 × 40 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Bệnh viện Thẩm mỹ Sao Hàn, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:9585;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |
| ↳ Event card · Hestia Night Beyond | `372:9610` | 350 × 414 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | Status=Ended · Prototype → [372:9700](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-9700) |
| ↳ ↳ Image | `I372:9610;364:533` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · f4fa945cf9b54a1de74ccadac9d0e844b1381e5b |  |
| ↳ ↳ ↳ ↳ ↳ Label | `I372:9610;364:536;360:639` | 63 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đã diễn ra |
| ↳ ↳ ↳ ↳ Type | `I372:9610;364:538` | 121 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Sự kiện đối tác |
| ↳ ↳ ↳ Title | `I372:9610;364:539` | 300 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hestia Night Beyond |
| ↳ ↳ ↳ ↳ Date | `I372:9610;364:545` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 2025 |
| ↳ ↳ ↳ ↳ Venue | `I372:9610;364:551` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I372:9610;364:552;360:623` | 93 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem tổng kết |

</details>

<details>
<summary>Handover</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `372:9636` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `372:9637` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Chuyển giao công nghệ | `372:9639` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Chuyển giao công nghệ |
| ↳ Title | `372:9640` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Đào tạo và bàn giao cùng đối tác |
| Handover grid | `372:9641` | 350 × 426 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Handover card · Workshop | `372:9642` | 350 × 426 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Handover card |
| ↳ ↳ Image | `I372:9642;364:571` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 |  |
| ↳ ↳ ↳ Chuyển giao & đào tạo | `I372:9642;364:573` | 185 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Chuyển giao & đào tạo |
| ↳ ↳ ↳ Title | `I372:9642;364:574` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Workshop chuyển giao công nghệ Laser Fractional CO₂ |
| ↳ ↳ ↳ ↳ Product | `I372:9642;364:580` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị: Hestia |
| ↳ ↳ ↳ ↳ Date | `I372:9642;364:586` | 276 × 20 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 06/2025 |
| ↳ ↳ ↳ ↳ Label | `I372:9642;364:587;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I372:9664;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I372:9664;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I372:9695;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
