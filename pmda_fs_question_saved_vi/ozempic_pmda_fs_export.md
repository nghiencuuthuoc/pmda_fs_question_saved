# PMDA FS Question Export — ozempic

Generated at: 2026-03-29T18:55:29
Question bank: E:\PharmAppDev\database\PMDA_v1_vi\pmda_question_bank_v8_vi\PMDA_RAG_Reusable_Question_Bank_vi.md
Index dir: E:\PharmAppDev\database\PMDA_v1_vi\pmda_fs_index_vi
Questions completed: 111

## Phase summaries

```json
{
  "non_ollama": {
    "phase": "non_ollama",
    "count": 111,
    "success": 111,
    "failed": 0,
    "elapsed_seconds_sum": 77.6236,
    "elapsed_seconds_avg": 0.6993,
    "retrieval_seconds_sum": 12.8245,
    "generation_seconds_sum": 6.6467,
    "estimated_context_tokens_sum": 55643,
    "estimated_prompt_tokens_sum": 65590,
    "estimated_answer_tokens_sum": 58402
  },
  "ollama": {
    "phase": "ollama",
    "count": 0,
    "success": 0,
    "failed": 0,
    "elapsed_seconds_sum": 0,
    "elapsed_seconds_avg": 0.0,
    "retrieval_seconds_sum": 0,
    "generation_seconds_sum": 0,
    "estimated_context_tokens_sum": 0,
    "estimated_prompt_tokens_sum": 0,
    "estimated_answer_tokens_sum": 0
  },
  "all": {
    "count": 111,
    "success": 111,
    "failed": 0,
    "elapsed_seconds_sum": 77.6236
  }
}
```

## 1. Các cảnh báo chính và chống chỉ định là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > Cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:07
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.2104
- Retrieval seconds: 0.0824
- Generation seconds: 0.1254
- Estimated prompt tokens: 965
- Estimated answer tokens: 325

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c c\u1ea3nh b\u00e1o ch\u00ednh v\u00e0 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các cảnh báo chính và chống chỉ định là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5973
  **** Tiêu chí tổng hợp:
  1,76 (khoảng tin cậy 95%:
  Ugobi Tiêm dưới da (Chỉ định:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3940
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 65 | mục=indication | điểm=6.9830
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  mg mỗi tuần một lần.
  4.1 Chỉ định điều trị
- Ozempic | interview_form | trang 64 | mục=indication | điểm=6.9421
  0,5 mg mỗi lần tiêm.
  XII.Tài liệu tham khảo
  Hiệu quả hoặc tác dụng
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=6.9167
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 17 | mục=indication | điểm=6.8495
  580 bệnh nhân, nhẹ:
  trường trung học cơ sở
  261 bệnh nhân, trung bình).

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 65
- Ozempic / interview_form / trang 64
- Ozempic / smpc_label / trang 1
- Ozempic / smpc_label / trang 17
```

## 2. Các chống chỉ định là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:07
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.3343
- Retrieval seconds: 0.0792
- Generation seconds: 0.0484
- Estimated prompt tokens: 1154
- Estimated answer tokens: 318

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các chống chỉ định là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication, indication

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 65 | mục=indication | điểm=6.9752
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  mg mỗi tuần một lần.
  4.1 Chỉ định điều trị
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=6.9094
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 64 | mục=indication | điểm=6.9046
  0,5 mg mỗi lần tiêm.
  XII.Tài liệu tham khảo
  Hiệu quả hoặc tác dụng
- Ozempic | smpc_label | trang 17 | mục=indication | điểm=6.8311
  580 bệnh nhân, nhẹ:
  trường trung học cơ sở
  261 bệnh nhân, trung bình).
- Ozempic | interview_form | trang 67 | mục=indication | điểm=6.7836
  Ngoài ra, bệnh nhân
  hiệu quả hoặc tác dụng
  bệnh tiểu đường loại 2

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 65
- Ozempic / smpc_label / trang 1
- Ozempic / interview_form / trang 64
- Ozempic / smpc_label / trang 17
- Ozempic / interview_form / trang 67
```

## 3. Các chỉ định đã được phê duyệt và hướng dẫn liều dùng là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:07
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.4647
- Retrieval seconds: 0.0767
- Generation seconds: 0.0555
- Estimated prompt tokens: 1160
- Estimated answer tokens: 454

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ch\u1ec9 \u0111\u1ecbnh \u0111\u00e3 \u0111\u01b0\u1ee3c ph\u00ea duy\u1ec7t v\u00e0 h\u01b0\u1edbng d\u1eabn li\u1ec1u d\u00f9ng l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các chỉ định đã được phê duyệt và hướng dẫn liều dùng là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: dosage, indication

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 64 | mục=indication | điểm=7.2183
  1 CHỈ ĐỊNH VÀ CÔNG DỤNG
  OZEMPIC® được chỉ định:
  leo thang dưới đây để giảm nguy cơ phản ứng bất lợi về đường tiêu hóa [xem Cảnh báo và
- Ozempic | interview_form | trang 65 | mục=indication | điểm=7.1402
  4.1 Chỉ định điều trị
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  Ozempic được chỉ định để điều trị cho người lớn mắc bệnh đái tháo đường týp 2 không được kiểm soát đầy đủ dưới dạng thuốc hỗ trợ cho chế độ ăn kiêng và tập thể dục.
- Ozempic | interview_form | trang 66 | mục=dosage | điểm=6.9811
  Tính an toàn và hiệu quả của semaglutide ở trẻ em và thanh thiếu niên dưới 18 tuổi vẫn chưa được thiết lập.
  Không có dữ liệu có sẵn.
  Semaglutide 0,25 mg không phải là liều duy trì.
- Ozempic | interview_form | trang 70 | mục=dosage | điểm=6.9076
  Tính an toàn và hiệu quả của OZEMPIC® chưa được thiết lập ở bệnh nhi.
  Nhóm đối tượng đặc biệt Đối tượng nhi khoa Tính an toàn và hiệu quả của semaglutide ở trẻ em và thanh thiếu niên dưới 18 tuổi vẫn chưa được thiết lập.
  9.5 Phụ nữ mang thai
- Ozempic | smpc_label | trang 17 | mục=indication | điểm=6.8311
  Viên nén Libersus (Chỉ định:
  Tiêm dưới da Ugobi (chỉ định:
  Ozempic tiêm dưới da (Chỉ định:

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 64
- Ozempic / interview_form / trang 65
- Ozempic / interview_form / trang 66
- Ozempic / interview_form / trang 70
- Ozempic / smpc_label / trang 17
```

## 4. Các thận trọng quan trọng trước khi dùng thuốc này là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:07
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.6207
- Retrieval seconds: 0.0754
- Generation seconds: 0.0818
- Estimated prompt tokens: 717
- Estimated answer tokens: 680

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c th\u1eadn tr\u1ecdng quan tr\u1ecdng tr\u01b0\u1edbc khi d\u00f9ng thu\u1ed1c n\u00e0y l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các thận trọng quan trọng trước khi dùng thuốc này là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 5. Trước khi dùng thuốc này, bệnh nhân cần lưu ý điều gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.5888
- Retrieval seconds: 0.083
- Generation seconds: 0.0835
- Estimated prompt tokens: 265
- Estimated answer tokens: 518

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u01b0\u1edbc khi d\u00f9ng thu\u1ed1c n\u00e0y, b\u1ec7nh nh\u00e2n c\u1ea7n l\u01b0u \u00fd \u0111i\u1ec1u g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Trước khi dùng thuốc này, bệnh nhân cần lưu ý điều gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 6. Những đối tượng nào không nên dùng thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.5618
- Retrieval seconds: 0.0902
- Generation seconds: 0.0146
- Estimated prompt tokens: 263
- Estimated answer tokens: 516

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng \u0111\u1ed1i t\u01b0\u1ee3ng n\u00e0o kh\u00f4ng n\u00ean d\u00f9ng thu\u1ed1c n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những đối tượng nào không nên dùng thuốc này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 7. Bệnh nhân nên tránh những gì khi đang dùng thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:08
- Elapsed seconds: 0.525
- Retrieval seconds: 0.079
- Generation seconds: 0.0157
- Estimated prompt tokens: 265
- Estimated answer tokens: 518

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "B\u1ec7nh nh\u00e2n n\u00ean tr\u00e1nh nh\u1eefng g\u00ec khi \u0111ang d\u00f9ng thu\u1ed1c n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Bệnh nhân nên tránh những gì khi đang dùng thuốc này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 8. Các phản ứng có hại chính và biến cố bất lợi nghiêm trọng là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:09
- Elapsed seconds: 0.5669
- Retrieval seconds: 0.0822
- Generation seconds: 0.1171
- Estimated prompt tokens: 580
- Estimated answer tokens: 400

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ph\u1ea3n \u1ee9ng c\u00f3 h\u1ea1i ch\u00ednh v\u00e0 bi\u1ebfn c\u1ed1 b\u1ea5t l\u1ee3i nghi\u00eam tr\u1ecdng l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các phản ứng có hại chính và biến cố bất lợi nghiêm trọng là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: adverse_event

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=7.2427
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | safety_notice | trang 2 | mục=adverse_event | điểm=7.0123
  11.1 Tác dụng phụ nghiêm trọng
  Viêm túi mật, viêm đường mật, vàng da ứ mật
  Tác dụng phụ
- Ozempic | patient_guide | trang 1 | mục=adverse_event | điểm=6.8440
  bệnh tiểu đường loại 2
  Ozempic tiêm dưới da 2mg
  Cập nhật tháng 7 năm 2025
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | safety_notice | trang 1 | mục=adverse_event | điểm=6.6339
  396 Thuốc trị đái tháo đường
  11.1 Tác dụng phụ nghiêm trọng
  Có nguy cơ tắc ruột bao gồm tắc ruột.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 37
- Ozempic / safety_notice / trang 2
- Ozempic / patient_guide / trang 1
- Ozempic / interview_form / trang 72
- Ozempic / safety_notice / trang 1
```

## 9. Có thận trọng nào cho bệnh nhi, người cao tuổi, phụ nữ mang thai hoặc cho con bú không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:09
- Elapsed seconds: 0.5608
- Retrieval seconds: 0.0819
- Generation seconds: 0.0777
- Estimated prompt tokens: 626
- Estimated answer tokens: 640

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 th\u1eadn tr\u1ecdng n\u00e0o cho b\u1ec7nh nhi, ng\u01b0\u1eddi cao tu\u1ed5i, ph\u1ee5 n\u1eef mang thai ho\u1eb7c cho con b\u00fa kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có thận trọng nào cho bệnh nhi, người cao tuổi, phụ nữ mang thai hoặc cho con bú không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=7.7382
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.
  Người nộp đơn đã trả lời như sau.
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 68 | mục=pregnancy | điểm=6.9967
  tiếp xúc với con người).
  (phơi nhiễm ≥3X ở người).
  từ ngày mang thai thứ 16 đến ngày thứ 140.
- Ozempic | interview_form | trang 69 | mục=pregnancy | điểm=6.9092
  Không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ.
  Vì không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ nên không nên sử dụng semaglutide trong thời gian cho con bú.
  Tờ hướng dẫn sử dụng của Úc
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]

Nguồn:
- Ozempic / smpc_label / trang 29
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 68
- Ozempic / interview_form / trang 69
- Ozempic / safety_notice / trang 1
```

## 10. Hiển thị các trang nói về cảnh báo, chống chỉ định và thận trọng.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:09
- Elapsed seconds: 0.6049
- Retrieval seconds: 0.1127
- Generation seconds: 0.0345
- Estimated prompt tokens: 970
- Estimated answer tokens: 331

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb c\u00e1c trang n\u00f3i v\u1ec1 c\u1ea3nh b\u00e1o, ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh v\u00e0 th\u1eadn tr\u1ecdng." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Hiển thị các trang nói về cảnh báo, chống chỉ định và thận trọng. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5973
  **** Tiêu chí tổng hợp:
  1,76 (khoảng tin cậy 95%:
  Ugobi Tiêm dưới da (Chỉ định:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3940
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 65 | mục=indication | điểm=6.9830
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  mg mỗi tuần một lần.
  4.1 Chỉ định điều trị
- Ozempic | interview_form | trang 64 | mục=indication | điểm=6.9421
  0,5 mg mỗi lần tiêm.
  XII.Tài liệu tham khảo
  Hiệu quả hoặc tác dụng
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=6.9167
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 17 | mục=indication | điểm=6.8495
  580 bệnh nhân, nhẹ:
  trường trung học cơ sở
  261 bệnh nhân, trung bình).

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 65
- Ozempic / interview_form / trang 64
- Ozempic / smpc_label / trang 1
- Ozempic / smpc_label / trang 17
```

## 11. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:08
- Finished: 2026-03-29T18:53:09
- Elapsed seconds: 0.7712
- Retrieval seconds: 0.2147
- Generation seconds: 0.0467
- Estimated prompt tokens: 258
- Estimated answer tokens: 512

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 12. Liệt kê đầy đủ thành phần định tính của sản phẩm.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:09
- Finished: 2026-03-29T18:53:09
- Elapsed seconds: 0.8347
- Retrieval seconds: 0.2269
- Generation seconds: 0.0358
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea \u0111\u1ea7y \u0111\u1ee7 th\u00e0nh ph\u1ea7n \u0111\u1ecbnh t\u00ednh c\u1ee7a s\u1ea3n ph\u1ea9m." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Liệt kê đầy đủ thành phần định tính của sản phẩm. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 13. Thành phần định lượng trên mỗi đơn vị liều là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:09
- Finished: 2026-03-29T18:53:10
- Elapsed seconds: 1.0864
- Retrieval seconds: 0.2674
- Generation seconds: 0.1422
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Th\u00e0nh ph\u1ea7n \u0111\u1ecbnh l\u01b0\u1ee3ng tr\u00ean m\u1ed7i \u0111\u01a1n v\u1ecb li\u1ec1u l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Thành phần định lượng trên mỗi đơn vị liều là gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 14. Có những dạng bào chế và hàm lượng nào?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:09
- Finished: 2026-03-29T18:53:10
- Elapsed seconds: 1.2413
- Retrieval seconds: 0.2319
- Generation seconds: 0.0699
- Estimated prompt tokens: 262
- Estimated answer tokens: 514

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng d\u1ea1ng b\u00e0o ch\u1ebf v\u00e0 h\u00e0m l\u01b0\u1ee3ng n\u00e0o?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có những dạng bào chế và hàm lượng nào cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 15. Những tá dược nào có trong viên 50 mg và 100 mg?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:09
- Finished: 2026-03-29T18:53:10
- Elapsed seconds: 1.2205
- Retrieval seconds: 0.1828
- Generation seconds: 0.0468
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 trong vi\u00ean 50 mg v\u00e0 100 mg?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào có trong viên 50 mg và 100 mg cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 16. Tá dược có khác nhau giữa các hàm lượng của sản phẩm không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:09
- Finished: 2026-03-29T18:53:11
- Elapsed seconds: 1.6784
- Retrieval seconds: 0.1147
- Generation seconds: 0.0293
- Estimated prompt tokens: 266
- Estimated answer tokens: 520

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e1 d\u01b0\u1ee3c c\u00f3 kh\u00e1c nhau gi\u1eefa c\u00e1c h\u00e0m l\u01b0\u1ee3ng c\u1ee7a s\u1ea3n ph\u1ea9m kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tá dược có khác nhau giữa các hàm lượng của sản phẩm không cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 17. Những thành phần công thức nào được liệt kê cho sản phẩm này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:10
- Finished: 2026-03-29T18:53:11
- Elapsed seconds: 0.9532
- Retrieval seconds: 0.1672
- Generation seconds: 0.0401
- Estimated prompt tokens: 267
- Estimated answer tokens: 520

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea cho s\u1ea3n ph\u1ea9m n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thành phần công thức nào được liệt kê cho sản phẩm này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 18. Tài liệu có phân biệt hoạt chất với tá dược không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:10
- Finished: 2026-03-29T18:53:11
- Elapsed seconds: 0.8168
- Retrieval seconds: 0.1243
- Generation seconds: 0.042
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e0i li\u1ec7u c\u00f3 ph\u00e2n bi\u1ec7t ho\u1ea1t ch\u1ea5t v\u1edbi t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tài liệu có phân biệt hoạt chất với tá dược không cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 19. Những tá dược/phụ gia dược dụng nào được nêu trong nhãn?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:10
- Finished: 2026-03-29T18:53:11
- Elapsed seconds: 0.1946
- Retrieval seconds: 0.167
- Generation seconds: 0.0264
- Estimated prompt tokens: 266
- Estimated answer tokens: 519

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c/ph\u1ee5 gia d\u01b0\u1ee3c d\u1ee5ng n\u00e0o \u0111\u01b0\u1ee3c n\u00eau trong nh\u00e3n?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược/phụ gia dược dụng nào được nêu trong nhãn cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 20. Hiển thị phần thành phần.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:11
- Finished: 2026-03-29T18:53:11
- Elapsed seconds: 0.7801
- Retrieval seconds: 0.1878
- Generation seconds: 0.0673
- Estimated prompt tokens: 258
- Estimated answer tokens: 511

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb ph\u1ea7n th\u00e0nh ph\u1ea7n." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Hiển thị phần thành phần. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 21. Chỉ hiển thị thông tin về tá dược.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:11
- Finished: 2026-03-29T18:53:12
- Elapsed seconds: 0.8854
- Retrieval seconds: 0.2408
- Generation seconds: 0.075
- Estimated prompt tokens: 260
- Estimated answer tokens: 514

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ch\u1ec9 hi\u1ec3n th\u1ecb th\u00f4ng tin v\u1ec1 t\u00e1 d\u01b0\u1ee3c." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Chỉ hiển thị thông tin về tá dược. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 22. Trích xuất danh sách tá dược và dạng bào chế.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:11
- Finished: 2026-03-29T18:53:12
- Elapsed seconds: 0.969
- Retrieval seconds: 0.2144
- Generation seconds: 0.0354
- Estimated prompt tokens: 263
- Estimated answer tokens: 516

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u00edch xu\u1ea5t danh s\u00e1ch t\u00e1 d\u01b0\u1ee3c v\u00e0 d\u1ea1ng b\u00e0o ch\u1ebf." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Trích xuất danh sách tá dược và dạng bào chế. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 23. Tóm tắt thành phần công thức và các đặc tính dược học/công nghệ của sản phẩm.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:11
- Finished: 2026-03-29T18:53:12
- Elapsed seconds: 1.1481
- Retrieval seconds: 0.1681
- Generation seconds: 0.1574
- Estimated prompt tokens: 271
- Estimated answer tokens: 524

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c v\u00e0 c\u00e1c \u0111\u1eb7c t\u00ednh d\u01b0\u1ee3c h\u1ecdc/c\u00f4ng ngh\u1ec7 c\u1ee7a s\u1ea3n ph\u1ea9m." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần công thức và các đặc tính dược học/công nghệ của sản phẩm. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 24. Liệt kê tất cả tá dược trong công thức.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:11
- Finished: 2026-03-29T18:53:12
- Elapsed seconds: 1.1186
- Retrieval seconds: 0.1761
- Generation seconds: 0.0454
- Estimated prompt tokens: 262
- Estimated answer tokens: 515

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea t\u1ea5t c\u1ea3 t\u00e1 d\u01b0\u1ee3c trong c\u00f4ng th\u1ee9c." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Liệt kê tất cả tá dược trong công thức. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 25. Liệt kê tất cả thành phần không có hoạt tính.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:12
- Finished: 2026-03-29T18:53:13
- Elapsed seconds: 0.9616
- Retrieval seconds: 0.1325
- Generation seconds: 0.0285
- Estimated prompt tokens: 263
- Estimated answer tokens: 516

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea t\u1ea5t c\u1ea3 th\u00e0nh ph\u1ea7n kh\u00f4ng c\u00f3 ho\u1ea1t t\u00ednh." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Liệt kê tất cả thành phần không có hoạt tính. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 26. Những thành phần không có hoạt tính nào được liệt kê trong tài liệu này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:12
- Finished: 2026-03-29T18:53:13
- Elapsed seconds: 0.8767
- Retrieval seconds: 0.1413
- Generation seconds: 0.0229
- Estimated prompt tokens: 270
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n kh\u00f4ng c\u00f3 ho\u1ea1t t\u00ednh n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea trong t\u00e0i li\u1ec7u n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thành phần không có hoạt tính nào được liệt kê trong tài liệu này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 27. Những tá dược nào nhiều khả năng đóng vai trò độn, dính, rã hoặc bôi trơn?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:12
- Finished: 2026-03-29T18:53:13
- Elapsed seconds: 0.8243
- Retrieval seconds: 0.1736
- Generation seconds: 0.0983
- Estimated prompt tokens: 270
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o nhi\u1ec1u kh\u1ea3 n\u0103ng \u0111\u00f3ng vai tr\u00f2 \u0111\u1ed9n, d\u00ednh, r\u00e3 ho\u1eb7c b\u00f4i tr\u01a1n?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào nhiều khả năng đóng vai trò độn, dính, rã hoặc bôi trơn cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 28. Những tá dược nào liên quan đến bao phim, tạo màu hoặc bảo quản?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:12
- Finished: 2026-03-29T18:53:13
- Elapsed seconds: 0.9407
- Retrieval seconds: 0.137
- Generation seconds: 0.2041
- Estimated prompt tokens: 968
- Estimated answer tokens: 370

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o li\u00ean quan \u0111\u1ebfn bao phim, t\u1ea1o m\u00e0u ho\u1eb7c b\u1ea3o qu\u1ea3n?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào liên quan đến bao phim, tạo màu hoặc bảo quản cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 29. Những tá dược nào có thể ảnh hưởng đến độ ổn định hoặc khả năng sản xuất?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:13
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.954
- Retrieval seconds: 0.1454
- Generation seconds: 0.0239
- Estimated prompt tokens: 970
- Estimated answer tokens: 372

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 \u1ea3nh h\u01b0\u1edfng \u0111\u1ebfn \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh ho\u1eb7c kh\u1ea3 n\u0103ng s\u1ea3n xu\u1ea5t?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể ảnh hưởng đến độ ổn định hoặc khả năng sản xuất cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 30. Những tá dược nào có thể ảnh hưởng đến độ tan, độ nhớt hoặc đặc tính giải phóng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:13
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.9987
- Retrieval seconds: 0.1569
- Generation seconds: 0.0551
- Estimated prompt tokens: 272
- Estimated answer tokens: 525

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 \u1ea3nh h\u01b0\u1edfng \u0111\u1ebfn \u0111\u1ed9 tan, \u0111\u1ed9 nh\u1edbt ho\u1eb7c \u0111\u1eb7c t\u00ednh gi\u1ea3i ph\u00f3ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể ảnh hưởng đến độ tan, độ nhớt hoặc đặc tính giải phóng cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 31. Tóm tắt thành phần tá dược và vai trò công nghệ có khả năng của chúng trong công thức.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:13
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.8949
- Retrieval seconds: 0.1182
- Generation seconds: 0.0466
- Estimated prompt tokens: 273
- Estimated answer tokens: 526

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n t\u00e1 d\u01b0\u1ee3c v\u00e0 vai tr\u00f2 c\u00f4ng ngh\u1ec7 c\u00f3 kh\u1ea3 n\u0103ng c\u1ee7a ch\u00fang trong c\u00f4ng th\u1ee9c." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần tá dược và vai trò công nghệ có khả năng của chúng trong công thức. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 32. Có cảnh báo nào liên quan đến tá dược không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:13
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.6602
- Retrieval seconds: 0.0936
- Generation seconds: 0.0177
- Estimated prompt tokens: 714
- Estimated answer tokens: 676

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến tá dược không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 33. Có chống chỉ định hoặc thận trọng nào liên quan đến tá dược không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.6311
- Retrieval seconds: 0.1121
- Generation seconds: 0.0253
- Estimated prompt tokens: 970
- Estimated answer tokens: 331

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh ho\u1eb7c th\u1eadn tr\u1ecdng n\u00e0o li\u00ean quan \u0111\u1ebfn t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có chống chỉ định hoặc thận trọng nào liên quan đến tá dược không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5973
  **** Tiêu chí tổng hợp:
  1,76 (khoảng tin cậy 95%:
  Ugobi Tiêm dưới da (Chỉ định:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3940
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 65 | mục=indication | điểm=6.9830
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  mg mỗi tuần một lần.
  4.1 Chỉ định điều trị
- Ozempic | interview_form | trang 64 | mục=indication | điểm=6.9421
  0,5 mg mỗi lần tiêm.
  XII.Tài liệu tham khảo
  Hiệu quả hoặc tác dụng
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=6.9167
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 17 | mục=indication | điểm=6.8495
  580 bệnh nhân, nhẹ:
  trường trung học cơ sở
  261 bệnh nhân, trung bình).

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 65
- Ozempic / interview_form / trang 64
- Ozempic / smpc_label / trang 1
- Ozempic / smpc_label / trang 17
```

## 34. Những tá dược nào có thể gây quá mẫn hoặc không dung nạp?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:14
- Elapsed seconds: 0.6456
- Retrieval seconds: 0.1503
- Generation seconds: 0.0795
- Estimated prompt tokens: 266
- Estimated answer tokens: 519

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 g\u00e2y qu\u00e1 m\u1eabn ho\u1eb7c kh\u00f4ng dung n\u1ea1p?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể gây quá mẫn hoặc không dung nạp cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 35. Có cảnh báo nào về chất bảo quản, chất màu, tá dược bao phim hoặc tá dược chứa cồn không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.6128
- Retrieval seconds: 0.0947
- Generation seconds: 0.0346
- Estimated prompt tokens: 725
- Estimated answer tokens: 690

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 ch\u1ea5t b\u1ea3o qu\u1ea3n, ch\u1ea5t m\u00e0u, t\u00e1 d\u01b0\u1ee3c bao phim ho\u1eb7c t\u00e1 d\u01b0\u1ee3c ch\u1ee9a c\u1ed3n kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về chất bảo quản, chất màu, tá dược bao phim hoặc tá dược chứa cồn không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7816
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7692
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5964
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 36. Có cảnh báo nào về đường, polyol hoặc hàm lượng natri trong công thức không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.6165
- Retrieval seconds: 0.0932
- Generation seconds: 0.0196
- Estimated prompt tokens: 722
- Estimated answer tokens: 684

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 \u0111\u01b0\u1eddng, polyol ho\u1eb7c h\u00e0m l\u01b0\u1ee3ng natri trong c\u00f4ng th\u1ee9c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về đường, polyol hoặc hàm lượng natri trong công thức không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 37. Sản phẩm có chứa tá dược cần thận trọng ở bệnh nhân nhạy cảm không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.5846
- Retrieval seconds: 0.0915
- Generation seconds: 0.016
- Estimated prompt tokens: 720
- Estimated answer tokens: 682

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "S\u1ea3n ph\u1ea9m c\u00f3 ch\u1ee9a t\u00e1 d\u01b0\u1ee3c c\u1ea7n th\u1eadn tr\u1ecdng \u1edf b\u1ec7nh nh\u00e2n nh\u1ea1y c\u1ea3m kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Sản phẩm có chứa tá dược cần thận trọng ở bệnh nhân nhạy cảm không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 38. Có cảnh báo liên quan đến công thức cho bệnh nhi không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:14
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.5604
- Retrieval seconds: 0.1138
- Generation seconds: 0.0951
- Estimated prompt tokens: 717
- Estimated answer tokens: 679

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho b\u1ec7nh nhi kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo liên quan đến công thức cho bệnh nhi không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 39. Có cảnh báo liên quan đến công thức cho người cao tuổi không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.5641
- Retrieval seconds: 0.0845
- Generation seconds: 0.0472
- Estimated prompt tokens: 718
- Estimated answer tokens: 681

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho ng\u01b0\u1eddi cao tu\u1ed5i kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo liên quan đến công thức cho người cao tuổi không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 40. Có cảnh báo nào về mang thai hoặc cho con bú liên quan đến công thức hay tá dược không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:15
- Elapsed seconds: 0.6514
- Retrieval seconds: 0.1474
- Generation seconds: 0.0523
- Estimated prompt tokens: 626
- Estimated answer tokens: 640

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 mang thai ho\u1eb7c cho con b\u00fa li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c hay t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về mang thai hoặc cho con bú liên quan đến công thức hay tá dược không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=7.7382
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.
  Người nộp đơn đã trả lời như sau.
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 68 | mục=pregnancy | điểm=6.9967
  tiếp xúc với con người).
  (phơi nhiễm ≥3X ở người).
  từ ngày mang thai thứ 16 đến ngày thứ 140.
- Ozempic | interview_form | trang 69 | mục=pregnancy | điểm=6.9092
  Không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ.
  Vì không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ nên không nên sử dụng semaglutide trong thời gian cho con bú.
  Tờ hướng dẫn sử dụng của Úc
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]

Nguồn:
- Ozempic / smpc_label / trang 29
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 68
- Ozempic / interview_form / trang 69
- Ozempic / safety_notice / trang 1
```

## 41. Có lo ngại an toàn nào liên quan đến bệnh tuyến giáp, suy thận hoặc hấp thu toàn thân không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.724
- Retrieval seconds: 0.1608
- Generation seconds: 0.0213
- Estimated prompt tokens: 275
- Estimated answer tokens: 528

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 lo ng\u1ea1i an to\u00e0n n\u00e0o li\u00ean quan \u0111\u1ebfn b\u1ec7nh tuy\u1ebfn gi\u00e1p, suy th\u1eadn ho\u1eb7c h\u1ea5p thu to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có lo ngại an toàn nào liên quan đến bệnh tuyến giáp, suy thận hoặc hấp thu toàn thân không cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 42. Việc dùng kéo dài, bôi trên diện rộng hoặc dùng trên niêm mạc có làm tăng nguy cơ an toàn liên quan đến công thức không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.7957
- Retrieval seconds: 0.1862
- Generation seconds: 0.0898
- Estimated prompt tokens: 282
- Estimated answer tokens: 535

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Vi\u1ec7c d\u00f9ng k\u00e9o d\u00e0i, b\u00f4i tr\u00ean di\u1ec7n r\u1ed9ng ho\u1eb7c d\u00f9ng tr\u00ean ni\u00eam m\u1ea1c c\u00f3 l\u00e0m t\u0103ng nguy c\u01a1 an to\u00e0n li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Việc dùng kéo dài, bôi trên diện rộng hoặc dùng trên niêm mạc có làm tăng nguy cơ an toàn liên quan đến công thức không cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 43. Tóm tắt các thận trọng ở quần thể đặc biệt liên quan đến công thức và tá dược.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn công thức liên quan đến quần thể đặc biệt và cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.8064
- Retrieval seconds: 0.1025
- Generation seconds: 0.0417
- Estimated prompt tokens: 722
- Estimated answer tokens: 685

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft c\u00e1c th\u1eadn tr\u1ecdng \u1edf qu\u1ea7n th\u1ec3 \u0111\u1eb7c bi\u1ec7t li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c v\u00e0 t\u00e1 d\u01b0\u1ee3c." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt các thận trọng ở quần thể đặc biệt liên quan đến công thức và tá dược. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 44. Các điều kiện bảo quản và thận trọng về độ ổn định được mô tả là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:15
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.7212
- Retrieval seconds: 0.0911
- Generation seconds: 0.0231
- Estimated prompt tokens: 720
- Estimated answer tokens: 685

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c \u0111i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n v\u00e0 th\u1eadn tr\u1ecdng v\u1ec1 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3 l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các điều kiện bảo quản và thận trọng về độ ổn định được mô tả là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7816
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7692
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5964
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 45. Những thành phần công thức nào có thể nhạy cảm với ánh sáng, nhiệt, ẩm hoặc oxy hóa?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.6547
- Retrieval seconds: 0.0884
- Generation seconds: 0.0258
- Estimated prompt tokens: 273
- Estimated answer tokens: 526

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c n\u00e0o c\u00f3 th\u1ec3 nh\u1ea1y c\u1ea3m v\u1edbi \u00e1nh s\u00e1ng, nhi\u1ec7t, \u1ea9m ho\u1eb7c oxy h\u00f3a?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thành phần công thức nào có thể nhạy cảm với ánh sáng, nhiệt, ẩm hoặc oxy hóa cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 46. Có lưu ý nào về bao bì hoặc dụng cụ chứa liên quan đến độ ổn định không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:16
- Elapsed seconds: 0.6622
- Retrieval seconds: 0.1754
- Generation seconds: 0.1102
- Estimated prompt tokens: 970
- Estimated answer tokens: 372

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 l\u01b0u \u00fd n\u00e0o v\u1ec1 bao b\u00ec ho\u1eb7c d\u1ee5ng c\u1ee5 ch\u1ee9a li\u00ean quan \u0111\u1ebfn \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có lưu ý nào về bao bì hoặc dụng cụ chứa liên quan đến độ ổn định không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 47. Tóm tắt dữ liệu độ ổn định liên quan đến công thức và hướng dẫn bảo quản.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.6435
- Retrieval seconds: 0.0879
- Generation seconds: 0.0394
- Estimated prompt tokens: 970
- Estimated answer tokens: 372

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c v\u00e0 h\u01b0\u1edbng d\u1eabn b\u1ea3o qu\u1ea3n." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định liên quan đến công thức và hướng dẫn bảo quản. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 48. Những chi tiết công thức nào quan trọng nhất cho phát triển thuốc generic?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.6711
- Retrieval seconds: 0.102
- Generation seconds: 0.0387
- Estimated prompt tokens: 270
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng chi ti\u1ebft c\u00f4ng th\u1ee9c n\u00e0o quan tr\u1ecdng nh\u1ea5t cho ph\u00e1t tri\u1ec3n thu\u1ed1c generic?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những chi tiết công thức nào quan trọng nhất cho phát triển thuốc generic cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 49. Những tá dược hoặc đặc tính công thức nào có thể là thuộc tính chất lượng trọng yếu (CQA)?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.6602
- Retrieval seconds: 0.0873
- Generation seconds: 0.0132
- Estimated prompt tokens: 274
- Estimated answer tokens: 527

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c ho\u1eb7c \u0111\u1eb7c t\u00ednh c\u00f4ng th\u1ee9c n\u00e0o c\u00f3 th\u1ec3 l\u00e0 thu\u1ed9c t\u00ednh ch\u1ea5t l\u01b0\u1ee3ng tr\u1ecdng y\u1ebfu (CQA)?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tá dược hoặc đặc tính công thức nào có thể là thuộc tính chất lượng trọng yếu (CQA) cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 50. Những cảnh báo nào liên quan đến công thức cần được xem xét trước khi cải tiến / reformulation?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:16
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.5714
- Retrieval seconds: 0.1199
- Generation seconds: 0.0651
- Estimated prompt tokens: 727
- Estimated answer tokens: 680

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c c\u1ea7n \u0111\u01b0\u1ee3c xem x\u00e9t tr\u01b0\u1edbc khi c\u1ea3i ti\u1ebfn / reformulation?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Thành phần hoạt chất, tá dược và đặc điểm công thức của ozempic là gì?
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 51. Những tài liệu mẫu nào có chứa thông tin về tá dược?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.5749
- Retrieval seconds: 0.0872
- Generation seconds: 0.0431
- Estimated prompt tokens: 265
- Estimated answer tokens: 518

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e0i li\u1ec7u m\u1eabu n\u00e0o c\u00f3 ch\u1ee9a th\u00f4ng tin v\u1ec1 t\u00e1 d\u01b0\u1ee3c?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tài liệu mẫu nào có chứa thông tin về tá dược cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 52. Tài liệu nào phù hợp hơn để lấy chi tiết tá dược: nhãn thuốc hay hướng dẫn bệnh nhân?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.5963
- Retrieval seconds: 0.1075
- Generation seconds: 0.0516
- Estimated prompt tokens: 273
- Estimated answer tokens: 526

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e0i li\u1ec7u n\u00e0o ph\u00f9 h\u1ee3p h\u01a1n \u0111\u1ec3 l\u1ea5y chi ti\u1ebft t\u00e1 d\u01b0\u1ee3c: nh\u00e3n thu\u1ed1c hay h\u01b0\u1edbng d\u1eabn b\u1ec7nh nh\u00e2n?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tài liệu nào phù hợp hơn để lấy chi tiết tá dược: nhãn thuốc hay hướng dẫn bệnh nhân cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 53. Tóm tắt thành phần, tá dược, độ ổn định và các nguy cơ an toàn liên quan đến công thức.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:17
- Elapsed seconds: 0.6201
- Retrieval seconds: 0.1061
- Generation seconds: 0.0188
- Estimated prompt tokens: 974
- Estimated answer tokens: 376

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n, t\u00e1 d\u01b0\u1ee3c, \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh v\u00e0 c\u00e1c nguy c\u01a1 an to\u00e0n li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần, tá dược, độ ổn định và các nguy cơ an toàn liên quan đến công thức. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 54. Tóm tắt dược động học của thuốc này.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:18
- Elapsed seconds: 0.7282
- Retrieval seconds: 0.1342
- Generation seconds: 0.1773
- Estimated prompt tokens: 962
- Estimated answer tokens: 432

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc c\u1ee7a thu\u1ed1c n\u00e0y." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt dược động học của thuốc này. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 55. Các thông số dược động học chính như Cmax, Tmax, AUC và thời gian bán thải là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:18
- Elapsed seconds: 0.8171
- Retrieval seconds: 0.0885
- Generation seconds: 0.1285
- Estimated prompt tokens: 974
- Estimated answer tokens: 411

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c th\u00f4ng s\u1ed1 d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc ch\u00ednh nh\u01b0 Cmax, Tmax, AUC v\u00e0 th\u1eddi gian b\u00e1n th\u1ea3i l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của ozempic là gì?
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.8408
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.7684
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 31 | mục=pk | điểm=6.6724
  An toàn (phòng ngừa, v.v.) 7.
  Không có phát hiện nào nêu lên vấn đề an toàn trong nghiên cứu này và nó được dung nạp tốt.
  (1) Phương pháp phân tích
- Ozempic | smpc_label | trang 3 | mục=pk | điểm=6.6152
  Ccr > 30~50mL/phút)
  Dựa trên phân tích.
  và 1,04[1,00;1,09].

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 30
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 31
- Ozempic / smpc_label / trang 3
```

## 56. Mô tả diễn biến nồng độ thuốc trong huyết tương theo thời gian.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 1.2966
- Retrieval seconds: 0.0839
- Generation seconds: 0.037
- Estimated prompt tokens: 268
- Estimated answer tokens: 521

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "M\u00f4 t\u1ea3 di\u1ec5n bi\u1ebfn n\u1ed3ng \u0111\u1ed9 thu\u1ed1c trong huy\u1ebft t\u01b0\u01a1ng theo th\u1eddi gian." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Mô tả diễn biến nồng độ thuốc trong huyết tương theo thời gian. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 57. Có những phân tích dược động học quần thể nào được báo cáo?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:17
- Finished: 2026-03-29T18:53:18
- Elapsed seconds: 0.9378
- Retrieval seconds: 0.1617
- Generation seconds: 0.1209
- Estimated prompt tokens: 968
- Estimated answer tokens: 437

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng ph\u00e2n t\u00edch d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc qu\u1ea7n th\u1ec3 n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có những phân tích dược động học quần thể nào được báo cáo cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 58. Tóm tắt hấp thu, phân bố, chuyển hóa và thải trừ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:18
- Finished: 2026-03-29T18:53:18
- Elapsed seconds: 0.7375
- Retrieval seconds: 0.0777
- Generation seconds: 0.0315
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft h\u1ea5p thu, ph\u00e2n b\u1ed1, chuy\u1ec3n h\u00f3a v\u00e0 th\u1ea3i tr\u1eeb." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt hấp thu, phân bố, chuyển hóa và thải trừ. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 59. Đã biết gì về hấp thu đường uống và sinh khả dụng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:18
- Finished: 2026-03-29T18:53:18
- Elapsed seconds: 0.1218
- Retrieval seconds: 0.0938
- Generation seconds: 0.0264
- Estimated prompt tokens: 264
- Estimated answer tokens: 517

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "\u0110\u00e3 bi\u1ebft g\u00ec v\u1ec1 h\u1ea5p thu \u0111\u01b0\u1eddng u\u1ed1ng v\u00e0 sinh kh\u1ea3 d\u1ee5ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Đã biết gì về hấp thu đường uống và sinh khả dụng cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 60. Các con đường chuyển hóa và enzyme chính liên quan là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:18
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 0.6117
- Retrieval seconds: 0.082
- Generation seconds: 0.0118
- Estimated prompt tokens: 266
- Estimated answer tokens: 519

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c con \u0111\u01b0\u1eddng chuy\u1ec3n h\u00f3a v\u00e0 enzyme ch\u00ednh li\u00ean quan l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các con đường chuyển hóa và enzyme chính liên quan là gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 61. Những chất vận chuyển nào được nhắc đến trong phần dược động học?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:18
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 0.574
- Retrieval seconds: 0.114
- Generation seconds: 0.1353
- Estimated prompt tokens: 970
- Estimated answer tokens: 438

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ch\u1ea5t v\u1eadn chuy\u1ec3n n\u00e0o \u0111\u01b0\u1ee3c nh\u1eafc \u0111\u1ebfn trong ph\u1ea7n d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những chất vận chuyển nào được nhắc đến trong phần dược động học cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 62. Có dữ liệu dược động học ở bệnh nhân suy thận hoặc suy gan không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:18
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 0.5761
- Retrieval seconds: 0.09
- Generation seconds: 0.0199
- Estimated prompt tokens: 970
- Estimated answer tokens: 438

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 d\u1eef li\u1ec7u d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc \u1edf b\u1ec7nh nh\u00e2n suy th\u1eadn ho\u1eb7c suy gan kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có dữ liệu dược động học ở bệnh nhân suy thận hoặc suy gan không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 63. Tóm tắt dược động học ở các quần thể đặc biệt.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 0.5861
- Retrieval seconds: 0.0801
- Generation seconds: 0.0504
- Estimated prompt tokens: 965
- Estimated answer tokens: 434

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc \u1edf c\u00e1c qu\u1ea7n th\u1ec3 \u0111\u1eb7c bi\u1ec7t." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt dược động học ở các quần thể đặc biệt. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 64. Các phát hiện PK chính là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:19
- Elapsed seconds: 0.6268
- Retrieval seconds: 0.0942
- Generation seconds: 0.0401
- Estimated prompt tokens: 1250
- Estimated answer tokens: 385

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ph\u00e1t hi\u1ec7n PK ch\u00ednh l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của ozempic là gì?
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=7.1631
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | interview_form | trang 4 | mục=pk | điểm=7.0521
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=7.0287
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.
- Ozempic | interview_form | trang 31 | mục=pk | điểm=7.0017
  An toàn (phòng ngừa, v.v.) 7.
  Không có phát hiện nào nêu lên vấn đề an toàn trong nghiên cứu này và nó được dung nạp tốt.
  (1) Phương pháp phân tích
- Ozempic | interview_form | trang 33 | mục=pk | điểm=6.9317
  (2) Tốc độ bài tiết
  Thành phần chính là semaglutide không thay đổi.
  (1) Vị trí trao đổi chất và con đường trao đổi chất

Nguồn:
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
- Ozempic / interview_form / trang 31
- Ozempic / interview_form / trang 33
```

## 65. Interview form nói gì về bảo quản và độ ổn định?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.6779
- Retrieval seconds: 0.0865
- Generation seconds: 0.2147
- Estimated prompt tokens: 1191
- Estimated answer tokens: 447

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Interview form n\u00f3i g\u00ec v\u1ec1 b\u1ea3o qu\u1ea3n v\u00e0 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Interview form nói gì về bảo quản và độ ổn định cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=7.1787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=7.1447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=7.0629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=7.0090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.
- Ozempic | interview_form | trang 27 | mục=stability | điểm=6.9940
  Magglutide dựa trên công nghệ acyl hóa, tương tự như liraglutide (được bán ở Nhật Bản dưới dạng thuốc tiêm dưới da Victoza® 18 mg), nhưng cũng bao gồm những sửa đổi đáng kể về cấu trúc hóa học giúp kéo dài thời gian bán hủy và làm cho nó phù hợp với liều dùng một lần mỗi tuần.
  Semaglutide (tên sản phẩm:
  adenosine monophosphate tuần hoàn

Nguồn:
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
- Ozempic / interview_form / trang 27
```

## 66. Phần nào của interview form mô tả thành phần và công thức?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.7131
- Retrieval seconds: 0.0981
- Generation seconds: 0.0458
- Estimated prompt tokens: 909
- Estimated answer tokens: 504

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ph\u1ea7n n\u00e0o c\u1ee7a interview form m\u00f4 t\u1ea3 th\u00e0nh ph\u1ea7n v\u00e0 c\u00f4ng th\u1ee9c?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Phần nào của interview form mô tả thành phần và công thức cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.4202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.9042
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3724
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 66 | mục=dosage | điểm=6.3522
  Tính an toàn và hiệu quả của semaglutide ở trẻ em và thanh thiếu niên dưới 18 tuổi vẫn chưa được thiết lập.
  Không có dữ liệu có sẵn.
  Semaglutide 0,25 mg không phải là liều duy trì.
- Ozempic | interview_form | trang 65 | mục=indication | điểm=6.3063
  4.1 Chỉ định điều trị
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  Ozempic được chỉ định để điều trị cho người lớn mắc bệnh đái tháo đường týp 2 không được kiểm soát đầy đủ dưới dạng thuốc hỗ trợ cho chế độ ăn kiêng và tập thể dục.
- Ozempic | interview_form | trang 70 | mục=dosage | điểm=6.2758
  Tính an toàn và hiệu quả của OZEMPIC® chưa được thiết lập ở bệnh nhi.
  Nhóm đối tượng đặc biệt Đối tượng nhi khoa Tính an toàn và hiệu quả của semaglutide ở trẻ em và thanh thiếu niên dưới 18 tuổi vẫn chưa được thiết lập.
  9.5 Phụ nữ mang thai

Nguồn:
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 66
- Ozempic / interview_form / trang 65
- Ozempic / interview_form / trang 70
```

## 67. Hiển thị bằng chứng từ phần dược động học.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.7354
- Retrieval seconds: 0.0905
- Generation seconds: 0.0615
- Estimated prompt tokens: 964
- Estimated answer tokens: 433

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Hiển thị bằng chứng từ phần dược động học. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 68. Tóm tắt dữ liệu độ ổn định của hoạt chất.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:19
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.7146
- Retrieval seconds: 0.1008
- Generation seconds: 0.0174
- Estimated prompt tokens: 962
- Estimated answer tokens: 364

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh c\u1ee7a ho\u1ea1t ch\u1ea5t." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định của hoạt chất. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 69. Tóm tắt dữ liệu độ ổn định của thành phẩm.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.7051
- Retrieval seconds: 0.1274
- Generation seconds: 0.1603
- Estimated prompt tokens: 963
- Estimated answer tokens: 365

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh c\u1ee7a th\u00e0nh ph\u1ea9m." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định của thành phẩm. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 70. Có những kết quả độ ổn định nào được báo cáo trong điều kiện bảo quản dài hạn?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:20
- Elapsed seconds: 0.6718
- Retrieval seconds: 0.0917
- Generation seconds: 0.0178
- Estimated prompt tokens: 972
- Estimated answer tokens: 374

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng k\u1ebft qu\u1ea3 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o trong \u0111i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n d\u00e0i h\u1ea1n?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có những kết quả độ ổn định nào được báo cáo trong điều kiện bảo quản dài hạn cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 71. Có những nghiên cứu độ ổn định tăng tốc nào được báo cáo?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6581
- Retrieval seconds: 0.0923
- Generation seconds: 0.0463
- Estimated prompt tokens: 966
- Estimated answer tokens: 368

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng nghi\u00ean c\u1ee9u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh t\u0103ng t\u1ed1c n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có những nghiên cứu độ ổn định tăng tốc nào được báo cáo cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 72. Những điều kiện stress nào đã được thử nghiệm, như nhiệt, độ ẩm và ánh sáng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6425
- Retrieval seconds: 0.0868
- Generation seconds: 0.0137
- Estimated prompt tokens: 271
- Estimated answer tokens: 524

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng \u0111i\u1ec1u ki\u1ec7n stress n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c th\u1eed nghi\u1ec7m, nh\u01b0 nhi\u1ec7t, \u0111\u1ed9 \u1ea9m v\u00e0 \u00e1nh s\u00e1ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những điều kiện stress nào đã được thử nghiệm, như nhiệt, độ ẩm và ánh sáng cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 73. Có những thay đổi nào xảy ra khi phơi sáng hoặc trong thử nghiệm độ bền ánh sáng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6765
- Retrieval seconds: 0.0992
- Generation seconds: 0.2229
- Estimated prompt tokens: 272
- Estimated answer tokens: 525

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng thay \u0111\u1ed5i n\u00e0o x\u1ea3y ra khi ph\u01a1i s\u00e1ng ho\u1eb7c trong th\u1eed nghi\u1ec7m \u0111\u1ed9 b\u1ec1n \u00e1nh s\u00e1ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có những thay đổi nào xảy ra khi phơi sáng hoặc trong thử nghiệm độ bền ánh sáng cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 74. Có nguy cơ phân hủy đáng chú ý hoặc thay đổi cảm quan nào không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:20
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6769
- Retrieval seconds: 0.0929
- Generation seconds: 0.0176
- Estimated prompt tokens: 268
- Estimated answer tokens: 521

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nguy c\u01a1 ph\u00e2n h\u1ee7y \u0111\u00e1ng ch\u00fa \u00fd ho\u1eb7c thay \u0111\u1ed5i c\u1ea3m quan n\u00e0o kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có nguy cơ phân hủy đáng chú ý hoặc thay đổi cảm quan nào không cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 75. Điều kiện bảo quản và hạn dùng được khuyến cáo là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6677
- Retrieval seconds: 0.0907
- Generation seconds: 0.0387
- Estimated prompt tokens: 966
- Estimated answer tokens: 367

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "\u0110i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n v\u00e0 h\u1ea1n d\u00f9ng \u0111\u01b0\u1ee3c khuy\u1ebfn c\u00e1o l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Điều kiện bảo quản và hạn dùng được khuyến cáo là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 76. Có dữ liệu về độ ổn định sau hoàn nguyên hoặc sau pha chế không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.6651
- Retrieval seconds: 0.0817
- Generation seconds: 0.0184
- Estimated prompt tokens: 968
- Estimated answer tokens: 370

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 d\u1eef li\u1ec7u v\u1ec1 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh sau ho\u00e0n nguy\u00ean ho\u1eb7c sau pha ch\u1ebf kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có dữ liệu về độ ổn định sau hoàn nguyên hoặc sau pha chế không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=6.5787
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=6.5447
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=6.4629
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=6.4090
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
```

## 77. Tóm tắt độ ổn định, bảo quản và các thận trọng liên quan đến bao bì.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:21
- Elapsed seconds: 0.4413
- Retrieval seconds: 0.0792
- Generation seconds: 0.0152
- Estimated prompt tokens: 720
- Estimated answer tokens: 686

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh, b\u1ea3o qu\u1ea3n v\u00e0 c\u00e1c th\u1eadn tr\u1ecdng li\u00ean quan \u0111\u1ebfn bao b\u00ec." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt độ ổn định, bảo quản và các thận trọng liên quan đến bao bì. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7816
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7692
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5964
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 78. Tóm tắt Kế hoạch Quản lý Nguy cơ (RMP) của thuốc này.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:22
- Elapsed seconds: 0.6293
- Retrieval seconds: 0.1447
- Generation seconds: 0.1593
- Estimated prompt tokens: 566
- Estimated answer tokens: 708

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft K\u1ebf ho\u1ea1ch Qu\u1ea3n l\u00fd Nguy c\u01a1 (RMP) c\u1ee7a thu\u1ed1c n\u00e0y." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt Kế hoạch Quản lý Nguy cơ (RMP) của thuốc này. cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 79. Những nguy cơ quan trọng đã được xác định trong RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:22
- Elapsed seconds: 0.6062
- Retrieval seconds: 0.0862
- Generation seconds: 0.0192
- Estimated prompt tokens: 567
- Estimated answer tokens: 709

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 quan tr\u1ecdng \u0111\u00e3 \u0111\u01b0\u1ee3c x\u00e1c \u0111\u1ecbnh trong RMP l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những nguy cơ quan trọng đã được xác định trong RMP là gì cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 80. Những nguy cơ tiềm ẩn quan trọng trong RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:22
- Elapsed seconds: 0.6362
- Retrieval seconds: 0.0815
- Generation seconds: 0.0462
- Estimated prompt tokens: 564
- Estimated answer tokens: 707

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 ti\u1ec1m \u1ea9n quan tr\u1ecdng trong RMP l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những nguy cơ tiềm ẩn quan trọng trong RMP là gì cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 81. Những thông tin còn thiếu quan trọng nào được liệt kê trong RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:21
- Finished: 2026-03-29T18:53:22
- Elapsed seconds: 0.6434
- Retrieval seconds: 0.0827
- Generation seconds: 0.0193
- Estimated prompt tokens: 568
- Estimated answer tokens: 711

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00f4ng tin c\u00f2n thi\u1ebfu quan tr\u1ecdng n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea trong RMP?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thông tin còn thiếu quan trọng nào được liệt kê trong RMP cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 82. Những hoạt động cảnh giác dược thường quy nào được mô tả trong RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:22
- Finished: 2026-03-29T18:53:22
- Elapsed seconds: 0.4657
- Retrieval seconds: 0.1055
- Generation seconds: 0.0194
- Estimated prompt tokens: 569
- Estimated answer tokens: 712

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng c\u1ea3nh gi\u00e1c d\u01b0\u1ee3c th\u01b0\u1eddng quy n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3 trong RMP?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những hoạt động cảnh giác dược thường quy nào được mô tả trong RMP cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 83. Những hoạt động cảnh giác dược bổ sung nào được mô tả?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:22
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.6208
- Retrieval seconds: 0.1486
- Generation seconds: 0.113
- Estimated prompt tokens: 265
- Estimated answer tokens: 518

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng c\u1ea3nh gi\u00e1c d\u01b0\u1ee3c b\u1ed5 sung n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những hoạt động cảnh giác dược bổ sung nào được mô tả cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 84. Những hoạt động giảm thiểu nguy cơ thường quy nào được mô tả?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:22
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.5984
- Retrieval seconds: 0.089
- Generation seconds: 0.0167
- Estimated prompt tokens: 267
- Estimated answer tokens: 520

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng gi\u1ea3m thi\u1ec3u nguy c\u01a1 th\u01b0\u1eddng quy n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những hoạt động giảm thiểu nguy cơ thường quy nào được mô tả cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 85. Những tài liệu giảm thiểu nguy cơ bổ sung nào được lên kế hoạch cho bệnh nhân hoặc nhân viên y tế?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:22
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.6076
- Retrieval seconds: 0.0788
- Generation seconds: 0.0317
- Estimated prompt tokens: 276
- Estimated answer tokens: 529

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e0i li\u1ec7u gi\u1ea3m thi\u1ec3u nguy c\u01a1 b\u1ed5 sung n\u00e0o \u0111\u01b0\u1ee3c l\u00ean k\u1ebf ho\u1ea1ch cho b\u1ec7nh nh\u00e2n ho\u1eb7c nh\u00e2n vi\u00ean y t\u1ebf?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những tài liệu giảm thiểu nguy cơ bổ sung nào được lên kế hoạch cho bệnh nhân hoặc nhân viên y tế cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 86. Những vấn đề liên quan đến hiệu quả điều trị nào được đưa vào RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:22
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.5979
- Retrieval seconds: 0.0819
- Generation seconds: 0.0324
- Estimated prompt tokens: 569
- Estimated answer tokens: 711

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng v\u1ea5n \u0111\u1ec1 li\u00ean quan \u0111\u1ebfn hi\u1ec7u qu\u1ea3 \u0111i\u1ec1u tr\u1ecb n\u00e0o \u0111\u01b0\u1ee3c \u0111\u01b0a v\u00e0o RMP?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những vấn đề liên quan đến hiệu quả điều trị nào được đưa vào RMP cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 87. Interview form hoặc RMP nói gì về các nguy cơ liên quan đến RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.4454
- Retrieval seconds: 0.0856
- Generation seconds: 0.0228
- Estimated prompt tokens: 707
- Estimated answer tokens: 542

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Interview form ho\u1eb7c RMP n\u00f3i g\u00ec v\u1ec1 c\u00e1c nguy c\u01a1 li\u00ean quan \u0111\u1ebfn RMP?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Interview form hoặc RMP nói gì về các nguy cơ liên quan đến RMP cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.7630
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.6062
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 66 | mục=dosage | điểm=6.2707
  Tính an toàn và hiệu quả của semaglutide ở trẻ em và thanh thiếu niên dưới 18 tuổi vẫn chưa được thiết lập.
  Không có dữ liệu có sẵn.
  Semaglutide 0,25 mg không phải là liều duy trì.

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 66
```

## 88. Những nguy cơ quan trọng đã xác định và nguy cơ tiềm ẩn trong các tài liệu RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.6088
- Retrieval seconds: 0.1495
- Generation seconds: 0.123
- Estimated prompt tokens: 574
- Estimated answer tokens: 716

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 quan tr\u1ecdng \u0111\u00e3 x\u00e1c \u0111\u1ecbnh v\u00e0 nguy c\u01a1 ti\u1ec1m \u1ea9n trong c\u00e1c t\u00e0i li\u1ec7u RMP l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những nguy cơ quan trọng đã xác định và nguy cơ tiềm ẩn trong các tài liệu RMP là gì cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 89. Tóm tắt toàn bộ RMP bao gồm nguy cơ, theo dõi và các biện pháp giảm thiểu nguy cơ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.6162
- Retrieval seconds: 0.0963
- Generation seconds: 0.0191
- Estimated prompt tokens: 573
- Estimated answer tokens: 716

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft to\u00e0n b\u1ed9 RMP bao g\u1ed3m nguy c\u01a1, theo d\u00f5i v\u00e0 c\u00e1c bi\u1ec7n ph\u00e1p gi\u1ea3m thi\u1ec3u nguy c\u01a1." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt toàn bộ RMP bao gồm nguy cơ, theo dõi và các biện pháp giảm thiểu nguy cơ. cho ozempic.
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 6 | mục=rmp | điểm=7.6714
  An toàn (Thận trọng, v.v.) 8.
  (3) Trong các thử nghiệm lâm sàng giai đoạn III (dữ liệu gộp)3,4,5,6,7 có sự tham gia của những người Nhật Bản, 859 (42,4%) trong số 2024 trường hợp đã được đánh giá về độ an toàn.
  Dược tính của sản phẩm
- Ozempic | interview_form | trang 7 | mục=rmp | điểm=7.4830
  Tổng quan về Kế hoạch quản lý rủi ro dược phẩm (RMP) Lưu ý) Các cân nhắc về an toàn
  Không có cân nhắc nào về tính hiệu quả ↓ Hoạt động giám sát an toàn dựa trên những điều trên
  Ung thư tuyến giáp thể tủy hạ đường huyết (khối u tế bào C tuyến giáp) Tác động đến nguy cơ tim mạch ở bệnh nhân Nhật Bản Rối loạn tiêu hóa Viêm tụy cấp An toàn khi dùng cho bệnh nhân rối loạn chức năng thận Tắc ruột (bao gồm cả tắc ruột) Ung thư tuyến tụy
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.8479
  Không có tài liệu áp dụng
- Ozempic | interview_form | trang 37 | mục=adverse_event | điểm=6.3016
  - Cung cấp hướng dẫn kỹ lưỡng về cách tiêu hủy tất cả các thiết bị một cách an toàn.
  Như một biện pháp phòng ngừa chung đối với chất chủ vận thụ thể GLP-1, vào ngày 14 tháng 2 năm 2020, Cục Y tế Môi trường và Dược phẩm của Bộ Y tế, Lao động và Phúc lợi, Thông báo Trưởng Phòng An toàn Dược phẩm (Dược phẩm)
  Hãy trả lời cẩn thận.
- Ozempic | interview_form | trang 5 | mục=general | điểm=6.1900
  Bảng viết tắt Nội dung viết tắt ATP Adenosine triphosphate AUC Diện tích dưới đường cong nồng độ trong huyết tương theo thời gian BG Biguanides BHK Thận của chuột hamster con cAMP Cyclic adenosine monophosphate Ccr Độ thanh thải creatinine Cmax Nồng độ tối đa trong huyết tương CYP Cytochrome P450 DPP-4 Dipeptidyl peptidase-4 EFD Sự phát triển của phôi thai eGFR tốc độ lọc cầu thận ước tính FAS Dân số phân tích lớn nhất FDA FDA Hoa Kỳ Bác sĩ Thực phẩm Dược phẩm GLP-1 Glucagon-like peptide-1 HbA1c Hemoglobin A1c MedDRAICH Thuật ngữ y tế quốc tế PT Thuật ngữ cơ bản QTc QTS GLT Chất mang đồng vận chuyển natri-glucose được hiệu chỉnh bằng phương pháp điều chỉnh nhịp tim sử dụng dữ liệu của từng đối tượng SOC Phân loại dành riêng cho cơ quan SU Sulfonylureas TG Triglycerides T1/2 Thời gian bán hủy thải trừ TZD Thiazolidines Thuốc ức chế α-GI α-glucosidase

Nguồn:
- Ozempic / interview_form / trang 6
- Ozempic / interview_form / trang 7
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / interview_form / trang 37
- Ozempic / interview_form / trang 5
```

## 90. Những thay đổi nhãn an toàn gần đây nào có nhắc đến thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:23
- Elapsed seconds: 0.6283
- Retrieval seconds: 0.0809
- Generation seconds: 0.0446
- Estimated prompt tokens: 267
- Estimated answer tokens: 520

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng thay \u0111\u1ed5i nh\u00e3n an to\u00e0n g\u1ea7n \u0111\u00e2y n\u00e0o c\u00f3 nh\u1eafc \u0111\u1ebfn thu\u1ed1c n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thay đổi nhãn an toàn gần đây nào có nhắc đến thuốc này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 91. Những cập nhật an toàn mới nào đã được ban hành cho thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.6382
- Retrieval seconds: 0.0898
- Generation seconds: 0.0296
- Estimated prompt tokens: 267
- Estimated answer tokens: 520

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng c\u1eadp nh\u1eadt an to\u00e0n m\u1edbi n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c ban h\u00e0nh cho thu\u1ed1c n\u00e0y?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những cập nhật an toàn mới nào đã được ban hành cho thuốc này cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 92. Có cảnh báo an toàn nào về viêm gan tối cấp, phản ứng da nặng hoặc viêm phổi kẽ không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.4677
- Retrieval seconds: 0.0889
- Generation seconds: 0.0131
- Estimated prompt tokens: 724
- Estimated answer tokens: 687

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o an to\u00e0n n\u00e0o v\u1ec1 vi\u00eam gan t\u1ed1i c\u1ea5p, ph\u1ea3n \u1ee9ng da n\u1eb7ng ho\u1eb7c vi\u00eam ph\u1ed5i k\u1ebd kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo an toàn nào về viêm gan tối cấp, phản ứng da nặng hoặc viêm phổi kẽ không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 93. Có cảnh báo về phản ứng da nặng trong các thông báo an toàn gần đây không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.7482
- Retrieval seconds: 0.1731
- Generation seconds: 0.2275
- Estimated prompt tokens: 722
- Estimated answer tokens: 684

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o v\u1ec1 ph\u1ea3n \u1ee9ng da n\u1eb7ng trong c\u00e1c th\u00f4ng b\u00e1o an to\u00e0n g\u1ea7n \u0111\u00e2y kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo về phản ứng da nặng trong các thông báo an toàn gần đây không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 94. Những thông báo an toàn nào nhắc đến rối loạn chức năng gan hoặc viêm gan?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:23
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.7533
- Retrieval seconds: 0.1011
- Generation seconds: 0.0269
- Estimated prompt tokens: 270
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00f4ng b\u00e1o an to\u00e0n n\u00e0o nh\u1eafc \u0111\u1ebfn r\u1ed1i lo\u1ea1n ch\u1ee9c n\u0103ng gan ho\u1eb7c vi\u00eam gan?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Những thông báo an toàn nào nhắc đến rối loạn chức năng gan hoặc viêm gan cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 95. Có cảnh báo nào liên quan đến mang thai, nguy cơ với thai nhi hoặc thiểu ối không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.7802
- Retrieval seconds: 0.097
- Generation seconds: 0.0497
- Estimated prompt tokens: 625
- Estimated answer tokens: 639

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn mang thai, nguy c\u01a1 v\u1edbi thai nhi ho\u1eb7c thi\u1ec3u \u1ed1i kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến mang thai, nguy cơ với thai nhi hoặc thiểu ối không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=7.7382
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.
  Người nộp đơn đã trả lời như sau.
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 68 | mục=pregnancy | điểm=6.9967
  tiếp xúc với con người).
  (phơi nhiễm ≥3X ở người).
  từ ngày mang thai thứ 16 đến ngày thứ 140.
- Ozempic | interview_form | trang 69 | mục=pregnancy | điểm=6.9092
  Không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ.
  Vì không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ nên không nên sử dụng semaglutide trong thời gian cho con bú.
  Tờ hướng dẫn sử dụng của Úc
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]

Nguồn:
- Ozempic / smpc_label / trang 29
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 68
- Ozempic / interview_form / trang 69
- Ozempic / safety_notice / trang 1
```

## 96. Có cảnh báo nào về tái hoạt HBV hoặc nguy cơ miễn dịch không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:24
- Elapsed seconds: 0.8035
- Retrieval seconds: 0.0886
- Generation seconds: 0.0359
- Estimated prompt tokens: 718
- Estimated answer tokens: 681

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 t\u00e1i ho\u1ea1t HBV ho\u1eb7c nguy c\u01a1 mi\u1ec5n d\u1ecbch kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về tái hoạt HBV hoặc nguy cơ miễn dịch không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 97. Có cảnh báo nào liên quan đến chuyển hóa như nguy cơ ở người chuyển hóa cực nhanh CYP2D6 không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.4968
- Retrieval seconds: 0.0797
- Generation seconds: 0.0137
- Estimated prompt tokens: 727
- Estimated answer tokens: 689

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn chuy\u1ec3n h\u00f3a nh\u01b0 nguy c\u01a1 \u1edf ng\u01b0\u1eddi chuy\u1ec3n h\u00f3a c\u1ef1c nhanh CYP2D6 kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến chuyển hóa như nguy cơ ở người chuyển hóa cực nhanh CYP2D6 không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 98. Có cảnh báo nào về rối loạn chức năng tuyến giáp hoặc hấp thu iod toàn thân không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > E. Bộ ví dụ Povidone-iodine
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.6818
- Retrieval seconds: 0.1301
- Generation seconds: 0.1818
- Estimated prompt tokens: 724
- Estimated answer tokens: 686

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 r\u1ed1i lo\u1ea1n ch\u1ee9c n\u0103ng tuy\u1ebfn gi\u00e1p ho\u1eb7c h\u1ea5p thu iod to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về rối loạn chức năng tuyến giáp hoặc hấp thu iod toàn thân không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 99. Có thận trọng nào liên quan đến công thức cho phụ nữ mang thai hoặc cho con bú không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > F. Các bộ smoke test giá trị cao > F1. Bộ tối thiểu 10 câu hỏi về công thức / an toàn
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.6758
- Retrieval seconds: 0.1145
- Generation seconds: 0.0261
- Estimated prompt tokens: 626
- Estimated answer tokens: 640

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 th\u1eadn tr\u1ecdng n\u00e0o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho ph\u1ee5 n\u1eef mang thai ho\u1eb7c cho con b\u00fa kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có thận trọng nào liên quan đến công thức cho phụ nữ mang thai hoặc cho con bú không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=7.7382
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.
  Người nộp đơn đã trả lời như sau.
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 68 | mục=pregnancy | điểm=6.9967
  tiếp xúc với con người).
  (phơi nhiễm ≥3X ở người).
  từ ngày mang thai thứ 16 đến ngày thứ 140.
- Ozempic | interview_form | trang 69 | mục=pregnancy | điểm=6.9092
  Không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ.
  Vì không thể loại trừ nguy cơ đối với trẻ bú sữa mẹ nên không nên sử dụng semaglutide trong thời gian cho con bú.
  Tờ hướng dẫn sử dụng của Úc
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]

Nguồn:
- Ozempic / smpc_label / trang 29
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 68
- Ozempic / interview_form / trang 69
- Ozempic / safety_notice / trang 1
```

## 100. Có cảnh báo nào liên quan đến rối loạn tuyến giáp hoặc hấp thu toàn thân không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > F. Các bộ smoke test giá trị cao > F1. Bộ tối thiểu 10 câu hỏi về công thức / an toàn
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:24
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.696
- Retrieval seconds: 0.0885
- Generation seconds: 0.0528
- Estimated prompt tokens: 723
- Estimated answer tokens: 685

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn r\u1ed1i lo\u1ea1n tuy\u1ebfn gi\u00e1p ho\u1eb7c h\u1ea5p thu to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến rối loạn tuyến giáp hoặc hấp thu toàn thân không cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 101. Hiển thị bằng chứng từ phần contraindications section.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.7709
- Retrieval seconds: 0.1104
- Generation seconds: 0.0593
- Estimated prompt tokens: 691
- Estimated answer tokens: 356

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n contraindications section." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Các chống chỉ định hoặc đối tượng không nên dùng ozempic là gì?
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=6.9094
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7692
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 36 | mục=contraindication | điểm=6.3654
  Chống chỉ định (Không dùng cho những bệnh nhân sau)
  2.Chống chỉ định và lý do
  (Bình luận) Nếu thuốc này được dùng cho bệnh nhân có tiền sử quá mẫn cảm với các thành phần của thuốc này, có khả năng các triệu chứng quá mẫn nghiêm trọng có thể phát triển, vì vậy nên tránh dùng thuốc.
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.2917
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0319
  Nó đã được thực hiện.
  Thuốc này nhóm 1,0 mg
  -Thuốc này nhóm 1,0 mg

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / smpc_label / trang 1
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 36
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
```

## 102. Hiển thị bằng chứng từ phần warnings section.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:25
- Elapsed seconds: 0.5682
- Retrieval seconds: 0.0954
- Generation seconds: 0.0172
- Estimated prompt tokens: 714
- Estimated answer tokens: 675

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n warnings section." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Các cảnh báo và thận trọng khi dùng ozempic là gì?
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5674
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.3251
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8172
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7816
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7692
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5964
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```

## 103. Trả lời kèm trích dẫn và hiển thị chính xác số trang tham chiếu.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:26
- Elapsed seconds: 0.7869
- Retrieval seconds: 0.1527
- Generation seconds: 0.2087
- Estimated prompt tokens: 268
- Estimated answer tokens: 521

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u1ea3 l\u1eddi k\u00e8m tr\u00edch d\u1eabn v\u00e0 hi\u1ec3n th\u1ecb ch\u00ednh x\u00e1c s\u1ed1 trang tham chi\u1ebfu." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Trả lời kèm trích dẫn và hiển thị chính xác số trang tham chiếu. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 104. Hiển thị bằng chứng hỗ trợ và các file trang nguồn cho câu trả lời PK.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:26
- Elapsed seconds: 0.7572
- Retrieval seconds: 0.0791
- Generation seconds: 0.0303
- Estimated prompt tokens: 1260
- Estimated answer tokens: 385

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng h\u1ed7 tr\u1ee3 v\u00e0 c\u00e1c file trang ngu\u1ed3n cho c\u00e2u tr\u1ea3 l\u1eddi PK." --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của ozempic là gì?
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=7.1631
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | interview_form | trang 4 | mục=pk | điểm=7.0521
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=7.0287
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.
- Ozempic | interview_form | trang 31 | mục=pk | điểm=7.0017
  An toàn (phòng ngừa, v.v.) 7.
  Không có phát hiện nào nêu lên vấn đề an toàn trong nghiên cứu này và nó được dung nạp tốt.
  (1) Phương pháp phân tích
- Ozempic | interview_form | trang 33 | mục=pk | điểm=6.9317
  (2) Tốc độ bài tiết
  Thành phần chính là semaglutide không thay đổi.
  (1) Vị trí trao đổi chất và con đường trao đổi chất

Nguồn:
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
- Ozempic / interview_form / trang 31
- Ozempic / interview_form / trang 33
```

## 105. Những trang nào đã được dùng để trả lời câu hỏi về stability?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:26
- Elapsed seconds: 0.7091
- Retrieval seconds: 0.0867
- Generation seconds: 0.0361
- Estimated prompt tokens: 1194
- Estimated answer tokens: 447

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng trang n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c d\u00f9ng \u0111\u1ec3 tr\u1ea3 l\u1eddi c\u00e2u h\u1ecfi v\u1ec1 stability?" --drug-name "ozempic" --json
```

### Result

```text
Câu hỏi: Thông tin độ ổn định và điều kiện bảo quản của ozempic là gì?
Bộ lọc thuốc: ozempic
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.3447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 4 | mục=stability | điểm=7.2429
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 9 | mục=stability | điểm=7.2106
  (7) Các chỉ số chính khác
  Bản đồ peptide, sắc ký lỏng
  (3) Tính hút ẩm Tính hút ẩm.
- Ozempic | interview_form | trang 59 | mục=stability | điểm=7.1232
  9.Ngày và chi tiết bổ sung chỉ định hoặc tác dụng, thay đổi cách sử dụng và liều lượng, v.v.
  4.Các lưu ý khi xử lý
  11.Thời gian tái khám
- Ozempic | interview_form | trang 11 | mục=stability | điểm=7.0625
  Những lưu ý khi xử lý.”
  Sự ổn định trong sử dụng
  Protein phân tử cao, v.v.
- Ozempic | interview_form | trang 27 | mục=stability | điểm=7.0469
  Magglutide dựa trên công nghệ acyl hóa, tương tự như liraglutide (được bán ở Nhật Bản dưới dạng thuốc tiêm dưới da Victoza® 18 mg), nhưng cũng bao gồm những sửa đổi đáng kể về cấu trúc hóa học giúp kéo dài thời gian bán hủy và làm cho nó phù hợp với liều dùng một lần mỗi tuần.
  Semaglutide (tên sản phẩm:
  adenosine monophosphate tuần hoàn

Nguồn:
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 9
- Ozempic / interview_form / trang 59
- Ozempic / interview_form / trang 11
- Ozempic / interview_form / trang 27
```

## 106. Các cảnh báo chính và chống chỉ định của ozempic là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H1. Hồi quy theo dạng câu hỏi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:25
- Finished: 2026-03-29T18:53:26
- Elapsed seconds: 0.7467
- Retrieval seconds: 0.1036
- Generation seconds: 0.043
- Estimated prompt tokens: 905
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c c\u1ea3nh b\u00e1o ch\u00ednh v\u00e0 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh c\u1ee7a ozempic l\u00e0 g\u00ec?" --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Các cảnh báo chính và chống chỉ định của ozempic là gì cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=8.0457
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.8805
  **** Tiêu chí tổng hợp:
  1,76 (khoảng tin cậy 95%:
  Ugobi Tiêm dưới da (Chỉ định:
- Ozempic | interview_form | trang 72 | mục=general | điểm=7.4296
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 64 | mục=indication | điểm=7.3442
  0,5 mg mỗi lần tiêm.
  XII.Tài liệu tham khảo
  Hiệu quả hoặc tác dụng
- Ozempic | interview_form | trang 65 | mục=indication | điểm=7.3304
  Là đơn trị liệu khi metformin được coi là không phù hợp do không dung nạp hoặc chống chỉ định.
  mg mỗi tuần một lần.
  4.1 Chỉ định điều trị
- Ozempic | smpc_label | trang 1 | mục=contraindication | điểm=7.2583
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / smpc_label / trang 13
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 64
- Ozempic / interview_form / trang 65
- Ozempic / smpc_label / trang 1
```

## 107. Hãy tóm tắt hồ sơ dược động học chi tiết bao gồm hấp thu, chuyển hóa và thải trừ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H1. Hồi quy theo dạng câu hỏi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:26
- Finished: 2026-03-29T18:53:26
- Elapsed seconds: 0.4959
- Retrieval seconds: 0.0867
- Generation seconds: 0.0208
- Estimated prompt tokens: 974
- Estimated answer tokens: 443

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "H\u00e3y t\u00f3m t\u1eaft h\u1ed3 s\u01a1 d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc chi ti\u1ebft bao g\u1ed3m h\u1ea5p thu, chuy\u1ec3n h\u00f3a v\u00e0 th\u1ea3i tr\u1eeb." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Hãy tóm tắt hồ sơ dược động học chi tiết bao gồm hấp thu, chuyển hóa và thải trừ. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 30 | mục=pk | điểm=6.5184
  Nó đã được đánh giá.
  7) Làm rỗng dạ dày19
  6) Bài tiết Glucagon17,19,20
- Ozempic | smpc_label | trang 43 | mục=pk | điểm=6.4557
  Sự an toàn khi dùng liều cao hơn 1,0 mg loại thuốc này đã được nghiên cứu ở người trưởng thành khỏe mạnh ở Nhật Bản và nước ngoài.
  Vì thuốc được dung nạp tốt nên chúng tôi tin rằng không có vấn đề cụ thể nào về thời gian dùng thuốc hoặc độ an toàn trong trường hợp quên liều.
  Độ an toàn của thuốc này khi dùng ở liều 0,5 mg và 1,0 mg cũng như khả năng dung nạp trong các thử nghiệm lâm sàng khi dùng liều cao hơn 1,0 mg của loại thuốc này.
- Ozempic | interview_form | trang 4 | mục=pk | điểm=6.4203
  VIII.Các nội dung liên quan đến an toàn (đề phòng, v.v.) 36
  Chi tiết và lý do cảnh báo .................................
  Chống chỉ định và nguyên nhân.................................
- Ozempic | interview_form | trang 13 | mục=pk | điểm=6.3931
  dự kiến sẽ thấp hơn.
  Quản lý vào cùng một ngày trong tuần.
  Các mục liên quan đến dược động học 1.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 30
- Ozempic / smpc_label / trang 43
- Ozempic / interview_form / trang 4
- Ozempic / interview_form / trang 13
```

## 108. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H2. Hồi quy theo tham số truy hồi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:26
- Finished: 2026-03-29T18:53:27
- Elapsed seconds: 0.6773
- Retrieval seconds: 0.1357
- Generation seconds: 0.16
- Estimated prompt tokens: 164
- Estimated answer tokens: 158

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "ozempic" --top-k 3
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
```

## 109. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H2. Hồi quy theo tham số truy hồi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:26
- Finished: 2026-03-29T18:53:27
- Elapsed seconds: 0.65
- Retrieval seconds: 0.0792
- Generation seconds: 0.0169
- Estimated prompt tokens: 360
- Estimated answer tokens: 512

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "ozempic" --top-k 8
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 110. Tóm tắt tất cả các nguy cơ chính.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H3. Stress test / kiểm thử so sánh
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:26
- Finished: 2026-03-29T18:53:27
- Elapsed seconds: 0.6487
- Retrieval seconds: 0.0981
- Generation seconds: 0.0492
- Estimated prompt tokens: 260
- Estimated answer tokens: 513

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft t\u1ea5t c\u1ea3 c\u00e1c nguy c\u01a1 ch\u00ednh." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: Tóm tắt tất cả các nguy cơ chính. cho ozempic.
Bộ lọc thuốc: ozempic

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2873
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.8202
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | interview_form | trang 35 | mục=general | điểm=6.3042
  Không có tài liệu áp dụng
- Ozempic | smpc_label | trang 53 | mục=general | điểm=6.0578
  Các trường hợp này được coi là quần thể phân tích độ an toàn và FAS, và FAS là quần thể phân tích hiệu quả.
  Trong số các đối tượng được chỉ định ngẫu nhiên, 387 đối tượng (bao gồm 129 đối tượng trong nhóm giả dược), ngoại trừ 1 đối tượng đã ngừng điều trị
  Ozempic Tiêm dưới da 2 mg_Novo Nordisk Pharma Co., Ltd._Báo cáo đánh giá Một nghiên cứu so sánh nhóm song song, ngẫu nhiên, mù đôi, đối chứng giả dược đã được tiến hành để kiểm tra hiệu quả và độ an toàn của đơn trị liệu.
- Ozempic | smpc_label | trang 18 | mục=general | điểm=6.0519
  1.2 Cân nhắc về hiệu quả
  Không có cài đặt
- Ozempic | smpc_label | trang 29 | mục=pregnancy | điểm=5.8999
  PMDA yêu cầu người nộp đơn giải thích ảnh hưởng của độc tính đối với phôi thai đến sự an toàn của con người được quan sát thấy trong các nghiên cứu phát triển phôi thai.
  Dựa trên những điều trên, người ta cho rằng có ít khả năng thuốc này tác động trực tiếp lên phôi người, nhưng vì chúng tôi tin rằng không thể loại trừ hoàn toàn mối quan hệ giữa các phát hiện bất thường quan sát được và con người, nên chúng tôi dự định cung cấp thông tin về kết quả và cảnh báo phụ nữ mang thai hoặc những phụ nữ có thể đang mang thai rằng không nên sử dụng loại thuốc này.
  Nó đã không được công nhận.

Nguồn:
- Ozempic / smpc_label / trang 6
- Ozempic / interview_form / trang 72
- Ozempic / interview_form / trang 35
- Ozempic / smpc_label / trang 53
- Ozempic / smpc_label / trang 18
- Ozempic / smpc_label / trang 29
```

## 111. So sánh các cảnh báo của alprazolam và abaloparatide.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H3. Stress test / kiểm thử so sánh
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:53:26
- Finished: 2026-03-29T18:53:27
- Elapsed seconds: 0.6914
- Retrieval seconds: 0.1014
- Generation seconds: 0.0496
- Estimated prompt tokens: 716
- Estimated answer tokens: 679

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "So s\u00e1nh c\u00e1c c\u1ea3nh b\u00e1o c\u1ee7a alprazolam v\u00e0 abaloparatide." --drug-name "ozempic"
```

### Result

```text
Câu hỏi: So sánh các cảnh báo của alprazolam và abaloparatide. cho ozempic.
Bộ lọc thuốc: ozempic
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Ozempic | smpc_label | trang 13 | mục=warning | điểm=7.5374
  Các biện pháp phòng ngừa cơ bản quan trọng" và "Bệnh võng mạc tiểu đường (các biến cố liên quan)" trong phần "11.2 Các tác dụng phụ khác" để kêu gọi thận trọng.
  Bệnh nhân mắc các biến chứng liên quan đến bệnh võng mạc tiểu đường có thể phát triển các triệu chứng nghiêm trọng có thể dẫn đến mù lòa, tùy thuộc vào hoàn cảnh của bệnh, vì vậy nguy cơ này được đánh giá là quan trọng.
  Để hiểu được sự xuất hiện của các biến cố liên quan đến bệnh võng mạc tiểu đường trong thực hành lâm sàng hàng ngày, điều quan trọng là phải có được thông tin về kiểm soát lượng đường trong máu và tiến hành theo dõi lâu dài.
- Ozempic | smpc_label | trang 6 | mục=general | điểm=7.2562
  Không tìm thấy đoạn tiếng Việt tương ứng trong dữ liệu trang nguồn.
- Ozempic | safety_notice | trang 1 | mục=warning | điểm=6.8027
  Có nguy cơ phát triển bệnh sỏi mật, viêm túi mật, viêm đường mật hoặc vàng da ứ mật, vì vậy nếu quan sát thấy các triệu chứng ở bụng như đau bụng, cần thực hiện các biện pháp thích hợp, chẳng hạn như xem xét nguyên nhân thông qua xét nghiệm hình ảnh, v.v., nếu cần.
  [Tên thuốc] Exenatide
  (Hướng dẫn nhập cảnh mới)]
- Ozempic | smpc_label | trang 12 | mục=warning | điểm=6.7657
  Biện pháp phòng ngừa quan trọng'' kêu gọi thận trọng khi sử dụng sản phẩm ở những bệnh nhân phụ thuộc insulin.
  Nguy cơ này được cho là phát sinh do việc điều trị không phù hợp cho những bệnh nhân cần sử dụng chế phẩm insulin bằng cách ngừng sử dụng insulin và chuyển sang dùng thuốc chủ vận thụ thể GLP-1 dùng một lần mỗi ngày.
  Rủi ro này đã được cảnh báo trong tờ hướng dẫn sử dụng điện tử và kế hoạch quản lý rủi ro thuốc đối với các chất chủ vận thụ thể GLP-1 khác và vì điều quan trọng là phải tiếp tục các hoạt động cảnh báo đối với loại thuốc này nên nó đã được chỉ định là một rủi ro tiềm ẩn quan trọng.
- Ozempic | interview_form | trang 72 | mục=general | điểm=6.7447
  Ozempic®, Ozempic®, OZEMPIC®, Libersus® và Ugobi® là các nhãn hiệu đã đăng ký của Novo Nordisk A/S
  Hợp tác quảng cáo
- Ozempic | patient_guide | trang 4 | mục=warning | điểm=6.5854
  [Tôi nên cẩn thận điều gì khi sử dụng thuốc này?]
  Nếu bạn cảm thấy bất thường, hãy tham khảo ý kiến ​​bác sĩ hoặc dược sĩ ngay lập tức.
  Nếu bạn gặp các triệu chứng hạ đường huyết, hãy ăn thực phẩm thường chứa carbohydrate.

Nguồn:
- Ozempic / smpc_label / trang 13
- Ozempic / smpc_label / trang 6
- Ozempic / safety_notice / trang 1
- Ozempic / smpc_label / trang 12
- Ozempic / interview_form / trang 72
- Ozempic / patient_guide / trang 4
```
