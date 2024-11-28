
# Hướng dẫn thêm ví whitelist rút tiền trên HashKey Exchange

Việc thêm ví whitelist để rút tiền trên HashKey Exchange giúp đảm bảo an toàn cho tài khoản của bạn và chỉ cho phép rút tiền về các địa chỉ đã được xác nhận trước đó. Dưới đây là hướng dẫn chi tiết các bước thực hiện:

---

## Bước 1: Đăng nhập vào tài khoản HashKey Exchange
1. Truy cập trang web của [HashKey Exchange]([https://global.hashkey.com/en-US/register/invite?invite_code=JMdixq]).
2. Nhập thông tin tài khoản (email/số điện thoại và mật khẩu) để đăng nhập.
3. Hoàn tất xác minh 2FA (Two-Factor Authentication) nếu được yêu cầu.

---

## Bước 2: Truy cập mục quản lý ví whitelist
1. Sau khi đăng nhập, vào phần **[Wallet]** (Ví) trên thanh điều hướng.
2. Chọn **[Withdrawal Address Management]** (Quản lý địa chỉ rút tiền).
3. Tại đây, bạn sẽ thấy danh sách các địa chỉ whitelist (nếu có) hoặc mục để thêm địa chỉ mới.

---

## Bước 3: Thêm địa chỉ ví mới
1. Nhấp vào nút **[Add Address]** (Thêm địa chỉ).
2. Điền thông tin yêu cầu:
   - **Coin/Token**: Chọn loại tài sản muốn rút (BTC, ETH, USDT, v.v.).
   - **Network**: Chọn mạng lưới tương ứng với tài sản (Ví dụ: ERC-20, BEP-20, TRC-20).
   - **Wallet Address**: Nhập địa chỉ ví cá nhân mà bạn muốn thêm.
   - **Label**: Đặt tên cho địa chỉ này để dễ nhận diện (Ví dụ: Ví cá nhân, Ví giao dịch, v.v.).
3. Kiểm tra kỹ thông tin để đảm bảo địa chỉ ví và mạng lưới chính xác.

---

## Bước 4: Xác minh địa chỉ ví
1. Sau khi nhập thông tin, bạn sẽ được yêu cầu xác minh:
   - **Email Verification**: Một email xác nhận sẽ được gửi đến địa chỉ email đã đăng ký của bạn. Mở email và nhấp vào liên kết xác minh.
   - **2FA Authentication**: Nhập mã 2FA từ ứng dụng Google Authenticator hoặc Authy.
2. Sau khi hoàn thành các bước xác minh, địa chỉ ví sẽ được thêm vào danh sách whitelist.

---

## Bước 5: Kiểm tra và sử dụng ví whitelist
1. Truy cập lại mục **[Withdrawal Address Management]** để kiểm tra xem địa chỉ ví đã được thêm thành công chưa.
2. Khi thực hiện rút tiền, bạn chỉ có thể chọn các địa chỉ đã được thêm vào whitelist. Điều này tăng cường bảo mật, ngăn chặn việc chuyển tiền đến các địa chỉ không đáng tin cậy.

---

## Lưu ý quan trọng
- Đảm bảo địa chỉ ví và mạng lưới chính xác để tránh mất tài sản.
- Chỉ thêm các ví cá nhân mà bạn tin tưởng và kiểm soát.
- Nếu không sử dụng địa chỉ nào trong thời gian dài, hãy xóa nó khỏi danh sách whitelist để đảm bảo an toàn.
- Bất kỳ thay đổi nào đối với địa chỉ whitelist đều yêu cầu xác minh qua email và 2FA.

---

Thực hiện các bước trên sẽ giúp bạn thêm ví whitelist một cách an toàn và hiệu quả trên HashKey Exchange. Nếu có bất kỳ vấn đề gì, liên hệ bộ phận hỗ trợ khách hàng của HashKey để được giúp đỡ.

---

# Hướng dẫn ký Signature bằng MyEtherWallet (MEW) để xác nhận ví whitelist trên HashKey Exchange

Khi thêm ví whitelist trên HashKey Exchange, bạn có thể được yêu cầu ký một thông điệp (signature) bằng ví Ethereum để xác minh quyền sở hữu địa chỉ ví. Dưới đây là hướng dẫn chi tiết cách ký signature bằng MyEtherWallet (MEW):

---

## Bước 1: Truy cập MyEtherWallet
1. Mở trình duyệt và truy cập vào trang chính thức của [MyEtherWallet (MEW)](https://www.myetherwallet.com).
2. Đảm bảo rằng bạn đang sử dụng trang web chính thức để tránh các trang web giả mạo.

---

## Bước 2: Đăng nhập vào ví Ethereum
1. Chọn phương thức đăng nhập phù hợp:
   - **Hardware Wallet (Ledger, Trezor, etc.)**: Nếu bạn sử dụng ví cứng.
   - **Keystore File**: Sử dụng file keystore để đăng nhập.
   - **Mnemonic Phrase**: Sử dụng cụm từ khôi phục (12/24 từ).
   - **Private Key**: Nhập private key nếu không sử dụng các phương pháp trên (không khuyến khích vì lý do bảo mật).
2. Hoàn tất quá trình đăng nhập để truy cập ví của bạn.

---

## Bước 3: Ký Signature
1. Sau khi đăng nhập, trong giao diện ví MEW:
   - Chọn mục **Message Signing** hoặc **Sign Message** (Ký thông điệp).
2. Nhập nội dung thông điệp do HashKey Exchange cung cấp vào ô trống. Thông điệp này thường được hiển thị trên giao diện thêm ví whitelist của HashKey và có thể bao gồm:
   - Địa chỉ ví.
   - Một mã xác nhận hoặc nội dung đặc biệt do sàn cung cấp.
3. Nhấp vào nút **Sign Message** để tiến hành ký.

---

## Bước 4: Sao chép chữ ký (Signature)
1. Sau khi ký thành công, MEW sẽ tạo ra một chuỗi ký tự được gọi là **Signature**.
2. Nhấp vào nút **Copy** để sao chép chuỗi này.

---

## Bước 5: Dán Signature vào HashKey Exchange
1. Quay lại giao diện thêm ví whitelist trên HashKey Exchange.
2. Trong bước xác minh ví, dán chữ ký vừa sao chép vào trường yêu cầu.
3. Nhấp **Submit** (Gửi) để hoàn tất quá trình xác minh.

---

## Lưu ý quan trọng
- **Không chia sẻ Signature với bất kỳ ai khác** ngoài HashKey Exchange để đảm bảo an toàn tài sản của bạn.
- Đảm bảo nội dung thông điệp chính xác như yêu cầu của HashKey trước khi ký.
- Nếu gặp lỗi hoặc có thắc mắc, liên hệ bộ phận hỗ trợ của HashKey để được trợ giúp.

---

Với các bước trên, bạn có thể dễ dàng ký Signature bằng MyEtherWallet (MEW) để hoàn tất xác minh ví whitelist trên HashKey Exchange một cách an toàn và hiệu quả.
