
# Group Feedback Synthesis

## Track 1 — Day 18 — Multiple Prototypes — Human–AI Design

---

## 1. Thông tin chung

- **Case:** Case B — AI Notes: Personal Learning Notes
- **Số prototype:** 3
- **Prototype:** Option A / Option B / Option C
- **Số phiên test:** 3
- **Mỗi tester trải nghiệm:** Cả ba phương án A/B/C
- **Mục tiêu:** So sánh cách phân chia công việc giữa learner và AI khi tổ chức các learning traces thành ghi chú có thể sử dụng lại.

---

## 2. Hypothesis Problem

> Khi đang học và lưu lại nhiều highlight, note, câu hỏi hoặc nội dung chưa hiểu, learner gặp khó khăn trong việc tổ chức lại các nội dung rời rạc thành một bộ ghi chú có thể sử dụng để ôn tập, vì việc tự phân loại và tổng hợp tốn thời gian và công sức, dẫn đến việc tổng hợp note bị trì hoãn hoặc không được thực hiện.

---

## 3. Ba Solution Options

### Option A — Người dùng tự tổ chức

Người dùng tự:

- đọc learning traces;
- phân loại;
- kéo/thả vào các nhóm;
- tạo hoặc sửa nhóm;
- lưu cấu trúc cuối.

```text
User creates
→ User organizes
→ User saves
```

**Đặc điểm chính:** Control cao nhất nhưng effort cũng cao nhất.

---

### Option B — AI hướng dẫn, người dùng quyết định

AI:

- đọc từng learning trace;
- đề xuất nhóm;
- giải thích lý do;
- hiển thị uncertainty khi cần.

Người dùng:

- xác nhận;
- sửa đề xuất;
- chọn nhóm khác;
- tạo nhóm mới;
- hoặc bỏ qua.

```text
AI suggests
→ AI explains
→ User confirms / corrects
→ Structure is built
```

**Đặc điểm chính:** AI hỗ trợ nhưng quyền quyết định cuối vẫn thuộc learner.

---

### Option C — AI tự tạo ghi chú

AI sử dụng toàn bộ learning traces để:

- gom nhóm;
- tóm tắt;
- tạo một bản ghi chú hoàn chỉnh.

Người dùng chủ yếu:

- kiểm tra;
- xem nguồn;
- sửa;
- tạo lại;
- xóa;
- hoặc từ chối output.

```text
AI generates
→ User reviews
→ Edit / Regenerate / Reject
→ Save
```

**Đặc điểm chính:** Automation cao nhất và effort của learner thấp nhất.

---

# 4. Tổng hợp feedback từ ba phiên test

Qua ba phiên test, nhóm quan sát được sự khác biệt rõ về **effort, control và mức độ AI tham gia** giữa ba phương án.

| Tiêu chí             | Option A             | Option B            | Option C                         |
| ---------------------- | -------------------- | ------------------- | -------------------------------- |
| AI tham gia            | Rất thấp           | Trung bình         | Cao                              |
| Effort của learner    | Cao                  | Trung bình         | Thấp                            |
| Human control          | Rất cao             | Cao                 | Chủ yếu ở bước review       |
| Tốc độ hoàn thành | Chậm hơn           | Trung bình         | Nhanh nhất                      |
| AI explanation         | Không cần          | Rõ ràng           | Chủ yếu qua source/uncertainty |
| Số thao tác          | Nhiều               | Trung bình/nhiều  | Ít                              |
| Rủi ro AI sai         | Gần như không có | Có nhưng dễ sửa | Cao hơn nếu user không review |

---

# 5. Pattern chung

## Pattern 1 — Learner không muốn tự làm quá nhiều thao tác

Option A cho learner quyền kiểm soát cao nhưng yêu cầu người dùng:

- đọc từng trace;
- tự hiểu;
- tự phân loại;
- tự tổ chức.

Khi số lượng learning traces tăng, lượng effort này cũng tăng theo.

**Learning:**

> Chỉ gom note về một chỗ chưa đủ; solution cần giảm effort tổ chức lại nội dung.

---

## Pattern 2 — AI suggestion hữu ích khi user vẫn có quyền sửa

Option B giảm effort bằng cách đưa ra một phương án trước.

Thay vì learner phải tự nghĩ:

> “Nội dung này thuộc nhóm nào?”

learner chỉ cần kiểm tra:

> “Đề xuất của AI có đúng với ý mình không?”

Việc có:

- lý do;
- uncertainty;
- khả năng Correct;
- khả năng Skip;

giúp learner vẫn giữ control.

**Learning:**

> AI có thể hỗ trợ quyết định, nhưng learner cần hiểu và sửa được quyết định của AI.

---

## Pattern 3 — Automation giúp nhanh hơn nhưng tạo nhu cầu review

Option C giảm số bước nhiều nhất vì AI tự tạo gần như toàn bộ ghi chú.

Điều này giúp learner chuyển từ:

```text
Create
→ Organize
→ Review
```

sang:

```text
Generate
→ Review
```

Tuy nhiên, khi AI làm nhiều hơn, learner cần kiểm tra:

- AI dựa vào source nào;
- nội dung có đúng ý không;
- AI có hiểu sai note hay không.

**Learning:**

> Automation càng cao thì evidence, uncertainty và recovery càng quan trọng.

---

# 6. Trade-off chính

Ba prototype tạo ra một spectrum:

```text
OPTION A
Control cao
Effort cao
Automation thấp
        ↓

OPTION B
Control cao
Effort trung bình
Automation trung bình
        ↓

OPTION C
Control thấp hơn
Effort thấp
Automation cao
```

Trade-off trung tâm của cả ba phiên test là:

> **Tốc độ và sự tiện lợi ↔ Quyền kiểm soát và mức độ tin tưởng vào AI**

Không có một option hoàn toàn tốt hơn ở mọi tiêu chí.

---

# 7. Group Learning

Learning chính của nhóm là:

> Vấn đề không đơn giản là “có nên dùng AI hay không”, mà là **AI nên tự động đến mức nào trước khi cần learner tham gia quyết định**.

Option A yêu cầu learner làm quá nhiều.

Option B giữ control tốt nhưng nếu có nhiều learning traces thì việc xác nhận từng trace có thể trở nên dài.

Option C giảm effort mạnh nhưng learner có thể phụ thuộc quá nhiều vào output AI nếu không review.

Vì vậy, nhóm không chọn giữ nguyên hoàn toàn một trong ba phương án.

---

# 8. Group Next Change

## Next Change

> **Kết hợp cơ chế tạo draft nhanh của Option C với transparency và human control của Option B.**

Thay vì yêu cầu learner xác nhận từng learning trace, AI sẽ tự tạo một bản notes draft trước.

Sau đó AI chỉ yêu cầu learner chú ý đến:

- phần AI không chắc;
- phần có inference;
- phần có khả năng hiểu sai intent của learner.

Flow mới:

```text
Learning Traces
        ↓
AI tự tạo Notes Draft
        ↓
AI gắn Source + Uncertainty
        ↓
AI đánh dấu phần cần chú ý
        ↓
User review các phần quan trọng
        ↓
Accept / Edit / Regenerate / Reject
        ↓
Save
```

---

## 9. Điều giữ lại từ mỗi Option

### Từ Option A

Giữ:

- quyền chỉnh sửa của learner;
- khả năng thay đổi cấu trúc;
- khả năng khôi phục khi kết quả không phù hợp.

Không giữ:

- việc bắt learner tự phân loại toàn bộ nội dung.

---

### Từ Option B

Giữ:

- AI explanation;
- evidence;
- uncertainty;
- user correction;
- human control.

Không giữ:

- việc bắt user Confirm từng learning trace một.

---

### Từ Option C

Giữ:

- AI tự gom nhóm;
- AI tự tóm tắt;
- AI tạo draft nhanh;
- giảm effort của learner.

Không giữ:

- việc để AI output xuất hiện mà không làm nổi bật những phần cần review.

---

# 10. Lý do chọn Next Change

Next Change không được chọn chỉ vì một option được thích hơn.

Nhóm chọn thay đổi này vì ba prototype cho thấy hai nhu cầu cùng tồn tại:

1. Learner muốn giảm effort khi tổ chức nhiều learning traces.
2. Learner vẫn cần hiểu và kiểm soát những phần AI có thể làm sai.

Do đó, iteration tiếp theo cần:

> **Automation ở những phần AI có thể xử lý tốt, Human Review ở những phần có uncertainty hoặc hậu quả khi sai.**

---

# 11. Still Unproven

Ba phiên test đầu tiên **không đủ để tuyên bố solution đã được validated**.

Nhóm vẫn chưa chứng minh được:

- learner có thực sự quay lại sử dụng notes sau vài ngày hoặc vài tuần hay không;
- notes được tổ chức có giúp learner nhớ hoặc hiểu bài tốt hơn hay không;
- AI thật có phân loại chính xác như canned output trong prototype hay không;
- learner có đọc lại AI-generated notes khi có nhiều nội dung hay không;
- user có bỏ qua uncertainty vì muốn hoàn thành nhanh hay không;
- mức automation nào phù hợp với nhiều loại learner khác nhau;
- solution có thực sự giảm thời gian ôn tập trong sử dụng dài hạn hay không.

---

# 12. Kết luận

Ba prototype đại diện cho ba cách chia công việc giữa human và AI:

```text
OPTION A
USER CREATES
        ↓

OPTION B
USER + AI CO-CREATE
        ↓

OPTION C
AI CREATES
USER REVIEWS
```

Qua ba phiên test, nhóm không xem một option là solution đã được validated.

Feedback được sử dụng để chọn **iteration tiếp theo**:

> **AI tự tạo notes draft để giảm effort, nhưng phải hiển thị source và uncertainty, đồng thời cho learner quyền kiểm tra, sửa, tạo lại hoặc từ chối trước khi lưu.**
