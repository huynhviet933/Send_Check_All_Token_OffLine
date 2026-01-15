# Send_Check_All_Token_OffLine================================================================
          HƯỚNG DẪN SỬ DỤNG DISTRIBUTION TOOL VIP
================================================================

1. CHUẨN BỊ TRƯỚC KHI CHẠY:
- Giải nén file .RAR vào một thư mục riêng (Ví dụ: Desktop\ToolToken).
- Đảm bảo máy tính có kết nối Internet.
- Nếu phần mềm bị trình duyệt hoặc Antivirus chặn, hãy chọn "Keep" hoặc "Allow" (Do tool mã hóa bảo mật nên có thể bị nhận diện nhầm).

2. KÍCH HOẠT BẢN QUYỀN (VĨNH VIỄN 1 MÁY):
- Bước 1: Mở file .exe lên.
- Bước 2: Tại màn hình yêu cầu kích hoạt, bạn sẽ thấy dòng: 
  "Mã Máy (HWID): XXXXX-XXXXX-XXXXX"
- Bước 3: Copy (bôi đen rồi nhấn chuột phải) mã HWID đó và gửi cho Admin.
- Bước 4: Sau khi nhận được Key từ Admin, hãy dán vào Tool và nhấn Enter.
- Sau khi kích hoạt thành công, Tool sẽ tạo file `license.dat`. Đừng xóa file này để không phải nhập lại Key.

3. CẤU HÌNH DỮ LIỆU ĐẦU VÀO:
Trong thư mục tool, bạn cần chuẩn bị các file sau (nếu chưa có hãy tự tạo file .txt):

- Pk.txt: Dán danh sách Private Key của các ví gửi (Mỗi dòng 1 Key).
- Wallet.txt: Dán danh sách địa chỉ ví nhận (Mỗi dòng 1 địa chỉ).
- config.json: Nơi lưu cấu hình mạng (Tool sẽ tự tạo nếu thiếu).

4. CÁC TÍNH NĂNG CHÍNH:
- Option 1 (Send Token): 
  + Nếu có 1 PK và nhiều Wallet -> Tự động chia tiền từ 1 ví ra nhiều ví.
  + Nếu có nhiều PK và nhiều Wallet -> Tự động gửi 1-đối-1 theo thứ tự.
- Option 2 (Check Balance): Kiểm tra số dư của tất cả ví trong Pk.txt và xuất ra file balance.txt.
- Option 3 (Sweep Token): Gom toàn bộ token/coin từ nhiều ví (Pk.txt) về duy nhất 1 địa chỉ đích.

5. LƯU Ý QUAN TRỌNG:
- Số dư: Đảm bảo ví gửi có đủ Coin làm phí gas (Native token như ETH, BNB, v.v.).
- Token mới: Nếu tool chưa có sẵn Token bạn cần, chọn "0. [Add New Token]" rồi dán Contract Address vào.
- Tốc độ: Tool xử lý giao dịch theo tốc độ mạng, không tắt tool khi đang gửi.

================================================================
Mọi thắc mắc và lấy Key kích hoạt vui lòng liên hệ Admin!
