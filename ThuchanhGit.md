# Bài tập thực hành Git
## Tổng quan về Git
### Các khái niệm quan trọng trong Git
+ Repository: Là nơi chứa mã nguồn (repository có nghĩa là "kho chứa"), tức là nơi mà chúng ta lưu trữ các file, các đoạn mã được viết ra trong suốt quá trình phát triển dự án. Có 2 loại Repository là Local Repository và Remote Repository.
+ Local Repository: Là nơi lưu trữ mã nguồn trên máy tính của lập trình viên. Chẳng hạn Bob và James mỗi người đều có các Local Repository trên máy của riêng mình. Các đoạn mã do Bob hoặc James viết ra đều được lưu trữ trên các Local Repository đó.
+ Remote Repository: Là nơi lưu trữ mã nguồn ở trên mạng (chẳng hạn là mạng Internet hay là mạng nội bộ của một công ty). Để có Remote Repository thì chúng ta cần có một máy chủ và cài Git Server lên đó. Hoặc chúng ta có thể sử dụng các dịch vụ miễn phí (chẳng hạn như GitHub.com, GitLab.com...). Remote Repository (có nghĩa là "kho chứa từ xa") là nơi mà cả Bob và James đều có thể truy cập được để tải mã nguồn về hoặc đưa mã nguồn lên đó.
+ Version (Phiên bản): Là trạng thái mã nguồn ở một thời điểm nhất định nào đó. Chẳng hạn, sáng hôm nay Bob hoàn thành xong tính năng Đăng nhập của website, Bob quyết định đánh dấu rằng đây là một phiên bản của mã nguồn. Đến buổi trưa, James hoàn thành tính năng Cài đặt lại mật khẩu, James lại quyết định đánh dấu rằng đây là một phiên bản nữa của mã nguồn. Như vậy, có thể thấy rằng trong quá trình phát triển một dự án thì mã nguồn sẽ có rất nhiều phiên bản được tạo ra liên tiếp nhau. Đến buổi chiều, chẳng may Bob lỡ tay xoá mất mấy đoạn mã quan trọng. Nhưng Bob không hề lo lắng, bởi vì Bob có thể "quay trở về" phiên bản trước đó của mã nguồn một cách dễ dàng. Đó là một trong rất nhiều những lợi ích của việc quản lý phiên bản mã nguồn.
+ Quản lý Phiên bản mã nguồn: Git không chỉ giúp chúng ta quản lý mã nguồn mà còn quản lý phiên bản mã nguồn. Tức là giúp chúng ta làm chủ được từng thay đổi của mã nguồn theo thời gian.
+ Đồng bộ giữa các Repository: Ngoài Repository chung (chính là Remote Repository) thì Bob và James đều có các Repository riêng của mình (chính là Local Repository), do đó phải có cơ chế để đồng bộ giữa các Repository này với nhau, tức là giữ cho mã nguồn ở các Repository này giống hệt nhau. Hay nói cách khác, tất cả các Repository này là những bản sao của nhau.
+ Snapshot: Là toàn bộ mã nguồn tại một thời điểm
+ CodeGym Huế
=======
+ day la dong 11 sua doi
