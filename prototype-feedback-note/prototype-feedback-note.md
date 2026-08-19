
# Prototype Feedback Note

## Track 1 — Day 18 — Multiple Prototypes — Human–AI Design

---

## 1. Thông tin phiên test

- **Facilitator:** Vũ Huy Hoàng
- **MHV:** 2A202601057
- **Case:** Case B — AI Notes: Personal Learning Notes
- **Tester:** T01
- **Tester ngoài nhóm:** Có
- **Prototype được test:** Option A / Option B / Option C
- **Hình thức:** Tester trực tiếp trải nghiệm cả ba prototype và phản hồi bằng lời nói
- **Evidence:** 3 file ghi âm của phiên test

---

## 2. Mục tiêu của phiên test

Phiên test nhằm quan sát cách learner phản ứng với ba cách phân chia công việc khác nhau giữa người dùng và AI khi tổ chức các nội dung đã lưu trong quá trình học.

Cả ba prototype cùng giải quyết một task:

> Từ các highlight, note, câu hỏi và nội dung “Chưa hiểu” đã lưu trong bài học, hãy tạo một bộ ghi chú mà bạn có thể sử dụng lại khi ôn tập.

Ba phương án khác nhau chủ yếu ở mức độ AI tham gia:

- **Option A:** Người dùng tự tổ chức toàn bộ.
- **Option B:** AI đưa ra đề xuất và hỏi người dùng trước mỗi quyết định.
- **Option C:** AI tự tạo phần lớn bản ghi chú, người dùng kiểm tra trước khi lưu.

---

## 3. Common Context

Tester được đặt trong cùng một bối cảnh ở cả ba phương án.

### 3.1. Bối cảnh

Tester vừa hoàn thành bài học:

**Monitoring, Logging & Observability**

Trong quá trình học, learner đã lưu lại 6 dấu vết học tập:

1. Highlight về **P95 latency**.
2. Highlight về **Average latency**.
3. Nội dung đánh dấu **“Chưa hiểu” — Percentile**.
4. Câu hỏi: **Tại sao dùng P95 thay vì average latency?**
5. Note: **P95 giúp nhìn thấy tail latency**.
6. Note: **Cần xem lại P50 / P95 / P99**.

### 3.2. Task

> Hãy thử cả ba phương án A/B/C và tạo một bộ ghi chú mà bạn có thể sử dụng để ôn tập sau này.

### 3.3. Desired Outcome

Learner có một bộ ghi chú:

- có cấu trúc;
- dễ hiểu;
- dễ quay lại sử dụng;
- giảm effort khi phải xử lý nhiều nội dung đã lưu.

---

# 4. Feedback — Option A

## 4.1. Phương án

### Option A — Người dùng tự tổ chức ghi chú

Cơ chế:

```text
Learning Traces
      ↓
User tự đọc
      ↓
User tự phân loại
      ↓
Kéo / thả vào các nhóm
      ↓
Save
```

Trong phương án này, AI không tự phân loại hoặc đưa ra suggestion.

Người dùng giữ toàn bộ quyền quyết định.

---

## 4.2. Tester đã làm gì?

Tester quan sát danh sách các nội dung đã lưu và tự quyết định nội dung nào nên nằm trong từng nhóm.

Tester phải thực hiện các bước:

1. Đọc từng learning trace.
2. Hiểu nội dung của trace.
3. Xác định trace thuộc nhóm nào.
4. Kéo/thả trace vào nhóm phù hợp.
5. Kiểm tra lại cấu trúc sau khi sắp xếp.
6. Lưu ghi chú.

Các nhóm mẫu gồm:

- **Khái niệm chính**
- **Cần xem lại**
- **Câu hỏi của tôi**

Tester cũng có khả năng tự tạo thêm nhóm khác nếu cấu trúc mặc định chưa phù hợp.

---

## 4.3. Hành vi đáng chú ý

Ở Option A, tester phải tự suy nghĩ về ý nghĩa của từng learning trace trước khi đưa ra quyết định.

Ví dụ, learner phải tự phân biệt:

- đâu là kiến thức chính cần nhớ;
- đâu là phần mình chưa hiểu;
- đâu là câu hỏi cần quay lại xử lý;
- đâu là nội dung cần xem lại sau.

Điều này cho thấy Option A tạo mức độ kiểm soát rất cao cho learner.

Tuy nhiên, toàn bộ cognitive effort vẫn nằm ở phía người dùng.

---

## 4.4. Friction

Friction chính của Option A là:

> Người dùng vẫn phải tự thực hiện gần như toàn bộ việc đọc, phân loại và sắp xếp nội dung.

Khi chỉ có một số ít note, cách này vẫn tương đối dễ sử dụng.

Tuy nhiên, nếu learner có nhiều:

- highlight;
- note;
- câu hỏi;
- nội dung chưa hiểu;

thì việc xử lý thủ công từng nội dung có thể trở nên mất thời gian.

Pain point ban đầu vì vậy chưa được giải quyết hoàn toàn, bởi learner vẫn phải dành effort để biến các note rời rạc thành một cấu trúc có thể sử dụng lại.

---

## 4.5. Điểm tích cực

Option A giúp tester:

- biết chính xác nội dung nào được đưa vào đâu;
- tự xây dựng cấu trúc phù hợp với cách học của mình;
- không phụ thuộc vào AI;
- dễ phát hiện lỗi vì mọi quyết định đều do chính learner thực hiện.

Tester giữ quyền kiểm soát gần như tuyệt đối đối với output cuối.

---

## 4.6. Trade-off

### Ưu điểm

- User control rất cao.
- Không có nguy cơ AI tự phân loại sai.
- Cấu trúc phản ánh trực tiếp cách learner muốn tổ chức.
- Dễ hiểu vì không có AI inference.
- Người dùng biết rõ tại sao từng nội dung nằm trong từng nhóm.

### Hạn chế

- Tốn nhiều thao tác.
- Learner phải tự đọc và tự phân loại từng nội dung.
- Có thể trở nên mệt nếu số lượng note lớn.
- Chưa giải quyết mạnh pain point về effort khi tổ chức lại note.

---

# 5. Feedback — Option B

## 5.1. Phương án

### Option B — AI hướng dẫn tổ chức ghi chú

Cơ chế:

```text
Learning Trace
      ↓
AI đọc nội dung
      ↓
AI đề xuất một nhóm
      ↓
AI giải thích lý do
      ↓
User Confirm / Correct / Skip
      ↓
Cấu trúc được tạo dần
```

AI không tự áp dụng quyết định.

Người dùng vẫn giữ quyền quyết định cuối cùng.

---

## 5.2. Tester đã làm gì?

Tester lần lượt xem các learning traces.

Ở mỗi trace, tester nhìn thấy:

- nội dung gốc;
- loại learning trace;
- cách AI đang diễn giải nội dung;
- nhóm mà AI đề xuất;
- lý do AI đề xuất nhóm đó;
- uncertainty nếu AI không chắc.

Sau đó tester có thể:

- xác nhận đề xuất của AI;
- chọn một nhóm khác;
- tạo một nhóm mới;
- bỏ qua learning trace;
- quay lại sửa quyết định trước đó.

---

## 5.3. Hành vi đáng chú ý

Khác với Option A, tester không phải bắt đầu hoàn toàn từ đầu.

AI cung cấp một suggestion trước:

```text
AI suggestion
      ↓
User review
      ↓
Confirm / Correct
```

Điều này làm giảm cognitive effort của learner.

Thay vì phải tự hỏi:

> “Nội dung này nên nằm ở đâu?”

learner chỉ cần đánh giá:

> “Đề xuất này của AI có đúng với ý mình không?”

Đây là sự khác biệt quan trọng giữa Option A và Option B.

---

## 5.4. AI Explanation

Một điểm đáng chú ý của Option B là AI không chỉ đưa ra category.

AI còn hiển thị lý do.

Ví dụ:

```text
Learning trace:
Percentile

AI suggestion:
Cần xem lại

Reason:
Bạn đã đánh dấu nội dung này là “Chưa hiểu”.
```

Điều này giúp learner biết AI đang dựa vào tín hiệu nào để đưa ra đề xuất.

Thay vì AI âm thầm phân loại, learner có thể hiểu logic đứng sau suggestion.

---

## 5.5. Uncertainty

Khi AI không đủ chắc chắn, giao diện hiển thị rõ uncertainty.

Ví dụ:

```text
AI chưa chắc chắn:

AI không biết bạn chưa hiểu
định nghĩa percentile
hay chưa hiểu cách áp dụng
percentile vào latency.
```

Thay vì che giấu uncertainty, hệ thống đưa uncertainty ra để learner tự quyết định.

Điều này giúp tăng transparency và giảm nguy cơ learner nghĩ rằng mọi đề xuất của AI đều chắc chắn đúng.

---

## 5.6. Human Control

Option B giữ learner trong vòng quyết định.

AI chỉ:

- đọc;
- diễn giải;
- đề xuất;
- giải thích.

AI không tự thực hiện quyết định cuối cùng.

User có thể:

- giữ nguyên đề xuất;
- sửa đề xuất;
- chọn category khác;
- tạo category mới;
- bỏ qua nội dung.

Do đó, Option B thể hiện rõ cơ chế:

```text
AI ASKS
      ↓
HUMAN DECIDES
```

---

## 5.7. Friction

Option B giảm effort so với Option A nhưng tạo ra một loại friction khác.

Mỗi learning trace đều cần một decision:

```text
AI Suggest
→ User xem
→ User quyết định
→ Confirm
→ Sang trace tiếp theo
```

Với 6 learning traces, quy trình này vẫn tương đối dễ thực hiện.

Tuy nhiên, nếu learner có:

- 30 notes;
- 50 highlights;
- hoặc hàng trăm learning traces;

thì việc review từng trace một có thể trở nên dài.

Vì vậy Option B giảm cognitive effort nhưng chưa loại bỏ hoàn toàn interaction cost.

---

## 5.8. Điểm tích cực

Option B tạo sự cân bằng giữa:

- AI assistance;
- transparency;
- human control.

Learner không cần tự làm toàn bộ như Option A nhưng cũng không phải giao toàn bộ công việc cho AI.

User vẫn có thể:

- sửa AI;
- bỏ qua;
- tạo nhóm mới;
- thay đổi quyết định;
- kiểm tra lý do AI đưa ra suggestion.

---

## 5.9. Trade-off

### Ưu điểm

- Giảm cognitive effort so với Option A.
- AI đưa ra suggestion để learner có điểm bắt đầu.
- AI giải thích lý do.
- Uncertainty được hiển thị.
- Người dùng vẫn quyết định cuối cùng.
- Có thể sửa lại AI khi AI hiểu sai.
- Transparency cao hơn Option C.

### Hạn chế

- User vẫn phải review từng learning trace.
- Có nhiều bước xác nhận.
- Khi dữ liệu lớn, flow có thể trở nên dài.
- Chậm hơn Option C.
- Có thể tạo cảm giác lặp lại nếu AI suggestion phần lớn đều đúng.

---

# 6. Feedback — Option C

## 6.1. Phương án

### Option C — AI tự tạo ghi chú cá nhân

Cơ chế:

```text
Learning Traces
      ↓
User kích hoạt AI
      ↓
AI Collect
→ Group
→ Summarize
→ Generate Draft
      ↓
User Review
      ↓
Edit / Regenerate / Delete / Reject
      ↓
Save
```

Ở Option C, AI thực hiện phần lớn công việc tạo output.

---

## 6.2. Tester đã làm gì?

Tester không cần tự phân loại từng learning trace.

Thay vào đó, tester kích hoạt chức năng tạo ghi chú.

AI sử dụng các learning traces để:

1. Thu thập nội dung.
2. Gom các nội dung liên quan.
3. Tóm tắt nội dung.
4. Tạo các section.
5. Sinh một bản Personal Learning Notes hoàn chỉnh.

Sau đó tester chuyển sang vai trò review.

---

## 6.3. Các thao tác tester có thể thực hiện

Sau khi AI tạo draft, tester có thể:

- đọc nội dung;
- xem source;
- chỉnh sửa nội dung;
- yêu cầu AI tạo lại một section;
- xóa section;
- từ chối toàn bộ draft;
- lưu kết quả.

Điều này cho phép learner không cần trực tiếp tạo cấu trúc nhưng vẫn có đường kiểm soát khi output của AI chưa phù hợp.

---

## 6.4. Hành vi đáng chú ý

Vai trò của learner thay đổi rõ rệt so với A và B.

### Option A

```text
User creates
```

### Option B

```text
User + AI co-create
```

### Option C

```text
AI creates
→ User reviews
```

Ở Option C, learner không còn là người trực tiếp xây dựng cấu trúc.

Learner trở thành người kiểm tra output mà AI đã tạo.

Đây là sự thay đổi lớn nhất về phân chia công việc giữa human và AI trong ba prototype.

---

## 6.5. Friction

Option C giảm rất nhiều thao tác nhưng tạo ra một rủi ro khác:

> Learner phải tin rằng AI đã hiểu đúng các learning traces.

AI thực hiện:

- inference;
- grouping;
- summarization;
- generation.

Nếu AI hiểu sai mục đích của một highlight hoặc note, output có thể không phản ánh đúng ý learner.

Ngoài ra, nếu user quá tin AI và không đọc lại nội dung, learner có thể chấp nhận một output chưa phù hợp.

---

## 6.6. Evidence

Để giúp learner hiểu AI đã dựa vào đâu, mỗi section có thể hiển thị source.

Ví dụ:

```text
Section:
Cần xem lại — Percentile

Dựa trên:
- Nội dung đánh dấu “Chưa hiểu”
- Note: Cần xem lại P50 / P95 / P99
```

Điều này giúp learner kiểm tra xem AI có đang sử dụng đúng dữ liệu hay không.

---

## 6.7. Uncertainty

Nếu AI không chắc chắn về một nội dung, hệ thống có thể hiển thị cảnh báo.

Ví dụ:

```text
AI chưa chắc chắn:

AI chưa biết bạn đang thiếu
định nghĩa percentile
hay cách áp dụng percentile.
```

Uncertainty giúp learner biết phần nào nên được review kỹ hơn.

---

## 6.8. Control & Recovery

Để giảm rủi ro AI sai, Option C cung cấp các cơ chế recovery.

### Xem nguồn

User có thể kiểm tra section được tạo từ learning trace nào.

### Sửa

User có thể tự sửa nội dung AI tạo.

### Tạo lại

User yêu cầu AI tạo một phiên bản khác.

### Xóa

User loại bỏ section không cần thiết.

### Từ chối bản nháp

Nếu toàn bộ output không phù hợp, learner có thể bỏ toàn bộ draft.

---

## 6.9. Điểm tích cực

Option C yêu cầu ít thao tác nhất.

Thay vì:

```text
Đọc từng trace
→ Phân loại
→ Sắp xếp
→ Tạo cấu trúc
```

learner chỉ cần:

```text
Tạo ghi chú
→ Kiểm tra
→ Lưu
```

Điều này đặc biệt hữu ích nếu learner có nhiều nội dung đã lưu.

---

## 6.10. Trade-off

### Ưu điểm

- Tốc độ hoàn thành nhanh.
- Effort của learner thấp.
- AI xử lý được nhiều learning traces cùng lúc.
- Có ngay một bản draft có cấu trúc.
- Phù hợp khi learner có nhiều note.
- Giảm đáng kể thao tác phân loại thủ công.

### Hạn chế

- AI inference cao.
- User control chủ yếu xuất hiện sau khi AI đã tạo output.
- User cần review kỹ.
- Có nguy cơ learner chấp nhận output AI mà không kiểm tra.
- Cần source và uncertainty rõ ràng để tăng trust.

---

# 7. So sánh A/B/C

| Tiêu chí                                 | Option A             | Option B               | Option C                            |
| ------------------------------------------ | -------------------- | ---------------------- | ----------------------------------- |
| Người thực hiện phần lớn công việc | User                 | User + AI              | AI                                  |
| Mức AI tham gia                           | Rất thấp           | Trung bình            | Cao                                 |
| Effort của user                           | Cao                  | Trung bình            | Thấp                               |
| User control                               | Rất cao             | Cao                    | Chủ yếu ở bước review          |
| Số quyết định user phải làm          | Nhiều               | Trung bình / nhiều   | Ít                                 |
| Tốc độ hoàn thành                     | Chậm hơn           | Trung bình            | Nhanh nhất                         |
| AI explanation                             | Không cần          | Rất quan trọng       | Quan trọng ở source / uncertainty |
| Rủi ro AI sai                             | Gần như không có | Có nhưng dễ sửa    | Cao hơn nếu user không review    |
| Recovery                                   | Undo / Reset         | Correct / Skip / Reset | Edit / Regenerate / Delete / Reject |
| Vai trò của user                         | Creator              | Co-creator             | Reviewer                            |
| Vai trò của AI                           | Không hành động  | Advisor                | Generator                           |

---

# 8. Pattern quan sát được

Ba phương án thể hiện ba cách phân chia công việc khác nhau giữa learner và AI:

```text
OPTION A
USER LÀM NHIỀU NHẤT

Control cao
Effort cao
        ↓

OPTION B
USER + AI CÙNG LÀM

Control cao
Effort trung bình
        ↓

OPTION C
AI LÀM NHIỀU NHẤT

Automation cao
Effort thấp
```

Điểm cần so sánh không chỉ là giao diện nào đẹp hoặc dễ thao tác hơn.

Điều quan trọng hơn là:

> Learner muốn tự tổ chức đến mức nào và sẵn sàng giao bao nhiêu công việc cho AI.

---

# 9. Preference và Trade-off

Qua quá trình trải nghiệm cả ba phương án, có thể thấy việc sử dụng AI giúp giảm đáng kể số thao tác mà learner phải thực hiện.

Option A cho learner mức kiểm soát cao nhất nhưng cũng yêu cầu nhiều effort nhất.

Option B giảm effort bằng cách đưa ra suggestion, đồng thời vẫn giữ learner trong vòng quyết định.

Option C giảm effort mạnh nhất vì AI tạo gần như toàn bộ output.

Trade-off chính giữa ba phương án là:

> **Tốc độ và tiện lợi ↔ Quyền kiểm soát và mức độ tin tưởng vào AI.**

Có thể biểu diễn như sau:

```text
A
Control cao
Automation thấp
        ↓

B
Cân bằng Control + Automation
        ↓

C
Automation cao
Effort thấp
```

---

# 10. Observation quan trọng nhất

Observation quan trọng nhất của phiên test là:

> Learner không nhất thiết muốn tự tổ chức mọi learning trace, nhưng cũng không nên để AI âm thầm quyết định toàn bộ mà không cho learner khả năng hiểu, kiểm tra và sửa lại kết quả.

Điều này cho thấy một solution phù hợp cần cân bằng ba yếu tố:

```text
Automation
+
Transparency
+
Human Control
```

AI nên giúp giảm effort của learner nhưng vẫn phải để learner:

- hiểu AI đang làm gì;
- biết AI dựa vào dữ liệu nào;
- sửa AI khi cần;
- khôi phục khi AI làm sai.

---

# 11. Next Change

Từ phiên test, iteration tiếp theo nên kết hợp điểm mạnh của Option B và Option C.

## 11.1. Thay đổi đề xuất

> AI tự tạo một bản notes draft trước như Option C, nhưng chỉ yêu cầu learner review những phần AI không chắc chắn hoặc có khả năng sai.

Flow đề xuất:

```text
Learning Traces
      ↓
AI tự tạo Notes Draft
      ↓
AI xác định các phần uncertainty
      ↓
User chỉ review phần cần chú ý
      ↓
Edit / Regenerate / Accept
      ↓
Save
```

---

## 11.2. Lý do

Option B có human control tốt nhưng yêu cầu learner xác nhận nhiều bước.

Option C nhanh hơn nhưng có nguy cơ learner quá phụ thuộc vào AI.

Iteration tiếp theo có thể:

- giữ tốc độ của Option C;
- giữ transparency của Option B;
- chỉ đưa human vào những decision quan trọng.

---

## 11.3. Cách hoạt động dự kiến

AI sẽ:

1. Tự gom learning traces.
2. Tự tạo bản ghi chú.
3. Hiển thị source cho mỗi section.
4. Tự đánh dấu các section AI không chắc chắn.
5. Không yêu cầu learner review từng trace nếu AI có mức chắc chắn cao.

Learner sẽ:

1. Không phải review tất cả từng trace.
2. Chỉ review các phần cần attention.
3. Có thể sửa.
4. Có thể tạo lại.
5. Có thể từ chối.
6. Có quyền quyết định trước khi lưu.

---

## 11.4. Mục tiêu của Next Change

Mục tiêu là giảm:

- số thao tác;
- số lần xác nhận;
- cognitive effort;

nhưng vẫn giữ:

- transparency;
- evidence;
- uncertainty;
- human control.

---

# 12. Điều vẫn chưa được chứng minh

Phiên test này chỉ cung cấp feedback ban đầu cho iteration tiếp theo.

Phiên test **không chứng minh solution đã được validated**.

Những điều vẫn chưa được chứng minh gồm:

- Learner có thực sự quay lại sử dụng các notes này sau vài ngày hoặc vài tuần hay không.
- Việc tổ chức note có làm learner hiểu bài hoặc nhớ bài tốt hơn hay không.
- AI thật có phân loại chính xác như canned output trong prototype hay không.
- AI thật có tóm tắt đúng ý learner hay không.
- User có thực sự kiểm tra output AI khi số lượng note lớn hay không.
- User có bỏ qua uncertainty vì muốn hoàn thành nhanh hay không.
- Option nào phù hợp nhất với nhiều loại learner khác nhau.
- Việc sử dụng hệ thống thường xuyên có thực sự giảm thời gian ôn tập hay không.
- Learner có hình thành thói quen quay lại sử dụng notes được tạo hay không.
- Mức độ automation nào tạo cảm giác phù hợp nhất cho learner.
- Learner có tin vào AI explanation và source hay không.

---

# 13. Feedback Summary

## 13.1. Option A — Người dùng tự tổ chức

**Điểm chính:**

> Control cao nhưng learner phải tự làm nhiều.

**Phù hợp khi:**

- user muốn kiểm soát hoàn toàn;
- số lượng note chưa nhiều;
- user không muốn AI inference.

**Rủi ro chính:**

- effort cao;
- mất thời gian;
- dễ trì hoãn việc tổ chức note.

---

## 13.2. Option B — AI hướng dẫn

**Điểm chính:**

> AI hỗ trợ từng quyết định và giải thích lý do, nhưng learner vẫn giữ quyền quyết định cuối cùng.

**Phù hợp khi:**

- learner muốn AI hỗ trợ;
- learner vẫn muốn kiểm soát;
- transparency quan trọng.

**Rủi ro chính:**

- quá nhiều bước xác nhận nếu số lượng trace lớn.

---

## 13.3. Option C — AI tự tạo ghi chú

**Điểm chính:**

> Nhanh và ít effort nhất, nhưng user phải review output của AI cẩn thận hơn.

**Phù hợp khi:**

- learner có nhiều learning traces;
- muốn giảm thao tác;
- sẵn sàng để AI thực hiện phần lớn công việc.

**Rủi ro chính:**

- user quá tin AI;
- không review output;
- AI hiểu sai intent ban đầu của note.

---

# 14. Learning chính của phiên test

Ba prototype cho thấy vấn đề thiết kế quan trọng không đơn giản là:

> “Có nên sử dụng AI hay không?”

Mà là:

> **AI nên tự động đến mức nào trước khi cần người dùng tham gia quyết định?**

Ba phương án tạo thành một spectrum:

```text
A
USER CREATES
      ↓

B
USER + AI CO-CREATE
      ↓

C
AI CREATES
USER REVIEWS
```

Iteration tiếp theo nên tìm một điểm cân bằng giữa:

- giảm effort;
- giữ transparency;
- giữ human control;
- tránh tạo quá nhiều bước xác nhận.

---

# 15. Kết luận phiên test

Phiên test cho thấy cả ba phương án đại diện cho ba cách phân chia công việc khác nhau giữa human và AI.

## Option A

Tối đa hóa quyền kiểm soát nhưng yêu cầu learner thực hiện nhiều thao tác nhất.

```text
User does everything
```

## Option B

Tạo sự cân bằng giữa AI assistance và human control.

```text
AI suggests
→ User decides
```

## Option C

Giảm effort mạnh nhất bằng cách để AI thực hiện phần lớn công việc.

```text
AI creates
→ User reviews
```

Điểm đánh đổi chính giữa ba phương án là:

> **Control ↔ Effort ↔ Automation**

Next Change phù hợp để tiếp tục kiểm thử là:

> **AI tự tạo draft như Option C nhưng sử dụng evidence, uncertainty và targeted review của Option B, để learner chỉ phải can thiệp tại những điểm AI thực sự không chắc chắn.**

Hướng này có khả năng giảm effort mà vẫn giữ được quyền kiểm soát của learner.

---

# 16. Tóm tắt cuối

| Option      | Cách hoạt động                | Điểm mạnh          | Hạn chế                  |
| ----------- | --------------------------------- | --------------------- | -------------------------- |
| **A** | User tự tổ chức                | Control cao           | Effort cao                 |
| **B** | AI đề xuất, User quyết định | Cân bằng AI + Human | Nhiều bước review       |
| **C** | AI tạo, User kiểm tra           | Nhanh, ít effort     | Phụ thuộc vào AI output |

### Next Change

```text
AI Generate Draft
        ↓
Detect Uncertainty
        ↓
Human Reviews Only Important Parts
        ↓
Edit / Regenerate / Accept
        ↓
Save
```
