# AI AUDIT REPORT

- Student name: Dương Gia Huy
- Student ID: 23127052

## AI-generated Artifact

### Artifact 1: 
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 16:09 25/05/2026
- **Prompt:**
```
Bạn hãy generate cho tôi phần format cho phần yêu cầu 1 (các layout dưới dạng .md, bạn hãy nhớ xóa các [cite])
```

**2. AI Output:**
Tạo template Markdown cho Requirement 1 gồm:
- Summary checklist (10 job trong 60 ngày, >=3 job AI, ảnh có ngày + username).
- Mẫu Job Posting với các trường: Category, Source Link, Screenshot, Job Description, Required Skills, Salary, AI Impact Analysis.
- Hướng dẫn lặp mẫu đến Job Posting 10 và gợi ý dùng thư mục images để lưu ảnh.

**3. Verdict:** VALID

**4. Reasoning:** AI đã tạo ra cấu trúc template phù hợp với bài tập HW01 (đầy đủ trường thông tin bắt buộc của Requirement 1).

**5. Student Fix:** Em có cập nhập lại một số chỗ như thay vì dùng Traditional QA thì ghi No AI-Requirement cho phần Category để dễ phân biệt hơn và thêm chú thích tiếng Việt tại các bullet header cho báo cáo dễ đọc.

### Artifact 2:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 14:11 26/05/2026
- **Prompt:**
```
Bạn hãy tìm cho tôi 5 cái defect liên quan tới AI/LLM (hallucination, prompt injection, bias) ở phần requirement 2
```

**2. AI Output:** Tổng hợp 5 defect liên quan AI/LLM (2022-2026), mỗi defect gồm: nguồn tham khảo, mô tả, severity, hậu quả, giải pháp, và 1 ví dụ AI bị ảo giác/thiên lệch khi giải thích vụ việc. Các case: Air Canada chatbot hallucination, Mata v. Avianca (án lệ giả), Chevy chatbot prompt injection, Gemini image bias lịch sử, NEDA chatbot Tessa tư vấn độc hại.

**3. Verdict:** INCOMPLETE

**4. Reasoning:** AI tìm ra đúng 5 defect nổi tiếng về AI/LLM diễn ra đúng giai đoạn 2022 - 2026 và trình bày cấu trúc đầy đủ. Nhưng các thông tin sinh ra lại bị source hallucination, các đường link đính kèm trên khung chat AI đều dẫn đến 1 trang không tồn tại và mặc dù vụ án Defect 2 luật sư nộp án lệ giả do ChatGPT tạo ra vào năm 2023 ở New York có tồn tại, nhưng em lại không thể tìm được nguồn nào nói về vụ việc này nên không thể xác thực được thông tin.

**5. Student Fix:**
- Em đã tự fact-check lại toàn bộ 5 sự kiện do AI gợi ý thông qua các nguồn báo chí uy tín và cập nhật lại các nguồn link chính xác.
- Riêng đối với Defect 2, em đã loại bỏ vụ án ở New York (2023) do thiếu thông tin để kiểm chứng. Và thay bằng một vụ việc có tính chất tương đương - Vụ luật sư nộp đơn kháng cáo chứa thông tin giả do ChatGPT sinh ra tại bang Utah vào năm 2025.

### Artifact 3:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 10:24 27/05/2026
- **Prompt:**
```
Bạn hãy tìm tiếp cho tôi thêm 15 cái của requirement 2 nữa
```

**2. AI Output:** Tổng hợp 15 defect phần mềm (Defect 6-20, 2022-2026). Mỗi defect có: source link, mô tả, severity, hậu quả, giải pháp, và 1 ví dụ AI bị ảo giác/thiên lệch khi giải thích. Danh sách gồm: CrowdStrike BSOD, Optus data breach, FAA NOTAM outage, NATS parsing failure, MOVEit SQLi, McDonald's outage, Toyota public bucket, AT&T outage, 23andMe credential stuffing, LastPass breach, Slack desktop RCE, Exchange Online token forgery, Confluence CVE-2023-22515, GitLab path traversal CVE-2024-0402, AnyDesk prod breach.

**3. Verdict:** INCOMPLETE

**4. Reasoning:** AI cung cấp danh sách 15 sự cố phần mềm rất đa dạng và đúng mốc thời gian, nhưng nó vẫn mắc lỗi tương tự như ở Artifact 2 các đường link đều dẫn tới trang không tồn tại.

**5. Student Fix:**
- Em đã tự tra cứu, fact-check lại thông tin thực tế và cập nhật các đường link nguồn từ các trang tin tức uy tín.
- Em chủ động giới hạn quy mô của Requirement 2 ở mức 15 defect để đảm bảo chất lượng phân tích. Nên em đã chọn lọc ra 10 sự cố tiêu biểu nhất đưa vào Requirement 2 để kết hợp với 5 defect trước đó.

### Artifact 4:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 21:50 29/05/2026
- **Prompt:**
```
Bây giờ bạn hãy generate giúp tôi format bảng để tôi điền các test case phần requirement 3 trước
```

**2. AI Output:**
Tạo template Requirement 3 gồm:
- Device Declaration (type, brand, model, year, serial, ảnh thiết bị + thẻ SV).
- Bảng 15 test case với cột chuẩn (Objective, Input, Steps, Expected/Actual, Verdict, Video/Notes).
- Quy định: ít nhất 5 test có video (<=60s), ít nhất 3 edge cases.
- Mục AI Missed Edge Cases Analysis: ảnh chat AI và giải thích vì sao AI bỏ sót TC13-15.

**3. Verdict:** VALID

**4. Reasoning:** Định dạng bài làm và bảng do AI tạo ra phù hợp với HW01 (bao quát đủ các trường và thông tin cần thiết của Requirement 3)

**5. Student Fix:** Em cũng có điều chỉnh lại đôi chút theo ý muốn mình (xóa bỏ cột Notes, điều chỉnh lại tên các Header...).

### Artifact 5:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 21:51 29/05/2026
- **Prompt:**
```
Bạn hãy generate ra 15 cái test case (dưới dạng format md bạn đã generate) cho thiết bị là quạt Senko, loại LS1630, có 3 nút bấm (tượng trưng cho 3 mức gió - 1, 2, 3) và 1 nút bấm (0) để tắt và 1 nút để xoay quạt
```

**2. AI Output:** Tạo 15 test case cho quạt Senko LS1630: TC01-12 là luồng chức năng chính (bật/tắt, đổi tốc độ, bật/tắt xoay, mất điện, cấp điện khi đã nhấn nút). TC13-15 là edge cases (nhấn đồng thời 2 nút tốc độ, xung đột nút 0 và 3, nhấn hờ gây tiếp xúc điện).

**3. Verdict:** INCOMPLETE

**4. Reasoning:** AI đã xây dựng luồng kiểm thử chức năng (TC01 - TC12) rất logic, bao quát được các trạng thái hoạt động cơ bản và điều kiện chuẩn, thường thấy ở quạt máy. Nhưng em không nghĩ 3 edge cases của AI thật sự cần thiết, vì các edge cases này theo em thấy chỉ nghiêng về các xung đột ở các nút bấm trên quạt (logic trạng thái trên các nút bấm).

**5. Student Fix:** Em đã tự thực thi và ghi nhận Actual Result cho 12 test case đầu, loại bỏ 3 edge cases của AI và thay bằng 3 edge cases em tự thiết kế, những edge cases này theo em thấy thì nó thực tế và bao quát các trường hợp biên đặc biệt nhưng có khả năng xảy ra cao hơn các test case do AI tạo.

### Artifact 6:
**1. Prompt + Tool**
- **Tool:** Gemini 3.5 Flash
- **Timestamp:** 11:05 30/05/2026 - 08:42 02/06/2026
- **Prompt:**
```
Bạn hãy tóm tắt vụ kiện liên quan tới [Các vụ Software Defect] vào năm [Năm xảy ra vụ Software Defect tương ứng]
```

**2. AI Output:** AI đã sinh ra các bản tóm tắt chi tiết cho 15 sự cố phần mềm (bao gồm nguyên nhân, diễn biến, hậu quả...)

**3. Verdict:** INVALID

**4. Reasoning:** Mặc dù AI tóm tắt đúng khung sự kiện cơ bản, nhưng khi nhìn vào chi tiết các số liệu, thông tin do AI generate ra. Thì có thể thấy AI đã tự bịa đặt số liệu, tự quy đổi tỷ giá tiền nhưng quy đổi sai, nhầm lẫn vụ Defect này với vụ Defect khác... 

**5. Student Fix:** Em đã kiểm chứng chéo với các bài báo gốc và phân tích những lỗi sai số liệu hoặc sự kiện do AI tự "chế" ra trong phần AI Bias/Hallucination của từng Defect.

### Artifact 7:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 09:38 02/06/2026 
- **Prompt:**
```
Bạn hãy generate cho tôi 1 script mermaid về QA/QC role mindmap
```

**2. AI Output:** Sinh mã Mermaid mindmap về vai trò QA/QC (QA, QC, Test Management, AI-augmented QA/QC) kèm các vai trò và hoạt động chính. Nhắc người dùng đối chiếu ISTQB để tìm 3 điểm sai trong mindmap.

**3. Verdict:** INVALID

**4. Reasoning:**
- AI hiểu sai kiến thức ISTQB cơ bản, thay vì đưa "Test Execution" vào nhánh QC là chuẩn kiến thức, nó lại đưa vào QA, đưa "Debugging Software" vào QC, trong khi đây là việc của Developer và còn dùng sai thuật ngữ "QA Automation" trong khi chuẩn phải là Test Automation thuộc nhánh QC.

**5. Student Fix:** Em đã cấu trúc lại mã Mermaid, bằng cách chuyển Test Execution sang nhánh QC, xóa Debugging ở nhánh QC và chuyển nhóm Automation về đúng vai trò của QC.

## Đánh giá & Kết luận

### Đánh giá độ chính xác của AI
* **VALID: 2/7 (28.6%)** 
  *(Artifact 1, Artifact 4)*
* **INCOMPLETE: 3/7 (42.8%)** 
  *(Artifact 2, Artifact 3, Artifact 5)*.
* **INVALID: 2/7 (28.6%)**
  *(Artifact 6, Artifact 7)*

### Kết luận
Thông qua quá trình thực hiện bài tập và đối chiếu kết quả, em rút ra kết luận về việc ứng dụng AI như sau:
**Khi nào nên dùng AI:**
1. Khi cần phải tạo cấu trúc template và tài liệu như sinh các template Markdown, bảng test case, hoặc các mã Mermaid...
2. Thiết kế các luồng test case cơ bản (bật/tắt, chuyển trạng thái).
3. Tiết kiệm thời gian thay vì tự kiếm các defects thì cho AI nêu tên các vụ defects chung chung, tiêu biểu rồi tự mình tìm hiểu sâu hơn.

**Khi nào không nên dùng AI:**
1. Dù phiên bản Gemini em dùng là bản Pro nhưng vẫn bị lỗi đường dẫn, nên việc tuyệt đối tin tưởng vào các đường link tham khảo hay số liệu chi tiết do AI cung cấp là không nên. Bắt buộc phải tự fact-check lại 100% bằng con người với các nguồn báo chí, tài liệu uy tín.
2. Khi cần tìm các edge cases cho các thiết bị vật lý, do AI không có nhận thức với các thao tác vật lý ngẫu nhiên của người dùng nên các test case nó sinh ra thường bị giới hạn trong tư duy logic phần mềm.
3. Khi cần tìm kiếm và xác nhận các kiến thức chuyên ngành, vì AI dễ bị nhiễu thông tin trên internet nên có khả năng cao phân loại sai các thuật ngữ, do đó việc tìm kiếm hay xác nhận luôn phải bám sát vào giáo trình.