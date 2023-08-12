
### Set up :

1. Phải chắc chắn rằng phiên bản php của bạn là 8.1 trở lên. Nếu không thì phải xóa đi và cải lại bản XAMPP mới nhất. Link: https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/8.1.17/ . Lưu ý cực kì quan trọng : trước khi xóa XAMPP, phải copy lại hết thư mục mysql trữ ở 1 thư mục khác để tránh mất dữ liệu. Sau khi cài đặt xong có thể copy thư mục vào. Thư mục mysql sẽ nằm ở thư mục xampp. Ví dụ: C:\xampp\mysql
2. Chạy lệnh ```composer update``` và ```composer install``` để cài đặt các thư viện cần thiết.
3. Chạy lệnh ```cp .env.example .env``` để copy ```.env.example``` cho ``.env``
4. Chạy lệnh ```php artisan key:generate```
5. Chỉnh sửa file ```.env``` , thay đổi DB_DATABASE thành tên database của bạn
6. Import file database ```shop.sql``` (đã gửi vào nhóm) lên database của bạn
8. ```npm install```
9. Trong thư mục có 1 file zip có tên storage, xóa folder storage cũ rồi giải nén storage mới.
10. Chạy lệnh [laravel file manager]:-  ```php artisan storage:link```
10. ```php artisan serve```
12. Admin Email/Password: ```admin@gmail.com```/```1111```. User Email/Password: ```user@gmail.com```/```1111```





