# Nghiên cứu One-way ANOVA: So sánh mức độ hài lòng với TMĐT giữa các thế hệ

## Tổng quan

Nghiên cứu này phân tích mức độ hài lòng với thương mại điện tử (TMĐT) giữa ba thế hệ người tiêu dùng: **Gen X (1965–1980), Millennials (1981–1996) và Gen Z (1997–2012)** sử dụng phương pháp phân tích phương sai một nhân tố (One-way ANOVA).

## Kết quả chính

- **Độ tin cậy thang đo**:
  - Cronbach's Alpha = 0.969 (xuất sắc)
  - Tương quan trung bình giữa các mục hỏi = 0.757 (cao)
- **Gen Z** có mức độ hài lòng cao nhất (M = 4.19, SD = 0.48)
- **Millennials** có mức độ hài lòng trung bình (M = 3.88, SD = 0.53)
- **Gen X** có mức độ hài lòng thấp nhất (M = 3.41, SD = 0.57)
- Kiểm định ANOVA: F(2, 1197) = 221.88, p < 0.001, η² = 0.27 (ảnh hưởng lớn)
- Tất cả các cặp so sánh đều có khác biệt có ý nghĩa thống kê (Tukey HSD, p < 0.001)
- Kiểm định phi tham số: Kruskal-Wallis H(2) = 340.64, p < 0.001

## Cấu trúc dự án

```
oneway-anova/
├── README.md                                      # File này
├── survey_questionnaire.md                        # Phiếu khảo sát
├── survey_data.csv                                # Dữ liệu khảo sát (n = 1200)
├── ecommerce_satisfaction.ipynb                   # Jupyter notebook phân tích
├── ecommerce_anova_report.md                      # Báo cáo nghiên cứu đầy đủ (Markdown)
├── ecommerce_anova_report.pdf                     # Báo cáo nghiên cứu đầy đủ (PDF)
├── analysis_results.json                          # Kết quả phân tích (JSON)
├── VALIDATION_REPORT.md                           # Báo cáo kiểm tra toàn bộ project
├── CHANGELOG.md                                   # Nhật ký thay đổi
├── SUMMARY.md                                     # Tóm tắt công việc
├── fig1_boxplot_satisfaction_by_generation.png    # Boxplot
├── fig2_hist_satisfaction_overall.png             # Histogram
├── fig3_violin_satisfaction_by_generation.png     # Violin plot
└── fig4_qqplot_residuals.png                      # QQ plot residuals
```

## Yêu cầu hệ thống

### Python packages
```bash
python >= 3.8
pandas
numpy
scipy
statsmodels
seaborn
matplotlib
jupyter
```

### Cài đặt
```bash
# Tạo virtual environment
python -m venv .venv

# Kích hoạt virtual environment
# macOS/Linux:
source .venv/bin/activate
# Windows:
.venv\Scripts\activate

# Cài đặt packages
pip install pandas numpy scipy statsmodels seaborn matplotlib jupyter
```

## Cách sử dụng

### 1. Xem báo cáo nghiên cứu
- **PDF**: Mở file `ecommerce_anova_report.pdf`
- **Markdown**: Xem file `ecommerce_anova_report.md`

### 2. Chạy phân tích
```bash
# Kích hoạt virtual environment
source .venv/bin/activate

# Mở Jupyter notebook
jupyter notebook ecommerce_satisfaction.ipynb
```

### 3. Xem dữ liệu và phiếu khảo sát
- **Dữ liệu**: `survey_data.csv` (1200 dòng, 12 cột)
- **Phiếu khảo sát**: `survey_questionnaire.md`

## Phương pháp nghiên cứu

### Thiết kế nghiên cứu
- **Thiết kế**: Định lượng, so sánh giữa các nhóm
- **Cỡ mẫu**: n = 1200 (Gen Z: 400, Millennials: 400, Gen X: 400)
- **Công cụ**: Bảng hỏi với thang đo Likert 5 mức (10 câu hỏi)
- **Độ tin cậy**: Cronbach's alpha = 0.969 (xuất sắc)

### Biến nghiên cứu
- **Biến độc lập**: Thế hệ (Generation) - 3 mức
- **Biến phụ thuộc**: Điểm hài lòng (Satisfaction) - trung bình Q1-Q10

### Phân tích thống kê
1. Thống kê mô tả (mean, SD, n)
2. Kiểm tra độ tin cậy: Cronbach's alpha
3. One-way ANOVA
4. Kiểm tra giả định ANOVA:
   - Shapiro-Wilk test (phân phối chuẩn của residuals)
   - Levene test (đồng nhất phương sai)
   - QQ plot (kiểm tra trực quan phân phối chuẩn của residuals)
5. Kiểm định hậu nghiệm: Tukey HSD
6. Effect size: η² (eta squared)
7. Robustness check: Kruskal-Wallis test

## Kết luận

Nghiên cứu cho thấy có sự khác biệt có ý nghĩa thống kê về mức độ hài lòng với TMĐT giữa các thế hệ, với thứ tự: **Gen Z > Millennials > Gen X**. Kết quả này có ý nghĩa thực tiễn cho các doanh nghiệp TMĐT trong việc thiết kế trải nghiệm khách hàng phù hợp với từng nhóm thế hệ.

## Tài liệu tham khảo

- Anderson, R. E., & Srinivasan, S. S. (2003). E-satisfaction and e-loyalty: A contingency framework. *Psychology & Marketing, 20*(2), 123–138.
- Parasuraman, A., Zeithaml, V. A., & Berry, L. L. (1988). SERVQUAL: A multiple-item scale for measuring consumer perceptions of service quality. *Journal of Retailing, 64*(1), 12–40.
- Field, A. (2013). *Discovering statistics using IBM SPSS statistics* (4th ed.). Sage.

## Giấy phép

Nghiên cứu này được thực hiện cho mục đích học tập và nghiên cứu.

## Tác giả

Nghiên cứu mẫu về One-way ANOVA - 2025

