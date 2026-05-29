# 02 — Group Problem Statement

## Thành viên

```text
Thành viên 1: 2A202600927 - Nguyễn Quang Huy
Thành viên 2: 2A202600743 - Bùi Ngọc Khánh
Thành viên 3: 2A202600670 - Nguyễn Xuân Hiệp
```

# Phase 3 — Group Convergence: từ 9–12 candidates về 1

## Mục tiêu

Nhóm có 3 thành viên, mỗi thành viên trình bày top 3 problems cá nhân. Tổng cộng nhóm có 9 candidate problems.  
Ở phase này, nhóm chưa viết Problem Statement hoàn chỉnh ngay, mà đi theo quy trình:

```text
Trình bày top 3
→ gom trùng / cluster
→ shortlist
→ chấm nhanh + đồng thuận chọn 1 candidate problem
```

---

## Bước 3.1 — Trình bày top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Thành viên 1 | Bệnh nhân có nhu cầu đi khám nhưng không biết nên khám khoa nào, cần chuẩn bị gì và quy trình thăm khám diễn ra như thế nào. | Bệnh nhân, người nhà, nhân viên tiếp nhận/tư vấn bệnh viện | Bước định hướng ban đầu trước khi đi khám: chọn khoa, chuẩn bị giấy tờ, hiểu quy trình và đặt lịch. | Actor rõ, workflow rõ, impact cao; tuy nhiên rủi ro y tế lớn nên cần boundary rất chặt. |
| 2 | Thành viên 1 | Nhân viên chăm sóc khách hàng phải trả lời nhiều câu hỏi lặp lại nhưng vẫn cần tra cứu thông tin cá nhân hóa trong cơ sở dữ liệu. | Nhân viên chăm sóc khách hàng, khách hàng, bộ phận vận hành | Tra cứu và tổng hợp dữ liệu khách hàng/đơn hàng/gói dịch vụ từ nhiều hệ thống trước khi trả lời. | Workflow rõ, metric dễ đo; nhưng nhóm chưa chắc có dữ liệu vận hành thực tế để validate. |
| 3 | Thành viên 1 | Học viên khó tự theo dõi lịch trình học tập vì lịch học, deadline, tài liệu, link nộp bài và thông báo thay đổi nằm rải rác ở nhiều kênh. | Học viên, trợ giảng, lớp trưởng | Tổng hợp thông tin từ nhiều kênh thành lịch trình cá nhân rõ ràng. | Gần bối cảnh lớp học, dễ validate; nhưng nếu chỉ nhắc deadline thì có thể rule/calendar đã đủ. |
| 4 | Thành viên 2 | Mỗi tuần mất 4–6 tiếng để đọc và tóm tắt 2–3 research papers chuẩn bị seminar. | Sinh viên AI năm cuối / sinh viên làm seminar hoặc literature review | Đọc full paper và viết tóm tắt có cấu trúc. | Pain lặp lại hàng tuần, workflow rõ, metric thời gian dễ đo, phù hợp đào sâu trong lab. |
| 5 | Thành viên 2 | Tìm kiếm và lọc paper liên quan trên arXiv/Google Scholar rất tốn thời gian và kém hiệu quả. | Thành viên nhóm dự án AI / sinh viên nghiên cứu | Đọc và lọc nhiều abstract không liên quan trước khi tìm được paper phù hợp. | Xảy ra ở giai đoạn đầu nghiên cứu, dễ validate với sinh viên AI. |
| 6 | Thành viên 2 | Tổng hợp literature review từ nhiều papers như so sánh methods, results và gaps còn rất thủ công. | Người viết literature review / báo cáo / milestone nghiên cứu | So sánh chéo nhiều paper và rút insight tổng hợp. | Impact lớn khi viết báo cáo, nhưng scope có thể rộng nếu ôm toàn bộ literature review. |
| 7 | Thành viên 3 | Viết báo cáo tiến độ nghiên cứu hàng tuần. | Sinh viên làm nghiên cứu / nhóm nghiên cứu | Chuyển tiến độ rời rạc thành báo cáo rõ ràng, có lập luận. | Có pain thật, nhưng khá gần với ví dụ weekly report nên nhóm cần tránh chọn nếu không có khác biệt rõ. |
| 8 | Thành viên 3 | Đọc tài liệu dài tiếng Anh. | Sinh viên, người học AI, người làm nghiên cứu | Đọc hiểu tài liệu dài và rút ý chính. | Tốn thời gian rõ, nhiều sinh viên gặp; có thể nhập vào cụm research paper. |
| 9 | Thành viên 3 | Đọc feedback giảng viên để sửa bài. | Sinh viên nhận feedback từ giảng viên/hướng dẫn | Diễn giải feedback và chuyển thành action cụ thể. | Có workflow vẽ được, nhưng improvement khó đo vì feedback rất khác nhau. |

---

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Research / Academic Reading & Synthesis | #4 đọc và tóm tắt research papers; #5 tìm kiếm/lọc paper; #6 tổng hợp literature review; #8 đọc tài liệu dài tiếng Anh; một phần #7 viết báo cáo tiến độ nghiên cứu. | Sinh viên/người nghiên cứu phải xử lý tài liệu học thuật dài, tìm paper liên quan, đọc hiểu, rút ý chính, so sánh và chuyển thành output dùng được cho seminar/báo cáo. | Đây là cụm có nhiều candidate nhất, nhiều thành viên hiểu domain và có trải nghiệm thật. |
| B — Healthcare Navigation | #1 bệnh nhân không biết khám khoa nào, cần chuẩn bị gì và quy trình đi khám ra sao. | Người bệnh cần được định hướng trước khi đi khám. | Impact cao nhưng rủi ro y tế lớn, cần nguồn dữ liệu bệnh viện và boundary rất rõ. |
| C — Customer Support Operation | #2 CSKH trả lời câu hỏi lặp lại nhưng cần tra cứu database cá nhân hóa. | Nhân viên phải vừa hiểu câu hỏi, vừa tra cứu thông tin khách hàng trước khi trả lời. | Workflow và metric tốt, nhưng nhóm chưa chắc có data hoặc hiểu rõ hệ thống vận hành thật. |
| D — Student Planning / Scheduling | #3 học viên khó theo dõi lịch học, deadline, tài liệu và link nộp bài. | Thông tin học tập bị phân tán, học viên phải tự tổng hợp lịch trình cá nhân. | Gần bối cảnh lớp học nhưng mức cần AI chưa mạnh nếu chỉ là nhắc deadline. |
| E — Feedback Interpretation | #9 đọc feedback giảng viên để sửa bài. | Người học phải chuyển feedback thành việc cần sửa. | Có pain thật nhưng metric và workflow khó chuẩn hóa hơn trong phạm vi lab. |

---

## Bước 3.3 — Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Sinh viên/người nghiên cứu mất nhiều thời gian để tìm, đọc, tóm tắt và tổng hợp research papers phục vụ seminar hoặc literature review. | Có sự hội tụ mạnh từ nhiều candidate của thành viên 2 và 3. Actor rõ, workflow rõ, nhóm hiểu domain, impact có thể đo bằng thời gian đọc/tóm tắt mỗi paper và số paper xử lý được. | Cần thu hẹp scope: hỗ trợ tóm tắt từng paper, lọc paper, hay tổng hợp literature review nhiều paper? Cần xác định summary “đủ tốt” gồm những phần nào. |
| Bệnh nhân có nhu cầu đi khám nhưng không biết nên khám khoa nào, cần chuẩn bị gì và quy trình khám diễn ra như thế nào. | Actor rõ, workflow rõ, impact cao, có thể vẽ before/after workflow. | Rủi ro y tế cao. Nếu làm không rõ boundary, hệ thống dễ bị hiểu nhầm là công cụ chẩn đoán. Nhóm cũng cần dữ liệu bệnh viện/phòng khám để validate. |
| Nhân viên chăm sóc khách hàng phải trả lời nhiều câu hỏi lặp lại nhưng vẫn cần tra cứu thông tin cá nhân hóa trong cơ sở dữ liệu. | Workflow vận hành rõ, bottleneck cụ thể, metric dễ đo như thời gian phản hồi/ticket/ngày/tỷ lệ trả lời sai. | Nhóm chưa chắc có data thật, chưa rõ nhân viên phải mở bao nhiêu hệ thống và thao tác nào được phép tự động hóa. |
| Học viên khó tự theo dõi lịch học, deadline, tài liệu và link nộp bài từ nhiều kênh. | Gần bối cảnh hiện tại, dễ validate với bạn học trong lớp. | Nếu chỉ nhắc deadline thì calendar/rule có thể đủ. Cần làm rõ AI giúp tổng hợp và cá nhân hóa lịch trình chứ không chỉ nhắc việc. |

---

## Bước 3.4 — Score để đồng thuận

Thang điểm: 1 = yếu, 5 = rất tốt.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Đọc, tóm tắt và tổng hợp research papers cho seminar/literature review | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| Học viên theo dõi lịch học, deadline và tài liệu từ nhiều kênh | 5 | 4 | 4 | 4 | 5 | 4 | 5 | 31 |
| CSKH trả lời câu hỏi lặp lại nhưng cần tra cứu dữ liệu khách hàng | 5 | 5 | 4 | 5 | 3 | 5 | 3 | 30 |
| Bệnh nhân định hướng khoa khám và quy trình trước khi đi khám | 5 | 5 | 4 | 4 | 3 | 5 | 3 | 29 |

### Candidate nhóm chọn

```text
Sinh viên/người nghiên cứu mất nhiều thời gian để tìm, đọc, tóm tắt và tổng hợp research papers phục vụ seminar hoặc literature review.
```

### Vì sao chọn

```text
Nhóm chọn candidate này vì có sự hội tụ rõ giữa các thành viên. Nhiều candidate khác nhau đều xoay quanh cùng một cụm vấn đề: đọc tài liệu dài tiếng Anh, tìm/lọc paper liên quan, tóm tắt paper và tổng hợp literature review.

Problem này có actor rõ là sinh viên AI, sinh viên năm cuối, thành viên nhóm nghiên cứu hoặc người chuẩn bị seminar. Workflow cũng có thể mô tả thành các bước cụ thể: xác định chủ đề → tìm paper → lọc paper liên quan → đọc paper → ghi chú contribution/method/result/limitation → so sánh nhiều paper → tạo output cho seminar hoặc báo cáo.

Bottleneck chính nằm ở bước đọc hiểu paper dài và chuyển nội dung học thuật thành ghi chú có cấu trúc, đủ chính xác để dùng trong seminar hoặc literature review. Impact có thể đo bằng thời gian đọc/tóm tắt một paper, số paper xử lý được, số ý quan trọng bị bỏ sót và thời gian chuẩn bị seminar.

Ngoài ra, nhóm hiểu domain này vì các thành viên đều là người học AI/nghiên cứu, có trải nghiệm đọc tài liệu tiếng Anh hoặc chuẩn bị seminar. Vì vậy problem này dễ validate và phù hợp để phân tích sâu trong phạm vi lab.
```

### Vì sao không chọn các candidate còn lại

```text
Nhóm chưa chọn problem bệnh nhân định hướng trước khi đi khám vì đây là problem có impact cao nhưng rủi ro y tế lớn. Nếu không thiết kế boundary rõ, hệ thống dễ bị hiểu nhầm là công cụ chẩn đoán. Nhóm cũng cần dữ liệu từ bệnh viện/phòng khám hoặc nhân viên tiếp nhận để validate tốt hơn.

Nhóm chưa chọn problem CSKH cần tra cứu dữ liệu khách hàng vì workflow và metric tốt, nhưng nhóm chưa có dữ liệu vận hành thật. Nếu không biết hệ thống dữ liệu gồm những gì, quyền truy cập ra sao và thao tác nào được phép tự động hóa, bài phân tích dễ dựa nhiều vào giả định.

Nhóm chưa chọn problem theo dõi lịch học/deadline vì một phần vấn đề có thể được giải quyết bằng calendar, checklist hoặc rule-based reminder. Mức độ cần AI chưa mạnh bằng bài toán đọc/tóm tắt/tổng hợp research papers.

Nhóm chưa chọn problem viết báo cáo tiến độ nghiên cứu hàng tuần vì chất lượng lập luận trong báo cáo khó đo hơn so với thời gian đọc và tóm tắt paper.

Nhóm chưa chọn problem đọc feedback giảng viên để sửa bài vì feedback rất đa dạng theo từng bài, từng giảng viên và từng loại lỗi. Do đó workflow và success metric khó chuẩn hóa hơn trong phạm vi lab.
```

### Nếu có disagreement, nhóm xử lý thế nào

```text
Ban đầu nhóm có nhiều hướng khác nhau như y tế, chăm sóc khách hàng, lịch học và nghiên cứu học thuật. Nhóm không vote ngay mà gom các candidates thành cluster để xem pattern chung.

Sau khi gom nhóm, cụm Research / Academic Reading & Synthesis có nhiều candidate nhất và nhiều thành viên hiểu domain nhất. Nhóm thống nhất chọn candidate này vì nó cân bằng tốt giữa impact, khả năng validate, khả năng đo metric và phạm vi phù hợp với lab.
```

---

# Phase 4 — Quick Validation + Research giải pháp

## Mục tiêu

Sau khi chọn candidate problem, nhóm cần kiểm tra nhanh:

- Pain có thật không?
- Người khác có gặp không?
- Đã có giải pháp nào tương tự chưa?
- Bài toán có nên giải bằng AI không?

---

## Bước 4.1 — Quick validation

### Kế hoạch validation

Nhóm hỏi nhanh 3–5 sinh viên đã từng đọc research paper hoặc chuẩn bị seminar/literature review.

Câu hỏi phỏng vấn nhanh:

1. Lần gần nhất bạn phải đọc research paper để chuẩn bị seminar/báo cáo là khi nào?
2. Bạn thường mất bao lâu để đọc và tóm tắt một paper?
3. Một tuần hoặc một milestone bạn thường phải đọc bao nhiêu paper?
4. Bước nào đau nhất: tìm paper, lọc paper, đọc method, hiểu result, hay tổng hợp nhiều paper?
5. Bạn đang dùng công cụ nào để hỗ trợ: Google Scholar, Semantic Scholar, ChatGPT, Elicit, Zotero, đọc thủ công?
6. Một summary “đủ tốt” với bạn cần có những phần nào?
7. Bạn có sợ AI tóm tắt sai, bỏ sót luận điểm hoặc bịa citation không?
8. Nếu có công cụ hỗ trợ, bạn muốn nó giúp ở bước nào nhưng vẫn để bạn kiểm soát phần nào?

### Kết quả validation

| Nguồn                | Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                                                                                                                  | Tín hiệu phản bác                                                                                                                                                      | Nhóm sửa problem thế nào                                                                                                                     |
| -------------------- | ----------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Interview nhanh      |       2 sinh viên | 2/2 sinh viên cho biết việc đọc paper tiếng Anh tốn nhiều thời gian, đặc biệt ở các phần method, experiment và related work. Thời gian đọc và ghi chú một paper dao động khoảng 60–120 phút tùy độ dài và độ khó của paper.                        | Không phải lúc nào người học cũng cần đọc full paper. Nếu mục tiêu chỉ là nắm ý chính, một số bạn chỉ đọc abstract, introduction và conclusion.                        | Nhóm thu hẹp problem từ “tự động làm literature review” thành “hỗ trợ tạo summary có cấu trúc và bảng so sánh để người học kiểm chứng”.      |
| Survey / poll nhỏ    |        5 phản hồi | Nhiều phản hồi cho thấy người học gặp khó khi tìm paper liên quan, hiểu method và rút ra contribution chính. Pain thường gặp không chỉ là “paper dài”, mà là khó chuyển nội dung paper thành ghi chú có cấu trúc để dùng cho seminar hoặc báo cáo. | Một số bạn đã dùng ChatGPT hoặc công cụ tóm tắt khác, nhưng vẫn phải kiểm tra lại vì lo AI bỏ sót ý quan trọng, hiểu sai method/result hoặc diễn giải quá chung chung. | Nhóm bổ sung human boundary: AI chỉ tạo draft summary và bảng so sánh ban đầu; người học phải đối chiếu lại với paper gốc trước khi sử dụng. |
| Minh chứng từ trao đổi nhóm học tập | 6 tin nhắn/ghi chú từ nhóm học tập và trao đổi cá nhân | Trong quá trình chuẩn bị seminar/báo cáo, nhóm ghi nhận nhiều trao đổi liên quan đến việc đọc paper như: “paper này dài quá”, “phần method khó hiểu”, “không biết contribution chính là gì”, “có paper nào liên quan hơn không?”, “summary của mỗi người đang viết khác format”. Các trao đổi này cho thấy pain không chỉ là đọc paper lâu, mà còn là khó hiểu method, khó rút ý chính và khó chuẩn hóa ghi chú giữa các thành viên. | Đây chưa phải log chính thức từ hệ thống học tập hay ticket support. Evidence chủ yếu đến từ nhóm chat/trao đổi nội bộ nên có thể bị thiên lệch theo trải nghiệm của nhóm. | Nhóm bổ sung yêu cầu output có cấu trúc cố định gồm: problem, contribution, method, dataset, result, limitation, citation note. Đồng thời nhóm đặt human boundary: người học phải kiểm chứng summary với paper gốc trước khi dùng cho seminar/literature review. |



## Bước 4.2 — Research giải pháp đã có

| Nguồn / tool / case                  | Link                                                                                   | Họ giải quyết phần nào?                                                                                                                                                          | Điểm mạnh                                                                                                                                        | Khoảng trống / rủi ro                                                                                                                                                           | Bài học cho nhóm                                                                                                                                         |
| ------------------------------------ | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Google Scholar / arXiv search        | https://scholar.google.com / https://arxiv.org                                         | Tìm paper theo keyword, tác giả, chủ đề.                                                                                                                                         | Phổ biến, dễ dùng, có nhiều paper.                                                                                                               | Người học vẫn phải tự lọc nhiều paper không liên quan và tự đọc/tóm tắt.                                                                                                        | Search tool có sẵn là tốt; nhóm không nên tự build search engine từ đầu.                                                                                 |
| Semantic Scholar                     | https://www.semanticscholar.org                                                        | Hỗ trợ tìm paper, khám phá paper liên quan, xem citation và related works.                                                                                                       | Tốt cho bước tìm và lọc paper ban đầu.                                                                                                           | Không giải quyết hoàn toàn việc tạo summary cá nhân hóa theo format seminar.                                                                                                    | Có thể coi là tool hỗ trợ ở bước search/lọc paper.                                                                                                       |
| Elicit                               | https://elicit.com                                                                     | Hỗ trợ tìm paper, trích xuất thông tin và so sánh paper theo bảng.                                                                                                               | Phù hợp cho giai đoạn research question, search và extract thông tin có cấu trúc.                                                                | Người học vẫn cần kiểm chứng paper gốc; output có thể chưa đúng mục tiêu môn học cụ thể.                                                                                        | Pattern tốt: search → extract → compare → human verify.                                                                                                  |
| Scholarcy                            | https://www.scholarcy.com                                                              | Hỗ trợ tóm tắt paper/article thành dạng dễ đọc hơn.                                                                                                                              | Tốt cho bước nắm ý chính ban đầu.                                                                                                                | Có thể bỏ sót chi tiết quan trọng; không thay thế việc đọc paper khi cần độ chính xác cao.                                                                                      | AI summary nên là draft hỗ trợ, không phải output cuối.                                                                                                  |
| Zotero                               | https://www.zotero.org                                                                 | Hỗ trợ lưu, quản lý, chú thích, trích dẫn và tổ chức thư viện paper.                                                                                                             | Tốt cho quản lý tài liệu và citation.                                                                                                            | Không trực tiếp giải quyết bottleneck đọc hiểu và tổng hợp insight.                                                                                                             | Có thể dùng như supporting tool, không phải giải pháp AI chính.                                                                                          |
| ChatGPT / LLM summary                | N/A                                                                                    | Tóm tắt, giải thích đoạn khó, chuyển paper thành ghi chú.                                                                                                                        | Linh hoạt, dễ dùng, có thể tùy biến format summary.                                                                                              | Rủi ro hallucination, hiểu sai method/result, không kiểm chứng citation nếu không có paper/context đầy đủ.                                                                      | Cần thiết kế boundary: luôn yêu cầu đối chiếu paper gốc và đánh dấu claim cần kiểm chứng.                                                                |
| RAG — Retrieval-Augmented Generation | Paper: “Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks”              | Kết hợp LLM với bước truy xuất tài liệu liên quan trước khi sinh câu trả lời. Trong bài toán của nhóm, RAG có thể dùng để truy xuất đúng đoạn trong paper trước khi tạo summary. | Giúp câu trả lời bám vào tài liệu nguồn hơn so với chỉ dùng LLM thuần; phù hợp khi cần trả lời dựa trên paper cụ thể.                            | Nếu retrieval sai đoạn, summary vẫn có thể sai. RAG cũng không tự đảm bảo hiểu đúng contribution/method/result nếu chunking hoặc query không tốt.                               | Workflow nên là: upload paper → chunk/index → retrieve đoạn liên quan → tạo summary theo template → người học kiểm chứng với paper gốc.                  |
| GraphRAG                             | Paper/case: “A Graph RAG Approach to Query-Focused Summarization” / Microsoft GraphRAG | Dùng graph/community structure để tổng hợp thông tin ở cấp corpus, phù hợp với câu hỏi kiểu “các theme chính là gì?”, “các paper có gap chung nào?”.                             | Hữu ích khi nhóm cần tổng hợp nhiều paper, tìm pattern, theme hoặc research gap thay vì chỉ tóm tắt từng paper riêng lẻ.                         | Phức tạp hơn RAG thường; cần xây graph/entity/relation/community summary. Có thể quá nặng nếu scope lab chỉ là tóm tắt 1–2 paper.                                               | Không nên chọn làm MVP đầu tiên, nhưng có thể nhắc như hướng mở rộng nếu bài toán chuyển sang tổng hợp literature review nhiều paper.                    |
| LightRAG                             | Paper: “LightRAG: Simple and Fast Retrieval-Augmented Generation”                      | Một hướng RAG dùng graph structure kết hợp retrieval ở nhiều mức để tăng contextual awareness và hiệu quả truy xuất.                                                             | Phù hợp với bài toán nhiều paper vì có thể biểu diễn quan hệ giữa khái niệm, method, dataset, task và result tốt hơn retrieval phẳng theo chunk. | Vẫn là hướng kỹ thuật tương đối mới/phức tạp; để triển khai tốt cần xử lý indexing, graph construction và evaluation. Không phù hợp nếu nhóm chỉ cần prototype nhanh trong lab. | Có thể ghi là hướng technical pattern tham khảo, không phải giải pháp bắt buộc. MVP nên bắt đầu từ RAG đơn giản + template summary + human verification. |

### Insight sau validation + research

```text
Pain thật không chỉ nằm ở việc “đọc paper lâu”, mà nằm ở việc biến paper dài thành ghi chú có cấu trúc và đủ tin cậy để dùng trong seminar hoặc literature review.

Các công cụ hiện có đã hỗ trợ từng phần riêng lẻ như tìm paper, quản lý tài liệu, tóm tắt nhanh hoặc trích xuất thông tin. Tuy nhiên, khoảng trống của nhóm là hỗ trợ sinh viên chuyển một hoặc nhiều research papers thành ghi chú học thuật có cấu trúc, có thể kiểm chứng và dùng được cho seminar/báo cáo.

Do đó, hướng hợp lý không phải Agent tự đọc, tự chọn paper, tự viết báo cáo hoàn chỉnh. Hướng phù hợp hơn là Workflow: người học cung cấp paper hoặc danh sách paper → hệ thống trích xuất các phần chính → tạo summary có cấu trúc → gợi ý so sánh → người học kiểm tra lại với paper gốc trước khi sử dụng.
```

---

# Phase 5 — Workflow + Problem Statement

## Bước 5.1 — Current workflow bản nhóm

### Current workflow — ASCII

```text
CURRENT WORKFLOW — Đọc và tổng hợp research papers thủ công

┌──────────────────────────────────────────────┐
│ 1. Xác định chủ đề / research question        │
│ Actor: Sinh viên                              │
│ Time: 10–20 phút                              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 2. Tìm keyword và search paper                │
│ Nguồn: Google Scholar / arXiv / Semantic      │
│ Time: 30–90 phút                              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 3. Lọc paper qua title / abstract / citation  │
│ Output: shortlist 2–5 papers                  │
│ Time: 20–60 phút                              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 4. Đọc full paper                             │
│ Input: PDF paper dài 8–20+ trang              │
│ Time: 60–120 phút/paper                       │
│ 🔴 BOTTLENECK 1                               │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 5. Ghi chú thủ công                           │
│ Problem / contribution / method / dataset     │
│ result / limitation                           │
│ Time: 30–60 phút/paper                        │
│ 🔴 BOTTLENECK 2                               │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 6. So sánh nhiều paper                        │
│ Methods / results / gaps / limitations        │
│ Time: 1–4 giờ                                 │
│ 🔴 BOTTLENECK 3                               │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 7. Viết slide seminar / literature review     │
│ Output cuối                                   │
│ Time: 1–3 giờ                                 │
└──────────────────────────────────────────────┘
```

### Current workflow dạng bảng

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Sinh viên/người nghiên cứu | Chủ đề seminar hoặc câu hỏi nghiên cứu | Từ khóa tìm kiếm ban đầu | 10–20 phút/lần | Người học thường phải tự nghĩ keyword và phạm vi tìm kiếm. |
| 2 | Sinh viên/người nghiên cứu | Từ khóa, Google Scholar/arXiv/Semantic Scholar | Danh sách paper candidate | 30–90 phút/lần | Có nhiều paper không liên quan hoặc chỉ liên quan một phần. |
| 3 | Sinh viên/người nghiên cứu | Abstract, title, venue, citation | Shortlist 2–5 paper cần đọc | 20–60 phút/lần | Dễ bỏ sót paper quan trọng hoặc chọn paper chưa phù hợp. |
| 4 | Sinh viên/người nghiên cứu | Full paper PDF | Hiểu nội dung chính của paper | 60–120 phút/paper | Bottleneck 1: paper dài, tiếng Anh học thuật và có nhiều chi tiết kỹ thuật. |
| 5 | Sinh viên/người nghiên cứu | Full paper + ghi chú cá nhân | Ghi chú problem, contribution, method, dataset, result, limitation | 30–60 phút/paper | Bottleneck 2: ghi chú dễ thiếu cấu trúc, mỗi người ghi một kiểu. |
| 6 | Sinh viên/người nghiên cứu | Ghi chú của nhiều paper | Bảng so sánh methods/results/gaps | 1–4 giờ/lần | Bottleneck 3: khó đối chiếu nhiều paper vì format và thuật ngữ khác nhau. |
| 7 | Sinh viên/người nghiên cứu | Ghi chú + bảng so sánh | Slide seminar / literature review draft | 1–3 giờ/lần | Dễ thiếu citation, bỏ sót insight hoặc viết lại quá giống paper gốc. |

### Bottleneck chính

```text
Bottleneck chính nằm ở bước 4, 5 và 6.

Sinh viên không chỉ mất thời gian đọc paper, mà còn mất nhiều effort để:
- hiểu paper dài bằng tiếng Anh học thuật;
- xác định contribution chính;
- tách method, dataset, experiment, result và limitation;
- chuyển nội dung paper thành ghi chú có cấu trúc;
- so sánh nhiều paper theo cùng một khung phân tích.

Khi cần đọc 2–3 paper, tổng thời gian chuẩn bị có thể lên tới 4–6 tiếng.
```

---

## Bước 5.2 — Future workflow bản nhóm

### Future workflow — ASCII

```text
FUTURE WORKFLOW — AI hỗ trợ, người học kiểm chứng

┌──────────────────────────────────────────────┐
│ 1. Xác định chủ đề / research question        │
│ Actor: Sinh viên                              │
│ Time: 5–10 phút                               │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 2. Search paper bằng tool có sẵn              │
│ Google Scholar / arXiv / Semantic Scholar     │
│ Time: 10–30 phút                              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 3. Chọn paper hoặc upload PDF                 │
│ Output: 2–5 papers cần xử lý                  │
│ 🟢 HUMAN DECISION                             │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 4. AI trích xuất nội dung chính               │
│ Problem / contribution / method / dataset     │
│ result / limitation                           │
│ Time: 5–10 phút/paper                         │
│ 🔵 AI SUPPORT                                 │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 5. AI tạo summary theo template               │
│ Output: structured summary                    │
│ Time: 5–10 phút/paper                         │
│ 🔵 AI SUPPORT                                 │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 6. Sinh viên kiểm chứng với paper gốc         │
│ Check method / result / citation / limitation │
│ Time: 20–30 phút/paper                        │
│ 🟢 HUMAN BOUNDARY                             │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 7. AI gợi ý bảng so sánh nhiều paper          │
│ Methods / datasets / results / gaps           │
│ Time: 10–20 phút                              │
│ 🔵 AI SUPPORT                                 │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│ 8. Sinh viên viết slide / literature review   │
│ Người học quyết định nội dung cuối            │
│ Time: 30–60 phút                              │
│ 🟢 HUMAN FINAL                                │
└──────────────────────────────────────────────┘
```

### Before/after impact

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 7 | 8 | Tăng 1 bước review rõ ràng để kiểm soát chất lượng. |
| Tổng thời gian đọc + tóm tắt 1 paper | 90–120 phút | 25–40 phút | AI tạo summary nháp, sinh viên kiểm chứng lại. |
| Tổng thời gian chuẩn bị 2–3 paper | 4–6 tiếng | 1.5–2.5 tiếng | Giảm effort ở bước đọc, ghi chú và so sánh. |
| Số bước thủ công nặng | 4 bước | 2 bước | Người học vẫn chọn paper và kiểm chứng nội dung. |
| Bottleneck chính | Đọc full paper, ghi chú thủ công, so sánh nhiều paper | Kiểm chứng summary AI với paper gốc | Bottleneck mới chấp nhận được vì đây là human boundary. |
| Risk mới | Không có hallucination AI, nhưng tốn thời gian | AI có thể tóm tắt sai, bỏ sót ý, hiểu sai result hoặc citation | Cần bắt buộc đối chiếu paper gốc. |

---

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên AI, sinh viên năm cuối hoặc thành viên nhóm nghiên cứu cần đọc research papers để chuẩn bị seminar, literature review hoặc báo cáo học thuật. |
| **Workflow** | Người học xác định chủ đề → tìm paper → lọc paper liên quan → đọc full paper → ghi chú contribution/method/result/limitation → so sánh nhiều paper → viết slide seminar hoặc literature review. |
| **Bottleneck** | Bước đọc full paper và viết summary có cấu trúc mất nhiều thời gian nhất, đặc biệt khi paper dài, viết bằng tiếng Anh học thuật và chứa nhiều chi tiết kỹ thuật. |
| **Impact** | Mỗi paper có thể mất khoảng 90–120 phút để đọc và tóm tắt; chuẩn bị 2–3 paper cho seminar có thể mất 4–6 tiếng. Người học dễ bỏ sót contribution, hiểu chưa đúng method/result hoặc khó tổng hợp thành insight. |
| **Success Metric** | Giảm thời gian tạo summary có kiểm chứng cho 1 paper từ 90–120 phút xuống khoảng 25–40 phút, đồng thời không bỏ sót các trường quan trọng như problem, contribution, method, dataset, result, limitation và citation. |
| **Boundary** | AI không thay người học đọc và chịu trách nhiệm học thuật. AI không được bịa citation, không được kết luận thay người học, không được dùng summary làm nội dung cuối nếu chưa đối chiếu với paper gốc. |

### Vấn đề của v0

```text
Problem Statement v0 đã có actor, workflow, bottleneck và metric ban đầu, nhưng vẫn còn một số điểm cần làm rõ:

1. Scope còn hơi rộng vì bao gồm cả tìm paper, đọc paper, tóm tắt và tổng hợp literature review.
2. Success metric mới tập trung vào thời gian, chưa đủ điều kiện chất lượng.
3. Boundary cần nói rõ hơn AI can thiệp ở bước nào và người học kiểm tra ở đâu.
4. Cần phân biệt rõ AI hỗ trợ tạo summary nháp, không tự viết báo cáo cuối.
```

---

# Phase 6 — Rule / Workflow / Agent + Decision

## Bước 6.0 — Ma trận độ phù hợp với AI để suy nghĩ nhanh

### Bài toán của nhóm nằm ở ô nào?

```text
Độ mơ hồ cao + độ phức tạp trung bình/cao.
```

### Vì sao?

```text
Bài toán có độ mơ hồ cao vì summary/literature review không chỉ có một đáp án đúng duy nhất. Một paper có thể được tóm tắt theo nhiều mức chi tiết khác nhau tùy mục tiêu: seminar, literature review, implementation hay báo cáo tiến độ.

Bài toán cũng có độ phức tạp tương đối cao vì workflow gồm nhiều bước nối tiếp: tìm paper, lọc paper, đọc paper, trích xuất thông tin, so sánh nhiều paper và tạo output học thuật. Tuy nhiên, các bước này vẫn khá rõ ràng và có thể thiết kế thành workflow tuần tự. AI chưa cần tự lập kế hoạch hoàn toàn như một agent.
```

---

## Bước 6.1 — So sánh No AI / Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Chỉ hướng dẫn người học đọc paper bằng phương pháp thủ công, ví dụ đọc abstract → introduction → method → experiment → conclusion. | Đủ nếu số lượng paper ít và người học chỉ cần nắm ý chính rất nhanh. | Không giải quyết bottleneck đọc hiểu tài liệu dài và so sánh nhiều paper. | Không chọn. |
| **Rule** | Dùng template cố định để ghi chú paper: problem, method, dataset, result, limitation; dùng checklist đọc paper thủ công. | Đủ nếu người học chỉ cần một form chuẩn để tự điền và số lượng paper ít. | Không giảm nhiều thời gian đọc hiểu; không hỗ trợ xử lý ngôn ngữ học thuật dài; vẫn phụ thuộc hoàn toàn vào người học. | Không chọn làm giải pháp chính, nhưng dùng làm cấu trúc output. |
| **Workflow** | Người học chọn/cung cấp paper → AI trích xuất summary theo template → người học kiểm chứng với paper gốc → AI hỗ trợ so sánh nhiều summary → người học viết slide/báo cáo cuối. | Đủ khi các bước đã rõ, AI chỉ hỗ trợ đọc hiểu, tóm tắt và so sánh; người học vẫn kiểm soát nội dung cuối. | AI có thể tóm tắt sai, bỏ sót ý, hiểu sai result hoặc hallucinate citation nếu không có kiểm chứng. | Chọn. |
| **Agent** | Agent tự tìm paper, tự chọn paper, tự đọc, tự tổng hợp literature review và đề xuất nội dung seminar hoàn chỉnh. | Chỉ cần nếu workflow có nhiều nhánh động, cần tự quyết định chiến lược tìm kiếm và tự gọi nhiều công cụ trong môi trường tin cậy. | Quá rộng cho lab; rủi ro chọn sai paper, bịa citation, hiểu sai nội dung học thuật; khó kiểm soát và khó đánh giá. | Chưa chọn. |

### Mức chọn

```text
Workflow
```

### Vì sao chọn

```text
Nhóm chọn Workflow vì bài toán có nhiều bước rõ ràng và AI có thể hỗ trợ ở một số bước cụ thể:
1. Tóm tắt paper.
2. Trích xuất các trường quan trọng.
3. Chuẩn hóa ghi chú theo template.
4. So sánh nhiều paper.
5. Gợi ý gap hoặc điểm khác biệt giữa các paper.

Người học vẫn phải chọn paper, kiểm chứng nội dung với paper gốc và quyết định nội dung cuối dùng trong seminar hoặc literature review.

Workflow phù hợp hơn Agent vì nhóm chưa cần AI tự lập kế hoạch toàn bộ, tự quyết định paper nào quan trọng hoặc tự viết báo cáo cuối. Rủi ro học thuật như hiểu sai method/result hoặc bịa citation cần human-in-the-loop rõ.
```

### Vì sao không chọn mức đơn giản hơn

```text
No AI hoặc Rule/template có thể giúp chuẩn hóa cách ghi chú paper, nhưng chưa giải quyết đủ bottleneck đọc hiểu tài liệu dài tiếng Anh và tổng hợp nội dung học thuật.

Nếu chỉ dùng checklist, người học vẫn phải tự đọc toàn bộ paper và tự viết summary từ đầu. Vì vậy, Rule có thể là một phần của workflow, nhưng chưa đủ làm giải pháp chính.
```

---

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên AI, sinh viên năm cuối hoặc thành viên nhóm nghiên cứu cần đọc research papers để chuẩn bị seminar, literature review hoặc báo cáo học thuật. |
| **Workflow** | Xác định chủ đề → tìm paper → lọc paper liên quan → đọc full paper → ghi chú contribution/method/dataset/result/limitation → so sánh nhiều paper → viết slide seminar hoặc literature review. |
| **Bottleneck** | Đọc full paper và chuyển nội dung học thuật dài thành summary có cấu trúc mất nhiều thời gian nhất, khoảng 90–120 phút/paper theo ước lượng ban đầu từ pitch cá nhân. |
| **Impact** | Khi cần đọc 2–3 paper cho một seminar, tổng thời gian chuẩn bị có thể lên tới 4–6 tiếng. Người học dễ bỏ sót contribution, hiểu chưa đúng method/result hoặc khó so sánh nhiều paper để rút ra gap. |
| **Success Metric** | Giảm thời gian tạo summary có kiểm chứng cho 1 paper từ 90–120 phút xuống khoảng 25–40 phút; summary vẫn phải có đủ các trường problem, contribution, method, dataset, result, limitation và citation note; người học không phải viết lại quá 50% summary sau khi review. |
| **Boundary** | AI không thay người học đọc và chịu trách nhiệm học thuật. AI không được bịa citation, không được kết luận thay người học, không tự chọn nội dung cuối đưa vào seminar/báo cáo nếu chưa được người học kiểm chứng với paper gốc. |
| **AI intervention point** | Sau khi người học có paper hoặc shortlist paper, AI hỗ trợ trích xuất thông tin chính, tạo summary theo template và gợi ý bảng so sánh giữa nhiều paper. |
| **Mức chọn** | Workflow: template/rule định nghĩa cấu trúc summary, AI hỗ trợ đọc hiểu và tổng hợp, người học review và quyết định nội dung cuối. |
| **Rủi ro & người thật kiểm tra** | Rủi ro: AI tóm tắt sai, bỏ sót ý quan trọng, hiểu sai method/result, tạo citation không chính xác hoặc làm người học phụ thuộc quá mức. Người thật kiểm tra: sinh viên/người nghiên cứu phải đối chiếu summary với paper gốc, kiểm tra citation và chỉnh sửa trước khi dùng trong seminar/literature review. |

### Problem Statement một câu

```text
Sinh viên/người nghiên cứu mất nhiều thời gian để đọc và chuyển research papers dài thành summary học thuật có cấu trúc phục vụ seminar/literature review; nhóm đề xuất workflow AI hỗ trợ trích xuất và so sánh nội dung, nhưng người học vẫn kiểm chứng với paper gốc trước khi sử dụng.
```

---

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor là sinh viên/người nghiên cứu; workflow đọc và tổng hợp paper có thể mô tả rõ. |
| Baseline và success metric đã đo được chưa? | Not Yet | Có ước lượng ban đầu 90–120 phút/paper và 4–6 tiếng cho 2–3 paper, nhưng cần validate bằng interview hoặc thử nghiệm thật. |
| Có data/input đủ dùng chưa? | Yes | Input có thể là PDF paper, abstract hoặc link paper do người học cung cấp. |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes, nếu có review | Hậu quả có thể kiểm soát nếu summary chỉ là bản nháp và người học bắt buộc kiểm chứng với paper gốc. |
| Có người review/owner vận hành không? | Yes | Người học là owner cuối, phải kiểm tra trước khi dùng. |
| Có cách non-AI đơn giản hơn không? | Yes | Template ghi chú paper và checklist đọc paper có thể hỗ trợ, nhưng không giảm đủ bottleneck đọc hiểu/tóm tắt. |

### Decision

```text
Not Yet → cần quick validation/pilot nhỏ trước khi Go.
```

### Lý do

```text
Nhóm chưa nên Go ngay vì baseline thời gian và mức độ pain hiện mới đến từ pitch cá nhân và quick validation sơ bộ, chưa có thử nghiệm thật với cùng một paper trước/sau khi dùng workflow AI.

Tuy nhiên, problem có actor rõ, workflow rõ, bottleneck rõ và rủi ro có thể kiểm soát bằng human review. Nếu validation/pilot xác nhận rằng sinh viên thực sự mất nhiều thời gian ở bước đọc/tóm tắt paper và AI summary giúp giảm thời gian mà không làm giảm chất lượng, nhóm có thể chuyển sang Go với scope nhỏ.
```

### Nếu Go, pilot nhỏ nhất là

```text
Pilot với 2–3 sinh viên và 1–2 research papers thật.

Quy trình pilot:
1. Mỗi sinh viên tự đọc/tóm tắt paper theo cách hiện tại và đo thời gian.
2. Sau đó dùng workflow AI để tạo summary theo template.
3. Sinh viên review summary với paper gốc.
4. Đo thời gian review, số lỗi AI, số ý bị bỏ sót và tỷ lệ nội dung phải viết lại.
5. So sánh tổng thời gian và chất lượng summary trước/sau.

Tiêu chí pass:
- Thời gian tạo summary có kiểm chứng giảm xuống khoảng 25–40 phút/paper.
- Summary không bỏ sót các trường quan trọng.
- Người học không phải viết lại quá 50% nội dung.
- Không có citation hoặc claim quan trọng bị bịa.
```

### Nếu Not Yet, cần validate gì trước

```text
1. Hỏi 3–5 sinh viên đã từng đọc paper để xác nhận baseline thời gian.
2. Xác định bottleneck lớn nhất là tìm paper, đọc paper, hiểu method/result hay so sánh nhiều paper.
3. Xác định format summary “đủ tốt” cho seminar/literature review.
4. Thử với 1 paper thật để kiểm tra AI có bỏ sót hoặc hiểu sai nội dung không.
5. Đo xem người học phải sửa bao nhiêu phần trăm summary sau khi AI tạo nháp.
```

### Nếu No-Go, nên làm gì thay AI

```text
Nếu validation cho thấy AI summary không đáng tin hoặc sinh viên vẫn phải viết lại phần lớn nội dung, nhóm nên hạ xuống giải pháp non-AI:
- Template đọc paper chuẩn.
- Checklist kiểm tra contribution/method/dataset/result/limitation.
- Bảng so sánh paper thủ công.
- Hướng dẫn cách đọc paper theo thứ tự: abstract → introduction → method → experiment → conclusion.
```

---

# Tự kiểm cuối phần nhóm

- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [x] [15đ nhóm] Nhóm có workflow trước/sau.
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
