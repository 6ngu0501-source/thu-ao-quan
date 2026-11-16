# Thử Áo Quần qua Webcam

App web chạy trên trình duyệt: https://6ngu0501-source.github.io/thu-ao-quan/

## Đang có

- Nhận diện cơ thể ngay trên máy bằng MediaPipe Pose Landmarker (không gửi hình webcam đi đâu).
- Làm mượt chuyển động, dự đoán ngắn khi mất điểm, áo mờ dần khi bám kém.
- Phân tích ảnh áo: xoá nền, tìm thân, đường vai và hai tay áo.
- Thân áo là lưới biến dạng uốn theo vai, cột sống và hông; tay áo xoay theo bắp tay và gập theo cẳng tay.
- Tay đưa ra trước ngực thì cẳng tay và bàn tay hiện đè lên áo.
- Ảnh mặt trước và mặt sau, tự đổi khi quay lưng.
- Chụp ảnh; chế độ AI tạo ảnh mặc thật qua fal.ai (cần khoá riêng, có phí).

## Giới hạn đã biết

- Phần bám theo cơ thể mới được kiểm thử bằng tư thế giả lập và áo vẽ mẫu, chưa đo trên điện thoại thật.
- Chưa có tách vùng cơ thể: tay che áo dựa trên vị trí khớp, nên viền tay chưa sát.
- Quần mới chỉ co giãn theo hông và mắt cá, chưa uốn theo từng chân.
- Một ảnh phẳng không có thông tin mặt bên, nên chỉ hỗ trợ xoay người nhẹ.
- Chưa phải app cài từ App Store / Google Play; bản React Native cần máy Mac và Xcode để dựng.
