# Chính sách quyền riêng tư — GPAcc · Tiện ích

*Áp dụng cho tiện ích trình duyệt «GPAcc · Tiện ích» trên Chrome Web Store, Microsoft Edge Add-ons và Firefox. Cập nhật: 18/11/2026.*

Tiện ích chạy trên trình duyệt của bạn. Chứng từ và dữ liệu kế toán chỉ được trao đổi với phần mềm GPAcc chạy trên **cùng máy** (địa chỉ 127.0.0.1), sau khi bạn ghép bằng mã ghép do chính bạn tạo trong GPAcc. Ngoài ra, từ bản 0.55.0, tiện ích liên lạc với **máy chủ bản quyền GPAcc** để dùng thử và kích hoạt — chỉ với các thông tin nêu ở mục «Bản quyền tiện ích» dưới đây.

**Dữ liệu tiện ích đọc.** Tiện ích đọc nội dung trên các trang bạn đã tự đăng nhập (ngân hàng, cổng thuế, hóa đơn điện tử, bảo hiểm xã hội…) **chỉ khi** bạn bấm chức năng tương ứng hoặc đã bật chức năng đó, và chỉ để đưa chứng từ (sao kê, hóa đơn, tờ khai, tệp) vào phần mềm GPAcc trên máy bạn. Các trang ngoài cổng thuế chỉ được đọc sau khi bạn cho phép từng trang.

**Bản quyền tiện ích (từ bản 0.55.0).**
- Khi cài, tiện ích tự tạo một **mã cài đặt** ngẫu nhiên (dạng `TI-XXXX-XXXX-XXXX`). Mã này không lấy từ máy tính, tài khoản hay trình duyệt của bạn.
- Khi bạn **tự bấm** «Dùng thử» hoặc «Xin kích hoạt / Gửi yêu cầu gia hạn», tiện ích gửi tới máy chủ bản quyền GPAcc: mã cài đặt, **tên khách / công ty và số điện thoại bạn tự gõ**, cùng số phiên bản tiện ích. Mục đích: mở dùng thử (mỗi số điện thoại được thử một lần), để GPAcc liên hệ bạn và cấp key kích hoạt.
- Sau đó tiện ích định kỳ hỏi máy chủ trạng thái key của **mã cài đặt** (chỉ gửi mã cài đặt) để tự nhận key khi được duyệt, nhận gia hạn hoặc biết key bị thu hồi.
- Máy chủ bản quyền GPAcc chạy trên dịch vụ Google Apps Script và lưu các thông tin trên trong bảng tính Google Sheets riêng của GPAcc, cùng hệ thống kích hoạt các phần mềm GPAcc khác.
- Quyền kết nối tới máy chủ này chỉ được xin khi bạn bấm lần đầu. Muốn xóa thông tin bản quyền của bạn trên máy chủ: liên hệ GPAcc.

**Những gì tiện ích không làm.**
- Không thu thập mật khẩu; không đăng nhập hộ; không chuyển tiền; không ký hay nộp hồ sơ thay bạn.
- Không gửi nội dung trang, chứng từ hay dữ liệu kế toán cho máy chủ của nhà phát triển hay bất kỳ bên thứ ba nào. Thứ duy nhất gửi về GPAcc là thông tin bản quyền ở mục trên.
- Không bán, không chia sẻ dữ liệu; không dùng dữ liệu để xét tín dụng hay cho vay.
- Không dùng công cụ thống kê, theo dõi hay quảng cáo; không tải mã từ xa.

**Lưu trữ.** Cài đặt, mã ghép, mã cài đặt và key lưu trong bộ nhớ của trình duyệt trên máy bạn; gỡ tiện ích là xóa hết. Chứng từ đưa vào GPAcc nằm trong dữ liệu của phần mềm GPAcc trên máy bạn. Thông tin bản quyền (mã cài đặt, tên, số điện thoại) lưu trên máy chủ bản quyền GPAcc cho tới khi bạn yêu cầu xóa.

**Liên hệ.** Qua địa chỉ email liên hệ hiển thị trên trang của tiện ích ở cửa hàng tiện ích.

---

## Privacy policy — GPAcc · Extension (English summary)

The extension runs in your browser. Documents and accounting data are exchanged only with the GPAcc software running on the **same computer** (127.0.0.1), after you pair it with a code you create in GPAcc. It reads pages you are already signed in to (banks, tax and e-invoice portals, social insurance) only when you trigger a feature or have enabled it, solely to bring your documents into GPAcc on your computer.

**Licensing (from version 0.55.0).** The extension generates a random installation code (`TI-XXXX-XXXX-XXXX`) that is not derived from your computer, account or browser. Only when you click «Try» or «Request activation / renewal», it sends that code, the customer/company name and phone number you type, and the extension version to the GPAcc licensing server (Google Apps Script, stored in GPAcc's own Google Sheets) to start a trial (one per phone number), contact you and issue a license key. It then periodically sends only the installation code to receive the key once approved, renewals or revocation. The network permission for this server is requested on your first click. Contact GPAcc to delete your licensing record.

It does not collect passwords, does not sign in, pay, sign or file on your behalf, sends no page content, documents or accounting data to the developer or any third party (licensing information above is the only data sent to GPAcc), does not sell or share data, does not use data for credit or lending decisions, uses no analytics, tracking, ads or remote code. Settings, pairing code, installation code and key are stored in your browser and removed when you uninstall the extension. Contact: the contact email shown on the extension's store page.
