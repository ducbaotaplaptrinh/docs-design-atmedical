# UI20 · Contact & Showroom

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI20 / Contact & Showroom / Desktop | [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) | 1440 × 2164 |
| UI20 / Contact & Showroom / Mobile | [371:8785](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8785) | 390 × 3498 |

## UI20 / Contact & Showroom / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [371:4851](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4851) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [371:4888](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4888) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Contact | [371:4901](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4901) | 272 | 1440 × 1016 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| FAQ | [371:5083](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5083) | 1288 | 1440 × 495 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | #F5F8FA |
| Footer | [371:5108](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5108) | 1783 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [371:5139](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5139) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I371:4851;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I371:4851;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I371:4851;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I371:4851;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I371:4851;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I371:4851;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I371:4851;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| Actions | `I371:4851;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I371:4851;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I371:4851;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I371:4851;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I371:4888;362:301` | 147 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I371:4888;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I371:4888;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I371:4888;362:301;362:278` | 49 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Liên hệ |
| Title | `I371:4888;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Liên hệ & showroom |
| Description | `I371:4888;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chọn đúng nhu cầu để yêu cầu đến bộ phận phù hợp. |

</details>

<details>
<summary>Contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `371:4902` | 680 × 936 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | viền #D9E2E8 1 · radius 16 |  |
| ↳ Gửi yêu cầu | `371:4903` | 138 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Gửi yêu cầu |
| ↳ Inquiry form · Tư vấn | `371:4904` | 614 × 838 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `371:4905` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4907;361:433` | 232 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:4907;361:434` | 232 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4913;361:427` | 234 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:4913;361:428` | 234 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4918;361:427` | 234 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:4918;361:428` | 234 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4923;361:427` | 234 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:4923;361:428` | 234 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4929;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I371:4929;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:4929;361:153` | 265 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4938;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I371:4938;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:4938;361:153` | 265 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4948;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I371:4948;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:4948;361:153` | 265 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:4957;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I371:4957;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:4957;361:153` | 265 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I371:4966;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I371:4966;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I371:4966;361:202` | 550 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chọn thiết bị |
| ↳ ↳ ↳ ↳ Label | `I371:4978;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I371:4978;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I371:4978;361:266` | 580 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I371:4987;361:397` | 580 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I371:4987;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I371:4992;360:273` | 146 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu tư vấn |
| Showroom & channels | `371:5002` | 472 × 794 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Contact items | `371:5003` | 472 × 240 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 8 / 20 / 8 / 20 | viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ ↳ ↳ Label | `I371:5004;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I371:5004;364:642` | 378 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I371:5012;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I371:5012;364:651` | 378 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |
| ↳ ↳ ↳ ↳ Label | `I371:5021;364:659` | 109 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Địa chỉ showroom |
| ↳ ↳ ↳ ↳ Value | `I371:5021;364:660` | 378 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ AT / Map | `371:5033` | 472 × 320 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 24 / 24 / 24 / 24 | #EDF5FA · viền #D9E2E8 1 · radius 12 | State=Loaded |
| ↳ ↳ Bản đồ showroom | `I371:5033;365:728` | 144 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Bản đồ showroom |
| ↳ ↳ Address | `I371:5033;365:729` | 403 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ ↳ ↳ Label | `I371:5033;365:730;360:623` | 158 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Mở trong Google Maps |
| ↳ AT / Showroom card | `371:5052` | 472 × 194 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Showroom card |
| ↳ ↳ ↳ Showroom & văn phòng | `I371:5052;364:616` | 192 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Showroom & văn phòng |
| ↳ ↳ ↳ Title | `I371:5052;364:617` | 422 × 32 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | A&T Medical — TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Address | `I371:5052;364:623` | 398 × 40 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I371:5052;364:630;360:623` | 120 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đặt lịch xem máy |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:5084` | 1200 × 72 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:5085` | 1200 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `371:5087` | 1166 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `371:5088` | 820 × 44 | W FIXED, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Giải đáp nhanh |
| FAQ list | `371:5089` | 1200 × 183 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `371:5090` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5090;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Có thể đặt lịch xem máy tại showroom không? |
| ↳ FAQ · 2 | `371:5096` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5096;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hỗ trợ kỹ thuật cho thiết bị đang vận hành thế nào? |
| ↳ FAQ · 3 | `371:5102` | 1200 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:5102;365:582` | 1180 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông tin tôi gửi được sử dụng ra sao? |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I371:5108;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I371:5108;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I371:5108;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I371:5139;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI20 / Contact & Showroom / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [371:8786](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8786) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [371:8800](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8800) | 64 | 390 × 184 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Contact | [371:8813](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8813) | 248 | 390 × 2100 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| FAQ | [371:8973](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8973) | 2348 | 390 × 413 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | #F5F8FA |
| Footer | [371:8998](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-8998) | 2761 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |
| Floating contact | [371:9029](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-9029) | 776 | 52 × 52 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I371:8786;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I371:8786;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I371:8786;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I371:8786;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I371:8786;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I371:8800;362:314` | 147 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I371:8800;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I371:8800;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I371:8800;362:314;362:278` | 49 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Liên hệ |
| Title | `I371:8800;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Liên hệ & showroom |
| Description | `I371:8800;362:325` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Chọn đúng nhu cầu để yêu cầu đến bộ phận phù hợp. |

</details>

<details>
<summary>Contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `371:8814` | 350 × 1266 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | radius 16 |  |
| ↳ Gửi yêu cầu | `371:8815` | 138 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | Gửi yêu cầu |
| ↳ Inquiry form · Tư vấn | `371:8816` | 350 × 1234 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `371:8817` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8819;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:8819;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8825;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:8825;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8830;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:8830;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8835;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I371:8835;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8841;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I371:8841;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:8841;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8850;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I371:8850;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:8850;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8860;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I371:8860;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:8860;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I371:8869;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I371:8869;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I371:8869;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I371:8878;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I371:8878;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I371:8878;361:202` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chọn thiết bị |
| ↳ ↳ ↳ ↳ Label | `I371:8890;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I371:8890;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I371:8890;361:266` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I371:8899;361:397` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I371:8899;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I371:8904;360:273` | 146 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu tư vấn |
| Showroom & channels | `371:8912` | 350 × 770 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Contact items | `371:8913` | 350 × 264 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0, pad 8 / 20 / 8 / 20 | viền #D9E2E8 1 · radius 12 |  |
| ↳ ↳ ↳ ↳ Label | `I371:8914;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I371:8914;364:642` | 256 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I371:8922;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I371:8922;364:651` | 256 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |
| ↳ ↳ ↳ ↳ Label | `I371:8931;364:659` | 109 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Địa chỉ showroom |
| ↳ ↳ ↳ ↳ Value | `I371:8931;364:660` | 256 × 72 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ AT / Map | `371:8940` | 350 × 240 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 24 / 24 / 24 / 24 | #EDF5FA · viền #D9E2E8 1 · radius 12 | State=Loaded |
| ↳ ↳ Bản đồ showroom | `I371:8940;365:728` | 144 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Bản đồ showroom |
| ↳ ↳ Address | `I371:8940;365:729` | 403 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ ↳ ↳ Label | `I371:8940;365:730;360:623` | 158 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Mở trong Google Maps |
| ↳ AT / Showroom card | `371:8952` | 350 × 226 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · viền #D9E2E8 1 · radius 12 | AT / Showroom card |
| ↳ ↳ ↳ Showroom & văn phòng | `I371:8952;364:616` | 192 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Showroom & văn phòng |
| ↳ ↳ ↳ Title | `I371:8952;364:617` | 300 × 64 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | A&T Medical — TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Address | `I371:8952;364:623` | 276 × 40 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 166–168A Phạm Phú Thứ, Phường Bảy Hiền, TP. Hồ Chí Minh |
| ↳ ↳ ↳ ↳ Label | `I371:8952;364:630;360:623` | 120 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đặt lịch xem máy |

</details>

<details>
<summary>FAQ</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Heading | `371:8974` | 350 × 62 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ Overline | `371:8975` | 350 × 16 | trục HORIZONTAL, wrap NO_WRAP, gap 10, W FILL, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Câu hỏi thường gặp | `371:8977` | 316 × 16 | W FILL, H HUG, grow 1 | #7A5A1F · Be Vietnam Pro / 600 / 12 / 16 / 1.4 | Câu hỏi thường gặp |
| ↳ Title | `371:8978` | 350 × 34 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 26 / 34 / -0.3 | Giải đáp nhanh |
| FAQ list | `371:8979` | 350 × 231 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | — |  |
| ↳ FAQ · 1 | `371:8980` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:8980;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Có thể đặt lịch xem máy tại showroom không? |
| ↳ FAQ · 2 | `371:8986` | 350 × 85 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:8986;365:582` | 330 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hỗ trợ kỹ thuật cho thiết bị đang vận hành thế nào? |
| ↳ FAQ · 3 | `371:8992` | 350 × 61 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | viền #D9E2E8 0 | State=Collapsed |
| ↳ ↳ ↳ Question | `I371:8992;365:582` | 330 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thông tin tôi gửi được sử dụng ra sao? |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I371:8998;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I371:8998;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I371:9029;365:657` | 52 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | #0B2D48 · radius 999 |  |

</details>
