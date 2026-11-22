# UI18 · Article detail

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI18 / Article detail / Desktop | [373:6523](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6523) | 1440 × 3073 |
| UI18 / Article detail / Desktop / Network error | [373:12565](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12565) | 1440 × 1057 |
| UI18 / Article detail / Desktop / Not found | [373:12675](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12675) | 1440 × 1033 |
| UI18 / Article detail / Mobile | [373:11514](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11514) | 390 × 3677 |
| UI18 / Article detail / Mobile / Network error | [373:13308](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13308) | 390 × 1301 |
| UI18 / Article detail / Mobile / Not found | [373:13395](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13395) | 390 × 1277 |

## UI18 / Article detail / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:6524](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6524) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [373:6561](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6561) | 80 | 1440 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 120 / 16 / 120 | — |
| Article header | [373:6572](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6572) | 132 | 1440 × 804 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 24 / 120 / 24 / 120 | — |
| Article body | [373:6579](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6579) | 936 | 1440 × 846 | trục HORIZONTAL, wrap NO_WRAP, gap 64, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Related articles | [373:6608](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6608) | 1782 | 1440 × 734 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| CTA section | [373:6639](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6639) | 2516 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [373:6655](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6655) | 2692 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [373:6686](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6686) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:6524;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:6524;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:6524;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:6524;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:6524;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:6524;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:6524;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #B99555 0 | State=Active · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:6524;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:6524;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:6524;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:6524;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:6524;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `373:6562` | 324 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:6562;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:6562;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I373:6562;362:274` | 65 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Kiến thức |
| ↳ AT / Icon / chevron-right | `I373:6562;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:6562;362:278` | 131 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tổng kết Workshop |

</details>

<details>
<summary>Article header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Badge | `373:6573` | 136 × 24 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H HUG, căn phụ CENTER, grow 0, pad 4 / 10 / 4 / 10 | #F7F2E8 · radius 999 | Tone=Gold |
| ↳ Label | `I373:6573;360:643` | 116 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hội thảo & đào tạo |
| H1 | `373:6575` | 880 × 112 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Tổng kết Workshop chuyên đề công nghệ Laser Fractional CO₂ |
| Đăng 19/06/2025 · A&T Medical | `373:6576` | 199 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng 19/06/2025 · A&T Medical |
| Hero image | `373:6577` | 1200 × 520 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 · radius 16 |  |
| Workshop Laser Fractional CO₂, 17/06/202 | `373:6578` | 1200 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Workshop Laser Fractional CO₂, 17/06/2025 |

</details>

<details>
<summary>Article body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Table of contents | `373:6580` | 280 × 148 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ Trong bài | `373:6581` | 76 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Trong bài |
| ↳ Tóm tắt | `373:6582` | 54 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt |
| ↳ Nội dung workshop | `373:6583` | 131 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nội dung workshop |
| ↳ Thiết bị liên quan | `373:6584` | 116 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị liên quan |
| Body | `373:6585` | 720 × 766 | trục VERTICAL, wrap NO_WRAP, gap 20, W FIXED, H HUG, grow 0 | — |  |
| ↳ Summary | `373:6586` | 720 × 96 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F7F2E8 · radius 12 |  |
| ↳ ↳ Tóm tắt | `373:6587` | 62 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tóm tắt |
| ↳ ↳ Workshop chia sẻ ứng dụng công nghệ Lase | `373:6588` | 680 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Workshop chia sẻ ứng dụng công nghệ Laser Fractional CO₂ cùng bác sĩ và đối tác. |
| ↳ Nội dung workshop | `373:6589` | 332 × 44 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Nội dung workshop |
| ↳ Thân bài nhập từ CMS với heading H2/H3,  | `373:6590` | 720 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thân bài nhập từ CMS với heading H2/H3, ảnh có chú thích và nguồn. |
| ↳ Thiết bị liên quan | `373:6591` | 201 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Thiết bị liên quan |
| ↳ Product card · Hestia | `373:6592` | 720 × 486 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ Image | `I373:6592;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I373:6592;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I373:6592;364:413` | 670 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I373:6592;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I373:6592;364:415` | 670 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I373:6592;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>Related articles</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `373:6609` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `373:6610` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Bài viết liên quan | `373:6612` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Bài viết liên quan |
| ↳ Title | `373:6613` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đọc tiếp |
| Related grid | `373:6614` | 1200 × 422 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Article card · Hestia Night Beyond – cột mốc hợp tác chiến lược | `373:6615` | 384 × 422 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Article card |
| ↳ ↳ Image | `I373:6615;364:559` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 88df9833c7f5c443743234d98bd496083b059fee |  |
| ↳ ↳ ↳ Category | `I373:6615;364:561` | 139 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tin doanh nghiệp |
| ↳ ↳ ↳ Title | `I373:6615;364:562` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hestia Night Beyond – cột mốc hợp tác chiến lược |
| ↳ ↳ ↳ Excerpt | `I373:6615;364:563` | 334 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt nội dung chính của bài viết. |
| ↳ ↳ ↳ Date | `I373:6615;364:564` | 52 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | 10/2025 |
| ↳ ↳ ↳ ↳ Label | `I373:6615;364:565;360:623` | 85 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đọc bài viết |
| ↳ Article card · A.P.E.X 2026 – AMI Partner of Excellence | `373:6627` | 384 × 422 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Article card |
| ↳ ↳ Image | `I373:6627;364:559` | 382 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 9906646dc39cb56f2e7171edd45f6db00f6f18e8 |  |
| ↳ ↳ ↳ Category | `I373:6627;364:561` | 139 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tin doanh nghiệp |
| ↳ ↳ ↳ Title | `I373:6627;364:562` | 334 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | A.P.E.X 2026 – AMI Partner of Excellence |
| ↳ ↳ ↳ Excerpt | `I373:6627;364:563` | 334 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt nội dung chính của bài viết. |
| ↳ ↳ ↳ Date | `I373:6627;364:564` | 54 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | 07/2026 |
| ↳ ↳ ↳ ↳ Label | `I373:6627;364:565;360:623` | 85 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đọc bài viết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:6639;365:685` | 1005 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I373:6639;365:686` | 300 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Quan tâm thiết bị Hestia? |
| ↳ Body | `I373:6639;365:687` | 313 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhận tư vấn cấu hình và lịch trải nghiệm. |
| CTA | `I373:6639;365:688` | 171 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I373:6639;365:688;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:6639;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:6655;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:6655;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:6655;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:6686;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI18 / Article detail / Desktop / Network error


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:12566](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12566) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| State | [373:12599](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12599) | 80 | 1440 × 596 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, căn phụ CENTER, grow 0, pad 96 / 120 / 96 / 120 | — |
| Footer | [373:12644](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12644) | 676 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:12566;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:12566;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:12566;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:12566;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:12566;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:12566;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:12566;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:12566;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:12566;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:12566;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:12566;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:12566;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>State</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| State · Network error | `373:12600` | 560 × 304 | trục VERTICAL, wrap NO_WRAP, gap 16, W FIXED, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=Network error |
| ↳ Icon | `I373:12600;363:515` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I373:12600;363:519` | 496 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tải được bài viết |
| ↳ Body | `I373:12600;363:520` | 496 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Kết nối hoặc máy chủ đang gián đoạn. Bài viết có thể vẫn tồn tại — vui lòng thử lại. |
| ↳ Actions | `I373:12600;363:521` | 279 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ Primary action | `I373:12600;363:522` | 111 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [373:6523](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6523) |
| ↳ ↳ ↳ Label | `I373:12600;363:522;360:222` | 47 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thử lại |
| ↳ ↳ ↳ Label | `I373:12600;363:532;360:426` | 89 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về trang chủ |
| AT / Field | `373:12628` | 560 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ Control | `I373:12628;361:314` | 560 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H FIXED, căn phụ CENTER, grow 0, pad 0 / 16 / 0 / 16 | #FFFFFF · viền #8796A1 1 · radius 8 |  |
| ↳ ↳ Value | `I373:12628;361:319` | 496 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm thiết bị, bài viết, sự kiện |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:12644;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:12644;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:12644;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI18 / Article detail / Desktop / Not found


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:12676](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12676) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| State | [373:12709](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12709) | 80 | 1440 × 572 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, căn phụ CENTER, grow 0, pad 96 / 120 / 96 / 120 | — |
| Footer | [373:12757](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-12757) | 652 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:12676;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:12676;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:12676;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:12676;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:12676;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:12676;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:12676;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:12676;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:12676;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:12676;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:12676;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:12676;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>State</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| State · Not found | `373:12710` | 560 × 280 | trục VERTICAL, wrap NO_WRAP, gap 16, W FIXED, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=Not found |
| ↳ Icon | `I373:12710;363:488` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I373:12710;363:493` | 496 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bài viết không còn tồn tại |
| ↳ Body | `I373:12710;363:494` | 496 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Bài viết có thể đã được gỡ hoặc đổi đường dẫn. |
| ↳ Actions | `I373:12710;363:495` | 354 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I373:12710;363:496;360:222` | 150 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về Kiến thức & tin tức |
| ↳ ↳ ↳ Label | `I373:12710;363:506;360:426` | 89 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về trang chủ |
| AT / Field | `373:12741` | 560 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ Control | `I373:12741;361:314` | 560 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H FIXED, căn phụ CENTER, grow 0, pad 0 / 16 / 0 / 16 | #FFFFFF · viền #8796A1 1 · radius 8 |  |
| ↳ ↳ Value | `I373:12741;361:319` | 496 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm thiết bị, bài viết, sự kiện |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:12757;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:12757;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:12757;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI18 / Article detail / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:11515](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11515) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Breadcrumb bar | [373:11529](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11529) | 64 | 390 × 52 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 16 / 20 / 16 / 20 | — |
| Article header | [373:11540](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11540) | 116 | 390 × 490 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0, pad 8 / 20 / 8 / 20 | — |
| Article body | [373:11547](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11547) | 606 | 390 × 1068 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 24 / 20 / 24 / 20 | — |
| Related articles | [373:11576](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11576) | 1674 | 390 × 1050 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| CTA section | [373:11607](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11607) | 2724 | 390 × 216 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [373:11621](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11621) | 2940 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [373:11652](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11652) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:11515;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:11515;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:11515;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:11515;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:11515;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Breadcrumb bar</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `373:11530` | 324 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:11530;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:11530;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Level 2 | `I373:11530;362:274` | 65 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Kiến thức |
| ↳ AT / Icon / chevron-right | `I373:11530;362:275` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:11530;362:278` | 131 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tổng kết Workshop |

</details>

<details>
<summary>Article header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Badge | `373:11541` | 136 × 24 | trục HORIZONTAL, wrap NO_WRAP, W HUG, H HUG, căn phụ CENTER, grow 0, pad 4 / 10 / 4 / 10 | #F7F2E8 · radius 999 | Tone=Gold |
| ↳ Label | `I373:11541;360:643` | 116 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hội thảo & đào tạo |
| H1 | `373:11543` | 350 × 120 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Tổng kết Workshop chuyên đề công nghệ Laser Fractional CO₂ |
| Đăng 19/06/2025 · A&T Medical | `373:11544` | 199 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng 19/06/2025 · A&T Medical |
| Hero image | `373:11545` | 350 × 230 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 1b246af44b256cb7cf8a35fbf748b25870a8ad15 · radius 16 |  |
| Workshop Laser Fractional CO₂, 17/06/202 | `373:11546` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Workshop Laser Fractional CO₂, 17/06/2025 |

</details>

<details>
<summary>Article body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Table of contents | `373:11548` | 350 × 148 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ Trong bài | `373:11549` | 76 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Trong bài |
| ↳ Tóm tắt | `373:11550` | 54 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt |
| ↳ Nội dung workshop | `373:11551` | 131 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nội dung workshop |
| ↳ Thiết bị liên quan | `373:11552` | 116 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thiết bị liên quan |
| Body | `373:11553` | 350 × 848 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Summary | `373:11554` | 350 × 144 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F7F2E8 · radius 12 |  |
| ↳ ↳ Tóm tắt | `373:11555` | 62 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tóm tắt |
| ↳ ↳ Workshop chia sẻ ứng dụng công nghệ Lase | `373:11556` | 310 × 72 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Workshop chia sẻ ứng dụng công nghệ Laser Fractional CO₂ cùng bác sĩ và đối tác. |
| ↳ Nội dung workshop | `373:11557` | 241 × 34 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Nội dung workshop |
| ↳ Thân bài nhập từ CMS với heading H2/H3,  | `373:11558` | 350 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Thân bài nhập từ CMS với heading H2/H3, ảnh có chú thích và nguồn. |
| ↳ Thiết bị liên quan | `373:11559` | 170 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Thiết bị liên quan |
| ↳ Product card · Hestia | `373:11560` | 350 × 506 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ Image | `I373:11560;364:410` | 320 × 264 | W FIXED, H FIXED, grow 0 | #F5F8FA · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 |  |
| ↳ ↳ ↳ Need | `I373:11560;364:412` | 164 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Trị sẹo – Trẻ hóa da |
| ↳ ↳ ↳ Name | `I373:11560;364:413` | 300 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Hestia |
| ↳ ↳ ↳ Technology | `I373:11560;364:414` | 147 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Laser Fractional CO₂ |
| ↳ ↳ ↳ Summary | `I373:11560;364:415` | 300 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Laser phân đoạn CO₂ cho liệu trình tái tạo bề mặt da tại phòng khám. |
| ↳ ↳ ↳ ↳ Label | `I373:11560;364:419;360:623` | 84 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Xem chi tiết |

</details>

<details>
<summary>Related articles</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `373:11577` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `373:11578` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Bài viết liên quan | `373:11580` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Bài viết liên quan |
| ↳ Title | `373:11581` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Đọc tiếp |
| Related grid | `373:11582` | 350 × 868 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Article card · Hestia Night Beyond – cột mốc hợp tác chiến lược | `373:11583` | 350 × 422 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Article card |
| ↳ ↳ Image | `I373:11583;364:559` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 88df9833c7f5c443743234d98bd496083b059fee |  |
| ↳ ↳ ↳ Category | `I373:11583;364:561` | 139 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tin doanh nghiệp |
| ↳ ↳ ↳ Title | `I373:11583;364:562` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hestia Night Beyond – cột mốc hợp tác chiến lược |
| ↳ ↳ ↳ Excerpt | `I373:11583;364:563` | 300 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt nội dung chính của bài viết. |
| ↳ ↳ ↳ Date | `I373:11583;364:564` | 52 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | 10/2025 |
| ↳ ↳ ↳ ↳ Label | `I373:11583;364:565;360:623` | 85 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đọc bài viết |
| ↳ Article card · A.P.E.X 2026 – AMI Partner of Excellence | `373:11595` | 350 × 422 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Article card |
| ↳ ↳ Image | `I373:11595;364:559` | 348 × 216 | W FILL, H FIXED, grow 0 | #F5F8FA · Ảnh FILL · 9906646dc39cb56f2e7171edd45f6db00f6f18e8 |  |
| ↳ ↳ ↳ Category | `I373:11595;364:561` | 139 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Tin doanh nghiệp |
| ↳ ↳ ↳ Title | `I373:11595;364:562` | 300 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | A.P.E.X 2026 – AMI Partner of Excellence |
| ↳ ↳ ↳ Excerpt | `I373:11595;364:563` | 300 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tóm tắt nội dung chính của bài viết. |
| ↳ ↳ ↳ Date | `I373:11595;364:564` | 54 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | 07/2026 |
| ↳ ↳ ↳ ↳ Label | `I373:11595;364:565;360:623` | 85 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đọc bài viết |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I373:11607;365:699` | 350 × 60 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I373:11607;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Quan tâm thiết bị Hestia? |
| ↳ Body | `I373:11607;365:701` | 350 × 24 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhận tư vấn cấu hình và lịch trải nghiệm. |
| CTA | `I373:11607;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I373:11607;365:702;360:273` | 95 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận tư vấn |
| ↳ Trailing | `I373:11607;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:11621;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:11621;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I373:11652;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>

## UI18 / Article detail / Mobile / Network error


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:13309](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13309) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| State | [373:13323](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13323) | 64 | 390 × 500 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 48 / 20 / 48 / 20 | — |
| Footer | [373:13364](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13364) | 564 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:13309;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:13309;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:13309;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:13309;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:13309;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>State</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| State · Network error | `373:13324` | 350 × 328 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=Network error |
| ↳ Icon | `I373:13324;363:515` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I373:13324;363:519` | 286 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Không tải được bài viết |
| ↳ Body | `I373:13324;363:520` | 286 × 72 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Kết nối hoặc máy chủ đang gián đoạn. Bài viết có thể vẫn tồn tại — vui lòng thử lại. |
| ↳ Actions | `I373:13324;363:521` | 279 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ Primary action | `I373:13324;363:522` | 111 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #0B2D48 · radius 8 | Emphasis=Primary, Size=SM, State=Default · Prototype → [373:11514](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11514) |
| ↳ ↳ ↳ Label | `I373:13324;363:522;360:222` | 47 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thử lại |
| ↳ ↳ ↳ Label | `I373:13324;363:532;360:426` | 89 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về trang chủ |
| AT / Field | `373:13348` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ Control | `I373:13348;361:314` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H FIXED, căn phụ CENTER, grow 0, pad 0 / 16 / 0 / 16 | #FFFFFF · viền #8796A1 1 · radius 8 |  |
| ↳ ↳ Value | `I373:13348;361:319` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm thiết bị, bài viết, sự kiện |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:13364;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:13364;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI18 / Article detail / Mobile / Not found


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:13396](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13396) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| State | [373:13410](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13410) | 64 | 390 × 476 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 48 / 20 / 48 / 20 | — |
| Footer | [373:13452](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-13452) | 540 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:13396;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:13396;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:13396;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:13396;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:13396;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>State</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| State · Not found | `373:13411` | 350 × 304 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, căn phụ CENTER, grow 0, pad 40 / 32 / 40 / 32 | #F5F8FA · radius 12 | Type=Not found |
| ↳ Icon | `I373:13411;363:488` | 56 × 56 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #FFFFFF · radius 999 |  |
| ↳ Title | `I373:13411;363:493` | 286 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bài viết không còn tồn tại |
| ↳ Body | `I373:13411;363:494` | 286 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Bài viết có thể đã được gỡ hoặc đổi đường dẫn. |
| ↳ Actions | `I373:13411;363:495` | 354 × 44 | trục HORIZONTAL, wrap WRAP, gap 12, gap trục phụ 12, W HUG, H HUG, căn chính CENTER, grow 0 | — |  |
| ↳ ↳ ↳ Label | `I373:13411;363:496;360:222` | 150 × 20 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về Kiến thức & tin tức |
| ↳ ↳ ↳ Label | `I373:13411;363:506;360:426` | 89 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Về trang chủ |
| AT / Field | `373:13436` | 350 × 52 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — | Kind=Search, State=Default |
| ↳ Control | `I373:13436;361:314` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H FIXED, căn phụ CENTER, grow 0, pad 0 / 16 / 0 / 16 | #FFFFFF · viền #8796A1 1 · radius 8 |  |
| ↳ ↳ Value | `I373:13436;361:319` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tìm thiết bị, bài viết, sự kiện |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:13452;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:13452;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>
