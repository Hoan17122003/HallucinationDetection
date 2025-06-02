# HallucinationDetection
- Using method Hallumeasure for hallucination detection in LLM 

# HallucinationDetection

## Hướng dẫn sử dụng

- Mỗi file `.ipynb` trong thư mục `src` tương ứng với một nhiệm vụ (task) trong bộ dữ liệu RAGtruth. Bạn chỉ cần chạy file notebook phù hợp với nhiệm vụ bạn muốn thực hiện.
- Thư mục `dataset` là nơi chứa bộ dữ liệu RAGtruth. Trong thư mục này sẽ có hai cấu trúc chính:
  - **source_info**: Cung cấp các câu prompt, tri thức và câu hỏi cho từng nhiệm vụ.
  - **response.json**: Chứa các câu trả lời (response) được sinh ra bởi hệ thống RAG nhằm giải quyết các đầu vào từ `source_info`. Trong cấu trúc này, trường `labels` là nhãn đánh dấu các trường hợp ảo giác (hallucination).