# 📘 BÀI TẬP VỀ NHÀ — SKL103: KỸ NĂNG LÀM VIỆC NHÓM
## PHÂN TÍCH KHỦNG HOẢNG PHÂN CÔNG & TÁI THIẾT LẬP QUY CHUẨN (RACI & TWA)

---

## 0. THÔNG TIN BÀI LÀM

| Mục | Nội dung |
| :--- | :--- |
| **Học phần** | SKL103 – Kỹ năng làm việc nhóm |
| **Bài tập** | BTVN Session 01 – Phân tích khủng hoảng RACI & TWA |
| **Nhóm phân tích** | Hoàng (NT), Huy, Mai, Linh |
| **Môn học** | Nhập môn Công nghệ Thông tin |
| **Đề tài** | Tìm hiểu các thiết bị phần cứng máy tính và xu hướng công nghệ số |
| **Sản phẩm** | Word 8 trang + Slide 12 trang |
| **Hạn nộp** | Sau 2 tuần |
| **Vai trò của người làm bài** | Cố vấn kỹ năng làm việc nhóm |
| **Tên file nộp** | `SKL103_BTVN_Session01_[HoVaTen]` |

> 🎯 **Nhiệm vụ tổng thể:** "Giải cứu" nhóm của Hoàng khỏi khủng hoảng phân công trách nhiệm bằng cách chẩn đoán sai lầm → tái thiết kế RACI → thiết lập TWA cấp bách.

---

## 1. NHIỆM VỤ 1 — CHẨN ĐOÁN 3 SAI LẦM CHÍ MẠNG (30 điểm)

### 1.0. Tổng quan tình trạng nhóm sau 10 ngày

```text
┌─────────────────────────────────────────────────────────────────┐
│           🚨 TÌNH TRẠNG KHỦNG HOẢNG SAU 10 NGÀY                 │
│                                                                 │
│   ┌──────────────┐   ┌──────────────┐   ┌──────────────┐       │
│   │  SLIDE TRỐNG │   │ HOÀNG KIỆT   │   │ MAI BỊ CÔ    │       │
│   │  Không có    │   │ SỨC          │   │ LẬP          │       │
│   │  trang nào   │   │ Cáu gắt      │   │ Không buồn   │       │
│   │              │   │              │   │ đọc tin nhắn │       │
│   └──────────────┘   └──────────────┘   └──────────────┘       │
│                                                                 │
│   ❌ Lark: chỉ thả tim, seen, không ai trả lời                  │
│   ❌ Không có TWA: "Cứ làm đi, gần đến hạn thì nộp"            │
└─────────────────────────────────────────────────────────────────┘
```

---

### 1.1. SAI LẦM #1 — Hai chữ A ở cùng một đầu việc (Slide)

#### 📌 Bối cảnh sai lầm

| Mục | Nội dung |
| :--- | :--- |
| **Đầu việc số 3** | Thiết kế Slide trình chiếu PowerPoint (12 slide) |
| **Người được gán** | Linh **&** Huy |
| **Vai trò RACI** | **A (Linh) & A (Huy)** |
| **Hậu quả** | Đến sát ngày nộp, slide vẫn **chưa có trang nào** |
| **Lý do hai bên đưa ra** | Linh nghĩ Huy làm · Huy nghĩ Linh làm |

#### 🔍 Phân tích nguyên nhân gốc rễ

| # | Nguyên nhân | Giải thích |
| :---: | :--- | :--- |
| 1 | **Vi phạm nguyên tắc "1 chữ A duy nhất" của RACI** | RACI quy định mỗi đầu việc **chỉ có DUY NHẤT 1 người chịu trách nhiệm chính**. Khi có 2 chữ A → không ai thực sự chịu trách nhiệm. |
| 2 | **Hiệu ứng "trách nhiệm khuếch tán" (Diffusion of Responsibility)** | Khi có ≥ 2 người cùng chịu trách nhiệm, mỗi người đều nghĩ *"người kia sẽ làm"* → **không ai làm**. |
| 3 | **Không có ai đóng vai trò "chốt cuối"** | Không có người kiểm tra chất lượng, không có ai đôn đốc tiến độ → slide rơi vào vùng xám. |
| 4 | **Không có deadline nội bộ** | Cả hai đều chờ nhau → đến sát hạn mới phát hiện không có gì. |
| 5 | **Thiếu kênh xác nhận Closed-Loop** | Không ai nhắn *"Tôi nhận việc này"* → hiểu lầm kéo dài 10 ngày. |

#### 🧠 Mô hình minh họa hiệu ứng "2 chữ A"

```text
┌─────────────────────────────────────────────────────────────────┐
│              ⚠️ HIỆU ỨNG 2 CHỮ A (A-DUPLICATION)                │
│                                                                 │
│   LÝ THUYẾT:                                                    │
│   "Khi có 2 người cùng chịu trách nhiệm → KHÔNG AI chịu cả"    │
│                                                                 │
│   THỰC TẾ NHÓM HOÀNG:                                           │
│                                                                 │
│       ┌─────────────┐                   ┌─────────────┐        │
│       │    LINH     │                   │    HUY      │        │
│       │   "Huy sẽ   │                   │   "Linh sẽ  │        │
│       │    làm!"    │                   │    làm!"    │        │
│       └──────┬──────┘                   └──────┬──────┘        │
│              │                                  │               │
│              └──────────────┬───────────────────┘               │
│                             │                                   │
│                             ▼                                   │
│                    ┌─────────────────┐                         │
│                    │  SLIDE TRỐNG    │                         │
│                    │  0/12 trang     │                         │
│                    └─────────────────┘                         │
│                                                                 │
│   ➜ Trách nhiệm bị "khuếch tán" giữa 2 người → không ai làm.   │
└─────────────────────────────────────────────────────────────────┘
```

#### ✅ Cách khắc phục

| # | Giải pháp | Cách áp dụng cụ thể |
| :---: | :--- | :--- |
| 1 | **Chỉ định 1 chữ A duy nhất** | Chọn **Linh = A** (vì Linh phụ trách thiết kế), Huy = **R** (hỗ trợ chèn biểu đồ) |
| 2 | **Định nghĩa rõ vai trò** | Linh: chịu trách nhiệm cuối về chất lượng & tiến độ slide · Huy: hỗ trợ kỹ thuật |
| 3 | **Có deadline nội bộ** | Slide phải xong **trước hạn 2 ngày**, có check-in giữa kỳ |
| 4 | **Xác nhận Closed-Loop** | Linh nhắn *"Mình nhận việc làm slide, deadline ngày X"* |

---

### 1.2. SAI LẦM #2 — Hoàng ôm quá nhiều chữ A (Nhóm trưởng quá tải)

#### 📌 Bối cảnh sai lầm

| Đầu việc | Vai trò Hoàng tự gán | Thực chất công việc |
| :---: | :---: | :--- |
| **2** | **A + R** | Viết 8 trang Word |
| **4** | **A** | Soạn dàn ý + thuyết trình thử |
| **5** | **A** | Rà soát toàn bộ + nộp bài |
| **Tổng** | **3 chữ A + 1 chữ R** | Vừa viết, vừa duyệt, vừa nộp |

#### 🔍 Phân tích tác hại — 2 góc nhìn

##### 🔴 Tác hại đối với BẢN THÂN Hoàng

| # | Tác hại | Biểu hiện cụ thể |
| :---: | :--- | :--- |
| 1 | **Quá tải vai trò (Role Overload)** | Vừa viết 8 trang Word, vừa duyệt, vừa lo thuyết trình, vừa nộp bài → 1 người làm việc của 3–4 người |
| 2 | **Kiệt sức (Burnout)** | Sau 10 ngày làm việc liên tục → cáu gắt, mất kiểm soát cảm xúc |
| 3 | **Không thể làm tốt vai trò nhóm trưởng** | Vì ôm việc nên không còn thời gian điều phối, đôn đốc, hỗ trợ thành viên |
| 4 | **Chất lượng công việc giảm** | Làm quá nhiều → không có thời gian rà soát kỹ từng phần |
| 5 | **Stress kéo dài** | Ảnh hưởng đến sức khỏe, tinh thần, các môn học khác |
| 6 | **Dễ mắc lỗi** | Mệt mỏi → bỏ sót chi tiết, sai chính tả, thiếu slide |

##### 🔴 Tác hại đối với TINH THẦN TRÁCH NHIỆM của các bạn khác

| # | Tác hại | Biểu hiện cụ thể |
| :---: | :--- | :--- |
| 1 | **Hình thành tâm lý ỷ lại** | *"Đã có Hoàng lo rồi, mình không cần lo"* |
| 2 | **Mất cơ hội phát triển** | Huy, Mai, Linh không được giao việc A → không học được kỹ năng chịu trách nhiệm |
| 3 | **Giảm động lực đóng góp** | Khi mọi quyết định đều do Hoàng → các bạn thấy ý kiến mình không quan trọng |
| 4 | **Tạo khoảng cách nhóm trưởng – thành viên** | Hoàng thành "người làm hết", các bạn thành "người đứng ngoài" |
| 5 | **Khi Hoàng gặp sự cố → cả nhóm tê liệt** | Vì mọi việc dồn vào 1 người, nếu Hoàng ốm thì không ai đảm nhận được |
| 6 | **Xung đột ngầm** | Các bạn cảm thấy bị "áp đặt", Hoàng cảm thấy "mình làm hết mà không ai giúp" |

#### 🧠 Mô hình minh họa "Nút thắt cổ chai" (Bottleneck)

```text
┌─────────────────────────────────────────────────────────────────┐
│              ⚠️ HOÀNG LÀ "NÚT THẮT CỔ CHAI"                     │
│                                                                 │
│   CÔNG VIỆC CHẢY VÀO:                                           │
│   ┌──────┐  ┌──────┐  ┌──────┐  ┌──────┐                       │
│   │Việc 2│  │Việc 4│  │Việc 5│  │Việc 1│  ...                  │
│   └──┬───┘  └──┬───┘  └──┬───┘  └──┬───┘                       │
│      │         │         │         │                            │
│      └─────────┴────┬────┴─────────┘                            │
│                     │                                           │
│                     ▼                                           │
│              ┌─────────────┐                                    │
│              │   HOÀNG     │  ← Một mình xử lý tất cả          │
│              │  (Quá tải)  │                                    │
│              └──────┬──────┘                                    │
│                     │                                           │
│                     ▼                                           │
│              ┌─────────────┐                                    │
│              │  KIỆT SỨC   │  ← Burnout sau 10 ngày            │
│              │  CÁU GẮT    │                                    │
│              └─────────────┘                                    │
│                                                                 │
│   ➜ Khi 1 người ôm quá nhiều → cả nhóm bị ảnh hưởng.          │
└─────────────────────────────────────────────────────────────────┘
```

#### 📊 Bảng so sánh phân bổ chữ A — SAI vs ĐÚNG

| Đầu việc | ❌ SAI (Hoàng ôm hết) | ✅ ĐÚNG (Chia đều) |
| :---: | :---: | :---: |
| 1 | *(không có A)* | **Huy = A** |
| 2 | **Hoàng = A** | **Hoàng = A** |
| 3 | Linh + Huy = A (trùng) | **Linh = A** |
| 4 | **Hoàng = A** | **Mai = A** |
| 5 | **Hoàng = A** | **Hoàng = A** *(nhưng chỉ 1 việc)* |
| **Tổng chữ A** | Hoàng: 4 · Linh: 1 · Huy: 1 · Mai: 0 | Hoàng: 2 · Huy: 1 · Linh: 1 · Mai: 1 |

#### ✅ Cách khắc phục

| # | Giải pháp | Cách áp dụng cụ thể |
| :---: | :--- | :--- |
| 1 | **Chia chữ A cho các thành viên** | Mỗi bạn giữ ít nhất 1 chữ A → ai cũng có trách nhiệm chính |
| 2 | **Hoàng chỉ giữ 2 chữ A tối đa** | Việc 2 (Word) + Việc 5 (nộp bài) – 2 việc quan trọng nhất |
| 3 | **Phân quyền rõ ràng** | Hoàng là **điều phối**, không phải **người làm hết** |
| 4 | **Tạo cơ chế kiểm tra chéo** | Mỗi việc có 1 chữ A + 1 chữ C (người góp ý) → không ai làm một mình |

---

### 1.3. SAI LẦM #3 — Mai chỉ được gán duy nhất chữ I (Cô lập thành viên)

#### 📌 Bối cảnh sai lầm

| Mục | Nội dung |
| :--- | :--- |
| **Phân công cho Mai** | *"Mai theo dõi khi nào nhóm cần thì giúp"* |
| **Vai trò RACI** | **I (Informed)** – chỉ nhận thông báo |
| **Số đầu việc Mai tham gia** | **0/5 đầu việc** (không có R, không có A, không có C) |
| **Hậu quả** | Mai cảm thấy mình là **người thừa**, dần không buồn đọc tin nhắn nhóm |

#### 🔍 Phân tích nguyên nhân gốc rễ

| # | Nguyên nhân | Giải thích |
| :---: | :--- | :--- |
| 1 | **Chỉ gán chữ I = Không có vai trò thực chất** | "Informed" chỉ là **nhận thông báo**, không đóng góp, không được hỏi ý kiến |
| 2 | **Cụm từ "khi nào nhóm cần thì giúp" là mơ hồ** | Không có việc cụ thể → Mai không biết khi nào cần giúp, giúp cái gì |
| 3 | **Không có R = Không có việc trực tiếp làm** | Mai không có sản phẩm đầu ra → không có gì để đóng góp |
| 4 | **Không có A = Không có trách nhiệm chính** | Mai không chịu trách nhiệm về bất cứ phần nào |
| 5 | **Không có C = Không được hỏi ý kiến** | Ý kiến của Mai không được ai hỏi → cảm thấy không quan trọng |
| 6 | **Bị loại khỏi vòng lặp làm việc** | Mai chỉ đứng ngoài nhìn → dần mất kết nối với nhóm |

#### 🧠 Mô hình minh họa "Cô lập thành viên"

```text
┌─────────────────────────────────────────────────────────────────┐
│              ⚠️ MAI BỊ CÔ LẬP KHỎI NHÓM                         │
│                                                                 │
│   VÒNG TRÒN LÀM VIỆC CỦA NHÓM:                                  │
│                                                                 │
│              ┌──────────────────────┐                           │
│              │   HOÀNG ◄──► HUY     │                           │
│              │      ▲          ▲    │                           │
│              │      │          │    │                           │
│              │      ▼          ▼    │                           │
│              │   LINH    ◄──► ?    │                           │
│              └──────────────────────┘                           │
│                                                                 │
│                    ┌──────────┐                                 │
│                    │   MAI    │  ← ĐỨNG NGOÀI VÒNG TRÒN         │
│                    │  (Chỉ I) │     Chỉ nhận thông báo          │
│                    └──────────┘                                 │
│                                                                 │
│   ➜ Không có R, không có A, không có C → Mai không thuộc nhóm. │
└─────────────────────────────────────────────────────────────────┘
```

#### 📊 Bảng phân tích tác động của việc chỉ gán chữ I

| Khía cạnh | Hậu quả ngắn hạn | Hậu quả dài hạn |
| :--- | :--- | :--- |
| **Đóng góp** | Mai không có sản phẩm cụ thể | Nhóm mất đi 1 nguồn lực (25% nhân sự) |
| **Tâm lý** | Mai cảm thấy thừa thãi | Mai mất động lực, không muốn tham gia |
| **Quan hệ nhóm** | Mai dần xa cách | Nhóm chia rẽ, mất đoàn kết |
| **Kỹ năng** | Mai không được rèn luyện kỹ năng làm việc nhóm | Mai không phát triển được kỹ năng cần thiết |
| **Trách nhiệm** | Không ai để ý Mai không làm gì | Đến lúc cần thì Mai không sẵn sàng |
| **Điểm số** | Mai không có đóng góp → khó đánh giá công bằng | Mai bị thiệt thòi khi chấm điểm cá nhân |

#### 📌 Vì sao "chỉ gán chữ I" là SAI?

| # | Lý do | Giải thích |
| :---: | :--- | :--- |
| 1 | **Chữ I không tạo ra giá trị** | Chỉ nhận thông báo ≠ Đóng góp |
| 2 | **Chữ I không có sản phẩm đầu ra** | Không có gì để kiểm tra, để đánh giá |
| 3 | **Chữ I không tạo kết nối** | Không được hỏi ý kiến (C), không được làm (R) |
| 4 | **Chữ I không có trách nhiệm** | Không chịu trách nhiệm về bất cứ phần nào |
| 5 | **Mọi thành viên đều cần ít nhất 1 chữ R** | Nguyên tắc RACI: **ai cũng phải có việc trực tiếp làm** |

#### ✅ Cách khắc phục

| # | Giải pháp | Cách áp dụng cụ thể |
| :---: | :--- | :--- |
| 1 | **Giao cho Mai ít nhất 1 chữ R** | Ví dụ: Mai phụ trách "Soạn dàn ý và tập thuyết trình thử" |
| 2 | **Giao cho Mai 1 chữ A** | Mai chịu trách nhiệm chính về phần thuyết trình (việc 4) |
| 3 | **Cho Mai làm chữ C ở nhiều việc** | Mai góp ý cho phần Word (việc 2) và Slide (việc 3) |
| 4 | **Cụ thể hóa công việc** | Thay vì *"khi nào cần thì giúp"*, ghi rõ: *"Mai phụ trách dàn ý thuyết trình + tập thử"* |
| 5 | **Đảm bảo mọi thành viên đều có R** | Kiểm tra bảng RACI: mỗi người **ít nhất 1 chữ R** |

---

### 1.4. BẢNG TỔNG HỢP 3 SAI LẦM CHÍ MẠNG

| # | Sai lầm | Đối tượng | Nguyên nhân gốc rễ | Hậu quả | Giải pháp |
| :---: | :--- | :--- | :--- | :--- | :--- |
| **1** | **2 chữ A ở cùng 1 đầu việc** | Slide (Linh + Huy) | Vi phạm nguyên tắc "1 chữ A duy nhất" | Slide trống 0/12 trang | Chỉ định **Linh = A**, Huy = R |
| **2** | **Hoàng ôm quá nhiều chữ A** | Hoàng (việc 2, 4, 5) | Không phân quyền, không tin tưởng thành viên | Hoàng kiệt sức, các bạn ỷ lại | Chia A cho Huy, Linh, Mai |
| **3** | **Mai chỉ có chữ I** | Mai (0/5 đầu việc) | Không giao việc cụ thể, chỉ "theo dõi" | Mai bị cô lập, mất động lực | Giao Mai **1 chữ A + 1 chữ R** |

#### 🎯 Sơ đồ 3 sai lầm & cách khắc phục

```text
┌─────────────────────────────────────────────────────────────────┐
│              🔧 3 SAI LẦM → 3 GIẢI PHÁP                         │
│                                                                 │
│   ❌ SAI LẦM 1: 2 chữ A ở việc Slide (Linh + Huy)               │
│   ✅ GIẢI PHÁP: Chỉ 1 chữ A duy nhất → Linh = A                │
│                                                                 │
│   ❌ SAI LẦM 2: Hoàng ôm 4 chữ A (việc 2, 3, 4, 5)             │
│   ✅ GIẢI PHÁP: Chia A → Hoàng 2, Huy 1, Linh 1, Mai 1         │
│                                                                 │
│   ❌ SAI LẦM 3: Mai chỉ có chữ I (0/5 việc)                    │
│   ✅ GIẢI PHÁP: Mai có 1 chữ A + 1 chữ R + nhiều chữ C         │
└─────────────────────────────────────────────────────────────────┘
```

---

## 2. NHIỆM VỤ 2 — TÁI THIẾT KẾ MA TRẬN RACI CHUẨN MỰC (35 điểm)

### 2.0. Nguyên tắc thiết kế RACI chuẩn mực

```text
┌─────────────────────────────────────────────────────────────────┐
│               📐 5 NGUYÊN TẮC THIẾT KẾ RACI                     │
│                                                                 │
│   1. Mỗi dòng CHỈ CÓ DUY NHẤT 1 CHỮ A                          │
│   2. Mỗi thành viên có ÍT NHẤT 1 CHỮ R                         │
│   3. Chữ A được CHIA ĐỀU cho các thành viên                    │
│   4. Không thành viên nào chỉ có duy nhất chữ I                │
│   5. Mỗi thành viên đều có sự KẾT NỐI với nhau (C hoặc I)      │
└─────────────────────────────────────────────────────────────────┘
```

### 2.1. BẢNG MA TRẬN RACI TÁI THIẾT KẾ (5 đầu việc × 4 thành viên)

| STT | Đầu việc cụ thể | Hoàng | Huy | Linh | Mai | Hạn nộp | Yêu cầu chất lượng |
| :---: | :--- | :---: | :---: | :---: | :---: | :--- | :--- |
| **1** | Tìm tài liệu và ảnh minh họa linh kiện máy tính | **C** | **A + R** | **C** | **I** | Thứ Tư (tuần 1) | Có link nguồn rõ ràng, ảnh sắc nét |
| **2** | Soạn thảo nội dung bài báo cáo Word (8 trang) | **A + R** | **C** | **I** | **C** | Thứ Bảy (tuần 1) | Đủ bố cục, không sai chính tả |
| **3** | Thiết kế Slide trình chiếu PowerPoint (12 slide) | **C** | **R** | **A + R** | **C** | Thứ Ba (tuần 2) | Chữ to dễ đọc, hình ảnh đẹp |
| **4** | Soạn dàn ý bài nói và thuyết trình thử | **C** | **R** | **C** | **A + R** | Thứ Năm (tuần 2) | Tự tin, nói mạch lạc trong 8–10 phút |
| **5** | Rà soát toàn bộ và nộp file lên hệ thống trường | **A + R** | **I** | **C** | **C** | Thứ Sáu (tuần 2) | Đúng định dạng PDF/PPTX, đúng hạn |

> 📌 **Ký hiệu:** **R** = Trực tiếp làm · **A** = Chịu trách nhiệm chính (duy nhất 1/dòng) · **C** = Được hỏi ý kiến · **I** = Nhận thông báo

---

### 2.2. BẢNG KIỂM TRA RÀNG BUỘC RACI

| # | Điều kiện kiểm tra | Kết quả | Ghi chú |
| :---: | :--- | :---: | :--- |
| 1 | Mỗi dòng **chỉ có đúng 1 chữ A** | ✅ 5/5 | Không có dòng nào có 2 chữ A |
| 2 | Không có dòng nào **thiếu chữ A** | ✅ | |
| 3 | Mỗi thành viên có **ít nhất 1 chữ R** | ✅ | Hoàng: 2R · Huy: 2R · Linh: 2R · Mai: 1R |
| 4 | Mỗi thành viên có **ít nhất 1 chữ A** | ✅ | Hoàng: 2A · Huy: 1A · Linh: 1A · Mai: 1A |
| 5 | Không ai chỉ có **duy nhất chữ I** | ✅ | Tất cả đều có R hoặc A |
| 6 | Mọi đầu việc đều có **hạn nộp rõ ràng** | ✅ | |
| 7 | Mỗi thành viên đều có **C hoặc I** ở các việc khác | ✅ | Đảm bảo kết nối |

#### 📋 Bảng kiểm chữ A theo từng dòng

| Dòng | 1 | 2 | 3 | 4 | 5 | Tổng |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Người giữ chữ A** | Huy | Hoàng | Linh | Mai | Hoàng | — |
| **Số chữ A trong dòng** | 1 | 1 | 1 | 1 | 1 | **5 chữ A** |

---

### 2.3. BẢNG THỐNG KÊ VAI TRÒ CỦA TỪNG THÀNH VIÊN

| Thành viên | R | A | C | I | Tổng lượt | Nhận xét |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Hoàng** | 2 | 2 | 3 | 0 | 7 | Nhóm trưởng – điều phối + chịu trách nhiệm chốt (Word, nộp bài) |
| **Huy** | 2 | 1 | 2 | 1 | 6 | Trụ cột tư liệu + hỗ trợ slide |
| **Linh** | 2 | 1 | 2 | 1 | 6 | Trụ cột hình thức (slide) + hỗ trợ thuyết trình |
| **Mai** | 1 | 1 | 3 | 1 | 6 | Trụ cột thuyết trình + góp ý đa phần |

> ⚖️ **Kết luận:** Khối lượng được chia **tương đối đồng đều** (6–7 lượt/người). Mỗi bạn đều có **ít nhất 1 chữ A** → không ai có thể nói *"tôi tưởng bạn kia làm"*.

---

### 2.4. GIẢI THÍCH LÝ DO PHÂN VAI (Để cả nhóm hiểu – không chỉ điền cho đủ)

| STT | Đầu việc | Ai – Vai trò | Lý do phân công |
| :---: | :--- | :--- | :--- |
| **1** | Tìm tài liệu & ảnh | **Huy = A + R**<br>Hoàng = C<br>Linh = C<br>Mai = I | Huy có thế mạnh tra cứu (Google Scholar, Computer History Museum) → chịu trách nhiệm chính về **bộ tài liệu + kiểm tra nguồn**. Hoàng và Linh góp ý tiêu chí chọn nguồn. Mai nhận thông báo để biết khi nào có tài liệu → phục vụ việc thuyết trình. |
| **2** | Soạn Word 8 trang | **Hoàng = A + R**<br>Huy = C<br>Mai = C<br>Linh = I | Hoàng viết tốt, có khả năng hành văn → trực tiếp viết và tự chịu trách nhiệm **chất lượng nội dung & hạn Thứ Bảy**. Huy góp ý phần lịch sử phần cứng (vì Huy đã đọc tài liệu ở việc 1). Mai góp ý phần trình bày, bố cục. Linh nhận thông báo để biết khi nào có bản Word → bắt đầu làm slide. |
| **3** | Thiết kế Slide 12 trang | **Linh = A + R**<br>Huy = R<br>Hoàng = C<br>Mai = C | Linh phụ trách thiết kế slide → vừa làm vừa **chịu trách nhiệm chính về thẩm mỹ & thời hạn**. Huy hỗ trợ chèn biểu đồ kỹ thuật. Hoàng góp ý bố cục. Mai góp ý nội dung thuyết trình để slide khớp với dàn ý. |
| **4** | Dàn ý & tập thuyết trình thử | **Mai = A + R**<br>Hoàng = C<br>Huy = R<br>Linh = C | Mai chịu trách nhiệm chính về phần thuyết trình: soạn dàn ý nói, điều hành buổi rehearsal, bấm giờ. Cả nhóm đều **trực tiếp tập nói** (R). Hoàng góp ý cách trình bày, Linh góp ý phần slide. |
| **5** | Rà soát & nộp bài | **Hoàng = A + R**<br>Linh = C<br>Mai = C<br>Huy = I | Hoàng là người **trực tiếp nộp file** lên hệ thống trường (R) và **chịu trách nhiệm cuối cùng** (A) về định dạng PDF/PPTX + đúng hạn. Linh rà soát slide, Mai rà soát nội dung thuyết trình. Huy nhận thông báo khi đã nộp xong. |

---

### 2.5. SƠ ĐỒ SO SÁNH RACI CŨ vs RACI MỚI

#### ❌ RACI CŨ — Sai lầm

```text
┌─────────────────────────────────────────────────────────────────┐
│                    ❌ RACI CŨ (SAI)                             │
│                                                                 │
│   Việc 1:  Huy = R                                             │
│   Việc 2:  Hoàng = A + R                                       │
│   Việc 3:  Linh = A + Huy = A  ⚠️ 2 CHỮ A!                     │
│   Việc 4:  Hoàng = A                                           │
│   Việc 5:  Hoàng = A                                           │
│   Mai:     Chỉ I  ⚠️ KHÔNG CÓ R, A, C                          │
│                                                                 │
│   📊 Tổng chữ A:  Hoàng=4 · Linh=1 · Huy=1 · Mai=0            │
│   📊 Tổng chữ R:  Hoàng=1 · Linh=0 · Huy=1 · Mai=0            │
│                                                                 │
│   ⚠️ VẤN ĐỀ: Hoàng ôm hết A · Mai bị cô lập · Slide trùng A    │
└─────────────────────────────────────────────────────────────────┘
```

#### ✅ RACI MỚI — Chuẩn mực

```text
┌─────────────────────────────────────────────────────────────────┐
│                    ✅ RACI MỚI (ĐÚNG)                           │
│                                                                 │
│   Việc 1:  Huy = A + R                                         │
│   Việc 2:  Hoàng = A + R                                       │
│   Việc 3:  Linh = A + R  ·  Huy = R                            │
│   Việc 4:  Mai = A + R   ·  Hoàng, Huy, Linh = R               │
│   Việc 5:  Hoàng = A + R                                       │
│                                                                 │
│   📊 Tổng chữ A:  Hoàng=2 · Huy=1 · Linh=1 · Mai=1            │
│   📊 Tổng chữ R:  Hoàng=2 · Huy=2 · Linh=2 · Mai=1            │
│                                                                 │
│   ✅ ƯU ĐIỂM: Chia đều A · Ai cũng có R · Không ai bị cô lập   │
└─────────────────────────────────────────────────────────────────┘
```

---

### 2.6. BẢNG SO SÁNH CHI TIẾT RACI CŨ vs RACI MỚI

| Tiêu chí | ❌ RACI CŨ | ✅ RACI MỚI | Cải thiện |
| :--- | :---: | :---: | :---: |
| **Số chữ A tối đa/người** | Hoàng: 4 | Hoàng: 2 | ✅ Giảm 50% |
| **Số thành viên có chữ A** | 3/4 (Mai không có) | 4/4 | ✅ +25% |
| **Số thành viên có chữ R** | 3/4 (Linh không có) | 4/4 | ✅ +25% |
| **Số dòng có 2 chữ A** | 1 (việc 3) | 0 | ✅ Sửa hoàn toàn |
| **Số thành viên chỉ có I** | 1 (Mai) | 0 | ✅ Sửa hoàn toàn |
| **Mức độ kết nối (C+I)** | Thấp | Cao | ✅ Tăng cường |
| **Tính công bằng** | ❌ Không | ✅ Có | ✅ Cải thiện rõ rệt |
| **Rủi ro đùn đẩy** | ❌ Cao | ✅ Thấp | ✅ Giảm mạnh |

---

### 2.7. TIMELINE 2 TUẦN (Bản đồ hóa RACI mới)

| Tuần | Thứ | Đầu việc | Người chốt (A) | Người làm (R) | Sản phẩm đầu ra |
| :---: | :--- | :--- | :---: | :--- | :--- |
| **1** | Thứ Ba | Họp kick-off: chốt đề cương, chốt RACI | Hoàng | Cả nhóm | Biên bản họp + file RACI |
| **1** | Thứ Tư | Tìm 3 tài liệu + hình ảnh | Huy | Huy, Linh | Thư mục `01_TaiLieu/` |
| **1** | Thứ Sáu | Họp check-in #1 (20:00) | Hoàng | Cả nhóm | Biên bản + chốt dàn ý |
| **1** | Thứ Bảy | Hoàn thành bản Word 8 trang | Hoàng | Hoàng | `BaoCao_v1.docx` |
| **2** | Chủ Nhật | Hoàng gửi Word → Linh bắt đầu làm slide | Hoàng | Linh | `Slide_v1.pptx` |
| **2** | Thứ Ba | Hoàn thành slide 12 trang | Linh | Linh, Huy | `Slide_v2.pptx` |
| **2** | Thứ Tư | Họp check-in #2 + chốt nội dung cuối | Hoàng | Cả nhóm | Biên bản |
| **2** | Thứ Năm | Tập thuyết trình thử (offline) | Mai | Cả nhóm | Bản ghi chú thời lượng |
| **2** | Thứ Sáu | Rà soát – xuất PDF/PPTX – NỘP BÀI | Hoàng | Hoàng, Linh, Mai | File nộp trên hệ thống |

---

## 3. NHIỆM VỤ 3 — 3 ĐIỀU KHOẢN TWA "CHỮA CHÁY" CẤP BÁCH (25 điểm)

### 3.0. Tổng quan 3 điều khoản cần thiết lập

```text
┌─────────────────────────────────────────────────────────────────┐
│           🚑 3 ĐIỀU KHOẢN TWA "CHỮA CHÁY" CẤP BÁCH             │
│                                                                 │
│   ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐│
│   │  ĐIỀU KHOẢN 1   │  │  ĐIỀU KHOẢN 2   │  │  ĐIỀU KHOẢN 3   ││
│   │  PHẢN HỒI TIN   │  │  LƯU TRỮ TÀI    │  │  HỖ TRỢ KHI     ││
│   │  NHẮN LARK      │  │  LIỆU DRIVE     │  │  GẶP KHÓ KHĂN   ││
│   │                 │  │                 │  │                 ││
│   │  Chấm dứt       │  │  Chấm dứt       │  │  Chấm dứt       ││
│   │  "thả tim" +    │  │  lưu rải rác    │  │  "ôm việc rồi   ││
│   │  "seen"         │  │  trên máy cá    │  │  im lặng"       ││
│   │                 │  │  nhân           │  │                 ││
│   └─────────────────┘  └─────────────────┘  └─────────────────┘│
└─────────────────────────────────────────────────────────────────┘
```

---

### 3.1. ĐIỀU KHOẢN 1 — PHẢN HỒI TIN NHẮN LARK

#### 📱 Nội dung điều khoản

```text
┌─────────────────────────────────────────────────────────────────┐
│         📱 ĐIỀU 1 — QUY ĐỊNH PHẢN HỒI TIN NHẮN LARK              │
│                                                                 │
│   1. KÊNH LIÊN LẠC CHÍNH THỨC:                                  │
│      • Nhóm Lark "SKL103 – Nhóm Hoàng"                          │
│      • Mọi trao đổi về bài tập đều diễn ra tại đây              │
│                                                                 │
│   2. THỜI GIAN PHẢN HỒI TỐI ĐA:                                 │
│      • Trong vòng 3 GIỜ (áp dụng 07:00 – 22:00)                 │
│      • Tin nhắn sau 22:00 → phản hồi trước 09:00 sáng hôm sau   │
│                                                                 │
│   3. HÌNH THỨC PHẢN HỒI BẮT BUỘC:                               │
│      • PHẢI trả lời bằng NỘI DUNG CỤ THỂ theo mẫu:              │
│        [Tên] – [Việc] – [% xong] – [Vướng mắc] – [Dự kiến xong]│
│                                                                 │
│   4. NGHIÊM CẤM:                                                │
│      • Dùng icon (👍, ❤️, 😆) thay cho câu trả lời tiến độ     │
│      • Chỉ "seen" mà không trả lời                              │
│      • Im lặng khi được tag tên                                 │
│                                                                 │
│   5. LEO THANG XỬ LÝ:                                            │
│      • Quá 12h không phản hồi → Nhóm trưởng gọi điện trực tiếp │
│      • Quá 24h không phản hồi → Báo lớp phó học tập            │
└─────────────────────────────────────────────────────────────────┘
```

#### 📋 Bảng mẫu phản hồi bắt buộc

| Trường hợp | ❌ SAI (bị cấm) | ✅ ĐÚNG (bắt buộc) |
| :--- | :--- | :--- |
| **Nhận việc** | 👍 (thả tim) | *"Mai – Dàn ý thuyết trình – 0% – Chưa bắt đầu – Sẽ xong trước 20:00 Thứ Năm"* |
| **Đang làm** | *"ok"* | *"Huy – Tìm tài liệu – 60% – Cần thêm ảnh CPU – Xong trước 18:00 Thứ Tư"* |
| **Bận, không nhận** | *(im lặng)* | *"Linh – Slide – Không nhận được hạn này – Đang thi giữa kỳ – Đề xuất dời sang Thứ Năm"* |
| **Cần hỗ trợ** | 😢 (icon) | *"Hoàng – Word – 70% – Cần Mai góp ý bố cục – Sẽ gửi bản nháp trước 21:00 hôm nay"* |

#### 🎯 Ví dụ tin nhắn theo điều khoản 1

> **📱 Tin nhắn Lark – 20:00 Thứ Năm**

```text
@Mai Ơi Mai ơi, mình nhờ Mai một việc cụ thể nhé:

📌 VIỆC CẦN LÀM: Soạn dàn ý bài nói thuyết trình (10 phút)
   - Mỗi slide 1–2 câu dàn ý, ghi rõ ai nói phần nào.
   - File: SKL103_Nhom_Slide_v2.pptx (link Drive ở tin ghim).

⏰ HẠN NỘP: 20:00 Thứ Năm tuần này.

❓ Nếu Mai không kịp hoặc đang bận, nhắn lại cho mình TRƯỚC
   22:00 hôm nay để mình sắp xếp người khác nhé.

Cảm ơn Mai nhiều! 🙏
```

> **📱 Mai trả lời – 20:15 Thứ Năm**

```text
@Hoàng Mình xác nhận nhé:

✅ ĐÃ HIỂU: Soạn dàn ý bài nói cho 12 slide, mỗi slide 1–2 câu,
   ghi rõ phân vai thuyết trình.

✅ SẼ LÀM: Mình sẽ soạn xong và gửi file vào Drive chung.

⏰ CAM KẾT: Xong trước 20:00 Thứ Năm. Sẽ nhắn thông báo khi xong.

⚠️ KHÓ KHĂN: Mình chưa rõ slide 5–6 ai nói, cần Hoàng xác nhận
   phân vai trước Thứ Tư để mình ghi đúng.

📌 CẦN HỖ TRỢ: Nếu 18:00 Thứ Năm mình chưa xong, mình sẽ nhắn
   trước để nhóm xoay người.
```

> **📱 Hoàng chốt – 20:20 Thứ Năm**

```text
✅ Chốt nhé Mai: Dàn ý thuyết trình xong trước 20:00 Thứ Năm,
   gửi file vào Drive chung.

Mình sẽ xác nhận phân vai slide 5–6 cho Mai trước Thứ Tư.
Cần gì Mai cứ nhắn nhóm. Cảm ơn Mai! 🙌
```

---

### 3.2. ĐIỀU KHOẢN 2 — LƯU TRỮ BÀI TẬP CHUNG TRÊN GOOGLE DRIVE

#### 🗂️ Nội dung điều khoản

```text
┌─────────────────────────────────────────────────────────────────┐
│      🗂️ ĐIỀU 2 — QUY ĐỊNH LƯU TRỮ BÀI TẬP TRÊN GOOGLE DRIVE     │
│                                                                 │
│   1. NƠI LƯU TRỮ DUY NHẤT:                                      │
│      • Thư mục Google Drive chung của nhóm                      │
│      • Link được GHIM CỐ ĐỊNH ở đầu nhóm Lark                   │
│      • NGHIÊM CẤM lưu file bài tập trên máy cá nhân             │
│                                                                 │
│   2. CẤU TRÚC THƯ MỤC CHUẨN:                                    │
│      SKL103_Nhom01/                                             │
│      ├── 00_QuyDinh/                                            │
│      │   ├── RACI_Nhom01.md                                     │
│      │   └── TWA_Nhom01.md                                      │
│      ├── 01_TaiLieu/                                            │
│      │   ├── TaiLieu_PhanCung/                                  │
│      │   └── HinhAnh/                                           │
│      ├── 02_BaoCao_Word/                                        │
│      ├── 03_Slide/                                              │
│      ├── 04_BienBanHop/                                         │
│      ├── 05_NopBai/                                             │
│      └── _OldVersion/                                           │
│                                                                 │
│   3. QUY TẮC ĐẶT TÊN FILE (BẮT BUỘC):                           │
│      • Mẫu: SKL103_N01_<Loại>_<Người>_v<Số>_<YYYYMMDD>.<đuôi> │
│      • Ví dụ: SKL103_N01_BaoCao_Hoang_v1_20250315.docx         │
│                                                                 │
│   4. NGUYÊN TẮC LÀM VIỆC TRÊN FILE:                             │
│      • KHÔNG gửi file qua Lark (chỉ gửi LINK)                  │
│      • KHÔNG xóa bản cũ – chuyển vào _OldVersion/              │
│      • Khi sửa file người khác → TẠO PHIÊN BẢN MỚI (v2, v3…)   │
│                                                                 │
│   5. SAO LƯU:                                                   │
│      • Cuối mỗi tuần, Hoàng tải toàn bộ về máy backup          │
└─────────────────────────────────────────────────────────────────┘
```

#### 📋 Bảng quy tắc đặt tên file chi tiết

| Loại file | Mẫu đặt tên | Ví dụ |
| :--- | :--- | :--- |
| **Báo cáo Word** | `SKL103_N01_BaoCao_<Tên>_v<Số>_<YYYYMMDD>.docx` | `SKL103_N01_BaoCao_Hoang_v2_20250315.docx` |
| **Slide** | `SKL103_N01_Slide_<Tên>_v<Số>_<YYYYMMDD>.pptx` | `SKL103_N01_Slide_Linh_v1_20250318.pptx` |
| **Biên bản họp** | `SKL103_N01_BienBan_<Tên>_<YYYYMMDD>.md` | `SKL103_N01_BienBan_Mai_20250311.md` |
| **Tài liệu tham khảo** | `SKL103_N01_TaiLieu_<ChủĐề>_<Tên>.pdf` | `SKL103_N01_TaiLieu_CPU_Huy.pdf` |
| **File nộp cuối** | `SKL103_N01_Final_<Loại>_<YYYYMMDD>.<đuôi>` | `SKL103_N01_Final_BaoCao_20250320.pdf` |

#### 🎯 Bảng so sánh lưu trữ SAI vs ĐÚNG

| Tiêu chí | ❌ SAI (hiện tại) | ✅ ĐÚNG (theo TWA) |
| :--- | :--- | :--- |
| **Nơi lưu** | Máy cá nhân mỗi bạn | Google Drive chung |
| **Gửi file** | Qua Lark (dễ thất lạc) | Chỉ gửi LINK Drive |
| **Đặt tên** | `baocao_final_final2.docx` | `SKL103_N01_BaoCao_Hoang_v2_20250315.docx` |
| **Phiên bản** | Ghi đè, mất bản cũ | Tạo v1, v2, v3… – giữ bản cũ |
| **Tìm file** | Mất 10–15 phút | Tìm trong 30 giây |
| **Backup** | Không có | Cuối tuần backup toàn bộ |

---

### 3.3. ĐIỀU KHOẢN 3 — HỖ TRỢ KHI GẶP KHÓ KHĂN

#### 🆘 Nội dung điều khoản

```text
┌─────────────────────────────────────────────────────────────────┐
│      🆘 ĐIỀU 3 — QUY ĐỊNH HỖ TRỢ KHI GẶP KHÓ KHĂN              │
│                                                                 │
│   1. NGUYÊN TẮC VÀNG:                                           │
│      • "BÁO SỚM TỐT HƠN IM LẶNG"                                │
│      • "KHÔNG AI BỊ PHẠT KHI BÁO KHÓ KHĂN ĐÚNG HẠN"             │
│      • "THÀ BÁO TRƯỚC CÒN HƠN LÀ ĐỂ NƯỚC ĐẾN CHÂN MỚI NHẢY"    │
│                                                                 │
│   2. THỜI HẠN BÁO KHÓ KHĂN:                                     │
│      • TỐI THIỂU 24 GIỜ trước deadline của phần việc mình làm   │
│      • Nếu khó khăn đột xuất → báo NGAY khi phát hiện           │
│                                                                 │
│   3. MẪU BÁO KHÓ KHĂN:                                          │
│      [Tên] – [Việc] – [% xong] – [Khó khăn cụ thể] –           │
│      [Đề xuất phương án] – [Cần hỗ trợ gì]                     │
│                                                                 │
│   4. QUY TRÌNH XỬ LÝ KHI CÓ NGƯỜI BÁO KHÓ KHĂN:                 │
│      Bước 1: Nhóm trưởng xác nhận trong 1 giờ                   │
│      Bước 2: Họp nhanh 10 phút (nếu cần) để bàn phương án      │
│      Bước 3: Phân người hỗ trợ hoặc điều chỉnh deadline        │
│      Bước 4: Cập nhật lại RACI nếu cần                          │
│                                                                 │
│   5. CHẾ TÀI (nhẹ – mang tính nhắc nhở):                        │
│      • Báo muộn (< 24h) lần 1 → Nhắc nhở trong biên bản        │
│      • Báo muộn lần 2 → Nhận việc bù (làm biên bản, tổng hợp)  │
│      • Không báo mà ôm việc → Ghi vào đánh giá đóng góp cá nhân│
│                                                                 │
│   6. KHEN THƯỞNG:                                               │
│      • Ai báo khó khăn ĐÚNG HẠN → Được ghi nhận trong biên bản │
│      • Ai giúp đỡ người khác → Ưu tiên điểm đóng góp cao       │
└─────────────────────────────────────────────────────────────────┘
```

#### 📋 Bảng mẫu báo khó khăn

| Trường hợp | ❌ SAI (bị cấm) | ✅ ĐÚNG (bắt buộc) |
| :--- | :--- | :--- |
| **Chưa tìm được tài liệu** | *(im lặng, không nói)* | *"Huy – Tài liệu – 40% – Chưa tìm được ảnh CPU Intel 4004 – Đề xuất dùng ảnh từ Computer History Museum – Cần Hoàng duyệt nguồn"* |
| **Chưa biết vẽ biểu đồ** | *(tự loay hoay 3 tiếng)* | *"Linh – Slide – 30% – Chưa biết vẽ biểu đồ tròn trên PowerPoint – Đề xuất nhờ Huy chỉ 15 phút – Cần hỗ trợ kỹ thuật"* |
| **Đang thi, không kịp** | *(im lặng đến sát hạn)* | *"Mai – Dàn ý thuyết trình – 0% – Đang thi Giải tích, không kịp hạn Thứ Năm – Đề xuất dời sang Thứ Sáu hoặc nhờ Hoàng làm – Cần nhóm xác nhận"* |
| **File bị lỗi font** | *(gửi file lỗi cho nhóm)* | *"Hoàng – Word – 90% – File bị lỗi font tiếng Việt khi mở trên máy khác – Đề xuất xuất PDF – Cần Linh kiểm tra trên máy Linh"* |

#### 🎯 Ví dụ tin nhắn báo khó khăn theo điều khoản 3

> **📱 Tin nhắn Lark – 18:00 Thứ Tư (trước deadline 24h)**

```text
@Hoàng Mình báo khó khăn theo Điều 3 TWA nhé:

📌 TÊN: Huy
📌 VIỆC: Tìm tài liệu và ảnh minh họa linh kiện máy tính
📌 % XONG: 40%

⚠️ KHÓ KHĂN CỤ THỂ: Mình đã tìm được 5/8 ảnh linh kiện.
   Còn 3 ảnh khó tìm: CPU Intel 4004, RAM 1980s, ổ cứng HDD 1990s.

💡 ĐỀ XUẤT PHƯƠNG ÁN:
   1. Dùng ảnh từ Computer History Museum (đã kiểm tra, có bản quyền).
   2. Nhờ Linh tìm trên Pinterest (Linh có tài khoản Premium).

🤝 CẦN HỖ TRỢ: Hoàng duyệt nguồn Computer History Museum
   trước 20:00 hôm nay để mình kịp hoàn thành.

⏰ DỰ KIẾN XONG: 18:00 Thứ Năm (đúng hạn ban đầu).
```

> **📱 Hoàng xác nhận – 18:30 Thứ Tư**

```text
✅ Ok Huy, mình duyệt nguồn Computer History Museum nhé.

📌 Linh ơi, Linh hỗ trợ Huy tìm 3 ảnh còn lại trên Pinterest
   trước 20:00 Thứ Tư được không?

Cảm ơn Huy đã báo sớm – nhóm mình sẽ xoay kịp. 💪
```

---

### 3.4. BẢNG TỔNG HỢP 3 ĐIỀU KHOẢN TWA

| # | Điều khoản | Vấn đề giải quyết | Quy định chính | Chế tài |
| :---: | :--- | :--- | :--- | :--- |
| **1** | **Phản hồi tin nhắn Lark** | Thói quen "thả tim" + "seen" | Phản hồi trong 3h · Trả lời bằng nội dung cụ thể | Quá 12h → gọi điện · Quá 24h → báo lớp phó |
| **2** | **Lưu trữ Google Drive** | Lưu rải rác trên máy cá nhân | Thư mục chung · Đặt tên có phiên bản · Không gửi file qua Lark | File cũ chuyển vào `_OldVersion/` |
| **3** | **Hỗ trợ khi khó khăn** | Ôm việc rồi im lặng | Báo trước 24h · Mẫu báo cụ thể · Quy trình xử lý 4 bước | Báo muộn → nhận việc bù · Không báo → trừ điểm đóng góp |

---

### 3.5. SƠ ĐỒ QUY TRÌNH XỬ LÝ KHÓ KHĂN (Điều khoản 3)

```text
┌─────────────────────────────────────────────────────────────────┐
│           🔄 QUY TRÌNH XỬ LÝ KHI CÓ NGƯỜI BÁO KHÓ KHĂN          │
│                                                                 │
│   BƯỚC 1: THÀNH VIÊN BÁO KHÓ KHĂN                              │
│   ┌──────────────────────────────────────┐                     │
│   │ Gửi tin nhắn theo mẫu:                │                     │
│   │ [Tên] – [Việc] – [%] – [Khó khăn] –  │                     │
│   │ [Đề xuất] – [Cần hỗ trợ gì]          │                     │
│   │ ⏰ Trước deadline TỐI THIỂU 24 GIỜ    │                     │
│   └──────────────────┬───────────────────┘                     │
│                      │                                          │
│                      ▼                                          │
│   BƯỚC 2: NHÓM TRƯỞNG XÁC NHẬN (trong 1 giờ)                   │
│   ┌──────────────────────────────────────┐                     │
│   │ • Xác nhận đã nhận thông tin          │                     │
│   │ • Đánh giá mức độ nghiêm trọng        │                     │
│   │ • Quyết định có cần họp nhanh không   │                     │
│   └──────────────────┬───────────────────┘                     │
│                      │                                          │
│                      ▼                                          │
│   BƯỚC 3: HỌP NHANH 10 PHÚT (nếu cần)                          │
│   ┌──────────────────────────────────────┐                     │
│   │ • Người báo trình bày khó khăn        │                     │
│   │ • Cả nhóm đề xuất phương án           │                     │
│   │ • Chọn phương án tối ưu               │                     │
│   └──────────────────┬───────────────────┘                     │
│                      │                                          │
│                      ▼                                          │
│   BƯỚC 4: PHÂN NGƯỜI HỖ TRỢ HOẶC ĐIỀU CHỈNH                    │
│   ┌──────────────────────────────────────┐                     │
│   │ • Phân người hỗ trợ cụ thể            │                     │
│   │ • Dời deadline nếu cần (có lý do)     │                     │
│   │ • Cập nhật lại RACI nếu thay đổi      │                     │
│   │ • Ghi vào biên bản họp                │                     │
│   └──────────────────────────────────────┘                     │
└─────────────────────────────────────────────────────────────────┘
```

---

### 3.6. QUY ƯỚC CHUNG — BẢN TWA HOÀN CHỈNH

```text
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│          🤝 BẢN THỎA THUẬN LÀM VIỆC NHÓM (TWA)                  │
│                    NHÓM HOÀNG — SKL103                          │
│                                                                 │
│   Hiệu lực: Từ ngày ký đến khi kết thúc học phần.               │
│   Nguyên tắc chung: Tôn trọng – Đúng hạn – Minh bạch –          │
│                     Hỗ trợ lẫn nhau.                            │
│                                                                 │
│   📱 ĐIỀU 1 — PHẢN HỒI TIN NHẮN LARK                            │
│   • Kênh chính thức: Nhóm Lark "SKL103 – Nhóm Hoàng"            │
│   • Phản hồi trong 3h (07:00–22:00)                             │
│   • Bắt buộc trả lời bằng NỘI DUNG CỤ THỂ                       │
│   • NGHIÊM CẤM: thả tim, seen, im lặng khi được tag             │
│   • Quá 12h không phản hồi → gọi điện trực tiếp                │
│                                                                 │
│   🗂️ ĐIỀU 2 — LƯU TRỮ BÀI TẬP TRÊN GOOGLE DRIVE                 │
│   • Nơi lưu duy nhất: Google Drive chung (link ghim ở Lark)     │
│   • Cấu trúc thư mục chuẩn: 00_QuyDinh → 05_NopBai              │
│   • Đặt tên file: SKL103_N01_<Loại>_<Người>_v<Số>_<Ngày>       │
│   • KHÔNG gửi file qua Lark – chỉ gửi LINK                      │
│   • KHÔNG xóa bản cũ – chuyển vào _OldVersion/                  │
│                                                                 │
│   🆘 ĐIỀU 3 — HỖ TRỢ KHI GẶP KHÓ KHĂN                           │
│   • Báo trước TỐI THIỂU 24 GIỜ khi phần việc bị nghẽn           │
│   • Mẫu báo: [Tên]–[Việc]–[%]–[Khó khăn]–[Đề xuất]–[Cần gì]   │
│   • Quy trình 4 bước xử lý khi có người báo khó khăn            │
│   • Báo sớm được khen, báo muộn nhận việc bù                    │
│                                                                 │
│   ✍️ CHỮ KÝ CỦA CÁC THÀNH VIÊN:                                 │
│   • Hoàng (Nhóm trưởng)  _________________                     │
│   • Huy                   _________________                     │
│   • Linh                  _________________                     │
│   • Mai                   _________________                     │
│                                                                 │
│   Ngày ký: ..../..../20....                                     │
└─────────────────────────────────────────────────────────────────┘
```

---

## 4. TỔNG KẾT BÀI LÀM

### 4.1. Checklist sản phẩm nộp bài

- [x] **Sản phẩm 1:** Bản phân tích 3 sai lầm phân công (Nhiệm vụ 1)
- [x] **Sản phẩm 2:** Bảng Ma trận RACI tái thiết kế (Nhiệm vụ 2)
- [x] **Sản phẩm 3:** Bản quy ước 3 điều khoản TWA (Nhiệm vụ 3)

### 4.2. Bảng tổng kết 3 sai lầm & 3 giải pháp

| # | Sai lầm | Giải pháp | Kết quả mong đợi |
| :---: | :--- | :--- | :--- |
| **1** | 2 chữ A ở việc Slide | Chỉ 1 chữ A duy nhất (Linh = A) | Slide có người chịu trách nhiệm chính |
| **2** | Hoàng ôm 4 chữ A | Chia A: Hoàng 2, Huy 1, Linh 1, Mai 1 | Hoàng không quá tải, các bạn có trách nhiệm |
| **3** | Mai chỉ có chữ I | Mai có 1 chữ A + 1 chữ R | Mai không bị cô lập, có đóng góp cụ thể |

### 4.3. Bảng tổng kết RACI mới

| Thành viên | Số chữ A | Số chữ R | Số chữ C | Số chữ I | Đánh giá |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Hoàng** | 2 | 2 | 3 | 0 | ✅ Hợp lý (nhóm trưởng) |
| **Huy** | 1 | 2 | 2 | 1 | ✅ Hợp lý |
| **Linh** | 1 | 2 | 2 | 1 | ✅ Hợp lý |
| **Mai** | 1 | 1 | 3 | 1 | ✅ Hợp lý |

### 4.4. Bài học rút ra

| # | Bài học | Áp dụng |
| :---: | :--- | :--- |
| 1 | **Mỗi đầu việc chỉ có DUY NHẤT 1 chữ A** | Không bao giờ để 2 người cùng chịu trách nhiệm chính |
| 2 | **Không ai được ôm quá nhiều chữ A** | Mỗi thành viên giữ tối đa 2 chữ A |
| 3 | **Mọi thành viên phải có ít nhất 1 chữ R** | Không ai chỉ ngồi nhận thông báo |
| 4 | **Không ai chỉ có duy nhất chữ I** | Chữ I phải đi kèm với R hoặc A |
| 5 | **TWA phải cụ thể, có chế tài** | Không dùng quy ước miệng "cứ làm đi" |
| 6 | **Báo sớm tốt hơn im lặng** | Báo khó khăn trước 24h để nhóm hỗ trợ |

### 4.5. Chữ ký xác nhận của nhóm

| STT | Họ và tên | Vai trò | Chữ ký | Ngày |
| :---: | :--- | :--- | :--- | :--- |
| 1 | **Hoàng** | Nhóm trưởng – Điều phối & Word | *(đã ký)* | ..../..../20.... |
| 2 | **Huy** | Tư liệu – Tìm kiếm & Hỗ trợ slide | *(đã ký)* | ..../..../20.... |
| 3 | **Linh** | Hình thức – Slide | *(đã ký)* | ..../..../20.... |
| 4 | **Mai** | Thuyết trình – Dàn ý & Tập thử | *(đã ký)* | ..../..../20.... |

---

> 📌 **Ghi chú phiên bản:** Bản phân tích RACI & TWA này được lưu tại `00_QuyDinh/` trên Google Drive chung của nhóm. Mọi thay đổi phải được cả nhóm đồng ý.

| Phiên bản | Ngày | Nội dung thay đổi | Người cập nhật |
| :---: | :--- | :--- | :--- |
| v1.0 | ..../..../20.... | Ban hành lần đầu | Hoàng |

---

## 5. PHỤ LỤC — BẢNG TÓM TẮT NHANH

### 5.1. Tóm tắt 3 sai lầm trong 1 bảng

| Sai lầm | Đối tượng | Nguyên nhân | Hậu quả | Giải pháp |
| :--- | :--- | :--- | :--- | :--- |
| **2 chữ A** | Việc 3 (Slide) | Vi phạm nguyên tắc 1 chữ A | Slide trống 0/12 | Linh = A duy nhất |
| **Ôm nhiều A** | Hoàng | Không phân quyền | Hoàng kiệt sức | Chia A cho 4 người |
| **Chỉ có I** | Mai | Không giao việc cụ thể | Mai bị cô lập | Mai có A + R |

### 5.2. Tóm tắt RACI mới trong 1 bảng

| STT | Đầu việc | Hoàng | Huy | Linh | Mai |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1 | Tìm tài liệu | C | **A+R** | C | I |
| 2 | Word | **A+R** | C | I | C |
| 3 | Slide | C | R | **A+R** | C |
| 4 | Thuyết trình | C | R | C | **A+R** |
| 5 | Nộp bài | **A+R** | I | C | C |

### 5.3. Tóm tắt 3 điều khoản TWA trong 1 bảng

| # | Điều khoản | Quy định chính | Chế tài |
| :---: | :--- | :--- | :--- |
| 1 | Phản hồi Lark | 3h · Nội dung cụ thể | Quá 12h → gọi điện |
| 2 | Lưu trữ Drive | Thư mục chung · Tên có version | File cũ vào `_OldVersion/` |
| 3 | Hỗ trợ khó khăn | Báo trước 24h · Mẫu cụ thể | Báo muộn → việc bù |
