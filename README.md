# Dev Tools Collection

Bộ sưu tập các công cụ tiện ích dành cho Developer, chạy trực tiếp trên trình duyệt mà không cần cài đặt server hay backend.

## 🚀 Danh sách công cụ

### 1. Distance Calculator (`distance_calculator.html`)
Công cụ tính khoảng cách giữa hai điểm tọa độ địa lý (Latitude/Longitude).
- **Tính năng:**
  - 🎯 **Chính xác cao:** Tích hợp thư viện **Geolib** để tính toán khoảng cách thực tế (Geodesic distance).
  - ⚡ **Nhập liệu thông minh:** Tự động nhận diện và trích xuất `lat`, `lon` từ chuỗi JSON, Object hoặc text bất kỳ.
  - 📊 **So sánh:** Hiển thị song song kết quả chính xác và kết quả ước lượng (công thức Haversine).
  - 📱 **Giao diện:** Responsive, hiện đại với Tailwind CSS.

## 📦 Hướng dẫn cài đặt & Sử dụng

### Chạy Local (Trên máy tính)
Rất đơn giản, bạn chỉ cần mở file `index.html` bằng trình duyệt web.

1. Clone repo hoặc tải code về.
2. Click đúp vào file `index.html`.
3. Chọn công cụ bạn muốn sử dụng.

### Deploy lên Internet (GitHub Pages)
Repo này đã sẵn sàng để deploy miễn phí lên GitHub Pages:

1. Push code lên GitHub.
2. Vào trang Repo > **Settings** > **Pages**.
3. Tại mục **Build and deployment** > **Branch**, chọn `main` (hoặc `master`) và folder `/` (root).
4. Nhấn **Save**. Link trang web sẽ hiện ra sau vài phút.

## 🛠 Công nghệ
- **Core:** HTML5, JavaScript (Vanilla).
- **Styling:** Tailwind CSS (CDN).
- **Libs:** Geolib (CDN).
