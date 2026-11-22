# Bàn giao nội dung và triển khai

## Ghi chú nội dung và bàn giao

Nguồn [381:292](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=381-292) và pending register [381:2](https://www.figma.com/design/uYPcN6opDF68E7Bs7dQT0X/AT-Medical-%E2%80%93-Homepage?node-id=381-2).
- Content model (đề xuất)
- Entity
- Trường chính
- Product
- id, slug, name, needGroup[], technology, summary, images[] (4:3, alt), specs[] {label, value, status: verified|updating, source}, documents[] {title, url|null, lang}, faq[], related[], status: published|pending
- Event
- id, title, date, location, status: open|full|cancelled|ended, capacity, image (16:9), recapArticleId
- Article
- id, title, date, category, cover (16:9), body, relatedIds[]
- Inquiry
- productId?, intent: consult|quote|demo|visit, name*, phone*, company?, email?, message?, consent* (version chính sách), source (page/section), utm?
- Contract form & intent
- • CTA trên trang sản phẩm gọi /lien-he?product=<slug>&intent=<quote|demo|visit>&source=<section>; form điền sẵn Product summary + Intent; người dùng có thể đổi.<br>• Bắt buộc: Họ tên, SĐT (định dạng VN), checkbox đồng ý (không tick sẵn). Email / công ty tùy chọn.<br>• Submit: disable nút + spinner; lỗi mạng giữ nguyên dữ liệu, hiện Alert + nút Thử lại; success hiển thị tóm tắt yêu cầu, không hứa thời gian.<br>• Prototype success / failure chỉ là mô phỏng — chưa có tích hợp CRM / email.
- Responsive
- • Breakpoints: <768 mobile · 768–1199 tablet · ≥1200 desktop; container 1200 (max), margin 120/24/20, section-y 96/64/48 theo collection AT / Layout.<br>• Lưới thẻ: 4/3 cột desktop, 2 cột tablet, 1 cột mobile. Ảnh thiết bị 4:3 object-fit: contain; ảnh sự kiện / bài 16:9 cover.<br>• Header: desktop nav + mega menu; ≤1199 dạng Menu drawer. Floating contact ẩn khi form trong viewport.<br>• 1920: giữ container 1200 căn giữa; không scale chữ.
- Accessibility & tương tác
- • Mục tiêu WCAG 2.2 AA: tương phản chữ ≥ 4.5:1 (navy trên gold ~5:1), vùng chạm ≥ 44px, focus ring hiển thị.<br>• Drawer / modal / lightbox: trap focus, Esc đóng, trả focus về nút mở; aria-expanded cho accordion / nav.<br>• Lỗi form: aria-describedby + tóm tắt lỗi có link; không chỉ dùng màu.<br>• prefers-reduced-motion: tắt chuyển động.
- Tracking (không gửi PII)
- • Sự kiện: cta_click {intent, product_slug, source}, inquiry_submit {intent, product_slug, result: success|error}, search {query_length, results_count}, filter_apply {need, technology}.<br>• Không gửi họ tên, SĐT, email, nội dung tin nhắn vào analytics / URL.
- Ngoài phạm vi
- CMS admin, tích hợp CRM / email, nội dung pháp lý chính thức, publish / go-live.

Các mục nội dung đang chờ duyệt hoặc bổ sung:
- Mã · Trang / frame · Nội dung thiếu · Nguồn hiện có · Ảnh hưởng · Fallback an toàn đang dùng
- C01 · UI05–UI12 · Thông số · Thông số kỹ thuật chi tiết đã xác minh từng máy · Catalogue / website cũ (chưa đối chiếu) · Bảng thông số · Dòng “Đang cập nhật” (Spec row Updating); chỉ hiển thị trường đã có nguồn
- C02 · UI07 Q Master Plus · Ảnh, công nghệ, nhóm nhu cầu, mô tả · Không có (không dùng ảnh Q Master) · Thẻ & trang chi tiết · “Hình ảnh đang cập nhật”, “Thông tin đang cập nhật”; ẩn zoom
- C03 · UI16 Dịch vụ · SLA / thời gian phản hồi bảo hành · Không có · Khối hậu mãi · Không hiển thị SLA; mô tả quy trình chung
- C04 · UI01 / UI02 · Số liệu (số máy lắp đặt, phòng khám, năm…) · Không có số đã xác minh · Trust bar · Dùng Trust item dạng năng lực, không số
- C06 · Toàn site · Copy marketing chính thức (hero, giới thiệu) · Brief + website cũ · Hero, section intro · Copy trung tính do designer đề xuất — cần duyệt
- C07 · UI05–UI12 · File catalogue / brochure PDF · Chưa có link · Document link · State “Gửi yêu cầu để nhận tài liệu”
- C08 · UI05–UI12 · Chỉ định / chống chỉ định lâm sàng, kết quả điều trị · Không có · Mục ứng dụng · Chỉ nêu nhóm ứng dụng; không cam kết kết quả, không before/after
- C09 · Footer / UI19 · URL mạng xã hội, kênh video · Chưa xác nhận · Footer, Media · Ẩn icon social (prop social hidden); không hiển thị kênh trống
- C10 · UI20 Liên hệ · Showroom, giờ mở cửa, bản đồ · Địa chỉ 166–168A Phạm Phú Thứ (footer website cũ) — chờ xác nhận · Contact, Showroom card · Giờ: “Đang cập nhật”; map placeholder
- C11 · UI01 / UI02 · Logo đối tác + quyền sử dụng · Chưa có · Partner tiles · Tên đối tác dạng chữ
- C13 · UI13 / UI14 · Sự kiện sắp tới thật · Chỉ có sự kiện đã qua (APEX 2026, Workshop, Hestia Night) · Events · State “No upcoming”; frame Open / Full / Cancelled dùng dữ liệu mẫu có nhãn
- C14 · UI15 Chuyển giao · Ảnh chuyển giao / lắp đặt thật · Không có (không dùng ảnh sửa máy) · Handover cards · Ảnh sự kiện đã có nguồn; ô ảnh trống “Hình ảnh đang cập nhật”
- C15 · UI24 Chính sách · Nội dung pháp lý đã duyệt · Không có · Privacy page, consent · Layout draft, gắn nhãn “Bản nháp” — chưa được xác nhận pháp lý
- C16 · UI05–UI12 · Ảnh sản phẩm sạch (không watermark), nhiều góc · Ảnh website cũ có watermark · Gallery · Dùng 1 ảnh có sẵn, ẩn thumbnail thiếu
- C17 · Header / Footer · Logo SVG gốc · PNG · Logo · PNG độ phân giải hiện có
- C18 · UI19 Media · Video (URL / file) · Chưa có · Video poster · Poster tĩnh, không nút play giả
- C19 · UI17 / UI18 / FAQ · Bài viết đầy đủ, FAQ chính thức · Tiêu đề bài có trên website cũ · Article, FAQ · Đoạn trích ngắn; FAQ đề xuất cần duyệt
- C20 · UI20 / Floating · Hotline kỹ thuật riêng · Không có · Contact · Chỉ hotline tư vấn 0948 818 159 (nguồn footer) — chờ xác nhận
- C21 · UI02 Giới thiệu · Lịch sử công ty, mốc thời gian · Không có số liệu xác minh · About · Mô tả năng lực, không mốc năm
- C22 · Catalog · Taxonomy nhóm nhu cầu / công nghệ chính thức · Brief · Bộ lọc, chip · 4 nhóm nhu cầu + 4 công nghệ đề xuất
- C23 · UI21 / UI14 · Nội dung email / SMS xác nhận, thời gian liên hệ lại · Không có · Success state · Không hứa thời gian cụ thể; “Đội ngũ A&T sẽ liên hệ lại”
