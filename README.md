# 👑 Bài Toán N-Hậu (N-Queens Problem) - Mô Phỏng Trực Quan
Đây là một phần của dự án **AlgoVisualizer**, tập trung vào việc mô phỏng cách thuật toán Quay lui (Backtracking) tìm kiếm lời giải cho bài toán đặt $N$ quân hậu trên bàn cờ $N \times N$.
---
### 📸 Demo Trực Quan (Giao diện dự án)
<img width="1919" height="871" alt="image" src="https://github.com/user-attachments/assets/11b8aa06-b04f-4b5d-9ad9-ece78c15ebef" />
<img width="1916" height="868" alt="image" src="https://github.com/user-attachments/assets/a8c31e9b-f475-4d78-ba94-4c09ac40396c" />
Ngoài ra còn có có 4 mã nguồn tham khảo:
<img width="1919" height="871" alt="image" src="https://github.com/user-attachments/assets/bf021977-8260-4612-b64a-a635c47e8eaa" />
<img width="1919" height="865" alt="image" src="https://github.com/user-attachments/assets/ae69454b-5c98-4f75-b355-00f7d673e537" />
<img width="1919" height="869" alt="image" src="https://github.com/user-attachments/assets/2a991c94-47b0-46ef-a688-b1bd58395b61" />
<img width="1919" height="872" alt="image" src="https://github.com/user-attachments/assets/35af4f71-f319-4082-8e60-5fb14477c145" />

---
### ✨ Tính năng của bản mô phỏng N-Hậu
- [x] **Tùy chỉnh Kích thước (N):** Cho phép thay đổi kích thước bàn cờ (ví dụ: N=10 như trong hình).
- [x] **Điều chỉnh Tốc độ:** Có các mức độ mô phỏng từ **Slow** đến **Rapidly** để dễ dàng quan sát.
- [x] **Nhật ký Giải thuật (Live Log):** Hiển thị chi tiết từng bước thuật toán thực hiện: "Đặt tại...", "Quay lui từ...", giúp hiểu rõ quy trình thử và sai.
- [x] **Trạng thái Real-time:** Hiển thị số bước đã thực hiện.
---
### 🧠 Về Thuật toán Backtracking cho N-Hậu
Thuật toán hoạt động theo nguyên tắc:
1.  **Đặt quân hậu:** Cố gắng đặt một quân hậu vào từng hàng, bắt đầu từ hàng trên cùng.
2.  **Kiểm tra tính hợp lệ:** Trước khi đặt, kiểm tra xem quân hậu mới có bị quân hậu nào đã đặt trước đó tấn công không (cùng cột, cùng đường chéo).
3.  **Quay lui (Backtracking):** Nếu không thể đặt quân hậu ở hàng hiện tại, hoặc đã thử hết các cột mà không tìm được lời giải, thuật toán sẽ quay lại hàng trước đó và di chuyển quân hậu ở hàng đó sang cột tiếp theo.
