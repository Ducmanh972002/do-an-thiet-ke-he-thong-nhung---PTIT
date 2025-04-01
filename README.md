# do-an-thiet-ke-he-thong-nhung---PTIT
# HỆ THỐNG PHÂN LOẠI QUẢ Sử DỤNG CAMERA AI NHÚNG

## Giới thiệu
Dự án này phát triển một hệ thống phân loại quả sử dụng Camera AI nhúng. Hệ thống có khả năng nhận diện và phân loại các loại quả theo thời gian thực, giúp tự động hóa quá trình kiểm tra và phân loại trong nông nghiệp hoặc công nghiệp thực phẩm.

## Tính năng chính
- Nhận diện và phân loại các loại quả thông qua Camera AI
- Xử lý ảnh bằng mô hình học sâu (Deep Learning)
- Hiển thị kết quả phân loại theo thời gian thực
- Giao diện đơn giản, dễ sử dụng
- Có thể mở rộng để nhận diện nhiều loại quả khác nhau

## Phần cứng sử dụng
- Camera AI nhúng (Ví dụ: Raspberry Pi Camera, Intel Movidius, NVIDIA Jetson Nano)
- Bộ xử lý nhúng (Raspberry Pi, Jetson Nano, ESP32-CAM,...)

## Phần mềm sử dụng
- Python
- OpenCV
- TensorFlow / PyTorch
- Flask (nếu cần giao diện web)

## Cách cài đặt và sử dụng
### 1. Cài đặt thư viện cần thiết
```sh
pip install opencv-python numpy tensorflow flask
```

### 2. Chạy chương trình
```sh
python main.py
```

### 3. Mở giao diện (nếu có giao diện web)
Truy cập trình duyệt tại: `http://localhost:5000`

## Mô hình AI
Mô hình sử dụng mạng CNN được huấn luyện với tập dữ liệu gồm nhiều loại quả khác nhau. Có thể tinh chỉnh mô hình bằng cách thêm dữ liệu và huấn luyện lại.

## Đóng góp
Nếu bạn muốn đóng góp vào dự án, vui lòng tạo một **pull request** hoặc liên hệ qua email.

## Giấy phép
Dự án được phát hành theo giấy phép MIT.

---
**Người thực hiện:** Tên của bạn

