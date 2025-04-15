# IT3120-PTTKHT - Discord clone

## Danh sách các Microservices trong Hệ thống Chat

| STT | Tên Service           | Vai trò chính                                                               |
| --- | --------------------- | --------------------------------------------------------------------------- |
| 1   | **Auth Service**      | Xử lý đăng ký, đăng nhập, refresh token, xác thực JWT                       |
| 2   | **User Service**      | Lưu thông tin người dùng (username, avatar,...), quản lý profile            |
| 3   | **Message Service**   | Lưu và truy xuất tin nhắn, kiểm tra quyền gửi, phân loại message            |
| 4   | **WebSocket Service** | Kết nối realtime, nhận và phát tin nhắn tới các client                      |
| 5   | **Friend Service**    | Gửi/nhận lời mời kết bạn, chấp nhận, block, danh sách bạn bè                |
| 6   | **Channel Service**   | Quản lý các channel trong server, phân quyền channel                        |
| 7   | **Server Service**    | Quản lý server (tạo, mời người, phân quyền trong server)                    |
| 8   | **Bot Service**       | Xử lý các command từ người dùng, phản hồi tự động (ví dụ: `/help`)          |
| 9   | **Billing Service**   | Quản lý thanh toán, subscription, premium features                          |
| 10  | **API Gateway**       | Cổng vào duy nhất, route request, xử lý xác thực, logging, rate limiting... |
