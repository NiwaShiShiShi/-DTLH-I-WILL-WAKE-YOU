# DTLH [I-WILL-WAKE-YOU]
> Sản phẩm bao gồm: 01 file .weights của model đã train, 01 file .cfg, 01 file .names, 01 file .xslx làm sẵn. Các link đi kèm bao gồm thư mục darknet chứa dữ liệu để train và link colab dùng cho quá trình train model cũng như link các file backup.
1. Thay các vị trí *"Your .cfg", "Your .names", "Your .weights", "Your .xlsx"* ở **IWWYwebcam.py** thành path của các file *yolov3.cfg, yolo.names, yolov3_1800.weights, sample.xlsx*
2. pip install những thư viện openpyxl, numpy, opencv-python để sử dụng
3. Nhấn Esc để thoát chương trình, trong quá trình chương trình đang chạy và trước khi nhấn Esc thì không thể mở file sample.xlsx
---

**1. Link dành cho mục đích kiểm tra việc train**
- Link colab: [Link](https://colab.research.google.com/drive/1rSjvK0XzyQSCPsmd-y84P3yKCEEklz_U?usp=sharing)
- Link các file .weights đã train và backup: [Link](https://drive.google.com/drive/folders/1D2cVzddCFhke6ibS6RRbSR90bcsBe1pI?usp=sharing)
- Link folder darknet (custom model): [Link](https://drive.google.com/drive/folders/1l9GeB9aBHzD73l0AyKSx7YFgwQQOrQnF?usp=sharing)
> darknet là folder có sẵn, tuy nhiên nhóm đã chỉnh sửa/thêm bớt một số file sau đây để phù hợp cho việc custom model:
> - Chỉnh sửa các file: cfg/yolov3.cfg, examples/detector.c
> - Thêm các file: folder data/images, data/label, yolo.names, yolo.data, val.txt, train.txt

**2. Link file cần tải về để chạy chương trình:**
- Link yolov3_1800.weights: [Link](https://drive.google.com/file/d/1-YtTaFOG0f6hLrN_4hSZ_jDSojtbed7G/view?usp=sharing)
