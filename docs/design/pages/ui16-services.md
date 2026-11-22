# UI16 · Services & After-sales

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI16 / Services & After-sales / Desktop | [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) | 1440 × 2208 |
| UI16 / Services & After-sales / Mobile | [371:9034](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9034) | 390 × 3100 |

## UI16 / Services & After-sales / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [371:5146](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5146) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [371:5183](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5183) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Services | [371:5196](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5196) | 272 | 1440 × 446 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Support process | [371:5241](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5241) | 718 | 1440 × 438 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| FAQ | [371:5264](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5264) | 1156 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| CTA section | [371:5289](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5289) | 1651 | 1440 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, căn phụ CENTER, grow 0, pad 56 / 120 / 56 / 120 | #0B2D48 |
| Footer | [371:5303](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5303) | 1827 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [371:5334](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5334) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I371:5146;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I371:5146;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I371:5146;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I371:5146;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I371:5146;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Kiến thức | `I371:5146;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I371:5146;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I371:5146;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I371:5146;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I371:5146;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I371:5146;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I371:5183;362:301` | 219 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I371:5183;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I371:5183;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I371:5183;362:301;362:278` | 121 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Dịch vụ & hậu mãi |
| Title | `I371:5183;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Dịch vụ & hậu mãi |
| Description | `I371:5183;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Lắp đặt, đào tạo vận hành, bảo hành và hỗ trợ kỹ thuật. |

</details>

<details>
<summary>Services</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:5197` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:5198` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Phạm vi dịch vụ | `371:5200` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Phạm vi dịch vụ |
| ↳ Title | `371:5201` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đồng hành sau khi bàn giao thiết bị |
| Service grid | `371:5202` | 1200 × 134 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `371:5203` | 282 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:5203;364:609` | 282 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt |
| ↳ ↳ Body | `I371:5203;364:610` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt và kiểm tra thiết bị tại cơ sở. |
| ↳ AT / Trust item | `371:5212` | 282 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:5212;364:609` | 282 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đào tạo vận hành |
| ↳ ↳ Body | `I371:5212;364:610` | 282 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hướng dẫn vận hành, an toàn và bảo quản hằng ngày. |
| ↳ AT / Trust item | `371:5222` | 282 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:5222;364:609` | 282 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành & bảo trì |
| ↳ ↳ Body | `I371:5222;364:610` | 282 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của từng thiết bị. |
| ↳ AT / Trust item | `371:5232` | 282 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:5232;364:609` | 282 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I371:5232;364:610` | 282 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận yêu cầu qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>Support process</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:5242` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:5243` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Quy trình hỗ trợ | `371:5245` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Quy trình hỗ trợ |
| ↳ Title | `371:5246` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | 4 bước tiếp nhận yêu cầu |
| Steps | `371:5247` | 1200 × 126 | trục HORIZONTAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Step 01 | `371:5248` | 282 × 126 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 01 | `371:5249` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ Gửi yêu cầu | `371:5250` | 117 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Gửi yêu cầu |
| ↳ ↳ Hotline hoặc biểu mẫu, nêu model và tình | `371:5251` | 282 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hotline hoặc biểu mẫu, nêu model và tình trạng. |
| ↳ Step 02 | `371:5252` | 282 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 02 | `371:5253` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Tiếp nhận & phân loại | `371:5254` | 215 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Tiếp nhận & phân loại |
| ↳ ↳ Kỹ thuật viên xác nhận thông tin. | `371:5255` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Kỹ thuật viên xác nhận thông tin. |
| ↳ Step 03 | `371:5256` | 282 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 03 | `371:5257` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Xử lý | `371:5258` | 49 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Xử lý |
| ↳ ↳ Hướng dẫn từ xa hoặc lịch xử lý tại cơ s | `371:5259` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hướng dẫn từ xa hoặc lịch xử lý tại cơ sở. |
| ↳ Step 04 | `371:5260` | 282 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 04 | `371:5261` | 23 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 04 |
| ↳ ↳ Hoàn tất | `371:5262` | 88 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hoàn tất |
| ↳ ↳ Xác nhận kết quả, lưu lịch sử bảo trì. | `371:5263` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xác nhận kết quả, lưu lịch sử bảo trì. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:5265` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:5266` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `371:5268` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `371:5269` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Giải đáp nhanh |
| FAQ list | `371:5270` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `371:5271` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5271;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Bảo hành áp dụng cho những hạng mục nào? |
| ↳ FAQ · 2 | `371:5277` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5277;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Có đào tạo lại khi phòng khám thay nhân sự không? |
| ↳ FAQ · 3 | `371:5283` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5283;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Làm sao gửi yêu cầu bảo trì định kỳ? |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I371:5289;365:685` | 955 × 64 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 1 | — |  |
| ↳ Title | `I371:5289;365:686` | 241 × 32 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Cần hỗ trợ kỹ thuật? |
| ↳ Body | `I371:5289;365:687` | 438 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Gửi yêu cầu kèm model thiết bị để chuyển đúng bộ phận. |
| CTA | `I371:5289;365:688` | 221 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |
| ↳ Label | `I371:5289;365:688;360:273` | 145 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu hỗ trợ |
| ↳ Trailing | `I371:5289;365:688;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I371:5303;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I371:5303;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I371:5303;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I371:5334;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI16 / Services & After-sales / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [371:9035](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9035) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [371:9049](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9049) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Services | [371:9062](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9062) | 248 | 390 × 784 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Support process | [371:9107](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9107) | 1032 | 390 × 678 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| FAQ | [371:9130](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9130) | 1710 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| CTA section | [371:9155](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9155) | 2123 | 390 × 240 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 40 / 20 / 40 / 20 | #0B2D48 |
| Footer | [371:9169](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9169) | 2363 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [371:9200](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9200) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I371:9035;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I371:9035;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I371:9035;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I371:9035;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I371:9035;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I371:9049;362:314` | 219 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I371:9049;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I371:9049;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I371:9049;362:314;362:278` | 121 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Dịch vụ & hậu mãi |
| Title | `I371:9049;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Dịch vụ & hậu mãi |
| Description | `I371:9049;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Lắp đặt, đào tạo vận hành, bảo hành và hỗ trợ kỹ thuật. |

</details>

<details>
<summary>Services</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:9063` | 350 × 96 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:9064` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Phạm vi dịch vụ | `371:9066` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Phạm vi dịch vụ |
| ↳ Title | `371:9067` | 350 × 68 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Đồng hành sau khi bàn giao thiết bị |
| Service grid | `371:9068` | 350 × 568 | trục HORIZONTAL, wrap WRAP, gap 24, gap trục phụ 24, W FILL, H HUG, grow 0 | — |  |
| ↳ AT / Trust item | `371:9069` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:9069;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Lắp đặt |
| ↳ ↳ Body | `I371:9069;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Lắp đặt và kiểm tra thiết bị tại cơ sở. |
| ↳ AT / Trust item | `371:9078` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:9078;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Đào tạo vận hành |
| ↳ ↳ Body | `I371:9078;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hướng dẫn vận hành, an toàn và bảo quản hằng ngày. |
| ↳ AT / Trust item | `371:9088` | 350 × 114 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:9088;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Bảo hành & bảo trì |
| ↳ ↳ Body | `I371:9088;364:610` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Theo điều kiện hợp đồng của từng thiết bị. |
| ↳ AT / Trust item | `371:9098` | 350 × 134 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 0 / 0 / 0 | viền #B99555 1 | Type=Capability |
| ↳ ↳ Title | `I371:9098;364:609` | 350 × 28 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hỗ trợ kỹ thuật |
| ↳ ↳ Body | `I371:9098;364:610` | 350 × 40 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tiếp nhận yêu cầu qua hotline và biểu mẫu kỹ thuật. |

</details>

<details>
<summary>Support process</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:9108` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:9109` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Quy trình hỗ trợ | `371:9111` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Quy trình hỗ trợ |
| ↳ Title | `371:9112` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | 4 bước tiếp nhận yêu cầu |
| Steps | `371:9113` | 350 × 496 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0 | — |  |
| ↳ Step 01 | `371:9114` | 350 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 01 | `371:9115` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ Gửi yêu cầu | `371:9116` | 117 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Gửi yêu cầu |
| ↳ ↳ Hotline hoặc biểu mẫu, nêu model và tình | `371:9117` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hotline hoặc biểu mẫu, nêu model và tình trạng. |
| ↳ Step 02 | `371:9118` | 350 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 02 | `371:9119` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Tiếp nhận & phân loại | `371:9120` | 215 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Tiếp nhận & phân loại |
| ↳ ↳ Kỹ thuật viên xác nhận thông tin. | `371:9121` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Kỹ thuật viên xác nhận thông tin. |
| ↳ Step 03 | `371:9122` | 350 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 03 | `371:9123` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Xử lý | `371:9124` | 49 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Xử lý |
| ↳ ↳ Hướng dẫn từ xa hoặc lịch xử lý tại cơ s | `371:9125` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Hướng dẫn từ xa hoặc lịch xử lý tại cơ sở. |
| ↳ Step 04 | `371:9126` | 350 × 106 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 16 / 0 / 0 / 0 | viền #B99555 1 |  |
| ↳ ↳ 04 | `371:9127` | 23 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 04 |
| ↳ ↳ Hoàn tất | `371:9128` | 88 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Hoàn tất |
| ↳ ↳ Xác nhận kết quả, lưu lịch sử bảo trì. | `371:9129` | 350 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xác nhận kết quả, lưu lịch sử bảo trì. |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:9131` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:9132` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `371:9134` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `371:9135` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Giải đáp nhanh |
| FAQ list | `371:9136` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `371:9137` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:9137;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Bảo hành áp dụng cho những hạng mục nào? |
| ↳ FAQ · 2 | `371:9143` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:9143;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Có đào tạo lại khi phòng khám thay nhân sự không? |
| ↳ FAQ · 3 | `371:9149` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:9149;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Làm sao gửi yêu cầu bảo trì định kỳ? |

</details>

<details>
<summary>CTA section</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Copy | `I371:9155;365:699` | 350 × 84 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0 | — |  |
| ↳ Title | `I371:9155;365:700` | 350 × 28 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 20 / 28 / 0 | Cần hỗ trợ kỹ thuật? |
| ↳ Body | `I371:9155;365:701` | 350 × 48 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 16 / 24 / 0 | Gửi yêu cầu kèm model thiết bị để chuyển đúng bộ phận. |
| CTA | `I371:9155;365:702` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) |
| ↳ Label | `I371:9155;365:702;360:273` | 145 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu hỗ trợ |
| ↳ Trailing | `I371:9155;365:702;360:274` | 20 × 20 | W FIXED, H FIXED, grow 0 | — | AT / Icon / arrow-right |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I371:9169;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I371:9169;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I371:9200;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
