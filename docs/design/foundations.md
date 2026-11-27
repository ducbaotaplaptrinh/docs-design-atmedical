# Foundations · A&T Medical

## Quy tắc triển khai giao diện public

### Responsive và khoảng cách

- Chọn mode Mobile dưới 768 px, Tablet từ 768 đến 1199 px và Desktop từ 1200 px. Dùng các frame 390, 768, 1440 và 1920 px để đối chiếu. Kiểm tra thêm 375, 767, 1199 và 1200 px để phát hiện tràn hoặc gãy bố cục ngay tại điểm đổi mode.
- Căn giữa container theo chiều rộng tối đa 1200 px. Mobile chừa hai lề 20 px, tablet chừa 24 px. Desktop giữ lề tối thiểu 24 px khi sát ngưỡng đổi mode, lề tính ra là 120 px ở 1440 và 360 px ở 1920. Kích thước 350 và 720 px là kết quả tại frame 390 và 768 px.
- Áp dụng `layout/section-y` cho padding trên/dưới section, `layout/section-gap` cho khoảng giữa các cụm nội dung, `layout/grid-gap` cho giữa các cột hoặc thẻ, và `layout/card-pad` cho padding trong thẻ. Dùng bảng token Responsive bên dưới và giữ cùng nhịp giữa các section cùng loại.
- Để chiều cao section và thẻ tăng theo nội dung thực tế. Ưu tiên Grid hoặc Flexbox cho việc xuống cột. Nội dung dài cần bọc dòng. Tab và bảng rộng có thể cuộn trong vùng của chúng, đồng thời trang vẫn vừa viewport.
- Dùng khoảng trống và chiều cao theo header thực tế khi đặt tab bar dính. Kiểm tra nút nổi, tab bar và lớp phủ trên mobile để chúng không che nút hoặc nội dung đang thao tác.

### Màu sắc

- Dùng token theo vai trò của giao diện. Nền mặc định dùng `color/bg/primary`, nền phân lớp dùng `color/bg/subtle`, chữ chính/phụ dùng `color/text/primary` và `color/text/secondary`. Nền tối dùng `color/bg/inverse` với `color/text/inverse`.
- Nút chính dùng nhóm `color/action/default`, `hover`, `pressed` và `disabled`. Nút chuyển đổi màu vàng dùng `color/action/accent` và `color/action/accent-hover` với chữ navy. Nhãn vàng trên nền sáng dùng `color/text/gold`. Kiểm tra độ tương phản trên nền thực tế, kể cả chữ đặt trên ảnh.
- Dùng token trạng thái cho nền và chữ tương ứng. Lỗi và thành công cần có thông báo bằng chữ. Focus bàn phím dùng `color/focus/ring` và phải thấy rõ trên nền hiện tại.

### Font chữ

- Dùng Be Vietnam Pro cho giao diện public. Chọn text style theo vai trò như Display, H1–H4, Body, Label và Overline, giữ cùng lúc weight, cỡ chữ, chiều cao dòng và khoảng cách ký tự theo bảng Typography.
- Dùng style Mobile cho Display và H1–H3 ở mode Mobile, giữ style Desktop ở 1920 px. Trên tablet, ưu tiên style của frame tương ứng và kiểm tra tiêu đề dài khi lưới đổi cột.
- Thử tiêu đề, nhãn nút và nội dung VI/EN dài, bao gồm chữ có dấu. Giữ thứ bậc tiêu đề và cho phép xuống dòng trước khi cân nhắc ngoại lệ về typography.

Các quy tắc triển khai ở trên diễn giải bảng token hiện có. Khi một frame mới có thông số riêng đã được xác nhận, ghi ngoại lệ trong file của trang đó.

## Foundations

Nguồn [380:386](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-386). Dùng navy cho primary, trắng/xám nhạt cho nền, gold cho CTA chuyển đổi và overline. Các đơn vị kích thước là px.

### Màu primitive và semantic

| Primitive | Giá trị | Variable ID | Swatch |
| --- | --- | --- | --- |
| color/white | #FFFFFF | VariableID:358:1080 | [380:546](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-546) |
| color/navy/950 | #071F35 | VariableID:358:1081 | [380:549](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-549) |
| color/navy/900 | #0B2D48 | VariableID:358:1082 | [380:552](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-552) |
| color/navy/800 | #0F3556 | VariableID:358:1083 | [380:555](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-555) |
| color/navy/700 | #174F73 | VariableID:358:1084 | [380:558](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-558) |
| color/blue/700 | #0C517A | VariableID:358:1085 | [380:561](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-561) |
| color/blue/600 | #12699C | VariableID:358:1086 | [380:564](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-564) |
| color/blue/100 | #D6E7F2 | VariableID:358:1087 | [380:567](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-567) |
| color/blue/50 | #EDF5FA | VariableID:358:1088 | [380:570](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-570) |
| color/gold/700 | #7A5A1F | VariableID:358:1089 | [380:573](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-573) |
| color/gold/600 | #A07C3C | VariableID:358:1090 | [380:576](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-576) |
| color/gold/500 | #B99555 | VariableID:358:1091 | [380:579](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-579) |
| color/gold/300 | #D9C190 | VariableID:358:1092 | [380:582](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-582) |
| color/gold/100 | #EFE3CB | VariableID:358:1093 | [380:585](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-585) |
| color/gold/50 | #F7F2E8 | VariableID:358:1094 | [380:588](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-588) |
| color/gray/900 | #182F41 | VariableID:358:1095 | [380:591](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-591) |
| color/gray/600 | #526575 | VariableID:358:1096 | [380:594](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-594) |
| color/gray/500 | #6B7C8A | VariableID:358:1097 | [380:597](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-597) |
| color/gray/400 | #8796A1 | VariableID:358:1098 | [380:600](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-600) |
| color/gray/200 | #D9E2E8 | VariableID:358:1099 | [380:603](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-603) |
| color/gray/100 | #EAF0F4 | VariableID:358:1100 | [380:606](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-606) |
| color/gray/50 | #F5F8FA | VariableID:358:1101 | [380:609](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-609) |
| color/green/700 | #257052 | VariableID:358:1102 | [380:612](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-612) |
| color/green/50 | #EEF8F2 | VariableID:358:1103 | [380:615](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-615) |
| color/red/700 | #B53838 | VariableID:358:1104 | [380:618](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-618) |
| color/red/50 | #FFF2F2 | VariableID:358:1105 | [380:621](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-621) |
| color/amber/700 | #8A4B00 | VariableID:358:1106 | [380:624](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-624) |
| color/amber/50 | #FFF4DE | VariableID:358:1107 | [380:627](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-627) |
| color/navy/overlay | #071F35 / 64% | VariableID:358:1108 | [380:630](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-630) |


| Semantic | Alias ghi trên styleguide | Fill trên swatch | Variable ID | Swatch |
| --- | --- | --- | --- | --- |
| color/bg/primary | color/white | #FFFFFF | VariableID:358:1144 | [380:394](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-394) |
| color/bg/subtle | color/gray/50 | #F5F8FA | VariableID:358:1145 | [380:398](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-398) |
| color/bg/accent | color/blue/50 | #EDF5FA | VariableID:358:1146 | [380:402](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-402) |
| color/bg/gold | color/gold/50 | #F7F2E8 | VariableID:358:1147 | [380:406](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-406) |
| color/bg/inverse | color/navy/950 | #071F35 | VariableID:358:1148 | [380:410](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-410) |
| color/bg/brand | color/navy/900 | #0B2D48 | VariableID:358:1149 | [380:414](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-414) |
| color/bg/overlay | color/navy/overlay | #071F35 / 64% | VariableID:358:1150 | [380:418](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-418) |
| color/text/primary | color/gray/900 | #182F41 | VariableID:358:1151 | [380:422](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-422) |
| color/text/secondary | color/gray/600 | #526575 | VariableID:358:1152 | [380:426](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-426) |
| color/text/inverse | color/white | #FFFFFF | VariableID:358:1153 | [380:430](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-430) |
| color/text/disabled | color/gray/500 | #6B7C8A | VariableID:358:1154 | [380:434](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-434) |
| color/text/brand | color/navy/900 | #0B2D48 | VariableID:358:1155 | [380:438](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-438) |
| color/text/gold | color/gold/700 | #7A5A1F | VariableID:358:1156 | [380:442](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-442) |
| color/border/default | color/gray/200 | #D9E2E8 | VariableID:358:1157 | [380:446](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-446) |
| color/border/strong | color/gray/400 | #8796A1 | VariableID:358:1158 | [380:450](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-450) |
| color/border/divider | color/gray/100 | #EAF0F4 | VariableID:358:1159 | [380:454](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-454) |
| color/border/inverse | color/navy/700 | #174F73 | VariableID:358:1160 | [380:458](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-458) |
| color/border/focus | color/blue/600 | #12699C | VariableID:358:1161 | [380:462](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-462) |
| color/action/default | color/navy/900 | #0B2D48 | VariableID:358:1162 | [380:466](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-466) |
| color/action/hover | color/navy/800 | #0F3556 | VariableID:358:1163 | [380:470](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-470) |
| color/action/pressed | color/navy/950 | #071F35 | VariableID:358:1164 | [380:474](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-474) |
| color/action/disabled | color/gray/100 | #EAF0F4 | VariableID:358:1165 | [380:478](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-478) |
| color/action/disabled-text | color/gray/500 | #6B7C8A | VariableID:358:1166 | [380:482](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-482) |
| color/action/secondary/hover | color/gray/50 | #F5F8FA | VariableID:358:1167 | [380:486](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-486) |
| color/action/accent | color/gold/500 | #B99555 | VariableID:358:1168 | [380:490](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-490) |
| color/action/accent-hover | color/gold/300 | #D9C190 | VariableID:358:1169 | [380:494](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-494) |
| color/accent/gold | color/gold/500 | #B99555 | VariableID:358:1170 | [380:498](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-498) |
| color/accent/blue | color/blue/600 | #12699C | VariableID:358:1171 | [380:502](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-502) |
| color/focus/ring | color/blue/600 | #12699C | VariableID:358:1172 | [380:506](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-506) |
| color/status/success | color/green/700 | #257052 | VariableID:358:1173 | [380:510](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-510) |
| color/status/success-bg | color/green/50 | #EEF8F2 | VariableID:358:1174 | [380:514](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-514) |
| color/status/warning | color/amber/700 | #8A4B00 | VariableID:358:1175 | [380:518](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-518) |
| color/status/warning-bg | color/amber/50 | #FFF4DE | VariableID:358:1176 | [380:522](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-522) |
| color/status/error | color/red/700 | #B53838 | VariableID:358:1177 | [380:526](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-526) |
| color/status/error-bg | color/red/50 | #FFF2F2 | VariableID:358:1178 | [380:530](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-530) |
| color/status/info | color/blue/600 | #12699C | VariableID:358:1179 | [380:534](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-534) |
| color/status/info-bg | color/blue/50 | #EDF5FA | VariableID:358:1180 | [380:538](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-538) |

### Typography

Font **Be Vietnam Pro**. Cột tracking là letter spacing theo px. Dùng style Mobile tương ứng ở viewport nhỏ và giữ typography desktop ở 1920.

| Style | Weight | Cỡ | Line height | Tracking | Node |
| --- | --- | --- | --- | --- | --- |
| AT/Display/XL | 500 | 72 | 80 | -1.4 | [380:637](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-637) |
| AT/Display/Desktop | 500 | 56 | 64 | -1 | [380:640](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-640) |
| AT/Display/Mobile | 500 | 36 | 44 | -0.5 | [380:643](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-643) |
| AT/Heading/H1 | 500 | 48 | 56 | -0.8 | [380:646](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-646) |
| AT/Heading/H1 Mobile | 500 | 32 | 40 | -0.4 | [380:649](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-649) |
| AT/Heading/H2 | 500 | 36 | 44 | -0.5 | [380:652](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-652) |
| AT/Heading/H2 Mobile | 500 | 26 | 34 | -0.3 | [380:655](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-655) |
| AT/Heading/H3 | 600 | 24 | 32 | -0.2 | [380:658](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-658) |
| AT/Heading/H3 Mobile | 600 | 20 | 28 | 0 | [380:661](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-661) |
| AT/Heading/H4 | 600 | 20 | 28 | 0 | [380:664](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-664) |
| AT/Body/Large | 400 | 18 | 28 | 0 | [380:667](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-667) |
| AT/Body/Default | 400 | 16 | 24 | 0 | [380:670](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-670) |
| AT/Body/Small | 400 | 14 | 20 | 0 | [380:673](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-673) |
| AT/Label/Large | 600 | 16 | 24 | 0 | [380:676](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-676) |
| AT/Label/Default | 600 | 14 | 20 | 0 | [380:679](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-679) |
| AT/Label/Small | 500 | 12 | 16 | 0.2 | [380:682](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-682) |
| AT/Overline | 600 | 12 | 16 | 1.4 | [380:685](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-685) |
| AT/Data/Value | 600 | 40 | 48 | -0.6 | [380:688](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-688) |

### Spacing, radius, elevation và motion

- Spacing trong styleguide: `0, 2, 4, 6, 8, 12, 16, 20, 24, 32, 40, 48, 56, 64, 80, 96, 112`.
- Radius: `0, 4, 8, 12, 16, 24, 999`. Nút/field 8, card 12–16, panel 24, chip 999.
- Motion: dissolve 200 ms ease-out cho chuyển trang/overlay, hover 150 ms, accordion/tab 200 ms, toast 240 ms và tự ẩn sau 5 giây. Carousel không tự chạy. Với `prefers-reduced-motion`, đổi trạng thái tức thì.
- Focus theo ghi chú: ring 2 px, offset 2 px và hiển thị khi dùng bàn phím.

| Layer | Effect | X | Y | Blur | Spread | Màu |
| --- | --- | --- | --- | --- | --- | --- |
| [380:847](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-847) | DROP_SHADOW | 0 | 4 | 16 | -4 | #071F35 / 6% |
| [380:850](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-850) | DROP_SHADOW | 0 | 16 | 48 | -8 | #071F35 / 18% |
| [380:853](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=380-853) | DROP_SHADOW | 0 | 0 | 0 | 3 | #12699C / 50% |


## Responsive

Nguồn quy tắc [373:17560](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-17560) và ghi chú bàn giao [381:292](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=381-292).

| Token | Mobile <768 | Tablet 768–1199 | Desktop ≥1200 |
| --- | --- | --- | --- |
| layout/container | 350 | 720 | 1200 |
| layout/page-margin tại frame tham chiếu | 20 tại 390 | 24 tại 768 | 120 tại 1440 |
| layout/section-y | 48 | 64 | 96 |
| layout/section-gap | 24 | 32 | 48 |
| layout/grid-gap | 16 | 20 | 24 |
| layout/header-h | 64 | 72 | 80 |
| layout/card-pad | 16 | 20 | 24 |
| Lưới thẻ tổng quát | 1 cột | 2 cột | 3–4 cột |
| Điều hướng | Menu drawer | Menu drawer | Nav + mega menu |


| Frame | Kích thước | Figma |
| --- | --- | --- |
| UI01 / Home / Mobile | 390 × 9285 | [367:614](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=367-614) |
| R01 / Home / Tablet 768 | 768 × 6443 | [373:16200](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-16200) |
| UI01 / Home / Desktop | 1440 × 6099 | [367:2](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=367-2) |
| R04 / Home / Wide 1920 | 1920 × 6099 | [373:17041](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=373-17041) |

- 1920: container 1200 căn giữa, giữ nguyên cỡ chữ. Các số 350/720 là chiều rộng tham chiếu trong mode tương ứng. Dùng chiều rộng khả dụng theo gutter và giới hạn container khi triển khai trên các viewport nằm giữa các mẫu.
- Ảnh thiết bị 4:3, `object-fit: contain`. Ảnh sự kiện/bài viết 16:9, `object-fit: cover`. Mobile đặt tóm tắt và CTA trước gallery ở trang chi tiết, in-page nav cuộn ngang. Ẩn floating contact khi form trong viewport.
- Trang mobile còn có frame Home 375 [387:18450](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=387-18450) và các frame popup/menu 375. Mẫu responsive chuẩn trong Readme là UI01 Mobile 390.
