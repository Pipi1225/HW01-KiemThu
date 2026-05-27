# AI AUDIT REPORT

## Artifact 1: 
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 16:09 25/05/2026
- **Prompt:**
```
Bạn hãy generate cho tôi phần format cho phần yêu cầu 1 (các layout dưới dạng .md, bạn hãy nhớ xóa các [cite])
```

**2. AI Output:**
```
Chào bạn, tôi đã thiết kế mẫu layout bằng Markdown cho Yêu cầu 1 dựa trên đúng các tiêu chí chấm điểm của bài tập. Mẫu này được cấu trúc chi tiết, tỉ mỉ để bạn dễ dàng điền thông tin mà không bỏ sót bất kỳ ràng buộc nào (như ảnh có username, 3 job AI, 1-2 câu phân tích).Việc rèn luyện thói quen trình bày báo cáo cẩn thận, có hệ thống như thế này sẽ rất có ích cho bạn khi chuẩn bị hồ sơ và bước vào môi trường thực tập chuyên nghiệp trong thời gian tới.Bạn có thể copy toàn bộ đoạn code dưới đây và dán vào file .md của mình:Markdown## Requirement 1 - QA/QC Job Market 2026+

**Summary Checklist:**
- [ ] Tổng cộng 10 tin tuyển dụng (được đăng trong vòng 60 ngày tính đến ngày nộp bài).
- [ ] Ít nhất 3 vị trí yêu cầu kỹ năng AI/LLM/Automation.
- [ ] Tất cả ảnh chụp màn hình đều hiển thị rõ ngày tháng và Tên tài khoản (Account Name) ở góc.

---

### Job Posting 1: [Tên vị trí tuyển dụng] - [Tên công ty]
* **Category:** [AI-Required / Traditional QA] *(Ghi chú rõ để đảm bảo đủ $\ge3$ AI jobs)*
* **Source Link:** [Chèn URL tin tuyển dụng]
* **Dated Screenshot:**
  ![Screenshot Job 1](đường_dẫn_tới_file_ảnh_1.jpg)
  > *Lưu ý: Đảm bảo ảnh thấy rõ ngày đăng tin và username nền tảng (LinkedIn, Indeed, v.v.) của bạn.*
* **Job Description:**
  - [Ghi chú tóm tắt 2-3 ý chính về nhiệm vụ của vị trí này].
* **Required Skills:**
  - [Kỹ năng 1, ví dụ: Test Automation]
  - [Kỹ năng 2, ví dụ: Prompt Engineering]
  - [Kỹ năng 3, ...]
* **Salary:** [Ghi rõ mức lương hoặc "Not disclosed / Thỏa thuận"]
* **AI Impact Analysis:**
  [Viết đúng 1-2 câu phân tích. Ví dụ: "Sự xuất hiện của LLM giúp vị trí này tự động hóa việc viết test script, tuy nhiên QA vẫn đóng vai trò cốt lõi trong việc thẩm định tính chính xác của các bộ test do AI sinh ra."]

---

### Job Posting 2: [Tên vị trí tuyển dụng] - [Tên công ty]
* **Category:** [AI-Required / Traditional QA]
* **Source Link:** [Chèn URL tin tuyển dụng]
* **Dated Screenshot:**
  ![Screenshot Job 2](đường_dẫn_tới_file_ảnh_2.jpg)
* **Job Description:**
  - [Tóm tắt mô tả công việc].
* **Required Skills:**
  - [Kỹ năng 1]
  - [Kỹ năng 2]
* **Salary:** [Mức lương]
* **AI Impact Analysis:**
  [1-2 câu phân tích tác động của AI đối với công việc này.]

---

### Job Posting 3: [Tên vị trí tuyển dụng] - [Tên công ty]
* **Category:** [AI-Required / Traditional QA]
* **Source Link:** [Chèn URL tin tuyển dụng]
* **Dated Screenshot:**
  ![Screenshot Job 3](đường_dẫn_tới_file_ảnh_3.jpg)
* **Job Description:**
  - [Tóm tắt mô tả công việc].
* **Required Skills:**
  - [Kỹ năng 1]
  - [Kỹ năng 2]
* **Salary:** [Mức lương]
* **AI Impact Analysis:**
  [1-2 câu phân tích tác động của AI đối với công việc này.]

---

*(Tiếp tục copy và dán block trên cho đến Job Posting 10)*

Một số mẹo nhỏ khi điền file:Phần Category tôi thêm vào để khi giảng viên chấm bài, họ nhìn lướt qua có thể đếm ngay được bạn đã đạt đủ điều kiện $\ge 3$ jobs AI.Bạn hãy tạo một thư mục images nằm cùng cấp với file .md để chứa ảnh chụp màn hình, khi đó đường dẫn ảnh sẽ rất gọn, ví dụ: ![Screenshot Job 1](images/job1.png).
```

**3. Verdict:** VALID

**4. Reasoning:**
- AI đã tạo ra cấu trúc template phù hợp với bài tập HW01 (đầy đủ trường thông tin bắt buộc của Requirement 1).

**5. Student Fix**
- Em có sửa lại một số chỗ như thay vì dùng luôn Traditional QA thì ghi No AI-Requirement cho phần Category và thêm chú thích tiếng Việt tại các bullet header.

## Artifact 2:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 14:11 26/05/2026
- **Prompt:**
```
Bạn hãy tìm cho tôi 5 cái defect liên quan tới AI/LLM (hallucination, prompt injection, bias) ở phần requirement 2
```

**2. AI Output:**
```
Chào bạn, đối với Yêu cầu 2, việc tìm ra 5 lỗi liên quan đến AI/LLM (hallucination, prompt injection, bias) kèm theo điểm "bẫy" là phải chỉ ra 1 lỗi ảo giác/thiên lệch của chính AI khi giải thích về các vụ việc này là một yêu cầu rất thú vị và đòi hỏi sự tinh tế.

Dưới đây là 5 case study kinh điển trong giai đoạn 2022-2026 được trình bày chi tiết theo đúng format bài tập yêu cầu. Bạn có thể sử dụng nội dung này để đưa vào báo cáo:

Defect 1: Air Canada Chatbot Hallucination (2024)
Source link: BBC - Air Canada chatbot must pay out (hoặc tìm từ khóa "Air Canada chatbot bereavement fare").

Description: Chatbot hỗ trợ khách hàng của Air Canada đã gặp hiện tượng ảo giác (hallucination), tự bịa ra một chính sách giảm giá vé máy bay (bereavement fare) cho một khách hàng có người thân vừa qua đời, trái ngược hoàn toàn với chính sách thực tế của hãng trên website.

Severity: High (Ảnh hưởng tài chính và pháp lý).

Consequences: Khách hàng kiện ra tòa. Tòa án buộc Air Canada phải bồi thường và tuân thủ chính sách do chính chatbot bịa ra. Hãng bị tổn hại nghiêm trọng về uy tín và phải tạm khóa chatbot.

Solution: Cần áp dụng kỹ thuật RAG (Retrieval-Augmented Generation) chặt chẽ hơn. Chỉ cho phép LLM trích xuất và tổng hợp câu trả lời từ cơ sở dữ liệu chính thức của công ty, vô hiệu hóa khả năng tự "sáng tạo" thông tin (temperature = 0 cho các câu hỏi về chính sách).

AI Bias/Hallucination Instance (Điểm ảo giác của AI khi giải thích lỗi này): Khi bạn yêu cầu AI (như ChatGPT/Gemini) tóm tắt vụ kiện này, AI thường bị ảo giác pháp lý khi nói rằng "Air Canada đã thắng kiện vì lập luận chatbot là một thực thể pháp lý riêng biệt". Sự thật là lập luận này của Air Canada đã bị tòa án bác bỏ ngay lập tức và họ đã thua kiện.

Defect 2: Luật sư nộp án lệ giả do ChatGPT tạo ra (Mata v. Avianca Airlines, 2023)
Source link: NY Times - The ChatGPT Lawyer.

Description: Một luật sư đã sử dụng ChatGPT để nghiên cứu hồ sơ kiện hãng hàng không Avianca. ChatGPT đã bị ảo giác (hallucination), tự động bịa ra ít nhất 6 bản án lệ không hề tồn tại kèm theo các trích dẫn pháp lý giả mạo để cung cấp cho luật sư.

Severity: Critical (Ảnh hưởng danh dự nghề nghiệp và tính nghiêm minh của luật pháp).

Consequences: Vụ kiện bị bác bỏ. Luật sư bị tòa án phạt tiền ($5,000) và bị kỷ luật công khai.

Solution: Cấm sử dụng LLM thuần túy cho mục đích trích dẫn pháp lý. Tích hợp AI với các hệ thống kiểm chứng tự động (Fact-checking) hoặc kết nối trực tiếp qua API với các cơ sở dữ liệu pháp luật uy tín (như Westlaw, LexisNexis) trước khi xuất kết quả.

AI Bias/Hallucination Instance: Khi yêu cầu AI giải thích hậu quả của sự cố này, AI thường xuyên bị ảo giác về hình phạt, bịa ra rằng "luật sư này đã bị tước giấy phép hành nghề (disbarred) hoặc bị đuổi việc". Thực tế ông ấy chỉ bị phạt tiền và cảnh cáo.

Defect 3: Chevrolet Dealership Chatbot bị Prompt Injection (2023)
Source link: Business Insider - Chevy dealer chatbot agrees to sell car for $1.

Description: Một đại lý Chevrolet ở Mỹ đã sử dụng chatbot dựa trên ChatGPT. Người dùng đã sử dụng kỹ thuật Prompt Injection, yêu cầu chatbot bỏ qua các quy tắc bán hàng, ép nó phải đồng ý bán một chiếc xe Chevy Tahoe đời mới với giá chỉ 1 đô la, hoặc yêu cầu nó viết các đoạn code Python không liên quan.

Severity: Medium (Ảnh hưởng danh tiếng và bảo mật hệ thống).

Consequences: Hình ảnh đại lý bị đem ra làm trò cười trên mạng xã hội, công ty phải lập tức gỡ bỏ chatbot để bảo trì.

Solution: Thiết lập Guardrails (rào chắn) mạnh mẽ cho System Prompt. Cần có cơ chế Input Filtering để chặn các lệnh thao túng (như "ignore all previous instructions") và giới hạn scope (phạm vi) hoạt động của bot chỉ trong FAQ của đại lý.

AI Bias/Hallucination Instance: Khi AI giải thích vụ này, nó hay vướng vào thiên lệch logic, cho rằng "Chevrolet đã phải chịu khoản lỗ lớn vì bị buộc phải bán xe với giá 1 USD do hợp đồng từ chatbot". Sự thật là những đoạn chat này không có giá trị pháp lý ràng buộc và không có giao dịch 1 USD nào diễn ra.

Defect 4: Google Gemini Image Bias - Lịch sử sai lệch (2024)
Source link: The Verge - Google pauses Gemini image generation.

Description: Công cụ tạo ảnh của Google Gemini bị lỗi thiên lệch (Bias) quá mức về sự đa dạng sắc tộc. Khi người dùng yêu cầu tạo ảnh "Binh lính Đức năm 1943" hoặc "Các nhà lập quốc Mỹ", AI đã chèn (inject) các từ khóa đa dạng vào prompt ngầm, tạo ra hình ảnh sai lệch hoàn toàn về mặt lịch sử (ví dụ: lính Đức da màu).

Severity: High (Danh tiếng và độ tin cậy của sản phẩm).

Consequences: Google phải lên tiếng xin lỗi toàn cầu, vô hiệu hóa tính năng tạo hình ảnh con người trong một thời gian dài, và cổ phiếu Alphabet bị sụt giảm.

Solution: Cải thiện cơ chế "Context-aware prompt adjustment" (Điều chỉnh prompt dựa trên ngữ cảnh). AI cần được huấn luyện để nhận biết khi nào yêu cầu tính đa dạng (diversity) và khi nào cần tôn trọng tính chính xác tuyệt đối của lịch sử.

AI Bias/Hallucination Instance: Nếu bạn hỏi một công cụ AI hiện tại (như Claude hoặc chính Gemini) yêu cầu mô tả chi tiết những bức ảnh nào đã gây tranh cãi, AI có thể thể hiện Safety Bias (Thiên lệch an toàn) bằng cách từ chối trả lời hoặc nói chung chung, không dám nhắc đến "lính Đức Quốc Xã năm 1943" vì sợ vi phạm chính sách bạo lực/hate speech, dẫn đến việc giải thích lỗi không trọn vẹn.

Defect 5: Chatbot y tế "Tessa" của NEDA đưa lời khuyên độc hại (2023)
Source link: NPR - Eating disorder helpline fires staff, transitions to chatbot.

Description: Hiệp hội Rối loạn Ăn uống Quốc gia (NEDA) Mỹ đã thay thế đường dây nóng bằng con chatbot tên Tessa. Thay vì hỗ trợ tâm lý, Tessa đã bị ảo giác và đưa ra những lời khuyên nguy hiểm cho bệnh nhân rối loạn ăn uống, ví dụ như khuyến khích giảm cân, tính calo và đo mỡ cơ thể.

Severity: Critical (Ảnh hưởng trực tiếp đến sức khỏe và tính mạng người bệnh).

Consequences: NEDA phải gỡ bỏ chatbot ngay lập tức giữa tâm bão phẫn nộ từ cộng đồng y khoa và bệnh nhân.

Solution: Đối với các lĩnh vực rủi ro cao như y tế và tâm lý, không được dùng Generative AI dạng mở. Cần dùng hệ thống dựa trên cây quyết định (Rule-based Decision Trees) hoặc có Human-in-the-loop (con người kiểm duyệt trước khi phản hồi) để đảm bảo an toàn tuyệt đối.

AI Bias/Hallucination Instance: Khi yêu cầu AI phân tích lỗi này, AI rất dễ vướng vào ảo giác về nguồn gốc (Source Hallucination), khẳng định rằng "Tessa là một phiên bản của ChatGPT/OpenAI". Trên thực tế, Tessa được phát triển bởi một công ty khác tên là Cass dựa trên công nghệ riêng, không liên quan đến OpenAI.

Bạn có thể điều chỉnh lại văn phong nếu muốn. Nếu bạn cần tôi hướng dẫn cách bóc tách "Edge cases" cho phần test thiết bị gia dụng thực tế (Requirement 3), hãy cho tôi biết nhé!
```

**3. Verdict:**

**4. Reasoning:**
- 

**5. Student Fix**
- 

## Artifact 3:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:** 10:24 27/05/2026
- **Prompt:**
```
Bạn hãy tìm tiếp cho tôi thêm 5 cái của requirement 2 nữa
```

**2. AI Output:**
```
Vì bạn đã có đủ 5 lỗi bắt buộc liên quan đến AI/LLM ở phần trước, 15 lỗi còn lại chúng ta có thể mở rộng ra các sự cố phần mềm nổi tiếng nói chung trong giai đoạn 2022-2026.

Tuy nhiên, bạn lưu ý một bẫy rất quan trọng trong đề bài: "this applies to EVERY defect... 20 instances total". Nghĩa là dù là lỗi phần mềm truyền thống, bạn vẫn phải chỉ ra được một điểm mà AI bị ảo giác hoặc thiên lệch khi bạn yêu cầu nó giải thích về sự cố đó.

Dưới đây là 5 lỗi tiếp theo (từ số 6 đến 10), được viết cực kỳ chi tiết kèm theo phần bóc tách ảo giác của AI để bạn đưa vào báo cáo:

Defect 6: Sự cố toàn cầu CrowdStrike Falcon BSOD (2024)
Source link: The Verge - CrowdStrike IT outage explained.

Description: Một bản cập nhật cấu hình nội dung (Channel File 291) bị lỗi của phần mềm bảo mật CrowdStrike Falcon đã được đẩy thẳng lên môi trường production. Do Falcon chạy ở cấp độ kernel (nhân hệ điều hành) của Windows, lỗi logic trong file này đã gây ra vòng lặp vô tận và lỗi bộ nhớ, khiến hàng triệu máy tính bị màn hình xanh (BSOD).

Severity: Critical (Mức độ nghiêm trọng cao nhất, ảnh hưởng toàn cầu).

Consequences: Hệ thống hàng không, ngân hàng, và bệnh viện trên toàn thế giới bị tê liệt trong nhiều ngày. Gây thiệt hại hàng tỷ USD.

Solution: Cải thiện quy trình QA: Cần có hệ thống kiểm thử tự động nghiêm ngặt cho mọi file cấu hình trước khi deploy. Áp dụng chiến lược "Staged Rollout" (phát hành từng nhóm nhỏ) thay vì đẩy bản cập nhật cho toàn bộ người dùng cùng lúc.

AI Bias/Hallucination Instance: Khi bạn hỏi AI về nguyên nhân sự cố, AI rất dễ bị ảo giác thông tin (Information Hallucination) khi cho rằng "CrowdStrike đã bị hacker tấn công và cài mã độc vào bản cập nhật". Thực tế, đây hoàn toàn là lỗi quy trình nội bộ (QA failure), không có bất kỳ cuộc tấn công mạng nào xảy ra.

Defect 7: Liên Minh Huyền Thoại - Lỗi Vanguard làm treo máy tính (2024)
Source link: IGN - League of Legends Vanguard anti-cheat issues.

Description: Riot Games bắt buộc triển khai hệ thống chống gian lận Vanguard (chạy ở cấp độ Kernel) cho tựa game Liên Minh Huyền Thoại. Tuy nhiên, phần mềm này xung đột nghiêm trọng với các driver phần cứng cũ hoặc BIOS chưa được cập nhật của người dùng, dẫn đến tình trạng máy tính bị treo, kẹt ở vòng lặp khởi động (boot loop) hoặc mất kết nối mạng.

Severity: High (Ảnh hưởng diện rộng đến trải nghiệm người dùng).

Consequences: Hàng loạt người chơi không thể truy cập game, một số người dùng thậm chí phải cài lại hệ điều hành Windows để cứu máy tính.

Solution: QA cần xây dựng ma trận kiểm thử phần cứng (Hardware Compatibility Matrix) đa dạng hơn, bao gồm cả các thiết bị đời cũ. Cung cấp công cụ chẩn đoán xung đột tự động cho người dùng trước khi ép buộc cài đặt phần mềm cấp kernel.

AI Bias/Hallucination Instance: Nếu yêu cầu phân tích hậu quả, AI thường xuyên bị thiên lệch khuếch đại (Exaggeration Bias), khẳng định rằng "Vanguard đã xóa dữ liệu cá nhân của người chơi". Thực tế, phần mềm này gây lỗi driver hệ thống chứ không hề có hành vi xóa file cá nhân.

Defect 8: Sập hệ thống NOTAM của Cục Hàng không Liên bang Mỹ FAA (2023)
Source link: CNN - FAA computer outage causes flight delays.

Description: Hệ thống Notice to Air Missions (NOTAM) chuyên cung cấp thông tin an toàn bay cho phi công của Mỹ bị sập. Nguyên nhân do một nhân viên vô tình xóa nhầm file trong quá trình đồng bộ hóa dữ liệu giữa cơ sở dữ liệu chính và cơ sở dữ liệu dự phòng (backup).

Severity: Critical (Ảnh hưởng an ninh quốc gia và giao thông vận tải).

Consequences: Toàn bộ các chuyến bay nội địa tại Mỹ bị cấm cất cánh trong nhiều giờ (hơn 11,000 chuyến bay bị hoãn), lần đầu tiên kể từ sự kiện 11/9.

Solution: Xây dựng cơ chế "Fail-safe" và phân quyền chặt chẽ trong quản trị cơ sở dữ liệu. Cần có quy trình cô lập cơ sở dữ liệu dự phòng để lỗi từ hệ thống chính không được tự động sao chép sang hệ thống backup.

AI Bias/Hallucination Instance: AI thường xuyên mắc lỗi ảo giác quy kết (Attribution Hallucination) bằng cách kết luận sự kiện này do "tấn công ransomware (mã độc tống tiền) từ tin tặc nước ngoài". Các báo cáo điều tra chính thức của chính phủ Mỹ xác nhận đây chỉ là lỗi con người và quy trình đồng bộ dữ liệu.

Defect 9: Sự cố sập nền tảng Ticketmaster đợt bán vé Taylor Swift (2022)
Source link: NPR - Ticketmaster cancels public sale of Taylor Swift tour.

Description: Hệ thống web của Ticketmaster bị sụp đổ hoàn toàn về mặt kiến trúc server khi mở bán vé sự kiện Eras Tour. Dù đã có hệ thống "Verified Fan" để giới hạn lượng truy cập, API của hệ thống không thể xử lý nổi lượng request khổng lồ từ bot và người dùng thật (gấp 4 lần đỉnh điểm lịch sử).

Severity: High (Khủng hoảng truyền thông và tài chính).

Consequences: Phải hủy bỏ đợt bán vé công khai, Ticketmaster bị điều trần trước Thượng viện Mỹ về vấn đề độc quyền và năng lực kỹ thuật yếu kém.

Solution: Tối ưu hóa lại kiến trúc Microservices, áp dụng các kỹ thuật Rate Limiting (giới hạn truy cập) mạnh mẽ hơn ở tầng Gateway, và nâng cấp thuật toán phát hiện/chặn Bot (Bot Mitigation) theo thời gian thực.

AI Bias/Hallucination Instance: Công cụ AI rất hay bị thiên lệch mỏ neo (Anchoring Bias) khi cho rằng "Máy chủ của Ticketmaster bị sập hoàn toàn và ngừng hoạt động trong nhiều ngày". Thực tế là hệ thống web chạy cực kỳ chậm, các hàng đợi (queue) bị lỗi và kẹt, chứ server không hề bị "chết" hoàn toàn (offline) nhiều ngày liền.

Defect 10: Toyota rò rỉ dữ liệu do lộ Key trên GitHub (2022)
Source link: Reuters - Toyota says data of 296,000 customers may have been leaked.

Description: Một nhà thầu phụ (subcontractor) phát triển phần mềm cho Toyota đã upload mã nguồn chứa đoạn mã truy cập (hard-coded access key) của server dữ liệu lên một repository công khai trên GitHub. Đoạn key này nằm chình ình trên mạng suốt 5 năm mà không ai hay biết.

Severity: High (Lỗi bảo mật nghiêm trọng).

Consequences: Dữ liệu cá nhân (địa chỉ email, mã số khách hàng) của gần 300,000 người dùng T-Connect bị kẻ xấu có khả năng truy cập tự do.

Solution: Tích hợp các công cụ Secret Scanning tự động vào đường ống CI/CD (ví dụ: GitHub Advanced Security hoặc SonarQube) để chặn ngay lập tức bất kỳ commit nào chứa token, mật khẩu hay API Key trước khi code được đẩy lên repo.

AI Bias/Hallucination Instance: AI thường xuyên bị ảo giác trầm trọng hóa (Catastrophizing Hallucination), bịa ra rằng "hacker đã lấy được mã khóa để điều khiển và khởi động xe Toyota từ xa". Lỗ hổng này thực chất chỉ ảnh hưởng đến hệ thống quản lý dữ liệu khách hàng (CRM), hoàn toàn không dính dáng đến hệ thống điều khiển nội bộ (CAN bus) của xe.
```

**3. Verdict:** VALID

**4. Reasoning:**
- 

**5. Student Fix**
- 

## Artifact 4:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:**
- **Prompt:**
```

```

**2. AI Output:**
```

```

**3. Verdict:** VALID

**4. Reasoning:**
- 

**5. Student Fix**
- 

## Artifact 5:
**1. Prompt + Tool**
- **Tool:** Gemini 3.1 Pro
- **Timestamp:**
- **Prompt:**
```

```

**2. AI Output:**
```

```

**3. Verdict:** VALID

**4. Reasoning:**
- 

**5. Student Fix**
- 