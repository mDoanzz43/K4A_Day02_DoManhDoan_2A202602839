# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đỗ Mạnh Đoan
- Mã học viên: 2A202602839
- Nhóm: Nhóm Nhanh Quên
- Candidate problem nhóm chọn: Chuẩn hóa và tổng hợp khoảng 200 phiếu khảo sát từ Công an xã và UBND xã thành file Excel và DOCX có cấu trúc, giảm thao tác nhập/copy thủ công và lỗi trước khi bàn giao cho Giám đốc/PM.
---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 problem trong workflow tìm việc của sinh viên mới tốt nghiệp, sau đó chọn ba problem về đối chiếu JD, cá nhân hóa CV và theo dõi application. | Nhóm có thêm ba candidate #16–#18 thuộc cluster tìm việc, trong đó có cả bài cần AI và bài chỉ cần Rule/Workflow. |
| Pitch Problem Card | Tôi trình bày Card #1 về việc đọc, tách yêu cầu và đối chiếu 20–25 JD AI với CV/project. Tôi nêu bottleneck 7–9 phút/JD, metric thời gian và rủi ro bỏ sót job phù hợp. | Candidate được đưa vào danh sách hội tụ với actor, workflow, metric, boundary và pilot 20 JD rõ ràng. |
| Challenge bài của bạn khác | Với candidate khảo sát của bạn Thương, tôi đặt lại câu hỏi: thực tế là 200 phiếu tổng cộng hay 200 xã × 2 loại phiếu, và 10 phút/phiếu đã bao gồm copy/chuẩn hóa chưa. | Nhóm không tiếp tục coi 66,6 giờ là fact; Phase 5 ghi hai công thức và yêu cầu bấm giờ tách từng bước. |
| Gom trùng / cluster | Tôi rà soát việc xếp #16–#18 vào cluster A và kiểm tra mỗi candidate chỉ thuộc một cluster chính. | Cluster tìm việc được tách thành ba điểm nghẽn: chọn job, sửa CV và theo dõi sau nộp, tránh gộp thành “trợ lý tìm việc toàn năng”. |
| Chọn candidate problem | Tôi đồng ý đưa #4 lên đầu vì actor, input và hai output Excel/DOCX rõ, nhưng yêu cầu giữ trạng thái giả định cho baseline. | Nhóm chọn được bài có workflow vẽ được nhưng không bỏ qua điểm yếu evidence. |
| Validation / research | Tôi review phần validation và chỉ ra chưa có interview quote, log hoặc sample thật; đồng thời kiểm tra việc giữ Forms/Power Query/template làm baseline non-AI. | Báo cáo ghi rõ Phase 4 chưa hoàn tất và không dùng số liệu chưa xác minh để kết luận Go triển khai. |
| Workflow nhóm | Tôi rà soát Current/Future Workflow, đặc biệt việc không cộng chồng 33,3 phút copy hoặc rework vào baseline 10 phút/phiếu nếu các khoảng này đã nằm trong cùng phép đo. | Workflow có bottleneck, handoff, machine step, AI step, BA review và fallback rõ hơn. |
| Problem Statement | Tôi review các field metric và boundary, sửa baseline thành 33,3 giờ nếu có 200 phiếu hoặc 66,7 giờ nếu có 400 phiếu. | Problem Statement v1 phân biệt fact/assumption và có cách tính lại khi số phiếu được xác nhận. |
| Rule / Workflow / Agent | Tôi đối chiếu ba mức và đặt câu hỏi liệu Rule/template có xử lý được 70–80% effort hay không. Tôi đồng ý chọn Workflow có Rule + một bước AI + BA review, không chọn Agent. | Giải pháp không bị solution-first: Rule xử lý trường cố định, AI chỉ hỗ trợ free text, BA giữ quyền duyệt. |
| Decision | Tôi review điều kiện Go/Not Yet/No-Go và đề xuất “Not Yet cho triển khai, Go cho pilot validation 50 phiếu”. | Quyết định cuối phù hợp với việc nhóm chưa có quote, baseline xác nhận, sample và quyền dữ liệu. |

**Dấu tay rõ nhất của tôi trong artifact cuối:**

```text
Dấu tay rõ nhất của tôi là phát hiện và yêu cầu sửa mâu thuẫn giữa 200/400 phiếu với baseline 66,6 giờ. Tôi cũng giúp giữ human boundary: AI chỉ gợi ý nhóm free text có nguồn, còn BA phải đối chiếu và duyệt trước khi bàn giao.
```

---


## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi dùng AI sau khi tự xác định bối cảnh tìm việc để mở rộng problem theo bốn lăng kính. | AI giúp gợi ý thêm các bước nhỏ như phát hiện JD trùng, nhập lại form và quản lý phiên bản CV. | Một số ý quá rộng như career coach toàn năng hoặc Agent tự apply, không phản ánh một bottleneck cụ thể. | Tôi loại các ý quá rộng và chỉ giữ 10 problem có actor, workflow và cách đo. |
| Problem Card | Tôi dùng AI để phản biện Card đối chiếu JD với CV và gợi ý metric/fallback. | AI giúp tách current/future workflow và nêu rủi ro keyword matching. | AI ban đầu chấp nhận baseline ước tính như số thật và đề xuất match score dễ tạo cảm giác chính xác giả. | Tôi ghi rõ baseline cần bấm giờ, dùng ground truth do người dùng review và không cho AI tự loại job. |
| Workflow | Tôi dùng AI để cấu trúc workflow hiện tại và workflow sau cho candidate nhóm. | AI giúp tách Rule, AI, human review, handoff và fallback thành các bước dễ đọc. | AI ban đầu có nguy cơ cộng chồng thời gian đọc, copy, sửa lỗi; đồng thời lẫn 200 phiếu với 400 phiếu. | Tôi kiểm lại phép tính, không cộng các khoảng có thể overlap và ghi hai trường hợp cần validation. |
| Research | Tôi dùng AI để gợi ý nhóm công cụ/pattern cần xem xét như form, Power Query, mail merge và workflow automation. | AI giúp nhóm nhìn ra baseline non-AI và tránh nghĩ chỉ có Agent. | AI có thể mô tả khả năng công cụ quá rộng hoặc đưa link mà chưa kiểm. | Tôi chỉ giữ link chính thức do nhóm cung cấp, ghi giới hạn từng công cụ và không dùng số liệu không có nguồn. |
| Problem Statement | Tôi dùng AI để kiểm tra đủ Actor–Workflow–Bottleneck–Impact–Metric–Boundary. | AI giúp phát hiện field còn thiếu và làm rõ intervention point. | AI ban đầu viết target quá tự tin khi Phase 4 chưa có log, interview hoặc sample thật. | Tôi chuyển target thành giả thuyết pilot, nêu công thức tính và đánh dấu baseline chưa xác nhận. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh ba mức trên cùng một problem. | AI giúp phân biệt Rule cho trường cố định, Workflow cho chuỗi bước và Agent cho kế hoạch động. | AI có xu hướng thêm AI/Agent vì free text dù chưa chứng minh Rule không đủ. | Tôi yêu cầu chạy baseline Rule/template trước và chỉ dùng AI ở bước nhóm ngữ nghĩa nếu tạo thêm lợi ích. |
| Decision | Tôi dùng AI để liệt kê điều kiện Go, Not Yet, No-Go và exit/rollback. | AI giúp tạo checklist về data, accuracy, human owner và rủi ro dữ liệu. | Đề xuất ban đầu nghiêng về Go với pilot dù evidence còn thiếu. | Tôi chốt Not Yet cho triển khai và chỉ Go cho pilot 50 phiếu đã ẩn danh, có ngưỡng dừng rõ. |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Sau khi nghe Top 3 problem của các thành viên, tôi nhận ra bài mạnh nhất không phải bài dùng AI nhiều nhất mà là bài có actor, workflow và bằng chứng rõ nhất. Trước buổi thảo luận, tôi thường nghĩ những việc có nhiều tài liệu tự do thì nên dùng Agent, nhưng nhiều candidate của nhóm thực tế có thể giải quyết phần lớn bằng form, template hoặc Rule. Khi so các candidate, tôi đưa ba problem tìm việc của mình vào cluster A nhưng đồng ý chọn bài tổng hợp phiếu khảo sát vì đầu vào và hai đầu ra Excel/DOCX cụ thể hơn. Tuy nhiên, tôi thay đổi từ “đồng ý Go” sang yêu cầu kiểm chứng khi nhận ra con số 66,6 giờ không khớp với mô tả 200 phiếu. Dấu tay rõ nhất của tôi trong artifact là rà lại phép tính, tách assumption khỏi fact và yêu cầu không cộng chồng những khoảng thời gian có thể cùng nằm trong 10 phút/phiếu. Điều khó nhất khi viết Problem Statement không phải nghĩ giải pháp mà là đặt metric có baseline, target và cách đo trong khi nhóm chưa có log thật. AI ban đầu chấp nhận số 66,6 giờ và đề xuất Go khá nhanh, nên nếu không review kỹ thì bài trông đầy đủ nhưng lập luận không chắc. Tôi đã sửa bằng cách giữ hai trường hợp 200/400 phiếu, chuyển target thành giả thuyết và chốt Not Yet cho triển khai nhưng Go cho pilot validation. Tôi cũng học được rằng boundary phải nói rõ AI được phép làm gì, ai kiểm nguồn và ai chịu trách nhiệm duyệt cuối. Nếu làm lại, tôi sẽ yêu cầu nhóm phỏng vấn BA và lấy 50 phiếu mẫu ngay từ đầu thay vì đợi đến sau khi chọn candidate. Tôi cũng sẽ challenge mạnh hơn về định nghĩa “một lỗi”, cách tạo gold set và liệu Rule/template đã giải quyết được ít nhất 80% effort chưa. Sau lab, tôi có thể tự giải thích mạch problem → workflow → bottleneck → metric → boundary → Rule/Workflow/Agent thay vì bắt đầu từ ý tưởng xây AI.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [X] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [X] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [X] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [X] [15đ] Nhóm có workflow trước/sau
- [X] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [X] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [X] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [X] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [X] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

