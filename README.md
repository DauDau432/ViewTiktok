***cấu hình***
=========================================================================

`use-proxy:`

Giá trị: false (hiện tại proxy không được bật).

Mục đích: Cho phép bật/tắt việc sử dụng proxy trong chương trình. Nếu được đặt thành true, chương trình sẽ sử dụng proxy từ tệp proxies.txt.


`proxy-type:`

Giá trị: "http".

Mục đích: Chỉ định loại proxy được sử dụng (trong trường hợp này là HTTP proxy).


`auth:`

Giá trị: false.

Mục đích: Cho biết proxy có yêu cầu thông tin xác thực (username/password) hay không.


`credential:`

Giá trị: "" (chuỗi rỗng).

Mục đích: Nếu auth được bật (giá trị true), trường này sẽ lưu thông tin xác thực của proxy (ví dụ: username:password).


`proxyscrape:`

Giá trị: false.

Mục đích: Cho biết proxy có tự động thu thập từ ProxyScrape) hay không
