B1: Clone project hoặc giải nén file có sẵn
B2: Vào file appsetting.json -> tìm chuỗi SQLServerIdentityConnection, thay Server= tên server database trên máy
B3: Mở Package Manager Console, gõ lệnh: update-database để tự động tạo database vào máy
B4: Run project lần đầu để seeding data vào database
//Các tài khoản đăng nhập xem trong file SeedData.cs (nằm trong thư mục Models). Trong database không xem được mật khẩu vì đã mã hóa
