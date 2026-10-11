# GIÁO ÁN CHI TIẾT BUỔI 1: THIẾT LẬP BẢO MẬT & DỰNG TRỢ LÝ CLAUDE CHUYÊN VIỆC
## (CHUYỂN GIAO CÀI ĐẶT ANTIGRAVITY)

> **Khóa học:** Làm chủ Claude AI cho công việc thật  
> **Chủ đề Buổi 1:** Thiết lập bảo mật, Bộ nhớ dài hạn & Dựng Trợ lý chuyên việc với Claude Projects  
> **Thời lượng:** 2.5 Giờ (150 phút) — 100% Thực chiến  
> **Tài liệu thực hành:** Bộ tài liệu mẫu doanh nghiệp NovaTech (`demo-files/buoi-01`)  
> **Sản phẩm mang về:** 01 Trợ lý chuyên việc nạp sẵn quy chế & mẫu biểu + Antigravity IDE sẵn sàng trên máy  

---

## 🧭 TỔNG QUAN AGENDA BUỔI 1 (150 PHÚT)

```
[00] 15 PHÚT: Khóa này giúp bạn bớt việc gì? (Tư duy & 3 Nguyên tắc bất di bất dịch)
  ↓
[01] 30 PHÚT: Thiết lập Tài khoản, Bảo mật (Privacy First) & Bộ nhớ dài hạn (Memory)
  ↓
[02] 75 PHÚT: Dựng Trợ lý Chuyên việc với Projects (Khởi động: Gia sư Tiếng Anh + 2 Case Doanh nghiệp)
  ↓
[03] 20 PHÚT: Nhận diện Scheduled Tasks & Nghiệm thu thành phẩm Buổi 1
  ↓
[CHUYỂN GIAO] 10 PHÚT: Hướng dẫn cài đặt Antigravity IDE trên máy tính cho Buổi 2
```

---

## PHẦN 0: KHÓA NÀY GIÚP BẠN BỚT VIỆC GÌ? (15 PHÚT)

### 1. Vấn đề quen thuộc khi dùng AI hiện nay
- ❌ **Gõ vài câu bâng quơ:** Mở khung chat lên hỏi chung chung, nhận về câu trả lời văn vở, dài dòng.
- ❌ **Mất thời gian sửa lại:** Số liệu thì mơ hồ hoặc bịa đặt, định dạng lung tung, không áp dụng được ngay.
- ❌ **Quay về làm tay:** Tắt tab chat AI và tiếp tục ngồi gõ Word, Excel thủ công hàng giờ như cũ.
- ❌ **Mất ngữ cảnh liên tục:** Mỗi lần mở chat mới lại phải đính kèm và nhắc lại bảng giá từ đầu.

### 2. Ba (03) Nguyên tắc bất di bất dịch của lớp học
* **Nguyên tắc 1: Làm trên việc thật của bạn.** Không làm bài tập mẫu vô thưởng vô phạt. Lấy đúng file báo cáo, bảng giá, hợp đồng của công ty ra làm.
* **Nguyên tắc 2: Mỗi buổi có sản phẩm mang về dùng ngay.** Hết 2.5 tiếng là có sẵn công cụ hoặc trợ lý để sáng mai mang lên văn phòng làm việc luôn.
* **Nguyên tắc 3: Không cần biết lập trình.** Bạn chỉ cần hiểu rõ chuyên môn công việc của mình, toàn bộ phần kỹ thuật để AI lo.

---

## PHẦN 1: THIẾT LẬP TÀI KHOẢN, BẢO MẬT & BỘ NHỚ (30 PHÚT)

### 1.1. Khóa bảo mật dữ liệu công việc (Privacy First)
* **Tại sao phải tắt tính năng này ngay?**
  * Mặc định trên nhiều nền tảng AI, nội dung bạn trò chuyện có thể được thu thập để huấn luyện (train) các mô hình AI thế hệ tiếp theo.
  * **Rủi ro doanh nghiệp:** Nếu không tắt, các dữ liệu nhạy cảm như báo cáo tài chính nội bộ, danh sách khách hàng, bảng lương hay công thức giá vốn có nguy cơ bị rò rỉ vào tập dữ liệu công khai!
  * **Cam kết khi tắt xong:** Toàn bộ dữ liệu chat và tài liệu tải lên hoàn toàn nằm trong không gian riêng tư của bạn, nhà cung cấp cam kết không dùng để huấn luyện AI.
* **Bốn (04) bước thao tác khóa bảo mật ngay lập tức trên Claude:**
  1. Bấm vào **Ảnh đại diện / Tên tài khoản** ở góc dưới bên trái màn hình ➡️ Chọn **Settings**.
  2. Ở danh mục bên trái bảng Settings, bấm chọn mục **Privacy**.
  3. Tìm dòng tùy chọn: **"Help improve our AI models"**.
  4. Gạt công tắc sang trạng thái **TẮT (Switch OFF)** — Công tắc chuyển sang màu xám.

---

### 1.2. Cài đặt Profile cá nhân (Settings > General)
Giúp Claude biết xưng hô chuẩn mực và hiểu bạn đang nhìn nhận bài toán dưới góc độ chuyên môn nào:
- **Full name:** `[Họ và tên của bạn]`
- **What should Claude call you?:** `[Anh Nam / Chị Lan / Em...]`
- **What best describes your work?:** `[Management / Finance / Sales / Legal...]`

---

### 1.3. Năm (05) Nguyên tắc ứng xử gốc (Instructions for Claude)
Cuộn xuống ô **Instructions for Claude** trong tab General, dán nguyên văn bộ quy tắc này để dập tắt thói quen chào hỏi rườm rà hay tự ý bịa số liệu:

```text
1. Luôn phản hồi bằng tiếng Việt chuẩn mực, gãy gọn, chuyên nghiệp.
2. Đi thẳng vào câu trả lời và giải pháp. Không mở đầu bằng lời chào rườm rà ("Chào bạn, tôi rất vui..."), không kết thúc bằng lời cảm ơn sáo rỗng.
3. Khi phân tích hoặc lập kế hoạch, ưu tiên trình bày bằng gạch đầu dòng và bảng biểu để dễ theo dõi.
4. Nếu yêu cầu thiếu dữ liệu cần thiết, hãy đặt câu hỏi ngắn để làm rõ thay vì tự đoán mò.
5. Tuyệt đối không tự bịa thông tin, số liệu, tên người hoặc điều khoản khi tài liệu không đề cập.
```

---

### 1.4. Kích hoạt và nạp Ký ức công việc (Memory)
* **Bản chất tính năng Memory:**
  * Cuốn sổ tay dài hạn: Tự động ghi nhận thói quen, dự án đang chạy, phong cách làm việc qua từng buổi chat.
  * Toàn quyền kiểm soát: Có thể chủ động nạp thêm, mở danh sách ra xem và bấm nút xóa bất kỳ lúc nào khi dự án kết thúc.
  * Tùy chọn *"Include sensitive topics in memory"* luôn giữ **TẮT** để tránh lưu thông tin tài khoản cá nhân.
* **Cách bật:** Vào **Settings** ➡️ Chọn **Memory** (biểu tượng đồng hồ) ➡️ Gạt **"Generate memory from chats"** sang **BẬT (Màu xanh)**.
* **Mẫu nạp ký ức bối cảnh công ty (Ví dụ NovaTech):**
  Cuộn xuống ô nhập dưới cùng của trang Memory, dán đoạn thông tin sau:

```text
Tôi đang phụ trách phát triển kinh doanh tại Công ty Cổ phần Giải pháp Số NovaTech. Sản phẩm chính là phần mềm quản trị doanh nghiệp NovaERP và hạ tầng Cloud. Ưu tiên phong cách làm việc nhanh gọn, các báo giá luôn cần chiết tính rõ ràng giá trước thuế, mức chiết khấu và thuế VAT 10%.
```

---

## PHẦN 2: DỰNG TRỢ LÝ CHUYÊN VIỆC VỚI CLAUDE PROJECTS (75 PHÚT)

### 2.1. Bước chuyển thế hệ: Chatbot vs AI Agent (Cộng sự tự chủ)

| Tiêu chí | Chế độ Chat (Hỏi - Đáp thông thường) | Chế độ Cowork / AI Agent (Cộng tác tự chủ) |
|---|---|---|
| **1. Cơ chế tương tác** | Tuần tự từng câu 1:1. Hỏi câu nào trả lời câu đó. | **Giao việc theo mục tiêu (Goal-driven)**, tự chia nhỏ thành chuỗi hành động đa bước. |
| **2. Mức độ rảnh tay** | **Thấp:** Phải ngồi trực màn hình để bấm câu lệnh tiếp theo. | **Cao:** Giao việc xong có thể đóng máy/rời đi, AI tự chạy ngầm đến khi hoàn thành. |
| **3. Môi trường thực thi** | Chạy trực tiếp trên giao diện web thông thường. | Chạy trong một **Cloud Sandbox (Hộp cát cô lập)** an toàn. |
| **4. Khả năng tạo file** | Chỉ xuất văn bản text, phải tự copy-paste vào Word/Excel. | **Tự tạo file thật:** Xuất file Word (.docx) chuẩn format, Excel (.xlsx) có công thức. |
| **5. Tính đa nền tảng** | Bị ràng buộc trên từng phiên làm việc cụ thể. | Giao việc trên máy tính, ra ngoài **xem tiến độ trên điện thoại**. |
| **6. Tự động hóa** | Tắt trình duyệt là phiên làm việc dừng lại. | Kết hợp hoàn hảo với **Scheduled Tasks** để hẹn giờ tự chạy định kỳ trên Cloud. |

#### Ma trận ra quyết định: Khi nào chọn Chat, khi nào chọn Cowork?
* **Chọn Chat thường khi:**
  * Tác vụ nhanh 1 lần (One-off): Dịch nhanh 1 đoạn email, sửa lỗi chính tả, hỏi nghĩa 1 từ.
  * Động não & Lên ý tưởng (Brainstorming): Cần phản hồi tức thì qua lại giữa người và AI.
  * Hỏi đáp nhanh dữ liệu đơn lẻ: Tra cứu 1 con số cụ thể trong tài liệu.
* **Chọn Cowork / Agent khi:**
  * Tạo văn bản hoàn chỉnh (.docx): Tra bảng giá + tính chiết khấu + soạn Thư chào giá in ra ký ngay.
  * Đối soát chéo tài liệu phức tạp: Đọc hợp đồng 5 trang + đối chiếu Tiêu chuẩn nội bộ + xuất Bảng cảnh báo rủi ro.
  * Tác vụ định kỳ tự chạy trên Cloud: Hẹn giờ 17h thứ Sáu tự động tổng hợp báo cáo tuần.

---

### 2.2. Claude Projects: Giải pháp "Ngăn kéo hồ sơ" chuyên việc
- **Nỗi khổ chat thường:** Cứ bấm chat mới là "quên sạch", phải đính kèm lại bảng giá; hôm nay dặn chiết khấu tối đa 8%, ngày mai mở chat mới nó lại quên và tự ý giảm 15%!
- **Giải pháp Projects:**
  - Mỗi đầu việc lớn là 1 Project riêng (Project *"Báo giá B2B"*, Project *"Pháp chế Hợp đồng"*).
  - Nạp tài liệu 1 lần duy nhất vào mục **Context / Project Knowledge**.
  - **Project Instructions:** Đóng vai trò như "Sổ tay quy trình" (Job Description) chỉ rõ từng bước nhân sự AI phải tuân thủ.

#### Bí quyết viết Project Instructions cho người mới tinh:
```
[Bước 1] Nạp tài liệu (PDF, Word) vào Context của Project.
   ↓
[Bước 2] Gõ quy trình bằng tiếng Việt đời thường: "Bước 1 làm gì, Bước 2 tính gì, Bước 3 duyệt sao, Output thế nào..."
   ↓
[Bước 3] Nhờ Claude tự viết Instructions: "Đọc các file trong Context và viết lại thành bản Project Instructions chuẩn chỉnh cho tôi" → Copy dán vào ô Instructions là xong!
```

---

### 2.3. Khởi động trực quan (Mini Case): Dựng Trợ lý "Gia sư Tiếng Anh Cá nhân hóa" (15 phút)

#### Tại sao bắt đầu bằng ví dụ này?
- **Gần gũi, ai cũng hiểu và có nhu cầu:** Giúp học viên ngay lập tức hiểu bản chất của Project mà không bị choáng ngợp bởi thuật ngữ hay tài liệu doanh nghiệp phức tạp.
- **Thấy ngay sự khác biệt giữa Chat thường vs Project:**
  - *Nếu dùng Chat thường:* Ngày nào cũng phải vào gõ lại câu lệnh dài dòng: *"Tôi đang học tiếng Anh, hãy sửa ngữ pháp, phiên âm và đọc mẫu..."*. Hôm sau mở chat mới là AI quên sạch hôm qua mình đã học từ gì, trình độ ra sao.
  - *Khi dùng Project:* Cài đặt đúng 1 lần duy nhất thành một **"Gia sư 1-1"**. Mỗi ngày vào học chỉ việc quăng câu mình vừa đặt, AI tự động chấm, sửa, phiên âm và theo dõi tiến độ.

#### Bước 1: Dùng tiếng Việt đời thường để Claude tự viết Instructions
Học viên mở một Project mới đặt tên là `Gia sư Tiếng Anh Cá nhân hóa (Daily English Mentor)`, mở khung chat của Project và gõ đúng mong muốn bằng ngôn ngữ tự nhiên:

```text
Tôi muốn tạo một Project trên Claude để làm Gia sư tiếng Anh cá nhân cho tôi. Mục tiêu là tôi muốn giỏi tiếng Anh trong 3 tháng bằng phương pháp mỗi ngày tự đặt 10 - 20 câu. Khi tôi gửi câu lên, gia sư phải:
1. Chỉ ra lỗi sai ngữ pháp, chính tả và sửa lại cho đúng.
2. Nâng cấp câu đó thành cách nói tự nhiên của người bản xứ (Natural/Native).
3. Hướng dẫn phát âm bằng phiên âm quốc tế IPA và mẹo ngắt nhịp ngữ điệu để tôi bắt chước đọc theo (Shadowing).
4. Giải thích từ vựng và cấu trúc đáng chú ý trong câu.
5. Luôn động viên và kết thúc bằng 1 câu đố phản xạ (Daily Quick Quiz).
Hãy đọc các yêu cầu trên và viết lại thành một bản Project Instructions thật chuyên nghiệp, chặt chẽ để tôi dán vào cài đặt Project nhé.
```

#### Bước 2: Bản Project Instructions hoàn chỉnh (Dán vào ô Instructions của Project)

```text
Bạn là "Alex" - Gia sư Tiếng Anh Cá nhân hóa chuyên sâu, tận tâm và am hiểu phương pháp giảng dạy hiện đại (Shadowing & Deliberate Practice).

MỤC TIÊU CỦA BẠN:
Giúp tôi thành thạo phản xạ viết và nói tiếng Anh trong 3 tháng thông qua việc sửa bài đặt câu hàng ngày, chuẩn bị nền tảng để thi chứng chỉ chính quy.

QUY TRÌNH PHẢN HỒI MỖI KHI TÔI GỬI CÂU:
Với mỗi câu tôi gửi, bạn PHẢI phân tích theo đúng cấu trúc 4 phần sau:

1. ĐÁNH GIÁ & SỬA LỖI (Grammar & Correction):
   - Câu gốc của tôi: [Trích lại]
   - Câu sửa chuẩn ngữ pháp: [Câu đã sửa đúng]
   - Giải thích ngắn gọn lỗi sai: (Sai thì, sai giới từ, dùng từ chưa chuẩn ngữ cảnh...)

2. PHIÊN BẢN TỰ NHIÊN NHƯ NGƯỜI BẢN XỨ (Native Way):
   - Cung cấp 1-2 cách diễn đạt tự nhiên hơn mà người bản xứ hay dùng hàng ngày.

3. HƯỚNG DẪN LUYỆN PHÁT ÂM (Pronunciation & Shadowing):
   - Phiên âm IPA chuẩn cho toàn bộ câu (kèm đánh dấu trọng âm chính).
   - Chỉ dẫn ngắt nhịp (/) và nhấn từ khóa (Keyword Stress) để tôi đọc theo có ngữ điệu tự nhiên.

4. TỪ VỰNG & CẤU TRÚC ĐÁNG CHÚ Ý:
   - Liệt kê 1-2 từ vựng hoặc collocations đắt giá trong câu.

QUY TẮC BẮT BUỘC:
- Luôn giữ văn phong kiên nhẫn, khuyến khích người học.
- Trình bày dạng bảng hoặc gạch đầu dòng rõ ràng, sạch đẹp, dễ đọc trên điện thoại.
- Kết thúc buổi sửa bài bằng 01 "Daily Quick Quiz" (1 câu tình huống ngắn yêu cầu tôi dịch hoặc đặt câu tiếp) để tạo phản xạ liên tục.
```

#### Bước 3: Thực hành trải nghiệm ngay tại lớp (Siêu nhàn, chỉ 5 giây)
Học viên vào Project, không cần nhắc lại bất kỳ câu lệnh nào, chỉ việc gõ bài tập:

```text
Hôm nay mình đặt 3 câu về chủ đề công việc văn phòng:
1. I am very busy today because my boss give me a lot of task.
2. We need to delay the meeting to next Monday.
3. Can you send me the price table as soon as fast?
```

* **Kết quả:** Claude lập tức chấm 4 bước, chỉ ra lỗi sai (`give -> gave/has given`, `a lot of tasks`, `as soon as possible`), gợi ý câu tự nhiên (`I'm swamped with work today...`), cung cấp phiên âm IPA và hướng dẫn ngắt nhịp để học viên nhại theo.
* **Mẹo nghe phát âm:** Học viên có thể bấm biểu tượng cái loa (hoặc tính năng **Read Aloud** trên ứng dụng điện thoại/web) để nghe AI đọc mẫu câu chuẩn bản xứ và luyện đọc theo (kỹ thuật Shadowing).

---

### 2.4. Case Study 1: Trợ lý Báo giá & Xử lý Deal Bán hàng B2B (NovaTech)

#### Bối cảnh & Bộ 3 tài liệu nạp vào Context:
1. `Bảng giá phần mềm quản trị và giải pháp số 2026 - NovaTech.pdf` (Đơn giá các gói Starter, Professional, Enterprise; phụ phí đào tạo tại chỗ 15 triệu/3 buổi; cam kết SLA 99.9%).
2. `Quy chế chiết khấu thương mại và chính sách thanh toán - NovaTech.docx` (Chiết khấu bậc thang 0% - 12%, giảm thêm 5% khi trả 100%, phụ thu 4% nếu chia 3 đợt; phân cấp thẩm quyền duyệt giá).
3. `Mẫu thư chào giá và thỏa thuận dịch vụ chuẩn - NovaTech.docx` (Mẫu biểu nhận diện thương hiệu chuẩn có thông tin tài khoản Vietcombank).

#### Quy trình 4 bước kiểm soát Deal & Phân cấp thẩm quyền:
* **Bước 1:** Phân tích nhu cầu (Số user gói phần mềm + dịch vụ đào tạo đi kèm).
* **Bước 2:** Chiết tính giá (Đơn giá gốc - chiết khấu bậc thang + phụ phí dòng tiền nếu chia đợt).
* **Bước 3: Kiểm soát thẩm quyền phê duyệt giảm giá:**
  * `0% - 5%`: [Thẩm quyền Sales tự quyết]
  * `5.1% - 8%`: [Cần Trưởng phòng Kinh doanh duyệt]
  * `Trên 8%`: [VƯỢT THẨM QUYỀN - Bắt buộc CEO ký duyệt]
* **Bước 4:** Soạn thảo Thư chào giá chuẩn theo đúng mẫu.

---

#### 📋 Prompt nhờ Claude viết Instructions Trợ lý Báo giá:
```text
Hiện tôi cần viết Instructions cho project này để làm trợ lý báo giá phần mềm B2B cho công ty NovaTech.
Quy trình xử lý tôi muốn như sau:
- Khi tôi đưa thông tin yêu cầu của khách hàng vào (số lượng người dùng, nhu cầu đào tạo, phương thức thanh toán, mức giảm giá khách đòi...):
  + Bước 1: Tra đúng gói phần mềm trong Bảng giá và tính tổng giá niêm yết.
  + Bước 2: Tính chiết khấu theo Quy chế chiết khấu (giảm thêm nếu trả 100%, phụ thu nếu chia 3 đợt).
  + Bước 3: Kiểm soát thẩm quyền phê duyệt giảm giá (dưới 5% là Sales tự quyết; 5% - 8% cần Trưởng phòng duyệt; trên 8% là vượt quyền, bắt buộc CEO duyệt).
  + Bước 4: Soạn Thư chào giá hoàn chỉnh theo đúng cấu trúc của Mẫu thư chào giá trong Context.
  + Chống ảo giác: Tính chính xác từng con số, nêu rõ giá trước thuế, VAT 10% và tổng thanh toán; đính kèm số tài khoản Vietcombank chuẩn.
Bạn hãy đọc kỹ 3 file tài liệu trong Context và viết lại thành một bản Project Instructions thật chuẩn chỉnh, chuyên nghiệp để tôi copy dán vào ô Instructions nhé.
```

---

#### 🚀 Thực hành Deal Nam Hải liên tục trong 1 phiên chat duy nhất:

* **Tình huống 1: Tiếp nhận & Bóc tách Deal phức tạp**
  ```text
  Khách hàng là Công ty Cổ phần Thương mại Dịch vụ Nam Hải vừa gửi yêu cầu sau:
  "Bên anh có 45 nhân sự cần dùng phần mềm quản lý bán hàng và kho. Anh muốn bên em đến đào tạo trực tiếp tại văn phòng công ty anh ở Quận Bình Thạnh (3 buổi). Anh muốn thanh toán làm 3 đợt. Do ngân sách có hạn, bên em có giảm được 15% tổng hóa đơn không? Báo giá gấp cho anh nhé."

  Hãy xử lý yêu cầu này theo đúng quy chế và tư vấn cách xử lý giúp tôi.
  ```

* **Tình huống 2: Xử lý khi khách ép giá so sánh đối thủ** *(Gõ tiếp ngay bên dưới)*
  ```text
  Khách hàng Nam Hải nhắn lại: "Anh thấy bên đối thủ khác đang chào gói tính năng tương tự rẻ hơn bên em tầm 20%. Em xem có bớt thêm được không chứ mức giá 73 triệu này sếp anh khó duyệt lắm?"

  Hãy giúp tôi soạn một tin nhắn phản hồi khéo léo, giữ vững mức giá dựa trên cam kết chất lượng Uptime SLA 99.9% và dịch vụ đào tạo tại chỗ của chúng ta, đồng thời gợi ý khách phương án thanh toán 100% để hưởng ưu đãi tối đa.
  ```

* **Tình huống 3: Lập bảng so sánh 2 phương án tài chính** *(Gõ tiếp ngay bên dưới)*
  ```text
  Để khách dễ trình Tổng Giám đốc của họ duyệt ngân sách, hãy lập cho tôi một BẢNG SO SÁNH 2 PHƯƠNG ÁN tài chính thật trực quan:
  - Phương án A (Thanh toán 100% một lần): Hưởng mức chiết khấu tối đa hợp lệ (8% theo phê duyệt của Trưởng phòng + 5% ưu đãi thanh toán sớm).
  - Phương án B (Thanh toán làm 3 đợt): Không được ưu đãi thanh toán sớm và phải chịu phụ phí dòng tiền 4%.
  Phân tích rõ số tiền cụ thể khách tiết kiệm được nếu chọn Phương án A để họ thấy rõ lợi ích dòng tiền.
  ```

* **Tình huống 4: Xuất Thư chào giá chuẩn để ký ngay** *(Gõ tiếp ngay bên dưới)*
  ```text
  Khách hàng Nam Hải đã đồng ý chốt theo Phương án A (Thanh toán 100% để hưởng ưu đãi tối đa).
  Hãy xuất toàn bộ Thư chào giá chính thức theo đúng cấu trúc của Mẫu thư chào giá trong Context:
  - Điền đầy đủ pháp nhân khách hàng (Công ty CP Thương mại Dịch vụ Nam Hải).
  - Chi tiết dịch vụ: Gói Professional (50 users) + 3 buổi đào tạo tại chỗ ở Bình Thạnh.
  - Bảng chiết tính số tiền cuối cùng sau thuế VAT 10%.
  - Thông tin tài khoản thụ hưởng Vietcombank chuẩn của NovaTech.
  - Người ký đại diện: Nguyễn Văn Hùng (Trưởng phòng Kinh doanh).
  Xuất văn bản hoàn chỉnh để tôi in ra trình ký đóng dấu ngay.
  ```

---

### 2.5. Case Study 2: Trợ lý Rà soát Hợp đồng & Cảnh báo Rủi ro (NovaTech)

#### Bối cảnh & Bộ 3 tài liệu nạp vào Context:
1. `Bộ tiêu chuẩn rà soát pháp lý hợp đồng doanh nghiệp - NovaTech.pdf` (Nêu rõ 5 "Ranh giới đỏ" bảo vệ quyền lợi công ty).
2. `Mẫu hợp đồng dịch vụ chuẩn của công ty - NovaTech.docx` (Hợp đồng khung chuẩn đã qua luật sư rà soát).
3. `Hợp đồng dịch vụ phần mềm và hạ tầng số (Bản đối tác đề xuất).docx` (Bản dự thảo đối tác Nam Hải gửi sang gài sẵn 4 điều khoản bẫy).

#### Năm (05) Ranh giới đỏ (Red Flags) không thể nhượng bộ:
* **FLAG 1 - Phạt vi phạm:** Tối đa không quá 8% phần nghĩa vụ vi phạm (Căn cứ Điều 301 Luật Thương mại 2005). Cấm chấp nhận phạt 20%.
* **FLAG 2 - Thời hạn nợ:** Tối đa không quá 15 ngày làm việc. Không chấp nhận điều khoản thanh toán lùi vô thời hạn.
* **FLAG 3 - Sở hữu trí tuệ:** Giữ độc quyền 100% mã nguồn, thuật toán gốc cho NovaTech. Khách chỉ có quyền sử dụng (License).
* **FLAG 4 - Trần bồi thường:** Tối đa không vượt quá tổng giá trị hợp đồng trong 12 tháng gần nhất.
* **FLAG 5 - Trọng tài thương mại:** Giải quyết tranh chấp tại Trung tâm Trọng tài Quốc tế Việt Nam (VIAC) tại TP.HCM.

---

#### 📋 Prompt nhờ Claude viết Instructions Trợ lý Pháp chế:
```text
Hiện tôi cần viết Instructions cho project này để làm trợ lý pháp chế rà soát hợp đồng kinh tế cho công ty NovaTech.
Quy trình xử lý tôi muốn như sau:
- Khi tôi đính kèm một file dự thảo hợp đồng của đối tác gửi sang:
  + Bước 1: Quét toàn bộ hợp đồng và đối soát với file "Bộ tiêu chuẩn rà soát pháp lý hợp đồng doanh nghiệp" trong Context.
  + Bước 2: Bắt các điều khoản bất lợi, vi phạm pháp luật, đặc biệt kiểm tra nghiêm ngặt 5 ranh giới đỏ (mức phạt tối đa 8% theo Điều 301 Luật Thương mại, thời hạn nợ tối đa 15 ngày, giữ độc quyền mã nguồn cho NovaTech, trọng tài VIAC tại TP.HCM).
  + Bước 3: Lập bảng cảnh báo rủi ro (tên điều khoản, mức độ rủi ro, lý do vi phạm hoặc bất lợi, căn cứ điều luật).
  + Bước 4: Viết lại nguyên văn câu chữ đề xuất sửa đổi cho từng điều khoản để gửi lại đối tác đàm phán.
  + Chống ảo giác: Chỉ trích dẫn chính xác nội dung trong văn bản và luật pháp Việt Nam, không tự suy diễn.
Bạn hãy đọc kỹ 2 file tài liệu trong Context và viết lại thành một bản Project Instructions thật chuẩn chỉnh, chuyên nghiệp để tôi copy dán vào ô Instructions nhé.
```

---

#### 🚀 Thực hành thẩm định Hợp đồng đối tác (5 bước liên hoàn):

* **Bước 1: Quét nhanh tổng quan trong 10 giây**
  *(Đính kèm file `Hợp đồng dịch vụ phần mềm... (Bản đối tác đề xuất).docx`)*
  ```text
  Đối tác Nam Hải vừa gửi sang bản dự thảo Hợp đồng dịch vụ phần mềm này.
  Trước khi đi vào chi tiết, hãy đọc lướt toàn bộ hợp đồng và lập một BẢNG TỔNG QUAN TÓM TẮT các thông số trọng yếu: Giá trị hợp đồng, thời hạn thực hiện, tiến độ thanh toán, thời hạn bảo hành và cơ quan giải quyết tranh chấp.
  ```

* **Bước 2: Bắt 4 bẫy pháp lý & Bảng cảnh báo rủi ro** *(Gõ tiếp ngay bên dưới)*
  ```text
  Bây giờ, hãy đối soát toàn diện hợp đồng này với file "Bộ tiêu chuẩn rà soát pháp lý hợp đồng doanh nghiệp" trong Context của chúng ta.
  Chỉ ra chính xác các điều khoản bất lợi, gài bẫy hoặc vi phạm pháp luật Việt Nam.
  Trình bày thành BẢNG CẢNH BÁO RỦI RO gồm các cột: Tên điều khoản -> Mức độ rủi ro (Nghiêm trọng / Trung bình) -> Lý do bất lợi hoặc vi phạm điều luật nào.
  ```

* **Bước 3: Viết lại câu chữ đề xuất sửa đổi (Redline)** *(Gõ tiếp ngay bên dưới)*
  ```text
  Đối với 4 điều khoản có rủi ro nghiêm trọng ở trên (Điều 6, Điều 7, Điều 9, Điều 11), hãy viết lại nguyên văn câu chữ đề xuất sửa đổi (redline) để chuyên viên kinh doanh copy gửi sang cho phòng pháp chế Nam Hải đàm phán lại. Câu từ cần chắc chắn về mặt pháp lý nhưng giữ văn phong lịch sự, thiện chí hợp tác.
  ```

* **Bước 4: Soạn Email Ngoại giao gửi đối tác** *(Gõ tiếp ngay bên dưới)*
  ```text
  Hãy giúp tôi soạn một email chính thức từ Ban Pháp chế & Ban Giám đốc NovaTech gửi người phụ trách hợp đồng của Nam Hải. Email cần trình bày trang trọng, lịch sự, giải thích rõ lý do vì sao chúng ta cần điều chỉnh 4 điều khoản này (đặc biệt nêu rõ mức phạt 20% là trái Điều 301 Luật Thương mại Việt Nam) và đính kèm phương án sửa đổi để hai bên nhanh chóng tiến tới ký kết.
  ```

* **Bước 5: Checklist 10 điểm an toàn trước khi ký** *(Gõ tiếp ngay bên dưới)*
  ```text
  Giả sử sau khi đàm phán, đối tác gửi lại bản hợp đồng đã chỉnh sửa. Hãy lập giúp tôi một CHECKLIST 10 ĐIỂM KIỂM TRA NHANH (dạng bảng có các cột: Tiêu chí kiểm tra, Căn cứ pháp lý/tiêu chuẩn, Trạng thái Đạt/Chưa đạt) để chuyên viên kinh doanh tự rà lại lần cuối trước khi trình Tổng Giám đốc ký kết.
  ```

---

## PHẦN 3: LÊN LỊCH TỰ ĐỘNG & NGHIỆM THU BUỔI 1 (20 PHÚT)

### 3.1. Scheduled Tasks: Hẹn giờ tác vụ tự động trên Cloud
- **Vị trí:** Góc dưới cùng bên phải của giao diện Project (khối **Scheduled** kèm biểu tượng `+`).
- **Cơ chế:** Chạy ngầm 100% trên Cloud của Anthropic vào khung giờ đã lên lịch, máy tính tắt vẫn tự chạy; chạy xong tự động gửi thông báo hoặc bản báo cáo vào Project.
- **Kịch bản ứng dụng định kỳ:**
  - *17:00 Thứ Sáu:* Tự động tổng hợp Deal Báo giá trong tuần (deal chốt vs deal kẹt).
  - *08:30 Thứ Hai:* Điểm tin & Cảnh báo văn bản pháp luật / thông tư mới ảnh hưởng đến hợp đồng công ty.

---

### 3.2. Bảng kiểm nghiệm thu Buổi 1 (Checklist thành phẩm)

#### TỰ TAY BẠN ĐÃ LÀM ĐƯỢC:
- [x] Khóa bảo mật `Help improve our AI models` (Settings > Privacy) bảo vệ dữ liệu công ty.
- [x] Thiết lập xong Profile và 5 nguyên tắc ứng xử gốc trong `Settings > General`.
- [x] Bật Memory và nạp thành công bối cảnh doanh nghiệp vào tài khoản cá nhân.
- [x] Nắm vững tư duy Cowork vs Chat để chọn đúng chế độ cho từng công việc.
- [x] Biết cách đưa quy trình ngôn ngữ nói để Claude tự viết Project Instructions chuẩn.
- [x] Dựng thành công **Trợ lý Gia sư Tiếng Anh**, trải nghiệm tính năng sửa bài và phiên âm IPA Shadowing.
- [x] Dựng thành công **Trợ lý Báo giá B2B**, nạp 3 file Context và xử lý trọn vẹn Deal Nam Hải.
- [x] Dựng thành công **Trợ lý Pháp chế**, bắt trọn 4 bẫy pháp lý và xuất Redline + Email ngoại giao.

#### HIỂU SÂU ĐỂ DÙNG LÂU DÀI:
- [x] Vì sao không nên dùng Chat thông thường ngoài trang chủ mà phải dùng Claude Projects.
- [x] Năng lực đối chiếu chéo nhiều file tài liệu (PDF, Word) cùng lúc trong Context.
- [x] Bản chất của Cloud Sandbox và khả năng tạo file thật trong Claude Cowork.
- [x] Nhận biết vị trí Scheduled Tasks để sẵn sàng cho tự động hóa ở Buổi sau.

---

## PHẦN 4: CHUYỂN GIAO CÔNG NGHỆ — CÀI ĐẶT ANTIGRAVITY CHO BUỔI 2 (10 PHÚT)

### 1. Tại sao Buổi 2 cần chuyển từ Claude Web sang Antigravity?
* **Claude Web ở Buổi 1 rất xuất sắc**, nhưng nó vẫn bị *"nhốt trong trình duyệt"*:
  * Muốn đọc file nào bạn phải tự bấm upload thủ công file đó.
  * Xuất file xong bạn phải bấm tải về máy.
  * Khi xử lý thư mục gồm 50 file hợp đồng hay file sao kê ngân hàng lớn, tài khoản web miễn phí sẽ bị nghẽn quota.
* **Antigravity giải phóng hoàn toàn rào cản này:**
  * **Chạm thẳng vào máy tính:** Antigravity đọc, phân loại, đổi tên và xử lý hàng loạt file Word/Excel trực tiếp trên ổ cứng laptop của bạn.
  * **Hoàn toàn miễn phí & ngữ cảnh cực lớn:** Dùng mô hình Gemini 2.0 / 3.0 với bộ nhớ context hàng triệu token.
  * **Sẵn sàng cho Buổi 2 & Buổi 3:** Tự làm bảng tính tương tác (Generative UI / Artifacts), kết nối dữ liệu thật (MCP) và tạo AI Agent tự động chạy theo quy trình.

### 2. Các bước cài đặt nhanh Antigravity IDE tại lớp:
1. Mở bộ cài đặt Antigravity IDE (hoặc truy cập đường dẫn do Mentor cung cấp).
2. Chạy file cài đặt, chọn cấu hình mặc định và bấm **Next ➡️ Finish**.
3. Đăng nhập bằng tài khoản Google cá nhân.
4. Mở khung chat Antigravity, gõ câu lệnh kiểm tra đầu tiên:
   ```text
   Xin chào! Hãy kiểm tra hệ thống và xác nhận bạn đã sẵn sàng làm việc cùng tôi trên máy tính này.
   ```
5. Nhìn thấy Agent phản hồi sẵn sàng là hoàn tất 100%!

### 3. Dặn dò học viên chuẩn bị cho Buổi 2:
- Gom sẵn một thư mục công việc thực tế trên máy tính (ví dụ: các file báo giá, hợp đồng nháp, hoặc file Excel số liệu đối soát visa / chi phí) để Buổi 2 đưa Antigravity vào xử lý tự động!
