
# Track 1 — Day 18 — Multiple Prototypes — Human–AI Design

## README — Tiến độ đến Chặng 4

> **Phạm vi hiện tại:** Hoàn thành nội dung từ **Chặng 1 đến Chặng 4** của Day 18.
> Chưa thực hiện phần test với người dùng, Prototype Feedback, Group Feedback Synthesis và Next Change.

---

# 1. Thông tin cá nhân và nhóm

* **Họ và tên:** Vũ Huy Hoàng
* **MHV:** 2A202601057
* **Case:** Case B — AI Notes: Personal Learning Notes
* **Actor chính:** Learner / Học viên

## Thành viên nhóm

| STT | Họ và tên    | MHV         |
| --- | --------------- | ----------- |
| 1   | Vũ Huy Hoàng  | 2A202601057 |
| 2   | Tạ Thị Nga    | 2A202601125 |
| 3   | Trần Hoài Nam | 2A202601751 |

---

# 2. Hypothesis Problem

Nhóm tiếp tục sử dụng Hypothesis Problem đã chốt từ Day 17:

> **Khi kết thúc một bài học và muốn sử dụng lại những nội dung đã ghi chú hoặc highlight để phục vụ việc ôn tập, learner có thể gặp khó khăn trong việc tổng hợp chúng vì các dấu vết học tập nằm rải rác ở nhiều trang, video, tài liệu hoặc công cụ khác nhau, dẫn đến mất thêm thời gian, trì hoãn hoặc bỏ qua việc tạo tài liệu ôn tập có cấu trúc.**

## Phân rã Hypothesis Problem

| Thành phần          | Nội dung                                                                                             |
| --------------------- | ----------------------------------------------------------------------------------------------------- |
| **User**        | Learner / Học viên                                                                                  |
| **Situation**   | Khi kết thúc một bài học và muốn sử dụng lại các nội dung đã ghi chú hoặc highlight   |
| **Job**         | Tập hợp, tổ chức và sử dụng lại các nội dung đã lưu để phục vụ việc ôn tập        |
| **Barrier**     | Các dấu vết học tập nằm rải rác ở nhiều trang, video, tài liệu hoặc công cụ khác nhau |
| **Consequence** | Mất thêm thời gian, trì hoãn hoặc bỏ qua việc tạo tài liệu ôn tập có cấu trúc         |

---

# 3. Evidence Continuity từ Day 17

## 3.1. Practice Note — Vũ Huy Hoàng

Hai lượt practice interview ghi nhận learner khi gặp phần chưa hiểu đã:

* đọc lại nội dung bài;
* xem ví dụ hoặc code;
* tìm Google;
* hỏi ChatGPT;
* quay lại bài sau khi xác định rõ điểm vướng.

P01 mất khoảng **15–20 phút**, P02 mất khoảng **20 phút**.

Hai lượt practice này giúp phát hiện Conversation Guide ban đầu đang nghiêng sang bài toán:

> “Learner xử lý thế nào khi không hiểu bài?”

thay vì tập trung đúng Case B:

> “Learner highlight/note với mục đích gì, có quay lại sử dụng không và việc tìm/gom note tạo friction như thế nào?”

Từ đó hướng phỏng vấn được điều chỉnh để tập trung vào:

* mục đích highlight/note;
* hành vi quay lại sử dụng;
* friction khi tìm/gom note;
* consequence thực tế.

---

## 3.2. Practice Note — Trần Hoài Nam

Learner có các hành vi thực tế:

* ghi nhanh ý chính;
* chụp màn hình slide;
* highlight trên PDF;
* ghi note trong Notion.

Khi cần ôn tập, các nội dung đã lưu nằm rải rác ở:

* điện thoại;
* Notion;
* PDF.

Khi mở lại một số đoạn đã highlight, learner không nhớ rõ vì sao lúc đó mình đánh dấu.

Với bài dài, learner có lúc bỏ qua việc tổng hợp và đến gần kỳ thi phải mượn note của người khác để học.

Evidence này hỗ trợ mạnh cho barrier của Hypothesis Problem:

> **Learning traces bị phân tán và tạo thêm effort khi cần sử dụng lại.**

---

## 3.3. Practice Note — Tạ Thị Nga

User ban đầu nói rằng mình:

> “Có quay lại xem.”

Tuy nhiên, khi được hỏi cụ thể:

> “Lần gần nhất là khi nào?”

user cho biết thực tế chưa từng quay lại xem.

User đồng thời cho biết việc tổng hợp note có thể mất khoảng:

> **30–45 phút.**

Evidence này cho thấy có khoảng cách giữa:

```text
Ý định sử dụng lại note
        ↓
Hành vi sử dụng lại thực tế
```

và effort của việc tổng hợp có thể tạo ra friction đáng kể.

---

## 3.4. Evidence Snapshot tổng hợp

```text
Learner tạo note / highlight / screenshot trong lúc học
        ↓
Learning traces nằm ở nhiều vị trí hoặc công cụ
        ↓
Khi muốn ôn tập phải tìm và tập hợp lại
        ↓
Tạo thêm effort và thời gian
        ↓
Có trường hợp trì hoãn hoặc bỏ qua việc tổng hợp
```

---

# 4. Three Solution Options

Ba option cùng giải quyết một Hypothesis Problem, cùng user, situation, task và desired outcome nhưng khác nhau về:

* solution mechanism;
* mức độ AI tham gia;
* quyền quyết định của learner.

---

## 4.1. Option A — User-led Organized Notes

> Learner tự chọn, tập hợp và tổ chức note/highlight trong một không gian thống nhất bằng section hoặc tag. AI không tự suy luận, không tự phân loại và không tạo nội dung mới.

### Cơ chế

```text
USER
Select
→ Organize
→ Tag / Group
→ Save

AI
→ Don't Act
```

### Mục tiêu

Kiểm tra liệu việc gom learning traces về cùng một nơi và trao toàn bộ quyền tổ chức cho learner có đủ giảm friction hay không.

### Trade-off

**Ưu điểm:**

* learner kiểm soát toàn bộ;
* ít nguy cơ AI hiểu sai;
* nội dung gốc được giữ nguyên.

**Đánh đổi:**

* learner vẫn phải tự bỏ effort để tổ chức;
* quá trình tổng hợp vẫn cần thao tác thủ công.

---

## 4.2. Option B — AI-assisted Note Organizer

> Learner chọn những nội dung muốn sử dụng lại; AI hỗ trợ phân loại, gom nhóm và đề xuất cấu trúc; learner review và quyết định bản cuối.

### Cơ chế

```text
USER
Select traces
        ↓
AI
Classify
→ Group
→ Suggest structure
        ↓
USER
Accept / Edit / Reject
→ Save
```

### Mục tiêu

Kiểm tra mô hình:

> **Human + AI Co-create**

AI giúp giảm effort nhưng learner vẫn giữ quyền quyết định.

### Trade-off

**Ưu điểm:**

* giảm effort tổ chức;
* learner vẫn kiểm soát output;
* AI chỉ đề xuất, không tự áp dụng.

**Đánh đổi:**

* AI có thể phân loại sai;
* learner vẫn phải review đề xuất.

---

## 4.3. Option C — AI-generated Personal Notes

> AI sử dụng các highlight, note, câu hỏi và mục “Chưa hiểu” để tạo một bản Personal Learning Notes có cấu trúc; learner review trước khi lưu.

### Cơ chế

```text
USER
Generate My Notes
        ↓
AI
Collect
→ Group
→ Summarize
→ Generate Draft
        ↓
USER
Review
→ Edit / Regenerate / Reject
→ Save
```

### Mục tiêu

Kiểm tra liệu để AI thực hiện phần lớn công việc tổng hợp có thể giảm đáng kể effort của learner hay không.

### Trade-off

**Ưu điểm:**

* giảm effort nhiều nhất;
* tạo nhanh một bản note có cấu trúc.

**Đánh đổi:**

* AI có thể hiểu sai lý do highlight;
* AI có thể bỏ sót nội dung;
* AI có thể tóm tắt khác với ý định learner.

---

# 5. Comparison Contract

## Những thứ giữ nguyên cho A/B/C

| Thành phần                   | Quyết định chung                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------ |
| **Target user**          | Learner / Học viên                                                                       |
| **Situation**            | Learner vừa hoàn thành một bài học và muốn sử dụng lại các nội dung đã lưu |
| **Task**                 | Tạo một bộ ghi chú có thể dùng lại để ôn tập                                   |
| **Desired outcome**      | Giảm effort khi tìm, tập hợp và sử dụng lại learning traces                        |
| **Content/Data Fixture** | Cùng một bài học và cùng bộ learning traces                                         |
| **Visual Style**         | Dùng chung component và cách trình bày                                                |

---

## Những thứ khác nhau

| Thành phần          | Option A                   | Option B                      | Option C                           |
| --------------------- | -------------------------- | ----------------------------- | ---------------------------------- |
| **Mechanism**   | User tự tổ chức         | AI hỗ trợ tổ chức         | AI tự tạo draft                  |
| **AI Mode**     | Don't Act                  | Ask                           | Act sau trigger                    |
| **User Agency** | Rất cao                   | Cao                           | Review và quyết định cuối     |
| **AI Agency**   | Thấp                      | Trung bình                   | Cao                                |
| **Control**     | Move / Edit / Undo / Reset | Accept / Edit / Reject / Undo | Edit / Regenerate / Reject / Reset |

---

## Distance Check

### A khác B vì

> Option A để learner tự tổ chức toàn bộ nội dung, trong khi Option B sử dụng AI để đề xuất cách phân loại và gom nhóm.

### B khác C vì

> Option B chỉ để AI hỗ trợ sau khi learner chọn nội dung, trong khi Option C để AI tạo một bản note hoàn chỉnh rồi learner review.

### A khác C vì

> Option A đặt phần lớn công việc ở learner, trong khi Option C đặt phần lớn công việc tạo output ở AI.

---

# 6. Human–AI Design Decisions

## Human–AI Decision Table

| Human–AI Decision                    | Option A — User-led                                                              | Option B — AI-assisted                                                          | Option C — AI-generated                                             |
| ------------------------------------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| **User làm gì? AI làm gì?** | User tự chọn, nhóm, tag và sắp xếp. AI chỉ hiển thị learning traces gốc | User chọn nội dung; AI phân loại, gom nhóm và đề xuất cấu trúc        | AI tập hợp, phân loại, tóm tắt và tạo draft; user review     |
| **AI Act / Ask / Don't Act?**   | **Don't Act**                                                               | **Ask**                                                                    | **Act** sau trigger rõ ràng                                  |
| **Capability / Limit**          | Không có AI inference                                                           | AI có thể nhóm sai hoặc hiểu sai note                                       | AI có thể bỏ sót, tóm tắt sai hoặc hiểu sai lý do highlight |
| **Evidence / Uncertainty**      | Hiển thị nội dung gốc và source                                              | Hiển thị source của từng đề xuất và đánh dấu nội dung cần kiểm tra | AI-generated content có source và nhãn draft                      |
| **Control / Recovery**          | Move, Edit, Undo, Reset                                                           | Accept, Edit, Reject, Undo AI Organization                                       | Edit, Regenerate, Reject Draft, quay lại original traces            |

---

## Human–AI Agency Spectrum

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
AI CREATES
USER REVIEWS
AI ACT AFTER TRIGGER
```

---

# 7. Shared Context và Content Fixture

## Common Context

Bài học mẫu:

> **Monitoring, Logging & Observability**

Learner vừa hoàn thành bài học và đã lưu:

> **6 learning traces**

---

## Content Fixture

### Highlight 01

> P95 latency represents the latency threshold under which 95% of requests complete.

### Highlight 02

> Average latency can hide a small number of very slow requests.

### “Chưa hiểu”

> Percentile

### Question

> Tại sao dùng P95 thay vì chỉ dùng average latency?

### Note 01

> P95 giúp nhìn thấy tail latency.

### Note 02

> Cần xem lại sự khác nhau giữa P50, P95 và P99.

---

## Task chung

> **Tạo một bộ ghi chú từ các nội dung đã lưu để có thể quay lại sử dụng khi ôn tập.**

---

# 8. Chặng 4 — Build ba Micro-prototype

Mỗi option chỉ tập trung vào critical interaction.

```text
COMMON CONTEXT
      ↓
CRITICAL INTERACTION
      ↓
RESULT / USER DECISION
```

---

## 8.1. Prototype A — User-led Organized Notes

### Critical Interaction

Learner tự kéo/thả và tổ chức các learning traces vào các section.

### Các thao tác

* Drag & Drop
* Add Section
* Rename Section
* Delete Section
* Undo
* Reset
* Save Notes

### Recovery

```text
Organized Notes
      ↓
Undo / Reset
      ↓
Original Learning Traces
```

---

## 8.2. Prototype B — AI-assisted Note Organizer

### Critical Interaction

AI đề xuất cách nhóm learning traces và learner quyết định:

* Accept
* Edit
* Reject

### Các thao tác

* Organize with AI
* View Sources
* Accept
* Edit
* Reject
* Undo AI Organization
* Reset

### Recovery

```text
AI Suggestion
      ↓
Reject / Undo
      ↓
Original Learning Traces
```

---

## 8.3. Prototype C — AI-generated Personal Notes

### Critical Interaction

AI tạo một Personal Learning Notes Draft và learner review trước khi lưu.

### Các thao tác

* Generate My Notes
* View Sources
* Edit
* Regenerate
* Reject Draft
* Save Notes
* Reset

### Recovery

```text
AI-generated Draft
      ↓
Edit / Regenerate / Reject
      ↓
Original Learning Traces
```

---

# 9. Đóng góp của tôi trong nhóm — Vũ Huy Hoàng

## Day 17 — Practice Interview

Tôi thực hiện hai lượt practice interview và ghi lại:

* situation;
* behavior;
* workaround;
* consequence;
* exact quote.

Qua hai lượt practice, tôi phát hiện Conversation Guide ban đầu đang nghiêng về bài toán:

> “Learner xử lý thế nào khi không hiểu bài?”

thay vì đúng Case B:

> “Learner highlight/note với mục đích gì, có quay lại sử dụng không và việc tìm/gom note tạo friction như thế nào?”

Từ đó tôi tham gia điều chỉnh:

* Recruitment Check;
* Story Opener;
* Big 3 Questions;
* hướng thu evidence.

---

## Day 18 — Chặng 1

Tôi tham gia:

* tổng hợp Evidence Huddle;
* phân biệt **Observed** và **Interpreted**;
* giữ Hypothesis Problem nối tiếp từ Day 17;
* xác định evidence nào thực sự hỗ trợ Case B.

---

## Day 18 — Chặng 2

Tôi tham gia chốt ba Solution Options:

* Option A — User-led Organized Notes;
* Option B — AI-assisted Note Organizer;
* Option C — AI-generated Personal Notes.

Tôi cùng nhóm giữ chung:

* user;
* situation;
* task;
* desired outcome;
* content fixture.

---

## Day 18 — Chặng 3

Tôi tham gia xác định Human–AI decisions cho A/B/C:

* Expectation;
* Role and Agency;
* Evidence and Uncertainty;
* Control and Recovery;
* AI Act / Ask / Don't Act.

---

## Day 18 — Chặng 4

Tôi phụ trách chính:

> **Option A — User-led Organized Notes**

Prototype A tập trung vào việc learner:

* tự chọn learning traces;
* kéo/thả nội dung;
* tự tạo cấu trúc;
* thêm section;
* đổi tên section;
* xóa section;
* Undo;
* Reset;
* Save Notes.

Mục tiêu của Option A là tạo một baseline:

> **User Control cao + AI Inference thấp**

để so sánh với Option B và Option C.

---

# 10. Prototype Reference

## Option A — User-led Organized Notes

Source code prototype:

```text
prototype/
└── option-a/
    ├── page.tsx
    └── option-a.module.css
```

Route khi chạy bằng Next.js:

```text
/prototype/option-a
```

---

## Option B — AI-assisted Note Organizer

Prototype B sử dụng cùng:

* Common Context;
* Task;
* Content Fixture.

Critical Interaction:

> AI Suggestion → Accept / Edit / Reject

---

## Option C — AI-generated Personal Notes

Prototype C sử dụng cùng:

* Common Context;
* Task;
* Content Fixture.

Critical Interaction:

> AI-generated Draft → Review / Edit / Regenerate / Reject

---

# 11. AI Support Log — Đến Chặng 4

AI được sử dụng để hỗ trợ:

1. rà soát Hypothesis Problem;
2. tổ chức Evidence Snapshot;
3. phân biệt observation và interpretation;
4. rà soát ba Solution Options;
5. kiểm tra A/B/C có khác nhau về mechanism hay không;
6. xây dựng Human–AI Decision Table;
7. gợi ý Expectation, Agency, Evidence, Uncertainty, Control và Recovery;
8. xây dựng Common Context và Content Fixture;
9. hỗ trợ thiết kế prototype;
10. hỗ trợ code Prototype A bằng TSX/CSS;
11. hỗ trợ tổ chức repository.

---

## Điểm AI từng chưa phù hợp

Trong quá trình hỗ trợ, AI từng:

* diễn giải hai Practice Interview của Vũ Huy Hoàng thành evidence trực tiếp cho Case B mặc dù nội dung interview chủ yếu liên quan tới việc learner chưa hiểu bài;
* viết phần tổng hợp thiên quá nhiều về evidence của hai thành viên còn lại;
* tạo Figma frame tĩnh trong khi mục tiêu cần một prototype có interaction;
* giả định repository đã là một project Next.js khi hướng dẫn chạy prototype.

---

## Cách tôi tự sửa

Tôi đã:

* giữ nguyên evidence thực tế;
* không biến interview thành evidence không tồn tại;
* giữ đúng Hypothesis Problem đã chốt từ Day 17;
* yêu cầu làm rõ phần đóng góp cá nhân;
* chuyển Option A sang giao diện TSX/CSS có interaction;
* kiểm tra lại cấu trúc project trước khi chạy;
* chỉ giữ nội dung thuộc Chặng 1–4.

---

# 12. Progress hiện tại

* [X] **Chặng 1 — Tổng hợp Evidence**
* [X] **Chặng 2 — Chọn ba Solution Options**
* [X] **Chặng 3 — Human–AI Design Pass**
* [X] **Chặng 4 — Build ba Micro-prototype**
* [ ] **Chặng 5 — Chuẩn bị Test**
* [ ] **Chặng 6 — Test với ba người**

> Bản README hiện tại dừng tại **Chặng 4**, đúng phạm vi thực hiện hôm nay.

---

# 13. Gate Self-check đến Chặng 4

## GATE 1 — Evidence Continuity

**Đạt**

* Hypothesis Problem có User.
* Có Situation.
* Có Job.
* Có Barrier.
* Có Consequence.
* Có observation nối từ Day 17.
* Observation và Interpretation được tách riêng.

---

## GATE 2 — Meaningful Options

**Đạt**

Ba option:

* cùng Problem;
* cùng User;
* cùng Situation;
* cùng Task;
* cùng Desired Outcome;
* khác Solution Mechanism;
* khác cách phân chia Human–AI Agency.

---

## GATE 3 — Human Control

**Đạt**

Mỗi option có:

* User Role;
* AI Role;
* AI Act / Ask / Don't Act;
* Capability;
* Limit;
* Evidence;
* Uncertainty;
* Control;
* Recovery.

---

## GATE 4 — Test-ready

Prototype được thiết kế theo cùng:

* Common Context;
* Task;
* Content Fixture;
* Desired Outcome.

Mỗi option tập trung vào Critical Interaction riêng.

---

# 14. Repository Structure — Hiện tại đến Chặng 4

```text
Track1_Day18_2A202601057_VuHuyHoang/
│
├── README.md
├── three-option-design-sheet.md
├── prototype-link.md
├── ai-support-log.md
│
└── prototype/
    ├── option-a/
    │   ├── page.tsx
    │   └── option-a.module.css
    │
    ├── option-b/
    │
    └── option-c/
```

---

# 15. Trạng thái hiện tại

Bài hiện tại đã hoàn thành đến:

> **Chặng 4 — Build ba Micro-prototype**

Các phần liên quan đến:

* tester;
* observation;
* Prototype Feedback;
* Group Feedback Synthesis;
* Next Change;
* Still Unproven sau test;

sẽ được bổ sung ở các chặng tiếp theo và không được tạo giả trong bản hiện tại.
