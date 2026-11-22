# UI21 · Inquiry / Desktop

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI21 / Inquiry / Desktop / General | [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) | 1440 × 1637 |
| UI21 / Inquiry / Desktop / Hestia · Quote · Default | [370:3078](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3078) | 1440 × 1745 |
| UI21 / Inquiry / Desktop / Hestia · Quote · Invalid | [370:3299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3299) | 1440 × 1991 |
| UI21 / Inquiry / Desktop / Hestia · Quote · Filled | [370:3543](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3543) | 1440 × 1745 |
| UI21 / Inquiry / Desktop / Hestia · Quote · Submitting | [370:3765](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3765) | 1440 × 1745 |
| UI21 / Inquiry / Desktop / Hestia · Quote · Success | [370:3996](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3996) | 1440 × 1163 |
| UI21 / Inquiry / Desktop / Andy · Demo · Filled | [370:4156](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4156) | 1440 × 1845 |
| UI21 / Inquiry / Desktop / Andy · Demo · Submitting | [370:4385](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4385) | 1440 × 1845 |
| UI21 / Inquiry / Desktop / Andy · Demo · Failure | [370:4617](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4617) | 1440 × 1945 |
| UI21 / Inquiry / Desktop / Andy · Demo · Retry submitting | [370:4857](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4857) | 1440 × 1845 |
| UI21 / Inquiry / Desktop / Andy · Demo · Success | [370:5089](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5089) | 1440 × 1163 |
| UI21 / Inquiry / Desktop / Viola · Showroom visit · Default | [370:5228](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5228) | 1440 × 1845 |
| UI21 / Inquiry / Mobile / General | [370:7838](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7838) | 390 × 2687 |
| UI21 / Inquiry / Mobile / Hestia · Quote · Default | [370:8025](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8025) | 390 × 2797 |
| UI21 / Inquiry / Mobile / Hestia · Quote · Invalid | [370:8223](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8223) | 390 × 3023 |
| UI21 / Inquiry / Mobile / Hestia · Quote · Submitting | [370:8438](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8438) | 390 × 2797 |
| UI21 / Inquiry / Mobile / Hestia · Quote · Success | [370:8642](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8642) | 390 × 1889 |
| UI21 / Inquiry / Mobile / Andy · Demo · Failure | [370:8762](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8762) | 390 × 3015 |
| R03 / Inquiry / Tablet 768 | [373:16864](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16864) | 768 × 2259 |

## UI21 / Inquiry / Desktop / General


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:2860](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2860) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:2893](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2893) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:2906](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2906) | 272 | 1440 × 984 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:3041](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3041) | 1256 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |
| Floating contact | [370:3072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3072) | 820 | 164 × 48 | trục VERTICAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ MAX, position ABSOLUTE, grow 0 | — |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:2860;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:2860;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:2860;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:2860;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:2860;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:2860;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:2860;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:2860;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:2860;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:2860;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:2860;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:2893;362:301` | 180 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:2893;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:2893;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:2893;362:301;362:278` | 82 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận tư vấn |
| Title | `I370:2893;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận tư vấn |
| Description | `I370:2893;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:2907` | 720 × 904 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Tư vấn | `370:2908` | 654 × 838 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:2909` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2911;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:2911;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2917;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:2917;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2922;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:2922;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2927;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:2927;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2933;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:2933;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:2933;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2942;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:2942;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:2942;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2952;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:2952;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:2952;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:2961;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:2961;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:2961;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:2970;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:2970;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:2970;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chọn thiết bị |
| ↳ ↳ ↳ ↳ Label | `I370:2982;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:2982;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:2982;361:266` | 620 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:2991;361:397` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:2991;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:2996;360:273` | 146 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu tư vấn |
| Aside | `370:3006` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:3007` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:3008` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:3009` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:3010` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:3011` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:3012` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:3013` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:3014` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:3015` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:3016` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:3017` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:3018` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:3019;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:3019;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:3029;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:3029;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:3041;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:3041;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:3041;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

<details>
<summary>Floating contact</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Trigger | `I370:3072;365:628` | 164 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn chính CENTER, căn phụ CENTER, grow 0, pad 14 / 20 / 14 / 20 | #0B2D48 · radius 999 |  |

</details>

## UI21 / Inquiry / Desktop / Hestia · Quote · Default


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:3079](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3079) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:3112](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3112) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:3125](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3125) | 272 | 1440 × 1092 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:3267](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3267) | 1364 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:3079;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:3079;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:3079;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:3079;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:3079;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:3079;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:3079;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:3079;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:3079;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:3079;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:3079;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:3079;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:3112;362:301` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:3112;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:3112;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:3112;362:301;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:3112;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận báo giá thiết bị |
| Description | `I370:3112;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:3126` | 720 × 1012 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:3127` | 654 × 946 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:3128;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:3128;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:3128;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:3128;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:3128;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:3142` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3144;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3144;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3149;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3149;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3155;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3155;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3160;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3160;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3166;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3166;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3166;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3175;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3175;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3175;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3185;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3185;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3185;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3194;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3194;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3194;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:3203;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3203;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3203;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:3215;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3215;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3215;361:266` | 620 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:3224;361:397` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:3224;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ Submit | `370:3229` | 234 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:3299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3299) |
| ↳ ↳ ↳ Label | `I370:3229;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu báo giá |
| Aside | `370:3237` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:3238` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:3239` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:3240` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:3241` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:3242` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:3243` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:3244` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:3245` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:3246` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:3247` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:3248` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:3249` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:3250;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:3250;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:3258;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:3258;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:3267;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:3267;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:3267;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Hestia · Quote · Invalid


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:3300](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3300) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:3333](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3333) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:3346](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3346) | 272 | 1440 × 1338 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:3511](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3511) | 1610 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:3300;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:3300;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:3300;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:3300;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:3300;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:3300;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:3300;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:3300;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:3300;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:3300;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:3300;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:3300;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:3333;362:301` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:3333;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:3333;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:3333;362:301;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:3333;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận báo giá thiết bị |
| Description | `I370:3333;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:3347` | 720 × 1258 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:3348` | 654 × 1192 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:3349;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:3349;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:3349;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:3349;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:3349;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ ↳ ↳ Title | `I370:3359;363:373` | 223 × 24 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Vui lòng kiểm tra 4 thông tin |
| ↳ ↳ ↳ Items | `I370:3359;363:374` | 612 × 80 | W FILL, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | • Họ và tên<br>• Số điện thoại<br>• Email<br>• Xác nhận đồng ý |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:3370` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3372;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3372;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3377;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3377;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3383;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3383;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3388;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3388;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3394;361:176` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3394;361:177` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3394;361:180` | 284 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Message text | `I370:3394;361:186` | 138 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng nhập họ tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3410;361:176` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3410;361:177` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3410;361:180` | 284 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Message text | `I370:3410;361:186` | 205 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng kiểm tra số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3424;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3424;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3424;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3433;361:176` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3433;361:178` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3433;361:180` | 284 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | minhanh@ |
| ↳ ↳ ↳ ↳ ↳ Message text | `I370:3433;361:186` | 185 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Email chưa đúng định dạng |
| ↳ ↳ ↳ ↳ Label | `I370:3446;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3446;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3446;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:3458;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3458;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3458;361:266` | 620 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:3467;361:415` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:3467;361:416` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ ↳ Error | `I370:3467;361:417` | 197 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng xác nhận để tiếp tục |
| ↳ ↳ Submit | `370:3473` | 234 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:3543](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3543) |
| ↳ ↳ ↳ Label | `I370:3473;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu báo giá |
| Aside | `370:3481` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:3482` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:3483` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:3484` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:3485` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:3486` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:3487` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:3488` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:3489` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:3490` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:3491` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:3492` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:3493` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:3494;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:3494;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:3502;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:3502;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:3511;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:3511;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:3511;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Hestia · Quote · Filled


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:3544](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3544) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:3577](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3577) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:3590](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3590) | 272 | 1440 × 1092 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:3733](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3733) | 1364 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:3544;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:3544;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:3544;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:3544;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:3544;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:3544;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:3544;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:3544;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:3544;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:3544;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:3544;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:3544;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:3577;362:301` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:3577;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:3577;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:3577;362:301;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:3577;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận báo giá thiết bị |
| Description | `I370:3577;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:3591` | 720 × 1012 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:3592` | 654 × 946 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:3593;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:3593;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:3593;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:3593;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:3593;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:3603` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3605;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3605;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3610;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3610;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3616;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3616;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3621;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3621;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3627;361:167` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3627;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3627;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nguyễn Minh Anh |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3636;361:167` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3636;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3636;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3646;361:167` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3646;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3646;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Phòng khám Da liễu Minh Anh |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3655;361:167` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3655;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3655;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | minhanh@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:3664;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3664;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3664;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:3676;361:280` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3676;361:282` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3676;361:284` | 620 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Cần báo giá cấu hình Hestia cho điều trị sẹo rỗ. |
| ↳ ↳ ↳ ↳ Label | `I370:3685;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:3685;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ Submit | `370:3695` | 234 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:3765](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3765) |
| ↳ ↳ ↳ Label | `I370:3695;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu báo giá |
| Aside | `370:3703` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:3704` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:3705` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:3706` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:3707` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:3708` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:3709` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:3710` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:3711` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:3712` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:3713` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:3714` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:3715` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:3716;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:3716;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:3724;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:3724;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:3733;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:3733;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:3733;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Hestia · Quote · Submitting


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:3766](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3766) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:3799](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3799) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:3812](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3812) | 272 | 1440 × 1092 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:3964](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3964) | 1364 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:3766;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:3766;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:3766;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:3766;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:3766;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:3766;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:3766;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:3766;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:3766;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:3766;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:3766;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:3766;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:3799;362:301` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:3799;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:3799;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:3799;362:301;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:3799;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận báo giá thiết bị |
| Description | `I370:3799;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:3813` | 720 × 1012 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:3814` | 654 × 946 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:3815;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:3815;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:3815;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:3815;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:3815;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:3825` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3827;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3827;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3832;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3832;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3838;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3838;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3843;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:3843;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3849;361:189` | 66 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3849;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3849;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nguyễn Minh Anh |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3858;361:189` | 93 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:3858;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3858;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3868;361:189` | 155 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3868;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3868;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Phòng khám Da liễu Minh Anh |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:3877;361:189` | 39 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:3877;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:3877;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | minhanh@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:3886;361:250` | 122 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3886;361:252` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3886;361:254` | 590 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:3900;361:302` | 62 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:3900;361:304` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:3900;361:306` | 620 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Cần báo giá cấu hình Hestia cho điều trị sẹo rỗ. |
| ↳ ↳ ↳ ↳ Label | `I370:3909;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:3909;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:3917;360:316` | 86 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang gửi… |
| Aside | `370:3934` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:3935` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:3936` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:3937` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:3938` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:3939` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:3940` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:3941` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:3942` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:3943` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:3944` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:3945` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:3946` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:3947;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:3947;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:3955;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:3955;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:3964;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:3964;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:3964;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Hestia · Quote · Success


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:3997](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-3997) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:4030](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4030) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:4043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4043) | 272 | 1440 × 510 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:4124](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4124) | 782 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:3997;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:3997;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:3997;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:3997;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:3997;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:3997;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:3997;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:3997;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:3997;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:3997;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:3997;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:3997;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:4030;362:301` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:4030;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:4030;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:4030;362:301;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:4030;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Nhận báo giá thiết bị |
| Description | `I370:4030;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:4044` | 720 × 430 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ AT / Success confirmation | `370:4045` | 654 × 364 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | #FFFFFF | AT / Success confirmation |
| ↳ ↳ Title | `I370:4045;363:555` | 654 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đã nhận yêu cầu của bạn |
| ↳ ↳ ↳ Intent | `I370:4045;363:557` | 614 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Mục đích: Nhận báo giá |
| ↳ ↳ ↳ Product | `I370:4045;363:558` | 614 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thiết bị: Hestia — Laser Fractional CO₂ |
| ↳ ↳ Body | `I370:4045;363:559` | 654 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | A&T Medical sẽ liên hệ theo thông tin bạn cung cấp. |
| ↳ ↳ ↳ Back to product | `I370:4045;363:561` | 197 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #0B2D48 · radius 8 | Emphasis=Primary, Size=MD, State=Default · Prototype → [369:2299](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2299) |
| ↳ ↳ ↳ ↳ Label | `I370:4045;363:561;360:171` | 121 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 16 / 24 / 0 | Quay lại Hestia |
| ↳ ↳ ↳ Browse devices | `I370:4045;363:571` | 218 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:4045;363:571;360:375` | 139 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Xem thiết bị khác |
| Aside | `370:4094` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:4095` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:4096` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:4097` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:4098` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:4099` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:4100` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:4101` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:4102` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:4103` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:4104` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:4105` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:4106` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:4107;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:4107;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:4115;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:4115;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:4124;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:4124;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:4124;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Andy · Demo · Filled


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:4157](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4157) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:4190](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4190) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:4203](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4203) | 272 | 1440 × 1192 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:4353](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4353) | 1464 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:4157;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:4157;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:4157;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:4157;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:4157;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:4157;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:4157;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:4157;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:4157;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:4157;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:4157;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:4157;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:4190;362:301` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:4190;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:4190;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:4190;362:301;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:4190;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đăng ký demo thiết bị |
| Description | `I370:4190;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:4204` | 720 × 1112 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Demo · Andy | `370:4205` | 654 × 1046 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:4206;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:4206;365:573` | 88 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng ký demo |
| ↳ ↳ ↳ ↳ Product | `I370:4206;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Andy — Laser Nd:YAG |
| ↳ ↳ ↳ Change product | `I370:4206;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:4206;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:4216` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4218;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4218;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4223;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4223;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4228;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4228;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4234;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4234;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4240;361:167` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4240;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4240;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Trần Quốc Bảo |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4249;361:167` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4249;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4249;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0903 222 111 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4259;361:167` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4259;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4259;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thẩm mỹ viện An Bình |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4268;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4268;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4268;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:4277;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4277;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4277;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Andy |
| ↳ ↳ ↳ ↳ Label | `I370:4289;361:167` | 149 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4289;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4289;361:171` | 620 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:4298;361:280` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4298;361:282` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4298;361:284` | 620 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Muốn trải nghiệm Andy cho liệu trình xử lý sắc tố. |
| ↳ ↳ ↳ ↳ Label | `I370:4307;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:4307;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ Submit | `370:4315` | 221 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:4385](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4385) |
| ↳ ↳ ↳ Label | `I370:4315;360:273` | 145 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi đăng ký demo |
| Aside | `370:4323` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:4324` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:4325` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:4326` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:4327` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:4328` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:4329` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:4330` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:4331` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:4332` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:4333` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:4334` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:4335` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:4336;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:4336;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:4344;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:4344;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:4353;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:4353;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:4353;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Andy · Demo · Submitting


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:4386](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4386) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:4419](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4419) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:4432](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4432) | 272 | 1440 × 1192 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:4585](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4585) | 1464 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:4386;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:4386;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:4386;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:4386;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:4386;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:4386;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:4386;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:4386;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:4386;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:4386;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:4386;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:4386;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:4419;362:301` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:4419;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:4419;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:4419;362:301;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:4419;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đăng ký demo thiết bị |
| Description | `I370:4419;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:4433` | 720 × 1112 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Demo · Andy | `370:4434` | 654 × 1046 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:4435;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:4435;365:573` | 88 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng ký demo |
| ↳ ↳ ↳ ↳ Product | `I370:4435;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Andy — Laser Nd:YAG |
| ↳ ↳ ↳ Change product | `I370:4435;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:4435;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:4445` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4447;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4447;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4452;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4452;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4457;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4457;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4463;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4463;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4469;361:189` | 66 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4469;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4469;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Trần Quốc Bảo |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4478;361:189` | 93 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4478;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4478;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0903 222 111 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4488;361:189` | 155 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4488;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4488;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thẩm mỹ viện An Bình |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4497;361:189` | 39 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4497;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4497;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:4506;361:250` | 122 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4506;361:252` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4506;361:254` | 590 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Andy |
| ↳ ↳ ↳ ↳ Label | `I370:4518;361:189` | 149 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4518;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4518;361:193` | 620 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:4527;361:302` | 62 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4527;361:304` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4527;361:306` | 620 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Muốn trải nghiệm Andy cho liệu trình xử lý sắc tố. |
| ↳ ↳ ↳ ↳ Label | `I370:4536;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:4536;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:4544;360:316` | 86 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang gửi… |
| Aside | `370:4555` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:4556` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:4557` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:4558` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:4559` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:4560` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:4561` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:4562` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:4563` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:4564` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:4565` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:4566` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:4567` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:4568;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:4568;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:4576;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:4576;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:4585;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:4585;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:4585;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Andy · Demo · Failure


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:4618](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4618) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:4651](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4651) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:4664](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4664) | 272 | 1440 × 1292 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:4825](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4825) | 1564 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:4618;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:4618;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:4618;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:4618;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:4618;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:4618;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:4618;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:4618;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:4618;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:4618;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:4618;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:4618;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:4651;362:301` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:4651;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:4651;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:4651;362:301;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:4651;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đăng ký demo thiết bị |
| Description | `I370:4651;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:4665` | 720 × 1212 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Demo · Andy | `370:4666` | 654 × 1146 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:4667;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:4667;365:573` | 88 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng ký demo |
| ↳ ↳ ↳ ↳ Product | `I370:4667;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Andy — Laser Nd:YAG |
| ↳ ↳ ↳ Change product | `I370:4667;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:4667;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ ↳ ↳ Title | `I370:4677;363:321` | 587 × 24 | W FILL, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chưa gửi được yêu cầu |
| ↳ ↳ ↳ ↳ Body | `I370:4677;363:322` | 587 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Kết nối bị gián đoạn. Thông tin của bạn vẫn được giữ — bấm Thử lại. |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:4688` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4690;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4690;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4695;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4695;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4700;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4700;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4706;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4706;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4712;361:167` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4712;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4712;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Trần Quốc Bảo |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4721;361:167` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4721;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4721;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0903 222 111 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4731;361:167` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4731;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4731;361:171` | 285 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thẩm mỹ viện An Bình |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4740;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4740;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4740;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:4749;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4749;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4749;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Andy |
| ↳ ↳ ↳ ↳ Label | `I370:4761;361:167` | 149 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4761;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4761;361:171` | 620 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:4770;361:280` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4770;361:282` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4770;361:284` | 620 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Muốn trải nghiệm Andy cho liệu trình xử lý sắc tố. |
| ↳ ↳ ↳ ↳ Label | `I370:4779;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:4779;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ Submit | `370:4787` | 130 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:4857](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4857) |
| ↳ ↳ ↳ Label | `I370:4787;360:273` | 54 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thử lại |
| Aside | `370:4795` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:4796` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:4797` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:4798` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:4799` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:4800` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:4801` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:4802` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:4803` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:4804` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:4805` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:4806` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:4807` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:4808;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:4808;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:4816;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:4816;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:4825;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:4825;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:4825;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Andy · Demo · Retry submitting


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:4858](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4858) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:4891](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4891) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:4904](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-4904) | 272 | 1440 × 1192 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:5057](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5057) | 1464 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:4858;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:4858;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:4858;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:4858;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:4858;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:4858;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:4858;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:4858;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:4858;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:4858;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:4858;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:4858;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:4891;362:301` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:4891;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:4891;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:4891;362:301;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:4891;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đăng ký demo thiết bị |
| Description | `I370:4891;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:4905` | 720 × 1112 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Demo · Andy | `370:4906` | 654 × 1046 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:4907;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:4907;365:573` | 88 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng ký demo |
| ↳ ↳ ↳ ↳ Product | `I370:4907;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Andy — Laser Nd:YAG |
| ↳ ↳ ↳ Change product | `I370:4907;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:4907;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:4917` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4919;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4919;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4924;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4924;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4929;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4929;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4935;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:4935;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4941;361:189` | 66 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4941;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4941;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Trần Quốc Bảo |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4950;361:189` | 93 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:4950;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4950;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0903 222 111 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4960;361:189` | 155 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4960;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4960;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thẩm mỹ viện An Bình |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:4969;361:189` | 39 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:4969;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:4969;361:193` | 285 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:4978;361:250` | 122 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4978;361:252` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4978;361:254` | 590 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Andy |
| ↳ ↳ ↳ ↳ Label | `I370:4990;361:189` | 149 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4990;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4990;361:193` | 620 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:4999;361:302` | 62 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:4999;361:304` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:4999;361:306` | 620 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Muốn trải nghiệm Andy cho liệu trình xử lý sắc tố. |
| ↳ ↳ ↳ ↳ Label | `I370:5008;361:405` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:5008;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:5016;360:316` | 109 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang gửi lại… |
| Aside | `370:5027` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:5028` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:5029` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:5030` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:5031` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:5032` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:5033` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:5034` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:5035` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:5036` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:5037` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:5038` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:5039` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:5040;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:5040;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:5048;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:5048;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:5057;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:5057;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:5057;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Andy · Demo · Success


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:5090](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5090) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:5123](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5123) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:5136](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5136) | 272 | 1440 × 510 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:5196](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5196) | 782 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:5090;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:5090;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:5090;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:5090;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:5090;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:5090;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:5090;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:5090;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:5090;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:5090;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:5090;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:5090;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:5123;362:301` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:5123;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:5123;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:5123;362:301;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:5123;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đăng ký demo thiết bị |
| Description | `I370:5123;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:5137` | 720 × 430 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ AT / Success confirmation | `370:5138` | 654 × 364 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | #FFFFFF | AT / Success confirmation |
| ↳ ↳ Title | `I370:5138;363:555` | 654 × 44 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đã nhận yêu cầu của bạn |
| ↳ ↳ ↳ Intent | `I370:5138;363:557` | 614 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Mục đích: Đăng ký demo |
| ↳ ↳ ↳ Product | `I370:5138;363:558` | 614 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thiết bị: Andy — Laser Nd:YAG |
| ↳ ↳ Body | `I370:5138;363:559` | 654 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | A&T Medical sẽ liên hệ theo thông tin bạn cung cấp. |
| ↳ ↳ ↳ Back to product | `I370:5138;363:561` | 187 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #0B2D48 · radius 8 | Emphasis=Primary, Size=MD, State=Default · Prototype → [369:3043](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-3043) |
| ↳ ↳ ↳ ↳ Label | `I370:5138;363:561;360:171` | 111 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 16 / 24 / 0 | Quay lại Andy |
| ↳ ↳ ↳ Browse devices | `I370:5138;363:571` | 218 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:5138;363:571;360:375` | 139 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Xem thiết bị khác |
| Aside | `370:5166` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:5167` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:5168` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:5169` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:5170` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:5171` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:5172` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:5173` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:5174` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:5175` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:5176` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:5177` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:5178` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:5179;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:5179;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:5187;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:5187;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:5196;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:5196;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:5196;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Desktop / Viola · Showroom visit · Default


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:5229](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5229) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:5262](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5262) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Inquiry body | [370:5275](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5275) | 272 | 1440 × 1192 | trục HORIZONTAL, wrap NO_WRAP, gap 56, W FILL, H HUG, grow 0, pad 40 / 120 / 40 / 120 | — |
| Footer | [370:5422](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-5422) | 1464 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:5229;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I370:5229;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I370:5229;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I370:5229;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I370:5229;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I370:5229;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I370:5229;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I370:5229;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I370:5229;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:5229;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:5229;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I370:5229;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:5262;362:301` | 313 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:5262;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:5262;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:5262;362:301;362:278` | 215 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đặt lịch xem máy tại showroom |
| Title | `I370:5262;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Đặt lịch xem máy tại showroom |
| Description | `I370:5262;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:5276` | 720 × 1112 | trục VERTICAL, wrap NO_WRAP, W FIXED, H HUG, grow 0, pad 32 / 32 / 32 / 32 | #FFFFFF · viền #D9E2E8 1 · radius 16 |  |
| ↳ Inquiry form · Xem máy · Viola | `370:5277` | 654 × 1046 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:5278;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 941eab1c1a89da82eb4990afb519f80393cac626 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:5278;365:573` | 105 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ Product | `I370:5278;365:574` | 498 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Viola — HIFU |
| ↳ ↳ ↳ Change product | `I370:5278;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:758](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-758) |
| ↳ ↳ ↳ ↳ Label | `I370:5278;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:5288` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5290;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:5290;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5295;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:5295;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5300;361:427` | 254 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:5300;361:428` | 254 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5305;361:433` | 252 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:5305;361:434` | 252 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5312;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:5312;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:5312;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5321;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:5321;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:5321;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5331;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:5331;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:5331;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:5340;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:5340;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:5340;361:153` | 285 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:5349;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:5349;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:5349;361:202` | 590 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Viola |
| ↳ ↳ ↳ ↳ Label | `I370:5361;361:149` | 149 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:5361;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:5361;361:153` | 620 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:5370;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:5370;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:5370;361:266` | 620 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:5379;361:397` | 620 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:5379;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:5384;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu đặt lịch |
| Aside | `370:5392` | 424 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 1 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:5393` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:5394` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:5395` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:5396` | 394 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:5397` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:5398` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:5399` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:5400` | 424 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:5401` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:5402` | 390 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:5403` | 424 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:5404` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:5405;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:5405;364:642` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:5413;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:5413;364:651` | 332 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:5422;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I370:5422;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I370:5422;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / General


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:7839](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7839) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:7853](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7853) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:7866](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7866) | 220 | 390 × 1730 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:7994](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-7994) | 1950 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:7839;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:7839;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:7839;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:7839;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:7839;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:7853;362:314` | 180 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:7853;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:7853;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:7853;362:314;362:278` | 82 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận tư vấn |
| Title | `I370:7853;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận tư vấn |
| Description | `I370:7853;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:7867` | 350 × 1234 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Tư vấn | `370:7868` | 350 × 1234 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:7869` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7871;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:7871;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7877;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:7877;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7882;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:7882;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7887;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:7887;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7893;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:7893;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:7893;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7902;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:7902;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:7902;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7912;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:7912;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:7912;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:7921;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:7921;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:7921;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:7930;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:7930;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:7930;361:202` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chọn thiết bị |
| ↳ ↳ ↳ ↳ Label | `I370:7942;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:7942;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:7942;361:266` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:7951;361:397` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:7951;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:7956;360:273` | 146 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu tư vấn |
| Aside | `370:7964` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:7965` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:7966` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:7967` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:7968` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:7969` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:7970` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:7971` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:7972` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:7973` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:7974` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:7975` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:7976` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:7977;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:7977;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:7985;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:7985;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:7994;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:7994;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / Hestia · Quote · Default


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:8026](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8026) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:8040](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8040) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:8053](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8053) | 220 | 390 × 1840 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:8191](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8191) | 2060 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:8026;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:8026;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:8026;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:8026;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:8026;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:8040;362:314` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:8040;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:8040;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:8040;362:314;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:8040;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận báo giá thiết bị |
| Description | `I370:8040;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:8054` | 350 × 1344 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:8055` | 350 × 1344 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:8056;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:8056;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:8056;365:574` | 194 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:8056;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ Label | `I370:8056;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:8066` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8068;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8068;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8073;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8073;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8079;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8079;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8084;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8084;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8090;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8090;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8090;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8099;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8099;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8099;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8109;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8109;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8109;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8118;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8118;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8118;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:8127;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8127;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8127;361:202` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:8139;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8139;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8139;361:266` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:8148;361:397` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:8148;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ Submit | `370:8153` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:8223](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8223) |
| ↳ ↳ ↳ Label | `I370:8153;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu báo giá |
| Aside | `370:8161` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:8162` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:8163` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:8164` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:8165` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:8166` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:8167` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:8168` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:8169` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:8170` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:8171` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:8172` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:8173` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:8174;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:8174;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:8182;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:8182;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:8191;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:8191;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / Hestia · Quote · Invalid


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:8224](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8224) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:8238](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8238) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:8251](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8251) | 220 | 390 × 2066 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:8406](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8406) | 2286 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:8224;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:8224;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:8224;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:8224;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:8224;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:8238;362:314` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:8238;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:8238;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:8238;362:314;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:8238;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận báo giá thiết bị |
| Description | `I370:8238;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:8252` | 350 × 1570 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:8253` | 350 × 1570 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:8254;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:8254;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:8254;365:574` | 194 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:8254;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ Label | `I370:8254;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ ↳ ↳ Title | `I370:8264;363:373` | 222 × 24 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Vui lòng kiểm tra 3 thông tin |
| ↳ ↳ ↳ Items | `I370:8264;363:374` | 308 × 60 | W FILL, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | • Họ và tên<br>• Số điện thoại<br>• Xác nhận đồng ý |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:8272` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8274;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8274;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8279;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8279;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8285;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8285;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8290;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8290;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8296;361:176` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8296;361:177` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8296;361:180` | 315 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Message text | `I370:8296;361:186` | 138 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng nhập họ tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8309;361:176` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8309;361:177` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8309;361:180` | 315 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Message text | `I370:8309;361:186` | 205 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng kiểm tra số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8323;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8323;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8323;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8332;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8332;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8332;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:8341;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8341;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8341;361:202` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:8353;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8353;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8353;361:266` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I370:8362;361:415` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:8362;361:416` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ ↳ Error | `I370:8362;361:417` | 197 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Vui lòng xác nhận để tiếp tục |
| ↳ ↳ Submit | `370:8368` | 350 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W FILL, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #B99555 · radius 8 | Emphasis=Accent, Size=MD, State=Default · Prototype → [370:8438](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8438) |
| ↳ ↳ ↳ Label | `I370:8368;360:273` | 158 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu báo giá |
| Aside | `370:8376` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:8377` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:8378` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:8379` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:8380` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:8381` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:8382` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:8383` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:8384` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:8385` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:8386` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:8387` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:8388` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:8389;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:8389;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:8397;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:8397;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:8406;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:8406;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / Hestia · Quote · Submitting


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:8439](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8439) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:8453](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8453) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:8466](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8466) | 220 | 390 × 1840 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:8610](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8610) | 2060 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:8439;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:8439;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:8439;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:8439;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:8439;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:8453;362:314` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:8453;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:8453;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:8453;362:314;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:8453;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận báo giá thiết bị |
| Description | `I370:8453;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:8467` | 350 × 1344 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Báo giá · Hestia | `370:8468` | 350 × 1344 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:8469;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 0e29566009a59084cd60cae981254b0b0c4bc773 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:8469;365:573` | 81 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Nhận báo giá |
| ↳ ↳ ↳ ↳ Product | `I370:8469;365:574` | 194 × 48 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Hestia — Laser Fractional CO₂ |
| ↳ ↳ ↳ Change product | `I370:8469;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ Label | `I370:8469;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:8479` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8481;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8481;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8486;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8486;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8492;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8492;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8497;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8497;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8503;361:189` | 66 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8503;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8503;361:193` | 316 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nguyễn Minh Anh |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8512;361:189` | 93 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8512;361:190` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8512;361:193` | 316 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8522;361:189` | 155 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8522;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8522;361:193` | 316 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8531;361:189` | 39 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8531;361:191` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8531;361:193` | 316 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:8540;361:250` | 122 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8540;361:252` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8540;361:254` | 286 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Hestia |
| ↳ ↳ ↳ ↳ Label | `I370:8552;361:302` | 62 × 20 | W HUG, H HUG, grow 0 | #6B7C8A · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8552;361:304` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8552;361:306` | 316 × 24 | W FILL, H HUG, grow 1 | #6B7C8A · Be Vietnam Pro / 400 / 16 / 24 / 0 | Cần báo giá cấu hình Hestia. |
| ↳ ↳ ↳ ↳ Label | `I370:8561;361:405` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:8561;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:8569;360:316` | 86 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đang gửi… |
| Aside | `370:8580` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:8581` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:8582` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:8583` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:8584` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:8585` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:8586` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:8587` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:8588` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:8589` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:8590` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:8591` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:8592` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:8593;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:8593;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:8601;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:8601;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:8610;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:8610;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / Hestia · Quote · Success


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:8643](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8643) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:8657](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8657) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:8670](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8670) | 220 | 390 × 932 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:8730](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8730) | 1152 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:8643;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:8643;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:8643;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:8643;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:8643;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:8657;362:314` | 241 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:8657;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:8657;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:8657;362:314;362:278` | 143 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận báo giá thiết bị |
| Title | `I370:8657;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận báo giá thiết bị |
| Description | `I370:8657;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:8671` | 350 × 436 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ AT / Success confirmation | `370:8672` | 350 × 436 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | #FFFFFF | AT / Success confirmation |
| ↳ ↳ Title | `I370:8672;363:555` | 350 × 88 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 36 / 44 / -0.5 | Đã nhận yêu cầu của bạn |
| ↳ ↳ ↳ Intent | `I370:8672;363:557` | 310 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Mục đích: Nhận báo giá |
| ↳ ↳ ↳ Product | `I370:8672;363:558` | 310 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Thiết bị: Hestia — Laser Fractional CO₂ |
| ↳ ↳ Body | `I370:8672;363:559` | 350 × 56 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | A&T Medical sẽ liên hệ theo thông tin bạn cung cấp. |
| ↳ ↳ ↳ Back to product | `I370:8672;363:561` | 197 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #0B2D48 · radius 8 | Emphasis=Primary, Size=MD, State=Default · Prototype → [369:2691](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=369-2691) |
| ↳ ↳ ↳ ↳ Label | `I370:8672;363:561;360:171` | 121 × 24 | W HUG, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 600 / 16 / 24 / 0 | Quay lại Hestia |
| ↳ ↳ ↳ Browse devices | `I370:8672;363:571` | 218 × 52 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 24 / 0 / 24 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=MD, State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ Label | `I370:8672;363:571;360:375` | 139 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Xem thiết bị khác |
| Aside | `370:8700` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:8701` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:8702` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:8703` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:8704` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:8705` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:8706` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:8707` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:8708` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:8709` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:8710` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:8711` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:8712` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:8713;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:8713;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:8721;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:8721;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:8730;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:8730;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI21 / Inquiry / Mobile / Andy · Demo · Failure


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [370:8763](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8763) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [370:8777](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8777) | 64 | 390 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [370:8790](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8790) | 220 | 390 × 2058 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | — |
| Footer | [370:8948](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-8948) | 2278 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I370:8763;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I370:8763;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I370:8763;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I370:8763;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I370:8763;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I370:8777;362:314` | 249 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I370:8777;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I370:8777;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I370:8777;362:314;362:278` | 151 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Đăng ký demo thiết bị |
| Title | `I370:8777;362:324` | 350 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Đăng ký demo thiết bị |
| Description | `I370:8777;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `370:8791` | 350 × 1562 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Demo · Andy | `370:8792` | 350 × 1562 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Image | `I370:8793;365:571` | 64 × 64 | W FIXED, H FIXED, grow 0 | #FFFFFF · Ảnh FIT · 760ce1ee8c44f20640f5adb936370f7f5edb52b2 · radius 6 |  |
| ↳ ↳ ↳ ↳ Intent | `I370:8793;365:573` | 88 × 16 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Đăng ký demo |
| ↳ ↳ ↳ ↳ Product | `I370:8793;365:574` | 194 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Andy — Laser Nd:YAG |
| ↳ ↳ ↳ Change product | `I370:8793;365:575` | 25 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 6, W HUG, H HUG, căn phụ CENTER, grow 0 | — | State=Default · Prototype → [368:1285](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1285) |
| ↳ ↳ ↳ ↳ Label | `I370:8793;365:575;360:623` | 25 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Đổi |
| ↳ ↳ ↳ ↳ Title | `I370:8803;363:321` | 283 × 24 | W FILL, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Chưa gửi được yêu cầu |
| ↳ ↳ ↳ ↳ Body | `I370:8803;363:322` | 283 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Thông tin của bạn vẫn được giữ — bấm Thử lại. |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `370:8811` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8813;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8813;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8818;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8818;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8823;361:433` | 280 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8823;361:434` | 280 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8829;361:427` | 282 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I370:8829;361:428` | 282 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8835;361:167` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8835;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8835;361:171` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Trần Quốc Bảo |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8844;361:167` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I370:8844;361:168` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8844;361:171` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | 0903 222 111 |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8854;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8854;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8854;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I370:8863;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I370:8863;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I370:8863;361:153` | 316 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I370:8872;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8872;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8872;361:202` | 286 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Andy |
| ↳ ↳ ↳ ↳ Label | `I370:8884;361:167` | 149 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thời gian mong muốn |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8884;361:169` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8884;361:171` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Sáng thứ Bảy tuần sau |
| ↳ ↳ ↳ ↳ Label | `I370:8893;361:280` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I370:8893;361:282` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I370:8893;361:284` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Muốn trải nghiệm Andy. |
| ↳ ↳ ↳ ↳ Label | `I370:8902;361:405` | 316 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I370:8902;361:406` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I370:8910;360:273` | 54 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Thử lại |
| Aside | `370:8918` | 350 × 432 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `370:8919` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `370:8920` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `370:8921` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `370:8922` | 320 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `370:8923` | 350 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `370:8924` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `370:8925` | 316 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `370:8926` | 350 × 48 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `370:8927` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `370:8928` | 316 × 48 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `370:8929` | 350 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `370:8930` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I370:8931;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I370:8931;364:642` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I370:8939;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I370:8939;364:651` | 258 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I370:8948;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I370:8948;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## R03 / Inquiry / Tablet 768


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:16865](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16865) | 0 | 768 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:16866](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16866) | 64 | 768 × 156 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Inquiry body | [373:16867](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16867) | 220 | 768 × 1486 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 20 / 24 / 20 / 24 | — |
| Footer | [373:16901](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16901) | 1706 | 768 × 553 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:16865;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo |
| Actions | `I373:16865;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:16865;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:16866;362:314` | 180 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:16866;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:16866;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:16866;362:314;362:278` | 82 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Nhận tư vấn |
| Title | `I373:16866;362:324` | 728 × 40 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Nhận tư vấn |
| Description | `I373:16866;362:325` | 728 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Trường có dấu * là bắt buộc. |

</details>

<details>
<summary>Inquiry body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Form card | `373:16868` | 720 × 1038 | trục VERTICAL, wrap NO_WRAP, W FILL, H HUG, grow 0 | #FFFFFF · radius 16 |  |
| ↳ Inquiry form · Tư vấn | `373:16869` | 720 × 1038 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ Bạn cần A&T hỗ trợ gì? | `373:16870` | 161 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Bạn cần A&T hỗ trợ gì? |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16872;361:433` | 286 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Tư vấn |
| ↳ ↳ ↳ ↳ ↳ Description | `I373:16872;361:434` | 286 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chọn giải pháp phù hợp |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16873;361:427` | 288 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Nhận báo giá |
| ↳ ↳ ↳ ↳ ↳ Description | `I373:16873;361:428` | 288 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Cấu hình và chi phí |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16874;361:427` | 288 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đăng ký demo |
| ↳ ↳ ↳ ↳ ↳ Description | `I373:16874;361:428` | 288 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trải nghiệm thao tác máy |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16875;361:427` | 288 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Đặt lịch xem máy |
| ↳ ↳ ↳ ↳ ↳ Description | `I373:16875;361:428` | 288 × 20 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem máy tại showroom |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16877;361:149` | 66 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Họ và tên |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I373:16877;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I373:16877;361:153` | 686 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nhập họ và tên |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16878;361:149` | 93 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Số điện thoại |
| ↳ ↳ ↳ ↳ ↳ Required mark | `I373:16878;361:150` | 8 × 20 | W HUG, H HUG, grow 0 | #B53838 · Be Vietnam Pro / 600 / 14 / 20 / 0 | * |
| ↳ ↳ ↳ ↳ ↳ Value | `I373:16878;361:153` | 686 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Ví dụ: 0912 345 678 |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16880;361:149` | 155 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Phòng khám / Công ty |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I373:16880;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I373:16880;361:153` | 686 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tên cơ sở |
| ↳ ↳ ↳ ↳ ↳ Label | `I373:16881;361:149` | 39 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Email |
| ↳ ↳ ↳ ↳ ↳ Optional tag | `I373:16881;361:151` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ ↳ Value | `I373:16881;361:153` | 686 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | email@phongkham.vn |
| ↳ ↳ ↳ ↳ Label | `I373:16882;361:198` | 122 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Thiết bị quan tâm |
| ↳ ↳ ↳ ↳ Optional tag | `I373:16882;361:200` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I373:16882;361:202` | 656 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chọn thiết bị |
| ↳ ↳ ↳ ↳ Label | `I373:16883;361:262` | 62 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 14 / 20 / 0 | Nội dung |
| ↳ ↳ ↳ ↳ Optional tag | `I373:16883;361:264` | 120 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | (không bắt buộc) |
| ↳ ↳ ↳ ↳ Value | `I373:16883;361:266` | 686 × 24 | W FILL, H HUG, grow 1 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Câu hỏi hoặc nhu cầu của phòng khám |
| ↳ ↳ ↳ ↳ Label | `I373:16884;361:397` | 686 × 20 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Tôi đồng ý để A&T Medical liên hệ về yêu cầu này theo Chính sách xử lý dữ liệu. |
| ↳ ↳ ↳ ↳ Policy link | `I373:16884;361:398` | 189 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Xem chính sách xử lý dữ liệu |
| ↳ ↳ ↳ Label | `I373:16885;360:273` | 146 × 24 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Gửi yêu cầu tư vấn |
| Aside | `373:16886` | 720 × 384 | trục VERTICAL, wrap NO_WRAP, gap 20, W FILL, H HUG, grow 0 | — |  |
| ↳ Sau khi gửi yêu cầu | `373:16887` | 191 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | Sau khi gửi yêu cầu |
| ↳ Step 01 | `373:16888` | 720 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 01 | `373:16889` | 18 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 01 |
| ↳ ↳ A&T tiếp nhận thông tin và thiết bị bạn  | `373:16890` | 690 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | A&T tiếp nhận thông tin và thiết bị bạn chọn |
| ↳ Step 02 | `373:16891` | 720 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 02 | `373:16892` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 02 |
| ↳ ↳ Chuyên viên liên hệ để làm rõ nhu cầu | `373:16893` | 686 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Chuyên viên liên hệ để làm rõ nhu cầu |
| ↳ Step 03 | `373:16894` | 720 × 24 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ 03 | `373:16895` | 22 × 24 | W HUG, H HUG, grow 0 | #7A5A1F · Be Vietnam Pro / 600 / 16 / 24 / 0 | 03 |
| ↳ ↳ Tư vấn cấu hình, báo giá hoặc xác nhận l | `373:16896` | 686 × 24 | W FILL, H HUG, grow 1 | #182F41 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Tư vấn cấu hình, báo giá hoặc xác nhận lịch |
| ↳ Direct contact | `373:16897` | 720 × 204 | trục VERTICAL, wrap NO_WRAP, gap 4, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ ↳ Cần trao đổi ngay? | `373:16898` | 153 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Cần trao đổi ngay? |
| ↳ ↳ ↳ ↳ Label | `I373:16899;364:641` | 84 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Hotline tư vấn |
| ↳ ↳ ↳ ↳ Value | `I373:16899;364:642` | 628 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | 0948 818 159 |
| ↳ ↳ ↳ ↳ Label | `I373:16900;364:650` | 34 × 16 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 500 / 12 / 16 / 0.2 | Email |
| ↳ ↳ ↳ ↳ Value | `I373:16900;364:651` | 628 × 24 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | customercare@atmedical.vn |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:16901;362:537` | 728 × 376 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:16901;362:565` | 728 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>
