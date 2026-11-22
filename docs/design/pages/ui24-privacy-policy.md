# UI24 · Privacy policy (draft layout)

Đọc [Foundations](../foundations.md), [Components](../components.md) và [ghi chú bàn giao](../handoff.md). Nguồn và phiên bản ở [mục lục](../figma-spec.md).

Nội dung dưới đây là mẫu thiết kế. Đối chiếu dữ liệu thật, bản dịch và khả năng chỉnh sửa trong Admin trước khi triển khai. Kích thước đo trong Figma là tham chiếu. Cho phép chiều cao thay đổi theo nội dung. Với chiều rộng chưa có frame riêng, dùng quy tắc ở Foundations.
## Frame và trạng thái

| Frame | Node | W × H |
| --- | --- | --- |
| UI24 / Privacy policy (draft layout) / Desktop | [373:6810](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6810) | 1440 × 1357 |
| UI24 / Privacy policy (draft layout) / Mobile | [373:11750](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11750) | 390 × 1981 |

Figma đánh dấu bố cục là bản nháp. Nội dung chính sách cần bản được duyệt trước khi công bố.

## UI24 / Privacy policy (draft layout) / Desktop


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:6811](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6811) | 0 | 1440 × 80 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 120 / 0 / 120 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:6844](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6844) | 80 | 1440 × 192 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 32 / 120 / 32 / 120 | #F5F8FA |
| Legal body | [373:6857](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6857) | 272 | 1440 × 704 | trục HORIZONTAL, wrap NO_WRAP, gap 64, W FILL, H HUG, grow 0, pad 96 / 120 / 96 / 120 | — |
| Footer | [373:6879](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6879) | 976 | 1440 × 381 | trục VERTICAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0, pad 72 / 120 / 40 / 120 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:6811;362:198` | 84 × 56 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:2 |
| Primary nav | `I373:6811;362:199` | 551 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 32, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ Nav · Thiết bị | `I373:6811;362:200` | 81 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:15059](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15059) |
| ↳ Nav · Về A&T | `I373:6811;362:207` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5340](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5340) |
| ↳ Nav · Sự kiện | `I373:6811;362:212` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [372:5327](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=372-5327) |
| ↳ Nav · Dịch vụ | `I373:6811;362:217` | 60 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:5145](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-5145) |
| ↳ Nav · Kiến thức | `I373:6811;362:222` | 74 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [373:6342](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-6342) |
| ↳ Nav · Liên hệ | `I373:6811;362:227` | 58 × 80 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H FIXED, căn phụ CENTER, grow 0, pad 0 / 4 / 0 / 4 | viền #D9E2E8 0 | State=Default · Prototype → [371:4850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=371-4850) |
| Actions | `I373:6811;362:232` | 275 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:6811;401:660;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:6811;362:233` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15161](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15161) |
| ↳ CTA consult | `I373:6811;362:238` | 119 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #B99555 · radius 8 | Emphasis=Accent, Size=SM, State=Default · Prototype → [370:2859](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=370-2859) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:6844;362:301` | 256 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:6844;362:301;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:6844;362:301;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:6844;362:301;362:278` | 158 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chính sách xử lý dữ liệu |
| Title | `I373:6844;362:311` | 1200 × 56 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 48 / 56 / -0.8 | Chính sách xử lý dữ liệu cá nhân |
| Description | `I373:6844;362:312` | 720 × 28 | W FIXED, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Ngày hiệu lực: đang cập nhật |

</details>

<details>
<summary>Legal body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Table of contents | `373:6858` | 300 × 232 | trục VERTICAL, wrap NO_WRAP, gap 8, W FIXED, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ Mục lục | `373:6859` | 62 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Mục lục |
| ↳ 1. Phạm vi áp dụng | `373:6860` | 126 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 1. Phạm vi áp dụng |
| ↳ 2. Dữ liệu được thu thập | `373:6861` | 162 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 2. Dữ liệu được thu thập |
| ↳ 3. Mục đích xử lý | `373:6862` | 114 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 3. Mục đích xử lý |
| ↳ 4. Thời gian lưu trữ | `373:6863` | 127 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 4. Thời gian lưu trữ |
| ↳ 5. Quyền của chủ thể dữ liệu | `373:6864` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 5. Quyền của chủ thể dữ liệu |
| ↳ 6. Liên hệ | `373:6865` | 66 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 6. Liên hệ |
| Content | `373:6866` | 836 × 512 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 1 | — |  |
| ↳ 1. Phạm vi áp dụng | `373:6867` | 217 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 1. Phạm vi áp dụng |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6868` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 2. Dữ liệu được thu thập | `373:6869` | 278 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 2. Dữ liệu được thu thập |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6870` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 3. Mục đích xử lý | `373:6871` | 196 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 3. Mục đích xử lý |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6872` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 4. Thời gian lưu trữ | `373:6873` | 220 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 4. Thời gian lưu trữ |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6874` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 5. Quyền của chủ thể dữ liệu | `373:6875` | 329 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 5. Quyền của chủ thể dữ liệu |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6876` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 6. Liên hệ | `373:6877` | 114 × 32 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 24 / 32 / -0.2 | 6. Liên hệ |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:6878` | 836 × 24 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:6879;362:505` | 1200 × 176 | trục HORIZONTAL, wrap NO_WRAP, gap 48, W FILL, H HUG, grow 0 | — |  |
| ↳ ↳ ↳ Link · Trị sẹo – Trẻ hóa da | `I373:6879;362:515` | 250.67 × 20 | W FILL, H HUG, grow 0 | #FFFFFF · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trị sẹo – Trẻ hóa da · Prototype → [368:1072](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=368-1072) |
| Bottom bar | `I373:6879;362:533` | 1200 × 45 | trục HORIZONTAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>

## UI24 / Privacy policy (draft layout) / Mobile


| Section | Node | Y | W × H | Auto Layout | Fill |
| --- | --- | --- | --- | --- | --- |
| Header | [373:11751](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11751) | 0 | 390 × 64 | trục HORIZONTAL, wrap NO_WRAP, W FILL, H FIXED, căn chính SPACE_BETWEEN, căn phụ CENTER, grow 0, pad 0 / 20 / 0 / 20 | #FFFFFF · viền #D9E2E8 0 |
| Subhero | [373:11765](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11765) | 64 | 390 × 196 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, grow 0, pad 20 / 20 / 24 / 20 | #F5F8FA |
| Legal body | [373:11778](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11778) | 260 | 390 × 984 | trục VERTICAL, wrap NO_WRAP, gap 24, W FILL, H HUG, grow 0, pad 48 / 20 / 48 / 20 | — |
| Footer | [373:11800](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-11800) | 1244 | 390 × 737 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0, pad 48 / 20 / 32 / 20 | #071F35 |

<details>
<summary>Header</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Logo | `I373:11751;362:249` | 68 × 45 | W FIXED, H FIXED, grow 0 | Ảnh FIT · dfd9f2a624e36addd6c0325455505155e584f7e4 | AT / Brand / Logo · Prototype → 367:614 |
| Actions | `I373:11751;362:250` | 245 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 4, W HUG, H HUG, căn phụ CENTER, grow 0 | — |  |
| ↳ ↳ Option · EN | `I373:11751;401:665;401:638` | 40 × 32 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Prototype → 401:640 |
| ↳ Search trigger | `I373:11751;362:251` | 44 × 44 | trục HORIZONTAL, wrap NO_WRAP, W FIXED, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0 | radius 999 | Style=Ghost, State=Default · Prototype → [373:15902](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15902) |
| ↳ Menu trigger | `I373:11751;362:256` | 105 × 44 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H FIXED, căn chính CENTER, căn phụ CENTER, grow 0, pad 0 / 18 / 0 / 18 | #FFFFFF · viền #0B2D48 1.5 · radius 8 | Emphasis=Secondary, Size=SM, State=Default · Prototype → [373:15721](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-15721) |

</details>

<details>
<summary>Subhero</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| AT / Breadcrumb | `I373:11765;362:314` | 256 × 20 | trục HORIZONTAL, wrap NO_WRAP, gap 8, W HUG, H HUG, căn phụ CENTER, grow 0 | — | AT / Breadcrumb |
| ↳ Level 1 | `I373:11765;362:314;362:270` | 68 × 20 | W HUG, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Trang chủ |
| ↳ AT / Icon / chevron-right | `I373:11765;362:314;362:271` | 14 × 14 | W FIXED, H FIXED, grow 0 | — | AT / Icon / chevron-right |
| ↳ Current | `I373:11765;362:314;362:278` | 158 × 20 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 400 / 14 / 20 / 0 | Chính sách xử lý dữ liệu |
| Title | `I373:11765;362:324` | 350 × 80 | W FILL, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 500 / 32 / 40 / -0.4 | Chính sách xử lý dữ liệu cá nhân |
| Description | `I373:11765;362:325` | 350 × 28 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 18 / 28 / 0 | Ngày hiệu lực: đang cập nhật |

</details>

<details>
<summary>Legal body</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Table of contents | `373:11779` | 350 × 232 | trục VERTICAL, wrap NO_WRAP, gap 8, W FILL, H HUG, grow 0, pad 20 / 20 / 20 / 20 | #F5F8FA · radius 12 |  |
| ↳ Mục lục | `373:11780` | 62 × 24 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 16 / 24 / 0 | Mục lục |
| ↳ 1. Phạm vi áp dụng | `373:11781` | 126 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 1. Phạm vi áp dụng |
| ↳ 2. Dữ liệu được thu thập | `373:11782` | 162 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 2. Dữ liệu được thu thập |
| ↳ 3. Mục đích xử lý | `373:11783` | 114 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 3. Mục đích xử lý |
| ↳ 4. Thời gian lưu trữ | `373:11784` | 127 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 4. Thời gian lưu trữ |
| ↳ 5. Quyền của chủ thể dữ liệu | `373:11785` | 191 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 5. Quyền của chủ thể dữ liệu |
| ↳ 6. Liên hệ | `373:11786` | 66 × 20 | W HUG, H HUG, grow 0 | #0B2D48 · Be Vietnam Pro / 400 / 14 / 20 / 0 | 6. Liên hệ |
| Content | `373:11787` | 350 × 632 | trục VERTICAL, wrap NO_WRAP, gap 16, W FILL, H HUG, grow 0 | — |  |
| ↳ 1. Phạm vi áp dụng | `373:11788` | 184 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 1. Phạm vi áp dụng |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11789` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 2. Dữ liệu được thu thập | `373:11790` | 236 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 2. Dữ liệu được thu thập |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11791` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 3. Mục đích xử lý | `373:11792` | 166 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 3. Mục đích xử lý |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11793` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 4. Thời gian lưu trữ | `373:11794` | 186 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 4. Thời gian lưu trữ |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11795` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 5. Quyền của chủ thể dữ liệu | `373:11796` | 279 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 5. Quyền của chủ thể dữ liệu |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11797` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |
| ↳ 6. Liên hệ | `373:11798` | 97 × 28 | W HUG, H HUG, grow 0 | #182F41 · Be Vietnam Pro / 600 / 20 / 28 / 0 | 6. Liên hệ |
| ↳ Nội dung mục này do bộ phận pháp chế A&T | `373:11799` | 350 × 48 | W FILL, H HUG, grow 0 | #526575 · Be Vietnam Pro / 400 / 16 / 24 / 0 | Nội dung mục này do bộ phận pháp chế A&T cung cấp. |

</details>

<details>
<summary>Footer</summary>

| Layer | Node | W × H | Auto Layout | Fill / typography | Nội dung / tương tác |
| --- | --- | --- | --- | --- | --- |
| Columns | `I373:11800;362:537` | 350 × 560 | trục VERTICAL, wrap NO_WRAP, gap 32, W FILL, H HUG, grow 0 | — |  |
| Bottom bar | `I373:11800;362:565` | 350 × 65 | trục VERTICAL, wrap NO_WRAP, gap 12, W FILL, H HUG, căn chính SPACE_BETWEEN, grow 0, pad 24 / 0 / 0 / 0 | viền #174F73 1 |  |

</details>
