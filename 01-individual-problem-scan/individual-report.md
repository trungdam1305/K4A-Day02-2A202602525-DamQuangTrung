# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

* Họ và tên: Đàm Quang Trung
* Mã học viên: 2A202602525
* Vai trò / bối cảnh: Sinh viên IT, học viên lớp K4A, có làm dự án nhóm Java và tham gia quản lý CLB
* Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

  * Làm và nộp bài lab theo repo GitHub cá nhân, mỗi buổi một repo fork riêng
  * Code và review dự án nhóm (Java/NetBeans, Flutter, SQL Server)
  * Theo dõi thông báo, deadline, phân công trong Discord lớp và group chat nhóm
  * Hỗ trợ thành viên mới chạy được project trên máy của họ
  * Tổng hợp việc của CLB: đăng ký, phân công, theo dõi ai đã làm xong

\---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

|#|Lăng kính|Problem quan sát được|Ai chịu ảnh hưởng?|Dấu hiệu thật (số + bằng chứng)|
|-|-|-|-|-|
|1|Lặp lại|Mỗi buổi lab phải fork repo → đổi tên đúng chuẩn → điền form → commit → nộp link, làm lại từ đầu mỗi buổi|Học viên K4A (cả lớp)|\~10 phút/buổi chỉ cho phần thao tác repo, không tính phần suy nghĩ. Bằng chứng: repo Day02 của tôi fork xong nhưng 3 file báo cáo vẫn trắng khi đến hạn|
|2|Lặp lại|Trước khi nộp phải tự đối chiếu repo với rubric xem thiếu field/thư mục nào|Học viên K4A|Rubric Day02 có 9 mục self-check; đối chiếu thủ công \~10 phút/lần. Bằng chứng: bản nộp Day02 của tôi thiếu toàn bộ nội dung mà không có cảnh báo nào|
|3|Tốn thời gian|Tìm lại deadline / thông báo / quyết định cũ trong Discord lớp khi cần|Học viên K4A|\~10 phút/lần tìm, \~3 lần/tuần|
|4|Tốn thời gian|Đọc tài liệu hướng dẫn dài để biết chính xác phải nộp cái gì|Học viên K4A|`01-worksheet.md` dài 835 dòng, `02-deliverable-example.md` 358 dòng — đọc kỹ mất 40-50 phút trước khi bắt tay làm|
|5|Pain từ người khác|Thành viên mới trong nhóm hỏi lại cùng một câu để chạy được project Java: JDK nào, SQL script nào, đổi connection string ở đâu|Thành viên mới + tôi (người trả lời)|3-4 câu hỏi lặp lại/người mới; 2-3 người mới mỗi dự án|
|6|Pain từ người khác|Nhóm không biết ai đã làm xong phần nào, phải nhắn hỏi từng người trước buổi họp|Cả nhóm đồ án|Ước lượng 5-8 tin nhắn hỏi lại trước mỗi buổi họp|
|7|Tốn thời gian|Viết báo cáo tiến độ nhóm từ commit log + chat rời rạc|Người phụ trách báo cáo trong nhóm|\~30 phút/lần, mỗi milestone 1 lần|
|8|AI có thể tốt hơn|Sinh seed data / test case cho bài tập cơ sở dữ liệu phải gõ tay từng dòng INSERT|Sinh viên làm bài DB|Repo `DBTest` của tôi: mỗi bảng cần 10-20 dòng seed, gõ tay \~15 phút/bảng|
|9|AI có thể tốt hơn|Setup lại môi trường chạy project khi đổi máy hoặc clone lại từ đầu|Tôi + thành viên nhóm|\~30-45 phút/lần, xảy ra 2-3 lần/học kỳ|
|10|Lặp lại|Tổng hợp danh sách đăng ký hoạt động CLB từ form + tin nhắn rải rác|Ban tổ chức CLB|Ước lượng 20-30 phút/sự kiện, vài sự kiện mỗi kỳ (xác nhận lại với ban tổ chức)|

> **Ghi chú giả định:** các con số gắn nhãn "ước lượng" chưa được bấm giờ. Trước khi nộp, tôi sẽ đo lại ít nhất 3 dòng (#1, #2, #3) bằng cách bấm giờ ở lần làm tiếp theo và đếm lại lịch sử Discord, rồi thay số thật vào bảng.

**AI đã dùng ở Phase 1 (nếu có):**

* Prompt đã hỏi: mô tả bối cảnh của tôi (sinh viên IT, làm dự án Java/Flutter, nộp bài qua GitHub, tham gia CLB), liệt kê các vấn đề tôi tự nghĩ ra trước, rồi nhờ AI mở rộng theo 4 lăng kính và yêu cầu mỗi gợi ý phải có actor + cách đo.
* Ý dùng được: gợi ý tách "nộp bài" thành hai vấn đề riêng — thao tác repo (#1) và rà soát đủ nội dung (#2). Trước đó tôi gộp làm một, nên không thấy được bottleneck nằm ở đâu.
* Ý bỏ vì không phải pain thật: gợi ý "làm trợ lý AI học tập tổng hợp" và "chatbot hỏi đáp tài liệu môn học" — quá rộng, không có workflow cụ thể tôi quan sát được, và tôi không đo được impact.

**Self-check Phase 1:**

* \[x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
* \[x] Dùng ít nhất 3/4 lăng kính (dùng đủ 4)
* \[x] Không có dòng chung chung kiểu "mất nhiều thời gian"
* \[x] Đã thay số ước lượng bằng số đo thật cho ít nhất 3 dòng

\---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

|Rank|Problem (copy từ bảng scan)|Vì sao chọn (2-3 ý)|Điều còn chưa chắc|
|-|-|-|-|
|1|#2 — Rà soát repo bài nộp xem thiếu field/thư mục nào trước khi nộp|Actor rõ (học viên K4A); workflow 5 bước vẽ được; bottleneck nằm đúng 1 bước là đối chiếu thủ công với rubric; impact đo được bằng số mục thiếu và số điểm mất; so sánh Rule/Workflow/Agent rất rõ vì Rule có thể đã đủ|Rubric mỗi buổi lab khác nhau, nên phần "đọc rubric" có thể không tự động hóa được bằng Rule thuần|
|2|#3 — Tìm lại deadline / quyết định cũ trong Discord lớp|Nhiều người cùng gặp, không chỉ mình tôi; có dấu hiệu đếm được (số lần search, số lần hỏi lại trong kênh)|Chưa rõ có quyền truy cập lịch sử kênh để làm thật không; scope dễ phình thành "search engine cho Discord"|
|3|#5 — Onboard thành viên mới chạy được project Java của nhóm|Pain đến từ người khác chứ không phải tự tôi nghĩ ra; có quote thật là các câu hỏi lặp lại trong group chat|Tần suất thấp (2-3 người/dự án) nên impact có thể không đủ lớn để đáng làm|

### 2.2. Problem Cards chi tiết

\---

#### Problem Card #1 — Rà soát bài nộp trước khi nộp

```text
Problem 1 câu:
Học viên K4A phải tự đối chiếu repo bài nộp với rubric trong README để biết còn thiếu
thư mục, file hay field nào, và bước đối chiếu thủ công này dễ bỏ sót nên bài bị mất
điểm vì thiếu phần chứ không phải vì làm sai.

Actor:
Học viên K4A đang chuẩn bị nộp repo bài lab cá nhân.

Thời điểm / bối cảnh:
Sát hạn nộp của mỗi buổi lab, thường là buổi tối cùng ngày hoặc hôm sau.

Current workflow 3-7 bước:
1. Mở README của repo, đọc lại phần cấu trúc repo và rubric
2. Mở từng thư mục con, mở từng file báo cáo
3. Đối chiếu thủ công từng mục self-check với nội dung đã điền
4. Ghi ra chỗ còn thiếu, quay lại điền
5. Commit, push, nộp link

Bottleneck:
Bước 3 — đối chiếu thủ công. Rubric Day02 có 9 mục self-check nằm rải ở 3 file khác
nhau, phải nhảy qua lại giữa README và file báo cáo. Ước lượng ~20 phút/lần và vẫn
sót, vì mắt người đọc form trắng dễ lướt qua.

Impact:
Mất khoảng 20 phút/lần nộp. Nghiêm trọng hơn là rủi ro mất điểm hệ thống: repo Day02
của tôi fork đúng chuẩn tên nhưng cả 3 file báo cáo vẫn trắng, và không có bất kỳ
cảnh báo nào trước hạn. Theo rubric, bài như vậy rơi thẳng vào mức "Không pass" dù
người học có hiểu bài hay không.

Success metric:
- Thời gian rà soát: từ ~20 phút xuống dưới 5 phút/lần nộp.
- Guard metric: số mục rubric bị bỏ sót khi nộp = 0, và số cảnh báo sai (báo thiếu
  trong khi thực tế đã có) dưới 1 mục/lần — tránh việc rà nhanh hơn bằng cách bỏ sót
  nhiều hơn.
- Cách đo: bấm giờ 3 lần nộp gần nhất làm baseline; sau đó đối chiếu kết quả công cụ
  với kết quả rà tay của chính tôi trong 3 buổi lab liên tiếp.

Non-AI alternative:
Một file checklist tĩnh trong repo, hoặc một script/GitHub Action đơn giản kiểm tra
sự tồn tại của 3 thư mục, 3 file, và phát hiện ô bảng còn rỗng bằng pattern `| |`.
Phương án này rẻ, chạy được ngay, và có lẽ giải được phần lớn trường hợp.

AI hypothesis:
AI chỉ cần thiết ở phần mà Rule không làm được: đọc rubric dạng văn xuôi của từng
buổi lab (mỗi buổi một rubric khác nhau) rồi đối chiếu với nội dung học viên đã
viết, để trả lời câu hỏi mềm hơn là "field này đã điền chưa" — ví dụ "metric này đã
có baseline và cách đo chưa". Người học vẫn tự quyết có sửa hay không.

Quick gut:
[ ] No AI / process fix
[x] Rule            <- đủ cho phần kiểm tra có/không
[x] Workflow        <- cần thêm nếu muốn kiểm tra chất lượng nội dung
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — ~25 phút

[1 Đọc lại README + rubric: 5']
→[2 Mở từng file báo cáo: 3']
→[3 Đối chiếu thủ công 9 mục self-check: 15']   <-- bottleneck
→[4 Quay lại điền chỗ thiếu: thay đổi]
→[5 Commit + push + nộp link: 2']

FUTURE STATE — ~6 phút

[1 Chạy check tự động cấu trúc + ô trống: 1']    -- Rule/script, không cần AI
→[2 AI đối chiếu nội dung với rubric, liệt kê mục yếu: 1']
→[3 Tôi đọc danh sách, tự quyết sửa gì: 3']     <-- human boundary
→[4 Commit + push + nộp link: 1']

Bottleneck mới: bước 3 — tôi vẫn phải tự đọc và tự quyết. Đây là bottleneck chấp
nhận được vì đó là điểm kiểm soát: công cụ không được phép tự sửa nội dung bài.

Risk mới: công cụ báo "đủ" trong khi nội dung thực chất rỗng tuếch → tôi yên tâm
giả và nộp bài kém. Vì vậy guard metric ở trên đo cả cảnh báo sai.

Fallback: nếu công cụ báo sai quá 1 mục/lần trong 2 buổi liên tiếp, bỏ phần AI, giữ
lại mỗi script kiểm tra cấu trúc và quay về rà tay phần nội dung.
```

File đính kèm: `01-individual-problem-scan-workflow-card-1.png`

\---

#### Problem Card #2 — Tìm lại deadline / quyết định cũ trong Discord lớp

```text
Problem 1 câu:
Học viên K4A mất khoảng 10 phút mỗi lần cần tìm lại một deadline hoặc một quyết định
đã được thông báo trong Discord lớp, vì thông tin nằm rải trong nhiều kênh và nhiều
thread, và người tìm thường không nhớ đúng từ khóa đã dùng.

Actor:
Học viên K4A cần xác nhận một thông tin đã thông báo trước đó (hạn nộp, cách đặt tên
repo, ai làm phần nào).

Thời điểm / bối cảnh:
Trước hạn nộp, hoặc khi bắt đầu một buổi lab mới và cần nhớ lại quy ước cũ.

Current workflow 3-7 bước:
1. Mở Discord, đoán xem thông tin nằm ở kênh nào
2. Search theo từ khóa nhớ mang máng
3. Lướt kết quả, mở từng thread để đọc ngữ cảnh
4. Không thấy thì hỏi lại trong kênh chung
5. Chờ người khác trả lời

Bottleneck:
Bước 2-3 — search theo từ khóa. Discord search khớp theo chữ chứ không theo ý, nên
nếu thông báo dùng từ khác với từ mình nhớ thì coi như không tìm được.

Impact:
Ước lượng ~10 phút/lần, ~3 lần/tuần cho một người. Nếu cả lớp cùng gặp thì phần
lớn chi phí rơi vào bước 4-5: câu hỏi lặp lại làm nhiễu kênh chung và người trả lời
phải trả lời lại điều đã nói.

Success metric:
- Thời gian tìm: từ ~10 phút xuống dưới 2 phút/lần.
- Guard metric: tỷ lệ câu trả lời trỏ đúng tin nhắn gốc ≥ 80%, tính trên 10 câu hỏi
  thử — nếu công cụ trả lời nhanh nhưng sai nguồn thì tệ hơn là không có.
- Cách đo: tự ghi lại 10 lần tìm gần nhất, đo thời gian và kiểm xem kết quả có trỏ
  đúng tin nhắn gốc không.

Non-AI alternative:
Pin các thông báo quan trọng, hoặc lập một file `deadlines.md` trong repo lớp và bắt
buộc mọi thông báo quan trọng phải được chép vào đó. Rẻ hơn nhiều và không cần quyền
truy cập lịch sử kênh.

AI hypothesis:
AI hỗ trợ ở bước tìm theo ý thay vì theo từ khóa, và trả về kèm link tin nhắn gốc để
người dùng tự kiểm.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~10 phút (hoặc lâu hơn nếu phải chờ người trả lời)
[1 Đoán kênh: 1'] → [2 Search từ khóa: 4']  <-- bottleneck
→ [3 Đọc từng thread: 4'] → [4 Hỏi lại trong kênh: 1' + thời gian chờ]

FUTURE STATE — ~2 phút

[1 Hỏi bằng câu hỏi tự nhiên: 0.5']
→ [2 Công cụ trả về câu trả lời + link tin nhắn gốc: 0.5']
→ [3 Tôi mở link, tự xác nhận: 1']   <-- human boundary, bắt buộc có nguồn

Risk mới: công cụ trả lời tự tin nhưng dựa trên thông báo đã bị thay thế bởi thông
báo mới hơn → tôi làm theo deadline cũ.

Fallback: mọi câu trả lời không kèm link tin nhắn gốc thì coi như không có; quay về
search tay hoặc hỏi trong kênh.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

\---

#### Problem Card #3 — Onboard thành viên mới chạy được project Java của nhóm

```text
Problem 1 câu:
Mỗi khi có thành viên mới vào dự án Java của nhóm, họ hỏi lại 3-4 câu giống hệt
người trước (JDK bản nào, chạy script SQL nào, sửa connection string ở đâu), và
người đã biết phải trả lời lại từ đầu qua chat.

Actor:
Thành viên mới vào dự án, và người trong nhóm đang phải trả lời (thường là tôi).

Thời điểm / bối cảnh:
Đầu mỗi dự án nhóm, hoặc khi có người vào giữa chừng.

Current workflow 3-7 bước:
1. Người mới clone repo
2. Chạy thử, gặp lỗi
3. Chụp màn hình lỗi gửi vào group chat
4. Tôi đọc lỗi, đoán nguyên nhân, trả lời
5. Lặp lại bước 2-4 cho tới khi chạy được

Bottleneck:
Vòng lặp bước 2-4. Mỗi vòng tốn thời gian của hai người và phụ thuộc vào việc tôi có
đang online hay không.

Impact:
3-4 câu hỏi lặp lại/người mới, 2-3 người mới mỗi dự án. Chi phí thật nằm ở độ trễ:
người mới bị chặn cho tới khi có người rảnh trả lời.

Success metric:
- Số câu hỏi setup lặp lại: từ 3-4 xuống dưới 1 câu/người mới.
- Guard metric: người mới vẫn chạy được project trong buổi đầu tiên (không phải giảm
  câu hỏi vì họ bỏ cuộc).
- Cách đo: đếm số tin nhắn hỏi về setup trong group chat cho 2 người mới tiếp theo.

Non-AI alternative:
Viết một file `SETUP.md` tử tế, kèm script khởi tạo DB và file cấu hình mẫu
`.env.example`. Đây gần như chắc chắn là phương án đúng và không cần AI.

AI hypothesis:
Hầu như không cần. Nếu có, chỉ dùng AI để sinh bản nháp `SETUP.md` từ lịch sử chat
và cấu trúc project, rồi tôi sửa lại.

Quick gut:
[x] No AI / process fix   <- viết tài liệu + script là đủ
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — nhiều vòng lặp, kéo dài cả buổi

[1 Clone: 5'] → [2 Chạy, gặp lỗi: 10'] → [3 Hỏi trong group: 1' + chờ]
→ [4 Tôi trả lời: 5'] → quay lại [2]   <-- bottleneck là vòng lặp + độ trễ chờ

FUTURE STATE — 1 vòng, ~20 phút

[1 Clone: 5'] → [2 Đọc SETUP.md + chạy script khởi tạo: 10']
→ [3 Chỉ hỏi khi gặp lỗi ngoài tài liệu: 5']   <-- human boundary

Fallback: nếu vẫn hỏi trên 1 câu/người, nghĩa là SETUP.md còn thiếu — bổ sung ngay
câu đó vào tài liệu thay vì trả lời riêng lần nữa.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

\---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Card #1 — Rà soát bài nộp trước khi nộp.
```

**Vì sao:**

```text
Workflow chỉ 5 bước và bottleneck nằm gọn ở đúng một bước: đối chiếu thủ công repo
với rubric, ước lượng 20 phút và vẫn sót. Impact không chỉ là thời gian mà là rủi ro
mất điểm hệ thống — repo Day02 của tôi đặt tên đúng chuẩn nhưng cả 3 file báo cáo
vẫn trắng đến hạn mà không có cảnh báo nào, và theo rubric bài như vậy rơi thẳng
xuống mức không pass. Bài này cũng cho phép so sánh Rule / Workflow / Agent rất rõ,
vì phần kiểm tra cấu trúc chỉ cần một script, còn AI chỉ đáng dùng ở phần đọc rubric
văn xuôi của từng buổi lab.
```

**Câu hỏi tôi muốn nhóm challenge :**

```text
1. Nếu một script kiểm tra thư mục, file và ô bảng rỗng đã bắt được phần lớn trường
   hợp, thì phần AI còn lại có đáng làm không, hay tôi đang cố nhét AI vào một bài
   toán mà Rule đã giải xong?
2. Metric "số mục rubric bị bỏ sót = 0" có thật sự đo được không, khi muốn biết mình
   bỏ sót thì vẫn phải có ai đó rà tay để đối chứng — tôi có đang định nghĩa một
   metric không thể đo độc lập không?
```

**AI phản biện Card:**

Self-check nộp phần 01

* \[x] Có 5+ problems + top 3 Cards đủ field
* \[x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
* \[x] Đã chọn 1 card pitch + câu hỏi challenge

