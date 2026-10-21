# Cấp đổi chứng nhận đăng ký xe — dựng theo video gốc

Video nguồn: https://github.com/minhviminhvi95-sketch/Tr-L-AI/releases/download/V1.0.0/IMG_8179.MP4
Nguồn dài 265,9 giây, 384×848. Bản dựng chia theo thao tác và mô phỏng lại giao diện bằng nét vẽ để dễ đọc; không phải bản sao giao diện chính thức. Không đưa dữ liệu định danh, mật khẩu, OTP, số điện thoại, email, biển số, số khung, số máy thật vào bản dựng.
Không phát hành lại video gốc hoặc ảnh chụp gốc trong gói đầu ra vì có dữ liệu cá nhân và mã xác thực. Có bảng mốc cắt nguồn và MP4 riêng từng cảnh để chỉnh sửa.

## Điểm đã kiểm tra từ video

- Ví dụ: cấp đổi chứng nhận đăng ký xe vì thay đổi màu sơn. Không phải đăng ký xe lần đầu hoặc cấp lại do bị mất.
- Cuối nguồn có lỗi tải trang đồng thời thông báo SMS nói đăng ký hồ sơ thành công. Đây là thông báo về việc nộp/đăng ký hồ sơ, không phải kết luận đã cấp đổi xong. Bản dựng hướng dẫn lưu mã và tra cứu trước khi nộp lại.
- Không coi bảng lệ phí 0 trong nguồn là miễn phí mọi trường hợp. Không suy ra đã hoàn tất giấy tờ chỉ vì nguồn cuộn nhanh qua thành phần hồ sơ.
- Trường hợp thay đổi màu sơn có yêu cầu đưa xe đến kiểm tra theo quy định; không trình bày cấp đổi này là mọi khâu đều thực hiện tại nhà.
- Giữ trình tự thao tác của nguồn. Tên dịch vụ, thẩm quyền và yêu cầu thực tế phải theo phiên bản dịch vụ hiện hành; không khẳng định giao diện nguồn là giao diện mới nhất.

## Nguồn đối chiếu ngày 21/10/2026

- [Video gốc do người dùng cung cấp, dài 265,9 giây](https://github.com/minhviminhvi95-sketch/Tr-L-AI/releases/download/V1.0.0/IMG_8179.MP4)
- [Bộ Công an: yêu cầu kiểm tra thực tế xe khi đổi đăng ký do thay đổi màu sơn](https://bocongan.gov.vn/bai-viet/quy-dinh-ve-cap-thu-hoi-chung-nhan-dang-ky-xe-bien-so-xe-co-gioi-xe-may-chuyen-dung-d1-t1591)
- [Cổng DVC Bộ Công an: hướng dẫn cấp đổi, ngoại lệ kiểm tra xe cải tạo và thay đổi màu sơn](https://dichvucong.bocongan.gov.vn/public/link-to/chi-tiet-thu-tuc?ma-thu-tuc=64209)
- [Quyết định 4685/QĐ-BCA-C08 ngày 23/7/2026: thủ tục đăng ký xe thống nhất, tránh dùng cứng tên dịch vụ cũ](https://congan.khanhhoa.gov.vn/FileStorage/images/phapche/Q%C4%90%20TTHC/4685-Q%C4%90-BCA.pdf)

## Phân cảnh và lời đọc

### 01. CẤP ĐỔI CHỨNG NHẬN ĐĂNG KÝ XE — 24.00 giây
Mốc nguồn: [0, 23].

Video này hướng dẫn theo các thao tác trong bản quay màn hình bạn cung cấp: cấp đổi chứng nhận đăng ký xe, với ví dụ thay đổi màu sơn.
Đầu tiên, mở trình duyệt và truy cập đúng cổng dịch vụ công. Kiểm tra tên miền trước khi đăng nhập.
Các màn hình trong bản vẽ tay đã được dựng lại để dễ đọc. Thông tin cá nhân, mật khẩu và mã xác thực thật không được hiển thị.

### 02. 01 / ĐĂNG NHẬP VÀ XÁC THỰC — 25.46 giây
Mốc nguồn: [23, 71].

Tại trang đăng nhập, chọn phương thức tài khoản định danh điện tử phù hợp, như thao tác đăng nhập qua VNeID trong video.
Nhập thông tin tài khoản của chính bạn, rồi thực hiện bước xác thực mà hệ thống yêu cầu. Không dùng các giá trị xuất hiện trong video làm dữ liệu mẫu.
Sau khi xác thực thành công, chờ hệ thống đưa trở lại cổng dịch vụ công. Không chia sẻ mật khẩu hoặc mã xác thực cho người khác.

### 03. 02 / MỞ MỤC NỘP HỒ SƠ — 18.75 giây
Mốc nguồn: [71, 82].

Sau khi đăng nhập, mở menu điều hướng của cổng dịch vụ công.
Chọn mục nộp hồ sơ trực tuyến. Màn hình chuyển sang phần tìm kiếm và lựa chọn thủ tục.
Trong video, người thực hiện dùng lĩnh vực đăng ký, quản lý phương tiện để tìm thủ tục về đăng ký xe.

### 04. 03 / CHỌN ĐÚNG THỦ TỤC CẤP ĐỔI — 20.92 giây
Mốc nguồn: [82, 103].

Tìm mục cấp đổi chứng nhận đăng ký xe theo danh sách dịch vụ đang hiển thị.
Phân biệt cấp đổi với cấp lại do bị mất, và với đăng ký xe lần đầu. Chọn đúng nội dung phù hợp hồ sơ của bạn.
Tên hoặc vị trí của dịch vụ có thể thay đổi theo thời điểm. Đọc mô tả và yêu cầu hiện hành trước khi tiếp tục.

### 05. 04 / CHỌN LOẠI XE VÀ NƠI GIẢI QUYẾT — 22.29 giây
Mốc nguồn: [103, 125].

Ở phần chọn trường hợp hồ sơ, chọn loại xe. Bản quay minh họa lựa chọn xe máy.
Tiếp theo, chọn tỉnh, thành phố và phường, xã hoặc cơ quan giải quyết mà dịch vụ yêu cầu. Chọn theo nơi và thẩm quyền phù hợp hồ sơ thực tế.
Kiểm tra lựa chọn và thông tin thời hạn đang hiển thị. Sau đó bấm đồng ý và tiếp tục.

### 06. 05 / XÁC ĐỊNH NGƯỜI NỘP HỒ SƠ — 20.96 giây
Mốc nguồn: [125, 134].

Tại màn hình kê khai, xác định người đang nộp hồ sơ là chủ xe hay người khai hộ.
Trong video, ô người nộp hồ sơ là chủ xe được chọn. Bạn chỉ chọn mục này khi đúng với trường hợp của mình.
Nếu thực hiện thay người khác, chọn đúng vai trò và chuẩn bị thông tin, giấy tờ theo yêu cầu của dịch vụ.

### 07. 06 / CHỌN NỘI DUNG VÀ LÝ DO CẤP ĐỔI — 23.17 giây
Mốc nguồn: [134, 150].

Tại phần tra cứu thông tin xe, chọn nội dung đăng ký cần đổi và lý do tương ứng.
Bản quay chọn đổi lại đăng ký xe, với lý do thay đổi màu sơn. Đây là ví dụ cụ thể, không phải lựa chọn chung cho mọi hồ sơ.
Nếu nhu cầu của bạn khác, chọn đúng lý do thực tế. Không chọn thay đổi màu sơn chỉ vì video minh họa mục này.

### 08. 07 / TRA CỨU THÔNG TIN PHƯƠNG TIỆN — 23.25 giây
Mốc nguồn: [150, 185].

Nhập biển số, số khung và các trường mà hệ thống yêu cầu. Đối chiếu trực tiếp với chứng nhận đăng ký và giấy tờ hợp lệ của xe.
Chọn màu biển phù hợp. Nhập mã bảo mật đang hiển thị trên màn hình, rồi bấm tra cứu.
Kiểm tra thông tin trả về và số máy nếu được yêu cầu. Không dùng số khung, số máy hoặc mã bảo mật trong video của người khác.

### 09. 08 / KIỂM TRA THÔNG TIN CHỦ XE — 22.54 giây
Mốc nguồn: [185, 198].

Cuộn tới phần chủ xe tự kê khai và kiểm tra dữ liệu định danh, giấy tờ, địa chỉ cùng các thông tin liên quan.
Kiểm tra số điện thoại và email để nhận được thông báo xử lý hồ sơ.
Chỉ kê khai các phần đại diện, ủy quyền hoặc giấy tờ khác khi đúng trường hợp và theo hướng dẫn. Không tự điền dữ liệu không có căn cứ.

### 10. 09 / CHỌN CÁCH NHẬN KẾT QUẢ — 23.88 giây
Mốc nguồn: [198, 205].

Ở trường hình thức nhận kết quả, mở danh sách các phương án mà dịch vụ hỗ trợ.
Chọn nhận tại cơ quan giải quyết hoặc qua dịch vụ bưu chính nếu phù hợp. Bản quay có thao tác mở danh sách này để lựa chọn.
Nếu nhận qua bưu chính, kiểm tra người nhận, số điện thoại và địa chỉ. Thực hiện các yêu cầu về giấy tờ gốc theo hướng dẫn của cơ quan tiếp nhận.

### 11. 10 / BỔ SUNG THÀNH PHẦN HỒ SƠ — 23.25 giây
Mốc nguồn: [205, 215].

Tại màn hình thành phần hồ sơ, đọc danh mục giấy tờ được yêu cầu cho trường hợp của mình.
Dùng nút chọn tệp để tải tài liệu vào đúng mục. Bảo đảm bản chụp hoặc bản quét rõ nội dung, đủ trang và đúng định dạng được chấp nhận.
Không bỏ qua giấy tờ bắt buộc chỉ vì bản quay cuộn nhanh qua mục này. Kiểm tra các tệp rồi bấm đồng ý và tiếp tục.

### 12. 11 / RÀ SOÁT TOÀN BỘ HỒ SƠ — 23.71 giây
Mốc nguồn: [215, 232].

Ở màn hình tổng hợp, đọc lại thông tin phương tiện và chủ xe một lần nữa.
Kiểm tra lý do cấp đổi, giấy tờ đính kèm và phương án nhận kết quả. Sửa các điểm sai trước khi gửi hồ sơ.
Nếu hệ thống hiển thị thông tin phí, lệ phí, đọc đúng thông báo của hồ sơ mình. Một con số trong bản quay không có nghĩa mọi trường hợp đều được miễn phí.

### 13. 12 / KIỂM TRA ĐỊA CHỈ NHẬN — 20.58 giây
Mốc nguồn: [232, 244].

Nếu hồ sơ yêu cầu khai nơi nhận kết quả, kiểm tra tên và số điện thoại của người nhận.
Chọn tỉnh, thành phố, phường, xã và nhập địa chỉ chi tiết theo biểu mẫu.
Nếu bạn chọn đến cơ quan nhận trực tiếp, thực hiện theo những trường tương ứng. Không tự sao chép địa chỉ của người quay video.

### 14. 13 / NHẬP MÃ VÀ ĐỌC CAM KẾT — 20.79 giây
Mốc nguồn: [244, 256].

Nhập mã xác nhận đang xuất hiện trên trang. Mã có thể thay đổi khi tải lại hoặc đổi mã, vì vậy không chép mã trong video.
Nếu khó đọc, dùng chức năng đổi mã rồi nhập lại cẩn thận.
Đọc nội dung cam kết về tính chính xác của thông tin. Chỉ tích xác nhận sau khi đã rà soát hồ sơ.

### 15. 14 / BẤM NỘP HỒ SƠ — 19.58 giây
Mốc nguồn: [256, 259].

Sau khi kiểm tra thông tin, mã xác nhận và cam kết, bấm nút nộp hồ sơ.
Chờ hệ thống phản hồi. Tránh bấm liên tục hoặc tự gửi lại nhiều lần khi trang đang xử lý.
Lưu thông báo và mã hồ sơ khi được cung cấp. Mã này dùng để theo dõi tình trạng giải quyết.

### 16. 15 / ĐỌC ĐÚNG KẾT QUẢ CUỐI VIDEO — 26.92 giây
Mốc nguồn: [259, 265.9].

Ở cuối video gốc, trình duyệt hiển thị lỗi tải trang. Đồng thời, một tin nhắn từ cổng dịch vụ công thông báo đăng ký hồ sơ thành công.
Vì vậy, không thể kết luận chỉ từ màn hình lỗi rằng hồ sơ chưa được gửi. Hãy lưu mã trong thông báo và tra cứu trạng thái.
Thông báo đăng ký hồ sơ thành công chưa phải là chứng nhận đăng ký xe đã được cấp đổi. Theo dõi yêu cầu bổ sung hoặc liên hệ nơi tiếp nhận trước khi nộp lại.

### 17. SAU KHI NỘP / THEO DÕI VÀ HOÀN TẤT — 27.96 giây
Mốc nguồn: Ghi chú bổ sung đối chiếu quy định.

Sau khi gửi, theo dõi trạng thái và thực hiện yêu cầu bổ sung của cơ quan giải quyết nếu có.
Với trường hợp đổi chứng nhận đăng ký do thay đổi màu sơn như ví dụ, còn có yêu cầu đưa xe đến cơ quan đăng ký để kiểm tra theo quy định. Nộp trực tuyến không đồng nghĩa đã hoàn tất mọi bước.
Nhận kết quả theo hướng dẫn và hình thức đã lựa chọn. Video này minh họa thao tác từ bản quay, không thay thế việc kiểm tra yêu cầu của dịch vụ hiện hành.

## Kỹ thuật và ghi công

Tranh giao diện được vẽ lại theo video người dùng cung cấp, dữ liệu minh họa; không có logo cơ quan nhà nước. Hiệu ứng nét liên tục dùng srt-whiteboard-animation của geeklee (MIT). Giọng đọc tổng hợp Piper vi_VN-vais1000-medium qua sherpa-onnx; VAIS-1000 Vietnamese Speech Synthesis Corpus, CC BY 4.0 theo MODEL_CARD. Bàn tay minh họa không có thương hiệu.
Giọng đọc tốc độ 0,91; nghỉ giữa đoạn 0,7 giây; giữ hình ít nhất 4,5 giây sau lời đọc cuối mỗi cảnh. Phụ đề chia theo đoạn lời đọc, không phải karaoke từng từ.
Mô hình: https://github.com/k2-fsa/sherpa-onnx/releases/download/tts-models/vits-piper-vi_VN-vais1000-medium.tar.bz2
Dữ liệu: https://ieee-dataport.org/documents/vais-1000-vietnamese-speech-synthesis-corpus
Giấy phép: https://creativecommons.org/licenses/by/4.0/
