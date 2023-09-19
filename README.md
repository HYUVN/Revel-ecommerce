--Name: Revel-ecommerce
	+Member: Phạm Quang Huy(leader)
		 Nguyễn Khôi Nguyên
		 Hoàng Hữu Huy
	+Time: 20/08/2023 - 30/09/2023
	+Teacher: Nguyễn Trung Kiên
--Setup:

1 .Import Project in Eclipse or Spring Tool (Visual Studio Code) or intelij IDEA

2. Setup Mysql workbench -> Open foder Documentation , run the script file sql.

3. Configure username & password Mysql in file :

Client: ..\Java Web\E-MultiVendor\E-WebParent\E-Client\src\main\resources\application.yml

Admin: ..\Java Web\E-MultiVendor\E-WebParent\E-Admin\src\main\resources\application.properties

4. Run Project

No.	URL / IP	User	Password
1. Admin	http://localhost:8080/Admin/	admin@gmail.com - pass: 12345678	12345678
2. Client	http://localhost:80/Client/	all tài khoản trong admin	all pass: 12345678

--Project

 Website Ecommerce MultiVendor

R= Đã hoàn thiện khoảng 90% trở lên
 C= Hoàn thiện khoảng 50% trở về

- Công nghệ sử dụng: 
 Java, Spring Boot, Hibernate, Thymeleaf, Bootstrap, jQuery, HTML, RESTful Webservices...
 Mô tả chi tiết: 
- Frontend:
 + Trang chủ: Hiển thị top sản phẩm mới nhất, sản phẩm best seller, sản phẩm flashsale, Hiển thị sản phẩm theo branch, category (R)
 + Hiện thị danh mục sản phẩm, phân trang số lượng sản phẩm. (R)
 + Hiện thị thông tin theo sản phẩm theo shop, category, brands. (R)
 + Chi tiết sản phẩm, đặt hàng (R)
 + Xem thông tin sản phẩm (R)
 + Xem toàn bộ sản phẩm, tìm kiếm theo keyword (R)
 + Đăng nhập bằng Google, Facebook, Remember Me, Cập nhật -  Đăng kí - Đăng xuất tài khoản - kích hoạt tài khoản qua email. (R [gg,fb,rm m (c)])
 + Cho phép người dùng đăng kí tài khoản -> tạo shop -> tạo sản phẩm đăng bán. (R)
 + Quản lí shop - thêm - xóa - sửa shop và sản phẩm (R)
 + Xem lịch sử đơn hàng, thanh toán bằng COD - Paypal - Credit Card. (C [COD (R)])
 + Chức năng đổi trả đơn hàng - đánh giá sản phẩm , vote ,... (R [Vote (C)])
Admin:
 + Hiển thi dashboard (R)
 + Xuất file excel, CSV, PDF (C [1 số CSV = Excel])
  + Chức năng thêm - xóa - sửa - tìm kiếm - phân trang (R)
 + Admin application for managing users, categories, brands, products, customers, orders, shops, sales report...(R)

--Technology:
	+Front-end: HTML, CSS, Javascipt, jQuery, Bootstrap (R)
	+Back-end: Java (R)
	+Database: MySql (R)
	+FrameWork: Spring + Thymeleaf (R)
	+Support: Docker, Amazon Web Services (C)

-- Yêu cầu ngoại lệ:
+ Excel [tổng hợp thông tin admin user database security fe-be form](R)
+ Word [báo cáo đồ án] (C)
+ Powerpoint [thuyết trình bảo vệ đồ án] (R)
+ DataBase (R)
+ Báo cáo tiến độ [word] (C)
+ Up hosting & có DNS trỏ tên miền về host (Chưa làm)

--Đánh giá tổng:
Hoàn thiện 72%
chưa làm được:
	+ xem thông tin shop
	+ xuất đúng file
	+ thanh toán paypal credit Card
	+ login witch google facebook 
	+ API call data to web
	+ Giao diện đẹp
