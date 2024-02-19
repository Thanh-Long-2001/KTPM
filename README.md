19020353 - Lê Thành Long

1. Khái niệm Docker
   Docker là một nền tảng cho developers và sysadmin để develop, deploy và run application với container. Nó cho phép tạo các môi trường độc lập và tách biệt để khởi chạy và phát triển ứng dụng và môi trường này được gọi là container. Khi cần deploy lên bất kỳ server nào chỉ cần run container của Docker thì application của bạn sẽ được khởi chạy ngay lập tức.
2. Docker Composer
   Docker Composer là công cụ cho phép run app với nhiều Docker containers 1 cách dễ dàng hơn. Docker Compose cho phép bạn config các command trong file docker-compose.yml để sử dụng lại.
   Docker Compose cung cấp khả năng khởi động và dừng các container liên quan đến ứng dụng của bạn với một lệnh đơn giản, giúp tạo ra một môi trường phát triển và triển khai đồng nhất.
3. Unix và Linux
   Unix là một hệ điều hành có nguồn gốc từ giai đoạn đầu của thập kỷ 1970, được phát triển tại Bell Labs của AT&T.
   Linux là một hệ điều hành có nguồn mở được tạo ra bởi Linus Torvalds vào những năm 1991. Linux dựa trên kiến trúc Unix và thường được xem như một phiên bản "Unix-like" hay "Unix-compatible".

Có nhiều phiên bản Unix khác nhau, ví dụ như Solaris của Oracle, AIX của IBM, HP-UX của Hewlett Packard, BSD (Berkeley Software Distribution), v.v.
Linux có nhiều phân phối (distribution) như Ubuntu, Debian, Red Hat, CentOS, Fedora, và nhiều hơn nữa.

Linux là một bản sao của Unix, hoạt động giống như Unix nhưng không chứa mã của nó.
Unix chứa một mã hóa hoàn toàn khác do AT&T Labs phát triển. Trong khi Linux chỉ là hạt nhân và ngược lại, Unix là một gói hệ điều hành hoàn chỉnh .

Linux linh hoạt và miễn phí hơn khi so sánh với các hệ thống Unix thực sự và đó là lý do tại sao Linux trở nên phổ biến hơn.

4. BSD và *nix
   Linux chỉ là một hạt nhân. Bản phân phối Linux phải làm công việc tập hợp tất cả các phần mềm cần thiết để tạo ra một hệ điều hành Linux hoàn chỉnh và kết hợp nó thành một bản phân phối Linux như Ubuntu, Mint, Debian, Fedora, Red Hat, hoặc Arch. Do đó, có rất nhiều bản phân phối Linux khác nhau.
   Ngược lại, BSD là cả một hạt nhân và một hệ điều hành. Ví dụ, FreeBSD cung cấp cả hai hạt nhân FreeBSD và hệ điều hành FreeBSD. Nó duy trì như một dự án duy nhất. Nói cách khác, nếu bạn muốn cài đặt FreeBSD, bạn chỉ cần cài đặt FreeBSD. Nếu bạn muốn cài đặt Linux, bạn sẽ cần phải chọn một trong số các bản phân phối Linux.
   BSDs bao gồm hệ thống port, cung cấp một cách để cài đặt các gói phần mềm. Hệ thống port có chứa phần mềm dưới dạng mã nguồn, vì vậy máy tính của bạn phải biên dịch chúng trước khi chúng sẽ chạy. (Nếu bạn đã từng sử dụng Gentoo khi nó đã được phổ biến, đó là một chút tương tự như thế.) Tuy nhiên, package cũng có thể được cài đặt dưới dạng nhị phân được cài đặt sẵn, do đó bạn không cần phải dành nhiều thời gian và tài nguyên hệ thống để biên dịch chúng.
   BSD và Linux có cơ chế quản lý tiến trình khác nhau. BSD sử dụng hệ thống quản lý tiến trình init, trong khi hầu hết các bản phân phối Linux sử dụng systemd.
   *nix là thuật ngữ đề cập đến một nhóm các hệ điều hành như Linux, BSD
5. MacOS có nguồn gốc từ Unix
6. So sánh Alpine Linux và Ubuntu
   Alpine Linux và Ubuntu là hai bản phân phối hệ điều hành Linux phổ biến, tuy nhiên chúng có một số sự khác biệt quan trọng.

Kích thước hệ thống:
Alpine: Nổi tiếng với kích thước nhỏ và trọng lượng lép, thích hợp cho các container và môi trường có yêu cầu tài nguyên thấp.
Ubuntu: Thường có kích thước lớn hơn so với Alpine do đi kèm với nhiều gói phần mềm và thư viện mặc định.

Hệ thống quản lý gói:
Alpine: Sử dụng apk là Alpine Package Keeper, một hệ thống quản lý gói nhẹ.
Ubuntu: Sử dụng apt (Advanced Package Tool) hoặc dpkg để quản lý gói.

Gói phần mềm và Thư viện:
Alpine: Thường đi kèm với phiên bản nhỏ gọn của các gói phần mềm và thư viện, chủ yếu tập trung vào việc cung cấp các gói cơ bản.
Ubuntu: Cung cấp một loạt rộng lớn các gói phần mềm và thư viện, chủ yếu dành cho các ứng dụng đa nhiệm và môi trường máy tính thông thường.

Bảo mật:
Alpine: Được thiết kế với ưu tiên về bảo mật và có thể tích hợp SELinux hoặc grsecurity.
Ubuntu: Cũng chú trọng đến bảo mật nhưng có thể có kích thước hệ thống lớn hơn và cài đặt mặc định một số dịch vụ.

7. VNC
   VNC là viết tắt của Virtual Network Computing, là một công nghệ cho phép bạn điều khiển và truy cập vào một máy tính từ xa thông qua internet
