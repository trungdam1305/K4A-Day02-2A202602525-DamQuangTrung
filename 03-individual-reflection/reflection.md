# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đàm Quang Trung
- Mã học viên: 2A202602525
- Nhóm: Nhóm 5B
- Candidate problem nhóm chọn: Người dùng mất quá nhiều thời gian để chọn món ăn phù hợp với khẩu vị, ngân sách, vị trí và thời gian hiện tại.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ bối cảnh sinh viên IT: nộp bài lab, tìm deadline Discord, onboard thành viên mới, seed data DB, tổng hợp CLB. Dùng đủ 4 lăng kính. | Đóng góp 3 candidate vào bảng chung (rà soát repo, tìm deadline Discord, onboard project Java). Candidate "onboard project Java" vào shortlist nhóm. |
| Pitch Problem Card | Pitch Card #1 — Rà soát bài nộp trước khi nộp. Trình bày workflow 5 bước, chỉ bottleneck ở bước đối chiếu thủ công, và dùng chính repo Day02 của mình làm bằng chứng (3 file trắng khi đến hạn). | Nhóm thấy bài toán rõ nhưng scope hẹp (chỉ áp dụng cho lớp K4A), nên không chọn làm candidate chung. Điều này đúng — tôi đồng ý. |
| Challenge bài của bạn khác | Challenge bài "chọn đồ ăn" của Vinh: hỏi "bộ lọc giá + khoảng cách trên GrabFood đã có sẵn, phần AI thêm vào có khác gì so với lọc thủ công?". | Nhóm bổ sung dòng Non-AI alternative trong Problem Card và ghi rõ Rule lọc cứng là fallback bắt buộc, AI chỉ thêm giá trị ở bước xếp hạng theo sở thích. |
| Gom trùng / cluster | Đề xuất gom "chọn đồ ăn", "tìm tài liệu", "tìm deadline Discord" vào cluster A (tìm kiếm + lọc quá nhiều thông tin). | Cluster A trở thành cụm có nhiều candidate nhất và giúp nhóm thấy pattern chung là decision fatigue. |
| Chọn candidate problem | Là facilitator: điều phối bảng score 7 tiêu chí, đảm bảo mỗi người chấm và nói rõ vì sao cho 5 hay cho 3. | Nhóm đồng thuận chọn "chọn đồ ăn" với tổng 32/35, cao nhất. Không có bất đồng lớn ở bước này. |
| Validation / research | Tham gia phỏng vấn nội bộ (1 trong 3 người được hỏi). Tự ghi lại thời gian chọn món 3 bữa trong tuần để đo baseline. | Cung cấp quote "Có hôm mất hơn 15 phút chỉ để chọn bữa tối". Số liệu baseline của tôi: 12 phút, 18 phút, 9 phút → median 12 phút. |
| Workflow nhóm | Review bản workflow của Vinh và Minh, góp ý tách bước "tìm món" và bước "lọc món" thành hai bước riêng vì bottleneck nằm ở phần sau chứ không phải phần tìm. | Workflow cuối có 5 bước thay vì 4, bottleneck được gán đúng vào bước 4 (so sánh và quyết định). |
| Problem Statement | Góp ý field Boundary: thêm "không tự suy đoán dị ứng" vào danh sách không làm, vì validation có 1 thành viên lo ngại về an toàn thực phẩm. | PS v1 có dòng boundary rõ hơn: "không tự đặt/thanh toán, không tự suy đoán dị ứng". |
| Rule / Workflow / Agent | Trả lời 5 câu hỏi chốt cùng Minh. Đặc biệt câu 5: đề xuất hạ từ Workflow về Rule nếu AI không cải thiện metric sau 20 lượt pilot. | Nhóm ghi rõ exit criteria: dừng AI khi tỷ lệ từ chối > 50% hoặc median thời gian không giảm sau 20 lượt. |
| Decision | Là người chốt cuối: tổng hợp 6 câu hỏi final decision, đọc lại từng câu trả lời trước nhóm, và xác nhận Go ở mức pilot nhỏ. | Decision = Go với điều kiện pilot 20 lượt, không kết nối thanh toán, có rollback rõ. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần Boundary trong PS v1 (dòng "không tự suy đoán dị ứng") và exit criteria trong Final Decision (dừng AI khi tỷ lệ từ chối > 50% hoặc không giảm median thời gian sau 20 lượt). Hai chỗ này tôi đề xuất và nhóm giữ nguyên vào bản cuối.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mô tả bối cảnh của tôi, liệt kê problems tôi tự nghĩ, nhờ AI mở rộng theo 4 lăng kính | Gợi ý tách "nộp bài" thành 2 vấn đề riêng (thao tác repo vs rà soát nội dung) — trước đó tôi gộp làm một | Gợi ý "trợ lý AI học tập tổng hợp" và "chatbot hỏi đáp tài liệu" — quá rộng, không có workflow cụ thể tôi quan sát được | Bỏ 2 ý quá rộng, giữ ý tách problem, tự bổ sung bằng chứng đếm được (số dòng bảng rỗng, số khối text trống) |
| Problem Card | Nhờ AI phản biện Card #1 theo vai skeptical PM | AI chỉ ra metric "sót = 0" khó đo vì cần ground truth, và actor quá rộng | AI gợi ý thay bằng metric tương đối nhưng không nói cụ thể đo thế nào | Tôi sửa thành: chạy song song rà tay + công cụ trong 3 buổi, so kết quả; pilot trên 1 người trước |
| Workflow | Nhờ AI vẽ draft workflow trước/sau cho 3 card | AI tạo được cấu trúc 5 bước với nhãn Rule/AI/Human rõ ràng | AI gộp bước "kiểm tra cấu trúc" và "kiểm tra nội dung" thành một, trong khi hai bước này cần tool khác nhau (script vs LLM) | Tách thành 2 bước riêng: bước 1 Rule/script, bước 2 AI |
| Research | Không dùng | Tự tìm Google Maps Explore và GrabFood vì đây là app tôi dùng hằng ngày, không cần AI search hộ | — | — |
| Problem Statement | Không dùng trực tiếp; Vinh và Minh viết draft, tôi review | — | — | Tôi góp ý bằng nhận định: thêm "không tự suy đoán dị ứng" vào boundary, vì đây là rủi ro an toàn mà draft chưa đề cập |
| Rule / Workflow / Agent | Không dùng | Nhóm tự thảo luận 5 câu hỏi chốt, mỗi người trả lời 1 câu rồi cả nhóm review | — | — |
| Decision | Không dùng | Tôi tổng hợp và đọc lại 6 câu hỏi final decision trước nhóm, chốt bằng đồng thuận | — | — |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 của các bạn khác, tôi nhận ra problem của mình (rà soát repo, tìm
deadline Discord) có scope quá hẹp — chỉ áp dụng trong lớp K4A. Trong khi đó bài
"chọn đồ ăn" của Vinh ai cũng gặp hằng ngày và bottleneck rõ hơn nhiều. Điều này
dạy tôi rằng problem tốt không phải problem mình thấy đau nhất, mà là problem có
actor đủ rộng và workflow đủ rõ để nhóm cùng làm.

Nhóm có một lúc bị solution-first: khi mới chọn xong "chọn đồ ăn", Cường đề xuất
luôn "làm app gợi ý món bằng GPT". Tôi với vai trò facilitator phải kéo lại: chưa
có workflow thì chưa biết AI can thiệp ở đâu. Sau khi vẽ workflow 5 bước và thấy
bottleneck nằm ở bước so sánh, nhóm mới đồng ý rằng AI chỉ cần ở bước xếp hạng
3 món, còn lọc cứng thì Rule đủ. Nếu không có bước vẽ workflow trước, chắc nhóm
đã nhảy thẳng vào Agent.

Điều khó nhất khi viết Problem Statement là boundary. Metric thì nhóm thống nhất
nhanh (thời gian chọn món), nhưng boundary phải tranh luận: AI có được tự đặt món
không? Có được suy đoán dị ứng không? Tôi đề xuất "không tự suy đoán dị ứng" vì
hậu quả sai là nghiêm trọng, và nhóm đồng ý ngay. Nhưng dòng "không tự đặt món"
thì Minh ban đầu muốn để AI đặt luôn cho tiện — phải mất thêm 5 phút thảo luận
về rủi ro đặt sai mới chốt được.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần baseline. Hiện tại số 23 phút
là ước lượng trung bình của cả nhóm, chưa ai bấm giờ nghiêm túc ngoài tôi (tôi
đo được median 12 phút cho 3 bữa). Con số 23 phút có thể bị thổi phồng để làm
metric trông ấn tượng hơn, và nếu baseline thật chỉ là 12 phút thì mục tiêu
"dưới 8 phút" sẽ khó hơn nhiều so với lúc nhóm tưởng.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
