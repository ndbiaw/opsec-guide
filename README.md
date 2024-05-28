
# opsec-guide

Hướng dẫn thực hành căn bản về bảo mật thông tin cá nhân/danh tính trên không gian mạng.
Lưu ý: dành cho bạn nào thắc mắc, mình đã không thực hiện OPSEC ngay từ đầu đối với tài khoản Github này và các tài khoản mạng xã hội liên quan đến tài khoản Github này vì cơ bản hoạt động ở những tài khoản này không có gì phải che giấu.

# Về việc chia sẻ thông tin trên mạng

## Thông tin tuyệt đối không được chia sẻ

 1. Biệt danh, Họ, Tên Đệm và Tên thật được sử dụng trong cuộc sống hàng ngày / Họ, Tên Đệm và Tên pháp lý
 2. Ngày, tháng, năm sinh
 3. Thông tin về gia đình, bao gồm số thành viên trong gia đình, Biệt danh, Họ, Tên Đệm và Tên được sử dụng trong cuộc sống hàng ngày / Họ, Tên Đệm và Tên pháp lý
 4. Mối quan hệ trong gia đình và xã hội
 5. Địa chỉ nhà, nơi làm việc và địa chỉ trường học
 6. Số nhận dạng, bao gồm số bảo hiểm y tế, số căn cước công dân, số định dạng cá nhân
 7. Những giấy tờ được chính phủ cấp, như hộ chiếu, bằng lái xe, sổ hộ khẩu
 8. Ảnh chụp màn hình đầy đủ của điện thoại hoặc máy tính cá nhân
 9. Cấu hình, mẫu mã của các thiết bị hay sử dụng như đồng hồ, điện thoại, máy tính cá nhân v.v
 10. Ảnh chụp màn hình của bất cứ ứng dụng nào có thể chứa thông tin cá nhân, hoặc ứng dụng được chính phủ phát hành như VNeID, BlueZone v.v
 11. Địa chỉ IP được nhà mạng cung cấp
 12. Thông tin có thể sử dụng để trả lời các câu hỏi bảo mật phổ biến, như tên thành phố được sinh ra, tên thú cưng đầu tiên, tên của giáo viên đầu tiên v.v
 13. Thông tin nhận dạng sinh trắc học như dấu vân tay, khuôn mặt, giọng nói
 14. Những thông tin có thể dùng để nhận dạng cá nhân như dây chuyền, kiểu tóc, hình xăm
 15. Số tài khoản ngân hàng, số tài khoản thẻ tín dụng, ngày hết hạn và mã bảo mật
 16. Biệt danh sử dụng chính trong công việc, giao tiếp, bao gồm tên khác với tên thật
 17. Địa chỉ email chính, số điện thoại chính chủ
 18. Giới tính, chủng tộc, xu hướng tình dục
 19. Mã ZIP, Thành Phố, Quốc gia cư trú
 20. Mật khẩu, tên người dùng thường được sử dụng
 21. Hồ sơ trên các trang mạng xã hội thường được sử dụng

## Quy tắc chia sẻ và sử dụng thông tin trên mạng

 1. Sử dụng ít nhất 3 địa chỉ email khác nhau dành cho các mục đích khác nhau. Ví dụ:
	 - Một địa chỉ email được sử dụng để xác minh các dịch vụ không thiết yếu như trò chơi, giải trí
	 - Một địa chỉ email được sử dụng để đăng kí các dịch vụ thiết yếu như ngân hàng, dịch vụ công
	 - Một địa chỉ email để giao tiếp

	Khuyến nghị như sau:
	 - Sử dụng các dịch vụ email được mã hoá và có mật mã bảo vệ hộp thư riêng sử dụng cho giao tiếp và đăng kí các dịch vụ thiết yếu. Khi sử dụng những dịch vụ email này thì kể cả cơ quan thực thi pháp luật ép buộc giao nộp thông tin thì cũng không thể đọc được những email bên trong. Khuyến nghị sử dụng [ProtonMail](https://mail.proton.me)
	 - Sử dụng tên miền riêng và sử dụng các dịch vụ chuyển tiếp email để đăng kí xác minh các dịch vụ không thiết yếu. Khuyến nghị sử dụng các tên miền cấp một không có máy chủ Whois như **.to**, **.si**, .**al** và sử dụng dịch vụ chuyển tiếp email [CloudFlare Email Routing](https://www.cloudflare.com/products/email-routing/)

 2. Không sử dụng cùng một mật khẩu cho nhiều dịch vụ, không sử dụng các trình quản lý mật khẩu trực tuyến. Khuyến nghị như sau:
	  - Sử dụng các trình tạo mật khẩu ngẫu nhiên, nên sử dụng trình tạo mật khẩu sau: [ấn vào đây](https://geekflare.com/tools/password-generator)
	  - Lưu trữ mật khẩu trong một thiết bị cứng được mã hoá, khuyến nghị các sản phẩm của: [OnlyKey](https://onlykey.io/collections/all)
	  - Lưu trữ mật khẩu trong một tệp được mã hoá. Có thể sử dụng bất kì công cụ mã hoá nào mà bạn coi là an toàn.
 3. Sử dụng xác thực hai lớp cho tất cả các dịch vụ. Không sử dụng ứng dụng xác thực hai lớp có thể sao lưu trực tuyến. Khuyến nghị như sau:
	 - Lưu trữ mã xác thực hai lớp trên các thiết bị cứng được mã hoá, khuyến nghị các sản phẩm của: [Yubico](https://www.yubico.com/products/)
	 - Sử dụng ứng dụng xác thực hai lớp mã nguồn mở và không cần đăng nhập, không thể sao lưu trực tuyến, khuyến nghị sử dụng Google Authenticator, đường dẫn tải xuống: [Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2) / [iOS](https://apps.apple.com/app/google-authenticator/id388497605)
4. Sử dụng các hệ điều hành mã nguồn mở. Ví dụ như Android cho các thiết bị di động và Linux cho các thiết bị máy tính.
5. Không đăng nhập và sử dụng các dịch vụ của các công ty công nghệ lớn như Google, Facebook khi chưa thực hiện các biện pháp cách ly thông tin. Đặc biệt không đăng nhập tài khoản Google nếu sử dụng các thiết bị Android.
6. Sử dụng các ứng dụng VPN để ẩn địa chỉ IP. Lưu ý sử dụng các dịch vụ VPN nhiều người sử dụng để có hiệu quả nhất, nếu không các cơ quan thực thi pháp luật vẫn có thể lần ra địa chỉ IP thực của bạn. Khuyến nghị sử dụng các dịch vụ VPN có thể thanh toán bằng tiền điện tử không thể lần dấu vết như Monero và không cần đăng kí tài khoản như [Mullvad VPN](https://mullvad.net/en/) hoặc [iVPN](https://www.ivpn.net/).
7. Không sử dụng cùng một biệt danh/tên đăng nhập cho nhiều dịch vụ khác nhau.
	- Sử dụng các biệt danh khác nhau cho các loại dịch vụ khác nhau. Ví dụ: biệt danh sử dụng cho trò chơi, biệt danh sử dụng cho mạng xã hội, biệt danh sử dụng cho diễn đàn.
	- Sử dụng các trình tạo chuỗi kí tự ngẫu nhiên, ví dụ như [Random.org String Generator](https://www.random.org/strings/?num=9&len=12&digits=on&upperalpha=on&loweralpha=on&unique=on&format=html&rnd=new)
8. Xoá các dữ liệu có thể nhận dạng trong các tệp có thể chia sẻ, đặc biệt là tệp hình ảnh thường chứa dữ liệu EXIF bao gồm vị trí, tên thiết bị, thời gian chụp. Khuyến nghị sử dụng các chương trình xoá EXIF ngoại tuyến và mã nguồn mở như [EXIF Cleaner](https://github.com/szTheory/exifcleaner/releases)
9. Sử dụng các trình duyệt tập trung vào bảo mật, không sử dụng trình duyệt ở chế độ toàn màn hình. Khuyến nghị sử dụng trình duyệt [FireFox](https://www.mozilla.org/vi/firefox/new/)
10. Không sử dụng viết tắt/từ lóng. Văn phong cũng có thể là thứ để nhận dạng bạn.
11. Sử dụng sim rác và hòm thư thoại để giao tiếp nếu cần. Thiết bị nên được đặt ở một nơi ngẫu nhiên khác với thành phố bạn sinh sống, ví dụ như một cột điện ngẫu nhiên nào đó. Sử dụng các ứng dụng đồng bộ hoá để truy cập thông tin. Hầu hết các nhà mạng đều cung cấp chức năng nạp tiền trực tuyến nên có thể duy trì thiết bị trong một thời gian dài.
