
# Three-Option Design Sheet

## Track 1 — Day 18 — Multiple Prototypes — Human–AI Design

### Case

**Case B — AI Notes: Personal Learning Notes**

### Thành viên nhóm

| STT | Họ và tên    | MHV         |
| --- | --------------- | ----------- |
| 1   | Vũ Huy Hoàng  | 2A202601057 |
| 2   | Tạ Thị Nga    | 2A202601125 |
| 3   | Trần Hoài Nam | 2A202601751 |

---

# 1. Hypothesis Problem

> **Khi kết thúc một bài học và muốn sử dụng lại những nội dung đã ghi chú hoặc highlight để phục vụ việc ôn tập, learner có thể gặp khó khăn trong việc tổng hợp chúng vì các dấu vết học tập nằm rải rác ở nhiều trang, video, tài liệu hoặc công cụ khác nhau, dẫn đến mất thêm thời gian, trì hoãn hoặc bỏ qua việc tạo tài liệu ôn tập có cấu trúc.**

## Cấu trúc

| Thành phần          | Nội dung                                                                  |
| --------------------- | -------------------------------------------------------------------------- |
| **User**        | Learner / Học viên                                                       |
| **Situation**   | Khi kết thúc bài học và muốn sử dụng lại các nội dung đã lưu |
| **Job**         | Tập hợp, tổ chức và sử dụng lại note/highlight để ôn tập       |
| **Barrier**     | Learning traces nằm rải rác ở nhiều trang, tài liệu hoặc công cụ |
| **Consequence** | Mất thêm thời gian, trì hoãn hoặc bỏ qua việc tổng hợp           |

---

# 2. Evidence Snapshot

| Practice Note             | Observation chính                                                                                                                                                                                                                             | Interpretation                                                                                                                                                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Vũ Huy Hoàng**  | Hai lượt practice ghi nhận learner khi gặp phần chưa hiểu đã đọc lại bài, xem ví dụ/code, Google và ChatGPT. P01 mất khoảng 15–20 phút, P02 khoảng 20 phút. Hai lượt này không ghi nhận trực tiếp highlight/note. | Giúp nhóm phát hiện Conversation Guide ban đầu lệch sang bài toán “không hiểu bài”, từ đó điều chỉnh hướng hỏi về purpose, reuse, friction và consequence của highlight/note. |
| **Trần Hoài Nam** | Learner ghi note, chụp slide và highlight PDF. Khi ôn tập, nội dung nằm rải rác ở điện thoại, Notion và PDF; có lúc bỏ việc tổng hợp và phải mượn note người khác.                                                   | Hỗ trợ mạnh giả thuyết rằng learning traces phân tán tạo thêm effort và có consequence thực tế.                                                                                           |
| **Tạ Thị Nga**    | User ban đầu nói có quay lại xem note nhưng khi hỏi lần gần nhất thì cho biết chưa thực sự quay lại. Việc tổng hợp note có thể mất khoảng 30–45 phút.                                                                 | Cho thấy khoảng cách giữa ý định reuse và hành vi reuse thực tế; effort tổng hợp có thể là một friction đáng kể.                                                                    |

## Pattern chung

```text
Learner lưu note / highlight / screenshot
        ↓
Learning traces nằm ở nhiều nơi
        ↓
Khi muốn ôn tập phải tìm và gom lại
        ↓
Tốn thêm effort và thời gian
        ↓
Có trường hợp trì hoãn hoặc bỏ qua việc tổng hợp
```

---

# 3. Shared Comparison Contract

Ba option A/B/C phải giữ cùng một context để việc so sánh có ý nghĩa.

| Thành phần                   | Quyết định chung cho A/B/C                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------ |
| **Target User**          | Learner / Học viên                                                                       |
| **Situation**            | Learner vừa hoàn thành một bài học và muốn sử dụng lại các nội dung đã lưu |
| **Task**                 | Tạo một bộ ghi chú từ learning traces để phục vụ ôn tập                         |
| **Desired Outcome**      | Learner có thể tìm, tổ chức và sử dụng lại nội dung với ít effort hơn         |
| **Content/Data Fixture** | Cùng một bài học và cùng 6 learning traces                                           |
| **Visual Style**         | Cùng component, card, badge và cách trình bày                                         |

## Shared Content Fixture

**Bài học:** Monitoring, Logging & Observability

Các learning traces:

1. **Highlight:** P95 latency represents the latency threshold under which 95% of requests complete.
2. **Highlight:** Average latency can hide a small number of very slow requests.
3. **Chưa hiểu:** Percentile.
4. **Question:** Tại sao dùng P95 thay vì chỉ dùng average latency?
5. **Note:** P95 giúp nhìn thấy tail latency.
6. **Note:** Cần xem lại sự khác nhau giữa P50, P95 và P99.

---

# 4. Three Solution Options

| Thành phần                 | Option A — User-led Organized Notes                    | Option B — AI-assisted Note Organizer                 | Option C — AI-generated Personal Notes          |
| ---------------------------- | ------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------ |
| **Solution Mechanism** | User tự tập hợp và tổ chức learning traces        | AI hỗ trợ phân loại và đề xuất cách tổ chức | AI tự tạo một Personal Learning Notes draft   |
| **User làm gì?**     | Chọn, kéo/thả, nhóm, đổi tên, sắp xếp và lưu | Chọn traces, review đề xuất, Accept/Edit/Reject    | Trigger Generate, review, edit/regenerate/reject |
| **AI làm gì?**       | Không suy luận, không tự tạo nội dung             | Phân loại, gom nhóm, đề xuất cấu trúc          | Collect, group, summarize và generate draft     |
| **Trigger**            | User chủ động mở và tổ chức note                 | User chọn**Organize with AI**                   | User chọn**Generate My Notes**            |
| **AI Mode**            | **Don't Act**                                     | **Ask**                                          | **Act after trigger**                      |
| **Trade-off chính**   | Control cao nhưng effort cao                           | Cân bằng control và effort                          | Effort thấp hơn nhưng AI inference cao hơn   |

---

# 5. Option A — User-led Organized Notes

## Solution Hypothesis

> Learner tự tập hợp và tổ chức learning traces trong một không gian thống nhất mà không để AI tự suy luận hoặc tạo nội dung.

## Critical Interaction

```text
Original Learning Traces
        ↓
User Drag & Drop / Organize
        ↓
Structured Notes
        ↓
Save / Undo / Reset
```

## User Control

* Drag & Drop
* Add Section
* Rename Section
* Delete Section
* Move Trace
* Remove Trace
* Undo
* Reset
* Save Notes

## Recovery

> **Undo / Reset → Original Learning Traces**

---

# 6. Option B — AI-assisted Note Organizer

## Solution Hypothesis

> Learner chọn nội dung muốn sử dụng lại; AI phân loại, gom nhóm và đề xuất cấu trúc; learner quyết định có sử dụng đề xuất hay không.

## Critical Interaction

```text
Selected Learning Traces
        ↓
Organize with AI
        ↓
AI Suggested Structure
        ↓
Accept / Edit / Reject
```

## User Control

* View Sources
* Accept
* Edit
* Reject
* Undo AI Organization
* Reset

## Recovery

> **Reject / Undo AI Organization → Original Learning Traces**

---

# 7. Option C — AI-generated Personal Notes

## Solution Hypothesis

> AI sử dụng learning traces để tạo một bản Personal Learning Notes có cấu trúc; learner review và quyết định trước khi lưu.

## Critical Interaction

```text
Learning Traces
        ↓
Generate My Notes
        ↓
AI-generated Draft
        ↓
Review / Edit / Regenerate / Reject
```

## User Control

* View Sources
* Edit
* Regenerate
* Reject Draft
* Save Notes
* Reset

## Recovery

> **Reject Draft → Original Learning Traces**

---

# 8. Distance Check

### A khác B vì

> **Option A để learner tự tổ chức toàn bộ nội dung, trong khi Option B sử dụng AI để đề xuất cách phân loại và gom nhóm nhưng learner vẫn quyết định bản cuối.**

### B khác C vì

> **Option B chỉ để AI hỗ trợ tổ chức các learning traces learner chọn, trong khi Option C để AI tạo một bản Personal Learning Notes hoàn chỉnh dạng draft.**

### A khác C vì

> **Option A gần như không có AI inference, trong khi Option C để AI thực hiện phần lớn quá trình tổng hợp và tạo output.**

---

# 9. Human–AI Decision Table

| Human–AI Decision                    | Option A                                    | Option B                                                                        | Option C                                              |
| ------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **User làm gì? AI làm gì?** | User tự tổ chức; AI không tự suy luận | User chọn/review; AI đề xuất                                                | AI tạo draft; user review và quyết định          |
| **AI Act / Ask / Don't Act?**   | **Don't Act**                         | **Ask**                                                                   | **Act after trigger**                           |
| **Capability / Limit**          | Chỉ hỗ trợ hiển thị nội dung gốc     | AI có thể nhóm sai hoặc hiểu sai một note                                 | AI có thể bỏ sót hoặc tóm tắt sai              |
| **Evidence / Uncertainty**      | Hiển thị original trace và source        | Hiển thị source cho từng suggestion; đánh dấu “Cần kiểm tra” khi cần | Hiển thị source, nhãn AI-generated và uncertainty |
| **Control / Recovery**          | Move / Edit / Undo / Reset                  | Accept / Edit / Reject / Undo                                                   | Edit / Regenerate / Reject / Reset                    |

---

# 10. Human–AI Agency Spectrum

```text
OPTION A
USER CREATES / ORGANIZES
AI DON'T ACT
        ↓

OPTION B
USER + AI CO-CREATE
AI ASK
        ↓

OPTION C
AI CREATES DRAFT
USER REVIEWS
AI ACT AFTER TRIGGER
```

---

# 11. Gate Check

## GATE 1 — Evidence Continuity

**Đạt**

* Hypothesis Problem nối tiếp Day 17.
* Có User, Situation, Job, Barrier và Consequence.
* Có observation thực tế từ Practice Notes.

## GATE 2 — Meaningful Options

**Đạt**

A/B/C:

* cùng problem;
* cùng user;
* cùng situation;
* cùng task;
* cùng desired outcome;
* khác solution mechanism;
* khác cách phân chia Human–AI work.

## GATE 3 — Human Control

**Đạt**

Mỗi option có:

* user role;
* AI role;
* AI Act / Ask / Don't Act;
* capability / limit;
* evidence / uncertainty;
* control;
* recovery.

---

# 12. Three Options cuối cùng

## Option A — User-led Organized Notes

> **Learner tự tập hợp và tổ chức learning traces. AI không tự suy luận hoặc tạo nội dung.**

## Option B — AI-assisted Note Organizer

> **Learner chọn nội dung; AI phân loại, gom nhóm và đề xuất cấu trúc; learner review và quyết định.**

## Option C — AI-generated Personal Notes

> **AI tạo một Personal Learning Notes draft từ learning traces; learner review, chỉnh sửa và quyết định trước khi lưu.**
