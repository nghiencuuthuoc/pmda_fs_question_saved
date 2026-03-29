# PMDA FS Question Export — keytruda

Generated at: 2026-03-29T18:49:59
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
    "elapsed_seconds_sum": 99.805,
    "elapsed_seconds_avg": 0.8991,
    "retrieval_seconds_sum": 17.2144,
    "generation_seconds_sum": 8.0782,
    "estimated_context_tokens_sum": 34424,
    "estimated_prompt_tokens_sum": 44373,
    "estimated_answer_tokens_sum": 44185
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
    "elapsed_seconds_sum": 99.805
  }
}
```

## 1. Các cảnh báo chính và chống chỉ định là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > Cách dùng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:27
- Elapsed seconds: 0.273
- Retrieval seconds: 0.1279
- Generation seconds: 0.1409
- Estimated prompt tokens: 1250
- Estimated answer tokens: 325

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c c\u1ea3nh b\u00e1o ch\u00ednh v\u00e0 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các cảnh báo chính và chống chỉ định là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=6.8110
  Nó đã được bắt đầu vào năm.
  Nó đã được thực hiện từ năm 2011.
  1.2.2 Về ung thư vú (1.1 (ii) ở trên)
- Keytruda | smpc_label | trang 7 | mục=indication | điểm=6.7802
  1.2 Lịch sử phát triển
  Ngoài ra, tháng 12 năm 2018
  được thực hiện từ tháng 12 năm 2015.
- Keytruda | smpc_label | trang 8 | mục=indication | điểm=6.7342
  1.2 Lịch sử phát triển
  Ngày phê duyệt/chỉ định
  được địa phương phê duyệt.
- Keytruda | safety_notice | trang 5 | mục=indication | điểm=6.7223
  1.2 Lịch sử phát triển
  Nó đã được bắt đầu vào năm.
  Ngoài ra, PD-L1 và PD-L2 còn
- Keytruda | safety_notice | trang 8 | mục=indication | điểm=6.6876
  (phiên bản sửa đổi)
  Nó đã được thực hiện.
  1.2 Lịch sử phát triển
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.6845
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch

Nguồn:
- Keytruda / safety_notice / trang 6
- Keytruda / smpc_label / trang 7
- Keytruda / smpc_label / trang 8
- Keytruda / safety_notice / trang 5
- Keytruda / safety_notice / trang 8
- Keytruda / interview_form / trang 291
```

## 2. Các chống chỉ định là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:27
- Elapsed seconds: 0.4656
- Retrieval seconds: 0.1332
- Generation seconds: 0.0666
- Estimated prompt tokens: 1466
- Estimated answer tokens: 321

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các chống chỉ định là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication, indication

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=6.8027
  Nó đã được bắt đầu vào năm.
  Nó đã được thực hiện từ năm 2011.
  1.2.2 Về ung thư vú (1.1 (ii) ở trên)
- Keytruda | smpc_label | trang 7 | mục=indication | điểm=6.7723
  1.2 Lịch sử phát triển
  Ngoài ra, tháng 12 năm 2018
  được thực hiện từ tháng 12 năm 2015.
- Keytruda | smpc_label | trang 8 | mục=indication | điểm=6.7281
  1.2 Lịch sử phát triển
  Ngày phê duyệt/chỉ định
  được địa phương phê duyệt.
- Keytruda | safety_notice | trang 5 | mục=indication | điểm=6.7163
  1.2 Lịch sử phát triển
  Nó đã được bắt đầu vào năm.
  Ngoài ra, PD-L1 và PD-L2 còn
- Keytruda | safety_notice | trang 8 | mục=indication | điểm=6.6770
  (phiên bản sửa đổi)
  Nó đã được thực hiện.
  1.2 Lịch sử phát triển
- Keytruda | safety_notice | trang 7 | mục=indication | điểm=6.6502
  1.2 Lịch sử phát triển
  Ngày phê duyệt/chỉ định
  1) Bao gồm Nhóm 1 đến 3.

Nguồn:
- Keytruda / safety_notice / trang 6
- Keytruda / smpc_label / trang 7
- Keytruda / smpc_label / trang 8
- Keytruda / safety_notice / trang 5
- Keytruda / safety_notice / trang 8
- Keytruda / safety_notice / trang 7
```

## 3. Các chỉ định đã được phê duyệt và hướng dẫn liều dùng là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:28
- Elapsed seconds: 0.7841
- Retrieval seconds: 0.1766
- Generation seconds: 0.1438
- Estimated prompt tokens: 1265
- Estimated answer tokens: 566

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ch\u1ec9 \u0111\u1ecbnh \u0111\u00e3 \u0111\u01b0\u1ee3c ph\u00ea duy\u1ec7t v\u00e0 h\u01b0\u1edbng d\u1eabn li\u1ec1u d\u00f9ng l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các chỉ định đã được phê duyệt và hướng dẫn liều dùng là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: dosage, indication

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 105 | mục=dosage | điểm=7.0092
  Xét nghiệm huyết học:
  ung thư vú bộ ba âm tính
  Điện tâm đồ 12 chuyển đạo
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=6.7563
  Chỉ định này được phê duyệt theo phê duyệt cấp tốc dựa trên khả năng sống sót không tiến triển.
  Tại Hoa Kỳ, vào tháng 11 năm 2020, “KEYTRUDA, kết hợp với hóa trị liệu, được chỉ định để điều trị
  Tính đến tháng 4 năm 2021, nó đã được phê duyệt ở 10 quốc gia hoặc khu vực để chỉ định điều trị ung thư vú.
- Keytruda | smpc_label | trang 7 | mục=indication | điểm=6.7280
  Nó đã được phê duyệt ở 18 quốc gia hoặc khu vực vì chỉ định liên quan đến ung thư.
  Chỉ định này được phê duyệt theo phê duyệt cấp tốc dựa trên tốc độ đáp ứng của khối u và độ bền của phản ứng.
  Chỉ định 1 và 2 ở trên được áp dụng cho "khối u ác tính" và "tế bào không nhỏ tiến triển/tái phát không thể cắt bỏ".
- Keytruda | smpc_label | trang 8 | mục=indication | điểm=6.6938
  Ngày phê duyệt/chỉ định
  Tại Nhật Bản, loại thuốc này đã được phê duyệt cho các chỉ định trong bảng dưới đây.
  Chỉ định này được phê duyệt dưới sự phê duyệt nhanh dựa trên tốc độ phản ứng của khối u và độ bền của phản ứng.
- Keytruda | safety_notice | trang 5 | mục=indication | điểm=6.6821
  Vào tháng 5 năm 2017, loại thuốc này đã được phê duyệt cho các chỉ định sau:
  Tính đến tháng 6 năm 2017, loại thuốc này đã được phê duyệt ở 34 quốc gia hoặc khu vực để chỉ định bệnh chHL.
  Chỉ định này được phê duyệt theo phê duyệt cấp tốc dựa trên tốc độ phản ứng của khối u và độ bền của phản ứng.
- Keytruda | safety_notice | trang 8 | mục=indication | điểm=6.6770
  Ngày phê duyệt/chỉ định
  Tại Nhật Bản, loại thuốc này đã được phê duyệt cho các chỉ định trong bảng dưới đây.
  Tại Hoa Kỳ, vào tháng 6 năm 2025, “KEYTRUDA được chỉ định để điều trị cho bệnh nhân trưởng thành bị ung thư có thể cắt bỏ được.

Nguồn:
- Keytruda / smpc_label / trang 105
- Keytruda / safety_notice / trang 6
- Keytruda / smpc_label / trang 7
- Keytruda / smpc_label / trang 8
- Keytruda / safety_notice / trang 5
- Keytruda / safety_notice / trang 8
```

## 4. Các thận trọng quan trọng trước khi dùng thuốc này là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:28
- Elapsed seconds: 1.405
- Retrieval seconds: 0.4139
- Generation seconds: 0.2068
- Estimated prompt tokens: 379
- Estimated answer tokens: 522

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c th\u1eadn tr\u1ecdng quan tr\u1ecdng tr\u01b0\u1edbc khi d\u00f9ng thu\u1ed1c n\u00e0y l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các thận trọng quan trọng trước khi dùng thuốc này là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 5. Trước khi dùng thuốc này, bệnh nhân cần lưu ý điều gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:29
- Elapsed seconds: 1.5143
- Retrieval seconds: 0.209
- Generation seconds: 0.1605
- Estimated prompt tokens: 226
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u01b0\u1edbc khi d\u00f9ng thu\u1ed1c n\u00e0y, b\u1ec7nh nh\u00e2n c\u1ea7n l\u01b0u \u00fd \u0111i\u1ec1u g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Trước khi dùng thuốc này, bệnh nhân cần lưu ý điều gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 6. Những đối tượng nào không nên dùng thuốc này?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:27
- Finished: 2026-03-29T17:00:29
- Elapsed seconds: 1.5939
- Retrieval seconds: 0.2083
- Generation seconds: 0.0701
- Estimated prompt tokens: 224
- Estimated answer tokens: 337

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng \u0111\u1ed1i t\u01b0\u1ee3ng n\u00e0o kh\u00f4ng n\u00ean d\u00f9ng thu\u1ed1c n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những đối tượng nào không nên dùng thuốc này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 7. Bệnh nhân nên tránh những gì khi đang dùng thuốc này?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:28
- Finished: 2026-03-29T17:00:29
- Elapsed seconds: 1.5463
- Retrieval seconds: 0.1893
- Generation seconds: 0.0848
- Estimated prompt tokens: 226
- Estimated answer tokens: 339

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "B\u1ec7nh nh\u00e2n n\u00ean tr\u00e1nh nh\u1eefng g\u00ec khi \u0111ang d\u00f9ng thu\u1ed1c n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Bệnh nhân nên tránh những gì khi đang dùng thuốc này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 8. Các phản ứng có hại chính và biến cố bất lợi nghiêm trọng là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:28
- Finished: 2026-03-29T17:00:29
- Elapsed seconds: 1.2343
- Retrieval seconds: 0.1805
- Generation seconds: 0.1271
- Estimated prompt tokens: 516
- Estimated answer tokens: 417

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ph\u1ea3n \u1ee9ng c\u00f3 h\u1ea1i ch\u00ednh v\u00e0 bi\u1ebfn c\u1ed1 b\u1ea5t l\u1ee3i nghi\u00eam tr\u1ecdng l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các phản ứng có hại chính và biến cố bất lợi nghiêm trọng là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: adverse_event

Bằng chứng truy xuất hàng đầu:
- Keytruda | patient_guide | trang 1 | mục=adverse_event | điểm=6.6515
  -Thuốc này ngăn chặn sự phát triển của khối u bằng cách ức chế sự liên kết của các thụ thể tế bào T (tế bào miễn dịch) (PD-1) và các chất do tế bào ung thư sản xuất (PD-L1 và PD-L2) và tăng cường kích hoạt tế bào T.・Nó được chỉ định cho những người mắc các bệnh sau đây.
  Cập nhật tháng 2 năm 2026
  KEYTRUDA Tiêm 100mg Tên gốc:
- Keytruda | smpc_label | trang 3 | mục=adverse_event | điểm=6.5787
  liều lượng hàng ngày
  40Gy (cột sống ngực)
  (-), HCVAb (định tính):
- Keytruda | safety_notice | trang 1 | mục=adverse_event | điểm=6.4829
  429 Thuốc điều trị ung thư khác
  [Tên thuốc] Pembrolizumab (tái tổ hợp di truyền)
  Trong phần "Tác dụng phụ đáng kể" của [Phản ứng bất lợi]
- Keytruda | safety_notice | trang 1 | mục=adverse_event | điểm=6.4814
  Viêm tụy, suy tụy ngoại tiết
  11.1 Tác dụng phụ nghiêm trọng
  [Tên thuốc] Pembrolizumab (tái tổ hợp di truyền)
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / patient_guide / trang 1
- Keytruda / smpc_label / trang 3
- Keytruda / safety_notice / trang 1
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 9. Có thận trọng nào cho bệnh nhi, người cao tuổi, phụ nữ mang thai hoặc cho con bú không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:29
- Finished: 2026-03-29T17:00:30
- Elapsed seconds: 1.1678
- Retrieval seconds: 0.2174
- Generation seconds: 0.082
- Estimated prompt tokens: 512
- Estimated answer tokens: 476

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 th\u1eadn tr\u1ecdng n\u00e0o cho b\u1ec7nh nhi, ng\u01b0\u1eddi cao tu\u1ed5i, ph\u1ee5 n\u1eef mang thai ho\u1eb7c cho con b\u00fa kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có thận trọng nào cho bệnh nhi, người cao tuổi, phụ nữ mang thai hoặc cho con bú không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 435 | mục=pregnancy | điểm=6.9890
  Tư vấn cho phụ nữ mang thai về nguy cơ tiềm ẩn đối với thai nhi.
  Không có dữ liệu sẵn có trên người cho biết nguy cơ gây độc cho phôi thai.
  Trong dân số Hoa Kỳ nói chung, nguy cơ cơ bản ước tính về dị tật bẩm sinh nghiêm trọng và sẩy thai ở
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / interview_form / trang 435
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 10. Hiển thị các trang nói về cảnh báo, chống chỉ định và thận trọng.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > A. Câu hỏi lõi về nhãn thuốc / hướng dẫn bệnh nhân
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:29
- Finished: 2026-03-29T17:00:30
- Elapsed seconds: 1.0916
- Retrieval seconds: 0.1551
- Generation seconds: 0.0482
- Estimated prompt tokens: 1256
- Estimated answer tokens: 331

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb c\u00e1c trang n\u00f3i v\u1ec1 c\u1ea3nh b\u00e1o, ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh v\u00e0 th\u1eadn tr\u1ecdng." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Hiển thị các trang nói về cảnh báo, chống chỉ định và thận trọng. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=6.8110
  Nó đã được bắt đầu vào năm.
  Nó đã được thực hiện từ năm 2011.
  1.2.2 Về ung thư vú (1.1 (ii) ở trên)
- Keytruda | smpc_label | trang 7 | mục=indication | điểm=6.7802
  1.2 Lịch sử phát triển
  Ngoài ra, tháng 12 năm 2018
  được thực hiện từ tháng 12 năm 2015.
- Keytruda | smpc_label | trang 8 | mục=indication | điểm=6.7342
  1.2 Lịch sử phát triển
  Ngày phê duyệt/chỉ định
  được địa phương phê duyệt.
- Keytruda | safety_notice | trang 5 | mục=indication | điểm=6.7223
  1.2 Lịch sử phát triển
  Nó đã được bắt đầu vào năm.
  Ngoài ra, PD-L1 và PD-L2 còn
- Keytruda | safety_notice | trang 8 | mục=indication | điểm=6.6876
  (phiên bản sửa đổi)
  Nó đã được thực hiện.
  1.2 Lịch sử phát triển
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.6845
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch

Nguồn:
- Keytruda / safety_notice / trang 6
- Keytruda / smpc_label / trang 7
- Keytruda / smpc_label / trang 8
- Keytruda / safety_notice / trang 5
- Keytruda / safety_notice / trang 8
- Keytruda / interview_form / trang 291
```

## 11. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:29
- Finished: 2026-03-29T17:00:30
- Elapsed seconds: 1.0628
- Retrieval seconds: 0.1946
- Generation seconds: 0.0539
- Estimated prompt tokens: 220
- Estimated answer tokens: 333

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 12. Liệt kê đầy đủ thành phần định tính của sản phẩm.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:29
- Finished: 2026-03-29T17:00:30
- Elapsed seconds: 0.9801
- Retrieval seconds: 0.1776
- Generation seconds: 0.0483
- Estimated prompt tokens: 225
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea \u0111\u1ea7y \u0111\u1ee7 th\u00e0nh ph\u1ea7n \u0111\u1ecbnh t\u00ednh c\u1ee7a s\u1ea3n ph\u1ea9m." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Liệt kê đầy đủ thành phần định tính của sản phẩm. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 13. Thành phần định lượng trên mỗi đơn vị liều là gì?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:30
- Finished: 2026-03-29T17:00:31
- Elapsed seconds: 0.8649
- Retrieval seconds: 0.1362
- Generation seconds: 0.0472
- Estimated prompt tokens: 225
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Th\u00e0nh ph\u1ea7n \u0111\u1ecbnh l\u01b0\u1ee3ng tr\u00ean m\u1ed7i \u0111\u01a1n v\u1ecb li\u1ec1u l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Thành phần định lượng trên mỗi đơn vị liều là gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 14. Có những dạng bào chế và hàm lượng nào?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:30
- Finished: 2026-03-29T17:00:31
- Elapsed seconds: 0.8248
- Retrieval seconds: 0.1311
- Generation seconds: 0.0352
- Estimated prompt tokens: 223
- Estimated answer tokens: 336

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng d\u1ea1ng b\u00e0o ch\u1ebf v\u00e0 h\u00e0m l\u01b0\u1ee3ng n\u00e0o?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có những dạng bào chế và hàm lượng nào cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 15. Những tá dược nào có trong viên 50 mg và 100 mg?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:30
- Finished: 2026-03-29T17:00:31
- Elapsed seconds: 0.7629
- Retrieval seconds: 0.1497
- Generation seconds: 0.0366
- Estimated prompt tokens: 225
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 trong vi\u00ean 50 mg v\u00e0 100 mg?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào có trong viên 50 mg và 100 mg cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 16. Tá dược có khác nhau giữa các hàm lượng của sản phẩm không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:30
- Finished: 2026-03-29T17:00:31
- Elapsed seconds: 0.7065
- Retrieval seconds: 0.1289
- Generation seconds: 0.0411
- Estimated prompt tokens: 228
- Estimated answer tokens: 341

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e1 d\u01b0\u1ee3c c\u00f3 kh\u00e1c nhau gi\u1eefa c\u00e1c h\u00e0m l\u01b0\u1ee3ng c\u1ee7a s\u1ea3n ph\u1ea9m kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tá dược có khác nhau giữa các hàm lượng của sản phẩm không cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 17. Những thành phần công thức nào được liệt kê cho sản phẩm này?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:31
- Finished: 2026-03-29T17:00:31
- Elapsed seconds: 0.7409
- Retrieval seconds: 0.1223
- Generation seconds: 0.0944
- Estimated prompt tokens: 228
- Estimated answer tokens: 341

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea cho s\u1ea3n ph\u1ea9m n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thành phần công thức nào được liệt kê cho sản phẩm này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 18. Tài liệu có phân biệt hoạt chất với tá dược không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:31
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7941
- Retrieval seconds: 0.1583
- Generation seconds: 0.0608
- Estimated prompt tokens: 226
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e0i li\u1ec7u c\u00f3 ph\u00e2n bi\u1ec7t ho\u1ea1t ch\u1ea5t v\u1edbi t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tài liệu có phân biệt hoạt chất với tá dược không cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 19. Những tá dược/phụ gia dược dụng nào được nêu trong nhãn?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:31
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7666
- Retrieval seconds: 0.1254
- Generation seconds: 0.0336
- Estimated prompt tokens: 227
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c/ph\u1ee5 gia d\u01b0\u1ee3c d\u1ee5ng n\u00e0o \u0111\u01b0\u1ee3c n\u00eau trong nh\u00e3n?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược/phụ gia dược dụng nào được nêu trong nhãn cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 20. Hiển thị phần thành phần.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:31
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7963
- Retrieval seconds: 0.1592
- Generation seconds: 0.0406
- Estimated prompt tokens: 219
- Estimated answer tokens: 332

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb ph\u1ea7n th\u00e0nh ph\u1ea7n." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Hiển thị phần thành phần. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 21. Chỉ hiển thị thông tin về tá dược.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:31
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7737
- Retrieval seconds: 0.1281
- Generation seconds: 0.0642
- Estimated prompt tokens: 222
- Estimated answer tokens: 335

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ch\u1ec9 hi\u1ec3n th\u1ecb th\u00f4ng tin v\u1ec1 t\u00e1 d\u01b0\u1ee3c." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Chỉ hiển thị thông tin về tá dược. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 22. Trích xuất danh sách tá dược và dạng bào chế.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7003
- Retrieval seconds: 0.114
- Generation seconds: 0.0338
- Estimated prompt tokens: 224
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u00edch xu\u1ea5t danh s\u00e1ch t\u00e1 d\u01b0\u1ee3c v\u00e0 d\u1ea1ng b\u00e0o ch\u1ebf." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Trích xuất danh sách tá dược và dạng bào chế. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 23. Tóm tắt thành phần công thức và các đặc tính dược học/công nghệ của sản phẩm.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B1. Thành phần và dạng bào chế
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:32
- Elapsed seconds: 0.7424
- Retrieval seconds: 0.1599
- Generation seconds: 0.0402
- Estimated prompt tokens: 232
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c v\u00e0 c\u00e1c \u0111\u1eb7c t\u00ednh d\u01b0\u1ee3c h\u1ecdc/c\u00f4ng ngh\u1ec7 c\u1ee7a s\u1ea3n ph\u1ea9m." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần công thức và các đặc tính dược học/công nghệ của sản phẩm. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 24. Liệt kê tất cả tá dược trong công thức.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:33
- Elapsed seconds: 0.7081
- Retrieval seconds: 0.1131
- Generation seconds: 0.0513
- Estimated prompt tokens: 223
- Estimated answer tokens: 336

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea t\u1ea5t c\u1ea3 t\u00e1 d\u01b0\u1ee3c trong c\u00f4ng th\u1ee9c." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Liệt kê tất cả tá dược trong công thức. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 25. Liệt kê tất cả thành phần không có hoạt tính.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:33
- Elapsed seconds: 0.6857
- Retrieval seconds: 0.1364
- Generation seconds: 0.0353
- Estimated prompt tokens: 224
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Li\u1ec7t k\u00ea t\u1ea5t c\u1ea3 th\u00e0nh ph\u1ea7n kh\u00f4ng c\u00f3 ho\u1ea1t t\u00ednh." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Liệt kê tất cả thành phần không có hoạt tính. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 26. Những thành phần không có hoạt tính nào được liệt kê trong tài liệu này?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:33
- Elapsed seconds: 0.7419
- Retrieval seconds: 0.1633
- Generation seconds: 0.0395
- Estimated prompt tokens: 231
- Estimated answer tokens: 344

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n kh\u00f4ng c\u00f3 ho\u1ea1t t\u00ednh n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea trong t\u00e0i li\u1ec7u n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thành phần không có hoạt tính nào được liệt kê trong tài liệu này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 27. Những tá dược nào nhiều khả năng đóng vai trò độn, dính, rã hoặc bôi trơn?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:32
- Finished: 2026-03-29T17:00:33
- Elapsed seconds: 0.7184
- Retrieval seconds: 0.1207
- Generation seconds: 0.055
- Estimated prompt tokens: 232
- Estimated answer tokens: 344

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o nhi\u1ec1u kh\u1ea3 n\u0103ng \u0111\u00f3ng vai tr\u00f2 \u0111\u1ed9n, d\u00ednh, r\u00e3 ho\u1eb7c b\u00f4i tr\u01a1n?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào nhiều khả năng đóng vai trò độn, dính, rã hoặc bôi trơn cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 28. Những tá dược nào liên quan đến bao phim, tạo màu hoặc bảo quản?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:33
- Finished: 2026-03-29T17:00:33
- Elapsed seconds: 0.7017
- Retrieval seconds: 0.1184
- Generation seconds: 0.0296
- Estimated prompt tokens: 229
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o li\u00ean quan \u0111\u1ebfn bao phim, t\u1ea1o m\u00e0u ho\u1eb7c b\u1ea3o qu\u1ea3n?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào liên quan đến bao phim, tạo màu hoặc bảo quản cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 29. Những tá dược nào có thể ảnh hưởng đến độ ổn định hoặc khả năng sản xuất?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:33
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.7549
- Retrieval seconds: 0.1892
- Generation seconds: 0.0408
- Estimated prompt tokens: 231
- Estimated answer tokens: 350

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 \u1ea3nh h\u01b0\u1edfng \u0111\u1ebfn \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh ho\u1eb7c kh\u1ea3 n\u0103ng s\u1ea3n xu\u1ea5t?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể ảnh hưởng đến độ ổn định hoặc khả năng sản xuất cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 30. Những tá dược nào có thể ảnh hưởng đến độ tan, độ nhớt hoặc đặc tính giải phóng?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:33
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.728
- Retrieval seconds: 0.1182
- Generation seconds: 0.0525
- Estimated prompt tokens: 233
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 \u1ea3nh h\u01b0\u1edfng \u0111\u1ebfn \u0111\u1ed9 tan, \u0111\u1ed9 nh\u1edbt ho\u1eb7c \u0111\u1eb7c t\u00ednh gi\u1ea3i ph\u00f3ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể ảnh hưởng đến độ tan, độ nhớt hoặc đặc tính giải phóng cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 31. Tóm tắt thành phần tá dược và vai trò công nghệ có khả năng của chúng trong công thức.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B2. Tá dược và vai trò trong công thức
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:33
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.6953
- Retrieval seconds: 0.1129
- Generation seconds: 0.0294
- Estimated prompt tokens: 234
- Estimated answer tokens: 348

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n t\u00e1 d\u01b0\u1ee3c v\u00e0 vai tr\u00f2 c\u00f4ng ngh\u1ec7 c\u00f3 kh\u1ea3 n\u0103ng c\u1ee7a ch\u00fang trong c\u00f4ng th\u1ee9c." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần tá dược và vai trò công nghệ có khả năng của chúng trong công thức. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 32. Có cảnh báo nào liên quan đến tá dược không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:33
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.7501
- Retrieval seconds: 0.1676
- Generation seconds: 0.0375
- Estimated prompt tokens: 376
- Estimated answer tokens: 519

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến tá dược không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 33. Có chống chỉ định hoặc thận trọng nào liên quan đến tá dược không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.7018
- Retrieval seconds: 0.1198
- Generation seconds: 0.0565
- Estimated prompt tokens: 1256
- Estimated answer tokens: 331

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh ho\u1eb7c th\u1eadn tr\u1ecdng n\u00e0o li\u00ean quan \u0111\u1ebfn t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có chống chỉ định hoặc thận trọng nào liên quan đến tá dược không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=6.8110
  Nó đã được bắt đầu vào năm.
  Nó đã được thực hiện từ năm 2011.
  1.2.2 Về ung thư vú (1.1 (ii) ở trên)
- Keytruda | smpc_label | trang 7 | mục=indication | điểm=6.7802
  1.2 Lịch sử phát triển
  Ngoài ra, tháng 12 năm 2018
  được thực hiện từ tháng 12 năm 2015.
- Keytruda | smpc_label | trang 8 | mục=indication | điểm=6.7342
  1.2 Lịch sử phát triển
  Ngày phê duyệt/chỉ định
  được địa phương phê duyệt.
- Keytruda | safety_notice | trang 5 | mục=indication | điểm=6.7223
  1.2 Lịch sử phát triển
  Nó đã được bắt đầu vào năm.
  Ngoài ra, PD-L1 và PD-L2 còn
- Keytruda | safety_notice | trang 8 | mục=indication | điểm=6.6876
  (phiên bản sửa đổi)
  Nó đã được thực hiện.
  1.2 Lịch sử phát triển
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.6845
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch

Nguồn:
- Keytruda / safety_notice / trang 6
- Keytruda / smpc_label / trang 7
- Keytruda / smpc_label / trang 8
- Keytruda / safety_notice / trang 5
- Keytruda / safety_notice / trang 8
- Keytruda / interview_form / trang 291
```

## 34. Những tá dược nào có thể gây quá mẫn hoặc không dung nạp?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:34
- Elapsed seconds: 0.7017
- Retrieval seconds: 0.1106
- Generation seconds: 0.0633
- Estimated prompt tokens: 227
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c n\u00e0o c\u00f3 th\u1ec3 g\u00e2y qu\u00e1 m\u1eabn ho\u1eb7c kh\u00f4ng dung n\u1ea1p?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược nào có thể gây quá mẫn hoặc không dung nạp cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 35. Có cảnh báo nào về chất bảo quản, chất màu, tá dược bao phim hoặc tá dược chứa cồn không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:35
- Elapsed seconds: 0.8488
- Retrieval seconds: 0.241
- Generation seconds: 0.0491
- Estimated prompt tokens: 296
- Estimated answer tokens: 431

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 ch\u1ea5t b\u1ea3o qu\u1ea3n, ch\u1ea5t m\u00e0u, t\u00e1 d\u01b0\u1ee3c bao phim ho\u1eb7c t\u00e1 d\u01b0\u1ee3c ch\u1ee9a c\u1ed3n kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về chất bảo quản, chất màu, tá dược bao phim hoặc tá dược chứa cồn không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.5644
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 36. Có cảnh báo nào về đường, polyol hoặc hàm lượng natri trong công thức không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:35
- Elapsed seconds: 0.8218
- Retrieval seconds: 0.1233
- Generation seconds: 0.0548
- Estimated prompt tokens: 384
- Estimated answer tokens: 527

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 \u0111\u01b0\u1eddng, polyol ho\u1eb7c h\u00e0m l\u01b0\u1ee3ng natri trong c\u00f4ng th\u1ee9c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về đường, polyol hoặc hàm lượng natri trong công thức không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 37. Sản phẩm có chứa tá dược cần thận trọng ở bệnh nhân nhạy cảm không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B3. An toàn liên quan đến tá dược
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:35
- Elapsed seconds: 0.8102
- Retrieval seconds: 0.123
- Generation seconds: 0.0394
- Estimated prompt tokens: 382
- Estimated answer tokens: 524

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "S\u1ea3n ph\u1ea9m c\u00f3 ch\u1ee9a t\u00e1 d\u01b0\u1ee3c c\u1ea7n th\u1eadn tr\u1ecdng \u1edf b\u1ec7nh nh\u00e2n nh\u1ea1y c\u1ea3m kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Sản phẩm có chứa tá dược cần thận trọng ở bệnh nhân nhạy cảm không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 38. Có cảnh báo liên quan đến công thức cho bệnh nhi không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:34
- Finished: 2026-03-29T17:00:35
- Elapsed seconds: 0.8591
- Retrieval seconds: 0.1892
- Generation seconds: 0.0358
- Estimated prompt tokens: 378
- Estimated answer tokens: 522

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho b\u1ec7nh nhi kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo liên quan đến công thức cho bệnh nhi không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 39. Có cảnh báo liên quan đến công thức cho người cao tuổi không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:35
- Finished: 2026-03-29T17:00:36
- Elapsed seconds: 0.7855
- Retrieval seconds: 0.149
- Generation seconds: 0.0654
- Estimated prompt tokens: 380
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho ng\u01b0\u1eddi cao tu\u1ed5i kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo liên quan đến công thức cho người cao tuổi không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 40. Có cảnh báo nào về mang thai hoặc cho con bú liên quan đến công thức hay tá dược không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:35
- Finished: 2026-03-29T17:00:36
- Elapsed seconds: 0.7699
- Retrieval seconds: 0.1342
- Generation seconds: 0.0289
- Estimated prompt tokens: 512
- Estimated answer tokens: 476

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 mang thai ho\u1eb7c cho con b\u00fa li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c hay t\u00e1 d\u01b0\u1ee3c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về mang thai hoặc cho con bú liên quan đến công thức hay tá dược không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 435 | mục=pregnancy | điểm=6.9890
  Tư vấn cho phụ nữ mang thai về nguy cơ tiềm ẩn đối với thai nhi.
  Không có dữ liệu sẵn có trên người cho biết nguy cơ gây độc cho phôi thai.
  Trong dân số Hoa Kỳ nói chung, nguy cơ cơ bản ước tính về dị tật bẩm sinh nghiêm trọng và sẩy thai ở
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / interview_form / trang 435
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 41. Có lo ngại an toàn nào liên quan đến bệnh tuyến giáp, suy thận hoặc hấp thu toàn thân không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:35
- Finished: 2026-03-29T17:00:36
- Elapsed seconds: 0.8449
- Retrieval seconds: 0.1947
- Generation seconds: 0.043
- Estimated prompt tokens: 236
- Estimated answer tokens: 349

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 lo ng\u1ea1i an to\u00e0n n\u00e0o li\u00ean quan \u0111\u1ebfn b\u1ec7nh tuy\u1ebfn gi\u00e1p, suy th\u1eadn ho\u1eb7c h\u1ea5p thu to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có lo ngại an toàn nào liên quan đến bệnh tuyến giáp, suy thận hoặc hấp thu toàn thân không cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 42. Việc dùng kéo dài, bôi trên diện rộng hoặc dùng trên niêm mạc có làm tăng nguy cơ an toàn liên quan đến công thức không?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:35
- Finished: 2026-03-29T17:00:36
- Elapsed seconds: 0.8294
- Retrieval seconds: 0.1459
- Generation seconds: 0.0639
- Estimated prompt tokens: 243
- Estimated answer tokens: 356

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Vi\u1ec7c d\u00f9ng k\u00e9o d\u00e0i, b\u00f4i tr\u00ean di\u1ec7n r\u1ed9ng ho\u1eb7c d\u00f9ng tr\u00ean ni\u00eam m\u1ea1c c\u00f3 l\u00e0m t\u0103ng nguy c\u01a1 an to\u00e0n li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Việc dùng kéo dài, bôi trên diện rộng hoặc dùng trên niêm mạc có làm tăng nguy cơ an toàn liên quan đến công thức không cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 43. Tóm tắt các thận trọng ở quần thể đặc biệt liên quan đến công thức và tá dược.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank VI > B. Công thức / thành phần / tá dược / an toàn > B4. An toàn liên quan đến công thức ở quần thể đặc biệt và điều kiện sử dụng
- Generator: none
- Success: Yes
- Started: 2026-03-29T17:00:36
- Finished: 2026-03-29T17:00:36
- Elapsed seconds: 0.7608
- Retrieval seconds: 0.1214
- Generation seconds: 0.0271
- Estimated prompt tokens: 384
- Estimated answer tokens: 528

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft c\u00e1c th\u1eadn tr\u1ecdng \u1edf qu\u1ea7n th\u1ec3 \u0111\u1eb7c bi\u1ec7t li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c v\u00e0 t\u00e1 d\u01b0\u1ee3c." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt các thận trọng ở quần thể đặc biệt liên quan đến công thức và tá dược. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 44. Các điều kiện bảo quản và thận trọng về độ ổn định được mô tả là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:22
- Elapsed seconds: 0.1568
- Retrieval seconds: 0.1221
- Generation seconds: 0.0318
- Estimated prompt tokens: 291
- Estimated answer tokens: 426

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c \u0111i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n v\u00e0 th\u1eadn tr\u1ecdng v\u1ec1 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3 l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các điều kiện bảo quản và thận trọng về độ ổn định được mô tả là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.5644
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 45. Những thành phần công thức nào có thể nhạy cảm với ánh sáng, nhiệt, ẩm hoặc oxy hóa?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:22
- Elapsed seconds: 0.3529
- Retrieval seconds: 0.1412
- Generation seconds: 0.0602
- Estimated prompt tokens: 234
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00e0nh ph\u1ea7n c\u00f4ng th\u1ee9c n\u00e0o c\u00f3 th\u1ec3 nh\u1ea1y c\u1ea3m v\u1edbi \u00e1nh s\u00e1ng, nhi\u1ec7t, \u1ea9m ho\u1eb7c oxy h\u00f3a?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thành phần công thức nào có thể nhạy cảm với ánh sáng, nhiệt, ẩm hoặc oxy hóa cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 46. Có lưu ý nào về bao bì hoặc dụng cụ chứa liên quan đến độ ổn định không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:23
- Elapsed seconds: 0.6294
- Retrieval seconds: 0.1972
- Generation seconds: 0.0773
- Estimated prompt tokens: 231
- Estimated answer tokens: 349

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 l\u01b0u \u00fd n\u00e0o v\u1ec1 bao b\u00ec ho\u1eb7c d\u1ee5ng c\u1ee5 ch\u1ee9a li\u00ean quan \u0111\u1ebfn \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có lưu ý nào về bao bì hoặc dụng cụ chứa liên quan đến độ ổn định không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 47. Tóm tắt dữ liệu độ ổn định liên quan đến công thức và hướng dẫn bảo quản.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B5. Độ ổn định, bảo quản, bao bì
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:23
- Elapsed seconds: 0.8282
- Retrieval seconds: 0.1406
- Generation seconds: 0.0604
- Estimated prompt tokens: 231
- Estimated answer tokens: 350

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c v\u00e0 h\u01b0\u1edbng d\u1eabn b\u1ea3o qu\u1ea3n." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định liên quan đến công thức và hướng dẫn bảo quản. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 48. Những chi tiết công thức nào quan trọng nhất cho phát triển thuốc generic?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:23
- Elapsed seconds: 0.8858
- Retrieval seconds: 0.1622
- Generation seconds: 0.0373
- Estimated prompt tokens: 232
- Estimated answer tokens: 344

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng chi ti\u1ebft c\u00f4ng th\u1ee9c n\u00e0o quan tr\u1ecdng nh\u1ea5t cho ph\u00e1t tri\u1ec3n thu\u1ed1c generic?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những chi tiết công thức nào quan trọng nhất cho phát triển thuốc generic cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 49. Những tá dược hoặc đặc tính công thức nào có thể là thuộc tính chất lượng trọng yếu (CQA)?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:22
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 1.2362
- Retrieval seconds: 0.2261
- Generation seconds: 0.3268
- Estimated prompt tokens: 236
- Estimated answer tokens: 348

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e1 d\u01b0\u1ee3c ho\u1eb7c \u0111\u1eb7c t\u00ednh c\u00f4ng th\u1ee9c n\u00e0o c\u00f3 th\u1ec3 l\u00e0 thu\u1ed9c t\u00ednh ch\u1ea5t l\u01b0\u1ee3ng tr\u1ecdng y\u1ebfu (CQA)?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tá dược hoặc đặc tính công thức nào có thể là thuộc tính chất lượng trọng yếu (CQA) cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 50. Những cảnh báo nào liên quan đến công thức cần được xem xét trước khi cải tiến / reformulation?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:23
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 1.1366
- Retrieval seconds: 0.1406
- Generation seconds: 0.0386
- Estimated prompt tokens: 388
- Estimated answer tokens: 522

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c c\u1ea7n \u0111\u01b0\u1ee3c xem x\u00e9t tr\u01b0\u1edbc khi c\u1ea3i ti\u1ebfn / reformulation?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Thành phần hoạt chất, tá dược và đặc điểm công thức của keytruda là gì?
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 51. Những tài liệu mẫu nào có chứa thông tin về tá dược?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:23
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 1.0875
- Retrieval seconds: 0.1165
- Generation seconds: 0.0359
- Estimated prompt tokens: 226
- Estimated answer tokens: 339

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e0i li\u1ec7u m\u1eabu n\u00e0o c\u00f3 ch\u1ee9a th\u00f4ng tin v\u1ec1 t\u00e1 d\u01b0\u1ee3c?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tài liệu mẫu nào có chứa thông tin về tá dược cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 52. Tài liệu nào phù hợp hơn để lấy chi tiết tá dược: nhãn thuốc hay hướng dẫn bệnh nhân?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:23
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 1.0874
- Retrieval seconds: 0.1288
- Generation seconds: 0.0687
- Estimated prompt tokens: 234
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00e0i li\u1ec7u n\u00e0o ph\u00f9 h\u1ee3p h\u01a1n \u0111\u1ec3 l\u1ea5y chi ti\u1ebft t\u00e1 d\u01b0\u1ee3c: nh\u00e3n thu\u1ed1c hay h\u01b0\u1edbng d\u1eabn b\u1ec7nh nh\u00e2n?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tài liệu nào phù hợp hơn để lấy chi tiết tá dược: nhãn thuốc hay hướng dẫn bệnh nhân cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 53. Tóm tắt thành phần, tá dược, độ ổn định và các nguy cơ an toàn liên quan đến công thức.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > B. Công thức / thành phần / tá dược / an toàn > B6. Nghiên cứu phát triển / thuốc generic
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 0.7698
- Retrieval seconds: 0.1645
- Generation seconds: 0.0735
- Estimated prompt tokens: 235
- Estimated answer tokens: 353

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft th\u00e0nh ph\u1ea7n, t\u00e1 d\u01b0\u1ee3c, \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh v\u00e0 c\u00e1c nguy c\u01a1 an to\u00e0n li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt thành phần, tá dược, độ ổn định và các nguy cơ an toàn liên quan đến công thức. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 54. Tóm tắt dược động học của thuốc này.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:24
- Elapsed seconds: 0.7804
- Retrieval seconds: 0.1323
- Generation seconds: 0.0586
- Estimated prompt tokens: 273
- Estimated answer tokens: 348

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc c\u1ee7a thu\u1ed1c n\u00e0y." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt dược động học của thuốc này. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 55. Các thông số dược động học chính như Cmax, Tmax, AUC và thời gian bán thải là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:25
- Elapsed seconds: 0.8133
- Retrieval seconds: 0.1376
- Generation seconds: 0.0473
- Estimated prompt tokens: 874
- Estimated answer tokens: 574

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c th\u00f4ng s\u1ed1 d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc ch\u00ednh nh\u01b0 Cmax, Tmax, AUC v\u00e0 th\u1eddi gian b\u00e1n th\u1ea3i l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của keytruda là gì?
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 9 | mục=pk | điểm=6.5045
  Nghiên cứu hiệu quả và độ an toàn của thuốc này trên 305 bệnh nhân bị NSCLC tái phát (152 bệnh nhân được đưa vào phân tích PK)
  Một nghiên cứu nhãn mở nhằm mục đích điều tra hiệu quả và độ an toàn của thuốc này trên 1.034 bệnh nhân (660 bệnh nhân để phân tích PK).
  Năm, tháng, ngày]>)
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | smpc_label | trang 6 | mục=pk | điểm=6.4668
  (Kỳ thi KEYNOTE-011)
  Trung vị (phạm vi) ‡ :
  Phải trong vòng 7 ngày.
- Keytruda | interview_form | trang 8 | mục=pk | điểm=6.4599
  Định nghĩa viết tắt rrPMBCLU lympho tế bào B lớn trung thất nguyên phát tái phát hoặc khó chữa U lympho tế bào B lớn trung thất nguyên phát tái phát hoặc khó chữaRTXạ trịXạ trịSDSbệnh ổn địnhSDĐộ lệch chuẩnĐộ lệch chuẩnt1/2Thời gian bán thải đào thảiTmaxThời gian đạt nồng độ tối đa trong huyết thanhThời gian đạt nồng độ tối đa trong huyết thanhTMB-Cao Gánh nặng đột biến khối u caoTNMTDi căn nút khối u-TPSTĐiểm tỷ lệ khối uTỷ lệ tế bào dương tính với PD-L1 giữa các tế bào khối uTSSHHormone kích thích tuyến giápHormone kích thích tuyến giápTTRThời gian đáp ứngThời gian đáp ứngUICCLiên minh kiểm soát ung thư quốc tếVEGFYếu tố tăng trưởng tế bào nội mô mạch máuYếu tố tăng trưởng tế bào nội mô mạch máuVzThể tích của giai đoạn cuốiThể tích phân bố của giai đoạn loại bỏ cuối cùngWESTrình tự toàn bộ exome-γ-GTPGamma-glutamyltransferaseγ-glutamyltransferase

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 9
- Keytruda / smpc_label / trang 39
- Keytruda / smpc_label / trang 6
- Keytruda / interview_form / trang 8
```

## 56. Mô tả diễn biến nồng độ thuốc trong huyết tương theo thời gian.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:25
- Elapsed seconds: 1.2925
- Retrieval seconds: 0.281
- Generation seconds: 0.3796
- Estimated prompt tokens: 229
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "M\u00f4 t\u1ea3 di\u1ec5n bi\u1ebfn n\u1ed3ng \u0111\u1ed9 thu\u1ed1c trong huy\u1ebft t\u01b0\u01a1ng theo th\u1eddi gian." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Mô tả diễn biến nồng độ thuốc trong huyết tương theo thời gian. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 57. Có những phân tích dược động học quần thể nào được báo cáo?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:26
- Elapsed seconds: 1.3498
- Retrieval seconds: 0.2562
- Generation seconds: 0.0369
- Estimated prompt tokens: 279
- Estimated answer tokens: 354

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng ph\u00e2n t\u00edch d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc qu\u1ea7n th\u1ec3 n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có những phân tích dược động học quần thể nào được báo cáo cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 58. Tóm tắt hấp thu, phân bố, chuyển hóa và thải trừ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:24
- Finished: 2026-03-29T18:48:26
- Elapsed seconds: 1.4395
- Retrieval seconds: 0.2069
- Generation seconds: 0.0748
- Estimated prompt tokens: 225
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft h\u1ea5p thu, ph\u00e2n b\u1ed1, chuy\u1ec3n h\u00f3a v\u00e0 th\u1ea3i tr\u1eeb." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt hấp thu, phân bố, chuyển hóa và thải trừ. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 59. Đã biết gì về hấp thu đường uống và sinh khả dụng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:25
- Finished: 2026-03-29T18:48:26
- Elapsed seconds: 1.5079
- Retrieval seconds: 0.1699
- Generation seconds: 0.0835
- Estimated prompt tokens: 226
- Estimated answer tokens: 338

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "\u0110\u00e3 bi\u1ebft g\u00ec v\u1ec1 h\u1ea5p thu \u0111\u01b0\u1eddng u\u1ed1ng v\u00e0 sinh kh\u1ea3 d\u1ee5ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Đã biết gì về hấp thu đường uống và sinh khả dụng cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 60. Các con đường chuyển hóa và enzyme chính liên quan là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:25
- Finished: 2026-03-29T18:48:26
- Elapsed seconds: 1.0351
- Retrieval seconds: 0.1531
- Generation seconds: 0.0519
- Estimated prompt tokens: 227
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c con \u0111\u01b0\u1eddng chuy\u1ec3n h\u00f3a v\u00e0 enzyme ch\u00ednh li\u00ean quan l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các con đường chuyển hóa và enzyme chính liên quan là gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 61. Những chất vận chuyển nào được nhắc đến trong phần dược động học?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:26
- Finished: 2026-03-29T18:48:27
- Elapsed seconds: 0.9114
- Retrieval seconds: 0.1357
- Generation seconds: 0.0307
- Estimated prompt tokens: 280
- Estimated answer tokens: 356

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ch\u1ea5t v\u1eadn chuy\u1ec3n n\u00e0o \u0111\u01b0\u1ee3c nh\u1eafc \u0111\u1ebfn trong ph\u1ea7n d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những chất vận chuyển nào được nhắc đến trong phần dược động học cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 62. Có dữ liệu dược động học ở bệnh nhân suy thận hoặc suy gan không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:26
- Finished: 2026-03-29T18:48:27
- Elapsed seconds: 0.7801
- Retrieval seconds: 0.1203
- Generation seconds: 0.0287
- Estimated prompt tokens: 280
- Estimated answer tokens: 356

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 d\u1eef li\u1ec7u d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc \u1edf b\u1ec7nh nh\u00e2n suy th\u1eadn ho\u1eb7c suy gan kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có dữ liệu dược động học ở bệnh nhân suy thận hoặc suy gan không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 63. Tóm tắt dược động học ở các quần thể đặc biệt.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C1. Dược động học
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:26
- Finished: 2026-03-29T18:48:27
- Elapsed seconds: 1.0448
- Retrieval seconds: 0.2037
- Generation seconds: 0.3176
- Estimated prompt tokens: 276
- Estimated answer tokens: 351

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc \u1edf c\u00e1c qu\u1ea7n th\u1ec3 \u0111\u1eb7c bi\u1ec7t." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt dược động học ở các quần thể đặc biệt. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 64. Các phát hiện PK chính là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:26
- Finished: 2026-03-29T18:48:27
- Elapsed seconds: 1.0496
- Retrieval seconds: 0.1612
- Generation seconds: 0.0441
- Estimated prompt tokens: 226
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c ph\u00e1t hi\u1ec7n PK ch\u00ednh l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của keytruda là gì?
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.8877
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.7683
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 65. Interview form nói gì về bảo quản và độ ổn định?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:27
- Finished: 2026-03-29T18:48:28
- Elapsed seconds: 1.063
- Retrieval seconds: 0.1337
- Generation seconds: 0.0508
- Estimated prompt tokens: 444
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Interview form n\u00f3i g\u00ec v\u1ec1 b\u1ea3o qu\u1ea3n v\u00e0 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Interview form nói gì về bảo quản và độ ổn định cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 7 | mục=stability | điểm=7.0577
  Quản lý 2 tuần một lần
  Quản lý 3 tuần một lần
  Quản lý 6 tuần một lần
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu

Nguồn:
- Keytruda / interview_form / trang 7
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 66. Phần nào của interview form mô tả thành phần và công thức?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:27
- Finished: 2026-03-29T18:48:28
- Elapsed seconds: 1.1009
- Retrieval seconds: 0.127
- Generation seconds: 0.0557
- Estimated prompt tokens: 228
- Estimated answer tokens: 350

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ph\u1ea7n n\u00e0o c\u1ee7a interview form m\u00f4 t\u1ea3 th\u00e0nh ph\u1ea7n v\u00e0 c\u00f4ng th\u1ee9c?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Phần nào của interview form mô tả thành phần và công thức cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=7.0242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 67. Hiển thị bằng chứng từ phần dược động học.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C2. Interview form / điều hướng kỹ thuật chuyên sâu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:27
- Finished: 2026-03-29T18:48:28
- Elapsed seconds: 0.8136
- Retrieval seconds: 0.1602
- Generation seconds: 0.0752
- Estimated prompt tokens: 275
- Estimated answer tokens: 350

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Hiển thị bằng chứng từ phần dược động học. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 68. Tóm tắt dữ liệu độ ổn định của hoạt chất.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:27
- Finished: 2026-03-29T18:48:28
- Elapsed seconds: 0.7932
- Retrieval seconds: 0.1315
- Generation seconds: 0.0531
- Estimated prompt tokens: 223
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh c\u1ee7a ho\u1ea1t ch\u1ea5t." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định của hoạt chất. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 69. Tóm tắt dữ liệu độ ổn định của thành phẩm.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:28
- Finished: 2026-03-29T18:48:29
- Elapsed seconds: 0.9779
- Retrieval seconds: 0.1592
- Generation seconds: 0.2071
- Estimated prompt tokens: 224
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft d\u1eef li\u1ec7u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh c\u1ee7a th\u00e0nh ph\u1ea9m." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt dữ liệu độ ổn định của thành phẩm. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 70. Có những kết quả độ ổn định nào được báo cáo trong điều kiện bảo quản dài hạn?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:28
- Finished: 2026-03-29T18:48:29
- Elapsed seconds: 1.0522
- Retrieval seconds: 0.1705
- Generation seconds: 0.0521
- Estimated prompt tokens: 232
- Estimated answer tokens: 351

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng k\u1ebft qu\u1ea3 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o trong \u0111i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n d\u00e0i h\u1ea1n?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có những kết quả độ ổn định nào được báo cáo trong điều kiện bảo quản dài hạn cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 71. Có những nghiên cứu độ ổn định tăng tốc nào được báo cáo?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:28
- Finished: 2026-03-29T18:48:29
- Elapsed seconds: 1.0205
- Retrieval seconds: 0.1522
- Generation seconds: 0.0503
- Estimated prompt tokens: 227
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng nghi\u00ean c\u1ee9u \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh t\u0103ng t\u1ed1c n\u00e0o \u0111\u01b0\u1ee3c b\u00e1o c\u00e1o?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có những nghiên cứu độ ổn định tăng tốc nào được báo cáo cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 72. Những điều kiện stress nào đã được thử nghiệm, như nhiệt, độ ẩm và ánh sáng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:28
- Finished: 2026-03-29T18:48:29
- Elapsed seconds: 1.0302
- Retrieval seconds: 0.1337
- Generation seconds: 0.0598
- Estimated prompt tokens: 232
- Estimated answer tokens: 345

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng \u0111i\u1ec1u ki\u1ec7n stress n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c th\u1eed nghi\u1ec7m, nh\u01b0 nhi\u1ec7t, \u0111\u1ed9 \u1ea9m v\u00e0 \u00e1nh s\u00e1ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những điều kiện stress nào đã được thử nghiệm, như nhiệt, độ ẩm và ánh sáng cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 73. Có những thay đổi nào xảy ra khi phơi sáng hoặc trong thử nghiệm độ bền ánh sáng?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:29
- Finished: 2026-03-29T18:48:29
- Elapsed seconds: 0.8298
- Retrieval seconds: 0.1217
- Generation seconds: 0.0525
- Estimated prompt tokens: 233
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nh\u1eefng thay \u0111\u1ed5i n\u00e0o x\u1ea3y ra khi ph\u01a1i s\u00e1ng ho\u1eb7c trong th\u1eed nghi\u1ec7m \u0111\u1ed9 b\u1ec1n \u00e1nh s\u00e1ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có những thay đổi nào xảy ra khi phơi sáng hoặc trong thử nghiệm độ bền ánh sáng cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 74. Có nguy cơ phân hủy đáng chú ý hoặc thay đổi cảm quan nào không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:29
- Finished: 2026-03-29T18:48:30
- Elapsed seconds: 0.7792
- Retrieval seconds: 0.1394
- Generation seconds: 0.0656
- Estimated prompt tokens: 229
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 nguy c\u01a1 ph\u00e2n h\u1ee7y \u0111\u00e1ng ch\u00fa \u00fd ho\u1eb7c thay \u0111\u1ed5i c\u1ea3m quan n\u00e0o kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có nguy cơ phân hủy đáng chú ý hoặc thay đổi cảm quan nào không cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 75. Điều kiện bảo quản và hạn dùng được khuyến cáo là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:29
- Finished: 2026-03-29T18:48:30
- Elapsed seconds: 0.7446
- Retrieval seconds: 0.1257
- Generation seconds: 0.0422
- Estimated prompt tokens: 226
- Estimated answer tokens: 344

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "\u0110i\u1ec1u ki\u1ec7n b\u1ea3o qu\u1ea3n v\u00e0 h\u1ea1n d\u00f9ng \u0111\u01b0\u1ee3c khuy\u1ebfn c\u00e1o l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Điều kiện bảo quản và hạn dùng được khuyến cáo là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 76. Có dữ liệu về độ ổn định sau hoàn nguyên hoặc sau pha chế không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:29
- Finished: 2026-03-29T18:48:30
- Elapsed seconds: 0.9802
- Retrieval seconds: 0.1246
- Generation seconds: 0.3018
- Estimated prompt tokens: 229
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 d\u1eef li\u1ec7u v\u1ec1 \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh sau ho\u00e0n nguy\u00ean ho\u1eb7c sau pha ch\u1ebf kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có dữ liệu về độ ổn định sau hoàn nguyên hoặc sau pha chế không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 77. Tóm tắt độ ổn định, bảo quản và các thận trọng liên quan đến bao bì.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C3. Độ ổn định
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:29
- Finished: 2026-03-29T18:48:30
- Elapsed seconds: 1.0072
- Retrieval seconds: 0.1594
- Generation seconds: 0.0361
- Estimated prompt tokens: 291
- Estimated answer tokens: 426

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft \u0111\u1ed9 \u1ed5n \u0111\u1ecbnh, b\u1ea3o qu\u1ea3n v\u00e0 c\u00e1c th\u1eadn tr\u1ecdng li\u00ean quan \u0111\u1ebfn bao b\u00ec." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt độ ổn định, bảo quản và các thận trọng liên quan đến bao bì. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.5644
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 78. Tóm tắt Kế hoạch Quản lý Nguy cơ (RMP) của thuốc này.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:30
- Finished: 2026-03-29T18:48:31
- Elapsed seconds: 0.9695
- Retrieval seconds: 0.1404
- Generation seconds: 0.0284
- Estimated prompt tokens: 1076
- Estimated answer tokens: 565

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft K\u1ebf ho\u1ea1ch Qu\u1ea3n l\u00fd Nguy c\u01a1 (RMP) c\u1ee7a thu\u1ed1c n\u00e0y." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt Kế hoạch Quản lý Nguy cơ (RMP) của thuốc này. cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 79. Những nguy cơ quan trọng đã được xác định trong RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:30
- Finished: 2026-03-29T18:48:31
- Elapsed seconds: 0.9914
- Retrieval seconds: 0.1296
- Generation seconds: 0.0588
- Estimated prompt tokens: 1078
- Estimated answer tokens: 566

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 quan tr\u1ecdng \u0111\u00e3 \u0111\u01b0\u1ee3c x\u00e1c \u0111\u1ecbnh trong RMP l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những nguy cơ quan trọng đã được xác định trong RMP là gì cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 80. Những nguy cơ tiềm ẩn quan trọng trong RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:30
- Finished: 2026-03-29T18:48:31
- Elapsed seconds: 0.7396
- Retrieval seconds: 0.1363
- Generation seconds: 0.0505
- Estimated prompt tokens: 1075
- Estimated answer tokens: 564

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 ti\u1ec1m \u1ea9n quan tr\u1ecdng trong RMP l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những nguy cơ tiềm ẩn quan trọng trong RMP là gì cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 81. Những thông tin còn thiếu quan trọng nào được liệt kê trong RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:30
- Finished: 2026-03-29T18:48:31
- Elapsed seconds: 0.7316
- Retrieval seconds: 0.1335
- Generation seconds: 0.0514
- Estimated prompt tokens: 1079
- Estimated answer tokens: 568

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00f4ng tin c\u00f2n thi\u1ebfu quan tr\u1ecdng n\u00e0o \u0111\u01b0\u1ee3c li\u1ec7t k\u00ea trong RMP?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thông tin còn thiếu quan trọng nào được liệt kê trong RMP cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 82. Những hoạt động cảnh giác dược thường quy nào được mô tả trong RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:31
- Finished: 2026-03-29T18:48:31
- Elapsed seconds: 0.7587
- Retrieval seconds: 0.1479
- Generation seconds: 0.0459
- Estimated prompt tokens: 1080
- Estimated answer tokens: 568

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng c\u1ea3nh gi\u00e1c d\u01b0\u1ee3c th\u01b0\u1eddng quy n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3 trong RMP?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những hoạt động cảnh giác dược thường quy nào được mô tả trong RMP cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 83. Những hoạt động cảnh giác dược bổ sung nào được mô tả?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:31
- Finished: 2026-03-29T18:48:32
- Elapsed seconds: 0.9835
- Retrieval seconds: 0.2087
- Generation seconds: 0.2072
- Estimated prompt tokens: 226
- Estimated answer tokens: 340

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng c\u1ea3nh gi\u00e1c d\u01b0\u1ee3c b\u1ed5 sung n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những hoạt động cảnh giác dược bổ sung nào được mô tả cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 84. Những hoạt động giảm thiểu nguy cơ thường quy nào được mô tả?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:31
- Finished: 2026-03-29T18:48:32
- Elapsed seconds: 0.948
- Retrieval seconds: 0.1164
- Generation seconds: 0.0336
- Estimated prompt tokens: 228
- Estimated answer tokens: 341

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng ho\u1ea1t \u0111\u1ed9ng gi\u1ea3m thi\u1ec3u nguy c\u01a1 th\u01b0\u1eddng quy n\u00e0o \u0111\u01b0\u1ee3c m\u00f4 t\u1ea3?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những hoạt động giảm thiểu nguy cơ thường quy nào được mô tả cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 85. Những tài liệu giảm thiểu nguy cơ bổ sung nào được lên kế hoạch cho bệnh nhân hoặc nhân viên y tế?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:31
- Finished: 2026-03-29T18:48:32
- Elapsed seconds: 0.9733
- Retrieval seconds: 0.1416
- Generation seconds: 0.0693
- Estimated prompt tokens: 238
- Estimated answer tokens: 350

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng t\u00e0i li\u1ec7u gi\u1ea3m thi\u1ec3u nguy c\u01a1 b\u1ed5 sung n\u00e0o \u0111\u01b0\u1ee3c l\u00ean k\u1ebf ho\u1ea1ch cho b\u1ec7nh nh\u00e2n ho\u1eb7c nh\u00e2n vi\u00ean y t\u1ebf?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những tài liệu giảm thiểu nguy cơ bổ sung nào được lên kế hoạch cho bệnh nhân hoặc nhân viên y tế cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 86. Những vấn đề liên quan đến hiệu quả điều trị nào được đưa vào RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:31
- Finished: 2026-03-29T18:48:32
- Elapsed seconds: 0.972
- Retrieval seconds: 0.1342
- Generation seconds: 0.0559
- Estimated prompt tokens: 1080
- Estimated answer tokens: 568

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng v\u1ea5n \u0111\u1ec1 li\u00ean quan \u0111\u1ebfn hi\u1ec7u qu\u1ea3 \u0111i\u1ec1u tr\u1ecb n\u00e0o \u0111\u01b0\u1ee3c \u0111\u01b0a v\u00e0o RMP?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những vấn đề liên quan đến hiệu quả điều trị nào được đưa vào RMP cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 87. Interview form hoặc RMP nói gì về các nguy cơ liên quan đến RMP?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:32
- Finished: 2026-03-29T18:48:33
- Elapsed seconds: 0.7348
- Retrieval seconds: 0.132
- Generation seconds: 0.0506
- Estimated prompt tokens: 1237
- Estimated answer tokens: 561

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Interview form ho\u1eb7c RMP n\u00f3i g\u00ec v\u1ec1 c\u00e1c nguy c\u01a1 li\u00ean quan \u0111\u1ebfn RMP?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Interview form hoặc RMP nói gì về các nguy cơ liên quan đến RMP cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.7744
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.4300
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.2263
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.1975
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 415 | mục=rmp | điểm=7.0990
  Thành phần hoạt chất:
  Phương pháp bảo quản:
  20.1 Tránh đóng băng.
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 415
- Keytruda / interview_form / trang 291
```

## 88. Những nguy cơ quan trọng đã xác định và nguy cơ tiềm ẩn trong các tài liệu RMP là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:32
- Finished: 2026-03-29T18:48:33
- Elapsed seconds: 0.7601
- Retrieval seconds: 0.1467
- Generation seconds: 0.0277
- Estimated prompt tokens: 1084
- Estimated answer tokens: 573

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng nguy c\u01a1 quan tr\u1ecdng \u0111\u00e3 x\u00e1c \u0111\u1ecbnh v\u00e0 nguy c\u01a1 ti\u1ec1m \u1ea9n trong c\u00e1c t\u00e0i li\u1ec7u RMP l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những nguy cơ quan trọng đã xác định và nguy cơ tiềm ẩn trong các tài liệu RMP là gì cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 89. Tóm tắt toàn bộ RMP bao gồm nguy cơ, theo dõi và các biện pháp giảm thiểu nguy cơ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > C. PK / độ ổn định / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:32
- Finished: 2026-03-29T18:48:33
- Elapsed seconds: 0.6986
- Retrieval seconds: 0.1262
- Generation seconds: 0.024
- Estimated prompt tokens: 1084
- Estimated answer tokens: 572

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft to\u00e0n b\u1ed9 RMP bao g\u1ed3m nguy c\u01a1, theo d\u00f5i v\u00e0 c\u00e1c bi\u1ec7n ph\u00e1p gi\u1ea3m thi\u1ec3u nguy c\u01a1." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt toàn bộ RMP bao gồm nguy cơ, theo dõi và các biện pháp giảm thiểu nguy cơ. cho keytruda.
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: rmp

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 437 | mục=rmp | điểm=7.4396
  Các tài liệu liên quan khác
  (1) Không áp dụng cho việc nghiền
  <Trang thông tin hướng dẫn khuyến mãi sử dụng tối ưu>
- Keytruda | interview_form | trang 4 | mục=rmp | điểm=7.0973
  Các mục liên quan đến an toàn (phòng ngừa, v.v.) 246
  Chi tiết và lý do cảnh báo.................................
  Chống chỉ định và nguyên nhân.................................
- Keytruda | interview_form | trang 30 | mục=rmp | điểm=7.0928
  Tổng quan về các cân nhắc về an toàn trong Kế hoạch quản lý rủi ro dược phẩm (RMP)
  Không có Cân nhắc về hiệu quả/Hiệu quả ở bệnh nhân có khối u rắn tiến triển/tái phát có TMB-High sau hóa trị ung thư trong điều kiện sử dụng thực tế ↓ Các hoạt động giám sát an toàn dựa trên những điều trên ↓ Các hoạt động giảm thiểu rủi ro dựa trên những điều trên Tổng quan về kế hoạch giám sát an toàn thuốc
  [Rủi ro tiềm ẩn quan trọng]
- Keytruda | interview_form | trang 26 | mục=rmp | điểm=7.0567
  Khả năng dung nạp, độ an toàn và hiệu quả của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và cisplatin) đã được nghiên cứu ở 19 bệnh nhân bị u trung biểu mô màng phổi ác tính tái phát.
  Hiệu quả và độ an toàn của liệu pháp kết hợp thuốc này và hóa trị liệu (pemeterxed natri và bạch kim) đã được nghiên cứu ở những bệnh nhân bị u trung biểu mô màng phổi ác tính (440 bệnh nhân được đưa vào phân tích hiệu quả pha III và 473 bệnh nhân được đưa vào phân tích an toàn pha II/III).
  Dược tính của sản phẩm
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay

Nguồn:
- Keytruda / interview_form / trang 437
- Keytruda / interview_form / trang 4
- Keytruda / interview_form / trang 30
- Keytruda / interview_form / trang 26
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
```

## 90. Những thay đổi nhãn an toàn gần đây nào có nhắc đến thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:32
- Finished: 2026-03-29T18:48:33
- Elapsed seconds: 0.9486
- Retrieval seconds: 0.2097
- Generation seconds: 0.2333
- Estimated prompt tokens: 228
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng thay \u0111\u1ed5i nh\u00e3n an to\u00e0n g\u1ea7n \u0111\u00e2y n\u00e0o c\u00f3 nh\u1eafc \u0111\u1ebfn thu\u1ed1c n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thay đổi nhãn an toàn gần đây nào có nhắc đến thuốc này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 91. Những cập nhật an toàn mới nào đã được ban hành cho thuốc này?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:33
- Finished: 2026-03-29T18:48:33
- Elapsed seconds: 0.9138
- Retrieval seconds: 0.1082
- Generation seconds: 0.034
- Estimated prompt tokens: 228
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng c\u1eadp nh\u1eadt an to\u00e0n m\u1edbi n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c ban h\u00e0nh cho thu\u1ed1c n\u00e0y?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những cập nhật an toàn mới nào đã được ban hành cho thuốc này cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 92. Có cảnh báo an toàn nào về viêm gan tối cấp, phản ứng da nặng hoặc viêm phổi kẽ không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:33
- Finished: 2026-03-29T18:48:34
- Elapsed seconds: 0.8849
- Retrieval seconds: 0.1124
- Generation seconds: 0.033
- Estimated prompt tokens: 386
- Estimated answer tokens: 529

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o an to\u00e0n n\u00e0o v\u1ec1 vi\u00eam gan t\u1ed1i c\u1ea5p, ph\u1ea3n \u1ee9ng da n\u1eb7ng ho\u1eb7c vi\u00eam ph\u1ed5i k\u1ebd kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo an toàn nào về viêm gan tối cấp, phản ứng da nặng hoặc viêm phổi kẽ không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 93. Có cảnh báo về phản ứng da nặng trong các thông báo an toàn gần đây không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:33
- Finished: 2026-03-29T18:48:34
- Elapsed seconds: 0.9238
- Retrieval seconds: 0.1353
- Generation seconds: 0.0542
- Estimated prompt tokens: 383
- Estimated answer tokens: 526

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o v\u1ec1 ph\u1ea3n \u1ee9ng da n\u1eb7ng trong c\u00e1c th\u00f4ng b\u00e1o an to\u00e0n g\u1ea7n \u0111\u00e2y kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo về phản ứng da nặng trong các thông báo an toàn gần đây không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 94. Những thông báo an toàn nào nhắc đến rối loạn chức năng gan hoặc viêm gan?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:33
- Finished: 2026-03-29T18:48:34
- Elapsed seconds: 0.7452
- Retrieval seconds: 0.1958
- Generation seconds: 0.0622
- Estimated prompt tokens: 232
- Estimated answer tokens: 344

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng th\u00f4ng b\u00e1o an to\u00e0n n\u00e0o nh\u1eafc \u0111\u1ebfn r\u1ed1i lo\u1ea1n ch\u1ee9c n\u0103ng gan ho\u1eb7c vi\u00eam gan?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Những thông báo an toàn nào nhắc đến rối loạn chức năng gan hoặc viêm gan cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 95. Có cảnh báo nào liên quan đến mang thai, nguy cơ với thai nhi hoặc thiểu ối không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:33
- Finished: 2026-03-29T18:48:34
- Elapsed seconds: 0.8026
- Retrieval seconds: 0.1453
- Generation seconds: 0.058
- Estimated prompt tokens: 511
- Estimated answer tokens: 474

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn mang thai, nguy c\u01a1 v\u1edbi thai nhi ho\u1eb7c thi\u1ec3u \u1ed1i kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến mang thai, nguy cơ với thai nhi hoặc thiểu ối không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 435 | mục=pregnancy | điểm=6.9890
  Tư vấn cho phụ nữ mang thai về nguy cơ tiềm ẩn đối với thai nhi.
  Không có dữ liệu sẵn có trên người cho biết nguy cơ gây độc cho phôi thai.
  Trong dân số Hoa Kỳ nói chung, nguy cơ cơ bản ước tính về dị tật bẩm sinh nghiêm trọng và sẩy thai ở
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / interview_form / trang 435
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 96. Có cảnh báo nào về tái hoạt HBV hoặc nguy cơ miễn dịch không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:34
- Finished: 2026-03-29T18:48:34
- Elapsed seconds: 0.8501
- Retrieval seconds: 0.145
- Generation seconds: 0.0491
- Estimated prompt tokens: 380
- Estimated answer tokens: 523

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 t\u00e1i ho\u1ea1t HBV ho\u1eb7c nguy c\u01a1 mi\u1ec5n d\u1ecbch kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về tái hoạt HBV hoặc nguy cơ miễn dịch không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 97. Có cảnh báo nào liên quan đến chuyển hóa như nguy cơ ở người chuyển hóa cực nhanh CYP2D6 không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > D. Câu hỏi về thông báo an toàn / theo dõi tín hiệu
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:34
- Finished: 2026-03-29T18:48:35
- Elapsed seconds: 1.1967
- Retrieval seconds: 0.3055
- Generation seconds: 0.2292
- Estimated prompt tokens: 388
- Estimated answer tokens: 532

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn chuy\u1ec3n h\u00f3a nh\u01b0 nguy c\u01a1 \u1edf ng\u01b0\u1eddi chuy\u1ec3n h\u00f3a c\u1ef1c nhanh CYP2D6 kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến chuyển hóa như nguy cơ ở người chuyển hóa cực nhanh CYP2D6 không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 98. Có cảnh báo nào về rối loạn chức năng tuyến giáp hoặc hấp thu iod toàn thân không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > E. Bộ ví dụ Povidone-iodine
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:34
- Finished: 2026-03-29T18:48:35
- Elapsed seconds: 1.1006
- Retrieval seconds: 0.1229
- Generation seconds: 0.0381
- Estimated prompt tokens: 516
- Estimated answer tokens: 636

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o v\u1ec1 r\u1ed1i lo\u1ea1n ch\u1ee9c n\u0103ng tuy\u1ebfn gi\u00e1p ho\u1eb7c h\u1ea5p thu iod to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào về rối loạn chức năng tuyến giáp hoặc hấp thu iod toàn thân không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.6859
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.5163
  Rối loạn chức năng gan và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan định kỳ (đặc biệt thường xuyên khi dùng chung với axitinib) và cần theo dõi cẩn thận tình trạng của bệnh nhân.
  Viêm gan tối cấp, suy gan, rối loạn chức năng gan và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan định kỳ (đặc biệt thường xuyên khi dùng chung với axitinib) và cần theo dõi cẩn thận tình trạng của bệnh nhân.
  (Hướng dẫn nhập cảnh mới)]
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm

Nguồn:
- Keytruda / safety_notice / trang 1
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 99. Có thận trọng nào liên quan đến công thức cho phụ nữ mang thai hoặc cho con bú không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > F. Các bộ smoke test giá trị cao > F1. Bộ tối thiểu 10 câu hỏi về công thức / an toàn
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:34
- Finished: 2026-03-29T18:48:35
- Elapsed seconds: 1.0809
- Retrieval seconds: 0.1484
- Generation seconds: 0.0376
- Estimated prompt tokens: 512
- Estimated answer tokens: 475

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 th\u1eadn tr\u1ecdng n\u00e0o li\u00ean quan \u0111\u1ebfn c\u00f4ng th\u1ee9c cho ph\u1ee5 n\u1eef mang thai ho\u1eb7c cho con b\u00fa kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có thận trọng nào liên quan đến công thức cho phụ nữ mang thai hoặc cho con bú không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning, pregnancy

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 435 | mục=pregnancy | điểm=6.9890
  Tư vấn cho phụ nữ mang thai về nguy cơ tiềm ẩn đối với thai nhi.
  Không có dữ liệu sẵn có trên người cho biết nguy cơ gây độc cho phôi thai.
  Trong dân số Hoa Kỳ nói chung, nguy cơ cơ bản ước tính về dị tật bẩm sinh nghiêm trọng và sẩy thai ở
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / interview_form / trang 435
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 100. Có cảnh báo nào liên quan đến rối loạn tuyến giáp hoặc hấp thu toàn thân không?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > F. Các bộ smoke test giá trị cao > F1. Bộ tối thiểu 10 câu hỏi về công thức / an toàn
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:34
- Finished: 2026-03-29T18:48:36
- Elapsed seconds: 1.098
- Retrieval seconds: 0.1516
- Generation seconds: 0.0598
- Estimated prompt tokens: 516
- Estimated answer tokens: 635

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00f3 c\u1ea3nh b\u00e1o n\u00e0o li\u00ean quan \u0111\u1ebfn r\u1ed1i lo\u1ea1n tuy\u1ebfn gi\u00e1p ho\u1eb7c h\u1ea5p thu to\u00e0n th\u00e2n kh\u00f4ng?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Có cảnh báo nào liên quan đến rối loạn tuyến giáp hoặc hấp thu toàn thân không cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.6859
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.5163
  Rối loạn chức năng gan và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan định kỳ (đặc biệt thường xuyên khi dùng chung với axitinib) và cần theo dõi cẩn thận tình trạng của bệnh nhân.
  Viêm gan tối cấp, suy gan, rối loạn chức năng gan và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan định kỳ (đặc biệt thường xuyên khi dùng chung với axitinib) và cần theo dõi cẩn thận tình trạng của bệnh nhân.
  (Hướng dẫn nhập cảnh mới)]
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm

Nguồn:
- Keytruda / safety_notice / trang 1
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 101. Hiển thị bằng chứng từ phần contraindications section.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:35
- Finished: 2026-03-29T18:48:36
- Elapsed seconds: 0.7543
- Retrieval seconds: 0.129
- Generation seconds: 0.0628
- Estimated prompt tokens: 226
- Estimated answer tokens: 302

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n contraindications section." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Các chống chỉ định hoặc đối tượng không nên dùng keytruda là gì?
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.5644
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.5644
  vết thương chảy máu
  Lượng máu chảy giảm
  Huyết áp bất thường

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 102. Hiển thị bằng chứng từ phần warnings section.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:35
- Finished: 2026-03-29T18:48:36
- Elapsed seconds: 0.7975
- Retrieval seconds: 0.1397
- Generation seconds: 0.0641
- Estimated prompt tokens: 285
- Estimated answer tokens: 415

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng t\u1eeb ph\u1ea7n warnings section." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Các cảnh báo và thận trọng khi dùng keytruda là gì?
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6299
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.5644
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.5644
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.5644
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.5644
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 103. Trả lời kèm trích dẫn và hiển thị chính xác số trang tham chiếu.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:35
- Finished: 2026-03-29T18:48:36
- Elapsed seconds: 0.8281
- Retrieval seconds: 0.1428
- Generation seconds: 0.0726
- Estimated prompt tokens: 229
- Estimated answer tokens: 342

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Tr\u1ea3 l\u1eddi k\u00e8m tr\u00edch d\u1eabn v\u00e0 hi\u1ec3n th\u1ecb ch\u00ednh x\u00e1c s\u1ed1 trang tham chi\u1ebfu." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Trả lời kèm trích dẫn và hiển thị chính xác số trang tham chiếu. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 104. Hiển thị bằng chứng hỗ trợ và các file trang nguồn cho câu trả lời PK.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:36
- Finished: 2026-03-29T18:48:37
- Elapsed seconds: 1.1649
- Retrieval seconds: 0.2715
- Generation seconds: 0.2765
- Estimated prompt tokens: 236
- Estimated answer tokens: 346

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Hi\u1ec3n th\u1ecb b\u1eb1ng ch\u1ee9ng h\u1ed7 tr\u1ee3 v\u00e0 c\u00e1c file trang ngu\u1ed3n cho c\u00e2u tr\u1ea3 l\u1eddi PK." --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Các dữ liệu dược động học chính của keytruda là gì?
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.8877
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.7683
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```

## 105. Những trang nào đã được dùng để trả lời câu hỏi về stability?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > G. Kiểm thử truy hồi / điều hướng / tiêu đề mục / xác thực provenance
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:36
- Finished: 2026-03-29T18:48:37
- Elapsed seconds: 1.1497
- Retrieval seconds: 0.1409
- Generation seconds: 0.0383
- Estimated prompt tokens: 448
- Estimated answer tokens: 347

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Nh\u1eefng trang n\u00e0o \u0111\u00e3 \u0111\u01b0\u1ee3c d\u00f9ng \u0111\u1ec3 tr\u1ea3 l\u1eddi c\u00e2u h\u1ecfi v\u1ec1 stability?" --drug-name "keytruda" --json
```

### Result

```text
Câu hỏi: Thông tin độ ổn định và điều kiện bảo quản của keytruda là gì?
Bộ lọc thuốc: keytruda
Bộ lọc loại tài liệu: interview_form
Gợi ý mục: stability

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 7 | mục=stability | điểm=7.1039
  Quản lý 2 tuần một lần
  Quản lý 3 tuần một lần
  Quản lý 6 tuần một lần
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=7.0443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu

Nguồn:
- Keytruda / interview_form / trang 7
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 106. Các cảnh báo chính và chống chỉ định của keytruda là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H1. Hồi quy theo dạng câu hỏi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:36
- Finished: 2026-03-29T18:48:37
- Elapsed seconds: 1.1118
- Retrieval seconds: 0.1297
- Generation seconds: 0.0361
- Estimated prompt tokens: 446
- Estimated answer tokens: 318

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "C\u00e1c c\u1ea3nh b\u00e1o ch\u00ednh v\u00e0 ch\u1ed1ng ch\u1ec9 \u0111\u1ecbnh c\u1ee7a keytruda l\u00e0 g\u00ec?" --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Các cảnh báo chính và chống chỉ định của keytruda là gì cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: contraindication, indication, warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | safety_notice | trang 6 | mục=indication | điểm=7.0979
  Nó đã được bắt đầu vào năm.
  Nó đã được thực hiện từ năm 2011.
  1.2.2 Về ung thư vú (1.1 (ii) ở trên)
- Keytruda | interview_form | trang 291 | mục=general | điểm=7.0892
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=7.0892
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=7.0892
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=7.0892
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường
- Keytruda | interview_form | trang 348 | mục=general | điểm=7.0892
  Lượng máu chảy giảm
  Giảm bicarbonate máu
  Tăng bicarbonate máu

Nguồn:
- Keytruda / safety_notice / trang 6
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
```

## 107. Hãy tóm tắt hồ sơ dược động học chi tiết bao gồm hấp thu, chuyển hóa và thải trừ.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H1. Hồi quy theo dạng câu hỏi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:36
- Finished: 2026-03-29T18:48:37
- Elapsed seconds: 1.1275
- Retrieval seconds: 0.1724
- Generation seconds: 0.0586
- Estimated prompt tokens: 284
- Estimated answer tokens: 360

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "H\u00e3y t\u00f3m t\u1eaft h\u1ed3 s\u01a1 d\u01b0\u1ee3c \u0111\u1ed9ng h\u1ecdc chi ti\u1ebft bao g\u1ed3m h\u1ea5p thu, chuy\u1ec3n h\u00f3a v\u00e0 th\u1ea3i tr\u1eeb." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Hãy tóm tắt hồ sơ dược động học chi tiết bao gồm hấp thu, chuyển hóa và thải trừ. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: pk

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 354 | mục=pk | điểm=8.0040
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  tăng trưởng còi cọc
  rối loạn thăng bằng
- Keytruda | interview_form | trang 332 | mục=pk | điểm=7.0176
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  rối loạn chuyển hóa
  viêm thận miễn dịch
- Keytruda | smpc_label | trang 39 | mục=pk | điểm=6.4719
  khoảng thời gian 6 tuần
  Không TMB-Cao mà không có MSI-Cao
  Tiêu chí đánh giá RECISTResponse trong khối u rắn Đánh giá hiệu quả điều trị đối với khối u rắn
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 354
- Keytruda / interview_form / trang 332
- Keytruda / smpc_label / trang 39
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 108. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H2. Hồi quy theo tham số truy hồi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:37
- Finished: 2026-03-29T18:48:37
- Elapsed seconds: 0.7438
- Retrieval seconds: 0.1311
- Generation seconds: 0.0341
- Estimated prompt tokens: 150
- Estimated answer tokens: 180

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "keytruda" --top-k 3
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
```

## 109. Hoạt chất và tá dược là gì?

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H2. Hồi quy theo tham số truy hồi
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:37
- Finished: 2026-03-29T18:48:38
- Elapsed seconds: 0.7591
- Retrieval seconds: 0.1346
- Generation seconds: 0.0609
- Estimated prompt tokens: 264
- Estimated answer tokens: 333

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "Ho\u1ea1t ch\u1ea5t v\u00e0 t\u00e1 d\u01b0\u1ee3c l\u00e0 g\u00ec?" --drug-name "keytruda" --top-k 8
```

### Result

```text
Câu hỏi: Hoạt chất và tá dược là gì cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 110. Tóm tắt tất cả các nguy cơ chính.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H3. Stress test / kiểm thử so sánh
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:37
- Finished: 2026-03-29T18:48:38
- Elapsed seconds: 0.7392
- Retrieval seconds: 0.1139
- Generation seconds: 0.0303
- Estimated prompt tokens: 221
- Estimated answer tokens: 334

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "T\u00f3m t\u1eaft t\u1ea5t c\u1ea3 c\u00e1c nguy c\u01a1 ch\u00ednh." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: Tóm tắt tất cả các nguy cơ chính. cho keytruda.
Bộ lọc thuốc: keytruda

Bằng chứng truy xuất hàng đầu:
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  bệnh thận nhiễm độc
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  viêm khớp miễn dịch
  khó chịu ở chân tay
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  chảy máu trực tràng
  Tình trạng suy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  khó chịu ở chân tay
  rối loạn thăng bằng
- Keytruda | interview_form | trang 348 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  Lượng máu chảy giảm
  Giảm bicarbonate máu
- Keytruda | interview_form | trang 358 | mục=general | điểm=6.4242
  Các mục liên quan đến an toàn (phòng ngừa, v.v.)
  vết thương chảy máu
  Lượng máu chảy giảm

Nguồn:
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
- Keytruda / interview_form / trang 348
- Keytruda / interview_form / trang 358
```

## 111. So sánh các cảnh báo của alprazolam và abaloparatide.

- Phase: non_ollama
- Section: PMDA_RAG_Reusable_Question_Bank_vi > H. Kiểm thử độ bền / hồi quy / stress test > H3. Stress test / kiểm thử so sánh
- Generator: none
- Success: Yes
- Started: 2026-03-29T18:48:37
- Finished: 2026-03-29T18:48:38
- Elapsed seconds: 0.6451
- Retrieval seconds: 0.1103
- Generation seconds: 0.0268
- Estimated prompt tokens: 378
- Estimated answer tokens: 521

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA_v1_vi\\pmda_fs_index_vi" "So s\u00e1nh c\u00e1c c\u1ea3nh b\u00e1o c\u1ee7a alprazolam v\u00e0 abaloparatide." --drug-name "keytruda"
```

### Result

```text
Câu hỏi: So sánh các cảnh báo của alprazolam và abaloparatide. cho keytruda.
Bộ lọc thuốc: keytruda
Gợi ý mục: warning

Bằng chứng truy xuất hàng đầu:
- Keytruda | smpc_label | trang 9 | mục=warning | điểm=6.6089
  [Xem phần "Cảnh báo", "Thận trọng liên quan đến liều lượng và cách dùng", "Thận trọng đối với bệnh nhân có hoàn cảnh cụ thể" và "Phản ứng bất lợi"] Số trường hợp (tỷ lệ mắc)
  Ngoài ra, các tác dụng phụ nghiêm trọng có thể xảy ra sau khi dùng thuốc này, vì vậy bệnh nhân cần được theo dõi cẩn thận ngay cả sau khi dùng thuốc này.
  Bệnh nhân cần được theo dõi cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào thì nên thực hiện chẩn đoán phân biệt thích hợp, có tính đến khả năng xảy ra tác dụng phụ do phản ứng miễn dịch quá mức gây ra.
- Keytruda | safety_notice | trang 1 | mục=warning | điểm=6.4708
  và viêm đường mật xơ cứng có thể xảy ra, vì vậy cần thực hiện xét nghiệm chức năng gan thường xuyên và tình trạng của bệnh nhân cần được theo dõi cẩn thận."
  Rối loạn chức năng gan kèm theo tăng AST (GOT), ALT (GPT), γ-GTP, Al-P, bilirubin, v.v., có thể xảy ra viêm gan và viêm đường mật xơ cứng, vì vậy hãy theo dõi bệnh nhân cẩn thận và nếu quan sát thấy bất kỳ dấu hiệu bất thường nào, hãy thực hiện các biện pháp thích hợp như ngừng sử dụng thuốc này.
  Tôi sẽ đổi nó thành.
- Keytruda | interview_form | trang 291 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  bệnh thận nhiễm độc
  bệnh phổi miễn dịch
- Keytruda | interview_form | trang 299 | mục=general | điểm=6.4443
  viêm khớp miễn dịch
  khó chịu ở chân tay
  Bệnh gamma đơn dòng
- Keytruda | interview_form | trang 310 | mục=general | điểm=6.4443
  chảy máu trực tràng
  Tình trạng suy giảm
  Lượng máu chảy giảm
- Keytruda | interview_form | trang 336 | mục=general | điểm=6.4443
  khó chịu ở chân tay
  rối loạn thăng bằng
  cảm giác bất thường

Nguồn:
- Keytruda / smpc_label / trang 9
- Keytruda / safety_notice / trang 1
- Keytruda / interview_form / trang 291
- Keytruda / interview_form / trang 299
- Keytruda / interview_form / trang 310
- Keytruda / interview_form / trang 336
```
