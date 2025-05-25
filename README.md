# 🐾 Image-Based Animal Search (Tìm kiếm ảnh động vật bằng AI)

Dự án Flask giúp người dùng tìm kiếm thông tin động vật dựa trên hình ảnh, sử dụng AI để trích xuất đặc trưng từ ảnh và so khớp với cơ sở dữ liệu. Giao diện nền tối, hỗ trợ quản lý người dùng, bài viết, và phân quyền admin.

---

## 🚀 Chức năng chính

- 📷 Tìm kiếm động vật bằng cách tải ảnh lên
- 🧠 Sử dụng EfficientNetB2 để trích xuất đặc trưng hình ảnh
- 🐍 Flask backend dễ tùy chỉnh
- 👤 Quản lý người dùng (Admin / User)
- ✍️ Quản lý bài viết về động vật
- 🌙 Giao diện nền tối hiện đại

---

## 🖼️ Ảnh minh họa

> 📌 Thay thế đường dẫn dưới đây bằng ảnh thực tế trong thư mục của bạn (ví dụ `static/demo.png`)

![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)
![Giao diện ứng dụng](static/screen/giaodienchinh.png)

---

## 🛠️ Cài đặt và chạy ứng dụng

### Yêu cầu:
- Python 3.8+
- pip
- Git

### Cách cài đặt:

```bash
tải trên github
Tải ứng dụng trên link github: https://github.com/thaibao3214/Image-based-Seekers hoặc link github của nhóm theo github lớp.
Tạo 1 file .env với nội dung:
MONGODB_URI=mongodb+srv://baoboybao:thaibao3214@clustersearchimge.eco6dhq.mongodb.net/clustersearchimge?retryWrites=true&w=majority
 
Bỏ file image_features.pkl vào thư mục data/features/ (vì đây là file mô hình train và nó quá 100 mb nên không thể push lên github) trong link drive: https://drive.google.com/drive/folders/1_kZ7GbcvqtgqWWVt1WaNpe19aoC5TRrJ?usp=sharing
Hoặc có thể tự train mô hình bằng file image_search.py với các thư viện tensorflow trong requirements.txt(tông thư viện khoảng 1.8 GB)
Tiến hành tải python 3.10 về máy (không lỗi chức năng của bản mới cũng như không lỗi thời).
Nên chạy với venv.
Các Lệnh:
+ python3.10 –m venv venv
+ venv/Scripts/activate
+ pip install –r requirements.txt
+ python app.py
