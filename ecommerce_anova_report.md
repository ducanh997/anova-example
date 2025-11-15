## So sánh mức độ hài lòng với thương mại điện tử giữa các thế hệ bằng One-way ANOVA

> **⚠️ LƯU Ý QUAN TRỌNG:** Nghiên cứu này sử dụng **dữ liệu mô phỏng** nhằm mục đích **minh họa phương pháp** One-way ANOVA trong phân tích hành vi người tiêu dùng. Dữ liệu **KHÔNG phải** từ khảo sát thực tế. Kết quả và các con số trong báo cáo **KHÔNG NÊN** được suy rộng cho dân số thực tế. Nghiên cứu này phục vụ mục đích **học tập và nghiên cứu phương pháp**.

### Tóm tắt

Nghiên cứu này nhằm minh họa cách so sánh **mức độ hài lòng đối với mua sắm thương mại điện tử (TMĐT)** giữa ba thế hệ người tiêu dùng: **Gen X (1965–1980), Millennials (1981–1996) và Gen Z (1997–2012)** bằng phương pháp One-way ANOVA. Dữ liệu mô phỏng được thiết kế theo cấu trúc bảng hỏi sử dụng thang đo Likert 5 mức với 10 mục hỏi về trải nghiệm TMĐT (hài lòng tổng thể, giao diện, quy trình đặt hàng, an toàn thanh toán, giao hàng, chất lượng sản phẩm, chăm sóc khách hàng, giá cả – khuyến mãi, ý định tiếp tục mua, ý định giới thiệu). Điểm hài lòng tổng hợp (`satisfaction`) được tính bằng trung bình cộng của 10 mục hỏi. Mẫu nghiên cứu gồm 1200 quan sát: Gen Z (n = 400), Millennials (n = 400), Gen X (n = 400).  
Kết quả thống kê mô tả cho thấy Gen Z có mức hài lòng trung bình cao nhất (M = 4.19, SD = 0.48), tiếp theo là Millennials (M = 3.88, SD = 0.53) và thấp nhất là Gen X (M = 3.41, SD = 0.57). Độ tin cậy của thang đo được đánh giá bằng Cronbach's alpha = 0.969 (xuất sắc), với tương quan trung bình giữa các mục hỏi là 0.757, chứng tỏ 10 mục hỏi đo lường cùng một khái niệm "hài lòng TMĐT". Kiểm tra giả định cho thấy: (1) residuals của mô hình vi phạm nhẹ giả định phân phối chuẩn (Shapiro-Wilk: p < 0.001), tuy nhiên với cỠ mẫu lớn (n = 1200) và cân bằng giữa các nhóm, ANOVA vẫn robust và đáng tin cậy; (2) phương sai các nhóm có khác biệt nhẹ (Levene: F = 11.83, p < 0.001) với tỷ lệ phương sai max/min = 1.42 (< 3, vẫn chấp nhận được). Phân tích One-way ANOVA cho kết quả F(2, 1197) = 221.88, p < 0.001, eta bình phương \(\eta^2 = 0.27\), cho thấy **tác động lớn** của thế hệ đối với mức độ hài lòng TMĐT. Kết quả được kiểm chứng bằng kiểm định phi tham số Kruskal-Wallis (H = 340.64, p < 0.001). Kiểm định hậu nghiệm Tukey HSD chỉ ra rằng cả ba cặp so sánh (Gen Z – Millennials, Gen Z – Gen X, Millennials – Gen X) đều khác biệt có ý nghĩa thống kê (p < 0.001). Thứ tự mức độ hài lòng là: **Gen Z > Millennials > Gen X**.  
Nghiên cứu góp phần làm rõ sự khác biệt thế hệ trong trải nghiệm TMĐT và minh họa khả năng ứng dụng One-way ANOVA trong phân tích hành vi người tiêu dùng.

**Từ khóa**: thương mại điện tử, mức độ hài lòng, Gen Z, Millennials, Gen X, One-way ANOVA, phân tích phương sai.

---

### 1. Giới thiệu

Trong khoảng hơn một thập kỷ qua, thương mại điện tử tại Việt Nam phát triển nhanh chóng với sự xuất hiện và mở rộng của các nền tảng như Shopee, Lazada, Tiki, v.v. Mua sắm trực tuyến dần trở thành một phần trong thói quen tiêu dùng của người dân. Tuy nhiên, **mức độ chấp nhận và hài lòng** với hình thức mua sắm này có thể **không đồng nhất giữa các thế hệ**:

- **Gen Z**: lớn lên cùng internet, smartphone, mạng xã hội, dễ dàng tiếp cận và sử dụng ứng dụng TMĐT;
- **Millennials**: là thế hệ “chuyển tiếp”, vừa quen công nghệ vừa chịu áp lực công việc và gia đình;
- **Gen X**: đã trưởng thành trước thời đại internet, có thể thận trọng hơn với mua sắm trực tuyến và thanh toán online.

Trong bối cảnh đó, câu hỏi đặt ra là: **mức độ hài lòng với TMĐT của các thế hệ này có khác nhau hay không?** Trả lời câu hỏi này giúp:

- Doanh nghiệp TMĐT hiểu rõ hơn về **phân khúc khách hàng** theo lứa tuổi/thế hệ;
- Nhà nghiên cứu và nhà quản lý có thêm bằng chứng định lượng về vai trò của yếu tố thế hệ trong trải nghiệm TMĐT.

Nghiên cứu này tập trung vào việc **so sánh mức độ hài lòng TMĐT giữa ba thế hệ** sử dụng dữ liệu khảo sát và phân tích One-way ANOVA, đồng thời trình bày quy trình nghiên cứu định lượng trong bối cảnh TMĐT.

---

### 2. Mục tiêu, câu hỏi và giả thuyết nghiên cứu

#### 2.1. Mục tiêu nghiên cứu

Nghiên cứu hướng đến việc:

- Đo lường và so sánh **mức độ hài lòng với TMĐT** giữa ba nhóm thế hệ Gen X, Millennials, Gen Z;
- Cung cấp bằng chứng thực nghiệm về mối quan hệ giữa thế hệ và mức độ hài lòng TMĐT;
- Đề xuất một số gợi ý cho các nhà quản trị TMĐT trong việc thiết kế trải nghiệm phù hợp với từng nhóm khách hàng theo thế hệ.

#### 2.2. Câu hỏi nghiên cứu

- **Câu hỏi nghiên cứu chính**:  
  Mức độ hài lòng với mua sắm TMĐT có khác nhau giữa các thế hệ Gen X, Millennials và Gen Z hay không?

#### 2.3. Biến nghiên cứu và giả thuyết thống kê

- **Biến độc lập (nhân tố)**: `generation` – thế hệ người tham gia khảo sát, gồm ba mức:
  - Gen X (1965–1980)
  - Millennials (1981–1996)
  - Gen Z (1997–2012)

- **Biến phụ thuộc**: `satisfaction` – điểm hài lòng tổng hợp với TMĐT, tính bằng trung bình cộng của 10 câu hỏi thang Likert (Q1–Q10) với giá trị từ 1 đến 5.

**Giả thuyết thống kê:**

- \(H_0\): \(\mu_{\text{Gen X}} = \mu_{\text{Millennials}} = \mu_{\text{Gen Z}}\)  
  (Không có khác biệt về mức độ hài lòng TMĐT giữa ba thế hệ.)

- \(H_1\): Tồn tại ít nhất một cặp \(\mu_i \neq \mu_j\)  
  (Có sự khác biệt về mức độ hài lòng TMĐT giữa các thế hệ.)

#### 2.4. Cơ sở lý thuyết và nghiên cứu liên quan

Khái niệm **sự hài lòng của khách hàng** nói chung và **hài lòng trong môi trường dịch vụ** nói riêng đã được nghiên cứu rộng rãi trong marketing và quản trị dịch vụ. Parasuraman, Zeithaml và Berry (1988) đề xuất thang đo SERVQUAL để đánh giá chất lượng dịch vụ và xem đây là một trong những yếu tố quan trọng dẫn đến hài lòng và trung thành của khách hàng. Trong bối cảnh trực tuyến, Anderson và Srinivasan (2003) mở rộng khái niệm này sang **e-satisfaction** và **e-loyalty**, nhấn mạnh vai trò của trải nghiệm trên website/ứng dụng, sự thuận tiện và độ tin cậy của hệ thống TMĐT.

Đối với TMĐT, nhiều nghiên cứu chỉ ra rằng mức độ hài lòng bị ảnh hưởng bởi các yếu tố như chất lượng website, độ tin cậy, an toàn thanh toán, chất lượng giao hàng, dịch vụ hậu mãi và giá cả/khuyến mãi (ví dụ: Zeithaml, Berry & Parasuraman, 1996). Đồng thời, **đặc điểm thế hệ** cũng được xem là một yếu tố quan trọng trong việc giải thích khác biệt về nhận thức và hành vi tiêu dùng. Các nghiên cứu về thế hệ (cohort) cho thấy Gen X, Millennials và Gen Z có mức độ gắn bó với công nghệ, thói quen sử dụng internet và thái độ với rủi ro trực tuyến khác nhau, từ đó có thể dẫn tới khác biệt về mức độ chấp nhận và hài lòng với TMĐT.

Từ góc độ này, việc khảo sát và so sánh mức độ hài lòng TMĐT giữa Gen X, Millennials và Gen Z không chỉ giúp lấp khoảng trống về thực nghiệm trong bối cảnh Việt Nam mà còn góp phần bổ sung bằng chứng cho các luận điểm về khác biệt thế hệ trong hành vi tiêu dùng số.

---

### 3. Phương pháp nghiên cứu

#### 3.1. Thiết kế nghiên cứu

Nghiên cứu sử dụng thiết kế **định lượng**, theo dạng:

- **Nghiên cứu mô tả – so sánh**, với biến nhóm (thế hệ) là biến phân loại;
- Áp dụng phép kiểm định **One-way ANOVA** để so sánh trung bình của ba nhóm độc lập.

Dữ liệu sử dụng trong báo cáo này được lưu trong tệp `survey_data.csv`, được xây dựng để phản ánh cấu trúc thang đo Likert 1–5 với các đặc điểm phân bố hợp lý cho phân tích thống kê.

#### 3.2. Đối tượng và mẫu nghiên cứu

- **Đối tượng nghiên cứu**: người tiêu dùng từ 18 tuổi trở lên đã từng mua hàng qua các sàn TMĐT (Shopee, Lazada, Tiki, v.v.) trong thời gian gần đây.
- **Mẫu nghiên cứu** (dữ liệu trong file `survey_data.csv`):
  - Gen Z: 400 người tham gia;
  - Millennials: 400 người tham gia;
  - Gen X: 400 người tham gia.  
  → **Tổng cỡ mẫu**: n = 1200.

Cỡ mẫu này đủ lớn để thực hiện phân tích thống kê suy luận và cho phép so sánh tương đối tin cậy mức độ hài lòng giữa các nhóm thế hệ.

#### 3.3. Công cụ thu thập dữ liệu

Công cụ chính là **phiếu khảo sát** (xem chi tiết trong file `survey_questionnaire.md`), gồm hai phần:

- **Phần A: Thông tin chung**  
  Thu thập các biến nhân khẩu học cơ bản như:
  - Năm sinh (để xác định thế hệ);
  - Giới tính;
  - Tần suất mua hàng trên TMĐT;
  - Nền tảng TMĐT thường dùng.

- **Phần B: Thang đo mức độ hài lòng TMĐT**  
  Gồm 10 phát biểu (Q1–Q10), mỗi phát biểu được đánh giá trên **thang Likert 5 mức**:
  - 1 – Rất không đồng ý  
  - 2 – Không đồng ý  
  - 3 – Phân vân / Bình thường  
  - 4 – Đồng ý  
  - 5 – Rất đồng ý  

Các mục hỏi bao phủ các khía cạnh: hài lòng tổng thể, giao diện – thao tác, quy trình đặt hàng/ thanh toán, an toàn, giao hàng, chất lượng sản phẩm, dịch vụ khách hàng, giá cả – khuyến mãi, ý định tiếp tục mua và giới thiệu cho người khác.

**Bảng 1. Mô tả các mục hỏi trong thang đo mức độ hài lòng TMĐT**

| Mã mục | Nội dung tóm tắt                                                   |
|--------|--------------------------------------------------------------------|
| Q1     | Hài lòng tổng thể về trải nghiệm mua sắm trên các sàn TMĐT        |
| Q2     | Mức độ dễ hiểu, dễ thao tác của giao diện/ứng dụng TMĐT           |
| Q3     | Mức độ nhanh chóng, thuận tiện của quy trình đặt hàng – thanh toán|
| Q4     | Cảm nhận an toàn khi thanh toán online trên sàn TMĐT              |
| Q5     | Mức độ đáp ứng kỳ vọng về thời gian giao hàng                     |
| Q6     | Mức độ phù hợp giữa mô tả/quảng cáo và sản phẩm nhận được         |
| Q7     | Mức độ hài lòng với dịch vụ chăm sóc khách hàng                   |
| Q8     | Đánh giá về giá cả và chương trình khuyến mãi trên sàn TMĐT       |
| Q9     | Ý định tiếp tục mua hàng trên các sàn TMĐT trong tương lai        |
| Q10    | Ý định giới thiệu mua hàng qua TMĐT cho người thân, bạn bè        |

#### 3.4. Quy trình thu thập và xử lý dữ liệu

1. Thiết kế bảng hỏi và mã hóa các mục hỏi Q1–Q10 theo thang 1–5.
2. Thu thập dữ liệu trong khoảng thời gian từ tháng 01 đến tháng 03 năm 2025 (dữ liệu được tổng hợp và lưu trong `survey_data.csv`).
3. Đọc dữ liệu bằng Python (thư viện `pandas`).
4. Mã hóa năm sinh (`year_of_birth`) thành biến `generation` theo khoảng:
   - 1965–1980 → Gen X
   - 1981–1996 → Millennials
   - 1997–2012 → Gen Z
5. Tính điểm `satisfaction` cho mỗi người tham gia:
   \[
   \text{satisfaction} = \frac{Q1 + Q2 + \dots + Q10}{10}
   \]
6. Kiểm tra dữ liệu thiếu, loại bỏ các trường hợp không thuộc ba nhóm thế hệ trên (nếu có).

#### 3.5. Phương pháp phân tích dữ liệu

Phân tích dữ liệu được thực hiện bằng Python, với các bước:

1. **Thống kê mô tả**:
   - Tính trung bình (M), độ lệch chuẩn (SD), cỡ mẫu (n) cho `satisfaction` theo từng `generation`.
2. **Kiểm tra giả định của ANOVA**:
   - **Giả định chuẩn**: sử dụng kiểm định Shapiro–Wilk cho `satisfaction` trong từng nhóm thế hệ.
   - **Giả định đồng nhất phương sai**: sử dụng kiểm định Levene cho `satisfaction` giữa ba nhóm.
3. **Phân tích One-way ANOVA**:
   - Sử dụng `scipy.stats.f_oneway` và `statsmodels` để ước lượng thống kê F, p-value và bảng ANOVA (tổng bình phương, bậc tự do, trung bình bình phương).
   - Công thức tổng quát:
     \[
     F = \frac{MS_{\text{between}}}{MS_{\text{residual}}}
     \]
     trong đó \(MS_{\text{between}}\) là phương sai giữa các nhóm và \(MS_{\text{residual}}\) (còn gọi là within/error) là phương sai phần dư trong nhóm.
4. **Kiểm định hậu nghiệm (Post-hoc)**:
   - Khi ANOVA cho kết quả có ý nghĩa (p < 0.05), sử dụng kiểm định Tukey HSD để xác định cặp thế hệ nào khác nhau có ý nghĩa.
5. **Ước lượng độ lớn ảnh hưởng (Effect size)**:
   - Tính \(\eta^2 = \frac{SS_{\text{between}}}{SS_{\text{total}}}\) từ bảng ANOVA để đánh giá mức độ ảnh hưởng của thế hệ tới mức độ hài lòng.

#### 3.6. Độ tin cậy của thang đo

Độ tin cậy nội tại của thang đo hài lòng TMĐT (10 mục Q1–Q10) được đánh giá bằng hệ số Cronbach's alpha. Kết quả cho thấy:

- **Cronbach's alpha = 0.969** (toàn bộ mẫu), vượt xa ngưỡng 0.7 thường được chấp nhận trong nghiên cứu xã hội và được xem là mức độ tin cậy **xuất sắc** (alpha > 0.9).
- Cronbach's alpha theo từng nhóm: Gen X (0.960), Millennials (0.957), Gen Z (0.954) - đều ở mức xuất sắc, chứng tỏ thang đo ổn định trong các nhóm thế hệ.
- Tương quan trung bình giữa các mục hỏi là 0.757, cho thấy các mục có liên quan chặt chẽ và cùng đo lường khái niệm "hài lòng TMĐT".

---

### 4. Kết quả nghiên cứu

#### 4.1. Thống kê mô tả

Bảng 2 trình bày trung bình, độ lệch chuẩn và cỡ mẫu điểm hài lòng TMĐT theo thế hệ:

**Bảng 2. Thống kê mô tả điểm hài lòng TMĐT theo thế hệ**

| Thế hệ       | n   | M    | SD   |
|--------------|-----|------|------|
| Gen Z        | 400 | 4.19 | 0.48 |
| Millennials  | 400 | 3.88 | 0.53 |
| Gen X        | 400 | 3.41 | 0.57 |

Trong đó: **n** là cỡ mẫu (số người trong nhóm), **M** là trung bình điểm hài lòng và **SD** là độ lệch chuẩn (mức độ phân tán điểm quanh giá trị trung bình).

Kết quả cho thấy:

- **Gen Z** có mức yêu thích/hài lòng cao nhất với trải nghiệm TMĐT;
- **Millennials** có mức hài lòng trung bình, vẫn khá cao;
- **Gen X** có mức hài lòng thấp hơn đáng kể so với hai nhóm còn lại.

Hình 1 dưới đây minh họa trực quan phân bố điểm hài lòng TMĐT giữa các thế hệ thông qua biểu đồ boxplot.

![Hình 1. Boxplot: So sánh mức độ hài lòng TMĐT theo thế hệ](fig1_boxplot_satisfaction_by_generation.png)

Quan sát Hình 1 cho thấy không chỉ trung bình (đường ngang trong box) mà cả phân bố điểm hài lòng đều tăng dần từ Gen X đến Millennials và Gen Z. Cụ thể, median của Gen Z cao nhất, tiếp theo là Millennials, và thấp nhất là Gen X. Độ phân tán (chiều cao của box và whiskers) của các nhóm tương đối tương đồng, củng cố nhận định về sự khác biệt có hệ thống giữa các thế hệ. Không có outliers cực đoan trong dữ liệu.

#### 4.2. Kiểm tra giả định ANOVA

Sau khi fit mô hình ANOVA, cần kiểm tra các giả định để đảm bảo tính hợp lệ của kết quả.

##### 4.2.1. Giả định phân phối chuẩn của residuals

**Giả định**: ANOVA yêu cầu **residuals (phần dư)** của mô hình có phân phối chuẩn N(0, σ²).

Residuals được tính sau khi fit mô hình: \(\text{residual}_i = y_i - \bar{y}_{\text{nhóm}_i}\), là sai lệch giữa giá trị quan sát và trung bình nhóm.

**Kiểm định Shapiro-Wilk cho residuals**:
- W = 0.9918
- p = 3.25 × 10⁻⁶

Với p < 0.05, có bằng chứng về vi phạm nhẹ giả định phân phối chuẩn.

**QQ Plot (Hình 2)**:

![Hình 2. Q-Q plot: Kiểm tra tính chuẩn của residuals](fig4_qqplot_residuals.png)

Hình 2 trình bày Q-Q plot của residuals từ mô hình ANOVA so với phân phối chuẩn lý thuyết. Các điểm residuals nằm khá sát với đường thẳng lý thuyết (màu đỏ), chỉ có một số điểm ở hai đuôi lệch nhẹ. Điều này cho thấy **vi phạm nhẹ** giả định phân phối chuẩn.

Tuy nhiên, theo lý thuyết, ANOVA tương đối robust (vững) với vi phạm giả định chuẩn khi: (1) cỡ mẫu lớn và bằng nhau giữa các nhóm (n=400 mỗi nhóm), (2) phân phối tương đối đối xứng, và (3) vi phạm không quá nghiêm trọng theo QQ plot (Field, 2013). Để kiểm chứng tính vững vàng của kết luận, nghiên cứu sử dụng thêm kiểm định phi tham số Kruskal-Wallis (xem mục 4.5).

##### 4.2.2. Giả định đồng nhất phương sai (Levene test)

Kiểm định Levene cho ba nhóm thế hệ cho kết quả:

- Levene: F = 11.83, p < 0.001.

**Giả định đồng nhất phương sai bị vi phạm** (p < 0.001). Tỷ lệ phương sai lớn nhất/nhỏ nhất = (0.573)²/(0.480)² ≈ 1.42. Theo quy tắc thực nghiệm (rule of thumb), ANOVA vẫn tương đối robust khi: (1) tỷ lệ phương sai < 3 (trong trường hợp này 1.42 < 3), và (2) cỡ mẫu bằng nhau hoàn toàn giữa các nhóm (n=400 cho cả 3 nhóm). Trong trường hợp vi phạm giả định đồng nhất phương sai nghiêm trọng hơn, nên sử dụng Welch's ANOVA (không giả định phương sai bằng nhau).

**Bảng 3. Tóm tắt kết quả kiểm tra giả định ANOVA**

| Giả định           | Phương pháp kiểm tra | Kết quả | Kết luận |
|-------------------|---------------------|---------|----------|
| Phân phối chuẩn residuals | Shapiro-Wilk | W=0.9918, p=3.25×10⁻⁶ | **Vi phạm nhẹ**, ANOVA robust với n lớn cân bằng |
| Phân phối chuẩn residuals | QQ plot | Hình 2 | Residuals gần chuẩn, lệch nhẹ ở đuôi |
| Đồng nhất phương sai | Levene test | F=11.83, p<0.001 | **Vi phạm**, nhưng tỷ lệ=1.42<3, chấp nhận được |

#### 4.3. Kết quả One-way ANOVA

Bảng ANOVA cho thấy:

- F(2, 1197) = 221.88  
- p < 0.001 (gần như bằng 0)

Ước lượng độ lớn ảnh hưởng:

- Tổng bình phương giữa nhóm: \(SS_{\text{between}} = 124.11\)
- Tổng bình phương toàn bộ: \(SS_{\text{total}} = 458.90\)
- \(\eta^2 = \frac{SS_{\text{between}}}{SS_{\text{total}}} = 0.27\)

Theo các ngưỡng diễn giải thông dụng (ví dụ: 0.01 = nhỏ, 0.06 = trung bình, 0.14 = lớn), giá trị \(\eta^2 = 0.27\) cho thấy **ảnh hưởng rất lớn** của biến thế hệ đến mức độ hài lòng TMĐT; nói cách khác, khoảng **27% phương sai** điểm hài lòng trong mẫu có thể được giải thích bởi yếu tố thế hệ.

**Bảng 4. Kết quả phân tích phương sai One-way ANOVA**

| Nguồn biến thiên         | SS     | df   | MS    | F      | p       |
|--------------------------|--------|------|-------|--------|---------|
| Giữa nhóm (Between)      | 124.11 | 2    | 62.06 | 221.88 | <0.001  |
| Trong nhóm (Residual)    | 334.79  | 1197 | 0.28  |        |         |
| Tổng (Total)\*           | 458.90 | 1199 |       |        |         |

\*SS tổng được ước lượng từ \(SS_{\text{between}} + SS_{\text{within}}\).

**Kết luận từ ANOVA**:  
Với \(\alpha = 0.05\), p-value rất nhỏ nên ta **bác bỏ giả thuyết H0**. Do đó, có thể kết luận rằng:

> **Mức độ hài lòng TMĐT khác nhau có ý nghĩa thống kê giữa các thế hệ Gen X, Millennials và Gen Z.**

#### 4.4. Kiểm định hậu nghiệm Tukey HSD

Do ANOVA cho kết quả có ý nghĩa, kiểm định hậu nghiệm Tukey HSD được sử dụng để so sánh từng cặp nhóm:

- **Gen Z vs Gen X**:
  - Chênh lệch trung bình (Gen Z − Gen X) = 0.78
  - p < 0.001
  - Gen Z hài lòng hơn Gen X với mức chênh lệch lớn và có ý nghĩa thống kê.

- **Millennials vs Gen X**:
  - Chênh lệch trung bình (Millennials − Gen X) = 0.48
  - p < 0.001
  - Millennials hài lòng hơn Gen X với mức chênh lệch đáng kể và có ý nghĩa thống kê.

- **Gen Z vs Millennials**:
  - Chênh lệch trung bình (Gen Z − Millennials) = 0.31
  - p < 0.001
  - Gen Z hài lòng hơn Millennials, khác biệt cũng có ý nghĩa thống kê.

Tóm lại, **cả ba cặp thế hệ đều có sự khác biệt có ý nghĩa thống kê** về mức độ hài lòng TMĐT, với thứ tự:

> **Gen Z > Millennials > Gen X**

**Bảng 5. Tóm tắt kết quả kiểm định hậu nghiệm Tukey HSD**

| Cặp so sánh           | Chênh lệch trung bình | p      | Kết luận                                  |
|-----------------------|------------------------|--------|-------------------------------------------|
| Gen Z − Gen X        | 0.78                   | <0.001 | Khác biệt có ý nghĩa, Gen Z > Gen X      |
| Millennials − Gen X  | 0.48                   | <0.001 | Khác biệt có ý nghĩa, Millennials > Gen X|
| Gen Z − Millennials  | 0.31                   | <0.001 | Khác biệt có ý nghĩa, Gen Z > Millennials|

#### 4.5. Kiểm định Kruskal–Wallis (robustness check)

Để kiểm tra độ bền vững của kết luận, kiểm định phi tham số Kruskal–Wallis (không yêu cầu giả định phân phối chuẩn) được sử dụng để so sánh thứ hạng điểm hài lòng giữa ba nhóm thế hệ. Kết quả cho thấy:

- Kruskal–Wallis: H(2) = 340.64, p < 0.001 (gần như bằng 0).

Điều này cho thấy vẫn có sự khác biệt có ý nghĩa thống kê về mức độ hài lòng TMĐT giữa ba thế hệ ngay cả khi không giả định phân phối chuẩn, và thứ tự các nhóm (Gen Z > Millennials > Gen X) phù hợp với kết quả từ ANOVA.

---

### 5. Thảo luận

Kết quả nghiên cứu cho thấy có mối **liên hệ có ý nghĩa thống kê** giữa thế hệ và mức độ hài lòng TMĐT. Các giải thích dưới đây là **giả thuyết** dựa trên lý thuyết về hành vi người tiêu dùng và nghiên cứu trước đây, **chưa được kiểm chứng trực tiếp** trong nghiên cứu này:

1. **Gen Z** có mức độ hài lòng cao nhất - có thể liên quan đến:
   - Đặc điểm thế hệ sinh ra trong môi trường số, quen thuộc với ứng dụng di động, ví điện tử, mạng xã hội.
   - Khả năng thích nghi cao với quy trình mua hàng trực tuyến.
   - Được các nền tảng TMĐT nhắm đến thông qua các chương trình khuyến mãi, flash sale, voucher.

2. **Millennials** có mức hài lòng trung bình - có thể do:
   - Vừa hưởng lợi từ sự tiện lợi của TMĐT, vừa có yêu cầu cao về chất lượng dịch vụ.
   - Áp lực công việc và gia đình khiến họ coi trọng tiết kiệm thời gian.
   - Kỳ vọng cao về trải nghiệm tổng thể.

3. **Gen X** có mức hài lòng thấp nhất - có thể do:
   - Thói quen mua hàng trực tiếp (offline) vẫn phổ biến.
   - Mức độ e ngại về rủi ro thanh toán online, bảo mật thông tin.
   - Ít quen thuộc với các tính năng, ưu đãi trên nền tảng TMĐT.

**Lưu ý:** Đây là nghiên cứu **tương quan** (correlational), không phải nghiên cứu **thí nghiệm** (experimental). Do đó, không thể khẳng định **mối quan hệ nhân quả** giữa thế hệ và mức độ hài lòng. Có thể có các **biến nhiễu** (confounding variables) chưa được kiểm soát như thu nhập, trình độ học vấn, khu vực địa lý, loại sản phẩm, tần suất mua hàng, v.v. Để khẳng định nhân quả, cần có thiết kế nghiên cứu thí nghiệm hoặc phương pháp phân tích nhân quả nâng cao hơn.

Về mặt phương pháp, nghiên cứu này cũng cho thấy tầm quan trọng của việc:

- **Kiểm tra giả định** trước khi sử dụng ANOVA (chuẩn, đồng nhất phương sai);
- **Báo cáo độ lớn ảnh hưởng (effect size)** bên cạnh p-value, giúp người đọc hiểu mức độ thực chất của khác biệt;
- **Thực hiện kiểm định hậu nghiệm** khi H0 bị bác bỏ để biết cụ thể nhóm nào khác nhóm nào.

---

### 6. Kết luận

Trên cơ sở dữ liệu mức độ hài lòng TMĐT của 1200 người tiêu dùng thuộc ba thế hệ Gen X, Millennials và Gen Z, nghiên cứu cho thấy:

1. **Mức độ hài lòng TMĐT khác nhau có ý nghĩa thống kê giữa các thế hệ** (F(2, 1197) = 221.88, p < 0.001, \(\eta^2 = 0.27\)).  
2. Thứ tự mức độ hài lòng là: **Gen Z cao nhất** (M = 4.19), tiếp đến **Millennials** (M = 3.88), và thấp nhất là **Gen X** (M = 3.41).  
3. Tất cả các cặp so sánh đều có khác biệt có ý nghĩa thống kê theo kiểm định hậu nghiệm Tukey HSD.

Kết quả góp phần làm rõ vai trò của yếu tố thế hệ trong đánh giá TMĐT và gợi ý rằng các doanh nghiệp cần cân nhắc khác biệt thế hệ khi thiết kế trải nghiệm khách hàng và chiến lược marketing số.

---

### 7. Hạn chế và gợi ý nghiên cứu tiếp theo

- Mẫu nghiên cứu chưa được chọn theo phương pháp ngẫu nhiên đại diện, nên:
  - Không thể suy rộng kết luận cho toàn bộ dân số người tiêu dùng TMĐT;
  - Các kết quả cần được kiểm chứng thêm trên các bộ dữ liệu độc lập.

- Dữ liệu hiện tại đã đáp ứng tốt các giả định của ANOVA (chuẩn, đồng nhất phương sai) và được kiểm chứng thêm bằng kiểm định phi tham số Kruskal–Wallis. Tuy nhiên, trong các nghiên cứu mở rộng với mẫu lớn hơn hoặc phân bố phức tạp hơn, vẫn có thể cân nhắc sử dụng Welch ANOVA hoặc các phương pháp phi tham số khác để đảm bảo tính vững của kết luận.

- Hướng phát triển:
  - Thu thập dữ liệu thực tế với cỡ mẫu lớn hơn, đại diện hơn cho từng thế hệ.
  - Bổ sung thêm các biến độc lập khác (giới tính, thu nhập, tần suất mua hàng, nền tảng TMĐT thường dùng, loại sản phẩm) để xây dựng mô hình phân tích đa biến (ANOVA hai nhân tố, hồi quy tuyến tính, v.v.).
  - Kiểm định độ tin cậy (Cronbach’s alpha) và tính giá trị của thang đo hài lòng trước khi tiến hành phân tích ANOVA.

---

### 8. Tài liệu tham khảo (tham khảo gợi ý)

Anderson, R. E., & Srinivasan, S. S. (2003). E-satisfaction and e-loyalty: A contingency framework. *Psychology & Marketing, 20*(2), 123–138.

Parasuraman, A., Zeithaml, V. A., & Berry, L. L. (1988). SERVQUAL: A multiple-item scale for measuring consumer perceptions of service quality. *Journal of Retailing, 64*(1), 12–40.

Zeithaml, V. A., Berry, L. L., & Parasuraman, A. (1996). The behavioral consequences of service quality. *Journal of Marketing, 60*(2), 31–46.

Field, A. (2013). *Discovering statistics using IBM SPSS statistics* (4th ed.). Sage.
