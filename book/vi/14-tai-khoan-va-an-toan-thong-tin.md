# 14. Tài khoản và an toàn thông tin

> Bản dịch không chính thức. Bản gốc tiếng Trung là chuẩn. Số, DOI, điều luật giữ nguyên.
> Nhiều quy định dưới đây là của Trung Quốc. Ở Việt Nam: mất điện thoại thì khóa SIM với nhà mạng, báo ngân hàng, bật 2FA.

Ai vào được tài khoản của bạn có thể rút tiền ngay, và dùng tài khoản đó lừa danh bạ của bạn.

### 1. Bật xác thực hai lớp cho email, thanh toán và mạng xã hội; ưu tiên popup trên điện thoại hơn mã SMS
<!-- 成本标签: 钱=0 时间=少 毅力=否 收益=大 口径=金钱 -->
- Chi phí: 0. Mỗi tài khoản mất 2–3 phút, làm một lần.
- Nói thường: Xác thực hai lớp là bước kiểm tra thêm ngoài mật khẩu. Popup trên điện thoại, bấm một cái để xác nhận, chặn hơn 90% lừa đảo chiếm tài khoản. Câu hỏi kiểu “lần trước đăng nhập ở đâu” chỉ chặn khoảng 10%.
- Lợi ích: Google phân tích 350.000 vụ chiếm tài khoản thật. Xác minh trên thiết bị (popup điện thoại hoặc khóa vật lý) chặn hơn 94% vụ lừa đảo và 100% vụ bot thử mật khẩu rò rỉ hàng loạt. Câu hỏi cá nhân chỉ chặn 10% lừa đảo và 73% bot.
- Bằng chứng: A
- Ghi chú: Cùng nghiên cứu: 52% người dùng thật không vào được lần đầu, nhưng 97% cuối cùng vào được. Bật email trước, vì tài khoản khác thường lấy lại mật khẩu qua email.
- Nguồn: Doerfler P, Thomas K, Marincenko M, et al. (2019). Evaluating Login Challenges as a Defense Against Account Takeover. WWW '19. <https://doi.org/10.1145/3308558.3313481>

### 2. Email phải có mật khẩu riêng, không dùng lại chỗ khác
<!-- 成本标签: 钱=0 时间=少 毅力=些 收益=大 口径=金钱 -->
- Chi phí: 0. Cất trong trình quản lý mật khẩu thì không cần nhớ. Khó là bỏ thói dùng một mật khẩu cho mọi trang.
- Nói thường: Mật khẩu bị lộ ở trang khác có thể dùng để vào email. Vào được email thì đặt lại mật khẩu mọi tài khoản gắn email đó.
- Lợi ích: Nhồi mật khẩu rò rỉ là cách tấn công dễ nhất. CISA (Mỹ) khuyên mỗi tài khoản một mật khẩu mạnh, ít nhất 16 ký tự, cất trong trình quản lý mật khẩu.
- Bằng chứng: C
- Ghi chú: Dùng trình quản lý mật khẩu của trình duyệt còn hơn dùng lại một mật khẩu. Đừng lưu mật khẩu trong mục yêu thích WeChat hoặc app ghi chú.
- Nguồn: US CISA. Use Strong Passwords. <https://www.cisa.gov/secure-our-world/use-strong-passwords>

### 3. Khóa màn hình điện thoại và đặt PIN cho SIM
<!-- 成本标签: 钱=0 时间=少 毅力=否 收益=大 口径=金钱 -->
- Chi phí: 0. Đặt một lần.
- Nói thường: SIM nhận mã SMS. Mất máy, người nhặt rút SIM sang máy khác là nhận được mã, rồi đặt lại từng tài khoản. PIN SIM bắt nhập mã khi SIM sang máy khác.
- Lợi ích: Không có PIN SIM thì đường chiếm tài khoản qua SMS vẫn mở. Có PIN thì chặn được đường đó.
- Bằng chứng: C
- Nguồn: xem bản Anh [book/en/14-Accounts-And-Security.md](../en/14-Accounts-And-Security.md), mục 3.

### 4–9. Các mục còn lại
Mất máy, thẻ bị rút trộm, thiết bị đăng nhập, quyền app, nhận diện khuôn mặt, quyền xem và xóa dữ liệu: bản đầy đủ tiếng Anh ở file trên. Quy định nhận diện khuôn mặt dẫn trong sách là lệnh số 19 của Trung Quốc, hiệu lực 1/6/2025 — không phải luật Việt Nam.
