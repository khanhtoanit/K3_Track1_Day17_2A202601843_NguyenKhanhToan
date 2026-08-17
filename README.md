# Track 1 - Day 17 — Finding and Validating Pain Points

## Thông tin

- **Lớp / Khóa:** K3 - Track 01 (AI Product Development)
- **Tên nhóm:** Nhóm 02
- **Case đã chọn:** **Case B — AI Notes: Personal Learning Notes**
- **Repo cá nhân nộp bài:** [github.com/khanhtoanit/K3_Track1_Day17_2A202601843_NguyenKhanhToan](https://github.com/khanhtoanit/K3_Track1_Day17_2A202601843_NguyenKhanhToan)

### 👥 Danh sách thành viên & Phân công trách nhiệm (RACI Matrix):

| Thành viên & Mã học viên                         | Vai trò trong nhóm                                                     | Trách nhiệm chính (Owner)                                                                                                                                                                                                                                                                                                                   | Phần phụ trách trong Repo                                                                                                                                                                                                                                                        |
| :---------------------------------------------------- | :----------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Phan Văn Tình***(MHV: 2A202601430)*      | **Product Lead & Problem Framer***(Trưởng nhóm)*                | - Chủ trì**Chặng 1**: Chuyển dịch Solution sang Capability trung tính, xây dựng Change Chain, JTBD, 2 Pain Hypotheses đối trọng và Evidence Map.- Trực tiếp thực hiện lượt **Interviewer chính** trong buổi phỏng vấn (Chặng 3).- Chủ trì viết **AI Support Log** và duyệt tổng thể báo cáo. | -[Phần 1: Problem Hypothesis Brief](#phần-1-problem-hypothesis-brief-kết-quả-chặng-1)- [interview/notes.md](file:///c:/Work/VinAI/Track1/K4-Track01-Lab17-2A202601430-PhanVanTinh/interview/notes.md)- [Phần 4: AI Support Log](#phần-4-ai-support-log-nhật-ký-cộng-tác-ai) |
| **2. Phạm Duy Hoàn***(MHV: 2A202601378)*      | **User Researcher & Guide Designer***(Chuyên viên Nghiên cứu)* | - Chủ trì**Chặng 2**: Thiết kế Conversation Guide chuẩn *The Mom Test*, soạn thảo Big 3 Questions, Scary Question, Probe Bank và 3 phản xạ Deflect/Anchor/Dig.- Chủ trì viết **Practice Reflection** ở Chặng 4 và hiệu chỉnh Conversation Guide sau buổi luyện phỏng vấn.                                 | -[Phần 2: Conversation Guide phiên bản cuối](#phần-2-conversation-guide-phiên-bản-cuối-đã-hiệu-chỉnh-sau-luyện-tập)- [Phần 3: Practice Reflection](#phần-3-practice-reflection-chặng-4)                                                                              |
| **3. Nguyễn Khánh Toàn***(MHV: 2A202601843)* | **Evidence & Quality Gate Auditor***(Kiểm soát Chất lượng)*   | - Bóc tách dữ liệu phỏng vấn, tổng hợp**Evidence Summary** và trích xuất Exact Quotes.- Quản lý lưu trữ file ghi âm và kiểm soát quyền truy cập tại `interview/recording-link.md`.- Chủ trì rà soát đối chiếu **Bảng tự kiểm tra (Self-Audit)** đảm bảo vượt qua 4 Gate đánh giá.        | -[interview/recording-link.md](file:///c:/Work/VinAI/Track1/K4-Track01-Lab17-2A202601430-PhanVanTinh/interview/recording-link.md)- [Bảng tự kiểm tra 4 Gate](#bảng-tự-kiểm-tra-theo-4-gate-đánh-giá-self-audit)                                                              |

---

## Mục lục nội dung

1. [Phần 1: Problem Hypothesis Brief (Kết quả Chặng 1)](#phần-1-problem-hypothesis-brief-kết-quả-chặng-1)
2. [Phần 2: Conversation Guide phiên bản cuối (Đã hiệu chỉnh sau luyện tập)](#phần-2-conversation-guide-phiên-bản-cuối-đã-hiệu-chỉnh-sau-luyện-tập)
3. [Phần 3: Practice Reflection (Chặng 4)](#phần-3-practice-reflection-chặng-4)
4. [Phần 4: AI Support Log (Nhật ký cộng tác AI)](#phần-4-ai-support-log-nhật-ký-cộng-tác-ai)
5. [Phần 5: Cấu trúc thư mục nộp bài &amp; Liên kết phỏng vấn](#phần-5-cấu-trúc-thư-mục-nộp-bài--liên-kết-phỏng-vấn)
6. [Bảng tự kiểm tra theo 4 Gate đánh giá (Self-Audit)](#bảng-tự-kiểm-tra-theo-4-gate-đánh-giá-self-audit)

---

## Phần 1: Problem Hypothesis Brief (Kết quả Chặng 1)

*Người phụ trách chính: Phan Văn Tình (Product Lead)*

### 1. Solution Directive & Capability trung tính

- **Solution directive ban đầu:**
  > Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu “Chưa hiểu”, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.
  >
- **Capability trung tính (đã gỡ bỏ toàn bộ hình thức công nghệ và tính năng cụ thể):**
  > Giúp người học lưu lại, tổng hợp và tổ chức những nội dung họ cho là quan trọng, chưa hiểu hoặc cần xem lại trong quá trình tiếp thu kiến thức để có thể sử dụng lại sau đó một cách dễ dàng và hiệu quả.
  >
- **Tính độc lập của Capability:**
  Không phụ thuộc vào: *AI, công cụ highlight, nút bấm “Chưa hiểu”, giao diện màn hình Notes, hay thời điểm kết thúc bài học.*

---

### 2. Chuỗi kỳ vọng thay đổi (Change Chain) & Phân biệt Output / Outcome

```text
Solution Directive (Ý tưởng ban đầu)
  ↓
Dấu vết quan trọng trong lúc học được ghi nhận kịp thời mà không ngắt mạch nghe (Immediate Capture)
  ↓
Dấu vết rời rạc được tập hợp và gắn liền với ngữ cảnh tài liệu gốc (Contextual Linking)
  ↓
Người học có tài liệu cô đọng phản ánh đúng điểm vướng mắc cá nhân (Structured Asset)
  ↓
Người học nhanh chóng tra cứu và hiểu lại mà không phải đọc/xem lại toàn bộ bài từ đầu (Targeted Retrieval)
  ↓
Outcome: Giảm tải áp lực nhận thức, tiết kiệm thời gian ôn tập và nâng cao hiệu quả tiếp thu kiến thức.
```

- **Output mà nhóm tạo ra được:** Một tập tài liệu / ghi chú được gom nhóm, có cấu trúc và giữ trọn vẹn ngữ cảnh gốc.
- **Outcome mà nhóm chỉ có thể tác động gián tiếp:** Người học hiểu sâu hơn, ghi nhớ lâu hơn, giảm thời gian tra cứu lãng phí và hoàn thành bài kiểm tra tốt hơn.

---

### 3. Phân tích Actor & Lựa chọn nhánh điều tra ưu tiên

| Nhóm Actor                                                                           | Họ đang làm gì trong thực tế?                                                                | Pain / Hậu quả có thể xảy ra                                                                                                    | Lợi ích kỳ vọng nếu giải quyết được                                                       |
| :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------- |
| **Người học có thói quen ghi chép sổ tay / highlight (Nhóm ưu tiên)** | Chủ động chép từ khóa, vẽ sơ đồ, highlight slide trong các buổi đào tạo/tự học.   | Tốc độ viết không kịp tốc độ nói; ghi chú rời rạc mất ngữ cảnh gốc; tốn nhiều thời gian đối chiếu lại slide. | Không bị đứt mạch nghe; dễ dàng tra cứu lại đúng trang slide chứa kiến thức cần ôn. |
| **Người học chỉ nghe giảng và ít ghi chép**                             | Nghe một mạch, chỉ xem lại tài liệu khi phải làm bài test khó.                           | Mất nhiều thời gian tìm kiếm từ đầu vì không có bất kỳ mốc định vị nào.                                            | Định vị nhanh hơn các phần quan trọng nếu có hệ thống gợi ý mốc bài giảng.          |
| **Diễn giả / Giảng viên đào tạo**                                        | Truyền tải lượng kiến thức lớn, nhiều case study và điều khoản trong thời gian ngắn. | Không biết người học bị "nghẽn" hoặc bỏ dở thông tin ở phần nội dung nào.                                             | Có dữ liệu tổng hợp để cải thiện tốc độ và cấu trúc bài giảng.                     |

> **Lý do chọn nhóm "Người học có thói quen ghi chép sổ tay / highlight" để điều tra trước:**
> Đây là nhóm đã có hành vi thực tế (Capture behavior) và có động lực học tập cao. Nếu nhóm này gặp bế tắc lớn giữa việc vừa viết vừa nghe và tốn nhiều giờ đối chiếu lại tài liệu sau đó, thì giá trị của một giải pháp hỗ trợ ghi chú có ngữ cảnh là cực kỳ cấp thiết.

---

### 4. Situation & Job to be Done (JTBD)

- **Situation (Bối cảnh thực tế):**
  > Khi đang tham gia một buổi đào tạo chuyên môn hoặc tự học trực tuyến có lượng thông tin lớn, tốc độ truyền tải nhanh...
  >
- **Job to be Done (JTBD Hypothesis):**
  > Tôi muốn nhanh chóng lưu lại các điểm then chốt và những phần chưa hiểu mà không làm gián đoạn việc nghe giảng, để khi ôn tập hoặc làm bài kiểm tra, tôi có thể đối chiếu ngay với ngữ cảnh tài liệu gốc mà không phải tốn hàng giờ tìm kiếm lại từ đầu.
  >

---

### 5. Hai Pain Hypotheses cạnh tranh & Lựa chọn kiểm chứng

```text
               ┌──► Pain Hypothesis A: Vấn đề nằm ở SỰ PHÂN MẢNH & TỐC ĐỘ GHI CHÉP
               │    (Vừa nghe vừa viết không kịp -> Quá tải nhận thức, đứt mạch học)
Vấn đề thực sự ┤
nằm ở đâu?     └──► Pain Hypothesis B: Vấn đề nằm ở MẤT LIÊN KẾT NGỮ CẢNH (CONTEXT LOSS)
                    (Ghi chú trong sổ bị tách rời khỏi file Slide/PDF -> "Mò kim đáy bể")
```

- **Pain Hypothesis A (Quá tải & Đứt mạch ghi chép):** Người học bị áp lực vì tốc độ nói của giảng viên nhanh hơn tốc độ viết, dẫn đến việc cắm cúi viết làm bỏ lỡ các nội dung quan trọng tiếp theo.
- **Pain Hypothesis B (Mất liên kết ngữ cảnh):** Ghi chú ngắn gọn hoặc dấu hỏi chấm trên sổ bị tách rời hoàn toàn khỏi số trang slide/mốc thời gian, khiến việc tra cứu lại file PDF sau đó cực kỳ tốn thời gian.
- **Kết luận sau phỏng vấn thực tế:** **Cả hai Pain Hypotheses đều được xác thực**, trong đó Pain B (Context Loss) tạo ra chi phí thời gian lớn nhất (~45 phút tra cứu tài liệu 60 trang).

---

### 6. Evidence Map & Điều kiện Bác bỏ giả thuyết (Falsification)

| Hạng mục kiểm tra                | Bằng chứng làm nhóm TIN HƠN (Validation)                                                                                  | Bằng chứng làm nhóm XEM XÉT LẠI / BÁC BỎ (Falsification)                                      |
| :---------------------------------- | :----------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- |
| **Situation có thật**       | Kể chi tiết buổi học sáng thứ 7 về quản lý rủi ro tài chính qua Zoom, diễn giả nói nhanh, nhiều điều khoản. | Không tham gia buổi học nào gần đây, hoặc chỉ nghe thụ động không ghi chép.             |
| **Pain có ý nghĩa**        | Bị cuống, tai ù đi vài phút vì không kịp chép; mất 45 phút lội file PDF 60 trang để tra cứu lại.              | Ghi chép kịp 100%; tra cứu lại trong vòng vài giây mà không gặp trở ngại nào.            |
| **Workaround tồn tại**      | Dùng sổ tay chép từ khóa + đánh dấu`?` to bên cạnh dòng viết dở để sau này mở PDF tra lại.                 | Không dùng cách nào vì cách học hiện tại đã hoàn hảo.                                    |
| **Consequence đáng kể**    | Mất 45 phút tra cứu cho bài test 15 phút (gấp 3 lần); nản lòng vì "mò kim đáy bể".                               | Không có hậu quả gì, việc thiếu ghi chú không ảnh hưởng đến điểm số hay công việc. |
| **Tính lặp lại (Pattern)** | Gặp thường xuyên ở hầu hết các buổi học/đào tạo trực tuyến có mật độ thông tin dày.                       | Chỉ xảy ra đúng một lần do sự cố hy hữu.                                                     |

---

### 7. Solution Parking Lot (Bãi đỗ ý tưởng giải pháp)

*Toàn bộ ý tưởng giải pháp được cô lập tại đây để không làm thiên lệch quá trình phỏng vấn:*

1. [AI] Tự động đồng bộ âm thanh bài giảng với từng trang slide PDF và trích xuất tóm tắt theo thời gian thực.
2. [Non-AI] Cho phép người học bấm phím tắt để đánh dấu mốc thời gian (timestamp bookmark) trên giao diện học trực tuyến.
3. [AI] Trợ lý ảo giải đáp nhanh các câu hỏi vướng mắc / điều khoản luật ngay trong lúc học dựa trên nội dung slide.
4. [Non-AI] Tự động tạo mục lục liên kết giữa ghi chú cá nhân và số trang slide PDF tương ứng.
5. [AI] Tạo bài test ôn tập nhanh từ các đoạn mà người học đánh dấu "Chưa hiểu".

---

## Phần 2: Conversation Guide phiên bản cuối (Đã hiệu chỉnh sau luyện tập)

*Người phụ trách chính: Phạm Duy Hoàn (User Researcher)*

### 1. Tiêu chí tuyển người & Câu hỏi sàng lọc (Recruitment Criteria)

- **Tiêu chí:**
  > Chúng tôi cần nói chuyện với người học đã **tham gia buổi học và có phát sinh hành vi ghi chép sổ tay, highlight hoặc tra cứu tài liệu trong vòng 7 ngày gần đây**.
  >
- **Recruitment Check (Câu sàng lọc đầu vào - Không tính là evidence):**
  > *"Trong khoảng một tuần trở lại đây, bạn có tham gia buổi học nào mà bạn có ghi chép sổ tay hoặc lưu tài liệu lại không?"*
  >

---

### 2. Lời mở đầu (Framing & Consent)

> *"Chào bạn, cảm ơn bạn đã dành thời gian trò chuyện hôm nay. Mình đang tìm hiểu về thói quen học tập và cách mọi người ghi chép, tra cứu tài liệu thực tế khi tham gia các buổi học.*
>
> *Buổi nói chuyện này hoàn toàn nhằm mục đích học hỏi trải nghiệm thực tế của bạn, **không có câu trả lời đúng hay sai, và mình không bán hay giới thiệu bất kỳ phần mềm hay tính năng nào**.*
>
> *Để tiện ghi chép và phân tích dữ liệu phục vụ nghiên cứu nội bộ, mình xin phép được ghi âm cuộc trò chuyện này. Bản ghi âm được bảo mật hoàn toàn và không công khai. Bạn có đồng ý cho mình bắt đầu ghi âm không?"*

---

### 3. Story Opener (Câu mở đầu neo chặt vào sự kiện gần nhất)

> **"Trong khoảng một tuần trở lại đây, bạn có tham gia buổi học nào không? Nội dung cụ thể của buổi đó là gì và lượng thông tin được truyền tải hôm đó ra sao?"**

---

### 4. Big 3 Questions (Ba câu hỏi cốt lõi nối với 3 điều cần học)

|                STT                | Điều quan trọng nhất cần học                                                                                                                          | Câu hỏi cốt lõi sẽ dùng (Quá khứ & Hành vi)                                                                                                                                                                                                   | Dấu hiệu câu trả lời làm yếu/bác bỏ giả thuyết                                                                  |
| :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------- |
|           **Q1**           | **Hành vi Capture & Rào cản nhận thức lúc học:** Người học ghi chép thế nào và việc ghi chép có làm đứt mạch nghe giảng không? | *"Khi bạn cúi xuống sổ để viết lại từ khóa hoặc vẽ sơ đồ, bạn có gặp khó khăn gì trong việc vừa viết vừa theo dõi lời giảng của diễn giả không? Kể lại một khoảnh khắc cụ thể khiến bạn khó chịu nhất?"* | Người học vừa nghe vừa chép trọn vẹn 100%, không bị lỡ bất kỳ thông tin nào và cảm thấy rất thư thái. |
|           **Q2**           | **Workaround & Hành vi Reuse:** Khi bị hụt thông tin hoặc cần ôn lại, họ đối chiếu ghi chú với tài liệu như thế nào?               | *"Sau khi buổi học kết thúc và nhận được file slide PDF, bạn đã làm gì với những chỗ bị bỏ trống/dấu hỏi chấm trong sổ? Quá trình đối chiếu diễn ra như thế nào?"*                                                  | Người học mở PDF ra tìm thấy ngay trong 5 giây nhờ nhớ chính xác số trang, không cần tìm kiếm vất vả.    |
| **Q3** *(Scary Question)* | **Chi phí & Hậu quả thực tế:** Việc tìm kiếm lại thông tin rải rác làm mất bao nhiêu thời gian và gây hệ quả gì?                 | *"Bạn đã mất bao nhiêu thời gian để tìm và làm rõ lại toàn bộ các điểm bị vướng đó? Việc này ảnh hưởng thế nào đến việc làm bài kiểm tra hoặc tâm lý của bạn?"*                                             | Người học bảo "Chỉ mất 1-2 phút, không đáng kể và mình không cảm thấy phiền toái gì".                   |

---

### 5. Probe Bank (Bộ câu hỏi đào sâu hành vi - workaround - hậu quả)

- *"Hãy kể cho tôi bạn thường làm gì với highlight và notes sau khi học xong một bài."*
- *"Lần gần nhất bạn xem lại notes của một bài học là khi nào? Bạn đã làm gì?"*
- *"Có khi nào bạn ghi chú hoặc đánh dấu ‘chưa hiểu’ nhưng sau đó không quay lại xử lý không? Vì sao?"*
- *"Việc sắp xếp / hệ thống hóa lại những gì bạn đã ghi chú sau một bài học thường mất bao nhiêu công sức/thời gian?"*
- *"Nếu hệ thống tự tổng hợp những gì bạn đã highlight, chưa hiểu và đặt câu hỏi thành một bản note, điều gì khiến bạn muốn dùng hoặc không muốn dùng nó?"*

---

### 6. Ba phản xạ chuẩn hóa dữ liệu khi phỏng vấn bị lệch (Bias Counter-Reflexes)

```text
┌───────────────────────────────┬────────────┬────────────────────────────────────────────────────────┐
│ Tình huống dữ liệu bị lệch    │ Phản xạ    │ Cách phản ứng và kéo về bằng chứng thực tế             │
├───────────────────────────────┼────────────┼────────────────────────────────────────────────────────┤
│ 1. User khen ngợi / Phán đoán │ DEFLECT    │ "Cảm ơn bạn. Nhưng quay lại với buổi học sáng thứ 7,   │
│    "Có app thông minh thì tốt"│ (Gạt đi)   │ lúc đó bạn đã dùng sổ tay ghi chép cụ thể ra sao?"     │
├───────────────────────────────┼────────────┼────────────────────────────────────────────────────────┤
│ 2. User nói chung chung /     │ ANCHOR     │ "Lần gần nhất bạn phải mở file PDF 60 trang để tra lại │
│    "Mình hay đọc lại slide"   │ (Neo lại)  │ là chiều hôm qua đúng không? Bạn đã tìm trang nào?"    │
├───────────────────────────────┼────────────┼────────────────────────────────────────────────────────┤
│ 3. User đề xuất tính năng     │ DIG        │ "Nếu có tính năng tự trích xuất slide thì nó giúp bạn  │
│    (Feature request)          │ (Đào sâu)  │ tiết kiệm được bao nhiêu phút so với 45 phút hôm qua?" │
└───────────────────────────────┴────────────┴────────────────────────────────────────────────────────┘
```

---

## Phần 3: Practice Reflection (Chặng 4)

*Người phụ trách chính: Phạm Duy Hoàn (User Researcher) phối hợp cùng Phan Văn Tình*

Sau khi hoàn thành phiên phỏng vấn thực tế với đối tượng `P-01`, dưới đây là 3 đúc kết thực chiến:

### 1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?

> **Câu hỏi mang lại hiệu quả nhất:**
> *"Kể lại chi tiết một khoảnh khắc cụ thể trong buổi sáng thứ 7 đó mà bạn cảm thấy khó chịu nhất vì việc vừa viết vừa nghe?"*
>
> **Lý do thành công:** Câu hỏi đào sâu thẳng vào cảm xúc tiêu cực và neo đúng buổi học sáng thứ 7. Nhờ đó, user đã kể lại một câu chuyện cực kỳ sống động và giàu chi tiết: Lúc diễn giả nói về *"3 trường hợp ngoại lệ trong xét duyệt rủi ro"*, user mới viết được trường hợp 1 thì diễn giả đã đọc xong trường hợp 3 $\rightarrow$ User bị cuống, bỏ dở dòng viết, tai ù đi vài phút và phải đánh dấu `?` to vào sổ.

### 2. Chỗ nào mình nhận ra cần làm tốt hơn ở lần phỏng vấn thật?

> **Lỗi tự nhận diện và bài học cải thiện:**
>
> 1. **Chưa khai thác ngay con số định lượng ở lần hỏi đầu tiên:** Khi user bảo *"Mất nhiều thời gian tìm kiếm lại file PDF"*, ban đầu interviewer định chuyển sang câu hỏi khác. Sau đó phải dùng câu hỏi phụ *"Cụ thể là mất bao nhiêu thời gian so với thời gian làm bài test?"* thì mới thu được con số đắt giá: **Mất 45 phút tra cứu cho bài test 15 phút**. Ở lần sau cần có phản xạ hỏi ngay con số định lượng (thời gian, chi phí, số lần lặp lại).
> 2. **Cần kiểm soát sự im lặng (Active Listening):** Đôi khi thấy user ngập ngừng suy nghĩ thì interviewer có xu hướng muốn gợi ý đáp án. Cần kiên nhẫn im lặng thêm 2-3 giây để user tự lục lại trí nhớ về các chi tiết thực tế.

### 3. Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?

> **Các điểm đã chỉnh sửa từ Bản thảo (Draft) sang Bản cuối (Final):**
>
> 1. **Bổ sung câu hỏi về "Rào cản nhận thức lúc nghe giảng":** Bản thảo ban đầu chỉ tập trung vào giai đoạn sau buổi học (*"Bạn xem lại note thế nào?"*). Sau buổi luyện, nhóm nhận thấy nỗi đau xuất hiện ngay từ lúc học (tốc độ viết không kịp tốc độ nói), nên đã bổ sung nhóm câu hỏi ở Phần 2 (*"Khi bạn cúi xuống viết, bạn có gặp khó khăn gì trong việc theo dõi lời giảng không?"*).
> 2. **Bổ sung Probe đo lường tỷ lệ thời gian:** Thêm câu hỏi so sánh giữa thời gian tìm kiếm thông tin và thời gian thực sự làm bài test để làm rõ mức độ nghiêm trọng của hậu quả (Consequence).
> 3. **Lược bỏ các từ ngữ mang tính gợi ý giải pháp:** Xóa bỏ hoàn toàn các câu hỏi về *"bạn có muốn số hóa ghi chú không"*, giữ đúng 100% tinh thần tìm bằng chứng về hành vi quá khứ.

---

## Phần 4: AI Support Log (Nhật ký cộng tác AI)

*Người phụ trách chính: Phan Văn Tình (Product Lead)*

### 1. AI đã hỗ trợ những gì?

- Giúp cấu trúc chuỗi phân tích từ **Solution Directive** thành **Capability trung tính** và bóc tách mạch suy luận Output vs Outcome.
- Hỗ trợ biên soạn và chuẩn hóa toàn bộ biên bản phỏng vấn đối thoại theo 3 phần: *Khóa chặt sự kiện $\rightarrow$ Đào sâu hành vi & rào cản $\rightarrow$ Truy vết hậu quả & chi phí thực tế*.
- Giúp thiết kế bảng đối chiếu bằng chứng (Evidence Summary) và làm nổi bật các Exact Quotes đắt giá phục vụ cho 4 Gate đánh giá.

### 2. Điểm sai, hời hợt hoặc thiên kiến của AI ban đầu

- **Xu hướng hỏi ý kiến (Opinion Bias):** AI ban đầu hay đưa vào các câu hỏi gợi ý giải pháp như *"Bạn nghĩ một công cụ tự động đồng bộ slide và ghi chú có cần thiết không?"* -> Vi phạm nguyên tắc The Mom Test vì mời chào đánh giá tính năng.
- **Thiếu chiều sâu về hành vi thực tế:** Các câu hỏi do AI tự sinh ban đầu còn chung chung, thiếu các tình huống đào sâu về rào cản tâm lý (bị cuống, tai ù đi, đánh dấu `?` vào sổ).

### 3. Con người đã can thiệp, chỉnh sửa và chuẩn hóa ra sao?

- **Đưa trải nghiệm và dữ liệu thực tế vào:** Tích hợp toàn bộ diễn biến cuộc phỏng vấn thật về buổi đào tạo quản lý rủi ro tài chính qua Zoom và file slide PDF 60 trang.
- **Chuẩn hóa các câu hỏi đào sâu (Probe):** Ép kịch bản tập trung vào việc bóc tách hành vi thực tế và con số định lượng (4 vị trí dấu hỏi chấm, 45 phút lội file PDF cho bài test 15 phút).
- **Hoàn thiện bảng Self-Audit:** Tự kiểm tra nghiêm ngặt theo 4 Gate đánh giá của chương trình.

---

## Phần 5: Cấu trúc thư mục nộp bài & Liên kết phỏng vấn

*Người phụ trách chính: Nguyễn Khánh Toàn (Evidence & Quality Gate Auditor)*

### Cấu trúc thư mục repo chuẩn:

```text
K3_Track1_Day17_2A202601843_NguyenKhanhToan/
├── README.md                 # Toàn bộ nội dung báo cáo chuẩn 5 phần
└── interview/
    ├── notes.md              # Bản ghi chép chi tiết phiên phỏng vấn (Interview Record & Transcript)
    └── Interview.m4a         # Đường dẫn bản ghi âm có consent của người tham gia
```

- **File ghi chép phỏng vấn:** Xem chi tiết tại [interview/notes.md](interview/notes.md)
- **File liên kết ghi âm:** Xem chi tiết tại [interview/Interview.m4a](interview/Interview.m4a)

---

## Bảng tự kiểm tra theo 4 Gate đánh giá (Self-Audit)

*Người phụ trách chính: Nguyễn Khánh Toàn (Evidence & Quality Gate Auditor)*

| Gate đánh giá                        | Tiêu chuẩn đạt                                                                                                            | Kết quả tự kiểm tra                                                                                                                                               |  Trạng thái  |
| :-------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------: |
| **Gate 1: Problem Framing**       | Đi đủ chuỗi Solution → Evidence; giả thuyết cụ thể, có thể bị bác bỏ; không chứa tên feature.                | Đã chuyển dịch hoàn chỉnh từ Solution Directive sang Capability trung tính; có 2 Pain Hypotheses đối trọng và điều kiện falsification rõ ràng.      | **ĐẠT** |
| **Gate 2: Interview Design**      | Big 3 nối trực tiếp với điều cần học; câu hỏi hỏi về quá khứ gần nhất; tuyệt đối không làm lộ solution. | Bộ câu hỏi 3 phần bám sát sự kiện thực tế trong 7 ngày; có Probe Bank và 3 phản xạ Deflect/Anchor/Dig.                                                 | **ĐẠT** |
| **Gate 3: Interview Practice**    | Có bản ghi được consent; interviewer đào sâu hành vi, ghi chép số liệu thời gian, workaround và exact quotes.   | Đã hoàn thành phỏng vấn, có transcript chi tiết trong`interview/notes.md` kèm số liệu định lượng (45 phút / bài test 15 phút) và 3 exact quotes. | **ĐẠT** |
| **Gate 4: Reflection & Revision** | Chỉ ra lỗi cụ thể khi thực hành và giải thích rõ những điểm đã chỉnh sửa trong Conversation Guide.           | Đã nêu rõ bài học khai thác con số định lượng, chủ động lắng nghe và 3 điểm cải tiến từ bản nháp lên bản cuối tại Phần 3.                | **ĐẠT** |
