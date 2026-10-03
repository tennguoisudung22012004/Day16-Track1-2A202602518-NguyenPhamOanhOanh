# Memo Teardown — Figma

**Họ tên: Nguyễn Phạm Oanh Oanh**

**Vì sao chọn sản phẩm này:** Figma cho thấy rõ cách một công cụ thiết kế cộng tác trên web mở rộng sang nhiều khâu của phát triển sản phẩm. Các mốc từ FigJam đến Figma Make cũng giúp phân tích sự dịch chuyển từ người thiết kế sang cả nhóm sản phẩm.

**§1. Timeline các cập nhật lớn**

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
|---|---|---|---|
| 2015-12 — [Preview Release](https://www.figma.com/blog/design-meet-the-internet/) | Ra mắt bản preview của công cụ thiết kế vector UI trên web. | Phần mềm sáng tạo khi đó chủ yếu dựa vào ứng dụng cài máy; nhóm sáng lập nhấn mạnh chia sẻ bằng link và cộng tác. | Đưa công cụ lên web để giảm rào cản truy cập và cộng tác ngay trên cùng thiết kế. |
| 2019-10 — [Figma Community](https://www.figma.com/blog/introducing-figma-community/) | Cho phép công khai, xem, remix và học từ tệp thiết kế; đồng thời ra mắt không gian làm việc nhóm. | Người dùng đã chia sẻ tài nguyên và mở thiết kế cho đồng đội; sản phẩm mở rộng từ công cụ cá nhân/nhóm thành hệ sinh thái. | Tận dụng nội dung cộng đồng để tăng khả năng khám phá, tái sử dụng và học hỏi. |
| 2021-04 — [FigJam](https://www.figma.com/blog/introducing-figjam/) | Ra mắt bảng trắng trực tuyến cho brainstorming và ideation. | Figma nhận thấy nhóm dùng canvas để trao đổi, lên ý tưởng và làm việc từ xa, không chỉ đẩy pixel hay làm sản phẩm. | Đưa cộng tác vào sớm hơn trong quy trình và mời người chưa chuyên thiết kế tham gia. |
| 2023-06 — [Dev Mode](https://www.figma.com/blog/introducing-dev-mode/) | Tạo không gian cho developer xem thông số, cấu trúc, tài nguyên và ngữ cảnh cần để triển khai thiết kế. | Figma cho biết trên các gói trả phí, developer truy cập nhiều hơn designer. | Mở rộng từ thiết kế sang bàn giao, giảm ma sát giữa design và development. |
| 2024-06 — [Figma Slides](https://www.figma.com/blog/introducing-figma-slides/) | Mở beta công cụ thuyết trình, kết hợp khả năng thiết kế của Figma với cộng tác; hỗ trợ designer và người không chuyên. | Figma cho biết người dùng đã tạo khoảng 3,5 triệu bài thuyết trình trong năm trước và thường phải chuyển thiết kế sang công cụ khác. | Mở rộng sang một công việc liền kề, đồng thời tái sử dụng tài sản và kỹ năng sẵn có. |
| 2025-05 — [Figma Make](https://www.figma.com/blog/introducing-figma-make/) | Ra mắt công cụ prompt-to-app để biến thiết kế hoặc mô tả thành trải nghiệm tương tác. | Tạo prototype có thể trải nghiệm thường tốn thời gian hoặc đòi hỏi biết code; Make đặt AI ngay trong canvas cộng tác. | Rút ngắn khoảng cách từ ý tưởng đến prototype, tận dụng cấu trúc thiết kế sẵn có thay vì bắt đầu từ số không. |

**Vì sao chọn những mốc này:** Sáu mốc thể hiện ba lần mở rộng rõ nhất: từ thiết kế cộng tác, sang hệ sinh thái và ideation, rồi sang bàn giao và tạo prototype bằng AI. Tôi bỏ qua các cập nhật nhỏ vì chúng ít cho thấy sự thay đổi về người dùng hoặc công việc Figma giải quyết.

**§2. Tệp user & JTBD**

| | Early adopters | Tệp hiện tại |
|---|---|---|
| Đặc điểm | Designer UI/UX và nhóm sản phẩm quen công cụ số, cần cùng xem và sửa thiết kế trên web. | Designer vẫn là lõi; developer, PM và người không chuyên thiết kế cùng tham gia ideation, bàn giao hoặc thuyết trình. |
| JTBD chính | Thiết kế giao diện số, nhận phản hồi và lặp nhanh cùng nhóm. | Giúp nhóm đi từ ý tưởng đến thiết kế, prototype, bàn giao và thống nhất quyết định trong cùng không gian làm việc. |
| Trước đó họ làm bằng cách nào | Công cụ thiết kế cài máy, gửi file/ảnh và phối hợp qua các lần bàn giao. | Ghép các công cụ rời cho brainstorming, thiết kế, handoff và slide; phải chuyển nội dung hoặc ngữ cảnh giữa chúng. |

**Dịch chuyển tệp:** FigJam (2021) mời cả nhóm vào giai đoạn ý tưởng; Dev Mode (2023) phục vụ developer; Slides (2024) nhắm cả người không chuyên thiết kế. Make (2025) tiếp tục hạ rào cản tạo prototype. Các mốc này mở rộng người tham gia bằng cách đưa thêm công việc liền kề vào quy trình Figma, thay vì chỉ thêm công cụ cho designer.

**Switching cost (map 4 forces):**
- **Push khỏi cách làm hiện tại:** Chuyển qua lại giữa tệp thiết kế, whiteboard, handoff và slide làm mất thời gian, dễ mất ngữ cảnh.
- **Pull sang Figma:** Cộng tác bằng link, thư viện dùng chung và các công cụ nối tiếp nhau khiến nhóm có thể làm nhiều khâu trong một workspace.
- **Anxiety khi đổi khỏi Figma:** Có thể mất thư viện/component, tệp, prototype, bình luận và quy trình nhóm; cần thời gian chuyển đổi, kiểm tra và học lại.
- **Habit/inertia giữ lại:** Đồng đội, design system, lịch sử tệp và workflow đã tích lũy tạo giá trị mạng lưới. Lực kéo đi có thể đến từ nhu cầu chuyên biệt hoặc công cụ AI thay thế tốt hơn; đây là rủi ro suy luận, không phải kết luận từ số liệu người dùng.

**§3. Ba dự đoán hướng đi (6–12 tháng tới: 2027-04 đến 2027-10)**

**Dự đoán 1** *(loại: mở rộng tính năng)*
- **Dự đoán:** Figma Make sẽ tiến gần hơn từ prototype tương tác tới prototype dùng được với dữ liệu và design system thực tế.
- **Lập luận:** Make đã biến thiết kế thành trải nghiệm tương tác; bài ra mắt còn nêu kết nối cơ sở dữ liệu bên thứ ba và design system là hướng tiếp theo. Điều này tiếp nối Dev Mode và mục tiêu nối các bước sản phẩm trong §1.

**Dự đoán 2** *(loại: segment)*
- **Dự đoán:** Developer, PM và người không chuyên thiết kế sẽ tham gia nhiều hơn vào workspace Figma, dù designer vẫn giữ vai trò trung tâm.
- **Lập luận:** Dev Mode giải quyết handoff, FigJam phục vụ ideation và Slides mở rộng sang thuyết trình. Ba mốc cho thấy chiến lược thu hút các vai trò ở hai đầu quy trình, không chỉ người vẽ giao diện (§1–§2).

**Dự đoán 3** *(loại: mô hình kiếm tiền)*
- **Dự đoán:** Figma có thể gắn quyền truy cập AI sâu hơn với các gói trả phí hoặc giới hạn theo mức sử dụng.
- **Lập luận:** Make mở rộng sản phẩm sang tác vụ AI tốn tài nguyên; đồng thời các tính năng cho developer và nhóm lớn tạo thêm giá trị ngoài thiết kế cơ bản. Đây là suy luận về cách thu phí có thể tiến hóa, không phải thông báo giá hay thay đổi gói đã được xác nhận.

**§4. AI Log**

| Việc | AI làm hay bạn làm? | Bạn kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| Tìm và sắp xếp timeline | AI tổng hợp; người học chọn Figma. | Đối chiếu mốc và mô tả với bài công bố chính thức của Figma được liên kết ở §1. |
| Phân tích user, JTBD và switching forces | AI đề xuất khung và diễn đạt. | Tách nội dung Figma công bố khỏi phần suy luận; không trình bày lực chuyển đổi như số liệu thực tế. |
| Đưa ra dự đoán 6–12 tháng | AI soạn ba giả thuyết từ các mốc §1–§2. | Ghi rõ dự đoán là suy luận, không phải roadmap đã xác nhận; đối chiếu từng giả thuyết với các xu hướng sản phẩm đã nêu. |
