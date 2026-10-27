# studio-ai-m1

Kho model cho **Studio AI** (https://yosimura99.github.io/studio-ai/) — ứng dụng chạy offline trong trình duyệt, không API key, không server.
Model được đóng gói lại (trọng số fp16 chia mảnh 45 MB, đồ thị fp32 đi kèm) từ bản ONNX công khai do FaceFusion phát hành; chỉ tải khi người dùng chọn.

| Model | Dung lượng | Giấy phép |
|---|---|---|
| hyperswap_1a_256 | 403 MB | ResearchRAIL-M (FaceFusion HyperSwap) |
| hyperswap_1b_256 | 403 MB | ResearchRAIL-M (FaceFusion HyperSwap) |
| simswap_256 | 110 MB | Phi thương mại (neuralchen/SimSwap) |
| crossface_simswap | 11 MB | theo model ghép đi kèm (FaceFusion) |
| crossface_ghost | 11 MB | theo model ghép đi kèm (FaceFusion) |

Chỉ dùng với ảnh của chính bạn hoặc người đã đồng ý. Không dùng để mạo danh, lừa đảo, hay tạo nội dung khiêu dâm/người chưa thành niên.
Bản quyền model thuộc tác giả gốc; xem giấy phép từng model trước khi dùng cho mục đích khác ngoài cá nhân.
