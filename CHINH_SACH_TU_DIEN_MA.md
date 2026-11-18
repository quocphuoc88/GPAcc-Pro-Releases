# Chính sách quyền riêng tư — GPAcc · Tự điền mã xác thực

*Áp dụng cho tiện ích trình duyệt «GPAcc · Tự điền mã xác thực» trên Chrome Web Store và Microsoft Edge Add-ons. Cập nhật: 18/11/2026.*

Tiện ích đọc ảnh mã xác thực (captcha) trên trang bạn đã chọn và điền vào ô mã. Việc đọc mã chạy **ngay trong trình duyệt của bạn**: ảnh mã không được gửi đi đâu.

**Trang tiện ích làm việc.** Tiện ích không chạy trên trang nào cho tới khi bạn tự chỉ: chuột phải vào ảnh mã trên trang đó › «🔑 Tự điền mã cho trang này» › Cho phép. Bạn bỏ trang bất cứ lúc nào ở nút tiện ích trên thanh công cụ. Trên các trang đó, tiện ích chỉ đọc ảnh mã và điền ô mã. Tiện ích không đọc ô tài khoản hay mật khẩu, và không bấm Đăng nhập thay bạn.

**Bản quyền.**
- Khi cài, tiện ích tự tạo một **mã cài đặt** ngẫu nhiên (dạng `TD-XXXX-XXXX-XXXX`). Mã này không lấy từ máy tính, tài khoản hay trình duyệt của bạn.
- Khi bạn **tự bấm** «Dùng thử» hoặc «Xin kích hoạt / Gửi yêu cầu gia hạn» ở trang Bản quyền, tiện ích gửi tới máy chủ bản quyền GPAcc: mã cài đặt, **tên khách / công ty và số điện thoại bạn tự gõ**, cùng số phiên bản tiện ích. Mục đích: mở dùng thử (mỗi số điện thoại được thử một lần), để GPAcc liên hệ bạn và cấp key kích hoạt.
- Sau đó tiện ích định kỳ hỏi máy chủ trạng thái key của **mã cài đặt** (chỉ gửi mã cài đặt), để tự nhận key khi được duyệt, nhận gia hạn hoặc biết key bị thu hồi.
- Máy chủ bản quyền GPAcc chạy trên dịch vụ Google Apps Script và lưu các thông tin trên trong bảng tính Google Sheets riêng của GPAcc.
- Quyền kết nối tới máy chủ này chỉ được xin khi bạn bấm lần đầu. Muốn xóa thông tin bản quyền của bạn trên máy chủ: liên hệ GPAcc.
- Nếu trên cùng trình duyệt có tiện ích «GPAcc · Tiện ích» đã kích hoạt, «Tự điền mã» hỏi tiện ích đó một câu «đã kích hoạt chưa». Câu trả lời chỉ là có / không, không kèm key, tên hay dữ liệu nào khác. Cuộc hỏi này diễn ra ngay trong trình duyệt, không qua mạng.

**Những gì tiện ích không làm.**
- Không gửi ảnh mã, nội dung trang hay bất kỳ dữ liệu nào trên trang bạn mở cho máy chủ của nhà phát triển hay bên thứ ba. Thứ duy nhất gửi về GPAcc là thông tin bản quyền ở mục trên.
- Không thu thập mật khẩu; không đăng nhập hộ; không bấm nút thay bạn.
- Không bán, không chia sẻ dữ liệu; không dùng dữ liệu để xét tín dụng hay cho vay.
- Không dùng công cụ thống kê, theo dõi hay quảng cáo; không tải mã từ xa (bộ đọc mã nằm sẵn trong gói).

**Lưu trữ.** Danh sách trang bạn chọn, kiểu mã từng trang, mã cài đặt và key lưu trong bộ nhớ của trình duyệt trên máy bạn; gỡ tiện ích là xóa hết. Thông tin bản quyền (mã cài đặt, tên, số điện thoại) lưu trên máy chủ bản quyền GPAcc cho tới khi bạn yêu cầu xóa.

**Liên hệ.** Qua địa chỉ email liên hệ hiển thị trên trang của tiện ích ở cửa hàng tiện ích.

---

## Privacy policy — GPAcc · Captcha Auto-fill (English summary)

The extension reads the captcha image on pages you choose and fills the captcha field. Reading happens **inside your browser**; captcha images are never sent anywhere. It works only on pages you explicitly add (right-click the captcha image › «Tự điền mã cho trang này» › Allow), reads only the captcha image and fills only the captcha field, never touches username/password fields and never clicks sign-in.

**Licensing.** The extension generates a random installation code (`TD-XXXX-XXXX-XXXX`) not derived from your computer, account or browser. Only when you click «Try» or «Request activation / renewal» on its License page, it sends that code, the customer/company name and phone number you type, and the extension version to the GPAcc licensing server (Google Apps Script, stored in GPAcc's own Google Sheets) to start a trial (one per phone number), contact you and issue a license key. It then periodically sends only the installation code to receive the key once approved, renewals or revocation. The network permission for this server is requested on your first click. If the «GPAcc · Extension» is installed and activated in the same browser, this extension asks it a yes/no «activated?» question inside the browser (no network, no other data). Contact GPAcc to delete your licensing record.

It sends no captcha images, page content or other page data to the developer or any third party (licensing information above is the only data sent to GPAcc), does not collect passwords, sign in or click for you, does not sell or share data, does not use data for credit or lending decisions, and uses no analytics, tracking, ads or remote code. Settings, chosen pages, installation code and key are stored in your browser and removed when you uninstall the extension. Contact: the contact email shown on the extension's store page.
